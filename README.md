# Capstone
 Data analysis project
 
 Garrick "G Money" Williams

Functions:
 LapMap - input[edge set, dataframe]. Edge set is of the form `[(base vertex, connected vertex, connected vertex...), (base vertex, connected vertex...), ...]` where the vertex ID is the index of observation from dataframe.
        - output[Laplacian matrix, dictionary], where the dictionary takes the index value of observation and returns customer ID.
        
 ConnectPoints - This is used within graphing functions to draw lines (connections) between vertices/observations.
 
 Graph - input[Laplacian matrix, dictionary], where the outputs of `LapMap` are used as inputs.
 
 GRAPH - input[Laplacian matrix, dictionary], where the outputs of `LapMap` are used as inputs.
 
 Eigenstuff - input[Laplacian matrix, dictionary], where the outputs of `LapMap` are used as inputs.
 
 relativestr - input[dataframe], where the dataframe is the output from `Eigenstuff`. 
