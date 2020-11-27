# [機器學習的實作教學](https://github.com/y-s-liu/machine-learning-tutorial)

[![hackmd-github-sync-badge](https://hackmd.io/izWotahaQiOyDbrZhpdwdg/badge)](https://hackmd.io/izWotahaQiOyDbrZhpdwdg)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/y-s-liu/machine-learning-tutorial/blob/master/)


配合課程說明，以 Jupyter notebook 的方式整理出來的實作。

## 一、監督式學習

### 1.1. [迴歸問題](https://github.com/y-s-liu/machine-learning-tutorial/blob/master/class1.1_regression.ipynb)
分析錢可以為人們帶來快樂，從OECD網站[https://homl.info/4](https://homl.info/4) 下載各國生活滿意度指標(better life index)，並且從IMF網站[https://homl.info/5](https://homl.info/5) 下載各國人均生產總額(gross domestic product, GDP)，從生活滿意度指標與GDP兩個資料來分析，是否GDP越高則生活滿意度指標會越高。

### 1.2. [分類問題](https://github.com/y-s-liu/machine-learning-tutorial/blob/master/class1.2_classification.ipynb)
使用 iris 資料集，要從versicolor與virginica中，以花瓣長度與花瓣寬度來分類。

### 1.3. [專案實作一、房地產投資決策](https://github.com/y-s-liu/machine-learning-tutorial/blob/master/class1.3_ML_project_1.ipynb)
使用加州人口普查資料來建立該州的房價模型，預測加州任一區的房價中位數。

### 1.4. [專案實作二、手寫數字辨識](https://github.com/y-s-liu/machine-learning-tutorial/blob/master/class1.4_ML_project_2.ipynb)
使用美國高中生和人口普查局員工手寫的數字圖片來建立數字分類模型，預測手寫數字圖片的數字為何。

### 1.5. [套件實作、pycaret](https://github.com/y-s-liu/machine-learning-tutorial/blob/master/pycaret.md)
* [PyCaret](https://pycaret.org/)是一個以少量程式碼並在短時間內執行多個機器學習任務的的Python開放原始碼函式庫，可自動執行機器學習工作流程，可以加快實驗週期，使工作效率更高。可在幾分鐘之內完成從準備資料、訓練模型到模型部署。

* 圍繞著幾個機器學習函式庫和框架，例如scikit-learn，XGBoost，LightGBM，CatBoost，spaCy，Optuna，Hyperopt，Ray等。可執行的機器學習任務包含分類(classification)、迴歸(regression)、分群(clustering)、異常偵測(anomaly detection)、自然語言處理(natural language processing)、關聯規則學習(association rule mining)

* PyCaret的設計和簡潔性受到了公民數據科學家(Citizen data scientist)概念的啟發，最初是由[Gartner](https://www.ithome.com.tw/news/127217)使用的一個術語。因為，經驗豐富的數據科學家通常很難找到，而且聘用成本昂貴，但是公民數據科學家可以有效地緩解這種差距，並解決業務環境中與資料分析相關的挑戰。

## 主要參考書籍

1. [I. Goodfellow, Y. Bengio and A. Courville, Deep Learning, The MIT Press, MIT, MA, 2016.](https://www.tenlong.com.tw/products/9789865021924?list_name=trs-t)[[Web](https://www.deeplearningbook.org/)]
2. [F. Chollet, Deep Learning with Python, Manning Publications Co., Shelter Island, NY, 2018.](https://www.tenlong.com.tw/products/9789863125501?list_name=rd)[[github](https://github.com/fchollet/deep-learning-with-python-notebooks)]
3. [A. Géron, Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems, O'Reilly Media, Sebastopol, CA, 2019.](https://www.tenlong.com.tw/products/9789865024345?list_name=c-deep-learning)[[github](https://github.com/ageron/handson-ml2/)]

## 推薦線上教學資源
1. [Gilbert Strang, Linear Algebra.](https://www.youtube.com/watch?v=YeznlKTrpmU&list=PL6839449936471E0C)
2. [林軒田，機器學習基石與技法。](https://www.coursera.org/instructor/htlin)
3. [李宏毅，機器學習與深度學習。](http://speech.ee.ntu.edu.tw/~tlkagk/courses_ML20.html)
4. [曾定章，深度學習電腦視覺。](http://ip.csie.ncu.edu.tw/i09.htm)

###### tags: `機器學習` `程式實作` `監督式學習`
