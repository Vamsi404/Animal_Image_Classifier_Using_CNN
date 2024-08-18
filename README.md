

# Animal Image Classifier using CNN

This repository contains a Convolutional Neural Network (CNN) model that classifies images of four categories: **Cats**, **Dogs**, **Humans**, and **Horses**. The model is implemented using Python and TensorFlow/Keras.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training and Evaluation](#training-and-evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project demonstrates the use of a CNN for multi-class image classification. The model is trained on a dataset containing images of cats, dogs, humans, and horses, and aims to accurately predict the category of a given image.

## Dataset
The dataset consists of labeled images divided into four classes:
- **Cats**
- **Dogs**
- **Humans**
- **Horses**

Images are split into training and validation sets to evaluate the model's performance.

## Model Architecture
The CNN model uses the following layers:
- Convolutional Layers
- Max Pooling Layers
- Fully Connected Layers (Dense)
- Dropout Layers (for regularization)

The architecture is designed to extract relevant features from the images and classify them accurately.

## Training and Evaluation
- The model is trained for 40 epochs with real-time tracking of accuracy and loss.
- The training data is augmented for better generalization.
- Evaluation is performed on a validation set to monitor the model’s performance.

## Installation
To run the code locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Animal_Image_Classifier_CNN.git
   cd Animal_Image_Classifier_CNN
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
After setting up the environment, you can train the model or use the pre-trained model to classify new images:

1. To train the model:
   ```bash
   python train_model.py
   ```

2. To use the pre-trained model for prediction:
   ```bash
   python predict.py --image_path path/to/your/image.jpg
   ```

## Results
The model achieved high accuracy on the validation set, demonstrating effective feature extraction and classification.

| Class  | Accuracy |
|--------|----------|
| Cats   | 91%      |
| Dogs   | 89%      |
| Humans | 92%      |
| Horses | 90%      |

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any improvements or new features.
