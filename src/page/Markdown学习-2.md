# Markdown 语言的编写[^作者]

[^作者]:王幽

## 一、区块

区块在段落的开头使用（>）符号来表示，然后后面紧跟一个空格符号，会显示一个竖线表示那一个区域，例如：
> 区块引用  
> 这里是区块的内容  
> 每行区块行末尾要换行的话使用两个空格符号换行

## 二、区块的嵌套

可以用（>）的个数来表示区块的互相嵌套
>最外层内容  
>>第一个子层内容
>>>第二一个子层内容

## 三、代码

### 在段落中显示片段代码

在一个段落中需要展示一个函数，或者某个片段代码的时候使用反引号将他们包裹起来,实例:  
`fun()`这里表示一个函数，`const a=100`这里表示一个片段代码。

### 显示一个代码块

显示一个代码块的时候使用四个空格或者一个制表符，也可以使用三个反引号的形式表示一段代码，并且指定一种语言，实例：  

指定一个JavaScript语言

``` javascript

function fun() {
      console.log("这里显示的是一个代码块")
    };  

```  

下面指定的语言是HTML，所以会看到提示为HTML语言

``` html
<html>
  <body>
  <h1>这里表示一个HTML文本</h1>
  </body>
</html>

```

## 四、链接

表示的方法：  
[链接的名称](链接的地址)  
或者写成  
<链接的地址>  
例如：[百度](www.baidu.com)

## 五、 图片

如下所示：
![图片不能正常显示时显示这段文字](../assets/天使彦.jpg "这里可以写一个标题")  

## 表格

制作表格的时候使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行  
实例:  
| 表头一 | 表头二 |  
| -----  | -----  |
| 单元格 |  单元格 |
| 单元格 |  单元格 |

### 设置表个的对齐方式

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
