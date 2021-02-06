# Tutorial for Embed Message.

## Me Royal Embed Message Docs.

### This Is Help In Welcome Message, Good Bye Message, Custom Command, YouTube Notification, Level Up.

__This Is Help You That How To Write In Welcome Message and Many More In easy way.__

#### To Add Embed Message In Dashboard. Here Is The Important Tag's.

**Me royal guide**

##### Welcomer & goodbye

**User info**
`{user}`- mention join user
`{user.id}`- join user id
`{user.name}`- join user name ex. record_buttonNAME BOYrecord_button
`{user.avatar}` -join user Avatar link send
`{user.tag}` - join user tag like this record_buttonNAME BOYrecord_button#2751

**Server info**
`{server.name}` - server name give
`{server.id}` - server id give
`{server.icon_url}` - server icon url give
`{membercount}` - server all membercount

**Mention info**
`{:<enter emoji name>}`- mention emoji like this 11 [support nitro emoji also]
`{#<enter channel name>}`- mention channel like this #🤖｜ʙᴏᴛ-ɪɴғᴏ  
`{&<enter role name>}`- mention role like this @━━⟡━━『 DEVELOPER 』━━⟡━━ 

**Embed info**
`{embed}`- embed ture or false checker
`{title:<your message>}`- embed title
`{description:<your message>}`- embed description message
`{imageUrl:< enter image url>}`- embed image
`{embedImage}` - welcome image like this- `https://cdn.discordapp.com/attachments/644751471107244033/752572157883842610/welcome.png`

`{thumbnailUrl:<enter thumbnail url>}`- embed thumbnail

**Note**-`<` `>`not include your message.

**EXAMPLE OF WELCOME AND GOOD BYE** - 

```javascript
{embed}
{description:**{:iron} Hey {user}
━━━━━━━━━━━━━━━━━━━━━━━━━━
Welcome to {:ma} ME ROYAL OFFICIAL {:ma}
━━━━━━━━━━━━━━━━━━━━━━━━━
{:11}│Read the server rules at {#638944397857259550} and follow them.

{:11}│Take your roles from {#651275188675149837}
 
{:11} │If you are facing any problem bot/uplife-api  mention any pingforhelp

{:11}│Enjoy and Please stay here.

{:11}│ Membercount = {membercount}

{:11}│Username = {user.name}
━━━━━━━━━━━━━━━━━━━━━━━━━**}
{embedImage}
{color:{randomText:#0099FF,#00FFFF,#FF0000,#00FF00}}
```

###### LEVEL UP MESSAGE

**Me Royal Guide 2**

Level
`{level}` - Give Your Current Level.

Othe tag Same as Level as Welcome and Good Bye.

**EXAMPLE OF LEVEL UP MESSAGE**-
```javascript
{user},You Just Reach {level}.
```

###### CUSTOM COMMANDS
**Me Royal Guide 3**
Role Manager
`{role.add:<role name or role I'd>}` - Add Role If You Type In Custom Command.
`{role.remove:<role name or role I'd }` - Remove Role If You Type In Custom Command.

Other Tag Same as Welcome and Good Bye.

**EXAMPLE OF CUSTOM COMMAND** - 
```javascript
{role.add:Official}
{role.remove:Unverified}
```

###### YOUTUBE NOTIFICATION
**Me Royal Guide 4**

YT Manager
`{here}` - replace by the @here mention.

`{everyone}` - replace by the @everyone mention.

`{videoTitle}` - replace by the Upload Video Title.

`{videoLink}` - replace by the Upload Video Link.

`{channelName}` - replace by the Upload Video Channel Name.

`{:< enter emoji name >}`- mention emoji like this {:hello}[support nitro emoji also].

**EXAMPLE OF YOUTUBE NOTIFICATION**-
```javascript
Hey {everyone}, **{channelName}** just posted a video! Go check it out! {:likesymbol} 
{:thanks} {videoLink}
```
