# hexo-theme-academia

<img src="https://img.shields.io/github/v/release/PhosphorW/hexo-theme-academia"> <img src="https://img.shields.io/badge/hexo-3.1%2B-blue.svg"> <img src="https://img.shields.io/badge/license-MIT-green.svg">

Simple page for academic websites on Hexo, crafted from Jekyll/academicpages.

## Introduction
This is a light & simple & responsive theme for academic websites on Hexo, crafted from [academicpages](https://github.com/academicpages/academicpages.github.io) on Jekyll. Thanks a lot.

The theme adopts only `post` and `page` in Hexo to show your informations. For an academic page, it's important to be simple and obvious.

Example page: [phosphorw.github.io](https://phosphorw.github.io/)

![mockup](https://raw.githubusercontent.com/PhosphorW/phower-img-folder/master/hexo-theme-academia_mockup.jpg)

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

- Top Menu: in-page anchor, new page links or any links you like
- Side Bar: Support avatar, social links, extra social links (optional), CV_download_link
- Box-shadow mode (optional)

All icons in page is supported with [font-awesome-4](http://fontawesome.dashgame.com/)

If you want to use rss feed, refer to hexo plugin: [hexo-generator-feed](https://github.com/hexojs/hexo-generator-feed)

![theme-layout](https://raw.githubusercontent.com/PhosphorW/phower-img-folder/master/hexo-theme-academia_layout.png)

### Update Theme
This theme supports `data files` smooth update. Copy `_config.yml` in theme folder to site folder `/source/_data/theme.yml`, if there is no `_data` folder, create it.

Then you can modify your theme configuration in the mentioned `theme.yml`. If there is any update, just pull the new branch and your configurations won't be merged. 

**Note:**
1. When use `data files` to config theme, you must restart hexo server after any modifictions. `hexo server` again.
2. Sometimes there will be changes in theme `_config.yml`, please refer to [release page](https://github.com/PhosphorW/hexo-theme-academia/releases) for more details before update.

## Document
中文文档：[Hexo-Theme-Academia 说明文档](https://phower.me/2020/03/Hexo-theme-academia-%E8%AF%B4%E6%98%8E%E6%96%87%E6%A1%A3/)

## Changelogs

**2020-04-22 Ver.1.2.0**
1. Feature: add pjax support
2. Feature: support `data files` smooth update
3. Fixed: optimize some appearance