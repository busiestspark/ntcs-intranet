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
<div class="infobox-title">Roar</div>

<br>
<img src="Roar Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Roar** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of sound.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">SENSITIVE</div>
		<div class="passive">
			<div class="tooltip-title">SENSITIVE</div>
			<div class="tags">Passive</div>
			<div class="description">
				You can hear the minute details of everything
you focus on up to CAT-1 distance from you, ranging
from the pace of a heartbeat to the weight of footsteps.
Some of your powers grant you the Tinnitus hook.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #feff01">
		<div class="tooltip-title" style="background: linear-gradient(white, gray); -webkit-background-clip: text; background-clip: text;">TINNITUS</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #feff01">
			<div class="tooltip-title" style="background: linear-gradient(white, gray); -webkit-background-clip: text; background-clip: text;">TINNITUS</div>
			<div class="tags" style="color: rgba(255,255,255,0.8);">Hook</div>
			<div class="description" style="color: white">
				When this hook fills up, gain the
Tinnitus condition:<br><br>
You become deaf. You cannot use any of your
Roar powers and actions that rely on hearing
without teamwork or set-up are always hard.
Remove this condition at the end of the scene.
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
		<div class="tooltip-title">CHORUS</div> 
		<div class="power">
			<div class="tooltip-title">CHORUS</div>
			<div class="tags">Charm, Long, 1 Scene</div>
			<div class="description">
				Change the point of origin for the sounds of objects up
to CAT size or less and living beings within range.
Select one of the following effects which lasts for the
rest of the scene:<br><br>
- <b>Harmonize:</b> Pick a living being or object within
range. A living being loses the ability to speak
freely. Instead, whatever you say is also projected
from their mouth using their voice, as if they were
mimicking you. An object now projects your voice
while you're speaking, as if it were a speaker.<br><br>
- <b>Swap:</b> Swap the “sounds” of any two targets. A gun
and a window as targets would make the window
produce a gunshot when slammed shut, and the gun
make the sound of a window slamming when fired. A
dog and a plastic bag may cause the bag to bark
when shaken, or the dog to only make light rustling
sounds through its mouth.<br><br>
Gain or grant +1D when you or an ally next acts to
take advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TUNE</div>
		<div class="power">
			<div class="tooltip-title">TUNE</div>
			<div class="tags">Transmute, CAT Area, 1 Scene</div>
			<div class="description">
				Forcibly alter the vibrations of the world in a CAT area centered on yourself.
While this effect is active you may apply any of the following effects once to a
living target or object of CAT size or smaller within it:<br><br>
- <b>Volume:</b> Completely silence a living being or object that produces sound
such as machinery, instruments, or weapons for the duration. You can also
instead choose to increase the volume of any living being or previously
mentioned objects to up to three times its original volume.<br><br>
- <b>Dissonance:</b> Exert powerful vibrations into a living being or object, causing it
to seize up and shake violently. This may disrupt, damage, or hinder targets.<br><br>
- <b>Echo:</b> You force a living being to repeat the last phrase or sound it made on
a loop. You can also select any sound produced within this area and play it
on loop, such as the sound of something falling to the floor or a gunshot.<br><br>
Every time you trigger an effect beyond the first, gain the Tinnitus hook. Gain
or grant +1D when you or an ally next acts to take advantage of any of these
effects. This may easily change the parameter of rolls such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CONCUSS</div>
		<div class="power">
			<div class="tooltip-title">CONCUSS</div>
			<div class="tags">Instant, 1/Scene</div>
			<div class="description">
				Create an amplified sound that causes a concussive blast
either centered in a CAT area around yourself OR in a
line equal to your CAT range. This blast of sound
shatters glass and fragile materials, deafens beings that
it hits for a few seconds, and is mildly harmful to
structures or buildings. Roll PSYCHE for its effects, only
spending a psyche burst on a success. Then choose one
of the following on a success:<br><br>
• The blast is particularly harmful to structures,
destroying the integrity of buildings and objects in
range.<br><br>
• The blast is particularly debilitating to living beings,
who become deaf until the end of the scene.<br><br>
• The blast is particularly harmful to one being
caught in the blast, and becomes concussed, unable
to take their next reaction. This may also instantly kill
a mundane human.<br><br>
You may take an additional choice by taking the Tinnitus
hook.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">RESONATE</div>
		<div class="power">
			<div class="tooltip-title">RESONATE</div>
			<div class="tags">Charm, 1 Scene</div>
			<div class="description">
				Temporarily improve your hearing
capabilities and increase the range of your
passive to CAT+1 for the rest of the scene.
You may also select certain phrases, sounds,
or keywords that when made or spoken
within this range, you gain the ability to
automatically focus on. You also naturally
echolocate, allowing you to perceive shapes,
forms, or dimensions within that range while
using this passive.<br><br>
You may gain or grant +1D when you or any
ally next acts to take advantage of this
power. This may easily affect the parameters
of rolls such as difficulty or risk. If you are the
target of a particularly powerful sound based
attack, you take the Tinnitus hook and end
this power early.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">RING</div>
		<div class="power">
			<div class="tooltip-title">RING</div>
			<div class="tags">Transmute, CAT+1 Distance, 1 Scene</div>
			<div class="description">
				Within this range you can manipulate the way you and
your allies' voices travel for the rest of the scene.<br><br>
At will, you may also allow anyone to hear the voices
of you or your allies in range that they would not
normally be able to hear through distance or physical
obstacles otherwise as long as they are also within
range. This does not work on deafened individuals or
those in hermetically sealed locations. You only need
to know what a recipient sounds like in order to ring
them. You may increase the CAT range of this power
by +2 by taking the Tinnitus hook.<br><br>
Gain or grant +1D to yourself or an ally when taking
advantage of this power while it is in effect.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
