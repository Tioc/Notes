# 这是h1
## 这是h2
### 这是h3
#### 这是h4
##### 这是h5
###### 这是h6

>这是区块引用  
这是区块引用

>这是区块引用
>
>>这是区块引用嵌套
>
>这是区块引用

无序列表
* red
* green
* blue

+ red
+ green
+ blue

- red
- green
- blue

有序列表
1. red
2. green
3. blue

代码  
这是代码片段`printf()`哦.  
这是代码片段``printf(`)``哦.

代码块

    // 函数func...
    function func(){
        return "markdown";
    }
    
分割线

* * *

***

*****

- - -

---------------------------------------

链接  
This is [an example](http://example.com/ "Title") inline link.  
[This link](http://example.net/) has no title attribute.

This is [an example] [id] reference-style link.  
接着，在文件的任意处，你可以把这个标记的链接内容定义出来：  
  
  [id]: <http://example.com/>  "Optional Title Here"  
  
下面是一个参考式链接的范例：  
I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"
  
如果改成用链接名称的方式写：  
I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"
  
自动链接  
<http://example.com/>

强调  
*em*
_em_
**strong**
__strong__

行内式的图片语法：

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")

参考式的图片语法：

![Alt text][id]  

[id]: url/to/image  "Optional title attribute"

反斜杠  
Markdown 可以利用反斜杠来插入一些在语法中有其它意义的符号，例如：如果你想要用星号加在文字旁边的方式来做出强调效果（但不用 <em> 标签），你可以在星号的前面加上反斜杠：

\*literal asterisks\*  

Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：  
\\   反斜线  
\`   反引号  
\*   星号  
\_   底线  
\{}  花括号  
\[]  方括号  
\()  括弧  
\#   井字号  
\+   加号  
\-   减号  
\.   英文句点  
\!   惊叹号  