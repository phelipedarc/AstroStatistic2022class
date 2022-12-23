# Classifier-Transient_search_RandomForest

<img src="https://farm66.staticflickr.com/65535/49055715328_092031af74_o.png"  width="150" />



Este trabalho é apresentado um tutorial de como usar um **Random Forest Classifier** para separar transientes astrofísicos de artefatos. 
Transientes são objetos astronômicos com luminosidade variável, como supernovas, kilonovas, entre outros. 
Identificar esses transientes no céu é historicamente feito por astrônomos treinados utilizando inspeção visual, facilitada pelo uso de algoritmos de diferenciação de imagem. 
Esses algoritmos subtraem de uma imagem contendo um candidato a transiente (search) uma imagem capturada anteriormente (template), 
procurando por locais de concentração de fluxo que poderiam indicar a presença de um transiente. Um dos problemas mais comuns desse método é o chamado Bad-Subtraction, 
que ocorre quando o 'search' e 'template' estão desalinhados, gerando artefatos que podem ser confundidos com transientes (falsos positivos). 
Para corrigir esse problema, usa-se um algorítimo de machine learning (Random Forest).


This code was developed by Phelipe Darc.
(21/11/2022)
