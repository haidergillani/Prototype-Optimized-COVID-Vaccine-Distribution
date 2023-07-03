# Prototype-Optimized-COVID-Vaccine-Distribution & SIR Simulation
Machine learning genetic algorithm for optimized vaccine distribution in UP, India, and SIR modeling. This project showcases the capacity to apply advanced optimization techniques and epidemiological models for real-world problems, combining computer science and public health in an impactful manner. The work completed here demonstrates skills in Python programming, heuristic optimization techniques (Genetic Algorithms), data analysis, simulation modeling (SIR model), and practical application of these skills in addressing a global pandemic situation. The potential impact of this project in managing disease spread and empowering strategic decision-making via efficient vaccine distribution underscores the significance of computer science skills in public health and crisis management.

## Project Overview
The project tackles the challenge of distributing COVID-19 vaccines to the 15 major cities of Uttar Pradesh (UP), India, which had major outbreaks of the virus. The objective was to find the most efficient route to transport vaccines using ground transportation to minimize travel time and reach the maximum number of people in the shortest amount of time.

A Genetic Algorithm, inspired by natural selection, was developed for this optimization problem. The algorithm generated a population of possible routes, evaluated their fitness (based on total travel distance), and iteratively improved the population by retaining the best routes (elitism), cross-breeding routes (crossover), and introducing random changes (mutation).

The optimization resulted in an ordered list of cities to visit, starting from Lucknow and moving through Gorakhpur, Varanasi, Prayagraj, and others, finally ending in Saharanpur, covering a total distance of about 2175.7 kilometers. This optimized route provided the fastest way to distribute vaccines across these 15 cities, ensuring timely vaccination and preventing further virus spread.

In addition to vaccine distribution, the project also employed a SIR (Susceptible-Infected-Recovered) model to simulate and predict the spread of COVID-19 in the state of Uttar Pradesh through sensitivity analysis for various infection and recovery rates depending upon available healthcare infrastructure and social distancing practices. The simulation made use of reported data on infection and recovery rates to visualize the trajectory of the disease spread and recovery after vaccine distribution.

## Genetic Algorithm Parameter values for optimal route
1. population_size = 50
50 individuals (routes) in each generation of the genetic algorithm.
2. elite_size = int(population_size *(0.1))
the top 10% of individuals (routes) of the population that are selected as elite based on their fitness score for reproduction in each generation are carried over to the next generation.
3. mutation_rate = 0.01
The probability of a mutation occurring during the breeding process is 1%. This represents the likelihood of a gene being randomly altered in an individual.
4. generations = 150
This means the genetic algorithm will iterate 150 times to find the optimum solution.

### Optimal Solution:
Vaccine Distribution System for the state of Uttar Pradesh, India <br>
Please visit the following 15 cities in order: <br>
['Lucknow', 'Gorakhpur', 'Varanasi', 'Prayagraj', 'Kanpur', 'Jhansi', 'Bareilly', 'Firozabad', 'Agra', 'Aligarh', 'Noida', 'Ghaziabad', 'Meerut', 'Moradabad', 'Saharanpur'] <br>
The total distance for this journey is about 2175.7 kilometers.
