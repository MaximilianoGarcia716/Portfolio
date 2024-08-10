Versión en español [aquí](https://github.com/MaximilianoGarcia716/Portafolio).
# Presentation
Greetings!, my name is Maximiliano Garcia Giron, I am an engineer in mechatronics graduated from Universidad Nacional de Cuyo and this is my professional portfolio. As you can observe while inspecting my student and professional projects, my most defining characteristic is curiosity, in conjunction with great desire of continuous learning, experimenting and developing creativity in a constant manner, I am interested in investigation and development, but open to maintenance and field works.

You can visit me on [Linkedin](https://www.linkedin.com/in/maximiliano-garcia-giron-01a9251ba/) and check my [Curriculum Vitae](https://github.com/MaximilianoGarcia716/Portfolio/blob/main/Curriculum%20Vitae/CURRICULUM%20VITAE%20Garcia%20Maximiliano%20-%20english.pdf).

In adition to being a native Spanish speaker, I have [english C2](https://efset.org/cert/wq7khc) level.

Next is presented a recap of my proyects, being produced alone or in a team, they all have a repository including code that you can check, but at the moment they are mostly in Spanish.

# Index:
- [Exploration holonomic differential robot for search and rescue](#Item1)
- [Port crane automaton](#Item2)
- [CO2 measurement chamber for soil respiration](#Item3)
- [Trajectory generation for ABB IRB 140 robot for welding](#Item4)
- [RAM memory simulator with C++ and SDL2](#Item5)

<a id="Item1"></a>
# Exploration holonomic differential robot for search and rescue

This project consist in an holonomic differential robot of three engines.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/03.jpg)

The robot has a Tensorflow type artificial intelligence trained to recognize five warning signals.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/01.jpg)

The robot also has an odometric/inertial navigation system that uses a Kalman filter to integrate both sensors. Finally the interface shows the status of the robot, the camera with the Tensorflow identification and a map that shows the robot's path and where signals can be placed to mark some points of interest. Said interface is designed to take the input from an xbox type controller for controlling the robot movement and the interface functions.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/02.jpg)

The full repository in spanish can be checked [here](https://github.com/MaximilianoGarcia716/Proyecto-Final-de-Estudios).

<a id="Item2"></a>
# Port crane automaton

This project was developed with another student of the Faculty of Engineering([Jonathan Obredor](https://github.com/jonathan-obredor)), consist in a control automaton for a port gantry crane implemented in a PLC simulation using functional block diagrams and structured text according the IEC 61131 standard, it has a three level control, being security, supervisor control and movement control for the lifting and trolley actuators, it also has a load swinging control and runs the simulation in the same PLC as the fisical system simulation. The results of said simulation are send through OPC UA to a Matlab terminal where the interface is shown.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/04.jpg)

The full repository in spanish can be checked [here](https://github.com/MaximilianoGarcia716/Automata-de-grua-portuaria).

<a id="Item3"></a>
# CO2 measurement chamber for soil respiration

This project was developed in team with the students [Santiago Urigüen](https://github.com/Santi-Uriguen), Fabricio Cano and [Mauricio Martínez](https://github.com/MauriM2023), and the engineers José Nicolás Martín and [Fernando Castro](https://github.com/nanocastro) from the Faculty of Agricultural Sciences, said project consists of a sealed chamber with SCD41 carbon dioxide sensors that measures the CO2 released by a treated sample of soil aiming to determine the microbial activity of said soil. Besides, said sensors it also has temperature and humidity sensing capacity.

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Soil%20Chamber.jpg)

Said sensors are multiplexed allowing up to four sensors to be used simultaneously, then their data are processed by a Wemos Lolin32 Lite and send to a Thingspeak server, in addition to being shown in a LCD screen. The case has the previously mentioned content in addition to a calibration button for altitude calibration by a pressure sensor before use.

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Soil%20Chamber%20Cabinet.jpg)

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Soil%20Chamber%20Cabinet%20with%20conections.jpeg)

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Cabinet%20while%20Measuring.jpeg)

The full repository can be checked [here](https://github.com/GenericLab/CO2-soil-respiration-chamber/tree/main/software/ESP32-S2/WEMOS-lolin32_Multiplexing_SCD41), please notice that this is part of a bigger repository due to other iterations of the project exist, furthermore is in english because is an open science and technology project.

<a id="Item4"></a>
# Trajectory generation for ABB IRB 140 robot for welding

This project was developed in team with the student William Alfaro of the Faculty of Engineering, consisted in the cinematic study of an ABB IRB 140 robot of six degrees of freedom, including direct and inverse cinematic development, articular limit and workspace study, including in all cases the arc welding tool PKI 300.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/05.jpg)

Finally the project concluded with the development of a trajectory generation software with implementation of the robotic toolbox by Peter Corke.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/06.jpg)

The full repository in spanish can be checked [here](https://github.com/MaximilianoGarcia716/Cinematica-y-soldadura-ABB-IRB-140).

<a id="Item5"></a>
# RAM memory simulator with C++ and SDL2

This project was developed in team with the students Araceli Arteaga and Stefanía Arias of the Faculty of Engineering, consisted in the modeling of a RAM memory, which can be sequential or random with regard to the processes placement, said memory can have 512 or 1024 spaces that contains processes and subprocesses simulated as code, pile and data sectors. Through multithreading each process can close each of its subprocess and itself, deleting itself from the list of active processes and releasing memory space. All of that is shown using the SDL2 library for C++..

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/07.jpg)

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/08.jpg)

The full repository in spanish can be checked [here](https://github.com/MaximilianoGarcia716/Simulador-RAM).
