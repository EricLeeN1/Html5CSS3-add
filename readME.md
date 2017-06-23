# css3属性补全--完善自我

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

