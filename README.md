# Agricultural-Robot
An agricultural robot with multiple mechanisms, and weed crop recognition
Here is a **polished, engaging, and GitHub-friendly README** for your agricultural robot project, based on both the design document and the Colab notebook you provided:

---

# 🤖 Smart Agricultural Robot with AI & IoT

A full-stack autonomous farming assistant that combines **IoT**, **AI/ML**, and **precision engineering** to revolutionize the future of agriculture — from **ploughing** to **weeding**, and **crop spraying** to **real-time health monitoring**.

> 🔬 “Automation is the key to sustainable agriculture. Our robot makes that future possible.”

---

## 🌾 Project Overview

This project is about an intelligent multi-functional agricultural robot designed to automate core farming activities such as:

* **Ploughing**
* **Precision Seed Sowing**
* **Watering**
* **Weed Detection and Removal**
* **Fertilizer & Pesticide Spraying**

Powered by **AI-driven YOLOv8 object detection** and built using **Ultralytics** and **Roboflow**, the robot achieves **high precision (mAP\@50 = 93.8%)** in detecting and differentiating between crops and weeds for smart action planning.

---

## ⚙️ Key Features

### 🔧 Hardware Capabilities

* **All-Terrain Navigation** with obstacle avoidance (6 gear motors, NodeMCU)
* **Multi-layered Ploughing System** for efficient soil aeration
* **Servo-based Seeding Mechanism** with uniform depth and spacing
* **Automated Water Irrigation System** with precision nozzles
* **Mechanical Weed Plucking Arms** with sensor control
* **Sprayer Unit** for pesticides or liquid fertilizers
* **Eco-friendly Battery-Powered Design** (NET ZERO Emissions)

### 🧠 AI/ML Integration

* Object detection via **YOLOv8** for real-time crop vs. weed classification
* Custom-trained model on **“TanCropnWeed” dataset** using **Ultralytics + Roboflow**
* **mAP\@50**: `0.938` | **Precision**: `0.916` | **Recall**: `0.812`
* Live predictions for precise weeding actions (no false crop pulling)

---

## 🛠️ Tech Stack

| Layer          | Technologies Used                                      |
| -------------- | ------------------------------------------------------ |
| 💡 AI/ML       | YOLOv8, Ultralytics, PyTorch, Roboflow, Colab          |
| 💻 Programming | Python, Arduino C                                      |
| 🌐 IoT         | NodeMCU, Wi-Fi Module                                  |
| ⚙️ Hardware    | Servo Motors, DC Motors, Sensors, Sprayer Pump, Wheels |

---

## 🚀 Training Details

* 📦 Dataset: Custom-labeled crop vs weed images (via Roboflow)
* 📐 Model: YOLOv8 Small (`yolov8s.pt`)
* 🔧 Augmentation: HSV adjustments, flipping, mosaic, perspective, etc.
* 📊 Evaluation Metrics:

  * **mAP\@50**: 93.8%
  * **mAP\@50–95**: 89.7%
  * **Inference Speed**: \~10ms per image on Tesla T4 GPU

---

## 🌱 Eco-friendly & Scalable

* ✅ Runs on **electrical power** (no emissions)
* 🔋 Designed for **solar integration** in future iterations
* 🌍 Works across diverse crop types and field conditions
* 🧩 Modular hardware — easily upgradable and repairable

---

## 🧩 Future Scope

* 🔍 Real-time **crop health monitoring** with NDVI imagery
* ☀️ **Solar-powered self-sustaining** version for remote villages
* 📡 Cloud sync and app dashboard for farmers
* 🤖 Integration with **Reinforcement Learning agents** for adaptive farming
* 🧭 Enhanced GPS + vision-based autonomous field coverage



