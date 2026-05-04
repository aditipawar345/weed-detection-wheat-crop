# weed-detection-wheat-crop
Deep Learning-based Weed Detection using U-Net

# 🌾 Weed Detection in Wheat Crops using Deep Learning (U-Net)

## 📌 Overview
This project focuses on detecting weeds in wheat crop images using a Deep Learning-based image segmentation approach. 
A U-Net architecture is implemented using PyTorch to accurately identify and segment weed regions from crop images.

This solution contributes to precision agriculture by enabling automated weed detection, reducing manual effort, and improving crop productivity.

---

## 🚀 Features
- Semantic segmentation using U-Net architecture
- Image preprocessing and normalization
- Custom dataset handling (images + masks)
- Combined Dice + Binary Cross Entropy Loss
- Visualization of predicted weed regions

---

## 🛠️ Tech Stack
- Python
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure

📁 weed-detection-wheat-crop

┣ 📄 weed_detection.ipynb

┣ 📄 README.md

---

## ▶️ How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install torch torchvision opencv-python matplotlib numpy

   📊 Results
Successfully segments weed regions from wheat crop images
Demonstrates effectiveness of U-Net for agricultural image segmentation
Provides clear visualization of predicted masks

⚠️ Limitations
Requires labeled mask dataset
Performance depends on dataset quality and size
Computationally intensive for large-scale deployment

🎯 Future Scope
Improve accuracy using advanced architectures (DeepLab, ResNet-based U-Net)
Real-time detection using drones or edge devices
Deployment as a web or mobile application

--------------------------------------------------------------------------------------------------------------------------------------
## 👩‍💻 Author
Aditi Pawar

---

⭐ If you like this project, give it a star!
