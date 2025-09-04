---
layout: single
classes: wide
permalink: /open_science/
title: "Open science"
---

# My open science efforts

I believe that it is my responsibility as a scientist to make my work fully transparent and reproducible. I also believe that following the principles of transparency and reproducibility naturally lead to the creation of rigorous documentation, which can be viewed as a resource for training the next generation of scientists. Here I detail my special interest in creating resources that facilitate transparent and reproducible practices, AKA "open science".

# Public access to sequence data

To date, I have contributed 

# Building a codebase

By creating GitHub repositories containing detailed documentation for each of the first-author projects I've led, I have generated a large codebase containing helpful scripts for running a myriad of phylogenetic and population genetic analyses, which you can peruse [here](https://github.com/DevonDeRaad?tab=repositories). In addition to making my individual projects transparent and reproducible, I take pride in maintaining this codebase as a public resource that can be used by the entire evolutionary genomics community. I am especially excited about the ability to use this codebase as a resource to help catalyze the growth of current and future mentees, helping to foster their rapid development into independent researchers.

# Software

### SNPfiltR
As part of my empirical work on the genomics of wild bird populations undertaken during my PhD, I identified a gap in available pipelines for analyzing next-generation sequence data (i.e., Illumina short-read sequences mapped to a reference genome). Specifically, there was no available software designed to filter single nucleotide polymorphism (SNP) datasets in an interactive way with built-in visualization tools. This typically resulted in users falling back on previously published sets of "standard filters", rather than optimizing filtering parameters based on the idiosyncracies of their specific dataset. To address this gap I developed the R package SNPfiltR, which is designed to visualize key parameters such as genotype quality and missing data proportion, allowing users to quickly and interactively design an optimized set of filtering parameters for their SNP dataset, without the hassle and potential introduction of mistakes associated with designing unique, homebrewed visualization and filtering scripts for each SNP dataset. A [manuscript](https://onlinelibrary.wiley.com/doi/abs/10.1111/1755-0998.13618) announcing the package was published in Molecular Ecology Resources and the package is freely available for download via [CRAN](https://cran.r-project.org/web/packages/SNPfiltR/index.html) and [GitHub](https://github.com/DevonDeRaad/SNPfiltR). The package website [https://devonderaad.github.io/SNPfiltR/](https://devonderaad.github.io/SNPfiltR/) contains detailed tutorial-style vignette walkthroughs demonstrating the filtering process for real empirical datasets.

### bgchm
I am involved as a co-author on the R package [bgchm](https://github.com/zgompert/bgc-hm), which is focused on updating Bayesian approaches to genomic and geographic cline analysis using Hamiltonian Monte Carlo (HMC; as opposed to the traditional Markov Chain Monte Carlo, MCMC) for sampling posterior distributions. This update facilitates faster and more accurate sampling of posterior distributions, allowing the R package to handle genome-scale datasets. The manuscript announcing the details of the package update can be found [here](https://www.biorxiv.org/content/10.1101/2024.03.29.587395v1).

# Workshops

### RADseq analysis workshop
In Fall 2022 I led a group of graduate students through a semester-long weekly workshop detailing the process of analyzing RADseq data from start to finish. This workshop included hands-on training on: understanding file directory structure, navigating the command-line interface, using a high performance computing cluster (HPCC), using RStudio to interactively filter SNP datasets using SNPfiltR, and performing standard descriptive phylogenetic and population genetic analyses. The materials for this workshop are publicly available and documented in the following [GitHub repository](https://github.com/DevonDeRaad/Fall.2022.RAD.workshop). Visualization of the workshop's structure is here:
![RADseq workshop structure](/assets/images/rad.workshop.png)

### SNPfiltR workshop (AOS 2023)
At the American Ornithological Society meeting in Ontario, Canada (August 2023) I led a half-day workshop designed to take a group of investigators through the process of filtering their SNP datasets. The materials are based heavily on the [SNPfiltR website](https://devonderaad.github.io/SNPfiltR/) and the exact details can be found in this publicly available [GitHub repository](https://github.com/DevonDeRaad/AOS.SNP.filtering.workshop).
