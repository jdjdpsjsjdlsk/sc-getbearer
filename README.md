# Socialclub-GetBearer

### This was build using nodejs v16.17.1

Get the BearerToken from RockstarGames Socialclub website

This is only the base for your own project to get the bearertoken, i also have an functional API here https://github.com/jdjdpsjsjdlsk/rsg-socialclub-api

Setup:
```
git clone https://github.com/jdjdpsjsjdlsk/sc-getbearer.git
cd sc-getbearer
npm install
```

or if you already have it downloaded:

```
npm install dotenv puppeteer node-schedule
```

For the first start go into .env file and set SC_LOGIN to true.

Start the script with `npm run start` or `node .` and login to the browser window that opens and make sure to check Remember Me to stay logged in.

Stop the script and set SC_LOGIN back to false now just start and let it run to always get fresh bearertoken.

This only gets the bearertoken you need to add an API or discord-bot or whatever yourself.
