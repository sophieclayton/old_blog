---
published: true
layout: post
title: Myria, IPython and finally a plot
---

## Playing with IPython, making figures, happy days!

It's always a great day when you make a nice figure from your data! With Dan's help I fixed the data type error I was running into on Tuesday, so I could start exploring the links between the seaflow data and the environmental conditions. I'm also taking this opportunity to force myself to use python, and particularly IPython notebooks to track my data analysis and code for making figures. 

You can take a look at my first ipython notebook [right here](http://nbviewer.ipython.org/github/uwescience/seaflow-myria/blob/master/ipython_notebooks/myria_TS_plots.ipynb). I use pandas to import the result of my Myria query directly into python, and then matplotlib to produce a figure that shows the mean forward scatter values for beads in T/S space. We use beads in seaflow to act as an internal standard. The position of the beads changes when the sensitivity of the instrument is changed to "see" larger or smaller populations. You can see in this figure how the instrument has been configured differently for different cruises.

![bead_TS_plot](https://raw.githubusercontent.com/sophieclayton/sophieclayton.github.io/master/images/bead_mean_fsc_TS.png)

tags: seaflow, incubator, python
