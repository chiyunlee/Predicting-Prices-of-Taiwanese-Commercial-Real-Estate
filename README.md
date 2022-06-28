# **Predicting-Prices-of-Taiwanese-Commercial-Real-Estate**
房價是決定投資不動產的重要因素，而每項影響房價的因子又存在不同的「重要性」(權重)，單靠人腦無法順利算出各項影響房價因子的權重，因此需要藉由電腦幫我們運算龐大的原始資料，訓練各項因子權重，提供了解未來房價的方向。
目前投資人多以觀察實價登錄資料或參考專業顧問意見來判斷是否要投入市場，缺乏綜觀且客觀分析。此外，目前預測模型多以分析住宅類型商品或評估不動產內部條件為主，缺乏其他使用類型(如商用)的研究或加入外部環境影響綜觀思考。
因此希望透由建立一個結合數值型資料(Numerical data)與圖像資料(Image data)的深度學習模型(Deep Learning Model)，運用多種建物本身及加強外在條件特徵(Features)進行模型訓練。
目前階段性模型訓練結果可將預測價差降至6萬/坪(約為半徑500公尺範圍內可能的價差)


## **Dataset**
##### - Retrieved Real Estate Transaction data in Taipei and New Taipei city.
##### -Utilized Heremap and Google APIs to add corresponding longitude, latitude, and nearby features.
## **Data preprocessing**
##### -Numerical Dataset: One-Hot Encoding, Standardization
##### -Image Dataset: Typecast each RGB image to a tensor  (3*256*256)
## **Algorithm and Training**
##### -Combined  numerical dataset and image dataset with Resnet50 + CNN and DNN model.
##### -Best Result:+- $13,000/sqm ($39,000/ping) (+-10%)
