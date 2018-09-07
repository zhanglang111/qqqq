

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

