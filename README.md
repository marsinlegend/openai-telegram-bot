# openai-telegram-bot

openai telegram bot for private messages &amp; groups

## Usage

```bash
git clone https://github.com/discountry/openai-telegram-bot.git
cd openai-telegram-bot

npm i

cp example.config.js config.js

# edit config.js with your token and api key
vim config.js

# test
node index.js

# run in background
npm install -g pm2

pm2 start index.js
```

# Interactions

**/ask**

ask normal questions or let the bot write code for you.

```
/ask how old are you
```

**/fix**

get grammer and typo fix.

```
/fix he am dgo
```

**/image**

get image reply from dalle2 model.

```
/image doge with twitter to the moon
```

**/reload**

reload chat history. The bot will forget everything.

```
/reload
```