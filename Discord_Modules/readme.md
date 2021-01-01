A discord package for Mudlet.\
![alt text2](https://raw.githubusercontent.com/Xiija/MudletStuff/master/Discord_Modules/discwebhook-02-sm.png)\
Includes code you can modify for the following...\
• Open the Mudlet Discord Server, Announce page with an alias.\
• Send an auction embed to a webhook.\
• Send a group request embed to a webhook.\
• Send a text message to a webhook.\
\
( right click these & open in a new tab )\
How to make a webhook on your server?\
<a href="https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks" target="_blank">Webhooks 101</a>
\
For Help on the Mudlet Discord Server\Help channel\
<a href="https://discord.com/channels/283581582550237184/283582068334526464">Mudlet Discord Server Help</a>
<h3> All these scripts and aliases can be modified however you want, these are just ideas on their use </h3>
<h1> How to Use </h1>

Make a webhook in a channel on your discord server ( see above )\
Change the code in the 3 scripts that use a webhook to use your new webhook url.

 Webhook example:\
 https://discordapp.com/api/webhooks/599286738644369409/oznnAtMO46Q1rjU_13GZasuoArN-h9yrUHwvU1Df05XYJiAyZbxlvDjs_yadayadayada
 
 The line in the scripts you need to change...  
  local url = "https://discordapp.com/api/webhooks/xxx_your_webhook_url_goes_here_xxx"

<h4> Then you can test the aliases in the package...</h4>

• Send an auction embed to a webhook.
\
 to use: auc -itemname- -price- -number of items for sale- ( 3 args, no spaces )\
 ex: auc cats 20gold 3  
 
 • Send a group request embed to a webhook.\
   to use: groupme -number of group members- -area to group in-  ( 2 args, no spaces )\
   ex: groupme 4-person Oblivion-Shores

• Send a text message to a webhook.\
   to use: dmsg -your text here- \
 ex: dmsg hello fellow gamers!\
 this will send the message to the webhook you have set in the accompanying function\

 • Open the Mudlet Discord Server, Announce page with an alias.\
  to use: just type ... discord ... this will open the Mudlet Discord page, Announcements channel
