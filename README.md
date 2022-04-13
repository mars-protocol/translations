# Mars web-app translations

This repository contains all language files used in the [Mars dApp](https://app.marsprotocol.io "Mars Protocol"). To contribute, please clone this repository and create a pull request (PR). If you never used a git repository or translated a json formatted file before, please follow the steps below:

## Getting Started

1. Setup a github.com Account and fork this Repository
2. Setup Sublime Text and Github Desktop
   - Download: [Sublime Text Editor](https://www.sublimetext.com/ "Sublime Text Editor")
   - Download: [Github Desktop Git GUI](https://desktop.github.com/ "Github Desktop Git GUI")
3. Edit an existing Language File or create a new Language File
4. Create a Pull Request (PR)

## Guidelines

### ISO 639-1 codes

If you are creating a new translation file, please look up the [ISO 639-1 code of your native language](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes "ISO 639-1 code of your native language") and create a new file with it.

### Curly Brackets

Whenever you find a word wrapped in curly brackets e.g.: `{{amount}}` **do not** translate them. Those are placeholders for variables passed to the translation string.

### Key:Value Pairs

The translation files consist of key:value pairs which are wrapped by double quotes. Please only edit the **value** part of the key:value pairs (see example below).

```
en.json: "close": "Close",
de.json: "close": "Schließen",
```

_A PR with changed keys will be declined._

### Names and proper nouns

DeFi related translations are full of names and proper nouns. Please try to keep the most well known terms in english. Here is a list of Names, you should not change as it will confuse the user more than it will help.

- Airdrop
- APR
- APY
- Council
- Fields
- Fields of Mars
- Lockdrop
- Martian Council
- My Station
- Red Bank
- Wallet

### Addressing the user

Address the user directly and informal. Some languages have different ways of addressing users. The english "you" is used universal and can be formal and informal, but if your language consits of way to address someone informally, please use it.

### Storytelling and Lore

The Mars protocol communications are based on the lore of a Mars landing. Please decide for your own, if you want to keep this lore or if it makes more sense to to explain the functionality of the Mars protocol on a more factual base.

## Disclaimer

The files of this repository are getting loaded by the [Mars dApp](https://app.marsprotocol.io "Mars Protocol"). Once you contributed to a file and it got approved and merged into the master branch, you'll find the updated/new translation inside the [Mars dApp](https://app.marsprotocol.io "Mars Protocol").
