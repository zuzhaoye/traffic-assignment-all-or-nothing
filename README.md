# traffic_assignment_all_or_nothing
It is an all-or-nothing algorithm for traffic assignment.

Given a network with limited links and demand between each node pair, calculate the traffic flow on each link based on all-or-nothing assignement algorithm, e.g. assign all the traffic demand from node 1 to 3 to its shortest path.

Example network:
![there should be a network image here, if you can not find load an image, check your browser capatibility](img/network.png?raw=true "An example network")

Input files:
- network.csv
- OD.csv (traffic demand on each origin - destination pair)

The Dijsktra algorithm on finding the shortest path is credited to [dingran](https://gist.github.com/dingran/b827b65a252000e25d818ba3520242e1).
