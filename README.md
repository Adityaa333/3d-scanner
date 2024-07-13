3D Scanner Project
======

This project is an innovative implementation of a cost-efficient 3D scanner that utilizes : 

- Arduino Nano
- A4988 motor modules
- SD card module 
- 2 NEMA-17 stepper motors
- IR sensor

### Abstract :
The scanner works by rotating the object to be scanned , using the help of the stepper motors while taking distance measurements of the object using the IR sensor.
The collected data is then saved onto an SD card for post-processing. The output data is captured in [Point Cloud format](https://in.mathworks.com/help/vision/point-cloud-processing.html) which can be viewed using [Meshlab](https://www.meshlab.net) .

#### References : 
1. Sensor Datasheet : https://www.alldatasheet.com/view.jsp?Searchword=Gp2y0a21yk0f
2. Code built upon : https://github.com/SuperMakeSomething/diy-3d-scanner
