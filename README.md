# SIMPLE: Statistical Inference on Membership Profiles in Large Networks
This repository contains the implementation, simulation studies, and real-world data analysis for our STAT293 project based on “SIMPLE: Statistical Inference on Membership Profiles in Large Networks” by ([Fan et al. (2021)](#ref-SIMPLE2021)).
The goal of this project is to understand and apply the SIMPLE methodology to test whether two nodes in a network share the same latent membership profile under both the Mixed Membership Stochastic Block Model (MMSB) and the Degree-Corrected Mixed Membership Model (DCMM).

## Authors
* Yuxin Liu
* Funmi Olawole

## SIMPLE Test Implementation
The notebook `Implement.ipynb` includes:
* All needed functions for SIMPLE Test 1 (MMSB) and Test 2 (DCMM)
* Simulation-Based Validation of SIMPLE
* Sensitivity Analyses
* Robustness Analysis Across Parameter Settings


## Airport Network Analysis
The notebook `Flightnetwork.ipynb` includes:
* Build an undirected network using `airports.dat` and `routes.dat`
* Perform spectral clustering for exploratory grouping
* Compute SIMPLE p-values for selected across-cluster and within-cluster airport pairs
* Visualize global airport communities on a geographical map
* Evaluate how SIMPLE complements clustering by revealing pairwise structural differences

## Data Sources
The real-world dataset is from the OpenFlights Global Airport Database:  
Airport metadata can be accessed in `airports.dat`.  
Flight routes can be accessed in `routes.dat`.  
Data source is from </em>https://github.com/jpatokal/openflights/tree/master.

## Final Report \& Slides
Final report writing files and figures are saved in `FinalReport/`.  
Final report generated file is `FinalReport.zip`.  
Final report compiled PDF file is `FinalReport.pdf`.  
The slides generated file is `FinalSlides.zip`.  
The slides is `FinalSlides.pdf`. 

## References
<div id="refs" class="references">
<div id="ref-SIMPLE2021">
Jianqing Fan, Yingying Fan, Xiao Han, and Jinchi Lv. 2021. "SIMPLE: Statistical Inference on Membership Profiles in Large Networks." <em>Journal of the Royal Statistical Society: Series B (Statistical Methodology)</em>. 
https://arxiv.org/abs/1910.01734.
</div>
</div>
