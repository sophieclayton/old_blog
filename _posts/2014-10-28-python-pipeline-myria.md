---
published: false
layout: post
title: 
---

## Building on a python pipeline for Myria, and revisiting my PhD research

Dan and I spent the morning working on implementing a way to submit queries in MyriaL and Datalog directly to Myria using python. This turned out to be much easier than I had expected. I'm glad that we did this because it means that I can start issuing queries to Myria and retrieving the results without having to switch between the website and python/R/Matlab. Over the next week I plan to build on this to come up with a complete python-Myria pipeline to submit queries, check ontheir progress and then download the results. It's going to be awesome.

This afternoon I finally plugged in the two 4TB hard drives that contain a big chunk of the model output that I analysed as part of my PhD research. It's a 1/6 degree global ocean circulation model with a coupled ecological model developed by [Mick Follows](http://ocean.mit.edu/~mick/), my PhD advisor at MIT. We're collaborating with researchers in France to extend the ecological anlaysis of the model output. Even after 7 years (the original run was done in late 2007 and took 3 months), it's still a very unique model run. This movie shows how the dominant phytoplankton types change over the seasonal cycle:

<iframe width="420" height="315" src="//www.youtube.com/embed/wAsNzQ2RDqM" frameborder="0" allowfullscreen></iframe>

tags: incubator, python, myria, MITgcm, Darwin model
