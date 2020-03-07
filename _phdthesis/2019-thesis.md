---
title: "Scalable and Efficient Data Management in Distributed Clouds: Service Provisioning and Data Processing"
collection: phdthesis
permalink: /phdthesis/darrous-thesis
excerpt: ''
date: 2019-12-17
venue: 'Library of ENS de Lyon'
paperurl: 'https://hal.inria.fr/tel-02501316'
citation: 'Jad Darrous. "Scalable and Efficient Data Management in Distributed Clouds: Service Provisioning and Data Processing". Ph.D. thesis, Dec. 2019, ENS de Lyon, France.'
---

**Abstract**

We are living in the era of Big Data where data is generated at an unprecedented pace from various sources all over the world. These data can be transformed into meaningful information that has a direct impact on our daily life. To cope with the tremendous volumes of Big Data, large-scale infrastructures and scalable data management techniques are needed. Cloud computing has been evolving as the de-facto platform for running data-intensive applications. Meanwhile, large-scale storage systems have been emerging to store and access data in cloud data centers. They run on top of thousands of machines to offer their aggregated storage capacities, in addition to providing reliable and fast data access. The distributed nature of the infrastructures and storage systems introduces an ideal platform to support Big Data analytics frameworks such as Hadoop or Spark to efficiently run data-intensive applications.

In this thesis, we focus on scalable and efficient data management for building and running data-intensive applications. We first study the management of virtual machine images and containers images as the main entry point for efficient service provisioning. Accordingly, we design, implement and evaluate Nitro, a novel VMI management system that helps to minimize the transfer time of VMIs over a heterogeneous wide area network (WAN). In addition, we present two container image placement algorithms which aim to reduce the maximum retrieval time of container images in Edge infrastructures. Second, towards efficient Big Data processing in the cloud, we investigate erasure coding (EC) as a scalable yet cost-efficient alternative for replication in data-intensive clusters. In particular, we conduct experiments to thoroughly understand the performance of data-intensive applications under replication and EC. We identify that data reads under EC are skewed and can result in noticeable performance degradation of data-intensive applications. We then introduce an EC-aware data placement algorithm that targets balancing data accesses across nodes and therefore improving the performance of data-intensive applications under EC.


[thesis](../files/thesis_jad_darrous.pdf) [slides](../files/thesis_slides.pdf)
