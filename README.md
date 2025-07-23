# TEMPARATURE-MONITORING-SYSTEM
COMPANY : CODTECH IT SOLUTIONS

NAME: SHAIK SHOUIB AKTHAR

INTER ID : CT08DF1355

DOMAIN : EMBEDDED SYSTEMS

DURATION: 8 WEEKS

MENTOR : NEELA SANTOSH

In the modern era of digital electronics and embedded systems, environmental monitoring plays a critical role in a wide range of applications—from home automation and weather forecasting to industrial process control and healthcare. One of the most commonly monitored environmental parameters is temperature, and microcontrollers like Arduino UNO offer a cost-effective and accessible way to build custom temperature sensing systems. The project discussed here is a Temperature Monitoring System implemented using an Arduino UNO board, a TMP36 temperature sensor, and a 16x2 I2C LCD module.This project aims to measure ambient temperature using a TMP36 analog temperature sensor and display the temperature value in real-time on an LCD screen. The system reads the analog voltage output from the sensor, converts it into a temperature value in Celsius, and continuously updates it on the LCD. Additionally, the temperature value is also printed to the serial monitor for debugging and observation purposes. The entire setup is simulated and tested using Tinkercad, a widely used online electronics simulation platform.Arduino UNO – The central microcontroller that processes data and controls output.TMP36 Temperature Sensor – An analog temperature sensor that provides voltage output linearly proportional to temperature.16x2 LCD with I2C Module – A display device to show the current temperature in readable format.Jumper Wires – To connect the components.Breadboard (optional) – Used for assembling the circuit, though not essential in this simulation.The Arduino sketch initializes the LCD and the serial monitor in the setup() function. In the loop() function, the analog input from the TMP36 is read, converted to voltage, and then to temperature. This value is displayed on the LCD using the LiquidCrystal_I2C library and printed to the serial monitor using Serial.println().During simulation on Tinkercad, the system successfully reads and displays the temperature values on both the serial monitor and the LCD. The readings fluctuate based on the simulated ambient conditions. For example, temperatures like 19.93°C, 67.00°C, and -33.09°C appear during runtime, which shows how the sensor interprets changing voltages.This temperature monitoring system can be adapted for a variety of real-world applications, such as:Home automation systems for climate control.Industrial safety systems to monitor overheating.Agricultural systems for greenhouse temperature monitoring.Weather stations for data collection.Student learning and embedded systems education.The temperature monitoring system using Arduino is a foundational project that introduces important concepts in analog sensing, microcontroller programming, and real-time data display. By combining a simple sensor like TMP36 with user-friendly modules such as the I2C LCD, users can create efficient and functional monitoring systems. It also builds a strong base for extending the system with features like data logging, threshold-based alarms, or wireless communication using modules like ESP8266 or Bluetooth. This hands-on experience not only demonstrates the power of embedded systems but also enhances understanding of practical electronics in a real-world scenario.

OUTPUT :

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/e6a544e6-a321-4121-8092-ca427bd39523" />
