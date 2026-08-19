# BDAL — YouTube Data Analysis on Hadoop

Lab report: **3 MapReduce jobs + 5 Apache Pig jobs** over the SFU YouTube dataset,
run on Hadoop 3.4.1 (pseudo-distributed) + Apache Pig 0.17.0 + OpenJDK 11.

Live: https://shinzuu.github.io/bdal-youtube-analysis/

Each job shows the code, the run commands, the execution log, and the verified result.

Reference implementation (Hadoop 2): https://github.com/SiddhiPrabhu1995/YouTube-Data-Analysis-using-Hadoop
— adapted here for Hadoop 3.4.1 (input format, a reducer-state fix in MR-1, and a nested-sort
rewrite for the Pig `ORDER BY` jobs).
