# Files Taken from X regarding the Israel-Hamas War
A collection of files taken from post from X about the Israel-Hamas war of 2023-2024.
These files are analyzed in the paper, "Assessing Bias During the Hamas-Israel War" from 2024 by Rosenfeld et al.

The folder "unprocessed_files" contains the scraped files without processing taken from a keyword search of "Palestine, Israel" from October-November 2023.
It also contains six hashtags-- three known to be Pro-Israel and three Pro-Palestinian, taken from November 2023.
The file all news tweets contains news tweets scraped from many news organizations X (Twitter) feed from October-November 2023.

The folder paper_files contained the processed files used in the analysis. These files were processed to remove duplicates, non-English tweets, tweets without text (but had pictures) and balanced the datasets based on the most popular tweets.
This left 4000 tweets in the keyword dataset, 900 tweets in the hastag dataset, and 2361 relevant tweets in the news dataset (tweets containing keywords pertaining to the conflic).
Details of these datasets, and the cleaning methods used, can be found in the paper.  The processed files for Weka are found in the Weka_files folder.

The Orange folder contains all processed files used for creating the Word Clouds in Orange.
