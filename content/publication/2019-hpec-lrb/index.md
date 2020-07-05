+++
title = "Improving Scheduling for Irregular Applications with Logarithmic Radix Binning"
date = 2019-09-25T14:43:34-04:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Graph Analytics"]
categories = []

authors = ["James Fox", "Alok Tripathy", "Oded Green"]
publication_types = ["1"]

abstract = "Effective scheduling and load balancing of applications on massively multi-threading systems remains challenging despite decades of research, especially for irregular and data dependent problems where the execution control path is unknown until run-time. One of the most widely used loadbalancing schemes used for data dependent problems is a parallel prefix sum (PPS) array over the expected amount of work per task, followed by a partitioning of tasks to threads. While sufficient for many systems, it is not ideal for massively multithreaded systems with SIMD/SIMT execution, such as GPUs.  More fine-grained load-balancing is needed to effectively utilize SIMD/SIMT units. In this paper we introduce Logarithmic Radix Binning (LRB) as a more suitable alternative to parallel prefix summation for load-balancing on such systems. We show that LRB has better scalability than PPS for high thread counts on Intel’s Knight’s Landing processor and comparable scalability on NVIDIA Volta GPUs. On the application side, we show how LRB improves the performance of PageRank up to 1.75X using the branch-avoiding model. We also show how to better load-balance segmented sort and improve performance on the GPU."

url_pdf = "https://www.researchgate.net/profile/Oded_Green/publication/335723059_Improving_Scheduling_for_Irregular_Applications_with_Logarithmic_Radix_Binning/links/5d7799ada6fdcc9961bcd95a/Improving-Scheduling-for-Irregular-Applications-with-Logarithmic-Radix-Binning.pdf"

publication_short = "IEEE High Performance Extreme Computing (HPEC) 2019"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
