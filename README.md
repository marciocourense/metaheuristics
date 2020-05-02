# metaheuristics
metaheuristics

this is composed of 2 exercises
A discrete optimization problem (TSP) for 2 countries 

And a continuos optimization problem of 6 algorithms

All the code is written in simple one file notebooks and execution is done, just by simply executing the notebook

Github link https://github.com/marciocourense/metaheuristics

# TSP problem
Main take aways:
As in all TSP problems, all cities must be visited exactly once. Using the shortest path possible
The algortihm used for the optimization is a Genetic Algorithm, as it is suitable for the problem at hand, is one the main algos, reviewed in the metaheuristics course. And I want to hand first hands experience with this algorithm in the exercise

The main libraries used are TSPlib95  in order to load this specific file type
 and DEAP https://pypi.org/project/deap/  as it contains Genetic algorithm using any imaginable representation
    List, Array, Set, Dictionary, Tree, Numpy Array, etc
 this was an obvious, as at the begining of this exervises I was not aware of the implications of using a tSP file

Stopping criteria: reaching the maximum nr. of iterations
Nr. of iterations: 3000

Results included at the end of each notebok

#inspirations:
https://github.com/DEAP/deap/blob/master/examples/ga/tsp.py
https://github.com/lmarti/evolutionary-computation-course/blob/master/AEC.03%20-%20Solving%20the%20TSP%20with%20GAs.ipynb
https://medium.com/@pasdan/genetic-algorithm-the-travelling-salesman-problem-via-python-deap-f238e0dd1a73


# Optimization and benchmarking of 6 different functions 
The algortihm used for the optimization is a Differential Evlotion Algorithm.
This was algorithm was chosen due to the fact it cann be easyly implemented and benchamarked.
I wanted to stick to the same algorithm for this exercise, in order to how the same algorithm behaves in different funcitons.

Stopping criteria: F(x) = 0 or Global minimum found or reaching the maximum nr. of iterations
   To further improve performance of the code, below a fitness critreria might be added in future, such as
   if after X iterations the finess hasn't improved, stop the iterations
Nr. of iterations is 3000

Results included at the end of each notebok
