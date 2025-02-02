# FIRE-SPREAD-SIMULATION
A simulation of fire spread between trees will be conducted with the probability of a tree catching fire when a neighboring tree catches fire being 10%, 20%, 30%, ..., 90%. The simulation will start with 3 trees burning at certain positions. In this simulation, the flame spread method will be used. 

Description

This project simulates the spread of fire among trees in a forest. The simulation models fire propagation using a probabilistic approach, where each tree has a defined probability of catching fire if its neighboring trees are burning. The spread follows the von Neumann neighborhood (N, W, S, E).

Features
Simulates fire spread using different burn probabilities (10% - 90%).
Uses a cellular automaton model for fire propagation.
Visualizes the fire spread process over time.
Computes the average percentage of the forest burned for each probability value.

Model and Assumptions
Assumptions
The forest is represented as a 17×17 grid.
Fire spreads only through von Neumann neighborhood (N, W, S, E).
The simulation starts with 3 trees burning at specific positions.
There is no lightning or spontaneous tree ignition.
Trees do not regrow during the simulation.
The simulation runs for 30 timesteps.
Periodic boundary conditions are applied.
Fire Spread Model
Each tree has a probability (burnProbability) of catching fire if at least one of its neighboring trees is burning. The probability values used in the simulation range from 10% to 90%.

Results and Analysis

The simulation produces visualizations showing fire spread at different burn probabilities. The results indicate that higher burn probabilities lead to a larger percentage of the forest burning. A polynomial degree-6 curve was found to best fit the relation between burnProbability and average burned area.

Conclusion:
Higher burnProbability results in faster and wider fire spread.
At burnProbability = 90%, the forest is likely to be completely burned before 30 timesteps.
Fire spread is probabilistic, making outcomes variable for 0% < burnProbability < 100%.

Contributors

Fadhlannafis Khawarizmi K.

Gema Nadiku P.

Muhammad Ariq Fakhri

Ghaisan Zaki Pratama

M. Arif Wibisono
