<div align="center">
  <br />

  <h1>Username Generator Bot</h1>

  <p>
    <img src="https://img.shields.io/badge/Node.js-LTS-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/discord.js-v14.15.3-5865F2?style=flat-square&logo=discord&logoColor=white" alt="discord.js" />
    <img src="https://img.shields.io/badge/axios-v1.6.0-5A29E4?style=flat-square&logo=axios&logoColor=white" alt="axios" />
    <img src="https://img.shields.io/badge/JavaScript-Node.js-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  </p>

  <br />
</div>

---

## Primeiro passo - instalar o Node.js

Você precisa ter o Node.js instalado no computador. Baixe no site oficial: [https://nodejs.org](https://nodejs.org) e instale a versão LTS. Depois de instalar, abra o CMD ou terminal e digite `node -v`. Se aparecer uma versão como `v20.x.x`, significa que está funcionando.

---

## Segundo passo - criar a pasta do bot

Crie uma pasta em qualquer lugar do seu computador, por exemplo chamada `username-gen-bot`. Dentro dessa pasta você vai colocar os arquivos do bot.

---

## Terceiro passo - adicionar o arquivo do bot

Coloque o arquivo `bot.js` dentro da pasta que você criou.

---

## Quarto passo - criar o package.json

Dentro da mesma pasta crie um arquivo chamado `package.json` e coloque este conteúdo dentro dele:

```json
{
"name": "username-gen-bot",
"version": "1.0.0",
"main": "bot.js",
"dependencies": {
"axios": "^1.6.0",
"discord.js": "^14.15.3"
}
}
