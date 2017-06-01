---
title: How To Create Static Website Using Jekyll
page_title: How To Create Static Website Using Jekyll
layout: post
tags: [Web, Design, Tutorials]
categories: [Jekyll]
author: Imam Ali Mustofa
date: '2017-05-30'
meta: Create a Static Website with Jekyll and free hosting with Github. Jekyll is
  a static website generator that we can use to create static blogs for documentation
  of a project and more. Jekyll uses the ruby programming language, quite easy to
  learn using Jekyll.
thumb: "/photos/jekyll.png"
---


Create a Static Website with Jekyll and free hosting with Github. Jekyll is a static website generator that we can use to create static blogs for documentation of a project and more. Jekyll uses the ruby programming language, quite easy to learn using Jekyll.
	
### Transform your plain text into static websites and blogs.


|   Simple | Static  | Blog-aware  |
| ------------ | ------------ | ------------ |
| No more databases, comment moderation, or pesky updates to install—just your content.  | Markdown (or Textile), Liquid, HTML & CSS go in. Static sites come out ready for deployment.  | Permalinks, categories, pages, posts, and custom layouts are all first-class citizens here.  |


### Free hosting with GitHub Pages
Sick of dealing with hosting companies? GitHub Pages are powered by Jekyll, so you can easily deploy your site using GitHub for free—custom domain name and all.

### Step 1

#### Install Ruby on Your Computer

Package Management Systems
If you cannot compile your own Ruby, and you do not want to use a third-party tool, you can use your system’s package manager to install Ruby.

Certain members in the Ruby community feel very strongly that you should never use a package manager to install Ruby and that you should use tools instead. While the full list of pros and cons is outside of the scope of this page, the most basic reason is that most package managers have older versions of Ruby in their official repositories. If you would like to use the newest Ruby, make sure you use the correct package name, or use the tools described further below instead.

apt (Debian or Ubuntu)
Debian GNU/Linux and Ubuntu use the apt package manager. You can use it like this:

{% highlight python %}
~ $ sudo apt-get install ruby-full
{% endhighlight %}

As of writing, the ruby-full package provides Ruby 1.9.3, which is an old stable release, on Debian and Ubuntu.

see [Ruby Installation Docs](https://www.ruby-lang.org/en/documentation/installation/ "Ruby Installation")

### Step 2

Install RubyGems Packages Management Framework for Ruby [Installation Page](https://rubygems.org/pages/download "Installation Page")

### Step 3
#### Get up and running in seconds.

{% highlight python %}
~ $ gem install jekyll bundler
~ $ jekyll new my-awesome-site
~ $ cd my-awesome-site
~/my-awesome-site $ bundle exec jekyll serve
# => Now browse to http://localhost:4000
{% endhighlight %}


In the next article we will see directory structures of Jekyll Project. Thanks and see you next time! :D