[首頁] > [中華傳道會李賢堯紀念中學]

# 3. 模擬輸入 / 輸出

## 數碼 VS 模擬

數碼與模擬有什麼區別呢？

- 數碼： 只有兩個數值（*0與1、low與high*）
- 模擬： 可以在一個範圍內的任何數值

生活中的模擬與數碼信號：

- 模擬電視 / 數碼電視： 數碼電視更穩定，能展示更多內容，更好的畫面分辨率
- 模擬信號電話 / 數碼信號電話： 更穩定、更快

為什麼會有這樣的區別？

- 模擬信號： 由銅條傳送信號，他們較容易被噪音干擾，亦容易受距離影響
- 數碼信號： 相對穩定，利用中繼器讓信號能到達更遠距離。他們由光纖傳達信號，可以傳送更遠距離，並可以傳送更多數據

你知道**光纖之父**嗎？ 2009年諾貝爾物理學獎得主。

## 模擬輸出（PWM）

我們上堂已經學過數碼輸入 / 輸出，那麼模擬輸出呢？

留意下Sensor Shield，我們只有模擬腳位輸入，但沒有相關的模擬輸出。為什麼？

那是因為Arduino利用PWM（脈衝寬度調變）技術，將數碼信號轉換成模擬信號出書。

> PWM技術
>
> PWM技術是吧數碼信號轉換成模擬信號的一種計算方法。

PWM的原理又是什麼呢？

如果一段時間內，有一半時間處於0V狀態，一半時間處於5V狀態（還記得數碼信號可以輸出0V(G)和5V(V)嗎？），那麼我們會計算它的**平均值**，即是2.5V。

只要將數碼腳位不斷轉換開關信號的相對比例，就可以輸出不同的平均值。

## PWM腳位

PWM腳位處於帶有~符號旁邊。（即 3,5,6,9,10,11）

## LED練習

把LED燈連接到3號腳位（PWM腳位），並編寫程序。

留意PWM值的範圍是0至255。

## 模擬輸入

### 七段顯示器

<!-- links -->
[首頁]: ../../../../../index.md
[中華傳道會李賢堯紀念中學]: ../../index.md