---
layout: post
title: Halaman Test
category: Edge Case
tags: Pengkategorian
excerpt_separator:  <!--more-->
---

Hydeout updates the original [Hyde](https://github.com/poole/hyde)
theme for [Jekyll](http://jekyllrb.com) 3.x and adds new functionality.

### Keep It Simple

In keeping with the original Hyde theme, Hydeout aims to keep the overall
design lightweight and plugin-free. JavaScript is currently limited only
to Disqus and Google Analytics (and is only loaded if you provide configuration
variables).

Hydeout makes heavy use of Flexbox in its CSS. If Flexbox is not available,
the CSS degrades into a single column layout.

<!--more-->

### Customization

Hydeout replaces Hyde's class-based theming with the use
of the following SASS variables:

```scss
$sidebar-bg-color: #202020 !default;
$sidebar-sticky: true !default;
$layout-reverse: false !default;
$link-color: #268bd2 !default;
