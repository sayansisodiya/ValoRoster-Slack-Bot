# ValoRoster
ValoRoster is an esports Slack bot for professional Valorant team and player info.

It's pretty basic; it uses Slack (slash commands and incoming webhook), Postman (webhooks and collections), and the [PandaScore REST API for Valorant](https://developers.pandascore.co/doc/index_valorant.htm).

Currently, the only two ValoRoster commands are:
* /roster \<teamName\>
  * returns the names and pictures of players currently on team \<team-name\>
* /player \<playerName\>
  * returns basic biographical and professional info on player \<gamertag\>
