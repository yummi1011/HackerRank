# 关于 Markdown  
------------------------------------------------------------------------------  
## 1. Markdown 标题  
Markdown 标题有两种格式。  
### 1.1 使用=和-标记一级和二级标题  
语法格式如下：  
~~~
我展示的是一级标题
=================

我展示的是二级标题
-----------------
~~~

显示效果如下：  


我展示的是一级标题
=================
我展示的是二级标题
-----------------  

### 1.2 使用#号标记

使用#号可表示1-6级标题，一级标题对应一个#号，二级标题对应两个#号，以此类推。  
 
 ```
# 一级标题  
## 二级标题  
### 三级标题  
#### 四级标题  
##### 五级标题  
###### 六级标题
```
显示效果如下:  
# 一级标题  
## 二级标题  
### 三级标题  
#### 四级标题  
##### 五级标题  
###### 六级标题

## 2. Markdown 段落格式  

### 2.1 Markdown 段落  
Markdown 段落没有特殊的格式，直接编写文字就好，段落的换行是使用两个以上空格加上回车。  
```
上一段（在最后添加两个空格）
下一段
```
也可以在段落后面使用一个空行来表示重新开始一个段落。  
```
上一段

下一段
```

### 2.2 Markdown 字体  
Markdown 可以使用以下几种字体  
```
*斜体文本*
_斜体文本_
**粗体文本**
__粗体文本__
***粗斜体文本***
___粗斜体文本___
```


### 2.3 分隔线

你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：
```
***

* * *

*****

- - -

----------
```

### 2.4 删除线
如果段落上的文字要添加删除线，只需要在文字的两端加上两个波浪线 ~~ 即可，实例如下：
```
GOOGLE.COM
~~BAIDU.COM~~
```
显示效果如下：
GOOGLE.COM
~~BAIDU.COM~~

## 3 Markdown 列表
Markdown 支持有序列表和无序列表。
### 3.1无序列表
使用星号(\*)、加号(+)或是减号(-)作为列表标记，这些标记后面要添加一个空格，然后再填写内容：
```
* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项


- 第一项
- 第二项
- 第三项
```
显示结果如下：
* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项


- 第一项
- 第二项
- 第三项
### 3.2 有序列表
使用数字并加上 . 号来表示，如：
```
1. 第一项
2. 第二项
3. 第三项
```
显示结果如下：
1. 第一项
2. 第二项
3. 第三项

### 3.3 列表嵌套
列表嵌套只需在子列表中的选项前面添加四个空格即可：
```
1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素
```
显示结果如下：
1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素

## 4 Markdown 区块
### 4.1 区块引用
Markdown 区块引用是在段落开头使用 > 符号 ，然后后面紧跟一个空格符号：

```
> 区块引用
> 菜鸟教程
> 学的不仅是技术更是梦想
```
显示结果如下：

> 区块引用
> 菜鸟教程
> 学的不仅是技术更是梦想

另外区块是可以嵌套的，一个 > 符号是最外层，两个 > 符号是第一层嵌套，以此类推：
```
> 最外层
> > 第一层嵌套
> > > 第二层嵌套
```

显示效果如下： 
> 最外层
> > 第一层嵌套
> > > 第二层嵌套

### 4.2 区块中使用列表

区块中使用列表实例如下：
```
> 区块中使用列表
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项
```

显示效果如下： 
> 区块中使用列表
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项

### 4.3 列表中使用区块
如果要在列表项目内放进区块，那么就需要在 > 前添加四个空格的缩进。

列表中使用区块实例如下：
```
* 第一项
    > 菜鸟教程
    > 学的不仅是技术更是梦想
* 第二项
```

显示效果如下： 
* 第一项
    > 菜鸟教程
    > 学的不仅是技术更是梦想
* 第二项

## 5 Markdown 代码
### 5.1 代码
如果是段落上的一个函数或片段的代码可以用反引号把它包起来（\`），例如：
```
`printf()` 函数
```
显示效果如下：
`printf()` 函数

### 5.2 代码区块
使用\`\`\`包裹一段代码：
```
```
$(document).ready(function () {
    alert('RUNOOB');
});
```
```
显示效果如下： 
```
$(document).ready(function () {
    alert('RUNOOB');
});
````

