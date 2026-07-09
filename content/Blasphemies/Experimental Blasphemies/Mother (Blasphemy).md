---
tags:
  - Blasphemy
  - ExperimentalBlasphemy
image: "[[Mother Card.png]]"
blsphID: "16"
---
<style>

table, td {
	color: white;
}

tr {
	border: none;
}

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

	background: linear-gradient(145deg, #200020, #8B008B);

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
	background-image: linear-gradient(145deg, #200020, #8B008B);
}

.quirk {
	background-image: linear-gradient(145deg, #003030, #8B008B);
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
<div class="infobox-title">Mother</div>

<br>
<img src="Mother Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from Games For Freaks Volume 3</div>
</div>

**Mother** is an experimental [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of one's own flesh and the application of the noological parasite "Mother".

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">MOTHER'S EMBRACE</div>
		<div class="passive">
			<div class="tooltip-title">MOTHER'S EMBRACE</div>
			<div class="tags">Passive</div>
			<div class="description">
				When you sin overflow, you may gain a <b>Mother's Mark</b> instead of a regular sin mark, and roll 2d6, picking the lowest, if you choose to keep control.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #8B008B">
		<div class="tooltip-title">MOTHER'S MARKS</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #8B008B;">
			<div class="tooltip-title">MOTHER'S MARKS</div>
			<div class="tags">Roll 1d3, then 1d6</div>
			<div class="description">
				A mother's mark does not lower sin overflow cap, but still counts as a sin mark in all other aspects. It has no other gameplay effects. Roll 1d6 for its aspect. You can gain the same mark more than once.<br><br>
				1. <b>New eye</b> in the center of forehead. Looks around on its own. You cannot see through it. <i>It is not yours.</i><br><br>
				2. <b>Large patch of skin or hair</b> loses all color, then gains banded stripes.<br><br>
				3. <b>New pupil</b> in eye.<br><br>
				4. <b>New tongue.</b>
				5. <b>New limb.</b> Elongated and double jointed.<br><br>
				6. <b>Spiraling patterns,</b> warping the skin and muscle. Patterns change and shift over time.<br><br>
				If you lose control and have at least one Mother's Mark, you become subsumed into Mother, becoming a <b>Mother's Favorite</b> instead of an Imago. This is not a kind fate.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #003030, #8B008B);">
		<div class="tooltip-title">MOTHER'S LOVE</div>
		<div class="quirk">
			<div class="tooltip-title">MOTHER'S LOVE</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Your strain of mother is less detectable, and
you look more human.<br><br>
Twice a hunt, you may listen to the whispers of
Mother (ask the GM what She is saying) when
using a blasphemy from this power.<br><br>
If you follow her advice or direction, you may
use that power without spending a psyche
burst, it gains +1D on any PSYCHE rolls, +1
CAT, and all sin costs from that power are
reduced to 1 for its duration.<br><br>
However, using the power becomes risky if it
wasn’t already, and the risk die becomes a ‘1’
automatically.
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
		<div class="tooltip-title">UNRAVEL</div> 
		<div class="power">
			<div class="tooltip-title">UNRAVEL</div>
			<div class="tags">Until Rest, Charm, Self</div>
			<div class="description">
				You unravel your skin, muscle, and organs into a pulsing mass. You can reform body parts such as hands, mouths, eyes, or teeth anywhere in this mass at will. While in this form:<br><br>
				• You cannot use or benefit from your own psychic powers (other than this one), but psychic powers or effects from others can still affect you.<br><br>
				• You can spread through spaces as small as a sink pipe, spread out your total mass over an area equal to CAT, or compact your mass into a tight shape about the size of a piece of luggage.<br><br>
				• Roll PSYCHE for any effects you'd use this form for while it's active.<br><br>
				• Humans are typically terrified by this form, and the next action against a human or group of humans after taking this form takes +1D.<br><br>
				When your party rests, or when you end this power, you reform in any area that has enough space for you that your mass is touching. If there is no room for you, you instead reform when there is space.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">POLYP</div>
		<div class="power">
			<div class="tooltip-title">POLYP</div>
			<div class="tags">Entire Hunt, Charm, Adjacent</div>
			<div class="description">
				You harmlessly but gruesomely remove and place either or both of your eyes, or your mouth (or any combination of your eyes and mouth) on a human, exorcist, sin, or flat surface that you can touch. For unwilling or unaware targets, roll PSYCHE and only activate this power on a success.<br><br>
				You can see and speak normally from your eye and mouth, but they disappear on your face for the duration. You take any stress your eye or mouth would take as a consequence of your actions with them, and they return to your face when you end this power, or after they take harm.<br><br>
				Additionally, any number of times while active, you can take 1 sin to use a blasphemy power from any eye or mouth in CAT+2 range as if you were there, spending a psyche burst as normal. Gain +1D if doing so would grant you an advantage. 
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">COLONY</div>
		<div class="power">
			<div class="tooltip-title">COLONY</div>
			<div class="tags">Instant, Self, Ally, Short</div>
			<div class="description">
				Gain 1d3 sin, then you or an ally in range gains a fleshy shield that absorbs 2 stress from external harm. If a character already has such a shield, increase it by +2, but they also gain 1d3 sin.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">KNOT</div>
		<div class="power">
			<div class="tooltip-title">KNOT</div>
			<div class="tags">Entire Hunt, Self</div>
			<div class="description">
				<b>Passive:</b> When you gain any amount of stress, you can capture its negative energy without spending a psyche burst, appearing as a raised knot on your skin. Reduce stress suffered by 2 for each knot gained. You can capture up to 3 knots. At the end of any scene in which you have one or more knots, roll 1d6. When a knot bursts, you take 2 irreducible stress.<br><br>
				• On a <b>1,</b> take 1d3 sin and burst a knot.<br><br>
				• On a <b>2-5,</b> take 1 sin and burst a knot.<br><br>
				• On a <b>6,</b> take no sin and don't burst a knot.<br><br>
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">COIL</div>
		<div class="power">
			<div class="tooltip-title">COIL</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				Your limb peels apart its flesh and skin, then lashes at a target in short range like a whip, dealing harm or pulling them some distance. Roll PSYCHE for its effects.<br><br>
				• Gain +1D if you have 3 or fewer sin boxes remaining.<br><br>
				• Gain +2 CAT in range and potency if you have sin overflowed this mission.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>