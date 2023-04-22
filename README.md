
# SpamBot+

Improved version of [CarloxCoC's SpamBot](https://github.com/CarloxCoC/SpamBot)

## Getting started
1. Install [node.js](https://nodejs.org/) and npm
2. Clone this repository
3. Configurate your bot in config.json
4. Install dependencies using `npm install`
5. Run the bot with `npm start`

## Config format
```json
{
  "username": "BotName",
  "password": "BotPassword",
  "ip": "IpAdress (probably should keep anarchy.6b6t.org)",
  "version": "MinecraftVersion (probably should stay on 1.19)",
  "messages": [
    "Message 1",
    "Message 2"
  ],
  "prefix": "Prefix (Intended to be used for color codes)",
  "blacklist": ["User1", "User2"],
  "delay": 20,
  "log":{
    "messages": true,
    "whispers": true,
    "sends": true,
    "kicks": true,
    "errors": true
  }
}
```


## Improvements
- Moved things like IP adress, version and delay into config.json instead of being hard coded into the code
- Prefix
- Console logging for messages sent and whispers
- Option to turn off different kinds of loggings
- Colors in console
- A bit more helpful README.md (in my opinion)

## Disclaimer
I do NOT hate Carlox or Colonizadores. This was not meant to make them look bad. I just had a bit of free time so I decided to expand this [great project](https://github.com/CarloxCoC/SpamBot).
