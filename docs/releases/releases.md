# Rise Gaming Takistan Life - Complete Release Notes

This document contains all release notes for the Rise Gaming Takistan Life Arma 3 server.

**Total Releases: 79**

---

## v1.23.0 - Latest Release
**Released:** August 31, 2025

### Added
- Added colour options when making gangs.
### Changed
- Capturing gang areas now changes the colour of the area to the gang's colour.
- Gangs get money paid into their gang funds every 15 minutes for each gang area they control ($25k per territory).
- Moved southern organs dealer to the black market.
- Indies can now farm, process and sell all drugs.
- Balanced prices of drug licences.
### Fixed
- Fixed issue where PMCs couldn't open their land vehicles garage.

---

## v1.22.0
**Released:** August 30, 2025

### Added
- Added garages to all VIP vehicles shops.
- Added air garage to PMC base heli shop.
### Changed
- Removed PMC and ESU chats as they don't work as expected.
- Removed civilian land/air garages.
- Civilian garages can now be found at the car shops in civ spawns and the air shops.
- Resources app now has better formatting (thanks Supersahen).
- Players dying no longer cleans up 3rd party items that are on the ground nearby (thanks Supersahen).
### Fixed
- Fixed civilian VIP safezones allowing other factions to enter.
- Fixed issue where Blufor & Opfor could lose weapons on death (thanks Supersahen).
- Fixed players equipping binoculars when respawning (thanks Supersahen).
- Fixed issue with spawn menu closing and getting stuck on a blank screen (thanks Supersahen).
- Fixed issue with death screen not opening in certain situations (thanks Supersahen).

---

## v1.21.0
**Released:** August 29, 2025

### Added
- Readded C130 wreck.
### Changed
- Reworked North and South Hospital.
- Moved Southern Mod Shop to space things out.
- Moved Southern Farmers Market to space things out.

---

## v1.20.2
**Released:** August 28, 2025

### Added
- Added custom voice and text chats for PMC and ESU.
### Changed
- Changed weight of meth ingrediants in line with meth weight balancing changes.

---

## v1.20.1
**Released:** August 26, 2025

### Changed
- Resource price and weight balancing.
### Fixed
- Fixed issue where having a dialog open when dying locks up your UI.

---

## v1.20.0
**Released:** August 25, 2025

### Added
- Added new tablet app that allows players to check the demand and price of resources.
- Added new inventory icons for resources.
### Changed
- Demand for resources increases every 45 minutes and decreases when selling large numbers of resources. Demand does not change if no players are online.
- Refuelling vehicles and buying jerry cans contribute to the price of oil increasing.
- Fuel consumption coefficient for most vehicles has been increased to 1.5.

---

## v1.19.0
**Released:** August 24, 2025

### Added
- Added car bomb kit to indie shops that works the same as bomb cars but the item can be applied to any vehicle.
- Added a more expensive car bomb kit with a larger bomb to indie shops.
### Changed
- Removed the bomb car from indie shops.
### Fixed
- Fixed GP-25 poison gas grenade launcher rounds not damaging players that walked into the smoke.
- Fixed cars with removed plates having them again when taken out of garages.
- Fixed vehicles not being saved to the DB when created with factories.
- Fixed error in nitro kit code.

---

## v1.18.3
**Released:** August 23, 2025

### Changed
- Moved southern car impound.
### Fixed
- Fixed some floating pallets and wonky buildings at the southern logistics shop.

---

## v1.18.2
**Released:** August 23, 2025

### Fixed
- Fixed vehicles not having nitro or speed upgrades after being stored.

---

## v1.18.1
**Released:** August 22, 2025

### Fixed
- Fixed issue with max carry weight calculation.

---

## v1.18.0
**Released:** August 21, 2025

### Added
- Added logistics shops to the North and South airfield.
- Added Southern Farmers Market.
- Added some more farmable resource spots.
### Changed
- Civilians can now start a delivery mission from the South airfield.
- Moved North and South delivery centers.
- Moved some farmable resource spots.
- Opfor can now harvest legal crops.
### Fixed
- Fixed vehicle factories creating vehicles that could not be stored in garages.

---

## v1.17.1
**Released:** August 20, 2025

### Changed
- Added more debug logging to vehicle cleanup code.

---

## v1.17.0
**Released:** August 18, 2025

