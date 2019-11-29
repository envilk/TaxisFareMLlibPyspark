# Apache Spark Software Technology Study Project

The software technology which will be discussed in this report is \textbf{Apache Spark}, an unified tool for analysing and processing data. In addition, \textbf{PySpark} is going to be used to write the code in \textbf{iPython Notebook}.

The purpose of this report is to check the different ways of processing big data using \textbf{Distributed Machine Learning} techniques, working with clusters, to see which way of \textbf{clustering} is more efficient.

The dataset taken for this project contains taxi travels with information about source location, target location, amount of passengers and taxi fare. This \textbf{large dataset} is a proficient approach to work with Spark in big data computing purposes.

There will be three Distributed Machine Learning models presented, in two approaches, one way for \textbf{Native Clustering}, which means one core acting as a cluster and the other approach is \textbf{Local Clustering} which means as many clusters as cores the processor has.

The models used are \textbf{Linear Regression}, \textbf{Decision Tree} and \textbf{Random Forest} generating several results. Basically, the results acknowledge the efficiency to work with Local Clustering rather than working with Native Clustering. 

Another improvement would be to work with \textbf{Remote Clustering} in a network with several machines, but it wasn't possible to implement it in the end. Remote clustering is more efficient because of the quantity of cores used to parallelize the tasks.

This repository contains the code of the Jupyter Notebook that we worked with and the Latex's Report about the Technology Study Project that we did.


