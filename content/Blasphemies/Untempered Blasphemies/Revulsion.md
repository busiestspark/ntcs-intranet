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

	background: linear-gradient(145deg, #083622, #1cc37b);

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
	background-image: linear-gradient(145deg, #083622, #1cc37b);
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
<div class="infobox-title">Revulsion</div>

<br>
<img src="Revulsion Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Revulsion** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the power of repulsion.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">PUTRID</div>
		<div class="passive">
			<div class="tooltip-title">PUTRID</div>
			<div class="tags">Passive</div>
			<div class="description">
				When within arm’s reach of you, all other
Exorcists may not use Set-Up or Teamwork to assist
you. You are immune to effects that would force you
to psychically or physically connect with another
being.<br><br>
If half or more of your sin boxes are slashed,
supernatural beings may avoid actions or movement
that puts them within a close distance of you.
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
		<div class="tooltip-title">ISOLATE</div> 
		<div class="power">
			<div class="tooltip-title">ISOLATE</div>
			<div class="tags">Curse, Short, Until Rest</div>
			<div class="description">
				Temporarily transfer your psychic antipathy
to another target. For the duration of this
effect,nullify the effects of the Putrid
passive. All other living beings perceive the
target as disgusting while within CAT range
of them, and will not listen to or willingly
assist them while within that range.<br><br>
This may cause Cultists to waver in their
faith, Myrmidons to attack the wrong
targets, or humans to start ostracizing
another individual.<br><br>
Whenever the tension increases, roll
PSYCHE. On a failure, this effect ends early.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SPEW</div>
		<div class="power">
			<div class="tooltip-title">SPEW</div>
			<div class="tags">Curse, Instant, Close, 1/Scene</div>
			<div class="description">
				You curdle the mental state of a being who can
perceive you. Force a target within range to forcibly
eject things from within them that they cannot
stomach, either physically or mentally. They are said
aloud in a forced and frantic way, as if vomiting, if it
is a mental attribute. Select a number of the
following equal to your ½ CAT:<br><br>
- The contents of their stomach.<br><br>
- A guilty memory or secret.<br><br>
- Worst fear and/or what they find the most
disgusting.<br><br>
Gain or grant +1D when you or any ally next acts to
take advantage of each answer.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CONTAMINATE</div>
		<div class="power">
			<div class="tooltip-title">CONTAMINATE</div>
			<div class="tags">Transmute, CAT Range, 1 Scene</div>
			<div class="description">
				You ruin the sanctity of a space for living beings,
making it feel agonizingly unclean. Select a
CAT+1 area within range. Living beings of your
choice no longer feel comfortable in that space,
hesitant to touch anything, including the floors
or walls. This may hinder the movement of a SIN
or prevent humans from wanting to enter certain
locations.<br><br>
Gain +1D when you or an ally take advantage of
this power while it is in effect.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">STENCH</div>
		<div class="power">
			<div class="tooltip-title">STENCH</div>
			<div class="tags">Transmute, Instant</div>
			<div class="description">
				Imbue a mundane CAT-sized or smaller object
with an intolerable field of antipathy for just a
moment, affecting even other objects in motion.
You may do this as a part of another action. This
affects everyone except yourself and other
Revulsion users. Roll PSYCHE to resolve the
effect of this, only expending a psyche burst on
a success. This could attempt to do any of the
following:<br><br>
- Cause a weapon attack to drive something
away from the battle in a rout.<br><br>
- Make everyone run away from or leave behind
an object.<br><br>
- Suddenly cause a vehicle to stop in front of an
object.<br><br>
- Prevent bullets from being loaded into a gun
for a moment.<br><br>
You may gain or grant +1D when you or any ally
next acts to take advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">OVERWHELM</div>
		<div class="power">
			<div class="tooltip-title">OVERWHELM</div>
			<div class="tags">Curse, CAT Range, 1 Scene</div>
			<div class="description">
				Assault the senses of a target within range on both
a physical and mental level. Pick two of the
following:<br><br>
- Sight<br>
- Smell<br>
- Hearing<br>
- Touch<br>
- Taste<br><br>
Until the end of the scene, the target cannot rely on
the selected senses, overwhelmed by an influx of
adverse sensations. This distorts their senses but
does not remove them entirely.<br><br>
You may gain or grant +1D when you or any ally
next acts to take advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
