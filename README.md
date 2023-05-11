# Graph Neural Networks Explained by Cuneyt Akcora and Baris Coskunuzer

**On Over-Squashing in Message Passing Neural Networks: The Impact of Width, Depth, and Topology by Francesco Di Giovanni, Lorenzo Giusti, Federico Barbero, Giulia Luise, Pietro Lio, Michael Bronstein.** [Link to the review page](reviews/overSquashing.md)<br>
**Venue**: ICML 2023<br>
**Task**: Node classification<br>
**TLDR**: provides a unified framework to study different recent methods introduced to cope with over-squashing and serves as a justification for a class of methods that fall under ‘graph rewiring.<br>
**Datasets**: PROTEINS, NCI1, PTC, ENZYMES<br> 
**Abstract**: "_Message Passing Neural Networks (MPNNs) are instances of Graph Neural Networks that leverage the graph to send messages over the edges. This inductive bias leads to a phenomenon known
as over-squashing, where a node feature is insensitive to information contained at distant nodes. Despite recent methods introduced to mitigate this issue, an understanding of the causes for oversquashing and of possible solutions are lacking. In this theoretical work, we prove that: (i) Neural network width can mitigate over-squashing, but at the cost of making the whole network more sensitive; (ii) Conversely, depth cannot help mitigate over-squashing: increasing the number of layers leads to over-squashing being dominated by vanishing gradients; (iii) The graph topology plays the greatest role, since over-squashing occurs between nodes at high commute time. Our analysis provides a unified framework to study different recent methods introduced to cope with over-squashing and serves as a justification for a class of methods that fall under ‘graph rewiring’._"

