# RadiantCT

**RadiantCT** leverages **Compressive Sensing (CS)** and **Conditional Generative Adversarial Networks (cGANs)** to enhance low-dose CT images, minimizing radiation exposure while improving image quality.

## Features

- **30% Noise Reduction**
- **25% Improvement in Clarity**
- Effective **Artifact Management**

## Methodology

1. **Compressive Sensing (CS)**: Efficient data representation reduces the need for high radiation.
2. **Conditional GAN (cGAN)**: Maps low-dose to high-quality images via a generator-discriminator framework.
   - **Generator**: Converts noisy, low-dose scans into high-quality images.
   - **Discriminator**: Differentiates between real and generated images.

## Results

- **Noise Reduction**: 30% decrease in image noise.
- **Image Clarity**: 25% enhancement in sharpness.
- **Artifact Removal**: Effective management of imaging artifacts.

## Requirements

- Python 3.7+
- TensorFlow 2.0+, Keras, NumPy, OpenCV, Matplotlib
