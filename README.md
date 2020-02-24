# hexo-theme-academia

!()[https://img.shields.io/badge/release-1.1.0-blue.svg]

!()[https://img.shields.io/badge/hexo-3.1%2B-blue.svg]

!()[https://img.shields.io/badge/license-MIT-green.svg]

Simple page for academic websites on Hexo, crafted from Jekyll/academicpages.

## Introduction
This is a light & simple & responsive theme for academic websites on Hexo, crafted from [academicpages](https://github.com/academicpages/academicpages.github.io) on Jekyll. Thanks a lot.

The theme adopts only `post` and `page` in Hexo to show your informations. For an academic page, it's important to be simple and obvious.

## Preparation

Some skills you need:
- Publish a Hexo blog: [Learn more](https://hexo.io)
- Git
- Markdown: [Learn more](https://www.appinn.com/markdown/#list)
- Deploy a server (Optional)
- Balabala...

## Installation

The simplest way to install is to clone the entire repository:
```
git clone https://github.com/PhosphorW/hexo-theme-academia.git themes/Academia
```

Some required renderers:
```
npm install hexo-renderer-pug hexo-renderer-stylus
```

Set theme in hexo work folder's `_config.yml`
```
theme: Academia
```

## Create your academic page

Only `post` and `page` are supported in this theme.

```
hexo n post "any title"
```
or
```
hexo n page "any title"
```

**Important:** </br>
Add `academia: true` in front_matter filed in `post .md`.

<img src="https://raw.githubusercontent.com/PhosphorW/phower-img-folder/master/hexo-theme-academia_front-matter.png" width="660px" alt="front_matter">

Only post with `academia: true` front_matter will be shown on home (index) page. You can write your informations in either one post or some posts with this method. The front_matter doesn't works in `page`. The `pages` are standalone with its markdown content.


## Theme Configurtion
All of below options can be config in theme folder `_config.yml`

- Top Menu
- Side Bar: Support avatar, social links, extra social links (optional), CV_download_link
- Box-shadow mode (optional)

All icons in page is supported with [font-awesome-4](http://fontawesome.dashgame.com/)
