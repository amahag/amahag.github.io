---
layout: post
title: Java Game Development
subtitle: Making a 2048 Replica
#cover-img: /assets/img/path.jpg
#thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [Java, JavaFX, drag-and-drop, Scratch, programming]
---

In August of 2022, I decided to build a replica of the popular game 2048. The project was a great opportunity for me to demonstrate
my programming skills while making a functional game that I had played for years. I used the JavaFX package to create a visually
appealing interface nearly identical to the original game, with cards getting lighter and darker depending on their values. I also
decided to track the number of moves made by the player and their total score, which was calculated from the total value of the cards
they had made.

One important feature I decided to implement was making the option to save the current game and reload it at another time. I did
this by generating a .dat file whenever the player saves the game. The file contains all the necessary information to recreate the game,
including the state of the board and the total number of moves. I used the Java I/O library to manage the reading and writing of the .dat
file, making it easy for players to save their progress and continue the game later. 

The highest score I've achieved on my replica is 2048 and I invite you to beat it. Check out the source code here!hyperlink it or see a few
screenshots of the game in action.



The program in action
![programInAction](/assets/img/snip1.PNG)




2048!
![2048SuccessScreen](/assets/img/withLabel.PNG)

