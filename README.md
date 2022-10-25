# Credit-Card-Default-Classification

# Tujuan Project
Pembuatan model Classification untuk memprediksi default_payment_next_month menggunakan dataset credit_card_default

# Background Project
Credit card merupakan salah metode pembayaran cicilan yang dilakukan seseorang ketika berbelanja atau membeli suatu barang yang diinginkan. setiap kartu kredit atau credit card memiliki limit tertentu. limit tersebut ditentukan oleh perusahan credit card atau bank berdasarkan faktor tertentu. menurut salah satu bank (sumber: https://www.ocbcnisp.com/id/article/2021/10/11/limit-kartu-kredit), limit credit ditentukkan berdasarkan saldo rekening, riwat keuangan, pendapatan atau gaji, status kepemilikkan rumah, jumlah hutang, dan jumlah pengajuan. setelah semua faktor tersebut, maka seseorang akan mendapatkan limit credit card. akan tetapi limit kartu kredit tersebut akan bertambah apabila seseorang membayar tepat waktu setiap cicilannya per bulan.

selain itu, ada kemungkinan customer dari kartu kredit lupa atau sengaja tidak membayar cicilan kartu kreditnya per bulan. hal ini dikarenakan keadaan ekonomi dari customer itu sendiri yang sedang tidak baik - baik aja. sehingga membuat customer melakukan keterlambatan pembayaran atau yang sering dikenal dengan tunggakan kartu kredit. apakah kartu kredit dari customer tersebut langsung default atau tidak?.

# Library
library yang digunakan dalam project ini, yaitu:
1. pandas versi 1.4.2
2. numpy versi 1.21.5
3. scikit learn versi 1.1.2
4. feature engine packages versi 1.4.1

# Feature Engineering
Pada project dilakukan beberapa feature engineering seperti:
1. Feature selection mengunakan phik matriks
2. Handling outlier mengunakan metode capping
3. Feature scalling mengunakan metode minmax scaller
4. Feature encoding mengunakan metode one hot encoder

# Model
Model yang digunakan dalam project ini, sebagai berikut:
1. Logistic Regression
2. SVM Model
3. Decision Tree
4. Random Forest
5. K-Nearest Neighbor (KNN)
6. Naive Bayes
7. Adaboost Clasifier

# Kesimpulan
Model yang memiliki performa paling bagus dalam memprediksi kartu kredit customer default atau tidak adalah model Logistic Regression 
dengan nilai akurasi sekitar 81%
