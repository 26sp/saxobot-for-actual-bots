# SAXOBOT
Saxobot is now optimised for actual bots!

# Setup
### Go to the [Dev portal](https://discord.com/developers/applications) and create an app. Head over to bot and add a bot.
### Reset the token, go to the bottom of `index.js` and paste it there.
### Run `npm install discord.js fs child_process ffmpeg` and then run `node index.js`
### That's it!


# Code to turn selfbots in to apps
Replace the "discord.js-selfbot" with

`const { Client, Intents } = require("discord.js");
const bot = new Client({
  intents: [Intents.FLAGS.GUILDS, Intents.FLAGS.GUILD_MESSAGES]
});`
