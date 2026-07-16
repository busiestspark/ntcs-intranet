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

	background: linear-gradient(145deg, #491f16, #df5c42);

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
	background-image: linear-gradient(145deg, #491f16, #df5c42);
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
<div class="infobox-title">Wave</div>

<br>
<img src="Wave Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Wave** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of grace itself.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">WELLSPRING</div>
		<div class="passive">
			<div class="tooltip-title">WELLSPRING</div>
			<div class="tags">Passive</div>
			<div class="description">
				You have an overflowing reservoir of
psychic energy. You raise your psyche burst max
from 3 to 4. Your psychic signature is easily
detectable within ½ CAT distance to other
supernatural beings, drifters, traces, or even
other exorcists.
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
		<div class="tooltip-title">LIGHTHOUSE</div> 
		<div class="power">
			<div class="tooltip-title">LIGHTHOUSE</div>
			<div class="tags">Instant, CAT+1 Distance, 1/Scene</div>
			<div class="description">
				You burn the grace inside of your body to produce a
distinct and highly visible flash of psychic energy,
visible only to the graced. Anywhere within a few
seconds to a few minutes of the admin’s choice, a
drifter of the admin’s choice enters the scene. It may
initially be distracted or entranced by your psychic
signature, and not be immediately hostile to you for a
few moments before taking its usual course of action.<br><br>
This may also be used to create a signal of psychic
energy detectable by your allies who can see in your
general direction, as the flash reaches up to a CAT+1
distance away.<br><br>
Gain or grant +1D to the next action roll that takes
advantage of this happening. This power may easily
affect the parameters of rolls such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DRAIN</div>
		<div class="power">
			<div class="tooltip-title">DRAIN</div>
			<div class="tags">Transmute, CAT Area, 1 Scene, 1/Mission</div>
			<div class="description">
				Generate a massive sinkhole in the psychic sea
centered on you. Every drifter, trace or sin within a
CAT area temporarily dissipates as they slide into the
subconscious layer of the psychic gestalt. Beings with
psychic abilities caught in the area including you and
your allies are drained of your grace. Any action that
would expend a psyche burst or roll with PSYCHE is
hard by default until the end of the scene. Enemies
that rely on psychic abilities may find it hard to
generate meaningful damage through them.<br><br>
At the end of the scene, any supernatural being
removed by this ability quickly remanifests and may
be additionally aggressive or hostile to the user of this
power.<br><br>
This power may easily change the parameter of rolls
such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TIDE</div>
		<div class="power">
			<div class="tooltip-title">TIDE</div>
			<div class="tags">Transmute, 1 Scene</div>
			<div class="description">
				Produce a torrent of psychic energy centered on yourself
which flows in a certain direction up to a CAT area around
you. This affects creatures of your choice with a CAT equal
to or lower than yours. Objects with supernatural
properties or other grace-affected phenomena are also
affected by this if loose or unattached to other objects.
Pick one of the effects below:<br><br>
• <b>Flood:</b> Generate a wave of psychic energy that rushes
outwards. Attempting to get closer to you feels like
trying to push against a waterfall or river.<br><br>
• <b>Recede:</b> Amass a dense concentration of psychic energy
on yourself, pulling everything of your choice towards
you. Getting further away from you feels like trying to
escape powerful riptide or a whirlpool.<br><br>
This may easily affect the parameters of rolls such as
difficulty and risk. This effect ends early if you sustain
an injury, and attempting to focus on or using other
powers becomes hard.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PATTERN</div>
		<div class="power">
			<div class="tooltip-title">PATTERN</div>
			<div class="tags">Instant, 1/Rest</div>
			<div class="description">
				This power does not consume a psyche burst. You
may only use this power during a resting scene. The
phenomena of grace follows a subtle order which you
can perceive in greater detail than most. Impose a
stable and repeating wave-form upon all psychic
phenomena in the investigation zone, making it follow
that specific order. Actions taken by exorcists however
may change the path of causality and render
predictions unreliable You may ask the Admin one of
the following questions:<br><br>
• What psychic effect will happen when pressure
increases, and who or where will be the most
affected?<br><br>
• Where will a specific supernatural being go if left
undisturbed by the exorcists?<br><br>
• What is the nature of the next tension move that a
supernatural being will take against my allies?<br><br>
Gain or grant +1D when you or any ally next acts to
take advantage of each answer.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BREACH</div>
		<div class="power">
			<div class="tooltip-title">BREACH</div>
			<div class="tags">Charm, Instant</div>
			<div class="description">
				Part the waves of the psychic sea that
others find it hard to move through. You
may take a corresponding amount of stress
to physically move through, with no issue,
complication, or difficulty, any of the following
psychic phenomena as apart of any action
or for the duration of 1 action roll:<br><br>
<b>1 Stress:</b> Environmental psychic effects; An
ogres miasma; A psychic based attack (you
still take stress, hooks, and afflictions as
normally); Psychically induced weather etc.<br><br>
<b>2 Stress:</b> Boundaries of psychic domains; An
alternate entrance or exit to a sin’s palace
(but within a short distance of the original
entrance); An gate user’s maze; etc.<br><br>
<b>4 Stress:</b> Normally impenetrable psychic
barriers; A tension user’s stasis; a force
field; An object made entirely out of
grace; etc.<br><br>
You take +1 additional stress as a cost
when using this against effects caused
by creatures of a higher CAT than you.
You may reduce stress taken from
this ability by 1d3 for every additional
psyche burst you spend on it.<br><br>
This may easily effect the parameter
of rolls such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
