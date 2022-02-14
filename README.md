# niu-jpl-gui-1
This repository is for development of the 2021-2022 CO2 Wireless Sensor Network. The following will be a rundown on the system requirements and how to run the program/

Developmental System Requirements:
- Qt (Community or Enterprise)
  (Download Qt Community Here: https://www.qt.io/download-open-source)
- Version: 5.12.4
- Develop in C/C++
- System Minimum Specifications:
  - Operating System: Windows 8 or higher
  - CPU: Intel Core i3-3210 or AMD A8 7600 APU
  - GPU: Nvidia Geforce 400 Series or AMD Radeon HD 7000 Series
  - RAM: 4GB DDR3
  - Disk Space: 50 MB for Program, 100GB for long-term data logs
  - Display Resolution: 1024 x 678
  - Serial Communication Ports
- XBees to interface

How to Test and Run Program:
1. Open your project (QtDistArray in this case)
2. Go to "Projects" and uncheck "Shadow Build"
3. For testing purposes, make sure that you are on "Debug" mode
4. Click on any of the three run/debug/build symbols to build and run the program
5. Your program should run at this point

How to run a release version of this program:
1. From File Explorer:
    > QtDistArray-main -> release -> Double click the QtDistArray Application
2. This should run the program


*Currently we are running into the following error:

code execution cannot proceed because Qt5Core.dll was not found. Reinstalling the program may fix the problem
