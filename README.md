
This repository contains the code for the paper "Bankruptcy prediction using optimal ensemble models under balanced and imbalanced data" published in Expert Systems journal.

### **Abstract:**
I explored the performance of gradient boosting methods in bankruptcy prediction for a highly imbalanced dataset. I developed different heterogenous ensemble models based on three popular gradient boosting methods—XGBoost, LightGBM, and CatBoost. My ensemble models were optimized using the cross-validation method and the results of the hold-out test sets showed that the optimized ensemble models not only outperform their base learners, but also improve the state-of-the-art benchmark results on the same dataset. Interestingly, we observed that the data oversampling technique that is commonly used to address the class imbalance issue had an adverse impact on my ensemble models' performance. This indicates that the proposed models are robust to the imbalanced dataset problem that typically degrades the classification performance of machine learning models.

**Link to the published paper:**
https://onlinelibrary.wiley.com/doi/10.1111/exsy.13599

**Link to the data repository:**
https://archive.ics.uci.edu/dataset/365/polish+companies+bankruptcy+data

### **The overal diagram of the ensemble model:**


![exsy13599-fig-0001-m (1)](https://github.com/user-attachments/assets/39ad2f5d-6af6-425f-b615-0d9cb496e319)



<img width="367" alt="Screenshot 2024-07-23 at 10 14 03 PM" src="https://github.com/user-attachments/assets/1b569cd3-e3b8-4a0c-a507-9c24b2c0241d">


### **AUC values obtained on the original data with no oversampling:**

<img width="479" alt="Screenshot 2024-07-23 at 10 11 03 PM" src="https://github.com/user-attachments/assets/43ab0efb-fb32-4bea-9c11-4495303a3491">




