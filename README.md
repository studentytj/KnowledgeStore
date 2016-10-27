# KnowledgeStore

[TOC]  
##目录
  * [Questions](遇到的问题)
  * [demo地址](demo地址)

##自学过程中遇到的问题                         
>登鹳雀楼---李白
>白日依山尽，黄河入海流
>欲穷千里目，更上一层楼
>>总要吃些苦头，才能尝尽甜头

##自学过程中遇到的问题
* 如何在*元素*前面添加一张**图片**？  
利用`content：url(imageurl)`即可添加  

!!! hint "待解决"  
        如何控制加入图片的垂直居中！

* `text-align`  
`text-align`主要用来定义行内内容（例如文字）如何相对它的块父元素对齐，并不控制块元素本身的对齐  
* `vertical-align`  
用在`inline`      `table-cell`元素  
* 图片`img`居中方法  
```css
img{
    display:block;  
    margin:0 auto;
}
```
5.如何使用div居中方法  
  参考**segmentfault**中的回答：  
  [div中的内容垂直居中的五种方法](https://segmentfault.com/a/1190000003745881)
----------------------------------------
##学习中的知识总结
1.元素类型  

|       元素类型 | 标签       | 特点|
|:-----------: | ---------- | ---------|
| 块状元素   | ```<div>,<p>,<h1>…<h6>,<ol>,<ul>,<dl>,<table>,<address>,<blockquote>,<form>```     | 1.每个块级元素都从新的一行开始，并且其后的元素也另起一行。（真霸道，一个块级元素独占一行）2.元素的高度、宽度、行高以及顶和底边距都可设置。3.元素宽度在不设置的情况下，是它本身父容器的100%（和父元素的宽度一致），除非设定一个宽度。|
|内联元素    | ```<a>,<span>,<br>,<i>,<em>,<strong>,<label>,<q>,<var>,<cite>,<code>```                  | 1、和其他元素都在一行上；2、元素的高度、宽度及顶部和底部边距不可设置；3、元素的宽度就是它包含的文字或图片的宽度，不可改变。
|内联块状元素| ```<img>  , <input>``` | 1、和其他元素都在一行上；2、元素的高度、宽度、行高以及顶和底边距都可设置。|









