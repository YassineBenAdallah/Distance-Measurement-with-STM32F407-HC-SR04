# Distance-Measurement-with-STM32F407-HC-SR04
<h1>Overview</h1>

<p>This project implements a real-time distance measurement system using the STM32F407 microcontroller and the HC-SR04 ultrasonic sensor. The measured distance is displayed on an I2C-based LCD, and a buzzer is triggered when the detected distance is less than a defined threshold.</p>
<h1>Features</h1>

<li> Accurate distance measurement using ultrasonic pulses and timer-based interrupts.</li>
<li>Real-time display of distance in centimeters on an LCD..</li>
<li> Proximity alert via a buzzer when the distance is below 10 cm..</li>
<li> Developed using the HAL (Hardware Abstraction Layer) library for better hardware compatibility..</li>
<h1>Hardware Requirements</h1>

<li>STM32F407 Discovery Board</h1>
<li>HC-SR04 Ultrasonic Sensor</li>
<li>I2C 16x2 LCD Display</li>
<li>Buzzer</li>
<li>Connection wires and resistors</li>
<h1>Software Requirements</h1>

<li>STM32CubeIDE</li>
<li>STM32 HAL Library</li>
<li>Standard peripheral libraries for I2C and timer configurations</li>

