# Smart-Parking-System

The Smart Car Parking System is an automated solution designed to manage parking spaces efficiently using Arduino Uno, Servo Motors, LEDs, Ultrasonic and IR sensors. This system aims to simplify the process of parking by detecting available spaces and controlling entry barriers, providing a seamless parking experience. The system is implemented using the Arduino IDE and the hardware components are integrated to create a functional and intelligent parking management system.

## Components

- Arduino Uno: The central microcontroller used to control the system.
- Servo Motors: Used to control the barriers at the entrance and exit of the parking lot.
- Ultrasonic Sensors: Used to measure distances and detect the presence of vehicles at the entrance and exit.
- IR Sensors: Used to detect the presence of cars in individual parking spaces.
- LEDs: Indicate the status of the parking spaces (optional for visual feedback).

## Functionality

### 1. Distance Measurement
The system uses two ultrasonic sensors to measure the distance of vehicles at the entrance and exit of the parking lot. The trigPin1 and echoPin1 are used for the entrance, while trigPin2 and echoPin2 are used for the exit.

### 2. Servo Motor Control
Servo motors are used to control the barriers at the entrance and exit. The servo attached to servoPin1 controls the entrance barrier, and the servo attached to servoPin2 controls the exit barrier. The barriers open and close based on the distance measurements from the ultrasonic sensors.

### 3. Parking Space Detection
The system uses three IR sensors connected to analog pins A0, A1, and A2 to detect the presence of cars in three parking spaces. The sensors provide digital signals indicating whether a parking space is occupied or vacant.

### 4. Occupancy Management
The system keeps track of the number of occupied parking spaces using counters count1, count2, and count3. These counters are incremented or decremented based on the signals from the IR sensors.

## Conclusion

The Smart Car Parking System provides an efficient and automated way to manage parking spaces. By utilizing ultrasonic sensors, IR sensors, and servo motors, the system can detect available parking spaces and control barriers, enhancing the parking experience. This project showcases the integration of various hardware components with Arduino to create a functional and intelligent system.
