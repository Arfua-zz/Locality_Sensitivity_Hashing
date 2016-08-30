# Locality_Sensitivity_Hashing

Locality Sensitive Hashing (LSH) provides for a fast, efficient approximate nearest neighbor search. 
The algorithm scales well with respect to the number of data points as well as dimensions.
Here we 
 * implement the LSH algorithm for approximate nearest neighbor search
 * examine the accuracy for different documents by comparing against brute force search, and also contrast runtimes
 * explore the role of the algorithm’s tuning parameters in the accuracy of the method

LSH performs an efficient neighbor search by randomly partitioning all reference data points into different bins. 
We will implement method of LSH known as random binary projection, which approximates cosine distance. 
There are other variants we could use for other choices of distance metrics.

We use pandas, numpy, scikit, scipy, matplotlib
