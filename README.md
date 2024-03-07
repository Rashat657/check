# SimuWare
- Unreal Engine - version 4.27.2

SimuWare is a virtual platform that enables users to assemble physical components like cubes, cones, etc. in a 3D game-like environment and simulate their interactions following physical and mechanical principles. It provides an educational and prototyping tool for simulation enthusiasts, students, educators, and researchers.

## Table of Contents
1. [Introduction](#introduction)
    1. [Purpose](#Purpose)
    2. [Scope](#Scope)
    3. [Definitions and Abbreviations](#Definitions-and-Abbreviations)  
2. [Overall Description](#overall-description)
    1. [Product Perspective](#Product-Perspective)
    2. [ Product Functions](#Product-Functions)
    3. [User Characteristics](#user-characteristics)
    4. [Constraints](#constraints)
    5. [Assumptions and Dependencies](#assumptions-and-dependencies)
3. [Specific Requirements](#specific-requirements)
4. [References](#references)

## 1. Introduction
### 1.1 Purpose
The purpose of our software (SimuWare) is to provide a virtual platform that enables users to assemble physical and electrical components in a 3D game-like environment and to simulate their interactions. SimuWare aims to provide an educational and prototyping tool for simulation enthusiasts, students, educators, and researchers.

### 1.2 Scope
#### 1.2.1 Goals
- SimuWare will feature a user-friendly interface for selecting, placing, and connecting components within a virtual environment.
- Users will also be able to simulate the behavior of assembled components.

#### 1.2.2 Benefits
- Users will be able to simulate their prototypes without having to build them in real life.
- They will easily get to know the flaws in their circuits and will be able to correct those before building a real-life prototype.

### 1.3 Definitions and Abbreviations


## 2. Overall Description
### 2.1 Product Perspective
This product aims to provide a rapid-prototyping environment for circuits and micro-controller based simulations. This will enable users to test their prototypes within our software without building them in real life. As a result, they will not have to do many hit-and-tries and waste their precious costly components.

#### 2.1.1 User Interfaces
SimuWare is a desktop application (for windows).

#### 2.1.2 Software Interfaces
- Unreal Engine / Unity 
- C++
- Arduino APIs

### 2.2 Product Functions
#### 2.2.1 3D Environment
- SimuWare will provide a 3D virtual environment using Unreal Engine / Unity.
- Users will be able to navigate the environment using intuitive controls.

#### 2.2.2 Part Assembly System
- Users shall be able to select from a library of Arduino components.
- Users shall be able to place selected components within the 3D environment.
- Components shall snap or attach to each other realistically when placed adjacent to each other.

#### 2.2.3 Physics Simulation
- SimuWare will incorporate physics simulation to simulate interactions between assembled components.
- Components shall interact realistically with each other and the environment (e.g., gravity, collisions).

#### 2.2.4 User Interface
- SinuGear shall provide a user-friendly interface for selecting, placing, and manipulating components.
- The interface shall allow users to access tools for assembly, simulation, and data visualization.

### 2.3 User Characteristics
SimuWare aims to provide an educational and prototyping tool for simulation enthusiasts, students, educators, and researchers. Users can range from beginners to advanced users who like to tinker and create stuff using microcontrollers.

### 2.4 Constraints
- The performance may vary on different hardwares depending upon factors like the presence of graphic card and RAM available.

### 2.5 Assumptions and Dependencies
- The platform assumes some basic ideal-physics assumptions and some results might differ from real-world simulations.
- The user should have basic knowledge of arduino and familiarity with basic circuit design.

## 3. Specific Requirements
### 3.1 User shall be able to ADD, CONNECT AND MOVE OBJECTS in the virtual environment
- User should be able to select components from an inventory and place them within the 3D environment.
- Components should be able to snap/attach to each other.
- Object manipulation should include resizability and rotatability
- Components should be categorized into mechanical and electrical (sensors, actuators, etc) for easy searching.

### 3.2 User shall be able to EXECUTE ARDUINO CODE on a specific ARDUINO OBJECT
- There should be a specific arduino object.
- It should have the ability to run a code on itself.

### 3.3 User shall be able to use an ARDUINO OBJECT to INTERACT with OTHER OBJECTS
- Arduino object should be able to connect to other objects.
- Its code should be able to manipulate other objects.

### 3.4 User shall be able to do PHYSICS-SIMULATION on the OBJECT
- The software shall be able to simulate objects in real time.

## 4. References
- [Arduino GitHub Repository] (https://github.com/arduino)
- [Unreal Engine] (https://www.unrealengine.com/en-US)