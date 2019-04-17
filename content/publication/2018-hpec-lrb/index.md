+++
title = "Logarithmic Radix Binning and Vectorized Triangle Counting"
date = 2018-09-25T14:43:34-04:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Graph Analytics"]
categories = []

authors = ["Oded Green", "James Fox", "Alex Watkins", "Alok Tripathy", "Kasimir Gabert", "Euna Kim", "Xiaojing An", "Kumar Aatish", "David A. Bader"]
publication_types = ["1"]

abstract = "Triangle counting is a building block for numerous graph applications and given the fact that graphs continue to grow in size, its scalability is important. As such, numerous algorithms have been designed for triangle counting-some of which are compute-bound rather than memory bound. Even for compute-bound algorithms, one of the key challenges is the limited control flow available on the processor. This is in-part due to the high dependency between the control flow, input data, and limited utilization of vector instructions. Not surprising, compilers are not always able to detect these data dependencies and vectorize the algorithms. Using the branch-avoiding model we show to remove control flow restrictions by replacing branches with an equivalent set of arithmetic operations. More so, we show how these can be vectorized using Intel's AVX-512 instruction set and that our new vectorized algorithms are 2 × −5× faster than scalar counterparts. We also present a new load balancing method, Logarithmic Radix Binning (LRB) that ensures that threads and the vector data lanes execute a near equal amount of work at any given time. Altogether, our algorithm outperforms several 2017 HPEC Graph Challenge Champions such as the KOKKOS framework and a GPU based algorithm by anywhere from 1.5× and up to 14×."

url_pdf = "https://www.researchgate.net/publication/327569911_Logarithmic_Radix_Binning_and_Vectorized_Triangle_Counting?_sg=NwkwZK-isqL5l96mfuPYP3SD9iZuNS5iSY2vdTWwltCgLBzVLyEpl3iAs4gW0-zWeoGb_K0OE-ChLLEhJLrS08jg-D6KYTv7h8aG-oGF.rDK8HkPd78kc0o4rYZ0HhHNpe6oHAJE6V8B1bYyTeG-_gAUg1Coo9FLKKh2ZZY2lmmlvxioE3i043T-xjqhYMw"

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
