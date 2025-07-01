# ABOUT THIS PROJECT

In our childhood, nearly all of us enjoyed playing classic snake games. Now we will try to enhance it with the help of Java concepts. The concept appears to be easy but it is not that effortless to implement.

One ought to comprehend the OOPs concept in detail to execute this effectively. Furthermore, ideas from Java Swing are used to create this application. The application should comprise the following functionalities:

The Snake will have the ability to move in all four directions.

The snake’s length grows as it eats food.

When the snake crosses itself or strikes the perimeter of the box, the game is marked over.

Food is always given at different positions.

This code implements a classic Snake Game using Java's Swing framework. It's split into two main classes:

Snake.java – sets up the game window (JFrame).

Board.java – handles the game logic, visuals, input, and game loop.

# Purpose of This Code

The purpose is to build a playable Snake game using basic Java GUI programming concepts:

Handling key input

Drawing graphics

Using a timer for animations and movement

Collision detection

Game-over logic

# What Happens During Gameplay:

The game starts with a 3-dot snake.

A red apple appears randomly.

Player moves the snake using arrow keys.

Snake eats the apple → grows.

If the snake hits itself or the wall → game over.

# 3 Resource Files Needed:

To have the following image files in your resources folder:

dot.png – snake body segment

head.png – snake head

apple.png – apple

These should be placed in a directory where getClass().getResource("/dot.png") can access them, such as src/main/resources/.

# 3 Learning Outcome:

This project teaches,

Object-oriented Java programming

GUI design and event handling

Basic game development principles

