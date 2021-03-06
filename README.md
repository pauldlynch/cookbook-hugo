Cookbook
========

Hugo based html content for my cookbook recipes.

I wrote these recipes originally for my son Andrew, when he went away
to college.  I extended them when my youngest son, Christopher, went
to university, and have added to them when I wanted to, or when I was
asked to.

The first of these are Pages documents shared on
[iWork.com](http://iwork.com), and can be viewed, downloaded in
various formats and printed; most of them are sitting on this web
site. The basic idea is to create a collection of student friendly
recipes that are nutritious, cheap to make and simple to prepare, but
there may have been some scope creep.

Good luck!

Feel free to share this page with anyone.

This site is built using [Hugo](https://gohugo.io) with the [Mainroad theme](https:/go/hugo.io/mainroad/), with some improvements from [Chris Titus](https://christitus.com/hugo-guide/), which I used to modify the taglist.html widget.

The dates on the posts for most of the pages are from when I restored
from a backup after a web site problem.  

The run the site, first install Hugo.  cd into the cookbook folder, and type:

`hugo server`

Open with a web browser `http://localhost:1313`.

I've provided a deploy script (set to my site, so CHANGE IT!).  run it as:

`./deploy`




The current site is built
using [Jekyll](http://jekyllrb.com/) and
[Jekyll-Bootstrap](http://jekyllbootstrap.com/); an older version was
hosted via my web site and a [WordPress](http://wordpress.org) blog,
with [AutoIndex](http://autoindex.sourceforge.net/) used to just list
the text files containing the recipes.

Build & deploy instructions:

For Jekyll 1.2:

    jekyll build; rake rsync:live 

For old, pre-1.0 Jekyll:

    jekyll --no-auto --no-server; rake rsync:live
