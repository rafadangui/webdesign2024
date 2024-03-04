# Guia HTML 5
**HTML** – (HyperText Marckup Language) Linguagem de Marcação de Hiper Texto, é uma linguagem de marcação que o desenvolvedor usa para se comunicar com o navegador do usuário, este que por sua vez transforma a marcação em algo que o usuário entenda, como um site. 
Podemos considerar o **HTML** como um idioma de comunicação entre o desenvolvedor e o dispositivo do usuário.
Como qualquer idioma, o **HTML**, também tem suas regras de sintaxe e escrita, e um arquivo de texto escrito em conformidade com essas regras chamada marcação **HTML** ou estrutura **HTML**.

## Estrutura de uma _tag_ HTML
O **HTML** utiliza comandos para exibir conteúdo para o usuário, esses comandos são chamados de _tags_ **HTML**. As _tags_ tem uma estrutura básica, onde a _tag de abertura_ é inserida antes do conteúdo e a _tag de fechamento_ é inserida após o conteúdo

```html
<h1>Primeira página web</h1>
<p>Está é minha primeira página web</p>
```
Uma _tag_ **HTML** é constituída por uma ou mais letras, ou letra e números, que devem ser escritas entre os sinais **<** e **>**. A _tag de fechamento_ é igual à _tag de abertura_ com um sinal de barra **/** na frente.

## Estrutura básica de um documento HTML
Dentro de um documento de marcação **HTML** não podemos simplesmente "jogar" _tags_, todo documento deve ter uma estrutura básica, elementos (_tags_), responsáveis por configurações e também exibição de conteúdo para o usuário.
1. Todo documento **HTML** inicia com a declaração do tipo de documento. Essa declaração informa ao navegador do usuário que a marcação que segue é do tipo **HTML5** (Padrão universal). Essa marcação não é uma _tag_ **HTML**.
```html
<!DOCTYPE html>
```
2. Após a declaração do tipo do documento devemos iniciar as _tags_ do elemento raiz do documento **HTML**. O elemento raiz engloba toda a marcação **HTML**. A _tag_ raiz também deve conter a linguagem da página, no nosso caso **Portugues Brasil**, essa configuração é representada pelo valor: **pt-br**. A informação do idioma da página é importante para que tecnologias assistivas, como leitores de texto, possam identificar o idioma e ler o conteúdo com a pronuncia adequada. Essa configuração deve ser feita por meio de um atributo chamado **lang**. Voltando ao elemento raiz, ele deve ter a _tag_ de aberto e de fechamento do documento.
```html
<!DOCTYPE html>
<html lang="pt-br">

</html>
```
3. Todo conteúdo **HTML** de um documento fica aninhado dentro da _tag_ raiz, o próximo elemento **HTML** que deve conter no documento são as configurações de cabeçalho. As informações de cabeçalho são importantes pois possibilitam que o desenvolvedor exiba informações, como o título da página, como também configure parâmetros e arquivos adicionais que iram compor o documento, como por exemplo arquivos de formatação **CSS** (Cascading Style Sheets) Folha de Estilo em Cascata. A _tag_ de cabeçalho é representada pelo elemento **HEAD**, esse elemente apresenta-se como uma seção, pois aceita vários outros elementos dentro dele. Assim como outros elementos **HTML** necessita da _tag de abertura e fechamento.
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head></head>
</html>
```
4. As informações que são exibidas para o usuário devem ficar em uma seção específica do documento **HTML** essa seção é chamada de corpo do documento, representada pela _tag_ **BODY**. Todos os elementos **HTML** que estiverem dentro da tag **body** serão renderizados (exibidos) na ordem que estão no documento. A seção **BODY** aceita muitos elementros **HTML** dentro dela, ao todo temos 108 elementos **HTML** que podem compor um documento. A _tag_ **body** fica logo após a _tag_ **head**, também necessita de _tag_ de abertura e fechamento.
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head></head>
  <body></body>
</html>
```
```html
<!DOCTYPE html> -> Define o tipo de documento
<html lang="pt-br">  -> Abertura do bloco HTML
  <head></head> -> Seção do cabeçalho do documento
  <body></body> -> Seção do corpo do documento
</html> -> Fechamento do bloco HTML
```
### Elementos básicos do HEAD
A seção do **HEAD** necessita de pelo menos dois elementos, o primeiro é o elemento/_tag_ que forma o título da página e o segundo o elemento/_tag_ de configuração da codificação do documento.
1. O título de uma página é exibido na barra de títulos da aba, onde a página está sendo exibida, no navegador do usuário. Elemento com carater informativo, mas muito útil para que o usuário saiba identificar qual página está acessando. O título é composta pela _tag_ **TITLE**, assim como outras _tags_ necessita de abertura e fechamento. O conteúdo é inserido entre as _tags_ de abertura e fechamento.
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Minha página web</title>
  </head>
  <body></body>
</html>
```
2. A codificação do arquivo **HTML** importante para que usuários localizados em diferentes países possam visualizar páginas cujo idioma contenha caracteres especiais sem a exibição de erros. A configuração de codificação do documento é inserida logo após o título da página, essa configuração é passada para o navegador do usuário através da _tag_ **META**. Essa _tag_ também é utilizada para muitas outras configurações. A codificação é representada pelo atributo **charset**, esse atríbuto necessita de um valor, assim como a **lang**, sendo o valor padrão **utf-8**, padrão amplamento utilizado.
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Minha página web</title>
    <meta charset="utf-8">
  </head>
  <body></body>
</html>
```

### Elementos de exibição
- [P](elementosexibicao.md#P)
- [H1-H6](elementosexibicao.md#H1-H6)
- [HR](elementosexibicao.md#HR)
- [SPAN](elementosexibicao.md#SPAN)
- [DIV](elementosexibicao.md#DIV)
