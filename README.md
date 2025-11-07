# His Majesty's Deck

This is a WIP Tarot-Deck Discord bot, specifically tailored towards playing His Majesty The Worm in discord channels. It automatically separates the deck into a GM's Deck with the Major Arcana (minus The Fool) and a Players' Deck with the Minor Arcana (plus The Fool), as per the requirements of the game's rules.

## Installation

Use the package manager [npm](https://nodejs.org/en/download/) to install all needed modules.

```bash
npm install
```
Then you have to rename ``config.json.example`` to ``config.json`` and to fill all your settings in.

Your can get the Token from the Discord Developer Page. [Link](https://discord.com/developers/applications)

## Roadmap

- create card and deck objects.
- store deck information on a per-channel basis.
- /shuffle - shuffles both the GM and Player decks, and initializes them if ran for the first time.
- /draw-player - draws a card from the Player deck and displays it to everyone
- /draw-gm - draws a card from the GM's deck and displays it to everyone
- /discards - display the top card of both of the discard piles
  

## Links you might need
- [DiscordJS.guide](https://discordjs.guide/)
- [discord.js](https://discord.js.org/#/)
- [Stack Overflow](https://stackoverflow.com/)

## License
[License](https://github.com/routerabfrage/License)
