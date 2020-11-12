---
layout: page
subheadline:
title:  "Teaching"
teaser: Causality in Biomedicine
permalink: "/teaching/"

image:
    title: V2_Teaching.jpg
    
---

<strong>Causality in Biomedicine</strong> is a course aimed at biologists, computer scientists and more broadly researchers from quantitative backgrounds.

The course begins by motivating the role of causal inference in biomedicine using three different major areas where causal techniques are currently being actively developed and applied: Personalised Medicine, Genome-Wide Association Studies (GWAS) and Gene Networks. This is followed by mathematically demonstrating why inferring causality directly from observational data using standard statistical estimators leads to biased or incorrect estimates for the quantities of interest and illustrate complications that may arise in a simple example. The course is split into two main parts: (i) Causal Effect Estimation and (ii) Causal Discovery and its relation to Machine Learning and AI. Causal Effect Estimation is discussed using two major frameworks: (i) the potential outcomes framework due to Rubin, and (ii) the Structural Causal Models (SCMs) due to Pearl. The second part of the course focuses on algorithms in Causal Discovery and recent Machine Learning developments in this area.

<!-- Given the broad expertise of the audience, the course is designed to contain biomedical motivations and examples as well as quantitative information and formulae. One of the goals of this course is to encourage interactive discussions amongst biologists and computer scientists across IGMM and the School of Informatics, particularly because Causality is an area that requires strong collaborations between the two sides. -->

<!-- <strong>Overview of the course:</strong>

<u>Estimating causal effects:</u>
1. Randomised trials vs observational data
2. Causal Effect Estimation
3. Rubin: Potential outcomes framework (observed & unobserved confounders)
4. Pearl: Structural causal models framework (observed & unobserved confounders)
5. Computer simulations and numerical exercises: Introducing Microsoft DoWhy and CausalGraphicalModels Python package

<u>Causal Discovery and Machine Learning:</u>
1. Constraint-based algorithms and Score-based algorithms
2. Connections to Machine Learning and AI -->



<table class="center">
<thead>
  <tr>
    <th>Date</th>
    <th>Topics</th>
    <th>Lecture</th>
  </tr>
</thead>
 <tbody>
     <tr>
      <td>23/Oct/2020</td>
      <td>Randomised experiments vs observational data <br/> Rubin-Neyman potential outcomes framework </td>
      <td><a href="/slides/Lec1_Introduction.pdf" download="">Lecture 1 slides</a><br />
      <a href="https://media.ed.ac.uk/media/Causality+in+BiomedicineA+Lecture+1/1_kliyh0nh/186508923">Video</a></td>
  </tr>
     <tr>
      <td>30/Oct/2020</td>
      <td> Confounders: Regression adjustment & propensity score <br/> Sensitivity analysis </td>
      <td><a href="/slides/Lec2_Rubin_potential_outcomes.pdf" download="">Lecture 2 slides</a><br />
      <a href="https://media.ed.ac.uk/media/Causality+in+BiomedicineA+Lecture+2/1_vvthlo84/186508923">Video</a></td>
  </tr>
    <tr>
      <td>6/Nov/2020</td>
      <td> Confounders: Instrumental variable (IV) <br/> Intro to causal graphical models </td>
      <td><a href="/slides/Lec3_IV.pdf" download="">Lecture 3 slides</a><br /></td>
    </tr>
      <tr>
      <td>13/Nov/2020</td>
      <td> Pearl's back-door criterion <br/> Confounder vs mediator </td>
      <td></td>
  </tr>
 </tbody> 
</table>


<strong>Learning outcomes:</strong>
1. Be able to find and follow papers in causal analysis techniques 
2. Understand which area of causal analysis the papers apply to
3. Be able to apply causal techniques to a particular problem of interest 
4. Use causal analysis packages in R and Python, for example, Microsoft DoWhy and CausalGraphicalModels
5. Be able to modify a current technique in order to apply it to a particular problem of interest 
6. For quantitative individuals in the audience: A foundation to start developing techniques in causal inference and causal discovery

