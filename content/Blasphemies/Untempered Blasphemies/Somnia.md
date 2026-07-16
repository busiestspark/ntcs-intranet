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

	background: linear-gradient(145deg, #400040, #FF00FF);

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
	background-image: linear-gradient(145deg, #400040, #FF00FF);
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
<div class="infobox-title">Somnia</div>

<br>
<img src="Somnia Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Somnia** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the phenomenon of sleep.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">HYPNOS</div>
		<div class="passive">
			<div class="tooltip-title">HYPNOS</div>
			<div class="tags">Passive</div>
			<div class="description">
				You are immune to psychic phenomena
while you are asleep, and while resting if you
choose to sleep. Afflictions or other effects
cannot prevent you from resting or sleeping.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
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
		<div class="tooltip-title">SURREAL</div> 
		<div class="power">
			<div class="tooltip-title">SURREAL</div>
			<div class="tags">Transmute, CAT Area, 1 Scene</div>
			<div class="description">
				You dramatically change the landscape around you into visions
of your dreams, equal to CAT area. The features and landscape
within that area change into one of the following of your choice:<br><br>
• <b>Bliss:</b> Hard surfaces become soft and fluffy to the touch,
lights shine brighter, and supernatural beings may appear less
threatening than usual.<br><br>
• <b>Terror:</b> Objects of your choice become angular, solid, and sharp, the
sky and area darken, and supernatural beings may appear more
threatening than usual.<br><br>
• <b>Incongruence:</b> Hanging objects begin to droop, lights flicker, and
visible features of buildings or landscapes warp slightly.<br><br>
At any point during the scene, spend 1 additional psyche burst to make
these changes last until rest. These changes do not affect the abilities
and statistics of SINs, traces, or other enemies.<br><br>
This may easily affect the parameters of rolls, such as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">MANIFEST</div>
		<div class="power">
			<div class="tooltip-title">MANIFEST</div>
			<div class="tags">Summon, 1 Scene</div>
			<div class="description">
				Manifest a number of intangible constructs up to your CAT.
They can be objects, small animals, or creatures that you’ve
seen at least once since you’ve last slept or deployed. Their
combined size cannot exceed your CAT. These
manifestations are visible even to mundane humans.<br><br>
• You control their movements and actions, although they
cannot inflict harm on anything or anyone due to being
intangible.<br><br>
• They cannot move farther than a long distance away from
you or else they disappear.<br><br>
• They cannot intelligently vocalize, and make garbled
incomprehensible speech when attempting to do so.<br><br>
Spend 1 additional psyche burst to manifest these constructs
into the waking world, and extend the duration to Until Rest.
They become physically tangible even to those without
Grace, may block attacks, and may interact with the world
around them. They have a combined 1+CAT talisman for their
durability, which can take damage and be ticked up like an
execution talisman by opponents.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">HAZE</div>
		<div class="power">
			<div class="tooltip-title">HAZE</div>
			<div class="tags">Charm, Self, 1 Scene</div>
			<div class="description">
				Temporarily alter the state of tangibility of yourself
and things you are wearing or carrying. For the
duration of the scene you are still visible as normal,
but you cannot be harmed or touched through
physical means. Objects or creatures move through
you with ease, but you interact with walls and
objects normally.<br><br>
While in this state you may additionally touch an
object or structure that is equal to your CAT size
or smaller, and cause it to share the same traits
as you do, becoming intangible but not invisible.<br><br>
Gain or grant +1D to the next roll that takes
advantage of this power.<br><br>
If you take stress from supernatural phenomena,
this effect ends early.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SLEEPWALK</div>
		<div class="power">
			<div class="tooltip-title">SLEEPWALK</div>
			<div class="tags">Charm, Self, 1/Rest</div>
			<div class="description">
				You force yourself to fall asleep for the rest of the
scene, but allow your body to keep moving in
response to threats and stimuli. For the duration:<br><br>
• Your passive triggers, granting you immunity to
psychic phenomena, but you still take stress
from mundane sources such as rubble or
weapons, even if produced by a supernatural
creature. This does not count as taking a rest.<br><br>
• You can use blasphemy powers freely but roll
0D on actions that would physically exert you
with difficulty or effort.<br><br>
• You cannot move faster than a slow walk.<br><br>
• You can catch combatants or hostiles off guard
easily. Gain or grant +1D to the first roll that
takes advantage of this.<br><br>
You wake up early if you take an injury. If this
power ends at the end of the scene you gain an
additional rest die and must spend it immediately.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">LULL</div>
		<div class="power">
			<div class="tooltip-title">LULL</div>
			<div class="tags">Transmute, 1 Scene</div>
			<div class="description">
				You adjust the levels of waking for all creatures of
choice within a CAT area centered on yourself. Pick 1 of
the following effects which last for the duration:<br><br>
• <b>Sleep:</b> Creatures of your choice become lethargic
and tired, barely able to stay awake. Creatures on the
brink of death, humans and weaker traces will fall
asleep instantly.<br><br>
• <b>Wake:</b> Creatures of your choice become active and
energetic, unable to rest. Creatures who are drowsy or
fatigued are instantly awakened, and will find it
impossible to sleep.<br><br>
This may easily affect the parameter of rolls, such as
risk or difficulty.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
