# This is a fundemental usage guidance about markdown.

## 1. 标题

## 2. 字体
**这是加粗的文字**

*这是倾斜的文字*`

***这是斜体加粗的文字***

~~这是加删除线的文字~~

## 3. 引用
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容

## 四、分割线
---
----
***
*****
## 五、图片
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加

![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")

## 六、超链接
[超链接名](超链接地址 "超链接title")
title可加可不加

[简书](http://jianshu.com)
[百度](http://baidu.com)

<a href="超链接地址" target="_blank">超链接名<a>
示例
<a href="https://www.jianshu.com/u/1f5ac0cf6a8b" target="_blank">简书</a>

## 七、列表
- 列表内容
+ 列表内容
* 列表内容注意：- + * 跟内容之间都要有一个空格




1. 列表内容
2. 列表内容
3. 列表内容

注意：序号跟内容之间要有空格


表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
列表嵌套
上一级和下一级之间敲三个空格即可

## 八、表格
- 有一个就行，为了对齐，多加了几个
文字默认居左
- 两边加：表示文字居中
- 右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
## 九、代码
    `代码内容`

```
  代码...
  代码...
  代码...
```
## 十、流程图（不支持）
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```