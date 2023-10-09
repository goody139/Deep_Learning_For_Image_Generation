# Deep_Learning_For_Image_Generation
This repository contains the presentation and Colab noteboks created for the course Deep learning for Image Generation. 

Ulf Krummnack 

2023 

University Osnabrück 

## Author 
Lisa Golla 

## Structure 
In the notebook folder there are 2 notebooks, namely one stable diffusion notebook and one notebook demonstrating a FaceSwap in terms of DeepFakes. The presentation slides are first of all the final presentation of the course, as well as a presentation on AI and creativity for the course as well as presentation slides from a DeepFake presentaion of the course Advanced Computer Vision by Gunther Heidemann since the two presentations were prepared in the same semester with similar input. The notebooks are meant to serve as a demo in order to demonstrate the functionalities and basic concepts. 

## Stable diffusion 

![diffusion_model](https://github.com/goody139/Deep_Learning_For_Image_Generation/assets/72889998/8ab6504e-b204-4d68-829b-64b813d3fc55)


## DeepFake FaceSwap with GHOST 

**How does GHOST work?**

GHOST is mainly based on the AEI-Net. The procedure is displayed above in the picture. The architecture is build like the following:

-  Identity Encoder
 -   (target) features extracted from X_s using the *pretrained* ArcFace model
-Attribute Encoder
 - Attribute features extraction from X_t using U-Net architecture
- AAD Generator
 - Attribute and identity features fusion + creation of output image ˆYs,t, which saves the ’identity’ of a
person from Xs and attributes from Xt


![GHOST](https://github.com/goody139/Deep_Learning_For_Image_Generation/assets/72889998/3bff667c-0567-4949-8b85-f1b0eb224b49)
