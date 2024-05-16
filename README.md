<p align="center">
    <h1 align="center">Hugowi</h1>
</p>

<p align="center">
    <img src="https://img.shields.io/github/stars/aziyan99/gohugo-theme-hugowi">
    <img src="https://img.shields.io/github/issues/aziyan99/gohugo-theme-hugowi">
    <img src="https://img.shields.io/github/license/aziyan99/gohugo-theme-hugowi">
</p>

![img-1](https://i.ibb.co/sbctGqr/hugowi.png)

## Installation
```shell
git submodule add https://github.com/aziyan99/gohugo-theme-hugowi.git themes/hugowi

echo theme = \"hugowi\" >> config.toml
```

## Upgrade
```shell
git submodule update themes/hugowi
```

if it's **the first time** you checkout the repo you need to use `--init` first

```shell
git submodule update themes/hugowi
```

## The `config.toml`
```toml
baseURL = 'https://aziyan99.github.io/'
languageCode = 'en-us'
title = 'Aziyan99'
theme = "hugowi"
copyright = '2022 Raja Azian All rights reserved'

[author]
  name = 'Raja Azian'
  email = 'rajaazian08@gmail.com'

[menu]
  [[menu.main]]
    name = "Main page"
    url = "/"
    weight = 1
  [[menu.main]]
    name = "Posts"
    url = "/posts"
    weight = 2
  [[menu.main]]
    name = "Tags"
    url = "/tags"
    weight = 3

[languages]
  [languages.en]
    languageName = "English"
    languageCode = "en-us"
    weight = 1

[params]
  introduction = "An learning journals and notes"
  oneliner = "-"
  githubAvatar = "https://avatars.githubusercontent.com/u/34334074?v=4"
  author = "Raja Azian"
  keywords = "HTML, CSS, Js, PHP, Programming, CPP, Python, Go, Web Programming, Java, C, Rust, MySQL, DBMS"
  description = "An learning journals and notes"
  [[params.link]]
    name = "GitHub"
    url = "https://github.com/aziyan99"
  [[params.link]]
    name = "Linkedin"
    url = "https://www.linkedin.com/in/raja-azian/"
  [[params.link]]
    name = "Youtube"
    url = "https://www.youtube.com/channel/UCsHAn_jONDr7KHaM2Qz52RQ"
  [[params.link]]
    name = "Instagram"
    url = "https://www.instagram.com/"

[sitemap]
  changefreq = 'weekly'
  filename = 'sitemap.xml'
  priority = 0.5
```

## Contributing

If you're interested in contributing to Hugowi, please post an issue first before submitting a pull request.

