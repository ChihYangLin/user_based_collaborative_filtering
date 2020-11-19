# User_based Collaborative Filtering

## 計算顧客之間的相似度，找出最相似的(TOP-N)顧客，依照評分高低做推薦。

## 實作步驟
* 將資料整理成三個欄位:[顧客ID, 商品ID, 評分]
* 製作USER-ITEM的矩陣，用cosine similarity 計算使用者的相似度
* 製作USER-USER的矩陣，根據相似度可找出(TOP-N)相似的USER
* 根據(TOP-N)USER 買過的商品評分高低做推薦
