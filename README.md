# Group-18
This is the GitHub page for our smartcar platform name _iCar_. We have explained different aspects of this platform and introduced various packages and software we have used to implement it. For any inquiries, feel free to contact the development team.

## What?
The _iCar_ is an interactive platform provides smart features for a virtual car to be controlled by the commands from the user and also send back some information about the surroundings, speed and travelled distance to the user through a communication channel.

The main functionality of the _iCar_ are as follows: 
* Control the car manually through the app
* Check the car surrounding by the camera feed 
* Automatically detects the obstacles and avoid them
* Provide messages to the user about the status of the connection between car and app

## Why?
The main objective of this software is to utilize and demonstrate the use of a real-time based embedded system in this case a functional user interface with the smart car emulator. One of our main goals is to implement a responsible GUI which can easily control all the functionality in the smart car emulator. Here we have also added practical based possible scenarios our system can go through. Some practical applications of this smartcart platform can be found in shopping malls when someone waits for his car to come and pick him up, semi-autonomous driving in which the driver needs to have an online meeting in the car and the car should find the least dangerous path to get to the destination.

## How?
We're working on two platforms, an Arduino car and a mobile application. For the Arduino car, we are going to create an Arduino sketch that holds the car's functions, and for the mobile application we are using Android Studio to create a simple UI. The communication between the car and the application will be easily done through MQTT broker in which the user _publish_ some commands through the App and the Arduino card _subscribe_ to those commands. Also, for some info like the camera feed and speed, this communication happens vice versa.

# Prerequisites

* Android device/emulator (Version: Android 9.0+)
* Android Studio preinstalled on your computer
* SMCE-gd preinstalled
* MQTT localhost preinstalled and running


# Milestones
* [Manual Control](https://github.com/gusallaar/iCar/wiki/Manual-Control)
* [Cruse Control](https://github.com/gusallaar/iCar/wiki/Cruse-Control)

# Get Started

## Downloads
* [MQTT Broker](https://mosquitto.org/download/)
* [Android Studio](https://developer.android.com/studio)
* [SMCE](https://github.com/ItJustWorksTM/smce-gd/releases)

## Clone
* Get the Group 18 repository to your computer

## SMCE
* Once downloaded, start the SMCE-Godot application and press “Start Fresh” then press“+” to add a new sketch.
* Open the file smarcar.ino file found at group-18/arduino/smartcar/smartcar.ino and select the sketch.
* Compile the arduino file and press “Start”
## Android Studio
* In Android studio’s welcome screen, press “open” and then choose SmartCarApp from group-18 folder found at group-18/SmartCarApp
* Build the project by clicking on the green hammer icon or by pressing CTRL+F9.
* Click on Tools > Device Manager. Click on “Create device” then on “New Hardware Profile” set the screen size to 6,53 inch and the resolution to 1080 x 2340 and ram to 1.53 GB. Press “finish”
* Run the app with the created device

## Mosquitto
* Open a command prompt in the mosquitto directory
* Start the MQTT broker locally by using the command _net start mosquitto_


# Development Team
Arezoo Allahyari (gusallaar@student.gu.se)

