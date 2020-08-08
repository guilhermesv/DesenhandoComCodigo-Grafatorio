# Introdução

Este site é um simples material de apoio a oficina Desenhando com código. Aqui estão organizados alguns breves textos e os exercícios aplicados durante a oficina. Algumas informações aqui talvez não façam tanto sentido sem o acompanhar das aulas.


## Sobre a oficina

A oficina foi pensada como uma adaptação online e intensiva em uma oficina ministrada duas vezes para o [Sesc São Paulo](http://sescsp.org.br/). São apresentados conceitos para criar composições visuais no software de programação visual [NodeBox 3](https://www.nodebox.net/). 

A partir dessa ferramenta serão vistos conceitos de pensamento computacional, design generativo, animação, entre outros. Todas as aulas são demonstrativas e propõe pelo menos um exercício prático para o aluno. 

Ao fim da oficina também é solicitado a criação de um projeto final envolvendo as técnicas ensinadas.

## Cronograma das aulas

- **Aula 01: Introdução:** apresentação sobre programar, pensamento computacional e introdução ao NodeBox 3
- **Aula 02: Design generativo:** conceitos básico sobre sistemas generativos e como utilizar os nós de aleatoriedade para criar artes generativas.
- **Aula 03: Criando animações:** exemplos de animações criadas computacionalmente e como combinar os nós do Nodebox para criar animações.
- **Aula 04: Projeto final:** apresentação dos alunos sobre seus projetos e compartilhamento de experiências.

## Sobre mim

Meu nome é Guilherme Vieira, sou um entusiasta da programação criativa, artista gráfico na [Norte](https://www.norte.in) e designer no estúdio [Daó](https://www.estudiodao.com) – o contrário também é válido. 

## Inspirações

Este site é altamente inspirado no material produzido pela [Monica Rizzoli](https://cargocollective.com/monicarizzolli) e [Alexandre Villares](https://abav.lugaralgum.com/) para suas oficinas e cursos. Você pode ver o material que eles criaram veja o repositório: [Programação criativa](https://github.com/arteprog/programacao-criativa)

<div class="separador"><video width="300" height="300" autoplay loop><source src="/assets/imgs/separador-compactado.mp4" type="video/mp4"></video></div>

# Aula 01 - Introdução

## Por que é legal programar?

1. Autonomia: criar ferramentas, automatização e parametrização
2. Você trabalha mais no processo e menos no resultado
3. Racionalização do processo criativo
4. Geração de possibilidades
5. Expandir o espaço das ideias

## Programar é sobre se comunicar

Aprender a programar, é aprender uma forma nova de se comunicar e nesse caso inicialmente se comunicar com a máquina. Uma vez que você aprende alguns princípios dessa comunicação, fica um pouco mais fácil de se expressar em diversas linguagens de programação.

Para saber mais sobre esse conceito: [Programar nunca foi sobre Código](https://www.youtube.com/watch?v=eLnLevR5mjg)

## Pensamento computacional

> “a utilização de  conceitos  fundamentais  da  computação
para resolver  problemas,  projetar  sistemas, e  compreender
comportamentos humanos”  — [Jeannette  Wing citada por Eduardo Omine](http://www.teses.usp.br/teses/disponiveis/16/16134/tde-12092014-122450/pt-br.php)

De uma forma bem simples e genérica o pensamento computacional é aplicar alguns conceitos que são muito comuns e diários do universo das ciências computacionais a outros campos e situações.

Destaco **4 conceitos** importantes para se começar a programar:

### Abstração

Identificar e extrair o mais relevante de um problema ou informação. Exemplos: números, mapas, agenda, etc.

<figure>
  <img alt="Mapa do Metrô de São Paulo" src="/assets/aula-01/mapa-metro.png">
  <figcaption>Mapa do Metrô de São Paulo: Fonte <a href="https://commons.wikimedia.org/wiki/File:Mapa_metro_sp.svg">Wikipedia</a></figcaption>
</figure>


### Algoritmo

Criar uma série de instruções para resolver uma tarefa e tarefas similares. Exemplos: operações matemáticas (somar, dividir, multiplicar, etc), receita de bolo, jogadas de futebol, etc.

<figure>
  <img alt="Operação de adição com números decimais" src="/assets/aula-01/conta-adicao.jpg">
  <figcaption>Operação de adição com números decimais. Fonte: <a href="http://seusaber.com.br/matematica/como-fazer-contas-de-somar-com-virgula.html">Seu saber</a></figcaption>
</figure>

### Decomposição

Decompor o problema/informação em porções menores. Exemplos: uma rota para se chegar a um local, estabelecer um cronograma baseado no tempo gasto em cada uma das etapas, entender o como uma bicicleta funciona a partir de suas peças, etc.

### Parametrização

Estabelecer variáveis de controle sobre uma solução ou ferramenta. Exemplos: controle de volume ou equalizador em um player ou caixa de som, registro da torneira, etc.

(Este é um conceito que não encontrei dessa forma nas bibliografias, mas achei importante ressaltar aqui)

## Estudos de caso

Uma seleção de projetos interessantes que utilizam da programação para criar peças visuais. Nem todos casos aqui selecionados utilizam o NodeBox como ferramenta.

// Pegar lista da apresentação


## Aula 01 - Demonstrações

Arquivos criados durante ou para demonstração nas aulas práticas

## Aula 01 - Exercício

1. Explorando as primitivas básicas e o nó grid criar um padrão geométrico.
2. Criar uma composição livre utilizando as transformações e o nó copie.

### Desafio:

Recriar o resultado abaixo com parametrização do número de colunas e linhas, ou seja ao mudar a quantidade de colunas ou linhas, o padrão deve se ajustar automaticamente
