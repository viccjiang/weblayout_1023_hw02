# weblayout_1023_hw02
hexschool1023

## 第二週 - Flexbox 網頁排版術

### 本週訓練菜單
* 1.1 做當週關卡作業，吸收當週教授觀念
* 1.3 將本週教授內容寫成[部落格](https://viccjiang.github.io/blog/)，以加深程式觀念
* 1.4 自主學習新語法，並寫成筆記 
* 2.1 熟悉三個編輯器熱鍵，熱鍵中文表  [熱鍵中文表](https://github.com/hexschool/VSCode_Hotkey_Translation)
* 2.2 幾乎全程使用 emmet 來開發  [emmet](https://docs.emmet.io/cheat-sheet/) 開發
* 3.1 透過 [keybr.com](https://www.keybr.com/profile/f5x1p6r) 練習英打，目前分數超級低，預計每天都要練習10min
* 3.2 刻意練習 emmet 與常見英文命名鍵位


### flex 觀念

* display: flex
* container 介紹
    * 外容器加上 display:flex 控制內元件
    * flex 可以再包 flex
* Flex 主軸與交錯軸觀念([測試工具](https://codepen.io/peiqun/pen/WYzzYX))
* 容器
    * 外容器：container
    * 內元件：item

### 常見語法
* Flex 起手式：在外容器加上 `display : flex ;`
  預設值為 `flex-direction :row;`
* 決定主軸線：flex-direction 
    * 1.row 水平
    * 2.row-reverse 水平反序
    * 3.column 垂直
    * 4.column-reverse 垂直反序
* 主軸對齊：justify-content 
    * 1.flex-start 靠起點對齊
    * 2.center 置中
    * 3.flex-end 靠終點對齊
    * 4.space-between 平均分配內容元素，左右元素貼齊
    * 5.space-around 平均分配內容元素，間距平均分配
    * 6.space-evenly

* 換行屬性：flex-wrap
    * 1.nowrap 不換行
    * 2.wrap 換行

* 交錯軸對齊：align-item
    * 1.flex-start 靠起點對齊
    * 2.center 置中
    * 3.flex-end 靠終點對齊
    * 4.stretch 將內容元素全部撐開至 Flexbox 的高度
    * 5.baseline 所有內容元素的基線作為對齊標準



### Flex emmet 
| df| fxd| jc | ac | ai |
| --------| --------| -------- | -------- | -------- |
| display:flex| flex-direction| justify-content     | align-content     | align-items     |

| fxd:c | fxd:cr | 
| -------- | -------- | 
| flex-direction:column    |flex-direction:column-reverse   |

| fxw | fxg | fxsh |
| -------- | -------- | -------- |
| flex-wrap    | flex-grow     | flex-shrink    |

| fxb | ord  |
| --------  | -------- |
| flex-basis     | order        |

| as:fe | as:fs | 
| -------- | -------- |
| align-self: flex-end;    | align-self: flex-start;    | 

| fxd:r | fxd:rr | 
| -------- | -------- | 
| flex-direction:row;   | flex-direction:row-reverse;| 




### 本週小節
* 主軸&交錯軸的觀念
* flex 不要濫用
* flex 要下對地方
* flex 排版技術
* 運用 flex emmet

### 補充資源
* [flex測試工具01](https://codepen.io/peiqun/pen/WYzzYX)
* [flex測試工具01](https://demos.scotch.io/visual-guide-to-css3-flexbox-flexbox-playground/demos/)
* [flex測試工具02](http://wcc723.github.io/WorkShop-gh-pages/cssFlex/)
* [圖解：CSS Flex 屬性一點也不難](https://wcc723.github.io/css/2017/07/21/css-flex/)
* [卡斯伯完整 Flex 影音教學(40分鐘)](https://www.youtube.com/watch?v=lmBM7_OTDBQ)


### 第二週主線任務

* [第二週-個人網站](https://viccjiang.github.io/weblayout_1023_hw02/)
* [code review](https://github.com/viccjiang/weblayout_1023_hw02)




### 第二週每日任務

* [10/26](https://codepen.io/viccjiang/pen/oNLZzZP) 
* [10/27](https://codepen.io/viccjiang/pen/MWepRGp) 
* [10/28](https://codepen.io/viccjiang/pen/LYZjePN)
* [10/29](https://codepen.io/viccjiang/pen/eYzVVbm)
* [10/30](https://)


### 第二週小組任務 
* [Flex pirate 新手關卡](https://hexschool.github.io/flexbox-pirate/index.html#/)
* [Flex 青蛙](https://flexboxfroggy.com/#zh-tw)
