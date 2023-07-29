### VIEW THE WORKING OF NEAT ALGORITHM(GENETIC IN NATURE)
To implement Flappy Bird using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm for reinforcement learning, we need to set up a neural network and apply the NEAT algorithm to evolve the network's weights over generations to optimize the bird's performance in the game. Here's a high-level overview of how it can be done:

1.Define the Game Environment: Set up the Flappy Bird game environment, including the bird, pipes, and ground. Implement the game logic, such as bird movement, pipe generation, collision detection, and scoring.
2.Define the Neural Network: Create a neural network that will act as the brain of the bird. The neural network should take inputs from the game environment (e.g., bird's vertical position, pipe's horizontal position, distance to the next pipe, etc.) and output actions (e.g., flap or not flap).
3.NEAT Initialization: Set up the NEAT algorithm with appropriate parameters such as population size, mutation rates, and the structure of the neural network.
4.NEAT Evolution Loop: Create a loop that runs the NEAT algorithm for multiple generations. In each generation, the NEAT algorithm evolves the neural networks by adjusting their weights to improve performance.
5.Fitness Function: Define a fitness function to evaluate the performance of each bird (neural network) in the game. The fitness function could be based on the bird's ability to stay alive longer and earn higher scores.
6.Evaluate Bird Performance: In each generation, run the game with multiple instances of the bird (with different neural networks) and evaluate their performance using the fitness function.
7.Reproduction and Mutation: Use the NEAT algorithm to select the best-performing birds and create new generations through reproduction and mutation of their neural networks.
8.Repeat: Repeat the evolution loop for a specified number of generations or until the bird's performance reaches a satisfactory level.
9.Best Bird: After the NEAT algorithm completes, select the best-performing bird (neural network) from the final generation. This bird should be the one that performs the best in the Flappy Bird game.
10.Test the Best Bird: Test the performance of the best bird in the actual game environment and observe how well it plays Flappy Bird.

By using the NEAT algorithm, the neural network's weights are optimized through generations of evolution, allowing the bird to learn and improve its performance in the game. This approach enables the bird to adapt and navigate through the pipes more effectively over time, resulting in better gameplay and higher scores.

### DEMO
https://drive.google.com/file/d/1sNxShdYrtDX3k2-aw0JZG2o5aoxE0h0U/view?usp=sharing
