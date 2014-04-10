---
title: "Step Three: Creating New Content"
description: "How to add new posts to your blog"
date: "2014-04-09"
categories:
  - "tutorial"
tags:
  - "hugo"
  - "blog"
  - "how-to"
---

[front matter]: http://hugo.spf13.com/content/front-matter
[markdown]:     http://daringfireball.net/projects/markdown/

So all of that is really wonderful, but I know why you're here. You want to
create your *own* content, right? This post will walk you through doing
exactly that.

Creating The File
-----------------

Take your favorite text editor and create a new file at
`content/post/my-first-post.md`. Inside of there you'll want to define the
properties of your post. First, paste the following at the very top of the
file:

```yaml
---
title: "Post Title"
description: "This is a description"
date: "2014-04-12"
categories:
  - "tutorial"
tags:
  - "example"
  - "hugo"
  - "blog"
  - "custom"
---
```

This defines your post. How links are formatted, where it's placed, what it's
related to; everything is defined in those few lines of [front matter][]. None
of this is included in your final page, it is only used by hugo at build time
to generate the final pages properly. Most of these should be pretty self
explanatory, so modify the values as you see fit and let's get to writing the
content!

Adding Some Meat
----------------

Below the front matter you can start writing your post however you see fit.
You can use plain text, which will be plain but perfectly readable. You
*ideally* will use [markdown][] to write your content as it is concise,
expressive, and Hugo will generate gorgeous HTML from it.

Bask
----

Save your file and point your browser to [http://localhost:1313]() *(assuming
you still have Hugo running in server mode)*. Your post should appear at the
top of the index! Click on it to see the content view. Browse around the
categories and tags to see how it's been added to those. No muss, no fuss.

Continue adding to your new post and playing around with it. Create two or
three more posts of different types and have a blast. There's no time limit or
anything, knock yourself out. This *is* why you're here!