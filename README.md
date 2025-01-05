# Neutron Field Reconstruction using Machine Learning ⚡

This repository contains a collection of machine learning models used for reconstructing neutron flux fields, such as **phi1**, **phi2**, and **Power**, based on sparse and noisy input data. The project demonstrates the application of different neural network architectures in a nuclear engineering context, including **Autoencoders**, **Masked Autoencoders**, **ResNet**, and **U-Net**.

## **Key Features** 🛠️:
- **Autoencoder Models**: Reconstruction using unsupervised learning techniques.
- **Masking and Noise Handling**: Exploration of the impact of sparsity and noise (sigma) on reconstruction accuracy.
- **Model Evaluation**: Performance metrics like **SSIM**, **L∞ Error**, and **Relative L2 Error** to assess model accuracy.
- **Data Preprocessing**: Handling of noisy, sparse data inputs and comparison of different architectures in reconstructing neutron flux fields.

## **Models Implemented** 🧠:
- **Autoencoders**: Basic model for learning compressed representations and reconstructing input.
- **Masked Autoencoders**: Autoencoders with randomly masked input to simulate incomplete data.
- **ResNet**: Residual networks for deeper, more complex data features.
- **U-Net**: A more advanced architecture for handling spatial data and reconstructing fine-grained outputs.

## **Results** 📊:
The project compares different architectures based on their ability to handle noisy and sparse data, showcasing how noise levels (sigma) and sparsity affect model performance. **U-Net** demonstrated the best overall performance across multiple metrics.

