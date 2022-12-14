# Artificial Intelligence Project Collection
This repository is filled with academic and personal projects. I wanted to showcase them, but they do not have enough substance to be within their own repositories. I might return to each project at some point to add to or retry them. Some of these projects have also inspired me to create a potentially larger project involving them all.

## nltk-chatbot
For this project I experimented with the NLTK Python library to a rudimentary question and answer chatbot. The purpose of this project was to look at the NLTK and see what I could apply to another major project I'm working on, which is also a chatbot, but one that I want to potentially converse with the user.

## nn-activation-function-tests
This project was an experiment with neural networks. It begun with an object oriented approach, where I had a layer class and a neural network class. I was following a Sebastian Lague video to gain a understanding of neural networks in general. Once I figured that out, I decided it would be the perfect opportunity to learn Google's Jax module. That meant I had to convert my object oriented apporach into a procedural approach, since Jax requires pure-stateless functions to use jit. For the sentiment analysis project I'm working on, I'm hoping to combine the class and procedural approach.

## ride-share-reflex-agent
I was assigned this project for my Intro to AI course. The idea was to create a reflex agent to handle cars for a ride sharing application. The agent's job was to pick up passengers and then drop them off. The agent prioritizes picking up passengers, and when 1 car is assigned multiple pickup or drop-offs, the shortest path is generated using a recursive search. The passengers are assigned based on the closest car to them.

## tic-tac-toe-markov-agent
For this assignment, I was tasked to create a Markov decision making model to play tic-tac-toe. In order to automate the testing and gameplay, I also needed to create a reflex agent to mimic the decision making of a human player. Eventually, I found that using the Markov decision making model wasn't especially beneficial in a game like tic-tac-toe, since the landscape was ever changing. The model became a glorified reflex agent. I would like to try this again. The Markov agent would be put into the into a landscape where it would benefit from being a Markov agent. I would also want to try to make a min-max/alpha-beta pruning agent for the tic-tac-toe langscape.

## tsp-genetic-algorithm
This assinment, I was required to make a genetic algorithm to find a solution to the travelling salesperson problem. I found difficulty implementing the genetic algorithm. I found that the problem would get stuck on being barely better than average. I would like to come back to this now that I have a better understanding of genetic algorithms.
