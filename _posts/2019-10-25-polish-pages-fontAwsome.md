---
title: "Polish your Github Pages-Icons"
date: 2019-10-25
permalink: /posts/polish-pages-icons/
tags:
  - github pages
---

In this post, we talk about how to use icons (font awesome icons) to decorate your github pages.

In fact, when we fork the repository from academic pages, some icons are already used by the original pages, such as github, location, email etc. The [original academicpages](https://academicpages.github.io/) uses the following three icons on the left.

<div class="list-group">
  <a class="list-group-item" href=""><i class="fa fa-github fa-fw" aria-hidden="true"></i>&nbsp; Github</a>
  <a class="list-group-item" href=""><i class="fa fa-linkedin fa-fw" aria-hidden="true"></i>&nbsp; Linkedin</a>
  <a class="list-group-item" href=""><i class="fa fa-envelope-square fa-fw" aria-hidden="true"></i>&nbsp; Email</a>
</div>

 These icons are generated using the following snippet of code.

```{html}
<i class="fa fa-github fa-fw">
<i class="fa fa-linkedin fa-fw">
<i class="fa fa-envelope-square fa-fw">
```

where ```fa-fw``` stands for fixed width and ```fa-github``` means the icon for github. These lines of code can be directly copied into html/md files of your github pages. Except for ```fa-fw```, there are other customization options that can be applied to the icons. For example, icons of different sizes can be generated using ```fa-xs, fa-sm, fa-lg, fa-2x, fa-3x```..., which stands for extra small, small, large, 2x larger, 3x larger respectively.

<i class="fa fa-github fa-xs"></i>
<i class="fa fa-github fa-sm"></i>
<i class="fa fa-github fa-lg"></i>
<i class="fa fa-github fa-2x"></i>
<i class="fa fa-github fa-3x"></i>

We are also able to spin the icons.

Reference: [Font Awesome Examples](https://fontawesome.com/v4.7.0/examples/)

