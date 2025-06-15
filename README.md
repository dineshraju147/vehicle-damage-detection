# 🚗 Vehicle Damage Detection - FastAPI Backend

This project provides a backend API built with **FastAPI** to detect vehicle damage from images. It uses a deep learning model trained on labeled car damage images to classify whether a car is normal or damaged, and the type and position of the damage.

---

## 🔍 Features

- 🧠 **Transfer Learning with ResNet50**
- 🏷️ **6-Class Classification**
  - Front Normal  
  - Front Crushed  
  - Front Breakage  
  - Rear Normal  
  - Rear Crushed  
  - Rear Breakage
- 📷 **Image Upload Endpoint** to get predictions
- ⚡ Fast and lightweight API using FastAPI
- 📈 Validation Accuracy: ~80%

---

## 🖥️ Sample Prediction

**Endpoint:** `POST /predict`  
**Request:** Upload a car image file  
**Response:**
```json
{
  "prediction": "Rear Breakage"
}
