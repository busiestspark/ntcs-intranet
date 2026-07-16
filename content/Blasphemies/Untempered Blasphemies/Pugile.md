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

	background: linear-gradient(145deg, #491f16, #df5c42);

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
	background-image: linear-gradient(145deg, #491f16, #df5c42);
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
<div class="infobox-title">Pugile</div>

<br>
<img src="Pugile Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Pugile** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the transformation of the body into an instrument of violence through sin.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">DISGRACED</div>
		<div class="passive">
			<div class="tooltip-title">DISGRACED</div>
			<div class="tags">Passive</div>
			<div class="description">
				Add +1 to the final result of all rolls made to resist
sin overflow.<br><br>
Some of your powers gain additional effects if you use
them while your current sin is at half (rounding up) or
more of your total sin cap or for the rest of the scene
after you experience sin overflow. This is considered
Metamorphosis.
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
		<div class="tooltip-title">IMPLODE</div> 
		<div class="power">
			<div class="tooltip-title">IMPLODE</div>
			<div class="tags">Instant, ½ CAT Area, 1/Scene.</div>
			<div class="description">
				This does not cost a psyche burst to use.
Overcharge a sinmark you possess with psychic
energy and detonate it in a ½ CAT area, creating
a small but powerful explosion that damages
structures and living beings in the area. The
selected sinmark is destroyed temporarily, and
the body part it occupies becomes mutilated. For
the rest of the mission you do not benefit from
any of that sinmark’s abilities, and any roll
involving that body part is hard by default
without set-up or teamwork. After the mission is
over, you can adjust to your disability and this no
longer has an effect on you (determine with
Admin how your character heals). No matter
what, your sinmark remanifests before the
next mission.<br><br>
If use of this power would be risky or unclear, or
inflict harm, roll PSYCH, adding +1D if the
sinmark you destroyed was evolved.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
		<div class="power" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #df5c42; left: calc(270% + 10px);">
			<div class="tooltip-title">METAMORPHOSIS</div>
			<div class="tags">Enhancement</div>
			<div class="description">
				If you roll for PSYCHE using this
power, gain +1D for every ability that
sinmark possessed (max +3D) .
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">APOTHEOSIS</div>
		<div class="power">
			<div class="tooltip-title">APOTHEOSIS</div>
			<div class="tags">Self, 1 Scene, 1/Scene</div>
			<div class="description">
				<b>Passive:</b> Lower your sin cap by 2 and roll to gain
a sin mark when you gain this power. This mark
does not count towards your resistance rolls.<br><br>
<b>Active:</b> Transform and enhance the abilities of your
cursed flesh. Select one sin ability you currently
possess. For the rest of the scene, you may select 1
more sin ability that manifests from the same mark as
your selected one.<br><br>
It manifests as a spreading infection or uncontrollable
growth. This may cause living beings that see you to
become apprehensive or scared, and you may gain +1D
on the next roll that takes advantage of this effect. It
disappears at the end of the scene, melting back into
your flesh. Then gain 1d3 sin.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
		<div class="power" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #df5c42; left: calc(270% + 10px);">
			<div class="tooltip-title">METAMORPHOSIS</div>
			<div class="tags">Enhancement</div>
			<div class="description">
				Instead of selecting 1 sin ability to manifest from the
mark you possess, you gain every sin ability from the
same sin mark as your selected ability. The marked area
becomes a mass of writhing flesh, horrific, and violently
grotesque. When this power ends, roll to gain a sin
mark.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FUSILLADE</div>
		<div class="power">
			<div class="tooltip-title">FUSILLADE</div>
			<div class="tags">Permanent</div>
			<div class="description">
				<b>Passive:</b> Your Blast now only manifests through your
limbs and physical strikes as its range is reduced to
touch. When you use your Blast this way and roll 2 or
more 6’s on a violent or harmful action, you may take
1d3 sin to deal +1 slash as your grace coalesces into a
finite destructive blow.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
		<div class="power" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #df5c42; left: calc(270% + 10px);">
			<div class="tooltip-title">METAMORPHOSIS</div>
			<div class="tags">Enhancement</div>
			<div class="description">
				Gain <b>Active:</b> Once per mission, target a creature with an
immeasurable fury, a flurry of limbs, an unstoppable
barrage. Start with a pool of 6d6 which cannot be added
to in any way. The Admin must answer the following
questions as if they were the targeted creature, removing
a dice for each of the following questions they can
respond “yes” to:<br><br>
• Have you avoided all conflict with the exorcist
up until now?<br><br>
• Are you certain you’ll survive this encounter?<br><br>
• Is there someone or something to block with
nearby?<br><br>
• Is the exorcist hindered, distracted, or under
duress in some way?<br><br>
Then roll the dice, dealing 1 slash per die rolled which
cannot exceed your ½ CAT + 3. If you roll a 6 on any of
the dice, you disfigure the target’s psychic signature,
leaving them concussed and severely dazed until the end
of the scene. This may interrupt threats or easily affect
the parameter of rolls such as difficulty or risk. Then
immediately experience sin overflow and roll to resist.
If you succeed, you become unconscious for the rest of
the scene. Upon failure you Imago.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">ACCELERATE</div>
		<div class="power">
			<div class="tooltip-title">ACCELERATE</div>
			<div class="tags">Charm, Self, 1 Scene</div>
			<div class="description">
				Enhance your speed to extreme capabilities by dipping
into the lingering grace in your body. In addition to any
action you take for the rest of the scene, you may
physically move up to a ½ CAT distance within less than
a second.<br><br>
Once per scene when you take advantage of this speed,
you can make an action roll without any hostile
creatures taking a reaction.<br><br>
This may easily affect the parameter of rolls such as
difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
		<div class="power" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #df5c42; left: calc(270% + 10px);">
			<div class="tooltip-title">METAMORPHOSIS</div>
			<div class="tags">Enhancement</div>
			<div class="description">
				You may trigger this effect twice per scene. You may
trigger it a third time by permanently reducing your sin
cap by 2. You may trigger it a fourth time by instantly
overflowing when the action resolves and giving up.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">STAIN</div>
		<div class="power">
			<div class="tooltip-title">STAIN</div>
			<div class="tags">Transmute, CAT+2 Area, Until Rest</div>
			<div class="description">
				You may trigger this power when you kill a human,
exorcist, or supernatural being. The psychic energy
of the being you just killed is violently mutilated as
a warning for other supernatural beings. Roll
PSYCHE if activating this power on a creature that
has a CAT higher than yours, only expending a
psyche burst on a success.<br><br>
All beings that can perceive grace within a CAT+2
area become immediately aware that you have
killed the target, and all beings with a CAT equal to
or lower than your slain target become
apprehensive and devote resources into avoiding
conflict with you. Supernatural beings with a CAT
higher than your slain target may see this as a
threat, challenge, or territorial dispute, and act
accordingly.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
		<div class="power" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #df5c42; left: calc(270% + 10px);">
			<div class="tooltip-title">METAMORPHOSIS</div>
			<div class="tags">Enhancement</div>
			<div class="description">
				The range of this ability becomes
CAT+2 distance instead. Beings
become apprehensive of you
regardless of CAT.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
