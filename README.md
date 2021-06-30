# DiscordBotJSTemplate
This is an structured folder layout of an DiscordBot made in Javascript. A template for future bots. Made with command and event handlers to setup and load all Javascript files within the folders: commands & events. 
Commands can be made in the structure like the "clear.js" command with a name, description and execute. In Events you can name the events like the events from DiscordJS. For security there is an env-file for environment variables for your DiscordBot.

# Table of Contents
- [Getting Started](#Getting-Started)
    - [Installing](#Installing)
- [Deployment](#Deployment)
    - [Running locally](#Running-locally)
    
## Build With
This application is build with the following technologies:
- [NodeJS and NPM, the package manager for JavaScript.](https://nodejs.org/en/)

## Used packages
This application uses the following dependancies: 
- [DiscordJS](https://discord.js.org/#/)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [fs](https://www.npmjs.com/package/fs)

## Functionalities
- ENV-file for security. Used to store environment variables like discord token and prefixes.
- Handlers to load and setup the JS-files within commands and events.
- Seperate folders for ``commands`` and ``events``. Where in you can structure different commands and events clearly.

# Getting Started
These instructions will get you a copy of the application/project up and running on your local machine or own device.

## Prerequisites
What things you need to install the application and how to install them
- Install Nodejs and NPM.
- Download or clone the project from the repository 
- Change the environment variables

## Installing
1. Download and install Nodejs and NPM on https://nodejs.org/
2. Download or [clone](https://help.github.com/articles/cloning-a-repository/#platform-all) the [application project](https://github.com/ametekohy/DiscordBotJSTemplate) on your computer.
3. Enter ``NPM install`` to install all the required packages.
4. Change the .env-file DISCORD_TOKEN to your own. [Need help setting up a bot?](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)

Now everything is ready for use!

# Deployment
There are a couple of ways to run this discordbot; locally from your own computer or an online (virtual) server. 

## Running locally
1. Open the terminal and go to the project folder ```DiscordBotJSTemplate```
2. Run the following: ``node .``
3. And enjoy the discordjs template bot on your discordserver!
