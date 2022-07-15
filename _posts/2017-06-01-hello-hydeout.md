---
layout: post
title: Hello Hydeout
excerpt_separator:  <!--more-->
---

Hydeout updates the original [Hyde](https://github.com/poole/hyde){:target="_blank"}
theme for [Jekyll](http://jekyllrb.com){:target="_blank"} 3.x and 4.x and adds new functionality.

### Keep It Simple

In keeping with the original Hyde theme, Hydeout aims to keep the overall
design lightweight and plugin-free.

Hydeout makes heavy use of Flexbox in its CSS. If Flexbox is not available,
the CSS degrades into a single column layout.

### New Features

* Hydeout also adds a new tags page (accessible in the sidebar) and a new
  "category" layout for dedicated category pages.

* Category pages are automatically added to the sidebar. All other pages
  must have `sidebar_link: true` in their front matter to show up in
  the sidebar.

* A simple redirect-to-Google search is available. If you want to use
  Google Custom Search or Algolia or something with more involved,
  override the `search.html`.

There's also a bunch of minor tweaks and adjustments throughout the
theme. Hope this works for you!
