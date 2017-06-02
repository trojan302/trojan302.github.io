---
title: Jekyll Directory Structure
page_title: Jekyll Directory Structure
layout: post
tags: [Web, Design, Tutorials]
categories: [Jekyll]
author: Imam Ali Mustofa
date: 2017-06-02
meta: Know the directory structure in Jekyll and what are the benefits of each directory and its function. Using Jekyll you can ...
thumb: "/photos/jekyll.png"
---

{% highlight perl %}

[Your-jekyll-site]
├── _config.yml
├── Gemfile
├── Gemfile.lock
├── _layouts /
├── ├── default.html
├── ├── home.html
├── ├── page.html
└── └── post.html
├── _posts /
| └── 2017-06-02-welcome-to-jekyll.md
├── index.md
├── about.md

{% endhighlight%}

In this tutorial we will learn and know the sususan dari directory Jekyll Website. You do not panic first, Jekyll is very neatly manipulate website structure that we need. By default Jekyll has the structure as above.

If you look at the `_config.yml` file you will see the contents of the file as follows:

{% highlight yaml%}

Title: Your awesome title
Email: your-email@domain.com
Description:> # this means to ignore newlines until "baseurl:"
  Write an awesome description for your new site here. You can edit this
  Line in _config.yml. It will appear in your document head meta (for
  Google search results) and in your feed.xml site description.
Baseurl: "" # the subpath of your site, e.g. / Blog
Url: "" # the base hostname & protocol for your site, e.g. Http://example.com
Twitter_username: jekyllrb
Github_username: jekyll

# Build settings
Markdown: kramdown
Theme: minima
Gems:
  - jekyll-feed
Exclude:
  - Gemfile
  - Gemfile.lock

{% endhighlight%}

## _config.yml
Holds the entire configuration for your Jekyll site. This is commonly used for:

Set global variables on the site
Configure collection (Collections) or default
Specifies the runtime variable we want to run at any time

## _drafts
This directory allows you to post to not publish directly to live sites.

## _includes
Used to save excerpts from files we will paste into one, or pieces of code or anything to merge on our website.

## _layouts
Templates that wrap the content. All HTML on your site such as header, footer and navigation usually stay in the layout. Layout can be used repeatedly.

## _posts
Contains your blog post written in the Markdown format, or TextTile.

## _data
`_data` contains YAML, JSON and CSV files. The data in this file can be used throughout the Jekyll site as a data bank, or we usually call it the database.

## _site
After Jekyll builds your site with the `bundle exec jekyll serve` command, it places all static sites including all your assets in the` _site` directory.

## .jekyll-metadata
This file is used by Jekyll's additional build feature to keep track of files that have changed.

## Other Files / Folders
You can create another directory as usual, then Jekyll will put the directory you created in the `_site` directory after it's built.