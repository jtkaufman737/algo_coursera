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
