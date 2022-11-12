# HTML

## 一般结构

```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>replit</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
  Hello world
  <script src="script.js"></script>

  <!--
  This script places a badge on your repl's full-browser view back to your repl's cover
  page. Try various colors for the theme: dark, light, red, orange, yellow, lime, green,
  teal, blue, blurple, magenta, pink!
  -->
  <script src="https://replit.com/public/js/replit-badge.js" theme="blue" defer></script>
</body>

</html>
```

简化为：

```html
<!DOCTYPE html>
<html>

<head>
  <title>replit</title>
</head>

<body>
  Hello world
</body>

</html>
```

必要的要素：第一行的`<!DOCTYPE html>`声明该文件是一个html文件，head标签主要放一些样式的引入、编码格式、默认语言等；body标签内的东西则是我们要搞的主要部分。同时JavaScript也通常在这部分中引入。

head标签里面通过`link`标签和`href`引入样式文件`.css`，JavaScript脚本通过`script`标签和`src`引入脚本文件`.js`。上面两者可分别在`style`标签和`script`标签里写样式和脚本。



## 常用标签

| 标签                   | 说明                     | 举例                                              |
| ---------------------- | ------------------------ | ------------------------------------------------- |
| h1, h2, h3, h4, h5, h6 | 多级标题，最多六级       | `<h1>Header #1</h1> `<br>`<h2>Header #2</h2> `... |
| p                      | 段落标签，用来放段落文字 | `<p>这是一段文字</p>`                             |
| a                      | 超链接标签               | `<a href="www.baidu.com">Click</a>`               |
|                        |                          |                                                   |

<!-- 插入图片 -->

<div align=center>
<img width="550" src="../img/html/1.1.jpg"/>
</div>
<div align=center>test pic</div>

另一个图片

  









