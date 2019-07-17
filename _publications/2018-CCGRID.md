---
title: "Nitro: Network-Aware Virtual Machine Image Management in Geo-Distributed Clouds"
collection: publications
permalink: /publications/darrous-ccgrid18
excerpt: 'This paper is about our system, Nitro, that is used to manage VM images in geo-distributed clouds.'
date: 2018-01-01
venue: '18th IEEE/ACM International Symposium on Cluster, Cloud, and Grid Computing'
paperurl: 'https://hal.inria.fr/hal-01745405'
citation: 'J. Darrous, S. Ibrahim, A.C. Zhou, C. Perez. &quot;Nitro: Network-Aware Virtual Machine Image Management in Geo-Distributed Clouds.&quot; <i>CCGrid</i>, May 2018, Washington DC, USA.'
---

**Abstract** - Recently, most large cloud providers, like Amazon and Microsoft, replicate their Virtual Machine Images (VMIs) on multiple geo-graphically distributed data centers to offer fast service provisioning. Provisioning a service may require to transfer a VMI over the wide-area network and therefore is dictated by the distribution of VMIs and the network bandwidth in-between sites. Nevertheless, existing methods to facilitate VMIs management (i.e., retrieving VMIs) overlook network heterogeneity in geo-distributed clouds. In this paper, we design, implement and evaluate Nitro, a novel VMI management system that helps to minimize the transfer time of VMIs over a heterogeneous WAN. To achieve this goal, Nitro incorporates two complementary features. First, it makes use of deduplication to reduce the amount of data which will be transferred due to the high similarities within an image and in-between images. Second, Nitro is equipped with a network-aware data transfer strategy to effectively exploit links with high bandwidth when acquiring data and thus expedites the provisioning time. Our results show that the network-aware data transfer strategy offers optimal solution when acquiring VMIs while introducing minimal overhead. Moreover, Nitro outperforms state-of-the-art VMI storage systems (e.g., OpenStack Swift) by up to 77%.

<!-- [Download slides](../files/ccgrid-slides.pdf) -->
Nitro source code is available [here](https://gitlab.inria.fr/jdarrous/nitro)

<!-- Download the paper from [here](https://hal.inria.fr/hal-01745405) -->
<!-- Conference acceptance rate is 20.8% -->
