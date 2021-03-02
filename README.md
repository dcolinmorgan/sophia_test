## Intro:
I am a visual thinker, and knowing only the basics of pair-end short read sequencing I found a really nice paper and [python package](https://github.com/OpenGene/AfterQC) for paired-end short read analysis and QC.

>Shifu Chen, Tanxiao Huang, Yanqing Zhou, Yue Han, Mingyan Xu and Jia Gu. AfterQC: automatic filtering, trimming, error removing and quality control for fastq data. BMC Bioinformatics 2017 18(Suppl 3):80 https://doi.org/10.1186/s12859-017-1469-3

## CH outperforms AH on several respects:

1.Erratic base content distributions  <br>

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig6_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig6_R1_a.png) | ![CH_Fig6_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig6_R1_a.png)<br>
2|![AH_Fig6_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig16_R2_a.png) | ![CH_Fig16_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig16_R2_a.png)

2.Skewed CG count distribution  <br>

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig7_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig17_R2_a.png) | ![CH_Fig7_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig7_R1_a.png)<br>
2|![AH_Fig7_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig7_R1_a.png) | ![CH_Fig17_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig17_R2_a.png)

3.Poor correlation of Kmr strand bias <br>

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig9_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig9_R1_a.png) | ![CH_Fig9_R1_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig9_R1_a.png)<br>
2|![AH_Fig19_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/AH/AH_Fig19_R2_a.png) | ![CH_Fig19_R2_a](https://raw.githubusercontent.com/dcolinmorgan/sophia_test/master/CH/CH_Fig19_R2_a.png)
