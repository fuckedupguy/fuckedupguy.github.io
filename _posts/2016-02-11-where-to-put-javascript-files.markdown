---
layout: post
title:  "Where To Put JavaScript Files"
date:   2016-02-11 09:58:51 -0800
categories: JavaScript
---

Now we know how to create a JavaScript files. let's learn how to use a JavaScript file in your website. to use JS file with our website, we need to include that JS file in your website.
<!--more-->

We can do this by two methods.

* Putting JS code directly inside HTML document.
* We can call JS file as a external file.

If you are gonna put JavaScript directly inside of HTML file. you need to put all your JS code inside <code>&lt;script&gt;&lt;/script&gt;</code> HTML tags. sometimes you may saw <code>&lt;script type="text/javascript"&gt;&lt;/script&gt;</code> HTML script tags with <code>type="text/javascript"</code> attribute. If you want, you can use HTML script tags with this HTML attribute. but it's not necessary. because JavaScript is the default scripting language in HTML. you may know there are few different types of scripting languages on the web.

An example how we can use JS directly inside of HTML document.

{% highlight javascript %}
<script type="text/javascript">

document.write('Hello fuckedupguy!');

</script>
{% endhighlight %}

Let's see how you can call external JavaScript file into your HTML document. for that we need to use <code>&lt;script type="text/javascript"&gt;&lt;/script&gt;</code> HTML tag with <code>src=""</code> attribute.

An example about how we can call external JS file into our HTML document.

{% highlight javascript %}
<script type="text/javascript" src="your-external-js-file-path.js"></script>
{% endhighlight %}

Also you need to know we can use or call JS in HTML pretty much anywhare in the HTML document. that's mean, you can use JS insde HTML <code>&lt;head&gt;&lt;/head&gt;</code> tags and HTML <code>&lt;body&gt;&lt;/body&gt;</code> tags. but it's better to use all your external JS file right before the <code>&lt;/body&gt;</code> tag. It can help to HTML DOM to fully loaded before load all these JS files. that's can improve your website loading time. and It's better to put all your onpage JS into a external JS file. so it can help to add better seperation between JS and HTML. and when we use external files, the web browser can cash those files. so It can help to load your website fast. so that's it. now you know how to use/call JS into your website. and best practices when you do that.