![Logo](https://www.seekpng.com/png/full/270-2700588_vip-tickets-for-trixie-delight-u0026-starship-vip.png)

<div align="center">
  
  </div>
  
  # Features
- Setup 
- Open 
- Close
- Add
- Remove
- Rename
- Close
- Reopen
- Per Server Prefix 
- Ping Command

# 🔩 Installation
## Create [TOKEN](https://discord.com/developers/)
```
$ under bot_token
```

## Create [prefix]()
```
$ server prefixes could be -; +; !; ?;...
```

# 💻 Code example
This is a simple example of code using this package.

```js
            id: require('quick.db').fetch(`TicketAdminRole_${message.guild.id}`),
            allow: ["SEND_MESSAGES", "VIEW_CHANNEL"]
        }, {
            id: message.guild.roles.everyone,
            deny: ["VIEW_CHANNEL"]
        }]).then(() => {
            message.channel.send({
                embed: {
                    title: '✅ | Done',
                    description: `${txt} has been added to this ticket`,
                    color: 0x00D700
                }
            }).then(async function(msg) {
                setTimeout(() => {
                    msg.delete().catch(err => { return })
                }, 1000 * 7);
```
&
```js
                const embed2 = new Discord.MessageEmbed()
                .setTitle(`Premium Ticket Commands`)
                .setThumbnail(message.guild.iconURL({ dynamic: true }))
                .setDescription(`**__Here Are My Commands:__**\n\`setup,\` \`transcript,\` \`rename,\` \`remove,\` \`ping,\` \`open,\` \`close\``)
                .setColor(`#0x2F3136`)
```

<br/>
