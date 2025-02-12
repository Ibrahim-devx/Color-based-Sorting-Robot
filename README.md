# 🎨🤖 Color-Based Sorting Robot  

A **smart automation system** that uses **computer vision and robotics** to detect and sort objects based on their color. This project integrates **Raspberry Pi, OpenCV, and a robotic arm** to enhance industrial automation by improving sorting accuracy and reducing manual labor.  

![Project Overview](demo_images/project.jpg) 
---

## 🚀 Features  
✅ **Real-time Color Detection** – Uses **OpenCV and a camera** to recognize colors.  
✅ **Automated Sorting** – A robotic arm sorts objects into bins based on color.  
✅ **Conveyor Belt System** – Moves objects for continuous sorting.  
✅ **Microcontroller Integration** – Powered by **Raspberry Pi & Arduino** for control.  
✅ **Efficient & Scalable** – Designed for **industrial and educational applications**.  

---

## 🎥 Demo & Project Overview  

### 📌 System Overview  
The system consists of:  
- A **conveyor belt** to transport objects  
- A **camera (Arducam) & OpenCV** for color detection  
- A **Raspberry Pi 4** for processing  
- An **Arduino-controlled robotic arm** for object sorting  

 
## 🎥 Demo GIF  
![Sorting Robot in Action](demo_images/project_demo.gif)
---

### 📌 Working Process  
1️⃣ **Object is placed on the conveyor belt**  
2️⃣ **Camera captures an image & detects color using OpenCV**  
3️⃣ **Raspberry Pi processes the image & determines sorting category**  
4️⃣ **Robotic arm picks & places the object in the correct bin**  

![Sorting Process](demo_images/flowchart.png)  

---

### 📌 Color Recognition in Action  
The system classifies objects into ** Green, Blue, and Yellow** bins based on **HSV color space processing** in OpenCV.  

![Color Detection](demo_images/color_detection.png)  

---

## 🛠️ Hardware & Software Used  

### 🔹 Hardware Components  
- 🎯 **Raspberry Pi 4** – Main processing unit  
<img src="demo_images/Raspberry pi 4.jpg" alt="Raspberry pi 4" height="350">
- 🎯 **Arduino Uno** – Controls robotic arm  
<img src="demo_images/Arduino.jpg" alt="Project Overview" width="500">

- 🎯 **Arducam Camera Module** – Captures object images
![Camera](demo_images/camera.jpg)   

- 🎯 **L298N Motor Driver** – Controls motors  
![Motor Driver](demo_images/L298N.jpg) 

- 🎯 **12V Gear-box Motor** – Moves conveyer belt
![Gear-box Motor](demo_images/12V Gear-box Motor.jpg) 

- 🎯 **Servo Motors** – Moves robotic arm  
![Servo Motor](demo_images/servo motor.jpg) 
<img src="demo_images/servo_motor.jpg" alt="servor motor" width="500">
- 🎯 **Conveyor Belt System** – Transports objects
- ![Conveyer](demo_images/conveyer_belt_3D.jpg)  
<img src="demo_images/conveyer_belt_3D.jpg" alt="onveyer belt 3D" width="500" height="300">

 
### 🔹 Software & Libraries  
- 🖥️ **Python & OpenCV** – Image processing & color detection  
- 🖥️ **KivyMD** – App interface for monitoring  
- 🖥️ **Arduino IDE** – Microcontroller programming  
- 🖥️ **Thonny IDE** – Microprocessor programming  
- 🖥️ **SolidWorks** – Mechanical design  

