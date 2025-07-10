# blipo_robotic_arm
This repository contains the control files for the Yahboom Jetcobot 7, a robotic arm powered by the Jetson Orin Nano. Blipo is a programmable 6 DOF robotic arm designed to work with ROS.

## Affiliations
This repository was published as part of a Capstone Deaign Course project sponsered in the [Intelligent Dynamics and Control Lab](https://ucalgary.ca/labs/intelligent-dynamics-control-lab), [Department of Mechanical and Manufacturing Engineering](https://schulich.ucalgary.ca/mechanical-manufacturing), Schulich School of Engineering, University of Calgary, under the supervision of [Dr. Mahdis Bisheban](https://profiles.ucalgary.ca/mahdis-bisheban). 

The Lab is directed by Dr. Mahdis Bisheban. For more research and open-source contributions, please visit [IDCL Lab GitHub page](https://github.com/IDCL-UCalgary)

## Contributors
- Joshua Gall
- Paula Vilamil
- Danika Bartell
- Doohyeon Kim
- Victoria Son
- Yaohui Liu
- Sponsored and Supervised by Dr. Mahdis Bisheban
- Advised by Dr. Marie Charbonneau


## Project Overview
The goal of the project is to control the arm and perform contact-based inspections. Based on camera feedback, the arm will move to the desired location and use depth sensing to bring the end effector into contact with the surface. 

## Features
- **ROS**: Blipo is fully integrated with ROS for control.
- **Camera Control**: The system uses vision for precise targeting

## Requirements 
- Jetson Orin Nano with Ubuntu 20.04 LTS
- ROS installed (Noetic)
- Yahboom Jetcobot 7 hardware

## Acknowledgments

This project is based on the **Yahboom Jetcobot 7**, which is powered by the **Jetson Orin Nano**. For the official documentation and additional resources, please visit the [Yahboom Jetcobot 7 GitHub repository](https://github.com/YahboomTechnology/JetCobot).

The code and setup provided in this repository build upon Yahboom's original work and extend its functionality for specific control and camera integration using ROS.
