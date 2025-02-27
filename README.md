# pookie-bot
Discord and slack bot for Pookie!

# Dependencies
Pyenv  + Pipenv  + pytho 3.8

# Contribute
Update [app/common_responses.py](app/common_responses.py) to add responses & GIFs

# License

We want to make Pookie as assessible as possible so we made the source public.
All versions released, including patch fixes for prior versions, are published
under the Server Side Public License (SSPL) v1 used by Mongo DB and Elastic Search. See LICENCE files for details.

# Invite Pookie to Your Server
https://discord.com/oauth2/authorize?client_id=795343874049703986&scope=bot%20applications.commands&permissions=8
# Invite DevPookie to Your Server
https://discord.com/oauth2/authorize?client_id=817371651653632020&scope=bot%20applications.commands&permissions=8

# Development Notes
## Add new slack events
Make sure to add the list of events to [Event Subscriptions](https://api.slack.com/apps/A01HWT3TYCA/event-subscriptions)
During development, slack bot uses bot token, if the event requires additional scopes, they need to be added [here](https://api.slack.com/apps/A01T0HFLTUH/oauth)
