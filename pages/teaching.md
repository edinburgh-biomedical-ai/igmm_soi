---
layout: page
subheadline:
title:  "Teaching"
teaser: "Undergradute, MSc and PhD training"
permalink: "/teaching/"

---
<strong>Causality in Biomedicine</strong> is a course aimed at biologists, computer scientists and more broadly researchers from quantitative backgrounds. Lecture slides (winter 2020) can be found [here][1].

The course begins by motivating the role of causal inference in biomedicine using three different major areas where causal techniques are currently being actively developed and applied: Personalised Medicine, Genome-Wide Association Studies (GWAS) and Gene Networks. This is followed by mathematically demonstrating why inferring causality directly from observational data using standard statistical estimators leads to biased or incorrect estimates for the quantities of interest and illustrate complications that it may lead to in a simple example. The course is split into two main parts: (i) Causal Effect Estimation and (ii) Causal Discovery and its relation to Machine Learning and AI. I will discuss Causal Effect Estimation using two major frameworks: (i) the potential outcomes framework due to Rubin, and (ii) the Structural Causal Models (SCMs) due to Pearl. Finally, algorithms in Causal Discovery and recent Machine Learning developments in this area are discussed. 

Given the broad expertise of the audience, the course is designed to contain both biomedical motivations and examples as well as quantitative information and formulae. One of the goals of this course is to encourage interactive discussions amongst biologists and computer scientists across IGMM and the School of Informatics, particularly because Causality is an area that requires strong collaborations between the two sides.

<strong>Overview of the course:</strong>

<u>Estimating causal effects:</u>
1. Randomised trials vs observational data
2. Causal Effect Estimation
3. Rubin: Potential outcomes framework (observed & unobserved confounders)
4. Pearl: Structural causal models framework (observed & unobserved confounders)
5. Computer simulations and numerical exercises: Introducing Microsoft DoWhy and CausalGraphicalModels Python package

<u>Causal Discovery and Machine Learning:</u>
1. Constraint-based algorithms and Score-based algorithms
2. Connections to Machine Learning and AI


<strong>Learning outcomes:</strong>
Be able to find and follow papers in causal analysis techniques 
Understand which area of causal analysis the papers apply to
Be able to apply causal techniques to a particular problem of interest 
Use causal analysis packages in R and Python, for example, Microsoft DoWhy and CausalGraphicalModels
Be able to modify a current technique in order to apply it to a particular problem of interest 
For quantitative individuals in the audience: A foundation to start developing techniques in causal inference and causal discovery

[1]: https://github.com/avakhamseh/Causality_in_Biomedicine_Lectures