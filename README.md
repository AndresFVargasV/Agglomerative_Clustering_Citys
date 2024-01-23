# Cluster Analysis of Colombian Cities

This project performs a hierarchical cluster analysis and graphs the minimum spanning tree (MST) for a set of cities in Colombia, using their distances in kilometers as a measure of similarity. In this project we can also see how a hierarchical algorithm can be connected with an MST to solve a transportation and distance problem.


## Content

The project contains the following files:

\- `cities.txt`: Text file with the names of the cities to analyze, one per line.

\- `Agglomerative_Clustering.ipynb`: Jupyter notebook where we perform all the analysis.


## Analysis Performed  

The main analysis performed are:

\- Calculation of distance matrix between all cities  

\- Hierarchical clustering using single linkage  

\- Dendrogram plot with 3 levels

\- Minimum Spanning Tree (MST) construction   

\- MST plot   

\- Creation of maps with markers and routes between cities based on the MST


## Requirements  

To run the project, Python 3 and the following libraries are required:

\- numpy

\- matplotlib

\- scipy 

\- networkx   

\- folium 

\- googlemaps

NOTE: To access Google services, a Google Cloud KEY is required to use the API.


## License

This project is shared under the MIT License. Feel free to use and modify it as you need.
