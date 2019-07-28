# Matrix-Completion-for-Different-Missing-Data-Patterns
Project for 'DS-GA 1013 Mathematics Tools for Data Science'

## Overview
Matrix completion and imputation is a common problem and an important cornerstone in data science applications. We compare the perfor- mance of three matrix imputation methods (Soft- Impute, SoftImpute-concat, Multiple Imputation) on different types of missing data patterns using both synthetic and real datasets. Although no method is found to perform significantly better under all circumstances, SoftImpute-concat indeed outperforms original SoftImpute when missing is not at random (NMAR) on our data. Besides, SoftImpute-concat has more robust performance than SoftImpute when missing rate increases. However, no theoretical proof of SoftImpute-concat superior performance under NMAR setting is given so far. Therefore, we discuss possible reasons based on a toy example.

## Data
1. Simulated Data
2. The MovieLens small dataset includes 100,000 ratings (ranging from 0.5 to 5) of 9000 movies by 600 users
3. EMBARC study, an 8-week randomized placebo-controlled clinical trial of sertraline enrolled about 300 patients with Major Depressive Disorder

## Algorithms
1. SoftImpute
2. SoftImpute-Concat
3. Multiple Imputation
