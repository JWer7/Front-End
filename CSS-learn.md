# Website
https://www.thinkcss.com/
# Introduction 
Cascading Style Sheets 层叠样式表 — 表现Html文件样式
***
## 关于速记标示/简写
https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties</br>
## 引用CSS文件
```<style>```</br>
```@import url(xxxxxx.css);```</br>
```</style>```</br>
但我们通常使用</br>
```<link rel="stylesheet" href="xxxxxx.css">```</br>
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
以点号表示，即英文标点符号的句号。**在<style>内定义**</br>
```<style>```</br>
```.center{```</br>
```text-align:center;```</br>
```font-weight:bold;}```</br>
```</style>```</br>
```<p class="center">......</p>```</br>
</br>
*类选择器可任意命名，但不可以数字开头*</br>
*在{}内撰写样式，不同样式间用分号隔开*</br>
*使用class="类选择器名"来调用该类选择器*</br>
## 伪类 —— 基于元素的状态
:hover —— 鼠标悬停的状态</br>
:active —— 被按下但未松手的状态/交互</br>
</br>
*注意使用场景，如PC端、手机端等*</br>
</br>
### 撰写方法
```<style>```</br>
```.类选择器名:hover{......}```</br>
```</style>```</br>
```<p class="类选择器名">.....</p>```</br>
## Div —— CSS盒子模型
```<style>```</br>
```.simple{```</br>
```height:300px;```</br>
```width:400px;```</br>
```border:1px solid black;}```</br>
```</style>```</br>
```<body>```</br>
```<div class="simple">我是一个盒子</div>```</br>
```</body>```</br>
</br>
### Width —— 宽度
为了保证不同设备不同屏幕的适配性，可以设定一个**最小宽度min-width**，一个**最大宽度max-width**</br>
</br>
### Overflow —— 内容溢出
overflow:hidden —— 超出盒子部分直接隐藏</br>
overflow:scroll —— 卷轴，即上下左右拉条</br>
</br>
### Border —— 边框
border-width —— 边框宽度</br>
border-style —— 边框样式|||solid-实线||dotted-一串方形点||dashed-虚线||double-两条实线</br>
border-color —— 边框颜色</br>
*快捷方式*</br>
border:3px solid blue
## Padding —— 内边距
内容与边框的距离</br>
padding-top —— 上方内边距；padding-bottom —— 下方内边距</br>
padding-right —— 右边内边距；padding-left —— 左边内边距</br>
*快捷方式*</br>
padding:10px 5px 3px 1px  上右下左
## Margin —— 外边距
盒子之间的空隙</br>
表达方式与内边距类似</br>
*快捷方式*</br>
margin:25px 50px 75px 100px  上右下左</br>
margin:25px 50px 75px 上/左右/下</br>
margin:25px 50px 上下/左右</br>
margin:25px 上下左右等值</br>
## Background-color —— 背景颜色
## Background-image —— 背景图片
```background-img:url('')```
## Block element & Inline element —— 块级元素和内联元素
### 块级元素
宽高都可以设置</br>
默认独占一行</br>
常用的<div>\<p>等都是块级元素</br>
### 内联元素
宽高不可以设置</br>
无需独占一行<br>
### Display —— 转换块级元素和内联元素
比如使用*ul*制作一个导航栏，但*li*为块级元素，需要独占一行，这时可以转换元素类型</br>
块级元素→内联元素 —— display:inline</br>
```<style>```</br>
```li{display:inline;```</br>
```margin:10px;}```</br>
```</style>```</br>
```<ul>```</br>
```<li>......</li>```</br>
```<li>......</li>```</br>
```<li>......</li>```</br>
```</ul>```</br>
</br>
内联元素→块级元素 —— display:block</br>
### Visibility —— 盒子可见性
visibility:hidden —— 隐藏但保留元素占用空间，即原有位置处空白显示，可使用display:none完全隐藏</br>
visibility:visible —— 可见</br>
```<style>```</br>
```li.coming-soon{visibility:hidden;}```</br>
```</style>```</br>
```<ul>```</br>
```<li>......</li>```</br>
```<li class="comng-soon">......</li>```</br>
```</ul>```
## Box-shadow —— 盒子投影
box-shadow:5px 5px 5px 5px #777777</br>
</br>
水平偏移、垂直偏移、模糊距离、阴影延展、颜色
## Border-radius —— 盒子边缘样式
border-top-right-radius —— 右上角（其他同理）</br>
radius —— 半径 —— 数值越大，圆角程度越大 —— 如为两个数字，则代表圆角横向值和圆角纵向值</br>
*快捷方式*</br>
border-radius:左上 右上 右下 左下
## List-style-type —— 项目符号
*li*元素的符号</br>
### UL —— 无序
circle —— 空心圆圈</br>
square —— 实心方块</br>
### OL —— 有序
decimal —— 阿拉伯数字</br>
lower-alpha —— 小写英文字母</br>
upper-alpha —— 大写英文字母</br>
lower-roman —— 小写罗马数字</br>
upper-roman —— 大写罗马数字</br>
### List-style-image —— 选择自己喜欢的图像
```list-style-image:url("")```
### List-style-position —— 定位
标记默认位于左侧</br>
list-style-position:outside —— 标记位于文本块左侧</br>
list-style-position:inside —— 标记位于文本块内部同时文本缩进</br>
*快捷方式*</br>
```list-style:位置 项目符号样式```</br>
## Table —— 表格样式
width —— 表格宽度</br>
padding —— 每个单元格边框与内容间的距离</br>
text-align —— 对齐方式</br>
background-color —— 表格背景颜色</br>
:hover —— 光标悬停在某一行时将该行强调显示</br>
text-transform —— 表格标题中的内容转为大写</br>
border:数值 样式 颜色 —— 单元格的边框</br>
border-spacing:单元格间的横向距离 单元格间的纵向距离</br>
border-collapse:collapse —— 相邻边框合并</br>
border-collapse:separate —— 相邻边框分离</br>
### Empty-cells —— 空单元格
empty-cells:hide —— 隐藏空单元格的边框</br>
empty-cells:show —— 显示空单元格的边框</br>
## Input —— 单行文本框样式
:focus —— 用户使用文本框时改变颜色</br>
其他属性类似</br>
## Botton —— 按钮样式
color —— 按钮上文本的颜色</br>
text-shadow —— 在支持该属性的浏览器中展示3D效果的文本</br>
background-color —— 按钮的背景颜色</br>
## Cursor —— 光标样式
default —— 箭头（常见）</br>
auto —— I形</br>
crosshair —— 十字</br>
pointer —— 手状</br>
wait —— 加载圆圈</br>
help —— 带问号的箭头</br>
## ID选择器
以井号#为选择符号。id名具有唯一性，不能相同
## * —— 通配符
```*_{margin:0;padding:0;}```去掉浏览器的默认边距</br>
## 标签选择器
```p{color:blue}```</br>
大部分html的元素都可以是标签选择器</br>
## Opacity —— 图像透明度
0.0 ~ 1.0 —— 值越小，越透明 —— img{}
## Float —— 浮动
```<style>```</br>
```div{width:100px;```</br>
```height:100px;```</br>
```text-align;}```</br>
```<!--id为1的选择器右浮，至包含块的边缘-->```</br>
```#first{float:right;}```</br>
```</style>```</br>
```<div id="first" style="background:blue"></div>```</br>
```<div id="second" style="background:red"></div>```</br>
```<div id="third" style="background:yellow"></div>```</br>
</br>
当一个元素浮动时，浏览器会把该元素原来占的位置的高度视为0，后面的元素会占据该元素原来的位置以及产生元素重叠；但若同为浮动块，则不会重叠而是碰到即止</br>
## Background-image —— 背景图像
当背景图较小，不能填充整个页面时，浏览器会自动重复图片以充满</br>
background-repeat:no-repeat/repeat-x/repeat-y —— 不重复图片/在水平方向上平铺/在竖直方向上平铺</br>
background-position:top/bottom/left/right/center —— 位置，可以写两个定位关键词</br>
每个元素都可以设置背景图</br>

