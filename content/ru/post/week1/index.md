---
title: Индивидуальный проект, часть 1
date: 2022-10-10
math: true
image:
  placement: 2
  caption: 'Image credit: [**John Moeses Bauan**](https://unsplash.com/photos/OGZtQF8iC0g)'
---

## Установить необходимое программное обеспечение.
`sudo snap install go` - installed Golang
`sudo apt-get install hugo` - installed hugo

## Скачать шаблон темы сайта.
copied the template from https://github.com/wowchemy/starter-hugo-academic  
`git clone git@github.com:mascomen4/sciprog_personal_website.git`

## Разместить его на хостинге git.
`git add .`
`git commit -m "message"`
`git push origin master`

## Установить параметр для URLs сайта.
`https://mascomen4.github.io`- filled the URL of the website  

## Разместить заготовку сайта на Github pages.
`gh repo create mascomen4.github.io --public` - created the repository  
`git submodule add git@github.com:mascomen4/mascomen4.github.io.git public` - added the repository as a submodule to the website project.
