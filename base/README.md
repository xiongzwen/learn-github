## 一、关于readme.md文件
README文件后缀名为md，md是markdown的缩写，markdown是一种编辑博客的语言。不过GitHub支持的语法在标准markdown语法的基础上做了修改，称为Github Flavored Markdown。 <br/>
- https://github.com/guodongxiaren/README
- http://wowubuntu.com/markdown/
- http://markdown.tw/
## 二、标题（#后面要空一格）
直接输入的文字就是普通文本,使用两个Tab符实现单行文本。使用回撤换行是不生效的，需要使用 \<br/> (如果要打出\<br/>需要在前面加上\反斜杠转义)。这些和html里面的标签很相像。 <br/>
可以用#表示几级标题，<br/>
例如：<br/>
# 一级标题 
## 二级标题  
### 三级标题  

## 三、插入图片
格式为  叹号! + 方括号[标识性的信息] + 括号(图片的URL "提示信息" ) 。
例如为图片加入超链接<br/>
\[![baidu]](http://baidu.com)  
\[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"<br/>
[![baidu]](http://baidu.com)  
[baidu](http://www.baidu.com/img/bdlogo.gif "百度Logo")
  
## 三、超链接
* 对于普通的链接，会自动变成可链接的形式的。例如http://liiqi.com/ 。
* 对于文字超链接，格式为 \[要链接的文字](链接的地址)  例如  \[我的博客](http://liiqi.com/ "点击进入") 就是[我的博客](http://liiqi.com/ "点击进入")
## 四、其他
### 1.圆角编号
编辑的时候使用星号\*可以实现前面第三条那种圆点，同样要注意的是星号\* 后面要有一个空格，否则显示为普通星号。在\*前面打tab键可以加入二级圆点和三级圆点
### 2.高亮
用` `包围一段话可以实现`高亮`显示，来起到突出强调的作用。注意这不是单引号，而是Tab上方，数字1左边的按键（注意使用英文输入法）
### 3.缩进
\>>树  <br/>
\>>>二叉树  <br/>
\>>>>平衡二叉树<br/>
就是<br/>
>>树 
>>>二叉树  
>>>>平衡二叉树
