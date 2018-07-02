# Conversational UX for Hubot with API.AI

This hubot script adds conversational user experience with API.AI as
back-end.

Hubot listens to everything, sends the information to api.ai, which 
in turns handles the dialog and detects intents and parameters.
Finally, the script [emits an event](https://github.com/hubotio/hubot/blob/master/docs/scripting.md#events)
so that it can be consummed by other scripts.

![example](doc/smartbot-api-ai.gif)

# Getting started

```
git clone https://github.com/ojacques/hubot-api-ai-poc.git
cd hubot-api-ai-poc
cp .env.template .env
vi .env   // Edit away!
./start.sh
```
