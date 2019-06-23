# Vexo = Vue.js Style + Hexo

> Vexo is a Hexo theme inspired by [Vue.js](https://cn.vuejs.org) official website.

[![Build Status](https://travis-ci.org/yanm1ng/hexo-theme-vexo.svg?branch=master)](https://travis-ci.org/yanm1ng/hexo-theme-vexo)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)


## Intro

![](http://file.muyutech.com/vexo.png)

## Demo

[Live Example](https://yanm1ng.github.io/)

## Features

* Fully Responsive
* SEO
* Immersive Status Bar
* Article Catalog

## Install

1. Download/Checkout this theme into your project

   ```
   cd your-hexo-folder

   git clone https://github.com/yanm1ng/hexo-theme-vexo.git themes/vexo

   cp -R themes/vexo/_source/* source/
   ```

2. Update project `_config.yml` theme config, look like this

   ```
   themes: vexo
   ```

   Here theme's name must same as the theme folder name.

3. Modify theme `themes/vexo/_config.yml` with your own info.

4. That's all , hope you will like :)

## Update Version

```
cd themes/vexo
git pull
```

## Post

The **front-matter** of a post looks like that:

```
---
title: "Hello World"
date: 2016-06-10 23:00
banner: your-banner-link.jpg
tags:
 - Movies
 - Life
---
```

Add this to the top of your article markdown file.

## Links

You can easily add your social account by just adding your settings into `_config.yml`
```
# Links
weibo_username: your_weibo_account
twitter_username: your_twitter_account
github_username: your_github_account
zhihu_username: your_zhihu_account
```

## About

- Give a star if you like , fork or just clone to use , and also you can help me fix bugs and add new feature :)
- If you have any problem or requirement , just open an issue here and i will help you.
- Thanks to [@imsun](https://github.com/imsun) , [@Evan You](https://github.com/yyx990803) and [@Hexo](https://hexo.io).

## LICENSE
MIT
