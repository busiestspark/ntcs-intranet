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

	background: linear-gradient(145deg, #1b6163, #3eaaac);

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
	background-image: linear-gradient(145deg, #1b6163, #3eaaac);
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
<div class="infobox-title">Erudition</div>

<br>
<img src="Erudition Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Erudition** is a mirrored [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of knowledge.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">AS ABOVE</div>
		<div class="passive">
			<div class="tooltip-title">AS ABOVE</div>
			<div class="tags">Passive</div>
			<div class="description">
				You have the ability to
see yourself from the third
person within short range,
toggling between third and first
perspective. This may allow you
to perceive points of interest or
objects you would not have been
able to notice normally. It is
difficult to physically sneak or
hide from you while in your
presence.
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
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">MINDWALK</div> 
		<div class="power">
			<div class="tooltip-title">MINDWALK</div>
			<div class="tags">Charm, Self, 1 Scene, 1/Rest</div>
			<div class="description">
				Force your way into the mind of another living being. It
becomes a physical space you can traverse with your own
mind as if the target owned a Palace (even on targets without
one). Most mundane human brains will resemble a small
room or place of comfort for the individual. While within this
space your real body is unconscious and vulnerable.<br><br>
Once inside, you gain a number of action rolls equal to your
½ CAT+1 to investigate, probe, or edit things as possible
within your capabilities. If you find a memory in the form of a
book or piece of paper you may attempt to hide it. If there is a
piece of information relevant to the hunt it may emerge in the
form of symbols or seemingly random events. Once you finish
your final action you are ejected back into your own body.<br><br>
If the target possesses a Palace, your mindwalk happens
within their designated domain with the caveat that you may
not be forcibly kicked out of the space or harmed once
entered.<br><br>
Gain or grant +1D to the next action that takes advantage of
information uncovered or actions taken during the mindwalk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DEDUCE</div>
		<div class="power">
			<div class="tooltip-title">DEDUCE</div>
			<div class="tags">Instant, 1/Mission</div>
			<div class="description">
				Psychically break down information and objects
uncovered in this investigation down to their
immutable truths. Select a number of objects you
possess or pieces of information (A phrase, a
statement, a person, place, or thing) equal to your
½ CAT+1.<br><br>
You may ask one yes or no question about a
selected object or piece of information. You may
ask more questions at the cost of 2 stress per
additional question. The admin then rolls a fate die:
(1-2): The Admin may refuse to answer 1 question
which may not be asked again. (3-5): The Admin
must answer yes or no as truthfully as possible. (6):
The Admin may answer vaguely, expanding upon
yes or no in any way of their choosing.<br><br>
Gain or grant +1D to the next roll that takes
advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">OSMOSIS</div>
		<div class="power">
			<div class="tooltip-title">OSMOSIS</div>
			<div class="tags">Charm, Short, Until Rest, 1/Rest</div>
			<div class="description">
				By maintaining eye contact with another
individual within range for a few seconds,
you may absorb skills, knowledge, or
specialized skills they possess. When used
on a mundane human, you may absorb
certain trademark skills or specialized
knowledge such as handiwork, years of
research on a particular subject, or certain
practical skills.<br><br>
Gain or grant +1D to rolls that match the
skills gained from this ability for the duration
of its effect. This may easily change the
parameter of rolls such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CONFLUENCE</div>
		<div class="power">
			<div class="tooltip-title">CONFLUENCE</div>
			<div class="tags">Instant, CAT Area, 1/Scene</div>
			<div class="description">
				By focusing for a moment, you force individuals of
your choice in a CAT area centered on yourself to
experience a shared overlay of your
understanding of a topic, skill, or knowledge of
the situation at hand. This happens
instantaneously but can project the full
knowledge of the investigation at hand, months
of training in a particular skill set, or any wide
breadth of knowledge.<br><br>
You may pick and choose details to leave out in
order to disguise where the information came
from, but still share the knowledge in an accurate
and precise way.<br><br>
Gain or grant +1D to the next action that takes
advantage of this power. This power may easily
affect the parameters of rolls such as difficulty or
risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CODEX</div>
		<div class="power">
			<div class="tooltip-title">CODEX</div>
			<div class="tags">Permanent</div>
			<div class="description">
				<b>Passive:</b> You possess a codex of blasphemies,
supernatural phenomena, individuals, and other
various information stored in your mind.
Whenever you encounter a blasphemy power
you do not possess (whether upon use from an
ally or enemy), you may add it to your codex (a
maximum of blasphemy powers equal to your
½ CAT+2). When you write down this
blasphemy you may additionally write down, if
you know it, the name of the individual that used
it, the location, and time of use.<br><br>
Once per rest by citing as much information as
you know about a recorded power, you may use
it yourself at a CAT rating equal to yours and
expending psyche bursts as normal as indicated
by the original power. You then remove it from
your codex and make a fortune roll. On a 1 or 2
gain 1 sin.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
