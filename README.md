# picoML
**TinyML Implementation using Raspberry Pi Pico: Geometry Gesture Detection**
A simple & Tiny Machine Learning algorithm to detect three different types of geometry: Circle, Square, and Triangle using Raspberry Pi Pico are implemented and demonstrated in this blog. A low-cost accelerometer ADXL335 with three-axis (x,y,z) analog output is used to detect the motion. The TinyML model is implemented using Edge Impulse Studio with Google TensorFlow support at the backend. Finally, the model is deployed using Edge Impulse’s C++ SDK and build using GCC Arm Compiler in Visual Studio code platform.
The source folder contains the main.cc file designed for Raspberry Pi Pico RP-2040. It is successfully tested and compiled using VS code-2019 version in Windows-10 Platform with CMake V3.19.
The CMake configuration is written in the CMakeLists.txt<br />
<br />
Full project is available here:<br />
**Part-01: Data collection and Model Training**<br />
https://medium.com/@subirmaity/tinyml-implementation-using-raspberry-pi-pico-geometry-gesture-detection-part-i-3f0717677561<br />
**Part-02: Hardware Implementation**_
https://medium.com/@subirmaity/tinyml-implementation-using-raspberry-pi-pico-geometry-gesture-detection-part-ii-d3d83a5d8cdb<br />
