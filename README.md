# Blocks World - Simple HTML Game

A simple Blocks World game implemented in **HTML, CSS, and JavaScript**. This is a small interactive educational tool to simulate the classic AI Blocks World environment.

## Features

- **Pick and Place**: Click a top block to pick it up, then click another top block or empty slot to place it.  
- **Logging**: Shows actions in real-time:
  - `holding(X)` — when picking up a block  
  - `ontable(X)` — when placing a block on an empty slot  
  - `on(X,Y)` — when placing a block on another block  
  - `handEmpty` — when your hand is empty  
  - `clear(X)` — shows top blocks that have nothing on them  
- **Colored Blocks**: Each block has a unique color (A-red, B-blue, C-green).  
- **Reset Button**: Resets the game to the starting configuration: A on C, C on table, B on table.

## How to Use

1. Open `index.html` in a modern web browser.  
2. Click on a **top block** to pick it up.  
3. Click on another top block to place it on top (`on(X,Y)`), or on an empty slot to place it on the table (`ontable(X)`).  
4. Check the log panel on the right to see all actions and state updates.  
5. Click **Reset** to restart the game.

## File Structure

