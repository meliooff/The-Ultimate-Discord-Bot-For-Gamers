# [Ultimate-Discord-Bot-for-Gamers](https://github.com/Valcore7/The-Ultimate-Discord-Bot-For-Gamers)
This is a WIP discord bot that will hopefully include everything that a discord bot for gamers needs, from stats in popular games like Apex and Fortnite, to helping you create a discord server from scratch! AGIAN THIS IS STILL A WORK IN PROGRESS AND I AM NOT VERY SKILLED AT CODING IN ANY LANGUAGE!

## Description
This is a basic discord bot written in [Discord.js](https://github.com/discordjs/discord.js) and [Discord.js-commando](https://github.com/discordjs/Commando).

# IMPORTANT
This is still a work in progress, if there are any issues or requests post them in the [ISSUES](https://github.com/Valcore7/The-Ultimate-Discord-Bot-For-Gamers/issues). Thanks!

## REQUIREMENTS
You will need to create a role named "duos" for lfg to work currently. lfg command is still a WIP
You will need a channel named `logs` and a channel named `reports` for the kick, ban, and report commands to function properly.
You will need to create a file named `.env` and paste the code below in it, then fill in everything by replacing the text in "" with the information.
```
TOKEN:"Bot_Token"
PREFIX:"Prefix"
FNBR:"FNBR-CO_Token"
FTEMAIL:"An Epic Games Fortnite account Email"
FTPASS:"An Epic Games Fortnite account Password"
```
EX: 
```diff
- PREFIX:"Prefix"
+ PREFIX:"?!"
```

## Commands:
### NOTE:
"|" means "or"
"<pfx>" stands for the prefix that activates your commands. Currently there is no prefix set.
You can also ping the bot by using ```@_bot username here_``` then the command and its arguments
EX: [@Valcore Bot]() ft shop

```
<pfx>ft <shop> 
<pfx>ping
<pfx>rps 
<pfx>clear <amount>
<pfx>help <command_name>
<pfx>ban <id | mention> <reason>
<pfx>kick <id | mention> <reason>
<pfx>report <id | mention> <reason>
```
## The sources to the code I have used are: 
- [The Source Code](https://github.com/The-SourceCode/Discord.js-Bot-Development)
- [MenuDocs](https://github.com/MenuDocs/Discord.JS-Tutorial)
- [Strandxo](https://github.com/Strandxo/simple-fortnite-api)
- [JDaatselaar](https://github.com/JDaatselaar/statscool-old/blob/master/bot.js#L111)
- More sources will be added as I continue to develop the bot. In each code that I have used and/or modified, is located at the top of the code

## TODO 
- [X] Release this github repo to the public
  - [ ] Add Fortnite commands
    - [ ] Shop command
      - [ ] Use canvas.js to generate an image of the item shop
        - [ ] Generate the cosmetic images
          - [ ] Create a basic cosmetic image
          - [ ] Add the text to the cosmetic images
            - Like price and name
        - [ ] Use the cosmetic images to create itemshop 
        - [ ] Send the itemshop image to discord
      - [ ] Add image links
       - Only Temparay until I make the canvas.js shop
    - [ ] Item command (search for a certain skin, backbling, wrap, etc)
      - [ ] Use canvas.js (Highly Customizable)
    - [ ] News (going to be ```<pfx>news <br | stw | bp | tn>```)
      - br = battle royale
      - stw = save the world
      - bp = battle pass
      - tn = tournament 
    - [ ] Stats command
    - 
- [X] Change the prefix command setup in [index.js](./index.js) to make it more simple and less code.
  - [X] change the prefix/command recongizer to be only one _block_ of code instead of two _blocks_ of code
  - [X] remove the ATPREFIX arg from _.env_ and change the code in [index.js](./index.js) to make ATPREFIX a constant that will automatically will set ATPREFIX to your bot's user id that way you won't have to copy and paste your bot's id into your _.env_ file. 
- [ ] Update code to discord.js v12
  - [ ] Update code to discord.js-commando for discord.js V12
- [ ] Create a lfg command for fortnite (looking for group)
- [ ] Create a command that sets up a user's discord server for them (Can be a basic setup, setup for fortnite, setup for all games, etc)
  - [ ] Create the Apex commands (Need to do research)
  - [ ] Create D&D commands (Need to do research)
- [ ] Release the bot in different forms ie: One only for Fortnite or one only for Apex
- More things will be added to the TODO list

# Thanks!
I would like to say thanks to everyone that has helped me out so far (and in the future) in developing this discord bot!
> [Valcore7](https://github.com/Valcore7)
> [10031623](https://github.com/10031623)
