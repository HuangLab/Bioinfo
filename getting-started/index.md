---
layout: article
title: "Getting Started with Skinny Bones"
date: 2014-06-25T13:57:25-04:00
modified: 2016-01-19
excerpt:
tags: []
image:
  feature:
  teaser:
  thumb:
share: false
---
HEELLLOOOOO!!!!!

<!-- {% include toc.html %} -->

## Installation

Skinny Bones requires [Jekyll](http://jekyllrb.com/) 3.0. Make sure to run `bundle update` if you aren't on the latest version or `bundle install` if this is your first time installing it.

If you are creating a new Jekyll site using Skinny Bones following these steps:

1. [Download Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll/archive/master.zip) and unzip.
2. Rename `skinny-bones-jekyll-master` to something meaningful ie: `new-site`
3. Run `bundle install` to install all dependencies (Jekyll, [Jekyll-Sitemap](https://github.com/jekyll/jekyll-sitemap), [Octopress](https://github.com/octopress/octopress), etc)
4. Update `_config.yml`, add navigation, and add posts/pages. Full details below.

If you want to use Skinny Bones with an existing Jekyll site follow these steps:

1. [Download Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll/archive/master.zip) and unzip.
2. Rename `skinny-bones-jekyll-master` to something meaningful ie: `new-site`
3. Run `bundle install` to install all dependencies (Jekyll, [Jekyll-Sitemap](https://github.com/jekyll/jekyll-sitemap), [Octopress](https://github.com/octopress/octopress), etc)
4. Add all of your existing posts, pages, and any other content you want to move over.
5. Update YAML front matter blocks to match names used by Skinny Bones. Full details below.
6. Update `config.yml`, add navigation links. Full details below. 

---

## Running Jekyll

The preferred method for running Jekyll is with `bundle exec`, but if you're willing to deal gem conflicts feel free to go cowboy with a `jekyll build` or `jekyll serve`.

> In some cases, running executables without bundle exec may work, if the executable happens to be installed in your system and does not pull in any gems that conflict with your bundle.
>
>However, this is unreliable and is the source of considerable pain. Even if it looks like it works, it may not work in the future or on another machine.

{% highlight text %}
bundle exec jekyll build

bundle exec jekyll serve
{% endhighlight %}
o
---


## License

This theme is free and open source software, distributed under the MIT License. So feel free to use this Jekyll theme on your site without linking back to me or including a disclaimer. 
