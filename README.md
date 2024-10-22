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

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage

- **Clone the Repository**:
  
  ```bash
  git clone https://github.com/GiorgosKots/Unet_MRI_Segmentation.git
  cd Unet_MRI_Segmentation
  ```

- **Open the Jupyter Notebook**:
  
  Launch Jupyter Notebook and open the [`Unet (5 Methods).ipynb`](https://github.com/GiorgosKots/Unet_MRI_Segmentation/blob/main/Unet%20(5%20Methods).ipynb) file:

  ```bash
  jupyter notebook
  ```

- **Run the Notebook**:
  
  Follow the cells in the notebook to train and evaluate the U-Net model on MRI data.

## Dataset

The notebook requires an MRI dataset for training and evaluation. The tests have been conducted using prostate cancer data from the Medical Segmentation Decathlon dataset. You can use publicly available datasets such as the **BraTS** dataset or any other MRI dataset suitable for segmentation tasks.

Ensure that the dataset is correctly preprocessed and stored in a suitable directory structure as described in the notebook.

## Results

The notebook presents the results for all five training methods, including:

- Model performance metrics such as **Dice coefficient** and **IoU (Intersection over Union)**.
- Visualizations of the segmented output compared to ground truth for qualitative analysis.

## Contributions

Feel free to contribute by:

- Forking the repository.
- Submitting a pull request.
- Enhancements such as:
  - Adding new segmentation methods.
  - Improving the U-Net architecture.
  - Refining the training procedure.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- The U-Net architecture was introduced by **Olaf Ronneberger, Philipp Fischer, and Thomas Brox** in their paper [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597).
- The dataset used for training and evaluation can be credited to the respective authors or contributors.

## Contact

For questions or support, please contact **Giorgos Kotsifakos** at [GitHub](https://github.com/GiorgosKots).

