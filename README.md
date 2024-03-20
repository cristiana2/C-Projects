# Saddle Point
This C++ program is designed to find saddle points in a given matrix. A saddle point in a matrix is an element that is both the minimum in its row and maximum in its column, or vice versa.

Here's a description of how the program works:

Input Matrix: The program first takes input for the size of the square matrix (m) and then reads the elements of the matrix from the user.

Display Matrix: After reading the matrix, the program displays the input matrix to the console.

Find Saddle Points: The program iterates through each row of the matrix. For each row, it finds the minimum element (min) and its position (pos[0][0] and pos[0][1]) within that row. Then, for each column corresponding to the position of the minimum element, it finds the maximum element (max) and its position (pos[1][0] and pos[1][1]) within that column.

Check for Saddle Points: If the minimum element (min) in a row is equal to the maximum element (max) in its corresponding column, and their positions match, then a saddle point is found. The program prints the position of the saddle point and its value.

Output: The program continues this process for all rows of the matrix, and if any saddle points are found, their positions and values are printed to the console.

Termination: Once all rows are processed, the program terminates.

The program aims to efficiently identify saddle points within a given matrix, providing their positions and values as output.

# First_missing_positive_integer

This C++ program aims to find the smallest positive integer missing from an array of integers. 

Input: The program first takes input for the size of the array (n) and then reads the elements of the array from the user.

Array Initialization: A vector v of size n is created to store the elements of the array.

Search for Ones: The program iterates through the elements of the array to check if the integer 1 is present. If found, the variable found is set to true.

Find Smallest Positive: If the integer 1 is found in the array, the program enters a loop to find the smallest positive integer missing from the array. It initializes smallest_positive to 1 and iterates through each positive integer, incrementing smallest_positive until it finds a positive integer that is not present in the array.

Output: Once the smallest positive integer missing from the array is found, it is printed to the console.

Termination: The program terminates after printing the smallest positive integer missing from the array.

In summary, this program efficiently identifies the smallest positive integer missing from a given array of integers by iterating through the elements and searching for missing integers in a sequential manner.

# Graph Coloring
This C program is designed to solve the graph coloring problem using a depth-first search (DFS) algorithm. Here's a breakdown of how the program works:

Input: The program takes input for the number of nodes (node_number) and the number of edges (edge_number). It then reads the edges between nodes from the input.

Initialization: Arrays are initialized to store information about visited nodes (fr array), node colors (colors array), and the adjacency matrix representing the graph (edge_matrix).

DFS Algorithm: The DFS function (dfs) performs a depth-first search starting from the given node (in this case, node 1). It marks visited nodes, explores adjacent nodes recursively, and assigns colors to nodes based on the colors of their adjacent nodes. If adjacent nodes have the same color, the color of the current node is incremented.

Initialization Functions: The initFr function initializes the fr array to mark all nodes as unvisited. The initColors function initializes the colors array, assuming all nodes initially have the same color.

Main Function: In the main function, the program initializes data structures, reads edges from input, calls the DFS function to traverse the graph and determine the number of colors needed to color the graph nodes properly.

Output: After DFS traversal, the program prints the number of colors needed to color the graph nodes properly.

In summary, this program determines the minimum number of colors needed to color the nodes of an undirected graph such that no two adjacent nodes have the same color, using a depth-first search algorithm.

