# Crop-disease-detection
Farm-Aid is a deep learning-based solution for classifying crop diseases from leaf images. The project uses convolutional neural networks (CNNs), specifically DenseNet121 and custom CNN architectures, to identify 23 types of crop diseases. The goal is to assist farmers of Maharashtra and Gujarat with early detection to reduce crop loss and improve yield.

### 🚀 Features
Trains and evaluates pre-trained models like ResNet50, MobileNetV2, DenseNet121, and EfficientNetB0, fine-tuned for agricultural image classification for multi-class image classification

Uses custom CNN models for performance comparison , designed for efficiency and accuracy

Applies data augmentation techniques

A diverse dataset of over 13,000 images covering both healthy and diseased crops

### 🧠 Model Architectures
- DenseNet121 
- ResNet50
- MobileNetV2
- EfficientNetB0
- Custom CNN

### 🚀 Result 

FARM-AID achieves over 96% classification accuracy, offering a scalable and field-ready solution that empowers farmers with actionable insights, improving crop yield and agricultural sustainability.

### 🔧 How to Run
1. Clone the repo
```bash
git clone https://github.com/jindsaini2013/Crop-disease-detection.git
```
2. Install required dependencies
```bash
pip install -r requirements.txt
```
3. Run the notebook
```bash
jupyter notebook "Farm-Aid CNN Models.ipynb"
```
