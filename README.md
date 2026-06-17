# 🤟 Sign Language Detector Using Computer Vision

## 📝 Project Description

This project is a real-time **Sign Language Detector** designed to bridge the communication gap between the hearing-impaired community and the general public. Utilizing state-of-the-art computer vision and machine learning frameworks, the system captures live video feed through a webcam, processes hand gestures, and translates them into textual labels in real-time.

Currently, the model is trained and optimized to accurately recognize and predict **7 essential daily-use signs/gestures**:

* 👋 **Hello**
* 👎 **No**
* 👌 **OK**
* 🙏 **Please**
* 🤟 **I Love You**
* 🙇‍♂️ **Thank You**
* 👍 **Yes**

---

## 🛠️ Tech Stack & Libraries Used

* **Python**: Core programming language.
* **OpenCV**: For real-time video capturing, image processing, and frame manipulation.
* **MediaPipe**: For high-fidelity, real-time hand landmark tracking (extracting coordinates of 21 hand joints).
* **NumPy / Scikit-learn / TensorFlow**: *(Select the one you used for training)* For dataset structuring and model prediction.

---

## 🚀 Key Features

* **Real-time Detection:** High FPS tracking with minimal latency.
* **High Accuracy:** Leverages MediaPipe's robust hand-landmark detection to handle varied lighting and backgrounds.
* **User-Friendly Interface:** Direct visual overlay of the predicted sign on the webcam feed screen.

---

## 📸 How It Works

1. The webcam captures live frames of the user's hand gestures.
2. **MediaPipe Hand Landmarker** extracts the spatial coordinates of the hand joints.
3. The extracted features are passed into the trained classification model.
4. The model predicts the probability of the sign and displays the corresponding text label (e.g., "Thank You", "Please") directly on the screen.

