---
title: " Smart Motion Detection System with ESP8266 and Blynk Integration"
description: "How we built this project using ESP8266 microcontroller, PIR motion sensor, LED, Blynk App"
dateString: Oct 2024
draft: false
tags: ["Sensors", "PIR", "Arduino", "Developer","Blynk","ESP8266","LED"]
weight: 102
cover:
    image: "/blog/PIR.png"
---

# Credentials
### 🔗 [Documentation](https://www.linkedin.com/posts/abdullah-nazmus-sakib-04024b261_project-smart-motion-detection-system-with-activity-7259044327761289216-TW3b?utm_source=share&utm_medium=member_desktop)


### 🎬 [Video](https://www.linkedin.com/posts/abdullah-nazmus-sakib-04024b261_project-smart-motion-detection-system-with-activity-7259044327761289216-TW3b?utm_source=share&utm_medium=member_desktop)

# Project Description
This project demonstrates a simple yet effective motion detection system using an ESP8266 microcontroller, a PIR motion sensor, and an LED, with real-time monitoring and control via the Blynk IoT platform. This system can be useful in home automation, security applications, and any project where motion detection and notification are needed.

# Project Overview:
 • Components Used:
 • ESP8266: A WiFi-enabled microcontroller used to connect to the Blynk app and manage the PIR sensor and LED.
 • PIR Motion Sensor: Detects motion within a range and sends a signal to the ESP8266.
 • LED: Visual indicator to signal detected motion.
 • Blynk App: Allows real-time monitoring of the sensor’s status, logging data, and provides an interface for remote viewing.

# How the Code Works:

 1. Setup:
 • The code initializes the PIR sensor on pin D1 (GPIO 5) and the LED on pin D2 (GPIO 4) of the ESP8266.
 • The device connects to WiFi using the provided credentials and establishes a connection to the Blynk cloud using the unique Blynk authentication token.
 2. Motion Detection:
 • The pirSensorControl() function reads the PIR sensor’s state. If motion is detected, it turns on the LED, sends the motion status to Blynk (V1), and logs it to the serial monitor.
 • If no motion is detected, the LED is turned off, and the status update is sent to Blynk.
 3. Blynk Connectivity:
 • A timer function (myTimerEvent()) runs every second to send the device’s uptime to Blynk, displayed on Virtual Pin V2.
 • The data sent to Blynk allows users to monitor motion status and device uptime remotely through the Blynk app.
 4. Real-Time Monitoring:
 • Blynk provides a live interface to track the motion detection status, which is updated instantly when the PIR sensor detects motion. The app shows “ON” for detected motion and “OFF” for no motion.


# Applications:
 • Home Security: Alerts users to unauthorized movement in specific areas.
 • Smart Home Automation: Triggers lights, cameras, or other devices when motion is detected.
 • IoT Monitoring: Blynk integration allows remote access and logging, making it a powerful solution for smart environments.

# Conclusion
This project showcases the integration of IoT with basic motion detection for real-time, remote monitoring, making it ideal for security and automation needs. By leveraging the ESP8266 and Blynk, this project is simple to deploy and enhances the convenience and accessibility of smart home systems.

### Source Code : https://lnkd.in/gqMT7wgT

Group_06(Debashis Dhali SHAH SULTAN Abu Hurraira Abid)

Edge IOT_And_Robotics_IIT_JU
Instructor : Redwan Ferdous, PRINCE2®, CSCM™