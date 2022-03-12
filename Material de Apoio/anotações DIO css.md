# Arquivo para anotações de aprendizado sobre CSS
## aula 1 - introdução e conceitos básicos
O css serve para oferecer uma formatação à página criada. Nele podemos mudar a fonte de um texto, alterar sua cor, seu tamanho, mudar o plano de fundo, etc.
Uma regra css é formada por seletor(es), que são os elementos html, e declarações - propriedades de formatação.
Obs: ao fazer a seleção de um elemento html para formatação, esse elemento terá essa mesma formatação repetida em todo o código, se o mesmo tiver repetições no arquivo html.

### ID e Class
Para conseguir formatar um elemento específico, mas que se repete no restante do código html, é necessário fazer a utilização do ID e/ou class no próprio arquivo html.
o ID só pode ser utilizado uma vez na página e, em seu código css, é precedido de um hashtag (#). Exemplo: #header {...}.
a Class não possui problema de utilizações e, em seu código css, é precedida por uma ponto (.). Exemplo: .header {....}

### Box Model
O navegador identifica cada elemento html com uma caixa retangular chamada de Box Model. Com o css é possível fazer alterações na aparência dessa caixa.
#### As 4 áreas do box model:
1. Margin: representa o espaçamento entre os elementos
2. Border: circundam o pading e o conteúdo (content). São alteráveis sua largura e cor
3. Pading: espaçamento entre o border e o content.
4. Content: conteúdo do bloco (texto/imagem/vídeo)


## Aula 2 - estilizando elementos, textos e listas
## Estilizando elementos:
### Formatando tamanhos do padding e margin:
- padding: 'A'px; (onde A representa um número e px informa que a medida está em pixel)
- padding: 'A'px 'B'px; (para este caso o Apx irá alterar no tamanho relacionado à parte superior e inferior e Bpx altera o tamanho relacionado aos lados - esquerda e direita)
- padding: 'A'px 'B'px 'C'px 'D'px; (onde Apx altera o tamanho superior, Bpx na direita, Cpx na parte inferior e Dpx na esquerda)
- padding-top: 'A'px; (altera o tamanho na parte superior)
- padding-right: 'A'px (altera o tamanho na parte direita)
- paddig-bottom: 'A'px (altera o tamanho na parte inferior)
- padding-left: 'A'px (altera o tamanho na parte esquerda)

### background
- background-color: "nome em inglês da cor"; (altera o fundo para a cor selecionada pelo nome em inglês)
- background-img: url("caminho da imagem"); (adiciona uma imagem)
- background-position: top; (muda o posicionamento da imagem: esse exemplo a imagem foi modificada para o topo)
obs: site para estudo - mozila developer network
#### Modificando cores de fundo
- background-color: "nome em inglês da cor"; (altera o fundo para a cor selecionada pelo nome em inglês)
- background-color: #008800; (altera o fundo para a cor selecionada pelo seu código)
- background: #008800; (altera o fundo para a cor selecionada por seu código porém sem precisar utilizar o póx-fixo '-color')

### Border
A propriedade Border pode possuir 3 valores: largura, cor e estilo.
Largura: pixel, centimentros, milimetros, etc
Cor: nome em inglês, código, etc
Estilo: sólido, pontilhado, tracejado, etc
Exemplos:
- border: 3px solid blue; (cria uma borda do tipo sólida com 3px e cor azul)
- border-top: 2px dotted green; (altera o topo da borda para estilo pontilhado com cor verde)
- border-right: 4px dashed pink; (altera o lada direito da borda para um estilo tracejado com cor rosa)
Existem também as propriedades específicas para cada valor da borda;
- border-width: 'A'px; (relacionado à dimensões/tamanho da borda)
- border-color: 'nome/código'; (relacionado à cor da borda)
- border-style: 'estilo'; (relacionado ao estilo - sólido, tracejado...)
Também pode-se adicionar formatar apenas um lado com as propriedades específicas da borda:
- border-top-width: 'A'px; (modifica a largura da parte superior)
- border-top-color: 'nome/código'; (modifica a cor da parte superior)
- border-top-style: 'estilo'; (modifica o estilo da parte superior)

### Border-radius
Permite arredondar os cantos de um elemento. Suas unidades mais comuns são os pixels (px) e as porcentagens (%).
- border-radius: 10px; (altera todos os cantos do elemento)
- border-radius: 50%; (tranforma um elemento quadrado em um círculo)

## Estilizando textos:
### Font-family:
Altera a fonte do texto.
Exemplo: 
font-family: verdana;
font-family: verdana, arial;
### Font-size:
altera o tamanho do texto.
Exemplo:
font-size: 'A'px; (o exemplo fio dado em pixel, que é a forma mais utilizada, mas também pode ser dado em centímetros, etc)
### Font-style:
Modifica o estilo da fonte.
Exemplo:
font-style: italic; (muda a fonte para itálico)
### Font-weight
Modifica o "peso" da fonte.
Exemplo:
font-weight: bold; (modifica a fonte para negrito)
### Text-transform:
Alterna o texto entre maiúsculas e minúsculas.
Exemplo:
text-transform: uppercase; (modifica todo o texto para caixa alta)
text-transform: lowercase; (modifica todo o texto para caixa baixa)
text-transform: capitalize; (coloca toda primeira letra de cada palavra em maiúscula)
### text-decoration:
Muito usado para dar destaque ao texto:
Exemplo:
text-transform: underline; (sublinha o texto)
text-transform: overline; (coloca uma linha acima do texto)
text-transform: line-through; (passa uma linha ao meio do texto)

## Estilizando listas
### List-style-type:
Utilizado para alterar o tipo do marcador da lista.
Exemplo:
list-style-type: square; (em uma lista não ordenada - ul - altera o símbolo para um quadrado)
list-style-type: upper-roman; (em uma lista ordenada - ol - altera para algarismo romanos em maiúsculo)
list-style-type: "\1F44D"; (em uma lista não ordenada altera para o símbolo do emoji de like)
### list-style-img:
Altera o marcador para uma imagem.
Exemplo:
list-style-img: url("caminho da imagem");
