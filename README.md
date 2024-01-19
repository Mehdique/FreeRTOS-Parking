<h1 align="center" id="title">Parking management system</h1>

<p align="center"><img src="https://socialify.git.ci/Mehdique/FreeRTOS-Parking/image?language=1&amp;owner=1&amp;name=1&amp;stargazers=1&amp;theme=Light" alt="project-image"></p>


<p id="description">This project is a GUI (Graphical User Interface) for a parking system prototype that uses a microcontroller to communicate with the PC using serial communication. The system has 3 Presence sensors and servo motors to control the entrance and access. The LED's on the interface will change color from green to yellow if the spot is no longer free. This project was made using QML and Qt creator C++. The microcontroller end is an STM32f407 that is utilizing FreeRTOS and multiple tasks to check Infrared sensors that will give us an idea on car presence and it will control servo motors for the entrance and exit. Another serial task is created to handle sending and receiving data through UART. This is not a full fetched project it's a semestrial project that was made in a short period of time for academic purposes.The GUI github repo: https://github.com/Mohamed-Sejid/parking_managment</p>
