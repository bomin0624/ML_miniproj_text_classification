# ML_miniproj_text_classification

I239E Machine Learning mini-project

* Description of this dataset:
This dataset is generated from GEO (a well-known semantic parsing dataset). The target of this dataset is the relation between the natural sentence and logic-term of its.

* It contains 5 columns ['label', '#1 ID', '#2 ID', 'sentence1', 'sentence2']. We only use 'sentence1', 'sentence2' and 'label' as a input features and label of each training/testing sample, separately.

* Size of this dataset: 20400 training samples, 3400 dev samples, around 9500 private test samples.



### Our Model performance 

```
               precision    recall  f1-score   support

           0       0.99      0.94      0.96      3097
           1       0.60      0.86      0.71       303

    accuracy                           0.94      3400
   macro avg       0.79      0.90      0.84      3400
weighted avg       0.95      0.94      0.94      3400

(0.5995423340961098, 0.8646864686468647, 0.708108108108108)

```
### Reference:

* [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html?fbclid=IwAR1KYu42yljTvDdAdoOtUiOZt_1YMsN3u6HgzidwrUSr67NzEgLFDO2MKJE)

* [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

* [Cross-validation](https://scikit-learn.org/stable/modules/cross_validation.html)

* [tf-idf](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)
