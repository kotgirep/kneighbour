# Use state of art libraries for Approximate nearest neighbor search
The following strategies can be used to determine exact k nearest:

1.Exhaustive search entails matching each position to any point, which takes time (the size of the dataset).

2.The Grid Trick entails sectioning the area into a grid, that necessitates increasing time and space (in the dimensionality of the dataset).
This is problematic because we're dealing with high-dimensional datasets.

### Strategies to find exact nearest Neighbours:

Vector Transformation – a transformation that is applied to vectors before they are classified.
Data reduction and vector transformation are two of them.

Vector encoding is a technique for constructing a search index using vectors.
Data structure-based methods such as Trees, LSH, and Quantization, a technique for encoding a vector into a considerably more condensed package, are one of these.

Extensive Search: None Component — a function that is applied to vectors to prevent an exhaustive search.
Twisted Files and Neighbor Charts are two of these approaches.
