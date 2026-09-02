# Maheswar N Praveen

> *"I'm lazy, but I do my work with cosmic-sane perfection."*

Robotics & AI Engineer based in Bangalore / Kochi, India. I build physical systems that move, think, occasionally try to catch fire, and eventually run with mathematical precision. 

My comfort zone spans the entire mess between hardware and software: from hand-soldering copper bus bars for 3S LiPos to writing 3-DOF inverse kinematics at 200 Hz, bridging ROS 2 without bloated middleware, and deploying YOLO on edge NPUs.

---

## Things I Built That Actually Work

### [RO-ARM-PlayMotion](https://github.com/MaheswarPraveen/RO-ARM-PlayMotion)
* **Officially listed on the [Waveshare RoArm-M2-S Wiki](https://www.waveshare.com/wiki/RoArm-M2-S)**.
* Built a custom driver with freedrive teaching (grab the arm, move it around, it learns) and keyboard jogging.
* Added quintic polynomial spline interpolation so the arm moves like a human limb instead of violently vibrating itself off the desk.

### [SpotMicro Quadruped](https://github.com/MaheswarPraveen/SpotMicro)
* A 12-DOF quadruped robot dog on a 3D-printed KDY0523 frame (4 walls, 20% gyroid infill because layer adhesion matters).
* Driven by 12x DS3218 servos powered through a dedicated 6.8V rail off a 3S LiPo with a hand-soldered copper bus bar (because regular wires turn into heaters).
* Prototyped on ESP32; currently migrating gait math to an Arduino UNO Q with the M33/Zephyr core crunching inverse kinematics at ~200 Hz while Linux handles high-level telemetry.

### [ArduROSPI](https://github.com/MaheswarPraveen/ArduROSPI)
* A lightweight ROS 2 <-> MAVLink serial bridge using `pymavlink`.
* Built because MAVROS is a 500MB headache when you just want to drive a rover on a Raspberry Pi.
* Handles heartbeat failsafes, IMU streaming at 10 Hz, and mode switching over clean ROS 2 topics. Recognized by the ArduPilot community on Reddit and forums.

### [Autonomous Agricultural Skid-Steer Rover](https://github.com/MaheswarPraveen/SKID-STEER-ROVER-WITH-ARM)
* Final-year engineering project: a heavy-duty field rover with a 4-DOF robotic arm for precision spraying and weed removal.
* Powered by DC-DC power distribution and packed with a Hailo-8L AI accelerator running real-time YOLO on the edge.
* It worked well enough in field tests that it got adopted for real-world agricultural deployment.

### [offgit](https://github.com/MaheswarPraveen/offgit)
* An ambient agentic development harness running in the background.
* It tracks technical reasoning (< 1ms) and syncs project repos to GitHub every 10 minutes without touching git by hand or spamming commit histories.

### [Kalkii Genesis](https://github.com/MaheswarPraveen/kalkii-genesis)
* Solo-developing a 2D cyberpunk side-scrolling action game in Godot Engine (GDScript).
* Because sometimes servos get hot and you just want to write narrative loops, combat mechanics, and custom shaders.

---

## What I Work With

* **Robotics & Middleware**: ROS 2 (Jazzy), ArduPilot, MAVLink, PX4, Mission Planner, MicroPython
* **Kinematics & Motion**: 3-DOF Analytical Inverse Kinematics, Quintic Splines, Gait Phasing, Freedrive Manipulation
* **Embedded Hardware**: ESP32, Arduino, Raspberry Pi, Hailo-8L NPU, PCA9685, DC-DC Power Systems, Soldering
* **AI & Computer Vision**: YOLO, OpenCV, PyTorch, TensorFlow, Edge Acceleration
* **Languages**: Python, C/C++, GDScript, Bash, PowerShell, JavaScript
* **Engines & Tools**: Godot 4, Linux (Ubuntu/Fedora), Git, FreeRTOS

---

## Contact & Links

* **Location**: Bangalore / Kochi, India
* **Email**: [maheswarpraveen@gmail.com](mailto:maheswarpraveen@gmail.com)
* **LinkedIn**: [linkedin.com/in/maheswarpraveen](https://www.linkedin.com/in/maheswarpraveen)
* **GitHub**: [github.com/MaheswarPraveen](https://github.com/MaheswarPraveen)