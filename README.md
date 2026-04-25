# Smart Thermostat and Morse Code Projects

## Overview
This portfolio entry includes two projects from my embedded systems course that demonstrate how I worked with hardware and software together using a Raspberry Pi.

The first project is a smart thermostat prototype that reads temperature data, allows user input through buttons, and controls output using LEDs, an LCD display, and UART communication. The second project is a Morse code system that uses a state machine to control LED signaling in a structured way.

Together, these projects show how I approached system design, hardware interaction, and state-based logic.

---

## Project Artifacts

### Smart Thermostat
- Reads temperature using an I2C sensor  
- Allows user input to adjust a temperature set point  
- Uses LEDs to indicate heating and cooling states  
- Displays system information on an LCD  
- Sends system data over UART  

### Morse Code System
- Converts input into Morse code signals  
- Uses a state machine to control LED behavior  
- Manages timing for dots, dashes, and pauses  
- Demonstrates structured control flow in an embedded system  

---

## Reflection

This project focused on building a working smart thermostat prototype using a Raspberry Pi and several hardware components. The goal was to read temperature data from a sensor, allow the user to adjust a set temperature using buttons, and respond by controlling heating or cooling through LEDs. The system also displayed information on an LCD and sent data over UART to simulate communication with a larger system. Along with the final thermostat, I included my Morse code project because it highlights how I used a state machine to control behavior in a structured and predictable way.

One thing I feel I did well in this project was breaking the system down into smaller parts and getting each piece working before putting everything together. For example, I tested the buttons, LEDs, and sensor individually before integrating them into the full thermostat logic. The Morse code project helped with this approach because it required me to think through each state and transition ahead of time, and that carried over into the thermostat design.

If I were to improve anything, I would spend more time organizing the code earlier in the process. As the project grew, it became more important to keep things clean and structured, especially with multiple inputs and outputs happening at the same time. I would also look into improving efficiency, such as reducing unnecessary updates or refining how often data is sent over UART. The Morse code project also showed me that timing could be improved to make output more consistent.

Throughout this course, I added several tools and resources to my support network. I relied on the lab guides for structure, but I also used documentation for libraries like GPIOZero and other examples to better understand how to manage hardware interactions. I also became more comfortable troubleshooting hardware issues by checking wiring, verifying connections, and testing components individually.

The skills from this project are very transferable to other work, especially anything involving embedded systems. I learned how to read sensor data, respond to user input, and control outputs based on logic. The use of a state machine in both the Morse code project and the thermostat is especially useful because it provides a clear way to manage system behavior based on different conditions.

To keep the project maintainable and readable, I followed a consistent structure and used comments to explain what each part of the code was doing. I grouped related functionality together, such as handling inputs, updating outputs, and managing system state. This made it easier to understand the code later and make changes without breaking other parts of the system.

---

## Skills Demonstrated
- Embedded systems development  
- GPIO input and output handling  
- I2C sensor integration  
- UART communication  
- State machine design  
- Hardware and software integration  
- Debugging and troubleshooting  

---

## How to Run

### Thermostat
```bash
sudo python3 Thermostat.py
