Introduction
============
    This document is intended to specify a set of requirements for the 
    project IDEG, which means “Identify Differently Expressed Genes”, 
    a web application for identifying genes’ expression differential..


Purpose
-------
    This article explains the basic design idea and basic function of 
    the gene system with different expression of syndrome differentiation, 
    so as to facilitate the discussion between gene researchers and fans. 
    In the range of gene expression we know, the software can find out the 
    differences between the expressed genes and distinguish the different 
    expressed genes.


The terms defined & Terminologies
---------------------------------
    * *IDEG*- Identification of differently Expressed Genes, which is the name of this project.
    * *logFC*- log fold change of gene expression. log_2 [T/C], where T is the gene expression level from a treatment sample, while C is the gene expression level from a control sample
    * *Control sample*- A cell sample prepared in its normal condition.
    * *Treatment sample*- A cell sample treated by special chemicals, or in which some genes are altered.
    * *Up-regulation*- A gene is said to be up-regulated if it has higher expression in treatment than in control.