#  Image Classification with CNN

This notebook implements an image classification pipeline using Convolutional Neural Networks (CNNs) in Keras. The image data is stored as NumPy arrays with pixel values ranging from 0 to 255 and is normalized before training.

##  Overview

- **Dataset Format**: Images stored as NumPy arrays.
- **Normalization**: Pixel values normalized to improve model performance.
- **Model**: A CNN built using the Keras Sequential API.
- **Training**: Model is trained with validation accuracy tracking.
- **Evaluation**: Model is evaluated using standard metrics.
- **Visualization**: Accuracy and loss curves plotted to monitor performance.

## Key Steps

- Data preprocessing and augmentation using `ImageDataGenerator`.
- Built a CNN model using Keras `Sequential` API.
- Trained the model using `model.fit()` with training and validation data.
- Evaluated the model performance on test data.
- Visualized training history such as accuracy and loss.

 ##  Libraries Used

- keras
- tensorflow
- numpy
- matplotlib
