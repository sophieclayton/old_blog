---
published: true
layout: post
title: Compute congestion
---

## Sometimes compute jobs just don't run the way you want them to...

Today I got back into the swing of running database queries on Myria.
Because the data that I am analysing was collected using three different instruments, during several different cruises, I have developed an algorithm to standardize the data for meta-analysis.
Translating the algorithm into a Myria query was pretty straightforward... Unfortunately running it wasn't!
The Myria compute cluster has been seeing heavy use over the last couple of weeks, and although this hasn't been an issue up until now, today it was swamped.
My queries just wouldn't run to completion because of the volume of work the cluster was being asked to do.
Thankfully I had plenty of other work to get done, and my query was finally run at the end of the day in less than 8 minutes.

tags: incubator, myria, seaflow
