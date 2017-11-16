---
layout: post
title:  "What is robots.txt?"
author: Sara V
date:   2017-11-15 04:37:11 -0600
categories: jekyll update
permalink: /robotstxt/
---

In the file robots.txt you can add information to serachspiders and robots  about what information they can acess from your site. In the textfile you write plain text that lets the robots know what folder or pages that are not allowed for them to visit.

For the robots.txt file to work you place it in the projects root directory and specify the preferences you want.
You can customise the info for different robots or implement the same rules for them all or choose to not have any limits at all.

To allow all search spiders free acess to all pages you specify:

>User-agent: *  
>Disallow:

And to disallow all spiders from every pages:

>User-agent: *   
>Disallow: /

You can find more info [here](http://www.robotstxt.org/){:target="_blank"}

For my site i used the disallow all syntax.