# airline-research

Repo for airline research project.

**CorrelationFile.csv**  
Correlates data between twitter and skytrax  
3 cols:  
Col1 – Skytrax airline name  
Col2- Twitter airline name  
Col 3 Correlation.   
american-airlines,American,-0.06794676027524565  
delta-air-lines,Delta,-0.031660612759636844  
southwest-airlines,Southwest,-4.796304395174328E-4  
united-airlines,United,-0.06850757261687115  
us-airways,US Airways,0.07418872703711722  
virgin-america,Virgin America,0.07688906028818855  
*********************************************************************
*********************************************************************
**CorrelationFile.csv.data.txt**  
Data which went into the calc for col 3 in file CorrelationFile.csv  
Col1 airline (either Skytrax airline name OR Twitter airline name)  
Col 2-N rating…  

*********************************************************************
*********************************************************************
**CorrelationText2Rating.csv**  
File correlates predicted rating (derived semantically) to the actual user rating  
Col1 – Skytrax airline name  
Col2 – Correlation  
american-airlines,0.34439832931130393  
delta-air-lines,0.3286290690951144  
southwest-airlines,0.4322473701396349  
*********************************************************************
*********************************************************************
**CorrelationText2Rating.csvdata.csv**  
Col1 – Skytrax airline name + type (Rating = user rating) (text= derived from the text)  
Col2-n Rating data used in calc  
*********************************************************************
********************************************************************* 
**reason.csv**  
Provides the stopword free text by airline and reason code.  
Col 1 - Col1 – Skytrax airline name    
Col 2 – reason code (one per row)  
Col 3 – user comments with stop words removed.  
*********************************************************************
*********************************************************************
**AllRows.CSV**  
Unedited rows that passed several criteria to be used   
Rules   
1.	enough columns  
2.	scope airline  
3.	enough volume.  
Use this file for sample reviews.  


*********************************************************************
*********************************************************************
**sample_reviews_skytrax.csv**  
col 1. airline name  
col 2. Category  
col 3. Review  

*********************************************************************
*********************************************************************
**sample_reviews_tweets.csv**  
col 1. airline name   
col 2. Category  
col 3. Review  



