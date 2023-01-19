<h1 align="center">

<img src="https://raw.githubusercontent.com/khalleb/ignews/main/public/images/avatar.svg" alt="rocketshoes" width="100px"/>

</h1>

<p align="center">
  Chat GPT - Integração WhatsApp 
  <br>
  <br>

  <img alt="Language count" src="https://img.shields.io/github/repo-size/khalleb/ignews"/>

  <a href="https://github.com/douglasgmsantos">
    <img alt="Made by douglasgmsantos" src="https://img.shields.io/badge/made%20by-douglasgmsantos-%237519C1">
  </a>

  <a href="https://github.com/victorharry">
    <img alt="Made by Victorharry" src="https://img.shields.io/badge/made%20by-Victorharry-%237519C1">
  </a>

  <a href="https://github.com/douglasgmsantos/chat-gpt-com-whatsapp/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/douglasgmsantos/chat-gpt-com-whatsapp">
  </a>

  <img alt="License" src="https://github.com/douglasgmsantos/chat-gpt-com-whatsapp">
</p>

---

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a> &#xa0; &#xa0; | &#xa0;
  <a href="#framed_picture-referência">Créditos</a> &#xa0; &#xa0;
</p>

<br>

## :dart: Sobre ##
O projeto chat-gpt-com-whatsapp é uma integração que pode ser utilizada para perguntar e receber as respostas via WhatsApp utilizando o Chart GPT.
<br>

## :rocket: Tecnologias ##

As seguintes tecnologias foram utilizadas no projeto:

- [dotenv](https://www.npmjs.com/package/dotenv)
- [openai](https://openai.com/)
- [venom-bot](https://github.com/orkestral/venom)

## :white_check_mark: Requerimentos

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/)

## :checkered_flag: Começando ##

```bash
# Clone this project
$ git clone https://github.com/douglasgmsantos/chat-gpt-com-whatsapp

# Acessar pasta
$ cd chat-gpt-com-whatsapp

# Instalar Dependências?
$ yarn add

# Pegar a API Key e Organization ID na OpenAI
A primeira coisa que precisamos aqui é da api key da openai, uma chave para autorização de envio das nossas requisições. Entre neste link para pegar sua chave https://beta.openai.com/account/api-keys, é bem auto explicativo.

# API Key na open api
Para pegar o organization ID também é bem fácil, é só acessar este link e copiar o seu ID https://beta.openai.com/account/org-settings

# Preencher variaveis de ambiente.
Substituir o arquivo, .env.example por.env e substituir as chaves.

# Rodar o projeto
$ node .

# Leitura do QR Code
Após aguardar alguns instantes será gerado um QR Code que deve ser lido pelo aplicativo do WhatsApp. 
Em seu aplicativo toque em “Mais opções” ou “Configurações”, selecione “Aparelhos conectados”.
Depois selecione a opção “Conectar um aparelho” para ler o QR Code gerado.

# Após o processo de leitura do QR Code, manda uma mensagem para você mesmo com o comando /bot "Mensagem"
# Exemplo: /bot Ordenar uma lista de números do maior para o menor 
```

## :star: Créditos ##
Todos os créditos ao  <a href="https://github.com/victorharry"> <img alt="Made by Victorharry" src="https://img.shields.io/badge/made%20by-Victorharry-%237519C1">
 </a>, que disponibilizou um  <a href="https://www.tabnews.com.br/victorharry/guia-completo-de-como-integrar-o-chat-gpt-com-whatsapp" _target="_blank"> artigo </a> bem bacana e simples, explicando passa a passa de como criar esse projeto.
 
 
