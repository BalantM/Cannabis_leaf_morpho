# Cannabis_leaf_morpho

This repository contains the data and code used in the manuscript *Intra-leaf modeling of *Cannabis* leaflet shape produces synthetic leaves that predict genetic and developmental identities* by Balant, M., Garnatje, T., Vitales, D., Hidalgo, O., Chitwood, DH. (Manuscript submitted; currently undergoing journal revisions)

### Abstract
The iconic, palmately compound leaves of *Cannabis* have attracted significant attention in the past. However, investigations into the genetic basis of leaf shape or its connections to phytochemical composition have yielded inconclusive results. This is partly due to prominent changes in leaflet number between leaves of a single plant during development, which has until this point prevented the proper use of common morphometric techniques. Here we present a new method that overcomes the challenge of nonhomologous landmarks in *Cannabis*. By modeling leaflet shape as a function of angle within a leaf, we create synthetic leaves with comparable numbers of leaflets to which morphometric analysis is applied. Using 1,995 pseudo-landmarks in synthetic leaves, we visualize a morphospace and accurately predict accession identity, leaflet number, and relative node number. Intra-leaf modeling offers a rapid, cost-effective means of identifying *Cannabis* accessions, making it a valuable tool for future taxonomic studies, cultivar recognition, and possibly chemical content analysis and sex identification, in addition to permitting the morphometric analysis of leaves in any species with variable numbers of leaflets or lobes.

### Description

In this repository you can find a dataset composed of 339 leaves from 24 individuals from nine *Cannabis* accessions, including both wild/feral accessions and cultivated varieties. 

1. Jupyter notebook *01_trace_leaf.ipynb* - extraction of the outlines of the scannes leaves
2. Jupyter notebook *02_model_and_visualize_leaf.ipynb* - data analysis workflow
3. The folder *03_out* containing the files with outline coordinates used in this study
4. The folder *04_land* containing the files with landmark corrdinates used in this study
