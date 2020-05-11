# MOTION TRIGGERED DPHOTOGRAPH
## 1 Introduction of project background
This is a security system that helps you find thieves who stole from you. It uses multisensor fusion technology, which uses motion and light sensors to capture the environment, and an executive-camera to capture the environment. The background of this project is that monitor assets with low power consumption and low memory. Normally, monitoring with a camera consumes a lot of memory and works continuously that cost energy.
To solve this problems, we start this project.We use motion detect sensor to sense the person passing through the door. If a person entering the door, the light sensor will decide whether there is sufficient light for a photograph and turn on or turn off the flashlight.Then the camera will capture five consecutive photos of the object and save all the photos on the folder chronologically. 
## 2 Hardwares
The hardwares we used in this project are follows,

- Motion sensor: PIR Motion Sensor (HC-SR501)

- Light Sensor: LM393

- Camera: Pi camera

- LED: As Flash light

- Botton: For interrupt
![image](https://user-images.githubusercontent.com/54963953/81525939-d6fd9600-9388-11ea-89d8-dd3ec6e05fa4.png)
## 3 Hardware circuit diagram
The real circuit diagram is shown in below.
![image](https://user-images.githubusercontent.com/54963953/81525985-f72d5500-9388-11ea-947b-2e9c5267a646.png)
## 4 Programming design
### 4.1 programming diagram
![图片1](https://user-images.githubusercontent.com/54963953/81526228-a1a57800-9389-11ea-9730-2cb75a1e5651.png)
### 4.2 part code of this project

1. Declare


2. Take photos (main)

![image](https://user-images.githubusercontent.com/54963953/81526317-da455180-9389-11ea-8f41-7d44a5e8eb09.png)
3. Stop the system

![image](https://user-images.githubusercontent.com/54963953/81526259-b8e46580-9389-11ea-907c-bedb6997177f.png)

## 5 Test

This system is tested by both in bright and dark enviroment and shows that it works well.
![image](https://user-images.githubusercontent.com/54963953/81526422-21334700-938a-11ea-8afb-ac0c942ce7de.png)





