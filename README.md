# U TURN ACCIDENT-PREVENTION-SYSTEM-USING-ARDUINO-UNO

# Introduction
There has been an alarming rise in road accidents, significantly U-Turn accidents, in Bangladesh over the past few years. The U-Turn remains one of the most dangerous driver strategy on roads worldwide. We all know U-turns are illegal most of the time - drivers are putting their own lives and the lives of other road users at serious risk when doing so at the wrong place and in the incorrect manner. In this section we want to focus on the U-Turn in an attempt to create awareness that could prevent many further crashes.
Here is an automated Internet of Things (IoT) based U-Turn accident prevention system.

# Novelty of the System
The U-turn accident detection system is innovative because it focuses on detecting accidents specifically related to U-turn maneuvers. It employs unique algorithms and integrates with vehicle sensors to identify U-turn collisions accurately. Upon detection, it triggers immediate alerts to warn drivers and others, potentially suggesting preventive actions. The system also accumulates data for safety insights and has the potential to integrate with autonomous driving technology for enhanced accident prevention. Overall, it offers a targeted approach to improving road safety by addressing a specific type of accident. Hence , the driver will become cautious while driving.

# Components Required
1. Arduino Uno
2. Jumper Wires
3. Motion Sensor
4. Breadboard (generic)
5. 5 MM LED : Green
6. 5 MM LED : Red

# Circuit Diagram
![image](https://github.com/Sushmoy-Nandi/ACCIDENT-DETECTION-SYSTEM-USING-ARDUINO-UNO/blob/main/Circuit%20Diagram.png)


# Operation
### CASE 1:
Whenever vehicle comes from right side then the IR sensor senses the vehicle and gives signal to arduino then 
arduino makes Red LED will glow to the opposite side of the U-turn in order to alert the 
driver. This will reduce accidents on the curved roads.
### CASE 2:
Whenever vehicle comes from left side then the IR sensor senses the vehicle and gives signal to Arduino then 
Arduino makes Red LED will glow to the opposite side of the U-turn in order to alert the 
driver. This will reduce accidents on the curved roads.

# FlowChart
![image](https://github.com/Sushmoy-Nandi/U-TURN-ACCIDENT-PREVENTION-SYSTEM-USING-ARDUINO-UNO/blob/main/Flow%20Chart.png)

![image](https://github.com/Sushmoy-Nandi/U-TURN-ACCIDENT-PREVENTION-SYSTEM-USING-ARDUINO-UNO/blob/main/Codeflow.svg)

# These connections have to make in the Arduino UNO (according to the code)
1. Hook the GND pin (Negative Pin) of all led to Pin GND of Arduino.
2. Connect Motion Sensor Pin (Positive Pin) to Pin 3 of Arduino.
3. Connect Red LED VCC Pin (Positive Pin) to Pin 7 of Arduino.
4. Connect Green LED VCC Pin (Positive Pin) to Pin 8 of Arduino.
   
![image](https://github.com/Sushmoy-Nandi/U-TURN-ACCIDENT-PREVENTION-SYSTEM-USING-ARDUINO-UNO/blob/main/Picture%2001.jpg)
![image](https://github.com/Sushmoy-Nandi/U-TURN-ACCIDENT-PREVENTION-SYSTEM-USING-ARDUINO-UNO/blob/main/Picture%2002.jpg)

# Project details
This project was developed during the 3rd semester while pursing B.Sc. in CSE of 2024 as part of the CSE-2113: Digital Electronics and Pulse Techniques Lab Course conducted by the National Institute of Textile Engineering and Research-NITER, Constituent Institute of the University of Dhaka, Savar, Dhaka-1350
# Future Work
We can use an alarm system and GPS technology to call the nearest police station and hospital in case of an accident and also alert them of the severity of the accident.

# Contributors
We'd like to give credit to the following contributors who have helped in the development of this project:

![image](https://github.com/Sushmoy-Nandi/U-TURN-ACCIDENT-PREVENTION-SYSTEM-USING-ARDUINO-UNO/blob/main/Contributors.png)

Last Updated 11 May, 2024




  



