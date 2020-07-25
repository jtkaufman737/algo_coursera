## DYNAMIC CONNECTIVITY & UNION FIND
- Problems in this space include:
  - Given a set of N objects, connect them
  - Given a set of N objectcs, find *if* they are connected (even indirectly)
  - Given a set of disconnected components, connect them
- Assumptions in this problem set:
  - Reflexive: assume node p is conneted to p
  - Symmetric: if p is connected to q, q is connected to p
  - Transitive: if p is connected to q, and q is connected to r, **p is connected to r**
  - Each grouping of connected components can be considered a *set* represented { x y z } { a b }
- Implementation details:
  - A traditional approach might be to have a class, uf, where the constructor takes n objects to initialize
  - Contains a union function taking two nodes to add a connection between them
  - Contains a connected function returning a boolean to answer *if* they are connected
- Approaches:
  1. **Quick Find**: (Eager Approach) p and q are connected if they have the same id, where the id is the first element of the component. A *union* operation
  is harder with this method because it could require multiple changes to entries of the array 
  2.
