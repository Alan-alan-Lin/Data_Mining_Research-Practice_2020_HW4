# Data_Mining_Research-Practice_2020_HW4
HW4 - Fake News Detection  
資料集 : Fake News Detection Challenge KDD 2020  
目標 : 預測一則新聞是否reliable  
流程 :  
>1.資料前處理  
 a. 讀取"train.csv"與"test.csv"並利用分割符號切割、建立train&test之DataFrame  
 (註：分割符號為tab(\t))  
 b. 去除停頓詞stop words   
 c. 文字探勘前處理，將文字轉換成向量  
2.建模：分別使用以下三種模型xgboost、GBDT、LightGBM  
3.評估模型  
利用"test.csv"的資料對2.所建立的模型進行測試，並計算Accuracy、Precision、Recall、F-measure  
