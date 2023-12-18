# Image Colorization using cGANs and Attention

## Introduction
Image colorization is one of the tasks under the Image Restoration umbrella. It involves predicting reasonable colors for grayscale images. Traditional methods to colorize images mostly relied on human input and feature mapping, due to which they were cumbersome to perform. In this project, we use the power of UNet and GANs, trained on the LSDIR dataset, which is a large-scale dataset for image restoration tasks. To further enhance the model's performance, we evaluated the effect of adding attention to the UNet. This resulted in overall faster convergence and less overfitting of the model. The paper provides experimentation results on four different image colorization architectures using Conditional GANs and UNet with Attention. The main applications of image colorization include the revival of historical black-and-white images, coloring astronomy photos, and fixing underwater and night-time images because of under/over saturation of colors in them. 

## Network Architecture

![ganarchitecture](https://github.com/haardikdharma10/nyu-cv-project/blob/main/gan.png)
![unetarchitecture](https://github.com/haardikdharma10/nyu-cv-project/blob/main/unet.png)