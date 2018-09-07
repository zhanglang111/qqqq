# qqqq
<!DOCTYPE html>
<html>
<head>
<title>MarkdownPad Document</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<style type="text/css">
/* GitHub stylesheet for MarkdownPad (http://markdownpad.com) */
/* Author: Nicolas Hery - http://nicolashery.com */
/* Version: b13fe65ca28d2e568c6ed5d7f06581183df8f2ff */
/* Source: https://github.com/nicolahery/markdownpad-github */

/* RESET
=============================================================================*/

html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
}

/* BODY
=============================================================================*/

body {
  font-family: Helvetica, arial, freesans, clean, sans-serif;
  font-size: 14px;
  line-height: 1.6;
  color: #333;
  background-color: #fff;
  padding: 20px;
  max-width: 960px;
  margin: 0 auto;
}

body>*:first-child {
  margin-top: 0 !important;
}

body>*:last-child {
  margin-bottom: 0 !important;
}

/* BLOCKS
=============================================================================*/

p, blockquote, ul, ol, dl, table, pre {
  margin: 15px 0;
}

/* HEADERS
=============================================================================*/

h1, h2, h3, h4, h5, h6 {
  margin: 20px 0 10px;
  padding: 0;
  font-weight: bold;
  -webkit-font-smoothing: antialiased;
}

h1 tt, h1 code, h2 tt, h2 code, h3 tt, h3 code, h4 tt, h4 code, h5 tt, h5 code, h6 tt, h6 code {
  font-size: inherit;
}

h1 {
  font-size: 28px;
  color: #000;
}

h2 {
  font-size: 24px;
  border-bottom: 1px solid #ccc;
  color: #000;
}

h3 {
  font-size: 18px;
}

h4 {
  font-size: 16px;
}

h5 {
  font-size: 14px;
}

h6 {
  color: #777;
  font-size: 14px;
}

body>h2:first-child, body>h1:first-child, body>h1:first-child+h2, body>h3:first-child, body>h4:first-child, body>h5:first-child, body>h6:first-child {
  margin-top: 0;
  padding-top: 0;
}

a:first-child h1, a:first-child h2, a:first-child h3, a:first-child h4, a:first-child h5, a:first-child h6 {
  margin-top: 0;
  padding-top: 0;
}

h1+p, h2+p, h3+p, h4+p, h5+p, h6+p {
  margin-top: 10px;
}

/* LINKS
=============================================================================*/

