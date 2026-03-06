# Face-Mask-Detection-using-Convolutional-Neural-Network-CNN-
# 😷 Face_Mask_Detection_using_CNN
Face Mask Detection using CNN and OpenCV

## 📌 Project Description
This project implements a **Face Mask Detection system** using **Deep Learning and Computer Vision**. The model is built using a **Convolutional Neural Network (CNN)** to classify images into two categories:

- **With Mask**
- **Without Mask**

The system can detect masks from **images and real-time webcam video** using OpenCV.

This solution can help monitor safety compliance in public places during health emergencies like COVID-19.

---

# 🎯 Project Objectives

- Develop a CNN model for mask detection
- Train the model using labeled image datasets
- Evaluate the model performance using accuracy metrics
- Implement real-time mask detection using webcam
- Demonstrate the use of Computer Vision and Deep Learning

---

# 🧠 Technologies Used

- Python
- NumPy
- Matplotlib
- OpenCV
- TensorFlow / Keras
- Jupyter Notebook

---

# 📊 Dataset

The dataset contains two classes:

| Class | Description |
|------|-------------|
| With Mask | Images of people wearing face masks |
| Without Mask | Images of people not wearing face masks |

## 📥 Download Dataset

Due to large size, the dataset is not uploaded to GitHub.

Download the dataset from the link below:

```
Dataset Download Link:
https://your-dataset-download-link
```

After downloading, extract the dataset and place it inside the project folder like this:

```
dataset/
   with_mask/
   without_mask/
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/chinnarasan007/face-mask-detection.git
```

Navigate to the project directory:

```bash
cd face-mask-detection
```

Install required dependencies:

```bash
pip install numpy opencv-python tensorflow matplotlib
```

---

# 🏗 Model Architecture

The CNN model includes the following layers:

1. Convolution Layer (Conv2D) – Extracts features from images  
2. MaxPooling Layer – Reduces spatial dimensions  
3. Flatten Layer – Converts feature maps into vectors  
4. Dense Layer – Fully connected classification layer  
5. Dropout Layer – Prevents overfitting  

---

# 🧪 Model Training

Example training code:

```python
model.compile(
    optimizer='adam',
    loss='binary_crossentropy',
    metrics=['accuracy']
)

history = model.fit(
    train_data,
    validation_data=validation_data,
    epochs=10
)
```

---

# 📈 Model Performance

| Metric | Result |
|------|------|
| Training Accuracy | ~95% |
| Validation Accuracy | ~93% |

*(Results may vary depending on dataset size.)*

---

# 📷 Real-Time Face Mask Detection

The project supports **live detection using webcam**.

Steps performed:

1. Capture video from webcam  
2. Detect faces using Haar Cascade  
3. Extract the face region  
4. Pass the image to the CNN model  
5. Display prediction result on screen  

Example output:

```
Person 1 → With Mask 😷
Person 2 → Without Mask ⚠️

```

# 🚀 Future Improvements

- Use Transfer Learning (MobileNetV2, ResNet)
- Improve accuracy with larger datasets
- Deploy the model using Flask or Streamlit
- Integrate with CCTV surveillance systems
- Build a mobile application

---

# 📚 Learning Outcomes

Through this project we learned:

- Image preprocessing techniques
- CNN architecture for image classification
- Model training and evaluation
- Real-time computer vision using OpenCV
- Deep learning model deployment

---

# 📌 Conclusion

This project demonstrates how **Deep Learning and Computer Vision** can be applied to solve real-world problems like face mask compliance monitoring.

The CNN model successfully classifies images as **mask or no-mask** and performs **real-time detection using webcam**.

---

# 👨‍💻 Author

Poojashri k
Aspiring Data Scientist
