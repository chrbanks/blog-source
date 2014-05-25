---
layout: post
title:  "Starting A New Blog With Jekyll"
date:   2014-05-25 10:46:00
categories: jekyll blog
---

This is a log of my experiences setting up a new blog with Jekyll.

I've been reading blogs for a long time.  It's a great way to learn and keep up with things.  I've also flirted with the idea of creating my own programming blog as a way to share information and improve my writing skills among other things.  At various points I would create accounts at free hosted blog sites, but I would never actually do anything with them, coming up with all sorts of excuses:

*  "What if I post something incredibly stupid?"
*  "What if I put a lot of effort into this and no one cares?"
*  "I prefer online anonymity"

Things like these have done nothing but prevent me from moving toward my goals. So recently I decided I was just going to push forward and start blogging.  Then it was time to figure out how I was going to do it.


# Why I Chose Jekyll

I looked into several tools to build a blog with, but settled on three to look into deeper: WordPress, Ghost, and Jekyll.  I spent several days after work researching them and comparing.  WordPress seemed like a lot more than I really need at the moment.  Ghost was similar.  I really didn't want to have to worry about databases, security, web hosting plans, etc. which led to me choosing Jekyll.  If there comes a point where Jekyll no longer meets my needs I'll see about something else.


# Installing Jekyll

Setting up a new blog was as simple as following the documentation's [Quick-start guide][quick-start].  This generated the default blog files, and after running the server I was able to see the blog in action locally.  The next step was to put the blog on [Github Pages][github-pages].

This is where I came across an issue.  Github pages doesn't yet support Jekyll 2.0.3, but this is what I downloaded.  So for now I'm pushing the build output to my [repository][my-repo].  Once Github Pages is updated to support the newer version I'll see about putting the source in the repository instead.


[quick-start]: http://jekyllrb.com/docs/quickstart/
[github-pages]: https://help.github.com/articles/using-jekyll-with-pages
[my-repo]: https://github.com/chrbanks/chrbanks.github.io
