# EnGNet
Ensemble and greedy approach for the reconstruction of large gene co-expression networks

EnGNet- Ensemble and greedy approach for the reconstruction of large gene co-expression networks
Introduction
EnGNet is a novel two-step method for large gene co-expression network inference. First, EnGNet uses an ensemble strategy for co-expression networks generation. Second, a greedy algorithm optimises both the size and the topological features of the network. 



# Implementation
This is a Java application for large gene co-expression network generation. As a multiplatform tools, it  can be used in linux, mac, and windows.

In DataSets file there are some input gene expression data for testing the tool.

# Usage information
Turn to console and set:

> java -jar EnGNet.jar 



# Parameters (config.properties):

> inputFile: The path to the input dataset (gene expression matrix)
> KendallThreshold: threshold for the Kendall classifier
> SpearmanThreshold: threshold for the Spearman classifier
> NMIThreshold: threshold for the NMI classifier
> addingThreshold: threshold to determine if the edge would be return into the network after the pruning step
> hubThr: threshold to determine if the node studie is a hub. Set this threshold to -1 to run the algorithm with standard selection.


NOTE: You should have installed JAVA for running this tool.



# AUTHOR:
Francisco Gómez Vela <fgomez@upo.es>.

Copyright © 2019 Universidad Pablo de Olavide, 

Spain.
