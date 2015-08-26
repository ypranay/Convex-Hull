# Convex-Hull in 2-D Plane
Implementation of Chan's Algorithm in C++ for computing Convex Hull for integer lattice points in a 2-D plane, yielding time complexity of O(n log h) where
  - n = # of lattics points
  - h = size of the convex hull set

###Input
Following is the content of the input file:
  - First Line denotes the No. of points, say N
  - Next N lines denote the points, space separated x and y coordinates respectively.
  - Sample Input:
      5
      0 0
      1 0
      3 0
      2 1
      1 1

###Output
Space separated Convex hull points for the given input
  - Sample Output for the above Sample Input:
      (0,0) (3,0) (2,1) (1,1) (0,0)

###Compile Instructions
For compiling and executing, use redirection operator '<' (for input redirection from file) and '>' (for output redirection to file). For example,
  - $g++ ChansAlgorithmforConvexHull.cpp
  - $./a.out < input > output



