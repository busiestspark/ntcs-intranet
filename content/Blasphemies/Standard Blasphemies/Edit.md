---
tags:
  - Blasphemy
image: "[[Edit Card.png]]"
blsphID: "8"
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
<div class="infobox-title">Edit</div>

<br>
<img src="Edit Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right; ">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

<div style="padding-right: calc(400px);">
<div style="border: 1px solid #00FF00; padding: 1rem; width: 90%;">ⓘ REMINDER<br><br>Edit users are may be required to assume the form on their CID card for identification. If you would like to change the photo on your CID card, see the CID Reapplication Form.</div>
</div>

**Edit** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the alteration of the self, world, and others by draw from alternative possibilities.[^1]

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">MIMIC</div>
		<div class="passive">
			<div class="tooltip-title">MIMIC</div>
			<div class="tags">Passive</div>
			<div class="description">
				You can alter minor things about your appearance. You
can change any of the following about yourself when resting,
within a variation of your original body:<br><br>
• body features such as height and weight<br><br>
• aesthetics such as facial features, skin color, hair, gender
presentation<br><br>
• age, down to 13 and up to 88<br><br>
You always look faintly similar, like a distant relative of yourself.
Your clothes always change to fit you, though you cannot alter
them. This doesn’t change anything about your skills or general
ability, and also cannot restore missing body parts or hide sin
marks or scars.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #00008B);">
		<div class="tooltip-title">ALTER</div>
		<div class="quirk">
			<div class="tooltip-title">ALTER</div>
			<div class="tags">Quirk</div>
			<div class="description">
				When you rest or go to sleep, you disappear
and are replaced by a different version of
yourself with similar memories. These
versions of yourself rotate in from another
reality where this power activated. Your
appearance changes as if you used the Mimic
passive. Choose one:<br><br>
• You are holding something small but
useful (a tool, a weapon, a key, a map)<br><br>
• You have faint memories of a piece of
information pertinent to the current
investigation. Ask the GM a yes or no
question about the current hunt and get a
truthful answer.<br><br>
• You are slightly less stressed (-1 stress)
than your current version.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #00008B);">
		<div class="tooltip-title">SCENERY</div>
		<div class="quirk">
			<div class="tooltip-title">SCENERY</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Once a scene, when using
any power from this
blasphemy, if you can pull
from a work of art nearby, it
does not cost a psyche
burst. The same work of
art does not work twice in
the same hunt, and the
quality of the end result is
dependent on the quality of
the artwork.
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
		<div class="tooltip-title">UNIFORM</div> 
		<div class="power">
			<div class="tooltip-title">UNIFORM</div>
			<div class="tags">Until Rest, Charm, Self</div>
			<div class="description">
				You make a brief edit of yourself. You can’t do
this in public (you need privacy, no matter how
tenuous). This power makes you officially part of
any profession or group with more than 5
members, with any necessary uniform,
equipment, id cards, memberships, etc, and
alters reality to make it so.<br><br>
Even if people don’t particularly remember you
being part of a group, they may get a vague
sense that you were a member.<br><br>
You don’t actually gain any particular skills and
any changes you make have to be to your own
person and must include things you could wear
or carry in one or both hands.<br><br>
Gain or grant +1D when you or any ally next acts
to take advantage of this power.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">ABSURD</div>
		<div class="power">
			<div class="tooltip-title">ABSURD</div>
			<div class="tags">1 Scene, Curse, Short</div>
			<div class="description">
				You swap up to a CAT group of humans or
exorcists with a different version of themselves
from an alternate timeline. You must roll
PSYCHE for this power to take effect on hostile
targets, only spending a psyche burst on
success. This can change:<br><br>
• what the target is wearing, but not holding
(so anything held in hand remains the same)<br><br>
• physical appearances of the targets, as your
MIMIC power.<br><br>
Targets retain their memories, and this does not
alter reality to accommodate the change, so it
can easily disorient unprepared humans. The
change is otherwise perfect.
Gain or grant +1D when you or any ally next acts
to take advantage of this power.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">UTILITY</div>
		<div class="power">
			<div class="tooltip-title">UTILITY</div>
			<div class="tags">Until Rest, Short</div>
			<div class="description">
				When you need any mundane object, tool, or
vehicle that could fit in a small room, you can
cause it to appear on a surface in range as though
it was always there, without spending KP.
However, the admin chooses one, or two if the
item is dangerous or rare:<br><br>
• The item is used, dented, scuffed, or poor
quality<br><br>
• The item is a real item that someone nearby
owned and has now disappeared, and they will
come looking for it<br><br>
• The item is ‘off’ somehow and appears as a
cheap knockoff made of odd materials that feel
spongey or organic<br><br>
• The item is missing some parts and doesn’t
work as well as it could with them<br><br>
The item cannot be a unique item, etc you cannot
create a particular car, key, book, etc, but is rather
a generic representative of a category. It
disappears after a rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FILTER</div>
		<div class="power">
			<div class="tooltip-title">FILTER</div>
			<div class="tags">1 Scene, Transmute, Adjacent</div>
			<div class="description">
				You produce a strong field affecting all matter in an
area about the size of a small room, which must
contain you. In this area you gain +1D to examine
its contents and:<br><br>
• you can cause any matter to become
transparent or opaque<br><br>
• you can change the lighting in the room as
though lit by an invisible light source, or snuff
out any light sources in the room<br><br>
• you can move around any objects in the area
without touching them and ‘pin’ them to any
point in space in the area, causing them to float<br><br>
• you can safely dissect any loose inanimate
object or furniture into its constituent parts or
reassemble any broken object, providing any
parts are present<br><br>
This effect expires when the scene ends, or if you
leave the area for any reason.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">COPY</div>
		<div class="power">
			<div class="tooltip-title">COPY</div>
			<div class="tags">1 Scene, Summon, Adjacent</div>
			<div class="description">
				You create a temporary, exact copy of a human or
exorcist.<br><br>
• This creates a doppelgänger: a simple, obedient
clone, without much intelligence or ability to
speak.<br><br>
• You may give it simple instructions of one or two
sentences, which it follows to the best of its
ability.<br><br>
• It dissolves into a pale sludge when the scene
ends, when touched by anyone except you, or if it
takes any harm.<br><br>
This ability creates a copy of the target in its present
state, including anything mundane a person is
carrying or wearing. A doppelgänger cannot gain,
use, or benefit from psychic powers and rolls just 1d6
to do anything.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>

[^1]: Note: The existence of "parallel universes" and similar such phenomena is currently unproven and is not to be considered in any official capacity.