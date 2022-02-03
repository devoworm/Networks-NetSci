## Euler Cycles for "Life": developing biological structure using multi-cell networks

The evolutionary transition to multicellular life in the form of cellular aggregates and embryos is marked by a need to form internal networks for oxygen and nutrient transfer between cells. The related transition from simple to complex cells involves an increase in the complexity of internal structure [1]. These inter- and intra-cellular networks can take the form of vascular, gap junction, and structural protein networks (Figure 1). In terms of graph theory, these biological networks can be mapped to multi-cell networks, and rely upon relationships between the network edges rather than the nodes. This allows us to examine the configurational complexity of morphologies by growing developmental networks with specific form-preserving connectivity patterns, cell shapes, and topological configurations. Multi-cell networks can grow, change shape, and be deformed by manipulating the relative position of their nodes, potentially revealing novel information about biological growth and form [2]. Yet how does this way of characterizing complex biological systems constrain developmental-related changes in our network? To answer this, we can utilize a tool from graph theory: Euler cycles. Consider that form a unipartite graph where each edge represents the boundary between two cells. When these networks represent a complete Euler cycle, then they can be said to be equistatic, meaning that each edge is both permeable and representative of an equal number of transfer points. 

![](https://github.com/devoworm/Networks-2021/blob/main/TopoNets/Figure-1.png)  
__Figure 1.__ Examples of how multi-cell networks map to living organisms. A: a seven-cell network mapped to an Archean with a triangular phenotype (single-cell morphogenesis). B: an eleven-cell network mapped to a Volvox colony (multi-cell morphogenesis).

Equistatic network maintenance and preservation are the selection criteria that yield the emergence of structural complexity. Coherence of multi-cell networks during network growth are assessed by a measure of Euler completeness. Euler completeness is assessed by drawing a path across every edge only once, with no trajectory self-crossings allowed (yielding a score of 0). In cases where a path cannot be completed, a score with a negative value denotes the number of edges not included in the path. Euler completeness is an upper bound to complexity of phenotype in which non-complete parts of the cycle are non-functional. The consequence is a meta-replication event, where our unipartite network becomes a bipartite network. Further deformation of the network topology by migrating the position of nodes can be used to simulate the emergence of highly complex and asymmetric phenotypes. 

![](https://github.com/devoworm/Networks-2021/blob/main/TopoNets/Figure-2.png)  
__Figure 2.__ A differentiation tree of a multi-cell network as it undergoes morphogenesis with Euler completeness score for each new network. Specific classes of network configurations include A: asymmetric transformation, B: modularity, C: no modularity, D: fractal representations.

Figure 2 shows an example of a differentiation tree [3] using rectangular/mixed cells. Each branch point in the tree shows a morphology with our measure of Euler completeness. Network topologies grow by symmetric divisions (two cells produce two additional cells), asymmetric divisions (two cells produce a single cell), and mutations (new cells of different shapes). Euler completeness is calculated for every one of these new networks. Aside from observing the emergence of multiple sublineages of variable complexity, we also observe examples of specific classes of network configuration, including modularity and fractality. 

## References:
[1] Bonner, J.T. (1988). The Evolution of Complexity by Means of Natural Selection. Princeton University Press, Princeton, NJ.

[2] Thompson, D.W. (1942). On Growth and Form. Cambridge University Press, Cambridge, UK.

[3] Gordon, R. (1999). The Hierarchical Genome and Differentiation Waves: Novel Unification of Development, Genetics and Evolution. World Scientific, Singapore.