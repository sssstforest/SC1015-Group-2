# SC1015 - B124 - Group 2

## Performance Prediction from game play

### Objective
To predict player's performance through game play to access the effectiveness of using game-based learning to train one's comprehension skills

### Overview
A dataset was obtained from an ongoing Kaggle competition, which was preprocessed to reduce the size of the predictor data file and extract characteristic values to combine the predictor and response file. However, the correlation between the preprocessed predictors and the response was still relatively low. With that, taking random guessing of 0.5 accuracy as baseline and 0.7 as goal, three model formulations - Decision Tree, Random Forest, and XGBoost - were explored. The test data, which was split from our train data, showed an accuracy of 0.64 for Decision Tree, 0.66 for Random Forest, and 0.66 for XGBoost. The hidden test data on Kaggle had an accuracy of 0.64 for Random Forest and 0.676 for XGBoost. With this, it is concluded that the dataset may predict the player's performance to a certain extent with 0.676 accuracy using XGBoost.

### Individual contribution
**Huang Caihong (U2222629H)**
- Project Definition Research
- Data preprocessing
- Exploratory Data Analysis (EDA)
- PPT and video

**He Haoshen (U2123053D)**
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Models formulation
- PPT and video

**Sun Ming Zhong (U2110180J)**
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Models formulation
- PPT and video

### References
- Project source : https://www.kaggle.com/competitions/predict-student-performance-from-game-play
- Data source : https://www.kaggle.com/competitions/predict-student-performance-from-game-play/data
- Game : https://pbswisconsineducation.org/jowilder/about/

### Data File link (TA exclusive, access already granted)
- Data file exceeds 2 GB and .zip file exceeds 500 MB, can't be uploaded to github.
- https://entuedu-my.sharepoint.com/:f:/r/personal/msun004_e_ntu_edu_sg/Documents/data%20file?csf=1&web=1&e=ZVNgix
