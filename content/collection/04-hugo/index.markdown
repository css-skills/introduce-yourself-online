---
title: "Why Hugo?"
weight: 6
subtitle: "Everything is a page, markdown-first."
date: 2022-01-21
draft: false
links:
- icon: campground
  icon_pack: fas
  name: slides
  url: "/slides/#56"
- icon: hiking
  icon_pack: fas
  name: activity
  url: "collection/04-hugo/#activity"
---

<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>

## Why Hugo?

<div class="shareagain" style="min-width:300px;margin:1em auto;">
<iframe src="/slides/#56" width="399.999999999999" height="300" style="border:2px solid currentColor;" loading="lazy" allowfullscreen></iframe>
<script>fitvids('.shareagain', {players: 'iframe'});</script>
</div>

## Activity

TIME: ⏱ 10 minutes

Let’s use this time to configure your new Hugo site.

### Site configuration

Edit your `config.toml` file. This is your basic Hugo site configuration file. It is not *quite* YAML- it is written in TOML, which means we have `key = value` instead of `key: value` pairs.

Biggest payoffs right away will be to switch up the built-in font choice:

``` yaml
  # alternatively, use a built-in font-family
  # serif options: Fraunces / EB Garamond / Bitter
  # sans-serif options: Commissioner / Alegreya Sans / Metropolis
  customtextFontFamily = "Commissioner"
  customheadingFontFamily = "Fraunces"
```

And the built-in site color theme:

``` yaml
  # use a built-in color theme
  # one of: forest / grayscale / peach / plum /
  #         poppy / sky / violet / water
  theme = "sky"
```

### Social

Open up `data/social.yaml` and add your social links there. Use these parameters in your `config.toml` file to control where they show up:

``` yaml
  # show/hide social icons in site header/footer/home page
  socialInHeader = false
  socialInFooter = true
  socialInHome = true
```
