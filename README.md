# 🚨 Threat Security Software (TSS)

## Real-Time Employee Danger & Safety Detection System

**Machine Learning | Computer Vision | Industrial Safety**

---

## 📌 Project Overview

**Threat Security Software (TSS)** is a real-time safety monitoring system designed to **detect dangerous human postures in industrial environments** and **prevent workplace accidents**.
The system leverages **computer vision and pose estimation** to continuously monitor human hand and body movements using live camera feeds and triggers immediate safety actions when unsafe proximity to hazardous zones is detected.

Unlike traditional safety systems, TSS is a **software-only solution** that utilizes **existing CCTV/webcam infrastructure**, eliminating dependency on physical sensors.

---

## 🎯 Problem Statement

Manual supervision in high-risk industrial environments is:

* Error-prone
* Costly
* Not scalable

Unsafe hand positions near machinery often lead to **severe injuries or fatal accidents**.
TSS addresses this problem by providing an **automated, non-intrusive, real-time posture detection system**.

---

## 🧠 Solution Approach

The system uses:

* **MediaPipe Holistic & Hand Landmark Models** for precise keypoint detection
* **OpenCV** for real-time video processing
* **Geometric distance analysis** to detect violation of safety boundaries
* **Rule-based decision logic** to trigger alerts and shutdown actions

---

## ⚙️ Key Features

* ✅ **Real-Time Hand & Body Pose Detection**
* ✅ **Danger Zone Violation Detection**
* ✅ **Machine Safety Boundary Enforcement**
* ✅ **Immediate Alert & System Shutdown Trigger**
* ✅ **No Sensor Dependency**
* ✅ **High FPS Real-Time Processing**
* ✅ **Works with Standard Webcams / CCTV Feeds**

---

## 🧩 System Architecture (High-Level)

1. Live video input captured from webcam/CCTV
2. Frame preprocessing using OpenCV
3. Pose & hand landmark extraction using MediaPipe
4. Distance computation between landmarks and danger lines
5. Safety rule evaluation
6. Alert generation and system response

---

## 🛠️ Technology Stack

| Category             | Technology                   |
| -------------------- | ---------------------------- |
| Programming Language | Python 3.9                   |
| Computer Vision      | OpenCV                       |
| Pose Estimation      | MediaPipe (Hands & Holistic) |
| Numerical Computing  | NumPy, SciPy                 |
| IDE                  | VS Code / PyCharm            |
| OS Support           | Windows / Linux / macOS      |

---

## 📁 Project Structure

```bash
.
├── EmployeeDangerSafetyFinal.py   # Main execution script
├── requirements.txt               # Project dependencies
├── README.md                      # Project documentation
```

---

## 🚀 Steps to Execute the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/threat-security-software.git
cd threat-security-software
```

---

### 2️⃣ Create & Activate Virtual Environment (Recommended)

```bash
python -m venv venv
```

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

> ⚠️ **Python 3.9 is strongly recommended** due to MediaPipe compatibility.

---

### 4️⃣ Run the Application

```bash
python EmployeeDangerSafetyFinal.py
```

---

## 📸 Output & Behavior

* Live video feed window opens
* Blue line → **Safety Boundary**
* Red line → **Machine Danger Zone**
* If any finger or hand crosses the danger line:

  * Warning is displayed
  * System prints shutdown alert
  * Safety action is triggered

---

## ⚠️ Important Notes

* Webcam access is mandatory
* Ensure proper lighting for accurate detection
* Run inside virtual environment for stability
* MediaPipe may fail on Python ≥ 3.11

---

## 🏭 Applications

* Industrial safety monitoring
* Manufacturing plants
* Construction sites
* Restricted area surveillance
* Touchless safety systems
* Accident prevention systems

---

## 📈 Future Enhancements

* Machine learning–based posture classification
* Integration with PLC / IoT controllers
* Audio-visual alert systems
* Multi-camera support
* Predictive accident analytics

---

## 📄 License

This project is developed for **academic and research purposes**.
