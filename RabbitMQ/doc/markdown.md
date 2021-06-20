[toc]
这边文章是介绍如何在 Markdown 中增加文献引用。[<sup>1</sup>](#refer-anchor-1)

# 1. Markdown画图 -- 流程图、序列图、饼图、甘特图
https://www.jianshu.com/p/77cc07f47cdc
# 2. Markdown之引用
## 2.1 Markdown通过链接引用

## 2.2 Markdown文本之间交叉引用
注意：csdn 不支持 md 的跳转，可以使用 [toc] 生成目录
[title](#3参考内容)

https://blog.csdn.net/qq_20515461/article/details/106809249
## 2.3 Markdown添加文献引用
**代码：**
```bash
## Markdown 增加文献引用

这边文章是介绍如何在 Markdown 中增加文献引用。[<sup>1</sup>](#refer-anchor-1)

## 参考

<div id="refer-anchor-1"></div>

- [1] [百度学术](http://xueshu.baidu.com/)

<div id="refer-anchor-2"></div>

- [2] [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)

```
**显示效果：**

Rabbit MQ

: 就是这样子


---
这边文章是介绍如何在 Markdown 中增加文献引用。[<sup>1</sup>](#refer-anchor-1)

 参考文献：
<div id="refer-anchor-1"></div>

- [1] [百度学术](http://xueshu.baidu.com/)
<div id="refer-anchor-2"></div>

- [2] [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)
---

# 3.参考内容
- [1] [Markdown 语法教程](https://markdown.com.cn/basic-syntax/links.html)

这里是另外一个教程[^1]

[^1]: 这是我的一个脚注