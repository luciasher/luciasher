---
layout: post
title: Lucia's Example Post
subtitle: here we go
gh-repo: daattali/beautiful-jekyll
gh-badge: [Lucia, hey, good morining]
bigimg: /img/SSC_0345.jpg
image: /img/8.216976.jpg
tags: [test]
comments: true
---

You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**GOOD MORNING!**

## My name is Lucia, but my nickname is Lurch. 

Here's a useless table:

| Siblings | Name | Age |
| :------ |:--- | :--- |
| 1 | Phoebe | 10 |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .center-block :}

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

### Photo Credits

{: .box-note}
**Photo Credit:** This is a notification box.

