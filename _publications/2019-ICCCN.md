---
title: "On the Importance of Container Image Placement for Service Provisioning in the Edge"
collection: publications
permalink: /publications/darrous-icccn19
excerpt: 'This paper is about container image placement algorithms to reduce the maximal retrieval time in Edge clouds.'
date: 2019-05-03
venue: '28th IEEE International Conference on Computer Communications and Networks'
paperurl: 'https://hal.inria.fr/hal-02134507'
citation: 'Jad Darrous, Thomas Lambert, Shadi Ibrahim. "On the Importance of Container Image Placement for Service Provisioning in the Edge". <i>ICCCN</i>, Jul 2019, Valencia, Spain.'
---

**Abstract** - Edge computing promises to extend Clouds by moving computation close to data sources to facilitate short-running and low-latency applications and services. Providing fast and predictable service provisioning time presets a new and mounting challenge, as the scale of Edge-servers grows and the heterogeneity of networks between them increases. This paper is driven by a simple question: can we place container images across Edge-servers in such a way that an image can be retrieved to any Edge-server fast and in a predictable time. To this end, we present KCBP and KCBP-WC, two container image placement algorithms which aim to reduce the maximum retrieval time of container images. KCBP and KCBP-WC are based on k-Center optimization. However, KCBP-WC tries to avoid placing large layers of a container image on the same Edge-server. Evaluations using trace-driven simulations show that KCBP and KCBP-WC can be applied to various network configurations and reduce the maximum retrieval time of container images by 1.1x to 4x compared to state-of-the-art placements (i.e., Best-Fit and Random).

<!-- [Download slides](../files/ccgrid-slides.pdf) -->
Simulator source code is available [here](https://gitlab.inria.fr/jdarrous/image-placement-edge)
