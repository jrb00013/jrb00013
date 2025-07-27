
# Joseph Black
### 🎓 B.S. in Computer Engineering @ WVU (May 2025)  
Interests: Robotics, AI, Embedded, IoT, Automation, and Secure Hardware


# 🌐 [![LinkedIn](https://img.shields.io/badge/LinkedIn-Joseph%20Black-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/joseph-black-wvu)
## Welcome to my GitHub Portfolio!

## 📊  Stats
<!-- 
![GitHub Streak](https://streak-stats.demolab.com?user=jrb00013&theme=radical)
![No Current Streak](https://github-readme-streak-stats.herokuapp.com/?user=jrb00013)
-->
![Repo Languages Pie Chart](https://github-readme-stats.vercel.app/api/top-langs/?username=jrb00013&layout=pie&theme=radical)

## 📝  About Me

I'm a junior engineer who just graduated from West Virginia University in 2025. I've worked on real-time robotics, OS and firmware development, automation tools, audio plugins, apps, and websites. I was a team lead for the WVU autonomous racing team, and I was also a Robotics Research Intern at the Intelligent Cyber-physical Systems Research Lab ([iCPS Lab](https://sites.google.com/site/amrselwakeel/intelligent-cyber-physical-systems-research-lab-icps-lab)) at WVU, who worked with utilizing sensor fusion data to develop efficient path planning and obstacle avoidance algorithms. I also have earned SAS certifications in data analysis and statistical decision-making that I have utilized in my ML-based projects. I'm interested in building dynamic AI-powered embedded systems and always looking to grow through the challenges that come with making them.

On top of my technical skills, I've also worked outside during my college summers as a maintence worker at my hometown cemetery, where I learned how to work with grit but also enjoy the little things while on the job. I'm thankful for the opportunities that I have.

Some of my skills and interests are listed below. I have links to some of my old uploaded projects by which I maintain the repos for and occasional update. I'm also working on a few new projects as well. 

Thanks for stopping by, enjoy your day! 
---
## 🔧  Projects

<details>
  <summary><strong>F1TENTH Autonomous Racecar</strong></summary>

Led the development of a 1/10th scale autonomous race car as part of WVU's F1TENTH team, achieving 2nd place at the 19th IEEE International F1TENTH Grand Prix. Engineered and tuned custom PID control loops for throttle and steering using VESC firmware, dramatically improving control precision and stability at high speeds. Implemented real-time path planning algorithms including pure pursuit, gap following, and dynamic obstacle avoidance using ROS2, Python, and LiDAR sensor fusion. Served as technical lead, learning ROS2 independently and training team members on framework integration, algorithm deployment, and hardware communication protocols.

![Workshop Desk View](https://raw.githubusercontent.com/jrb00013/jrb00013/main/images/f1tenth-image-1.png)

![Track Test](https://raw.githubusercontent.com/jrb00013/jrb00013/main/images/f1tenth-image-2.png)

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/F1TENTH?color=blue&label=F1TENTH-Last-Commit)
</details>

<details>
  <summary><strong>Aamati: AI-Powered MIDI Groove Synthesizer VST3 Plugin</strong></summary>

Developing an early development intelligent VST3 audio plugin using JUCE framework (C++) and PyTorch for real-time MIDI rhythm manipulation based on psychoacoustic modeling.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/Aamati?color=green&label=Aamati-Last-Commit)
</details>

<details>
  <summary><strong>Lydlr: Multimodal Edge AI Compression System</strong></summary>

Currently designing a real-time multimodal sensor data compression system using ROS2 and PyTorch, targeting edge devices. At the moment, I'm deploying my nodes onto a Raspberry Pi, and eventually plan to utilize an NVIDIA Jetson. The system fuses camera, LiDAR, IMU, and audio inputs through convolutional and recurrent neural networks to achieve efficient learned compression with temporal context. Integrated a reinforcement learning-based adaptive compression controller that dynamically balances compression quality and system resource usage, guided by live perceptual quality assessment (LPIPS) and system metrics. I also prepared the data for quantization for AI edge hardware.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/Lydlr?color=crimson&label=Lydlr-Last-Commit)
</details>

<details>
  <summary><strong>ASM x86 Real Mode OS</strong></summary>

Designed a bootable operating system written in pure x86 assembly, designed to run in real mode on legacy x86 architecture. Developed a custom 512-byte bootloader that initializes CPU, loads kernel from disk using BIOS INT 13h, and implements a command-line shell with keyboard input handling. Integrated FAT12 file system parsing, custom interrupt handlers through IVT modification, and basic memory management with segment:offset addressing. Successfully deployed on PlayStation 2 hardware using Free McBoot and a DMS3 modchip. Currently updating.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/asmOS?color=orange&label=asmOS-Last-Commit)

</details>

<details>
  <summary><strong>PortGremlin: USB Spoofing Firmware</strong></summary>

Developed firmware for the EK-TM4C123GXL microcontroller that dynamically cycles through multiple USB device classes (HID keyboard, audio, printer, gamepad, MIDI) with randomized vendor/product IDs to spoof USB identities. Implemented timed USB descriptor switching and VID/PID spoofing using TI’s TivaWare USB library to test host OS device enumeration, driver stability, and security assumptions. Designed malformed descriptors to evaluate host resilience against unexpected USB device behaviors.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/PortGremlin?color=yellow&label=PortGremlin-Last-Commit)

</details>

<details>
  <summary><strong>ExamJam: Interactive Full-Stack Study Platform</strong></summary>

Developed a full-stack collaborative study platform specifically designed for West Virginia University students, providing free access to course-organized flashcards and study materials. Built using React.js frontend with Firebase authentication and MySQL backend, featuring dynamic search functionality, class-based organization, and responsive UI design. Implemented secure user authentication, real-time data synchronization, and intuitive course categorization to eliminate paywalls common in commercial study apps. Collaborated in an Agile development environment with Git version control, contributing to architectural design, component logic, and testing infrastructure.  

<p align="center">
  <img src="https://raw.githubusercontent.com/jrb00013/jrb00013/main/logoimage.jpeg" alt="Exam Jam Logo" width="200"/>
</p>

[Live App](https://examjam-firebase.firebaseapp.com/)  

[GitHub Repo](https://github.com/WVU-CS230-2024-01-Group01/exam-jam)  

![Last Commit](https://img.shields.io/github/last-commit/WVU-CS230-2024-01-Group01/exam-jam?color=purple&label=ExamJam-Last-Commit)


</details>

<details>
  <summary><strong>404NotFound MPX OS</strong></summary>

Designed and implemented a cooperative multitasking OS kernel using C and x86 assembly, mimicking early embedded RTOS architectures with precise timing and interrupt control. Developed custom interrupt service routines, system call interfaces, and process management using Process Control Blocks (PCBs) and Memory Control Blocks (MCBs). Implemented full context-switching mechanisms managing register states and stack frames, along with modular shell support, serial drivers (polling and interrupt modes), software timers, and real-time I/O scheduling without relying on existing operating systems.

[Group GitHub](https://github.com/WVU-CS450/404NotFound/)

![Last Commit](https://img.shields.io/github/last-commit/WVU-CS450/404NotFound?color=gold&label=404NotFound-Last-Commit)

</details>

<details>
  <summary><strong>MSP432 Microcontroller Robot</strong></summary>

Programmed a fully autonomous robot using bare-metal C on the MSP432 microcontroller with no operating system. Integrated analog and digital sensors via GPIO and implemented real-time obstacle avoidance logic using timer interrupts and PWM-based motor control. Focused on efficient resource usage, low-latency decision-making, and precise motor speed modulation to achieve responsive navigation in dynamic environments. Demonstrated deep understanding of embedded systems design, peripheral configuration, and hardware-level programming.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/MSP432BOT?color=teal&label=MSP432BOT-Last-Commit)

</details>

<details>
  <summary><strong>VHDL RISC-Style CPU with Custom ISA</strong></summary>

Engineered a custom 8-bit CPU from scratch using VHDL, emphasizing instruction-level control and finite state machine design. Created custom instruction set, hardcoded ALU, register file, and memory-mapped I/O interface with ModelSim simulation for timing analysis. Implemented FSMs for instruction fetch/decode/execute cycles, addressing real-world timing constraints including clock domain crossing and synchronous resets. Designed architecture supports basic arithmetic, logic operations, and I/O interfacing, laying groundwork for future FPGA-based projects.


![Last Commit](https://img.shields.io/github/last-commit/jrb00013/vhdl-cpu?color=indigo&label=VHDL-CPU-Last-Commit)
</details>

<details>
  <summary><strong>Discord Call of Duty Statistics Bot</strong></summary>

Developed and deployed a feature-rich Discord bot for gaming community management, integrating with Call of Duty API (https://codapi.dev/) to track ranked play statistics. Implemented RESTful API communication, asynchronous programming patterns, and real-time message parsing for interactive user commands. Features modular event-driven architecture with comprehensive error handling, logging systems, and live testing protocols. Maintains active deployment with version control and community-driven feature updates.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/CDLstatsBOT?color=blueviolet&label=CDLstatsBOT-Last-Commit)
</details>

<details>
  <summary><strong>UDP Probe Network Utility Tool</strong></summary>

Built a comprehensive Linux-based command-line network diagnostic tool for UDP health assessment and latency analysis. Implemented custom socket programming in C with precise timing mechanisms for round-trip time calculation, jitter analysis, and packet loss statistics. Features robust logging modules and statistical visualization for network behavior analysis under variable conditions. Designed for network administrators requiring detailed UDP connection diagnostics and performance monitoring capabilities.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/udp-probe?color=cyan&label=udp-probe-Last-Commit)


</details>
<details>
  <summary><strong>JaxK Website</strong></summary>

Upcoming Full Stack React website powered with Vite and deployed with Firebase. Functionality is undetermined as of writing.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/jaxk-website?color=pink&label=JaxK-Last-Commit)
</details>

---

### **Programming Languages & Tools:**
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cpp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=flat-square)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vue.js&logoColor=4FC08D)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![XML](https://img.shields.io/badge/XML-E44D26?style=flat-square)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-452F84?style=flat-square)
![UART](https://img.shields.io/badge/UART-555555?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-003366?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![OpenVPN](https://img.shields.io/badge/OpenVPN-EA7E20?style=flat-square&logo=openvpn&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-FF0000?style=flat-square&logo=solidworks&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=flat-square)
![LTSpice](https://img.shields.io/badge/LTSpice-A4373A?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-005F87?style=flat-square)
![Quartus](https://img.shields.io/badge/Quartus-0071C5?style=flat-square)
![AutoCAD](https://img.shields.io/badge/AutoCAD-E34F26?style=flat-square&logo=autodesk&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![Vulkan](https://img.shields.io/badge/Vulkan-B61C1C?style=flat-square)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/RaspberryPi-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square)
![nRF](https://img.shields.io/badge/nRF-005F87?style=flat-square)
![Altera FPGA](https://img.shields.io/badge/Altera-0071C5?style=flat-square)




