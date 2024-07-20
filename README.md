# Pathfinding-with-Potential-Reweighting

Calculating Potential Values
1. Determine the potential values for each node by calculating the straight-line distance from each node to the destination node D.

2. Adjusting Edge Lengths
Edge lengths are adjusted using the formula:
New length(u,v)=Old length(u,v)+Potential(u)−Potential(v)

Effect on Dijkstra's Algorithm
With these adjusted edge lengths, Dijkstra's algorithm prioritizes paths closer to the destination, improving efficiency in finding shorter paths.
