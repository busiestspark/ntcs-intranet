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

	background: linear-gradient(145deg, #87946b, #e9ffb7);

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
	background-image: linear-gradient(145deg, #87946b, #e9ffb7);
}

.tooltip-title {
	font-family: Cuasigothic;
	font-size: 1.5rem;

	text-align: center;

	background: linear-gradient(gray, black);

	-webkit-background-clip: text;
	background-clip: text;
	
	color: transparent;
}

.tags {
	font-family: Arial;
	font-weight: bold;
	font-style: italic;
	color: rgba(0,0,0,0.8);

	text-align: center;
	
	margin-top: 5px;
}

.description {
	font-family: Arial;
	color: black;
	margin-top: 10px;
}

.credit {
	width: 100%;

	font-family: Arial;
	font-style: italic;
	text-align: right;
	color: rgba(0,0,0,0.6);

	margin-top: 5px;
}
</style>

<div class="infobox" >
<div class="infobox-title">Death</div>

<br>
<img src="Death Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Death** is an XK-Class [[Blasphemies|Blasphemy]].

It is concerned with the concept of death.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">PALE HORSE</div>
		<div class="passive">
			<div class="tooltip-title">PALE HORSE</div>
			<div class="tags">Passive</div>
			<div class="description">
				You can mildly control the life force of a
mundane human within close range. You can allow a
human on the brink of death to survive for much
longer than normal. Once per rest you may instantly
kill a human that you can touch.
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
		<img src="HD All Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FATE</div> 
		<div class="power">
			<div class="tooltip-title">FATE</div>
			<div class="tags">Instant, Far, 1/Mission</div>
			<div class="description">
				You may trigger this power as a reaction whenever you
or an ally in range fails their resist roll or suffers instant
death. Spend all of your remaining psyche bursts
(min 1). The Admin must offer a deal that would allow
the target to succeed their resist roll or avoid suffering
instant death. If your target agrees to the deal, it cannot
be broken. If they reject the deal, refund all psyche
bursts spent and gain +1D to your next roll.<br><br>
Some examples of deals that could be made are: (Your
name and face becomes known and unforgettable to the
wrong people. You are beset with a permanent and
debilitating affliction. Your body becomes weak and frail.
The next time you die will be brutal, painful, and
unavoidable, regardless of this power.)<br><br>
If the deal is taken, you allow the scene to play out as if
the target succeeded their resist roll or did not take their
last source of stress, remove 1 injury from them and
clear all stress on their current talisman, and gain 1d3
sin.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">ENTROPY</div>
		<div class="power">
			<div class="tooltip-title">ENTROPY</div>
			<div class="tags">Transmute, CAT Area, 1 Scene</div>
			<div class="description">
				You accelerate the flow of time for all
mundane beings and objects within a CAT
area around you. They rapidly age and
decay, altering them accordingly:<br><br>
- Small animals quickly die as their lifespan
plays out in seconds.<br><br>
- Humans reach old age or expire.<br><br>
- Objects deteriorate, rust, or malfunction.<br><br>
- Injuries may heal quickly or fester,
depending on their circumstances.<br><br>
Gain or grant +1D to the next action that
takes advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SAP</div>
		<div class="power">
			<div class="tooltip-title">SAP</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				Siphon the psychic life force of another living
being into yourself or others. Roll PSYCHE to
deal slashes to a target’s execution talisman,
removing a combined total amount of stress
from yourself or allies equal to 1+ the amount of
slashes dealt. Gain +1D for each question you
can answer ‘yes’ to (max of +3D):<br><br>
- Is your target severely injured?<br><br>
- Is the target scared, apprehensive, or
fearful?<br><br>
- Are you severely injured?<br><br>
If a human receives life force drained this way, it
can heal them of injuries and afflictions. This
may easily affect the parameters of rolls such as
difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">OBLITERATION</div>
		<div class="power">
			<div class="tooltip-title">OBLITERATION</div>
			<div class="tags">Instant, CAT Distance, 1/Scene</div>
			<div class="description">
				Remove a chunk of the living world from
existence of a size up to your CAT within range.
This completely erases light, heat, and organic
matter as if it had never existed in the first place.
Roll PSYCHE for creative uses of this power. This
may automatically kill mundane living beings if
caught within its area of effect.<br><br>
Gain or grant +1D to the next roll that takes
advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">EMPATHY</div>
		<div class="power">
			<div class="tooltip-title">EMPATHY</div>
			<div class="tags">Instant, CAT Area, 1/Rest</div>
			<div class="description">
				You may trigger this power in response to a
living being dying within close range of you,
making them the primary target of this ability.
Every mundane human within a CAT area dies
in the same way your original target died. A
decapitation results in everyone’s heads falling
off as if sliced. A lethal car accident would not
manifest additional cars, but crush and mangle
the bodies of other humans.<br><br>
If a supernatural being with 2 or less segments
remaining on it’s talisman is in this area, you
may make a PSYCHE roll. On a success they
die the same way your target did too.<br><br>
You may spend up to 2 additional psyche
bursts to increase the CAT of this power
by +1 per burst spent.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
