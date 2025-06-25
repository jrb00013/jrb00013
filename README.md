# Joseph Black - B.S. in Computer Engineering | Interests and Skills in: Robotics, Embedded Systems, Software Design, Electrical Design, Cybersecurity and Firmware Security

Hi! I'm Joseph Black, welcome to my GitHub Portfolio.

I'm a 2025 Computer Engineering graduate from West Virginia University with a strong interest in embedded systems, automation, and cybersecurity. I’ve worked on real-time robotics, OS and firmware development, apps, automation tools, audio plugins, and websites. I was a team lead for the WVU autonomous racing team, and I was also a Robotics Research Intern at the Intelligent Cyber-physical Systems Research Lab (iCPS Lab) at WVU, who worked on pushing the boundaries of path planning and obstacle avoidance algorithms utilizing sensor fusion data. I also have earned SAS certifications in data analysis and statistical decision-making that I have utilized in my ML projects.

On top of my technical skills, I've also worked outside during the summer as a maintence worker for my hometown cemetery for 3 years while attending school. I learned how to work hard in a team and enjoy the little things while on the job. I'm passionate about building dynamic AI-powered embedded systems and always looking to grow through the challenges that come with making them.

Some of my skills and interests are listed below. I have links to some of my uploaded projects by which I maintain the repos for.

Have a good safe day!
  
---
## Projects

### **F1TENTH Autonomous Racing**  
- Led the development of a 1/10th scale autonomous race car as part of WVU's F1TENTH team, achieving 2nd place at the 19th IEEE International F1TENTH Grand Prix. Engineered and tuned custom PID control loops for throttle and steering using VESC firmware, dramatically improving control precision and stability at high speeds. Implemented real-time path planning algorithms including pure pursuit, gap following, and dynamic obstacle avoidance using ROS2, Python, and LiDAR sensor fusion. Served as technical lead, learning ROS2 independently and training team members on framework integration, algorithm deployment, and hardware communication protocols.

### **ASM x86 Real Mode OS**  
- Created a fully functional bootable operating system written in pure x86 assembly, designed to run in real mode on legacy x86 architecture. Developed a custom 512-byte bootloader that initializes CPU, loads kernel from disk using BIOS INT 13h, and implements a command-line shell with keyboard input handling. Integrated FAT12 file system parsing, custom interrupt handlers through IVT modification, and basic memory management with segment:offset addressing. Successfully deployed on PlayStation 2 hardware using Free McBoot and a DMS3 modchip. Currently updating.

### **Aamati: Machine Learning VST3 Audio Filtering / Layering Plugin**  
- Currently developing an early development intelligent VST3 audio plugin using JUCE framework (C++) and PyTorch for real-time drum rhythm manipulation based on psychoacoustic analysis. 

### **MSP432 Microcontroller Robot**  
- Programmed a fully autonomous robot using bare-metal C on the MSP432 microcontroller with no operating system. Integrated analog and digital sensors via GPIO and implemented real-time obstacle avoidance logic using timer interrupts and PWM-based motor control. Focused on efficient resource usage, low-latency decision-making, and precise motor speed modulation to achieve responsive navigation in dynamic environments. Demonstrated deep understanding of embedded systems design, peripheral configuration, and hardware-level programming.

###  **ExamJam**  
- Developed a full-stack collaborative study platform specifically designed for West Virginia University students, providing free access to course-organized flashcards and study materials. Built using React.js frontend with Firebase authentication and MySQL backend, featuring dynamic search functionality, class-based organization, and responsive UI design. Implemented secure user authentication, real-time data synchronization, and intuitive course categorization to eliminate paywalls common in commercial study apps. Collaborated in an Agile development environment with Git version control, contributing to architectural design, component logic, and testing infrastructure.

### **PortGremlin**  
- Developed firmware for the EK-TM4C123GXL microcontroller that dynamically cycles through multiple USB device classes (HID keyboard, audio, printer, gamepad, MIDI) with randomized vendor/product IDs to spoof USB identities. Implemented timed USB descriptor switching and VID/PID spoofing using TI’s TivaWare USB library to test host OS device enumeration, driver stability, and security assumptions. Designed optional malformed descriptors to evaluate host resilience against unexpected USB device behaviors.

