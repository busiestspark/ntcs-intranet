---
tags: Blasphemy
image: "[[Tension Card.png]]"
blsphID: "1"
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
<div class="infobox-title">Tension</div>

<br>
<img src="Tension Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

**Tension** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the creation and manipulation of tension forces.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">IRON SOUL</div>
		<div class="passive">
			<div class="tooltip-title">IRON SOUL</div>
			<div class="tags">Passive</div>
			<div class="description">
				When you would fill up your
		execution talisman, you may roll 1d6. On a
		4+, go to 1 stress under maximum instead
		and ignore any excess, then lose the use of
		this passive until you rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #8B0000);">
		<div class="tooltip-title">STEEL SOUL</div>
		<div class="quirk">
			<div class="tooltip-title">STEEL SOUL</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You specialize in projecting tension fields
		over bladed weapons. You gain the
		Severance power for free (even past the
		cap of 5 powers). You always use it at +1
		CAT. However, you can only use it while
		wielding a bladed weapon in one or both
		hands.<br><br>
		Additionally, you can project a psychic
		cutting force at short range by rolling
		PSYCHE. This doesn’t cost a psyche burst
		but doesn’t have enough force to
		significantly harm someone - enough to
		sever a strap, cord, or cause minor cuts.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #8B0000);">
		<div class="tooltip-title">SILVER SOUL</div>
		<div class="quirk">
			<div class="tooltip-title">SILVER SOUL</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Your body is infused with psychic fields that
		are stronger when you follow your
		convictions, and weaker when you don’t.
		<br><br>When you end a conflict scene, you
		automatically erase 1 stress if you followed
		any agenda item in that scene. If you didn’t
		follow any, gain 2 nonlethal stress instead.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #8B0000);">
		<div class="tooltip-title">LEAD SOUL</div>
		<div class="quirk">
			<div class="tooltip-title">LEAD SOUL</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Your body is suffused with tension fields
		that make you extremely dense, heavy, and
		tough. Your weight is tripled and only
		forces 2 categories higher than your
		current category can move you against
		your will. Your unarmed strikes count as
		service weapons (and can be upgraded). In
		addition, you can only take a maximum of 1
		stress from falling or impacts from vehicles
		or objects, no matter the category.
		<br><br>In return, actions that require you to move
		quickly are hard for you by default.
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
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">AEGIS</div> 
		<div class="power">
			<div class="tooltip-title">AEGIS</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				When you or a visible ally in short range of you
	would mark stress from external harm, you can
	intervene by answering the following questions:<br><br>
	• Can you reach your target in time?<br><br>
	• Is there any part of the environment you can
	use to shield your target?<br><br>
	• Is your heart in this?<br><br>
	You create a flash tension field of incredible
	strength, blocking damage. For each ‘yes’
	answer, roll 1d6. For every 2+ rolled reduce
	stress suffered by 1, and for every 6 rolled
	reduce it by 2. This could reduce stress suffered
	to 0.<br><br>
	After using this power, lose its use until you
	rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">STASIS</div>
		<div class="power">
			<div class="tooltip-title">STASIS</div>
			<div class="tags">1 Scene, Curse, Short</div>
			<div class="description">
				With a gesture, you can lock yourself or a CAT
sized group of humans or exorcists in a tension
cage that covers them like a second skin,
paralyzing them. If a human is hostile or unwilling,
roll PSYCHE, and only spend the burst on success.<br><br>
Once trapped, your target is locked in, unable to
move or act for the scene, and is immune to all
harm and effects from the outside. The effect only
ends once the scene passes and you cannot end it
earlier. They can be moved around like a (very stiff)
object and are fully sensate while inside, though
they can see as though looking through a thick
pane of glass and don’t need to breathe.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SEVERANCE</div>
		<div class="power">
			<div class="tooltip-title">SEVERANCE</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				You can project a tension field of incredible
strength over any edge, as obvious as a
blade and as subtle as a fingernail, and use it
as a cutting implement. Roll PSYCHE to cut
an object or opponent with a clean and
decisive blow, only spending a psyche burst
on success.<br><br>
• Gain +1D if you are striking to protect
another person<br><br>
• Gain +1D against immobile objects or
opponents
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">MALLEATE</div>
		<div class="power">
			<div class="tooltip-title">MALLEATE</div>
			<div class="tags">Until Rest, Transmute, Adjacent</div>
			<div class="description">
				You can invert and infuse a tension field to make
an area of nonliving matter incredibly pliable and
soft. The size of this block of matter you can
affect is affected by CAT. Choose one of the
following effects, then you may gain or grant +1D
when you or any ally next acts to take advantage
of this power:<br><br>
• <b>Rubber:</b> The matter becomes bouncy and
springy<br><br>
• <b>Mud:</b> The matter melts into a thick mud. It
becomes pliable and sticky and difficult to
move through<br><br>
• <b>Liquid:</b> The matter melts into liquid<br><br>
This power may easily affect the parameters of
rolls, such as difficulty and risk. When the effect
expires, the matter slowly reverts to its original
state and form.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FORTRESS</div>
		<div class="power">
			<div class="tooltip-title">FORTRESS</div>
			<div class="tags">Until Rest, Summon, Short</div>
			<div class="description">
				Once a scene, you can create a spot tension field
with a size determined by up to CAT that appears
as a large plane of shimmering force, invisible to
humans. It can only exist as a flat plane (no bends
or curves), and intersect or overlap any nonliving
material, but otherwise is as hard as a solid object
and prevents all living and nonliving matter and
energy from crossing it. It has a 2+CAT talisman
for its durability, which can take damage and be
ticked up like an execution talisman by opponents.
The field lasts until destroyed, until used again, or
until rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>
