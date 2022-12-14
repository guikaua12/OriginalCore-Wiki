## Permissions
| Permission                | Description                                                       |
|:--------------------------|-------------------------------------------------------------------|
| .                         | .                                                                 |
| oc.joinavatar.join        | Player should have this permission to receive the avatar message. |
| oc.playtime.bypass        | Permission to bypass the chat limitations.                        |
| oc.giveall                | Permission to use the /giveall command                            |
| oc.fly.unlimited          | Unlimited fly                                                     |
| oc.fly.limited            | Limited fly                                                       |
| .                         | .                                                                 |
| oc.nickname.nick          | Permission required to use the /nick commmand                     |
| oc.nickname.nick.bold     | Permission required to use bold in prefix/nick/suffix             |
| oc.nickname.nick.italic   | Permission required to use italic in prefix/nick/suffix           |
| oc.nickname.nick.others   | Permission required modify another player nickname                |
| oc.nickname.prefix        | Permission required to use the /nick prefix commmand              |
| oc.nickname.prefix.bold   | Permission required to use bold in prefix/nick/suffix             |
| oc.nickname.prefix.italic | Permission required to use italic in prefix/nick/suffix           |
| oc.nickname.prefix.others | Permission required modify another player prefix                  |
| oc.nickname.suffix        | Permission required to use the /nick suffix commmand              |
| oc.nickname.suffix.bold   | Permission required to use bold in prefix/nick/suffix             |
| oc.nickname.suffix.italic | Permission required to use italic in prefix/nick/suffix           |
| oc.nickname.suffix.others | Permission required modify another player suffix                  |
| .                         | .                                                                 |
| oc.vanish.use             | Permission to use the vanish command                              |
| oc.vanish.see             | Permission to see vanished players                                |
| .                         | .                                                                 |
| oc.tags                   | Permission to use the tag command                                 |
| oc.tags.admin             | Admins permission to use commands such as create/remove,etc       |

## Placeholders
| Placeholder                  | Description                                              |
|:-----------------------------|----------------------------------------------------------|
| %OriginalCore_fly_timeleft%  | Return the player time left for the fly                  |
| .                            | .                                                        |
| OriginalCore_tag_identifier% | Return the tag identifier.                               |
| %OriginalCore_tag_tag%       | Return the tag that the player is using                  |
| %OriginalCore_description%   | Return the tag description                               |
| %OriginalCore_tag_amount%    | Return the amount of tags that the player have access to |
| .                            | .                                                        |
| %OriginalCore_vanish_count%  | Return the amount of vanished players                    |
|                              |                                                          |

## OGCoins
| Command                         | Description                                                                   | Permission Node      |
|---------------------------------|-------------------------------------------------------------------------------|----------------------|
| `/ogcoins`                      | Same as the /ogcoins help                                                     |                      |
| `/ogcoins help`                 | Displays a list of the plugin's commands.                                     |                      |
| `/ogcoins reload`               | Reloads all of the plugin's files and applies any saved changes made to them. | oc.ogcoins.reload    |
| `/ogcoins pay <name> <amount>`  | Transfers the specified amount of points from your balance to another player. | oc.ogcoins.pay       |
| `/ogcoins give <name> <amount>` | Gives the target player a specified amount of points.                         | oc.ogcoins.give      |
| `/ogcoins giveall <amount>`     | Gives points to all online players.                                           | oc.ogcoins.giveall   |
| `/ogcoins take <name> <amount>` | Take points from a player.                                                    | oc.ogcoins.take      |
| `/ogcoins set <name> <amount>`  | Set a player's points to the specified amount.                                | oc.ogcoins.set       |
| `/ogcoins reset <name>`         | Resets a player's points back to 0.                                           | oc.ogcoins.reset     |
| `/ogcoins look <name>`          | View how many points a player has.                                            | oc.ogcoins.look      |
| `/ogcoins me`                   | View how many points you have.                                                | oc.ogcoins.me        |
| `/ogcoins lead [page]`          | View a page of the points leaderboard.                                        | oc.ogcoins.lead      |
| `/ogcoins broadcast <name>`     | Broadcasts a player's points.                                                 | oc.ogcoins.broadcast |
