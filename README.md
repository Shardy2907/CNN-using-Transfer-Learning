# Rice Image Classification using VGG16 and Transfer Learning

## Overview

This repository contains the code for a Convolutional Neural Network (CNN) developed for the classification of rice images. The model is built using the VGG16 architecture and employs transfer learning to leverage pre-trained weights. The dataset used is the Rice Image Dataset, available on Kaggle.

## Dataset

The Rice Image Dataset is available on Kaggle: [Rice Image Dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset).

- **Dataset Description:** The dataset comprises images of different varieties of rice grains. The task is to classify these images into their respective rice varieties.

- **Dataset Structure:**
  - `train/`: Training images
  - `test/`: Test images
  - `labels.csv`: CSV file containing image filenames and corresponding labels (class labels for rice varieties)

## Model Architecture

The model is based on the VGG16 architecture. Transfer learning is employed by using pre-trained weights from the ImageNet dataset. The top 4 layers have been frozen and the fully connected layers have been added.
![image](https://github.com/Shardy2907/CNN-using-Transfer-Learning/assets/110985317/3ad5cb9a-351d-44e9-9078-b0ab2e181fe9)


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.
