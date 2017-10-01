# Playing 2048 game with an automated bot.
Bot uses Expectimax search with depth of 4 to find the best possible move.
Project is still in progress.During testing it gave  1024 tiles all the time and 2048 tile upto <br />
60% of the games.


# Prerequisites
Game theory ,Minmax,Expectimax

# files info:
direct.py --> Expectimax implementation(all brainy stuffs in there )<br />
puzzle.py ---> Implementation of game(main file,run this file for demo)<br />
logic.py ----> logic of game progress<br />
merge.py ----->helper file for merging of matrix<br />



## demo

cd 2048-Ai
$ python puzzle.py

![webp net-resizeimage 2](https://user-images.githubusercontent.com/17298412/31058099-8a9077a4-a70b-11e7-99bb-e55cd540bb6d.png)




## Heuristics
I have used score and penalty function.
A configuration Gets a high score if it follows snake line pattern.
Weights are assigned to individual tiles.U can tweek them to get better results.
Penalty is given if u have too many empty tiles.
U can download the game interface from https://github.com/yangshun/2048-python.

### Future work
1.Getting 2048  tiles or more at higher freq.<br />
2.Using Reinforcement learning(one i am using give tiles upto only 128 :p)


