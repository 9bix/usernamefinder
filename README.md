* Primeiro passo - instalar o Node.js
  Você precisa ter o Node.js instalado no computador. Baixe no site oficial: [https://nodejs.org](https://nodejs.org) e instale a versão LTS. Depois de instalar, abra o CMD ou terminal e digite `node -v`. Se aparecer uma versão como `v20.x.x`, significa que está funcionando.

* Segundo passo - criar a pasta do bot
  Crie uma pasta em qualquer lugar do seu computador, por exemplo chamada `username-gen-bot`. Dentro dessa pasta você vai colocar os arquivos do bot.

* Terceiro passo - adicionar o arquivo do bot
  Coloque o arquivo `bot.js` dentro da pasta que você criou.

* Quarto passo - criar o package.json
  Dentro da mesma pasta crie um arquivo chamado `package.json` e coloque este conteúdo dentro dele:

{
"name": "username-gen-bot",
"version": "1.0.0",
"main": "bot.js",
"dependencies": {
"axios": "^1.6.0",
"discord.js": "^14.15.3"
}
}

* Quinto passo - instalar as dependências
  Abra o terminal ou CMD dentro da pasta do bot e digite `npm install`. Isso vai instalar as bibliotecas necessárias como discord.js e axios. Depois disso a pasta vai ter os arquivos `node_modules` e `package-lock.json`.

* Sexto passo - colocar o token do bot
  Abra o arquivo `bot.js` e procure a linha `const TOKEN = "SEU_TOKEN_AQUI"`. Substitua pelo token do seu bot do Discord Developer Portal. Nunca compartilhe esse token com outras pessoas.

* Sétimo passo - iniciar o bot
  No terminal dentro da pasta do bot digite `node bot.js`. Se tudo estiver correto vai aparecer algo como `Logado como NomeDoBot` e `Slash commands atualizados`.

* Oitavo passo - usar o bot no servidor
  No Discord, dentro do servidor onde o bot está, digite `/menu`. Vai aparecer o menu com os modos RR, 5N, 4L e os botões LIST e UPDATE LIST para ver ou atualizar os usernames encontrados.

* Arquivo criado automaticamente
  O bot cria automaticamente um arquivo chamado `found.json`. Esse arquivo salva todos os usernames que o bot encontrou disponíveis para que eles não se repitam.

* Problemas comuns
  Se o bot não iniciar, verifique se rodou `npm install`.
  Se o comando `/menu` não aparecer, espere alguns segundos depois de iniciar o bot ou reinicie ele.
  
