# EEE598_NeuralQLearning_Assgn
This repository contains the implementation for Assignment 3 of EEE 598: Reinforcement Learning in Robotics. The project solves an episodic stochastic shortest-path problem using neural Q-learning, replacing the tabular Q-function from Assignment 2 with a feedforward neural network.

The implementation uses experience replay, mini-batch optimization, epsilon-greedy exploration, and a separate target network. Training is performed independently for five random seeds, followed by stochastic evaluation of each learned greedy policy over 1,000 episodes.
