---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## **Applying and Improving Model Counting**   
**Introduction:**  
We are applying and improving Model Counting which is a classical problem of computing the number of solutions for a given SAT formula. For application, we integrate state-of-the-art model counters into Alloy as another back-end engine. We also applied model counters to quantify of the performance of and semantic differences among trained machine learning models. For improvement, we are trying to utilize symmetry breaking which is a widely used approach in facilitating SAT solving, but has never been considered in model counting. Besides, we also did testing for model counters and found bugs which has been confirmed by the authors.   
**Contributions:**  
    **•** Integrated model counters into Alloy Analyzer to provide users a platform of conducting model counting for their models. This work was published at **ESEC/FSE Demo 2020**.  
    **•** Applied model counters to help evaluate ML model performance in learning relational properties of complex graph structures. This work was published at **SPIN 2019**, **PLDI 2020**.  
    **•** Studied the impact of symmetry breaking on model counting. This work was published at **TACAS 2020**.  
    **•** Tested four state-of-the-art model counters using metamorphic testing and differential testing. This work was published at **ASE 2020**.  

## **Improving Alloy Analyzer**
**Introduction:**  
We are enhancing the Alloy Analyzer, a well-known software modeling tool, based on first-order logic and SAT solving. For first-order logic level, regression command selection and solution reuse ideas can be applied in evolving Alloy models to reduce the number of SAT solver calls. For SAT level, one direction is to propose advanced searching and learning strategy using the knowledge in first-order logic level. Another possibility is to intelligently select a fast SAT solver (from candidate solvers) for different given Alloy models.  
**Contributions:**  
    **•** Proposed an approach that can efficiently conduct incremental analysis for evolving Alloy models. This work was published at **TACAS 2019**.  
    **•** Proposed an approach that uses machine learning techniques to automatically select a SAT solver for Alloy, based on the features extracted from the given model. This work was published at **ICST 2019**.  

## **A Bit-Vector Solver with Word-Level Propagation using Machine Learning**
**Introduction:**
Solving bit-vector constraint problems is an NP-hard back-end problem involved in many areas such as software verification, cryptography, scheduling and planning. Bit-vector Satisfiability Modulo Theory (SMT) solver is designed to solve huge amounts of complicated bit-vector constraints. The common method called bit-blasting is to break the bit-vector constraints down to the propositional formulas and solve them with SAT solver. However, during the ‘break’ process, lots of useful information get lost which is the bottleneck of this method. We aim to solve bit-vector constraints directly in bit-vector/word level using advanced constraint solving method.  
**Contributions:**  
    **•** Designed a novel learning and back-tracking architecture based on SAT solver called MiniSAT particularly for the word-level bit-vector SMT solver, and proposed special algorithms and policies for improving the word-level solving efficiency. This work was published at **CPAIOR 2016**.  
    **•** Proposed a portfolio bit-vector solver called Wombit which outperformed state-of-the-art solver STP significantly both in time and memory usage. This work was published at **JAR 2018**.  

