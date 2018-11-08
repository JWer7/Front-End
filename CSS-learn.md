# Introduction 
Cascading Style Sheets 层叠样式表 — 表现Html文件样式
***
## Font-size — 字体大小
```<p style="font-size:......">......</p>```</br>
</br>
*单位：像素（px）、百分比（%）、em值*</br>
字体在浏览器默认显示大小为**16px**=**100%**，以此类推
## Color — 颜色
```<p style="color:......">......</p>```</br>
</br>
*表示方式：RGB、16进制编码、颜色名称*</br>
color:red ▏color:rgb(225,10,10) 参数值可用数字也可用百分值 ▏color:63B1DC
## Font-weight —— 字体粗细
```<p style="font-weight:......">......</p>```</br>
</br>
*表示方式：数字或名称*</br>
数字从100到900由细至粗，**400=Normal**，**700=Bold**
## Font-style:italic —— 斜体
```<p style="font-style:italic">......</p>```
## Text-decoration —— 横线
```<p style="font-decoration:underline">下划线</p>```</br>
```<p style="font-decoration:overline">顶部实线</p>```</br>
```<p style="font-decoration:line-through">删除线</p>```
## Line-height —— 行间距
```<p style="line-height:......">......</p>```</br>
</br>
*1em = 当前字体尺寸；2em = 当前尺寸的两倍*
## Letter-spacing —— 字母间距
```<p style="letter-spacing:......">......</p>```
## Text-align —— 对齐
```<p style="text-align:......">......</p>```</br>
</br>
*left/right/center/justify-两端对齐*
## Text-indent —— 文本缩进
```<p style="text-indent:......">......</p>```
## Text-shadow —— 投影
```<p style="text-shadow:5px 5px 5px #FF6600">......</p>```</br>
</br>
*水平阴影、垂直阴影、模糊距离、阴影颜色-其他表达方式亦可*
## 链接样式
*默认情况下，浏览器常用蓝色显示链接并附带下划线*
### 伪类：基于元素状态
```<style>```</br>
```a:link{color:red}```</br>
```a:hover{```</br>
```color:cyan;```</br>
```text-decoration:underline;}```</br>
```a:active{color:pink}```</br>
```a:visited{color:grey}```</br>
```</style>```</br>
```<a href="www.baidu.com">百度</a>```</br>
</br>
*未访问过的链接的显示样式*</br>
*鼠标在链接上徘徊但是并未点击的状态*</br>
*链接呗点击后的状态*</br>
*已经点击且浏览过了的链接样式*</br>
## Class —— 类选择器
以点号表示，即英文标点符号的句号。在<style>内定义</br>
```<style>```</br>
```.center```</br>
```</style>```</br>
</br>
*类选择器可任意命名，但不可以数字开头*
