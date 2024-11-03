## A Gentle Introduction to Graph Neural Networks

From https://distill.pub/2021/gnn-intro/

A set of objects, and the connections between them, are naturally expressed as a graph
![image](https://github.com/user-attachments/assets/32341da8-38f9-479d-b8e9-530610344030)
![image](https://github.com/user-attachments/assets/e750528b-813e-4d15-a2f5-8d05c53fb95a)

### Problems have graph structured data
- Graph-level task:
![image](https://github.com/user-attachments/assets/71d08c43-97a8-45ec-9a62-1cb4ed8a6ab8)

- Node-level task:
![image](https://github.com/user-attachments/assets/0275a6b7-f600-4932-9d45-040a564cbeed)

- Edge-level task:
![image](https://github.com/user-attachments/assets/224a4691-b7f6-4b61-a67b-00de489bb7a8)


### The simplest GNN:  learn new embeddings for all graph attributes 
![image](https://github.com/user-attachments/assets/0f7de3f5-1920-4859-bb83-d4899e74309d)
- output graph of a GNN with the same adjacency list and the same number of feature vectors as the input graph
- But, the output graph has updated embeddings, since the GNN has updated each of the node, edge and global-context representations



#### Thinking in early / spatio temporal / graph aspects:

directed edge: one-way street

like dictionary? 

define a structure
