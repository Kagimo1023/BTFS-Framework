# Better Than Fucking Script (BTFS)
Language: [RU](https://github.com/Kagimo1023/BTFS-Framework/blob/main/README.md) | [EN](https://github.com/Kagimo1023/BTFS-Framework/blob/main/README_EN.md)

## Contents  

1. [**Project**](#project)  
   - [Brief Description](#brief-description)
   - [History](#history)
   - [Features](#features)
   - [Drawbacks](#drawbacks)
   - [Project Goals](project-goals)
   - [Roadmap](#roadmap)
   - [Technical Details](#technical-details)
   - [FAQ](#faq)

2. [**Links**](#links)
3. [**Acknowledgements**](#acknowledgements)  

---

## Project  
### Brief Description  

**Better Than Fucking Script (BTFS)** is a comprehensive framework that provides tools for developing custom game modes in *Superfighters Deluxe*. It allows users to create characters, abilities, chat commands, and other in-game elements without writing code from scratch.  

### History  

The project emerged in **2022**, initially intended to expand the functionality of my own game mode, **Shootout Mode**. Over time, the idea evolved into separating the mode into universal components that could be used to create modes of "any type."  

By **summer 2022**, BTFS became a fully independent project, no longer tied to *Shootout Mode: Extended*. The mode itself began running through BTFS, and new components were added, significantly simplifying development.  

In **2023-2024**, the project was put on hold due to a lack of motivation.  

By **late 2024**, work resumed with a simple reason: **"Just finish something already!"** The main motivation was to build the habit of **"start → finish."**  

During the break from BTFS, a universal **CommandShell** component was developed (initially for a tournament script). Later, it was seamlessly integrated into BTFS.  

### Features  

- Creation of new game modes and complex scripts  
- Ready-made components for characters, skills, and chat commands  
- **MSBuild** support for compiling outside the game  
- A container for multiple modes with switching capability  

### Drawbacks  

Unfortunately, the project has many flaws due to being developed at different stages of life. Key issues include:  

- Poor code organization  
- Lack of optimization  
- Inconsistent coding style  
- No use of design patterns  
- No **Git** usage initially, leading to problems  
- Some parts are well-written, others are terrible  

### Project Goals  

- Implementation of universal components  
- Creation of a unified scripting system  
- Development of a visual editor: **"BTFS: Creative Studio"**  

### Roadmap  

The project is currently in development. Planned tasks:  

#### **Core**  
- **Documentation**  
  - Status: *Partially done (BTFS Framework)*  
- **Git Repository Usage**  
  - Status: *Done!*  
- **Optimization**  
  - Status: *Not started*  
- **Consistent Code Style**  
  - Status: *In progress*  
- **Project Restructuring**  
  - Status: *In progress*  

#### **Components**  

1. **Item Component**  
   - *Description*: Allows creating custom items based on existing in-game objects.  
   - *Requirements*:  
     - Base implementation  
     - External testing  
     - Subclass implementation  
     - Status: *Done*  

2. **CustomGameover Component**  
   - *Description*: Enables custom game-ending conditions.  
   - *Requirements*:  
     - Base implementation  
     - External testing  
     - Subclass implementation  
     - Status: *Done*  

3. **Animation Component**  
   - *Description*: Adds interpolation-based animations.  
   - *Requirements*:  
     - Base implementation  
     - External testing  
     - Subclass implementation  
     - Status: *Done*  

### Technical Details  
#### Core Components  

| Component       | Description                          |  
|----------------|-------------------------------------|  
| **Callbacks**   | Event management system             |  
| **Character**   | Character creation                  |  
| **Command**     | Chat commands                       |  
| **CommandShell**| Command manager                     |  
| **Game**        | Extends `GameScriptInterface`       |  
| **Global**      | Utilities & global variables        |  
| **Mode**        | Base class for game modes           |  
| **Plugin**      | Third-party script integration      |  
| **Skill**       | Character abilities                 |  

### FAQ  

#### **What’s the purpose of this?**  
*Superfighters Deluxe* has a proprietary license, meaning modding is legally restricted. The only tool available is **ScriptAPI**, which offers limited functionality. BTFS aims to provide essential components for gameplay expansion, making it easy to add missing features.  

#### **What’s a "complex script"?**  
A script combining multiple components to create advanced functionality. Examples: *BotExtended*, *Commands+*.  

#### **What modes can be created?**  
- Character-based modes  
- RPG modes  
- Tournament modes  

---

## Links  
- [Superfighters Deluxe](https://mythologicinteractive.com/)  
- [Script API](https://juansero29.github.io/SFDScripts/)
- [BotExtended](https://github.com/NearHuscarl/BotExtended)
- [Commands+](https://steamcommunity.com/sharedfiles/filedetails/?id=1906413901)

## Acknowledgements  
Special thanks to **Guldrelokk** for inspiration and support.  
