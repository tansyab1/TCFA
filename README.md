# TCFA: Triplet Clustering Fusion Autoencoder for Quality Enhancement of Wireless Capsule Endoscopy Images (MICCAI 2023)
<b><a href='https://github.com/tansyab1'>Tan-Sy Nguyen</a>, Marie Luong, John Chaussard, Azeddine Beghdadi, Hatem Zaag, Thuong Le-Tien</b> 
<hr>
<i>Medical images such as Wireless Capsule Endoscopy (WCE) images are prone to degradations such as noise, blur, or uneven illumination, which may adversely affect the reliability of the diagnosis. Uneven illumination is one of the degradations that most affects the visibility of relevant details making diagnosis difficult. It should be noted that the use of image quality enhancement methods based on deep neural network architectures has been relatively unexplored for uneven illumination correction, unlike the case of denoising, deblurring, or contrast enhancement, and especially in the case of WCE images. In this paper, we propose a novel method, called Triplet Clustering Fusion Autoencoder (TCFA), for enhancing the quality of WCE images that not only deals with the three types of degradations, namely noise, blur, and uneven illumination but also considers different levels of distortion severity. The main contributions presented in this paper are the following: First, we introduce a distortion level encoder that classifies the severity of each type of distortion using the triplet loss function. Second, we propose a variational cross-attention module that extracts global information for efficient uneven illumination correction, in addition to local perceptual information. Third, a pre-trained network is used to extract relevant structural features from WCE images. These contributions significantly improve the performance of image enhancement tasks, as demonstrated through extensive experiments on WCE images of Kvasir-Capsule with varying levels of degradations. TCFA effectively handles multilevel image distortions, including noise, blur, and uneven illumination. The proposed method is extensively evaluated on the WCE images of Kvasir-Capsule with varying levels of degradations, demonstrating superior performance compared to several state-of-the-art methods.</i>

## Overview

![TCFA](fig/combined.png)

## Package dependencies
The project is built with PyTorch 1.9.0, Python3.7, CUDA11.1. For package dependencies, you can install them by:
```bash
pip install -r requirements.txt
```

## Data preparation 
For Kvasir-Capsule , you can download the simulated dataset from the [official url](https://cloud.math.univ-paris13.fr/index.php/s/2HKjpj8wEbiHkeA).


## Visualization

We provide a visualization of the image enhancement results of TCFA on Kvasir-Capsule dataset

![TCFA](fig/visual.png)

## Contact
Please contact us if there is any question or suggestion(Tan-Sy Nguyen tansy.nguyen@math.univ-paris13.fr).