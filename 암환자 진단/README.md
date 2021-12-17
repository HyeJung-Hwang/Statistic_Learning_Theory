## 유방암 환자 진단 프로젝트
### Data
-Wisconsin Breast Cancer Database

### Model
-Logistic Regression model을 사용했다.
-SelectFromModel 로 feature selection 하여, Clump Thickness,Marginal Adhesion,Single Epithelial Cell Size ,Bare Nuclei로 모델을 학습하기로 결정했다.
-L2 regularization을 사용했다.

### Results
|Model|Accuracy|
|-----|-------|
|Logistic Regression|**98.99%**|


### Structure
|--- README.md

|--- Code

|     |--암환자_진단(최종).ipynb
