<h1 align="center"> Encriptador de Texto </h1>
![Encriptador] (https://github.com/user-attachments/assets/2bdd352e-7c35-4e2e-baad-06de01013f39)

/</div>
> Table of Contents
> <ul>
>   <li><a href="#o-projeto">sobre</a></li>
>   <li><a href="#-funcoes">Como funciona</a></li>
>   <li><a href="#-telas">Screenshots</a></li>
>   <li><a href="#-tecnologias">Tecnologias</a></li>
> >  <li><a href="#-licença">Licença</a>
> </ul>

## O projeto

Esse projeto é um Codificador e Decodificador de texto feito com javascript, html e css. 
Foi realizado como um Challenge de Encriptador de Texto, do Programa Oracle ONE da Alura.

## Como funciona

Essa aplicação criptografa textos, possibilitando a troca de mensagens secretas com outras pessoas que saibam o segredo da criptografia utilizada.

As "chaves" de criptografia utilizadas são:
A letra "e" é convertida para "enter"
A letra "i" é convertida para "imes"
A letra "a" é convertida para "ai"
A letra "o" é convertida para "ober"
A letra "u" é convertida para "ufat"

Requisitos:
- Deve funcionar apenas com letras minúsculas
- Não devem ser utilizados letras com acentos nem caracteres especiais
- Deve ser possível converter uma palavra para a versão criptografada e também retornar uma palavra criptografada para a versão original.

Por exemplo:
"gato" => "gaitober"
gaitober" => "gato"

A página deve ter campos para inserção do texto a ser criptografado ou descriptografado, e a pessoa usuária deve poder escolher entre as duas opções
O resultado deve ser exibido na tela.
Extras:
- Existe Um botão que copie o texto criptografado/descriptografado para a área de transferência - ou seja, que tenha a mesma funcionalidade do ctrl+C ou da opção "copiar" do menu dos aplicativos.

##  Screenshots

<details><summary>Desktop:</summary>
<img src="https://user-images.githubusercontent.com/90913523/191306451-f8232c67-6c01-4259-98c9-e5afbd459aab.png" width="900"></details>

<details><summary>Tablet:</summary>

<img src="https://user-images.githubusercontent.com/90913523/191306502-7a314618-cf0a-4622-956a-3594401f024c.png" width="600"></details>

<details><summary>Mobile:</summary>

<img src="https://user-images.githubusercontent.com/90913523/191306534-9dcff814-d996-4292-bbf0-a64f8117d258.png" height="1000" ></details>

## Tecnologias utilizadas

- Javascript
- CSS
- HTML


## 🚀 Rodando localmente

Caso queira fazer modificações no site, siga estes passos:

Clone o projeto

```bash
  git clone https://github.com/Aliine98/decodificador
```

Entre no diretório do projeto

```bash
  cd decodificador
```

E abra o <code>index.html</code> no navegador ou, caso use o VScode, instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) e clique no botão <ins><strong>Go Live</strong></ins>, se não pode instalar o http-server para que suas modificações sejam recarregadas automaticamente em seu navegador

```bash
  npm install http-server
```
Abra o servidor

```bash
  http-server ./
```

Será mostrado os links do servidor, clique ou copie e abra no navegador.
<p>Após a instalação do http-server também adicione um <code>.gitignore</code> com a pasta node_modules.</p>

Utilize o comando abaixo para saber mais sobre o http-server:

```bash
  npm docs http-server
```

## 😯 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)

## 📝 Licença

![License](https://img.shields.io/github/license/Aliine98/decodificador?style=for-the-badge)

Feito com ❤️ por Aline Bevilacqua!﻿# Encriptador
