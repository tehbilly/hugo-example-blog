---
title: "Step Five: Getting It Out THere"
description: "How to build and publish your site"
date: "2014-04-07"
categories:
  - "tutorial"
tags:
  - "example"
  - "hugo"
  - "blog"
  - "build"
  - "deploy"
---

[hugo doc]:   http://hugo.spf13.com/overview/introduction
[hugo local]: http://localhost:1313
[gh pages]:   https://pages.github.com
[aws s3]:     http://aws.amazon.com/s3/
[github]:     https://github.com
[gh windows]: https://windows.github.com
[gh mac]:     https://mac.github.com

So now you've got your content, organized it, and you're ready to share it
with the world. I suppose we can do something about that.

Building
--------

The most basic, but extremely useful, way to turn your source into a site is
by running `hugo` from the command line in the base of your project directory.
This will create a new directory called `public` that contains your generated
HTML and static assets (things such as images, css, javascript).

There is also the `hugo server` command *(we covered it earlier!)* which will
allow you to view your site at [hugo local][], an invaluable asset for
previewing your work without having to put it somewhere else first. It is
highly recommended that you run the command as `hugo server -w`, so that hugo
will automatically rebuild your site when you make changes to the source.

Deploying
---------

One of the beautiful things about having a static site generated is that you
don't need much to host it. [GitHub Pages][gh pages] is a great option, so is
[Amazon S3][aws s3], or anywhere else that'll provide serving of static
content.

You are, of course, also free to serve the site on any existing server you
have. If in doubt, call out to the nearest geek in your life for more help. We
geeks generally enjoy helping people get going.

GitHub Pages
------------

This option is straightforward, fast, and free. We'll cover the few very basic
steps needed to take this site you've lovingly crafted and share it with the
world.

If you do not already have a GitHub account, sign up for one [here][github].
It's free and you'll be joining a wonderful community.

To create a user page you should create a new repository called
`yourusername.github.io` (be sure to replace `yourusername` with your GitHub
username). Follow the instructions provided to `clone` this repository to your
local computer. If you do not have one already, you should download a git
client. GitHub has [windows][gh windows] and [mac][gh mac] clients readily
available, which will allow you to sign in and immediately clone your
repository.

Ensure that `config.yaml` has `http://yourusername.github.io/` as the `baseurl`
value, then build your site by running `hugo`. You can now copy the contents
of the `public` directory to the base directory of the `yourusername.github.io`
project you cloned in the last step.

This step assumes you are using one of the GitHub clients, so the instructions
may be slightly different if you are using a different client. From within the
repository view of the GitHub client make sure all files are checked and enter
a commit message. Commit your changes and then click the `sync` button. This
will add the files to your repository, then push them to GitHub.

Within a couple of minutes you should be able to visit
`https://yourusername.github.io/` and see your site! Give yourself a pat on the
back and then head over to the [Hugo documentation][hugo doc] to learn more.

Congratulations!
----------------

You've now taken all of the steps needed to configure, create, maintain, and
publish your own blog!