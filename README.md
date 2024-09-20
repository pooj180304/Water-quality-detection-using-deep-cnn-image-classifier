## Water Quality Detection Using CNN

This project utilizes a Convolutional Neural Network (CNN) to classify water images into two categories: **clean** or **polluted**. The model was built using TensorFlow and consists of multiple convolutional and pooling layers, followed by dense layers for classification.

## Model Architecture

The CNN model includes the following layers:
- Conv2D : layers for feature extraction
- MaxPooling2D : layers for downsampling
- Flatten layer : to convert the 2D output into a 1D vector
- Dense layers : for classification

| Layer Type  | Output Shape    | Parameters |
|-------------|-----------------|------------|
| Conv2D      | (254, 254, 16)  | 448        |
| MaxPooling2D | (127, 127, 16) | 0          |
| Conv2D      | (125, 125, 32)  | 4640       |
| MaxPooling2D | (62, 62, 32)   | 0          |
| Conv2D      | (60, 60, 16)    | 4624       |
| MaxPooling2D | (30, 30, 16)   | 0          |
| Flatten     | (14400)         | 0          |
| Dense       | (256)           | 3,686,656  |
| Dense       | (1)             | 257        |

## Training Results

The model was trained over **24 epochs** on a dataset containing **228 images** divided into 2 classes. Here are the results:

- **Final Training Accuracy**: 100%
- **Final Validation Accuracy**: 100%
- **Final Validation Loss**: 0.0098

The model successfully converged, achieving a high accuracy of 100% on both the training and validation datasets by the end of training.

## Output

| Epoch  | Training Accuracy | Validation Accuracy | Validation Loss |
|--------|-------------------|---------------------|-----------------|
| 1      | 48.12%            | 50.00%              | 0.7021          |
| 12     | 81.88%            | 89.06%              | 0.2969          |
| 24     | 100%              | 100%                | 0.0098          |

*Graph of Training and Validation Accuracy over Epochs.*

![Model Training Graph](https://github.com/user-attachments/assets/9e6f65f1-7211-47cc-80f8-31d4237f08f8)

## How to Run

1. Clone this repository.
2. Install the necessary dependencies.
   pip install -r requirements.txt
3. Run the water.ipynb file
