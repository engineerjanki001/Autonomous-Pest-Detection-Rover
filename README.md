# 🌾 Autonomous Pest-Detection Rover

## 🚀 Overview
The **Autonomous Pest-Detection Rover** is a low-cost robotic system designed to help identify early signs of pest infestation or plant stress in crops. The rover autonomously navigates through plant rows, collects data, and alerts users to potential issues, supporting sustainable and efficient agriculture.

---

## ❓ Problem
Pests and plant diseases are often detected too late through manual inspection, resulting in:
- Crop damage
- Reduced yield
- Excessive pesticide use

This process is time-consuming and difficult to scale.

---

## 💡 Solution
Our rover automates plant monitoring by:
- Navigating autonomously
- Avoiding obstacles
- Monitoring plant health using sensors
- Optionally detecting pests using camera-based image analysis

Early detection allows faster and more targeted intervention.

---

## ⚙️ System Architecture
- **Raspberry Pi Pico H**
  - Motor control
  - Sensor data collection
  - Obstacle avoidance

- **Optional Raspberry Pi 3/4**
  - Camera input
  - Image processing
  - ML-based pest detection

---

## 🧰 Hardware Used
- Raspberry Pi Pico H  
- (Optional) Raspberry Pi 3 / 4  
- Rover chassis with DC motors  
- Motor driver (L298N / TB6612)  
- Ultrasonic sensors  
- Soil moisture sensor  
- Battery pack  
- Camera module (optional)

---

## 🧠 Software Stack
- MicroPython / C++ (Pico H)
- Python (Raspberry Pi)
- OpenCV (optional)
- TensorFlow Lite (optional)

---

## 🤖 How It Works
1. Rover moves autonomously along a predefined path  
2. Ultrasonic sensors detect obstacles  
3. Plant data is collected at regular intervals  
4. System analyzes sensor data (and images if enabled)  
5. Alerts are generated when abnormalities are detected  

---

## 🎥 Demo
- Autonomous navigation
- Plant stress detection using sensors
- Optional image-based pest detection
- Live or recorded output

---

## 💰 Budget
- 
- **Full version (camera + ML):** $105–150  

---

## 🌱 Impact
- Encourages sustainable farming
- Reduces pesticide overuse
- Enables early pest detection
- Affordable and scalable

---

## 🔮 Future Improvements
- Advanced pest classification models
- GPS-based field mapping
- Cloud analytics dashboard
- Automated targeted spraying
- Multi-rover coordination

---

