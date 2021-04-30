# 11685_HW5
HW5 from 11685 course, GAN/VAEs implementation with GANs

Drive project repo: https://drive.google.com/drive/folders/1KpDmxM7pHKPXjjZBLHwq6pcKIAK4I06n?usp=sharing

Ideas for improvements:

![image](https://user-images.githubusercontent.com/48241673/116557246-4509d880-a8cc-11eb-8af6-37d42d6bdaee.png)


- in SRGAN Generator, where does it add the global skip connection??? (elementwise sum?)

- From Rylan:
  - add in Wassertein GAN
  - add gradient clipping
  - find a published GAN training routine
  - Compare with code from recitation



- from the paper (but not mentioned by the TA, so it may not be relevant):
  - their implementation of SRGAN's generator net has 16 building blocks, we only have 6 in current implementation.


- should we implement the phi_5,4 loss supposed to be more representative of visual perception / higher level picture features?
- same LR for GEn and Discriminator ?



To do list:
- present autoencoder implementation
- present SRGAN implementation
- present ESRGAN implementation

Try improvements for each and select the best
Explain the results in some ways




