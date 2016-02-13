---
layout: post
title:  "Just Another Testing Post"
date:   2016-02-10 17:31:24 -0800
categories: general
---

Just another testing post. :)

#### Image adding.
![annonymouse picture](assets/img/2016/feb/annonymous.jpg "Just a picture")

{% highlight php %}
function settings_save_alerts() {

	if (isset($_SESSION['settings_saved']) && $_SESSION['settings_saved'] === 'y') {
		echo '<h4 style="color:green">Settings saved.</h4>';
		unset($_SESSION['settings_saved']);
	}

	if (isset($_SESSION['settings_saved']) && $_SESSION['settings_saved'] === 'n') {
		echo '<h4 style="color:orange">Settings could not be saved.</h4>';
		unset($_SESSION['settings_saved']);
	}

}
{% endhighlight %}