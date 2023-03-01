## Symbols
Please note that we use k0 to k80 represent new variables in our code,  all recovered superpolys are for new variables.


## 1 Structure of the reference codes
start.py: a starting code used to call other code, which also contains the process to extract the quadratic or balanced superpolys and the and obtain addtional polynomials by combining quadratic superpolys.

mothercube.cpp : the main function to evaluate the superpoly, you can change the number of rounds or the mothercube in it.

trivium.cpp, deg.cpp, computeANF.cpp,evaluateResTrivium.cpp,key-recovery.cpp,newtrivium.cpp,utrivium.cpp,triviumtrack.cpp,triviumframework.cpp : codes for recoverying superpolys.

result: the folder is for information about superpolys

decube.txt: it contains the subcubes to be searched,  '-1 -1 19 11'  represents a subcube  with indices I\{19,11}, I is the mother cube indices.


##2 Usage of the codes 

1. Select the number of rounds and a mother cube in mother.cpp, put the subcubes you want to search in decube.txt  

2. 'python start.py' 

3. The ouput will be displayed in the folder named ''result''.