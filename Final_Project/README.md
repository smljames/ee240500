# Final Project
# Showy Dancing Robot

### **Objective**
Boe-Bot Robot will track the light, and when it is under the light, the robot will dance with different styles according to the gesture recognized  by the webcam using OpenCV C++ API.

### **List of software or hardware components**  
* **Software**   
  * OpenCV (C++)    
  * C/C++  

* **Hardware**  
  * Nitrogen6X  
  * Boe-Bot Robot    
  * Webcam  
  * XBEE  
  * Ultrasound distance sensor  

### **Schematic or flow diagram of your system**  
  **Music**: Webcam (gesture) -> Server (analysis using OpenCV) -> XBEE -> Robot can play the music  
  
  **Dancing**: Brightness (spotlight) -> Robot go ahead to it -> Ultrasound (check the space) -> Robot can dance with the music  
