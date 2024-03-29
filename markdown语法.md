>
> 以下内容均参考自网络整理，上传github验证.md排版效果
> [官方教程](https://markdown.com.cn/basic-syntax/headings.html)


# 1. MD（markdown）简介
## 1.1 markdown是什么？
一种只有4个基本标记符（*+->）的超简单的标记语言。

## 1.2 markdown用来做什么?
主要是解决文档快速排版和快速读取的问题（易写易读）。  
实现：快速梳理逻辑思路和文章层次

## 1.3 如何使用markdown?
编辑：记事本（我现在就是在用记事本编辑这份文档）  
读取：github、简书、有道云等可以呈现出美观的渲染样式

# 2. markdown语法
2.1 标题符号: \#  
代码：  
```
# 一级标题
## 二级标题
### 三级标题
# ...
```

效果：  
# 一级标题
## 二级标题
### 三级标题
# ...

2.2 基本符号：\*\+\-\>  
代码：  
`+ 标题（标题前有空格）`

效果：  
+ 标题

2.3 正文  
	换行后，直接写，无任何标识符号。

2.4 段落  
	插入一空白行，表示段落

2.5 字体样式  
- (1) 代码：`*倾斜*`  
   效果：*倾斜*


- (2) 代码：`**加粗**`  
   效果：**加粗**


- (3) 代码：`***倾斜并加粗***`  
   效果：***倾斜并加粗***

- (4) 代码：`~~文字删除线~~`  
   效果： ~~文字删除线~~

2.6 引用  
- (1) 文字引用：  
``>这是一段引用内容,文字前无需加空格``  
``>>这是一段引用内容,文字前无需加空格``  
效果：
> 这是一段引用内容,文字前无需加空格 
>> 这是一段引用内容,文字前无需加空格


- (2) 行内代码引用：  
\`这是行内代码\`引用语法  
行内代码引用效果：   
`这是行内代码`引用语法

- (3) 块代码引用：  
\`\`\`  
代码1      
代码2    
代码3    
\`\`\`      
块代码引用效果：

	```
	代码1  
	代码2  
	代码3  
	```





