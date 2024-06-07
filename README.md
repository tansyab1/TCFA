# A New Method for Uneven Illumination Correction of Wireless Capsule Endoscopy Images
<b><a href='https://github.com/tansyab1'>Tan-Sy Nguyen</a>, Marie Luong, John Chaussard, Azeddine Beghdadi, Hatem Zaag, Thuong Le-Tien</b> 
<hr>
<i>We propose a novel method, named Triplet Clustering Fusion Autoencoder (TCFA), oriented for uneven illumination (UI) correction of Wireless Capsule Endoscopy (WCE) images. Our approach also accounts for different levels of distortion severity. To achieve this, we introduce a distortion level encoder utilizing the triplet loss function to classify the UI severity. Additionally, we propose a Variational Cross-Attention module to efficiently correct uneven illumination by extracting both global and structural local information. Furthermore, we leverage a pre-trained network to extract relevant structural features from WCE images. Our method demonstrates significant improvements in image enhancement tasks, as evidenced by extensive experiments conducted on WCE images from the Kvasir-Capsule dataset.
</i>

## Package dependencies
The project is built with PyTorch 1.9.0, Python3.7, CUDA11.1. For package dependencies, you can install them by:
```bash
pip install -r requirements.txt
```

## Data preparation 
For Kvasir-Capsule , you can download the simulated dataset from the [official url](https://cloud.math.univ-paris13.fr/index.php/s/2HKjpj8wEbiHkeA).

## Contact
Please contact us if there is any question or suggestion(Tan-Sy Nguyen tansy.nguyen@math.univ-paris13.fr).
