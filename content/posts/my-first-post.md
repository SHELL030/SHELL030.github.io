+++
date = '2024-10-23T14:39:50+08:00'
draft = true
title = 'My First Post'
categories = ["通用技术"]
tags = ["博客搭建", "Bilibili"]
+++

这是第一篇文章。

行内数学公式：$a^2 + b^2 = c^2$。

块公式，

$$
a^2 + b^2 = c^2
$$

<div>
$$
\boldsymbol{x}_{i+1}+\boldsymbol{x}_{i+2}=\boldsymbol{x}_{i+3}
$$
</div>

公式中有超过三个大括号，渲染就会出问题，所以要div

```css
.post-content pre,
code {
  font-family: "JetBrains Mono", monospace;
  font-size: 1rem;
  line-height: 1.2;
}
```