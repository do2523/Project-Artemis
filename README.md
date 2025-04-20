# Project Artemis

## Inspiration
We were inspired by the idea of blending robotics, AI, and interactive systems to create something both fun and technically challenging. The concept of a smart Nerf gun turret came from a mix of sci-fi influences and a desire to apply our skills in real-time systems, machine learning, and embedded programming in a creative way.

## What It Does
**Project Artemis** is an autonomous Nerf gun turret that can detect and identify human faces using a custom-trained face recognition model. It features:

- Voice command activation via the Google Voice Recognition API  
- Manual control with a PS4 controller using the SDL2 library  
- Serial communication to interact with hardware components  
- Patrol mode, where the turret scans its environment for targets  
- Autonomous firing when a recognized face or target is detected  

## How We Built It
We developed Project Artemis using:

- **C++** as the main programming language  
- **CMake** for project configuration and building  
- **vcpkg** to manage C++ libraries  
- **Custom face recognition model**, trained using OpenCV  
- **Google Speech-to-Text API** for voice control  
- **SDL2** for PS4 controller input  
- **Serial communication libraries** to interact with the turret's hardware  

We tied everything together into a multi-threaded system that handles input, processing, and actuation in real-time.

## Challenges We Ran Into
- Integrating multiple subsystems (voice, vision, control, and hardware) and managing concurrency  
- Training the face recognition model to perform reliably under different lighting and angles  
- Tuning the servo controls to move the turret smoothly and accurately  
- Serial communication bugs, especially syncing messages across different hardware platforms  
- Latency issues in real-time recognition and response  

## Accomplishments That We're Proud Of
- Building a fully functional AI-powered Nerf turret from scratch  
- Successfully integrating face and voice recognition in a real-time C++ system  
- Achieving smooth and responsive manual and autonomous turret control  
- Creating an immersive experience with patrol mode and intelligent targeting  

## What We Learned
- Advanced multi-threaded programming and real-time systems design  
- How to train and deploy a face recognition model with OpenCV  
- Practical integration of software and hardware components  
- Debugging and optimizing performance across different subsystems  

## What's Next for Project Artemis
- Implementing target vs non-target classification to avoid firing on authorized individuals  
- Upgrading to a more powerful onboard computer  
- Adding web or mobile control interfaces  
- Integrating object tracking and predictive targeting  
- Improving the voice interface to understand more complex commands  

## Built With
- `arduino`  
- `c`  
- `c++`  
- `cmake`  
- `linux`  
- `opencv`  
- `python`  
- `sdl2`  
- `shell`  
