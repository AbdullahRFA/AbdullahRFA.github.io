---
title: "Sequential Relay Control for Device Automation"
description: "How we built this project using Relay MOdule, AC Motor "
dateString: Sep 2024
draft: false
tags: ["Sequential", "Relay", "Arduino", "Control","Automation","AC_Motor","Motor"]
weight: 103
cover:
    image: "/blog/relay.jpeg"
---

# Credentials
### 🔗 [Documentation](https://www.linkedin.com/posts/abdullah-nazmus-sakib-04024b261_project-sequential-relay-control-for-device-activity-7258117049250381824-qbad?utm_source=share&utm_medium=member_desktop)



### 🎬 [Video](https://www.linkedin.com/posts/abdullah-nazmus-sakib-04024b261_project-sequential-relay-control-for-device-activity-7258117049250381824-qbad?utm_source=share&utm_medium=member_desktop)

# Project Description
This project demonstrates how to control four relays in sequence using a microcontroller. Relays are commonly used to control high-power devices with low-power control signals from microcontrollers like an Arduino. In this project, each relay is connected to a designated digital pin and activated one at a time in a set sequence, making it ideal for applications that need staggered control of multiple devices.

# Project Overview
### Components Used:
 1. 4 Relays: Each relay controls an electrical device connected to the system.
 2. Microcontroller (e.g., Arduino): Sends digital signals to control the relay states.
 3. Relay Pins Setup:
 4. Relay 1: Controlled by pin 3
 5. Relay 2: Controlled by pin 4
 6. Relay 3: Controlled by pin 5
 7. Relay 4: Controlled by pin 6

 # Working Principle of Relays:
 ### Relay Structure:
 1. A relay is an electrically operated switch that uses an electromagnet to mechanically switch a circuit on or off.
 2. When a low voltage signal is sent to the relay’s input pin (from a microcontroller), it activates the electromagnet within the relay, closing or opening its contacts to control a high-power circuit.
 ### Relay Types:
 1. The relays in this project are typically normally open (NO) relays, meaning the circuit they control is open by default and closes when the relay is activated (relay pin set to LOW).
 2. The relay is turned “on” by setting the digital pin to LOW, and it is turned “off” by setting the pin to HIGH.


# How the Code Works:
 ### Setup:
 1. Each relay is defined with a digital pin (3 to 6), and all are configured as outputs.
 2. In the setup function, all relays are set to HIGH to ensure they start in the “off” position.
 ### Loop:
 1. The loop sequentially activates each relay:
 2. Relay 4 is activated (set to LOW) while others remain off, and then turned off (set to HIGH) after 2 seconds.
 3. Relay 3 follows the same process, turning on for 2 seconds, then off.
 4. Relay 2 activates next for 2 seconds, then turns off.
 5. Relay 1 stays on for a longer period of 10 seconds before turning off.
 6. This sequence can control devices like lights, motors, or pumps in a timed pattern.

# Applications:

 ### Automation Systems: 
 The staggered activation is useful for systems that require sequential operation of different devices, such as conveyor systems, irrigation systems, or even home automation.
 ### Timing Control: 
 The code can serve as a timer-based control mechanism where devices need to activate in a specific order.

 # Conclusion
 This project provides an introduction to relay control, enabling the microcontroller to handle high-power devices safely and effectively.

### source code: https://lnkd.in/gGFymeKa

Group-06(Debashis Dhali.SHAH SULTAN, Abu Hurraira Abid)

Edge IOT and Robotics course
Instructor: Redwan Ferdous, PRINCE2®, CSCM™

