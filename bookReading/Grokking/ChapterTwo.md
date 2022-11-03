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
Data structures are concepts in computer science used to represent data in a way that is suitable for efficient processing by algorithms. <br />
*Graphs: Representing search problems and solutions:* <br />
- Data structure containing several states with connections among them.
- Each state in a graph is called a node(/vertex)
- A connection between two states is called an edge. 
<br />
*Representing a graph as a concrete data structure:* <br />
- A graph can be represented by an array of arrays that indicates relationships among nodes. <br />
- Other representations -> incidence matrix, an adjacency matrix, and an adjacency list. <br />
- Adjacency of nodes in a graph is important. An adjacent node is a node that is connected directly to another node. <br />