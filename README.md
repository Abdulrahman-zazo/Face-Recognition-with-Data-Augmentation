# Optimizing Deep Learning Performance in Face and Emotion Recognition Using Data Augmentation

This project aims to enhance the accuracy of deep learning models (CNNs) for face recognition and emotion analysis using data augmentation strategies. The models are trained on two datasets:  
1. **Olivetti Faces Dataset** (Face Recognition).  
2. **FER2013 Dataset** (Facial Emotion Recognition).  

## 📝 Requirements
- Python 3.8+
- TensorFlow 2.x
- Keras
- scikit-learn
- pandas, numpy, matplotlib
## 🚀 How to Run
Download Datasets:
1- Olivetti Dataset ![Olivetti Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_olivetti_faces.html)
2- FER2013 Dataset ![FER2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)

Run Google Colab Notebooks:

Olivetti Notebook
FER2013 Notebook

Train the Model:

python
# Example for FER2013 training
model.fit(train_generator, epochs=50, validation_data=test_generator)
