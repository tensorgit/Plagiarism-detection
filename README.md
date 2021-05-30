# Plagiarism-detection
## Plagiarism detection with non-linear SVC (sklearn)


**Description:**
- A machine learning model trained to detect plagiarism w.r.t the given data set. This data is a slightly modified version of a dataset created by Paul Clough (Information Studies) and Mark Stevenson (Computer Science), at the University of Sheffield. You can read all about the data collection and corpus, at [their university webpage](https://ir.shef.ac.uk/cloughie/resources/plagiarism_corpus.html). 

> **Citation for data**: Clough, P. and Stevenson, M. Developing A Corpus of Plagiarised Short Answers, Language Resources and Evaluation: Special Issue on Plagiarism and Authorship Analysis, In Press. [Download]
- A Support Vector Classifier with a non-linear 'rbf' kernel is used for the training and prediction
- For feature comparision, we extract the 'Containment' with different n-grams (word-groups) and also evaluate the 'Least Common Subsequence' (the longest common phrase) for each unit text group of the dataset

## Further Directions
(suggested)
There are many ways to improve or add on to this project to expand your learning or make this more of a unique project for you. A few ideas are listed below:
* Train a classifier to predict the *category* (1-3) of plagiarism and not just plagiarized (1) or not (0).
* Utilize a different and larger dataset to see if this model can be extended to other types of plagiarism.
* Use language or character-level analysis to find different (and more) similarity features.
* Write a complete pipeline function that accepts a source text and submitted text file, and classifies the submitted text as plagiarized or not.
* Use API Gateway and a lambda function to deploy your model to a web application.
