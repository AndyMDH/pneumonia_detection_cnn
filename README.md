## **Pneumonia Detection in Chest X-Rays Using CNN**

In this Jupyter notebook, we explore an automated approach for detecting pneumonia from chest X-ray images using Convolutional Neural Networks (CNNs). Pneumonia, a serious infectious disease affecting the lungs, is a major health threat that can be fatal. It is mainly caused by the bacterium Streptococcus pneumoniae and is a leading cause of death, particularly in India, where it accounts for one in three deaths (Varshni et al., 2019). X-ray imaging is a pivotal tool in diagnosing pneumonia, helping distinguish between bacterial and viral pneumonia.

Our model showcases an impressive ability to discern between healthy and pneumonia-affected lung scans, boasting a **96% accuracy** on the training set and an **88% accuracy** on the test/validation set. The dataset, drawn from the Kaggle competition repository, comprises a diverse collection of chest X-ray images, including both normal and pneumonia-positive samples.

**Project Scope**
The project encompasses the development and evaluation of a CNN model tailored for accurate pneumonia detection, with a particular focus on differentiating between healthy and affected lung images.

**a. CNN Model Development:**
- Crafting and training a CNN model utilizing the provided dataset.
- Goal: Precisely identify pneumonia in lung images.
  
**Key Focus Areas:**
  - Crafting a CNN architecture with convolution-pooling layers.
  - Tuning parameters such as strides, padding, and activation functions to maximize accuracy.
  - Employing techniques to counter overfitting and boost model generalizability.
    
**b. Training and Evaluation:**
- Employing the training dataset to refine the CNN model.
- Adjusting hyperparameters with validation data to improve outcomes.
- Validating the model's efficacy in detecting pneumonia through test dataset evaluation.

**Methodologies Employed:**
This endeavor employs a suite of techniques including data preprocessing and augmentation, development of CNN architecture with specific attention to padding, strides, and activation functions such as ReLU and sigmoid, optimization using Adam, dropout and L2 regularization for overfitting mitigation, and utilization of callbacks like early stopping, model checkpoint, and ReduceLROnPlateau. Hyperparameter optimization is conducted through Keras Hyperband.
