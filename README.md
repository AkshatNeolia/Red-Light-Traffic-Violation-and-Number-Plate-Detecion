# RED-LIGHT-TRAFFIC-VIOLATION-AND-NUMBER-PLATE-DETECTION

## Project Overview
An autonomous traffic red-light violation detection system was built, which has the potential to significantly improve transportatsion management in smart cities. The operation of the system is mostly dependent on contemporary computer vision methods, which were implemented in OpenCV inside the Python environment. 

--- 

# Introduction
Traffic management has evolved into an urgent issue due to the growing number of cars on the road and the fast urbanization of cities. The danger of accidents and disruptions to traffic flow caused by drivers disobeying traffic signals, particularly red lights, is a major issue in contemporary traffic regulation. Many accidents, injuries, and deaths are caused by drivers who disregard red lights and continue to drive through [1] them. Particularly in densely populated urban areas, the ability of conventional traffic enforcement measures, such as traffic cops watching junctions, to guarantee constant surveillance and enforcement is sometimes lacking. A potential remedy to these constraints is an automated system that detects when a red signal has been violated.

## 🚀 Development Plan

1. Project Initialization
  Define the project scope and objectives.
  Set up the development environment.
  Initialize Git repository and create a structured folder hierarchy.

2. Data Collection & Preprocessing
  Gather video footage of traffic signals and vehicle violations.
  Annotate datasets for training.
  Preprocess images/videos.

3. 🛠 Setting Up MATLAB
  Download MATLAB from the official MathWorks website.
  Install the required toolboxes (e.g., Computer Vision Toolbox, Image Processing Toolbox).
  Activate MATLAB using a valid license.

4. Installation...
  Open MATLAB and run the following command to check installation:
   ```
   ver
   ```

5. Set Up MATLAB Path
   Add your project folder to the MATLAB path:
   ```
   addpath('C:\path\to\your\project')
   savepath

   ```

6. Running a MATLAB Script
   ```
   cd 'C:\path\to\your\project'

   ```

7. Troubleshooting
  If MATLAB doesn't recognize a function, ensure the script is in the current directory.
  Use which function_name to locate missing functions.
  Reset MATLAB path if needed:
    ```
    restoredefaultpath
    rehash toolboxcache
    savepath
    ```

    
# Architecture Diagram 
![image](https://github.com/user-attachments/assets/4b2d13b9-31d4-48b7-a4df-e4fd6fc1bea2)



![WhatsApp Image 2025-02-05 at 23 00 10_7ef5e659](https://github.com/user-attachments/assets/506e9321-1024-4342-b4a8-4abf6bc9e0a0)

![WhatsApp Image 2025-02-05 at 23 00 41_48e2550c](https://github.com/user-attachments/assets/8409c50e-abaa-4f25-b53e-f4d868aacd84)

![WhatsApp Image 2025-02-05 at 23 21 19_7f644a95](https://github.com/user-attachments/assets/be910a23-eda8-41ba-8674-11e9adfe6c90)

![WhatsApp Image 2025-02-05 at 23 21 32_866cc415](https://github.com/user-attachments/assets/ad93ff1d-2875-4787-9b4a-8a760072622b)

![image](https://github.com/user-attachments/assets/c927f744-bd95-4d78-a97f-61762b7a0bce)

![image](https://github.com/user-attachments/assets/8a755611-775b-411a-837f-a6cf51fd0991)

![image](https://github.com/user-attachments/assets/81d30275-baa5-468b-9b2b-c3db22062e91)

![image](https://github.com/user-attachments/assets/02a1cdad-0410-484e-abba-41cc3b2cf46f)




In addition to improving road safety by reducing traffic offenses, the suggested approach helps make traffic management more efficient. Such automated solutions will be crucial in preserving order and decreasing traffic-related accidents as cities transition to smart infrastructure. This article showcases how computer vision can revolutionize transportation management and set the stage for future smart city innovations.

# Conclusion
In the context of smart cities in particular, the installation of a system to automatically identify red-light violations showed promise for improving traffic control. The system effectively detected and tracked cars that disobeyed traffic signals in real-time by applying contemporary computer vision methods combined with OpenCV in a Python environment. When it came to detecting infractions and accurately recognizing the license plates of violating cars, the system performed well.
The object tracker and object detector, the system's backbone, collaborated to keep tabs on where and how cars were doing. At junctions, the object detector detected automobiles and the tracker followed their every move. Because of this collaboration, the system was able to reliably and efficiently detect red-light offenders by differentiating between complying and non-compliant cars.
In general, the system that automatically detects whether a red light has been violated was a useful tool for making roads safer. Its capacity to collect license plates, identify offenders accurately, and detect in real-time make it a priceless tool for contemporary transportation networks. A sustainable and effective answer to the issues of smart city traffic management is provided by the system, which leverages computer vision capabilities.
