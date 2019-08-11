---
title: How to change the fields of a "post"
date: 2019-08-11T01:04:33.864Z
description: I would like to turn posts into events.
---
I'm going to try to learn how to edit the fields in the netlify CMS - if it's even possible - to add the fields necessary for a calendar event system. I will be adding my findings to this post as I learn!

I started digging into the github repo and found this file, /blob/master/site/static/admin/config.yml. It looks very promising.

I need to line up the "Label", "Name" and "widget" values with fields in the CMS before I'll have confidence to make changes.

So I did it. I made a change that made no change. That's better than having it break the site!! [Here's my commit](https://github.com/kendalllindley/hugo-test-2/commit/e5583995ed9ee41dafa4493ecde8a3af00a302a4). It didn't add a field to the blog post in Netlify CMS automatically. I'm going to see if there's a way to get the CMS to have a field to populate the placeholder I made. 
