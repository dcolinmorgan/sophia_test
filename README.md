## Summary of Task:
I am a visual thinker, and knowing only the basics of what I could gather on the details of pair-end short read sequencing in a week, I found a really nice paper and [python package](https://github.com/OpenGene/AfterQC) for paired-end short read analysis and QC. From what I was able to gather, QC can be controlled for based on a few criteria, of which I chose three which most differentiated the two processed files presented in the assigned task. Based on the plots presented below, which use the three criteria to compare between the processing methods, I determined CH to be the superior method for such analysis, for its [nice content distribution](#1-erratic-base-content-distributions), [CG count distribution](#2-skewed-cg-count-distribution) and most tellingly I think, [the correlation in both reads between forward and reverse strand bias](#3-poor-correlation-of-kmr-strand-bias). From the perspective of a data scientist as well as a biologist, I should think the high correlation between forward and reverse strands a hallmark of accurate sequencing.

>Shifu Chen, Tanxiao Huang, Yanqing Zhou, Yue Han, Mingyan Xu and Jia Gu. AfterQC: automatic filtering, trimming, error removing and quality control for fastq data. BMC Bioinformatics 2017 18(Suppl 3):80 https://doi.org/10.1186/s12859-017-1469-3

## CH outperforms AH on several respects:

### 1. Erratic base content distributions

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig6_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig6_R1_a.png) | ![CH_Fig6_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig6_R1_a.png)<br>
2|![AH_Fig6_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig16_R2_a.png) | ![CH_Fig16_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig16_R2_a.png)

### 2. Skewed CG count distribution

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig7_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig17_R2_a.png) | ![CH_Fig7_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig7_R1_a.png)<br>
2|![AH_Fig7_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig7_R1_a.png) | ![CH_Fig17_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig17_R2_a.png)

### 3. Poor correlation of Kmr strand bias

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig9_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig9_R1_a.png) | ![CH_Fig9_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig9_R1_a.png)<br>
2|![AH_Fig19_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig19_R2_a.png) | ![CH_Fig19_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig19_R2_a.png)
