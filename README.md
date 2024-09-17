# Breathalyzer


This project implements a simple alcohol detection device using a gas sensor (MQ-3), a buzzer, and an LCD screen. The device measures the blood alcohol concentration (BAC) in a person's breath and provides a visual and audible alert if the alcohol level exceeds a certain threshold.

Project Overview
Purpose: The breathalyzer project detects alcohol in a user's breath, calculating the BAC (Blood Alcohol Concentration) and determining whether the person is "Normal" or "Drunk" based on the reading.
Components Used:
MQ-3 Alcohol Sensor: Detects the alcohol content in the breath.
LCD Screen (16x2): Displays the BAC reading and the status ("Normal" or "Drunk").
Buzzer: Sounds an alarm if the BAC exceeds a safe threshold.
Features
Calibration Process: At startup, the device runs a calibration process to ensure accurate readings.
BAC Calculation: The alcohol concentration is displayed in mg/L on the LCD screen.
Visual and Audible Alerts:
If the BAC exceeds 0.8 mg/L, the device triggers a "Drunk" message on the LCD screen and sounds the buzzer.
If the BAC is within the safe limit, it displays "Normal" on the screen.
Usage
Once powered on, the device automatically calibrates itself.
After calibration, the user can blow on the alcohol sensor.
The BAC is displayed on the screen, and an alert is provided based on the reading.
For a detailed look at the code and how the project works, please refer to the PDF file that contains the complete source code and an explanation of the implementation.
[Breathalyzer_compressed.pdf](https://github.com/user-attachments/files/17028838/Breathalyzer_compressed.pdf)
