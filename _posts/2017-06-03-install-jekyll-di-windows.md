---
title: Install Jekyll di Windows
page_title: Install Jekyll di Windows
layout: post
tags: [Web, Design, Tutorials]
categories: [Jekyll]
author: Imam Ali Mustofa
date: 2017-06-03
meta: Bagaimana caranya mengintall Jekyll pada Windows? Caranya cukup mudah, buka Command Prompt -> klik kanan dan pilih "Run as Administrator" 
keywords: HTML, CSS, Javascript, Jekyll
thumb: "/photos/jekyll.png"
---

Bagaimana caranya mengintall Jekyll pada Windows? Caranya cukup mudah, buka `Command Prompt -> klik kanan dan pilih "Run as Administrator"`.

### Step 1
#### Install Chocolatey Package Manager for Windows

[Cocholatey](https://chocolatey.org/) The package manager for Windows
Copy dan Paste snippet berikut pada Command Prompt:

    @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin

Tutup Command Prompt dan buka kembali untuk memastikan Chocolatey tersedia, ingat jalankan Command Prompt as administrator.

### Step 2
#### Install Ruby dengan Chocolatey

install Ruby:

    choco install ruby -y
 
 Tutup Command Prompt dan buka kembali untuk memastikan Ruby tersedia, ingat jalankan Command Prompt as administrator.

### Step 3
#### Install Jekyll dengan gem

dan sekarang install Jekyll dan Bundler

    gem install jekyll bundler
 
pastikan jekyll terinstall dengan menggunakan perintah sebagai berikut

    jekyll -v

Yeah! Sekarang Jekyll ada di komputer anda.