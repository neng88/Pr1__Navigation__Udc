# Pr1__Navigation__Udc


## Introduction

This project is the first project in Udacity's Deep Reinforcement Learning Nanodegree. In this project, a trained agent navigates and collects bananas in a large square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  


## State space
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Thus, the agent needs to learn how to best select actions.  Four actions are available:

- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.
