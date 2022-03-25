# Discord Bot Template
This template is using [discord.js](https://discord.js.org/#/docs/discord.js/v13/general/welcome)

## Command Structure

```json
    {
    name: "" -- Here you have to put command name
    memberPermissions: [] -- Here you can put required permissions for using a command
    botPermissions: [] -- Here you can put required permissions for a bot to execute a command
    filter: () => return { text: "" } // Here you can create custom filter for a command (for example you can make a filter to use command only on nsfw channel). If filter returns {text: ""} then its gonna stop executing a command and reply to user with text in a object
    run: () => {} // Here is a code for a command
    }
```

## License
[MIT](https://choosealicense.com/licenses/mit/)