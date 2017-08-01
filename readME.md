# css3属性补全--完善自我
2017/8/1 16:41:34 

## 1.calc

    使用“+”、“-”、“*” 和 “/”四则运算；
    可以使用百分比、px、em、rem等单位；
    可以混合使用各种单位进行计算；
    表达式中有“+”和“-”时，其前后必须要有空格，如"widht: calc(12%+5em)"这种没有空格的写法是错误的；
    表达式中有“*”和“/”时，其前后可以没有空格，但建议留有空格。
    使用方法:
    .elmClass{
    width: 1200px;
    /*不支持calc时要设置一个备用宽度*/
    width: -moz-calc(100%-40px);
    width: -webkit-calc(100%-40px);
    width: calc(100%-40px);
    margin: auto;
    }

## 2.apperance

    改变元素的外观
    使用方法:
    .eleClass{
    -webkit-appearance: value;
    -moz-appearance: value;
     appearance: value;
    }

## 3.audio

## 4.video

## 5.HTML-5拖放

	1. 设置元素为可拖放
		draggable = "true"
	2. 拖动什么
		ondragstart和setData()
	3. 放到何处
		ondragover
	4. 进行放置
		ondrop
	
## 6.canvas

## 7.svg

## 8.地理定位

## 9.Web存储
	
	1. localStorage
	2. sessionStorage

## 10.CSS3-border
	
	1. border-radius
	2. box-shadow
	3. border-image

## 11.CSS3-bg
	
	1. background-size
	2. background-origin

## 12.CSS3-text	
	
	1. text-shadow
	2. word-wrap
	3. @font-face{}
		 `@font-face {
            font-family: myFamily;
            src: url("");
            src: url("");
        }
        div {
            font-family: myFamily;
        }`

## 13.CSS3-2d->transform
	
	1. translate()->移动
	2. rotate()->旋转
	3. scale()->缩放
	4. skew()->倾斜
	5. matrix()->方法需要六个参数，包含数学函数，允许您：旋转、缩放、移动以及倾斜元素。

## 14.CSS3-3d->transform
	
	1. rotateX()
	2. rotateY() 

## 15.CSS3-过渡
		
	transition

## 16.CSS3-动画

	1. animation
	2. @keyframes name{}

## 17.CSS3-多列
	
	1. column-count
	2. column-gap
	3. column-rule
	