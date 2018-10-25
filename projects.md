---
layout: page
title: Projects
permalink: /projects
---
<link rel="stylesheet" href="/style.css" type="text/css" media="all" ></link>

## Reasearch projects

### 1. Structure-Property linkages using Machine Learning
Process-Structure-Property relationship is the crux of materials engineering. To design a material to try to meet a user's need. Based on the user's need we decide upon what properties the material should have (it can be strength, toughness, hydrogen resistance etc.) and then we try to figure  out which structure leads to the desired properties. The structure of the material is tuned by the processing technique used to manufacture the material. This is the inductive or the Goal/Means approach. The other way round is deductive or the Cause/Effect approach where we have a processing technique which decides the structure and that particular structure gives some properties and we try to find some applications for that material with those properties. Below is a schematic

<p align="center">

<img src="/PSPP.jpg" width="50%">

</p>


In this project I have particularly focused on structure and property linkages. The ultimate goal of the project is to be able to construct the yield surface of a material by generating yield loci using robust machine learning models under different loading conditions. Before going to advanced analytical models like the Barlat YLD 2004-18p model I have attempted to replace relatively simpler crystal plasticity model called the nonlocal crystal plasticity model as given by [Anxin Ma and Alexander Hartmaier]. The output of the project would lead to a tool which can obviate the need to carry out time consuming and computationally expensive crystal plasticity finite element simulations. The motivation behind using machine learning algorithms comes because of the following reasons:
<p align="left">
1. Only requires an initial investment of computational resources to train the model and once it is trained it is ready to be deployed and used
2. Takes very less time to use it and is cost effective
3. Machine learning models are very good at generalization and carefuly trained models also work well on new 'unseen' data points
</p>
The below flow chart summarizes the steps involved in the project:

<p align="center">
<img src="/flow_chart.jpg" width="70%" height="70%">
</p>

The project involves generation of training data to performing feature engineering and final development of machine learning pipeline to efficiently predict microstructural information from flow curve of the material.

### 2. Internship at Indian Institute of Sciences, Bengaluru



### 3. Hot cracking susceptibility of Ni-based superalloys during laser based additive manufacturing

A multi-scale approach for formualted to predict the cracking susceptibilty of Ni-based superalloys. A macro-sclae model was used to model the heat flow which predicted the cooling rates, gradients of temperature in in the domain. This was then fed into a phase field model to predict the morphological evolution of the microstructre in the soldiifaction front.  The shape of the dendrites was used to claculate the cracking susceptibilty. All the simulaions were carried out using in-house codes.


### 5. Study of grain growth characteristics in spark plama sintered MgO

The goal was to model the growth charecteristics of MgO as a function of the processing parameters. Through this we were able to deduce the effect of electric current, pressure, temperature on the growth of nano MgO powders. I performed ball milling to achieve nano powders for used XRD,  optical and scanning electron microscopy to charecterise the samples before and after sintering.  


## Course projects

### 1. Effect of an inhomogenity on a dislocation

The dynamics of dislocations determines the plasticity of a material. Though there are various reasons for the movement dislocations to get hindered, presence of inhomogeneity plays a very significant role. The presence of inhomogeneity can significantly hinder the dislocations thus strengthening the material. This is the mechanism by which many alloys, including Al-Cu alloys, acquire its strength. Thus, understanding the effect of inhomogeneities on dislocation would enable us to predict the mechanical response of many industrially relevant alloy systems. To understand how inhomogeneities in the matrix affect the dislocation motion, we tried to determine the force acting on the dislocation for a given strain boundary condition and compare it with the case where the material is homogeneous.


### 2. Calculation of Interfacial energies for θ′ precipitates in Al-Cu matrix

We presented a study to model the interface energies of precipitates growing in a mtrix. We implemented DFT techniques to calculate the bulk energies of Al-Cu matrix, θ′ precipitates , inerface energicies of the matrix and θ′ precipitates and the energy due to the coherency strain associated with the interface. We tried to calculate all the parameters that are required by models like phase field methods to understand the microstructure evolution thus enabling a multiscale approach to solve engineering problems.

Normal Text

<p align="center">
  <b>Some Links:</b><br>
  <a href="#">Link 1</a> |
  <a href="#">Link 2</a> |
  <a href="#">Link 3</a>
  <br><br>
  <img src="http://s.4cdn.org/image/title/105.gif">
</p>

Normal text


[Anxin Ma and Alexander Hartmaier]: https://doi.org/10.1080/14786435.2013.847290
