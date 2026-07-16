---
tags:
  - Blasphemy
unlisted: true
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

	background: linear-gradient(145deg, #500000, #FF0000);

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
	background-image: linear-gradient(145deg, #500000, #FF0000);
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
<div class="infobox-title">War</div>

<br>
<img src="War Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**War** is an XK-Class [[Blasphemies|Blasphemy]].

It is concerned with the concept of battle.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">RED HORSE</div>
		<div class="passive">
			<div class="tooltip-title">RED HORSE</div>
			<div class="tags">Passive</div>
			<div class="description">
				All weapons you are wielding are considered
to have a +1 bonus to their current CAT score. You
can telekinetically pull loose weapons not being
stored, held, or affixed to a surface within a close
distance to your hands.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #FF0000">
		<div class="tooltip-title" style="background: linear-gradient(white, gray); -webkit-background-clip: text; background-clip: text;">XK CLASS</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #FF0000">
			<div class="tooltip-title" style="background: linear-gradient(white, gray); -webkit-background-clip: text; background-clip: text;">XK CLASS</div>
			<div class="tags" style="color: rgba(255,255,255,0.8);">Note</div>
			<div class="description" style="color: white">
				You cannot take this blasphemy during initial character creation. Taking a power from this blasphemy for the first time takes 2 advances instead of 1.
			</div>
			<div class="credit" style="color: rgba(255,255,255,0.6);">From the Harpocrates Dossier 2.2</div>
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
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SPEAR</div> 
		<div class="power">
			<div class="tooltip-title">SPEAR</div>
			<div class="tags">Instant, 1/Scene</div>
			<div class="description">
				Become a weapon of mass destruction and
propel yourself at mach speed up to a CAT
distance. You break through walls, objects,
structures, and damage all creatures you
launch yourself into or through this way. You
do not take any physical damage while using
this power. Roll PSYCHE to determine
damage, and you may damage multiple
creatures at once this way.<br><br>
You may spend additional psyche bursts on
this power to increase the CAT distance you
travel by +1 per additional burst spent.<br><br>
Gain or grant +1D to the next roll that takes
advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">WEAPON</div>
		<div class="power">
			<div class="tooltip-title">WEAPON</div>
			<div class="tags">Transmute, Touch, 1 Scene</div>
			<div class="description">
				Turn any mundane object into a weapon of your choice. You
decide its shape, form, and size, but it always has a CAT equal
to yours. It has an execution talisman of your ½ CAT+2 before
it is destroyed, may be targeted by enemies separately, and it
takes 1 stress every time it is used for an attack. It is
considered supernatural but does not gain bonus dice from
set up and teamwork or outside abilities other than divine
agony. Roll PSYCHE when choosing to attack with it. It gains
+1D bonus dice for each of the following question you can
answer yes to:<br><br>
- Is this object important to someone else?<br><br>
- Is this object important to you?<br><br>
- Is this object traditionally dangerous, powerful, or of note?<br><br>
The object is gone forever once the weapon is destroyed.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DETONATE</div>
		<div class="power">
			<div class="tooltip-title">DETONATE</div>
			<div class="tags">Instant, CAT Distance, 1/Scene</div>
			<div class="description">
				Select any point within CAT distance that you
can see. You make it explode in an area up to
your CAT+1, at a minimum of CAT 2. This
blast will always reach its maximum area size
by default. Roll PSYCHE to successfully
contain the blast to any area smaller than
CAT 3, spending a psyche burst regardless of
success or failure. Deal a number of slashes
equal to your ½ CAT + 1. If you or another
Exorcist are caught in this blast, they take
slashes dealt as stress.<br><br>
The explosion is powerful, bright, and loud. It
evaporates most structures and mundane
objects, and is instantly fatal to humans. If
this causes considerable and substantial
damage, your Admin may dock any amount
of scrip for clean up.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TACTICUS</div>
		<div class="power">
			<div class="tooltip-title">TACTICUS</div>
			<div class="tags">Charm, 1/Rest</div>
			<div class="description">
				This power does not cost a psyche burst to
use. Wage a simulacrum of war within your
mind of the current battle that lets you predict
your opponent’s next move. Select a number of
combatants in the same scene as you. You ask
your Admin a question which they must
answer truthfully:<br><br>
- Can I win this fight?<br><br>
If the answer is a yes, gain +1D on the first
action you take this scene to inflict violence or
harm. Regardless of the answer, you roll the
risk die alongside the Admin when you take
your turn up to a number of times equal to
your ½ CAT and take the higher number,
having seen all possibilities.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BELLUM</div>
		<div class="power">
			<div class="tooltip-title">BELLUM</div>
			<div class="tags">CAT+1 Area, 1 Scene, 1/Rest</div>
			<div class="description">
				Fill living beings around you within a CAT+1
area with extreme anger and the urge to
commit violence. All beings of your choice
within range are filled with this roiling
emotion and may use it to attack each other,
finding it difficult to differentiate friend from
foe. For the duration all creatures under the
effect of this rage also have their physical
CAT increased by 1, even if they are
mundane in nature.<br><br>
This may easily affect the parameter of rolls,
such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
