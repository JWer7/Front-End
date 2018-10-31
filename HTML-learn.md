# Websites
* https://www.w3schools.com/</br>
* https://www.coding61.com</br>
* http://www.runoob.com/
***
# Introduction
Hyper Text Markup Language
***
# HTML TAG ( Makeup Tag )
成对 — 开始标签&结束标签
</br>
## Heading — 标题   
```<h1>......</h1>```  *字号随数字增大而减小*
## Paragraph — 段落
```<p>......</p>```
### Italic — 斜体
```<i>......</i>```
### Bold — 粗体
```<b>......</b>```
## Break — 换行
```<br/>```
## Preformatted — 限定形式
```<pre>......</pre>```
## Horizontal — 水平线
```<hr/>```
## 插入图片
```<img src="......"/>```
## Ordered List — 有序列表
```<ol>```
```<li>......</li>```
```</ol>```
## Unordered List — 无序列表
```<ul>```
```<li>......</li>```
```</ul>```
## Definition List — 定义列表
```<dl>```
```<dt>被定义的词</dt>```
```<dd>定义</dd>```
```</dl>```
## 添加链接
```<a href="......"target="_blank">文字</a>```
## 添加视频/音频
```<video src="......"></video>```</br>
```<audio src="......"></audio>```</br>
```preload="none"```  *用户按下播放按钮后，浏览器再加载视频*</br>
```preload="auto"```  *浏览器在页面加载时载入视频*</br>
```preload="metadata"```  *页面加载后仅加载音频或视频的元数据*</br>
```controls```  *浏览器需提供默认播放插件*</br>
```loop```  *视频结束后重新反复播放/轮播*</br>
```autoplay```  *自动播放*</br>
```<video src="......" preload="......" controls loop></video>```  *音频同理*
## 注释
```<!--......-->```  *不写注释会被大魔王掳走喔*
## 块级元素 
```<div>......</div>```
## 表格
```<table>```</br>
```<tr>```</br>
```<th>......</th>```  *表头字体自动加粗*</br>
```<td>......</td>```</br>
```</tr>```</br>
```</table>```
## 表单
```<label>......</label>```  *标签*</br>
```<input type="text" name="username" maxlength="30"/>```</br>
*单行输入框  信息输入点（可写可不写）  最大字符输入量（默认20字符）*</br>
```<input type="password" name="password" maxlength="30"/>```  *密码框*</br>
```<textarea name="......" cols="......" rows="......">......</textarea>```</br>
*文本域/多行文本框  宽度  高度（纵向上占据的行数）*
## 下拉列表框
```<select name="......">``` *控件名称*</br>
```<option value="......" selected="selected">......</option>```  *选项的值*</br>
```</select>```
## 复选框
```<input type="checkbox" name="......" value="......" checked="checked"/>......```
## Button — 按钮
```<button>......</button>```
## 转义字符
## 完整结构
```<!doctype html>```  *不同版本*</br>
```<html lang="en" class="......">```</br>
```<head>```</br>
```<title>......</title>```</br>
```</head>```</br>
```<body>......</body>```</br>
```</html>```
