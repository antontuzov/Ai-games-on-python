How It Works
The AI is trained using the NEAT algorithm, which evolves a population of neural networks to maximize the fitness score (in this case, surviving longer and avoiding pipes).

Key Concepts:
Bird Class: Handles bird movement, jumping, and animation.
Pipe Class: Handles the movement and collision of the pipes.
Base Class: Creates the illusion of a moving ground.
NEAT Algorithm: The neural networks evolve over generations, with each bird in the population representing a different neural network. Over time, birds that survive longer are rewarded, and their "genes" are passed on.
NEAT Configuration:
config-feedforward.txt: This file contains the configuration settings for the NEAT algorithm, such as population size, fitness thresholds, mutation rates, and neural network parameters.