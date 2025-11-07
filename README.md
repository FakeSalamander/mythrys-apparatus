# Mythrys' Apparatus

This is a WIP Tarot-Deck Discord bot based off [bastianleicht's DiscordJSBot Base](https://github.com/bastianleicht/DiscordJS-Bot-Base) specifically tailored towards playing His Majesty The Worm in discord channels. It automatically separates the deck into a GM's Deck with the Major Arcana (minus The Fool) and a Players' Deck with the Minor Arcana (plus The Fool), as per the requirements of the game's rules.

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
- /draw-player - draws a card from the Player deck and displays it to everyone before sending it to the Player discard pile.
- /draw-gm - draws a card from the GM's deck and displays it to everyone before sending it to the GM discard pile.
- /discards - display the top card of both of the discard piles.

- /hold-player - draws 4 cards from the Player deck, then discreetly places then in that player's hand.
- /hold-gm n - draws n number of cards from the GM deck, then discreetly places them in that player's hand
- /peek - the bot DMs that player a list of their held cards

- /play (card) - openly displays one of the cards in your hand, then discards it. Used for overt actions like attack, etc
- /place-facedown (card) (your turn?) - removes one card from your hand and places it into your "faceodwn" slot. Used for actions like Dodge or Aid Another.
- /reveal-facedown - openly reveals your facedown card, then discards it.
- /discard-faceodwn - discards your facedown card.

- /initiative (card) - a player submits one of the minor arcana in their hand  to use as their initiative card
- /monster-initiative (card) (monster_name) - the GM submits one of the major arcana in their hand to use as the initiative card for a certain monster.
- /replace-initiative (card) - discards your current initiative card and places down a new one from your hand.
- /take-turns - reveals which player/NPC goes next & their initiative card, and then prompts them to take a turn.
- /next-round - discards all of the initiative cards & held cards (except for placed facedown cards) to reset the round
- /reveal-initiative (monster_name) - reveals your own initiative card (or the initiative card of one of your monsters), even if it is not your turn yet.
  

## Links you might need
- [DiscordJS.guide](https://discordjs.guide/)
- [discord.js](https://discord.js.org/#/)
- [Stack Overflow](https://stackoverflow.com/)

## License
[License](https://github.com/routerabfrage/License)
