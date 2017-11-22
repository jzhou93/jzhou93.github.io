---
title:  "Python Programming"
date:   2017-11-22 17:10:00
description: What I have learnt after completing a project with Python
---
What I have learnt after completing a project with Python

Disclaimer: By no means am I a professional programmer, I am largely self taught and try to find the best way to solve a particular problem as it comes up.

I used python for a data integration project. The requirements were to set up an automated ETL process that extracted data files from an FTP server, transform it based on various business rules and to the necessary formats to be consumed by a personalisation and campaign tool. An intermediate database was also used.

My setup
This was my first introduction to git, which I used for version control across files on my local machine, bitbucket and production files on an AWS server. Jupyter notebook was used for scripting and testing on my local machine. I also experimented with docker to test the end to end process on my local machine, by creating mysql containers for testing. Production code was then deployed to the AWS instance, and cron jobs were set up to automatically trigger the jobs when required.

The libraries
Some of the notables libraries used were pandas for manipulating data and perfoming the required transformations, paramiko for connecting to and accessing files on FTP server and mysqldb for connecting to a mysql database.

Lessons learnt
The difference between memory, CPU and storage and how to measure the performance of each on a linux box
Putting the theories of modularity and functions into use
Batch processing to reduce the memory and CPU consumption of a process
The importance of testing and how modifications to once part of your code always seems to have an impact on something else
