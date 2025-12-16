
Neo 4j is a graph database . It is schemaless
Stores data in a graph structure
Data is stored as nodes & relationships

Objects are called nodes

Objects are connected by relationships which are called edges

Neo 4j uses graph structure to store data - Labeled property graph

- **Nodes** - The fundamental entities in the graph
    
- **Relationships** - The connections between nodes
    
- **Labels** - Categories or types for nodes
    
- **Properties** - The attributes of nodes and relationships



Nodes: Circles in a graph . Represent objects or entities

Labels: Nodes  are grouped or categorized by labels. 

Relation: Connects two nodes

Relations have a type & a direction

Nodes can have multiple relations


Properties: 

You can store data against nodes & relationships as properties. Properties are named key,value pairs.

Nodes and relationships can have any number of properties, and those of the same type do not have to have the same properties (i.e. Neo4j is schemaless).

Properties have a type (integer, boolean, string, list, etc) and can be unique identifiers (keys) for specific node labels.

Graph database have their own query language - GQL

In neo 4j it's called cypher - It's a declarative language


Nodes are represented in ( )

Inside node mention the labels

Labels are prefixed a colon :

Relations are drawn with two dashes (--) & an > /< . 
Relationship info is contained within square brackets [ ]


MATCH is a clause used to find patterns in a data

