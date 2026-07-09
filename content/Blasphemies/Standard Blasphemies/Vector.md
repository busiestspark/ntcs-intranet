---
tags:
  - Blasphemy
image: "[[Vector Card.png]]"
blsphID: "4"
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
<div class="infobox-title">Vector</div>

<br>
<img src="Vector Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

**Vector** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of gravity and velocity.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">BRAKE</div>
		<div class="passive">
			<div class="tooltip-title">BRAKE</div>
			<div class="tags">Passive</div>
			<div class="description">
				Automatically remove velocity from all
projectiles that would hit you, taking -1 stress from
them.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #822700, #bd7611);">
		<div class="tooltip-title">AXIS</div>
		<div class="quirk">
			<div class="tooltip-title">AXIS</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Your powers rely on rotational velocity.<br><br>
<b>Inscribe Axis:</b> The Fling and Current powers
from this blasphemy moving things either
clockwise or counter clockwise around you or
a point you choose in hand’s reach, instead of
in a straight line. The range of these abilities
instead becomes the radius of this circular
path.<br><br>
<b>Holy Chakra:</b> You may roll 1d6 when an object
or projectile equal or lower than your CAT
would impact you. If you roll a 4+, it instead
orbits harmlessly around you and away from
you, missing you and inflicting a max of 1
stress. If successful, lose the use of this
passive until you rest.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #822700, #bd7611);">
		<div class="tooltip-title">RAIL</div>
		<div class="quirk">
			<div class="tooltip-title">RAIL</div>
			<div class="tags">Quirk</div>
			<div class="description">
				When moving, you automatically increase
your own velocity. All your own movement
(not movement granted to others), is +1
CAT higher, including movement without
your powers. You can ‘skate’ on a small
bubble of vectorized air underneath your
feet, allowing you to move across water or
slippery surfaces.<br><br>
However, none of your powers work if you
are unable to move while using them.
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
		<div class="tooltip-title">FLING</div> 
		<div class="power">
			<div class="tooltip-title">FLING</div>
			<div class="tags">Instant, Adjacent</div>
			<div class="description">
				With a touch, you can imbue velocity into
yourself or another object or living being and
send it flying. The combined size of the object
or being and the range you send them must
equal your CAT+2 or less. Once sent flying, the
direction of your target cannot be changed.<br><br>
You can alternately remove all velocity by
touching an object or person of CAT+2 size,
bringing it to a complete stop.<br><br>
Roll PSYCHE for this power’s effects, including
any harm inflicted, and only spend a psyche
burst on at least one success.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">LIFT</div>
		<div class="power">
			<div class="tooltip-title">LIFT</div>
			<div class="tags">1 Scene, Charm, Self</div>
			<div class="description">
				You reverse gravity’s effect on yourself and a CAT
sized group of other exorcists or humans with a
low but constant Vector effect. For this scene, any
affected gain the following benefits:<br><br>
• you can run, walk, or climb up vertical surfaces<br><br>
• you can slow your fall at will, and you cannot
take harm from falling<br><br>
• you can glide a distance equal to CAT range.
You must start at height to gain this benefit<br><br>
This power may easily affect the parameters of
rolls, such as difficulty and risk
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CURRENT</div>
		<div class="power">
			<div class="tooltip-title">CURRENT</div>
			<div class="tags">Until Rest, Transmute, CAT+2 Range</div>
			<div class="description">
				You create a weaker, but persistent Vector
force in an area that lasts until you rest. It
creates a line that goes about CAT+2 range
in length and covers about the width of a
street. It pushes constantly in one direction
(including up or down) like a strong wind.
Allies moving in that direction gain +1D on
actions to move with the current. Anything
moving against that direction struggles, and
anything falling falls slowly. It becomes hard
for allies to move against the current, and
actions taken against anyone trying to
struggle against the current gain +1D. You
can dismiss this effect at will.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BULLET</div>
		<div class="power">
			<div class="tooltip-title">BULLET</div>
			<div class="tags">Instant, CAT+1 Range</div>
			<div class="description">
				You can imbue strong bursts of velocity into
the air at your fingertips, creating pressurized
air bullets that hit with extreme force. Roll
PSYCHE for its effects, only spending a
psyche burst on success.<br><br>
• Gain +1D when making shots from an
elevated position.<br><br>
• Gain +1D when making shots to disarm,
distract, or disable instead of harm.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FINESSE</div>
		<div class="power">
			<div class="tooltip-title">FINESSE</div>
			<div class="tags">Instant, CAT Range</div>
			<div class="description">
				<b>Passive:</b> You may finely manipulate threads of
force to perform fine motor skills you could
perform with your hands at ½ CAT range, such as
opening doors, picking up objects, or even skills
like typing on a keyboard, etc. Roll a relevant skill
such as interfacing for this.<br><br>
• You have to be able to see your target, even if
it’s far away. However, you can perform this
manipulation even if your path to the target is
blocked, such as if you could see it through a
window, etc.<br><br>
• You can pick up objects and move them around
through the air but they cannot be any bigger
or heavier than a laptop or a full briefcase.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>