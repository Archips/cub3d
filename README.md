# cub3D

![cub3D-demo](https://github.com/Archips/cub3d/blob/main/cub3d_hd.gif)

Based on the famous game Wolf3D, Cub3D is a graphical programming endeavor designed to create a realistic 3D graphical representation of the inside of a maze from a first-person perspective. It leverages the principles of Ray-Casting to accomplish this task. The project aims to enhance programming skills by focusing on rigor, C language proficiency, basic algorithms, and information research. Additionally, it provides an opportunity to delve into graphic design concepts such as window management, color handling, event handling, and shape rendering.

## Score

-  110%

## Project Highlights
- **Graphics with Ray-Casting:** The core objective of this project is to generate a 3D graphical representation using Ray-Casting techniques, offering a visually immersive experience.

- **Smooth Window Management:** The program ensures smooth window management, including switching to different windows, minimizing, and more.

- **Texture Mapping:** Different wall textures are displayed based on the orientation of the wall (North, South, East, West), enhancing the visual appeal of the maze.

- **Customizable Colors:** Users can set distinct colors for the floor and ceiling, allowing for creative customization.

- **Keyboard and Mouse Interaction:** The program responds to keyboard input (arrow keys for looking, WASD keys for movement) and mouse interaction (closing the window), offering an interactive gameplay experience.

- **Scene Configuration:** Users can configure the scene by providing a scene description file with specific elements like textures and colors.

## Usage
1. Clone the repository to your local machine [macOs version](https://github.com/Archips/cub3D_macos) | [linux version](https://github.com/Archips/cub3D_linux). 
2. Compile the program using the provided Makefile.
3. Run the program with a map file in the `.cub` format as the first argument.
   `./cub3D path_to_scene.cub`
4. The program will display the scene in a graphical window.
5. To close the window and exit the program, either press the "ESC" key or click the window's close button.

## Keys  

  - move         `[w s a d]`
  - camera       `[up / down / left / right arrow]`
  - minimap      `[m]`
  - rays         `[r]`
  - exit         `[esc]`

## Author

[Archibald Thirion](https://github.com/Archips)  
[Clément Vidon](https://github.com/clemedon)
