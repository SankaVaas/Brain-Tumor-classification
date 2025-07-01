# 🧠 Brain Tumor Classification using Xception Model
Brain tumor diagnosis is a critical and time-sensitive task in the medical field. Accurate classification of brain tumors can significantly improve the prognosis and treatment planning for patients. This project presents a deep learning-based solution to classify brain tumors from MRI images using the Xception model, a state-of-the-art convolutional neural network architecture known for its performance and efficiency in image classification tasks.

The primary goal of this project is to build a robust and accurate model capable of distinguishing between different types of brain tumors (e.g., glioma, meningioma, pituitary tumor) and non-tumor brain scans. What makes this project unique is the implementation of both TensorFlow and PyTorch versions of the same architecture, offering flexibility for researchers and developers to choose their preferred deep learning framework.

The Xception model (Extreme Inception) is an extension of the Inception architecture that replaces standard Inception modules with **depthwise separable convolutions**. This results in a more efficient and accurate model with fewer parameters and better generalization, especially for medical imaging tasks. In this project, we leverage pre-trained Xception weights (ImageNet) and fine-tune the model on our brain tumor dataset to adapt it for medical classification.

## 🧪 Dataset
The dataset I used is the **'Brain Tumor MRI Dataset'**, which includes MRI images of brain scans labeled by tumor type. This is a combination of figshare, SARTAJ dataset,and Br35H datasets. It is preprocessed to ensure consistent input size and balanced classes for training. You may need to download the dataset separately and place it in the dataset/ directory.

![image](https://github.com/user-attachments/assets/0a60efad-fbeb-4817-82b8-35947b292e2b)

✅ Objective
The main objectives of this project:

  1. Compare TensorFlow and PyTorch workflows for the same model architecture.
  
  2. Demonstrate the performance of the Xception model in medical image classification.
  
  3. Provide a ready-to-use solution for brain tumor classification using deep learning.
