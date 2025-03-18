# SVG Maze Game

Can you solve the maze? Fork this repository and edit the README to move the player (blue circle) from start to finish without crossing any walls!

<svg width="300" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Maze walls -->
  <rect x="0" y="0" width="300" height="300" fill="white" stroke="black" />
  <line x1="50" y1="0" x2="50" y2="250" stroke="black" stroke-width="2" />
  <line x1="100" y1="50" x2="100" y2="300" stroke="black" stroke-width="2" />
  <line x1="150" y1="0" x2="150" y2="200" stroke="black" stroke-width="2" />
  <line x1="200" y1="100" x2="200" y2="300" stroke="black" stroke-width="2" />
  <line x1="0" y1="100" x2="150" y2="100" stroke="black" stroke-width="2" />
  <line x1="100" y1="200" x2="300" y2="200" stroke="black" stroke-width="2" />
  
  <!-- Start point -->
  <circle cx="25" cy="25" r="10" fill="green" />
  
  <!-- End point -->
  <circle cx="275" cy="275" r="10" fill="red" />
  
  <!-- Player (to be moved in your fork) -->
  <circle cx="25" cy="25" r="8" fill="blue" />
  
  <!-- Instructions -->
  <text x="10" y="330" font-family="Arial" font-size="12">Fork this repo and modify the blue circle's position to solve the maze!</text>
</svg>

## How to Play
1. Fork this repository
2. Edit the README.md file
3. Find the line with `<circle cx="25" cy="25" r="8" fill="blue" />`
4. Change the `cx` and `cy` values to move the blue circle
5. Trace a valid path from the green circle (start) to the red circle (finish)
6. Commit your changes to save your progress
7. Submit your solution by sharing your forked repo

## Rules
- The blue circle must not cross any black lines (walls)
- You must update the position to show the complete path
- The final position must be at the red circle (275, 275)

## Solutions
When you solve the maze, add your GitHub username below:
- @username1 - [Link to Solution](https://github.com/username1/maze-game)
