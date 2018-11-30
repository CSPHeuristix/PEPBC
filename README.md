# PEPBC
Precoloring Extension Problems Benchmark in Choco (PEPBC)

The basis graph coloring problem has 100 vertices, 10 colors and 180 edges (knowledge base constraints) 
-> see file GraphColoring.java

The set of dynamic constraints in precoloring extension problems hold 10 constraints.
-> see file 150 sets of Dynamic Constraints.data

A sample line from "Dynamic Constraints.data" is given below. 
First byte is user ID, the following 100 bytes are holding initiated (non-zero values) and non-initiated (zero values) colors of each vertices. Each byte is seperated with a coma.
Foe example, in this sample line from set of dynamic constraints, vertex-4 is precolored with color code=6, and vertex-7 is precolored with color code=4, and so on and so forth.

0,0,0,0,6,0,0,4,0,0,0,0,0,0,0,0,0,0,7,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,7,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,3,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,4,0,0,0,0,3,0,0,0,0,0,0,0,5,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0
