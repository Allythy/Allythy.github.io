---
layout:     post
title:      "Como criar apresentação de slides no terminal"
subtitle:   "Neste artigo, vamos aprender como criar uma apresentação de slides no terminal"
date:       2017-03-16 14:00:00
author:     "Allythy"
header-img: ""
categories: Terminal


---
Neste artigo, vamos aprender como criar uma apresentação de slides no terminal.
Não há necessidade de instalar uma tonelada de softwares, afim de criar uma apresentação agradável e informativa.

O TPP é uma simples ferramenta de linha de comando que permite que você faça isso,
com suporte a cores, saída de código fonte e animações, tudo isso com um simples arquivos de texto ASCII.
Para fazer a instalação no Debian e derivados, basta executar o comando:

{% highlight bash %}
sudo apt-get install tpp
{% endhighlight %}

Irei fazer uma apresentação simples de dois slides com o titulo, nome do autor, uma frase centralizada e a data da criação. Para isso, criarei um arquivo de texto e salvá-lo com a extensão .tpp.

{% highlight bash %}
vim apresentacao.tpp
{% endhighlight %}

E nesse arquivo vou colocar as informações a baixo:

{% highlight bash %}
--author Por Allythy Souza
--date today
--newpage
--center Saudações Livres
{% endhighlight %}

Para saber mais sobre os comandos do TPP basta ler o README que esta em  /usr/share/doc/tpp. Você pode ver uma pequena [apresentaçao usando TPP aqui.](https://youtu.be/fcC2aKCDGAs) Caso você queira ver o código desse vídeo ele vai estar [no meu GitHub.](https://github.com/allythy/Apresentacao-de-Slides-no-Terminal)