### **404NotFound MPX OS**  
- Designed and implemented a bare-metal cooperative multitasking OS kernel using C and x86 assembly, mimicking early embedded RTOS architectures with precise timing and interrupt control. Developed custom interrupt service routines, system call interfaces, and process management using Process Control Blocks (PCBs) and Memory Control Blocks (MCBs). Implemented full context-switching mechanisms managing register states and stack frames, along with modular shell support, serial drivers (polling and interrupt modes), software timers, and real-time I/O scheduling without relying on existing operating systems.

### **VHDL RISC-Style CPU with Custom ISA**  
- Engineered a custom 8-bit CPU from scratch using VHDL, emphasizing instruction-level control and finite state machine design. Created custom instruction set, hardcoded ALU, register file, and memory-mapped I/O interface with ModelSim simulation for timing analysis. Implemented FSMs for instruction fetch/decode/execute cycles, addressing real-world timing constraints including clock domain crossing and synchronous resets. Designed architecture supports basic arithmetic, logic operations, and I/O interfacing, laying groundwork for future FPGA-based projects.

### **Discord Call of Duty Statistics Bot**  
- Developed and deployed a feature-rich Discord bot for gaming community management, integrating with Call of Duty API (https://codapi.dev/) to track ranked play statistics. Implemented RESTful API communication, asynchronous programming patterns, and real-time message parsing for interactive user commands. Features modular event-driven architecture with comprehensive error handling, logging systems, and live testing protocols. Maintains active deployment with version control and community-driven feature updates. 

### **Keke RTOS App**  
- Currently developing a lightweight real-time operating system that integrates AI decision-making with SQL database management for autonomous stock inventory control. Built using C/C++ with custom RTOS concepts, featuring priority-based task scheduling, message passing, and thread-safe inter-process communication. Incorporates SQLite for real-time inventory tracking and REST API integration for live stock data analysis. Implements AI-powered trend forecasting and autonomous reorder suggestions, simulating edge-device intelligence for IoT and logistics applications with local decision-making capabilities.

### **UDP Probe Network Utiltiy Tool**
- Built a comprehensive Linux-based command-line network diagnostic tool for UDP health assessment and latency analysis. Implemented custom socket programming in C with precise timing mechanisms for round-trip time calculation, jitter analysis, and packet loss statistics. Features robust logging modules and statistical visualization for network behavior analysis under variable conditions. Designed for network administrators requiring detailed UDP connection diagnostics and performance monitoring capabilities.

### **JaxK Website**  
- Upcoming Full Stack React website powered with Vite and deployed with Firebase. Functionality is undetermined as of writing.

---

### **Programming Languages & Tools:**
- **C, C++, Java, Python, Go Rust**  
- **HTML, CSS, JavaScript, React.js, Node.js, Vue.js, PHP**  
- **VHDL, Assembly, OpenGL, SQL**  
- **Kali Linux, Wireshark, AWS, GCP, Azure**  
- **MATLAB, SolidWorks, Simulink, Quartus Prime, AutoCAD, Unity, Vulkan**

### **Web and Network Skills:**
- **Networking & Security**: VLANs, VPNs, Firewalls, Network Protocols, Penetration Testing, Digital Forensics  
- **Software Development**: Security Robotics, Cloud Security

###  Electrical Hardware and Circuit Design Skills

- **Embedded Systems**: FPGA, ROS2, Microcontrollers, Sensor Integration, Motor Control  
- **ADC/DAC Interfacing**: Signal acquisition and processing on FPGAs.
- **Bare Metal Programming**: Low-level applications on ARM Cortex-M microcontrollers.
- **Digital Filtering**: Created simple digital filters
- **Diagnostic Equipment**: Skilled in using hands-on lab equipment like multimeters, oscilloscopes and logic analyzers for system debugging.
- **Familiar Electrical Hardware & Components**: NVIDIA Jetson, SiC/GaN Power Modules, Texas Instruments DSPs, STM32s, STSPIN Motors, Bosch BNO055, Hokuyo and Ouster Lidars, VESC Speed Controllers, ARM Micocontrollers, Altera FPGA

---


## 🌐 [LinkedIn](https://www.linkedin.com/in/joseph-black-wvu)

