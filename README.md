# Gesture-Control-GUI-for-Mitsubishi-Industrial-Robot
A graphical user interface for gesture control of Mitsubishi MELFA series developed in C++/CLI language in .Net environment. Mediapipe framework in Python was used.
1. An MXT command is firstly executed in RT Toolbox to create a UDP socket on the robot controller.
2. The GUI ("multithread test") will establish a UDP communication line if the user pressed the 'connect' button.
3. When the UDP communication has been established, the feedback of the robot position will be displayed in the position respective textbox.
4. A built-in gesture recognition algorithm was developed in the GUI and can be activated through the button 'Capture'. This gesture recognition module was developed through convex hull algorithm.
5. The external gesture recognition module using mediapipe can be initialized by first clicking the "external" button in the GUI.
6. A TCP socket will be created and ready to listen to incoming clients.
7. To activate the gesture recognition module, run the python file "main".
8. Mitsubishi MELFA robots can be controlled through gesture based on the guidelines displayed in the GUI.
9. Video simulation: https://www.youtube.com/watch?v=mrISdGT7T6s
10. Project documentation presentation: https://www.youtube.com/watch?v=I_dsUn9pdNo


The python project repository can be find in gesture-recognition-modue while the C++/CLI GUI can be found in Mitsubishi-gesture-gui
