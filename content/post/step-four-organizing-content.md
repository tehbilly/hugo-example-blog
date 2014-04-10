---
title: "Step Four: Organizing Content"
description: "Indexes? Okay."
date: "2014-04-08"
categories:
  - "tutorial"
tags:
  - "example"
  - "hugo"
  - "blog"
  - "indexes"
---

[clowder]:    http://www.merriam-webster.com/dictionary/clowder
[hugo index]: http://hugo.spf13.com/indexes/overview

You're merrily on your way to being a blog champion. Creating new content
(which is just *gorgeous* btw) and taking names. So before you have an entire
[clowder][] to herd, you may want to know how to keep it all organized!

Indexes
-------

Indexes are ways to group and organize similar content. For example, in this
blog there are two indexes defined: `categories` and `tags`. You can see them
defined in `config.yaml` and in the front matter of each post. The index
display is controlled by files in `layout/indexes/category.html` and
`layout/indexes/tag.html` respectively.

For a more thorough explanation of what indexes are and how to define custom
ones you should take a look at the
[Hugo documentation][hugo index].

Since we've got a couple of commonly used indexes set up and ready to roll we
won't cover too much more here. But it's important to know that they exist and
how to use them, so at some point you should peruse the Hugo documentation to
learn more.