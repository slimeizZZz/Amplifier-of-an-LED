
<h1>Amplifier of an LED </h1>

<h2>Description</h2>
This project describes a simple amplifier of an LED's intensity using a bjt npn transistor and a 10k potentiometer at its base.
<br />

<h2>The Technology of the Circuit</h2>
The principle is simple. The transistor functions like a variable resistor in the active region that changes its Vbe voltage via a potentiometer in order to vary the collector current. The more collector current, the stronger the LED's intensity. I have also connected a capacitor in parallel with the LED so that the imperfections of the microcontroller can be negligible regarding the voltage drop. I have also made a code in MatLab that plots the live signal of the LED's amplitude.
<br />
<h2>The Schematic in orCAD</h2>
<img src="https://imgur.com/gWYrCr0.png="80% width="80%" alt="Disk Sanitization Steps"/>
<br />
<h2>Languages and Utilities Used</h2>

- <b>Arduino IDE</b>
-  <b>orCAD</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b> 
<h2>Components Used</h2> 
- <b>breadboard</b> 
<br />
- <b>ESP32</b>
<br />
- <b>Potentiometer</b> 
<br />
- <b>BJT NPN transistor</b> 
<br />
- <b>wires</b> 
<br />
- <b>100uF capacitor</b> 
<br />

<h2>Pictures and Videos of the Project</h2>

<p align="center">
  Watch video:  (https://imgur.com/6ANyvya)

 <br/>
<img src="https://imgur.com/Uz5EIL0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://imgur.com/gVyA7LD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>The graph at minimum resistence without capacitor:</b> 
<img src="https://imgur.com/CYckpw4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>How the graph at minimum resistence changes by connecting a capacitor:</b> 
<img src="https://imgur.com/Jqw3lZu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
