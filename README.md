# Introduction of repo
This repo inplement a Gobang game as my homework to a BUAA programing course. The game will be written in python and use modules like pygame, sqlite3 and etc. All are welcome to enjoy the game or improve it after I finish my homework. And of course you can help me with my homework if you want. ( :

# Software function

## Basic function

> 1.Play Gobang game in one PC
>
> 2.Get the rules of Gobang before play

## Extension function

These function is challenging for me to inplement because of the homework time limit, but I will try my best.

> 1.Use SQLite3 to record the Gobang games that players played
>
> 2.Provide some epic endgame to improve players' Gobang level 
>
> 3.Use socket to help players playing in LAN
>
> 4.Create a Gobang AI to play with players

# Code instruction

## Environment in my PC

> python:3.7.8
>
> pygame:1.9.6
>
> VScode:1.48.2

## Document instruction

>Chess.py:include the chess class
>
>Utility.py:include some universal function
>
>Main.py:include the main function, the game starts here
>
>StartGame.py:just used to print the main menu
>
>PlayInOnePc.py:implement the function of playing in one PC
>
>PlayInLAN.py:implement the function of playing in LAN
>
>WatchVideo.py:implement the function of watching video through browser

# Known problem

> 1.(PlayInLAN mode)Because the program uses UDP to communicate, player may wait the opponent to operate. In this case, the program will be unresponsive.
>
> 2.(all mode)Because the program doesn't clear the queue of pygame.event, some unexpected operation may be left in the queue which can cause trouble.