Go beyond invisible - be undetectable and anonymous.
Give your players that creepy feeling.

![pa_banner.png](https://s28.postimg.org/jido5c6fx/pa_banner.png)

This plugin works very well for Minecraft 1.10, and some earlier versions are available for older versions of Minecraft. However, it will not be updated for future Minecraft versions because I've finally retired from Minecraft development (5 years of plugins!), and I'm moving on to develop indie games. :) You can follow me in my adventures here: 

facebook.com/BigScaryGames

PhantomAdmin turns your administrative team into ghosts - players won't know who they are, where they are, what they're doing, or even whether they're online unless they decide to reveal themselves. Administrative invisibility plugins stop at just making your character invisible in-game, but don't eliminate all the ways you can accidentally reveal your presence, like opening doors or chests, noisily placing blocks, stepping on pressure plates, accidentally chatting or dropping items with Q and so on. PhantomAdmin does all that, and also mitigates your server's vulnerability to account hacking (password-guessing) apps by hiding admins' identities behind nicknames so that players won't get an admin's real in-game name.


**Features**

Invisibility is foolproof and always-on. Unlike some other popular solutions, you can't accidentally log in with invisibility off, and reloading this plugin won't force you back into visibility. You also won't show up in any server queries (like those used by server list websites). The server will actually stop sending information about you to players, making it impossible for players to see you with hacked clients or other cheats. There are of course no particles or other effects indicating your location. If you really want to appear, you can toggle invisibility with slash commands.

Config Notes: You may optionally disable invisibility-by-default, which means that you would log in visibly and only go invisible when you type /Vanish.

Security Through Anonymity. Players who know your user name might use it to nefarious ends, like launching a password-guesser (account "hacker") app to log into your server as you and do permanent damage. "Hackers" will never succeed in taking over your account if they don't know your username. Both public and private messages from phantoms will always display nicknames instead of real player names, and your players can still send admins private messages using their nicknames.

Config Notes: By default, you'll keep anonymity in the tab list and in chat (but not the label over your character's head) when you're visible. You may optionally disable anonymity when visible, making you chat and appear in the tab list using your real in-game name when you're not skulking about.

Forget Doors - Pass Through Walls! Noisily opening a door tips-off players that you're near. In creative mode, right-click with an ender pearl in hand to instantly pass through any solid mass, or leap across wide open spaces in a flash. Enjoy a new level of freedom - flying will seem sluggish by comparison, gamemode-switching a hassle, teleport commands tedious.

Silently Modify Container and Player Inventories. Phantom admins open chests silently (in edit mode!) and without animation, so players won't know you're working nearby. Because dropping items on players gives away your location and /give can alert a player by landing an item in his hot bar or dropping an item near him when his inventory is full, phantom admins can directly access a player's inventory with a right-click to make more subtle changes (or just have a peek!).

Build Discreetly. Phantom admins don't make any sound when breaking blocks (you do still hear your own sounds, but other nearby players won't). Make changes right behind, above, or below players without making a ruckus. Note: Block placements can still be heard by nearby players due to this craftbukkit/spigot bug.

Slash Command Invisibility. Players can't use an admin's username or nickname to determine whether he's online or not - private messages will always seem to work even when the admin isn't online, and aiming other types of slash commands at an admin when the player doesn't have permission to see him will result in the command being cancelled, whether the admin is online or not.

Safety Switches to Keep You Hidden. Never accidentally drop an item, send a slash command line as chat, activate a touch plate, or pick up items again! So many minor stumbles can reveal your presence to nearby players. Phantom admins enjoy automatic safety mechanisms which can be conveniently toggled on or off by sneaking (holding shift) - no tedious slash commands, config file changes, or permission updates necessary!

No login/logout/death Messages for Phantoms. Players will always wonder whether admins are online and watching them, which will surely motivate them to be on their best behavior even when you're not really watching. ;) Did you know even a creative mode player can die, revealing his presence and player name? Both the Vanilla /kill command and falling out of the world can kill an otherwise invincible player, so PhantomAdmin even hides death messages.

Super-Simple Setup. Default settings work perfectly for semi-vanilla servers where all admins are /op. Otherwise, setup only requires assigning a few permission nodes and giving PhantomAdmin your list of private message commands (in the config file). All other settings are entirely optional, with defaults set to deliver maximum security.

All messages are customizable. Use messages.yml to translate all the messages sent to players and admins into any language you choose.

Created by an Experienced and Professional Developer. This plugin delivers what its description promises. I have a great track record for creating quality plugins and maintaining them over time.

Why not keep using VanishNoPacket (it's free)?
PA hides your identity (in-game name) in chat and private messages, VNP does not. "Hackers" who have your in-game name may use password guessers to discover your password and log into your server as an administrator.
PA allows editing silently-opened chests, VNP offers only read-only.
PA prevents players from determining your online status by targeting you with slash commands, VNP does not.
PA allows access to player inventories, VNP does not.
PA allows toggling common options like item pickup, item drop, and touchplate activation by sneaking. VNP has you memorize and tediously type slash commands and/or toggle your invisibility for common tasks.
PA allows for passing through walls without slash commands. With VNP, opening doors alerts players to your presence.
VNP is bloated with aesthetics like smoke and lightning.
PA works out of the box for server ops. VNP requires a permissions plugin for initial setup.
VNP doesn't stop experience orbs from revealing your location, PA does.
PA silently breaks blocks, VNP doesn't.
VNP makes you visible every time you /reload, PA does not.
VNP hasn't been updated in more than a year, and the comments are disabled. PA is supported.

**Commands**

/UnlockChat allows you to chat. Chat is turned off by default for phantom admins to prevent accidental chat by missing the slash (/) at the front of a command line.

/SetNickname sets a player's anonymous nickname.

/SetChatFormat sets a player's anonymous chat format.

/Appear makes you visible to all players.

/Vanish makes you invisible to all players who don't have permission to see invisible.

/PlayerInventory accesses a player's personal inventory.

/EnderInventory accesses a player's ender chest inventory.

/WhoIs reveals the real names of nicknamed players.

/PAReload re-loads settings from the config file, useful if you've changed your config while the server is running.

Note: Default anonymous nickname, default anonymous chat format, and the anonymous whisper message formats are all configurable in config.yml.


**Permissions**

phantomadmin.* conveniently grants all of the below.
phantomadmin.anonymous - anonymous chat.
phantomadmin.invisible - invisibility.
phantomadmin.teleport - teleport with ender pearl in creative mode.
phantomadmin.silentjoinleave - join and leave without sending a notification message to all players.
phantomadmin.setnickname - set personal nickname.
phantomadmin.setchatformat - set personal anonymous chat style.
phantomadmin.setnicknameother - set someone else's nickname.
phantomadmin.setchatformatother - set someone else's chat style.
phantomadmin.seeinvisible - see invisible players.
phantomadmin.inventoryaccess - access and change another player's personal or ender chest inventory.
phantomadmin.reload - grants access to /PAReload.

Note: Changing a player's permissions doesn't immediately change his visibility status. He'll have to /Vanish, or log out and back in (assuming you haven't disabled invisibility by default in the config).


**Installation** 

Copy PhantomAdmin.jar into your plugins folder and either /reload or reboot your server.
If your server has any non-vanilla private messaging commands, update PhantomAdmin's config file to list them.
Optional - update the defaults for nicknames and chat format in the config file. The default settings make all players appear the same as a player chatting using the console (/say and /tell).
Optional - update the anonymous private message formats in the config file. The default setting makes anonymous private messages look the same as vanilla private messages (/tell).
