# Elementos de Exibição
Os elementos/_tag_ de exibição são responsáveis por exibir conteúdo para o usuário, em sua grande maioria textos.

## Itens do documento
- [P](#P)
- [H1-H6](#H1-H6)
- [HR](#HR)
- [SPAN](#SPAN)
- [DIV](#DIV)

## P
O elemento **P** é responsável por colocar o conteúdo, dentro das _tags_ de abertura e fechamento, em um parágrafo no documento **HTML**. Esse parágrafo pode conter quantas linhas, caracteres e palavras que forem necessárias. Também podendo existir quantos blocos de _tag_ **p** forem necessárias no documento **HTML**.
- Exemplo 1:
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Minha página web</title>
    <meta charset="utf-8">
  </head>
  <body>
    <p>Essa é minha primeira página web</p>
  </body>
</html>
```
- Exemplo 2:
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Minha página web</title>
    <meta charset="utf-8">
  </head>
  <body>
    <p>Essa é minha primeira página web</p>
    <p>Ela foi feita utilizando HTML 5</p>
  </body>
</html>
```
[:arrow_up: Voltar ao topo](#Elementos)

## H1-H6
O elemento **H** é responsável pela criação de títulos no conteúdo **HTML**. A _tag_ **H** necessita de um número após, esse número identifica o nível do título, podendo ir do 1 ao 6, sendo o primeiro o mais alto e o segundo o mais baixo. De forma geral o número identifica o tamanho que o título será exibido para o usuário. O conteúdo deve estar entre as _tags_ de abertura e fechamento.
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Minha página web</title>
    <meta charset="utf-8">
  </head>
  <body>
    <h1>Página Web</h1>
    <p>Essa é minha primeira página web</p>
  </body>
</html>
```
## HR
O elemento **HR** destina-se a criar uma linha horizontal no navegador, usado especialmente como separação de conteúdo no documento **HTML**. A _tag_ **hr** é uma _tag_ simples, não necessitando de fechamento.
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Minha página web</title>
    <meta charset="utf-8">
  </head>
  <body>
    <p>Essa é minha primeira página web</p>
    <hr>
    <p>Ela foi feita utilizando HTML 5</p>
  </body>
</html>
```
## SPAN
O elemento **SPAN** é um elemento do tipo _inline_, destinado a criar um container geral para outros elementos, ou sejá, não tem uma destinação específica. A _tag_ **span** não é renderizada no navegador do usuário, parecendo não estar presente. A _tag_ **span** é utilizada em níveis mais avançados, principalmente para formação, podendo aplica formatação apenas ao conteúdo que estiver dentro dela. É um elemento **HTML** que necessita de abertura e fechamento e seu conteúdo fica entre as duas _tags_.
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Minha página web</title>
    <meta charset="utf-8">
  </head>
  <body>
    <p>Essa é minha <span>primeira</span> página web</p>
    <hr>
    <p>Ela foi feita utilizando HTML 5</p>
  </body>
</html>
```
## DIV
O elemento **DIV** também um elemento que cria um container geral, podendo receber outros elementos **HTML** dentro dele. Não tem aspecto visual na renderização, mas é muito utilizado em níveis avançado como elemento de separação e formatação de seções da página web. A _tag_ **div** contém abertura e fechamento, podendo deceber outros elementos **HTML** entre as _tags_.
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Minha página web</title>
    <meta charset="utf-8">
  </head>
  <body>
    <div>
      <h2>Sub seção da página</h2>
      <p>Essa é minha <span>primeira</span> página web</p>
    </div>
    <hr>
    <div>
      <h3>Outra seção na página</h3>
      <p>Ela foi feita utilizando HTML 5</p>
    </div>
  </body>
</html>
```
