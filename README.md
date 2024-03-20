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





