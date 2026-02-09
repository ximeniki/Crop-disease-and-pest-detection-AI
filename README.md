# Agricultural Health AI: Disease & Pest Recognition

This repository features two specialized Deep Learning models developed to enhance agricultural productivity through automated monitoring. Using **Computer Vision**, these models can be integrated into drone systems or mobile apps to detect plant pathologies and pest infestations in real-time.

## Datasets Used
* **PlantVillage Dataset:** Comprehensive dataset of healthy and diseased crop leaves. [Access here](https://www.kaggle.com/datasets/mohitsingh1804/plantvillage)
* **IP102:** Specialized collection for agricultural pest identification. [Access here](https://www.kaggle.com/datasets/rtlmhjbn/ip02-dataset)

## Technical Highlights

### 1. Plant Disease Classification (Transfer Learning)
* **Model:** MobileNetV2 (Pre-trained on ImageNet).
* **Dataset:** PlantVillage (focusing on multiple species and disease categories).
* **Strategy:** Leveraged **Transfer Learning** for a lightweight architecture, ensuring high efficiency for edge devices like drones.
* **Techniques:** Data Augmentation, Global Average Pooling, and Categorical Cross-Entropy.

### 2. Pest Recognition (Custom CNN)
* **Model:** Custom Convolutional Neural Network.
* **Architecture:** Sequential layers with **Dropout** for regularization to ensure robust performance on external datasets.
* **Optimization:** Adam Optimizer with optimized learning rates.

## Tech Stack
* **Language:** Python 3.x
* **AI Frameworks:** TensorFlow, Keras.
* **Libraries:** OpenCV (Image Processing), NumPy, Matplotlib, Pandas.
* **Environment:** Google Colab.

## Project Structure
* `Plant_Disease_MobileNetV2.ipynb`: Notebook for disease classification using Transfer Learning.
* `Pest_Detection_Custom_CNN.ipynb`: Notebook for custom pest recognition model.

## Results
The models demonstrate high accuracy in identifying crop anomalies, providing a scalable solution for precision agriculture. By utilizing **MobileNetV2**, the system maintains a low computational footprint without compromising predictive power.

---
*Developed as part of my Master’s in AI journey, bridging Mechatronics Engineering with real-world applications.*
