---
layout: post
title: 'Loop for na Linguagem C'
date: '2012-11-24T15:08:00.000-08:00'
image: '/assets/img/c/for_c.jpg'
description: 'Fazer coisas básicas e aos poucos fazem memorização e fixação melhor dos detalhes.'
tags:
- linguagemc
---

![Loop for na Linguagem C](/assets/img/c/for_c.jpg "Loop for na Linguagem C")

Fazer coisas básicas e aos poucos fazem memorização e fixação melhor dos detalhes. Estou postando 2 exemplos de loop simples em for, ambos no mesmo código, como compilar, está nos posts antigos sobre C, é só pesquisar, breve passarei teorias sobre tudo.

{% highlight c %}
#include <stdio.h>
int main(){

    int i;
    char letra;
    for(i=1;i<=10;i++)
        printf("%d\n",i);
   
    for(letra = 'A';letra<='Z';letra++)
        printf("%c\n",letra);
        return(0);

}
{% endhighlight %}

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

<!-- Informat -->
<ins class="adsbygoogle"
 style="display:block"
 data-ad-client="ca-pub-2838251107855362"
 data-ad-slot="2327980059"
 data-ad-format="auto"
 data-full-width-responsive="true"></ins>

<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>



