# kittyverse.json

Free open public domain data for cryptokitties and copycats in JSON incl. fancies, cattributes, trait types, traits, genes, and more - No API key required ;-)


Example - All 12 Trait Types with 32 Traits - [`traits.json`](https://raw.githubusercontent.com/cryptocopycats/kittyverse.json/master/traits.json):

``` json
{
  "body": {
    "genes": "0-3",
    "name": "Fur",
    "code": "FU",
    "kai": {
      "1": "savannah",
      "2": "selkirk",
      "3": "chantilly",
      "4": "birman",
      "5": "koladiviya",
      "6": "bobtail",
      "7": "manul",
      "8": "pixiebob",
      "9": "siberian",
      "a": "cymric",
      "b": "chartreux",
      "c": "himalayan",
      "d": "munchkin",
      "e": "sphynx",
      "f": "ragamuffin",
      "g": "ragdoll",
      "h": "norwegianforest",
      "i": "mekong",
      "j": "highlander",
      "k": "balinese",
      "m": "lynx",
      "n": "mainecoon",
      "o": "laperm",
      "p": "persian",
      "q": "fox",
      "r": "kurilian",
      "s": "toyger",
      "t": "manx",
      "u": "lykoi",
      "v": "burmilla",
      "w": "liger",
      "x": ""
    }
  },
  ...
 }
```

Example - All Fancy Cats (Normal, Exclusive, Special Edition) with Trait Recipes, Max Limits, IDs, Time Windows, and More - [`fancies.json`](https://raw.githubusercontent.com/cryptocopycats/kittyverse.json/master/fancies.json):

``` json
{
  "tallythepurrocious": {
    "name": "Tally The Purrocious",
    "date": "2019-01-10", "time": { "end": "2019-01-21" },
    "traits": ["selkirk", "koala", "arcreactor", "sully" ],
    "desc": "Gods Unchained Promotion - Mystical Cat Talisman"
  },
  "aeoncat": {
    "name": "Aeoncat",
    "date": "2019-01-10", "limit": 380, "time": {"start": "2019-01-17", "end": "2019-01-28"},
    "desc": "Goddess Aeona - Goddess of Nature - Gods Unchained Promotion",
    "special": true
  },
  "hypurrion": {
    "name": "Hypurrion",
    "date": "2019-01-10", "limit": 1, "ids": [269],
    "desc": "Hyperion - Mythic Titan of Light - Gods Unchained Promotion",
    "exclusive": true
  },
  "catzy": {
    "name": "Catzy",
    "date": "2018-12-31", "limit": 10, "ids": [1137653,1137654,1137655,1137656,1137657,
                                               1137658,1137659,1137660,1137661,1137662],
    "special": true,
    "desc": "Changpeng \"CZ\" Zhao - CEO of Binance - Top 10 Blockchain Influencer of the Year 2018 by CoinDesk"
  },
  ...
}
```
