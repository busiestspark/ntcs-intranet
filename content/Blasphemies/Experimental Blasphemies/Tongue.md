---
tags:
  - Blasphemy
  - ExperimentalBlasphemy
image: "[[Tongue Card.png]]"
blsphID: "13"
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

	background: linear-gradient(145deg, #000000, #8B0000);

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
	background-image: linear-gradient(145deg, #000000, #8B0000);
}

.quirk {
	background-image: linear-gradient(145deg, #200020, #8B0000);
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
<div class="infobox-title">Tongue</div>

<br>
<img src="Tongue Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from Games For Freaks Volume 3</div>
</div>

Tongue is an experimental [[Blasphemies|Blasphemy]].

It is concerned with the psychological effects of language.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">THE WORD</div>
		<div class="passive">
			<div class="tooltip-title">THE WORD</div>
			<div class="tags">Passive</div>
			<div class="description">
				Your powers have no effect if you
can’t speak, or if sound is suppressed
somehow. Using the same power from this
blasphemy more than once before resting
has ramping effects, which are not
optional.<br><br>
• <b>Second time:</b> +1 CAT (min. CAT 2),
take 1 irreducible stress.<br><br>
• <b>Third time:</b> +2 CAT (min CAT 3,
max CAT 7), +1D, take 3 irreducible
stress. Anyone in short range from
you takes the defeaned affliction for
the rest of the hunt (hard on rolls that
require hearing).<br><br>
• <b>Fourth time:</b> Power always
resolves at CAT 7 and do not roll
(automatic successes per die rolled).
Afterwards, suffer instant death as
your body is ripped apart by forces
beyond comprehension, which cannot
be ignored. Anyone in short range of
you is permanently deafened.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #8B0000);">
		<div class="tooltip-title">TABOO</div>
		<div class="quirk">
			<div class="tooltip-title">TABOO</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Certain words are banned for you. When
you, the character or the player, speak
those words (even inadvertently) in any
voice louder than a whisper, resolve any
powers triggered by your speech, then it
inflicts a supernatural destructive
shockwave on everything other than you in
a CAT+1 area centered on you (roll
PSYCHE for effects, including harm, etc),
and temporarily deafens everyone in that
area. Your voice is blown out and your
character is unable to speak or use powers
from any blasphemy until you rest.<br><br>
<b>Banned words:
Sin, Cain, the name
of any blasphemies
or blasphemy
powers, including
your own, the name
of a sin type (ogre,
lord, etc).</b>
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
		<div class="tooltip-title">BANG</div> 
		<div class="power">
			<div class="tooltip-title">BANG</div>
			<div class="tags">Instant, CAT Range</div>
			<div class="description">
				You say ‘bang’. This causes a
massive influx of force affecting up to a
½ CAT area with its center in range that
typically manifests as an extreme
pressure wave. It affects everything
except you. Roll PSYCHE for its effects,
and only spend a psyche burst on
success.<br><br>
• Gain +1D if the environment around
you is quiet or subdued.<br><br>
• Gain +1D if you are in an area with
favorable acoustics, like a canyon, a
performance venue, theatre, or a
stadium.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SILENCE</div>
		<div class="power">
			<div class="tooltip-title">SILENCE</div>
			<div class="tags">1 Scene, Transmute, Long</div>
			<div class="description">
				You say ‘silence’ and choose an area up
to CAT size with its center at a point in range.
Everything in the area completely stops
producing noise. Anything mundane that would
make a loud noise as part of normal part of its
operation completely stops functioning, such as
vehicle engines, creaky door hinges, guns,
explosives, fireworks, etc. Your powers from this
blasphemy or any other blasphemy or psychic
effect that would create a loud noise do not
work inside this area.<br><br>
• Gain or grant +1D when next acting on this
power.<br><br>
• This power can easily affect the
parameters of rolls.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">NARRATE</div>
		<div class="power">
			<div class="tooltip-title">NARRATE</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				Pick up to a CAT-sized group of humans or
exorcists in range (which could include yourself), an
object or location in range, and a verb. Then narrate
a sentence using the following structure:<br><br>
<div style="text-align: center;">
<b>(He/she/they) was/were (verb)ing the (noun).</b>
</div><br>
<span style="font-style: italic">
<b>For example:</b><br>
He was opening the door.<br>
She was falling in the air.<br>
He was driving the car.<br>
They were lying on the floor.
</span>
<br><br>
Roll PSYCHE for its effects, and only spend a
PSYCHE burst on a success. After the sentence
finishes and if the roll is successful, it becomes true,
including moving any affected people where they
need to be as if they were always there. This power
does not adjust human memory nor can it create
anything, change anyone, or directly harm anyone (it
could still easily harm someone indirectly, as you can
see from the examples).
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DIE</div>
		<div class="power">
			<div class="tooltip-title">DIE</div>
			<div class="tags">Instant, Curse</div>
			<div class="description">
				You say ‘die’ and instantly
kill all humans in an area up to
CAT size, centered on you. This is
not optional, you don’t get to
choose who to kill or spare, and
you don’t require a roll to do so. If
you used this power at least once
to kill one person, at the end of a
hunt, permanently fill in a sin box.
If you used it at least once to kill
more than one person,
permanently fill in 1d3 sin boxes.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SNAP, CLICK, POP</div>
		<div class="power">
			<div class="tooltip-title">SNAP, CLICK, POP</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				You say ‘Snap”, ‘Click’, or ‘Pop’, and
produce an effect that would normally produce
one of those sounds. For example, you could
use ‘click’ to open a locked door, push a button,
or type on a keyboard. You could use ‘snap’ to
break a weapon or an arm. You could use ‘pop’
to blow a car tire or shoot a gun someone else
is holding.<br><br>
If necessary, roll PSYCHE for effects that would
be risky, unclear, or inflict harm, and only spend
a burst on success. Otherwise, this power is
always successful. When you or an ally next
acts to gain advantage of this power, they may
gain +1D.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>