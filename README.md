# IR2022_A2_57


## Q2: 

### Methodology:

1. took only qid:4 files as asked in question. Converted to dataframe for easier manipulation.
2. Maximum DCG is obtained when documents are retrieved in descending order of rankings. So we sorted the documents in decreasing order that gave us a ranking. Number of such rankings are calculated in notebook.
3. NDCG is calculated as (DCG of documents)/(max DCG that can be obtained). We created a function for this.
4. Preicison-Recall curve in notebook.


## Q3:

### Methodlogy:

1. Preprocessed the dataset by removing everything except alphabets and numbers.
2. Text is converted to lower case.
3. Tokens of length <= are removed.
4. Tokens are lemmatized to bring them to root word.
5. Randomly split data.
6. Top k features for each class are calculated using TFICF and then merged to form a new vocabulary.
7. Vectorization is  done using TFIDF.
8. Gaussian Naive Bayes is implemented for each class.
9. Results like accuracy and confusion matrix are shown in the notebook.
10. Inferences about the results are also shown in the document.