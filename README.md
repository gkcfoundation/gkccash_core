GKC Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/GKC-Project/GKC.svg?branch=master)](https://travis-ci.org/GKC-Project/GKC) [![GitHub version](https://badge.fury.io/gh/GKC-Project%2FGKC.svg)](https://badge.fury.io/gh/GKC-Project%2FGKC)

GKC is a cutting-edge cryptocurrency with many functions that most other cryptocurrencies do not have.

1. The POS function design with entrusted PO is adopted, and the number of DPOS nodes is not limited. Currently, there are more than 110 effective DPOS nodes;
2. Use sigma protocol for anonymous transactions;
3. Fast transactions with guaranteed zero confirmation transactions, which we call SwiftTX;
4. Decentralized blockchain voting provides consensus for the advanced consensus-based Masternode technology, which is used to protect the network and provide the above functions. Each Masternode has a 10K GKC mortgage;
5. Integrated EVM virtual, with Turing complete smart contract.

### Build
See depends/README.md


### Coin Specs
<table>
<tr><td>Algo</td><td>scrypt</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>PoW Coin Supply</td><td>23,509,830 GKC</td></tr>
<tr><td>PoS Coin Supply</td><td>8,900,500 GKC</td></tr>
<tr><td>Season Supply</td><td>3,681,600 GKC</td></tr>
<tr><td>Total Supply</td><td>36,091,930 GKC</td></tr>
</table>


### PoW Rewards Breakdown

First_Block	Last_Block	Miner	Total	Acc
1	1	23000000.00000000 	23000000.00000000 	23000000.00000000 
2	3000	170.00000000 	509830.00000000 	23509830.00000000 


### PoS Rewards Breakdown

First_Block	Last_Block	Miner	Masternodes	Entrust	Fund	Total	Acc
3001	250000	1.20000000 	0.60000000 	6.60000000 	0.00000000 	2074800.00000000 	2074800.00000000 
250001	538680	1.20000000 	0.48000000 	6.60000000 	0.35000000 	2390270.40000000 	4465070.40000000 
538681	1074360	0.60000000 	0.24000000 	3.30000000 	0.17500000 	2217715.20000000 	6682785.60000000 
1074361	1610040	0.30000000 	0.12000000 	1.65000000 	0.08750000 	1108857.60000000 	7791643.20000000 
1610041	2145720	0.15000000 	0.06000000 	0.82500000 	0.04375000 	554428.80000000 	8346072.00000000 
2145721	2681400	0.07500000 	0.03000000 	0.41250000 	0.02187500 	277214.40000000 	8623286.40000000 
2681401	3217080	0.03750000 	0.01500000 	0.20625000 	0.01093750 	138607.20000000 	8761893.60000000 
3217081	3752760	0.01875000 	0.00750000 	0.10312500 	0.00546875 	69303.60000000 	8831197.20000000 
3752761	4288440	0.00937500 	0.00375000 	0.05156250 	0.00273438 	34651.80000000 	8865849.00000000 
4288441	4824120	0.00468750 	0.00187500 	0.02578125 	0.00136719 	17325.90000000 	8883174.90000000 
4824121	5359800	0.00234375 	0.00093750 	0.01289063 	0.00068359 	8662.95000000 	8891837.85000000 
5359801	5895480	0.00117188 	0.00046875 	0.00644531 	0.00034180 	4331.47500000 	8896169.32500000 
5895481	6431160	0.00058594 	0.00023438 	0.00322266 	0.00017090 	2165.73750000 	8898335.06250000 
6431161	6966840	0.00029297 	0.00011719 	0.00161133 	0.00008545 	1082.86875000 	8899417.93125000 
6966841	7502520	0.00014648 	0.00005859 	0.00080566 	0.00004272 	541.43437500 	8899959.36562500 
7502521	8038200	0.00007324 	0.00002930 	0.00040283 	0.00002136 	270.71718750 	8900230.08281250 
8038201	8573880	0.00003662 	0.00001465 	0.00020142 	0.00001068 	135.35859375 	8900365.44140625 
8573881	9109560	0.00001831 	0.00000732 	0.00010071 	0.00000534 	67.67929688 	8900433.12070312 
9109561	9645240	0.00000916 	0.00000366 	0.00005035 	0.00000267 	33.83964844 	8900466.96035156 
9645241	10180920	0.00000458 	0.00000183 	0.00002518 	0.00000134 	16.91982422 	8900483.88017578 
10180921	10716600	0.00000229 	0.00000092 	0.00001259 	0.00000067 	8.45991211 	8900492.34008789 
10716601	11252280	0.00000114 	0.00000046 	0.00000629 	0.00000033 	4.22995605 	8900496.57004394 
11252281	11787960	0.00000057 	0.00000023 	0.00000315 	0.00000017 	2.11497803 	8900498.68502197 
11787961	12323640	0.00000029 	0.00000011 	0.00000157 	0.00000008 	1.05748901 	8900499.74251098 
12323641	12859320	0.00000014 	0.00000006 	0.00000079 	0.00000004 	0.52874451 	8900500.27125549 
12859321	13395000	0.00000007 	0.00000003 	0.00000039 	0.00000002 	0.26437225 	8900500.53562775 
13395001	13930680	0.00000004 	0.00000001 	0.00000020 	0.00000001 	0.13218613 	8900500.66781387 
13930681	14466360	0.00000002 	0.00000001 	0.00000010 	0.00000001 	0.06609306 	8900500.73390693 
14466361	15002040	0.00000001 	0.00000000 	0.00000005 	0.00000000 	0.03304653 	8900500.76695347 
15002041	INF	0.00000000 	0.00000000 	0.00000002 	0.00000000 	0.00000000 	8900500.76695347 


### Season Rewards Breakdown

First_Block	Last_Block	Season	Reward	Total	Acc
3001	538680	6	156000.00000000 	936000.00000000 	936000.00000000 
250001	538680	6	145600.00000000 	873600.00000000 	1809600.00000000 
538681	1074360	12	78000.00000000 	936000.00000000 	2745600.00000000 
1074361	1610040	12	39000.00000000 	468000.00000000 	3213600.00000000 
1610041	2145720	12	19500.00000000 	234000.00000000 	3447600.00000000 
2145721	2681400	12	9750.00000000 	117000.00000000 	3564600.00000000 
2681401	3217080	12	4875.00000000 	58500.00000000 	3623100.00000000 
3217081	3752760	12	2437.50000000 	29250.00000000 	3652350.00000000 
3752761	4288440	12	1218.75000000 	14625.00000000 	3666975.00000000 
4288441	4824120	12	609.37500000 	7312.50000000 	3674287.50000000 
4824121	5359800	12	304.68750000 	3656.25000000 	3677943.75000000 
5359801	5895480	12	152.34375000 	1828.12500000 	3679771.87500000 
5895481	6431160	12	76.17187500 	914.06250000 	3680685.93750000 
6431161	6966840	12	38.08593750 	457.03125000 	3681142.96875000 
6966841	7502520	12	19.04296875 	228.51562500 	3681371.48437500 
7502521	8038200	12	9.52148438 	114.25781250 	3681485.74218750 
8038201	8573880	12	4.76074219 	57.12890625 	3681542.87109375 
8573881	9109560	12	2.38037109 	28.56445313 	3681571.43554687 
9109561	9645240	12	1.19018555 	14.28222656 	3681585.71777344 
9645241	10180920	12	0.59509277 	7.14111328 	3681592.85888672 
10180921	10716600	12	0.29754639 	3.57055664 	3681596.42944336 
10716601	11252280	12	0.14877319 	1.78527832 	3681598.21472168 
11252281	11787960	12	0.07438660 	0.89263916 	3681599.10736084 
11787961	12323640	12	0.03719330 	0.44631958 	3681599.55368042 
12323641	12859320	12	0.01859665 	0.22315979 	3681599.77684021 
12859321	13395000	12	0.00929832 	0.11157990 	3681599.88842010 
13395001	13930680	12	0.00464916 	0.05578995 	3681599.94421005 
13930681	14466360	12	0.00232458 	0.02789497 	3681599.97210503 
14466361	15002040	12	0.00116229 	0.01394749 	3681599.98605251 
15002041	15537720	12	0.00058115 	0.00697374 	3681599.99302626 
15537721	16073400	12	0.00029057 	0.00348687 	3681599.99651313 
16073401	16609080	12	0.00014529 	0.00174344 	3681599.99825656 
16609081	17144760	12	0.00007264 	0.00087172 	3681599.99912828 
17144761	17680440	12	0.00003632 	0.00043586 	3681599.99956414 
17680441	18216120	12	0.00001816 	0.00021793 	3681599.99978207 
18216121	18751800	12	0.00000908 	0.00010896 	3681599.99989104 
18751801	19287480	12	0.00000454 	0.00005448 	3681599.99994552 
19287481	19823160	12	0.00000227 	0.00002724 	3681599.99997276 
19823161	20358840	12	0.00000114 	0.00001362 	3681599.99998638 
20358841	20894520	12	0.00000057 	0.00000681 	3681599.99999319 
20894521	21430200	12	0.00000028 	0.00000341 	3681599.99999660 
21430201	21965880	12	0.00000014 	0.00000170 	3681599.99999830 
21965881	22501560	12	0.00000007 	0.00000085 	3681599.99999915 
22501561	23037240	12	0.00000004 	0.00000043 	3681599.99999957 
23037241	23572920	12	0.00000002 	0.00000021 	3681599.99999979 
23572921	24108600	12	0.00000001 	0.00000011 	3681599.99999989 
24108601	INF	12	0.00000000 	0.00000000 	3681599.99999989 
