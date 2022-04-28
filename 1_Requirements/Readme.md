# Distance Measurement

## What is Ultrasonic sensor
* Ultrasonic sensor is a tool that measures distance to an object using ultrasonic sound waves.
*  The ultrasonic sensor uses a transducer to send and receive ultrasonic pulses that relay information about the proximity of an object. 
*   High-frequency sound waves reflect from boundaries to produce distinct echo patterns.
### How Ultrasonic sensor works
 Ultrasonic sensors operate by sending sound waves at a frequency greater than the human hearing range. The sensor transducer acts as a microphone to receive and transmit ultrasonic sound. Our ultrasonic sensors, like many others, use a single transducer to transmit heart rate and echo. The sensor determines the distance to the target by measuring the time between sending and receiving the ultrasonic pulse.
The working principle of this module is simple. It sends an ultrasonic pulse out at 40kHz through the air and if there is an obstacle or object, it will jump back into the sensor. By calculating travel time and sound speed, distance can be calculated. Ultrasonic sensors are a good solution for the detection of clear objects. By measuring the liquid level, applications that use infrared sensors, for example, struggle with this specific use due to the directed light. In order to detect presence, ultrasonic sensors detect objects regardless of color, surface, or material (unless the material is as soft as wool, as it can absorb sound.
## Components Required
## Components
Hardware: ATmega328, Power supply (5v), LCD hd_44780_E, 1KΩ resistor (pieces) , HC-SR04 sensor.
* Atmega328 :-The ATMEGA328P-PN is a popular microcontroller due to it being a major component in the Arduino board products. The ATMEGA328P-PN is the 8-bit RISC heart of the Arduino Uno and Nano, with a maximum clock frequency of 20MHz, 32KB program FLASH, and 2KB of RAM.
* Power Supply(5v):- its an fixed voltage to tigger potentiometer.
* Resistor :-  A resistor is a passive two-terminal electrical component that implements electrical resistance as a circuit element. In electronic circuits, resistors are used to reduce current flow, adjust signal levels, to divide voltages, bias active elements, and terminate transmission lines, among other uses.
* HC-SR04 sensor :- The HC-SR04 Ultrasonic Distance Sensor is a sensor used for detecting the distance to an object using sonar. It's ideal for any robotics projects your have which require you to avoid objects, by detecting how close they are you can steer away from them!

Software : Vscode(code editor with support for development operations like debugging, task running, and version control) ,Simulide( for simulation of circuit).


## SWOT Analysis
### Strengths
*   It has higher sensing distance (in centimeters and inches) compare to inductive/capacitive proximity sensor types.
*   It has sensing capability to sense all the material types.
*   This sensor is not affected due to atmospheric dust, rain, snow etc.
*   It can work in any adverse conditions.

### Weaknesses
*   It has more difficulties in reading reflections from soft, curved, thin and small objects.
### Opportunities
*   They have greater accuracy than many other methods at measuring thickness and distance to a parallel surface.
*   Their high frequency, sensitivity, and penetrating power make it easy to detect external or deep objects.
### Threats
*   Limited testing distance
*   Inaccurate readings
*   Inflexible scanning methods
### 4W's and 1'H 
*   Who :The importance of the project is calculating accurate distance from any obstacle that we want to measure. Ultrasonic sensors are used primarily as proximity sensors. They can be found in automobile self-parking technology and anti-collision safety systems.
*   What :As the name indicates, ultrasonic sensors measure distance by using ultrasonic waves. The sensor head emits an ultrasonic wave and receives the wave reflected back from the target. Ultrasonic Sensors measure the distance to the target by measuring the time between the emission and reception.
*   When :Ultrasonic sensors can measure the distance to a wide range of objects regardless of shape, color or surface texture. They are also able to measure an approaching or receding object. By using “non-contact” ultrasonic sensors, distances can be measured without damage to the object.
*   Where :The device can be used in many different fields and categories like distance calculation in construction field, robots, car sensor to avoid obstacles and many other applications.
*   How :Ultrasonic sensors are useful for measuring distances. Ultrasonic waves are transmitted and whenever these strike an obstacle and return back in the from of an echo. Difference of outgoing sound and returning echo gives us the distance.
### Requirements
### High Level Requirement
| ID | Description | Status |
| ----- | ----- | ----- |
| 1. | The high-level signal is sent to 10 microseconds using Trigger | Implemented |
| 2. | The module sends 40 KHz signals automatically and then detects whether the pulse is received or not through Echo| Implemented |
| 3. | Capable of measuring a distance of up to 400 cm| Implemented |
| 4. | It can be further enhanced by implementing improvements especially in its accuracy and portability | Future |
### Low Level Requirements
| ID | Description | Status |
| ----- | ----- | ----- |
| 1. | Suitable for close range detection up to ten meters | Implemented |
| 2. | Provide multiple range measurements per second| Implemented |
