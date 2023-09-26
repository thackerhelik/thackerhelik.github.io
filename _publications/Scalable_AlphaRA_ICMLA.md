---
title: "A scalable solution to AlphaZero based Redundancy Analysis for semiconductor chips"
permalink: /publication/Scalable_AlphaRA_ICMLA
date: 2023-03-23
venue: 'ICMLA 2022'
---

<!---
---
title: "A Statistical Wafer Scale Error and Redundancy Analysis Simulator"
collection: publications
permalink: /publication/SEARS_Springer
excerpt: 'Something here.'
date: 2020-07-22
venue: 'Part of the IFIP Advances in Information and Communication Technology book series (IFIPAICT, volume 586)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-53273-4_7'
citation: "Atishay, A. Gupta, R. Sonawat, H. K. Thacker and B. Prasanth, 'SEARS: A Statistical Error and Redundancy Analysis Simulator,' 27th International Conference on VLSI-SoC, pp. 117-122, 2019."
---
--->

_**Abstract**_ -- Manufacturing flaws in memory devices give rise to defective memory cells rendering the chips unusable and consequently reducing the wafer yield. To overcome the effect of faulty memory cells, redundancies are included in the form of spare rows and columns in the memory device. Redundancy Analysis (RA) is the process of mapping these spare rows and columns to repair faulty lines in the chip. Our previous work AlphaRA, an AlphaZero based Redundancy Analysis method, has demonstrated promising yields. However, training for large values of chip sizes (n) is time-consuming. In this paper, we introduce SAZRA, a scalable solution for AlphaZero based Redundancy Analysis algorithms with the use of Graph Neural Networks (GNNs). The memory chip is designed as a graph so that it can be used in GNNs, thus making the solution independent of n. With just a single training on a dataset of n=16 chips, we are able to achieve yields outperforming existing algorithms on n up to 128 times larger and previously unseen to the neural network. SAZRA maintains a high yield while having the least spare utilization across all chip sizes. It achieves scalability with reduction in training time, execution time, and GPU memory and disk memory requirements.

[Download paper here](https://ieeexplore.ieee.org/document/10069266)

Recommended citation: H. K. Thacker et al., "A scalable solution to AlphaZero based Redundancy Analysis for semiconductor chips," 2022 21st IEEE International Conference on Machine Learning and Applications (ICMLA), Nassau, Bahamas, 2022, pp. 119-125, doi: 10.1109/ICMLA55696.2022.00024.