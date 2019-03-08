## The open source Discord bot
**CoffeeBot** is a free and open source solution to all of your server managing problems. A fork of [SwitchbladeBot/switchblade](https://github.com/SwitchbladeBot/switchblade).

## Setting up a development environment
> For this guide, we're assuming that you already have NPM, Node and Windows Build Tools installed.

**0. Fork the repository** (You don't have to do this if you're part of our organization)


**1. Clone your fork and checkout the `dev` branch**
```bash
git clone https://github.com/<your username>/switchblade
cd switchblade
git checkout dev
```

**2. Install all the dependencies with NPM**
```bash
npm install
```

**3. Create a file named `.env` inside of the bot's folder and add all of the [required environment variables](https://github.com/SwitchbladeBot/switchblade/wiki/Environment-Variables) to it.**

In the end, your file should look like this:
```
DISCORD_TOKEN=YOUR TOKEN HERE
PREFIX=s!
```

**4. Run the bot!**
```
npm run start-dev
```
The `start-dev` script loads the variables from `.env` into the process, and automatically restarts the bot when you make changes to the code.

Happy hacking!
