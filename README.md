# Introduction to parallel computing with R
Hana &#352;ev&#269;&#237;kov&#225;
University of Washington


**Keywords**: Parallel Computing, Master-Slave Paradigm, Reproducibility, Load Balancing, Distributed Random Number Generators

# Goal

The goal of this tutorial is to introduce attendees to concepts and tools available in R for parallel computing. It is aimed at novice R programmers to lower an often percieved mental hurdle when dealing with code paralelization. 


# Description

Over the past few years, R has become increasingly popular outside of the statistical community. It became one of the most popular programming languages among data scientists. With an increasing amount of data and more complex algorithms available to scientists today, parallel processing is almost always a must, and in fact is expected in packages implementing time-consuming methods. 

Numerous R packages for parallel computing have been developed over the past two decades, with **snow** being one of the pioneers in providing a high level interface for parallel computations on a cluster or in a multicore environment. More recently, most of the **snow** functionality has been implemented in the R core package **parallel**. 

The main focus of the tutorial will be on the viewpoint implemented in the **parallel** package, namely the master-slave paradigm. Note that other viewpoints, such as Single Program/Multiple Data (SPMD), grid computing, map/reduce will be briefly introduced only as concepts, without going into detail.

In a parallel statistical application a few issues need more attention than in its sequential counterpart. These include reproducibility, random number generation, computation transparency or load balancing. We will talk about solutions to these and other issues implemented in  user-contributed packages.

# Outline

* Paradigms of parallel computing
* The master-slave paradigm in R
* Examples of using **parallel**
* Random numbers generation
* Reproducibility and load balancing
* Review of useful **snow**-like R packages with examples

# Pre-requisites

The tutorial is targeting people relatively new to R, so only basic knowledge of R is required.

# Instructor

[Hana &#352;ev&#269;&#237;kov&#225;](http://www.stat.washington.edu/hana) is a Senior Research Scientist at the Center for Statistics and the Social Sciences at the University of Washington. She has collaborated on implementation of R packages for parallel computing and distributed random number generators, such as **snowFT**, **rlecuyer** and **snow**. More recently, she has been involved in developing demographic R packages as part of a collaborative research project with the United Nations.



