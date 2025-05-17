# 🤟 Real-Time American Sign Language (ASL) Recognition App

A real-time hand gesture recognition app built using **Streamlit**, **TensorFlow**, **OpenCV**, and **MediaPipe**, designed to recognize 12 common American Sign Language (ASL) signs from webcam or uploaded images.

---

## 🚀 Features

- 🎥 **Live Webcam Gesture Detection**  
  Predict ASL signs in real time using your webcam.

- 🖼️ **Image Upload Prediction**  
  Upload an image to classify a hand gesture on a static frame.

- 🤖 **AI-Powered Classification**  
  Uses a trained deep learning model built with TensorFlow and Keras to predict from 126 3D hand landmarks.

- ✋ **Dual-Hand Support**  
  Processes up to two hands and handles single-hand gestures gracefully.

- 🔍 **Prediction Confidence + FPS Display**  
  Displays classification probability and system performance (frames per second).

- 🛠️ **Robust Logging & Error Handling**  
  Provides detailed logs for troubleshooting and performance monitoring.

---

## 🧠 Recognized ASL Classes (12)

```text
[
            "age", "book", "call", "car", "day", "egypt", "english", "enjoy", "every", "excuse",
            "football", "forget", "fun", "good", "hate", "have", "hello", "help", "holiday", "I",
            "iam", "love", "meet", "month", "morning", "my", "name", "nice", "no", "not", "number", 
            "ok", "picture", "play", "read", "ride", "run", "sorry", "speak", "sport", "take", "thanks",
            "time", "today", "understand", "what", "when", "where", "year", "yes", "you", "your"
]
````

---

## 🛠️ Installation

### ✅ Prerequisites

Ensure Python 3.8–3.10 is installed. Then install dependencies:

```bash
pip install -r requirements.txt
```

### 🔧 Run the App

```bash
streamlit run app-Aug.py
```

> ⚠️ If running in GitHub Codespaces or a remote container:

* Make sure port `8501` is forwarded.
* Allow camera access in your browser.
* Refresh the page if the camera doesn’t start initially.

---

## 📂 Project Structure

```
├── app-Aug.py                   # Streamlit application file
├── requirements.txt             # Required Python packages
├── sign_language_model_AUG_12_TF_2.15.0.h5  # Pretrained model (optional)
└── sign_language_model_AUG_12.h5           # Fallback model weights
```

---

## ⚙️ Tech Stack

* **UI**: Streamlit `v1.34.0`
* **Modeling**: TensorFlow `v2.15.0`, Keras
* **Vision**: OpenCV `v4.9.0`, MediaPipe `v0.10.21`
* **Utilities**: NumPy, Pillow, Logging

---

## 📌 Future Improvements

* 🔡 Add more ASL classes
* 🧾 Display sign descriptions and learning resources
* 🧠 Fine-tune on larger datasets for improved accuracy
* 📱 Create a mobile/web deployable version

---

## 👨‍💻 Author

Developed by:

* [**Mohammed Allam**](https://github.com/mohamedallamai)
* [**Hassan Anwar**](https://github.com/hassancodeanwar)
* [**Ahmed El-Sharkawy**](https://github.com/user-name)

For support, contributions, or collaboration, feel free to connect with us on GitHub.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---
