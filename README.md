![Profile Logo](https://raw.githubusercontent.com/jrb00013/jrb00013/main/images/joseph-black-logo.jpeg)
# [![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Welcome+to+my+GitHub+Portfolio!;Projects+are+located+below+⬇️;Thanks+for+stopping+by!)](https://git.io/typing-svg)

## About me 
I'm a systems engineer, musician, organization leader, and a 2025 graduate of West Virginia University, focused on building scalable AI and robotics systems. I currently work as a Software Engineer at Lighthouse Avionics in Hilliard, Ohio, and I'm also a lead developer at [Deepiri](https://github.com/team-deepiri), where I mentor developers from all over the world and build open source research projects. I'm also the founder of [elomix](https://github.com/elomix), a stealth startup focused on embodied AI solutions. Previously, I worked as an AI Engineer at Genaiva, a voice AI startup, and led an undergraduate autonomous racing team to a 2nd place finish at the International F1Tenth Grand Prix. I've also worked on robotics research in sensor fusion and autonomous navigation through the iCPS lab, during my time at West Virginia University.

## Education
West Virginia University, B.S. in Computer Engineering - (Graduated May 2025)  

# [![LinkedIn](https://img.shields.io/badge/LinkedIn-Joseph%20Black-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/joseph-black-wvu)

## Stats

<!--![Stats Are Down](https://github-readme-stats.vercel.app/api?username=jrb00013&theme=dark&hide_border=true&include_all_commits=false&count_private=true)-->


![---> GitHub Streak is Down At The Moment <---](https://streak-stats.demolab.com/?user=jrb00013&theme=radical)
<!--![Top Languages](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=jrb00013&layout=pie)-->






---
## Personal Projects

<details>
  <summary><strong>Lydlr: Multimodal Edge AI Compression System</strong></summary>

Currently designing a real-time multimodal sensor data compression system using ROS2 and PyTorch, targeting edge devices. At the moment, I'm deploying my nodes onto a Raspberry Pi, and eventually plan to utilize an NVIDIA Jetson. The system fuses camera, LiDAR, IMU, and audio inputs through convolutional and recurrent neural networks to achieve efficient learned compression with temporal context. Integrated a reinforcement learning-based adaptive compression controller that dynamically balances compression quality and system resource usage, guided by live perceptual quality assessment (LPIPS) and system metrics. I also prepared the data for quantization for AI edge hardware.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/Lydlr?color=crimson&label=Lydlr-Last-Commit)
</details>

<details>
  <summary><strong>Dynodal</strong></summary>

Implemented a research-grade 3D ballistic dynamics simulation framework with high-fidelity physics, UKF state estimation, Neural ODE corrections, Transformer-based impact prediction, and GPU-accelerated surrogate models. Developed Python APIs, integrated real-time 3D visualization, and modularized subsystems for physics, estimation, prediction, and uncertainty quantification.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/dynodal?color=blue&label=dynodal-Last-Commit)

</details>

<details>
  <summary><strong>ASM x86 Real Mode OS</strong></summary>

Designed a bootable operating system written in pure x86 assembly, designed to run in real mode on legacy x86 architecture. Developed a custom 512-byte bootloader that initializes CPU, loads kernel from disk using BIOS INT 13h, and implements a command-line shell with keyboard input handling. Integrated FAT12 file system parsing, custom interrupt handlers through IVT modification, and basic memory management with segment:offset addressing. Successfully deployed on PlayStation 2 hardware using Free McBoot and a DMS3 modchip. Currently updating.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/asmOS?color=orange&label=asmOS-Last-Commit)

</details>

<details>
  <summary><strong>rudycanshoot: Screenshot MCP for AI Assistants</strong></summary>

Shipped an MCP server and CLI that lets AI coding assistants take and view screenshots. Auto-installs into Claude Code, Cursor, Windsurf, Codex, Gemini CLI, OpenCode, Continue, Cline, and related tools so agents can see the screen while they work.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/rudycanshoot?color=red&label=rudycanshoot-Last-Commit)
</details>

<details>
  <summary><strong>F1TENTH Autonomous Racecar</strong></summary>

Led the development of a 1/10th scale autonomous racecar as part of WVU's F1TENTH team, achieving 2nd place at the 19th IEEE International F1TENTH Grand Prix. Engineered and tuned custom PID control loops for throttle and steering using VESC firmware, dramatically improving control precision and stability at high speeds. Implemented real-time path planning algorithms including pure pursuit, gap following, and dynamic obstacle avoidance using ROS2, Python, and LiDAR sensor fusion. Served as technical lead, learning ROS2 independently and training team members on framework integration, algorithm deployment, and hardware communication protocols. 

![F1Tenth Article Picture](https://raw.githubusercontent.com/jrb00013/jrb00013/main/images/f1tenth-article.png)

![Workshop Desk View](https://raw.githubusercontent.com/jrb00013/jrb00013/main/images/f1tenth-image-1.png)

![Track Test](https://raw.githubusercontent.com/jrb00013/jrb00013/main/images/f1tenth-image-2.png)

![Car On Track](https://raw.githubusercontent.com/jrb00013/jrb00013/main/images/f1tenth-image-3.jpeg)

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/F1TENTH?color=blue&label=F1TENTH-Last-Commit)
</details>

<details>
  <summary><strong>Click here for more projects</strong></summary>

<br/>

---

<p></p>

<details>
  <summary><strong>Aamati: AI-Powered DAW</strong></summary>

Building an AI-native DAW with mood intelligence — standalone studio shell plus JUCE audio engine, MIDI workflows, and a Python ML pipeline that trains ONNX models to predict musical mood and drive real-time effects across 10 categories.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/Aamati?color=green&label=Aamati-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>NeuralGPTOS</strong></summary>

Designed and implemented NeuralGPTOS, an AI-native operating system with kernel-integrated agent runtime, eBPF-based semantic messaging, and vector memory services. Developed GPU memory management, sensory I/O drivers, and WASM/eBPF sandboxing to enable secure, high-performance AI agent execution directly within the OS.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/neuralgptos?color=blue&label=NeuralFabricGPTOS-Last-Commit)

</details>

<br/>

<details>
  <summary><strong>Smitical: Generative Materials Discovery</strong></summary>

Research engine for inverse design of crystal structures and alloys from abundant elements, aimed at reducing reliance on scarce specialty metals. Combines structure generation, surrogate filtering, and synthesis-oriented outputs.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/smitical?color=silver&label=smitical-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>Keke: Real-time AI-Powered Excel Assistant </strong></summary>

Built a native AI-driven FreeRTOS-based application for analyzing, cleaning, visualizing, and predicting from spreadsheet data. Developed the core processing engine, integrated intelligent data workflows with FreeRTOS, and designed an simple user interface to help with data analysis.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/keke?color=white&label=Keke-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>tripblip </strong></summary>

Designed and implemented a small interactive agentic social gathering, local event planning, and trip advisory platform with OpenAI integrations. 

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/tripblip?color=orange&label=tripblip-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>Rohomieo: Self-Hosted Remote Desktop</strong></summary>

Built a self-hosted remote desktop stack that streams and controls a computer from a phone over WireGuard + WebRTC. One-command setup across WSL2, Linux, macOS, and Windows, with signaling, host binaries, and session start/stop tooling so you own the full remote path end to end.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/rohomieo?color=teal&label=rohomieo-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>razochar6e: Firmware Battery Charge Scheduler</strong></summary>

Cross-platform laptop battery charge scheduling that keeps packs in a healthy 20–80% band via firmware-backed charge thresholds. One binary and setup flow for Linux, Windows, macOS, and WSL→Windows host control, with support across common OEM charge-limit interfaces.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/razochar6e?color=yellow&label=razochar6e-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>PDF2Text Studio</strong></summary>

Convert PDFs to plain text or Markdown without losing images: placeholder markers, reversible Base64 embedding, AI image descriptions, or extracted assets. Ships as a CLI, local web UI, and desktop app for archival, accessibility, and doc pipelines.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/pdf2text-studio?color=blue&label=pdf2text-studio-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>pdf-genesis: Research Paper PDF Generator</strong></summary>

Research PDF toolkit that synthesizes structured papers from repo metadata, theory docs, experiments, and benchmarks — or compiles markdown exports into a compendium. Supports JSON export modes and LaTeX math rendering for reproducible research writeups.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/pdf-genesis?color=purple&label=pdf-genesis-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>JMS Porthole: Janus Monitoring Suite</strong></summary>

Python CLI toolkit for remote monitoring, desktop broadcasting, and network recon. Commands cover VNC broadcast, live system metrics, port scanning, service fingerprinting, SSH shells, remote screenshots, and live log tailing under a single `jms` / `porthole` interface.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/jms-porthole?color=orange&label=jms-porthole-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>stora6e: Local Storage Cleanup</strong></summary>

Local-only storage cleanup app with a C++ backend that scans for old, large, cache, temp, log, and duplicate files, plus a React UI bound to localhost. Safe trash-first deletes and scoped scanning — nothing leaves the machine.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/stora6e?color=green&label=stora6e-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>brac7: Tournament Bracket Generator</strong></summary>

Tournament bracket generator with CLI, Python library, and Django UI. Supports single/double elimination, seeding, byes, and export to XLSX, PDF, Markdown, and Mermaid, plus interactive winner tracking and a 2D design workspace.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/brac7?color=crimson&label=brac7-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>Sykum Flight Simulator</strong></summary>

Developed a flight simulator combining Unreal Engine 5 and a Python/Flask web backend. Engineered core flight physics, 3D terrain and camera systems, HUD telemetry, and optional YOLOv8 detection. Built a responsive web frontend with chase/cockpit camera, keyboard/remote input, and real-time physics integration.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/sykum-sim?color=green&label=sykum-sim-Last-Commit)

</details>

<br/>

<details>
  <summary><strong>Smart Home 3D Simulator with Universal Remote</strong></summary>

Engineered a full-stack 3D smart home simulator with autonomous scheduling and interactive control. Developed a multi-protocol C universal remote supporting NEC, RC5, RC6, Sony SIRC, and brand-optimized IR transmission with assembly-level timing for precise 38kHz carrier generation. Built a GPU-accelerated 3D living room environment with responsive TV, dynamic lighting, and clickable remote controls. Implemented modular firmware architecture with universal TV code scanning, multi-protocol fallback, and latency instrumentation for performance profiling. Integrated REST API, WebSocket, MQTT, and Home Assistant/Node-RED adapters, enabling simulation or real device control. Created real-time interactive web UI bridging native C firmware with Python backend for streaming service shortcuts, animated feedback, and full virtual device control.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/smart-home-rc-simulator?color=purple&label=universal-remote-simulator-Last-Commit)

</details>

<br/>

<details>
  <summary><strong>PortGremlin: USB Spoofing Firmware</strong></summary>

Developed firmware for the EK-TM4C123GXL microcontroller that dynamically cycles through multiple USB device classes (HID keyboard, audio, printer, gamepad, MIDI) with randomized vendor/product IDs to spoof USB identities. Implemented timed USB descriptor switching and VID/PID spoofing using TI’s TivaWare USB library to test host OS device enumeration, driver stability, and security assumptions. Designed malformed descriptors to evaluate host resilience against unexpected USB device behaviors.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/PortGremlin?color=yellow&label=PortGremlin-Last-Commit)

