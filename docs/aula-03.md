---
title: "Desenhando com Código<br>:<br>Aula 03 — Animação"
---

# Conceitos

## Parâmetros e Tempo

Criar animações utilizando programação envolve sempre desenhar algo e estabelecer parâmetros que vão ser controlados com a passagem do tempo. Então antes de iniciar qualquer processo desse tipo é interessante imaginar qual será esse parâmetro e como esse parâmetro vai ser controlado através do tempo.

No exemplo a seguir podemos ver o **parâmetro tamanho** do círculo que **aumentar linearmente** a medida que o tempo passa:

<video width="600" height="600" autoplay loop><source src="{{ site.url }}/aula-03/Animacao-01-Comp.mp4" type="video/mp4"></video>

Além de entender como vai funcionar o parâmetro a ser animado, a forma como esse parâmetro vai ser controlado através do tempo também é algo importante para se pensar. Pequenas mudanças em como é feito esse processo mudam bastante a percepção em relação a animação.

Agora a baixo temos o mesmo parâmetro tamanho controlado utilizando uma função seno:

<video width="600" height="600" autoplay loop><source src="{{ site.url }}/aula-03/Animacao-02-Comp.mp4" type="video/mp4"></video>

Existem infinitas possibilidades e técnicas para controlar parâmetros através do tempo como utilizar [equações mais complexas para criar efeitos de aceleração](https://easings.net/) ou então utilizar algorítimos como [Ruído de Perlin](https://en.wikipedia.org/wiki/Perlin_noise).

E por fim esses conceitos de parâmetros e tempo não precisam necessariamente ter uma relação direta com a ideia da tradicional linha do tempo de programas de animação e edição de vídeo onde muitas vezes pensamos mais em uma sequência de acontecimentos que tem um início e um fim muito claro determinado no tempo, no nosso caso muitas animações criadas não precisam ter essa ideia de finitude. 

## Estudos de caso

### Bees and Bombs

Trabalhos criados pelo designer [Dave Whyte](http://beesandbombs.com/).

<div class="galeria">
<figure><img alt="Animação do designer Bees and Bombs" src="{{ site.url }}/aula-03/BeesAndBombs-01.webp"></figure>
<figure><img alt="Animação do designer Bees and Bombs" src="{{ site.url }}/aula-03/BeesAndBombs-02.webp"></figure>
<figure><img alt="Animação do designer Bees and Bombs" src="{{ site.url }}/aula-03/BeesAndBombs-03.webp"></figure>
<figure><img alt="Animação do designer Bees and Bombs" src="{{ site.url }}/aula-03/BeesAndBombs-04.webp"></figure>
<figure><img alt="Animação do designer Bees and Bombs" src="{{ site.url }}/aula-03/BeesAndBombs-05.webp"></figure>
<figure><img alt="Animação do designer Bees and Bombs" src="{{ site.url }}/aula-03/BeesAndBombs-06.webp"></figure>
</div>

### Daily Drawbot

Trabalhos criados pelo designer [Just van Rossum](https://dailydrawbot.tumblr.com/).

<div class="galeria">
<figure><img alt="Animação do designer Just van Rossum" src="{{ site.url }}/aula-03/DailyDrawbot-01.webp"></figure>
<figure><img alt="Animação do designer Just van Rossum" src="{{ site.url }}/aula-03/DailyDrawbot-02.webp"></figure>
<figure><img alt="Animação do designer Just van Rossum" src="{{ site.url }}/aula-03/DailyDrawbot-03.webp"></figure>
<figure><img alt="Animação do designer Just van Rossum" src="{{ site.url }}/aula-03/DailyDrawbot-04.webp"></figure>
<figure><img alt="Animação do designer Just van Rossum" src="{{ site.url }}/aula-03/DailyDrawbot-05.webp"></figure>
<figure><img alt="Animação do designer Just van Rossum" src="{{ site.url }}/aula-03/DailyDrawbot-06.webp"></figure>
</div>

### Experimentos Hyojung Seo

Trabalhos criados pela artista [Seo Hyojung](https://www.instagram.com/seohyo/).

<div class="galeria">
<video autoplay loop><source src="{{ site.url }}/aula-03/HyojungSeo-00.mp4" type="video/mp4"></video>
<video autoplay loop><source src="{{ site.url }}/aula-03/HyojungSeo-01.mp4" type="video/mp4"></video>
<video autoplay loop><source src="{{ site.url }}/aula-03/HyojungSeo-02.mp4" type="video/mp4"></video>
<video autoplay loop><source src="{{ site.url }}/aula-03/HyojungSeo-03.mp4" type="video/mp4"></video>
</div>
Abaixo alguns trabalhos desenvolvidos em conjunto com seus alunos:
<div class="galeria">
<video autoplay loop controls><source src="{{ site.url }}/aula-03/HyojungSeo-04.mp4" type="video/mp4"></video>
<video autoplay loop controls><source src="{{ site.url }}/aula-03/HyojungSeo-05.mp4" type="video/mp4"></video>
</div>

---

# Demonstrações

Arquivos criados durante ou para demonstração nas aulas práticas.

<a target="_blank" rel="noopener noreferrer" class="btn" href="https://guilhermesv.github.io/DownGit/#/home?url=https://github.com/guilhermesv/DesenhandoComCodigo-Grafatorio/tree/master/Aula-03-Demonstracoes">Acessar download dos arquivos</a>

# Exercícios

### Exercício 01

Adicionar alguma animação nos exercícios anteriores.

### Exercício 02

Criar uma animação que seja um loop perfeito, ou seja o começo e o fim se encaixem dando a sensação de ser infinita. 

### Desafio:

Parte 1 - Recriar a animação abaixo:

<video autoplay loop controls><source src="{{ site.url }}/aula-03/Aula03-Desafio-01.mp4" type="video/mp4"></video>

Parte 2 - Recriar alguma dessas variações:

<video autoplay loop controls><source src="{{ site.url }}/aula-03/Aula03-Desafio-02.mp4" type="video/mp4"></video>

<video autoplay loop controls><source src="{{ site.url }}/aula-03/Aula03-Desafio-03.mp4" type="video/mp4"></video>

### Dicas

- Para completar esse desafio você deve ter um controle individual sobre cada uma das linhas, então primeiro tente resolver como desenhar a linha e o círculo que caminha nela.
- Na segunta parte do desafio eu utilizei subnetworks. Na documentação do Nodebox tem um execelente tutorial, acesse neste [link](https://www.nodebox.net/node/documentation/concepts/subnetworks).

# Resolução dos exercícios

Todas as sugestões de resoluções dos exercícios e desafio podem ser baixadas no link abaixo:

<a target="_blank" rel="noopener noreferrer" class="btn" href="https://guilhermesv.github.io/DownGit/#/home?url=https://github.com/guilhermesv/DesenhandoComCodigo-Grafatorio/tree/master/Aula-03-Exercicios">Acessar download dos arquivos</a>


Dúvidas, de como baixar o arquivo do GitHub? [Clique aqui](https://guilhermesv.github.io/DesenhandoComCodigo-Grafatorio/faq)








