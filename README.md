# Image Colorization using cGANs and Attention

## Introduction
Image colorization is one of the tasks under the Image Restoration umbrella. It involves predicting reasonable colors for grayscale images. Traditional methods to colorize images mostly relied on human input and feature mapping, due to which they were cumbersome to perform. In this project, we use the power of UNet and GANs, trained on the LSDIR dataset, which is a large-scale dataset for image restoration tasks. To further enhance the model's performance, we evaluated the effect of adding attention to the UNet. This resulted in overall faster convergence and less overfitting of the model. The paper provides experimentation results on four different image colorization architectures using Conditional GANs and UNet with Attention. The main applications of image colorization include the revival of historical black-and-white images, coloring astronomy photos, and fixing underwater and night-time images because of under/over saturation of colors in them. 

## Network Architecture

### Conditional GANs
![ganarchitecture](https://github.com/haardikdharma10/nyu-cv-project/blob/main/gan.png)

### UNet
![unetarchitecture](https://github.com/haardikdharma10/nyu-cv-project/blob/main/unet.png)

## Results

### Comparison of various architectures
<img width="324" alt="results" src="https://github.com/haardikdharma10/nyu-cv-project/assets/53044263/7a871ec6-acd1-4014-9680-c9240a3f73bc">

### Graphs demonstrating convergence of each model
<img width="453" alt="graphs" src="https://github.com/haardikdharma10/nyu-cv-project/assets/53044263/a1195c35-8059-4782-abe8-51844490e248">

### Ablation results
<img width="773" alt="table" src="https://github.com/haardikdharma10/nyu-cv-project/assets/53044263/59b18c77-72bc-4ece-b809-0e8434144a73">
