---
layout: post
title: "Hello World!"
tagline: "a brief introduction to this blog."
description: "A brief introduction to this blog."
category : general
tags : [hello, first, introduction]
---
{% include JB/setup %}

###Who is this guy?###

Hey guys, so here i go with the infamous 'first post' as it where. After a very inspiring talk from [@rem](https://twitter.com/rem) today at Uni, i felt compelled towards finally ticking off that one thing on my 'to-do list' that i never quite got round to doing - set up a blog.

Fist of all an introduction to myself.. I am Gavin Owen, a Web Technologies student at the University of Portsmouth in the UK. Since i was first inspired at a young age by a member of my family, i have always been fascinated by computers and more namely the web. However i never took the liberty to actually  contributing to this until more recently when. I started out by learning some basic static HTML followed by some python 3.0 and since then i have been hooked.

I will be using this blog as a medium for me to document my journey into the world wide web. So i guess i will start by talking about this blog and the choices i had to make to join the world of blogging..

###Why Jekyll? ###

Well.. when i first decided i was going to jump on the blogging bandwagon, i thought to myself "what am i really looking to achieve here" and what do i want from my chosen blogging engine/cms, the main things i decided that i wanted where as follows..

- Something super lightweight
- An engine where there is plenty of room for hacking and tinkering

So, after this i went about looking at a bunch of different blogging platforms, the most obvious being wordpress, blogger and tumblr, however i decided that all of these would be too much for me and each had their own issues. I then looked deeper into the market and started to stumble on some more niche platforms, although not choosing to use it, one of the most notable platforms was [calepin](http://calepin.co), calepin is very different to the likes of wordpress and more traditional cms style blogging platforms in the way that it works. Calepin is presented to the end user as a DropBox app. Once installed, Calepin looks in a specific directory within the said dropbox account for .md files (being a bit of a markdown evangelist this really appealed to me) it then passes these files through the [Pelican engine](http://pelican.readthedocs.org/en/3.1.1/) to generate a static html version of the post. However, the main thing that put me off of this service was the lack of control that would be given to me as a user, and i understant, that for all good intents and purposes that this is not a design fault and more a design feature. Calepin is noted for its simplicity and if you just want to write and post with ease, then Calepin is perfect for you.

So after my realisation that i could blog in markdown, i thought maybe there is another service that lets me do this, but also lets me hack around a lot more. At this point i stumbled upon [Jekyll](https://github.com/mojombo/jekyll). Jekyll is somewhat different to the traditional blogging platform in the way that it works, in the readme provided on the ithub repository it is described as *a simple, blog aware, static site generator*. Jekyll doesn't run on a database system, making it extremely lightweight and all that is needed from the bloggers end is a server that supports ruby, even this is little fo a problem for most as github offer free hosting for users.

So after about an hour or so of wrestling with ruby to install [DevKit](https://github.com/oneclick/rubyinstaller/wiki/development-kit) on my windows machine and the required gems, here i am writing that first post. For those who are interested, you can find a bit more info about Jekyll and how it works over at their [Github Repo](https://github.com/mojombo/jekyll). There is also a really nice guide written by Jade Dominguez on [how to set up Jekyll with a Twitter bootstrap front end](http://jekyllbootstrap.com/).




