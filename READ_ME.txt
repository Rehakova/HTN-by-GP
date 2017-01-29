This CD contains the master thesis as thesis.pdf

The domain specification folder contais files with domain specification and problem definition.

The HTNPlanner folder contains runnable jar file with the implementation of our algorithm.

The ecj.rar file contains the source code of our algorithm. The main class is in ec/GenericHTN folder in partialOrderPlanner.java file.

The statistic folder contains statistic information about all the experiments.
Individual experiments are in separate folders. Each such folder contains followng files:
1. best TEST NAME.txt - individual representing optimal solution of the test
2. no best TEST NAME.txt - some individual from the test, if no optimal solution was found
3. TEST NAME_1 file - list of numbers indicating when the optimal individual was found (max value if it was not found)
4. TEST NAME_2 file - statistical information about the test (number og generation, standart error squared, standart error, min, max, mean best individual)
5. TEST NAME folder with *.out2.stat files