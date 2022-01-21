# ML_miniproj_text_classification

I239E Machine Learning mini-project

* Description of this dataset:
This dataset is generated from GEO (a well-known semantic parsing dataset). The target of this dataset is the relation between the natural sentence and logic-term of its.

* It contains 5 columns ['label', '#1 ID', '#2 ID', 'sentence1', 'sentence2']. We only use 'sentence1', 'sentence2' and 'label' as a input features and label of each training/testing sample, separately.

* Size of this dataset: 20400 training samples, 3400 dev samples, around 9500 private test samples.



### Our Model performance 

```
               precision    recall  f1-score   support

           0       0.99      0.95      0.97      3097
           1       0.61      0.89      0.73       303

    accuracy                           0.94      3400
   macro avg       0.80      0.92      0.85      3400
weighted avg       0.96      0.94      0.95      3400

(0.6141552511415526, 0.8877887788778878, 0.7260458839406209)

```
### License
MIT

### Reference:

* [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html?fbclid=IwAR1KYu42yljTvDdAdoOtUiOZt_1YMsN3u6HgzidwrUSr67NzEgLFDO2MKJE)

* [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

* [Cross-validation](https://scikit-learn.org/stable/modules/cross_validation.html)

* [tf-idf](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)

### TODO:
1. Try LightGBM to see if it can improve the accuracy.
2. Adjusting the parameters.
