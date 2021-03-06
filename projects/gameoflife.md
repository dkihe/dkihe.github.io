---
layout: project
type: project
image: images/golsmall.png
title: Conway's Game of Life
permalink: projects/gameoflife
# All dates must be YYYY-MM-DD format!
date: 2018-05-01
labels:
  - Godot
  - GDScript
summary: A clone of Conway's Game of Life
---

This project was a done while following a tutorial at [Brainjar Games](http://www.brainjargames.com/game-of-life/). After following this tutorial I was able to learn more about grid based development.  The skills I learned in this tutorial helped me develop other games such as my [Tetris Attack clone](https://dkihe.github.io/projects/tetrisattack).

The rules of the game, according to [Brainjar Games](http://www.brainjargames.com/game-of-life/), are:
  1. Any live cell with fewer than two live neighbors dies, as if caused by underpopulation.
  2. Any live cell with two or three live neighbors lives on to the next generation.
  3. Any live cell with more than three live neighbors dies, as if by overpopulation.
  4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

Making this game taught me how to work with grids.  Apparently this game is related to computer science topics such as the concept of cellular automatons and turing machines.  It was also easy to modify the game to include more cells and different initial spawning rates.  I found that increasing the cell count produced interesting results.  The picture below shows a game with a size of 100 x 100.  

<img class="ui image" src="../images/gollarge.png">


