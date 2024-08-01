# Presentation
Greetings!, my name is Maximiliano Garcia Giron, I am an engineer in mechatronics graduated from Universidad Nacional de Cuyo and this is my professional portfolio. As you can observe while inspecting my student and professional projects, my most defining characteristic is curiosity, in conjunction with great desire of continuous learning, experimenting and developing creativity in a constant way, I am interested in investigation and development, but open to maintenance and field works.

You can visit me on [Linkedin](https://www.linkedin.com/in/maximiliano-garcia-giron-01a9251ba/) and check my [Curriculum Vitae](https://github.com/MaximilianoGarcia716/Portafolio/blob/main/Curriculum%20Vitae/CURRICULUM%20VITAE%20Garcia%20Maximiliano.pdf).

In adition to being a native Spanish speaker, I have [english C2](https://efset.org/cert/wq7khc) level.

Next is presented a recap of my proyects, being produced alone or in a team, they all have a repository including code that you can check, but at the moment they all in Spanish.

# Index:
- [Robot holonómico diferencial de exploración para busqueda y rescate](#Item1)
- [Automata de grúa portuaria](#Item2)
- [Cámara de medición de CO2 para respiración de suelos](#Item3)
- [Generación de trayectorias para robot ABB IRB 140 para soldadura](#Item4)
- [Simulador de memoria RAM con C++ y SDL2](#Item5)

<a id="Item1"></a>
# Robot holonómico diferencial de exploración para busqueda y rescate

Este proyecto consiste en un robot de tipo holonómico diferencial de tres motores.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/03.jpg)

El robot posee una inteligencia artificial de tipo Tensorflow entrenada para reconocer 5 señales de peligro.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/01.jpg)

Además posee un sistema de navegación odométrico/inercial utilizando filtro de Kalman para integrar ambos sensores. Finalmente la interfaz muestra el estado del robot, la cámara con la identificación de Tensorflow y un mapa donde se muestra el recorrido del robot y además pueden colocarse señales en dicho mapa para ubicar ciertos puntos de interés. Dicha interfaz está diseñada para tomar la consigna de un mando tipo Xbox para controlar el movimiento del robot y las funciones de la interfaz.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/02.jpg)

El repositorio completo puede verse [aquí](https://github.com/MaximilianoGarcia716/Proyecto-Final-de-Estudios).

<a id="Item2"></a>
# Automata de grúa portuaria

Ese proyecto fué desarrollado en conjunto con otro alumno de la Facultad de Ingeniería([Jonathan Obredor](https://github.com/jonathan-obredor)), consiste en un autómata de control para una grúa de tipo pórtico implementado en una simulación de PLC utilizando grafos y texto estructurado según al estándar de programación IEC61131, posee un control de tres niveles, siendo estos seguridad, control supervisor y control de movimiento para el actuador de izaje y movimiento del carro, además se agregó un control de balanceo para la carga y se realiza una simulación en el propio PLC del sistema físico. Los resultados de dicha simulación son enviados por OPC UA a la terminal de Matlab donde se muestra en la interfaz.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/04.jpg)

El repositorio completo puede verse [aquí](https://github.com/MaximilianoGarcia716/Automata-de-grua-portuaria).

<a id="Item3"></a>
# Cámara de medición de CO2 para respiración de suelos

Este proyecto fué desarrollado en conjunto con los alumnos [Santiago Urigüen](https://github.com/Santi-Uriguen), Fabricio Cano y [Mauricio Martínez](https://github.com/MauriM2023), además de los ingenieros José Nicolás Martín y [Fernando Castro](https://github.com/nanocastro) de la Facultad de Ciencias Agrarias, dicho proyecto consta de una cámara estanca con sensores de dióxido de carbono SCD41 los cuales miden el CO2 liberado por una muestra tratada de suelo con el objetivo de medir la actividad microbiana de dicha muestra. Además dichos sensores posee la capacidad de medir temperatura y humedad.

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Soil%20Chamber.jpg)

Dicho sensor se multiplexa, permitiendo hasta 4 sensores en simultáneo, sus datos posteriormente son procesados mediante un Wemos Lolin32 Lite para posteriormente ser enviados a un servidor de Thingspeak, además de ser mostrados en una pantalla LED. El gabinete que contiene lo anteriormente nombrado además posee un boton de calibración para calibrar por altitud los sensores antes de su uso mediante un sensor de presión.

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Soil%20Chamber%20Cabinet.jpg)

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Soil%20Chamber%20Cabinet%20with%20conections.jpeg)

![Image](https://raw.githubusercontent.com/GenericLab/CO2-soil-respiration-chamber/main/hardware/WEMOS-lolin32_Multiplexing_SCD41%20schematics/Cabinet%20while%20Measuring.jpeg)

El repositorio puede encontrarse [aquí](https://github.com/GenericLab/CO2-soil-respiration-chamber/tree/main/software/ESP32-S2/WEMOS-lolin32_Multiplexing_SCD41), nótese que es parte de un repositorio mayor, debido a que existen diversas iteraciones del proyecto, además se encuentra en inglés debido a que es un proyecto de ciencia y tecnología abierta.

<a id="Item4"></a>
# Generación de trayectorias para robot ABB IRB 140 para soldadura

Este proyecto se realizó en conjunto con el alumno William Alfaro de la Facultad de ingeniería, consistió en el estudio cinemático de un robot ABB IRB 140 de 6 Grados de Libertad, incluyendo desarrollo de su cinemática directa e inversa, estudio de límites articulares y espacio de trabajo, incluyendo en todos los casos la herramienta de soldadura por arco PKI 300.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/05.jpg)

Finalmente el proyectó culminó con el estudio de un programa de generación de trayectorias para soldaduras con implementación con el toolbox Robotics de Peter Corke.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/06.jpg)

El repositorio completo puede verse [aquí](https://github.com/MaximilianoGarcia716/Cinematica-y-soldadura-ABB-IRB-140).

<a id="Item5"></a>
# Simulador de memoria RAM con C++ y SDL2

Este proyecto se realizó en conjunto con las alumnas Araceli Arteaga y Stefanía Arias de la Facultad de Ingeniería, consistió en el modelado de una memoria RAM, la cual puede ser secuencial o aleatoria en cuanto a la ubicación de los procesos, dicha memoria puede ser de 512 o 1024 espacios y contiene procesos y subprocesos simulados mediante memoria de código, pila y datos. Mediante multithreading cada proceso puede cerrar a sus subprocesos y cerrarse a si mismo, eliminándose de la lista de procesos activos y liberando espacio en la memoria. Todo lo anterior es graficado mediante las librería de SDL2 para C++.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/07.jpg)

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/08.jpg)

El repositorio completo puede verse [aquí](https://github.com/MaximilianoGarcia716/Simulador-RAM).
