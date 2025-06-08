# U-Net MRI Segmentation

This repository contains a Jupyter Notebook implementing a U-Net model for MRI image segmentation, with five different training and evaluation methods. The goal is to accurately segment MRI images, which is crucial for various medical imaging applications, such as identifying and delineating tumors or other structures in the brain.

## Features

- **U-Net Architecture**: The code utilizes the U-Net neural network, a popular architecture for biomedical image segmentation known for its ability to learn from relatively small datasets and produce accurate segmentations.
- **MRI Segmentation**: The model is trained and evaluated on MRI images, demonstrating its effectiveness for medical image analysis.
- **Five Methods**: The notebook includes five different methods for training and evaluating the model, providing a comprehensive approach to segmentation tasks.

## Requirements

To run the notebook, you need the following dependencies:

- Python 3.x
- Jupyter Notebook
- TensorFlow or PyTorch (depending on the backend used in the notebook)
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

## Dataset

The notebook requires an MRI dataset for training and evaluation. The tests have been conducted using prostate cancer data from the Medical Segmentation Decathlon dataset. You can use publicly available datasets such as the **BraTS** dataset or any other MRI dataset suitable for segmentation tasks.

Ensure that the dataset is correctly preprocessed and stored in a suitable directory structure as described in the notebook.

## Results

The notebook presents the results for all five training methods, including:

- Model performance metrics such as **Dice coefficient** and **IoU (Intersection over Union)**.
- Visualizations of the segmented output compared to ground truth for qualitative analysis.
