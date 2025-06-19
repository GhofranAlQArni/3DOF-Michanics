# 😊 Facial Emotion Recognition Using Deep Learning

## 🧠 Project Domain  
Computer Vision / Deep Learning / Human-Computer Interaction

---

## 📖 Introduction  
Facial expressions are powerful indicators of a person's emotional state and play a vital role in non-verbal communication. Recognizing emotions automatically from facial expressions has numerous applications, including:
- Mental health analysis
- Human-computer interaction
- Virtual assistants
- Surveillance systems

This project aims to classify human facial emotions into **seven categories** using a **Convolutional Neural Network (CNN)** trained on the **FER-2013** dataset.  
The model detects the following emotions:
> 😠 Angry | 🤢 Disgust | 😨 Fear | 😄 Happy | 😢 Sad | 😲 Surprise | 😐 Neutral

---

## 🧩 Functional Requirements  

### 🖼️ Dataset Loading  
- Loaded FER-2013 dataset from Kaggle.

### 🧹 Data Preprocessing  
- Reshaped and normalized pixel values.  
- One-hot encoded the target emotion labels.  
- Applied data augmentation to improve generalization.

### 🧠 Model Architecture  
- Built a custom CNN using **Keras** and **TensorFlow**.

### 📉 Training Strategy  
- Used callbacks for **early stopping** and **learning rate scheduling**.  
- Tuned the **learning rate** and **batch size** for optimal performance.

### 📈 Model Evaluation  
- Evaluated model based on:  
  - Accuracy  
  - Loss  
  - Confusion Matrix

### 📷 Real-time Prediction  
- Integrated with **OpenCV** to perform real-time facial emotion recognition via webcam.

---

## 📂 Dataset  

- **Source**: [Kaggle - FER-2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)  
- **Records**: 35,887 labeled grayscale images  
- **Image Size**: 48x48 pixels  
- **Categories**: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral  
- **Format**: `.jpg` files

---

## ⚙️ Tools and Libraries Used  

- Python 3.x  
- Jupyter Notebook / Google Colab  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- OpenCV  

---

## 🚀 Future Improvements  
- Deploy as a web app using Streamlit  
- Add multi-face detection in real-time  
- Improve accuracy with deeper networks or transfer learning  
- Add support for video input

---

## 🤝 Let's Connect  
If you're passionate about AI, computer vision, or emotion recognition — feel free to connect or collaborate!


