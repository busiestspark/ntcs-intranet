---
tags:
  - Blasphemy
image: "[[Smother Card.png]]"
blsphID: "6"
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
<div class="infobox-title">Smother</div>

<br>
<img src="Smother Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

**Smother** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the abstraction of and removal of concepts from objects.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">ABSENTIA</div>
		<div class="passive">
			<div class="tooltip-title">ABSENTIA</div>
			<div class="tags">Passive</div>
			<div class="description">
				You can improve the CAT of any of
your Smother powers by +2 when you use
them, to a max CAT of 7. However, when you
do, gain the <b>Absentia Hook.</b>
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #bd7611">
		<div class="tooltip-title">ABSENTIA</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #bd7611">
			<div class="tooltip-title">ABSENTIA</div>
			<div class="tags">Hook</div>
			<div class="description">
				You can gain this hook with your passive. If
this hook fills up, you take an injury and black
out for a few moments. When you wake up,
you are missing a body part (roll 1d6). It
simply disappears (cleanly) as though it had
never existed, leaving a stump or hole. It
doesnt come back, even if you heal the injury.
If you have no body part left to lose (when
you roll), reduce the result by 1. If the result is
0, you lose your head and suffer (gruesome)
instant death instead. Missing body parts
might make some rolls hard or risky,
dependent on the situation. You adjust to any
disability after the mission, and it has no
further effect.<br><br>
1. Eye<br>
2. Nose<br>
3. Ear<br>
4. Finger<br>
5. Toe<br>
6. Nothing<br>
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #822700, #bd7611);">
		<div class="tooltip-title">DIGIT</div>
		<div class="quirk">
			<div class="tooltip-title">DIGIT</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You can instantly (and cleanly) lose a finger to gain
+1D and +1 CAT to any power when you use it. It
disappears as if it had been cut off a long time ago.
Roll 1d6 (2-3: left hand, 4-5 right hand).<br><br>
If you run out of fingers on one hand, you
automatically lose fingers on the other. If you roll a 1,
you lose another finger and roll again (this can keep
going!). If you roll a 6, you can choose which hand you
lose a finger on.<br><br>
Gain -1D on any rolls that would require using the
affected hand until the next hunt, when you have time
to adjust to the disability. If you have no fingers left,
you lose your head instead and suffer (gruesome)
instant death, which cannot be ignored.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #822700, #bd7611);">
		<div class="tooltip-title">BAN</div>
		<div class="quirk">
			<div class="tooltip-title">BAN</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Gain the <b>Abstract</b> power from this
Blasphemy for free (even the limit of 5
powers). You can now use it once a hunt to
affect a single human or exorcist, leaving
them an unrecognizable blur and
preventing them from taking action. They
recover if taking harm or if the scene
passes.<br><br>
Roll PSYCHE for effects and only spend a
psyche burst on success. Take or grant
+1D on the next action taking advantage
of this as normal.
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
		<div class="tooltip-title">HOLLOW</div> 
		<div class="power">
			<div class="tooltip-title">HOLLOW</div>
			<div class="tags">Until Rest, Charm, Adjacent</div>
			<div class="description">
				You temporarily remove weight from a single
object, human, or exorcist, giving them the total
weight of 1 lb if heavier. The size of the object
must be CAT or lower, and you can end this
modification any time, though you must use this
power again to regain its effects. Roll PSYCHE
for any creative uses of this power, only
spending a burst on at least one success.<br><br>
• Gain or grant +1D when you or any ally next
acts to take advantage of this power<br><br>
• This power ends on its previous target if used
again.<br><br>
This power may easily affect the parameters of
rolls, such as difficulty and risk.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">ABSTRACT</div>
		<div class="power">
			<div class="tooltip-title">ABSTRACT</div>
			<div class="tags">1 Scene, Transmute, Short</div>
			<div class="description">
				With a gesture, you remove recognizable
properties of CAT+1 number of distinct tools,
vehicles, windows, doors, or any other objects
that can be held or worn. The chosen objects
can no longer be used for their intended
purpose and no human, sin, or exorcist
(including you!) can recognize them - staring at
them for too long causes extreme discomfort,
even for exorcists. For example, weapons can
no longer fire, doors can no longer open, or
windows can no longer be looked through.<br><br>
Gain or grant +1D when you or any ally next
acts to take advantage of this power. It may also
affect the parameters of rolls while active.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SMOOTH</div>
		<div class="power">
			<div class="tooltip-title">SMOOTH</div>
			<div class="tags">1 Scene, Transmute, Short</div>
			<div class="description">
				You temporarily remove almost all friction from a
CAT sized group of human or exorcists, or an area up
to CAT. The area or target(s) become incredibly
slippery. If targeting an area, it becomes hard for
anyone to stand, climb, or move normally in the area,
though people are able to slide around.<br><br>
• Roll PSYCHE to affect hostile targets with this
power, only spending a psyche burst on success.<br><br>
• You can sculpt this area if you wish to affect just
part of it, or sculpt a path.<br><br>
Gain or grant +1D when you or any ally next acts to
take advantage of this power. This power may also
easily effect the parameters of rolls, such as difficulty
and risk.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DARK AGE</div>
		<div class="power">
			<div class="tooltip-title">DARK AGE</div>
			<div class="tags">Until Rest, Charm, Short</div>
			<div class="description">
				You produce a strong field from your body disabling
even the simplest human advancements from
working in CAT area. The effect moves with you. You
can choose up to three of the following to suppress,
ceasing their operation, then gain or grant +1D when
you or any ally next acts to take advantage of this
power:<br><br>
• Electricity<br>
• Internet<br>
• Combustion engines<br>
• Running Water<br>
• Door handles, window latches, zippers, catches<br>
• Open fires<br><br>
These things stop working even if it would not make
sense, i.e. suppressing running water would mean
water pressure simply stops working. You can end
this effect willingly, but must end all effects at once.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BLIND</div>
		<div class="power">
			<div class="tooltip-title">BLIND</div>
			<div class="tags">1 Scene, Transmute, Adjacent</div>
			<div class="description">
				A number of objects or living beings equal to CAT, or
location of a size up to CAT you touch ceases
producing sound, reflecting light, or both for the
scene. Gain or grant +1D when you or any ally next
acts to take advantage of this power:<br><br>
• Targeting a person allows the effect to move with
them for the scene<br><br>
• Targeting a location affects an area, removing all
sound and/or light. You can ‘filter’ this effect by
allowing light or sound inside the location to
operate normally, but not enter or exit the area.<br><br>
This power may easily affect the parameters of rolls,
such as difficulty and risk.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>