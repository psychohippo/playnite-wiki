### Game doesn't start properly when using option to not use official client

In that case: 
- Edit the game and go to "Actions" tab
- Uncheck "Managed by library plugin" option
- Set play action to "URL" type and set path to `twitch://fuel-launch/<gameid>` (for Twitch client) or `amazon-games://play/<gameid>` (for Amazon Games client), where replace `<gameid>` with game's id you can find on "Advanced" tab.