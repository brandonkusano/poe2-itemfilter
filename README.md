Green = Gear for your character
Purple = Gear for your character / Money
Orange = Money / Gear for your character



This is an item leveling filter and does not help with endgame (it's not an endgame filter)
The classes that are outlined are Stormweaver, Warbringer, Pathfinder, and Witchhunter. 
We outline classes because each class has their own stat priority (with the exception of Pathfinder and Witchhunter)
Each filter only picks up specific weapons as well (although it picks up every single type of weapon)
Stormweaver will only pick up wands and focus
Warbringer will only pick up melee one handed, melee two handed, and shields (maces and axes)
Pathfinder will only pick up bows and quivers
Witchhunter will only pick up crossbows

NOTE: Although most of the gear in the builds is accounted for, the weapon filter is generic and probably won't meet your exact builds parameters.
My tip is to slightly adjust the filter for weapons. Example: A monk build using quarterstaves will use the dexterity page (either Pathfinder or Witchhunter)
but the weapon will need to be changed to quarterstaves instead of whichever items are coded/present.

SIDENOTE: What if I can't code the item filter? Don't care. Each item filter is unique and I'm not coding 20 item filters for 20 slighlty different builds.
The actual operation of changing your item filter for our case is easy. Just get the weapon you would like to filter and replace it with the weapon that I coded.
If there are any problems then the game will tell you ("Item filter loaded successfully" is what we're looking for) and in some cases you might have to use youtube
to solve your problem e.g Quarterstaves and Staves will actually conflict in the filter unless you use a specific operator (==).


WEAPONFILTERADDED: A more user technical version of the item filter. We use "BaseType" instead of "Class" to filter our weapons. This looks cleaner in-game
with all specified weapons (even whites) being pinged while weapons from the same class type are pinged to purple, regular blue, and hidden. The updated 
filter is identical to the previous filters with the exception of a single line of "Class" being changed to "BaseType". 

Example with previous filter : Class Wand

Example with new filter : BaseType "Attuned Wand"

Notice that in this example the user needs to know what weapon they are using (Build specific). I have released another item filter that uses "BaseType" 
as an example. 

UPDATE: Small early game adjustment, flasks now always appear in campaign. Scroll of wisdom now turned off for high level areas (Slight end game adjustment).