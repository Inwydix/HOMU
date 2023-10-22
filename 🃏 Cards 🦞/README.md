# 🃏 Cards 🦞
### `?cards`
> Show your owned cards. You select the set and rarity of the cards to display using a select menu called `smCards`.
### `$onInteraction[smCards]`
> What happens when you choose any of the options from the `smCards` select menu.
### `?rank up`
> A command to rank up maxed cards. Only works if you are level 30 or more in the bot. It shows only the maxed cards you own in a select menu called `smRankUp<cards-set-number>`
### `$onInteraction[smRankUp1]`
> Rank up the chosen maxed card to the next level of rarity (common to rare/rare to ultra rare)
## 📦 Variable 📦
The variable is the cards json. Acutally it looks like this:
`{ "hi31":{ "1":{ "pp":69, "rank":"c", "lock":"f" }, "2":{ "pp":69, "rank":"c", "lock":"f" }, "3":{ "pp":69, "rank":"c", "lock":"f" }, "4":{ "pp":69, "rank":"c", "lock":"f" }, "5":{ "pp":69, "rank":"c", "lock":"f" }, "6":{ "pp":69, "rank":"c", "lock":"f" }, "7":{ "pp":69, "rank":"c", "lock":"f" }, "8":{ "pp":69, "rank":"c", "lock":"f" }, "9":{ "pp":69, "rank":"c", "lock":"f" }, "10":{ "pp":69, "rank":"c", "lock":"f" }, "11":{ "pp":69, "rank":"r", "lock":"f" }, "12":{ "pp":69, "rank":"r", "lock":"f" }, "13":{ "pp":69, "rank":"r", "lock":"f" }, "14":{ "pp":69, "rank":"r", "lock":"f" }, "15":{ "pp":69, "rank":"r", "lock":"f" }, "16":{ "pp":69, "rank":"r", "lock":"f" }, "17":{ "pp":69, "rank":"r", "lock":"f" }, "18":{ "pp":69, "rank":"r", "lock":"f" }, "19":{ "pp":69, "rank":"r", "lock":"f" }, "20":{ "pp":69, "rank":"r", "lock":"f" }, "21":{ "pp":69, "rank":"u", "lock":"f" }, "22":{ "pp":69, "rank":"u", "lock":"f" }, "23":{ "pp":69, "rank":"u", "lock":"f" }, "24":{ "pp":69, "rank":"u", "lock":"f" }, "25":{ "pp":69, "rank":"u", "lock":"f" }, "26":{ "pp":69, "rank":"u", "lock":"f" }, "27":{ "pp":69, "rank":"u", "lock":"f" }, "28":{ "pp":69, "rank":"u", "lock":"f" }, "29":{ "pp":69, "rank":"u", "lock":"f" }, "30":{ "pp":69, "rank":"u", "lock":"f" }, "31":{ "pp":69, "rank":"s", "lock":"f" }, "32":{ "pp":69, "rank":"s", "lock":"f" } } }`

It follows the structure of: `{ "set" { "card-number" { "power points":<number>, "rank":<rarity>, "unlocked": <true/false>} } }`
