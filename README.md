# ONNI the Arduino based under water drone
> **Note:** This post is currently in the making and will include all CAD files and programes when finished.

This project involves the design and fabrication of a first prototype of a remotely operated, open-source, and affordable submersible drone.
It is designed to navigate in calm marine environments, such as lakes, and dive up to 10 meters deep.
Additionally, the idea is for it to be capable of collecting waste and transmitting certain information to the user, such as water temperature and pressure.
To achieve this, it is equipped with an onboard Raspberrypi camera providing a real time feed for the user as well as several other sensors and the addition of a robotic claw is currently in the design stage.
This project was proposed by my class mate and I as a one year academic project.

## Easy to controle

The drone is controlled using and game controller connected to a computer.
An interface is written in Python and is used to communicate with the drone.
For this purpose the computer is connected to the Arduino and the Raspberrypi using a modified RJ45 cable.

> **Note:** We currently have problems transmitting the video feed over long distances so this setup might change later on.

## Setup

The drone currently consists of the following parts:

- **Arduino DUE** as main controller
- **5 Brushless drone motors** with 3D printed propelors as the thrusters
- **5 quadcopteur ESCs** for controlling the motors
- **Raspberrypi Zero and camera module v2.1** for the video feed
- **MPU6050** as gyro
- **GY-MS5837** as external pressure and temp sensor
- **DHT11** as internal temp and humidity sensor
- **2 high power LEDs** as lighting for the camera in deep water
- **4000mAh 7.2V battery** as the main power supply
