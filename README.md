# Social Network Analysis in Python

## Week 1
- Types of graphs:
    - undirected
    - directed
    - signed
    - multigraph (possible to have more than 1 edge between same 2 nodes)
    - weighted
```python
G.nodes(date=True) # list of all nodes with attributes
G.node['A']['role'] # getting node A's role attribute

# Accessing edge attributes
G.edges(data='relation')
G.edge['A']['B']['weight']
```
- bipartite graph: nodes can be split into 2 sets, L and R, and every edge connects a node in L with a node in R

