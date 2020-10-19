# stock_0050_analysis
抓取網頁資料與分析0050資料

* stock_0050_udDB.ipynb
到「台灣證券交易所」撈取每日收盤數據，主要是分析0050，所以此程式是針對0050進行撈取並存到sqlite中
https://www.twse.com.tw/zh/

* stock_0050_pick.ipynb
從db中將資料取出並進行圖表繪製，包含收盤價、SMA、KD等趨勢圖，目標是透過觀察，找出適合進場的時機點

