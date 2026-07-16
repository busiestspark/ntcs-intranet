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
<div class="infobox-title">Severed</div>

<br>
<img src="Severed Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Severed** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the power to copy oneself.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SPLIT</div>
		<div class="passive">
			<div class="tooltip-title">SPLIT</div>
			<div class="tags">Passive</div>
			<div class="description">
				At any point during a mission you may spend a
psyche burst to Split, creating an exact copy of yourself,
with all the clothes you are wearing (but not objects you
are holding), originating from your body. You may also
split as a reaction to taking stress from physical harm that
involves cutting, slicing, or slashing, reducing stress taken
by 2.<br><br>
While split you may not choose to split again until you
become whole.<br><br>
• Both copies share the same statistics and
exorcist sheet. If one of you suffers instant
death or overflow, you both do.<br><br>
• You control both bodies which can act
independently of each other, each taking their
own action in an investigation or conflict
scene but receiving all consequences as
normal (risk die). All stress you receive during
a conflict scene while split is increased by +1.<br><br>
• You always perceive everything from both
bodies at once.<br><br>
• Items from KP are shared between both
versions of yourself, and it is not a
duplicated resource.<br><br>
• Both of you must choose to rest at the same
time, and become whole after doing so,
waking up in the body of the Admin’s choice
if separated.
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
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">MULTIPLY</div> 
		<div class="power">
			<div class="tooltip-title">MULTIPLY</div>
			<div class="tags">Instant, Touch</div>
			<div class="description">
				Touch a mundane object in range that you can
hold and carry with one hand. Create a number
of copies of that object equal to your CAT that
spill out from the original. These copies are
indistinguishable from the original and maintain
all the same properties as the original.<br><br>
When you rest, all additional versions of the
object disappear, and you may decide which
version is the original copy if you are holding at
least one of them. Otherwise the Admin decides.<br><br>
This power may easily affect the parameter of
rolls, such as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PARADE</div>
		<div class="power">
			<div class="tooltip-title">PARADE</div>
			<div class="tags">Summon, 1 Scene</div>
			<div class="description">
				You can only activate this power when whole.
Create up to ½ CAT+3 less powerful copies of
yourself which can only move together and
follow basic 1 word commands. They cannot
use any of your abilities or powers but can pick
up mundane objects. Roll PSYCHE for creative
uses of this power (damage rolled this way
counts as mundane). Your parade has a 1/2
CAT+3 talisman for their durability, which can
take damage and be ticked up like an execution
talisman by opponents, each copy evaporating in
a fine pink mist when destroyed. They all
evaporate regardless at the end of the scene.<br><br>
You may consume additional psyche bursts with
this power. For every additional burst add 1d3
more members to your parade and add 1d3+1
segments to their durability talisman.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CLEAVE</div>
		<div class="power">
			<div class="tooltip-title">CLEAVE</div>
			<div class="tags">Transmute, Touch, 1 Scene</div>
			<div class="description">
				Harmlessly part an object or creature of CAT size or
smaller into individual pieces. You may “cleave” a
specific portion or part of your target OR yourself up
to 1d3 times, which cannot separate it into more than
4 pieces. Roll PSYCHE if targeting an unwilling
creature, only spending a psyche burst on a success.
Objects divided this way may cease to function
properly, but supernaturally maintain their integrity
and structure. Creatures divided this way do not feel
pain and maintain control and function over their
individual parts. This control may be difficult for
creatures caught unaware by this power.<br><br>
Cleaved parts of objects and creatures slowly float
back together at the end of a scene unless otherwise
prevented through purposeful separation or
otherwise.<br><br>
This power may easily affect the parameter of rolls,
such as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PASS</div>
		<div class="power">
			<div class="tooltip-title">PASS</div>
			<div class="tags">Instant, 1/Scene</div>
			<div class="description">
				This power does NOT take a psyche burst.
You must be split to use this power.
Once per scene you may immediately
transfer any object you are holding and
carrying into the hands of your other. This
ignores any distance or otherwise
impossible obstacles between you and
your other.<br><br>
Gain or grant +1D to the next
roll that takes advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">ABEL</div>
		<div class="power">
			<div class="tooltip-title">ABEL</div>
			<div class="tags">Charm, Instant, 1/Scene</div>
			<div class="description">
				When you use this ability while split, instantly
kill one version of yourself of choice, leaving
the other version alive. You may choose how
this death manifests whether it is passing out,
wounds appearing on the body, or instant
combustion, which cannot deal physical harm
to other creatures.<br><br>
If you use this ability currently under the effect
of cleave or parade while whole, or any other
blasphemy ability where you produce a copy of
yourself, you may choose to regenerate from
one cleaved portion of yourself or one copy by
killing the rest of your portions harmlessly.<br><br>
Gain +1D to your next roll that takes advantage
of this power. You may not choose to split until
after you rest.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
