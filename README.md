
# AI for Medical Imaging: A Beginner's Guide <br>

## Medical Image Visualization ##
This Python script is a beginner-friendly guide for handling and visualizing medical images. It includes code snippets for reading DICOM, NIfTI, MAT, and TIFF formats, providing a quick start for beginners in medical image processing. The script uses popular libraries like PyDicom, NiBabel, SciPy, and scikit-image.

## Denoising Autoencoder
This repository contains code for building a convolutional autoencoder model to denoise MR images. The autoencoder architecture is designed to remove noise from MR images, simulating real-world scenarios where medical images are subject to noise during acquisition or transmission.

#### The main components of this repository include:

1. Data loading: The MR images are loaded from the specified directory.

2. Adding Noise: White Gaussian noise with variance is added to simulate real-world noise conditions.

3. Model architecture: The convolutional autoencoder model, comprising encoder and decoder layers.

4. Model training: The autoencoder is trained using noisy MR images as input and corresponding noise-free images as output.

5. Model optimization and evaluation: The trained model's performance is optimized by Adam Optimizer and evaluated using Mean Squared Error (MSE) and Peak Signal-to-Noise Ratio (PSNR) metrics.

6. Results visualization: Random samples of original noise-free images, noisy MR images, and denoised images are visualized.
