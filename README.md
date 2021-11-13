# MCCDataGeneration
- This repository is used to generate the training data for our upcoming physics-constrained neural network training.
- The code is based on the modified Cam-Clay model.

## Yield function
<img src="doc/Equation/yieldfunc.gif" alt="" height="50" title="">

## Initial volum 
<img src="doc/Equation/InitialVolum.gif" alt="" height="50" title="">

## Elastic modulus
<img src="doc/Equation/elasticModulus.gif" alt="" height="120" title="">

## Gaussian process
- kernel function
<img src="doc/Equation/kernelFunction.gif" alt="" height="50" title="">

- Gaussian function
<img src="doc/Equation/gaussianFunction.gif" alt="" height="50" title="">

- Covariance Matrix
<img src="figSav/curlCoefComparation/CovariabceHeatMap_curl2.png" alt="" height="150" title="">

- Gaussian random loading path
<img src="figSav/curlCoefComparation/ConfiningPressureGP_curl2.png" alt="" height="150" title="">
<img src="MCCData/animation/deformation_0.gif" alt="" height="200" title="">

<p float="left">
  <img src="figSav/curlCoefComparation/ConfiningPressureGP_curl2.png" height="150" />
  <img src="MCCData/animation/deformation_0.gif" height="150" /> 
</p>

Gaussian random loading path          |  Deformation of the configuration
:-------------------------:|:------------------------------------:
![](figSav/curlCoefComparation/ConfiningPressureGP_curl2.png){:height="700px" width="400px"}  |  ![](MCCData/animation/deformation_0.gif){:height="700px" width="400px"}

![](figSav/curlCoefComparation/ConfiningPressureGP_curl2.png)  ![](MCCData/animation/deformation_0.gif)
## Results of the simulation
Assuming that the loading will end up in the critical state.
<img src="figSav/MCCmodel-1.png" alt="MCC loading display" height="200" title="MCC loading display">
<img src="figSav/MCCmodel-2.png" alt="MCC loading display" height="200" title="MCC loading display">

## Size of the yield surface controlled by the hardening variable in the yield function
<img src="figSav/YieldSurface.svg" alt="MCC loading display" height="200" title="MCC loading display">
