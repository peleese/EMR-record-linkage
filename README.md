# Probabilistic-matching
Program to perform probabilistic matching between EMR and external data. 

*--Developer:  Peter Leese
*--Institution:  UNC-Health Care System
*--Developed:  May 2015

*--EMR to External Death Data Probabilistic match program 

*--Purpose:  This program standardizes emr patient
 identifiersand external death information, then peforms
 a probabilistic match and computes a weighted-match
 score. Examples of external death data sources would
 be death data available from Social Security, the NDI
 from CDC for research purposes, or the state-level files 
used to assemble the NDI.  

*--Notes:  This program is presented to illustrate the
logic and method to employ probabilistic matching as a
form of data integration to supplement native emr 
documentation.  This program is not intended to function
as-is or as a macro to be implemented unmodified within
a different environment.  This is a simple probabilistic 
matching program developed in a short period of time - 
after dedicatedtesting, we felt this program represented  
the optimal balance of match performance relative to 
development time that still allowed flexible implementation 
both in statistical programming and data integration/SQL
environments.  
