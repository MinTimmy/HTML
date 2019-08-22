#   HTML

###  文字段落編排

|標籤        | 中文解釋  |
| ------------- | :-----:|
|&lt;br&gt;|換行標籤|
|&lt;p&gt;|段落標籤|
|&lt;h1&gt;~&lt;h6&gt;|標題標籤：其中&lt;h1&gt;字體最大，&lt;h6&gt;字體最小|
|&lt;hr&gt;|水平線標籤|
|&lt;blockquote&gt;|縮排標籤|
|&lt;div&gt;|區域元素標籤，此標籤前後自動換行，常配合CSS|
|&lt;span&gt;|行內元素標籤，此標籤前後不會換行，常配合CSS|
|&lt;!--註解--&gt;|HTML註解功能|


<br>

## 顯示特殊字元
|標籤| 中文解釋  |
| ------------- | :-----:|
|&lt|&lt;|
|&gt|&gt;|
|&quot|&quot;|
|&times|&times;|
記的指令最後都要加分號

<br>

##  編號項目符號

1.&lt;ul&gt;編號清單
<br>
```HTML
<ol start="起始編號" type="編號模式">
    <li>項目一</li>
    <li>項目二</li>
</ol>
```
type=&quot;1&quot;，阿拉伯數字<br>
type=&quot;i&quot;，小寫羅馬數字<br>
type=&quot;I&quot;，大寫羅馬數字<br>
type=&quot;a&quot;，小寫英文字母<br>
type=&quot;A&quot;，大寫英文字母<br>



2.&lt;ul&gt;符號清單
<br>
```HTML
<ul type="編號模式">
    <li>項目一</li>
    <li>項目二</li>
</ul>
```
type=&quot;circle&quot;，阿拉伯數字<br>
type=&quot;square&quot;，小寫羅馬數字<br>


## 文字格式
|標籤| 中文解釋  |
| ------------- | :-----:|
|&lt;b&gt;,&lt;strong&gt;|文字以粗體顯示|
|&lt;i&gt;,&lt;em&gt;|文字以斜體顯示|
|&lt;u&gt;,&lt;ins&gt;|文字下面加上底線|
|&lt;s&gt;,&lt;del&gt;|文字加上刪除線|

##  超連結
```HTML
<a href="聯結資源" target="聯結方式">網頁顯示的圖片或文字</a>
```


##  圖片的使用
```HTML
<img src="圖擋路徑" width="寬度" height="高度">
```
|標籤屬性|說明|
|:------:|:------:|
|src|設定圖擋路徑|
|align|left：圖片靠左<br>right：圖片靠右<br>center：圖片置中<br>bottom：文字對齊圖片下緣<br>top：文字對齊圖片上緣<br>middle圖片垂直至中對齊文字|
|height|設定圖片高度：預設值pixels|
|width|設定圖片寬度：預設值pixels|
|border|設定圖片外框|
|alt|設定圖片說明文字：當圖片無法顯示時會出現|

# CSS

|CSS語法       | 功能           | 細項  |
| ------------- |:-------------:| :-----:|
|font-family|改變字體|sans-serif , serif , monospace , cursive , fantasy|
|font-size|改變字的大小| small , medium , large , 10px , 120%|
|font-weight|改變字的粗細| bold=粗 , normal=細|
|font-style|改變字的風格|italic=斜體字向右傾斜|
|color , background-color|改變字的顏色|[color charts] : (https://www.w3schools.com/cssref/css_colors.asp) <br> rgb(80%,40%,0%) <br>rgb(204,102,0)|
|text-decoration|裝飾字體|underline=底線 , line-through=文字中有條線（刪除線）, overline=頂線 , none=沒有線 |

例子在:demo3,demo4

