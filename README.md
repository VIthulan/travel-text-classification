# Text classification

Text classififaction for question-answering on Travel domain is analysed here for 5000 questions. Here I have evaluated 5 methods. <br/>
1. Five Text features
2. FastText word embedding
3. LSTM
4. BERT

## Summary
|  Model |  Average accuracy (of 10 Folds) |
|---|---|
|SVM Classifier with 5 Text features   |77.34%|
|SVM Classifier with only Lemmatized BoW   |  82% |
|SVM with FastText word embedding   | 82.6%  |
|LSTM   | 81%  |
|BERT   | 84.46%   |
