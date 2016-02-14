---
layout: post
title:  "All About Markdown Syntax"
date:   2016-02-13 09:34:54 -0800
categories: Markdown
---

Will update this post
<!--more-->

* Headers

### Headers

Markdown supports two style of headers

1. [Setext style headers](#setext-style-headers)
2. [Atx style headers](#atx-style-headers)

#### Setext style headers

There are two types of setext style headers

1. [First level headers (H1)](#first-level-setext-headers-h1)
2. [Second level headers (H2)](#second-level-setext-headers-h2)

##### First level setext headers (H1)

First level <b>setext</b> headers can be created using <strong>underlined</strong> <strong>equel signs (=)</strong>.

For example:

<pre>
	<code>
This is a H1 header
===================
	</code>
</pre>

Will display like:

<img src="assets/img/2016/feb/h1_header.jpg" alt="H1 Header">

##### Second level setext headers (H2)

Second level <b>setext</b> headers can be created using <strong>underlined</strong> <strong>dashes</strong>.

For example:

<pre>
	<code>
This is a H2 header
-------------------
	</code>
</pre>

Will display like:

<img src="assets/img/2016/feb/h2_header.jpg" alt="H2 Header">

<p><mark><strong>Any number of underlining =’s or -’s will work.</strong></mark></p>

#### Atx style headers

You can create atx style header using 1-6 hash/pound sign (#) at the beginning of the header text, number of hash signs corresponding to header levels 1-6.

For example:

<pre>
	<code>
# Header level one - H1

## Header level two - H2

### Header level three - H3

#### Header level fore - H4

##### Header level five - H5

###### Header level six - H6
	</code>
</pre>

Output will be like this:

<img src="assets/img/2016/feb/1_6_html_headers.jpg" alt="1 to 6 HTML headers">

If you want, optionally you can <b>close</b> atx style headers. you can do that if you think it's looks clean. The closing shash signs (#) don't even need to be match the number of hashes used to start the header text. The number of starting hashes will determines the header level.

The optional way to create atx style headers.

<pre>
	<code>
# Header level one - H1 #

## Header level two - H2 ##

### Header level three - H3 ###

#### Header level fore - H4 ############

##### Header level five - H5

###### Header level six - H6 #
	</code>
</pre> 

Output will be the same:

<img src="assets/img/2016/feb/1_6_html_headers.jpg" alt="1 to 6 HTML headers">

* * *