+++
title = "Accurately and Efficiently Estimating Dynamic Point-to-Point Shortest Path"
date = 2020-11-05T10:38:16-04:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Graph Analytics"]
categories = []

authors = ["Alok Tripathy", "Oded Green"]
publication_types = ["1"]

url_pdf = ""

abstract = "Point-to-point shortest path (PPSP), or s-t connectivity, is a variant of the shortest path problem found in graph theory. In this problem, we are given a graph and pairs of vertices over time, and the output is the shortest path between each pair of vertices. In this paper, we present two algorithms. Our first algorithm approximately solves the PPSP problem on any arbitrary graph. For each pair of vertices queried, it accurately and efficiently estimates the shortest path between the two vertices. Our second algorithm extends the first to work on dynamic graphs. That is, our second algorithm can efficiently account for changes in the graph, such as friend requests on the Facebook network or road closures on road networks. At a high level, both algorithms partition the graph into highly connected communities. To respond to a query q(u, v), they each find the fewest number of partitions between u and v, and the shortest path through each partition. We show that our static graph algorithm can approximate the distance between two vertices with about 20%-35% percent error and anywhere from 80X-70000X faster than a BFS in practice with the right choice of partitions. Additionally, we show that our dynamic graph algorithm can account for updates to the graph anywhere from 20X-20000X faster than rerunning the static graph algorithm for each change to the graph."

publication_short = "IEEE BigGraphs Workshop at International Conference on Big Data (BigData) 2020 (to appear)"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
