# CVZ-Zombie-Shooter-Game

CVZ: Cube vs Zombies is an interactive shooting game built from scratch using C and the SDL2 library. This is a fun action-packed and challenging game in which you must survive against incoming swarms of various enemies and gain as many points as you can!

 We built this as a Major Project in our introduction to computer-science course (ICS-1010) in IIT Jodhpur.



## Features

1. Main Menu and Pause Menu to provide a more interactive experience.

2. Theme Music to maintain the game atmosphere.

3. Player movement using W, A, S, D keys and either of their combination for diagonal movement.

4. Collision detection with maze walls and doors.

5. Enemies with different characteristics(damage, points dropped, speed) (Zombies, Witches, Bosses).

6. Health, points and ammo system.

7. Randomly spawning treasures with claimable loot.

8. Allows Room Change, when the player reaches a certain amount of points.



## Requirements and Setup

1. You must have gcc/mingw installed on your system.

2. To compile and run the game, you need to have SDL2 library installed on your system. Follow the steps below:

    Install SDL2: Download SDL2 library from the official website and follow the installation instructions for your platform.
    https://wiki.libsdl.org/SDL2/Installation

3. Clone the repository: Clone this repository to your local machine using Git:
git clone <repository_url>

4. If you're facing linker issues , include sdl- mixer,ttf and image libraries within the game folder with the main.c file

## Compilation

1. Compile the code: Navigate to the cloned directory and compile the code using a C compiler. For example, using GCC:

    Command prompt:

    gcc -o CVZ main.c -lSDL2 -lSDL2_image -lSDL2_ttf

2. Run the game: After successful compilation, run the game executable:

    Command prompt:

    ./CVZ


## Game Instructions
  1) Game starts by giving player 100 ammo and 0 points initially.

2) There are 3 types of enemies : white(skeleton), purple(witch),red(boss)-> their stats and points vary from lowest to highest.
   
3) Press W,A,S,D for movement in up, left, down and right directions respectively. You can use their combinations for diagonal movement.
   
4) Use the spacebar key to shoot.

5) You'll get random treasure drops , Press 'F' to claim: It might give you some damage , health , ammo or points.

6) If you're in any room , and you need a breathing space and want to escape the enemies you can escape the room by unlocking the new one -> go at centre of any side of the screen and Press 'G' and 1000 points will be deducted from you and you'll be in another room.

7) Press the escape key to pause the game.
   
8)  This game is an infinite shooter , so it goes on till you survive.



## 🔗 Contributions
https://github.com/AayushBade14

1. Idea of the Project
2. Player Movement
3. Player and enemy damage system
4. Shooting system
5. Game menu system
6. Health system
7. Screen shake system


https://github.com/Satvik0110

1. Random Enemy Spawning based on fixed probability
2. Enemy Movement and Player Targetting System
3. Doors and Unlockable Maps System
4. Loot Box Spawning and Claiming System
5. Defining of Collisions
6. Ammo System

https://github.com/tkciitj

1. Points System
2. Text Rendering using ttf
3. Images and Sprites Rendering and Animation.




https://github.com/shashankparchure
1. Audio Rendering
2. Bugs and Error Fixing
   

## Demo
The video in the attached google drive link gives a demonstration of the game.
https://drive.google.com/file/d/1NOqMKViqv-DrP7XxA6XgN50ghxJyYe_k/view?usp=drive_link
