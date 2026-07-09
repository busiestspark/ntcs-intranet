---
tags:
  - Blasphemy
  - ExperimentalBlasphemy
image: "[[Wire Card.png]]"
blsphID: "15"
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
<div class="infobox-title">Wire</div>

<br>
<img src="Wire Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from Games For Freaks Volume 3</div>
</div>

**Wire** is an experimental [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of phone lines, electrical systems, and the internet.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">MAIN ARTERY</div>
		<div class="passive">
			<div class="tooltip-title">MAIN ARTERY</div>
			<div class="tags">Passive</div>
			<div class="description">
				You have a cell phone, with better features such as
wireless internet access. It doesn’t take KP. You can produce or
remove it at will, forming it from psychic energy, even if you lose
it.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #00008B);">
		<div class="tooltip-title">WORM</div>
		<div class="quirk">
			<div class="tooltip-title">WORM</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You can produce light reading
material (novels, magazines,
etc) at will, without costing KP,
though it dissolves after a few
minutes of losing contact with
your body.<br><br>
In addition, all wire powers apply to books instead
of computers or phones and can be used with
books. When you’d produce a computer terminal
with Terminal or Deck, you instead produce an
appropriate book (almanac, history book,
encyclopedia, comic book, etc), including from
people’s bodies. Surge works with books (you
must have read or at least be familiar with the
destination book), and Disk turns your target into a
book. Call creates a duplicate journal on both you
and your target if the target picks up. Writing in the
journal causes the writing to supernaturally and
instantly appear on the duplicate, regardless of
distance.
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
		<div class="tooltip-title">TERMINAL</div> 
		<div class="power">
			<div class="tooltip-title">TERMINAL</div>
			<div class="tags">Until Rest, Charm, Self</div>
			<div class="description">
				You manifest a computer terminal that
emerges harmlessly (but somewhat disturbingly)
from your body, usually from your chest or back.
While manifesting this terminal, activities are hard
if you are moving or under duress, but you can
otherwise act normally, including typing or
interfacing from yourself. The terminal has a fast
connection to the internet and is powered, regardless
of location. Any other character interacting with the
terminal can use your relevant skills to gather
information using you. The first time in a scene
someone gathers information this way, also gain
+1D. You end this power with a few moments’
concentration, retracting the terminal.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DECK</div>
		<div class="power">
			<div class="tooltip-title">DECK</div>
			<div class="tags">1 Scene, Curse, Adjacent</div>
			<div class="description">
				You flip a keyboard out from any object,
construction, vehicle, human, or exorcist. The
keyboard lasts until you produce a new one, or
until the end of the scene. While the keyboard is
out and you’re able to type on it, when gathering
information on your subject, you can interact
with them as if they were a computer. You may
roll either PSYCHE or the interfacing skill,
whichever is higher. The first time you do this for
each keyboard, gain +1D. You can flip it out from
even impossible surfaces, it may be made from
unusual materials, and it does not harm a person
it is produced from, although it is hard to type on
them if they are unwilling or while they are
moving.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SURGE</div>
		<div class="power">
			<div class="tooltip-title">SURGE</div>
			<div class="tags">Instant, CAT+2 Range</div>
			<div class="description">
				You instantly transpose your physical form and a group of up to
CAT size of willing humans or exorcists in short range from you into a
psychic electrical charge, then travel rapidly through a phone line or a
networked computer, appearing instantly on the other side. However, you
must be able to clearly see your destination, or else know the phone # of
the target you want to reach, or the network address of the computer on
the other side. You can use this power without knowing your destination,
but where you end up is entirely up to the Admin.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DISK</div>
		<div class="power">
			<div class="tooltip-title">DISK</div>
			<div class="tags">Instant, Adjacent</div>
			<div class="description">
				You touch an adjacent willing human or exorcist, or an object, vehicle, or
construction of CAT size (including anything on or inside that object), and store them as a
CD, spending a psyche burst. You can keep a number of CDs equal to your CAT +1. They reset
between missions, and their contents are freed. A person stored is in a stasis of sort and has
no awareness or sensation, and cannot take harm or be affected in any way, though hooks,
talismans, and afflictions on exorcists within can continue to build up, affecting them
instantly on release if filled. Putting a stored CD into a CD disk drive lets you read
information about its captive like a text document. When you activate the CD again, or if is
broken before them, the stored person or object reappears in a space in short range of you,
regardless of it there is room for it or not. Roll PSYCHE for any of its effects.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CALL</div>
		<div class="power">
			<div class="tooltip-title">CALL</div>
			<div class="tags">Instant</div>
			<div class="description">
				You call any human, sin, or exorcist. Only spend a
psyche burst if they pick up. If they didn’t have a phone
on them, this power manifests one when they pick up, and
a new number for them (which you don’t know unless
they tell you). This phone is a little odd and disintegrates
into psychic energy when you rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>