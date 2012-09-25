---
layout: post
title: "octopress command"
date: 2012-09-25 10:11
comments: true
categories: 
---

- install
>- git clone git://github.com/imathis/octopress.git
>- bundle install
>- rake setup_github_pages

- configuration: _config.yml
>- url: username.github.com
>- title, disqus_short_name


- create post: rake new_post["my first blog"] 

- publish: 
>- rake generate
>- rake preview
>- rake deploy
