# tMap Unify

> ### Introducing brand new tMap Unify.

## 概念
### 創作目的
透過提供整合資訊、協助使用者從起始點與目的地，結合自身理想條件等，提供國內各式交通工具之利與弊以輔助選擇
### N需求
使用者不知道如何選擇哪一種交通工具，同時也懶得一直切換不同的app
交通方式：步行、自行車、開車、機車、大眾運輸
### A方法
整合多種資料來源（e.g. google maps、[Weather API/OpenWeatherMap](https://openweathermap.org/api)、中油、台鐵、高鐵、北捷、公車票價、ubike、網路上被別人偷看的監視器, etc.），並經過分析 （天氣、價錢、轉乘複雜度），得出最佳的推薦交通工具、路線
### B收益
有利於使用者更快速選擇出門方式、節省使用者花更多的時間去查詢複數以上的其他網站平台、金錢與燃料/體力消耗
### C競爭
整合性
## 功能實現
1. 從GOOGLE MAP推薦前往方式出發，依照建議前往方式提供使用者對應氣候資訊。
### 交通工具選擇
- 共同
    - 花費時間
    - 花費金錢
    - 氣候資訊(包含:溫度、降雨機率、空氣品質指標、紫外線指數)
- 個別資訊
    - 步行
    - 自行車
        - youBike站點(最近站點)
    - 開車
        - 今日油價
    - 機車
        - 今日油價
    - 大眾運輸
        - 票價
    - 乘車
      匯率

## 7/20輪桌討論的回饋
R1
1. Ｇoogle maps功能重疊性較高，但部分資訊能須經由其他平台
2. 短期內技術上沒辦法以概略資訊搜尋到實際地點
3. 每個地點附上Google maps、中油油價等的外部資料來源連結
4. 配合使用者的年齡對分析結果與推薦選項進行調整
5. 同時提供當地道路監視器影像供使用者參考？
R2
6. 操作方式？
	1. 輸入起終點
	2. 規劃路線
	3. 分析
   4. 提供使用者選擇
    ```
    因素：
    - 路線中各地天氣(氣溫、降水)
    - 交通耗時
    - 花費
    ```
	5. 給出各種交通方式的分析
	6. 
7. 最佳路徑上每一個區域的天氣資訊
8. 我們的主意很棒(拍手)
9. 號誌燈數量、時長，步行區？
10. cross functional diagram

