# CartPole-v1
Reinforcement Learning (RL) implementation for solving the CartPole-v1 environment from OpenAI Gym. This project includes  RL algorithms like Q-learning and DQN. Train agents to balance a pole on a cart using state-of-the-art techniques

## Cart pole
![cartpole](https://github.com/ashwin232003/CartPole-v1/assets/143198668/84bce757-5a5d-45ec-be28-8b22eb470109)

This environment is part of the Classic Control environments(openAI Gym).

![image](https://github.com/ashwin232003/CartPole-v1/assets/143198668/565e37a7-6f66-4d48-837a-d75e44328fb5)

## Description
 A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The pendulum is placed upright on the cart and the goal is to balance the pole by applying forces in the left and right direction on the cart.

## Action Space
The action is a ndarray with shape (1,) which can take values {0, 1} indicating the direction of the fixed force the cart is pushed with.

![image](https://github.com/ashwin232003/CartPole-v1/assets/143198668/68a34024-d4f4-43e7-b4fd-48f08118e0fd)

## Reward 

Since the goal is to keep the pole upright for as long as possible, a reward of +1 for every step taken, including the termination step, is allotted.



