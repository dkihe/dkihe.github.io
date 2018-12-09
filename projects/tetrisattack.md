---
layout: project
type: project
image: images/tetrisattackpic.png
title: Tetris Attack Clone
permalink: projects/tetrisattack
# All dates must be YYYY-MM-DD format!
date: 2018-04-05
labels:
  - Godot
  - GDScript
summary: A clone of the SNES game 'Tetris Attack'
---

<img class="ui medium right floated rounded image" src="../images/tetrisattack.png">
This project was created using a game engine called Godot.  Godot uses it's own language that is very similar to python called GDScript.  

This project was created using a game engine called Godot.  Godot uses it's own language that is very similar to python called GDScript.  

Tetris Attack is a puzzle game for the SNES.  It was also known as "Panel de Pon" in Japan and also goes by the name of "Puzzle League" or "Puzzle Challenge".  The player controls a cursor which switches the position of two blocks.  Matching 3 or more blocks of the same color destroys the blocks and sends garbage blocks to the other player in competitive play.  The player loses once their blocks reach the top of the play area. 

The future of the Puzzle Challenge(or Tetris Attack) series is not clear.  Recently it was featured as a small mini-game in the "Animal Crossing" series.  As a fan of the series, I decided to try and make my own clone of it.  It was hard to find any kind of help in making this clone because the series is not very popular.  

This was a solo project with the goal of learning the Godot engine.  While making this project I learned a lot about game development.  Since there are not many tutorials on this kind of game, and since Godot is still fairly new, I was left on my own for the most part.  I learned a lot on how to manage dictionaries and arrays for a game.  The grid is simply a 2D that updates as the blocks move.  The blocks also move slowly upward, so I had to make sure that the game updated the position of the blocks as soon as they arrive.  I had to make sure the blocks had their positions locked or else the player could cause blocks to overlap if they swap blocks at the same time it changes position vertically.  

Currently the game is still unfinished.  It was challenging for me to get to it's current point without help.  The only things implemented are the swapping of blocks, rising random blocks, and gravity.  Things like destroying blocks after they match, a losing condition, and other things are still missing.  Gravity has been implemented, but it isn't a perfect replica of the original game.    