### Changed
- Consolidated vehicle updating functionality to reduce DB calls.
- Shop functionality rewritten by Supersahen.
- Attachments/Magazines can now be sold directly from inventory or from equipped loadout.
- Changed weapon prices for weapons that came with attachments to prevent money duping.
### Fixed
- Fixed attachments not being sellable.
- Fixed shops slowing down the more they're opened.
- Fixed issue where stat loading would duplicate original CUP attachments if weapons with preloaded attachments are changed.
- Fixed garages not showing correct info for selected vehicles.

---

## v1.16.10
**Released:** August 16, 2025

### Changed
- Lowered sell prices of unrefined minerals.
- Increased carry weight of coal, meth and oil.
- Buffed drug sell prices.
- Reworked organ harvesting function.

---

## v1.16.9
**Released:** August 15, 2025

### Changed
- Removed the last of the mp_compile_code function usages in favour of safer remoteExec functions.
- Optimised shop opening code (work done by Supersahen).
- Rolled back friendly faction changes because they allowed enemies to see each other at all times.
### Fixed
- Fixed duping money and items when players Alt + F4 after dying.
- Fixed not being able to search for attachments in shops (work done by Supersahen).

---

## v1.16.8
**Released:** August 13, 2025

### Changed
- Removed searchlight objects from the mission as they never spawn nicely in CUP.
### Fixed
- Fixed playSound triggers from stacking if the player enters the trigger repeatedly.

---

## v1.16.7
**Released:** August 13, 2025

### Changed
- Black market shop items are now tax free.
### Fixed
- Fixed phone market prices being 1000% higher instead of 500%.
- Fixed being able to start many instances of mining with the same vehicle.
- Fixed vehicles with the miner upgrade continuing to mine while the owner isn't near them.

---

## v1.16.6
**Released:** August 12, 2025

### Fixed
- Fixed factory storage, stock and queues not having player contents loaded from DB.
- Fixed factory storage showing player inventory items that can't be used with factories.

---

## v1.16.5
**Released:** August 12, 2025

### Changed
- Vehicles left on the map when the server restarts are now impounded rather than being erased from existence.

---

## v1.16.4
**Released:** August 11, 2025

### Fixed
- Fixed being able to dupe money from selling the "No vehicles stored" index on the garage dialog.
- Fixed losing money from trying to retrieve the "No vehicles stored" index on the garage dialog.
- Fixed several spelling mistakes.

---

## v1.16.3
**Released:** August 10, 2025

### Fixed
- Fixed vehicles being impounded causing garage listing to break.

---

## v1.16.2
**Released:** August 09, 2025

### Changed
- Southern civ spawn shop now sells lockpicks like the northern civ spawn shop.
- View distance is set to 10km by default now to remove rendering fog.
### Fixed
- Fixed Darter drone not being in the garage war vehicles list.

---

## v1.16.1
**Released:** August 09, 2025

### Added
- Added player counter and faction counter to bottom left of player HUD.
### Changed
- Increased size of service point triggers.
### Fixed
- Fixed vehicle info not being saved correctly.
- Fixed exploit allowing players to mine while driving their vehicles.

---

## v1.16.0
**Released:** August 08, 2025

### Added
- Added southern vehicle mod shop.
- Added energy drink item that allows players to sprint without consuming stamina for a minimum of 1 min to a max of 2 mins.
- Added vehicle mining modification to mod shops.
- Added clothing shops to the Blufor, Opfor and Indie VIP areas.
### Changed
- All factions are now configured to be friendly to make arresting and detaining players in vehicles easier.
- Removed view distance GFX setting, view distance is now based off the player-defined graphics setting.
- Tweaked all Opfor heli spawns to prevent issues with Mi-6 spawning.
### Fixed
- Fixed issue where safezone triggers were deleted from the .sqm but not the codebase.
- Fixed Blufor no kill zone not being present on the map.

---

## v1.15.0
**Released:** August 07, 2025

### Added
- New super secret admin commands.
### Changed
- Redesigned Opfor main base.
- Redesigned Opfor VIP base.
- Redesigned OSF base.
- Moved Southern Prison.
- Moved Gold mining area.
- Moved a bombing mission that targeted a random house near southern truck shop.
- Reworked garage dialog.
- Improved DB logging for various admin commands.
- Carmageddon is now Impoundmageddon. If admins need to clean up the map, all cars are now impounded.
- Removed global messaging app as it's not currently needed.
- Reworked Blufor main base.
- Reworked SRT base.

---

## v1.14.3
**Released:** August 06, 2025

