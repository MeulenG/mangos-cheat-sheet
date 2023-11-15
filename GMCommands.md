### account
- GM Level: 0
- Syntax: Syntax: .account
- Description: Display the access level of your account.

### account characters
- GM Level: 3
- Syntax: Syntax: .account characters [#accountId|$accountName]
- Description: Show list all characters for account selected by provided #accountId or $accountName, or for selected player in game.

### account create
- GM Level: 4
- Syntax: Syntax: .account create $account $password
- Description: Create account and set password to it.

### account delete
- GM Level: 4
- Syntax: Syntax: .account delete $account
- Description: Delete account with all characters.

### account lock
- GM Level: 0
- Syntax: Syntax: .account lock [on|off]
- Description: Allow login from account only from current used IP or remove this requirement.

### account onlinelist
- GM Level: 4
- Syntax: Syntax: .account onlinelist
- Description: Show list of online accounts.

### account password
- GM Level: 0
- Syntax: Syntax: .account password $old_password $new_password $new_password
- Description: Change your account password.

### account set addon
- GM Level: 3
- Syntax: Syntax: .account set addon [#accountId|$accountName] #addon
- Description: Set user (possible targeted) expansion addon level allowed. Addon values: 0 â€" normal, 1 â€" tbc, 2 â€" wotlk.

### account set gmlevel
- GM Level: 4
- Syntax: Syntax: .account set gmlevel [#accountId|$accountName] #level
- Description: Set the security level for targeted player (canâ€™t be used at self) or for #accountId or $accountName to a level of #level.; #level may range from 0 to 3.

### account set password
- GM Level: 4
- Syntax: Syntax: .account set password (#accountId|$accountName) $password $password
- Description: Set password for account.

### achievement
- GM Level: 3
- Syntax: Syntax: .achievement $playername #achivementid
- Description: Show state achievment #achivmentid (can be shift link) and list of achievement criteria with progress data for selected player in game or by player name.

### achievement add
- GM Level: 3
- Syntax: Syntax: .achievement add $playername #achivementid
- Description: Complete achievement and all itâ€™s criteria for selected player in game or by player name. Command canâ€™t be used for counter achievements.

### achievement criteria add
- GM Level: 3
- Syntax: Syntax: .achievement criteria add $playername #criteriaid #change
- Description: Increase progress for non-completed criteria at #change for selected player in game or by player name. If #chnage not provided then non-counter criteria progress set to completed state. For counter criteria increased at 1.

### achievement criteria remove
- GM Level: 3
- Syntax: Syntax: .achievement criteria remove $playername #criteriaid #change
- Description: ecrease progress for criteria at #change for selected player in game or by player name. If #chnage not provided then criteria progress reset to 0.

### achievement remove
- GM Level: 3
- Syntax: Syntax: .achievement remove $playername #achivementid
- Description: Remove complete state for achievement #achivmentid and reset all achievementâ€™s criteria for selected player in game or by player name. Also command can be used for reset counter achievements.

### additem
- GM Level: 3
- Syntax: Syntax: .additem #itemid/[#itemname]/#shift-click-item-link #itemcount
- Description: Adds the specified number of items of id #itemid (or exact (!) name $itemname in brackets, or link created by shift-click at item in inventory or recipe) to your or selected character inventory. If #itemcount is omitted, only one item will be added.; .

### additemset
- GM Level: 3
- Syntax: Syntax: .additemset #itemsetid
- Description: Add items from itemset of id #itemsetid to your or selected character inventory. Will add by one example each item from itemset.

### ahbot items amount
- GM Level: 3
- Syntax: Syntax: .ahbot items amount $GreyItems $WhiteItems $GreenItems $BlueItems $PurpleItems $OrangeItems $YellowItems
- Description: Set amount of each items color be selled on auction.

### ahbot items amount blue
- GM Level: 3
- Syntax: Syntax: .ahbot items amount blue $BlueItems
- Description: Set amount of Blue color items be selled on auction.

### ahbot items amount green
- GM Level: 3
- Syntax: Syntax: .ahbot items amount green $GreenItems
- Description: Set amount of Green color items be selled on auction.

### ahbot items amount grey
- GM Level: 3
- Syntax: Syntax: .ahbot items amount grey $GreyItems
- Description: Set amount of Grey color items be selled on auction.

### ahbot items amount orange
- GM Level: 3
- Syntax: Syntax: .ahbot items amount orange $OrangeItems
- Description: Set amount of Orange color items be selled on auction.

### ahbot items amount purple
- GM Level: 3
- Syntax: Syntax: .ahbot items amount purple $PurpleItems
- Description: Set amount of Purple color items be selled on auction.

### ahbot items amount white
- GM Level: 3
- Syntax: Syntax: .ahbot items amount white $WhiteItems
- Description: Set amount of White color items be selled on auction.

### ahbot items amount yellow
- GM Level: 3
- Syntax: Syntax: .ahbot items amount yellow $YellowItems
- Description: Set amount of Yellow color items be selled on auction.

### ahbot items ratio
- GM Level: 3
- Syntax: Syntax: .ahbot items ratio $allianceratio $horderatio $neutralratio
- Description: Set ratio of items in 3 auctions house.

### ahbot items ratio alliance
- GM Level: 3
- Syntax: Syntax: .ahbot items ratio alliance $allianceratio
- Description: Set ratio of items in alliance auction house.

### ahbot items ratio horde
- GM Level: 3
- Syntax: Syntax: .ahbot items ratio horde $horderatio
- Description: Set ratio of items in horde auction house.

### ahbot items ratio neutral
- GM Level: 3
- Syntax: Syntax: .ahbot items ratio neutral $neutralratio
- Description: Set ratio of items in $neutral auction house.

### ahbot rebuild
- GM Level: 3
- Syntax: Syntax: .ahbot rebuild [all]
- Description: Expire all actual auction of ahbot except bided by player. Binded auctions included to expire if â€œallâ€ option used. Ahbot re-fill auctions base at current settings then.

### ahbot reload
- GM Level: 3
- Syntax: Syntax: .ahbot reload
- Description: Reload AHBot settings from configuration file.

### ahbot status
- GM Level: 3
- Syntax: Syntax: .ahbot status [all]
- Description: Show current ahbot state data in short form, and with â€œallâ€ with details.

### announce
- GM Level: 1
- Syntax: Syntax: .announce $MessageToBroadcast
- Description: Send a global message to all players online in chat log.

### auction
- GM Level: 3
- Syntax: Syntax: .auction
- Description: Show your team auction store.

### auction alliance
- GM Level: 3
- Syntax: Syntax: .auction alliance
- Description: Show alliance auction store independent from your team.

### auction goblin
- GM Level: 3
- Syntax: Syntax: .auction goblin
- Description: Show goblin auction store common for all teams.

### auction horde
- GM Level: 3
- Syntax: Syntax: .auction horde
- Description: Show horde auction store independent from your team.

### auction item
- GM Level: 3
- Syntax: Syntax: .auction item (alliance|horde|goblin) #itemid[:#itemcount] [[[#minbid] #buyout] [short|long|verylong]
- Description: Add new item (in many stackes if amount grater stack size) to specific auction house at short|long|verylogn perios similar same settings in auction in game dialog. Created auction not have owner.

### aura
- GM Level: 3
- Syntax: Syntax: .aura #spellid
- Description: Add the aura from spell #spellid to the selected Unit.

### ban account
- GM Level: 3
- Syntax: Syntax: .ban account $Name $bantime $reason; Ban account kick player.; $bantime: negative value leads to permban, otherwise use a timestring like â€œ4d20h3sâ€.
- Description: nan

### ban character
- GM Level: 3
- Syntax: Syntax: .ban character $Name $bantime $reason; Ban account and kick player.; $bantime: negative value leads to permban, otherwise use a timestring like â€œ4d20h3sâ€.
- Description: nan

### ban ip
- GM Level: 3
- Syntax: Syntax: .ban ip $Ip $bantime $reason; Ban IP.; $bantime: negative value leads to permban, otherwise use a timestring like â€œ4d20h3sâ€.
- Description: nan

### baninfo account
- GM Level: 3
- Syntax: Syntax: .baninfo account $accountid; Watch full information about a specific ban.
- Description: nan

### baninfo character
- GM Level: 3
- Syntax: Syntax: .baninfo character $charactername; Watch full information about a specific ban.
- Description: nan

### baninfo ip
- GM Level: 3
- Syntax: Syntax: .baninfo ip $ip; Watch full information about a specific ban.
- Description: nan

### bank
- GM Level: 3
- Syntax: Syntax: .bank
- Description: Show your bank inventory.

### banlist account
- GM Level: 3
- Syntax: Syntax: .banlist account [$Name]; Searches the banlist for a account name pattern or show full list account bans.
- Description: nan

### banlist character
- GM Level: 3
- Syntax: Syntax: .banlist character $Name; Searches the banlist for a character name pattern. Pattern required.
- Description: nan

### banlist ip
- GM Level: 3
- Syntax: Syntax: .banlist ip [$Ip]; Searches the banlist for a IP pattern or show full list of IP bans.
- Description: nan

### cast
- GM Level: 3
- Syntax: Syntax: .cast #spellid [triggered]; Cast #spellid to selected target. If no target selected cast to self. If â€˜trigeredâ€™ or part provided then spell casted with triggered flag.
- Description: nan

### cast back
- GM Level: 3
- Syntax: Syntax: .cast back #spellid [triggered]; Selected target will cast #spellid to your character. If â€˜trigeredâ€™ or part provided then spell casted with triggered flag.
- Description: nan

### cast dist
- GM Level: 3
- Syntax: Syntax: .cast dist #spellid [#dist [triggered]]; You will cast spell to pint at distance #dist. If â€˜trigeredâ€™ or part provided then spell casted with triggered flag. Not all spells can be casted as area spells.
- Description: nan

### cast self
- GM Level: 3
- Syntax: Syntax: .cast self #spellid [triggered]; Cast #spellid by target at target itself. If â€˜trigeredâ€™ or part provided then spell casted with triggered flag.
- Description: nan

### cast target
- GM Level: 3
- Syntax: Syntax: .cast target #spellid [triggered]; Selected target will cast #spellid to his victim. If â€˜trigeredâ€™ or part provided then spell casted with triggered flag.
- Description: nan

### character achievements
- GM Level: 2
- Syntax: Syntax: .character achievements [$player_name]
- Description: Show completed achievments for selected player or player find by $player_name.

### character customize
- GM Level: 2
- Syntax: Syntax: .character customize [$name]
- Description: Mark selected in game or by $name in command character for customize at next login.

### character deleted delete
- GM Level: 4
- Syntax: Syntax: .character deleted delete #guid|$name
- Description: Completely deletes the selected characters.; If $name is supplied, only characters with that string in their name will be deleted, if #guid is supplied, only the character with that GUID will be deleted.

### character deleted list
- GM Level: 3
- Syntax: Syntax: .character deleted list [#guid|$name]
- Description: Shows a list with all deleted characters.; If $name is supplied, only characters with that string in their name will be selected, if #guid is supplied, only the character with that GUID will be selected.

### character deleted old
- GM Level: 4
- Syntax: Syntax: .character deleted old [#keepDays]
- Description: Completely deletes all characters with deleted time longer #keepDays. If #keepDays not provided the used value from mangosd.conf option â€˜CharDelete.KeepDaysâ€™. If referenced config option disabled (use 0 value) then command canâ€™t be used without #keepDays.

### character deleted restore
- GM Level: 3
- Syntax: Syntax: .character deleted restore #guid|$name [$newname] [#new account]
- Description: Restores deleted characters.; If $name is supplied, only characters with that string in their name will be restored, if $guid is supplied, only the character with that GUID will be restored.; If $newname is set, the character will be restored with that name instead of the original one. If #newaccount is set, the character will be restored to specific account character list. This works only with one character!

### character erase
- GM Level: 4
- Syntax: Syntax: .character erase $name
- Description: Delete character $name. Character finally deleted in case any deleting options.

### character level
- GM Level: 3
- Syntax: Syntax: .character level [$playername] [#level]
- Description: Set the level of character with $playername (or the selected if not name provided) by #numberoflevels Or +1 if no #numberoflevels provided). If #numberoflevels is omitted, the level will be increase by 1. If #numberoflevels is 0, the same level will be restarted. If no character is selected and name not provided, increase your level. Command can be used for offline character. All stats and dependent values recalculated. At level decrease talents can be reset if need. Also at level decrease equipped items with greater level requirement can be lost.

### character rename
- GM Level: 2
- Syntax: Syntax: .character rename [$name]
- Description: Mark selected in game or by $name in command character for rename at next login.

### character reputation
- GM Level: 2
- Syntax: Syntax: .character reputation [$player_name]
- Description: Show reputation information for selected player or player find by $player_name.

### character titles
- GM Level: 2
- Syntax: Syntax: .character titles [$player_name]
- Description: Show known titles list for selected player or player find by $player_name.

### combatstop
- GM Level: 2
- Syntax: Syntax: .combatstop [$playername]; Stop combat for selected character. If selected non-player then command applied to self. If $playername provided then attempt applied to online player $playername.
- Description: nan

### commands
- GM Level: 0
- Syntax: Syntax: .commands
- Description: Display a list of available commands for your account level.

### cooldown
- GM Level: 3
- Syntax: Syntax: .cooldown [#spell_id]
- Description: Remove all (if spell_id not provided) or #spel_id spell cooldown from selected character or you (if no selection).

### damage
- GM Level: 3
- Syntax: Syntax: .damage $damage_amount [$school [$spellid]]
- Description: Apply $damage to target. If not $school and $spellid provided then this flat clean melee damage without any modifiers. If $school provided then damage modified by armor reduction (if school physical), and target absorbing modifiers and result applied as melee damage to target. If spell provided then damage modified and applied as spell damage. $spellid can be shift-link.

### debug anim
- GM Level: 2
- Syntax: Syntax: .debug anim #emoteid
- Description: Play emote #emoteid for your character.

### debug arena
- GM Level: 3
- Syntax: Syntax: .debug arena
- Description: Toggle debug mode for arenas. In debug mode GM can start arena with single player.

### debug bg
- GM Level: 3
- Syntax: Syntax: .debug bg
- Description: Toggle debug mode for battlegrounds. In debug mode GM can start battleground with single player.

### debug getitemvalue
- GM Level: 3
- Syntax: Syntax: .debug getitemvalue #itemguid #field [int|hex|bit|float]
- Description: Get the field #field of the item #itemguid in your inventroy.; Use type arg for set output format: int (decimal number), hex (hex value), bit (bitstring), float. By default use integer output.

### debug getvalue
- GM Level: 3
- Syntax: Syntax: .debug getvalue #field [int|hex|bit|float]
- Description: Get the field #field of the selected target. If no target is selected, get the content of your field.; Use type arg for set output format: int (decimal number), hex (hex value), bit (bitstring), float. By default use integer output.

### debug moditemvalue
- GM Level: 3
- Syntax: Syntax: .debug moditemvalue #guid #field [int|float| &= | |= | &=~ ] #value
- Description: Modify the field #field of the item #itemguid in your inventroy by value #value.; Use type arg for set mode of modification: int (normal add/subtract #value as decimal number), float (add/subtract #value as float number), &= (bit and, set to 0 all bits in value if it not set to 1 in #value as hex number), |= (bit or, set to 1 all bits in value if it set to 1 in #value as hex number), &=~ (bit and not, set to 0 all bits in value if it set to 1 in #value as hex number). By default expect integer add/subtract.

### debug modvalue
- GM Level: 3
- Syntax: Syntax: .debug modvalue #field [int|float| &= | |= | &=~ ] #value
- Description: Modify the field #field of the selected target by value #value. If no target is selected, set the content of your field.; Use type arg for set mode of modification: int (normal add/subtract #value as decimal number), float (add/subtract #value as float number), &= (bit and, set to 0 all bits in value if it not set to 1 in #value as hex number), |= (bit or, set to 1 all bits in value if it set to 1 in #value as hex number), &=~ (bit and not, set to 0 all bits in value if it set to 1 in #value as hex number). By default expect integer add/subtract.

### debug play cinematic
- GM Level: 1
- Syntax: Syntax: .debug play cinematic #cinematicid
- Description: Play cinematic #cinematicid for you. You stay at place while your mind fly.

### debug play movie
- GM Level: 1
- Syntax: Syntax: .debug play movie #movieid
- Description: Play movie #movieid for you.

### debug play sound
- GM Level: 1
- Syntax: Syntax: .debug play sound #soundid
- Description: Play sound with #soundid.; Sound will be play only for you. Other players do not hear this.; Warning: client may have more 5000 soundsâ€¦

### debug setitemvalue
- GM Level: 3
- Syntax: Syntax: .debug setitemvalue #guid #field [int|hex|bit|float] #value
- Description: Set the field #field of the item #itemguid in your inventroy to value #value.; Use type arg for set input format: int (decimal number), hex (hex value), bit (bitstring), float. By default expect integer input format.

### debug setvalue
- GM Level: 3
- Syntax: Syntax: .debug setvalue #field [int|hex|bit|float] #value
- Description: Set the field #field of the selected target to value #value. If no target is selected, set the content of your field.; Use type arg for set input format: int (decimal number), hex (hex value), bit (bitstring), float. By default expect integer input format.

### debug spellcoefs
- GM Level: 3
- Syntax: Syntax: .debug spellcoefs #spellid
- Description: Show default calculated and DB stored coefficients for direct/dot heal/damage.

### debug spellmods
- GM Level: 3
- Syntax: Syntax: .debug spellmods (flat|pct) #spellMaskBitIndex #spellModOp #value
- Description: Set at client side spellmod affect for spell that have bit set with index #spellMaskBitIndex in spell family mask for values dependent from spellmod #spellModOp to #value.

### delticket
- GM Level: 2
- Syntax: Syntax: .delticket all; .delticket #num; .delticket $character_name
- Description: all to dalete all tickets at server, $character_name to delete ticket of this character, #num to delete ticket #num.

### demorph
- GM Level: 2
- Syntax: Syntax: .demorph
- Description: Demorph the selected player.

### die
- GM Level: 3
- Syntax: Syntax: .die
- Description: Kill the selected player. If no player is selected, it will kill you.

### dismount
- GM Level: 0
- Syntax: Syntax: .dismount
- Description: Dismount you, if you are mounted.

### distance
- GM Level: 3
- Syntax: Syntax: .distance [$name/$link]
- Description: Display the distance from your character to the selected creature/player, or player with name $name, or player/creature/gameobject pointed to shift-link with guid.

### event
- GM Level: 2
- Syntax: Syntax: .event #event_id; Show details about event with #event_id.
- Description: nan

### event list
- GM Level: 2
- Syntax: Syntax: .event list; Show list of currently active events.; Show list of all events
- Description: nan

### event start
- GM Level: 2
- Syntax: Syntax: .event start #event_id; Start event #event_id. Set start time for event to current moment (change not saved in DB).
- Description: nan

### event stop
- GM Level: 2
- Syntax: Syntax: .event stop #event_id; Stop event #event_id. Set start time for event to time in past that make current moment is event stop time (change not saved in DB).
- Description: nan

### explorecheat
- GM Level: 3
- Syntax: Syntax: .explorecheat #flag
- Description: Reveal or hide all maps for the selected player. If no player is selected, hide or reveal maps to you.; Use a #flag of value 1 to reveal, use a #flag value of 0 to hide all maps.

### flusharenapoints
- GM Level: 3
- Syntax: Syntax: .flusharenapoints
- Description: Use it to distribute arena points based on arena team ratings, and start a new week.

### gearscore
- GM Level: 3
- Syntax: Syntax: .gearscore [#withBags] [#withBank]
- Description: Show selected playerâ€™s gear score. Check items in bags if #withBags != 0 and check items in Bank if #withBank != 0. Default: 1 for bags and 0 for bank

### gm
- GM Level: 1
- Syntax: Syntax: .gm [on/off]
- Description: Enable or Disable in game GM MODE or show current state of on/off not provided.

### gm chat
- GM Level: 1
- Syntax: Syntax: .gm chat [on/off]
- Description: Enable or disable chat GM MODE (show gm badge in messages) or show current state of on/off not provided.

### gm fly
- GM Level: 3
- Syntax: Syntax: .gm fly [on/off]; Enable/disable gm fly mode.
- Description: nan

### gm ingame
- GM Level: 0
- Syntax: Syntax: .gm ingame
- Description: Display a list of available in game Game Masters.

### gm list
- GM Level: 3
- Syntax: Syntax: .gm list
- Description: Display a list of all Game Masters accounts and security levels.

### gm setview
- GM Level: 1
- Syntax: Syntax: .gm setview
- Description: Set farsight view on selected unit. Select yourself to set view back.

### gm visible
- GM Level: 1
- Syntax: Syntax: .gm visible on/off
- Description: Output current visibility state or make GM visible(on) and invisible(off) for other players.

### go
- GM Level: 1
- Syntax: Syntax: .go [$playername|pointlink|#x #y #z [#mapid]]; Teleport your character to point with coordinates of player $playername, or coordinates of one from shift-link types: player, tele, taxinode, creature/creature_entry, gameobject/gameobject_entry, or explicit #x #y #z #mapid coordinates.
- Description: nan

### go creature
- GM Level: 1
- Syntax: Syntax: .go creature (#creature_guid|$creature_name|id #creature_id); Teleport your character to creature with guid #creature_guid, or teleport your character to creature with name including as part $creature_name substring, or teleport your character to a creature that was spawned from the template with this entry #creature_id.
- Description: nan

### go graveyard
- GM Level: 1
- Syntax: Syntax: .go graveyard #graveyardId; Teleport to graveyard with the graveyardId specified.
- Description: nan

### go grid
- GM Level: 1
- Syntax: Syntax: .go grid #gridX #gridY [#mapId]
- Description: Teleport the gm to center of grid with provided indexes at map #mapId (or current map if it not provided).

### go object
- GM Level: 1
- Syntax: Syntax: .go object (#gameobject_guid|$gameobject_name|id #gameobject_id); Teleport your character to gameobject with guid #gameobject_guid, or teleport your character to gameobject with name including as part $gameobject_name substring, or teleport your character to a gameobject that was spawned from the template with this entry #gameobject_id.
- Description: nan

### go taxinode
- GM Level: 1
- Syntax: Syntax: .go taxinode #taxinode
- Description: Teleport player to taxinode coordinates. You can look up zone using .lookup taxinode $namepart

### go trigger
- GM Level: 1
- Syntax: Syntax: .go trigger (#trigger_id|$trigger_shift-link|$trigger_target_shift-link) [target]
- Description: Teleport your character to areatrigger with id #trigger_id or trigger id associated with shift-link. If additional arg â€œtargetâ€ provided then character will teleported to areatrigger target point.

### go xy
- GM Level: 1
- Syntax: Syntax: .go xy #x #y [#mapid]
- Description: Teleport player to point with (#x,#y) coordinates at ground(water) level at map #mapid or same map if #mapid not provided.

### go xyz
- GM Level: 1
- Syntax: Syntax: .go xyz #x #y #z [#mapid]
- Description: Teleport player to point with (#x,#y,#z) coordinates at ground(water) level at map #mapid or same map if #mapid not provided.

### go zonexy
- GM Level: 1
- Syntax: Syntax: .go zonexy #x #y [#zone]
- Description: Teleport player to point with (#x,#y) client coordinates at ground(water) level in zone #zoneid or current zone if #zoneid not provided. You can look up zone using .lookup area $namepart

### gobject add
- GM Level: 2
- Syntax: Syntax: .gobject add #id
- Description: Add a game object from game object templates to the world at your current location using the #id.; spawntimesecs sets the spawntime, it is optional.; Note: this is a copy of .gameobject.

### gobject delete
- GM Level: 2
- Syntax: Syntax: .gobject delete #go_guid; Delete gameobject with guid #go_guid.
- Description: nan

### gobject move
- GM Level: 2
- Syntax: Syntax: .gobject move #goguid [#x #y #z]
- Description: Move gameobject #goguid to character coordinates (or to (#x,#y,#z) coordinates if its provide).

### gobject near
- GM Level: 2
- Syntax: Syntax: .gobject near [#distance]
- Description: Output gameobjects at distance #distance from player. Output gameobject guids and coordinates sorted by distance from character. If #distance not provided use 10 as default value.

### gobject setphase
- GM Level: 2
- Syntax: Syntax: .gobject setphase #guid #phasemask
- Description: Gameobject with DB guid #guid phasemask changed to #phasemask with related world vision update for players. Gameobject state saved to DB and persistent.

### gobject target
- GM Level: 2
- Syntax: Syntax: .gobject target [#go_id|#go_name_part]
- Description: Locate and show position nearest gameobject. If #go_id or #go_name_part provide then locate and show position of nearest gameobject with gameobject template id #go_id or name included #go_name_part as part.

### gobject turn
- GM Level: 2
- Syntax: Syntax: .gobject turn #goguid [#z_angle]
- Description: Changes gameobject #goguid orientation (rotates gameobject around z axis). Optional parameters are (#y_angle,#x_angle) values that represents rotation angles around y and x axes.

### goname
- GM Level: 1
- Syntax: Syntax: .goname [$charactername]
- Description: Teleport to the given character. Either specify the character name or click on the characterâ€™s portrait, e.g. when you are in a group. Character can be offline.

### gps
- GM Level: 1
- Syntax: Syntax: .gps [$name|$shift-link]
- Description: Display the position information for a selected character or creature (also if player name $name provided then for named player, or if creature/gameobject shift-link provided then pointed creature/gameobject if it loaded). Position information includes X, Y, Z, and orientation, map Id and zone Id

### groupgo
- GM Level: 1
- Syntax: Syntax: .groupgo [$charactername]
- Description: Teleport the given character and his group to you. Teleported only online characters but original selected group member can be offline.

### guid
- GM Level: 2
- Syntax: Syntax: .guid
- Description: Display the GUID for the selected character.

### guild create
- GM Level: 2
- Syntax: Syntax: .guild create [$GuildLeaderName] â€œ$GuildNameâ€
- Description: Create a guild named $GuildName with the player $GuildLeaderName (or selected) as leader. Guild name must in quotes.

### guild delete
- GM Level: 2
- Syntax: Syntax: .guild delete â€œ$GuildNameâ€
- Description: Delete guild $GuildName. Guild name must in quotes.

### guild invite
- GM Level: 2
- Syntax: Syntax: .guild invite [$CharacterName] â€œ$GuildNameâ€
- Description: Add player $CharacterName (or selected) into a guild $GuildName. Guild name must in quotes.

### guild rank
- GM Level: 2
- Syntax: Syntax: .guild rank $CharacterName #Rank
- Description: Set for $CharacterName rank #Rank in a guild.

### guild uninvite
- GM Level: 2
- Syntax: Syntax: .guild uninvite [$CharacterName]
- Description: Remove player $CharacterName (or selected) from a guild.

### help
- GM Level: 0
- Syntax: Syntax: .help [$command]
- Description: Display usage instructions for the given $command. If no $command provided show list available commands.

### hidearea
- GM Level: 3
- Syntax: Syntax: .hidearea #areaid
- Description: Hide the area of #areaid to the selected character. If no character is selected, hide this area to you.

### honor add
- GM Level: 2
- Syntax: Syntax: .honor add $amount
- Description: Add a certain amount of honor (gained today) to the selected player.

### honor addkill
- GM Level: 2
- Syntax: Syntax: .honor addkill
- Description: Add the targeted unit as one of your pvp kills today (you only get honor if itâ€™s a racial leader or a player)

### honor updatekills
- GM Level: 2
- Syntax: Syntax: .honor updatekills
- Description: Force the yesterdayâ€™s honor kill fields to be updated with todayâ€™s data, which will get reset for the selected player.

### instance listbinds
- GM Level: 3
- Syntax: Syntax: .instance listbinds; Lists the binds of the selected player.
- Description: nan

### instance savedata
- GM Level: 3
- Syntax: Syntax: .instance savedata; Save the InstanceData for the current playerâ€™s map to the DB.
- Description: nan

### instance stats
- GM Level: 3
- Syntax: Syntax: .instance stats; Shows statistics about instances.
- Description: nan

### instance unbind
- GM Level: 3
- Syntax: Syntax: .instance unbind all; All of the selected playerâ€™s binds will be cleared.; .instance unbind #mapid; Only the specified #mapid instance will be cleared.
- Description: nan

### itemmove
- GM Level: 2
- Syntax: Syntax: .itemmove #sourceslotid #destinationslotid
- Description: Move an item from slots #sourceslotid to #destinationslotid in your inventory; Not yet implemented

### kick
- GM Level: 2
- Syntax: Syntax: .kick [$charactername]
- Description: Kick the given character name from the world. If no character name is provided then the selected player (except for yourself) will be kicked.

### learn
- GM Level: 3
- Syntax: Syntax: .learn #spell [all]
- Description: Selected character learn a spell of id #spell. If â€˜allâ€™ provided then all ranks learned.

### learn all
- GM Level: 3
- Syntax: Syntax: .learn all
- Description: Learn all big set different spell maybe useful for Administaror.

### learn all_crafts
- GM Level: 2
- Syntax: Syntax: .learn crafts
- Description: Learn all professions and recipes.

### learn all_default
- GM Level: 1
- Syntax: Syntax: .learn all_default [$playername]
- Description: Learn for selected/$playername player all default spells for his race/class and spells rewarded by completed quests.

### learn all_gm
- GM Level: 2
- Syntax: Syntax: .learn all_gm
- Description: Learn all default spells for Game Masters.

### learn all_lang
- GM Level: 1
- Syntax: Syntax: .learn all_lang
- Description: Learn all languages

### learn all_myclass
- GM Level: 3
- Syntax: Syntax: .learn all_myclass
- Description: Learn all spells and talents available for his class.

### learn all_mypettalents
- GM Level: 3
- Syntax: Syntax: .learn all_mypettalents
- Description: Learn all talents for your pet available for his creature type (only for hunter pets).

### learn all_myspells
- GM Level: 3
- Syntax: Syntax: .learn all_myspells
- Description: Learn all spells (except talents and spells with first rank learned as talent) available for his class.

### learn all_mytalents
- GM Level: 3
- Syntax: Syntax: .learn all_mytalents
- Description: Learn all talents (and spells with first rank learned as talent) available for his class.

### learn all_recipes
- GM Level: 2
- Syntax: Syntax: .learn all_recipes [$profession]
- Description: Learns all recipes of specified profession and sets skill level to max.; Example: .learn all_recipes enchanting

### levelup
- GM Level: 3
- Syntax: Syntax: .levelup [$playername] [#numberoflevels]
- Description: Increase/decrease the level of character with $playername (or the selected if not name provided) by #numberoflevels Or +1 if no #numberoflevels provided). If #numberoflevels is omitted, the level will be increase by 1. If #numberoflevels is 0, the same level will be restarted. If no character is selected and name not provided, increase your level. Command can be used for offline character. All stats and dependent VALUESrecalculated. At level decrease talents can be reset if need. Also at level decrease equipped items with greater level requirement can be lost.

### linkgrave
- GM Level: 3
- Syntax: Syntax: .linkgrave #graveyard_id [alliance|horde]
- Description: Link current zone to graveyard for any (or alliance/horde faction ghosts). This let character ghost from zone teleport to graveyard after die if graveyard is nearest from linked to zone and accept ghost of this faction. Add only single graveyard at another map and only if no graveyards linked (or planned linked at same map).

### list creature
- GM Level: 3
- Syntax: Syntax: .list creature #creature_id [#max_count]
- Description: Output creatures with creature id #creature_id found in world. Output creature guids and coordinates sorted by distance from character. Will be output maximum #max_count creatures. If #max_count not provided use 10 as default value.

### list item
- GM Level: 3
- Syntax: Syntax: .list item #item_id [#max_count]
- Description: Output items with item id #item_id found in all character inventories, mails, auctions, and guild banks. Output item guids, item owner guid, owner account and owner name (guild name and guid in case guild bank). Will be output maximum #max_count items. If #max_count not provided use 10 as default value.

### list object
- GM Level: 3
- Syntax: Syntax: .list object #gameobject_id [#max_count]
- Description: Output gameobjects with gameobject id #gameobject_id found in world. Output gameobject guids and coordinates sorted by distance from character. Will be output maximum #max_count gameobject. If #max_count not provided use 10 as default value.

### list talents
- GM Level: 3
- Syntax: Syntax: .list talents
- Description: Show list all really known (as learned spells) talent rank spells for selected player or self.

### loadscripts
- GM Level: 3
- Syntax: Syntax: .loadscripts $scriptlibraryname
- Description: Unload current and load the script library $scriptlibraryname or reload current if $scriptlibraryname omitted, in case you changed it while the server was running.

### lookup account email
- GM Level: 2
- Syntax: Syntax: .lookup account email $emailpart [#limit]
- Description: Searchs accounts, which email including $emailpart with optional parametr #limit of results. If #limit not provided expected 100.

### lookup account ip
- GM Level: 2
- Syntax: Syntax: lookup account ip $ippart [#limit]
- Description: Searchs accounts, which last used ip inluding $ippart (textual) with optional parametr #$limit of results. If #limit not provided expected 100.

### lookup account name
- GM Level: 2
- Syntax: Syntax: .lookup account name $accountpart [#limit]
- Description: Searchs accounts, which username including $accountpart with optional parametr #limit of results. If #limit not provided expected 100.

### lookup achievement
- GM Level: 2
- Syntax: Syntax: .lookup $name; Looks up a achievement by $namepart, and returns all matches with their quest IDâ€™s. Achievement shift-links generated with information about achievment state for selected player. Also for completed achievments in list show complete date.
- Description: nan

### lookup area
- GM Level: 1
- Syntax: Syntax: .lookup area $namepart
- Description: Looks up an area by $namepart, and returns all matches with their area IDâ€™s.

### lookup creature
- GM Level: 3
- Syntax: Syntax: .lookup creature $namepart
- Description: Looks up a creature by $namepart, and returns all matches with their creature IDâ€™s.

### lookup currency
- GM Level: 3
- Syntax: Syntax: .lookup currency $namepart
- Description: Looks up a currency by $namepart, and returns all matches.

### lookup event
- GM Level: 2
- Syntax: Syntax: .lookup event $name; Attempts to find the ID of the event with the provided $name.
- Description: nan

### lookup faction
- GM Level: 3
- Syntax: Syntax: .lookup faction $name; Attempts to find the ID of the faction with the provided $name.
- Description: nan

### lookup item
- GM Level: 3
- Syntax: Syntax: .lookup item $itemname
- Description: Looks up an item by $itemname, and returns all matches with their Item IDâ€™s.

### lookup itemset
- GM Level: 3
- Syntax: Syntax: .lookup itemset $itemname
- Description: Looks up an item set by $itemname, and returns all matches with their Item set IDâ€™s.

### lookup object
- GM Level: 3
- Syntax: Syntax: .lookup object $objname
- Description: Looks up an gameobject by $objname, and returns all matches with their Gameobject IDâ€™s.

### lookup player account
- GM Level: 2
- Syntax: Syntax: .lookup player account $accountpart [#limit]
- Description: Searchs players, which account username including $accountpart with optional parametr #limit of results. If #limit not provided expected 100.

### lookup player email
- GM Level: 2
- Syntax: Syntax: .lookup player email $emailpart [#limit]
- Description: Searchs players, which account email including $emailpart with optional parametr #limit of results. If #limit not provided expected 100.

### lookup player ip
- GM Level: 2
- Syntax: Syntax: .lookup player ip $ippart [#limit]
- Description: Searchs players, which account last used ip inluding $ippart (textual) with optional parametr #limit of results. If #limit not provided expected 100.

### lookup pool
- GM Level: 2
- Syntax: Syntax: .lookup pool $pooldescpart
- Description: List of pools (anywhere) with substring in description.

### lookup quest
- GM Level: 3
- Syntax: Syntax: .lookup quest $namepart
- Description: Looks up a quest by $namepart, and returns all matches with their quest IDâ€™s.

### lookup skill
- GM Level: 3
- Syntax: Syntax: .lookup skill $$namepart
- Description: Looks up a skill by $namepart, and returns all matches with their skill IDâ€™s.

### lookup spell
- GM Level: 3
- Syntax: Syntax: .lookup spell $namepart
- Description: Looks up a spell by $namepart, and returns all matches with their spell IDâ€™s.

### lookup taxinode
- GM Level: 3
- Syntax: Syntax: .lookup taxinode $substring
- Description: Search and output all taxinodes with provide $substring in name.

### lookup tele
- GM Level: 1
- Syntax: Syntax: .lookup tele $substring
- Description: Search and output all .tele command locations with provide $substring in name.

### lookup title
- GM Level: 2
- Syntax: Syntax: .lookup title $$namepart
- Description: Looks up a title by $namepart, and returns all matches with their title IDâ€™s and indexâ€™s.

### mailbox
- GM Level: 3
- Syntax: Syntax: .mailbox
- Description: Show your mailbox content.

### maxskill
- GM Level: 3
- Syntax: Syntax: .maxskill; Sets all skills of the targeted player to their maximum VALUESfor its current level.
- Description: nan

### modify aspeed
- GM Level: 1
- Syntax: Syntax: .modify aspeed #rate
- Description: Modify all speeds -run,swim,run back,swim back- of the selected player to â€œnormalbase speed for this move typeâ€*rate. If no player is selected, modify your speed.; #rate may range from 0.1 to 10.

### modify bwalk
- GM Level: 1
- Syntax: Syntax: .modify bwalk #rate
- Description: Modify the speed of the selected player while running backwards to â€œnormal walk back speedâ€*rate. If no player is selected, modify your speed.; #rate may range from 0.1 to 10.

### modify currency
- GM Level: 2
- Syntax: Syntax: .modify currency $id $amount
- Description: Add $amount points of currency $id to the selected player.

### modify drunk
- GM Level: 1
- Syntax: Syntax: .modify drunk #value; Set drunk level to #value (0..100). Value 0 remove drunk state, 100 is max drunked state.
- Description: nan

### modify energy
- GM Level: 1
- Syntax: Syntax: .modify energy #energy
- Description: Modify the energy of the selected player. If no player is selected, modify your energy.

### modify faction
- GM Level: 1
- Syntax: Syntax: .modify faction #factionid #flagid #npcflagid #dynamicflagid
- Description: Modify the faction and flags of the selected creature. Without arguments, display the faction and flags of the selected creature.

### modify fly
- GM Level: 1
- Syntax: Syntax: .modify fly #rate; .fly #rate
- Description: Modify the flying speed of the selected player to â€œnormal base fly speedâ€*rate. If no player is selected, modify your fly.; #rate may range from 0.1 to 10.

### modify gender
- GM Level: 2
- Syntax: Syntax: .modify gender male/female
- Description: Change gender of selected player.

### modify hp
- GM Level: 1
- Syntax: Syntax: .modify hp #newhp
- Description: Modify the hp of the selected player. If no player is selected, modify your hp.

### modify mana
- GM Level: 1
- Syntax: Syntax: .modify mana #newmana
- Description: Modify the mana of the selected player. If no player is selected, modify your mana.

### modify money
- GM Level: 1
- Syntax: Syntax: .modify money #money; .money #money
- Description: Add or remove money to the selected player. If no player is selected, modify your money.; #gold can be negative to remove money.

### modify morph
- GM Level: 2
- Syntax: Syntax: .modify morph #displayid
- Description: Change your current model id to #displayid.

### modify mount
- GM Level: 1
- Syntax: Syntax: .modify mount #id #speed; Display selected player as mounted at #id creature and set speed to #speed value.
- Description: nan

### modify phase
- GM Level: 3
- Syntax: Syntax: .modify phase #phasemask
- Description: Selected character phasemask changed to #phasemask with related world vision update. Change active until in game phase changed, or GM-mode enable/disable, or re-login. Character pts pasemask update to same value.

### modify rage
- GM Level: 1
- Syntax: Syntax: .modify rage #newrage
- Description: Modify the rage of the selected player. If no player is selected, modify your rage.

### modify rep
- GM Level: 2
- Syntax: Syntax: .modify rep #repId (#repvalue | $rankname [#delta]); Sets the selected players reputation with faction #repId to #repvalue or to $reprank.; If the reputation rank name is provided, the resulting reputation will be the lowest reputation for that rank plus the delta amount, if specified.; You can use â€˜.pinfo repâ€™ to list all known reputation ids, or use â€˜.lookup faction $nameâ€™ to locate a specific faction id.
- Description: nan

### modify runicpower
- GM Level: 1
- Syntax: Syntax: .modify runicpower #newrunicpower
- Description: Modify the runic power of the selected player. If no player is selected, modify your runic power.

### modify scale
- GM Level: 1
- Syntax: Syntax: .modify scale #scale
- Description: Change model scale for targeted player (util relogin) or creature (until respawn).

### modify speed
- GM Level: 1
- Syntax: Syntax: .modify speed #rate; .speed #rate
- Description: Modify the running speed of the selected player to â€œnormal base run speedâ€*rate. If no player is selected, modify your speed.; #rate may range from 0.1 to 10.

### modify standstate
- GM Level: 2
- Syntax: Syntax: .modify standstate #emoteid
- Description: Change the emote of your character while standing to #emoteid.

### modify swim
- GM Level: 1
- Syntax: Syntax: .modify swim #rate
- Description: Modify the swim speed of the selected player to â€œnormal swim speedâ€*rate. If no player is selected, modify your speed.; #rate may range from 0.1 to 10.

### modify tp
- GM Level: 1
- Syntax: Syntax: .modify tp #amount
- Description: Set free talent pointes for selected character or characterâ€™s pet. It will be reset to default expected at next levelup/login/quest reward.

### movegens
- GM Level: 3
- Syntax: Syntax: .movegens; Show movement generators stack for selected creature or player.
- Description: nan

### mute
- GM Level: 1
- Syntax: Syntax: .mute [$playerName] $timeInMinutes
- Description: Disible chat messaging for any character from account of character $playerName (or currently selected) at $timeInMinutes minutes. Player can be offline.

### namego
- GM Level: 1
- Syntax: Syntax: .namego [$charactername]
- Description: Teleport the given character to you. Character can be offline.

### neargrave
- GM Level: 3
- Syntax: Syntax: .neargrave [alliance|horde]
- Description: Find nearest graveyard linked to zone (or only nearest from accepts alliance or horde faction ghosts).

### notify
- GM Level: 1
- Syntax: Syntax: .notify $MessageToBroadcast
- Description: Send a global message to all players online in screen.

### npc add
- GM Level: 2
- Syntax: Syntax: .npc add #creatureid
- Description: Spawn a creature by the given template id of #creatureid.

### npc addcurrency
- GM Level: 2
- Syntax: Syntax: .npc addcurrency #currencyId #buycount #extendedcost
- Description: Add currency #currencyId to item list of selected vendor.

### npc additem
- GM Level: 2
- Syntax: Syntax: .npc additem #itemId <#maxcount><#incrtime><#extendedcost>r
- Description: Add item #itemid to item list of selected vendor. Also optionally set max count item in vendor item list and time to item count restoring and items ExtendedCost.

### npc addmove
- GM Level: 2
- Syntax: Syntax: .npc addmove #creature_guid [#waittime]
- Description: Add your current location as a waypoint for creature with guid #creature_guid. And optional add wait time.

### npc addweapon
- GM Level: 3
- Syntax: Not yet implemented.
- Description: nan

### npc aiinfo
- GM Level: 2
- Syntax: Syntax: .npc npc aiinfo
- Description: Show npc AI and script information.

### npc allowmove
- GM Level: 3
- Syntax: Syntax: .npc allowmove
- Description: Enable or disable movement creatures in world. Not implemented.

### npc changelevel
- GM Level: 2
- Syntax: Syntax: .npc changelevel #level
- Description: Change the level of the selected creature to #level.; #level may range from 1 to 63.

### npc delcurrency
- GM Level: 2
- Syntax: Syntax: .npc delcurrency #currencyId
- Description: Remove currency #currencyId from item list of selected vendor.

### npc delete
- GM Level: 2
- Syntax: Syntax: .npc delete [#guid]
- Description: Delete creature with guid #guid (or the selected if no guid is provided)

### npc delitem
- GM Level: 2
- Syntax: Syntax: .npc delitem #itemId
- Description: Remove item #itemid from item list of selected vendor.

### npc factionid
- GM Level: 2
- Syntax: Syntax: .npc factionid #factionid
- Description: Set the faction of the selected creature to #factionid.

### npc flag
- GM Level: 2
- Syntax: Syntax: .npc flag #npcflag
- Description: Set the NPC flags of creature template of the selected creature and selected creature to #npcflag. NPC flags will applied to all creatures of selected creature template after server restart or grid unload/load.

### npc follow
- GM Level: 2
- Syntax: Syntax: .npc follow
- Description: Selected creature start follow you until death/fight/etc.

### npc info
- GM Level: 3
- Syntax: Syntax: .npc info
- Description: Display a list of details for the selected creature.; The list includes:; â€" GUID, Faction, NPC flags, Entry ID, Model ID,; â€" Level,; â€" Health (current/maximum),; â€" Field flags, dynamic flags, faction template,; â€" Position information,; â€" and the creature type, e.g. if the creature is a vendor.

### npc move
- GM Level: 2
- Syntax: Syntax: .npc move [#creature_guid]
- Description: Move the targeted creature spawn point to your coordinates.

### npc name
- GM Level: 2
- Syntax: Syntax: .npc name $name
- Description: Change the name of the selected creature or character to $name.; Command disabled.

### npc playemote
- GM Level: 3
- Syntax: Syntax: .npc playemote #emoteid
- Description: Make the selected creature emote with an emote of id #emoteid.

### npc say
- GM Level: 1
- Syntax: Syntax: .npc say #text; Make the selected npc says #text.
- Description: nan

### npc setdeathstate
- GM Level: 2
- Syntax: Syntax: .npc setdeathstate on/off
- Description: Set default death state (dead/alive) for npc at spawn.

### npc setmodel
- GM Level: 2
- Syntax: Syntax: .npc setmodel #displayid
- Description: Change the model id of the selected creature to #displayid.

### npc setmovetype
- GM Level: 2
- Syntax: Syntax: .npc setmovetype [#creature_guid] stay/random/way [NODEL]
- Description: Set for creature pointed by #creature_guid (or selected if #creature_guid not provided) movement type and move it to respawn position (if creature alive). Any existing waypoints for creature will be removed from the database if you do not use NODEL. If the creature is dead then movement type will applied at creature respawn.; Make sure you use NODEL, if you want to keep the waypoints.

### npc setphase
- GM Level: 2
- Syntax: Syntax: .npc setphase #phasemask
- Description: Selected unit or pet phasemask changed to #phasemask with related world vision update for players. In creature case state saved to DB and persistent. In pet case change active until in game phase changed for owner, owner re-login, or GM-mode enable/disable..

### npc spawndist
- GM Level: 2
- Syntax: Syntax: .npc spawndist #dist
- Description: Adjust spawndistance of selected creature to dist.

### npc spawntime
- GM Level: 2
- Syntax: Syntax: .npc spawntime #time
- Description: Adjust spawntime of selected creature to time.

### npc subname
- GM Level: 2
- Syntax: Syntax: .npc subname $Name
- Description: Change the subname of the selected creature or player to $Name.; Command disabled.

### npc tame
- GM Level: 2
- Syntax: Syntax: .npc tame
- Description: Tame selected creature (tameable non pet creature). You donâ€™t must have pet.

### npc textemote
- GM Level: 1
- Syntax: Syntax: .npc textemote #emoteid
- Description: Make the selected creature to do textemote with an emote of id #emoteid.

### npc unfollow
- GM Level: 2
- Syntax: Syntax: .npc unfollow
- Description: Selected creature (non pet) stop follow you.

### npc whisper
- GM Level: 1
- Syntax: Syntax: .npc whisper #playerguid #text; Make the selected npc whisper #text to #playerguid.
- Description: nan

### npc yell
- GM Level: 1
- Syntax: Syntax: .npc yell #text; Make the selected npc yells #text.
- Description: nan

### pdump load
- GM Level: 3
- Syntax: Syntax: .pdump load $filename $account [$newname] [$newguid]; Load character dump from dump file into character list of $account with saved or $newname, with saved (or first free) or $newguid guid.
- Description: nan

### pdump write
- GM Level: 3
- Syntax: Syntax: .pdump write $filename $playerNameOrGUID; Write character dump with name/guid $playerNameOrGUID to file $filename.
- Description: nan

### pinfo
- GM Level: 2
- Syntax: Syntax: .pinfo [$player_name]
- Description: Output account information for selected player or player find by $player_name.

### pool
- GM Level: 2
- Syntax: Syntax: .pool #pool_id
- Description: Pool information and full list creatures/gameobjects included in pool.

### pool list
- GM Level: 2
- Syntax: Syntax: .pool list
- Description: List of pools with spawn in current map (only work in instances. Non-instanceable maps share pool system state os useless attempt get all pols at all continents.

### pool spawns
- GM Level: 2
- Syntax: Syntax: .pool spawns #pool_id
- Description: List current creatures/objects listed in pools (or in specific #pool_id) and spawned (added to grid data, not meaning show in world.

### quest add
- GM Level: 3
- Syntax: Syntax: .quest add #quest_id
- Description: Add to character quest log quest #quest_id. Quest started from item canâ€™t be added by this command but correct .additem call provided in command output.

### quest complete
- GM Level: 3
- Syntax: Syntax: .quest complete #questid; Mark all quest objectives as completed for target character active quest. After this target character can go and get quest reward.
- Description: nan

### quest remove
- GM Level: 3
- Syntax: Syntax: .quest remove #quest_id
- Description: Set quest #quest_id state to not completed and not active (and remove from active quest list) for selected player.

### quit
- GM Level: 4
- Syntax: Syntax: quit
- Description: Close RA connection. Command must be typed fully (quit).

### recall
- GM Level: 1
- Syntax: Syntax: .recall [$playername]
- Description: Teleport $playername or selected player to the place where he has been before last use of a teleportation command. If no $playername is entered and no player is selected, it will teleport you.

### reload all
- GM Level: 3
- Syntax: Syntax: .reload all
- Description: Reload all tables with reload support added and that can be _safe_ reloaded.

### reload all_achievement
- GM Level: 3
- Syntax: Syntax: .reload all_achievement
- Description: Reload all `achievement_*` tables if reload support added for this table and this table can be _safe_ reloaded.

### reload all_area
- GM Level: 3
- Syntax: Syntax: .reload all_area
- Description: Reload all `areatrigger_*` tables if reload support added for this table and this table can be _safe_ reloaded.

### reload all_eventai
- GM Level: 3
- Syntax: Syntax: .reload all_eventai
- Description: Reload `creature_ai_*` tables if reload support added for these tables and these tables can be _safe_ reloaded.

### reload all_item
- GM Level: 3
- Syntax: Syntax: .reload all_item
- Description: Reload `item_required_target`, `page_texts` and `item_enchantment_template` tables.

### reload all_locales
- GM Level: 3
- Syntax: Syntax: .reload all_locales
- Description: Reload all `locales_*` tables with reload support added and that can be _safe_ reloaded.

### reload all_loot
- GM Level: 3
- Syntax: Syntax: .reload all_loot
- Description: Reload all `*_loot_template` tables. This can be slow operation with lags for server run.

### reload all_npc
- GM Level: 3
- Syntax: Syntax: .reload all_npc
- Description: Reload `points_of_interest` and `npc_*` tables if reload support added for these tables and these tables can be _safe_ reloaded.

### reload all_quest
- GM Level: 3
- Syntax: Syntax: .reload all_quest
- Description: Reload all quest related tables if reload support added for this table and this table can be _safe_ reloaded.

### reload all_scripts
- GM Level: 3
- Syntax: Syntax: .reload all_scripts
- Description: Reload `*_scripts` tables.

### reload all_spell
- GM Level: 3
- Syntax: Syntax: .reload all_spell
- Description: Reload all `spell_*` tables with reload support added and that can be _safe_ reloaded.

### reload config
- GM Level: 3
- Syntax: Syntax: .reload config
- Description: Reload config settings (by default stored in mangosd.conf). Not all settings can be change at reload: some new setting values will be ignored until restart, some values will applied with delay or only to new objects/maps, some values will explicitly rejected to change at reload.

### repairitems
- GM Level: 2
- Syntax: Syntax: .repairitems
- Description: Repair all selected playerâ€™s items.

### reset achievements
- GM Level: 3
- Syntax: Syntax: .reset achievements [$playername]
- Description: Reset achievements data for selected or named (online or offline) character. Achievements for persistance progress data like completed quests/etc re-filled at reset. Achievements for events like kills/casts/etc will lost.

### reset all
- GM Level: 3
- Syntax: Syntax: .reset all spells
- Description: Syntax: .reset all talents; Request reset spells or talents (including talents for all characterâ€™s pets if any) at next login each existed character.

### reset honor
- GM Level: 3
- Syntax: Syntax: .reset honor [Playername]; Reset all honor data for targeted character.
- Description: nan

### reset level
- GM Level: 3
- Syntax: Syntax: .reset level [Playername]; Reset level to 1 including reset stats and talents. Equipped items with greater level requirement can be lost.
- Description: nan

### reset specs
- GM Level: 3
- Syntax: Syntax: .reset specs [Playername]; Removes all talents (for all specs) of the targeted player or named player. Playername can be name of offline character. With player talents also will be reset talents for all characterâ€™s pets if any.
- Description: nan

### reset spells
- GM Level: 3
- Syntax: Syntax: .reset spells [Playername]; Removes all non-original spells from spellbook.; . Playername can be name of offline character.
- Description: nan

### reset stats
- GM Level: 3
- Syntax: Syntax: .reset stats [Playername]; Resets(recalculate) all stats of the targeted player to their original VALUESat current level.
- Description: nan

### reset talents
- GM Level: 3
- Syntax: Syntax: .reset talents [Playername]; Removes all talents (current spec) of the targeted player or pet or named player. With player talents also will be reset talents for all characterâ€™s pets if any.
- Description: nan

### respawn
- GM Level: 3
- Syntax: Syntax: .respawn
- Description: Respawn selected creature or respawn all nearest creatures (if none selected) and GO without waiting respawn time expiration.

### revive
- GM Level: 3
- Syntax: Syntax: .revive
- Description: Revive the selected player. If no player is selected, it will revive you.

### save
- GM Level: 0
- Syntax: Syntax: .save
- Description: Saves your character.

### saveall
- GM Level: 1
- Syntax: Syntax: .saveall
- Description: Save all characters in game.

### send items
- GM Level: 3
- Syntax: Syntax: .send items #playername â€œ#subjectâ€ â€œ#textâ€ itemid1[:count1] itemid2[:count2] â€¦ itemidN[:countN]
- Description: Send a mail to a player. Subject and mail text must be in â€œâ€. If for itemid not provided related count values then expected 1, if count > max items in stack then items will be send in required amount stacks. All stacks amount in mail limited to 12.

### send mail
- GM Level: 1
- Syntax: Syntax: .send mail #playername â€œ#subjectâ€ â€œ#textâ€
- Description: Send a mail to a player. Subject and mail text must be in â€œâ€.

### send mass items
- GM Level: 3
- Syntax: Syntax: .send mass items #racemask|$racename|alliance|horde|all â€œ#subjectâ€ â€œ#textâ€ itemid1[:count1] itemid2[:count2] â€¦ itemidN[:countN]
- Description: Send a mail to players. Subject and mail text must be in â€œâ€. If for itemid not provided related count values then expected 1, if count > max items in stack then items will be send in required amount stacks. All stacks amount in mail limited to 12.

### send mass mail
- GM Level: 3
- Syntax: Syntax: .send mass mail #racemask|$racename|alliance|horde|all â€œ#subjectâ€ â€œ#textâ€
- Description: Send a mail to players. Subject and mail text must be in â€œâ€.

### send mass money
- GM Level: 3
- Syntax: Syntax: .send mass money #racemask|$racename|alliance|horde|all â€œ#subjectâ€ â€œ#textâ€ #money
- Description: Send mail with money to players. Subject and mail text must be in â€œâ€.

### send message
- GM Level: 3
- Syntax: Syntax: .send message $playername $message
- Description: Send screen message to player from ADMINISTRATOR.

### send money
- GM Level: 3
- Syntax: Syntax: .send money #playername â€œ#subjectâ€ â€œ#textâ€ #money
- Description: Send mail with money to a player. Subject and mail text must be in â€œâ€.

### server corpses
- GM Level: 2
- Syntax: Syntax: .server corpses
- Description: Triggering corpses expire check in world.

### server exit
- GM Level: 4
- Syntax: Syntax: .server exit
- Description: Terminate mangosd NOW. Exit code 0.

### server idlerestart
- GM Level: 3
- Syntax: Syntax: .server idlerestart #delay
- Description: Restart the server after #delay seconds if no active connections are present (no players). Use #exist_code or 2 as program exist code.

### server idlerestart cancel
- GM Level: 3
- Syntax: Syntax: .server idlerestart cancel
- Description: Cancel the restart/shutdown timer if any.

### server idleshutdown
- GM Level: 3
- Syntax: Syntax: .server idleshutdown #delay [#exist_code]
- Description: Shut the server down after #delay seconds if no active connections are present (no players). Use #exist_code or 0 as program exist code.

### server idleshutdown cancel
- GM Level: 3
- Syntax: Syntax: .server idleshutdown cancel
- Description: Cancel the restart/shutdown timer if any.

### server info
- GM Level: 0
- Syntax: Syntax: .server info
- Description: Display server version and the number of connected players.

### server log filter
- GM Level: 4
- Syntax: Syntax: .server log filter [($filtername|all) (on|off)]
- Description: Show or set server log filters. If used â€œallâ€ then all filters will be set to on/off state.

### server log level
- GM Level: 4
- Syntax: Syntax: .server log level [#level]
- Description: Show or set server log level (0 â€" errors only, 1 â€" basic, 2 â€" detail, 3 â€" debug).

### server motd
- GM Level: 0
- Syntax: Syntax: .server motd
- Description: Show server Message of the day.

### server plimit
- GM Level: 3
- Syntax: Syntax: .server plimit [#num|-1|-2|-3|reset|player|moderator|gamemaster|administrator]
- Description: Without arg show current player amount and security level limitations for login to server, with arg set player linit ($num > 0) or securiti limitation ($num < 0 or security leme name. With `reset` sets player limit to the one in the config file

### server restart
- GM Level: 3
- Syntax: Syntax: .server restart #delay
- Description: Restart the server after #delay seconds. Use #exist_code or 2 as program exist code.

### server restart cancel
- GM Level: 3
- Syntax: Syntax: .server restart cancel
- Description: Cancel the restart/shutdown timer if any.

### server set motd
- GM Level: 3
- Syntax: Syntax: .server set motd $MOTD
- Description: Set server Message of the day.

### server shutdown
- GM Level: 3
- Syntax: Syntax: .server shutdown #delay [#exit_code]
- Description: Shut the server down after #delay seconds. Use #exit_code or 0 as program exit code.

### server shutdown cancel
- GM Level: 3
- Syntax: Syntax: .server shutdown cancel
- Description: Cancel the restart/shutdown timer if any.

### setskill
- GM Level: 3
- Syntax: Syntax: .setskill #skill #level [#max]
- Description: Set a skill of id #skill with a current skill value of #level and a maximum value of #max (or equal current maximum if not provide) for the selected character. If no character is selected, you learn the skill.

### showarea
- GM Level: 3
- Syntax: Syntax: .showarea #areaid
- Description: Reveal the area of #areaid to the selected character. If no character is selected, reveal this area to you.

### stable
- GM Level: 3
- Syntax: Syntax: .stable
- Description: Show your pet stable.

### start
- GM Level: 0
- Syntax: Syntax: .start
- Description: Teleport you to the starting area of your character.

### taxicheat
- GM Level: 1
- Syntax: Syntax: .taxicheat on/off
- Description: Temporary grant access or remove to all taxi routes for the selected character. If no character is selected, hide or reveal all routes to you.; Visited taxi nodes sill accessible after removing access.

### tele
- GM Level: 1
- Syntax: Syntax: .tele #location
- Description: Teleport player to a given location.

### tele add
- GM Level: 3
- Syntax: Syntax: .tele add $name
- Description: Add current your position to .tele command target locations list with name $name.

### tele del
- GM Level: 3
- Syntax: Syntax: .tele del $name
- Description: Remove location with name $name for .tele command locations list.

### tele group
- GM Level: 1
- Syntax: Syntax: .tele group#location
- Description: Teleport a selected player and his group members to a given location.

### tele name
- GM Level: 1
- Syntax: Syntax: .tele name [#playername] #location
- Description: Teleport the given character to a given location. Character can be offline.

### ticket
- GM Level: 2
- Syntax: Syntax: .ticket on; .ticket off; .ticket #num; .ticket $character_name; .ticket respond #num $response; .ticket respond $character_name $response
- Description: on/off for GMs to show or not a new ticket directly, $character_name to show ticket of this character, #num to show ticket #num.

### titles add
- GM Level: 2
- Syntax: Syntax: .titles add #title; Add title #title (id or shift-link) to known titles list for selected player.
- Description: nan

### titles current
- GM Level: 2
- Syntax: Syntax: .titles current #title; Set title #title (id or shift-link) as current selected titl for selected player. If title not in known title list for player then it will be added to list.
- Description: nan

### titles remove
- GM Level: 2
- Syntax: Syntax: .titles remove #title; Remove title #title (id or shift-link) from known titles list for selected player.
- Description: nan

### titles setmask
- GM Level: 2
- Syntax: Syntax: .titles setmask #mask
- Description: Allows user to use all titles from #mask.; #mask=0 disables the title-choose-field

### trigger
- GM Level: 2
- Syntax: Syntax: .trigger [#trigger_id|$trigger_shift-link|$trigger_target_shift-link]
- Description: Show detail infor about areatrigger with id #trigger_id or trigger id associated with shift-link. If areatrigger id or shift-link not provided then selected nearest areatrigger at current map.

### trigger active
- GM Level: 2
- Syntax: Syntax: .trigger active
- Description: Show list of areatriggers with activation zone including current character position.

### trigger near
- GM Level: 2
- Syntax: Syntax: .trigger near [#distance]
- Description: Output areatriggers at distance #distance from player. If #distance not provided use 10 as default value.

### unaura
- GM Level: 3
- Syntax: Syntax: .unaura #spellid
- Description: Remove aura due to spell #spellid from the selected Unit.

### unban account
- GM Level: 3
- Syntax: Syntax: .unban account $Name; Unban accounts for account name pattern.
- Description: nan

### unban character
- GM Level: 3
- Syntax: Syntax: .unban character $Name; Unban accounts for character name pattern.
- Description: nan

### unban ip
- GM Level: 3
- Syntax: Syntax : .unban ip $Ip; Unban accounts for IP pattern.
- Description: nan

### unlearn
- GM Level: 3
- Syntax: Syntax: .unlearn #spell [all]
- Description: Unlearn for selected player a spell #spell. If â€˜allâ€™ provided then all ranks unlearned.

### unmute
- GM Level: 1
- Syntax: Syntax: .unmute $playerName
- Description: Restore chat messaging for any character from account of character $playerName.

### waterwalk
- GM Level: 2
- Syntax: Syntax: .waterwalk on/off
- Description: Set on/off waterwalk state for selected player.

### wchange
- GM Level: 3
- Syntax: Syntax: .wchange #weathertype #status
- Description: Set current weather to #weathertype with an intensity of #status.; #weathertype can be 1 for rain, 2 for snow, and 3 for sand. #status can be 0 for disabled, and 1 for enabled.

### whispers
- GM Level: 1
- Syntax: Syntax: .whispers on|off; Enable/disable accepting whispers by GM from players. By default use mangosd.conf setting.
- Description: nan

### wp add
- GM Level: 2
- Syntax: Syntax: .wp add [#creature_guid or Select a Creature]
- Description: nan

### wp export
- GM Level: 3
- Syntax: Syntax: .wp export [#creature_guid or Select a Creature] $filename
- Description: nan

### wp import
- GM Level: 3
- Syntax: Syntax: .wp import $filename
- Description: nan

### wp modify
- GM Level: 2
- Syntax: Syntax: .wp modify [#creature_guid or Select a Creature]; add â€" Add a waypoint after the selected visual; waittime $time; emote ID; spell ID; text1| text2| text3| text4| text5 ; model1 ID; model2 ID; move(moves wp to player pos); del (deletes the wp)
- Description: Only one parameter per time!

### wp show
- GM Level: 2
- Syntax: Syntax: .wp show [#creature_guid or Select a Creature]; on; first; last; off; info
- Description: For using info you have to do first show on and than select a Visual-Waypoint and do the show info!
