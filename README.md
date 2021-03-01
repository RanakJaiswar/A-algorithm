# A* algorithm
Reaching a destination via the shortest route is a daily activity we all do. A-star (also referred to as A*) is one of the most successful search algorithms to find the shortest
path between nodes or graphs. It is an informed search algorithm, as it uses information about path cost and also uses heuristics to find the solution.

		Node (also called State) — All potential position or stops with a unique identification
		Transition — The act of moving between states or nodes.
		Starting Node — Whereto start searching
		Goal Node — The target to stop searching.
		Search Space — A collection of nodes, like all board positions of a board game
		Cost — Numerical value (say distance, time, or financial expense) for the path from a node to another node.
		g(n) — this represents the exact cost of the path from the starting node to any node n
		h(n) — this represents the heuristic estimated cost from node n to the goal node.
		f(n) — lowest cost in the neighboring node n

install pygame 

# To run this

1 - First left click on grid makes a start node

![](https://github.com/RanakJaiswar/A-algorithm/blob/main/images/A_%20Path%20Finding%20Algorithm%2001-03-2021%2011_12_16.png)

2 - Second left click on gird makes destination or end node

![](https://github.com/RanakJaiswar/A-algorithm/blob/main/images/A_%20Path%20Finding%20Algorithm%2001-03-2021%2011_12_28.png)

3 - the thrid left click or clicks would make a barriers on grid

![](https://github.com/RanakJaiswar/A-algorithm/blob/main/images/A_%20Path%20Finding%20Algorithm%2001-03-2021%2011_12_44.png)

4 - hittig the spacebar would start the algorithm 

![](https://github.com/RanakJaiswar/A-algorithm/blob/main/images/A_%20Path%20Finding%20Algorithm%2001-03-2021%2011_13_00.png)

5 - Press key "C" to clear the grid
