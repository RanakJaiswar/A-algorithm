# A* algorithm

install pygame

Reaching a destination via the shortest route is a daily activity we all do. A-star (also referred to as A*) is one of the most successful search algorithms to find the shortest path between nodes or graphs. It is an informed search algorithm, as it uses information about path cost and also uses heuristics to find the solution.

In this article, I will focus on how to build A-star (A*) search algorithm using a simple python code. I found many articles and blogs focus heavily on theory but not much information on the program. I am trying here to present the code step-by-step with easy to understand details.

First, let’s have a bit of theory to warm-up.
A* achieve optimality and completeness, two valuable property of search algorithms.
When a search algorithm has the property of optimality, it means it is guaranteed to find the best possible solution. When a search algorithm has the property of completeness, it means that if a solution to a given problem exists, the algorithm is guaranteed to find it.

Now to understand how A* works, first we need to understand a few terminologies:
Node (also called State) — All potential position or stops with a unique identification
Transition — The act of moving between states or nodes.
      Starting Node — Whereto start searching
      Goal Node — The target to stop searching.
      Search Space — A collection of nodes, like all board positions of a board game
      Cost — Numerical value (say distance, time, or financial expense) for the path from a node to another node.
      g(n) — this represents the exact cost of the path from the starting node to any node n
      h(n) — this represents the heuristic estimated cost from node n to the goal node.
      f(n) — lowest cost in the neighboring node n
      Each time A* enters a node, it calculates the cost, f(n)(n being the neighboring node), to travel to all of the neighboring nodes, and then enters the node with the lowest         value of f(n).
      These values we calculate using the following formula:
            f(n) = g(n) + h(n)
