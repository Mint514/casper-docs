---
sidebar_position: 6
---

# Create a giveaway!

One of Caspers awesome features is a super robust giveaway system. In this quick guide we'll show you how to get one setup.

**Free users can have one giveaway running at a time**

To get started, we need to use the following command `/giveaway create` you'll be presented with the following options, some are mandatory and some are optional **if you do not select the optional channel field, it will post in the channel you are in**

| field | Description |  Mandatory |
|----------|----------|----------|
| `duration` | How long do you want the give away to run for (e.g, 1m, 1h, 1d) | YES |
| `winners` | How many winners do you want? | YES |
| `prize` | What is the prize? this will become the title of the giveaway | YES |
| `description` | Custom description to show in the giveaway message  | NO |
| `hostedby` | You can select a user or a role to display  | NO |
| `channel` | Select a channel for the giveaway to post in, othewrwise it will post in the channel you use the command in | NO |
| `restrictedrole` | Stop users with a certain role from entering  | NO |
| `minmessages` | The amount of messages a user must have to enter (only messages since the bot has been invited to your server count) | NO |

For example you could run the following
```
/giveaway create [1d] [1] [Test prize] [Enter to win this test prize] [@Casper] [#general] [Admins] [10]
```
This would create a Giveaway that lasts **1 Day** to win **A test prize** in **General** that **Admins** cannot enter and everyone must have **10 messages** to enter. 

That's it! 
