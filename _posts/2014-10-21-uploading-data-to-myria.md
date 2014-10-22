---
published: true
---

## Uploading data to the Myria database: success and pitfalls

I finished uploading the last of the temperature and salinity data to the Myria database at the end of last week, and spent today starting to explore it. Uploading the data using the myria-python package was a big success (despite some odd SSL errors). 

Now for the pitfall... Some of the data was uploaded in the wrong format (LONG_TYPE rather than as a STRING). Unfortunately, until I fix this, I can't combine the flow cytometry data with the temperature and salinity data. The major issue is that the file IDs for the flow cytometry data are saved as strings, whereas the file IDs for the temperature and salinity data are saved as longs. Dan wasn't around, and it was beyond my SQL/Myria skills to fix this (apparently you can't CAST longs to strings or vice versa). Hopefully get this fixed tomorrow.

While the long/string debacle was a bit of a pain, I did start putting some python code into ipython notebooks for visualising the data once I manage to extract it. Next job on this front will be to try to develop a python pipeline to submit queries to Myria, extract the results and produce figures without fiddling around with .csv files and Matlab.

tag: incubator, myria, python