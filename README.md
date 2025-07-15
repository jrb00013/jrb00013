# Joseph Black - B.S. in Computer Engineering | Interests and Skills in: Robotics, Embedded Systems, Software Design, Electrical Design, Cybersecurity and Firmware Security

## About Me
Hi! Welcome to my GitHub Portfolio!

My name is Joseph Black, and I'm a junior engineer who graduated in 2025 from West Virginia University with a strong interest in machine learning, embedded systems, automation, and cybersecurity. I’ve worked on real-time robotics, OS and firmware development, automation tools, audio plugins, apps, and websites. I was a team lead for the WVU autonomous racing team, and I was also a Robotics Research Intern at the Intelligent Cyber-physical Systems Research Lab (iCPS Lab) at WVU, who worked on pushing the boundaries of utilizing sensor fusion data to develop efficient path planning and obstacle avoidance algorithms. I also have earned SAS certifications in data analysis and statistical decision-making that I have utilized in my ML-based projects. I'm interested in building dynamic AI-powered embedded systems and always looking to grow through the challenges that come with making them.

On top of my technical skills, I've also worked outside during my college summers as a maintence worker at my hometown cemetery, where I learned how to work with grit but also enjoy the little things while on the job. I'm thankful for the opportunities that I have.

Some of my skills and interests are listed below. I have links to some of my uploaded projects by which I maintain the repos for.

Thanks for stopping by, enjoy your day! 
  
---
## Projects

### **F1TENTH Autonomous Racing**  
- Led the development of a 1/10th scale autonomous race car as part of WVU's F1TENTH team, achieving 2nd place at the 19th IEEE International F1TENTH Grand Prix. Engineered and tuned custom PID control loops for throttle and steering using VESC firmware, dramatically improving control precision and stability at high speeds. Implemented real-time path planning algorithms including pure pursuit, gap following, and dynamic obstacle avoidance using ROS2, Python, and LiDAR sensor fusion. Served as technical lead, learning ROS2 independently and training team members on framework integration, algorithm deployment, and hardware communication protocols.

### **ASM x86 Real Mode OS**  
- Created a fully functional bootable operating system written in pure x86 assembly, designed to run in real mode on legacy x86 architecture. Developed a custom 512-byte bootloader that initializes CPU, loads kernel from disk using BIOS INT 13h, and implements a command-line shell with keyboard input handling. Integrated FAT12 file system parsing, custom interrupt handlers through IVT modification, and basic memory management with segment:offset addressing. Successfully deployed on PlayStation 2 hardware using Free McBoot and a DMS3 modchip. Currently updating.

### **Aamati: AI-Powered MIDI Groove Synthesizer VST3 Plugin**  
- Developing an early development intelligent VST3 audio plugin using JUCE framework (C++) and PyTorch for real-time MIDI rhythm manipulation based on psychoacoustic 

### **PortGremlin: USB Spoofing Firmware**  
- Developed firmware for the EK-TM4C123GXL microcontroller that dynamically cycles through multiple USB device classes (HID keyboard, audio, printer, gamepad, MIDI) with randomized vendor/product IDs to spoof USB identities. Implemented timed USB descriptor switching and VID/PID spoofing using TI’s TivaWare USB library to test host OS device enumeration, driver stability, and security assumptions. Designed malformed descriptors to evaluate host resilience against unexpected USB device behaviors.

### **Lydlr: Multimodal Edge AI Compression System**
- Currently designing a real-time multimodal sensor data compression system using ROS 2 and PyTorch, targeting edge devices. At the moment, I'm deploying my nodes onto a Raspberry Pi, and eventually plan to utilize an NVIDIA Jetson. The system fuses camera, LiDAR, IMU, and audio inputs through convolutional and recurrent neural networks to achieve efficient learned compression with temporal context. Integrated a reinforcement learning-based adaptive compression controller that dynamically balances compression quality and system resource usage, guided by live perceptual quality assessment (LPIPS) and system metrics. Developed synthetic data pipelines for robust simulation and benchmarking, and prepared the model for quantized deployment on resource-constrained hardware.

###  **ExamJam: Interactive Full-Stack Study Platform**  
- Developed a full-stack collaborative study platform specifically designed for West Virginia University students, providing free access to course-organized flashcards and study materials. Built using React.js frontend with Firebase authentication and MySQL backend, featuring dynamic search functionality, class-based organization, and responsive UI design. Implemented secure user authentication, real-time data synchronization, and intuitive course categorization to eliminate paywalls common in commercial study apps. Collaborated in an Agile development environment with Git version control, contributing to architectural design, component logic, and testing infrastructure. Link: https://examjam-firebase.firebaseapp.com/

### **404NotFound MPX OS**  
- Designed and implemented a bare-metal cooperative multitasking OS kernel using C and x86 assembly, mimicking early embedded RTOS architectures with precise timing and interrupt control. Developed custom interrupt service routines, system call interfaces, and process management using Process Control Blocks (PCBs) and Memory Control Blocks (MCBs). Implemented full context-switching mechanisms managing register states and stack frames, along with modular shell support, serial drivers (polling and interrupt modes), software timers, and real-time I/O scheduling without relying on existing operating systems.

### **MSP432 Microcontroller Robot**  
- Programmed a fully autonomous robot using bare-metal C on the MSP432 microcontroller with no operating system. Integrated analog and digital sensors via GPIO and implemented real-time obstacle avoidance logic using timer interrupts and PWM-based motor control. Focused on efficient resource usage, low-latency decision-making, and precise motor speed modulation to achieve responsive navigation in dynamic environments. Demonstrated deep understanding of embedded systems design, peripheral configuration, and hardware-level programming.

### **VHDL RISC-Style CPU with Custom ISA**  
- Engineered a custom 8-bit CPU from scratch using VHDL, emphasizing instruction-level control and finite state machine design. Created custom instruction set, hardcoded ALU, register file, and memory-mapped I/O interface with ModelSim simulation for timing analysis. Implemented FSMs for instruction fetch/decode/execute cycles, addressing real-world timing constraints including clock domain crossing and synchronous resets. Designed architecture supports basic arithmetic, logic operations, and I/O interfacing, laying groundwork for future FPGA-based projects.

### **Discord Call of Duty Statistics Bot**  
- Developed and deployed a feature-rich Discord bot for gaming community management, integrating with Call of Duty API (https://codapi.dev/) to track ranked play statistics. Implemented RESTful API communication, asynchronous programming patterns, and real-time message parsing for interactive user commands. Features modular event-driven architecture with comprehensive error handling, logging systems, and live testing protocols. Maintains active deployment with version control and community-driven feature updates. 

### **UDP Probe Network Utility Tool**
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

