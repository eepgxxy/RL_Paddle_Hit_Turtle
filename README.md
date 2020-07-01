# RL_Paddle_Save_Turtle
Using reinforcement learning algorithm DQN from PARL to play a game called Paddle_Save_Turtle.
The goal of the game is to use a paddle to save a turtle from falling down.The turtle can move randomly, but the paddle can only move horizontally.
Details of the rules are described by the code.

This game is being slightly modified by only changing the red ball to green turtle based on the original paddle ball game from [this environment](https://github.com/shivaverma/Orbit).
All the rules of the original environment are not changed, so the benchmark should be the same.


This repository includes the user-friendly jupyter notebook version of the solution.
The code is written using [PaddlePaddle](https://github.com/PaddlePaddle). The DQN algorithm from [PARL](https://github.com/PaddlePaddle/PARL) is being used. 

After training for twice with 300 episodes for each training, the best evaluation reward of at least 466+ points per episode is achieved. 
Actually, after a few episodes of training, we hardly see the paddle misses the turtle.
The second training is based on the trained model from the first training with slightly different hyper parameters. 

![train rewards](https://github.com/eepgxxy/RL_Paddle_Save_turtle/blob/master/train.png)

![eval rewards](https://github.com/eepgxxy/RL_Paddle_Save_turtle/blob/master/eval.png)

![result](https://github.com/eepgxxy/RL_Paddle_Save_turtle/blob/master/result_3.gif)
