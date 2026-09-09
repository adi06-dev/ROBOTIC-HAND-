# Camera Controlled Robotic Hand

This is a **camera-controlled robotic hand** that I built using an Arduino Nano, servo motors and a 3D printed hand mechanism.

The main idea of this project is to control the robotic fingers using **real-time hand gestures captured through a Windows camera/webcam**. The camera tracks the movement of my hand and the detected finger positions are sent to the Arduino, which controls the servo motors accordingly.

Each servo motor is connected to a finger mechanism using threads, allowing the robotic fingers to open and close according to the movement of the user's hand.

### Components Used

* Arduino Nano
* 5 Servo Motors
* 3D Printed Robotic Hand
* Webcam / Windows Camera
* Battery / External Power Supply
* Jumper Wires
* Thread-based finger mechanism
* Breadboard

### Software Used

* Python
* OpenCV
* MediaPipe
* Arduino IDE
* Arduino C/C++

### How It Works

The webcam captures the user's hand in real time. Python and MediaPipe are used to detect the hand and finger positions. Based on whether each finger is open or closed, commands are sent to the Arduino Nano through serial communication.

The Arduino then controls the corresponding servo motors, making the robotic hand copy the movement of the real hand.

### What I Learned

While building this project, I worked with **computer vision, Arduino programming, servo motor control, serial communication and mechanical assembly**. One of the main challenges was getting the finger movement and servo positions to work smoothly together.

### Future Improvements

I plan to improve the finger movement, make the hand more responsive and explore wireless control instead of USB serial communication.

**Built by Aditya Kaushik**
