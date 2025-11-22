# 🧠 OpenCV Static Motion Detection Project

This project demonstrates a **Static Motion Detection System** built using **OpenCV** and **Python**.
There is a defined **Region of Intrest(ROI)** It allows users to detect motion **only within that ROI area** of the video frame.

---

## 🎯 Project Overview

The goal of this project is to identify movement in a **specific region** of a video feed.
This can be useful for surveillance applications where you only care about motion in a certain zone (for example, a doorway, window, or specific part of a room).

---

## 🧩 Features

* 🎥 **Real-Time Motion Detection** using webcam or video file.
* ⚡ **Motion Detection Inside ROI Only.**
* 🚨 **Alert Display:** Motion Detection alerts appear at the top of the Video Frame.

---

## 🛠️ Built With

* **Python 3.x**
* **OpenCV (cv2)**
* **NumPy**

---

## 🚀 How It Works

1. The video stream is captured using **OpenCV**.
2. The system compares the current frame ROI with a reference background frame ROI.
3. If significant pixel differences are detected **within any ROI**, a **motion alert** is displayed on that region.

---

## 💻 Installation & Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Shivaxp/Motion-Detection-Using-Open-cv.git
   cd OpenCV-Static-Motion-Detection-Project
   ```

2. **Install Dependencies:**

   ```bash
   pip install opencv-python numpy
   ```

3. **Run the Project:**

   ```bash
   python motion_detection.py
   ```

---
# **Demo Video**
[Demo](https://youtu.be/ygUDTbizSGk)


