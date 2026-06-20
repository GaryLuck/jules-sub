Write a complete, single-file HTML5 game called "Deep Sea Explorer" using HTML, CSS, and pure JavaScript inside a canvas element. The game is for a 6-year-old, so it must be bright, visually exciting, and forgiving.

Key Requirements:
1. Canvas Setup: Fullscreen on an iPad with a beautiful deep-blue gradient background.
2. Player Submarine: 
   - Draw a yellow submarine using basic canvas shapes (rectangles, circles for portholes, a propeller).
   - Controls: Holding or pressing applies upward thrust (buoyancy). Releasing it lets gravity gently pull the sub down. 
   - Keep the submarine fixed on the left side of the screen (X position), moving only vertically.
3. Procedural Environment:
   - The ocean scrolls from right to left to simulate forward movement.
   - Spawn regular gentle bubbles rising from the bottom.
   - Spawn colorful fish swimming from right to left at random heights.
   - Spawn glowing treasures (starfish, gold coins, or gems) to collect.
4. Kid-Friendly Mechanics:
   - NO Game Over from crashing. If the sub hits the top or bottom boundaries, just bounce gently.
   - When the sub touches a treasure, create a juicy particle explosion effect (burst of tiny colorful circles) and play a simple procedural sound effect using the Web Audio API (a nice 'ping' or 'bloop').
   - Track a "Treasures Found" score prominently at the top with large text.
5. Code Structure: Single clean file, standard requestAnimationFrame game loop, fully commented state management for player, background objects, and particles.