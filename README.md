# EMR to External Data Probabilistic Matching
Program to perform probabilistic matching between EMR and external data. 

*--Developer:  Peter Leese

*--Institution:  UNC-Health Care System

*--Developed:  May 2015

*--EMR to External Death Data Probabilistic match program 

Purpose:  This program standardizes emr patient
 identifiersand external death information, then peforms
 a probabilistic match and computes a weighted-match
 score. Examples of external death data sources would
 be death data available from Social Security, the NDI
 from CDC for research purposes, or the state-level files 
used to assemble the NDI.  

Notes:  This program is presented to illustrate the
logic and method to employ probabilistic matching as a
form of data integration to supplement native emr 
documentation.  This program is not intended to function
as-is or as a macro to be implemented unmodified within
a different environment.  This is a simple probabilistic 
matching program developed in a short period of time - 
after dedicated testing, we felt this program represented  
the optimal balance of match performance relative to 
development time that allowed flexible implementation 
in both statistical programming and data integration/SQL
environments.  

The focus of this program is on extracting and standardizing 
input data for the match and then performing the probabilistic match. 
Once the match is performed and high-confidence match cut-offs are 
assessed from the weighted match score, keys can be generated between
patient data and external datafacilitate matching of additional 
data not included in the match extracts created for the match.

Recommended references on probabilistic matching methods:

https://www.lexjansen.com/wuss/2010/databases/2997_2_DDI-Wright.PDF
https://www.lexjansen.com/nesug/nesug07/ap/ap23.pdf
https://www.lexjansen.com/wuss/2011/data/Papers_Wright_G_76128.pdf
http://support.sas.com/resources/papers/proceedings14/1674-2014.pdf
https://support.sas.com/resources/papers/proceedings/proceedings/sugi24/Advtutor/p46-24.pdf
https://www.ncbi.nlm.nih.gov/books/NBK253312/
http://support.sas.com/resources/papers/proceedings14/1316-2014.pdf

