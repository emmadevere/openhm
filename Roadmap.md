# Looking into the Future #

This is our current programming roadmap, detailing when each release will be brought out, or more likely, what each release will feature, and will allow you to look back at what each release was and what was its specific goal. It will show you that, for example, the x.y.z series relates to introducing a tractor, and when that release is reached it'll describe the different releases in the series and what they actually accomplished, with seperate pages later on for each series & sub-series.


## EXPERIMENTAL QUALITY ##

# 0.0.x Series #

  * _0.0.1 (To develop a basic window in Pyglet, to see what can and can't be done)_
  * _0.0.2 (To add in menus if possible, a documentation browser feature for later)_
  * _0.0.3 (Creation of a small "box", 4x4 square, and a basic sprite)_
  * _0.0.4 (Figuring out fuctions of the sprite, to map keyboard keys to movement)_
  * _0.0.4b (optimisations, if necessary)_
  * **0.0.5 (Use of a much larger surface, use of maps possibly, or tiles. this will be the farmland)**
  * 0.0.6 (A mailbox and closed shack is added in, testing unmovable-object interaction)
  * 0.0.7 (More UOs are added, namely what will become the barn, a tree, chicken coop, etc.)
  * 0.0.8a (We test with items you can't pick up, how jack will react to them)
  * 0.0.8b (Tests with people, who move around on different "tiles" (that aren't visible))
  * 0.0.8c (Tests with animals, who move around freely)
  * 0.0.8d (Tests with items that can be pushed/pulled)
  * 0.0.8e (Tests with items that can be picked up?)
  * 0.0.8f (Tests with items like stumps, and their respective values)
  * 0.0.8g (more tests, stabilisation of current code)
  * 0.0.8h (attempt to mix all of the above together)
  * 0.0.9 (Attempt to make an inventory for items picked up. Initially one item held, then one in the bag and one held, then more as necessary)

# 0.1.x Series #

  * 0.1.0 (Branch's stable release)
  * 0.1.0b (The branch's stable release, with .8h's features mixed in for more testing with it.)
  * 0.1.0.1 (The first artifical NPC character, Yasu, is introduced, as a character who walks around near a building, his house.)
  * 0.1.0.1b (Yasu begins to get some dialogue; he's whatever. Interacts with Jack)
  * 0.1.0.2 (Yasu becomes a fully developped character, who has a very simple friendship points system (talking raises points to change dialogue))
  * 0.1.1.0 (Doors appear in the field)
  * 0.1.1.1 (We try getting doors to open and auto-close)
  * 0.1.1.2 (Developpement of Jack's first house)
  * 0.1.1.3 (We link the two together)
  * 0.1.1.4 (Same as the above, except in this release the door should make the field yield to the house, and vice versa)
  * 0.1.1.5 (TimeStopper is implemented, or possibly a save system)
  * 0.1.1.6 (Introduction of NPCs and animals in a building)
  * 0.1.1.7 (Items in buildings)
  * 0.1.1.8 (Multiple buildings, and initial development of the river)
  * 0.1.1.9 (Buildings should be finalised, with the introduction of the "locked doors" concept)

## BUG SEASON ##

# 0.1.2.x Series #

  * 0.1.2.0 (The river should be done by now, as well as a pond of sorts)
  * 0.1.2.1 (Tools are introduced, as well as the field itself if we haven't done so already)
  * 0.1.2.2 (Actually implementing the generic code for tools)
  * 0.1.2.2.1 (First comes the hoe)
  * 0.1.2.2.1.1 (Hoe's upgrades?)
  * 0.1.2.2.2 (Then comes the hammer)
  * 0.1.2.2.2.1 (A bit of testing in terms of hammer strenght)
  * 0.1.2.2.3 (Then comes the axe)
  * 0.1.2.2.3.1 (More axe and hammer strenght, this should be easier)
  * 0.1.2.2.4 (Sickle)
  * 0.1.2.2.4.1 (Sickle's upgrades?)
  * 0.1.2.2.5 (Fishing rod -- **IMPORTANT:** Doesn't actually catch anything yet; just set to bleep you when it catches something)
  * 0.1.2.2.6 (Watering can -- same as rod, but this waters infinetly)
  * 0.1.2.2.6.1 (Try to get a water retention system going)
  * 0.1.2.2.6.2 (Apply the above over multiple upgrades)
  * 0.1.2.2.6.3 (Watering can's strenght implemented)
  * 0.1.2.2.7 (Generic tool)
  * 0.1.2.2.8 (Seed bags)
  * 0.1.2.3.1 (Different types of seeds are introduced. Namely, Turnips, Tomatoes, and Carrots. No seeds for winter)
  * 0.1.2.3.1.1 (Generic seed code)
  * 0.1.2.3.2 (Getting the program to realise that when a seed bag is used, all squares around it and the current square are sown)
  * 0.1.2.3.3 (Implementing water in relation to plants)
  * 0.1.2.3.4 (Getting the plant schedules done, like what they look like in different phases, and time to reach each phase)
  * 0.1.2.3.5 (General testing release)
  * 0.1.2.3.6 (Creating the finalised product, a vegetable at the end of the process)
  * 0.1.2.3.7 (Taking into account that a day without water makes the plant retarded by a day)

**IMPORTANT**

At this time, item giving needs to be implemented. Individual characters and objects can be given items, and will give a reaction based on that. For characters it's a dialogue and an increase or decrease in FP/LP, for the shipping bin and internal counter is incremented. Hopefully this will be modular as the rest of the code should be, so that it simply refers to an external (plaintext) file to determine how to react to who, or how to deal with shipping values.

  * 0.1.2.3.8 (Eating function is implemented)
  * 0.1.2.3.9 (Shipping box in built, doesn't do anything but count whatever you have in it)
  * 0.1.2.4.1 (Creation of the shipping subsystem)
  * 0.1.2.4.2 (Creation of whoever is responsible for shipping)
  * 0.1.2.4.2b (Massive testing in regards to interaction between Shipper, items, Jack, and Yasu)
  * 0.1.2.4.3 (Prices list is created, the box now shows values in terms of quantity and value)
  * 0.1.2.4.4 (Developpment of currency as a simple value)
  * 0.1.2.4.5 (Shipping bin is emptied at the end of the day, or 5PM or something, and value is paid)
  * 0.1.2.4.6 (Yasu starts selling seed bags in his shack. Money exchange tests)
  * 0.1.2.4.7 (Yasu starts selling food in his shack. More tests)
  * 0.1.2.4.8 (More testing)
  * 0.1.2.4.9 (Yasu no longer sells items, but the code is retained for later)
  * 0.1.2.5.1 (Initial developpement outside of the town; just a wooded area)
  * 0.1.2.5.2 (Yasu's house is moved there)
  * 0.1.2.5.3 (If all goes well with .3, we add in stumps and a lumberjack's house)
  * 0.1.2.5.4 (Introduction of lumberjack)
  * 0.1.2.5.5 (Another area is introduced, the town in its basic form)
  * 0.1.2.5.6 (Mouvement through the town and other experiments continue)
  * 0.1.2.6.1 (Developpement of a Blacksmith's lot)
  * 0.1.2.6.2 (Blacksmith can now trade money, sells a brush and other tools to Jack)
  * 0.1.2.6.3 (Implementation of tool upgrading)
  * 0.1.2.6.4 (Figuring out how to keep his door shut when he's working)
  * 0.1.2.7.1 (General Store is opened and ShopKeep is introduced)
  * 0.1.2.7.2 (Has counters, sells seeds depending on season)
  * 0.1.2.7.3 (Testing the purchase of larger rucksacks)
  * 0.1.2.7.4 (Baskets? General new items to mess around with for the rest of the series)
  * 0.1.2.7.5 (ShopKeep's daughter and wife are introduced)
  * 0.1.2.8.1 (Wildflowers are implemented)
  * 0.1.3.x (Devoted to items)
  * 0.1.4.x (General section for love points and friendship points)
  * 0.1.5.x (More testing, if necessary)
  * 0.1.6.x (Festivals)
  * 0.1.7.x (Grasses, chicken feed)

## ALPHA QUALITY ##

# 0.2.x Series #

  * 0.2.0.1 (Chicken farm and cow farm are introduced)
  * 0.2.1.x (Chickens are introduced with the chicken coop)
  * 0.2.1.1.1 (Ducks, a sub-class of chickens, can be bought and taken care of)
  * 0.2.2.x (Cows can be bought and taken care of)
  * 0.2.2.1.1 (Goats, a sub-class of cows, can be bought and taken care of)
  * 0.2.3.x (Sheep can be bought and taken care of)
  * 0.2.4.x (Animals can have affection points now, and a system is developped to measure it)
  * 0.2.5.x (Animals begin to produce things)
  * 0.2.6.x (Introduction of lumber as a building material)
  * 0.2.7.x (Barn and coop can be upgraded, possbility of building more)
  * 0.2.8.x (More land can be purchased?)
  * 0.2.9.x (General bug testing)

# 0.3.x Series #

  * 0.3.1.x (House upgrades?)
  * 0.3.2.x (Home furnishings)
  * 0.3.3.x (On the topic of electricity, as well as weather)
  * 0.3.4.x (Preprations for marriage, and the things it brings)
  * 0.3.5.x (More developpements in town, extra stores and the winery)
  * 0.3.6.x (In town, a second zone is added, a residential area, and the Inn is completed. Guests stay at the inn, some permanent residents.)
  * 0.3.7.x (Developpment outside of town; the beach, the woods, etc.)
  * 0.3.8.x (AI is being worked on, for speech and movement patterns, more characters added)
  * 0.3.9.x (Interaction of characters and analysation that no characters will collide)

## BETA QUALITY ##

# 0.4.x Series #

(Game feels "done" at this point for simple farming)
  * 0.4.0.1 (Horse races)
  * 0.4.1.x (Any other festivals and events, random events are developped now.)
  * 0.4.2.x (Dialogues should be reworked at this point; they should be more or less 100% "perfect")
  * 0.4.3.1 (Creation of an installer for windows) (Creation of an installer for OSX) (Packaging of the linux version)
(And methods to further package quickly for all OS and archs)
  * 0.4.4.x (Possible addition of the cat)
  * 0.4.5.x (Addition of wild animals)
  * 0.4.6.x (Ferry as a location)

# 0.5.x Series #

  * 0.5.x (The Emotion Engine subsystem and associated mechanics, things like love points, friends points, recieving and giving items, etc.)

# 0.6.x Series #

  * 0.6.x (Aging within animals, especially for the horse, the dog, and the possible death of animals)

# 0.7.x Series #

  * 0.7.x (Fishing system)

# 0.8.x Series #

  * 0.8.x (Removing the old time system, building a special custom one, that works properly)

# 0.9.x Series #

  * 0.9.x (Basic aging within the people; specifically the player's children to toddler age)

# 0.10.x Series #

  * Creation of the in-game help system and in-game statistics.

# 0.11.x Series #

  * Bug squashing
  * Alpha/beta + rc series are incorporated as 1.0-beta1 etc.

## REQUIREMENTS FOR STABLE RELEASES (1.0, 2.0) ##
  * No outstanding bugs
  * Successor to x.100-final.
  * Completion of the help system.

## RELEASE RELEASE ##
  * Translated in various languages, at least French.
  * Distribution as a CD?
  * Distribution of printed manual.

### 2.0 RELEASE ROADMAP ###
As of now, only developpement of a network. Would allow users to buy from each other, talk/chat to others, play minigames, etc. Maybe gamecube version, by starting off with the use of an emulator like Dolphin, and an IDE like EclipseGC.

# Notes #

Some steps can be skipped for later; for example, if fishing is too difficult at the time, or we're missing pieces, the 0.7.x series can be about something further on. They aren't in a specific order when it's at Beta quality.