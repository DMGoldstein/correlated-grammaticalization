# Data and source code for the paper "Correlated grammaticalization: The rise of articles in Indo-European" 

## Overview

This repository contains the data and source code for the paper "There's no escaping phylogenetics."

## Data

The data used in the paper can be found in the folder `data`, which contains two Nexus files, `final_narrow_dataset.nex` and `final_broad_dataset.nex`. These are the narrow and broad datasets, respectively. 

## Scripts

The folder `scripts` contains two sub-folders, `likelihood` and `mcmc`. The former contains the `.Rev` scripts for calculating the marginal likelihoods and the latter the scripts for the MCMC sampling of the posterior distributions. The analyses for both were carried out with RevBayes v.1.1.1.

## Trees

There are two files in the `Trees` folder, `ChangA3.tree` and `ieo_hundred.nex`. The first of these is the MAP tree from the A3 dataset and model of Chang et al. 2015 (which is configuration file `a1-c2-d0-g2-l2-s1-t1-z3` in their supplementary materials). The second is a sample of one hundred trees generated from this model and dataset. 

## Results for the analysis of the broad dataset

The folder `broad-dataset-results` contains a `.pdf` file with an overview of the broad dataset and the posterior distributions of the rates obtained with `final_broad_dataset.nex` and `final_broad_dependent.Rev`.

