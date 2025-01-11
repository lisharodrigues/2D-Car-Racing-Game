# 2D Car Racing Game

This is a simple 2D car racing game developed using C programming language.

## Features

* **Gameplay:**
    * Race against AI-controlled cars.
    * Increase speed as you score points.
    * Avoid collisions with enemy cars.
    * Game over upon collision.
* **Menu:**
    * Play
    * Controls
    * High Scores
    * Customize 
        * Car Shape
        * Theme
    * Credits
    * Exit
* **High Scores:**
    * Track and display top 5 high scores.
    * Enter your name to be included in the high scores list.
* **Customization:**
    * Change the appearance of your car.
    * Select different color themes.

## Technology Stack

* **Programming Language:** C
* **Graphics Library:** Turbo C++ Graphics Library (BGI)
* **Data Structures:** 
    * Structures for storing car positions, player details, and high scores.
* **File Handling:** 
    * Reading and writing game data (player name, car shape, color theme) from/to a binary file.
    * Reading and writing high scores to/from a binary file.

## Game Logic

* **Car Movement:** 
    * Player car movement is controlled using arrow keys.
    * Enemy cars move at a constant speed and are randomly positioned.
* **Collision Detection:**
    * Collision between the player's car and enemy cars is detected using bounding box checks.
* **Scoring:**
    * Points are awarded based on distance traveled.
    * Speed increases gradually as the score increases. 
* **High Score Handling:**
    * High scores are stored in a file.
    * New high scores are added to the list and the list is sorted.

## Customization

* **Car Shape:** Players can choose from a variety of car shapes.
* **Color Theme:** Players can select different color schemes for the game background and elements.

## Installation and Setup

1. **Install Turbo C++:** If not already installed, download and install the Turbo C++ compiler and IDE.
2. **Compile:** Open the source code file in Turbo C++ and compile the project.
3. **Run:** Execute the compiled executable file.

## Contributing

Contributions are welcome! Please feel free to fork this repository and submit pull requests.

