# Parking Space Management System

## Abstract
In metropolitan cities like Mumbai, the growing population, industrialization, and mismanagement of parking spaces contribute to a significant parking issue. Our project addresses this problem by providing a digital platform to inform users about the availability of parking slots, reducing the time and effort spent on finding parking spaces. The system utilizes ultrasonic sensors to detect the presence of cars, informing users about slot availability, and calculating fare based on the duration of parking.

## Problem Definition
The surge in population growth and car ownership has led to a parking crisis in metropolitan areas. Finding parking spots, especially in prime locations, has become challenging. The unpredictable availability of free parking slots has created a common issue in cities like Mumbai, necessitating an efficient solution.

## Scope
The proposed system aims to automate and manage parking slot availability, informing users about vacant or occupied slots. By reducing manual intervention, the system enhances efficiency and user experience. It calculates fare based on parking duration, providing a comprehensive digital platform.

## Proposed System Features
1. Utilizes ultrasonic sensors to detect car presence in parking slots.
2. Informs users about the availability of specific parking slots.
3. Checks for slot availability every 5 seconds.
4. Calculates fare based on the duration of car parking.

## Objectives
1. Automate the car parking system at prime locations.
2. Regulate traffic flow by providing information on empty parking slots.
3. Digitize transactions and provide fare information.

## Issues/Limitations
1. Ultrasonic sensors may detect metallic bodies, leading to false bookings.
2. Limited sensing range of ultrasonic sensors may require multiple installations.
3. Fare calculation is not displayed at the user's end (future integration with an app).

## Hardware
- Raspberry kit
- LED
- Ultrasonic sensor HC-SR04
- Resistors and jumper wires
- Breadboard

## Software
- NOOBS
- VNC server and VNC Viewer
- Python IDE

## Algorithm
1. Trigger the ultrasonic sensor to send and receive waves.
2. Calculate the distance based on the reflected wave.
3. Check if the parking slot is occupied.
4. If unoccupied, print the status and start the timer.
5. Calculate the time difference if the slot becomes occupied again.

This project aims to revolutionize parking space management, providing real-time information to users and contributing to the optimization of urban parking.
