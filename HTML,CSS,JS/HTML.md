# HTML

Com o HTML definimos o significado e a estrutura do conteúdo da web, com o HTML podemos adicionar, além do text, imagens, vídeos e vários outros formatos na página.

Um elemento HTML é formado pela tag de abertura(<) e seus atributos, o conteúdo e uma tag de fechamento(/>)

Alguns elementos não tem tag de fechamento

## Estrutura básica do html

A primeira linha do documento deve ser o `<!DOCTYPE html>` , ela diz ao navegador que ele está lidando com um arquivo do tipo HTML5.

*`<html>`*

A tag html é a raiz do documento, **todos** os elementos html devem estar dentro dela. Aqui informamos ao navegador o idioma do documento, através do atributo **lang** (pt-BR, para português)

*`<head>`*

A tag head contém elementos que serão lidos pelo navegador, como metadados, o JavaScript (com a tag script), o CSS (com as tags style e link) e o título da página (com a tag title).

*`<body>`*

Na tag body colocamos todo o conteúdo **visível** ao usuário: textos, imagens, vídeos, etc.

## Semântica

*`<section>`*

Representa uma seção genérica de conteúdo quando não houver um elemento mais específico para isso.

*`<header>`*

É o cabeçalho da página ou de uma seção, normalmente contém logotipos, menus e campos de busca.

*`<article>`*

Representa um conteúdo independente e de maior relevância dentro de uma página, como notícias em uma barra lateral ou bloco de comentários. Pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens.

*`<aside>`*

É uma seção que engloba conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografia do autor e publicidade.

*`<div>`*

Define uma divisão da página, funciona como um container para conteúdo de fluxo.

*`<footer>`*

Representa o rodapé do conteúdo ou de parte dele.

*`<h1> - <h6>`*

Utilizados para marcar a importância dos títulos, sendo o `<h1>` o mais importante e o `<h6>` o menos.

## Textos e links

*`<p>`*

Representa um parágrafo, onde além de texto, podemos também adicionar imagens, código, vídeos e outros tipos de conteúdo

*`<a>`*

Representa um hyperlink, interliga vários conteúdos e páginas na web. O elemento tem vários atributos, como href e target. O href representa o hyperlink para onde o elemento `<a>` aponta.

## Formulário

*`<input>`*

Possui o atributo type, que varia entre diversos tipos,
