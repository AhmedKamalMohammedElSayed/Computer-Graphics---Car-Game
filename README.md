<div style="text-align: center;">
    <h1>OpenGL Car Game</h1>
    <p>This project is a simple car game developed using OpenGL and C++. The goal of the game is to navigate a car through a field of randomly placed cubes without colliding with them and reach a target to win.</p>
    <img src="assests/reviwe.gif" alt="Game review" style=" display: block; margin: 0 auto;">
</div>

## Table of Contents:
1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Game Controls](#game-controls)
5. [Dependencies](#dependencies)
6. [Contributors](#contributors)



## Features

- ### Random Obstacles:
     Each game session generates a new set of randomly placed cubes.
- ### Collision Detection: 
     The game detects and responds to collisions between the car and cubes.
- ### Victory Condition: 
     Reach a specific target position to win the game.
- ### Menu Options: 
     In-game menu to choose different texture options.

## Installation

To install the project, clone the repository and install the requirements:

```bash
git clone https://github.com/yourusername/car-game.git
```
```bash
# Navigate to the project directory
cd car-game
```
```bash
# Build the Project:
g++ -o carGame main.cpp -lGL -lGLU -lglut -lGLEW -lm

```

## Usage
1. Run the Game:

```bash
./carGame
```
2. Play the Game:
Use the arrow keys to navigate the car through the field of cubes and reach the target.

## Game Controls

- ### Arrow Keys: 
    Control the car's movement.
- ### Right Mouse Button:
    Open the in-game menu to select texture options.

  
## Code Structure
- ### main.cpp:
   The main file containing the game logic and OpenGL setup.
- ### getBMP.h:
   Header file for loading BMP images as textures.
- ### getBMP.cpp:
    Implementation of BMP image loading.
   
  
## Dependencies
- ### `OpenGL`: For rendering graphics.
- ### `GLUT`: For handling window creation and input.
- ### `GLEW`: For managing OpenGL extensions.
- ### `GLM`: For mathematics operations, particularly vectors and matrices.

  
## Contributors <a name = "contributors"></a>
<table>
  <tr>
    <td align="center">
    <a href="https://github.com/AbdulrahmanGhitani" target="_black">
    <img src="https://avatars.githubusercontent.com/u/114954706?v=4" width="150px;" alt="Abdulrahman Shawky"/>
    <br />
    <sub><b>Abdulrahman Shawky</b></sub></a>
    </td>
<td align="center">
    <a href="https://github.com/omarnasser0" target="_black">
    <img src="https://avatars.githubusercontent.com/u/100535160?v=4" width="150px;" alt="omarnasser0"/>
    <br />
    <sub><b>Omar Abdulnasser</b></sub></a>
    </td>
         <td align="center">
    <a href="https://github.com/AhmedKamalMohammedElSayed" target="_black">
    <img src="https://avatars.githubusercontent.com/u/96977876?v=4" width="150px;" alt="Ahmed Kamal"/>
    <br />
    <sub><b>Ahmed Kamal</b></sub></a>
    </td>
         <td align="center">
    <a href="https://github.com/AbdullahOmran" target="_black">
    <img src="https://avatars.githubusercontent.com/u/30219936?v=4" width="150px;" alt="Abdullah Omran"/>
    <br />
    <sub><b>Abdullah Omran</b></sub></a>
    </td>
 <td align="center">
    <a href="https://github.com/MO-Nigo" target="_black">
    <img src="https://avatars.githubusercontent.com/u/103186952?v=4" width="150px;" alt="Mohammed Ali"/>
    <br />
    <sub><b>Mohammed Ali</b></sub></a>
    </td>
    <td align="center">
    <a href="https://github.com/MoAziz404" target="_black">
    <img src="https://avatars.githubusercontent.com/u/116502299?v=4" width="150px;" alt="Mohammed Aziz"/>
    <br />
    <sub><b>Mohammed Aziz</b></sub></a>
    </td>
      </tr>
 </table>
