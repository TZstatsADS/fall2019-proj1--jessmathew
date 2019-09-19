# ADS Project 1:  R Notebook on Lyrics Analysis

### Doc folder

The doc directory contains the report or presentation files. It can have subfolders.  

For peer reviews, run the FullAnalysisForPeerReview.Rmd. To run this code, all you need to do is set your working directory to the folder before you store your "Data". The relative path in the R Markdown file is ../Data/lyrics.RData

VERY IMPORTANT: You need to go to the "figs" folder and download "CiaraFuture.jpg" and "FutureZahirWilburn.jpg". Save them into the same data folder that has "lyrics.RData". These images are used to generate the final HTML output.

ALSO IMPORTANT: There's a portion that has the data for a couple of other male and female artists. What I do is overwrite the data with just data for Future and Ciara. I left the other information there in case any of the peer reviewers wanted to play around with the data and use some of their favorite artists.

The longest portion to run is the stemming section. On my computer it takes about 30 minutes, hopefully for you it is the same!

TextProcessing.Rmd is the file that was given to us by the intructor group. I modified it to remove all vulgar words as well, because I wanted a little more meaning for the lyrics I was analyzing.

FullAnalysis.Rmd is the structure of my final html report. I included these two files seperately in case anyone did not want to run the stemming words process. To run that file, you need the relative path to lead to ../Data/processed_Lyrics.RData. But this would basically run off of the data that you already "processed" so it would be unique to you.

If you want the version that I displayed in class, the only one you need to run is FullAnalysisForPeerReview.Rmd
