---
layout: post
title:  "Правильное подключение скриптов с GitHub на сайт"
date:   2017-03-19 14:00:00 +0300
category: [Life]
icon: github
link: life
---
<p>Недавно столкнулась с проблемой работы скриптов, находящиеся в репозитории GitHub. Например, если подключить <a href="//github.com/ViKapitoshka/blog/blob/master/assets/js/main.js">этот</a> скрипт напрямую, то файл изменится до неузнаваемости и, конечно же, не будет работать. Почему так происходит?</p>
<p>GitHub невозможно использовать как CDN (сеть доставки контента), по сути он запрещает использовать прямые ссылки на файлы при подключении в страницу. Для того чтобы подключить скрипт можно использовать <a href="//rawgit.com">RawGit</a></p>
<p>Здесь всё очень просто - нужно вставить ссылку на нужный файл из репозитория, а сервис отдаст нам ссылку на тот же файл, но с правильными заголовками. RawGit отдаёт сразу две ссылки - на продакшн и разработку.</p>