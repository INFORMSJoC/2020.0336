# Data for replication

This folder contains the data from QAPLIB
https://coral.ise.lehigh.edu/data-sets/qaplib/

There are three dats sets which are organized as follows:
small_instances:  small size instances 10<=n<=20
medium_instances: medium size instances 21<=n<=40
large_instances:  large size instances 41<=n<=256

Optimal_values.m is a script that contains best known upper bounds and instance naems from the QAPLIB instances.
Optimal_values.m is loaded in  qrun_tests.m to compute the relataive gap between the best known upper bounds and solver lower bounds (called optgap).

datafilename.mat is generated as a temporary file when the datatype is 1 or 2, see in main.m.
==============================================================================
Sep 20, 2021

