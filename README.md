# CNN Emotion Predictor

A deep learning project that predicts whether a person in an image is **happy** or **sad** using Convolutional Neural Networks (CNNs).

## Overview
This project was built to refresh and strengthen my understanding of **CNN architecture** and **image classification** using deep neural networks.  
The model was trained to distinguish between **happy** and **sad** facial expressions.

Through this project, I practiced:
- Constructing CNNs using **Keras** with a **TensorFlow** backend
- Data preprocessing and augmentation for image classification
- Model training, evaluation, and performance visualization

---

## Technologies Used
- **Python 3**
- **Keras** & **TensorFlow**
- **NumPy**, **Matplotlib**
- **Jupyter Notebook**

---

## Dataset
A sample dataset of happy and sad facial images was used for training and testing.  
I obtained these images through **Google Images searches** and used a browser extension to download images by page.

> **Note:** Dataset was used strictly for educational purposes to practice CNN architecture and is not intended for commercial use.

---

## Results
Training and validation performance:

![Accuracy](deep_learning_model_accuracy.png)
![Loss](deep_learning_model_loss.png)

Example predictions:
- **happy_test.jpg** → Predicted: **Happy**
- **sad_test.jpg** → Predicted: **Sad**

---

## How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/patrickkirbyjr/CNN-Emotion-Predictor.git
    ```
2. Install required dependencies:
    ```bash
    pip install tensorflow keras numpy matplotlib
    ```
3. Open and run the Jupyter Notebook:
    ```bash
    jupyter notebook image_classifier.ipynb
    ```

---

## Lessons Learned
- Refreshed understanding of CNN architecture and training process
- Improved skills in handling image datasets and visualizing model performance
- Gained hands-on experience integrating **Keras** with **TensorFlow**

---

## Next Steps
- Expand dataset to include more emotion classes
- Experiment with transfer learning using pre-trained mod
