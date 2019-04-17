+++
title = "Scalable K-Core Decomposition for Static Graphs Using a Dynamic Graph Data Structure"
date = 2018-12-13T10:38:16-04:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Graph Analytics"]
categories = []

authors = ["Alok Tripathy", "Fred Hohman", "Duen Horng Chau", "Oded Green"]
publication_types = ["1"]

url_pdf = "https://www.researchgate.net/publication/328874544_Scalable_K-Core_Decomposition_for_Static_Graphs_Using_a_Dynamic_Graph_Data_Structure"

abstract = "The k-core of a graph is a metric used in a wide range of applications, including social networks analytics, visualization, and graph coloring. Finding the maximal k-core of a graph can be be done in near linear time. The low computational requirements for finding the maximal k-core makes effective parallelization challenging, especially for the iterative algorithms that prune vertices and edges that no longer meet the requirements of the maximal k-core and require rebuilding the graph every iteration. In this paper, we present a new parallel and scalable algorithm for finding the maximal k-core. Similar to past algorithms, our algorithm also prunes vertices and edges. Unlike past approaches, our new algorithm does not rebuild the graph in every iteration-rather, it uses a dynamic graph data structure and avoids one of the largest performance penalties of k-core. We also show how to extend our algorithm to support k-core edge decomposition for different size k-cores found in the graph. This can be used for visualization and community analysis. While our new algorithms are architecture independent, our implementations target NVIDIA GPUs. When comparing our algorithms against several highly optimized algorithms, including the sequential igraph implementation and the multi-thread ParK implementation, our new algorithms are significantly faster. For finding the maximal k-core in the graph, our new algorithm can be up-to 58× faster the igraph and up-to 4× faster than ParK executed on a 36 core (72 thread) system. For the k-core decomposition algorithm, we saw even greater and more consistent speedups for our algorithm where it was up-to 130× faster than igraph and up-to 8× faster than ParK. Our algorithms were executed on an NVIDIA P100 GPU."

publication_short = "IEEE International Conference on Big Data (BigData) 2018"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
