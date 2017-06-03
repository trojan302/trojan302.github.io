---
title: Bagaimana Membuat Web Statis Dengan Jekyll
page_title: Bagaimana Membuat Web Statis Dengan Jekyll
layout: post
tags: [Web, Design, Tutorials]
categories: [Jekyll]
author: Imam Ali Mustofa
date: '2017-05-30'
meta: Membuat sebuah Website Statis dengan jekyll dan Free Hosting dengan Github. Jekyll adalah sebuah static generator yang bisa digunakan untuk membuat blog statis atau untuk membuah website dolumentasi dari sebuah project. Jekyll menggunakan ruby sebagai bahasa pemrogramannya dan menggunakan template engine Liquid. Sangat mudah untuk belajar menggunakan Jekyll.
keywords: HTML, CSS, Javascript, Jekyll
thumb: "/photos/jekyll.png"
---


Membuat sebuah Website Statis dengan jekyll dan Free Hosting dengan Github. Jekyll adalah sebuah static generator yang bisa digunakan untuk membuat blog statis atau untuk membuah website dolumentasi dari sebuah project. Jekyll menggunakan ruby sebagai bahasa pemrogramannya dan menggunakan template engine Liquid. Sangat mudah untuk belajar menggunakan Jekyll.
	
### Transformasi Teks Biasa Anda Menjadi Situs Web Statis dan Blog.


|   Mudah | Statis  | Cocok Untuk Blog  |
| ------------ | ------------ | ------------ |
| Tidak ada Database, mudah untuk mengatur konten dan mudah di install  | Menggunakan Markdown (atau Textile), Liquid, HTML & CSS. Website anda siap diluncurkan | Permalinks, kategori, halaman, posting, dan layout dapat dilakukan disini. |


### Free hosting dengan GitHub Pages
Malas berurusan dengan perusahaan hosting? Halaman GitHub didukung oleh Jekyll, sehingga Anda dapat dengan mudah menyebarkan situs Anda menggunakan GitHub untuk nama domain khusus gratis dan semuanya.

### Step 1

#### Install Ruby di Komputer Anda

Untuk menginstall Ruby yang anda perlukan lakukan adalah sebagai berikut:

Untuk Pegguna Linux (Ubuntu)
{% highlight python %}
~ $ sudo apt-get install ruby-full
{% endhighlight %}

atau anda bisa membaca dokumentasi untuk cara installasinya di [Ruby Installation Docs](https://www.ruby-lang.org/en/documentation/installation/ "Ruby Installation")

### Step 2

Install RubyGems Packages Management Framework untuk Ruby [Installation Page](https://rubygems.org/pages/download "Installation Page")

### Step 3
#### Install Jekyll dan Bundler

{% highlight python %}
~ $ gem install jekyll bundler
~ $ jekyll new my-awesome-site
~ $ cd my-awesome-site
~/my-awesome-site $ bundle exec jekyll serve
# => Now browse to http://localhost:4000
{% endhighlight %}

Mudah bukan untuk menginstall Jekyll? Nah, pada kesempatan berikutnya kita akan melihat struktur direktori jekyll. Se you next time!