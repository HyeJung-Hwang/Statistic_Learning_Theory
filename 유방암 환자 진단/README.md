## 유방암 환자 진단 프로젝트
### Data
-Wisconsin Breast Cancer Database

### Model
-SelectFromModel 로 feature selection 하여, Clump Thickness,Marginal Adhesion,Single Epithelial Cell Size ,Bare Nuclei로 모델을 학습하기로 결정했다.

-아래의 사진처럼, 정규화 정도나 feature를 다양하게 조절해가며 정확도를 비교해본 결과, L2 regularization(lamda=0.01)로 학습했을 때 가장 높은 정확도가 나왔습니다.

![표1](https://user-images.githubusercontent.com/79091824/146669116-bc185462-3c6c-490f-be94-0b4a7475e512.PNG)

![표2](https://user-images.githubusercontent.com/79091824/146669220-e6e0a76d-bcb1-42d9-afce-dd79632de62e.PNG)

### Results
|Model|Best Accuracy|
|-----|-------------|
|Logistic Regression|**98.99%**|


### Structure
|--- README.md

|--- Code

|--------암환자_진단(최종).ipynb
