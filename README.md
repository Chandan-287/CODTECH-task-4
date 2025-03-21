# CODTECH Internship – Task 4

Name: Chandan A  
Company: CODTECH IT Solutions Pvt. Ltd.  
ID: CT6WTWE  
Domain: Embedded Systems  
Duration: February 20th, 2025 – April 5th, 2025  
Mentor: Neela Santhosh Kumar  

# Project Title  
Speech Recognition System Using Arduino  

# Project Overview  
The Speech Recognition System uses voice commands to control electronic devices.  
It integrates an Arduino Uno microcontroller with a speech recognition module to recognize pre-defined voice commands and trigger specific actions, such as turning on/off an appliance or activating a motor.  

# Key Features  
1. Voice-Controlled System  
   - Responds to pre-defined speech commands.  
2. Multiple Device Control  
   - Controls multiple devices based on different commands.  
3. Real-Time Operation  
   - Immediate response to recognized speech.  
4. LED Indicator and Relay Activation  
   - LEDs show device status, and relays switch appliances on/off.  

# Components Used  
- Microcontroller: Arduino Uno  
- Speech Recognition Module: Elechouse Voice Recognition V3  
- Relay Module: For switching devices  
- LED Indicators: To show device status  
- Power Supply: 5V  
- Breadboard and Jumper Wires  

# Working Principle  
1. The speech recognition module captures the voice command.  
2. The module processes the speech and sends a digital signal to the Arduino Uno.  
3. The Arduino decodes the command and performs the corresponding action:  
   - Turns appliances on/off.  
   - Activates/deactivates motors or LEDs.  
4. The LED indicator shows the current status of the device.  

# Applications  
- Smart Home Automation  
   - Voice-controlled lights, fans, and appliances.  
- Assistive Technology  
   - Hands-free device control for individuals with disabilities.  
- Robotics and Automation  
   - Control robotic movements through speech commands.  

# How to Run  
1. Assemble the Circuit  
   - Connect the Arduino, speech recognition module, and relay module according to the circuit diagram.  
   - Ensure proper power supply and connections.  

2. Upload the Code  
   - Use the Arduino IDE to upload the `.ino` file.  

3. Train the Speech Module  
   - Record and save pre-defined voice commands.  
   - Test the module with voice commands.  

4. Power the System  
   - Power the Arduino with a 5V supply or USB connection.  
   - Use speech commands to control the devices.  

# Troubleshooting  
1. Speech Commands Not Recognized  
   - Ensure the module is properly trained.  
   - Speak clearly and close to the microphone.  

2. No Response from Appliances  
   - Verify relay wiring and power connections.  
   - Check the Arduino serial monitor for debugging.  

# Contributing  
Contributions are welcome!  
If you have any improvements or bug fixes, feel free to fork the repository and submit a pull request.  

![Working model](https://github.com/user-attachments/assets/43af1869-8b79-4c34-a5e9-c015368ab4f5)
