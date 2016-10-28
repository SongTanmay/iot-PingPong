# iot-PingPong
This is a class project which is meant to explore internet of things

Circuit:

In this project, input is taken from [Flora 9DoF IMU](https://www.adafruit.com/products/2020). and output is shown on [7-Segment Display - 6.5" (Red)](https://www.sparkfun.com/products/8530). To connect seven segment to I have used [SparkFun Large Digit Driver](https://www.sparkfun.com/products/13279). Now, motion sensor gives three values(Accelerometer/Gyroscope/Magnetometer) around three axis(x/y/z) I have used accelerometer to determine the orientation on object.

Visualization:

Visualization is achieved by creating a cube with [threejs](https://threejs.org/). In previous project I have used interactive cubes build by webgl whereas here I am using simple geometrical triangles to create a face/square. Then with such six faces constructed cube.
