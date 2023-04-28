# Capstone
 Data analysis project
 
 Garrick "G Money" Williams

Functions:
 LapMap - input[edge set, dataframe]. Edge set is of the form `[(base vertex, connected vertex, connected vertex...), (base vertex, connected vertex...), ...]` where the vertex ID is the index of observation from dataframe.
 
 LapMap - output[Laplacian matrix, dictionary], where the dictionary takes the index value of observation and returns customer ID.
        
 ConnectPoints - This is used within graphing functions to draw lines (connections) between vertices/observations.
 
 Graph - input[Laplacian matrix, dictionary], where the outputs of `LapMap` are used as inputs.
 
 GRAPH - input[Laplacian matrix, dictionary], where the outputs of `LapMap` are used as inputs.
 
 GRAPH - output[(cluster 1, cluster 2, cluster 3, cluster 4)]. The clusters are determined by the pattern of signs assigned via the eigenvectors. Cluster 1 is when both eigenvectors assigned a negative sign to the vertex. Cluster 2 is when the first eigenvector assigned a negative sign but the next eigenvector assigned a positive sign. Cluster 3 is when both eigenvectors assigned a positive sign to the vertex. Cluster 4 is when the first eigenvector assigned a positive sign but the next eigenvector assigned a negative sign.
 
 Eigenstuff - input[Laplacian matrix, dictionary], where the outputs of `LapMap` are used as inputs.
 
 relativestr - input[dataframe], where the dataframe is the output from `Eigenstuff`. 
