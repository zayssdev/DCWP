## Discord API Wrapper for NodeJS
The -probably- hardest way to interact with Discord API while using a NodeJS library.

![GitHub stars](https://img.shields.io/github/stars/zayssdev/DWP)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/zayssdev/DWP)
![GitHub](https://img.shields.io/github/license/zayssdev/DWP)
![GitHub package.json version](https://img.shields.io/github/package-json/v/zayssdev/DWP)
![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/zayssdev/DWP)

To start using this wrapper, install the library:

`npm install @zayssdev/DWP@1.0.0`


Bring the library & call the class into your code:


`const DiscordWrapper = require("@zayssdev/DWP")`

`const client = new DiscordWrapper()`

Here you go, now you need to login to the client with your bot's token:

`client.login("token")`

```js
const DiscordWrapper = require("@zayssdev/DWP")
const client = new DiscordWrapper()
client.login("token")
```

If you have any questions, feel free to DM me via Discord [zayss#9339)!