</details>

<br/>

<details>
<summary><strong>ninehoto</strong></summary>

Native photo and video cleanup for iOS and Android: SwiftUI + Photos on iOS, .NET for Android with MediaStore. Swipe left to queue deletes, right to keep; nothing is removed until you confirm. Includes LRU thumbnail caching, prefetching, and a refreshed shell on both platforms.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/ninehoto?color=green&label=ninehoto-Last-Commit)

</details>

<br/>

<details>
  <summary><strong>DescentDefense: Local Network Monitor</strong></summary>

Home WIFI defensive monitoring dashboard with LAN device discovery, packet/bandwidth visibility, alerting, and optional live screen viewing for devices on your network.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/descent-defense?color=darkgreen&label=descent-defense-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>Taperforge: Harm-Reduction TUI Planner</strong></summary>

Terminal companion for evidence-informed taper planning and harm-reduction education — check-ins, cited clinical calculators, journaling, and crisis hotlines. Not medical advice.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/taperforge?color=olive&label=taperforge-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>Differential Harness: Salinity-Gradient Energy Research</strong></summary>

Hardware and simulation research stack for salinity-gradient energy concepts: physics models, OpenSCAD part designs, DAQ logging, and bench validation tooling.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/differential-harness?color=navy&label=differential-harness-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>Doctier: Local Context Agent + Browser Extension</strong></summary>

