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
* &lt;html&gt;
* &lt;head&gt;&lt;/head&gt; - informações carregadas antes do usuário
* &lt;body&gt;&lt;/body&gt; - informações que aparecem para o usuário.

#### Falando sobre Tags                                                                   
* Tudo entre as tags vai ser executado conforme a interpretação do navegador.                                                                      
* &lt;strong&gt;&lt;/Strong&gt; negrito&gt;<&lt;i&gt&lt;/i&gt; itálico - ex tags com fechamento

* &lt;input&gt; tag sem fechamento que inseri um campo de preenchimento.
* &lt;input type=“text”&gt; atribui o tipo de preenchimento
* &lt;input type= “number”&gt;

#### Atributos básicos das Tags
* &lt;strong id=“titulo”&gt; identificador deste elemento para o javascripty
* &lt;strong style=”titulo"&gt; style serve para o css aplicar estilos no elemento
* &lt;strong class=”titulo principal"&gt; formatar padrão uma classe de elementos

* &lt;input type=“text”&gt; insere um campo de preenchimento de acordo com o tipo da informaçao
* &lt;input type=“number”&gt;
* &lt;input type=“color”&gt;

* &lt;img / kjdkslj.jpg”&gt; endereço local de arquivos de imagem
* &lt;img src=“https://klsfjdhfieh.com”&gt;
* &lt;img width=“250” src=“https://klsfjdhfieh.com”&gt;

* &lt;br&gt; espaço entre as linhas
* &lt;hr/&gt; linha separadora

* &lt;body bgcolor=“#8792” ou “nome da Cor”&gt; mudar cor de fundo. Não funciona a partirdo html5
* &lt;body background=“endereço de imagem”&gt; imagem no plano de fundo em .gif ou jpg
 
#### Executando uma página HTML
* (exemplo no  index.html)
  
#### Falando sobre textos
 * h1, h2, h3, h4, h5, títulos com (fechamento)
 * &lt;p&gt; parágrafo&lt;/p&gt;
 * &lt;i&gt; italico&lt;/i&gt; 
 * &lt;u&gt; sublinhado&lt;/u&gt; 
 * &lt;strong&gt;negrito&lt;/strong&gt; 
 * &lt;mark&gt; marca texto&lt;/mark&gt;
 * &lt;u&gt sublinhar &lt;/u&gt;
 * &lt;sup&gt;*&*#r®&lt;/sup&gt;
 * &lt;small&g;tvoltar&lt;/small&gt;
  
#### Lista ordenada e não  ordenada                             
* (Usar li para as enumerações dentro de ol ou ul.)

#### Links
* &lt;a href=“endereço do site”&gtNome que será exibido&lt;/a&gt abre na mesma aba
* &lt;a href=“endereço do site” target=“_blank”&gtNome que será exibida&lt;/a&gt abre outra aba
* &lt;a href=“endereço do site” title=“clique e conheça”&gtNome que será exibido&lt;/a&gtabre um tool tip que ajuda a navegação
* Ancoragem: usada para buscar na página um item marcado
* &lt;a href=“ ”&gt;&lt;/a&gt;
* &lt;ul&gt;
* &lt;li&gt;&lt;a href=“#assunto1”&gt; Assunto 1&lt;/a&gt;
* &lt;/li&gt;&lt;/ul&gt;

*(necessário fazer uma atrtibuição id=”” para cada título de referência, além da lista)

