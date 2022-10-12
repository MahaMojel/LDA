# LDA
This project aims to apply one of the NLP algorithm (LDA) on SO site for all posts related to data science .


This folder contains 3 pyhton file (To speed up the work and seprate the run)

First Dataset taken from here with CSV format and it has been converted into XML for our statitics to work. 
https://ia800107.us.archive.org/view_archive.php?archive=/27/items/stackexchange/datascience.stackexchange.com.7z 


1. topics-modeling-lda.ipynb: This is the main code as we preprocess, build the LDA and find coherence value through this file. 
2. SO_Pop_and_Diff.ipynb: In this file we optain the LDA again in order to find the statisics as we could not make it in first file  because the first dataframe only contains limited metrics e.g no answer count, favourite..etc but here same dataset and posts but having more metrics.
3. statistics.ipynb: in this file we found all staticis for our metrics including popularity, difficulty and correlation betweenn them.
