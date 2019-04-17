+++
title = "Scaling Betweenness Centrality in Dynamic Graphs"
date = 2018-09-25T14:43:34-04:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Graph Analytics"]
categories = []

authors = ["Alok Tripathy", "Oded Green"]
publication_types = ["1"]

url_pdf = "https://www.researchgate.net/publication/327569969_Scaling_Betweenness_Centrality_in_Dynamic_Graphs"

abstract = "The Betweenness Centrality of a vertex is an important metric used for determining how “central” a vertex is in a graph based on the number of shortest paths going through that vertex. Computing the betweenness centrality of a graph is computationally expensive, O(V ·(V +E)). This has led to the development of several important optimizations includ- ing: approximation, parallelization, and dealing with dynamic updates. Dynamic graph algorithms are extremely favorable as the amount of work that they require is orders of magnitude smaller than their static graph counterparts. Recently, several such dynamic graph algorithms for betweenness centrality have been introduced. Many of these new dynamic graph algorithms tend to have decent parallel scalability when the betweenness centrality metric is computed in an exact manner. However, for the cases where the approximate solution is used, the scalability drops because of bad load-balancing due to the reduction in the amount of work. In this paper, we show a dynamic graph betweenness centrality algorithm that has good parallel scalability for both exact and approximate computations. We show several new optimizations made to the data structures, the load balancing technique, and the parallel granularity that have improved overall performance to 1.6X − 4X faster than one of the fastest previous implementations. More so, our new algorithm scales to larger thread counts than before." 

publication_short = "IEEE High Performance Extreme Computing (HPEC) 2018"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
