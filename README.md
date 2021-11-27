# Re-Cycle-TacxFlow1680-Smart
 Re-Cycle your analog Tacx 1680 as a full Smart Trainer in Zwift

This ESP32 project enables a Tacx Flow Trainer, version 1680, to act as a smart trainer. Tacx 1680 are the trainers controlled by a orange head unit (https://www.amazon.de/-/en/Tacx-Flow-Turbo-Trainer-T1680/dp/B001EOOBHY). Those trainers are available on ebay for ~50 Euros, so you're looking at around 70 Euros for a full smart trainer. Power measurement is coming very close to my crank (Power2Max), it adjusts the resistance accordiing to the gradient and supports erg-mode.
A web interface allows to check the current values and run a spindown. The spindown result adjusts the power calculation and can be stored on the ESP32.
I've tested and optimized the device over several months in lockdown, riding on Zwift. It is a stable and tested solution, not a prototype.

The arduino code runs on an ESP32 chip, tested on the WROOM and WROVER versions. 
The ESP32 communicates with Zwift via Bluetooth uses Wifi for the web interface

Kudos to krisc-informatica has provided the electronic layout of the Tacx 1680 trainer which was crucial for me to get even started: https://github.com/krisc-informatica/arduino-smart-bike-trainer
