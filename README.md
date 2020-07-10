# The-Winner-Swimmer-Revamp
This project is a continuation of AIM MSDS2021 LT 10s The Winner Swimmer notebook using KNN by exploring other classification models.

Read more on the previous project on this [link](https://bit.ly/winner-swimmer?fbclid=IwAR1zFP51aDoO3Xe9Nj6EpFH-kxoA70rNOAPmSqxKumyQoza2sml1vWmtbZc).

## <font color='navy'>Summary of Findings for this Study</font>

> Upon performing the additional Machine Learning Methods below, the group was able to improve upon the initial accuracy of 88% to **99.94%** using the **Non-Linear Support Vector Machine Classifier with the Radial Basis Function (rbf) kernel with gamma = 20.0**. Amongst the 8 other features, sitting hours proved to be the best variable when it came to predicting alterations in male fertility, for one is subjected to an increase in the risk of having *Oligospermia* or low sperm production due to the increased temperature of the scrotum when sitting for long periods. Another highlight of the study finds that frequent alcohol intake ranks second as it temporarily reduces sperm count and testosterone levels. 

<center>
    <h4>Model Results Summary</h4>
</center>

|Machine Learning Method| Test Accuracy | Best Parameter | Top Predictor Variable
| :---: | :---: | :----: |:---:|
| kNN | 87.86% | N_Neighbor = 3| age
| Logistic (L1) | 72.81% |C=20| age
| Logistic (L2) | 72.58% | C=100 | age
| Linear SVM (L1) |72.55% | C=1000 | age
| Linear SVM(L2) | 72.55%| C=20 | age
| Non-Linear SVM (rbf) | 99.94%| gamma = 20 | sitting hours


Authors:

    Alphonso Nico Aguila
    Fiona Marie Bautista
    Daniel Rey Cimafranca
    Abel Joshua Cruzada
    Lennart Panton
    John Christopher Tambago
