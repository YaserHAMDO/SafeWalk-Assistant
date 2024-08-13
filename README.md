# Smombie Safety System

## Overview
The Smombie Safety System is a prototype designed to protect people who use their phones while walking.<br>
The system uses an Arduino microcontroller, HC-06 Bluetooth module, ultrasonic sensors, and vibrations in headphones, all connected to an Android app.<br>
This project aims to ensure user safety by alerting them through notifications and vibrations when they approach obstacles or people.

## Techniques Used

- Arduino UNO<br>
- Android Studio<br>
- Bluetooth Communication (HC-06)<br>
- Electronic Components: Ultrasonic Sensors, Vibration Motors in Headphones and Battery.

## Key Features

-**Obstacle Detection:** The system detects obstacles in all directions (front, back, left, right). When an obstacle is detected, the app sends a notification to the user, and the headphones vibrate to indicate the direction of the obstacle.<br>

-**Directional Vibration Feedback:**- **Front:** Both headphones vibrate simultaneously.
  - **Back:** Both headphones vibrate with a different tune.
  - **Left/Right:** The corresponding headphone vibrates.

-**Social Distance Mode:** This mode ensures the user maintains a safe distance (around 2.5 meters) from others in crowded places. The system checks all directions and alerts the user via the app and vibrations.<br>

-**Bluetooth Connectivity:** The system connects to the Android app via Bluetooth, ensuring real-time communication between the phone and the safety system.



## How It Works
The system continuously monitors the user's surroundings using ultrasonic sensors.
When an obstacle is detected within a certain range, the system triggers an alert on the user's phone and provides vibration feedback through the headphones, guiding the user to avoid the obstacle.<br>
In crowded environments, the social distance mode ensures that the user maintains a safe distance from others, helping to prevent close contact, which can be crucial during pandemics.<br>


## Images

System Hardware Images:<br>

<p align="left">
  <img alt="f" src="https://github.com/user-attachments/assets/81b74a2b-c2c5-4060-a39d-b6e05604a6ce" width="60%">
</p>
&nbsp;
&nbsp;

<p align="left">
  <img alt="f" src="https://github.com/user-attachments/assets/3a1c2331-3a51-49f0-8bfb-3fb192d1abfd" width="60%">
</p>
&nbsp;
&nbsp;


Android App Screenshot:
<p align="left">
  <img alt="screenshot" src="https://github.com/user-attachments/assets/c15e7c34-dc56-46e2-8646-14154ed22325" width="30%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="screenshot" src="https://github.com/user-attachments/assets/007c9e0a-bc66-4cd7-a23f-67f489db9294" width="30%">
</p>
&nbsp;
&nbsp;

<p align="left">
  <img alt="screenshot" src="https://github.com/user-attachments/assets/2c695e25-92a3-4b47-9485-a1bf6e52aa5b" width="30%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="screenshot" src="https://github.com/user-attachments/assets/e7f435af-db68-4752-9241-aaf02c851f7b" width="30%">
</p>
&nbsp;
&nbsp;


## Video Demonstration
You can watch a video demonstration of the Smombie Safety System [here.](https://drive.google.com/file/d/1r93dUeUha8gNAYmgf3ZZCbwWyLJU6i1X/view?usp=sharing)


