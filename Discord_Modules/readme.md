A discord package for Mudlet.\
![alt text2](https://raw.githubusercontent.com/Xiija/MudletStuff/master/Discord_Modules/discwebhook-02-sm.png)\
Includes code you can modify for the following...\
• Open the Mudlet Discord Server, Announce page ( or any server channel ) with an alias.\
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
This package is intended more for education purposes, and not as working code. 
<h1> How to Use </h1>

Make a webhook in a channel on your discord server ( see above )\
Change the code in the 3 scripts that use a webhook to use your new webhook url.\
<em>(script names:  Do Auction, Do Group, and msg2discord )</em>

 Webhook example:\
 https://discordapp.com/api/webhooks/599286738644369409/oznnAtMO46Q1rjU_13GZasuoArN-h9yrUHwvU1Df05XYJiAyZbxlvDjs_yadayadayada
 
 The line in the scripts you need to change...  
  local url = "Paste_Your_Webhook_Here"

<h4> Then you can test the aliases in the package...</h4>

• Send an auction embed to a webhook.
\
 to use: auc -itemname- -price- -number of items for sale- ( 3 args, no spaces )\
 ex: auc werecats 20gold 3  
 
 • Send a group request embed to a webhook.\
   to use: groupme -number of group members- -area to group in-  ( 2 args, no spaces )\
   ex: groupme 4-person Oblivion-Shores

• Send a text message to a webhook.\
   to use: dmsg -your text here- \
 ex: dmsg hello fellow gamers!\
 <em>this will send the message to the webhook you have set in the accompanying function</em>

 • Open the Mudlet Discord Server, Announce page with an alias.\
  to use: just type ... discord ... this will open the Mudlet Discord page, Announcements channel
