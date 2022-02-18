# Variational Bayesian GAN for Mixtures-of-Gaussian
To test the ability to infer a multi-modal posterior which helps avoiding the mode collapse, an instance of over-fitting in regular GAN training. We generate 2-dimensional synthetic data by mixtures of 8 Gaussian distribution scattered equality on circumference. We run the synthetic data on our proposed, vanilla GAN and Bayesian GAN, showing 100 samples from the models every 10000 iterations and find out that our proposed and Bayesian GAN are more powerful to capture the modes of mixtures of Gaussian avoiding the mode collapse.

Bayesian GAN credit to https://github.com/vasiloglou/mltrain-nips-2017/blob/master/ben_athiwaratkun/pytorch-bayesgan/Bayesian%20GAN%20in%20PyTorch.ipynb

* Our Model Architecture

<p align="center">
  <img src="figures/Model_slide.PNG" width="450">
  <em>VBGAN</em>
</p>
<p align="center">
  <img src="figures/Model_slide_w.PNG" width="450">
  <em>VBGAN with wasserstein metric</em>
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
 <figcaption> vanilla GAN (left) and our proposed (right) </figcaption> 


                                  	   