### Changed
- Drones retrieved from garages no longer need to be hacked before use, they also spawn unlocked.

---

## v1.14.2
**Released:** August 05, 2025

### Changed
- Purchased drones no longer need to be hacked before use, they also spawn unlocked.
- The server's 6 hour restarts are now soft mission restarts handled by BEC rather than server .exe restarts.
### Fixed
- Fixed issue where large vehicles could not be impounded after the persistent impound update.

---

## v1.14.1
**Released:** August 05, 2025

### Changed
- Improved readability of Warrants menu.
### Fixed
- Fixed issue where R3F functionality is disabled on vehicles stored and retrieved from garages.
- Fixed issue where players were kicked if their character is created in-game before their stats have finished loading.

---

## v1.14.0
**Released:** August 04, 2025

### Changed
- Impounded vehicles now persist across restarts.

---

## v1.13.1
**Released:** August 03, 2025

### Changed
- Reworked design of Checkpoint Alpha, Bravo and Delta.
### Fixed
- Fixed issue causing gangs not to load correctly.
- Fixed JIP issues with not being able to pickup fortification shop items.

---

## v1.13.0
**Released:** August 02, 2025

### Added
- Added AH-6X drone to Blufor shops.
### Changed
- The Darter drone is now a war vehicle for Blufor.
### Fixed
- Fixed some typos.

---

## v1.12.1
**Released:** July 26, 2025

### Added
- Added better description to vehicles shown in shops to include storage capacity and avaliable weapons.
### Changed
- Reworked the following dialogs: keychain, warrants, settings and text messaging.
- Removed unused code and assets.
### Fixed
- Fixed ATM dialog issues for players not using 16:9 aspect ratio.

---

## v1.12.0
**Released:** July 23, 2025

### Added
- Added more types of delivery cargo.
### Changed
- Players can now take up to 3 delivery jobs at once.
### Fixed
- Fixes to gang updating functionality.
- Fixed PMC default say text.
- Fixed shop in use issue for mobile shop app.

---

## v1.11.9
**Released:** July 22, 2025

### Fixed
- Fixed not receiving Arma 3 items bought from the item shop app.

---

## v1.11.8
**Released:** July 12, 2025

### Fixed
- Fixed losing keys after relogging.

---

## v1.11.7
**Released:** April 24, 2025

### Changed
- Reverted loaded launcher changes after CUP vehicle handling issues were found.
### Fixed
- Fixed weapons losing their attachments and mags when stored in vehicles that are stored in the garage.
- Fixed players losing laser designator batteries when their player gear is saved to the DB.
- Fixed some shop items having classnames instead of display names.
- Fixed two incorrect backpack classnames.
- Fixed active gang persistence issues.
- Fixed rank/war/martial law shops not loading when opened.

---

## v1.11.6
**Released:** April 23, 2025

### Changed
- Removed setTimeMultiplier configuration but moved mission start to 15:30 so that both day and night are experienced during each 6 hour server cycle.
- Changed item dropping so that all items are now dropped in suitcases so repair kits and money can be picked up easier.
### Fixed
- Fixed Bank robbery gold bars not having pick up actions.
- Fixed Casino robbery not informing other players that the Casino is being robbed.
- Fixed Casino robbery 30 minute cooldown not being calculated correctly.
- Fixed shop buy amount not being taken into account when buying virtual items.

---

## v1.11.5
**Released:** April 22, 2025

### Changed
- Opening shops and filtering has been reworked to load faster and work more reliably.

---

## v1.11.4
**Released:** April 20, 2025

### Changed
- Players no longer need to be armed to check the inventory of a ziptied player.
### Fixed
- Fixed ESU now being able to load in.

---

## v1.11.3
**Released:** April 18, 2025

### Changed
- ESU now shared their bank account with Civs like PMC.
### Fixed
- Fixed further issues with gang persistence.
- Fixed PMC contract viewing issues.

---

## v1.11.2
**Released:** April 18, 2025

### Fixed
- Fixed issues with gang persistence.

---

## v1.11.1
**Released:** April 18, 2025

### Added
- Added vehicle lock change service to the mod shop. This service removes the vehicle keys from other players.
- Added plane push back action to help get planes unstuck or to assist in taxiing.

---

## v1.11.0
**Released:** April 18, 2025

