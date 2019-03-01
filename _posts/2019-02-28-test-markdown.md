---
layout: post
title: 测试 markdown
subtitle: 每一个帖子还有一个副标题
gh-repo: wzm19681003/wgit
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

你可以在这里写常规文字， Jekyll会自动将它转换成一个漂亮的网页 - 我强烈建议你花5分钟学习如何用markdown来写 - 它将教你如何将常规文本转换为粗体/斜体/标题/表格等。
**这是一些大胆的文字**

## 这是一些大胆的文字

这是一个无用的表：

| 数字 | 下一个数字 | 以前的数字 |
| :------ |:--- | :--- |
| 五 | 六 | 四 |
| 十 | 七 | 九 |
| 七 | 八 | 六 |
| 二 | 三 | 一 |


一个美味的绉纱怎么样？

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

这是一个代码块：

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

以下是语法高亮显示的相同代码：

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

以下是相同的代码，但排成一行：
{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## 盒子
您可以添加如下通知、警告和错误框：

### 通知

**{: .box-note}**
**注意：** 这是一个通知框。

### 警告

**{: .box-warning}**
**警告:** 这是一个警告框。

### Error

**{: .box-error}**
**错误:** 这是一个错误框。
