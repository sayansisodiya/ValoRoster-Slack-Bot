# ValoRoster
ValoRoster is an esports Slack bot for professional Valorant team and player info (Valorant is an online multiplayer video game). I created it while working as a Developer Relations Intern at [Postman](https://www.postman.com/).

ValoRoster is pretty basic; it uses Slack (slash commands and incoming webhook), Postman (webhooks and collections), the [PandaScore REST API for Valorant](https://developers.pandascore.co/doc/index_valorant.htm), and some JavaScript.

If you want to read about my development process for ValoRoster, here's a shameless plug for a [blog I wrote](https://blog.postman.com/building-a-bot-for-busy-gamers/) about ValoRoster on Postman's website :).

### Using ValoRoster

Interested in using ValoRoster yourself? [This public workspace in Postman](https://www.postman.com/sayansoloPW/workspace/valoroster-slack-bot/overview) should have all the info you need to get up and running.

Currently, the only two ValoRoster commands are:
* /roster \<teamName\>
  * returns the names and pictures of players currently on team \<team-name\>
* /player \<playerName\>
  * returns basic biographical and professional info on player \<gamertag\>

### ValoRoster Demo
![](https://github.com/sayansisodiya/ValoRoster-Slack-Bot/blob/main/valorostergif.gif)
