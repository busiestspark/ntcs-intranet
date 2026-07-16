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

	background: linear-gradient(145deg, #000000, #101010);

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
	background-image: linear-gradient(145deg, #000000, #101010);
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
<div class="infobox-title">Famine</div>

<br>
<img src="Famine Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Famine** is an XK-Class [[Blasphemies|Blasphemy]].

It is concerned with the concept of scarcity.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">BLACK HORSE</div>
		<div class="passive">
			<div class="tooltip-title">BLACK HORSE</div>
			<div class="tags">Passive</div>
			<div class="description">
				By maintaining eye contact with someone
for a few moments, you may instinctively know
what it is they desire most. Gain +1D on your next
roll to take advantage of this knowledge.
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
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SCARCITY</div> 
		<div class="power">
			<div class="tooltip-title">SCARCITY</div>
			<div class="tags">Transmute, CAT+2 Area, Until Rest, 1/Mission</div>
			<div class="description">
				This power does not cost a psyche burst to
use. Completely drain the world of resources
around you. Arsenals of weapons will be left
scarce, guns empty of ammunition. Shelves of
supplies grow emptier, commonplace items
mysteriously under stocked. Basic necessities
such as food, water, and electricity slowly
disappear and become difficult to find, with
only meager amounts left for those within the
area.<br><br>
Whenever pressure increases, the impact of
this power becomes more noticeable and
drastic, which may cause unrest or panic
among the mundane population within the
area of effect. As the effect moves with you,
parts of the investigation zone that are not
within the area of effect slowly recover their
resources over time.<br><br>
This may easily affect the parameter of rolls
such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DESICCATE</div>
		<div class="power">
			<div class="tooltip-title">DESICCATE</div>
			<div class="tags">Instant, CAT+1 Area</div>
			<div class="description">
				Completely dry out an area equal to
CAT+1 around you of its vitality. This does
not affect supernatural beings, but this
may kill plant life, remove all traces of
water, or turn mundane creatures into
dried out husks. This will leave humans
barely alive.<br><br>
Gain or grant +1D to the next action that
takes advantage of this power. This may
easily affect the parameters of rolls such
as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">EMPTY</div>
		<div class="power">
			<div class="tooltip-title">EMPTY</div>
			<div class="tags">Curse, Short, Until Rest</div>
			<div class="description">
				Cause any number of living beings equal to
your CAT in range to experience extreme
anhedonia, a lack of ability to experience
pleasure, joy, or satisfaction. This easily
alters their state of mind and causes
individuals to overexert, overindulge, or even
give up on most actions they would have
otherwise taken. While emptied, living beings
become more susceptible to the influence of
others. They may also break or render
ineffective abilities and supernatural
phenomena that manipulate emotions.<br><br>
Gain or grant +1D to the next action that
takes advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FLOCK</div>
		<div class="power">
			<div class="tooltip-title">FLOCK</div>
			<div class="tags">Summon, CAT Distance, Instant</div>
			<div class="description">
				Call upon mundane living beings within range
that travel together such as pests, crows, rats,
foxes, insects, or other creatures of your choice.
Then, select a target.<br><br>
These animals will attempt to devour your target,
ripping off flesh, skin, or other pieces of
consumable organic material until they have
reached bone. They flee shortly after. When you
use this power, roll PSYCHE and answer the
following questions, gaining +1D for each ‘yes’
answer (only spending a Psyche Burst on
success):<br><br>
- Are you outside and near nature?<br><br>
- Is your target wounded or bleeding?<br><br>
This may easily affect the parameters of rolls such
as difficulty and risk. This power cannot be used if
your flock cannot reach the target, such as being
in an enclosed or sealed space.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">AMICIDE</div>
		<div class="power">
			<div class="tooltip-title">AMICIDE</div>
			<div class="tags">Curse, 1 Scene, 1/Rest</div>
			<div class="description">
				Induce uncontrollable cannibalism and
starvation on a group of creatures within
range, causing them to devour each other
almost immediately as this power is used.
Traces may turn on one another or mundane
humans may be driven to consume each
other as well. This may help neutralize a
conflict scene groups of minor enemies or
provide a flashy and violent distraction.<br><br>
Gain or grant +1D to the next action that
takes advantage of this power. This may
easily affect the parameters of rolls such as
difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
