# MLST_WDND
Dataset used by the Machine Learning Seeding Tool (MLST), a data-driven approach that leverages supervised learning to enhance solution initialization to predict high-performing initial solutions [1]. 

The MLST dataset aggregates relevant information derived from multiple network topologies [2], introducing variability and structural diversity into the training data. The resulting dataset contains 58,311 unique, complete observations—free of duplicates, nulls, or missing values—providing a solid foundation for training predictive models.

The first five columns correspond to the predictor variables and the last column denotes the target. The variables \textit{Net}, \textit{Pipe (Id)}, and \textit{Diameter} are categorical, whereas the remaining ones are numerical. Note that the last digit of the \textit{Net} variable represents the network type (e.g., residential, industrial, commercial), while the preceding digit(s) indicate its size. A higher value signifies a larger network, with a corresponding increase in the number of nodes and connections between them. Furthermore, the \textit{Pipe} variable assumes values greater than or equal to 90 million if one of the connected nodes is a specialized type (e.g., a reservoir or a water pump). Consequently, it identifies both the pipe and the type of the primary node connected to it.





# References
[1] Paper to publish in CACIC 2025.

[2} A. De Corte and K. S¨orensen, “An iterated local search algorithm for water distribution network design optimization,” Network, vol. 67, no. 3, pp. 187–198, 2016.
