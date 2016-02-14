---
layout: post
title:  "How To Output Data In JavaScript"
date:   2016-02-12 18:30:24 -0800
categories: JavaScript
---

As many other programming languages JavaScript does'nt have any built-in functions to display data. but there are some ways to display data in JavaScript. let's see how to do that.
<!--more-->

## Few ways to display JavaScript data

* window.alert()
* document.write()
* innerHTML
* console.log()

## Using window.alert()

You can use JS built-in alert functionality to display data.

{% highlight javascript %}
<script>
window.alert('fuckedupguy here!');
</script>
{% endhighlight %}

## Using document.write()

Executing document.write() method after fully loaded HTML can delete all existing HTML.

{% highlight javascript %}
<script>
document.write('fuckedupguy here!');
</script>
{% endhighlight %}

## Using innerHTML

You can use innerHTML property to set HTML values to any selected HTML element. for select HTML element, simply we can use <code>document.getElementById()</code> method. 

{% highlight html %}
<!DOCTYPE html>
<html>
<body>

<p id="box"></p>

<script>
document.getElementById("box").innerHTML = 'fuckedupguy here!';
</script>

</body>
</html>
{% endhighlight %}

## Using console.log()

We can use <code>console.log()</code> method to output values into web browser console. to view browser console, simply press <kbd>F12</kbd> and select console tab/window.

{% highlight javascript %}
console.log('fuckedupguy here!');
{% endhighlight %}

This is how console window display values when you use <code>console.log()</code> method in your JavaScript code.

<img src="assets/img/2016/feb/chrome_browser_console_window.jpg" alt="Chrome Web Browser Console Window">