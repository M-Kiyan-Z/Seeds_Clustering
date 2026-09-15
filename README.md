# Seeds_Clustering

## Introduction 
This project solves a grouping/clustering problem within a dataset of different measurements of different seeds, helping farmers to divide different seed types from one another even though they arrived unlabeled.
The study and all of the relevant information has been thoroughly stated in the report PDF.

## Purpose of study
This study aims to help farmers or agriculture co-op to be able to differentiate the seeds without having to do in-depth studies on each individual seed or to group hem by chance. Through clustering, we can use the measurements in hopes of grouping each seed in it's relative type and use our findings in the future. In the mean time, we are evaluating how precise can clustering match the real varieties and the decisions that has to be made in the process of finding the correct cluster amount

## Findings summarized
Across the measured 210 seeds, we have found 3 different varieties of seeds in our disposal, regrouping them with 92% purity, and capturing 88% of the variance of the data using the first two principle components. 

## Methodology and Data
In this project we have used PCA and K-clustering with the help of packages that are available to viewers in the SourceCode directory as a frozen requirements text. Data is the courtesy of : Charytanowicz, M., Niewczas, J., Kulczycki, P., Kowalski, P., & Lukasik, S. (2010). Seeds [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5H30K.

## Caution
It has to be taken into consideration that the original 7 features have been reduced into only 2 using PCA, so it would be recommended to be caution when making judgement by only looking at the PCA Scatter plots (Present in both the report file and the outputs directory). The Purity score may be high but still not 100% accurate, so despite being a great help, this method can not be taken as the sole solution to the problem and there is always room for improvements and advancements. Also we must mention that **A cluster is not automatically a real biological category.**

The Notebook already has all of its outputs visible, and more information can be found in the reports file.

For more about my projects, please refer to my LinkedIn. 
Thank you very much for your time and attention and have a wonderful day
