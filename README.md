# Hi there, I'm Bartosz 

c++/c/c#/python developer • low-level programming • embedded systems • linux  

---

## About me
- Programming in **C++, C, C#, and Python**
- Interested in **microcontrollers and SBCs**:
  - ESP32
  - STM32
  - Arduino
  - Raspberry Pi
- Focus areas:
  - Embedded systems
  - Networking & system-level programming
  - Hardware–software integration

---

## Tech stack
**Languages**
- C++ • C • C# • Python • x86 Assembly 

**Embedded / Hardware**
- ESP32 • STM32 • Arduino • Raspberry Pi  

**Tools & Environment**
- Fedora Linux
- NeoVim
- Git/SVN
- KiCAD/Eagle
- CubeIDE

---
  
  ## Some Projects I've Been Working On
  
  ### [Simple CPU Simulation & Visualization](https://github.com/MrRooby/Maszyna-W-ESP32)
<table>
<tr>
<td>
<img src="https://github.com/user-attachments/assets/cdd90341-6911-4052-8dec-bbbc3e2d4a60" width="600" alt="Front View"/>
<br><em>Front view</em>
</td>
<td>
<img src="https://github.com/user-attachments/assets/aed93962-8428-4eef-a9b9-467ec26d6f69" width="600" alt="LED Display"/>
<br><em>LED displays</em>
</td>
</tr>
</table>
  This was my undergraduate thesis project. I built an ESP32-S3 based RGB LED device for students learning computer science fundamentals.  
  The device simulates a simple CPU called "Maszyna W", visualizing its internal operations in real-time.  
  
  - **Connectivity:** WiFi-enabled for live integration with a web simulator via **WebSockets**.  
  - **Modes:** Supports both **local** and **online** operation.  

  ### [Low-Level Image Pixelization Filter](https://github.com/MrRooby/JA_Pixelizacja_Obrazu)
<table>
<tr>
<td>
<img src="https://github.com/user-attachments/assets/22384dda-cc17-4f1b-a3ea-2e1e41419864" width="600" alt="Front View"/>
<br><em>Program UI</em>
</td>
<td>
<img src="https://github.com/user-attachments/assets/ba0584ca-dc1c-4d4a-ab9a-68aa7f69e9ae" width="600" alt="LED Display"/>
<br><em>Output example</em>
</td>
</tr>
</table>
This project implements a pixelization algorithm that averages blocks of pixels to create a pixelated effect.  

- **Algorithm Implementation:** Three dynamic libraries written in **C++**, **x86 Assembly**, and **x86 Assembly with AVX vector instructions**.  
- **Performance Features:** Supports **multithreading** for faster processing.  
- **User Interface:** Built in **C#**, including **histogram visualization** for both original and pixelated images.

  ### [Nixie Tube Clock](https://github.com/MrRooby/Nixie-Clock-v1.0)
<table>
<tr>
<td>
<img src="https://github.com/user-attachments/assets/8d9ec057-aad7-412b-9b84-ae9d039dcfe2" width="600" alt="Front View"/>
<br><em>First Prototype</em>
</td>
<td>
<img src="https://github.com/user-attachments/assets/9ae01518-790d-4a9d-b913-7fb5d7fea3b9" width="600" alt="LED Display"/>
<br><em>PCB Design</em>
</td>
</tr>
</table>

This project combines **retro Soviet Nixie tube displays** with modern IoT functionality to show **time, date, temperature, and humidity**.  

- **Display:** Uses authentic **170 V Nixie tubes** for a vintage aesthetic.  
- **Sensors:** Includes a **gas sensor** for detecting **CO levels**.  
- **Hardware:** Built around an **ESP32 microcontroller**.  
- **Companion App:** Allows users to **set alarms** and interact with the device remotely.  
