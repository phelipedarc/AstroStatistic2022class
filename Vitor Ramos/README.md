# Modelagem de Lentes Gravitacionais com Normalizing Flows

Arquivos do trabalho final da disciplina Métodos em Grande Volume de Dados e Astroinformática, do professor Clécio Roque de Bom no Centro Brasileiro de Pesquisas Físicas, ministrada no semestre de 2022/2.

![image](https://user-images.githubusercontent.com/43800987/207366836-d2b2e010-2a0f-4138-92f1-5b9f2666276b.png)

## Resumo

**Introduction:**
Strong Gravitational Lensing is a phenomenon in which the deformation of spacetime by massive objects (such as galaxies or galaxy clusters) causes the incoming light from more distant galaxies to be deflected, leading to the appearance of multiple images of the distant source. This effect can be used to study dark matter distribution in galaxies, estimate the expansion rate of the universe (the Hubble constant) and even aid the study of very distant galaxies, along with many other applications in astrophysics and cosmology. With upcoming surveys in the next decade expected to greatly increase the number of known Strong Lensing systems, the ability to model this phenomenon accurately and fast can prove an invaluable asset in physics.

**Goal:**
The goal of this work is to create a deep learning model capable of inferring a set of lensing parameters from images of Strong Lensing systems. 

**What I’m going to do:**
The first step to this process is obtaining a dataset of simulated images with known parameters. As for the deep learning model, a method known as Normalizing Flows can be used. This technique relies on reversible transformations to approximate a complex probability distribution given a base distribution. Thus, given a certain image, the model is able to infer the probability distributions of Strong Lensing parameters, allowing for uncertainty estimation. 
