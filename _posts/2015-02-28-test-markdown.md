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

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
