#NSGA & CNSGA
This repository contains implementations of NSGA-II and CNSGA-II algorithms applied to solve two distinct optimization problems: ZDT3 and Crashworthiness Design of Vehicles for NSGA-II, and MW7 and Cantilever Beam Design for CNSGA-II.

#Algorithms
Both NSGA-II and CNSGA-II implementations consist of the following components:

Initialization: The initial population is generated randomly to kickstart the optimization process.
Evaluation: Each individual in the population is evaluated using the respective problem's evaluation function to determine its performance.
Fitness Assignment: Individuals are assigned fitness values based on their dominance ranks and crowding distances.
Tournament Selection: A selection process where individuals are chosen for reproduction based on their fitness values.
Crossover: Genetic operators are applied to selected individuals to produce offspring with combined characteristics.
Mutation: A random perturbation is introduced to some individuals to maintain diversity in the population.
Environmental Selection: The next generation population is selected based on the combined pool of parents and offspring, considering dominance and diversity.
CNSGA-II Extension
CNSGA-II extends NSGA-II by incorporating constraint evaluations into the optimization process. This ensures that the generated solutions not only optimize the objective function but also satisfy any given constraints.

#Problems
The optimization problems solved by each algorithm are as follows:

NSGA-II:
ZDT3: A benchmark multi-objective optimization problem.
Crashworthiness Design of Vehicles: Optimizing vehicle structures for crash safety.
CNSGA-II:
MW7: A multi-well oil reservoir management problem.
Cantilever Beam Design: Designing a cantilever beam subject to various constraints.
These implementations serve as versatile tools for solving multi-objective optimization problems, providing insights into the trade-offs between conflicting objectives and the exploration of feasible solutions.
