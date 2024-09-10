SR-PCM-HDP <br>
======
A novel clustering algorithm named Self-Regulating Possibilistic C-Means with High-Density Points (SR-PCM-HDP), which streamlines cluster number determination and enhances clustering efficiency.

Files <br>
=====
* datasets.zip: the synthetic datasets used in our paper. The real datasets can obtained from UCI. <br>
* source code.zip: the implementation of the SR-PCM-HDP algorithm by matlab, which includes 3 functions and one matlab script. 

Functions
====
* DBKE: extract high-density points. <br>
* SRPCMHDP: iteratively remove rebundant clusters and get final clustering results.
* FCM: classical Fuzzy C-Means algorithm.

Usage
====
Run the matlab script test_SRPCMHDP.m to obtain the final number of clusters and clustering labels for a specific dataset.
