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


###链接
	[我是链接文本](http://www.xx.com)

[我是链接文本](http://www.xx.com)


###只是显示图片 
    ![github](http://github.com/unicorn.png "alt 提示") 
    
![github](http://github.com/unicorn.png "alt 提示")  
  
###想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com  

	[![image]](http://www.github.com/)  
	[image]: http://github.com/github.png

[![image]](http://www.github.com/)  
[image]: http://github.com/github.png
