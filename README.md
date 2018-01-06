# PageRank
In this repository, the PageRank algorithm that is used by Google search engine to rank websites is implemented with MapReduce. 
Data source http://www.limfinity.com/ir/, pr.txt is the initial PageRank matrix, transition.txt is the transition matrix.

In the pagerank branch, built the transition matrix to represent the relationship between websites; solved the edge cases of dead ends and spider traps by introducing damping factor; PageRank matrix was computed iteratively by multiplying transition matrix and previous PageRank matrix; used the converged PageRank weights to rank websites.