### Changed
- Created gangs are now saved to the DB and persist between sessions.
- Stun gun range balancing. Now stun guns are only effective up to 30 metres.
- Speed gun usage range has been reduced to 100 metres.
- PMC contracts will now show for all players on the server but contract info apart from contract type is redacted if you are not the client or PMC.
- Changed elections for Blufor/Opfor/Indie to allow players to vote for themselves as leader if they're the only player in this faction at the time.
- Changed single-use rocket launcher classnames so that bought launchers spawn with a rockets included.
- Removed single-use rocket launcher ammo from shops.
- Updated community name in serveral areas of the mission file.
### Fixed
- Fixed flags being instantly captured if players select the capture actions straight after finishing the neutralisation action.

---

## v1.10.3
**Released:** April 16, 2025

### Added
- Added new CUP clothes to Blufor and Opfor.
### Changed
- Removed some SRT clothes that are actually used by Russia.

---

## v1.10.2
**Released:** April 16, 2025

### Fixed
- Fixed setFlagTexture resetting the flag texture shortly changing.
- Fixed progressBar typo that broken all progressBar calls.

---

## v1.10.1
**Released:** April 16, 2025

### Fixed
- Fixed bail resetting when a prisoner dies.
- Fixed r3f actions disappearing when retrieving a stored vehicle.
- Fixed vehicles being damaged in safezones.
- Fixed players being able to get in vehicles or hiding after starting flag capture/neutralisation actions.

---

## v1.10.0
**Released:** April 15, 2025

### Added
- Added Speedbomb to Indie equipment shops.
- Added phone shop app where basic items can be bought and instantly delivered to players. Takistan delivery fees mean that these items cost 500% more.
- Added TP actions for Blufor, Opfor and Indie to allow them to TP to VIP areas from their main base ATMs if they have a VIP licence.
- Added VIP spawn points for all factions if players have VIP licences.
- Added Presidential vehicle shop with one vehicle to start with, more can be added later.
### Fixed
- Fixed players being able to close the downed UI.
- Fixed players somehow managing to close the spawn menu.

---

## v1.9.3
**Released:** April 15, 2025

### Added
- Added item search bar and type filtering functionality to shops.
- Added shop discounts for all items in VIP, SRT and OSF shops (30% for VIP, 15% for SRT and OSF).
- Added SWAG SUV to Indie VIP.
### Changed
- Removed SWAG SUV from Blufor VIP.
### Fixed
- Fixed admin log menu and logging.

---

## v1.9.2
**Released:** April 11, 2025

### Changed
- Better formatting for vehicle info in shops.
### Fixed
- Fixed showing information about vehicles in shops.

---

## v1.9.1
**Released:** April 10, 2025

### Changed
- Slightly reduced time between territory payments.
- Tweaked progress bar script to prevent territory from being captured instantly.
### Fixed
- Fixed rank increase script not giving points to other players.

---

## v1.9.0
**Released:** April 09, 2025

### Added
- Added area capture functionality for Blufor, Opfor and Indies. These factions will earn money for each piece of territory they own.
- Added fortification shop to Indie base.
### Changed
- Decrease convoy payout to 500k.
- Indies will now gain rank points for successful bombing missions (30 for the bomber/10 for helpers).
- Extended ID check request functionality to drivers of vehicles during traffic stops.
### Fixed
- Fixed fog.
- Fixed interaction issues between higher ranking cops and lower ranking.

---

## v1.8.2
**Released:** April 07, 2025

### Added
- Added more street lights to main roads and towns.
- Added more lights to the North Prison.
### Changed
- Changed the North Prison layout to allow Huey-sized helicopters to land there for prison breaks.
- Changed Treefixer and World Heal code to also fix street lights.
- Changed fog base level to 500m (this should keep fog in the mountains).
### Fixed
- Fixed Indie air vehicle spawns to prevent helis being damaged when they're bought.
- Fixed gap between SRT safezone and Blufor airbase safezone.

---

## v1.8.1
**Released:** April 07, 2025

### Fixed
- Fixed suitcases and player money dropping on death but not being removed from the player on respawn.
- More fixes for police light despawning.

---

## v1.8.0
**Released:** April 05, 2025

### Added
- Added cruise control to ground vehicles.
- Added custom action overrides.
### Changed
- Say text shouts bound to keys 7, 8, 9 and 0.
- Cases should no longer hover over ground.
- Cases should not stack on top of each other. They should now scatter out.
- Suitcases should now drop all at once.
### Fixed
- Fixed issue causing launchers to be duped.
- Fixed magazines replenishing by raising your hands.
- Fixed suitcase drop when dying.
- Fixed Police lights floating when a vehicle is destroyed or impounded, or otherwise cease to exist.

