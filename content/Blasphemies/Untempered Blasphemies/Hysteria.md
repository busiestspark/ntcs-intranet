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
<div class="infobox-title">Hysteria</div>

<br>
<img src="Hysteria Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Hysteria** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of inhibition.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">DELIRIUM</div>
		<div class="passive">
			<div class="tooltip-title">DELIRIUM</div>
			<div class="tags">Passive</div>
			<div class="description">
				When you use a Hysteria power, you
may instead affect up to a CAT amount of
additional targets within ½ CAT range of the
target. When you do however, gain the
Apostasy hook before the power resolves.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #1cc37b">
		<div class="tooltip-title">APOSTASY</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #1cc37b">
			<div class="tooltip-title">APOSTASY</div>
			<div class="tags">Hook</div>
			<div class="description">
				You can gain this hook with your
passive or from powers. Some of your powers
may interact with this hook. When this hook fills
up, gain the agenda item “Do something risky,
regardless of the consequences”. If you did not
fulfill this agenda at the end of a session, take
1 sin. At the end of a mission roll 1d6. On a 4+
you may remove the agenda item and effect.<br><br>
If you fill this hook again after it has been filled
once and its agenda item hasn’t been removed,
you gain the following condition:<br><br>
<b>Psychosis:</b> Gain +1D on rolls when they are both
risky and hard. When the Admin rolls a 2 or lower
on the risk dice against your actions, it is always
much worse than expected, is treated as a 1,
and may trigger severe attacks from the Sin.<br><br>
Remove this condition after you rest or at the end
of the current mission.
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
		<div class="tooltip-title">HARLEQUIN</div> 
		<div class="power">
			<div class="tooltip-title">HARLEQUIN</div>
			<div class="tags">Curse, CAT Range, 1 Scene</div>
			<div class="description">
				You put on a convincing performance or rhetoric,
and distort your target’s sense of reality
temporarily. Select yourself, another living being,
or an object within range to be your Red Herring.
Select any number of the following effects:<br><br>
-The target can only pay attention to the Red
Herring.<br><br>
-The target finds the Red Herring hilarious.<br><br>
-The target lets down their guard and drops
what they are holding in the presence of the
Red Herring<br><br>
-The target moves closer to the Red Herring.<br><br>
-The target becomes unreasonably upset or
angry at the Red Herring.<br><br>
For every selection more than an amount equal
to ½ CAT, gain the Apostasy hook once. If you
use Delirium on this power it affects ALL beings
of choice within ½ CAT range of the target.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FUGUE</div>
		<div class="power">
			<div class="tooltip-title">FUGUE</div>
			<div class="tags">Curse, Close, 1 Scene</div>
			<div class="description">
				Reach into a target’s psyche and rip off their inhibition.
They lose control as you take off the mask. That
target’s current primary emotion causes them to go
into a frenzy, and for the rest of the scene they gain
your choice of up to ½ CAT of the following effects:<br><br>
-They can only choose to harm the closest target to
them.<br><br>
-They lose the ability to focus on specific or
complicated tasks.<br><br>
-They become painfully hot to the touch. This
cannot harm them.<br><br>
-They cannot be incapacitated and do not feel pain.<br><br>
-They begin to dance fervently and uncontrollably.<br><br>
This power may easily affect the parameters of rolls,
such as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">INFECT</div>
		<div class="power">
			<div class="tooltip-title">INFECT</div>
			<div class="tags">Transmute, Touch, Until Rest</div>
			<div class="description">
				Instill a lingering psychic virus into an object or living
being that you can detonate at any moment. While the
target you have touched is within CAT+2 range of
you, you know where they are and can see what is in
its immediate vicinity. If the target touches or is
touched by another potential target, you may spread
the infection to them by spending 1 psyche burst.<br><br>
To detonate the virus, select any of your powers with
the Curse or Transmute tags, and trigger them on valid
infected targets without consuming additional
psyche bursts (you cannot enhance powers
used this way through additional bursts,
passives, or other abilities).<br><br>
This power may easily affect the parameters of rolls,
such as difficulty and risk. Using Delirium on this
power grants and instantly fills the Apostasy hook.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SEETHE</div>
		<div class="power">
			<div class="tooltip-title">SEETHE</div>
			<div class="tags">Charm, Short, Until Rest, 1/Rest</div>
			<div class="description">
				This does not cost a psyche burst to use. You or a
target exorcist lets their roiling emotions flow through
them. The target then chooses to answer the following
questions as truthfully as they can:<br><br>
-Who has wronged you?<br><br>
-What do you hate most about humanity?<br><br>
-What do you deserve that was denied to you?<br><br>
If that exorcist directly acts upon any of their answers
they may gain 1 psyche burst after doing so, up to once
per answer.<br><br>
After gaining a psyche burst this way, roll PSYCHE.
On a failure, the selected target gains the Apostasy
Hook. You may not use Delirium to boost this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">OUTBURST</div>
		<div class="power">
			<div class="tooltip-title">OUTBURST</div>
			<div class="tags">Curse, CAT Range, 1 Scene</div>
			<div class="description">
				Pick a target within range. Roll PSYCHE if the target is
unwilling, only spending a psyche burst and taking the
effects of Delirium on a success (if used). The target
bursts into a cry of uncontrollable emotion. They cannot
move faster than a slow crawl from their current location
and find it difficult to take deliberate actions without
struggle. They also become loud and obvious to anything
else that can naturally detect them. (Graceless beings
will not hear or see a SIN under this effect).<br><br>
This effect ends on hostile targets if the target takes 3 or
more slashes on its execution talisman.<br><br>
Gain or grant +1D when you or any ally next acts to take
advantage of this power. This power may easily affect the
parameters of rolls, such as difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
