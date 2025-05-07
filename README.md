# Facial Expression Detection using CNN

The goal of this project is to develop a deep learning-based **Facial Expression Recognition (FER)** system that detects and classifies facial emotions in **real-time** using a **Convolutional Neural Network (CNN)**.

---

## 😀 Recognized Emotions

The system is trained to detect the following seven facial expressions:
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

## 📊 Performance

Achieved Accuracy: ~60% using a custom CNN model trained from scratch

Benchmark Accuracy: ~79.79% using pretrained models (see [FER2013 benchmark on PapersWithCode](https://paperswithcode.com/sota/facial-expression-recognition-on-fer2013))

⚠️ Note: This project intentionally avoids using transfer learning or pretrained models to demonstrate the potential of a raw CNN built and trained from scratch.

---

## 💡 Applications

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


