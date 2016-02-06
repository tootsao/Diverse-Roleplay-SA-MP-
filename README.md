# Diverse-Roleplay-SA-MP-
A feature-filled, neat, but poorky-written SA:MP script. 
(I'd start by making all arrays start at index 0, and removing the use of PVars on variables that are set/retrieved often.)

#[Changelog]#
- [x] Added ingame UCP.
- [x] Totally redone, optimized, menu-based inventory for players, houses.
- [x] Added /v lights as an alternative to the Fire key.
- [x] Wrote 'PData' library for automated saving and loading of strings, floats and integers. Requires no MySQL knowledge. Optimized edition. *Unused since I'm now scripting alone.*
- [x] Added Tagging system for factions and admins, /tag. Supports: Fonts, Font Size, Bold, Color, Pos/Angle.
- [x] Added Silencers and /silencer for Colt M1911s.
- [x] Major optimizations.
- [x] Business and house saving re-written, optimized to be over 3000x faster.
- [x] Converted /v spawn to a dialog menu instead of /v spawn (1-3).
- [x] Many bug fixes/typo fixes.
- [x] /v radio works for all vehicles now instead of just personal cars.
- [x] Rewrote ban system to check for IP, Username AND SA:MP's gpci, making it extremely hard to ban-evade.
- [x] Fixed toy system.
- [x] Commands /call, /sms, /contacts and /(h)angup have been added for easier interactions with phone calls.
- [x] Replaced reloading text with a progress bar.
- [x] Added RemoveInvItem(playerid,itemid,amt,slot).
- [x] Added the ability to change the material of house and biz objects.
- [x] Added progress bar to gas stations.
- [x] Added per-layer material resetting to object editing in houses and bizzes.
- [x] Added Boombox as an inventory-based item, any player over 24 TLS can get a boombox.
- [x] Added /lights to houses.
- [x] Added Furniture Rights to businesses and house.
- [x] Added /door.
- [x] Added a textdraw to the loading screen.
- [x] Added multiple chatlines to the chat-types that were missing it.
- [x] Added /togb, /ajail(shortcut to adminjail), etc.
- [x] Added the ability to put ciggy in ur hand, mouth, etc.
- [x] Added /biz setexit and /biz setcp (for setting the buy-stuff-checkpoint)
- [x] Added /biz bareswitch, to switch to an empty interior and build from scratch.
- [x] Added /carsign for cops
- [x] Added corpse system
- [x] Added shots fired warning for cops. Silenced guns and houses/bizzes excluded.
- [x] Added tons of utility functions.
- [x] Added /v corpse to take corpses out of your vehicles trunk.
- [x] Added /lockdoor for /door.
- [x] Changed the reset material and material-layer system to stream objects on reset.
- [x] Made it so there are 3 IC days per 1 day IRL.
- [x] Added /unsethduty to force helpers off-duty.
- [x] Now the selected material-layer you're editing is high-lighted red.
- [x] Made it so the "H" key runs /door.
- [x] Added /house lookout to see who's outside your house door, moves your camera.
- [x] /hack now tells the admin if the player is health-hacking so the admin doesn't have to manually check if their HP changed.
- [x] Added /house bank/deposit/withdraw and /biz bank/deposit/withdraw for money storage.
- [x] You must be near a safe to access bizz/house safe/bank.
- [x] Added /house plantsafe for convenience.
- [x] Made it so regular users can use Pay N' Spray, however they have limited uses that regenerate.
- [x] Made house/biz safes require a combo to open them. When unlocked anyone can access the funds/items.
- [x] Made /house plantsafe work with Furniture Rights.
- [x] Converted /house and /biz setcombo to /safe setcombo, works with both businesses and houses.
- [x] Added /safe [lock/unlock], when a player who doesn't own the house enters an incorrect combo it notifies the house owner.
- [x] Added drive-thrus that close at night.
- [x] Modified /house [usage] and /biz [usage] to be-able to fit all the commands.
- [x] Moved all RECENT and NEW Textdraws to a separate location. (better organization)
- [x] Added the ability to pawn cellphones and watches at the hardware store, just like in the original script. #tbt 2009.
- [x] Added debit/cash payment method option to stores.
- [x] Added cheat protection from NPC control hacks.
- [x] Added speed traps
- [x] Added /lights for house lights.
- [x] Added DMV and SAN News to /locations
- [x] Added car bombs for factions to order.
- [x] Added wire transferring. (w/ anti money farm)
- [x] Added GPDID to prevent client-dialog manipulation.
- [x] New, better, optimized MDC for police.
- [x] Added /propose, /divorce.
- [x] You can't despawn a vehicle when a corpse is inside.
- [x] Added /searchtrunk, everyone can search open trunks - but not take from them. You are notified if there is a corpse in the trunk.
- [x] Made it so anyone can remove a corpse from a vehicle while the trunk's opened.
- [x] Corpses now only cleanup if they aren't being actively used in roleplay.
- [x] When a corpse has been left in a car for too long it occasionally prints in purple to new players the follow: ***A foul odour can be smelt emitting from the 'VehName'
- [x] /factionbonus now saves and loads.
- [x] Added boat dealership.
- [x] Added boat dealership to /locations.
- [x] Redid the wheel-selection menu for cars, now uses textdraws.
- [x] Added business inventories.
- [x] Completely refactored and optimized how house-inventories are handled by the gamemode.
- [x] Cops can now drop/store non-weapon/non-ammo items.
- [x] Added the option to Pawn MP3 players at the hardware shop. (Cellphones and Watches can of course still be pawned.)
- [x] Added house rentals "/house [rentfee/rentlist/rentto/unrent]"
- [x] Right Mouse Button now stops your current animation as a shortcut to /stopanim.
- [x] /house interior is now totally bug free.
- [x] Completely re-wrote the registration system, it now caches applications to for any-time approval regardless of whether or not the player is online.
- [x] Business names and slogans, faction names too - are now properly 'escaped' to allow for apostrophes again without causing the database grief.
- [x] Guns no longer linger on your back when you store them in a vehicle.
- [x] Fixed some issues with registration and MySQL malforming data when an online-players app is accepted.
- [x] Fixed incorrect pricing on /createhouse
- [x] Changed 'Position in queue' in pending-app info to 'Applications pending'.
- [x] Handcuffs are now automatically removed after being arrested.
- [x] Fixed a bug with house and business furnishing rights.
- [x] /bring now works as an alternative to /gethere.
- [x] Drug effects last 1/3rd as long
- [x] Addded /abiz for developers.
- [x] Added a warning to /biz bareswitch.
- [x] Fixed a few typos.
- [x] Updated/improved gas-station dialog.
- [x] Fixed /take inv for cops - it now also only takes guns and drugs.
- [x] Fixed 'you're currently on route' message while braking in a vehicle while on job duty.
- [x] Fixed /newsspawn
- [x] Added bulletproof vest to ammunation.
- [x] Added backpacks to hide holsters.
- [x] Added email address support, if you set your email, you can recover your password via the Web-UCP.
- [x] Added /despawnnewscar and /despawnrlscar.
- [x] Added in-game map editor and "Mapper" rank.
- [x] Cops now lose their weapons when they quit their faction.
- [x] Fixed all deprecated lengthless strings in sscanf references.
- [x] Heavily improved in-game map editor. (Still some improvements to go.)
- [x] Added a dialog to /house sell telling you your houses value.
- [x] Made biz-exit markers an 'information' pick-up icon. (Works nicer with biz-CP system.) (Part of /biz setcp fix)
- [x] Added "Radio Los Santos" radio station, DJ'd by RLS leaders.
- [x] Fixed URL-based music not refreshing when entering non-personal vehicles.
- [x] Improved RLS' in-game DJ system. (/stream)
- [x] Now all passengers in a car can use /v radio. (More realistic.)
- [x] Added /findmapping, /map mine - to find all of a certain mapper's mapping. (and edit it)
- [x] Fixed 'Previous Page' in in-game UCP's Ban List.
- [x] Fixed '/event 0' changing the server name to a name containing the old site.
- [x] Fixed lingering /carsign's.
- [x] Added object-selector to house, business and map object editor. (Before it'd automatically pick the object highest in the array because the ModelSelection include doesn't have the callbacks to properly handle this.) I feel we've done this as efficiently as possible, with low resource usage.
- [x] Many miscellaneous improvements, fixes, optimizations.
- [x] Totally re-wrote house and business furniture saving/loading.
- [x] Fixed a MAJOR exploit with name-changes via the game-UCP. (Thankfully no-one found it out.)
- [x] Added name-change ticket support to ingame UCP's name-change system.
- [x] Basketball added to Ganton courts. (See /help for usage.)
- [x] Fixed shipments being empty or not spawning if the orderer crashes or logs off.
- [x] Improved basketball, you can no longer exit the court with the ball, or shoot it out of the court. If you leave the court you auto-quit the basketball game.
- [x] Added a 5 second delay in between dunks to prevent dunk-spam.
- [x] Made weather set to a default one while in interiors. (houses, interiors, businesses.)
- [x] Added a 1 second delay after grabbing the basketball to prevent accidental dunks.(Not noticeable when you're really trying to dunk.)
- [x] Increased max house and business inventory slots from 8 to 20.
- [x] Made inventories have the appropriate cells allocated to prevent cut-off item names.
- [x] Fixed a /possible/ issue where laggy players had their car's fuel reset when they despawned it.
- [x] Fixed a false-positive on weapon hack detection.
- [x] More improvements to basketball. (Specificially missed shots and accidently post-pickup shot prevention.)
- [x] Fixed /help--> "Basketball Help".
- [x] Fixed a bug in the in-game map editor where going "Back" at the material-selection menu deselects your object.
- [x] Added object rotation and pos editting via a input-box.
- [x] Fixed a bug with saving of house and biz furniture.
- [x] Added "Delete a Faction" feature to ACP. (Also removes both online and offline playerss from the now non-existant faction.)
- [x] Fixed /(o)oc for non-staff members.
- [x] Fixed faction-shipment items sometimes being placed into the wrong crate-ID.
- [x] Fixed PData resetting when you change your name. (I forgot to re-save it all after your 'new' account is created, it's not handled with normal player-data saving.)
- [x] Fixed a bug where removed mapping wasn't being deleted from memory in some cases.
- [x] Fixed an exploit where rifles were free in faction shipments.
- [x] Added bullet proof vests and silencers to faction shipments.
- [x] Fixed many small bugs with faction shipments.
- [x] Added vehicle iterator. (Faster for looping through active vehicles.)
- [x] Improved NPC system.
- [x] Fixed bus-driver NPCs and bus routes.
- [x] Made DespawnVehicle(id) to use instead of DespawnVehicle(id). (Deletes from iterator.)
- [x] Fixed /v sellto
- [x] Added /checksb as a shortcut to /checkseatbelt.
- [x] Re-wrote how person-vehicles are handled by the script. (Also increased max ownable-vehicles.)
- [x] Fixed a bug where buying a vehicle wouldn't give you the key to the new vehicle. (Caused by vehicle-system rewrite.)
- [x] Added "Input Position" for both house and business furniture editing.
- [x] Added '/house furn' and '/biz furn' to view all objects planted in the current house. (Assuming you have furniture rights there.)
- [x] Added /wat (wear all toys) and /rat (remove all toys) to instantly attach/detach all your accessories.
- [x] Changed the pickup-object for business exits.
- [x] Fixed beanbags causing bullet-wounds.
- [x] Added "Headwound" when killed with a headshot.
- [x] Equipped gun shows in your hand when you die to prevent MG.
- [x] Time spent in the hospital is no longer based on your wounds, now 30 seconds regardless.
- [x] Tweaked headshot system.
- [x] Lowered shipment time.
- [x] Improved toy-precision.
- [x] Coded dynamic SQL-based gate system. (/gatehelp)
- [x] Re- [x] Removed faction warehouse, lowered shipment times.
- [x] Fixed a bug where storing tazers would store a gun with "NUlL" ammo.
- [x] Added /give carkey, /take carkey and /drop carkey.
	*/give carkey brings up a dialog with all your cars, you can give the keys to whichever car you want.
	*/take carkey brings up a dialog with all your cars, you can take the keys to whichever car you want.
	*/drop carkey brings up a dialog with all your currently borrowed car-keys, you can click a key-slot for information on the vehicle, and choose to discard of the key.
- [x] Increased job pay by 2-3x
- [x] Totally recoded vehicle systems, they are now 100% dynamic.
	*You can own up to 3 vehicles, 4 if you're a donor, 5 if you're a monthly subscriber.
	*Cars now have stats like Mileage, Car Alarms, and different levels of locks.
- [x] There is now a 30 second delay before the cops are notified of shots fired. (Silenced M1911's don't notify cops at all, if bullets are shot outside of LS cops aren't notified - same goes for interiors.)
- [x] Removed 'Civilian is injured' notifications to cops, because it causes mass MG and ruins RP situations.
- [x] New prison interior w/ yard.
- [x] Changed the style of [TIP]'s in the gamemode.
- [x] You can now set opening and closing sounds for gates.
- [x] Rewrote interior system, now supports live-updates for every field. (Immensely optimized object streaming on entry = less lag-related crashing, prevents falling through the map when lagging on entry.)
- [x] Refactored gate system. (Optimised greatly + bugs fixed.) (The MAX_GATES variable no longer has an effect on performance, only active-gates do.)
- [x] Shells that aren't still "Hot" can be picked up by clickng "Y".
- [x] Added 100% dynamic payphone system. (/payphonehelp - shows both mapper and normal user [only 1 command] payphone commands.)
- [x] Fixed /houseentrance, /houseexit, /bizentrance, /bizexit not saving.
- [x] Improved exiting houses that are in a VW  other than one.
- [x] Improved entering interiors that are in a VW other than one.
- [x] Added "Taxi Meter" and automated Taxi Payment.
- [x] Added SawnOff, 9mm and Uzi skill. (Admin setable/donateable.)
- [x] Removed incoming-shipment notification, now factons must truely investigate to catch arms/drug dealers.
- [x] Added /v paint for changing your car's paintjob.
- [x] Increased job pay once again.
- [x] Added /setfare for taxi drivers.
- [x] Added house/business iterator.

- [x] Added all 0.3.7 faction and non-faction skins. (Except holsterless cops, they're useless.)
- [x] Minor vehicle-system changes to make it feel smoother in-game.
- [x] Undercover ATF vehicles no longer have any distinguishing marks. 
- [x] Dead bodies now actually appear (uses 0.3.7 actor system.)
- [x] Added action-tags above players heads to show what they're doing. (e.g: "(breaking into car)")
- [x] Converted MOST NPCs to actors.
- [x] Added a "materials" system and item crafting system.
- [x] Added 4 slot gloveboxes to all non-helmet personal vehicles.
- [x] LEOs can now rappel down from helicopters.
- [x] Toys now stick around when you namechange. (This is nicer and improves MySQL efficiency, this way old toys get deleted.)
- [x] Your vehicles inventory can no longer be accessed through "/(inv)entory" only through the "N" key, part of multi-vehicle spawn support.
- [x] Now /(wi)ndows really opens/closes the driver and passenger window.
- [x] Anyone can store corpses in any vehicles trunk so long as it's opened, instead of just being able to store it in your OWN trunk.
- [x] Players can now have MAX_SPAWNED_CARS spawned at once. (Default: 2)
- [x] Added /house (put/take)mats.
- [x] Added /give materials [id] [amount].
- [x] Added /weapon for what will later be holster-manipulation functions.
- [x] PlayerToCar() and NearestAccessCar() now find the closest car to you that matches the entered criteria instead of the first in the Vehicle pool.
- [x] Fixed wearable-items Z-axis being wrongly offset.
- [x] Slightly tweaked drug system.
- [x] Added "Pack Of Cigarettes" item, contains 25 cigarettes.
- [x] Fixed "Death Reason" always being unknown when examining corpses.

- [x] Renamed /searchtrunk to /search trunk to make organization nicer for future /search commands. (such as /search trailer.)
- [x] Added new trucking mission to obtain materials.
- [x] Added /v delete for donated vehicles.
- [x] Added "Theft Cars", stealable Linerunners for the trucking mission. (3 hidden around LS.)
- [x] Added a tag for crafting to prevent crafting during RP.
- [x] Improved how MySQL handles payphones and gates.
- [x] Optimised and fixed rim selection.
- [x] Nerfed material runs.

- [x] Fixed "Vehicle has already been hotwired" delay being on Theft Cars (the delay was only supposed to be for personal vehicles.)
- [x] Fixed many inventory-related bugs (with trunks and whatnot).
- [x] Optimised and improved buses.
- [x] Optimised vehicle modding/inventories/cheat protection/dialog menus.
- [x] Added /resetspawn to reset a players spawn area to 0.0,0.0,0.0.
- [x] Added /housefurnitureinfo, /houseeditfurniture for admins.
- [x] Added /fireremoveall for admins.
- [x] Added /bizclear, /houseclear and /vehicleclear to clear biz/house inventories for admins.
- [x] Added /vehiclesetspawn, /vehicledespawn for admins.
- [x] Added /sendto [playerid] [targetid] for admins
- [x] Added house garages: /garage. (Admin: /housegarage /houseremovegarage /housegarageinterior) [Garages can be customized furniture-wise like houses.]
- [x] Added /siren and /elm for LSPD/Government vehicles.
- [x] Recoded inventories (WAY faster, less R.A.M usage, easier to create quantity-based items/unique items.) [Not really any visual difference].
- [x] Major script optimizations (mainly switching away from PVars and optimising loops/adding iterators.)
- [x] Misc. improvements/changes.
- [x] Added divide/combine options to drugs in your inventory.

- [x] Improved /spec [playerid].
- [x] Added /accent.
- [x] Added CheckInvItemID(playerid, itemid) [Counts the total amount of a specific item in your inv, all stacks taken into consideration.]
- [x] Admins can now use 'VEHICLE_HANDBRAKE' key to cycle through players while in spectate.
- [x] Added fishing system.
- [x] Changed the automated /me's for storing/taking things to /ame's to prevent MG.
- [x] You no longer lose your toolkit after use.

- [x] Removed some unnecessary/deprecated MySQL fields.

- [x] Changed dynamic objects throughout in-game gate creation to player objects til the gate is complete.
- [x] Removed vehicles from intro textdraw.
- [x] Misc. bug fixes/improvements.


[December 2015 - 2016]
- [x] Optimized player account loading.
- [x] Added weapon-serials, and serial-lookup in MDC.
- [x] Changed how passwords are hashed, way faster and way more secure.
- [x] Improved how MySQL handles name changes.
- [x] Fixed a bug where changing your password THEN your name in the same session would cause your password to revert back to the old one.
- [x] Added /cw (car-whisper), now recognises masks.
- [x] Added /removetickets [playerid] for LSPD members rank 3 or higher.
- [x] Optimized inventory loading as much as it can be optimized.
- [x] Added additions to the 'knockout' system in he script. (When being attacked with melee weapons.)

- [x] Added the ability to change the color of any layer on attached toys. (/items)
- [x] Replaced "Exit" buttons on [i][b]lists[/b][/i] in the in-game UCP with "Back" buttons.
- [x] Added /despawnvehicle [vehicle-id] so admins can now despawn vehicles without being in them.
- [x] Rewrote and improved faction shipments/crates.
- [x] Added '/(house|biz|map) select' which allows you to use your cursor to select and edit an object.
- [x] Fixed /getcar [vehicle-id] not setting the vehicle's virtual world and interior.
- [x] Added text-file ban/unban logs. (This way admins can get the logs while they're not built into the web-UCP.)
- [x] Added further support for hidden-admin mode. (/ahide [value] | 0 = not hidden | 1 = hidden | 2 = totally hidden.)
- [x] Worked around an issue where 'RemoveBuildingForPlayer(playerid);' removes even streamer created objects with the same model, if they're in the same position (decimals excluded).
- [x] Added /gethid to get the house-ID of the house you're standing on.
- [x] Fixed any script-wise bugs with ganton mapping, and the houses in it's interior. (Also you'll no longer fall through the floor when leaving houses in the ganton interior, as they're in a "mapped" virtual world now.)
- [x] Removed weapons from crafting system. (Except Colt .45 at level 5, costs lots of materials to craft.)
- [x] Added 'Toggle Payment TD' setting to /ucp -> settings so people with the weird Textdraw glitch can use a plain dialog menu instead when making purchases.
- [x] When buying automatic weapons or car bombs in a faction shipment, your shipment now needs to be approved by an administrator.
- [x] More optimizations to inventory script. (Decreased RAM usage.)
- [x] Added new vehicle-impound system.
- [x] Added /aimpound [vehicle-id] [price ($1-$2500)].
- [x] The streamer now pre-loads areas before moving you to them to prevent vehicles from falling through mapping. (Now we don't have to watch mapped interiors load, woo!) (NOTE: Lag spikes may still cause this to happen, blame Incognito nothing I could do but delay SetPlayerPos which would look ugly as shit.)
- [x] Now freezes you momentarily when doing /specoff so you don't fall through mapping you were on.
- [x] /goto and /bring(/gethere) now preload the area for the client who's being teleported, and temporarily freezes them if in a custom interior or world.
- [x] Added /weapon [adjust/bone/reset] for editing holster positions of specific weapons. (Remember backpacks hide holsters, /weapon hide only hides secondary holsters.)
- [x] Your 'time' is no longer set when in an interior, this way it looks more realistic at night since your house is a little dimmer. It allows your house lights to actually serve a purpose.
- [x] Fixed a bug where the drug come-down would revert your time back to the old time system (where 1 day is 24 hours IRL).
- [x] Fixed GPCI banning, bye ban evaders.
- [x] Added temporary bans that check if you should be unbanned during connection, rather than checking all bans every minute. (/tempban && /tempbanacc)
- [x] General ban system improvements.
- [x] "DROP WEAPON" in the inventory now works even while your inventory is full.
- [x] Firefighters can drop weapons and ammo again, just fire extinguishers don't create an item when dropped.
- [x] The script now checks if your inventory is full before letting you pick items up.
- [x] Rewrote map, house, and business furniture saving/loading.
- [x] Re-enabled outdoor furniture. (Checks to make sure its an approved furniture object when planting outdoors.)
- [x] Houses can now be unlocked near the garage.
- [x] Added confirmation dialog to '/[house/biz] removeall'.
- [x] Talking while fishing no longer removes your fishing animation.
- [x] Added radio stations and "Radio Los Santos" station (in normal radio list) support to boom boxes.
- [x] URL streams now properly refresh after leaving a vehicle.
- [x] Added '/drop weapon' to drop the weapon you're currently holding as an item.
- [x] Raised max house and business objects to 1000, outdoor limit is still 20.
- [x] Added extra checks to GPCI banning that makes it less effective, but since Kalcar sucks and these aren't unique I had to. Welcome back ban evaders with half a brain.
- [x] Added HasInvItem(playerid, itemid, amount), this function returns the slot to prevent item duplication during crack cooking.
- [x] More improvements to ban evasion detection. (We're as good as SA:MP will allow unless we want to start making assumptions that can lead to false-positives.)
- [x] Re-wrote and added /forbid /unforbid this time it actually saves and doesn't use 'GetPVarInt' in OnPlayerUpdate.
- [x] Further optimizations to OnPlayerUpdate. Moved some things out of OnPlayerUpdate that didn't need to be there.
- [x] Fixed an issue where /putgun would run the player-save operation before removing your weapon. (So lets say you /pg then the server restarts, you'd have he gun in your inventory AND in your hand.)
- [x] Added /ab. (Like /b except uses your admin-name and rank-color.)

- [x] Coded a 'watchdog' script that'll restart the server if it were to ever crash.

- [x] You can no longer change your staff name to one thats in use. (Sort of redundant cause it logs the admin's player name and staff name.)
- [x] Admins are now notified when 'GetTickCount()' tells the script that it's within 1 day of overflowing. It tells the admins that the VPS (or whatever the servers hosted on) needs to be restarted.
- [x] There are now 2 IC days per 1 OOC day instead of 3.
- [x] Fixed "Previous Page" option in ban list.
- [x] Added /gotopos [x] [y] [z] (Optional: [vw] [interior].)
- [x] Added support for entering/exiting: Journeys, Ambulances, Police Enforcers, AT400s, and Tropics with /enter and the 'H' key.
- [x] /cw (car whisper) now allows people in the vehicle's interior to hear you.
- [x] /s and /knock now support vehicle-interiors.
- [x] /v radio support for vehicle-interiors added, enter-able non-engine vehicles can now use /v radio as well.
- [x] Made all the /goto and /gethere style functions support vehicle-interiors.
- [x] Added police scanners.
- [x] Added /spawntowtruck, /despawntowtruck ('tt' for short.) for Rapid Recovery faction to spawn tow-trucks.
- [x] Added /impound [price ($2500 max)] for Rapid Recovery faction.
- [x] Added /v release.
- [x] Improved armour hack protection.
- [x] Fixed the 'MessageEx' functions dropping wrongfully 1 character from the string.
- [x] /cuff (animation) is now /cuffanim. /cuff is now an alternative to /handcuff.
- [x] Added /bolo.
- [x] Added house backdoors again. (/housebackdoor [house-id] /housebackdoorremove [house-id])
- [x] Added business backdoors again. They now use pickups instead of checkpoints. (/bizbackdoor [biz-id] /bizbackdoorremove [biz-id]).

- [x] Added new limit system to faction-shipments.
- [x] Added [drugcount/wepcount] to /setfaction [id] so level 8+ admins can set factions closer to/further from their order-caps.
- [x] Added "Empty Slot" option when selecting shipment items to empty a slot.

- [x] Added /factions to list the amount of players on for every faction.
- [x] Added /spawn as an alternative to /v spawn.
- [x] Added /vehiclespawn [database-ID] | rewrote /vehicledespawn [database-ID].
- [x] Changed some commands and rank requirements.

- [x] /l is now a shortcut for /low.
- [x] Fixed a bug where /v lock wouldn't work in your car sometimes.
- [x] Admins can now use staff-names that are already in use. (Since we log more than just the staff-name anyways and 1 admin may have multiple characters.)
- [x] Interior exits are now marked.
- [x] Added /setname for lvl 6+ admins.
- [x] Added /apm.
- [x] Redid vehicle ELM.

- [x] Added /showpms.
- [x] Fixed an exploit with level 9 admins and /makeadmin. 
- [x] Police can now impound cars instead of just Rapid Recovery.
- [x] Added /deletefurn that lets admins select house/bizz furn w/ their cursor and allows them to delete it. (It asks for a confirmation, and says who's house/bizz it's part of before removing it.)
- [x] Updated admin help.
- [x] Added /deletetag that lets admins select spraypaint w/ their cursor and delete it. (/removetag is the same command.) (Asks for confirmation.)
- [x] Added /deleteclosetag that lets admins delete a nearby tag. (Within 6 units.) (/removeclosetag is the same command.) (Asks for confirmation.)
- [x] Added /deletetags [faction-ID] that lets admins delete all tags that belong to a specific faction. This notifies other admins and the faction. (/removetags is the same command.) (Asks for confirmation.)

- [x] Added new vehicle furnishing system.
	*Outside your vehicle you can place vehicle-approved objects like speakers, etc.
	*Vehicles with interiors let you build inside like you would in a house or business.
	*Vehicle objects support materials, etc, just like house and business objects.
	*Vehicle furnishing rights can be given using /v rights.
	*Max of 15 vehicle-objects outside. (Dynamic, changeable.)
	*Max of 60 vehicle-objects total. (Dynamic, changeable.)
	*Max of 3 neon-underglows (Dynamic, changeable.) (Subsriber only.) (Expensive.)
- [x] Added /toggleoutdoorvehiclefurn to enable/disable outdoor vehicle objects. (Level 7+ administrator required.)
- [x] Added /deletevehiclefurn that lets admins select vehicle objects w/ their cursor and delete them. (Asks for confirmation.)
- [x] Added /deleteallvehiclefurn that lets admins delete all furniture objects belonging to a specific vehicle ID. (Asks for confirmation.)
- [x] Added /toggleneonunderglow so admins can enable/disable neon underglow.

- [x] Added /v neon so users can toggle neon-underglow on/off.
- [x] Added /takemelee (/tm) to equip a melee weapon from your inventory.

- [x] /putgun (/pg) now saves your last primary weapon, secondary weapon, and melee weapon and attempts to equip the proper one when using /take(prim/sec/melee).
- [x] Changed shipment flare to a green property marker, now when the shipment arrives it broadcasts the location name to the faction and sets a checkpoint on their minimap.
- [x] Added /shipmenttimeleft [faction-ID] [minutes left.] to level 9+ admins so they can choose how long it takes a factions shipment to arrive. (This is logged.)

#[TODO]#
- [ ] Baitcar system.
- [ ] Set the players velocity to 0 when using a swat-rope and manually lower them to the ground using a timer, or even OnPlayerUpdate.
- [ ] Make all array-indexes that start at '1', start at '0'.
- [ ] Make sure theres no more stupid 'if (found == 0) { }' in loops, and ensure they use 'break' statements instead.
- [ ] Convert any PVars that are set/called fairly often to be part of the PlayerInfo array.