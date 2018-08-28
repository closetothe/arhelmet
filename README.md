# AR HEADSET V2.0 #

This version of AR Headset allows for basic functionalities in a C++ environment
(V1 included basic demos in Python)

## Setup:
The `deps.sh` script will install system dependencies and the following libraries: 
	- Intel RealSense (legacy)
	- RTIMULib2
	- ncurses
	- OpenGL
	- OpenCV

*NOTE: The AR2 code has only been tested on an Odroid XU4.*

To install, run the following commands in the terminal:

```
git clone https://github.com/closetothe/ARHeadset2.git AR2
cd AR2
sudo -s
chmod 755 deps.sh
./deps.sh
```


=======

This version of AR Headset allows for basic functionalities in a C++ environment
(V1 included basic demos in Python)

>>>>>>> b8137ae73a6b56a39a326b8c044a2463a2366edc
## Hardware:
ODROID XU4, BNO055 IMU sensor, Intel RealSense R200, and a multitouch display

## Software: 
Ubuntu 16.04, Ubuntu MATE

## Libraries: 
TIMULib2, librealsense (legacy version 1), and standard C/C++ libraries including ncurses   

## Currently working:
      - Pre-calibrated BNO055  
      - Simple menu system to display data stream from BNO055  
        (including acceleration, gyro, euler, etc.)  


## Planned:  
      - Computer vision demo  
      - SLAM integration to computer vision  
      - 2D object detection  
      - Irrotational flow calculation on scanned 2D object  
      - Streamlines in AR  
