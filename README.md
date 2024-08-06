# Presentation
Greetings!, my name is Maximiliano Garcia Giron, I am an engineer in mechatronics graduated from Universidad Nacional de Cuyo and this is my professional portfolio. As you can observe while inspecting my student and professional projects, my most defining characteristic is curiosity, in conjunction with great desire of continuous learning, experimenting and developing creativity in a constant way, I am interested in investigation and development, but open to maintenance and field works.

You can visit me on [Linkedin](https://www.linkedin.com/in/maximiliano-garcia-giron-01a9251ba/) and check my [Curriculum Vitae](https://github.com/MaximilianoGarcia716/Portafolio/blob/main/Curriculum%20Vitae/CURRICULUM%20VITAE%20Garcia%20Maximiliano.pdf).

In adition to being a native Spanish speaker, I have [english C2](https://efset.org/cert/wq7khc) level.

Next is presented a recap of my proyects, being produced alone or in a team, they all have a repository including code that you can check, but at the moment they all in Spanish.

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

Dicho sensor se multiplexa, permitiendo hasta 4 sensores en simultáneo, sus datos posteriormente son procesados mediante un Wemos Lolin32 Lite para posteriormente ser enviados a un servidor de Thingspeak, además de ser mostrados en una pantalla LED. El gabinete que contiene lo anteriormente nombrado además posee un boton de calibración para calibrar por altitud los sensores antes de su uso mediante un sensor de presión.

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Soil%20Chamber%20Cabinet.jpg)

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Soil%20Chamber%20Cabinet%20with%20conections.jpeg)

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Cabinet%20while%20Measuring.jpeg)

The full repository can be checked [here](https://github.com/GenericLab/CO2-soil-respiration-chamber/tree/main/software/ESP32-S2/WEMOS-lolin32_Multiplexing_SCD41), please notice that this is part of a bigger repository due to other iterations of the project exist, furthermore is in english because is an open science and technology project.

<a id="Item4"></a>
# Trajectory generation for ABB IRB 140 robot for welding

Este proyecto se realizó en conjunto con el alumno William Alfaro de la Facultad de ingeniería, consistió en el estudio cinemático de un robot ABB IRB 140 de 6 Grados de Libertad, incluyendo desarrollo de su cinemática directa e inversa, estudio de límites articulares y espacio de trabajo, incluyendo en todos los casos la herramienta de soldadura por arco PKI 300.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/05.jpg)

Finalmente el proyectó culminó con el estudio de un programa de generación de trayectorias para soldaduras con implementación con el toolbox Robotics de Peter Corke.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/06.jpg)

The full repository in spanish can be checked [here](https://github.com/MaximilianoGarcia716/Cinematica-y-soldadura-ABB-IRB-140).

<a id="Item5"></a>
# RAM memory simulator with C++ and SDL2

Este proyecto se realizó en conjunto con las alumnas Araceli Arteaga y Stefanía Arias de la Facultad de Ingeniería, consistió en el modelado de una memoria RAM, la cual puede ser secuencial o aleatoria en cuanto a la ubicación de los procesos, dicha memoria puede ser de 512 o 1024 espacios y contiene procesos y subprocesos simulados mediante memoria de código, pila y datos. Mediante multithreading cada proceso puede cerrar a sus subprocesos y cerrarse a si mismo, eliminándose de la lista de procesos activos y liberando espacio en la memoria. Todo lo anterior es graficado mediante las librería de SDL2 para C++.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/07.jpg)

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/08.jpg)

The full repository in spanish can be checked [here](https://github.com/MaximilianoGarcia716/Simulador-RAM).
