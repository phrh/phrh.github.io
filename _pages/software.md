---
layout: page    
title: software
permalink: /software/
nav: true
---


## SPSoil
[SPSoil](https://github.com/cavargar/SPSoil) Repository for our spectral based estimation of soil properties using regression and classification.
The regression folder you will find the python code, example data and instructions to install and run the code. In the classification folder you will find the MATLAB code, example data for MATLAB and instructions to run the code.
Citation:

Delgadillo-Duran, Diego A. and Vargas-García, Cesar A. and Varón-Ramírez, Viviana M. and Calderón, Francisco and Montenegro, Andrea C. and Reyes-Herrera, Paula H. Using vis-NIRS and ML to diagnose properties in colombian sugarcane soils (2022) arXiv. https://arxiv.org/abs/2012.12995


## MultiGWAS

[MultiGWAS](https://github.com/agrosavia-bioinfo/multiGWAS)
MultiGWAS is a tool that does GWAS for diploid and tetraploid organisms by executing in parallel four GWAS software, two for polyploid data (GWASpoly and SHEsis) and two for diploids data (GAPIT and TASSEL). MultiGWAS has several advantages. It runs either in the command line or in an graphical interface; it manages different genotype formats, including VCF; it allows control for population structure and relatedness, along with several quality control checks on genotype data. Besides, MultiGWAS can test for each GWAS tool all its gene action models, and through a proprietary scoring function, select the best model to report its associations. Finally, it generates several reports that facilitate the identification of false associations from both the significant and the top association SNP among the four software.




## BackCLIP
[BackCLIP](https://github.com/phrh/BackCLIP): The PAR-CLIP protocol derives a transcriptome wide set of binding sites for RNA Binding Proteins. However, non-specific RNA background remains. We propose a tool, BackCLIP, to identify the presence of common RNA background in a PAR-CLIP dataset. We built a common background set where each element has a score that reflects its presence in several PAR-CLIP datasets. We present a tool that uses this score to identify the amount of common backgrounds present in a PAR-CLIP dataset, and we provide the user the option to use or remove it.

This Git contains the software code and output results from [P.H Reyes-Herrera, C.A Speck-Hernandez, C.A. Sierra, and S. Herrera.(2015) BackCLIP: a tool to identify common background presence in PAR-CLIP datasets. Bioinformatics.] (http://bioinformatics.oxfordjournals.org/content/early/2015/07/29/bioinformatics.btv442.abstract)




## PredRAD 
[PredRAD](https://github.com/phrh/PredRAD): High-throughput sequencing of reduced representation libraries obtained through digestion with restriction enzymes–generally known as restriction-site associated DNA sequencing (RAD-seq)–is now one most commonly used strategies to generate single nucleotide polymorphism data in eukaryotes. The choice of restriction enzyme is critical for the design of any RAD-seq study as it determines the number of genetic markers that can be obtained for a given species, and ultimately the success of a project.

For the design of a study using RAD-seq, or a related methodology, there are two general fundamental questions that researchers face: i) what is the best restriction enzyme to use to obtain a desired number of RAD tags in the organism of interest? And ii) how many markers can be obtained with a particular enzyme in the organism of interest? This software pipeline will allow any researcher to obtain an approximate answer to these questions and will help guide the design of any study using RAD sequencing and related methods.

This Git contains the software code and output results from Herrera S., P.H. Reyes-Herrera & T.M. Shank (2015) Predicting RAD-seq Marker Numbers across the Eukaryotic Tree of Life.


