# Node-Removal-Optimization-with-Graph-Theory
- Name: Tochi Onwuasoanya
- Email: tonwuaso@u.rochester.edu
- 4/26/22


The purpose of this project is to build a program that reads a text file and build a graph from it. It also removes nodes by degree ("-d" argument) and by collective influence ("-r" argument). 

This project contains 3 classes, GraphLayout.java, StopContagion.java, and CollectiveInfluence.java. 

The GraphLayout class builds the graph and the adjacency list. It also prints the graph, and has the method that removes a node from the graph.

The CollectiveInfluence class makes the collective influence methods (ball and sigmaBall) for the "-r" argument, and sets up the degree methods to calculate and remove the degrees for the "-d" argument

The StopContagion class just has a method to print the graph and it also has the main method to run the code.

To run the code, the user needs to type in "-d" or "-r" along with the number of nodes they want to remove, plus the file name.

If no "-d" or "-r" arguments are given, then nodes will automatically be removed by collective influence.

If both "-d" and "-r" arguments are input, then the program will only follow the "-d" argument. Thus, it is best to do either "-d" or "-r", not both. 

Example Command Line input: java StopContagion -d 2 4 inputFile.txt
