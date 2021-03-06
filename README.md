<h1 align="center">
  <img alt=" Improving genomic prediction for seed quality traits in oat (Avena sativa L.) using trait-specific relationship matrices" width = "1711.846" height = "200" src = Title.svg>
</h1>


## Abstract
The observable phenotype is the manifestation of information that is passed along different organization levels (transcriptional, translational, and metabolic) of a biological system. The widespread use of various omic technologies (RNA-sequencing, metabolomics, etc.) has provided plant genetics and breeders with a wealth of information on pertinent intermediate molecular processes that may help explain variation in conventional traits such as yield, seed quality, and fitness, among others. A major challenge is effectively using these data to help predict the genetic merit of new, unobserved individuals for conventional agronomic traits. Trait-specific genomic relationship matrices (TGRMs) model the relationships between individuals using genome-wide markers (SNPs) and place greater emphasis on markers that most relevant to the trait compared to conventional genomic relationship matrices. Given that these approaches define relationships based on putative causal loci, it is expected that these approaches should improve predictions for related traits. In this study we evaluated the use of TGRMs to accommodate information on intermediate molecular phenotypes (referred to as endophenotypes) and to predict an agronomic trait, total lipid content, in oat seed. Nine fatty acids were quantified in a panel of 336 oat lines. Marker effects were estimated for each endophenotype, and were used to construct TGRMs. A multikernel TRGM model (MK-TRGM-BLUP) was used to predict total seed lipid content in an independent panel of 210 oat lines. The MK-TRGM-BLUP approach significantly improved predictions for total lipid content when compared to a conventional genomic BLUP (gBLUP) approach. Given that the MK-TGRM-BLUP approach leverages information on the nine fatty acids and total lipid content to predict total lipid content in unobserved individuals, we compared the MK-TGRM-BLUP approach to a multi-trait gBLUP (MT-gBLUP)
approach that jointly fits phenotypes for fatty acids and total lipid content. The MK-TGRM-BLUP approach significantly outperformed MT-gBLUP. Collectively, these results highlight the utility of using TGRM to accommodate information on endophenotypes and improve genomic prediction for a conventional agronomic trait.

## Background
This repo contains all the code used for the manuscript.

* **1. Compute BLUPs for fatty acids**
   - Diversity Panel [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/targBLUPs_DP.Rmd)
   - Elite Panel [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/targBLUPs_Elite.Rmd)

* **2. Estimate marker effects for each fatty acid**
   - File incluedes code for Figure 1. [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/estimateMarkerEffects.Rmd)

* **3. Genomic prediction for fatty acids**
   - [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/FAprediction.Rmd)
   
* **4. Genomic prediction for total lipid content - MK-TGRM-BLUP vs gBLUP**
   - [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/NIRS_TGRMvgBLUP.Rmd)
   
* **5. Genomic prediction for total lipid content - MK-TGRM-BLUP vs multi-trait gBLUP**
   - [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/MKvMT.Rmd)
   
* **6. Genomic prediction for total lipid content - Multi-kernel prediction using kernels for most and least abundant fatty acids**
   - [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/MostLeast.Rmd)
   
* **7. Manhattan Plots**
   - [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/ManPlots.Rmd)
   
* **8. Dendrogram**
   - [.Rmd File](https://github.com/malachycampbell/TGRM_frontiers/blob/master/markdownFiles/dend.Rmd)
   
---

