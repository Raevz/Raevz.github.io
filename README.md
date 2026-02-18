# About Me
I'm a fourth year Electrical Engineering student at BCIT focused on practical embedded systems, robotics, and software systems.

I like working on projects that allow me to take a solution from start to finish. 

I am currently working on a capstone project with other members of my team from BCIT. We are working to program a Nao robot (from Aldebaran Robotics) to perform to the specifications of the [UBC NEST Lab.](https://www.nestlab.ca/) This includes programming the robot to perform dances, stretches, and conversations. Programming is mainly in the proprietary software Choregraphe (Python based). If you're interested in the project please see the video linked in the projects section below and feel free to message me.  

## Contact Me
You can find me at [LinkedIn.](www.linkedin.com/in/ryan-mckay-3a798a348)

Email: rmckay37@my.bcit.ca

---

# What I’m focused on right now
- Embedded firmware + RTOS patterns (task design, concurrency, logging, serial tooling)
- Sensors and signal processing (radar-ish sensing, serial protocols, real-world noise)
- Building “demoable” systems: repeatable builds, clear docs, clean interfaces
- Developing reliable robotic systems

---

# Skills (practical)
**Embedded / Firmware**
- C/C++, FreeRTOS-style tasking, interrupts, concurrency, debugging, serial tooling
- Peripheral interfaces: UART, SPI, I2C, GPIO, PWM

**Software / Tools**
- Python for automation and utilities (serial parsing, CSV logs, quick tooling)
- MATLAB for modeling/simulation when it saves time
- Git/GitHub workflows, documentation, reproducible builds

**FPGA / Digital Design**
- SystemVerilog basics, hardware/software partitioning, memory-mapped I/O
- SoC integration concepts (FPGA ↔ processor communication)

**Hardware**
- Prototyping, soldering, bring-up/debug with scope/logic analyzer
- Working with real constraints (power, grounding, signal integrity)

---

# Projects I'm Proud to Share
## C language
### NFC reader attendance system (RTOS)(2025)
**Why I think it's cool:** In this project I was able to focus on the architecture of the hardware and firmware. I also really focused on a high level of documentation for this project.
- [Attendance System Code](https://github.com/Raevz/Pico2w_NFC_Logger/blob/main/README.md)
![Photo 2026-02-07, 12 49 07 PM](https://github.com/user-attachments/assets/38b82c26-2060-42f7-a2a8-7c0b28bc489c)

---

## C++
### SCARA robot simulation (2025)
**Why I think it's cool:** This project (for the ELEX robotics course) taught me about operating within a 3D space, coordinate systems, forward and inverse kinematics, trajectories, and object tracking.
- [SCARA Robot Code](https://github.com/Raevz/Virtual_Robotics/blob/main/README.md)
- please forgive my terrible camera quality.
<img width="1006" height="731" alt="image" src="https://github.com/user-attachments/assets/f4773487-0e7c-4df8-ad77-21c142c4e356" />

### Coloured ball sorter (2024)
**Why I think it's cool:** This project (for the ELEX C++ course) required the use of a Raspberrypi to sort balls using image processing techniques, heavy servo integration, and a server/client structure allowing for remote control of the sorter. The project introduced me to the power of the rpi as well as the constraints (power and timing) of integrating an entire system.
- [Ball Sorter Code](https://github.com/Raevz/Colour_Sorter/blob/main/README.md)
- [Ball Sorter Video](https://www.youtube.com/watch?v=m2Mln-6vOI4)
<img width="638" height="1033" alt="image" src="https://github.com/user-attachments/assets/fe384e2a-22d5-4c2f-9fee-beea7863b2f1" />

---

## Python
### Nao robot capstone project (2025-2026)
**Why I think it's cool:** The [Nao robot](https://maxtronics.com/en/nao6/) comes with 25 degrees of freedom and many sensors to interact with the world. This is a system that has the potential to damage itself if not treated with care, teaching me patience and caution when woring with the robot. Using Python and the proprietary Choregraphe software has given me experience working with a system that includes many of the easier tasks preporgrammed, allowing for a higher level of interaction as I attempt to program the Nao robot. 
- [Video only](https://youtu.be/onvUL8-2nvM)

---

## System Verilog
### Ultrasonic radar system (2025)
**Why I think it's cool:** This project was a practice in making multiple subsystems and peripherals interact smoothly. In many ways this project is a precursor to the attendance system above, including multiple communication protocols and my first python script for displaying the data gathered by the system. 
- [Radar Codebase](https://github.com/Raevz/Radar/blob/main/README.md)
- [Radar Video](https://youtu.be/I0dLHpoX5mE)
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/c5a2fdee-ca6f-43af-8e7f-4648e58fc1ac" />
