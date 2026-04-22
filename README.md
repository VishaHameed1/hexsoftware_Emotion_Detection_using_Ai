
# 🎭 Emotion Detection using AI

Detect human emotions (Happy 😊, Sad 😔, Tired 😴, Neutral 😐) from facial expressions using **OpenCV** and AI-based techniques.

---

## 📌 Overview

This project uses **Computer Vision** to analyze facial expressions and classify emotions in real-time. It leverages **Haar Cascade Classifier** for face detection and a trained AI model for emotion prediction.

---

## 🚀 Features

* 🎥 Real-time emotion detection via webcam
* 🖼️ Supports image input
* 😀 Detects multiple emotions:

  * HAPPY 😊
  * SAD 😔
  * TIRED 😴
  * NEUTRAL 😐
* ⚡ Fast and efficient using OpenCV
* 🎯 High accuracy with Haar Cascades

---

## 🧠 Tech Stack

* Python 🐍
* OpenCV 👁️
* NumPy 🔢
* Haar Cascade Classifier

---

## 📂 Project Structure

```
Emotion-Detection/
│── model/                # Trained AI model
│── haarcascade/          # Haar cascade XML files
│── images/               # Sample images
│── main.py               # Main execution file
│── utils.py              # Helper functions
│── README.md             # Project documentation
```

---

## 📦 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/emotion-detection-ai.git
cd emotion-detection-ai
```

### 2️⃣ Install Dependencies

```bash
pip install opencv-python numpy
```

---

## ▶️ Usage

### 🔹 Run with Webcam

```bash
python main.py
```

### 🔹 Run with Image

```bash
python main.py --image path/to/image.jpg
```

---

## ⚙️ How It Works

1. Capture image/frame from webcam
2. Detect faces using Haar Cascade
3. Extract facial region
4. Pass to trained AI model
5. Predict emotion label
6. Display result on screen

---

## 📸 Output Example

```
[INFO] Detecting emotions...
Face Detected → Emotion: HAPPY 😊
```

---

## 🎯 Future Improvements

* 🔥 Deep Learning (CNN) integration
* 🎭 More emotions (Angry, Surprise, Fear)
* 📱 Mobile app deployment
* ☁️ Cloud-based API

---

## 🤝 Contribution

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Commit changes
4. Push and create PR

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Author

**Visha Hameed**
AI/ML Engineer in Progress 🚀


