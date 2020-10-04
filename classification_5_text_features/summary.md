Lemmotized bag of words, POS tags, Headwords, Headword synoynms, Named entity provided the f1 score of 77.8% but I was able to get the maximum F1 score of 82% using Lemmotized bag of words as the only feature. Following are the metrics from that model:
```
                precision    recall  f1-score   support

           1       0.86      0.82      0.84        76
           2       0.76      0.70      0.73        23
           3       0.93      0.83      0.88        60
           4       0.85      0.72      0.78       112
           6       0.83      0.93      0.87        98
           7       0.71      0.82      0.76       114
           9       1.00      0.94      0.97        17

    accuracy                           0.82       500
   macro avg       0.85      0.82      0.83       500
weighted avg       0.83      0.82      0.82       500
```

*   Accuracy score: 82.0
*   F1 Score: 82.0

Confustion matrix
```
[[62  0  1  2  1 10  0]
 [ 0 16  0  0  3  4  0]
 [ 3  0 50  4  1  2  0]
 [ 2  1  3 81  7 18  0]
 [ 1  0  0  2 91  4  0]
 [ 4  4  0  6  6 94  0]
 [ 0  0  0  0  1  0 16]]
 ```

