# Simulated Annealing for Travelling Salesman Problem

This repository contains code for solving the Travelling Salesman Problem (TSP) using Simulated Annealing (SA). The TSP is a well-known NP-hard problem that seeks to find the shortest Hamiltonian cycle (a path that visits each city exactly once and returns to the starting city) among a set of cities with pairwise distances.

Simulated Annealing is a metaheuristic optimization algorithm that mimics the annealing process in metallurgy. The algorithm starts with a high "temperature" and gradually decreases it over time, allowing for "bad" moves in the beginning but gradually restricting the search to the "good" ones as the temperature cools down. SA has been shown to be an effective method for solving the TSP, especially for large instances of the problem.

## Usage
The code is written in Python 3 and requires the following dependencies: numpy, matplotlib. To use the code, simply run the `code.ipynb` file with the desired parameters. The script will generate a random instance of the TSP with a given number of cities (default 30), solve it using SA with a specified cooling rate (default 0.99), and plot the distance vs temperature curve for three different cooling rates (fast, medium, slow). The final path and distance will also be printed to the console.

## References
The code is based on the algorithm described in the following paper:

1. Kirkpatrick, S., Gelatt, C.D., and Vecchi, M.P. (1983). Optimization by Simulated Annealing. Science, 220(4598), 671-680. https://doi.org/10.1126/science.220.4598.671
For more information about the TSP and its variants, see:

2. Lawler, E. L., Lenstra, J. K., Rinnooy Kan, A. H. G., and Shmoys, D. B. (1985). The Traveling Salesman Problem: A Guided Tour of Combinatorial Optimization. John Wiley & Sons.

3. Applegate, D. L., Bixby, R. E., Chvátal, V., and Cook, W. J. (2007). The Traveling Salesman Problem: Computational Solutions for TSP Applications. Princeton University Press.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
