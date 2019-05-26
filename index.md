---
title: Hello, 龍的博客
---

{{ page.title }}

---
### 过分谦虚，其实是一种傲娇。    --- 雷总
---
### 错也是一种对。    --- 宋总
---
### 乐人之乐，人亦乐其乐。    --- 小邱总
---
### 你大爷始终是你大爷。    --- 王总
---



{% for post in site.posts %}
{{ post.date|date_to_string }} <a href='{{ site.baseurl }}{{ post.url }}'>{{ post.title }}</a>
{% endfor %}


### Markdown


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for


```markdown

# HI！
## I am Lulongfei
### 来我们一起搞点事情吧 

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

 ![Image](https://spring-packer.github.io/parker/imgs/1.jpg)

1. 第一篇文章 [文章一](https://spring-packer.github.io/parker/2019/05/21/%E7%AC%AC%E4%B8%80%E7%AF%87%E6%96%87%E7%AB%A0.html)

2. 第二篇文章 [文章二](https://spring-packer.github.io/parker/2019/05/21/%E7%AC%AC%E4%B8%80%E7%AF%87%E6%96%87%E7%AB%A0.html)


### 最是一年春好处，绝胜烟柳满皇都


