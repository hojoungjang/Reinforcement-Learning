# Reinforcement-Learning

Reinforcement Learning with OpenAI gym


## What is OpenAI Gym?
OpenAI Gym is an environment that provides diverse game-like environments where we can play around with our reinforcement agents.

![openai_gym](README_images/openai_gym.gif)

There are many environments. The cart pole environment, for example, is an environment where the goal is to balance the pole on the cart as long period as we can. If the pole tilts more than certain degrees the games is over.

For more information about OpenAI Gym:
https://github.com/openai/gym (OpenAI Gym Github)

The Wiki page on the Github page gives a detailed view on most of the environments.

## Q Learning
What is Q-learning? Q-learning is a reinforcement learning algorithm where the agent tries to learn a policy that teaches which actions to take under certain circumstances.This algorithm is based on [Markov decision process](https://en.wikipedia.org/wiki/Markov_decision_process) and here is an brief explanation of the math that goes behind Q-learning.

![q_formula](README_images/q_formula.JPG)

This is the formula used to calculate Q values and we create a table of Q values where each row is a state and each column is an possible action.

![q_table](README_images/q_table.png)

For each state, we take the action with the greatest Q value which ultimately make our agent win the game.

For more information on Q Learning:
https://en.wikipedia.org/wiki/Q-learning (Q learning Wikipedia)

## Frozen Lake with Q learning
This is one of the games I have played around with. It is called frozen lake. Basically, we want to get from 'S'(the starting point) to 'G'(the goal point). 'F' denotes the frozen part of the lake where we can step on and 'H' denotes the hole in the lake where we are not suppose to step on. If we do step on 'H', it is game over.

![frozen lake demo](README_images/frozen_lake_q.gif)

As we can see, the agent is trying to make its way to the goal point by only stepping on the frozen part of the lake. The output also displays episode number (basically the nth trial of the game), current state, action taken, total reward gained, and epsilon decay for q learning to better visualize how our agent is doing.

## Deep Q Learning (DQN)
#### TODO: Add the rest of the topics...
