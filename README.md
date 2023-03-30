# _desafio-html-na-pratica
Desafio do curso Aprendendo HTML na prática, da DIO com o Prof. Diogo Mainardes.
# Aprendendo HTML na Prática 

* Excelente oportunidade de fazer de novamente uma trilha com HTML, sendo que dessa vez, um programa todo voltado a esta linguagem de marcação tão necessária. Fica a dica que deveria ser o programa para quem se interessa por programar, mesmo que esse interesse não se limite apenas ao Front-end. 

* Apesar de não possuir ainda as configurações de diagramação necessárias para uma página de boa qualidade, fiquei muito satisfeita em usar apenas o HTML. Foi tão desafiador quanto usar as linguagens de programação de fato e as mais avançadas, tanto que não me furtei o trabalho de criar uma página especial, com um breve porém instigante recorte, ao perceber quantas mulheres fizeram contribuições para o desenvolvimento da Ciência da Computação e da Programação.   

* Abaixo segue um resumo dos conteúdos acrescidos de pequenas anotações que fiz e outras que só constam diretamente no index.html. 

#### Aprendendo HTML na prática
Prof. Diogo Medeiros Mainardes
Desenvolvedor Sênior / Tech Lead

#### Percurso
* 1› Surgimento da Internet e seus percursores e protagonistas
* 2 Como funciona o HTML
* 3› Ferramentas utilizadas
* 4› Usando o Inspetor de Elementos
* 5› Estrutura básica do HTML
* 6› Falando sobre Tags
* 7› Atributos básicos
* 8› Executando uma página HTML
* 9› Textos
* 10› Listas ordenadas e não ordenadas
* 11› Link

#### Objetivo Geral

Aprender a instalar e configurar o ambiente de desenvolvimento. Entender o funcionamento do inspetor de elementos do navegador e criar sua primeira página HTML.

#### Ferramentas utilizadas
VS Code,extensões:
* Live server
* (Emmet, já inclusa por padrão)
* Google chrome
* Usando o Inspetor  Elementos (Recurso disponível no navegador.)
 
#### Estrutura básica do HTML
* <html>
* <head></head> - informações carregadas antes do usuário
* <body></body> - informações que aparecem para o usuário.

#### Falando sobre Tags                                                                   
Tudo entre as tags vai ser executado conforme a interpretação do navegador.                                                                      
<strong></Strong> negrito <i></i> itálico - ex tags com fechamento

<input> tag sem fechamento que inseri um campo de preenchimento.
<input type=“text”> atribui o tipo de preenchimento
<input type= “number”>

* Atributos básicos das Tags
* <strong id=“titulo”> identificador deste elemento para o javascripty
* <strong style=”titulo"> style serve para o css aplicar estilos no elemento
* <strong class=”titulo principal"> formatar padrão uma classe de elementos

<input type=“text”> insere um campo de preenchimento de acordo com o tipo da informaçao
<input type=“number”>
<input type=“color”>

<img / kjdkslj.jpg”> endereço de arquivos de imagem
<img src=“https://klsfjdhfieh.com”>
<img width=“250” src=“https://klsfjdhfieh.com”>

<br> espaço entre as linhas
<hr /> linha separadora

<body bgcolor=“#8792” ou “nome da Cor”> mudar cor de fundo. Não funciona a partirdo html5
<body background=“endereço de imagem”> imagem no plano de fundo em .gif ou jpg
 
#### Executando uma página HTML
(exemplo no  index.html)
  
#### Falando sobre textos
 h1, h2, h3, h4, h5, títulos com (fechamento)
 <p> parágrafo</p>
 <i> italico</i> 
 <u> sublinhado</u> 
 <strong>negrito</strong> 
 <mark> marca texto</mark>
 <u> sublinhar </u>
 <sup>*&*#r®</sup>
 <small>voltar</small>
  
#### Lista ordenada e não  ordenada                             
(Usar li para as enumerações dentro de ol ou ul.)

#### Links
 <a href=“endereço do site”>Nome que será exibido</a> abre na mesma aba
 <a href=“endereço do site” target=“_blank”>Nome que será exibida</a> abre outra aba
 <a href=“endereço do site” title=“clique e conheça”>Nome que será exibido</a> abre um tool tip que ajuda a navegação
**Ancoragem: usada para buscar na página um item marcado
 <a href=“ ”></a>
 <ul>
 <li><a href=“#assunto1”> Assunto 1</a>
 </li></ul>

 (necessário fazer uma atrtibuição id=”” para cada título de referência, além da lista)

