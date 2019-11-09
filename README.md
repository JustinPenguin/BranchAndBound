# BranchAndBound
I am unfortunately not alowed to post the code of this for academic integrity purposes, but here is the synposis and spec.

This program is themed after Pokemon, and shaped to resemble the NP-Hard Travelling Salesperson Problem. 
We are given a list of coordinates, and are taksed to either visit every location and return back to the starting point with the minimal distance traveled. The other option is to find an MST to all of the locations. There are multiple flags that the user is allowed to input. 
If the sea flag makes it so that the bottom left quadrant is the "Sea" where the only way to access locations in that quadrant requires the user to first visit a location that is on the negative X or Y axes. 
For the TSP portion, there are two modes that need to be accounted for, FASTTSP and OPTTSP. OPTTSP requires the use of a branch and bound algorithm to be able to optimally yet efficiently solve the TSP problem with pruning. The FASTTSP requires an almost optimal solution in a much faster time, in which case I implemented with nearset insertion.
