# 🎉 Movie Recommendations using Matrix Factorization for MovieLens 🎉
Manos Chatzakis, Hind El-Bouchrifi and Lluka Stojollari

{emmanouil.chatzakis, hind.elbouchrifi, lluka.stojollari}@epfl.ch

Distributed Information Systems, Recommender Systems Project, EPFL

## Context
This repository contains a solution to a [Kaggle](https://www.kaggle.com/competitions/dis-project-2-recommender-system/) competition of Distributed Information Systems course of EPFL. The competition is about the creation of a Recommendation Engine for the MovieLens dataset, which is automatically evaluated in the competition using RMSE.

## Approach
We describe our approach in our report (report/Report.pdf), as well us our final submission notebook (src/kaggle.ipynb). Briefly, we utilize an optimized Matrix Factorization approach to generate user rating predictions. 

## Contents
- src/
    - models/
        - Code for all implemented information retrieval models (TF-iDF, Doc2vec, DSSM, BM25)
    - preprocessors/
        - Code for all preprocessing and query expansion techniques
    - scripts/
        - Pipelines for model training, text preprocessing, query expansion
    - testing/
            - Examples of model usage
    - IR_Utils.ipynb: Utility functions for IR
    - kaggle.ipynb: Final competition notebook, implementing our final best scoring approach

- report/
    - report.pdf: A brief report describing our approach

- data/
    - Movielens data

## Data Availability
Test and training query splits are present under data/ directory. Every other needed file is available at [Google Drive](https://drive.google.com/drive/folders/1Vw6yYoB8Akq_kde3RIS4y9HQdMXjih07)
