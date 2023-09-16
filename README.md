# Suggestion-Mining-NLP

# Details
This work involves tasks for feature engineering, training and evaluating a classifier for suggestion detection. We will work with the data from SemEval-2019 Task 9 subtask A to classify whether a piece of text contains a suggestion or not. 


Download train.csv, test_seen.csv and test_unseen.csv from the [Github](https://github.com/sharduls007/Assignment_2_CT5120) or uncomment the code cell below to get the data as a comma-separated values (CSV) file. The CSV file contains a header row followed by 5,440 rows in train.csv and 1,360 rows in test_seen.csv spread across 3 columns of data. Each row of data contains a unique id, a piece of text and a label assigned by an annotator. A label of $1$ indicates that the given text contains a suggestion while a label of $0$ indicates that the text does not contain a suggestion.

You can find more details about the dataset in Sections 1, 2, 3 and 4 of [SemEval-2019 Task 9: Suggestion Mining from Online Reviews and Forums
](https://aclanthology.org/S19-2151/).

We will be using test_seen.csv for benchmarking our model, hence it has label. 
