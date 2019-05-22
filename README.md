# Understanding Heart Disease

Data originally from kaggle dataset: https://www.kaggle.com/ronitf/heart-disease-uci

Please note the kaggle dataset is incorrect (inverted heart disease tags, and some errors in encoding). I have taken the raw data from the original paper [Detrano et al. 1989](https://www.ajconline.org/article/0002-9149(89)90524-9/pdf)

We have data which classifies patients as either having heart disease or not along with several demographics and cardiac disease risk factors. We will try to use this data to create a model which can be used to predict if a patient has this disease or not. We will mainly use the logistic regression (classification) algorithm, and briefly compare other methods.