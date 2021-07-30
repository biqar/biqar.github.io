+++
title = "Scalable Hash Table for NUMA Systems"
date = 2021-03-09T14:43:34-04:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["GPU Data Structure"]
categories = []

authors = ["Alok Tripathy", "Oded Green"]
publication_types = ["3"]

abstract = "Hash tables are used in a plethora of applications, including database operations, DNA sequencing, string searching, and many more. As such, there are many parallelized hash tables targeting multicore, distributed, and accelerator-based systems. We present in this work a multi-GPU hash table implementation that can process keys at a throughput comparable to that of distributed hash tables. Distributed CPU hash tables have received significantly more attention than GPU-based hash tables. We show that a single node with multiple GPUs offers roughly the same performance as a 500-1,000-core CPU-based cluster. Our algorithm's key component is our use of multiple sparse-graph data structures and binning techniques to build the hash table. As has been shown individually, these components can be written with massive parallelism that is amenable to GPU acceleration. Since we focus on an individual node, we also leverage communication primitives that are typically prohibitive in distributed environments. We show that our new multi-GPU algorithm shares many of the same features of the single GPU algorithm -- thus we have efficient collision management capabilities and can deal with a large number of duplicates. We evaluate our algorithm on two multi-GPU compute nodes: 1) an NVIDIA DGX2 server with 16 GPUs and 2) an IBM Power 9 Processor with 6 NVIDIA GPUs. With 32-bit keys, our implementation processes 8B keys per second, comparable to some 500-1,000-core CPU-based clusters and 4X faster than prior single-GPU implementations."

url_pdf = "https://arxiv.org/pdf/2104.00792.pdf"

publication_short = "arXiv:2104.00792"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
