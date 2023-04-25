# AI_Beats_FlappyBird

Flappy Bird AI using NEAT

This is a Flappy Bird game that uses a neural network trained with the NEAT algorithm to play the game autonomously. The goal of the game is to navigate a bird through a series of obstacles by flapping its wings to avoid colliding with them.

The NEAT algorithm (NeuroEvolution of Augmenting Topologies) is an evolutionary algorithm that can evolve neural networks with complex topologies and optimize their weights to perform a given task. In this game, NEAT is used to evolve a neural network that can control the bird's actions in real-time based on the game's state.

The game is built using the Pygame library in Python, and the NEAT-Python library is used for implementing the NEAT algorithm. The game starts with a population of neural networks that play the game and their performance is evaluated based on how far they can go without colliding with any obstacles. The best-performing networks are then selected for breeding and the process repeats for a number of generations until a network is evolved that can play the game successfully.

This project includes the following files:

    flappy_bird.py: The main game file that includes the game loop and the rendering of the game.
    neat_config.txt: The configuration file for the NEAT algorithm that specifies the parameters for the algorithm.
    bird.png, pipe.png, background.png: The image files used for the game graphics.

To run the game, simply run the flappy_bird.py file in Python. The game will start automatically and the neural network will begin playing. You can adjust the parameters in the neat_config.txt file to change the behavior of the NEAT algorithm.

Enjoy playing Flappy Bird with an AI that learns to play the game using NEAT!

![FlappyBird](https://user-images.githubusercontent.com/114453891/234326045-475d636e-25bb-4214-9fb5-331e98447f49.png)
