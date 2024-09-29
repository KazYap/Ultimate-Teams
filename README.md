# Ultimate-Teams
UltimateTeams is a light-weight teams plugin for Minecraft servers running Spigot and most of its forks, developed with optimization in mind!

UltimateTeams does not support any grief prevention tool such as land claiming or securing containers within your team.

UltimateTeams DOES however offer the ability to disable friendly fire within your team!

UltimateTeams does support H2 (preferred over SQLite), SQLite, MySQL, MariaDB (preferred over MySQL) and PostgreSQL, check the config for further information.

**All database operations are executed asynchronously, to prevent any form of lag**

# Features

⭐ Optimization
The whole plugin is developed with optimization in mind, and it has been tested with more than 100 active players.

⭐ Home & Warps
Each team can have a home and one ore more warps (check the config). Teleportation can also be handled by HuskHomes

⭐ Bedrock Support
With floodgate correctly installed, bedrock players are automatically managed

⭐ Team & Team allies chat
Players of each team and all its allies can talk in their dedicated channels

⭐ Allies and Enemies
Other teams can be marked as allies or enemies

⭐ PlaceholderAPI
Some placeholders are already available without requiring to download an external jar

⭐ Admin commands
Staff members can force players to join a team or disband another

⭐ GUI
Teams list can also be accessed in a paginated GUI

# Commands

/team command
Aliases: /team

The /team command is the main command of the plugin, with /team you can do the following:

/team create <name> - Creates A new team if not already in one
/team disband - If you are the team owner, this will destroy your team
/team leave - If you are in a team, this will remove you from it
/team invite <player> - Will invite a player to your team if they are not already in one
/team join - Will add you to a team that you have been invited too.
/team kick <player> - Will kick a player from your team
/team info - Will display information about your current team
/team list - Will list all teams in the server
/team prefix <prefix> - Will change the prefix for your team in chat
/team ally [add|remove] <team-name> - Will either add or remove an allied team to yours
/team enemy [add|remove] <team-name> - Will either add or remove an enemy team to yours
/team pvp - Will toggle the friendly fire status for your team
/team [sethome|home] - Will set a team home location or teleport you or you team members to this location.
/teamadmin command
Aliases: /ta

The /teamadmin command is purely for server admins only.

4 arguments are implemented which are:

/teamadmin reload - This reloads the plugins config.yml & the messages.yml files from disk.
/teamadmin disband <team-name> - This allows admins to delete any unauthorised teams.
/teamadmin about - This give you an overview of the plugin's core information.
/tc command
Aliases: /teamchat, /tchat, /tc

The /tc command is for the sole purpose of utilising the per team chat. The following syntax is accepted:

/tc <message> - This will send a message to only the members of YOUR team or the team you are in.

# Permissions
 
Player permissions

ultimateteams.chat.spy
ultimateteams.team.create
ultimateteams.team.warp
ultimateteams.team.setwarp
ultimateteams.team.delwarp
ultimateteams.team.disband
ultimateteams.team.invite.accept
ultimateteams.team.invite.send
ultimateteams.team.invite.deny
ultimateteams.team.sethome
ultimateteams.team.home
ultimateteams.team.pvp
ultimateteams.team.enemy.add
ultimateteams.team.enemy.remove
ultimateteams.team.ally.add
ultimateteams.team.ally.remove
ultimateteams.team.leave
ultimateteams.team.kick
ultimateteams.team.join
ultimateteams.team.list
ultimateteams.team.transfer
ultimateteams.team.prefix
ultimateteams.team.info
Admin permissions:

ultimateteams.admin.about
ultimateteams.admin.reload
ultimateteams.admin.about
ultimateteams.bypass.pvp
ultimateteams.bypass.homecooldown
ultimateteams.bypass.chatcooldown
ultimateteams.bypass.warpcooldown
