<h1 align="center"> Encriptador de Texto </h1>

 
## Descrição do Projeto
<p align="left"> Esse projeto é um Codificador e Decodificador de texto feito com javascript, html e css. 
Foi realizado como um Challenge de Encriptador de Texto, do Programa Oracle ONE da Alura.</p>

## Como funciona

Essa aplicação criptografa textos, possibilitando a troca de mensagens secretas com outras pessoas que saibam o segredo da criptografia utilizada.<p>

As "chaves" de criptografia utilizadas são:
- A letra "e" é convertida para "enter"
- A letra "i" é convertida para "imes"
- A letra "a" é convertida para "ai"
- A letra "o" é convertida para "ober"
- A letra "u" é convertida para "ufat"

Requisitos:
- Deve funcionar apenas com letras minúsculas
- Não devem ser utilizados letras com acentos nem caracteres especiais
- Deve ser possível converter uma palavra para a versão criptografada e também retornar uma palavra criptografada para a versão original.

Por exemplo:
- "gato" => "gaitober"
- gaitober" => "gato"

A página deve ter campos para inserção do texto a ser criptografado ou descriptografado, e a pessoa usuária deve poder escolher entre as duas opções.
O resultado deve ser exibido na tela.

Extras:
- Existe um botão que copie o texto criptografado/descriptografado para a área de transferência - ou seja, que tenha a mesma funcionalidade do ctrl+C ou da opção "copiar" do menu dos aplicativos.

- Criptografia: Converte texto claro em uma forma criptografada usando regras de substituição.
- Descriptografia: Reverte o texto criptografado para seu formato original.
- Validação de Texto: Garante que apenas letras minúsculas e sem acento sejam usadas.
- Copiar para Área de Transferência: Permite copiar o texto criptografado/descriptografado para a área de transferência.
- Feedback ao Usuário: Mostra mensagens de alerta e feedback conforme necessário.

## Tecnologias
- HTML5: Estruturação da página.
- CSS3: Estilo e layout responsivo.
- JavaScript: Lógica de criptografia/descriptografia e manipulação DOM.

## Como Usar

1. Clone o repositório:

git clone 

2. Abra o arquivo index.html no seu navegador

## Exemplo 

- Criptografar:<p>
   Digite: `ola mundo`<p>
   Resultado: `oberlai mufatndober`

- Descriptografar:<p>
   Digite: `oberlai mufatndober`<p>
   Resultado: `ola mundo`
