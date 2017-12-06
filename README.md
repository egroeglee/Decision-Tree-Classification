# Decision-Tree-Classification

決策樹的資料分析模板，基本上可以直接套用。

- Decision tree 決策樹 -容易過度擬合
    CART1 : (classification分類(離散數據Nominal)
    CART2 : (Regression回歸(連續的數字.可數Numeric)
	  可用指標: Gini / Entropy / Information Gain / Misclassification Error

範例: 
	 
	根據需求的條件將資料分出 並拆出最終結果以便最後進行測試
	 
		 
	預設是GINI係數 這次用熵
		再用confusion Matrix來直觀的觀看計算出的預測結果為何
	 
	圖表: 訓練集的結果，這裡可以看到測試集的結果被完美的分配，但這個卻代表被過度擬合
	 
圖表: 測試集
 
	根據confusion Matrix可以看到有9個被分類錯誤與上圖相同
