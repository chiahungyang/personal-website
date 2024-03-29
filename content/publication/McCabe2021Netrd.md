---
title: "netrd: A library for network reconstruction and graph distances"
subtitle: "McCabe S., Torres L., LaRock T., Haque S. A., **Yang C.-H.**, Hartle H., Klein B. (2020). *Journal of Open Source Software*, 6(62), 2990."
summary: "McCabe S., Torres L., LaRock T., Haque S. A., **Yang C.-H.**, Hartle H., Klein B. (2020). *Journal of Open Source Software*, 6(62), 2990."
date: "2021-06-01"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

links:
  - name: CrossRef
    url: "https://joss.theoj.org/papers/10.21105/joss.02990"
---

Over the last two decades, alongside the increased availability of large network datasets, we have witnessed the rapid rise of network science. For many systems, however, the data we have access to is not a direct description of the underlying network. More and more, we see the drive to study networks that have been inferred or reconstructed from non-network data---in particular, using time series data from the nodes in a system to infer likely connections between them. Selecting the most appropriate technique for this task is a challenging problem in network science. Different reconstruction techniques usually have different assumptions, and their performance varies from system to system in the real world. One way around this problem could be to use several different reconstruction techniques and compare the resulting networks. However, network comparison is also not an easy problem, as it is not obvious how best to quantify the differences between two networks, in part because of the diversity of tools for doing so. The netrd Python package seeks to address these two parallel problems in network science by providing, to our knowledge, the most extensive collection of both network reconstruction techniques and network comparison techniques (often referred to as graph distances) in a single library ([this https URL](https://github.com/netsiphd/netrd)). In this article, we detail the two main functionalities of the netrd package. Along the way, we describe some of its other useful features. This package builds on commonly used Python packages and is already a widely used resource for network scientists and other multidisciplinary researchers. With ongoing open-source development, we see this as a tool that will continue to be used by all sorts of researchers to come. 
