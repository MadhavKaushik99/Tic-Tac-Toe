# Tic-Tac-Toe
Human vs. ‘Intelligent’ Computer – (Minimax with Alpha-Beta Pruning)

The Minimax algorithm relies on systematic searching, that is on brute force and a simple evaluation function. Every time during deciding the next move we search through a whole tree, all the way down to leaves. Effectively looking into all the possible outcomes and every time determine the best possible move. Even searching to a certain depth sometimes takes an unacceptable amount of time. Therefore, Minimax applies search to a fairly low tree depth aided with appropriate heuristics, and a well designed, yet simple evaluation function.

Alpha–beta is actually an improved minimax using a heuristic. It stops evaluating a move when it makes sure that it's worse than previously examined move. Such moves need not to be evaluated further. When added to a simple minimax algorithm, it gives the same output, but cuts off certain branches that can't possibly affect the final decision by dramatically improving the performance.

The main concept is to maintain two values through whole search: Alpha: Best already explored option for player Max Beta: Best already explored option for player Min Initially, alpha is negative infinity and beta is positive infinity. This method allows to ignore many branches that lead to values that won't be of any help for the decision, nor they would affect it in any way.
