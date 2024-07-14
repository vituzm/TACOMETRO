# TACHOMETER
> This project consists on a [tachometer](https://en.wikipedia.org/wiki/Tachometer) to measure the rotation speed of a 5V controled bushless [fan](https://netcomputadores.com.br/gs/hy60n05ap803--fan--sepa-dc-5v/39173?srsltid=AfmBOor2hONwDeeEb6BnhoTzcTBVaMVkfP5J6wRe7xtLnUkBQYk5WPlPrH8).

## Table of Contents
* [General Info](#general-information)
* [Hardware Used](#technologies-used)
* [Software Used](#technologies-used)
* [Usage](#usage)
* [Fotos and videos](#fotos-and-videos)
* [Contact](#contact)
  
## General Information
- This project is based on a work for school
- Most of the names of the variables and comments were written in portuguese
- The fan used had a feedback wire of it's frequency to calcule the RPM via software
- Cube Monitor file is named as [flow.json](https://drive.google.com/open?id=1V2o8UZM_N2qDBOTmcZdjXmnnTfqAlt_q&usp=drive_copy).

## Hardware Used
- STM32 NUCLEO F446RE
- Brushless fan:
    - 5V control pin
    - 12V supply pin
    - GND supply pin
- Optocoupler: 4N25
- Capacitor: 100nF
- Resistors (ohms):
    - 390
    - 4.7K
    - 330K
    - 3.3K
- LM741 as a buffer

## Software Used
- C programminng language
- JavaScript Object Notation (JSON)
- Serial ports for communication 
- [Cube IDE](https://www.st.com/en/development-tools/stm32cubeide.html)
- [Cube Monitor](https://www.st.com/en/development-tools/stm32cubemonitor.html) as IHM
- PWM signal generation and control through serial port
- Input capture of the 446RE microcontroller

## Usage
- Download the code for the Cube IDE and Monitor
- Plug the fan pins where is indicated on the schematic
- Connect the microcontroller on a USB serial port:
    - 115200 baudrate
    - 8 data bits
    - No parity bit
    - 1 stop bit
- See results on the cube monitor IHM

## Fotos and videos
- Schematic of the circuit used:
<img src="https://github.com/vituzm/Tacometro/assets/134985122/ebb543b6-89d8-4111-a106-c851b85c0322" alt = "Schematic" width="50%" height="20%"/>

&nbsp; 
- IHM of the user and node red notation 
<img src="https://github.com/vituzm/Tacometro/assets/134985122/71b1c4b0-d80d-46f2-beae-b5a209930a1e" alt = "IHM" width="80%" height="40%"/>

&nbsp; 
- Video
<a href="https://www.youtube.com/watch?v=lcBYFT1z83I&t=1s" target="_blank">
  <img src="https://img.youtube.com/vi/lcBYFT1z83I/0.jpg" alt="Video" width="80%" height="40%">
</a>

## Contact
Created by [vituzm](https://github.com/vituzm) - feel free to contact!
