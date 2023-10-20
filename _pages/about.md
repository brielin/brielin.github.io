---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoc at the New York Genome Center, jointly advised by Dr's [David Knowles](https://daklab.github.io/) and [Tuuli Lappalainen](https://tllab.org/). For the first two years of my postdoc, I was funded as a [Data Science Institute Fellow](https://datascience.columbia.edu/research/postdoctoral-researchers/) at Columbia University, where I hold a joint appointment. I am broadly interested in the development and application of statistical and computational methods in genetics and genomics with a focus on complex traits. I am particularly interested in large-scale exploratory data analysis, causal inference, 'omic data integration, and cross-ancestry analysis.

I received the PhD from the Department of Computer Science at the University of California, Berkeley in 2016, where I was jointly supervised by Dr's [Lior Pachter](https://pachterlab.github.io/) and [Noah Zaitlen](https://bioscience.ucla.edu/people/noah-zaitlen/). Prior to joining NYGC, I worked as a computational biologist at [Verily Life Sciences](https://verily.com/). In a past life, I studied [quantum complexity theory](https://csdmp.github.io/docs/brown2011.pdf).

## Research Highlights

### Multi-omic data integration
Multi-omic studies are becoming commonplace, with studies simultaneously measuring RNA sequencing, DNA methylation, chromatin accessability, and more. However, integration of these data remains challenging. I am interested in the development of methods to extract meaningful shared signal from these data and their application to the biology of human complex traits and disease. To this end, I have spent substantial time studying the application of Canonical Correlation Analysis (CCA) to genomics. As a graduate student, I helped develop [Principal Component Correlation Analysis](https://github.com/pachterlab/PCCA/), which we used to find under-appreciate population structure in the GEUVADIS study. More recently, we developed a multi-modal extension of CCA which uses a probabilistic graphical model to simultaneously estimate shared and private features in multi-omic data.

* B.C. Brown*<sup>#</sup>, C.L. Wang<sup>#</sup>, ..., D.A Knowles and T. Lappalainen (2023) [Multiset correlation and factor analysis enables exploration of multi-omic data](https://www.cell.com/cell-genomics/fulltext/S2666-979X(23)00142-8). Cell Genomics 3, 100359, 9 August 2023
* B.C. Brown, N.L. Bray, L. Pachter (2018) [Expression Reflects Population Structure](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1007841). PLOS Genetics 14(12): e1007841 19 December 2018

### Causal network inference and Mendelian randomization
Recently, the role of network structure in complex trait genetics has received renewed attention. Network structure estimation (also called _causal discovery_) is a challenging problem, however progress can be made by leveraging perturbation-response data, where one or more nodes in the network are perturbed and the response of the remaining variables is observed. We consider two sources of large-scale perturbation response data: large-scale CRISPR-based inhibition data, and genetic association data. Genetic variants provide a natural source of perturbations, which can be used to estimate putatively causal effects using a technique called Mendelian randomization. We have developed [Welch-weighted Egger regression](https://github.com/brielin/WWER) (WWER), a technique for fast estimation of pairwise bi-directed causal effects in bio-bank scale data, as well as [inverse sparse regression](https://github.com/brielin/inspre/) (inspre), a strategy for turning a dense network of pairwise causal effects into a sparse directed graph. We have applied these techniques to the genome-wide perturb seq and UK biobank datasets.

* B.C. Brown, J.A. Morries, T. Lappalainen and D.A. Knowles (2023) [Large-scale causal discovery using interventional data sheds light on the regulatory network architecture of blood traits](https://www.biorxiv.org/content/10.1101/2023.10.13.562293). bioRxiv, 13 October 2023.
* B.C. Brown* and D.A. Knowles* (2021) [Welch-weighted Egger regression reduces false positives due to correlated pleiotropy in Mendelian randomization](https://www.sciencedirect.com/science/article/pii/S0002929721003839). The American Journal of Human Genetics, 108 (12), p2319–2335, 2 December 2021
* B.C. Brown* and D.A. Knowles* (2020) [Phenome-scale causal network discovery with bidirectional mediated Mendelian randomization](https://www.biorxiv.org/content/10.1101/2020.06.18.160176v2). bioRxiv, 22 June 2020.

### Cross-population complex trait analysis
Human phenotypes vary in their global distributions due to a combination of genetic and environmental factors, however the vast majority of genetic studies of disease focus on individuals of European ancestry. We asked a simple question - does the same genetic variant have the same phenotypic effect in two ancestal populations? This led to the development of the cross-population genetic correlation, and one of the first studies that revealed practical concerns applying European-derived genetic information to other populations in the context of complex traits. The resulting tool [popcorn](https://github.com/brielin/Popcorn) is now widely used.
* M. Lam, C. Chen et al. (2019), [Comparative genetic architectures of schizophrenia in East Asian and European populations](https://www.nature.com/articles/s41588-019-0512-x). Nature Genetics 51, p1670–1678, 18 November 2019
* K.J. Galinsky, Y.A. Reshef, H.K. Finucane, P. Loh, N. Zaitlen, N.J. Patterson, B.C. Brown* and A.L. Price* (2018), [Estimating cross-population genetic correlations of causal effect sizes](https://onlinelibrary.wiley.com/doi/10.1002/gepi.22173). Genetic Epidemiology 25 November 2018
* B.C. Brown*, AGEN-T2D, C.J. Ye, A.L. Price and N. Zaitlen* (2016), [Transethnic genetic correlation estimates from summary statistics](https://www.sciencedirect.com/science/article/pii/S0002929716301355). The American Journal of Human Genetics, 99 (1), p76–88, 7 July 2016


### Note
* This site is a work in progress! Please check back later for more updates.
* This site was created by forking [https://github.com/academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io). Special thanks to all the contributors there for a wonderful template.