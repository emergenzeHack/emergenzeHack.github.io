---
layout: page
title: Protezioni Civili
description: "tutti i feed delle protezioni civili italiane"
tags: [emergenza, emergenzehack, protezioni-civili]
comments: false
permalink: /protezioni-civili/
image:
  feature: All4.jpg
---

## Di seguito i riferimenti delle protezioni civili italiane di cui abbiamo i FEED degli aggiornamenti. I FEED sono i formati dati più usati per generare "bollettini di aggiornamento". Segnalaci quello del tuo comune o della tua città se lo trovi. ##

## Se non hai trovato un feed rss perchè non è disponibile puoi comunque crearlo partendo da una pagina web del tuo comune. ##

## Una buona guida per farlo la trovi nel Wiki del progetto AlboPOP [qui](https://github.com/aborruso/albo-pop/wiki/Strumenti) ##

## Non appena lo hai trovato o creato segnala il link [qui](https://github.com/emergenzehack/emergenzeHack.github.io/issues/new?title=%5Bfeed%20pc%5D). ##

## Se vuoi che gli aggiornamenti della tua protezione civile siano inseriti in questa lista ma non sai come creare il tuo feed apri un issue [qui](https://github.com/emergenzehack/emergenzeHack.github.io/issues/new). Cercheremo di aiutarti ##

{% for prot in site.pc %}
  <li><a href="{{ site.url }}{{ prot.url }}">{{ prot.title }}</a></li>
{% endfor %}
