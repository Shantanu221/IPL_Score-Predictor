# IPL_Score Predictor
This Streamlit webapp enables user to predict total runs between teams using current runs and wickets.

**Algorithms used**:
- Linear Regression
- K-Nearest Neighbor Regressor
- XGBoost Regressor
- RandomForest Regressor
- SVR
- Decision Tree Regressor

**Dataset used**: ipl_data.csv

- mid - match i
- date - when matches are played
- venue - place where matches aew played
- bat_team - batting team
- bowl_team - bowling team
- batsman - batsman
- bowler - bowler
- runs - runs scored
- wickets - wickets
- overs - overs - next 3 are based on this
- run_last_5 - runs scored in last 5 overs
- wicket_last_5 - wickets in last 5 overs
- stricker - batsman playing as main 1
- non-striker - batsman playing as runner up - not main 0
- total - total score (target variable)

**Web app**:

![](https://github.com/Shantanu221/IPL_Score-Predictor/blob/main/streamlit-ipl_score_predict.gif)
