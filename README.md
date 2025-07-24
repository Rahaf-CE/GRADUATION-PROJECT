# Skin Disease Detection Using Deep Learning and Image Processing

This project is a graduation capstone developed by students from Birzeit University. It presents a complete AI-based system for classifying 10 types of skin diseases using dermoscopic images, deep learning models, and a user-friendly web application.

## 🩺 Project Objective
To develop an automated, real-time, and accessible skin disease classification tool using convolutional neural networks (CNNs), optimized through transfer learning and deployed via a Flask web application.

## 🔍 Key Features
- Multi-class classification of 10 common skin conditions.
- Preprocessing techniques for improved accuracy.
- Multiple CNN models trained and evaluated (Custom CNN, ResNet50, DenseNet121, MobileNetV2).
- Best model (MobileNetV2) selected based on performance.
- Flask-based web app for user interaction and prediction.
- Supports image upload and live camera capture.
- Multilingual interface: English & Arabic.

## 📂 Dataset
- Source: [Kaggle Skin Disease Dataset](https://www.kaggle.com/)
- Total Images: 25,000+
- Classes: Eczema, Melanoma, Atopic Dermatitis, Basal Cell Carcinoma, Nevi, Psoriasis, Fungal Infections, Viral Infections, etc.
- Stratified train-validation-test split with data augmentation.
- Imbalance handled using class-weighted loss.

## 🧠 Deep Learning Models
| Model         | Description                      |
|---------------|----------------------------------|
| Custom CNN    | Built from scratch               |
| ResNet50      | Deep network with skip connections |
| DenseNet121   | Feature reuse for improved learning |
| MobileNetV2   | Lightweight and high-performance |

- Framework: PyTorch
- Optimizer: Adam
- Loss: CrossEntropy with class weights
- Transfer Learning: Pre-trained on ImageNet

## 🚀 Web App Deployment
- Backend: Flask
- Frontend: HTML, CSS, JS (Bootstrap)
- Features:
  - Upload or capture image
  - Instant prediction with confidence score
  - Disease information display
  - Language toggle (EN/AR)
  - Dark/light mode

## 📊 Results
| Model         | Accuracy | Notes                        |
|---------------|----------|------------------------------|
| Custom CNN    | Low      | Underfitting                 |
| ResNet50      | Moderate | Accurate but large           |
| DenseNet121   | Moderate | Good accuracy, heavier model |
| MobileNetV2   | **Best** | High accuracy, fast, small   |

- MobileNetV2 achieved highest performance and was used in deployment.

## 📱 Future Work
- Add Grad-CAM visualizations for interpretability.
- Extend to Android mobile app.
- Test with real clinical data.
- Expand to additional disease classes.


Appendix 
 
1. Model link : https://drive.google.com/uc?id=12ASf_FHdmt_JjNOIepkU_zh74y8NofZM 
 
2. Codes link 
https://drive.google.com/drive/folders/1u_3Os8QRrldNLJ8B_CiV_OO3Ccsz1aqj?usp=sharing 
 
3. App link : 
https://drive.google.com/uc?export=download&id=19cubmqjcHGHuupmI4WK_AtET0L8MPUhO 
 
4. Web link: https://effervescent-griffin-c9e25b.netlify.app/
