# Deninho

Repositório contendo o código do bot em execução no canal [@pachicodes][1].

# Executando

Para executar este projeto, você precisa do [NodeJS][2] instalado e um token de acesso para uma conta existente na Twitch. Pode-se utilizar usa própria conta para testes, mas o ideal é ter uma exclusiva para o bot.

Para obter o token, entre [neste serviço][3] e autorize-o a ter acesso a sua conta da Twitch. Guarde o token obtido em um local seguro. Com o token em mãos: clone este repositório, instale as dependências, defina as variáveis de ambiente e execute a aplicação:

```
git clone https://github.com/pachicodes/deninho-bot.git

cd ./deninho-bot
npm install

BOT_NAME=dininhobot         # nome de usuário da sua conta.
CHANEL_NAME=pachicodes      # canal que irá escutar pelos comandos.
TOKEN=                      # token de acesso obtido anteriormente.

node index.js

    Bot is running at irc-ws.chat.twitch.tv:80
```

# Contribuindo

- Crie uma branch a partir da `main`, exemplo: `git checkout -b minha-branch`.
- Faça o commit das suas alterações e envie um novo pull request tendo a branch `main` como destino.

[1]: https://www.twitch.tv/pachicodes
[2]: https://nodejs.org/en/download/
[3]: https://twitchapps.com/tmi/
