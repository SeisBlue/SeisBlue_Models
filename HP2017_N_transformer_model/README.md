# HP2017_N_transformer_model

## 模型基本說明

|||
|---|---|
|模型中文名稱（name_cht）|地震Transformer模型
|模型英文名稱（name_eng）|EQTransformer
|模型編號(id)|HP2017_N_transformer_model
|模型摘要(含目的/用途/價值等) （description）|地震P, S波相到時辨識
|模型共享範圍及授權方式(license)|禁止商業使用
|模型來源（creator）|Mousavi, S.M., Ellsworth, W.L., Zhu, W., Chuang, L, Y., and Beroza, G, C. Earthquake transformer—an attentive deep-learning model for simultaneous earthquake detection and phase picking. Nat Commun 11, 3952 (2020). https://doi.org/10.1038/s41467-020-17591-w
|模型關鍵字（keywords）| Transformer, Attention, Phase Picking
|模型支援之框架(model framework)與版本|Tensorflow 2.5.0
|模型上架時間（createtime）|2022/07
|模型版本號碼（version）|1.0.0
|聯絡人姓名|黃俊銘
|聯絡人電話|(02) 3366-2932
|聯絡人email|jimmy60504@gmail.com


## 模型訓練說明

|||
|---|---|
|模型中文名稱|地震Transformer模型
|模型英文名稱|EQTransformer
|模型編號|HP2017_N_transformer_model
|訓練資料集名稱|HP2017
|訓練資料集來源|地震構造實驗室
|訓練資料集取得方式|自行收集
|訓練資料集取得/上架時間|2017/07
|訓練資料集檔案大小|地震波Z, N, E分量與P, S, Noise標籤各3008個資料點，11,140筆地震事件，107,077筆P波，107,031筆S波
|訓練資料集檔案類型|裁切地震波形
|訓練資料集是否包含個資與隱私，資料授權方式|無個資與隱私，資料不公開
|標記資料來源與類型|資料來源：地震構造實驗室人工標記 類型：波相到時時間戳記
|訓練日期時間|2022/06
|模型訓練之GPU或CPU使用資源|GPU：Nvida RTX 3090, 10496 Cores, 24GB
|模型訓練之記憶體使用量|10GiB
|模型之使用空間|6.4MB
|模型訓練結果輸出類型|P, S, Noise的機率密度函數
|模型訓練結果類型|recall、precision
|模型訓練結果|P: recall: 0.92, precision: 0.91, S: recall: 0.85, precision: 0.83


## 模型驗證說明

|||
|---|---|
|模型中文名稱|地震Transformer模型
|模型英文名稱|EQTransformer
|模型編號|HP2017_N_transformer_model
|驗證資料集名稱|HP2020
|驗證資料集來源|地震構造實驗室
|驗證資料集取得方式|自行收集
|驗證資料集取得/上架時間|2020/07
|驗證資料集檔案大小|連續地震波形Z, N, E分量，時間長度：4/1-6/30, 4,250筆地震事件，31,925筆P波，31,005筆S波
|驗證資料集檔案類型|連續地震波形
|驗證資料集是否包含個資與隱私，資料授權方式|無個資與隱私，資料不公開
|標記資料來源與類型|資料來源：地震構造實驗室人工標記，類型：波相到時時間戳記
|驗證日期時間|2022/06
|模型驗證之GPU或CPU使用資源|GPU：Nvida RTX 3090, 10496 Cores, 24GB
|模型驗證之記憶體使用量|10GiB
|模型之使用空間|6.4MB
|模型驗證結果輸出類型|P, S, Noise的機率密度函數
|模型驗證結果類型|recall、precision
|模型驗證結果|P: recall: 0.89, precision: 0.10, S: recall: 0.81, precision: 0.09


## 模型效能量測說明

|||
|---|---|
|模型中文名稱|地震Transformer模型
|模型英文名稱|EQTransformer
|模型編號|HP2017_N_transformer_model
|效能量測所使用之資料集名稱|CWBSN
|效能量測所使用之資料集來源|中央氣象局
|效能量測所使用之資料集取得方式|GDMS 中央氣象局 台灣地震與地球物理資料管理系統 https://gdmsn.cwb.gov.tw/eqconDownload.php
|效能量測所使用之資料集取得/上架時間|2012/02
|效能量測所使用之資料集檔案大小|地震連續資料Z, N, E分量，時間長度：2012 1/1-1/31，2,232筆地震事件，79個地震測站
|效能量測所使用之資料集檔案類型|地震連續波形
|效能量測所使用之資料集是否包含個資與隱私，資料授權方式|無個資與隱私，政府公開資料
|效能量測所使用之資料之標記資料來源與類型|資料來源：中央氣象局地震目錄，類型：波相到時時間戳記
|模型使用之GPU或CPU使用資源|GPU：Nvida RTX 3090, 10496 Cores, 24GB
|模型使用之記憶體使用量|10GiB
|模型之使用空間|6.4MB
|模型預期之測試執行時間|2022/05
|模型預期之測試結果輸出類型|P, S, Noise的機率密度函數
|模型預期之測試結果類型|Recall
|模型預期之測試結果|P recall: 0.59，S recall: 0.54，地震目錄 recall: 0.56
