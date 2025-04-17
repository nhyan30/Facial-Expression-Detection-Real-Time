# Facial Expression Detection using CNN

The goal of this project is to develop a deep learning-based **Facial Expression Recognition (FER)** system that detects and classifies facial emotions in **real-time** using a **Convolutional Neural Network (CNN)**.


---
The system is trained on grayscale facial images and is capable of recognizing common human emotions such as:
- 😃 Happy
- 😢 Sad
- 😠 Angry
- 😲 Surprise
- 😐 Neutral
- 😨 Fear
- 😖 Disgust

---

## 🧠 Model Architecture

- Input: Grayscale images (48x48)
- CNN layers with ReLU and MaxPooling
- Dropout for regularization
- Fully Connected (Dense) layers
- Softmax output for classification

---

## 🛠️ Applications

- **Human-Computer Interaction (HCI):** Enhance user experience based on detected emotions.
- **Healthcare Monitoring:** Detect mental health signals (e.g., stress, depression).
- **Education:** Analyze student engagement in online classrooms.
- **Marketing:** Gauge customer reactions to content and products.
- **Security:** Monitor suspicious behavior in surveillance systems.
- **Robotics:** Enable emotional intelligence in robots.

---

## 🛠️ Result
We can use Opencv library to capture the image in a real-time and predict the expression. After running the final piece of code i.e., webcam_test, we will get the below result:


https://github.com/user-attachments/assets/63654367-304d-4905-913e-0f9b15b950cc


