---
title: "Step Two: First Steps"
description: "Who are you and where do we go from here?"
date: "2014-04-10"
categories:
  - "tutorial"
tags:
  - "hugo"
  - "blog"
---

[hugo conf]: http://hugo.spf13.com/overview/configuration

Configuration
-------------

The first thing you've got to do with your new site is *configure* it. You can
do so by opening `config.yaml` in the base directory of the repository and
changing a few variables. Here's the content of the provided `config.yaml`:

```yaml
---
baseurl: "http://blog.hugoexample.com/"
title: "Hugo Example Blog"
canonifyurls: true
indexes:
  category: "categories"
  tag: "tags"
---
```

At a minimum you'll want to change the value of `baseurl` and `title`, although
you don't have to do so just yet. Later on in this series we'll instruct you to
change these values before you deploy, however you should understand that the
configuration file is an extremely important part of your site.

Take a minute to glance over the Hugo documentation on
[configuration][hugo conf] before the next step.

Running and Viewing the Site
----------------------------

Since you installed Hugo in the first step *(you did install it, didn't you?)*
you should get Hugo running in server mode so you can view changes to the
site as you make them. From a command line navigate to the base directory of
this repository and run `hugo server -w`. This will start Hugo in server mode
and rebuild the site whenever you make changes.

Go ahead, try it out! When it's running you can visit [http://localhost:1313]()
to see your copy of the site.

Whenever you're following along with this example, or you're working on your
site in the future, it's recommended you use Hugo's server mode to get fast
feedback on what you're doing.