
# **RED-LIGHT-TRAFFIC-VIOLATION-AND-NUMBER-PLATE-DETECTION**

## Project Overview
An autonomous traffic red-light violation detection system was built, which has the potential to significantly improve transportation management in smart cities. The operation of the system is mostly dependent on contemporary computer vision methods, which were implemented in OpenCV inside the Python environment.

---

# Introduction
With the rapid increase in urbanization and vehicles, red-light violations are a major cause of traffic accidents. Traditional traffic management, such as traffic cops at intersections, often cannot ensure consistent surveillance. This project presents an automated system using computer vision to detect red-light violations in real-time and capture the license plates of the offending vehicles. The system aims to enhance road safety and traffic management, especially in smart cities, by leveraging automation and computer vision technology.

---

## 🚀 Development Plan

1. **Project Initialization**
   - Define the project scope and objectives.
   - Set up the development environment.
   - Initialize Git repository and create a structured folder hierarchy.

2. **Data Collection & Preprocessing**
   - Gather video footage of traffic signals and vehicle violations.
   - Annotate datasets for training.
   - Preprocess images/videos.

3. 🛠 **Setting Up MATLAB**
   - Download MATLAB from the official MathWorks website.
   - Install the required toolboxes (e.g., Computer Vision Toolbox, Image Processing Toolbox).
   - Activate MATLAB using a valid license.

4. **Installation**
   - Open MATLAB and run the following command to check installation:
   ```
   ver
   ```

5. **Set Up MATLAB Path**
   - Add your project folder to the MATLAB path:
   ```
   addpath('C:\path	o\your\project')
   savepath
   ```

6. **Running a MATLAB Script**
   ```
   cd 'C:\path	o\your\project'
   ```
   ## **TVD File Summary**

The **TVD file** contains essential video footage and frame data required for traffic violation and accident detection. Please **extract** the file before use, as the system processes these frames and videos for analysis.

### **Key Components:**

1. **Accident_Detection.m (MATLAB Script)**
   - Detects accidents in **.avi** video files using image processing and **CNN-based analysis**.
   - Provides an interactive **GUI** for video selection and processing.

2. **bson.c (C Library)**
   - Handles **BSON (Binary JSON)** data for seamless integration with **MongoDB**.
   - Enables efficient **serialization and storage** of accident detection results.

### **Functionality & Usage:**
- The system analyzes **traffic surveillance footage** to detect accidents and violations in real-time.
- Detected incidents are logged and structured using **MongoDB** as a **big data tool** for efficient record-keeping.

 **Important:** Before running the project, **extract** the **TVD file** to access the required videos and frames. The system relies on these files for accurate detection and processing.

# Architecture Diagram 
![image](https://github.com/user-attachments/assets/4b2d13b9-31d4-48b7-a4df-e4fd6fc1bea2)

The **Red Light Traffic Violation Detection System** integrates **OpenCV, Python, YOLOv5, and MATLAB** for automated enforcement. Traffic cameras capture real-time video, which is processed using **OpenCV** for frame extraction and **MATLAB** for signal detection. **YOLOv5** detects and tracks vehicles, while movement analysis determines violations. License plates are extracted using **OCR (Tesseract/EasyOCR)**, and violation data is stored in a database. The system generates automated reports and sends notifications via **SMS/Email**. A dashboard allows law enforcement to monitor violations efficiently. This solution enhances road safety by reducing manual intervention and ensuring accurate red-light violation detection. 🚦

#  **Output Images**
![WhatsApp Image 2025-02-05 at 23 00 10_7ef5e659](https://github.com/user-attachments/assets/506e9321-1024-4342-b4a8-4abf6bc9e0a0)

![WhatsApp Image 2025-02-05 at 23 00 41_48e2550c](https://github.com/user-attachments/assets/8409c50e-abaa-4f25-b53e-f4d868aacd84)

![WhatsApp Image 2025-02-05 at 23 21 19_7f644a95](https://github.com/user-attachments/assets/be910a23-eda8-41ba-8674-11e9adfe6c90)

The **Number Plate Detection System** leverages **YOLOv5, OpenCV, and OCR** for automated license plate recognition. It includes **RC verification** by cross-checking a vehicle database, a **Duplicate Plate Detector** to identify fraudulent plates, and a **Parking Analyzer** to monitor and manage parking violations. The system enhances security, prevents fraud, and improves parking management for **law enforcement and smart parking applications**. 🚗🔍

![WhatsApp Image 2025-02-05 at 23 21 32_866cc415](https://github.com/user-attachments/assets/ad93ff1d-2875-4787-9b4a-8a760072622b)

![image](https://github.com/user-attachments/assets/c927f744-bd95-4d78-a97f-61762b7a0bce)

![image](https://github.com/user-attachments/assets/8a755611-775b-411a-837f-a6cf51fd0991)

![image](https://github.com/user-attachments/assets/81d30275-baa5-468b-9b2b-c3db22062e91)

![image](https://github.com/user-attachments/assets/02a1cdad-0410-484e-abba-41cc3b2cf46f)

---

# Conclusion
The automated red-light violation detection system demonstrates significant potential in improving traffic control and road safety in smart cities. Using computer vision methods, the system accurately detects violations in real-time and captures the license plates of violators. The combination of object tracking and detection enables efficient monitoring, making the system a valuable tool for modern transportation networks.

---
