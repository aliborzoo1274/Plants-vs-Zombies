# 🌻 Plants vs.  Zombies

A C++ implementation of the classic tower defense game Plants vs. Zombies, built with the SFML (Simple and Fast Multimedia Library) graphics library.

![Image](https://github.com/user-attachments/assets/5a961c56-0912-4b4b-95f2-899e3bec0bba)

## 📋 Overview

This project is a recreation of the popular Plants vs. Zombies game, featuring object-oriented design and real-time graphics rendering.  Defend your lawn from zombie invasions by strategically placing plants with unique abilities! 

## ✨ Features

### Plants
- **Peashooter** - Shoots peas at zombies
- **Snow Peashooter** - Shoots freezing peas that slow down zombies
- **Sunflower** - Generates sun energy for planting
- **Wall-nut** - Defensive barrier with high health

### Game Mechanics
- Grid-based board system
- Resource management (sun collection)
- Score tracking
- Projectile system (peas and snow peas)
- Zombie waves with different behaviors
- Real-time game rendering

## 🛠️ Technology Stack

- **Language**: C++ (C++20 standard)
- **Graphics Library**: SFML (Simple and Fast Multimedia Library)
  - sfml-graphics
  - sfml-window
  - sfml-system
  - sfml-audio
- **Build System**: Make

## 📁 Project Structure

```
Plants-vs-Zombies/
├── src/              # Source files (. cpp)
├── include/          # Header files (. hpp)
├── build/            # Compiled object files
├── files/            # Game assets and SFML libraries
├── Makefile          # Build configuration
└── pvz.out           # Executable binary
```

### Core Components

- **Game Engine**:  Main game loop and state management
- **Board**: Game grid and tile management
- **Handler**: Event handling and game logic coordination
- **Entities**: Plants, zombies, projectiles, and sun objects
- **Settings**: Game configuration and parameters
- **Score**: Score tracking system

## 🚀 Getting Started

### Prerequisites

- C++ compiler with C++20 support (g++)
- SFML library (included in `files/` directory)
- Make build tool

### Building the Game

```bash
# Compile the project
make

# Run the game
./pvz.out
```

### Cleaning Build Files

```bash
make clean
```

## 🎮 How to Play

1. Collect sun to gain resources
2. Plant sunflowers to generate more sun
3. Use offensive plants (Peashooters) to defend against zombies
4. Use Wall-nuts to protect your other plants
5. Survive zombie waves and protect your lawn!

## 🏗️ Architecture

The project follows object-oriented programming principles with: 

- **Inheritance hierarchy**: Base `Plant` class with specialized plant types
- **Polymorphism**: Different plant and zombie behaviors
- **Encapsulation**:  Separate header and implementation files
- **Component-based design**:  Modular game entities (Board, Handler, Score, etc.)

## 📝 Documentation

For detailed project requirements and specifications, see `APS03-A5-Description.pdf`.