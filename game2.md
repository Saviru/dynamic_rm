# SVG Maze Game

Can you solve the maze? Fork this repository and edit the README to move the player (blue circle) from start to finish!

<svg width="400" height="400" viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <!-- Background -->
  <rect width="400" height="400" fill="#f5f5f5"/>
  
  <!-- Maze border -->
  <rect x="50" y="50" width="300" height="300" stroke="black" stroke-width="2" fill="none"/>
  
  <!-- Maze walls -->
  <line x1="100" y1="50" x2="100" y2="250" stroke="black" stroke-width="2"/>
  <line x1="150" y1="100" x2="150" y2="350" stroke="black" stroke-width="2"/>
  <line x1="200" y1="50" x2="200" y2="250" stroke="black" stroke-width="2"/>
  <line x1="250" y1="150" x2="250" y2="350" stroke="black" stroke-width="2"/>
  <line x1="50" y1="150" x2="200" y2="150" stroke="black" stroke-width="2"/>
  <line x1="150" y1="250" x2="350" y2="250" stroke="black" stroke-width="2"/>
  
  <!-- Start point (green) -->
  <circle cx="75" cy="75" r="15" fill="green"/>
  
  <!-- End point (red) -->
  <circle cx="325" cy="325" r="15" fill="red"/>
  
  <!-- Player (blue) -->
  <circle cx="75" cy="75" r="10" fill="blue"/>
</svg>

## How to Play

1. Fork this repository
2. Edit the README.md file
3. Find the line with `<circle cx="75" cy="75" r="10" fill="blue"/>`
4. Change the `cx` and `cy` values to move the blue circle
5. Trace a valid path from the green circle (start) to the red circle (finish)
6. Commit your changes to save your progress

## Rules

- The blue circle must not cross any black lines (walls)
- Your goal is to reach the red circle from the green one
