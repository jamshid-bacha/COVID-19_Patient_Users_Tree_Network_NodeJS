# Project Overview #

The project focuses on simulating a tree-based network to trace COVID-19 contacts and their subsequent spread. The goal is to visualize the chains of infection starting from a primary patient (known as the "index case" or "patient zero") to individuals who came into contact with them, as well as their extended network of contacts.
Using a tree data structure, the project represents individuals as nodes and the relationships (contact events) as edges connecting these nodes. The root of the tree represents the index case, and branches represent the contact paths. This approach allows researchers or healthcare authorities to efficiently track, visualize, and manage the spread of infections in a structured manner.

# Features #

Contact Mapping: Traces and visualizes individuals' contact paths from the index case.

Dynamic Representation: Provides an interactive or visual snapshot of how the virus spreads across the network.

Data Insights: Helps in understanding the hierarchy of infection chains, potential superspreaders, and critical nodes in the contact network.

Scalability: The tree model can be extended to handle large datasets of contact tracing.


# Description of Results #
The provided screenshot illustrates an example of the tree network:

![IMG-20210715-WA0017](https://github.com/user-attachments/assets/a21f08aa-64f0-4bd7-96c3-e3ee91d3364a)


Nodes Representation: Each circle in the tree represents a user or contact, starting from the root node (index case) and branching out into layers of contacts.

Edges: Lines connecting the nodes represent the direct contact between individuals.

Hierarchical Levels:
Level 1 contains the first direct contacts of the index case.

Level 2 extends to the contacts of Level 1 individuals.

This hierarchical structure enables identifying "superspreaders" (nodes with multiple branches) or isolated contacts.



Numerical Labels: Each node is labeled with an identifier, such as "1" for the index case and subsequent numbers for their contacts. 

For example: Node 1 (the index case) connects to nodes 2, 4, 78, and 89.

Node 2 connects further to nodes 10 and 6, which lead to other nodes such as 155 and 12, respectively.

Nodes with more connections (like 89) highlight individuals who might have a higher potential for spreading the virus.

The screenshot effectively visualizes how contact tracing data is structured and provides a clear understanding of the tree-like progression of potential COVID-19 spread.

![IMG-20210715-WA0018](https://github.com/user-attachments/assets/21d3a81d-786d-465b-bdbc-52542da0490a)

![IMG-20210719-WA0005](https://github.com/user-attachments/assets/ae5321d4-60ad-4d95-9ca4-20859c29e79e)