---

## v1.7.5
**Released:** April 03, 2025

### Changed
- Changed mission start date.

---

## v1.7.4
**Released:** April 02, 2025

### Fixed
- Fixed spike strips not being removable by players.
- Fixed ESU not receiving dispatch notifications for calls.
- Fixed ESU not being able to use medkits to heal people.
- Fixed speed kit item use error.
- Fixed nitro kit item use error.
- Fixed modshop purchasing error.
- Fixed repainted vehicle texture not being set globally.

---

## v1.7.3
**Released:** April 01, 2025

### Fixed
- Fixed paint shop dialog not being found.
- Fixed some mod shop RPT file errors.
- Fixed Admin Menu not opening from Phone.

---

## v1.7.2
**Released:** April 01, 2025

### Fixed
- Fixed serveral mod shop script errors.
- Fixed paint shop jobs taking 1 second instead of 30.
- Fixed wrong variables being used when taxes are changed.

---

## v1.7.1
**Released:** April 01, 2025

### Fixed
- Fixed Mod shop not opening.
- Fixed Speed and Nitro kits having no use.
- Fixed altitude not being reported for speed guns.
- Fixed paint shop not having a dialog.

---

## v1.7.0
**Released:** March 31, 2025

### Added
- Added speed upgrade kit to car tuning and equipment shops.
- Added nitro kit to car tuning and equipment shops.
- Added car painting option to the Mod Shop.
- Added speed upgrade option to the Mod Shop.
- Added nitro kit option to the Mod Shop.
- Added licence plate removal option to the Mod Shop.
- Added larger backpacks to Civ VIP clothing shops.
- Added CHDKZ GAZ Tigrs to Independent.
- Added Takistan Army Mi-8 Rockets Helicopter to Opfor.
- Added CHDKZ Mi-8 Rockets Helicopter to Independent.
- Added spawn music for Opfor.
### Changed
- Bank interest payment balancing to curb money snowballing (VIPs get better interest rates).
- Indie Huey Gunship price balancing.
### Fixed
- Fixed issues with Jerry Can refueling.
- Fixed PMC and ESU not being able to open Civ VIP shops.
- Fixed another tip typo.

---

## v1.6.2
**Released:** March 30, 2025

### Changed
- Removed code that set the selected shop item to the first item in the shop list when the shop had finished loading.
### Fixed
- Fixed Blufor convoys not having the rob action.
- Fixed roulette bet button having the default bet value instead of the input box.
- Fixed some masterarray typos that caused RPT spam.

---

## v1.6.1
**Released:** March 30, 2025

### Changed
- Replaced CUP Vehicle Service Points with Arma 3 trigger scripts.
- Removed random palace from Rasman that Ahon accidentally added.
### Fixed
- Fixed Casino money handling issues.

---

## v1.6.0
**Released:** March 29, 2025

### Added
- Added functionality for Civs to rob the casino.
- Added 2 hour day/night cycle to the mission.
### Changed
- Increased convoy reward to match that of the bounty for robbing it.
- Added Discord QR code to playe HUD.
- Updated loading screen with QR code.
- New code to announce when a pmc contract is cancelled or completed to the server.
- Balancing for Drone/UAV prices.
### Fixed
- Fixed issue allowing multiple people to steal convoy at same time.
- Fixed issue causing convoy to be instantly robbed or failed robbery.
- Fixed casino money dupe exploit.
- Fixed licence requirements for Blufor Coast Guard 412.
- Fixed several typos.

---

## v1.5.0
**Released:** March 27, 2025

### Added
- Added Casino to the Rasman Hotel which includes roulette and blackjack terminals.
- Added various GAZ Tigrs and M1151s to the PMC vehicle shop.
### Fixed
- Fixed issue where bait cars stored in the garage cannot have kit installed after retrieval.

---

## v1.4.4
**Released:** March 27, 2025

### Fixed
- Fixed issue where bait cars stored in garage cannot have kit installed after retrieval

---

## v1.4.3
**Released:** March 26, 2025

### Fixed
- Fixes for player actions disappearing when a player dies.
- Fixes for Bank Insurance and Bank Insurance x5 not stacking in the same pill
- Fixes for Bank Insurance x5 not protecting players from being robbed

---

## v1.4.2
**Released:** March 24, 2025

