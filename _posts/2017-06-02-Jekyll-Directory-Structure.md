---
title: Stuktur Direktori Jekyll
page_title: Stuktur Direktori Jekyll
layout: post
tags: [Web, Design, Tutorials]
categories: [Jekyll]
author: Imam Ali Mustofa
date: 2017-06-02
meta: Memahami struktur direktori Jekyll dan apa saja yang bisa anda lakukan dengan menggunakan Jekyll.
keywords: HTML, CSS, Javascript, Jekyll
thumb: "/photos/jekyll.png"
---

Secara Default Jekyll telah memberikan anda struktur direktori seperti berikut:

{% highlight perl %}

[jekyll-site]
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

{% endhighlight %}

Dalam tutorial ini kita akan mempelajari dan mengetahui struktur direktori Jekyll Website. Anda tidak boleh panik dulu, Jekyll sangat rapi memanipulasi struktur website yang kita butuhkan. Secara default Jekyll memiliki struktur seperti di atas.

Jika Anda melihat file `_config.yml` Anda akan melihat isi file sebagai berikut:

{% highlight perl %}

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
Memegang seluruh konfigurasi untuk situs Jekyll Anda. Ini biasa digunakan untuk:

Metapkan variabel global di situs dan Mengkonfigurasi koleksi (Collections) atau Menentukan default variabel runtime yang ingin kita jalankan kapan saja.

## _drafts
Memungkinkan anda untuk membuat posting dan tidak ingin mempublikasikannya secara langsung.

## _includes
Seperti pada pembuatan website pada umumya, sebuah file dengan ratusan atau bahkan ribuan baris tidak akan di tulis begitu saja pada satu file. anda bisa menggunakan folder `_includes` untuk menyimpan file - file potongan yang akan anda sisipkan ke fil utama.

## _layouts
Adalah template yang membungkus konten. Semua HTML di situs Anda seperti header, footer dan navigasi biasanya berada di layout. layout bisa digunakan berulang kali.

## _posts
Berisi posting blog Anda yang ditulis dalam format Markdown, atau Textile.

## _data
`_data` Berisi file YAML, JSON dan CSV. Data dalam file ini dapat digunakan di seluruh situs Jekyll sebagai bank data, atau biasanya kita menyebutnya database.

## _site
Setelah Jekyll membangun situs Anda dengan perintah `bundle exec jekyll serve`, jekyll akan menempatkan semua situs statis termasuk semua aset Anda di direktori`_site`.

## .jekyll-metadata
File ini digunakan oleh fitur build tambahan Jekyll untuk melacak file yang telah berubah.

## Other Files / Folders
Anda bisa membuat direktori lain seperti biasa, maka Jekyll akan meletakkan direktori yang Anda buat di direktori `_site` setelah dibangun.