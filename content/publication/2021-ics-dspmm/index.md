+++
title = "Distributed-Memory Parallel Algorithms for Sparse Times Tall-Skinny-Dense Matrix Multiplication"
date = 2021-06-09T14:43:34-04:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Distributed Matrix Multiplication"]
categories = []

authors = ["Oguz Selvitopi", "Benjamin Brock", "Israt Nisa", "Alok Tripathy", "Katherine Yelick", "Aydın Buluç"]
publication_types = ["1"]

abstract = "Sparse times dense matrix multiplication (SpMM) finds its applications in well-established fields such as computational linear algebra as well as emerging fields such as graph neural networks. In this study, we evaluate the performance of various techniques for performing SpMM as a distributed computation across many nodes by focusing on GPU accelerators. We examine how the actual local computational performance of state-of-the-art SpMM implementations affect computational efficiency as dimensions change when we scale to large numbers of nodes, which proves to be an unexpectedly important bottleneck. We consider various distribution strategies, including A-Stationary, B-Stationary, and C-Stationary algorithms, 1.5D and 2D algorithms, and RDMA-based and bulk synchronous methods of data transfer. Our results show that the best choice of algorithm and implementation technique depends not only on the cost of communication for particular matrix sizes and dimensions, but also on the performance of local SpMM operations. Our evaluations reveal that with the involvement of GPU accelerators, the best design choices for SpMM differ from the conventional algorithms that are known to perform well for dense matrix-matrix or sparse matrix-sparse matrix multiplies."

url_pdf = "https://dl.acm.org/doi/pdf/10.1145/3447818.3461472"

publication_short = "ACM Proceedings of the ACM International Conference on Supercomputing (ICS), 2021"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
