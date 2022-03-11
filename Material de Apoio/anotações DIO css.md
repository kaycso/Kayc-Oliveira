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