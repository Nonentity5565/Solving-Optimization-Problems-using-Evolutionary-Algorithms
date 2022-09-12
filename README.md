# Computational-Intelligence-Assignment1
***
## Assignment Description
Students of Computational Intelligence (CSC3034) at Sunway University were tasked with two problem statements and must employ artificial intelligent algorithms to find the solution and solve them.
---
### Problem 1: Optimal Seating Arrangements
A table is provided to show the "happiness scale" of how happy a person is when seated next to another person.
| |A|B|C|D|E|
---|---|---|---|---|---
|A|0|20|20|30|25|
|B|20|0|50|20|5|
|C|10|10|0|100|10|
|D|50|5|10|0|-5
|E|-50|-30|-100|-10|0|
---
### Problem 2: Determine the ideal time to move out
Given the following factors with their respective formulas:
* Renovation level of the new accomodation (Higher = better)
* Accomodation cost (Lower = better)
* Price to be paid when leaving (Lower = better)

Students are to also develop their own fitness function and balance different priorities.

## Solution
### Problem 1 - Genetic Algorithm
Genetic Algorithm is a pattern searching algorithm based on the principles of natural selections and genetics. Each organism carries different values for each properties and breed through generations to find the best pattern.

* Result: After 10 trial runs, all result unanimously reached a total happiness of 225 with the seating arrangement set to [B, C, D, A, E].

### Problem 2 - Particle Swarm Optimization
Particle Swarm Optimization is a discovery algorithm where particles are initially dispersed onto an area and the particles slowly converge at the optimal position.

* Result: The optimal time to move out was found to be around Sunday 21:43, the combined cost for accommodation and moving will be RM 303.30 and the renovation level of the new location will be 98.8% completed.
