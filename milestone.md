# Spooky Author Identification
## Overview
The project milestone is an opportunity for you to practice your data story skills. You will reach the milestone when you have produced an early draft of the final Capstone Project 2 report.

## Problem
In celebration of the season, train a model to learn text from three popular authors and classify the author who wrote the unknown text.  This is a multi-class NLP classification problem, as three possibilities exist (EAP = Edgar Allen Poe, MWS = Mary W. Shelley, HPL = HP Lovecraft).  However, this will leverage different algorithms and parameter optimizations to provide a better guess to the author who wrote it.

## Client
The business problem to address is identifying an author based on what they wrote.  This may be useful for linguists who want to classify or differentiate between the authors, or to create a new set of prose from a particular author.  However, this may extend further to those who want to classify and differentiate text from writer.  For instance, while emails may have the sender's information, for business literature, it may help to classify or find similar authors and research findings.  This is common with recommendation systems.  

## Data
### Start
The initial file is train.csv.  This is the data that will create the machine learning model.  The file originated as part of three .csv files (the other two are test.csv and submission.csv) from Kaggle.com for their competition to identify the author who wrote the text.  The dataset contains 19579 observations and 3 features.  They are ID (primary key), author (categorical by abbreviation), and text (text).  Here, the target variable is the author and the the data is the text.  Other data is the train.csv, containing 8,392 observations and two features (ID and text).  The train.csv is what we test our model with, to identify the author.  

### Cleanse
Cleaning the data (in this case, text) requires two micro-steps and one major step.  The two micro-steps are (a) stop words and (b) punctuations.  They will interfere with comparing words and will take up a lot of features.  The macro-step is to transform the data from text into binary code (similar to a one-hot encoder technique) to process on the texts.  

## Findings

## Resources

## Discussion

## Reference
* “Spooky Author Identification: Share code and discuss insights to identify horror authors from their writings.”  Kaggle.com.  Published 10/25/2017.  Retrieved 12/07/2017. URL: https://www.kaggle.com/c/spooky-author-identification.  
* R. Tatman.  “Beginner’s Tutorial: Python”.  Kaggle.com.  Published 10/25/2017.  Retrieved 12/07/2017.  URL: https://www.kaggle.com/rtatman/beginner-s-tutorial-python. 
* S. Dane.  “Intermediate Tutorial: Python”.  Kaggle.com.  Published 10/25/2017.  Retrieved 12/07/2017.  URL: https://www.kaggle.com/sohier/intermediate-tutorial-python/. 
* K. Markham. “Machine Learning with Text in sci-kit learn”.  PyCon Portland, 05/28/2016.  Published 06/08/2016.  Retrieved 12/08/2017.  URL: http://bit.ly/2yPaYB4.  
* (optional) S. Bird, E. Klein, and E. Loper.  Natural Language Processing with Python: Analyzing Text with the Natural Language Toolkit.  Published URL: http://www.nltk.org/book/.
