# GAME-DEVELOPMENT-SNAKE-GAME

COMPANY NAME -CODTECH IT SOLUTIONS

NAME -Arjun Ganpati Waghmode

INTERN ID -CT08DK949

DOMAIN NAME -C++ PROGRAMMING

DURATION -8 WEEKS(APRIL 25th to JUNE 25th 2025)

MENTOR -NEELA SANTHOSH KUMAR



✅ Overview


🐍 A classic Snake game implemented using C++ and SFML, a multimedia library for graphics and windowing.

🎮 Player controls the snake using arrow keys to collect fruit and grow longer.

🍎 Eating fruit increases the snake's length and repositions the fruit.

🧱 The game runs on a grid of 30x20 cells, each 16x16 pixels.

💻 Simple yet functional logic demonstrating game loops, rendering, and real-time input.


⚙ How It Works


🧱 1. Game Grid & Window

Grid size: 30 (width) × 20 (height).

Each cell = 16x16 pixels.

Game window = 480x320 pixels.

The game uses a tile-based system for movement and rendering.

🐍 2. Snake Representation

The snake is an array of Snake structs storing (x, y) positions.

num keeps track of the current length of the snake (starting at 4).

🍎 3. Fruit Representation

The fruit is a Fruit struct with a random (x, y) position.

Appears in a new location when eaten.

🎮 4. Input Handling

Arrow keys change the snake’s direction:

Left ⬅, Right ➡, Up ⬆, Down ⬇

Reversal is prevented (can’t go directly opposite).

⏱ 5. Game Loop & Timing

A clock keeps track of time between updates.

The Tick() function is called at regular intervals to update the game logic.

🔁 6. Snake Movement

All body parts shift to follow the head.

Head moves based on direction.

🍓 7. Eating Fruit

If the head’s position matches the fruit, the snake grows (num++).

A new fruit appears at a random position.

🔄 8. Screen Wrapping

If the snake moves off one edge, it appears on the opposite side.

No walls = infinite wrap-around grid.

💥 9. Collision Detection

If the snake runs into itself, the game shortens the snake to that point (num = i).

This acts as a "soft reset" or punishment for collision.

🖼 10. Rendering with SFML

Two textures used:

white.png for background tiles.

red.png for snake and fruit.

Everything drawn on a window using SFML sprites.


🎯 Learning Objectives

👨‍💻 1. Basic Game Development with C++

Understand how to use loops, structures, and conditionals for interactive gameplay.

🖼 2. Introduction to SFML

Learn how to create windows, load textures, and draw sprites.

Get hands-on experience with real-time input and rendering.

⏱ 3. Managing Time and Updates

Use clocks and timers to control game speed independently of hardware performance.

🧠 4. Implementing Game Logic

Practice writing custom logic for movement, growth, collision, and wrapping.

🔁 5. Event-Driven Programming

Learn how to handle keyboard input using SFML events.

🧱 6. Coordinate Systems and Grid Design

Work with a tile/grid-based approach for cleaner movement and visuals.

📚 7. Structs and Arrays in Practice

Use data structures (struct, arrays) to manage multiple game entities.





Output

![Image](https://github.com/user-attachments/assets/cfab5ab5-d0fc-44cb-bd36-a1cddbbcfb75)
