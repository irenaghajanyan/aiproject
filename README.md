# Arificial Inteligence Project


The problem will have a clear knowledge of the environment. The walls are characterized as “+,” dirt is “*,” and clear space is just a clear sting “ .“ The starting point of the vacuum is fixed at a certain location in the labyrinth. Since the environment is known we use Breadth-first graph search, depth-first graph search, A star search. 
Our Goal state is to clean all the dirt from the maze. The dirt has its fixed positions, as well as the walls, do.  
The environment is the single-agent environment, deterministic because the next action will depend on whether the vacuum cleaner already visited that state or not. Sequential, the current decision can affect future decisions. Static, nothing changes in the environment as the vacuum moves. Discrete, and fully observable.
Our agent is a model-based agent. It has the actions for moving up, down, right, and left. Also has a suck function that cleans the dirt. In comparison to other variations of this problem, in our case, it is not possible for the dirt to appear again in the cell. The agent keeps track of the visited states, using graph search and it has the percept of the environment. 
