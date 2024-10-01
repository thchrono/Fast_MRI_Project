# MRI Reconstruction using Deep Learning-Based Proximal Gradient Descent

This project implements a deep learning-based Proximal Gradient Descent (PGD) algorithm to reconstruct MRI images from under-sampled k-space measurements. It is inspired by the paper "Regularization by Architecture: A Deep Prior Approach for Inverse Problems." The goal is to accelerate the MRI acquisition process by using fewer k-space measurements, ultimately reducing scan time while maintaining high-quality image reconstruction.

The neural network acts as the proximal operator in the PGD framework, iteratively reconstructing images from partial k-space data. This approach takes advantage of compressed sensing techniques to optimize data acquisition in MRI.

The project utilizes the fastMRI dataset, a collaborative effort between Facebook AI Research (FAIR) and NYU Langone Health, which provides real-world knee MRI data for training and testing the model.

Key Features:
- Efficient MRI reconstruction: Leverages under-sampled k-space data to reconstruct MRI images, reducing acquisition time.
- Deep learning integration: A neural network serves as the proximal operator in the Proximal Gradient Descent framework.
- Compressed sensing: The project employs compressed sensing principles to reduce the number of k-space measurements required, maintaining the quality of the reconstructed images.
