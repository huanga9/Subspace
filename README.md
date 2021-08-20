# A subspace clustering method for satisfying stoimetric constraints in scRNA-seq # 

This clustering approach was developed to identify and categorize cell populations within single-cell RNA-seq data. It leverages this subspace structure and learns a cell-to-cell affinity matrix based on notions of subspace similarity. It also faciliates recovery of information on developmental time.


Questions: Contact huanga1@seas.upenn.edu


## Download and Run ##
This repo contains the following:

All code needed to run the algorithm. The main clustering function is found in 'subspaceClustering.m'.

Inputs: 

mat dataset = matrix input (row: cell, column: gene)
csvfile labels = true labels of samples given by dataset authors, if available
int k = number of clusters
csvfile edges = strength output of SNN-Cliq from SNN.m 
csvfile cliques = cluster output of SNN-Cliq from Cliq.py 


MATLAB 
v. R2017b (and >)
