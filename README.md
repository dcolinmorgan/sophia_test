## Daniel Morgan Test or Sophia Genetics 
comparison of two different target sequencing approaches (hg19) for paired-end short reads from same DNA DGS to diagnosis solid tumor.
[AH fastQC results](https://github.com/dcolinmorgan/test/AH)
[CH fastQC results](https://github.com/dcolinmorgan/test/CH)

CH outperforms AH on several respects:


1. Erratic base content distributions  <br>

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig6_R1_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/AH/AH_Fig6_R1_a.png) | ![CH_Fig6_R1_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/CH/CH_Fig6_R1_a.png)<br>
2|![AH_Fig6_R2_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/AH/AH_Fig16_R2_a.png) | ![CH_Fig16_R2_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/CH/CH_Fig16_R2_a.png)

2. Skewed CG count distribution  <br>

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig7_R1_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/AH/AH_Fig17_R2_a.png) | ![CH_Fig7_R1_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/CH/CH_Fig7_R1_a.png)<br>
2|![AH_Fig7_R2_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/AH/AH_Fig7_R1_a.png) | ![CH_Fig17_R2_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/CH/CH_Fig17_R2_a.png)

3. Poor correlation of Kmr strand bias <br>

read|AH method| CH method 
-----|---------|-----------
1|![AH_Fig9_R1_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/AH/AH_Fig9_R1_a.png) | ![CH_Fig9_R1_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/CH/CH_Fig9_R1_a.png)<br>
2|![AH_Fig19_R2_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/AH/AH_Fig19_R2_a.png) | ![CH_Fig19_R2_a](https://raw.githubusercontent.com/dcolinmorgan/test/master/CH/CH_Fig19_R2_a.png)
