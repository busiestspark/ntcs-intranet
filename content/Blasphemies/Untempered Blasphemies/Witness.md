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

	background: linear-gradient(145deg, #9e9e00, #feff01);

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
	background-image: linear-gradient(145deg, #9e9e00, #feff01);
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
<div class="infobox-title">Witness</div>

<br>
<img src="Witness Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Witness** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the clarity of sight and memory.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">XANTHOUS</div>
		<div class="passive">
			<div class="tooltip-title">XANTHOUS</div>
			<div class="tags">Passive</div>
			<div class="description">
				Your memories cannot be erased or manipulated
by effects or powers outside of your own. You accurately
recall everything you have seen and heard
over the last number of months equal
to your CAT.
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
		<div class="tooltip-title">TRUESIGHT</div> 
		<div class="power">
			<div class="tooltip-title">TRUESIGHT</div>
			<div class="tags">Charm, Self, 1 Scene</div>
			<div class="description">
				For the rest of the scene, you see things for what
they truly are. This may even allow you to see the
faint outline of a Whisper’s Shadow, the opening
or entrance to a palace, and hidden
compartments or entrances. Additionally, when
you become aware that someone has told a lie,
you may ask one of the following questions
which that person must answer truthfully:<br><br>
• Why did you lie?<br><br>
• Who do you trust?<br><br>
• What will it take for you to tell the truth?<br><br>
Gain or grant +1D to yourself or an ally when
taking advantage of this power while it is in effect.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">GLARE</div>
		<div class="power">
			<div class="tooltip-title">GLARE</div>
			<div class="tags">Summon, Short, 1 Scene</div>
			<div class="description">
				You create a source of ethereal blinding light
at any point within range, no larger than your
CAT-1 in size. This may be disorienting to
living beings that rely on sight, and it appears
to the graceless as well.<br><br>
Wherever the light touches, you have the
ability to perceive in great detail, from the
inside of dark cracks or slits in walls and
windows, to the texture of surfaces and skin.
You may choose to move the source of light at
a pace no faster than your walking speed, and
it can be concealed by mundane opaque
materials such as within a pocket or under a
cup.<br><br>
This power may easily affect the parameters of
rolls, such as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SCATHE</div>
		<div class="power">
			<div class="tooltip-title">SCATHE</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				Condense your vast and precise perception of the
psychic sea into a boiling hot pulse of energy,
centered on a target’s mind. A creature must be
able to perceive you in some way for you to target
them. This is instantly fatal to humans,
evaporating their brains upon triggering this
power and leaving nothing but smoke inside of
their skulls.<br><br>
When targeting supernatural beings, roll PSYCHE
for damage. In a conflict scene, gain +1D on this
roll for every time the Sin’s reaction has been
countered through trauma questions. If rolling 3+
successes, you stagger the target preventing
them from taking a reaction this turn.<br><br>
You cannot target a creature with this more
than once in the same scene.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SANCTIFY</div>
		<div class="power">
			<div class="tooltip-title">SANCTIFY</div>
			<div class="tags">Transmute, CAT+1 Area, Until Rest</div>
			<div class="description">
				You must spend 2 minutes of focused concentration
to use this power before it activates. Sanctify an area
up to CAT+1 centered on a point you touch. This
effect does not move with you. For the duration of the
effect you now know:<br><br>
• Who or what is within that area, although not
their exact location or specific details.<br><br>
• When something or someone enters or leaves,
but not from where within range they leave.<br><br>
• The general location of something you have
intimate knowledge of if it is in that area. (An
object you have handled frequently, a fellow
Exorcist, a SIN you have fought and know all
trauma questions for, etc.)<br><br>
When you search for someone or something in the
area that you do not have intimate knowledge of,
roll PSYCHE. On a success you know where it is.
<b>They discover where you are as well.</b>
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">REDACT</div>
		<div class="power">
			<div class="tooltip-title">REDACT</div>
			<div class="tags">Transmute, CAT+1 Range, Until Rest</div>
			<div class="description">
				Remove one piece of information from the minds of
everything and everyone within range temporarily.
You may redact:<br><br>
• A name.<br><br>
• A location.<br><br>
• A certain individual’s action.<br><br>
• A death.<br><br>
• Or any other simple piece of information
that can be mentioned in one sentence,
at the approval of your Admin.<br><br>
Creatures under the effect of this have this piece
of information seamlessly blocked in their mind,
unable to recall or identify the piece of missing
information. Gain or grant +1D to yourself or an
ally when taking advantage of this power while
it is in effect. This effect ends early if you take an
injury. This may temporarily render a trauma
answer unusable for the duration.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
