# ADS Project 1:  R Notebook on Lyrics Analysis

### Doc folder

The doc directory contains the report or presentation files. It can have subfolders.  

For peer reviews, run the FullAnalysisForPeerReview.Rmd. To run this code, all you need to do is set your working directory to the folder before you store your "Data". The relative path in the R Markdown file is ../Data/lyrics.RData

Everything is done based off of this. The longest portion to run is the stemming section. On my computer it takes about 30 minutes, hopefully for you it is the same!

TextProcessing.Rmd is the file that was given to us by the intructor group. I modified it to remove all vulgar words as well, because I wanted a little more meaning for the lyrics I was analyzing.

FullAnalysis.Rmd is the structure of my final html report. I included these two files seperately in case anyone did not want to run the stemming words process. To run that file, you need the relative path to lead to ../Data/processed_Lyrics.RData. But this would basically run off of the data that you already "processed" so it would be unique to you.

If you want the version that I displayed in class, the only one you need to run is FullAnalysisForPeerReview.Rmd
