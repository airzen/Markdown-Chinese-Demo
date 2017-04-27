针对中文,演示Markdown的各种语法




  
大标题
===================================

	大标题
	===================================

  大标题一般显示工程名,类似html的\<h1\><br />
  你只要在标题下面跟上=====即可

  
中标题
-----------------------------------

	中标题
	-----------------------------------

  中标题一般显示重点项,类似html的\<h2\><br />
  你只要在标题下面输入------即可
  
### 小标题

	### 小标题

  小标题类似html的\<h3\><br />
  小标题的格式如下 ### 小标题<br />
  注意#和标题字符中间要有空格

### 注意!!!下面所有语法的提示我都先用小标题提醒了!!! 

### 单行文本框
    这是一个单行的文本框,只要两个Tab再输入文字即可`sd`

### airzen 补充的知识要点 

#### #号可以认为是H
> 一个#可以认为是H1，两个#可以认为是H2，依次排开

#### 上面提到的单行文本或多行文本以两个Tab 起始，其实据我研究用四个半角空格也是可以的
> !!两个tab 其实可以认为是四个半角空格也可以

#### 段落中 需要特殊包起来的重点强调的词可以用 esc 下方的那个键半角字符包起来，比如下面 凤姐 两个字 `凤姐`

比如 `凤姐` 拿到了绿卡，哈哈。

### 多行文本框  
    这是一个有多行的文本框
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可
    这里你可以输入一段代码

### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧
    public class HelloWorld {

      /**
      * @param args
	    */
	    public static void main(String[] args) {
		    System.out.println("HelloWorld!");

	    }

    }

### 文字被些字符包围

	> 文字被些字符包围
	>
	> 只要再文字前面加上>空格即可
	>
	> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
	> 但> 只能放在行首才有效

> 文字被些字符包围
>
> 只要再文字前面加上>空格即可
>
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
> 但> 只能放在行首才有效

### 文字被些字符包围,多重包围

	> 文字被些字符包围开始
	>
	> > 只要再文字前面加上>空格即可
	>
	>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
	>
	> > > > 但> 只能放在行首才有效

> 文字被些字符包围开始
>
> > 只要再文字前面加上>空格即可
>
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
>
> > > > 但> 只能放在行首才有效

### 特殊字符处理
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>



* 在行首加点

行首输入*，空格后输入内容即可
    
### 段落中重点加粗的文本，用 `**` 与 `**` 包起来

	我的名字叫 **airzen** 喜欢看 **毛片**, 哈哈。

我的名字叫 **airzen** 喜欢看 **毛片**, 哈哈。

### 表格 


	|ID |公司 | 简介 |
	|-----|------|------|
	|[@w3c中国](http://weibo.com/w3cchina)|#|万维网联盟中国办事处官方微博|
	|[@TheFrontEnd](http://weibo.com/javascriptdev)|#|JavaScript技术资讯、新闻、教程、深度文章。|
	|[@前端快爆](http://weibo.com/fekb)|阿里巴巴|有HTML5、CSS3、JS |
	|[@HTML5中国](http://e.weibo.com/html5cn)|#|中国www.html5cn.org官方微博|
	|[@developerWorks](http://weibo.com/developerworks)|#|#|

如下

|ID |公司 | 简介 |
|-----|------|------|
|[@w3c中国](http://weibo.com/w3cchina)|#|万维网联盟中国办事处官方微博|
|[@TheFrontEnd](http://weibo.com/javascriptdev)|#|JavaScript技术资讯、新闻、教程、深度文章。|
|[@前端快爆](http://weibo.com/fekb)|阿里巴巴|有HTML5、CSS3、JS |
|[@HTML5中国](http://e.weibo.com/html5cn)|#|中国www.html5cn.org官方微博|
|[@developerWorks](http://weibo.com/developerworks)|#|#|

### 表格对齐
表格
====================
	|字段1|字段2|字段3|
	|---|:---:|---:|
	|默认我是左对齐|我是居中对齐|我是右对齐|

如下

|字段1|字段2|字段3|
|---|:---:|---:|
|默认我是左对齐|我是居中对齐|我是右对齐|

### 链接
	[我是链接文本](http://www.xx.com)

[我是链接文本](http://www.xx.com)


### 只是显示图片 
    ![github](http://github.com/unicorn.png "alt 提示") 
    
![github](http://github.com/unicorn.png "alt 提示")  
  
### 想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com  

	[![image]](http://www.github.com/)  
	[image]: http://github.com/github.png

[![image]](http://www.github.com/)  
[image]: http://github.com/github.png

#### 超链接
[我是超链接 指向baidu](http://www.baidu.com)

#### 我是图片

![image1](http://note.youdao.com/iyoudao/wp-content/themes/youdao2012/images/header-s8b121c3b5e.png)


#### 下面这个图片带链接 （也就是超链接与图片的合体）

[![image1](http://note.youdao.com/iyoudao/wp-content/themes/youdao2012/images/header-s8b121c3b5e.png)](http://www.youdao.com )

#### 段落中链接引用 

> 形式为 [文字][链接标识符]

> 链接标识符**不区分大小写** 字母，数字，空白和标点符号

I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][3]. [Google][1] 

[1]: http://google.com/        "Google 这里是alt值" 
[2]: http://search.yahoo.com/  "Yahoo Search" 
[3]: http://search.msn.com/    "MSN Search"

> 以上形式必须要注意的是正文与链接 之间必须要有一个空行

>也可以用以下语法来 推荐还是用上面的语法

I get 10 times more traffic from [Google][] than from [Yahoo][] or [MSN][].  

[Google]: http://google.com/        "Google 这里是alt值" 
[Yahoo]: http://search.yahoo.com/  "Yahoo Search" 
[MSN]: http://search.msn.com/    "MSN Search"

#### 图片 

``` 
![Alt text](/path/to/img.jpg "Optional title")

```
### 图片指定 
```
![Alt text][id]

[id]: url/to/image  "Optional title attribute"
```

### 所以对于图片链接的混合体就是
```
[图片代码](链接 "title")

展开后如下

[![Alt text](/path/to/img.jpg "Optional title")](链接 "title")
```

### 自动链接 邮件也如此
<http://baidu.com>
<39192170@qq.com>

#### 转义语法 
Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：

```
\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
```

