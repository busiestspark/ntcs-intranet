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

	background: linear-gradient(145deg, #466f00, #76ba00);

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
	background-image: linear-gradient(145deg, #466f00, #76ba00);
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
<div class="infobox-title">Melt</div>

<br>
<img src="Melt Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Melt** is a mirrored [[Blasphemies|Blasphemy]].

It is concerned with the power of corrosion.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">SO THE SOUL</div>
		<div class="passive">
			<div class="tooltip-title">SO THE SOUL</div>
			<div class="tags">Passive</div>
			<div class="description">
				Your psychic influence is highly
corrosive, both mentally and physically.
When using psyche for minor effects,
they may also:<br><br>
- Melt or corrode small bindings such as
rope or handcuffs touching you.<br>
- Chemically burn the surface of
someone else's skin upon touch.<br>
- Once per scene, make a mundane
human feel weak or dizzy in your
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
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TOXIN</div> 
		<div class="power">
			<div class="tooltip-title">TOXIN</div>
			<div class="tags">Summon, Touch</div>
			<div class="description">
				Produce a small dose of potent neurotoxin from any area of skin
on your body, palm, fingers, lips, etc. You may choose to release
this toxin into a container or different medium such as food or a
syringe, or allow it to linger on your skin. This neurotoxin affects
mundane beings instantly upon contact or consumption. Choose
the toxin to have one of the following effects:<br><br>
<b>Paralytic:</b> The victim is paralyzed completely, unable to take any
physical actions or movements.<br><br>
<b>Hallucinogen:</b> The victim experiences vivid and realistic
hallucinations which may hinder or stagger them.<br><br>
<b>Lethal:</b> The victim dies, as the toxin shuts down their primary
bodily functions.<br><br>
You may roll PSYCHE to attempt to effect a psychic being with
your toxin, spending a burst regardless of success. Upon
success, the toxin only has half the normal effects it would on a
mundane being, either partially paralyzing them, rendering
hallucinations mild, or injuring them as opposed to killing them
outright.<br><br>
This may easily affect the parameter of rolls such as difficulty or
risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SLIP</div>
		<div class="power">
			<div class="tooltip-title">SLIP</div>
			<div class="tags">Charm, 1/Scene</div>
			<div class="description">
				Dissolve your presence, making you harder
to perceive or physically restrain. A thin
psychic membrane forms over your skin,
making you physically slippery and near
impossible to grab or restrain. Additionally,
your words and presence slide off the
consciousness, reducing the difficulty of
actions to hide from, escape, or avoid
others. Mundane beings may get mild
headaches or lose their train of thought
when attempting to focus on you or the
words you say.<br><br>
Gain or grant +1D to the next action you or
your allies make to take advantage of this
power. This power may easily affect the
parameter of rolls such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SOFTEN</div>
		<div class="power">
			<div class="tooltip-title">SOFTEN</div>
			<div class="tags">Curse, Touch</div>
			<div class="description">
				Mold someone’s mind in your hands like
putty. A mundane human being in your
touch immediately becomes unable to focus
on anything except for the sensation of your
skin while you are speaking to them. While
touching them, you can suggest a course of
actions that are not outright harmful to
themselves, such as “drive the car down this
street” or “unlock the password on this
computer”, and they will willingly do so to
their best ability. When you stop touching
them this power ends.<br><br>
This may easily affect the parameter of rolls
such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CLOUD</div>
		<div class="power">
			<div class="tooltip-title">CLOUD</div>
			<div class="tags">Transmute, CAT Area, 1 Scene</div>
			<div class="description">
				Subtly spread your psychic influence
through the air up to a CAT area centered
on yourself. All mundane objects of your
choice within this range begin to degrade
and slough off as if exposed to a strong
acid including buildings, weapons, gear,
or clothing. Breathing in the air may be
painful to mundane living beings.<br><br>
Gain or grant +1D to the next action you
or your allies make to take advantage of
this power. This power may easily affect
the parameter of rolls such as difficulty or
risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CAUSTIC</div>
		<div class="power">
			<div class="tooltip-title">CAUSTIC</div>
			<div class="tags">Permanent</div>
			<div class="description">
				<b>Passive:</b> Your blood is highly corrosive to everything other
than your own body, able to melt most things. Mundane
harmful or violent actions that pierce your skin deal -1
stress (taking a minimum of 1 stress) as your blood melts
and singes the resulting attack. Blades corrode, bullets
dissolve, and unprotected fists against your blood may
recoil back in pain.<br><br>
<b>Active:</b> You may also choose to take 1d3+1 stress at any
time to bite a part of your mouth to bleed, and spray it out
in a caustic spray which may dissolve or burn living beings
or objects it touches. While injured, you may reduce the
stress cost for this action by a number equal to your
current number of injuries, as you pool blood from your
bleeding body.<br><br>
If necessary, roll PSYCHE for effects that would be risky,
unclear, or inflict harm. When you or an ally next acts to
gain advantage of this power’s active ability, they may
gain +1D.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
