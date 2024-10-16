# GeneticAlgorithmsTutorial

Edward Liu

Genetic Algorithms Tutorial for CSCI 6380 Data Mining

https://docs.google.com/presentation/d/150Iu9aCCKkSNd9V_VgQcN5-u-vFNS5f8x7j8Y0hToEY/edit?usp=sharing

https://www.geeksforgeeks.org/genetic-algorithms/

Dependencies: random

global POPULATION_SIZE: Population size for each generation

global GENES: Valid genes - letters, numbers, and some special symbols

global TARGET: Target string to be generated

class Individual: Class representing individual in population

  __init__: init function for class object
  
  mutated_genes: mutation operator
  
  create_gnome: chromosome creation operator

  mate: crossover operator

  cal_fitness: fitness assignment operator

main: driver code
