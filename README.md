# **Snake Game on Terminal (C++)**
A classic Snake game implemented in C++ using a terminal-based UI library. The game runs in the console and allows the player to control a snake that grows as it eats food while avoiding self-collision.

## **Demonstration**
![image](https://github.com/user-attachments/assets/a5ff9937-eafe-4dec-be90-a2df3adb9231) 

## **Getting Started**
### **Prerequisites**
- A C++ compiler (e.g., `g++`)
- A Linux or Windows system with a terminal
- Basic familiarity with C++ and terminal-based applications

### **Setup**
1. Clone this repository:
   ```bash
   git clone https://github.com/AbaanKhan970/Snake-Game.git
   cd SnakeGame
   ```
2. Run the game using the project executable:
   ```bash
   ./Project.exe
   ```

## **Gameplay Overview**
The game is played within a bounded board where the player controls a snake that moves in four directions (Up, Down, Left, Right). The snake eats food to grow in length while avoiding collisions with itself.

### **Controls**
- `W` - Move Up
- `A` - Move Left
- `S` - Move Down
- `D` - Move Right
- `ESC` - Quit the Game

### **Game Mechanics**
- **Food Generation:** The game generates food in a random location that the snake must reach to grow.
- **Self-Collision Detection:** The game ends if the snake collides with itself.
- **Screen Wrapping:** The snake appears on the opposite side of the screen if it crosses the boundary.

## **Code Structure**
The implementation follows an object-oriented approach, splitting game logic into various modules.

### **Core Components**
#### **GameMechs.cpp / GameMechs.h**
- Handles game mechanics like input handling, score tracking, and food generation.
- Uses an internal flag system to track when the game should exit or when the player loses.

#### **Player.cpp / Player.h**
- Manages the snake's movement and self-collision detection.
- Updates the direction based on player input and moves the snake accordingly.

#### **objPos.cpp / objPos.h**
- Represents the position of objects in the game, such as food and snake segments.
- Includes utility functions for setting and retrieving positions.

#### **objPosArrayList.cpp / objPosArrayList.h**
- Implements a dynamic array list to manage the snake's growing body.
- Supports insertion, removal, and retrieval of snake body segments.

#### **MacUILib.c / MacUILib.h**
- Provides terminal-based rendering functions to display the game.
- Supports input handling and screen clearing.

#### **Project.cpp**
- The main entry point of the program.
- Initializes game components and runs the game loop.

## **Features**
✔️ Terminal-based interface for a retro gaming experience  
✔️ Dynamic snake growth with real-time movement  
✔️ Randomized food placement  
✔️ Self-collision detection to end the game  
✔️ Simple and clean object-oriented design  

## **Future Improvements**
🚀 Add difficulty levels with increasing speed  
🚀 Implement more food types with different effects  
🚀 Add Data Structures and Algorithms concepts learnt in courses  

