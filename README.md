# Stroke-Prediction-EDA (뇌졸중 예측 프로젝트)

### ML PROJECT

#### * Title : Stroke Prediction EDA

#### * Context
###### - 뇌졸중은 뇌에 혈액을 공급하는 혈관이 막히거나(뇌경색) 터져서(뇌출혈) 사망에 이르거나 신체장애가 나타나는 질환
###### - 세계보건기구에 따르면, 뇌졸중은 전 세계적으로 2번째의 주요 사망 원인이며, 전체 사망의 약 11%를 차지

#### * Stroke Prediction
###### - 성별, 연령, 나이, 다양한 질병 및 흡연 상태와 같은 상황를 기반으로 환자가 뇌졸중에 걸릴 가능성이 있는지 예측하고자 함

#### * Contents
###### - 1) Load Data
###### - 2) Data Preprocessing
###### - 3) Exploratory Data Analysis (EDA)
###### - 4) Down-sampling
###### - 5) ML 5-Model Evaluation

#### * Attribute Info
###### - id : unique identifier
###### - gender : "Male", "Female", "Other"
###### - age : age
###### - hypertension : 0 --> doesn't have, 1--> have
###### - heart_disease : 0 --> doesn't have, 1--> have
###### - ever_married : "Yes", "No"
###### - work_type : "children", "Govt_jov", "Never_worked", "Private", "Self-employed"
###### - Residence_type : "Rural", "Urban"
###### - avg_glucose_level : average glucose level in blood
###### - bmi : body mass index
###### - smoking_status : "formely smoked", "never smoked", "smokes", "Unknown"
###### - stroke : 0 --> doesn't have, 1--> have
###### * "Unknown" in smoking_status means that the info is unavailable for this patient
###### * Source : https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

#### *Machine Learning Model
###### - 1) Linear Regression
###### - 2) Logistic Regression
###### - 3) XGBoost
###### - 4) KNN
###### - 5) Random Forest

#### * CONCLUSION
###### - 각 모델을 classification report을 통해 precision, recall, f1-score, accuracy를 평가한 결과,
######   각 모델 모두 class 0에 초점을 맞춘 결과를 보여줌 (class 0의 샘플이 class 1보다 많기 때문)
###### - 그럼에도, class 1에서 제일 높은 예측율을 보여준 모델은 Random Forest Model (precision 0.55, recall 0.4)
###### -class 1의 recall 등 값을 더 높이려면 TP(True Positive)를 높여야 할 필요성이 보임


