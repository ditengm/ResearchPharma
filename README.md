# ResearchPharma
Researching pharmaceutical market
## EDA and Preproccesing
1. Classes have been balanced
2. Defined categorical columns
3. Looked at the correlation
4. Removed outliers
5. Worked with gaps by removing and inserting median values
6. Apply OneHotEncoding and MeanTargetEncoding for categorial columns
7. Normalization data
## Results
Metric: **ROC-AUC** because classes have been balanced
- CatBoost: ROC-AUC = 0.683
- LogisticRegression: ROC-AUC = 0.607
- SVC: ROC-AUC = 0.606
- RandomForestClassifier: ROC-AUC = 0.663