# SVG Maze Game

This is a static maze. Fork this repo and modify the SVG to solve the maze!

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
```
