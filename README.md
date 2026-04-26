# Smart Thermostat and Morse Code Projects

## Overview
This portfolio entry includes two projects from my embedded systems course that demonstrate my ability to work with both hardware and software. The main project is a smart thermostat built using a Raspberry Pi, and the second artifact is a Morse code system that uses a state machine to control LED output. These projects show how I approached system design, hardware interaction, and structured logic.

---

## Project Artifacts

### Smart Thermostat
- Reads temperature using an I2C sensor  
- Uses buttons to adjust a temperature set point  
- Controls heating and cooling indicators using LEDs  
- Displays system data on an LCD  
- Sends data over UART to simulate communication with a server  

### Morse Code System
- Converts input into Morse code signals  
- Uses a state machine to control LED behavior  
- Manages timing for dots, dashes, and pauses  
- Demonstrates structured control flow  

---

## Reflection

### Summarize the project and what problem it was solving
The main project was a smart thermostat prototype that simulates how a real system would monitor and control temperature. It reads temperature data, allows the user to adjust a set point, and responds by turning heating or cooling on or off using LEDs. It also displays information on an LCD and sends data through UART to simulate communication with a larger system. The Morse code project focused on solving a different problem by translating input into timed LED signals using a state machine, which helped build a strong foundation for managing system behavior.

### What did you do particularly well
One thing I did well was breaking the system into smaller parts and testing each one before combining everything. I made sure the buttons, LEDs, and sensor were all working individually before integrating them into the thermostat. I also had a good understanding of how to use a state machine, which helped in both the Morse code project and the thermostat when handling different system states.

### Where could you improve
I could improve by organizing my code earlier in the process. As the project became more complex, it became more important to keep everything structured and easy to follow. I would also improve efficiency by reducing unnecessary updates and refining how often data is sent over UART. In the Morse code project, I could improve the timing to make the output more consistent.

### What tools and/or resources are you adding to your support network
I added several resources to my support network during this course. I used the lab guides as a starting point, but I also relied on documentation for libraries like GPIOZero and online examples to better understand how to work with hardware. I also gained more experience troubleshooting hardware issues by checking wiring, verifying connections, and testing components step by step.

### What skills from this project will be particularly transferable to other projects and/or course work
The skills from this project are very transferable, especially for embedded systems and hardware-based applications. I learned how to read sensor data, respond to user input, and control outputs based on logic. The use of a state machine is especially important because it provides a clear way to manage system behavior. These skills can be applied to many different types of systems beyond this project.

### How did you make this project maintainable, readable, and adaptable
I kept the project maintainable and readable by using a consistent structure and adding comments to explain each part of the code. I grouped related functionality together, such as input handling, output control, and state management. This made it easier to understand the code later and make changes without affecting other parts of the system.

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
