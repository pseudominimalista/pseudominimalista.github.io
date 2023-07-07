---
title: Sway
description: Um compositor Wayland. 
slug: sway-window-manager
date: 2023-06-10 00:00:00+0000
image: cover.png
categories:
    - Linux
tags:
    - Open Source
    - Window Manager
---
Não me pergunte o porquê de eu querer fazer um artigo sobre uma interface gráfica.  
Eu só tô entediado e sem nada melhor para fazer.  

Nos últimos dias dessa semana eu voltei a utilizar o [Sway](https://swaywm.org) (A interface gráfica, não o programa da Microsoft) só por puro tédio.  
Eu tive que pegar uma configuração antiga minha e reconfigurar quase tudo para deixar ela atualizada e confortável para o  
meu workflow atual, como por exemplo: uma troca na paleta de cores.  

Antes a paleta de cores que eu usava era a [Catppuccin Mocha](https://catppuccin.com), porém por alguma razão ela me dá dores de cabeça.  
Isso pode ter relação com o contraste que eles usam, eu sinceramente não sei. Eu só sei que ela me dá dor de cabeça,  
então eu troquei ela por outra paleta de cores, essa que é confortável para os meus olhos e também é muito bonita: [Nord](https://nordtheme.com).  

Feito isso, o próximo passo foi re-adaptar algumas teclas de atalho, essa parte foi bem mais tranquila graças ao arquivo de configuração  
do Sway que é extremamente simples e legível.  

Aqui está um trecho do meu arquivo de configuração:  
```
    Ctrl+Shift+Print exec $term wf-recorder -a -f out.mkv  
```
Agora chegou a hora de explicar o que está acontecendo aqui encima. Bem, “bindsym” é a palavra chave para criar uma tecla de atalho,  
o que vem em seguida são as teclas que eu quero e depois disso a ação que esse tecla de atalho fará.  

No caso do exemplo acima, após eu apertar as teclas Ctrl, Shift e Print juntas, uma janela de um terminal irá aparecer e dentro dela  
um programa de gravação de tela será executado, quando eu quiser finalizar a gravação, tudo o que eu preciso fazer é clicar na janela  
aberta e apertar as teclas Ctrl e C juntas. Após isso a janela fechará e a gravação de tela estará pronta.  

Eu com toda certeza te enchi de informações que aparentam serem desconexas, mas confie em mim quando eu digo que elas tem  
uma relação bem lógica e que, quando analisada, é extremamente simples.  

Tendo isso dito, acho que é seguro dizer com toda certeza do mundo que eu sou um nerd.  
