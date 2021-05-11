# TheBreakingBot
Discord bot that creates a message representing a card break with a body as well as a title and description as optional arguments that users can claim spots in.

## List of Commands: `*KEYS MUST BE SEPERATED BY SPACES`

**All Users:**

  * **!claim or !c `<key(s)>`** The core command of the bot, this command lets users claim the key(s) desired.
  * **!unclaim or !uc `<key(s)>`** Lets users unclaim their claim(s)
  * **!available or !a** Displays key(s) that are not claimed
  * **!claimhelp** Sends a URL to this page.
  
**Administrators:**

  * **!title `<title>`** *(Optional)* The title of break **(EX: !title This is a Test Title!)**
  * **!desc `<description>`** *(Optional)* The description of the break **(EX: !desc Box 1, Box 2, Box 3)**
  * **!keysprice `<key>` `<price>`** The key(s) with corresponding price(s) of the break **(EX: !keysprice SPOT1 29 SPOT-2 30)** 
  * **!keys `<body>`** Only the key(s) of the break **(EX: !keys SPOT1 SPOT-2)** 
  * **!build** Builds and sends the message from the data inserted above
<br/><br/>
  * **!setclaim or !sc `<name>` `<key(s)>`** Claims key(s) for a desired user, overwrites everyone **(EX: !setclaim Bob SPOT1 SPOT-2)**
  * **!setpaid or !sp `<key(s)>`** Adds a money bag next to the user's name signifying that the user has paid **(EX: !setpaid SPOT1)**
  * **!delclaim ot !dc `<key(s)>`** Removes the user(s) that claimed the team(s) **(EX: !delclaim SPOT-2)**
  * **!delbuild or !db** Deletes the break in the current channel 
  * **!export or !e** Creates a spreadsheet that lasts for 1 minute with the key(s) and user(s) on it **(Best for copying & pasting into a personal sheet)** 

## Examples:
**Claim Commands**

https://user-images.githubusercontent.com/69171981/116199336-dbcb6f00-a6eb-11eb-90fe-3daaeb5d60b7.mp4
