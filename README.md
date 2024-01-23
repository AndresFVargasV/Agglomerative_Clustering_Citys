#Analysis of Clusters of Colombian Cities

This project performs a hierarchical cluster analysis and graphical minimum spanning tree (MST) for a set of cities in Colombia, using their distances in kilometers as a measure of similarity. In this project we can also see how a hierarchical algorithm can be connected with an MST to solve a problem on transportation and distance issues.

##Content

The project contains the following files:

- `cities.txt`: Text file with the names of the cities to analyze, one per line.
- `Agglomerative_Clustering.ipynb`: Jupyter notebook where we perform all the analysis.

##Analysis performed

The main analyzes carried out are:

- Calculation of distance matrix between all cities
- Hierarchical conglomerate using single type linkage
- Dendrogram graph with 3 levels.
- Minimum spanning tree (MST) construction
- MST graph
- Creation of maps with markers and routes between cities based on the MST

##Requirements

To run the project, Python 3 and the following libraries are required:

- numb
- matplotlib
- spicy
- redx
- Invoice
- Google maps

    NOTE: In order to access Google services, it is necessary to have a Google Cloud KEY to use the API.

## License

This project is shared under the MIT License. Feel free to use it and modify it as you need.
