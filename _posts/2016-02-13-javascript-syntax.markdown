---
layout: post
title:  "JavaScript Syntax"
date:   2016-02-13 08:54:29 -0800
categories: JavaScript
---

If you write JavaScript codes, you must agree with some rules that JS built on. those rules are called JavaScript syntax. If you did something against of those rules, your JS code wont work. so let's learn JS syntax.
<!--more-->

## So what's we are gonna talk about

* JavaScript statements
* White spaces in JavaScript
* Values in JavaScript
* JavaScript variables
* JavaScript operators
* JavaScript expressions
* JavaScript keywords
* JavaScript comments
* JavaScript identifiers
* Indentifiers naming styles
* JavaScript Casesensitivity
* JavaScript character set

### JavaScript statements

Every JavaScript is created with set of instructions. those instructions are called JavaScript statements. every JS statement ended with semicolon(;). In JavaScript, ending statements with semicolon is <strong>not</strong> required. but it's better to use semicolons when terminating statements. it can avoids unnecessory errors in your JS code.

This is how JS statements can be terminated with semicolons.
{% highlight javascript %}
var num_one = 100;

var num_two = 120;

var sum = num_one + num_two;
{% endhighlight %}

### White spaces in JavaScript

White spaces like spaces, tags, newlines ignored by JavaScript interpreter when you those spaces between JS statements. so that's mean you can use those spaces to add more readability into your JS codes. but spaces in string values is not ignored by JS interpreter.

This JS code block is 100% identical to
{% highlight javascript %}
var num_one = 100;

var num_two = 120;

var sum = num_one + num_two;
{% endhighlight %}

This code block. because whites spaces are used between JS statements.
{% highlight javascript %}
var num_one = 100;var num_two = 120;var sum = num_one + num_two;
{% endhighlight %}

White spaces are matter in string values.
{% highlight javascript %}
var name = 'Hello Im  fucked    up          guy!';
{% endhighlight %}

The output of above JS code.
<pre><samp>Hello Im  fucked    up          guy!</samp></pre>

### Values in JavaScript

Values in JavaScript can be devided in to two main categories.

* Variables
* Literals

#### JavaScript Variables

Variables are containers for storing defferent type of data types. so variable values can be varying. that's why those containers are called variables. In JavaScript variables can be create/declare using <code>var</code> built-in JS keyword.

How to create a JS varible
{% highlight javascript %}
var name = 'fuckedupguy';
{% endhighlight %}

#### Literals

Literals are values, that we asign to variables. for example <code>'fuckedupguy'</code> is a string literal, <code>125</code> is a number literal A.K.A integer literal, <code>54.2</code> is a float/double literal. so those values not change themself.

### JavaScript variables

So we talk bit about JS varibles. but there is much to talk about JS variables. so let's talk about JS variable naming convension. and other stuff related to JS variables.

So when you naming a JS variable, you should follow below rules.

* Variable name only can be start with <b>letter</b>, <b>underscore(_)</b>, <b>dollor sign($)</b>
* Varible name cannot start with a number
* Variable names are case sensitive
* You can't use JS built-in keywords in JS variable names

I will update this post...