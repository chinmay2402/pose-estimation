# 🎥 Pose Estimation and Rep Counter using OpenCV and Mediapipe

This project is a **Pose Estimation and Exercise Counter** using **OpenCV** and **Mediapipe** to track and analyze human body movements in real time through a webcam feed. It counts repetitions of an exercise by measuring the angle between joints, such as a bicep curl or similar movements.

---

## 📚 **Table of Contents**
- [🎯 Project Overview](#-project-overview)
- [⚙️ Technologies Used](#️-technologies-used)
- [🚀 Getting Started](#-getting-started)
- [📜 License](#-license)
- [📧 Contact](#-contact)

---

## 🎯 **Project Overview**

This project uses **Mediapipe's Pose Solution** to identify body landmarks and calculate angles between joints dynamically. The application tracks the position of the left shoulder, left elbow, and left wrist to:
- Measure the angle formed by these points.
- Count repetitions based on specific angles (like a bicep curl).
- Display the current angle and repetition count live on the feed.

The project uses:
- **OpenCV** for capturing and displaying video frames.
- **Mediapipe** to extract body landmarks and draw skeletons.

---

## ⚙️ **Technologies Used**
- 🐍 **Python 3.9+**
- 🎥 **OpenCV 4.5+** – For video capturing and image processing.
- 🤖 **Mediapipe** – For real-time human pose tracking.
- 📊 **NumPy** – For mathematical operations and array manipulations.

---
## 🚀 **Getting Started**

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/pose-estimation.git
```
### 2. Install Required Packages
```bash
pip install opencv-python
pip install mediapipe
pip install numpy
```
### 3. Run the Application
```bash
python main.py
```

---

📜 License
This project is licensed under the MIT License. You are free to modify, distribute, and use this code as per the license terms.

---

📧 Contact
For any questions or inquiries, feel free to contact:

📧 Email: chinmay24csk@gmail.com

🔗 GitHub: https://github.com/chinmay2402