Local-first context agent and Chrome extension that tracks submissions, correlates open tabs, and surfaces live briefings via a gateway, overlay, and dashboard — all running on your machine.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/doctier?color=lightblue&label=doctier-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>TV Stretch: Multi-Room HDMI-CEC Control</strong></summary>

Room-aware TV coordination with ESP32 HDMI-CEC nodes, KiCad hardware, and a FastAPI control plane for power, input, and multi-TV handoff across a home.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/tv-stretch?color=maroon&label=tv-stretch-Last-Commit)
</details>

<br/> 

<details>
  <summary><strong>ExamJam: Interactive Full-Stack Study Platform</strong></summary>

Developed a full-stack collaborative study platform specifically designed for West Virginia University students, providing free access to course-organized flashcards and study materials. Built using React.js frontend with Firebase authentication and MySQL backend, featuring dynamic search functionality, class-based organization, and responsive UI design. Implemented secure user authentication, real-time data synchronization, and intuitive course categorization to eliminate paywalls common in commercial study apps. Collaborated in an Agile development environment with Git version control, contributing to architectural design, component logic, and testing infrastructure.  

![ExamJam Logo Image](https://raw.githubusercontent.com/jrb00013/jrb00013/main/images/logoimage.jpeg)

[Live App](https://examjam-firebase.firebaseapp.com/)  

[GitHub Repo](https://github.com/WVU-CS230-2024-01-Group01/exam-jam)  

![Last Commit](https://img.shields.io/github/last-commit/WVU-CS230-2024-01-Group01/exam-jam?color=purple&label=ExamJam-Last-Commit)

</details>

<br/>

<details>
  <summary><strong>404NotFound MPX OS</strong></summary>

Designed and implemented a cooperative multitasking OS kernel using C and x86 assembly, mimicking early embedded RTOS architectures with precise timing and interrupt control. Developed custom interrupt service routines, system call interfaces, and process management using Process Control Blocks (PCBs) and Memory Control Blocks (MCBs). Implemented full context-switching mechanisms managing register states and stack frames, along with modular shell support, serial drivers (polling and interrupt modes), software timers, and real-time I/O scheduling without relying on existing operating systems.

[Group GitHub](https://github.com/WVU-CS450/404NotFound/)

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/404NotFound?color=gold&label=404NotFound-Last-Commit)

</details>

<br/>

<details>
  <summary><strong>MSP432 Microcontroller Robot</strong></summary>

Programmed a fully autonomous robot using bare-metal C on the MSP432 microcontroller with no operating system. Integrated analog and digital sensors via GPIO and implemented real-time obstacle avoidance logic using timer interrupts and PWM-based motor control. Focused on efficient resource usage, low-latency decision-making, and precise motor speed modulation to achieve responsive navigation in dynamic environments. Demonstrated deep understanding of embedded systems design, peripheral configuration, and hardware-level programming.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/MSP432BOT?color=teal&label=MSP432BOT-Last-Commit)

</details>

<br/>

<details>
  <summary><strong>VHDL RISC-Style CPU with Custom ISA</strong></summary>

Engineered a custom 8-bit CPU from scratch using VHDL, emphasizing instruction-level control and finite state machine design. Created custom instruction set, hardcoded ALU, register file, and memory-mapped I/O interface with ModelSim simulation for timing analysis. Implemented FSMs for instruction fetch/decode/execute cycles, addressing real-world timing constraints including clock domain crossing and synchronous resets. Designed architecture supports basic arithmetic, logic operations, and I/O interfacing, laying groundwork for future FPGA-based projects.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/vhdl-cpu?color=indigo&label=VHDL-CPU-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>AthletiDB</strong></summary>
A sports data analysis and management system designed for sports analysts, researchers, and enthusiasts. This pipeline provides robust data collection, normalization, analysis, and export capabilities across multiple sports leagues.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/athletidb?color=brown&label=JaxK-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>Discord Call of Duty Statistics Bot</strong></summary>

Developed and deployed a feature-rich Discord bot for gaming community management, integrating with Call of Duty API (https://codapi.dev/) to track ranked play statistics. Implemented REST API communication, asynchronous programming patterns, and real-time message parsing for interactive user commands. Features modular event-driven architecture with comprehensive error handling, logging systems, and live testing protocols. Maintains active deployment with version control and community-driven feature updates.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/CDLstatsBOT?color=blueviolet&label=CDLstatsBOT-Last-Commit)
</details>

<br/>

<details>
  <summary><strong>Gotzi - Network Probe Utility Tool</strong></summary>

Built a comprehensive Linux-based command-line network diagnostic tool for UDP health assessment and latency analysis. Implemented custom socket programming in Python with precise timing mechanisms for round-trip time calculation, jitter analysis, and packet loss statistics. Features robust logging modules and statistical visualization for network behavior analysis under variable conditions. Designed for network administrators requiring detailed UDP connection diagnostics and performance monitoring capabilities.

![Last Commit](https://img.shields.io/github/last-commit/jrb00013/gotzi-probe?color=cyan&label=gotzi-Last-Commit)
</details>

</details>


# Background
<details>
  
I went to college at West Virginia University and served as a team lead for the WVU Autonomous Racing Team in 2024, which competed at the International F1Tenth Grand Prix in Niagara Falls, Canada, where we secured [2nd Place](https://media.statler.wvu.edu/news/2024/09/24/wvu-f1tenth-team-places-second-in-international-competition).

During my time at WVU, I was also a Robotics Research Intern at the Intelligent Cyber-physical Systems Research Lab ([iCPS Lab](https://sites.google.com/site/amrselwakeel/intelligent-cyber-physical-systems-research-lab-icps-lab)), where I worked with analyzing sensor fusion data to develop efficient path planning and obstacle avoidance algorithms for mobile robots. 

As I graduated in 2025, I received a contract offer to work as an AI Software Engineer at Genaiva, a voice AI startup focused on seamlessly designing and integrating agentic restaurant communication systems.

I left Genaiva after my contract ended and founded [Deepiri](https://deepiri.com), an open-source R&D group founded in November 2025 where I mentor developers and build systems focused on generative intelligence, AI infrastructure, and large-scale data pipelines. This effort was rooted in my own non-traditional path into tech, having never had a formal corporate internship early on and wanting to create opportunities for others facing similar barriers.

Alongside this, I founded and run exovra (Elomix), a small startup focused on building intelligent embodied systems that bridge software, hardware, and real-world environments. This includes developing AI inference platforms, fleet orchestration systems, and custom hardware designed for scalable autonomous operations.

Today, I am a Software Systems Engineer at Lighthouse Avionics, where I work on optical-based aerospace infrastructure and autonomous drone systems. My work spans counter-UAS sensing platforms, terrain-aware drone coverage simulation, geospatial algorithms, and real-time optical/thermal processing pipelines used for mission-critical deployments.

On top of my high-level system design experience, I’ve built digital logic circuits, designed embedded real-time firmware for robotics, and developed operating systems from scratch.

I've obtained SAS certifications in data analysis and statistical decision-making that I have utilized in my ML-based projects and automation pipelines. I'm always looking to grow through the challenges that come with any system I make, and can perform well wherever is needed in multiple hardware and software domains.

Outside of my technical work, I also spent three of my college summers as a maintenance worker at my hometown cemetery, where I dug graves, poured cement, and wasn't afraid of manual labor. 

</details>

### **Programming Languages & Frameworks:**
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
