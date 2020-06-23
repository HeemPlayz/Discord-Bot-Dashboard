# Introduction
I made this open-source project for the usage of all people, it shows how you can use OAuth2 by Discord to use it as Bot dashboard
It only has Login, and the bot details.

# Setup
First of all, install all required packages in order to work, after installing them, you will need to change `config.json.sample` to `config.json`
to make the file scan it,
Fill all the details in `config.json`

```
{
    "token": "Bot's Token",
    "id": "Bot's ID",
    "secret": "Bot's Secret"
}
```
`token`: Put the token here (Only you can have it, don't give it to any user)<br />
`id`: You bot's ID<br />
`secret`: Can be obtained in the developers page of discord<br />
Note: all these can be obtained from https://discord.com/developers, and all these are important, any one of these isn't filled will make you have an error.

After doing all these steps, you are good to go, just do `node server.js` and it will listen to port `3000` by default.

# Credits
This website is fully made by `HeemPlayz#8342` and goes under `Apache 2.0` License, you can modify, publish it on your own in safe way, I do not take any responsibilites of miss using it, any problems or suggestions, feel free to open an issue to this repo.
