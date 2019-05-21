# A Dataset for Meta-Analysis of Defect Prediction Primary Studies #

## Contributors ##
   * Jooyong Yi (jooyong@unist.ac.kr), UNIST (Ulsan National Institute of Science and Technology)
   * Vladimir Ivanov (v.ivanov@innopolis.ru), Innopolis University
   * Giancarlo Succi (g.succi@innopolis.ru), Innopolis University

## What This Is About ##
In our [ICSE-NIER-19 paper](http://jooyongyi.com/papers/ICSE-NIER19.pdf) titled **Mining Plausible Hypotheses from the Literature via Meta-Analysis**, we conduct meta-analysis to mine plausible hypotheses about confounding factors that may affect the performance of defect prediction. 

In this repository, we share all datasets we collected, parts of which were used in our meta-analysis. 

**Note**: If you use any part of our tool or data present in this repository, then please do cite our ICSE-NIER-19 paper.

## The Dataset ##

Our dataset is stored in the following three sub-directories under the data directory.

  * AUC: In our meta-study, we compared performance of defect prediction based on AUC (Area Under the Curve). This directory contains the raw data used for our meta-analysis.  
  * AUC.stat: While most of the studies report mean values, the studies included in this directory also report standard deviations.
  * all: This directory contains all data we collected. For our meta-analysis, we used some of them that satisfies the requirements described in the paper. To relieve the burden of other researchers, we also share all data we collected. 

Lastly, the papers.xlsx contains the list of papers from which our dataset is collected. The confounding factors reported in our meta-analysis are also marked in this file.