# ITS PLC Pick and Place System (`ITS-PLC-Pick-and-Place`)

An industrial automation and simulation project designed for the **ITS PLC MHJ Edition** 3D plant simulation environment, controlled using Siemens SIMATIC STEP 7 (S7 Classic) / WinSPS-S7.

## 🎥 Demonstration Video

This repository corresponds to the setup and simulation demonstrated in the following YouTube video:

* [ITS PLC Pick and Place System](https://www.youtube.com/watch?v=YYAYbaBbmDc)

## 🏗️ Project Overview

The **ITS-PLC-Pick-and-Place** repository contains the PLC configuration and control logic to simulate a pick-and-place robotic arm or handling unit. The primary objective of this automated plant is to pick items from a feed conveyor using precise multi-axis positioning (e.g., pneumatic or motorized axes) and a gripping mechanism (such as a vacuum suction cup or mechanical clamp), then accurately place them onto an exit station, palette, or secondary conveyor.

### Key Components:

* **PLC Program Blocks:** Contains organization blocks, function blocks, and statement list/ladder logic code managing sequential operations, axis motion control, gripper timing, and sensor feedback.
* **Hardware & Network Configuration:** Hardware layout files tailored to the virtual 3D pick-and-place scene in ITS PLC.
* **Symbol & Variable Tables:** Tag mappings and memory addresses linking the virtual plant's actuators, proximity switches, and control panels to the PLC program.

## 🛠️ Software Requirements & Tools

To open, run, or modify this project, you will need:

1. **Siemens SIMATIC STEP 7 (v5.x)** or **WinSPS-S7** (featuring the built-in S7-300 simulation environment).
2. **ITS PLC MHJ Edition** (3D Industrial Plant Simulation Software featuring the Pick and Place scene).

## 🚀 Getting Started

1. Clone or download this repository to your workspace.
2. Open **WinSPS-S7** or **Siemens STEP 7** and load the pick-and-place project files.
3. Launch the **ITS PLC MHJ** 3D Pick and Place scene simulator.
4. Establish communication between the PLC environment and the 3D plant simulator to test the sequential automation routines.