a {
  color: #4183C4;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* LISTS
=============================================================================*/

ul, ol {
  padding-left: 30px;
}

ul li > :first-child, 
ol li > :first-child, 
ul li ul:first-of-type, 
ol li ol:first-of-type, 
ul li ol:first-of-type, 
ol li ul:first-of-type {
  margin-top: 0px;
}

ul ul, ul ol, ol ol, ol ul {
  margin-bottom: 0;
}

dl {
  padding: 0;
}

dl dt {
  font-size: 14px;
  font-weight: bold;
  font-style: italic;
  padding: 0;
  margin: 15px 0 5px;
}

dl dt:first-child {
  padding: 0;
}

dl dt>:first-child {
  margin-top: 0px;
}

dl dt>:last-child {
  margin-bottom: 0px;
}

dl dd {
  margin: 0 0 15px;
  padding: 0 15px;
}

dl dd>:first-child {
  margin-top: 0px;
}

dl dd>:last-child {
  margin-bottom: 0px;
}

/* CODE
=============================================================================*/

pre, code, tt {
  font-size: 12px;
  font-family: Consolas, "Liberation Mono", Courier, monospace;
}

code, tt {
  margin: 0 0px;
  padding: 0px 0px;
  white-space: nowrap;
  border: 1px solid #eaeaea;
  background-color: #f8f8f8;
  border-radius: 3px;
}

pre>code {
  margin: 0;
  padding: 0;
  white-space: pre;
  border: none;
  background: transparent;
}

pre {
  background-color: #f8f8f8;
  border: 1px solid #ccc;
  font-size: 13px;
  line-height: 19px;
  overflow: auto;
  padding: 6px 10px;
  border-radius: 3px;
}

pre code, pre tt {
  background-color: transparent;
  border: none;
}

kbd {
    -moz-border-bottom-colors: none;
    -moz-border-left-colors: none;
    -moz-border-right-colors: none;
    -moz-border-top-colors: none;
    background-color: #DDDDDD;
    background-image: linear-gradient(#F1F1F1, #DDDDDD);
    background-repeat: repeat-x;
    border-color: #DDDDDD #CCCCCC #CCCCCC #DDDDDD;
    border-image: none;
    border-radius: 2px 2px 2px 2px;
    border-style: solid;
    border-width: 1px;
    font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
    line-height: 10px;
    padding: 1px 4px;
}

/* QUOTES
=============================================================================*/

blockquote {
  border-left: 4px solid #DDD;
  padding: 0 15px;
  color: #777;
}

blockquote>:first-child {
  margin-top: 0px;
}

blockquote>:last-child {
  margin-bottom: 0px;
}

/* HORIZONTAL RULES
=============================================================================*/

hr {
  clear: both;
  margin: 15px 0;
  height: 0px;
  overflow: hidden;
  border: none;
  background: transparent;
  border-bottom: 4px solid #ddd;
  padding: 0;
}

/* TABLES
=============================================================================*/

table th {
  font-weight: bold;
}

table th, table td {
  border: 1px solid #ccc;
  padding: 6px 13px;
}

table tr {
  border-top: 1px solid #ccc;
  background-color: #fff;
}

table tr:nth-child(2n) {
  background-color: #f8f8f8;
}

/* IMAGES
=============================================================================*/

img {
  max-width: 100%
}
</style>
</head>
<body>
<h1>git使用技巧</h1>
<h2>1.</h2>
<ul>
<li>mkdir 新建一个工作文档</li>
<li>cd 进入子目录</li>
<li>pwd 显示路径</li>
</ul>
<h2>2.</h2>
<ul>
<li><a href="www.baidu.com">git add</a></li>
<li>git commit </li>
</ul>
<h2>3.</h2>
<ul>
<li>git log</li>
<li>git log --pretty=oneline</li>
<li>git reflog</li>
</ul>
<h2>4.</h2>
<ul>
<li>git reset --hard head</li>
<li>git reset --hard head^^</li>
</ul>
<h2>5.</h2>
<ol>
<li>先修改某个文件 </li>
<li>再git add</li>
<li>发现现在并不能checkout,原因是checkout是用在add之前的</li>
<li>现在的方法是回退:git reset head 此文件名称</li>
<li>再git checkout 此文件名称</li>
</ol>
<h2>6.</h2>
<h3>解决git remote push orgin 总是显示登录git的问题</h3>
<blockquote>
<p>git remote rm origin</p>
<blockquote>
<p>git remote add origin https://zhanglang111:FURONG...15228509303@github.com/zhanglang111/studygit.git</p>
</blockquote>
</blockquote>
<hr />
<hr />
<h2>这是UDP通信的代码</h2>
<p><code>function fun(){
         echo &quot;这是一句非常牛逼的代码&quot;;
    }
    fun();</code></p>
<h2>7.表达感受</h2>
<p>今天是第一天编辑文档，很开心
<img src="https://image.baidu.com/search/detail?ct=503316480&amp;z=0&amp;ipn=d&amp;word=github&amp;step_word=&amp;hs=0&amp;pn=1&amp;spn=0&amp;di=11787571730&amp;pi=0&amp;rn=1&amp;tn=baiduimagedetail&amp;is=0%2C0&amp;istype=0&amp;ie=utf-8&amp;oe=utf-8&amp;in=&amp;cl=2&amp;lm=-1&amp;st=undefined&amp;cs=3018925442%2C793684611&amp;os=2361203686%2C3671564774&amp;simid=3240026234%2C182033702&amp;adpicid=0&amp;lpn=0&amp;ln=1786&amp;fr=&amp;fmq=1536288555354_R&amp;fm=&amp;ic=undefined&amp;s=undefined&amp;se=&amp;sme=&amp;tab=0&amp;width=undefined&amp;height=undefined&amp;face=undefined&amp;ist=&amp;jit=&amp;cg=&amp;bdtype=0&amp;oriquery=&amp;objurl=http%3A%2F%2Fstatic.movingpackets.net%2F2013%2F12%2Fgithub-logo-transparent.jpg&amp;fromurl=ippr_z2C%24qAzdH3FAzdH3F45etg2rwvhjpf_z%26e3BgjpAzdH3Fda8cAzdH3FadAzdH3FacAzdH3Fu-fv6trp-g5o-2tpi7kAzdH3F&amp;gsm=0&amp;rpstart=0&amp;rpnum=0&amp;islist=&amp;querylist=" alt="v字仇杀" /></p>

</body>
</html>
<!-- This document was created with MarkdownPad, the Markdown editor for Windows (http://markdownpad.com) -->

