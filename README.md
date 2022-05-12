# kmodR

## K-Means with simultaneous Outlier Detection

Version: 0.2.0  
Date: 2022-04-11  
Author: David Charles Howe <kmodR@edgecondition.com>

## Description:

An implementation of the ‘k-means–’ algorithm proposed by Chawla and
Gionis, 2013 in their paper, “k-means– : A unified approach to
clustering and outlier detection. SIAM International Conference on Data
Mining (SDM13)”, and using ‘ordering’ described by Howe, 2013 in the
thesis, “Clustering and anomaly detection in tropical cyclones”.  
Useful for creating (potentially) tighter clusters than standard k-means
and simultaneously finding outliers inexpensively in multidimensional
space.

## Usage:

kmod(X, k = 3, l = 5)  
use ?kmod for more details

## Arguments

X – matrix of numeric data or an object that can be coerced to such a
matrix (such as a data frame with numeric columns only)  
k – the number of clusters to find (default = 5)  
l – the number of outliers to find (default = 0)
