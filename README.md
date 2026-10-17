
# Data-Driven Exploration Game

## Overview

This project is a JavaScript-based first-person exploration game that simulates a three-dimensional environment using two-dimensional images. Rather than rendering a 3D environment, the game displays predetermined images based on the player's location and orientation.

The project was developed as part of a university game development course and uses JSON files to manage game states and navigation.

## Key Features

- First-person exploration using 2D images.
- Directional navigation using keyboard arrow keys.
- JSON-based state management to determine the player's current location and orientation.
- Image-based environment constructed from a Minecraft woodland mansion.

## Technical Implementation

The game uses a state-driven navigation system. Each navigable location is represented by images captured from four cardinal directions.

When the player rotates or moves, the JavaScript logic determines the appropriate state using the game's JSON data and displays the corresponding image.

This approach creates the appearance of exploring a 3D environment without requiring real-time 3D rendering.

## Asset Generation and Automation

One of the largest challenges was creating and organizing the images required for the environment.

To streamline this process, I developed an automated workflow involving:

- **Minecraft:** Used a woodland mansion as the environment for capturing images.
- **Java Mod:** Created a custom modification to automatically position the player at precise block coordinates.
- **Macro Automation:** Automated player rotation, positioning commands, and screenshot capture.
- **File Naming:** Designed a consistent naming convention to organize the directional images and associate them with game states.

This reduced the manual effort required to capture and organize the environment.

## Challenges and Lessons Learned

The project required integrating multiple tools and technologies to solve a problem that extended beyond the original game's navigation logic.

A major takeaway was learning how to break a complicated task into smaller systems, identify repetitive processes, and develop automation tools to make those processes more manageable.

The experience also strengthened my understanding of state-driven application design, debugging, and working with unfamiliar development tools.

## Technologies Used

- JavaScript
- HTML / CSS
- JSON
- Java (Minecraft modding)
- Minecraft
- Macro automation software

## Running the Project

*Instructions TBD*
  
