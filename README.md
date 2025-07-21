
# 🚶‍♂️ CrowdSense
<video src="https://github.com/Yash-Codez/CrowdSense/blob/main/video/Sample_1080.mp4"></video>
CrowdSense is a Python-based intelligent system for analyzing pedestrian and vehicle movements using state-of-the-art computer vision and machine learning techniques. Designed for traffic insights, safety analytics, and smart city applications, it features real-time object tracking, zone-based behavior analysis, and advanced visualization — all powered through a sleek graphical interface.

---

## 🎉 What's New (April 2025)

✅ **Smart Intersection Tracking**  
✅ **Custom Zone Definition (sidewalks, crosswalks, etc.)**  
✅ **Vehicle-Pedestrian Interaction Detection**  
✅ **Advanced Homography Calibration for Real-world Scaling**  
✅ **Enhanced Trajectory Mapping & Speed Indicators**  
✅ **Automated Plot Interpretation with Groq’s LlamaVision 90B**  
✅ **Modular Tracking via `tracker_pedv.py`**

---
Enhanced pedestrian tracking visualization with PedV (NEW) 
![pedestrian tracking visualization](img/analysisGUI.png)
Advanced analysis interface with zone definition (NEW)
![analysis interface](img/analysisGUI.png)
## 🚀 Features

- 🔍 YOLOv8-based Object Detection  
- 🔄 Kalman Filter Multi-Object Tracking  
- 🚦 Co-tracking of Pedestrians and Vehicles  
- 🗺️ Custom Zone-Based Analysis (crosswalks, roads, etc.)  
- 📏 Real-world coordinate transformation via Homography  
- 📈 Density and Speed Estimation (Voronoi & traditional methods)  
- 🧠 AI Analysis of PedPy Plots using LlamaVision via Groq API  
- 🖥️ PyQt6-based Interactive GUI  
- 📂 Exportable Trajectory Data & Zone Reports

---

## 🖥️ GUI Preview

- Load and analyze video in real time  
- Visualize object paths, speed heatmaps, and zone-based metrics  
- View automatic plot interpretations in the analysis panel

> **Screenshots & Demo Videos**
[![watch crowdsense demo](img/logo2.png)](https://www.youtube.com/watch?v=8AqZnFtbx6g)

Main application interface
![screenshot](img/GUI_setting.png)
Video processing and tracking visualization
![visualization](img/GUI-2.png)
Density, Speed and trajectory analysis plots using Pedpy and LllamaVision
[Density, Speed and trajectory analysis](img/Plot_window.png)

---

## 📦 Installation

```bash
git clone https://github.com/Yash-Codez/CrowdSense.git
cd CrowdSense
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python CrowdSense.py
