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

	background: linear-gradient(145deg, #8d8d8d, #FFFFFF);

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
	background-image: linear-gradient(145deg, #8d8d8d, #FFFFFF);
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
<div class="infobox-title">Conquest</div>

<br>
<img src="Conquest Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Conquest** is an XK-Class [[Blasphemies|Blasphemy]].

It is concerned with the concept of control.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">WHITE HORSE</div>
		<div class="passive">
			<div class="tooltip-title">WHITE HORSE</div>
			<div class="tags">Passive</div>
			<div class="description">
				During a mission, small
objects you have ownership over or
things you are holding in your hand
cannot be taken away from you by
any means.
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
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">COMMAND</div> 
		<div class="power">
			<div class="tooltip-title">COMMAND</div>
			<div class="tags">Curse, Far, 1 Scene</div>
			<div class="description">
				Issue a command to a CAT sized group of humans, or a
single supernatural being that can hear you. If this being
has a higher CAT than you, take 1d3+1 stress for each
level of difference. Choose one of the following
commands:<br><br>
<b>Freeze:</b> They stop what they are doing completely, and
become unable to move for a few moments until moved
or harmed by another living being.<br><br>
<b>Drop:</b> They abruptly drop everything they are holding.<br><br>
<b>Approach:</b> They approach you as quickly as possible.<br><br>
<b>Flee:</b> They attempt to escape from you as quickly as
possible.<br><br>
Gain or grant +1D to the next action that takes advantage
of this power. This may easily affect the parameters of
rolls such as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">ANCHOR</div>
		<div class="power">
			<div class="tooltip-title">ANCHOR</div>
			<div class="tags">Transmute, Short, 1 Scene</div>
			<div class="description">
				Create a zone of overwhelming pressure
equal to CAT area centered on a point
within range. Within this area your willpower
manifest as a great weight within the air,
pushing down on living beings within it:<br><br>
- Targets of your choice find it difficult to
move freely in the area.<br><br>
- No one, including yourself, can leave the
area without suffering 1d3+1 stress, or
1+½ CAT slashes as a cost.<br><br>
Gain or grant +1D to the next roll that takes
advantage of this power. This effect ends
early if you use another blasphemy power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TAME</div>
		<div class="power">
			<div class="tooltip-title">TAME</div>
			<div class="tags">Curse, Short, 1 Scene</div>
			<div class="description">
				You may select a number of traces whose
combined execution talisman is less than or
equal to your CAT+1, a drifter whose CAT is
lower than or equal to yours, or any number
of mundane animals within range. They now
treat you as if you were an ally or friend and
may follow or listen to simple commands.
This control breaks if you or an ally directly
harm the tamed creature(s).<br><br>
This may easily affect the parameter of rolls
such as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TERRITORY</div>
		<div class="power">
			<div class="tooltip-title">TERRITORY</div>
			<div class="tags">CAT+1 Area, 1 Scene, 1/Rest</div>
			<div class="description">
				Designate an area equal to your CAT+1 centered
on yourself as your “territory” for the rest of the
scene. Supernatural creatures instinctively know
that this area “belongs” to you for the duration.
Mundane humans may act in deference to you
instinctively or innately believe you possess
ownership of buildings or structures within this
area unless outright knowing otherwise.<br><br>
Gain or grant +1D to the next roll that takes
advantage of this power. This may easily affect
the parameters of rolls such as difficulty and
risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PESTILENCE</div>
		<div class="power">
			<div class="tooltip-title">PESTILENCE</div>
			<div class="tags">Curse, CAT+2 Area, 1/Mission</div>
			<div class="description">
				Designate an area equal to your CAT+1 centered
on yourself as your “territory” for the rest of the
scene. Supernatural creatures instinctively know
that this area “belongs” to you for the duration.
Mundane humans may act in deference to you
instinctively or innately believe you possess
ownership of buildings or structures within this
area unless outright knowing otherwise.<br><br>
Gain or grant +1D to the next roll that takes
advantage of this power. This may easily affect
the parameters of rolls such as difficulty and
risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
