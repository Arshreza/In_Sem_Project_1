# In_Sem_Project_1
# Snake game
This is our first project. It is an entertaining and fun game called 'SnakeGame'.

## Table Of Content
1.Introduction 

2.Features

3.Installation

4.Usage



## Introduction

Our project is on the snake game which is a classic arcade game where the player controls a snake that grows in size as it consumes fruit. The game ends if the snake
collides with itself or the boundaries of the play area.

## Features


![Screenshot 2025-02-05 171105.png](<https://media-hosting.imagekit.io//2cc9012a0852456b/Screenshot 2025-02-05 171105.png?Expires=1833364247&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=aRbvSZRBiwh5fVb5Labl6KdHFXXkHlvKobEEuezY2yvXzs221sO7lAtLOYtBgXFCBcez-3cn3ZCtEF~yBleOzeW5AYSLS5EO9GtEXIbBz3xUuqVK4tIUQ35Id5iyDMQHIKc3R0BnHP31mzhMndX-KheJd7lFwMCrvAZZmqWenSTQLuU387cur21i4ed~INjBgvMpJtUKIDqk7W1R1~gj2UD10ZBoIzAsZZIZuoTtgfXePMFskbkx0S6CXbTAN-o5z5~907TKxdGffP7svDcFjnDPPfHmoug1rsnfBu9OOL1o5ruBXknwqLLlRWznidB5QB-ULqwqFpON1AXEjcdzjw__>)

- Terminal based UI and it doesn't require any external graphics library.
- It has RESTART and QUIT option.
- It also displays HIGHEST score.
- It also displays live score.

## Requirements
- Windows OS.
- C++ compiler.
## Data Structure Analysis 
We have used Deque(Double-ended queue) as the data structure to represent snake's body because it allows faster insertion and removal of body from both the ends. The other data structure is 2D-Array to make the play area of the game. We have used two classes namely point class and snakegame class. Point class is used for coordinates on the playarea for snake and fruit. Snakegame class is used for all the logic of game, random generation of fruit in the form of methods(functions).


## Installation
- Download code from github link
~~~bash
https://github.com/Arshreza/In_Sem_Project_1.git
~~~


- Open terminal and go to the source code.
- Use this command to compile and run the code.

~~~bash
  g++ -o snake snake.cpp
~~~
~~~bash
 snake.exe
 ~~~

## Usage

### Controls

1.You can move snake by W/A/S/D keys.




~~~bash
w = UP
a = Left
s = Down
d = Right
F = Fruit
r = Restart 
q = quit
~~~


### How to play

- Compile in c++ compiler and run.
- Use W/A/S/D keys to control snake's direction.
- Eat fruit to grow longer and increase your score.
- Try to avoid hitting the borders or snake's own body; otherwise the game will end.

 
