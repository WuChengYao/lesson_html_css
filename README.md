# 常用style
----
###  背景
    background-color: #666;             /* 背景顏色 除了RGB也能RGBA */
    [bg-color參考網址](https://developer.mozilla.org/zh-TW/docs/Web/CSS/background-color)
    ==========
    background-image: url('圖片路徑');   /* 背景圖片 */
    [bg-image參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-image)
    ==========
    background-size: cover;             /* 背景圖片大小 */
    [bg-size參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-size)
    ==========
    background-repeat: no-repeat;       /* 圖片重複 */
    [bg-repeat參考網址](https://developer.mozilla.org/en-US/docs/Web/CSS/background-repeat)
    ==========
    background-position: center;        /* 圖片定位 */
    [bg-position參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-position)
    ==========
    background-attachment: fixed        /* 背景圖片釘圖 */
    [bg-attachment參考網址](https://developer.mozilla.org/zh-TW/docs/Web/CSS/background-attachment)
----
###  文字
    font-size: 20px;            /* 文字大小 */
    [參考網址](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size)
    ==========
    font-family: serif;          /* 文字樣式 */
    [參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-family)
    ==========
    font-weight: 600px          /* 文字粗細 */
    [參考網址](https://developer.mozilla.org/en-US/docs/Web/CSS/font-weight)
    ==========
    font-style: oblique;         /* 文字樣式(斜體 */
    [參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-style)
    ==========
    colro: #666;                 /* 文字顏色 除了RGB也能RGBA */
    [色碼表](https://www.toodoo.com/db/color.html)
    ==========
    line-height: 200%;          /* 行高 */
    [參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/line-height)
    ==========
    letter-spacing: 2px        /* 文字間距 */
    [參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/letter-spacing)
    ==========
    text-align: center;         /* 文字對齊 */
    [參考網址](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)
    ==========
----
###  定位position
    position: relative;         /* 爸爸就沒爸爸，所以找就地定位 */
    position: absolute;         /* 兒子往上層找爸爸，沒爸爸就跟body */
    ==========
    position: fixed;             /* 永遠釘在視窗 */
    ==========
    [參考網址](https://zh-tw.learnlayout.com/position.html)
    position都須搭配 top 、 right 、 bottom 、 left 屬性。
----
###  控制display
    display: Flex;                   /* 變成可控制容器 */
    ==========
    justify-content: center;         /* 容器控制內部:水平置中 */
    ==========
    align-items: center;             /* 容器控制內部:垂直置中 */
    ==========
    flex-wrap: wrap;                 /* 容器控制內部:自動換行 */
    ==========
    flex: 1;                      /* 內部元件自行劃分空間，一般值都用數字最快 */
    ==========
    [參考網址](https://wcc723.github.io/css/2017/07/21/css-flex/)
----
###  陰影
    box-shadow: X Y 半徑模糊 顏色;           /* 區塊陰影 */
    [參考網址](https://developer.mozilla.org/zh-TW/docs/Web/CSS/box-shadow)
    ==========
    text-shadow: 1px 2px 5px red;          /* 文字陰影 */
    [參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-shadow)
    ==========
----
###  內、外距
    margin: 上 右 下 左;           /* 內距 */
    [參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/margin)
    ==========
    padding: 1px 1px 1px 2px;          /* 外距 */
    [參考網址](https://developer.mozilla.org/zh-CN/docs/Web/CSS/padding)
    ==========
