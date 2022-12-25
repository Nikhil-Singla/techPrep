## Chapter 2—Search fundamentals <br />

#### What are planning and searching?
- Planning: Details to acomplish task.
- Searching: Guide by steps in plan.

#### Cost of Computation
Cost = Processing Time.
Big O Notation = Complexity (Models number of operations as inputs increases).

#### Problems applicable to searching algorithms
Problem that requires a series of decisions to be made can be solved with search algorithms <br />
Optimal Solution: The performance of the solution in addressing the problem at hand. <br />
The problem space needs to be represented in a form that is applicable to computation and can be processed with search algorithms. <br />

#### Representing state: Creating a framework to represent problem spaces and solutions
When representing data need to encode it logically so that it can be understood objectively. <br />
Data is raw facts about something, and information is an interpretation of those facts that provides insight about the data in the specific domain. <br />
Information requires context and processing of data <br />
Data structures are concepts in computer science used to represent data in a way that is suitable for efficient processing by algorithms. <br /><br />
*Graphs: Representing search problems and solutions:* 
- Data structure containing several states with connections among them.
- Each state in a graph is called a node(/vertex)
- A connection between two states is called an edge. 
<br />

*Representing a graph as a concrete data structure:* 
- A graph can be represented by an array of arrays that indicates relationships among nodes.
- Other representations -> incidence matrix, an adjacency matrix, and an adjacency list.
- Adjacency of nodes in a graph is important. An adjacent node is a node that is connected directly to another node. 
<br />

*Trees: The concrete structures used to represent search solutions:*
- Tree simulate hierarchy of values or objects. 
- A hierarchy is an arrangement of things in which a single object is related to several other objects below it. 
- A tree is a connected acyclic graph—every node has an edge to another node, and no cycles exist.
- Specific point = Node. Root node with zero of more child subtrees.
- Parent nodes, children nodes(aka neighbour nodes) and leaf nodes (nodes without child nodes).
- Level of specfic node = depth. Level of overall tree = height. Indexed from root (start at 0)
- A node connected to another node by following a path away from the root node is called a descendent
- A node connected to another node by following a path toward the root node is called an ancestor
- The term degree is used to describe the number of children a node has

Uninformed search: Looking blindly for solutions
- Uninformed search is also known as unguided search, blind search, or brute-force search.
- No additional information except representation of the problem
- Depth-first search explores a specific path from the start until it finds a goal at the utmost depth. 
- Breadth-first search explores all options at a specific depth before moving to options deeper in the tree.