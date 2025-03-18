
## 2. Tic-Tac-Toe

A simple game of tic-tac-toe where players take turns editing the board.

```markdown name=tic-tac-toe.md
# SVG Tic-Tac-Toe

Play Tic-Tac-Toe by editing this README! Fork the repo and make your moves.

<svg width="300" height="300" viewBox="0 0 300 300" xmlns="http://www.w3.org/2000/svg">
  <!-- Game board -->
  <rect width="300" height="300" fill="#f5f5f5"/>
  
  <!-- Grid lines -->
  <line x1="100" y1="0" x2="100" y2="300" stroke="black" stroke-width="3"/>
  <line x1="200" y1="0" x2="200" y2="300" stroke="black" stroke-width="3"/>
  <line x1="0" y1="100" x2="300" y2="100" stroke="black" stroke-width="3"/>
  <line x1="0" y1="200" x2="300" y2="200" stroke="black" stroke-width="3"/>
  
  <!-- Moves - Add X's and O's here -->
  <!-- Example X: <path d="M30,30 L70,70 M30,70 L70,30" stroke="blue" stroke-width="5"/> -->
  <!-- Example O: <circle cx="150" cy="150" r="35" stroke="red" stroke-width="5" fill="none"/> -->
  
</svg>

## Current Game State
- Next turn: X

## How to Play
1. Fork this repository
2. Edit the README.md file
3. Add your move (X or O) to an empty cell
4. For X: `<path d="M[x1],[y1] L[x2],[y2] M[x3],[y3] L[x4],[y4]" stroke="blue" stroke-width="5"/>`
5. For O: `<circle cx="[x]" cy="[y]" r="35" stroke="red" stroke-width="5" fill="none"/>`
6. Update the "Next turn" indicator
7. Commit your changes
8. Wait for your opponent to make their move

## Cell Coordinates (center points)
- Top Left: (50, 50)
- Top Middle: (150, 50)
- Top Right: (250, 50)
- Middle Left: (50, 150)
- Center: (150, 150)
- Middle Right: (250, 150)
- Bottom Left: (50, 250)
- Bottom Middle: (150, 250)
- Bottom Right: (250, 250)

## Game History
- Game started by @Savirugive on 2025-03-18
