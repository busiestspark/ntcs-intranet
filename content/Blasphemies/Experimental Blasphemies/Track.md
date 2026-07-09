---
tags:
  - Blasphemy
  - ExperimentalBlasphemy
image: "[[Track Card.png]]"
blsphID: "14"
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

	background-image: linear-gradient(145deg, #301e04, #bd7611);

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
	background-image: linear-gradient(145deg, #301e04, #bd7611);
}

.quirk {
	background-image: linear-gradient(145deg, #822700, #bd7611);
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
<div class="infobox-title">Track</div>

<br>
<img src="Track Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from Games For Freaks Volume 3</div>
</div>

**Track** is an experimental [[Blasphemies|Blasphemy]].

It is concerned with the psychological effects of music.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">PLAYLIST</div>
		<div class="passive">
			<div class="tooltip-title">PLAYLIST</div>
			<div class="tags">Passive</div>
			<div class="description">
				You have a powerful cursed object, which is
the focus of your powers. It’s a music player, typically
a tape player or a cd player with attached
headphones. It doesn’t take KP, and you can
supernaturally form and reform it in your hands at
will. Make a (real) playlist of 6 songs at the start of
each hunt. Some of your powers key off this playlist.
Any music you play from this playlist can be heard
diagetically (in the game) if you so choose. It appears
to come from either a visible location in short range,
your player, or nowhere in particular (like a
soundtrack), and you can turn it on and off at will.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #822700, #bd7611);">
		<div class="tooltip-title">CATCH VIBE</div>
		<div class="quirk">
			<div class="tooltip-title">CATCH VIBE</div>
			<div class="tags">Quirk</div>
			<div class="description">
				<b>This adds to your existing passive instead of replacing it.</b><br><br>
				Your starting playlist is smaller (4 tracks).
However, you can add or swap in and out
any (real life) music track played during
the session by you, your GM, or any of
the players into your active playlist for
the remainder of the hunt, or any music
track played diagetically (in the game).
This could push it up to 10 tracks.
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
		<div class="tooltip-title">VIBE</div> 
		<div class="power">
			<div class="tooltip-title">VIBE</div>
			<div class="tags">1 Scene, Self, Charm</div>
			<div class="description">
				When a scene starts, you may use this power to play a track
from your playlist. Decide if the track is Melancholy, Chill, or Angsty.
Gain a bonus based on the tracks’ type for the rest of the scene.<br><br>
• <b>Melancholy:</b> You or any ally erase 1 stress when they fail a roll.<br><br>
• <b>Angst:</b> After you or an ally gains an injury, hook, or affliction, they
gain +1D on their next action.<br><br>
• <b>Chill:</b> At the end of the scene, everyone in short range of you
erases 1 stress if there was no risky or hard rolls made this scene.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SHUFFLE</div>
		<div class="power">
			<div class="tooltip-title">SHUFFLE</div>
			<div class="tags">Instant, Transmute, CAT Area</div>
			<div class="description">
				You may choose any number of objects, vehicles, or
people in the affected area. Anything swapped may have a size up
to 1/2 CAT (min 0). You instantly swap their positions and
momentum. You must swap things of approximately the same size
and mass. If attempting otherwise, or if you need to roll for effects
such as harm, roll PSYCHE and only spend a burst on success.
When you or an ally next acts to gain advantage of this power,
they may gain +1D.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">REPLAY</div>
		<div class="power">
			<div class="tooltip-title">REPLAY</div>
			<div class="tags">Whole Mission, Charm, Short</div>
			<div class="description">
				<b>Passive:</b> Without spending a psyche burst, you or an ally in short range from
you performs a course of activity that takes no longer than 10 seconds, which
you record on your player. It records you or your ally at the moment of the
recording, including dress, speech, and objects held or worn, but nothing else
around them. You can keep 3 recordings this way.<br><br>
<b>Active:</b> You can playback a recording by spending a psyche burst. This
immediately replays a psychic double of the recording. This double is
physically tangible, looks and sounds believable, can inflict harm, and can
interact with the physical world, though it de-manifests after 10 seconds and
cannot interact in any way that was not previously recorded (for example, it
can’t respond to any speech, move through a wall, or open a door if it was not
recorded previously doing so). Roll PSYCHE for its effects if they are unclear,
contested, or risky, and only spend a psyche burst on success.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BOOST</div>
		<div class="power">
			<div class="tooltip-title">BOOST</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				You can activate this power once a scene before yourself
or any ally in range uses a blasphemy and makes a PSYCHE roll.
Pick a track from your playlist. Record the first three digits of the
track length (like 3, 3, 5). 0s do not count, so a 10:35 track would
record 1, 3, 5. For each die rolled, the action gains +1 additional
CAT for every die rolled that matches a number recorded from the
track length (min +1 CAT, max +3 CAT, max CAT 7).
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TITLE</div>
		<div class="power">
			<div class="tooltip-title">TITLE</div>
			<div class="tags">Summon, Instant, Short</div>
			<div class="description">
				You play a track from your playlist. You can manifest in short range from you a
psychic manifestation based on any part of the title, up to CAT in size or magnitude. The
effect can create:<br><br>
• A psychic copy of any object named in the title<br><br>
• A psychic copy of any human or animal in the title<br><br>
• A brief burst or energy, weather, or physical force (fire/rain/wind/push/pull/pressure)
named in the title<br><br>
The manifestation lasts until you would roll for its effects or actions, until you use this power
again, or until the scene passes, then it dissipates. Anything created is tangible but has an
aura of unreality or ‘wrongness’ around it to regular humans, who will catch on under close
inspection. It can cause tangible harm or force and interact with the physical world but is in
no way obligated to follow your instructions if it can act independently. If the use of this
power would cause harm, or be risky or uncertain in some way, roll PSYCHE for its effects
when it is used, only manifesting and spending a burst on success. Otherwise, it always
takes effect.
			</div>
			<div class="credit">From Games for Freaks Vol. 3</div>
		</div>
	</div>
</div>