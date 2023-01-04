---
layout: post
title:  "Personal Website Day 3: Jekyll Theme Minima Personalization"
date:   2023-01-03
categories: personal website
---

Today we will be making some minor customizations to our Jekyll Theme. We will use [this guide](https://jekyllrb.com/docs/themes/#overriding-theme-defaults) on overriding defaults on our jekyll theme to achieve this.

I will be making my website barbie pink themed where I can. The hex for barbie pink is #e0218a.

The quickest way to do this is the override the defaults in our current theme. To figure out our websites current theme, 1) navigate to the ```_config.yml``` folder located in the project root 2) Find the ```theme property```. Our website's current theme is called ```minima```.

In order to change the color palette, According to the guide we must:

1. Locate the theme's source files on our computer by executing
```bundle info --path minima```
2. Make a copy of minima's stylesheet in your project's root```cp <theme location/_sass/minima.scss> <project root location>```.
3. Override default values as necessary.

The code related to this can be found in [this commit](https://github.com/e0218a/e0218a.github.io/commit/b0894e14438201b73d05b65ed29a4e8af344e1ff#diff-b3834a425684c020b9844f69e1f2d8290a25eaa227a995372ea1c3954c095830)


