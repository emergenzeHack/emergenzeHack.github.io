---
layout: page
title: Protezioni Civili
description: "tutti i feed delle protezioni civili italiane"
tags: [emergenza, emergenzehack, protezioni-civili]
comments: false
image:
  feature: All4.jpg
---

## Di seguito i riferimenti delle protezioni civili italiane di cui abbiamo i FEED degli aggiornamenti. Segnalaci quello del tuo comune o della tua città. ##

## Se non hai trovato un feed rss perchè non è disponibile puoi comunque crearlo partendo da una pagina web del tuo comune. ##

## Una buona guida per farlo la trovi nel Wiki del progetto AlboPOP [qui](https://github.com/aborruso/albo-pop/wiki/Strumenti) ##

## Non appena lo hai trovato o creato segnala il link [qui](https://github.com/emergenzehack/emergenzeHack.github.io/issues/new?title=%5Bfeed%20pc%5D). ##

## Se non sai come creare il tuo feed apri un issue [qui](https://github.com/emergenzehack/emergenzeHack.github.io/issues/new). ##

{% for prot in site.pc %}
  <li><a href="{{ site.url }}{{ prot.url }}">{{ prot.title }}</a></li>
{% endfor %}
