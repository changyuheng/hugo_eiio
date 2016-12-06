# Hugo blog theme

This is a [hugo](https://gohugo.io/) static blog engine theme, if you like this theme,please give me star  ~_~

[See Dome](https://feiio.com)

# Installation
Inside the folder of your Hugo site run:

```
cd themes
git clone https://github.com/leonhe/hugo_eiio

```
# Config
Modify your configuration:
```
baseurl = "https://feiio.com/"
title = "Site Name"
languageCode = "zh-CN"
themesdir = "themes"
theme = "hugo_eiio"
Paginate=15 
PaginatePath="page"
pygmentsuseclasses = true
#disqusShortname = "user id"
googleAnalytics='google analytics code'
[taxonomies]
  category = "categories"
  tag = "tags"

[params]
  description = "site description"
  author = "your name"
  github ="github username"
[sitemap]
  changefreq = "monthly"
  priority = 0.5
  filename = "sitemap.xml"

```

# License
This theme is released under the [MIT License](https://github.com/leonhe/hugo_eiio/blob/master/LICENSE).
