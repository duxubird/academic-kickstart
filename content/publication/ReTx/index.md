+++
authors = ["Xu Du", "Yin Sun", "Ness Shroff", "Ashutosh Sabharwal"]
date = "2019-02-01"
math = false
featured=true
publication="submitted to IEEE Transactions on Wireless Communication"
abstract = "One fundamental challenge in 5G URLLC is how to optimize massive MIMO communication systems for achieving both low latency and high reliability. A reasonable design is to choose the smallest possible target error rate, which can achieve the highest link reliability and the minimum retransmission latency. However, the overall system latency is the sum of latency due to queueing and due to retransmissions, hence choosing the smallest target error rate does not always minimize the overall latency. In this paper, we minimize the overall latency by jointly designing the target error rate and transmission rate, which leads to a sweet tradeoff point between queueing latency and retransmission latency. This design problem can be formulated as a Markov decision process, whose complexity is prohibitively high for real-system deployments. Nonetheless, we managed to develop a low-complexity closed-form policy named Large-arraY Reliability and Rate Control (LYRRC), which is latency-optimal in the large-array regime. In LYRRC, the target error rate is a function of the antenna number, arrival rate, and channel estimation error; and the optimal transmission rate is twice of the arrival rate. Using over-the-air channel measurements, our evaluations suggest that LYRRC can satisfy both the latency and reliability requirements of 5G URLLC."
title = "Balance Queueing and Retransmission: Latency-Optimal Massive MIMO Design"
summary="Design latency-optimal massive MIMO via optimizing the error rate for balancing queueing and retransmission latency."
publication_types=["3"]
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/1902.07676.pdf"
url_project = ""
url_slides = ""
url_video = ""

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Scheduling", "Low-Latency", "massive MIMO", "MIMO"]
categories = []

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
