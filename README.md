# Traveling-Salesman-Problem-with-Genetic-Algorithm

# Project's aim
The aim is finding a solution to the traveling salesman problem. TSP is a NP-hard problem, it has been proved that for large-size TSP, 
it is almost impossible to generate an optimal solution within a reasonable amount of time. 
Creating a genetic algorithm can find near-optimal solutions in a short period of time.

# Technologies
* Programming language: JAVA
* Tool: Eclipse

* To check if results were right, were used code written in Python (not included in this repository).

# Solution of TSP
To create TSP genetic algorithm were written:
* Tournament selection and roulette wheel selection (Both are implemented but tournament selection is used because it gives better results.)
* Several types of crossover: PXM, CX, OX, UOBX
* Mutation by swap and mutation by inversion (Better results gives mutation by inversion.)

# Launch
The repository includes only a code written with JAVA. My purpose is to show my example of creating TSP genetic algorithm. 

File "berlin52_txt" is a sample file with distances between cities. File "berlin52_txt" is to test working an TSP genetic algorithm. 
In file "berlin52_txt" is written a sample result reached by running the JAVA code.
"JAVA_code_TSP" could be runned by pasting the code to a JAVA tool (for example Eclipse) and by setting a proper local path to testing file ("berlin52_txt") in the code. 
