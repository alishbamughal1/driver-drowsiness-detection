# 🚗 Driver Drowsiness Detection System

## 📌 Overview

Driver drowsiness is a major cause of road accidents worldwide. This project presents a real-time driver drowsiness detection system using computer vision techniques to monitor driver alertness and prevent potential accidents.

---

## 🎯 Objective

The main objective of this project is to enhance road safety by detecting early signs of driver fatigue and providing timely alerts.

---

## ⚙️ Technologies Used

* Python
* YOLOv8 (Object Detection Model)
* OpenCV (Computer Vision)
* NumPy

---

## 🧠 Methodology / Working

1. The system captures real-time video input from a webcam.
2. YOLOv8 model is used to detect facial features, especially eyes.
3. Eye state (open/closed) is continuously monitored.
4. If eyes remain closed for a specific duration, the system identifies drowsiness.
5. An alert (sound/notification) is triggered to wake the driver.

---

## 📊 Features

* Real-time monitoring
* Fast and efficient object detection using YOLOv8
* Automated alert system
* Can be extended for vehicle safety systems

---

## 🚀 Future Improvements

* Improve accuracy with larger datasets
* Add head pose detection
* Deploy as a mobile or embedded system
* Integrate with IoT-based vehicle systems

---

## 📂 Project Structure

* `notebook.ipynb` → Main implementation
* `model/` → Trained model files
* `utils/` → Helper functions

---

## ▶️ How to Run

1. Install required libraries:

   ```bash
   pip install opencv-python ultralytics numpy
   ```
2. Run the Jupyter Notebook
3. Ensure webcam is connected

---

## 📈 Results

The system successfully detects driver drowsiness in real-time and provides alerts, helping reduce the risk of accidents.

---

## 📫 Contact

**Alishba**
📧 [malishba510@gmail.com](mailto:malishba510@gmail.com)
