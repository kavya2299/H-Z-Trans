# H-Z-Trans
A project based on adversarial networks.
We want to take an image from an input domain  Di  and then transform it into an image of target domain  Dt  
without necessarily having a one-to-one mapping between images from input to target domain in the training set. 
One-to-one mapping makes this formulation quite powerful - the same method could be used to tackle a variety of problems
by varying the input-output domain pairs - performing artistic style transfer, adding bokeh effect to phone camera photos, 
creating outline maps from satellite images or convert horses to zebras and vice versa.
This is achieved by a type of generative model, specifically a Generative Adversarial Network dubbed CycleGAN by the authors of the paper 
by Jun-Yan Zhu, Taesung Park, and Tongzhou Wang. 

I have gone through their paper here and have made note of important points and have used their algorithm, 
which is subject to changes in the future.
