---
title: "Multiset correlation and factor analysis enables exploration of multiomic data"
collection: talks
type: "Talk"
permalink: /talks/2022-CHARGE-spring
venue: "CHARGE Philidelphia Spring 2022"
date: 2022-04-28
location: "Philidelphia, PA USA"
---

[Link to slides](http://brielin.github.io/files/CHARGE-2022-spring.pdf)

Abstract:
Multi-omics datasets promise to revolutionize biomedical research, providing insight into the coordination of molecular processes that cannot be inferred from any single omics type in isolation. However, methods for the integration of such data are currently lacking. Here, we introduce Multi-set Correlation and Factor Analysis (MCFA), an unsupervised data integration method that generalizes canonical correlation analysis and enables fast inference of shared and private factors in multi-modal data. MCFA is specifically designed to overcome challenges that are common with genomics data such as high data dimensionality and the unknown contributions of dataset-specific technical factors. We used MCFA to integrate methylation markers, protein expression, RNA expression, and metabolite levels in 614 samples from the MESA cohort analyzed in the TOPMed multi-omics pilot. We found extensive sharing across modalities: 30% of the total variance in protein expression is explained by the shared space, and 17% for RNA expression. We observed that samples cluster strongly by race in the shared space, even with the absence of genetic information. Building on this, we used linear modeling to determine variance in sample metadata explained by the shared space. The shared space captures 79% of the variance in race, 97% of the variance in sex, and 57% of the variance in age, while additionally capturing effects of cell-type composition, air quality, inflammatory biomarkers, and more. Dataset-private spaces often captured technical features such as sequencing center but also captured residual variation in cell-type composition and, in the case of metabolite data, the month of sample collection. Finally, we integrated whole genome sequencing data by conducting a genome-wide association study of the shared factors. We found enrichment of genetic association with shared factors at known disease GWAS SNPs and eQTLgen trans-eQTLs. Our study provides a foundation and framework for further integrative analysis of ever larger multi-modal genomic datasets.
