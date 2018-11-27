# Variational Bayesian GAN for Mixtures-of-Gaussian
To test the ability to infer a multi-modal posterior which helps avoiding the mode collapse, an instance of over-fitting in regular GAN training. We generate 2-dimensional synthetic data by mixtures of 8 Gaussian distribution scattered equality on circumference. We run the synthetic data on our proposed, vanilla GAN and Bayesian GAN, showing 100 samples from the models every 10000 iterations and find out that our proposed and Bayesian GAN are more powerful to capture the modes of mixtures of Gaussian avoiding the mode collapse.


<p align="center">
  <img src="figures/Model_slide.PNG" width="450">
  <img src="figures/Model_slide_w.PNG" width="450">
</p>

## Setting
- Framework:
    - Pytorch 0.4.0
- Hardware:
	- CPU: Intel Core i7-2600 @3.40 GHz
	- RAM: 20 GB DDR4-2400
	- GPU: GeForce GTX 980

## Result of Vanilla GAN and VBGAN
 <img src="figures/gan/Iteration_10000.png" width="400">  <img src="figures/vbgan/Iteration_10000.png" width="400"> 

 <img src="figures/gan/Iteration_20000.png" width="400/">  <img src="figures/vbgan/Iteration_20000.png" width="400/"> 

 <img src="figures/gan/Iteration_30000.png" width="400">  <img src="figures/vbgan/Iteration_30000.png" width="400"> 
                                  	   







