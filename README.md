# Churn-Prediction-Ecommerce

Dataset : https://www.kaggle.com/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction

Pada studi kasus dataset tersebut adalah meningginya jumlah customer yang churn (tidak menggunakan layanan aplikasi)
Tujuan dilakukan analisa ini :
1. untuk mengurangi customer yang berindikasi churn
2. dapat mengetahui variabel apa yang berdampak pada customer churn

Dataset ini dilakukan pengolahan yang terdiri dari beberapa tahapan yaitu: Analisa Data -> Data Cleansing -> EDA -> Modelling -> Recommendation

Pada modelling ini menggunakan 5 jenis Macine Learning yaitu:
* KNN
* Decision Tree
* Random Forest
* Logistic Regression
* XGBoost

Dari 5 ML tersebut hasil terbaik pada XGBoost dengan nilai recall 0.93 -> alasan digunakan recall sebagai acuan karena ingin mengintervensi customer 
yang terindikasi akan churn agar tetap loyal dalam  menggunakan app ecommerce

![alt text](https://ibb.co/frwdBsH/)

Berdasarkan gambar shap tersebut variabel yang berdampak pada customer churn yaitu Tenure, Complain, NumberofAddres, DaySinceLastOrder dan WarehouseToHome
