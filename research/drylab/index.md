---
layout: page
subheadline:
title:  "Dry Lab"
teaser: "One of the aims of biomedical genomics is to determine causal molecular interactions underlying biological processes. These interactions can be highly complex, involving many dependent variables constituting a given biological system of interest. Quantifying interactions, beyond extracting their magnitude, and moving towards obtaining information on their directionality (causality) requires well-designed experiments and/or large-scale individual-level biomedical data."

image:
    title: tianyi-ma-WiONHd_zYI4-unsplash.jpg
    caption: An unsplash photo
    caption_url: https://unsplash.com/photos/WiONHd_zYI4

---
One of our current research interests involves developing causal inference, probabilistic and machine learning techniques to predict higher-order interactions amongst variables in biomedical data. We import and develop methods that are generally applicable to different biomedical datasets. Since such data typically involves many dependent variables that influence each other, inferring unbiased causal estimates is a challenging task. However, it has been made more accessible via the framework of Targeted Learning, a subfield of mathematical statistics, created by Mark van der Laan, Professor of Biostatistics and Statistics at UC Berkeley. Targeted Learning demands that subject experts define their target quantity of interest objectively (non-parametrically), whilst relying on as few assumptions as possible.

By either generating data from well-controlled randomised experiments in the lab (1), or using large-scale data bases such as the UK Biobank (2), we seek to address the following important biomedical questions by employing the above methods:

1. <strong><u>Cancer Biology</u></strong>:  We design and/or apply computational methods to analyse and predict how different combinations of mutations relate to their transcriptional trajectory, as well as infer how different driver mutations cooperate or compete in early oncogenesis.

2. <strong><u>Population Biomedicine & Causality</u></strong>: Genome-wide association studies (GWAS) are methods to identify genetic variants in the genome of individuals in a population, that could be associated with a disease or trait. In case-control GWAS, one searches for variants, a collection of single nucleotide changes in the DNA, that occur more frequently in people with a particular disease (cases) as compared to those without the disease (controls). The goal of GWAS is to find candidate genes that could potentially increase the risk of a certain disease, with the medical aim of identifying potential drug targets. Currently, one of the main aims of this field of study is to move away from associational to causal variant-trait relations. For the magnitude of causal effects of genomic variants on traits to be inferred accurately, one is required to (i) relax parametric assumptions such as the linear dependencies of the traits on the variants, and (ii) take into account interactions amongst the variants affecting traits, known as epistasis.
