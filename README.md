

# Windmill Village - OpenGL 2D Project

## Overview
The Windmill Village project is a 2D OpenGL simulation developed in Code::Blocks IDE. It features a rural scene centered around a windmill with various environmental elements, such as moving clouds and rotating wind turbines. This project explores transformations, rotations, and color contrast to create a visually engaging simulation.

## Table of Contents
1. [Objective](#objective)
2. [Features](#features)
3. [Getting Started](#getting-started)
4. [Project Structure](#project-structure)
5. [Usage](#usage)
6. [Code Details](#code-details)
7. [Future Work](#future-work)
8. [Contributors](#contributors)

## Objective
- Create a realistic OpenGL-based 2D village scene centered around a windmill.
- Implement transformations and rotations to simulate moving clouds and rotating turbines.
- Use polygons for different shapes and apply color contrast for visual enhancement.

## Features
- **2D Environment:** Includes objects like hills, trees, houses, wind turbines, and clouds.
- **Animated Elements:** Clouds move across the scene, and wind turbines rotate.
- **Color Contrast:** Custom color schemes applied for a more realistic look.
- **Basic Transformations:** Use of OpenGL functions for translation and rotation.

## Getting Started
### Prerequisites
- Code::Blocks IDE
- OpenGL library installed

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/WindmillVillage.git
   ```
2. Open the project in Code::Blocks.
3. Build and run the project to start the simulation.

## Project Structure
```
WindmillVillage/
├── main.cpp                # Main code file
├── objects.h               # Functions for individual objects
└── README.md               # Project documentation
```

## Usage
- The project can be run through Code::Blocks. After building, the simulation window will display the Windmill Village scene with animated clouds and wind turbines.

## Code Details
### Key Functions
- **Translations & Rotations:**
  ```cpp
  glTranslatef(500, 0, 0);
  glRotatef(spin, 0, 0, 1);
  ```
- **Cloud Model:** Uses circles to create cloud shapes.
- **Hill and Tilla Models:** Various polygonal shapes for hills and field elements.
- **House and Windmill:** Complex shapes composed of polygons with color variations.

### Main Elements
- `main.cpp` handles rendering and transformation functions.
- Functions for individual elements (cloud, hill, windmill) are defined separately for modularity.

## Future Work
- Add sunrise and sunset effects by changing sky color.
- Add elements like a cattle ranch.
- Implement shadow effects using shearing for more realism.

## Contributors
- **Mahathir F Nabil** 
- **Faria Afroz Muskan** 

