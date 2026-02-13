# 🚦 Real-Time Intelligent Traffic Violation Detection System

## 📌 Overview

Road safety remains a major concern worldwide, especially in densely populated countries. Traditional traffic monitoring systems rely heavily on manual surveillance, which is inefficient and error-prone.

This project presents a **real-time intelligent traffic violation detection system** that leverages deep learning models to automatically detect and classify traffic violations from video streams.

The system integrates:

* **YOLOv8** for object detection
* **MobileNetV3** for lightweight classification
* Real-time image & video processing pipeline
* Automated violation flagging mechanism

---

## 🎯 Objectives

* Detect vehicles in real-time using deep learning
* Identify traffic violations such as:

  * 🏍️ Helmet violation
  * 🚗 Lane violation {yet to decide}
  * 🛑 Signal violation
  * 🏍️ Tripling violation
  * 🔢 HSRP number plate violation
* Build an optimized and lightweight solution for deployment
* Ensure real-time performance suitable for smart city applications

---

## 🧠 Technologies Used

| Category         | Tools & Frameworks                           |
| ---------------- | -------------------------------------------- |
| Language         | Python                                       |
| Deep Learning    | PyTorch                                      |
| Object Detection | YOLOv8                                       |
| Classification   | MobileNetV3                                  |
| Computer Vision  | OpenCV                                       |
| Model Training   | Ultralytics Framework                        |
| Dataset          | Custom Traffic Dataset / Public Road Dataset |
| Deployment       | Local GPU / Edge Device                      |

---

## 🏗️ System Architecture

1. Input Image and video stream (CCTV / recorded footage / dashcam footage)
2. YOLOv8 detects vehicles and relevant objects
3. Region of Interest (ROI) extraction
4. MobileNetV3 classifies violation type
5. Violation logging and alert generation

---

## ⚙️ Methodology

### 1️⃣ Object Detection (YOLOv8)

* Pre-trained YOLOv8 model fine-tuned on traffic dataset
* Detects:

  * Cars
  * Bikes
  * Number Plates
  * Traffic signals
  * Riders
  * Helmets

Why YOLOv8?

* High accuracy
* Real-time speed
* Lightweight compared to previous versions

---

### 2️⃣ Violation Classification (MobileNetV3)

* Used for lightweight classification
* Optimized for real-time edge deployment
* Efficient architecture with reduced computation cost

Why MobileNetV3?

* Fast inference
* Suitable for embedded systems
* Low memory footprint

---

## 📊 Model Performance

* Real-time detection achieved at XX FPS
* Detection Accuracy: XX%
* Classification Accuracy: XX%
* Low false positive rate in controlled testing

(You can update these after training)

---

## 🚀 Features

* ✅ Real-time processing
* ✅ Lightweight and efficient architecture
* ✅ Modular design for scalability
* ✅ Easy integration with CCTV systems
* ✅ Edge-device compatible

---

## 🌍 Applications

* Smart City Surveillance
* Automated Traffic Monitoring
* Law Enforcement Assistance
* Accident Prevention Systems

---

## 👥 Team Members

* Lurvik Pokala
* Pushkar Potdar
* Pranjal
* Rahul R

---

## 📈 Future Improvements

* License Plate Recognition (ANPR integration)
* Cloud-based violation reporting dashboard
* Real-time alert notification system
* Deployment on Raspberry Pi / Edge TPU
* Multi-camera tracking system

---

## 📜 Conclusion

This project demonstrates how modern deep learning models such as YOLOv8 and MobileNetV3 can be combined to create an efficient and scalable real-time traffic violation detection system.

The proposed system aims to improve road safety and reduce manual monitoring efforts through intelligent automation.