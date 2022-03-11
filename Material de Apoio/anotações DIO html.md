# Arquivo para anotações de aprendizado sobre html
## Aula 1 - Estrutura Básica
criando um arquivo index.html com as tags de estruta básica:
 !DOCTYPE html - 
 html - onde fica todo o conteúdo da página
    head - possui informações que o navegador necessita para "entender" o arquivo. Geralmente possui as tags meta e title
        meta - tag utilizada para fornecer as informações citadas no 'head'
        title - fornece o título existente na aba do navegador
    body - lugar onde se localiza todo o conteúdo da página

### Exemplo da estrutura básica de um arquivo html:
!DOCTYPE html 
html

    head
        meta
        title"título da aba"/title
    /head
    body
    /body
/html


## Aula 2 - Semântica
Entendendo as semânticas e adicionado as tags:
 header/header -  Para adicionar um cabeçalho (podendo haver mais de um como em sections, articles, etc)
 h'x'/h - X de 1 à 6. Para por como título de página, seção, etc
 section/section - divide o conteúdo da página em uma seção afim de descrever um determinado assunto
 article/article - representa um conteúdo relevante na página
 aside/aside - representa um conteúdo relacionado ao conteúdo da página (links relacionados, biografia de um autor)
 footer/footer - rodapé da página ou de parte dela (section, article, etc)
  

## Aula 3 - Textos e Links
Tags para textos:
 hx/h - de 1 à 6, utilizado para dar títulos
 p/p - representa um parágrafo (não apenas para textos)
Tags para links:
 a'y'/a - interliga vários conteúdos da web
     atributos: y = href e y = target (existem mais tipos)
     a href="link"/a - hiperlink para um site externo (para email, colocar o prefixo mailto, para telefone, colocar o prefixo tel)
     a target="_blank"/a - indica como o link será aberto (o exemplo "_blank" serve para abrir o link em uma nova página)


## Aula 4 - Imagens
Para anexar uma imagem usa-se a tag 'img' (obs: não possui fechamento)
Usa-se 'img src="caminho da imagem"' como elemento obrigatório o qual mostra o diretório da imagem e anexa a mesma na página
Usa-se 'img alt="descrição da imagem" como elemento de descrição que aparecerá no lugar da imagem se a mesma não for carregada
Exemplo:
img src="workspace/img_logo" alt="logo do site"

## Aula 5 - Adicionando Listas
ul/ul - lista em que a ordem dos itens não é importante/relevante
ol/ol - a ordem da lista é importante e tem representação com números, letras, etc
li/li - item da lista