# classification-of-ct-kidney-diseases

Welcome to the CT Kidney Disease Classification project! This repository focuses on detecting and classifying abnormalities in CT kidney images. Two different approaches are used: models trained from scratch. = pipeline are designed to predict whether a kidney is normal or abnormal and, if abnormal, classify the type of abnormality. Dataset [CT Kidney Classification](https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone) 

## Dataset Overview
Our dataset contains 12,446 unique samples distributed as follows:

- **Normal**: 5,077 images
- **Cyst**: 3,709 images
- **Stone**: 1,377 images
- **Tumor**: 2,283 images

## Models

### cnn Models
- **Binary Model**: Classifies images as Normal or Abnormal.
- **Multiclass Model**: Classifies Abnormal images into one of the three classes: Cyst, Stone, or Tumor.

## Tools and Libraries

- Python: Programming language for model development.
- TensorFlow/Keras: Deep learning framework.
- NumPy and Pandas: Data manipulation libraries.
- Matplotlib and Seaborn: Visualization tools.

## Training and Evaluation

- Data Split: The dataset is divided into training, validation, and testing sets.
- Evaluation Metrics: Metrics like accuracy, precision, recall, and F1-score are used to evaluate performance.
- Optimization: Uses Adam optimizer with a learning rate scheduler.
  
## License
This project is open-source under the MIT License. Feel free to contribute and improve!

