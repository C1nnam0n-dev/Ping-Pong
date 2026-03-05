# Ping-Pong
This program is a simple Ping Pong game built using Python’s Turtle module. Two players control paddles on opposite sides of the screen and try to bounce the ball past their opponent to score points. The ball speeds up as the rally continues, making the game progressively more challenging.

# The program asks the user for:

- The program does not require typed input, but it asks players to use the keyboard to control the paddles.
- Controls:
  - Right Paddle
    - Up Arrow → Move paddle up
    - Down Arrow → Move paddle down
  - Left Paddle
    - W → Move paddle up
    - S → Move paddle down

# How the program works:

- The program creates a game window using the Turtle graphics library.
- Two paddles are created and positioned on the left and right sides of the screen.
- A ball object moves across the screen continuously.
- If the ball hits the top or bottom wall, it bounces back in the opposite direction.
- If the ball collides with a paddle, it bounces horizontally and its speed slightly increases.
- If the ball passes a paddle and reaches the edge of the screen:
  - The opposing player receives a point.
  - The ball resets to the center.
- A scoreboard keeps track of the left and right player’s scores and updates after each point.

# What I learnt:

- How to structure a project using multiple Python files and classes.
- How object-oriented programming (OOP) works in Python.
- How to use the Turtle graphics library to build interactive programs.
- How to detect collisions between objects.
- How to use keyboard listeners to control objects in a game.
- How to create a game loop and control game speed.
