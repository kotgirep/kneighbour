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

### Vector Encoding using Trees

1. When it comes to ANN, tree-based algorithms are among the most frequent methodologies. By dividing the dataset into subgroups, they create forests (a group of trees) as their dataset.
2. Annoy, which utilizes trees (more precisely forests) to allow Spotify's music suggestions, is one of the most well-known options available. Because there is a fintuition behind this one, how to utilize it, and the benefits and drawbacks.

Accuracy performance trademark is denoted by following:
number of trees — the number many binary trees we construct; a higher value yields quite reliable data but bigger indexes.
search k — the number of binary trees we explore for every point; a higher value yields better reliable data but takes more time to return.
