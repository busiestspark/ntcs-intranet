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
<div class="infobox-title">Expiration</div>

<br>
<img src="Expiration Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Expiration** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of air.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">EXHALE</div>
		<div class="passive">
			<div class="tooltip-title">EXHALE</div>
			<div class="tags">Passive</div>
			<div class="description">
				You maintain minor control over the
property of air around you in a ½ CAT area. At
will you can control:<br><br>
- How heavy the air feels, from no resistance
to a light pressure.<br>
- The humidity, from dry to slightly moist.<br>
- The sound of living things breathing, from
silencing it to making it overtly audible.<br>
- Scents in the air, from negating smells to
doubling the strength of existing odors.
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
		<div class="tooltip-title">INCENSE</div> 
		<div class="power">
			<div class="tooltip-title">INCENSE</div>
			<div class="tags">Curse, CAT Distance, 1/Rest</div>
			<div class="description">
				This power does not cost a psyche burst. You
expel or manifest a visible atmospheric vapor or
smoke that floats up to a CAT distance away from
you. Laced with psychic influence, this substance
floats towards the following points of interest that
it approaches, making them clear or obvious:<br><br>
• The traces of supernatural beings other than the
exorcists, objects they may have touched,
footsteps left behind by psychic beings, etc.<br><br>
• Points of fragility in physical structures, stress
fractures, or architectural weak points.<br><br>
• Deceased beings or corpses.<br><br>
Gain or grant +1D when you or any ally next acts
to take advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">REPOSE</div>
		<div class="power">
			<div class="tooltip-title">REPOSE</div>
			<div class="tags">Transmute, CAT Area, 1 Scene</div>
			<div class="description">
				You halt the processes of decay, poisons, and delay death
temporarily up to a CAT area around you. Within this area,
matter that is decaying through either mundane or
supernatural means also temporarily pauses. This may delay
certain hooks or the effects of certain afflictions at admin
discretion.<br><br>
Additionally, when an allied exorcist on the brink of death
within this area takes stress, you may burden yourself with
their potential death and take all stress inflicted instead.<br><br>
This may easily affect the parameter of rolls such as difficulty
or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">OXIDE</div>
		<div class="power">
			<div class="tooltip-title">OXIDE</div>
			<div class="tags">Instant, CAT+1 Distance</div>
			<div class="description">
				Rapidly degrade exposed metals, oxygen, or
flammable materials within range through air
contact, and temporarily perceive anything in
range through air contact. The oxidation affects
an area up to your CAT, and you may choose one
of the following effects:<br><br>
• <b>Flake:</b> Things you select begin to rust away
and flake into red dust, corrode, or age
rapidly, becoming irreparably damaged and
unusable.<br><br>
• <b>Burn:</b> Rapidly oxidize your selected object or
area causing it to ignite instantaneously. This
lasts only for a few moments but completely
destroys whatever you select.<br><br>
If this would cause damage to a hostile target,
roll PSYCHE for it. This may easily affect the
parameter of rolls such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DECOMPOSE</div>
		<div class="power">
			<div class="tooltip-title">DECOMPOSE</div>
			<div class="tags">Charm, Self, 1 Scene</div>
			<div class="description">
				Rapidly decompose inanimate organic matter (corpses,
plants, food, etc.) you touch into its simplest chemical
components. For the rest of the scene, any organic matter
up to CAT in size that you touch breaks down within
seconds into gases, water, and carbon compounds,
forming a thick, dark, unrecognizable sludge. This
substance is highly flammable.<br><br>
Gain or grant +1D to yourself or an ally when taking
advantage of this power while it is in effect.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BLOAT</div>
		<div class="power">
			<div class="tooltip-title">BLOAT</div>
			<div class="tags">Transmute, Touch, 1 Scene, 1/Rest</div>
			<div class="description">
				By touching a living or dead being, you can make it
emanate dangerous fumes within a CAT area. You may
increase the CAT of this power by +1 for every additional
burst you spend on it. This effect lasts for 2d3 minutes if
the target is alive, or for the rest of the scene if the target is
a corpse. When you activate this power, you can choose
the opacity of this gas, ranging from transparent to
opaque smog.<br><br>
This gas can ignite from any source of combustion, such
as fire, a spark, or concentrated heat. The resulting
explosion damages structures and kills or injures any
unprotected humans in the area. Roll PSYCHE for damage
if this would harm a living or supernatural being.<br><br>
You may gain or grant +1D when you or any ally next acts
to take advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
