# hexo-theme-academia
Simple page for academic websites on Hexo, crafted from Jekyll/academicpages.

## Introduction
This is a light & simple & responsive theme for academic websites on Hexo, crafted from [academicpages](https://github.com/academicpages/academicpages.github.io) on Jekyll.

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

**Important:**
Add `academia: true` in front_matter filed in `post .md` (Note: only post with this front_matter will be shown on index page).

![post front_matter](https://github.com/PhosphorW/phower-img-folder/blob/master/hexo-theme-academia_front-matter.png)

## Theme Configurtion

菜单的配置