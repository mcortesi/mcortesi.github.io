---
layout: post
title: "Functional Programming: On Pure Functions"
excerpt: "Why pure functions are important? How and When to use them."
tags: [functional programming]
modified: 2015-06-20
comments: true
image:
  feature: backgrounds/flor-bsas.jpg

---

### Examples on pure and impure functions

{% highlight js %}
function pure(a, b) {
  return a + b;
}

var b = 5;
function impure(a) {
  return a + b;
}

var obj = {
  impure: function(a) {
    return this.b + a;
  }
  b: 5
}
{% endhighlight %}
