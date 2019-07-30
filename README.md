# backboning

This repository is a Python 3 package to sparsify networks. This was 
originally written by [Michele Coscia](http://www.michelecoscia.com/?page_id=287) 
and [adapted further](https://github.com/carolinamattsson/follow_the_money/blob/a2b1df7912766ad88feba2e406d45232b4d2da45/network/backboning.py). 
This repository has been created to track how the module has changed with 
the above updates and any further changes to be made.

## Michele Coscia's original synopsis

The archive contains a Python module to perform network backboning, which 
is the filtering of non-significant edges from a very dense and noisy network.

The module provides several utilities and the following methods:

* Noise Corrected: New methodology published at ICDE 2017 developed by Frank 
  Neffke and me (please cite: Coscia & Neffke "Network Backboning with Noisy 
  Data", ICDE 2017 — Paper, Bibtex);
* Disparity Filter: http://www.pnas.org/content/106/16/6483.full;
* High Salience Skeleton: http://www.nature.com/articles/ncomms1847;
* Doubly Stochastic Transformation: http://www.pnas.org/content/106/26/E66.full.pdf;
* Maximum Spanning Tree: https://en.wikipedia.org/wiki/Minimum_spanning_tree;
* Naive Thresholding.

The module requires the following Python packages:
                            
* Pandas
* Numpy
* Networkx
                                    
