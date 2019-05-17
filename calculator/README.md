# 計算機

## 說明

1. 簡易的文字型計算機
2. 輸入：a, op, b 三個欄位
3. 輸出：result

舉例： a=3 , op=* , b=5

```js
  function calculate() {
    var a = document.getElementById('a')
    var op = document.getElementById('op')
    var b = document.getElementById('b')
    var result = document.getElementById('result')
    result.innerText = eval(a.value + op.value + b.value)
  }
```

我們可以用 document.getElementById('a') 取得 a 元件，以此類推。

按下計算按鈕之後，就會用 

result.innnerText = eval(a+op+b)


算出結果並呈現在畫面上

於是就會顯示 15


