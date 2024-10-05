# NEAT-based Car Avoidance and Coin Collection Game

This Python project uses the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to evolve a car AI that avoids obstacles (rocks) while collecting coins. The AI learns to navigate using a feed-forward neural network that controls the car's left and right movement based on the environment.

## Features
- **Obstacle Avoidance**: The car must avoid randomly placed rocks on the road.
- **Coin Collection**: The car is rewarded for collecting coins placed on the road.
- **AI Evolution**: The NEAT algorithm evolves the neural network to improve car movement over multiple generations.
- **Real-Time Visualization**: Displays the car's movements, obstacles, coins, and score in real-time using the Pygame library.

## Prerequisites

To run the project, you'll need the following dependencies:

- **Python 3.x**
- **Pygame**: For game visualization.
- **NEAT-Python**: For implementing neuroevolution.

You can install the dependencies using the following commands:

```bash
pip install pygame neat-python
