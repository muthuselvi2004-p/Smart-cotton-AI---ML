# 🌿 Smart Cotton AI

An AI-powered smart agriculture system for cotton disease detection using Deep Learning, Autoencoder Anomaly Detection, Arduino Automation, Telegram Alerts, and a Colorful Gradio Web Interface.

---

# 🚀 Project Overview

Smart Cotton AI is an intelligent crop monitoring system designed to help farmers identify cotton plant diseases automatically using AI models.

The system combines:

- ✅ Autoencoder-based anomaly detection
- ✅ CNN disease classification
- ✅ Real-time webcam detection
- ✅ Telegram alert notifications
- ✅ Arduino automated spray control
- ✅ Detection history logging
- ✅ Bilingual fertilizer recommendations (English + Tamil)
- ✅ Interactive Gradio UI

---

# 🧠 AI Models Used

## 1️⃣ Autoencoder Model
Used for:
- Healthy vs abnormal plant detection
- Reconstruction error analysis

If reconstruction error is below threshold:

:contentReference[oaicite:0]{index=0}

The leaf is considered healthy.

---

## 2️⃣ CNN Model (MobileNet)
Used for disease classification.

Detected Classes:
- Aphids
- Army Worm
- Bacterial Blight
- Fungal Disease
- Powdery Mildew
- Healthy

---

# ⚙️ Features

## 🌿 Disease Detection
- Upload cotton leaf image
- Webcam live capture
- Real-time AI prediction

## 📱 Telegram Alerts
- Sends automatic alerts
- Includes detected disease image
- Fertilizer recommendations

## 🤖 Arduino Smart Spray
- Activates pesticide spray automatically
- Different triggers for healthy/diseased plants

## 📊 Detection History
- Stores previous detections
- Timestamp logging

## 🌐 User-Friendly Interface
- Beautiful colorful Gradio UI
- Simple farmer-friendly workflow

---

# 🏗️ System Architecture

```text
Cotton Leaf Image
        ↓
Autoencoder Detection
        ↓
Healthy ? ---- YES → Healthy Output
        ↓ NO
CNN Disease Classification
        ↓
Telegram Alert + Arduino Spray
        ↓
Detection History Storage
```

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main Programming |
| TensorFlow / Keras | Deep Learning |
| OpenCV | Image Processing |
| Gradio | Web Interface |
| Arduino | Smart Spray Automation |
| Telegram Bot API | Alert Notifications |
| NumPy | Numerical Operations |
| Pandas | Detection History |


# ⭐ Conclusion

Smart Cotton AI helps farmers with:
- Early disease detection
- Reduced crop loss
- Automated smart farming
- Real-time monitoring
- AI-powered recommendations

This project combines Artificial Intelligence, IoT, and Smart Agriculture into a single intelligent system.

---

