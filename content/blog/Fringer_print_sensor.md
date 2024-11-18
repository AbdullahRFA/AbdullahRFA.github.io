---
title: "Advanced Fingerprint-Based Authentication System with LED Indication and User Identification"
description: "How We developed this project using fringer print sensor, arduino?"
dateString: Nov 2024
draft: false
tags: ["Sensors", "Fringer_Print", "Arduino", "Developer"]
weight: 101
cover:
    image: "/blog/fringer_print_sensor.jpeg"
---

# Credentials
### 🔗 [Document](https://www.linkedin.com/posts/abdullah-nazmus-sakib-04024b261_iotabrandabrroboticsabriitabrju-activity-7261398084578869249-0jTr?utm_source=share&utm_medium=member_desktop)



### 🎬 [Video](https://www.linkedin.com/posts/abdullah-nazmus-sakib-04024b261_iotabrandabrroboticsabriitabrju-activity-7261398084578869249-0jTr?utm_source=share&utm_medium=member_desktop)

# Project Description:
This project demonstrates an advanced fingerprint-based security and authentication system using the Adafruit optical fingerprint sensor and Arduino, which ensures high security and convenience through biometric authentication. The project was built with multiple core functions, including fingerprint enrollment, user identification, and visual feedback through LED indicators for access validation.


# Key Features:

 1. Fingerprint Enrollment and Matching: The system allows for enrolling fingerprints with unique IDs, storing up to 127 fingerprints. Once enrolled, users can authenticate by placing their finger on the sensor, and the system will identify the user by matching their fingerprint with stored templates.
 2. Access Control and Visual Feedback:
 • Green LED for Successful Authentication: Upon successful authentication, the green LED lights up, indicating access is granted.
 • Red LED for Denied Access: If the fingerprint is not recognized, the red LED lights up, signaling that access has been denied.
 3. Detailed User Identification: The system is configured to recognize specific fingerprints and output the associated user names. For example, upon recognizing a fingerprint ID, the system identifies and prints the user’s name, such as “Debashis,” “Shanto,” or “Abdullah,” enhancing user interaction.
 4. Error Handling: The system includes error handling for various scenarios, such as communication errors, imaging errors, and unmatched fingerprints. This ensures reliable and accurate functionality, even in cases where the fingerprint may be difficult to read.





# Technical Highlights:

 • Hardware: Built using Arduino and an Adafruit optical fingerprint sensor, connected via Serial communication. The SoftwareSerial library is used for compatibility with various microcontrollers.
 • Software: Designed using C++ on the Arduino IDE, the code handles fingerprint scanning, image processing, and template matching using the Adafruit Fingerprint library.
 • User Feedback: Integrates two LEDs to indicate the status of each authentication attempt, providing an intuitive visual response for the user.


# Potential Applications:
This project serves as a foundation for secure access systems in residential, commercial, and industrial environments where authentication security is a priority. It can be applied to doors, safes, or restricted areas, offering both personal and enterprise-level security solutions.

### Source code for user indentification: https://lnkd.in/gQj-utgN
### Source code for user fringer print string: https://lnkd.in/gHE8wZAr

Group-06(Debashis Dhali SHAH SULTAN Abu Hurraira Abid)
Instructure : Redwan Ferdous, PRINCE2®, CSCM™
Edge hashtag#IOT_AND_ROBOTICS_IIT_JU


