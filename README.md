
This repository contains the code for the paper "Bankruptcy prediction using optimal ensemble models under balanced and imbalanced data" published in Expert Systems journal.

I explored the performance of gradient boosting methods in bankruptcy prediction for a highly imbalanced dataset. I developed different heterogenous ensemble models based on three popular gradient boosting methods—XGBoost, LightGBM, and CatBoost. My ensemble models were optimized using the cross-validation method and the results of the hold-out test sets showed that the optimized ensemble models not only outperform their base learners, but also improve the state-of-the-art benchmark results on the same dataset. Interestingly, we observed that the data oversampling technique that is commonly used to address the class imbalance issue had an adverse impact on my ensemble models' performance. This indicates that the proposed models are robust to the imbalanced dataset problem that typically degrades the classification performance of machine learning models.

Link to the published paper: 
https://onlinelibrary.wiley.com/doi/10.1111/exsy.13599

Link to the data repository:
https://archive.ics.uci.edu/dataset/365/polish+companies+bankruptcy+data

![image](https://github.com/user-attachments/assets/70b51ba0-bbd8-4297-83e1-e03515839950)

**Results obtained on the original data with no oversampling:**
 	Year1	Year2	Year3	Year4	Year5	 
 	 	Hold-out test set
 		Mean	Std. Dev	Mean	Std. Dev	Mean	Std. Dev	Mean	Std. Dev	Mean	Std. Dev
CatBoost	 	0.958	0.011	0.941	0.021	0.941	0.018	0.943	0.018	0.961	0.011
LightGBM	 	0.960	0.014	0.934	0.020	0.936	0.019	0.943	0.018	0.958	0.013
XGBoost	 	0.956	0.016	0.934	0.015	0.937	0.017	0.943	0.016	0.961	0.011
Ensemble 1	 	0.964	0.011	0.945	0.018	0.943	0.017	0.948	0.016	0.963	0.011
Ensemble 2	 	0.964	0.011	0.946	0.018	0.943	0.018	0.948	0.016	0.963	0.011
Ensemble 3	 	0.964	0.011	0.945	0.018	0.943	0.017	0.948	0.016	0.963	0.011
Ensemble 4	 	0.963	0.010	0.946	0.018	0.943	0.017	0.948	0.016	0.963	0.011
![image](https://github.com/user-attachments/assets/901c7f5c-f861-4971-a3e0-dc7d94e0454c)