### Changed
- ESU revive failure rate decreased from 35% to 20%.
### Fixed
- Fix for impound lot taking money when a vehicle hasn't been selected from impound.
- Fix for cops not being able to release prisoners from prison.
- Fix for cops and opfor being marked as criminals for killing players.

---

## v1.4.1
**Released:** March 23, 2025

### Changed
- Paycheck licence bonus balancing.
- Having VIP now gives players a paycheck bonus.
- Having VIP now gives players an increased private storage max weight.
- Having VIP now gives players an increased max carry weight.
- Balancing for clothing shops so there's a lot less crossover between Civs and Indies.

---

## v1.4.0
**Released:** March 22, 2025

### Added
- Added GAZ Tigrs to various shops
- Added M1151s to various shops
- Added Leopard 1A3 to various shops
- Added T-90M to various shops
- Added P30L to various shops
- Added Smith & Wesson R8 Model 327 Tactical Revolver to various shops
- Added XM29 to various shops
### Changed
- Replaced Kamaz Tempest custom skins with CUP versions
- Updated Discord links in mission

---

## v1.3.3
**Released:** October 01, 2022

### Changed
- AFK kicker disabled for now (if we enable it again, it'll only kick a player that's been AFK for 15 minutes)
### Fixed
- Item and Weapon bag functionality is inconsistant
- Players getting stuck on "Initialising Client" on the black screen when loading in

---

## v1.3.2
**Released:** September 12, 2022

### Fixed
- Blufor, Opfor and Indies not gaining rank XP and money from killing each other
- Balancing
- Price balancing for gathered/mined resources

---

## v1.3.1
**Released:** August 27, 2022

### Added
- ESU can now put dead bodies in body bags and take them to hospitals for money
### Changed
- ESU now gain rank XP for responding to medical emergencies
- ESU now gain rank XP for successfully reviving a downed player
- Reviving players now has a chance to fail which kills the downed player
### Fixed
- Blufor and Opfor no longer lose their primary and launcher weapons when they die
- Players can't respawn after dying in a blown up vehicle that's already despawned
- Assassination mission doesn't clean up when the assassin dies
- Assassination targets don't get rewarded for killing the assassin
- ESU can get point from calling medics to their own body
- Revived players are subdued
- Harvesting organs doesn't kill a downed player

---

## v1.3.0
**Released:** August 24, 2022

