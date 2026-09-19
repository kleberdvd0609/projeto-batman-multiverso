#  Batman Multiverse

## Sobre o Projeto
Este é um projeto acadêmico desenvolvido para a disciplina de **Desenvolvimento Front-End** (Prof. Israel Cunha). Foi construído **exclusivamente com HTML5 semântico**, sem o uso de CSS ou frameworks, com o objetivo de demonstrar a organização estrutural da linguagem.

A ideia central do projeto foi criar um dossiê interativo catalogando os seis atores que interpretaram o Batman no cinema, juntamente com o registro criminal de cinco de seus maiores vilões (Charada, Coringa, Duas-Caras, Mulher-Gato e Pinguim).

##  Estrutura e Navegação
Na página principal (Terminal Central), o usuário encontra:
* **Menu de Navegação:** Uma tag `<nav>` global logo abaixo do `<header>`, permitindo uma navegação fluida entre os dossiês de heróis e vilões.
* **Lore do Personagem:** Uma seção descritiva sobre a história do Cavaleiro das Trevas.
* **Imersão Multimídia:** Três trilhas sonoras clássicas inseridas através da tag `<audio>` para proporcionar nostalgia durante a leitura.
* **Avisos do Sistema:** O uso estratégico da tag `<aside>` para destacar notas do desenvolvedor e o link para a pesquisa de satisfação.

##  Dossiês de Personagens
Para as subpáginas dos personagens, o código seguiu um esqueleto semântico rigoroso e padronizado. O dossiê de cada personagem fictício foi estruturado utilizando as seguintes tags HTML5:
* `<article>`, `<section>`, `<header>`, `<main>`, `<footer>`
* `<figure>` e `<figcaption>` para imagens e fotografias.
* `<details>` e `<summary>` para ocultar/mostrar inventários e níveis de ameaça.
* `<blockquote>` para citações clássicas dos filmes.

##  Formulário de Avaliação
O projeto conta com um questionário de avaliação criado para demonstrar o domínio de formulários web. Estruturado com a tag `<form>`, ele permite a coleta de dados do usuário através de:
* `<input>` e `<label>` para identificação e escolha do Batman favorito (via radio buttons).
* `<select>` e `<option>` para o menu suspenso de escolha do vilão favorito.
* `<input type="number">` para emissão de uma nota de 0 a 10 para o site.
* `<textarea>` para envio de comentários e sugestões.

## Autoria
Para padronizar o fechamento do projeto, todas as páginas contam com um `<footer>` global. Dentro dele, foi empregada a tag `<address>` para indicar a assinatura acadêmica, curso e autoria (Kleber David) como desenvolvedor do sistema.