# SVG Color Puzzle

Color the shapes following the rules to create a beautiful pattern!

<svg width="400" height="400" viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <!-- Background -->
  <rect width="400" height="400" fill="white"/>
  
  <!-- Shapes to color -->
  <circle cx="100" cy="100" r="50" stroke="black" stroke-width="2" fill="none" id="circle1"/>
  <circle cx="300" cy="100" r="50" stroke="black" stroke-width="2" fill="none" id="circle2"/>
  <circle cx="100" cy="300" r="50" stroke="black" stroke-width="2" fill="none" id="circle3"/>
  <circle cx="300" cy="300" r="50" stroke="black" stroke-width="2" fill="none" id="circle4"/>
  
  <rect x="150" y="50" width="100" height="100" stroke="black" stroke-width="2" fill="none" id="rect1"/>
  <rect x="50" y="150" width="100" height="100" stroke="black" stroke-width="2" fill="none" id="rect2"/>
  <rect x="250" y="150" width="100" height="100" stroke="black" stroke-width="2" fill="none" id="rect3"/>
  <rect x="150" y="250" width="100" height="100" stroke="black" stroke-width="2" fill="none" id="rect4"/>
  
  <polygon points="200,25 225,75 175,75" stroke="black" stroke-width="2" fill="none" id="tri1"/>
  <polygon points="25,200 75,225 75,175" stroke="black" stroke-width="2" fill="none" id="tri2"/>
  <polygon points="375,200 325,225 325,175" stroke="black" stroke-width="2" fill="none" id="tri3"/>
  <polygon points="200,375 225,325 175,325" stroke="black" stroke-width="2" fill="none" id="tri4"/>
</svg>

## Color Puzzle Rules
1. No adjacent shapes can be the same color
2. Use only these colors: red, blue, green, yellow, purple, orange
3. Circles can only be colored blue or green
4. Rectangles can only be colored red or yellow
5. Triangles can only be colored purple or orange

## How to Play
1. Fork this repository
2. Edit the README.md file
3. Add fill colors to shapes by changing `fill="none"` to `fill="color"`
4. Example: `<circle cx="100" cy="100" r="50" stroke="black" stroke-width="2" fill="blue" id="circle1"/>`
5. Follow all the coloring rules
6. Commit your changes to see your progress

## Your Progress
- Shapes colored: 0/12
- Rules followed: Yes/No
