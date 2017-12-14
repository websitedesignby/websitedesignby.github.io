---
layout: post
title:  "Generate a WordPress administrator account"
date:   2017-12-14 07:19:53 -0500
categories: wordpress php programming
---
This script will generate an administrator account using the credentials and information defined in the variables. Simply update the variables below and upload, upload the script the the root of your WordPress site and visit the page in your browser.

{% highlight php %}
$username = "your-username"; // important!
$password = "your-password"; // important!
$user_email = "you@your-domain.com"; // important!
$user_nicename = "You";
$user_url = "http://www.your-domain.com";
$display_name = "Display Name";
{% endhighlight %}

Visit gist:

[generate-wp-admin.php](https://gist.github.com/websitedesignby/e0e0f379553bad3da9c59e12e4f4d9a4)


