# Socialclub-GetBearer
Get the BearerToken from RockstarGames Socialclub website

`npm install dotenv puppeteer node-schedule` for setup

For the first start go into .env file and set SC_LOGIN to true.

Start the script with `npm run start` or `node .` and login to the browser window that opens and make sure to check Remember Me to stay logged in.

Stop the script and set SC_LOGIN back to false now just start and let it run to always get fresh bearertoken.

This only gets the bearertoken you need to add an API or discord-bot or whatever yourself.
