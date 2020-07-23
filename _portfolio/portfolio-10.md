---
title: "TLD long-term tracking algorithm"
excerpt: " <img src='/images/tld.png' style='width:1000px;'> | *Long-term tracking of previously unknown objects in unconstrained Environments.* <br> <br>
**Languages/Frameworks used: C++, OpenCV.** "
date: "June 2012"
collection: portfolio
priority: "10"
---

<img src='/images/tld.png'>

The  main  approach  taken  in  the  TLD  algorithm  is  the  concept  of  online  training.  Since the object is unknown until runtime, training can not be decoupled from detection. The algorithm utilizes a short-term tracker working in tandem with a sliding-window detector to train a random forest classifier on-the-fly, and grow and improve the decision forest with time. 

<img src='/images/tld2.png'>


The project was an implementation of the original work by [Zdenek Kalal](http://kahlan.eps.surrey.ac.uk/featurespace/tld/).