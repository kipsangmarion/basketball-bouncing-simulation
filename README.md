# Bouncing Ball Simulation

This project simulates the bouncing motion of a free-falling ball and plots the height against time using appropriate kinematic equations from physics.

## Description

The simulation calculates the motion of a bouncing ball based on the initial height provided by the user. It iteratively computes the height, velocity, and time at each time interval until the maximum height after bouncing falls below the specified minimum height.

The simulation uses the following physics principles:
- Acceleration due to gravity: 9.8 m/s^2
- Kinematic equations: The time taken to reach the ground, the velocity at impact, and the velocity after bouncing are calculated using the kinematic equations for vertical motion.

The resulting height and time values are then plotted on a graph to visualize the relationship between height and velocity during the bouncing motion.

## Getting Started

### Dependencies

The simulation requires the following dependencies:

- Python (version 3.6 or higher)
- matplotlib library

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/kipsangmarion/basketball-bouncing-simulation.git
   ```

2. Change to the project directory:

   ```
   cd basketball-bouncing-simulation
   ```

3. Install the required dependencies:

   ```
   pip install matplotlib
   ```

### Usage

1. Open the notebook and run all cells

2. The simulation will calculate the bouncing motion and display the resulting graph showing the height against velocity.

3. Modify the parameters in the `simulation_run` function to customize the simulation as desired.


The simulation will display a graph showing the height against time during the bouncing motion of the ball.

## Acknowledgments

This simulation project is inspired by the principles of physics and aims to provide a visual representation of the bouncing motion of a free-falling ball.

