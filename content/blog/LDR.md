---
title: "Automated Light Control using an LDR Sensor with Arduino"
description: "How we built this project using Arduino, LDR sensor, LED"
dateString: July 2024
draft: false
tags: ["Sensors", "LDR", "Arduino", "LED"]
weight: 104
cover:
    image: "/blog/LDR.jpeg"
    # caption: "A sample landmark detection on a photo by Ayo Ogunseinde taken from Unsplash"
---

# Credentials
### 🔗 [Documentation](https://www.linkedin.com/posts/abdullah-nazmus-sakib-04024b261_project-automated-light-control-using-an-activity-7256946429275889667-7RAz?utm_source=share&utm_medium=member_desktop)



### 🎬 [Video](https://www.linkedin.com/posts/abdullah-nazmus-sakib-04024b261_project-automated-light-control-using-an-activity-7256946429275889667-7RAz?utm_source=share&utm_medium=member_desktop)

# Project Description 
This project demonstrates a basic automated light control system using an Arduino, a Light Dependent Resistor (LDR), and an LED indicator. The goal is to use ambient light levels to automatically control a light source, which could be applied in streetlights, home automation, or energy-saving lighting systems.

# Project Overview 
  Hardware Components: Arduino, LDR (Light Dependent Resistor), and an LED (or external light).
  Functionality: The LDR sensor reads the ambient light intensity and adjusts the LED’s state based on a predefined threshold. When the light level falls below a specified threshold, the LED turns on, simulating an automatic light that activates in low-light conditions.

# How it works
 • The LDR provides an analog value representing the ambient light level.
 • The Arduino continuously monitors this value; when it drops below 5 (indicating low light), it turns the LED on. Otherwise, the LED remains off.
 • This control is achieved with simple condition checks and a feedback delay for optimal performance.

# Application 
This project is scalable to develop automated lighting systems for homes, streetlights, or other settings where responsive lighting is needed, helping to improve energy efficiency by minimizing unnecessary light usage.



### source code : https://lnkd.in/gE8S_gj7

IOT_JU_Group_06_(Debashis Dhali, SHAH SULTAN, Abu Hurraira Abid)
Edge IOT and Robotics course
Instructor: Redwan Ferdous, PRINCE2®, CSCM™
