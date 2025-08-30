# Distance-sensor-Arduino
This beginner project uses an ultrasonic sensor connected to an Arduino UNO to measure the distance between the sensor and an object. If the object is closer than 20 cm, an LED turns on as an alert signal.

  Project Preview

![Project Image](arduino%20uno.png)
---
Components Used
- Arduino UNO  
- Ultrasonic Sensor (PING)))  
- LED  
- 220Ω Resistor  
- Breadboard  
- Jumper wires
---
 How it Works
1. The ultrasonic sensor emits a signal and waits for the echo.
2. The Arduino calculates the duration of the echo.
3. The distance is calculated using the formula:  
   `distance = duration * 0.034 / 2`
4. If the distance is less than 20 cm, the LED turns ON.

---
 Code
The full Arduino code is available in the [Distance_sensor_code.pdf.pdf](Distance_sensor_code.pdf.pdf) file.

---
 Notes
This is a simple project done during my first year as a computer engineering student. It helped me understand the basics of working with sensors, controlling outputs, and writing Arduino code.
