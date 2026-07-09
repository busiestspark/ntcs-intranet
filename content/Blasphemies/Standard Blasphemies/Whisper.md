---
tags:
  - Blasphemy
image: "[[Whisper Card.png]]"
blsphID: "7"
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

	background-image: linear-gradient(145deg, #000020, #00008B);

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
	background-image: linear-gradient(145deg, #000020, #00008B);
}

.quirk {
	background-image: linear-gradient(145deg, #200020, #00008B);
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
<div class="infobox-title">Whisper</div>

<br>
<img src="Whisper Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

**Whisper** is a standard [[Blasphemies|Blasphemy]].

It is concerned with precognition and the concept of fate.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">SHADOW</div>
		<div class="passive">
			<div class="tooltip-title">SHADOW</div>
			<div class="tags">Passive</div>
			<div class="description">
				You harbor a separate being that follows you
everywhere, even when you sleep.<br><br>
THE SHADOW is intangible and invisible to
everyone, even the psychically sensitive. It
can only weakly interact with the physical
world and has its own mind and senses. It
can move in about short range from you. It
can pass through walls and surfaces easily
but retreats into your body in bright light,
preventing it from doing anything.<br><br>
You can talk to it telepathically, but talking to
it is dangerous and causes 1 stress after any
interaction ends. It has no obligation to tell
you the truth unless you use your powers.<br><br>
You may talk to it safely using your abilities,
and it knows the future. The Admin will
answer for it.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #00008B);">
		<div class="tooltip-title">THE FUTURE RULES!</div>
		<div class="quirk">
			<div class="tooltip-title">THE FUTURE RULES!</div>
			<div class="tags">Quirk</div>
			<div class="description">
				<b>This adds to your existing passive instead of replacing it.</b><br><br>
				You cannot die, except from causes which
aren’t ignorable. If you would die, you
miraculously survive in an improbable way, pass
out, and come to consciousness at the start of
the next scene with 1 remaining injury and half
your stress full.<br><br>
However, roll 1d6 at the end of each mission you
complete. On a 1, foreboding doom sets in, and
you become certain that the next mission is the
one you die on. Increase the range of this
number by +1 for each mission it doesn’t trigger
(so the next time would be on a roll of 1-2).<br><br>
While you are affected by foreboding doom, you
lose your ability to ignore death and suffer
instant death instead any time you suffer an
injury. You can defy this fate as normal.
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
		<div class="tooltip-title">OMEN</div> 
		<div class="power">
			<div class="tooltip-title">OMEN</div>
			<div class="tags">Instant, Self</div>
			<div class="description">
				Ask your shadow ‘What will happen if I X’, where
X is a simple course of activity you plan to take
in the next hour or so (open this door, attend the
meeting, attack this person, go down this street).
The shadow gives you a brief impression of the
future:<br><br>
• Gain +1D when you or an ally next acts on
the answer.<br><br>
• Pre-roll the risk die before you take the
action. You can decide to back out of the
action if you like, but if you follow the same
course of activity in the future, use the pre-
rolled risk die.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SHIVER</div>
		<div class="power">
			<div class="tooltip-title">SHIVER</div>
			<div class="tags">1 Scene, Charm, Self</div>
			<div class="description">
				When you are looking for a human, sin,
exorcist, location, or object, you can declare
‘I feel a shiver’. You send a psychic pulse
out to CAT range in a radius around you,
which remains active for this scene. While
your target is close enough to be in range,
you feel a strong sense of cold and
discomfort. You can home in on this feeling
easily. It’s never hard to track your target
while this power is active. If your target is in
short range of you, you also gain +1D on
any rolls to track or locate them.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DISSECT</div>
		<div class="power">
			<div class="tooltip-title">DISSECT</div>
			<div class="tags">Instant, CAT Range</div>
			<div class="description">
				Examine a human or exorcist you can see
in CAT range, roll PSYCHE, and ask your
shadow one of the following questions,
plus one more per success. They answer
truthfully, but can use a maximum of three
words to answer each.<br><br>
• Is this person lying?<br><br>
• What is the main emotion this person is
feeling?<br><br>
• Where has this person just come from?<br><br>
• Where are they planning to go next?<br><br>
Gain or grant +1D when you or any ally
next acts to take advantage of each
answer.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PRECOGNITION</div>
		<div class="power">
			<div class="tooltip-title">PRECOGNITION</div>
			<div class="tags">Instant, Self</div>
			<div class="description">
				When the Admin is describing a scene or you are
about to take a course of action, you can ‘flash back’.
Make an action roll or play a scene out in the past,
where you had a vision of the present moment. This
cannot completely alter the established facts of the
present (you can’t have knocked someone out in the
past if you just finished having a conversation with
them in the present, for example), but could change
the situation or alter present details, or it could set
up yourself or any ally. For example you could have
made preparations for the current moment (locked
or unlocked a door, stowed some gear, made a
phone call, etc). If you use this power for gear, mark
KP for it as normal.<br><br>
If the situation is complicated, also take 1 nonlethal
stress. If it’s convoluted or far fetched, take 3
nonlethal stress.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">OMNIPRESENCE</div>
		<div class="power">
			<div class="tooltip-title">OMNIPRESENCE</div>
			<div class="tags">Instant, CAT+2 Range</div>
			<div class="description">
				When an ally is in a scene, and you are not
present in that scene, and your ally is in CAT+2
range, you can use this power to walk in on the
scene, having already predicted that this course
of events would happen. Roll PSYCHE, and
choose one of the following per success:<br><br>
• nobody is following you<br><br>
• you are hidden<br><br>
• you are able to enter your ally’s location
without distraction or harm<br><br>
• you have a useful tool or object on you for
the present situation (a key, a weapon, a
wrench, etc)<br><br>
After using this power, lose its use until you rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>