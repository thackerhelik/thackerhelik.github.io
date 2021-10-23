---
title: "SEARS: A Statistical Error and Redundancy Analysis Simulator"
permalink: /publication/SEARS_VLSI_SoC
date: 2019-12-05
venue: '2019 IFIP/IEEE 27th International Conference on Very Large Scale Integration (VLSI-SoC)'
---
Manufacturing a DRAM chip involves multiple steps. External impurities, faulty deposition, or manufacturing errors in any of these steps could generate chips with faulty memory cells, rendering the chip unusable. To overcome these faulty memory cells, redundancies are included in the memory, allowing mapping of faulty memory cells to these redundant cells. The process of mapping faulty cells to redundant cells is called Redundancy Analysis (RA). Different RA algorithms have been developed and are often tested on randomly generated defect to test their efficiency and execution time. But in real life, the defect pattern of a chip is not completely random, it follows a distribution pattern and the algorithms should be tested on chips with similar error distribution patterns. So, in this paper, we propose a Statistical Error and Redundancy Analysis Simulator to generate defects on the chips similar to defects on the manufacturing line. These chips are tested with existing RA algorithms to analyze their performance. The simulated errors on the chips are based on statistical models derived from real data. After generating defects on the chip, execution, comparison and benchmarking of algorithms based on yield and execution time is done. The simulator gives insights on algorithm behavior with different kinds of memory architectures and defect patterns. This allows designers of memory architecture and RA algorithm to simulate and predict wafer yield for different RA algorithm designs and memory architectures before manufacturing a new memory device.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/8920344)

Recommended citation: Atishay, A. Gupta, R. Sonawat, H. K. Thacker and B. Prasanth, 'SEARS: A Statistical Error and Redundancy Analysis Simulator,' 27th International Conference on VLSI-SoC, pp. 117-122, 2019.