### Added
- Added CH146s to standard blufor shops using a US army skin
- Added CH146s to opfor shops using a Takistan army skin
- Added ZIL Karatel (Ifrit) with custom skin to OSF (credit to Supersahen, MRWeapon and Ahon)
- Added Gendarmerie Arma 3 Offroads and Vans with custom skins to police vehicle shop
- Added Kamaz Typhoon (Tempest) with custom skin to OSF and Eastern Arms Dealer (credit to MRWeapon)
- Added Oshkosh M997 (HEMTT) to Blufor and Western Arms Dealer
- Added more TP options to Blufor and Opfor so they can traverse their bases quicker (credit to Ahon)
- Added Vodniks to Insurgent shops with custom skins (credit to Ahon)
- Added South Takistan Pharmacy
- Added flashbangs (implementing this has replaced stones as they're used for flashbangs)
- Added appearance missions for the President (credit to Ahon)
- Added Arma 3 UAV terminals to various equipment shops on all factions
- Added UAV drones to various shops on all factions
### Changed
- Replaced News SUV with News Van
- Replaced HIL skin for CH146 with shark teeth US army skin at SRT
- Insurgent Hilux's that didn't have CHDkZ skins now have them
- Reworked SRT and Cop base
- Stealing a convoy payroll now takes 60 seconds (credit to Ahon)
- Blufor and Opfor now gain rank XP and additional paycheck money for guarding more locations (CP Alpha, CP Bravo, CP Delta and North Jail(Money only) for Blufor) (CP Alpha, CP Bravo, CP Delta, South Jail(Money only) and the TLA Communications Centre for Opfor) (credit to Ahon)
- Removed the military fortications from civ fort shops (credit to Ahon)
- Added fortications to Civ VIP fortications shop (credit to Ahon)
- Reworked respawning system to allow ESU to revive downed players
- Reworked jail functionality
### Fixed
- Using medkits causing glitched animation stance
- Player only recieve their stamina boost and traits when they've respawned
- Gear not saving after buying clothing
- Factory queue not displaying correctly
- Vehicles created at factories not storing in garages
- ESU cannot revive dead players
- Storing a vehicle while on a different faction to the owner would store it on the storer's factions rather than the owner's
### Removed
- Removed stone from shops
- Removed CUP UAV terminal backpack as it doesn't work
- Balancing
- Price and weight balancing for gathered/mined resources

---

## v1.2.1
**Released:** August 13, 2022

### Changed
- Moved opfor air shop and spawn to inside the HQ safezone
- M16s changes from requiring a rifle licence to an automatic licence at the gun shop
- Clothing shops now have useful information for items like armour level
### Fixed
- M1014 Entry variant shoguns not having ammo
- M1014 Entry variant shoguns can now stun people
- War vehicles being buyable outside of war in SRT shop
- Presidents without staff perms couldn't change laws
- Opfor light vehicle shop cannot store vehicles
- Bomb cars not working
- Committing suicide counts as teamkilling
- Death logs not going into the DB
- Supervisor commands not working
- ESU sirens not working
- Blufor and Opfor can farm XP points by ticketing each other
- Couldn't defuse gear-based bombs and mines
- Able to glitch out of jail
- Players can gather resources while in a vehicle
- Previously impounded vehicles cannot be stored
- Black civ SUV spawning in blue and white
- R3F vehicle contents not working
- Not being able to store helis at blufor air shop
- Indies, Civs, PMC and ESU getting blue polo uniforms in the DB they die
- Air impound deleting land vehicles retrieved from it and vice versa
- Being to store vehicles whilst towing
- Players set wanted for drug selling after switching factions
- Inconsistencies with hitting other players
- Player info app not updating stats
- Processing mined resources can be duped
- Depositing and withdrawing small amounts of money does not change your balance
- Being able to open backpack of other players from the furthest distance that the scroll option would allow
- Being able to open backpack of other players whilst they're spawning in
- Custom say text not working and breaking say text in general
- Factories not opening
- Factories not saving their related information
- Players can be pulled out of locked Tanks/APCs
- Dying in prison doesn't get your gear back on release
- Able to dupe money from deathlogging
- Some checkpoint items cannot be picked up

---

## v1.2.0
**Released:** August 02, 2022

### Added
- Added JSRS as an optional mod
- Added an "Check ID" function for Blufor/Opfor/PMC
- Added ATMs to Northern and Southern jails
- Added Captain shop at Police HQ for Blufor
- Added earplugs to more shops for Civs/ESU
- Added Impound lot near police HQ where it used to be in Arma 2
- Added some basic helmets and pilot helmets to PMC clothing shop
- Added beanbag rounds for the Saiga 12, SPAS-12 and M1014
- Added stun shotguns to Blufor/Opfor/PMC
- Added Southern Resource Refinery and Southern Oil barrel trader
- Added a Presidential Palace to a custom compound north-east of northern Civ VIP shop
- Added vehicle storage including land and air garage locations for civs to store vehicles (other factions can store theirs at their bases)
### Changed
- The weapons of stunned players are now saved if someone dies next to them
- Updated to a newer version of R3F
- Convoys are no longer deleted when the time limit passes if a person is still in the vehicle
- Delivering a convoy now also awards every player in the faction 5 rank XP as well as the monetary reward
- Civs and Indies who steal a convoy payroll now have a warrant set to them
- Holstering reworked to store one weapon that won't be re-equiped when you exit a vehicle
- The stun rifle's ammo has been renamed to rubber bullets and they are now effective for stunning at 100 metres
- Readded player marker on the map
- Phone removed from inventory screen and treefixer weight set to 0
- Opposing factions can no longer view the TLA HQ or Indie base
- Moved southern oil resource oilfield south of southern Civ VIP shop
- Moved oil resource north of jail to the Nagara-1 oilfield
- Moved rubies resource to the hills near Karachinar
- Moved coal resource to the hills near Zavarak
- Moved copper resource to where rubies used to be
- Moved Government Complex to a custom compound north-east of northern Civ VIP shop
- The President can now speak to a presidential advisor to change laws/taxes at the Presidential Palace
- The NPC used to voted for President at the Government Complex now sell licences
- Indies now get $100k for helping the bomber complete their bombing mission if they say within 1km of the target
### Fixed
- Been able to access vehicle trunks regardless of distance from vehicle
- Staff cannot access admin menu when being restrained/stunned
- Bail cannot be paid
- Placing checkpoint items removes attachments and ammo
- Indies cannot rob players
- PMCs not being able to ziptie
- Sell prices are now based on the sell prices in the master array rather than a fixed amount
- Police caps not being in blufor clothing shop
- Organ harvesting and selling now works
- Laws not resetting when the president dies
- Dragged players being stuck when the dragger dies
- Buying/selling in shops could be abused to duplicate money
- Check inventory function returning "any" instead of a player's gear
- Getting out of a vehicle will no longer re-equip your holstered weapons
- War vehicles can now be sold outside of War/Martial Law
- Using cleaning equipment creates infinite mixing equipment
- Shipping depot missions not working
- Bombing missions randomly failing as soon as the bomb is placed
- Tear gas not working
- Poison gas not working
- Captains being able to access the Colonel shop on Blufor
- Fixed glitching out of jail as much as possible
- Processing resources can be duped
- Suitcase bombs not working
- Dirty bombs not working
- Unflip vehicle function sinking vehicles into the ground
- Inventory weight check consistently issues
- Roadside assistance kits not working for ESU
- Inconstitant killer faction death logs
- Issues with using bipods and then getting in vehicles
- Inconsistencies with hitting
- Killers not setting being set wanted
- General map fixes
### Removed
- Player UI name tags
- Balancing
- Various price balancing and fixes
- Vehicle inventory capacity balancing

---

## v1.1.2
**Released:** July 14, 2022

### Changed
- Gun licences are only lost on arrest
- Vehicle licences aren't lost from VDM anymore
- Players now recieve faction-appropriate clothing if they don't have uniform
- Changed difficulty settings to custom to allow the hiding of enemy markers, friendly marker, mine markers and player marker
### Fixed
- PMCs can't load in after the first time
- Animation incorrect if you have a weapon and you surrender
- Vehicle info menu no longer works
- Lottery system not working/dialog too small
- Sending text messages doesn't work
- Trunk inventory doesn't refresh
- JIP unrestrained issues
- Drugs being duped while processing
- Airhorns not working
- Emergency lights not working
- Pressing 'O' to open bargates while in a vehicle as Cop/Opfor
- PMCs not having 3 rounds in their tasers
- Balancing
- Various price balancing and fixes

---

## V1.1.1
**Released:** July 13, 2022

### Changed
- Changing mission difficulty from "Custom" to "Regular"

---

## v1.1.0
**Released:** July 13, 2022

### Added
- Patrol points for Opfor
- Cleanup script kicks in automatically once server FPS goes below a agreed threshold
- Added code to stop war vehicles from being purchased if there's no war/martial law
- Players will now be kicked if they're AFK for 10 minutes
- Blufor, Opfor and Indies now recieve 3 XP for killing each other
- Blufor and Opfor now recieve 1 XP for ticketing players
### Changed
- Backend functionality reworked for performance improvements
- Patrol point(s) XP gain has been reduced from 4 to 1
- PMC contracts are now limited to being viewed by the contract giver and the PMCs
- Doubled max weight to negate stamina issues
- Repair kit repairing cycle
- Fuel kit refueling cycle
- Lockpick lockpicking cycle
- Gang flag capture reworked
- Remade northern jail
- Moved Western and Eastern Arms Dealers to far corners of the North and South respectively
- ISIS training changed to Jihadi training
- Jihadi training allows Indies to buy from civilian shops
### Fixed
- VIP repair kits
- Weapon/Tripod bags bought in shop now spawn correctly
- Robbing store timeouts are now store-specific, rather than player specific.
- Joint Ops request/accept/end issues
- President paychecks
- Incorrect chat messages for restraining
- Items that require engineer training
- Police landrover skin
- Swag SUV skin
- Special Forces SUV skin
- Defense mission(s) no longer cancel unless you're outside the zone for more than 10 seconds
- Looting player weapons when they die
- Vehicles spawning with toolkits
- First mag of a taser having 16 rounds
- Ticketing giving XP points to all players
- Convoys can be stolen by their own faction
- PMCs don't pop up in the player list
- Speed gun giving incorrect system chat log
- Admin menu button in phone breaks after one use
- Election countdown timer not working correctly
- Binocular slot items not stat saving
- Players can be robbed in safezones
- Various glitches/bugged NPCs on the map
### Removed
- Keychain from inventory as there's an app for it
### Balancing
- Various price balancing and fixes

---

## Rise Gaming Takistan Life v1.0.0
**Released:** June 25, 2022

The initial launch of our Takistan Life mission for Arma 3.

---

