# 1.5. 套件實作、pycaret
* 課程教學範例(中文)
    * [二元分類教學（CLF101）- 初級 - 台灣信用卡客戶違約支付預測](https://github.com/y-s-liu/machine-learning-tutorial/blob/master/PyCaretT_Binary_Classification_Tutorial_Level_Beginner_CLF101.ipynb)
    * [二元分類實例 - CNC機台銑刀磨損偵測](https://github.com/y-s-liu/machine-learning-tutorial/blob/master/PyCaretT_CNC_Mill_Tool_Wear_Detection_Train_Test.ipynb)

* 在幾分鐘之內完成從準備資料到部署模型。
    * [執行步驟](https://pycaret.org/get-data/)
        * 初始化(initialize)
            * 獲取分析資料(getting data)
            * 建構實驗環境(setting up environment)
        * 訓練模型(model training)
            * 比較分類與迴歸模型(compare models)
            * 建立模型(create models)
            * 調整模型(tune model)
        * 分類與迴歸模型組裝(model ensembling)
            * 組合分類與迴歸模型(ensemble model)
            * 混合分類與迴歸模型(blend models)
            * 堆疊分類與迴歸模型(stack models)
        * 模型分析(model analysis)
            * 圖形化分析(plot model)
            * 解釋分類與迴歸模型(interpret model)
            * 無監督學習結果分配檢測(assign model)
            * 分類模型校正(calibrate model)
            * 分類模型門檻值最佳化(optimiza threshold)
       * 模型運用(model deployment)
            * 最終模型(finalize model)
            * 模型預測(predict model)
            * 模型部署至公有雲(deploy model)
            * 模型保存(save model)
            * 實驗保存(save experiment)

* 官方教學範例(英文)
    * [迴歸問題](https://github.com/pycaret/pycaret/blob/master/tutorials/Regression%20Tutorial%20Level%20Beginner%20-%20REG101.ipynb)
        * 初始化
            * 獲取分析資料：使用pandas函式庫讀取檔案，也可從PyCaret資料集導入資料。
            * 設置實驗環境：在PyCaret中設置實驗用以開始構建迴歸模型。
        * 訓練模型
            * 建構模型：建構模型，執行分層交叉驗證和評估分類指標。
            * 調整模型：自動調整迴歸模型的超參數。
        * 模型分析
            * 分析模型性能：使用各種圖形分析模型性能。
        * 模型運用
            * 最終模型：在實驗結束時最終確定最佳模型。
            * 模型預測：對未知的資料進行預測。
            * 模型保存/載入：保存/載入模型以備將來使用。

    * [分類問題](https://github.com/pycaret/pycaret/blob/master/tutorials/Binary%20Classification%20Tutorial%20Level%20Beginner%20-%20%20CLF101.ipynb)
        * 初始化
            * 獲取分析資料：使用pandas函式庫讀取檔案，也可從PyCaret資料集導入資料。
            * 設置實驗環境：在PyCaret中設置實驗用以開始構建分類模型。
        * 訓練模型
            * 建構模型：建構模型，執行分層交叉驗證和評估分類指標。
            * 調整模型：自動調整分類模型的超參數。
        * 模型分析
            * 分析模型性能：使用各種圖形分析模型性能。
        * 模型運用
            * 最終模型：在實驗結束時最終確定最佳模型。
            * 模型預測：對未知的資料進行預測。
            * 模型保存/載入：保存/載入模型以備將來使用。

    * [異常偵測](https://github.com/pycaret/pycaret/blob/master/tutorials/Anomaly%20Detection%20Tutorial%20Level%20Beginner%20-%20ANO101.ipynb)
        * 初始化
            * 獲取分析資料：使用pandas函式庫讀取檔案，也可從PyCaret資料集導入資料。
            * 設置實驗環境：在PyCaret中設置實驗用以開始構建異常偵測模型。
        * 訓練模型
            * 建構模型：如何建構模型並將異常標籤分配給原始資料集進行分析。
        * 模型分析
            * 分析模型性能：使用各種圖形分析模型性能。
        * 模型運用
            * 最終模型：在實驗結束時最終確定最佳模型。
            * 模型預測：使用訓練後的模型將異常標籤分配給未知的資料。
            * 模型保存/載入：保存/載入模型以備將來使用。
