# easy-peasy-slash-command-app
A template project to get you started writing Slack slash commands using Botkit
Please see the word document for the updated tutorial to get everything up and running.

To host the app as instructed in the tutorial (using localtunnel), run the command `lt --port 8765 --subdomain awesomeslashcommand`

To host the slash command (note that the app must be running to host the command), use the command `CLIENT_ID=xxx.yyy CLIENT_SECRET=abc VERIFICATION_TOKEN=123 PORT=8765 npm start`. See the word document for how to find these values on your Slack app's page.

Here's the original tutorial also linked in the word document:

Follow along with [Easy Peasy Slash Commands](https://medium.com/slack-developer-blog/easy-peasy-slash-commands-getting-started-c37ff3f14d3e#.nfr4px2vi)
