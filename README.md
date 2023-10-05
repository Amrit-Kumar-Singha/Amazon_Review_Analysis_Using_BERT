# Amazon_Review_Analysis_Using_BERT

## Data-Set Link: https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews
A BERT model that is developed to determine and distinguish between 2 different types of reviews Positive and Negative
* Positive Review is valued as ==>1
* Negative Review is valued as ==>0
## Pre-Processing Techniques Used:
* Removal of Stop-Words
* Lemmatization
* BERT Pre-Processing
* BERT Encoding
## Model Accuracy: 74%
## Confusion Matrix
    array([[ 838,  412],
           [ 245, 1005]], dtype=int64)
## Summary of Classification Report of the Model
                  precision    recall  f1-score   support

    Negative           0.77      0.67      0.72      1250
    Positive           0.71      0.80      0.75      1250

    accuracy                               0.74      2500
    macro avg          0.74      0.74      0.74      2500
    weighted avg       0.74      0.74      0.74      2500
