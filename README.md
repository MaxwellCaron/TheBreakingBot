# TheBreakingBot
Discord bot that creates a message representing a card break with a body as well as a title and description as optional arguments that users can claim spots in.

## List of Commands: `*TEAMS MUST BE SEPERATED BY SPACES`

**All Users:**

  * **!claim `<team>`** The core command of the bot, this command lets users claim the team desired.
  * **!unclaim `<team>`** Lets users unclaim their claim
  * **!available** Displays team that are not claimed
  * **!claimed** Displays user's claimed team
  * **!claimhelp** Sends a URL to this page.
  
**Administrators:**

  * **!build `<team>` `<price>`** Adds teams to a break with corresponding prices. **(EX: !build ANA 55 BOS 79)**
  * **!title `<title>`** *(Optional)* The title of break **(EX: !title This is a Test Title!)**
  * **!desc `<description>`** *(Optional)* The description of the break **(EX: !desc Box 1, Box 2, Box 3)**
<br/><br/>
  * **!setclaim `<name>` `<team>`** Claims team for a desired user, overwrites everyone **(EX: !setclaim Bob SPOT1 SPOT-2)**
  * **!setpaid `<team>`** Adds a money bag next to the user's name signifying that the user has paid **(EX: !setpaid SPOT1)**
  * **!delclaim `<team>`** Removes the user that claimed the team **(EX: !delclaim SPOT-2)**
  * **!changeprice `<team>` `<new price>`** Changes price of a team **(EX: !changeprice SPOT1 $1)**
  * **!discount `<discount amount>` `<team>`** Subtracts `<discount amount>` from `<team>` **(EX: !discount $10 SPOT1 SPOT-2)**
  * **!changeteam `<old name>` `<new name>`** Changes name of already active team **(EX: !changeteam SPOT-2 SPOT-7)**
  * **!delteam `<team>`** Deletes a team **(EX: !delteam SPOT-7)**
  * **!addteam `<team>` `<price>`** Adds a team to the active break, `<price>` is only needed in a `<team>` - `<price>` break format. **(EX: !addteam SPOT-3 $77)**

  * **!export** Creates a spreadsheet that lasts for 1 minute with the team and user on it **(Best for copying & pasting into a personal sheet)** 
  * **!delbreak** Deletes the break in the current channel 
  
## Examples:
**Claim Commands**

https://user-images.githubusercontent.com/69171981/116199336-dbcb6f00-a6eb-11eb-90fe-3daaeb5d60b7.mp4
