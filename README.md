# PageRank
In this repository, the PageRank algorithm that is used by Google search engine to rank websites is implemented with MapReduce.

In the pagerank branch, built the transition matrix to represent the relationship between websites; solved the edge cases of dead ends and spider traps by introducing damping factor; PageRank matrix was computed iteratively by multiplying transition matrix and previous PageRank matrix; used the converged PageRank weights to rank websites.
