# 🏆 Image Classification: Sport Celebrities 🏆   

## Overview  
This project is an AI/ML-based image classification system that identifies and classifies sport celebrities from a given dataset. The system uses cutting-edge techniques such as **OpenCV** for image processing, **wavelet transformation** for feature extraction, and **grid search** for hyperparameter tuning. The trained model is saved as a **pickle file** for easy deployment and reuse.  

---

## ✨ Features  
- 🧹 **Data Cleaning**: Cleans the test dataset to ensure high-quality input.  
- 🖼️ **Image Processing**: Uses OpenCV for image manipulation and preprocessing.  
- 🔍 **Feature Extraction**: Applies wavelet transformation to extract image features.  
- 🧠 **Model Training**: Optimizes hyperparameters with grid search.  
- 💾 **Model Saving**: Saves the trained model as a `.pkl` file.  

---

## 🛠️ Requirements  
Install the required libraries:  
```bash
pip install opencv-python numpy pandas scikit-learn PyWavelets jupyter
```
---

## 📂 Dataset          


dataset/        

├── cropped/    &nbsp;    &emsp;    # Final cropped Images       
├── celebrity1/     &emsp;     # Subdirectory for celebrity 2           
├── celebrity2/      &emsp;    # Subdirectory for celebrity 2            
└── ...         &emsp;  &emsp;   &emsp; &emsp;   # Subdirectories for other celebrities

---

## 🚀 Usage
**1. Data Cleaning**
   
 - Open the data_cleaning.ipynb notebook to clean and preprocess the dataset:          

 
```bash
jupyter notebook notebooks/data_cleaning.ipynb
```

**2. Image Classification**
   
 - Open the image_classification.ipynb notebook to classify images using the trained model:    

```bash
jupyter notebook notebooks/image_classification.ipynb
```

---




