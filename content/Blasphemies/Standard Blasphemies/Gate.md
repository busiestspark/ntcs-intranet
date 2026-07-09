---
tags: Blasphemy
image: "[[Gate Card.png]]"
blsphID: "5"
---
<style>

.section-background {
	width: 50%;
	background: linear-gradient(90deg, #161616, rgba(0,0,0,0));
}

.section-header {
	width: 20%;

	text-align: left;
	font-family: Cuasigothic;
	font-size: 1.5rem;

	margin: 20px 0px 20px 10px;
	padding: 10px 0;

	background: linear-gradient(white, gray);

	-webkit-background-clip: text;
	background-clip: text;
	
	color: transparent;
}

.tooltip {
	width: 20%;

	display: flex;
	align-items: center;
	justify-content: center;

	border: 2px solid rgba(0,0,0,0.5);
	border-radius: 1.3rem;

	margin: 10px 0;
	padding: 10px;

	transform: translateZ(0px);
	transition: transform 0.2s ease;

	background-image: linear-gradient(145deg, #301e04, #bd7611);

	position: relative;

	z-index: 1;
}

.tooltip:hover {
	z-index: 10;
}

.tooltip:hover .passive,
.tooltip:hover .quirk,
.tooltip:hover .power {
	visibility: visible;
	opacity: 1;
	transition: opacity 0.2s ease-in-out;
}

.card-container {
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: center;
	gap: 5px;
	
	perspective: 1000px;
	transform-style: preserve-3d;

}

.passive,
.quirk,
.power {
	visibility: hidden;
	opacity: 0;

	height: fit;
	width: 150%;

	top: -5px;  
	left: 105%;

	display: flex;
	flex-direction: column;
	align-items: center;

	border: 2px solid rgba(0,0,0,0.5);
	border-radius: 1.3rem;

	padding: 15px;

	transform: translateZ(0px);
	transition: transform 0.2s ease;

	position: absolute;

	z-index: 2;

	transition: opacity 0.2s ease;
}

.passive,
.power {
	background-image: linear-gradient(145deg, #301e04, #bd7611);
}

.quirk {
	background-image: linear-gradient(145deg, #822700, #bd7611);
}

.tooltip-title {
	font-family: Cuasigothic;
	font-size: 1.5rem;

	text-align: center;

	background: linear-gradient(white, gray);

	-webkit-background-clip: text;
	background-clip: text;
	
	color: transparent;
}

.tags {
	font-family: Arial;
	font-weight: bold;
	font-style: italic;
	color: rgba(255,255,255,0.8);

	text-align: center;
	
	margin-top: 5px;
}

.description {
	font-family: Arial;
	color: white;
	margin-top: 10px;
}

.credit {
	width: 100%;

	font-family: Arial;
	font-style: italic;
	text-align: right;
	color: rgba(255,255,255,0.6);

	margin-top: 5px;
}
</style>

<div class="infobox" >
<div class="infobox-title">Gate</div>

<br>
<img src="Gate Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

**Gate** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the creation of portals and the manipulation of space.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">POCKET</div>
		<div class="passive">
			<div class="tooltip-title">POCKET</div>
			<div class="tags">Passive</div>
			<div class="description">
				You can fit a compressed tear in space into a
piece of clothing that you are wearing.<br><br>
• You gain +1 KP<br><br>
• You can stow or retrieve items inside your pocket, which
can hold a combined total of items worth up to 3 KP.
Once inside, the items are stored in an extra
dimensional space and hidden and safe, no matter their
size. The pocket is attached to your clothes and if they
are destroyed, items inside pop out.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #822700, #bd7611);">
		<div class="tooltip-title">STROLL</div>
		<div class="quirk">
			<div class="tooltip-title">STROLL</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Once a scene, without spending a
psyche burst, you can attempt to
teleport yourself to a point in short
distance you can see (even just
partly) with enough space for you to
arrive by rolling 1d6. On a 3+, you
are successful. On a 1-2, you
teleport anyway to a point in range,
but the Admin tells you where you
end up.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #822700, #bd7611);">
		<div class="tooltip-title">RUMMAGE</div>
		<div class="quirk">
			<div class="tooltip-title">RUMMAGE</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Once a scene, you can spend 1 kp to pull a random item out of a
space that an item could be stored (clothing, suit pocket, in a
desk drawer, etc). This only works if you are not looking while
you’re pulling the item out. The item that comes out may not
necessarily logically fit the space, but comes out anyway. Roll
1d6, then the Admin picks something from the rolled list.<br><br>
1. Fountain pen, Live Grenade, Leather gloves, Lighter (small,
plain), Pack of cigarettes (2 missing), Phone charger<br><br>
2. Roll of coins, Crowbar, Stapler, Claw hammer, Camcorder (1 hr
tape), Chapstick<br><br>
3. Handgun (unloaded), two cigarettes, Faded photograph,
Instruction manual for building furniture (in Swedish), Map of the
area (folded, well used, in Swedish), Large pack of caramel
candies.<br><br>
4. Cell phone (10% battery), Thick sheathe of printer paper, Large
amount of cash, Full bottle of wine, Fire Axe, Huge box of nails<br><br>
5. Chewing Gum, Lipstick, Coffee Mug (novelty), Folded Letter, Hat
(situation appropriate), Clip of 9mm ammo for a handgun<br><br>
6. Useful key, Pocket Knife, Lighter (oversized, novelty), Bicycle
(foldable), Dictionary for translating Swedish, six sided die
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
</div>

<div class="section-background">
	<div class="section-header">
	Powers
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TEAR</div> 
		<div class="power">
			<div class="tooltip-title">TEAR</div>
			<div class="tags">Until Rest, Summon, CAT Range</div>
			<div class="description">
				You create a point in CAT range, and another
point within the same range, though you have
to be able to see both points when you use this
ability. The two points are connected by a slash
in the fabric of reality, a portal that can be
moved through and connects the two points as
though they were right next to each other.
Objects, beings, and forces up to ½ CAT in size
can freely move through the tear for the
duration, and momentum is preserved.<br><br>
You may gain or grant +1D when you or any ally
next acts to take advantage of this power.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PINCH</div>
		<div class="power">
			<div class="tooltip-title">PINCH</div>
			<div class="tags">Instant, Special Range</div>
			<div class="description">
				You can choose a single living being or object
you can see. The combined size of the object or
being and the distance you attempt to move
them must be CAT+2 or less. Roll PSYCHE if your
target is unwilling, only spending a psyche burst
on success. As long as you can see your target,
on at least one success, you can pinch space
between the two of you to move your target right
next to you. From the target’s perspective, they
don’t appear to move at all, but the world smears
around them. They ignore all physical
obstructions between them and you - as long as
you can see your target, they simply appear next
to you.<br><br>
You may gain or grant +1D when you or any ally
next acts to take advantage of this power.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BLOOM</div>
		<div class="power">
			<div class="tooltip-title">BLOOM</div>
			<div class="tags">1 Scene, Summon, Short</div>
			<div class="description">
				By splitting space in creative ways, you create a
number of controllable duplicates of any of your
limbs or hands equal to CAT+1 on any surfaces in
short range from you, emerging from a tear in
space. They are stuck in place and cannot move.
Gain or grant +1D when you or any ally next acts
to take advantage of this power:<br><br>
• You can control them like your normal limbs,
making action rolls through them and you have
normal sensation with them.<br><br>
• They can be placed on any surface, including
moving surfaces or living beings.<br><br>
• You take any stress they would take from your
actions made through them.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TRANSMISSION</div>
		<div class="power">
			<div class="tooltip-title">TRANSMISSION</div>
			<div class="tags">Instant, CAT+2 Range</div>
			<div class="description">
				Instantly move to any other area in CAT+2 range.
However, the Admin asks you the following
questions and rolls 1d6 per ‘no’ answer.<br><br>
• Are you familiar with your destination?<br><br>
• Can you see where you are going?<br><br>
• Are you calm and concentrated?<br><br>
On at least one ‘1’, you end up in a different
location nearby your destination, but the Admin
chooses where. On a double 1, you end up
somewhere else briefly before arriving at your
final destination. Not only are you off target, but
you also take 2d3 stress.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">MAZE</div>
		<div class="power">
			<div class="tooltip-title">MAZE</div>
			<div class="tags">Entire Hunt, Transmute, Adjacent, CAT Area</div>
			<div class="description">
				You rearrange an area equal to CAT around you,
causing the rearrangement of human built structures
in the area. Gain or grant +1D when you or any ally
next acts to take advantage of this power. You may:<br><br>
• create or remove doors and windows, or change
the existing arrangement of doors and windows<br><br>
• add corridors, or rearrange the floor plan of
rooms<br><br>
• change the direction of gravity inside of a room.
For example, you could make a wall the ‘floor’<br><br>
• make a room larger or smaller<br><br>
• arrange or remove the furniture inside a room any
way you like<br><br>
You cannot remove rooms entirely, make any room
smaller than a closet or larger than a ballroom, or
add anything that does not already exist in a building
other than corridors. This could cause a structure to
be bigger on the inside than outside.<br><br>
For each choice, the Admin rolls 1d6. If they roll at
least one ‘1’ the Admin gains one use of this power
against you at your current CAT and can activate it
any time they like.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>