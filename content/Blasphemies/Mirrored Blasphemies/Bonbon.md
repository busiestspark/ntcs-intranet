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

	background: linear-gradient(145deg, #6f2d5c, #c24fa1);

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
	background-image: linear-gradient(145deg, #6f2d5c, #c24fa1);
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
<div class="infobox-title">Bonbon</div>

<br>
<img src="Bonbon Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Bonbon** is a mirrored [[Blasphemies|Blasphemy]].

It is concerned with the power of consumption.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">AS THE UNIVERSE</div>
		<div class="passive">
			<div class="tooltip-title">AS THE UNIVERSE</div>
			<div class="tags">Passive</div>
			<div class="description">
				You are always able to spend 1
kp to produce a small candy of your
choice. Consuming it relieves (1-3):
nothing (4+): 1 stress. Some of your
powers inflict the Overdose hook.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #c24fa1">
		<div class="tooltip-title">OVERDOSE</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #c24fa1">
			<div class="tooltip-title">OVERDOSE</div>
			<div class="tags">Hook</div>
			<div class="description">
				When this hook fills up, gain the
following affliction:<br><br>
<b>Overdose:</b> Your body is overfilled
with psychic chemicals which abuse
your dopamine receptors and impair
your sense of reality. Actions that
require concentrated or focused
thinking are always hard by default
unless assisted by set-up or
teamwork. You may choose to take
1d3 non-lethal stress to ignore the
difficulty penalty on any specific roll.
If you take a hook for this affliction
while you have it, you take 1d3 stress
instead per tick inflicted. This
affliction disappears after you rest.
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
		<div class="tooltip-title">ADDICTION</div> 
		<div class="power">
			<div class="tooltip-title">ADDICTION</div>
			<div class="tags">Curse, Short, 1 Scene, 1/Rest</div>
			<div class="description">
				You may activate this power without spending a
psyche burst. You trigger this power when a being in
range consumes or imbibes in anything ranging from
water to food or drugs. Upon activation, the target
becomes helplessly addicted to the substance they
consumed or imbibed, experiencing intense
withdrawal symptoms when not indulging in it after a
few minutes. They may become desperate to the
point of harmful or violent actions towards others or
themselves.<br><br>
Gain or grant +1D to the next action you or your allies
make to take advantage of this power. 
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CRUNCH</div>
		<div class="power">
			<div class="tooltip-title">CRUNCH</div>
			<div class="tags">Transmute, Short, 1 Scene, 1/Scene</div>
			<div class="description">
				Once per scene you may target an object or living
being up to CAT size. For the duration of this
power the target becomes metaphysically edible to
any living being. The physical composition of the
target does not change, but the teeth of other
beings pass through it with ease, as if it were
made of sugar, and bites of the target taken this
way dissolve easily in the mouth. This may render
objects inoperable if biting off an important piece
of an object or leave injuries on living beings.<br><br>
If the target was mostly consumed, gain the
Overdose hook. If the target was fully consumed,
gain the hook twice instead. Mundane beings that
eat an affected target are inflicted with high levels
of blood sugar and subsequent heart palpitations.<br><br>
This may easily change the parameter of rolls such
as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">INFLUENCE</div>
		<div class="power">
			<div class="tooltip-title">INFLUENCE</div>
			<div class="tags">Curse, CAT Area, 1 Scene</div>
			<div class="description">
				Every living being of your choice within a CAT
area of you becomes immediately inebriated,
as if drunk or high. This renders their ability-
making abilities sporadic or uncontrolled,
induces loss of certain motor functions, and
sustains any other effects an inebriant such
as alcohol or drugs may have on a living
being. You may take the Overdose affliction
hook up to two times to increase the CAT of
this power by +1 per hook taken.<br><br>
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
		<div class="tooltip-title">CAPTIVATE</div>
		<div class="power">
			<div class="tooltip-title">CAPTIVATE</div>
			<div class="tags">Transmute, Short, 1 Scene</div>
			<div class="description">
				Fill a living being or object up to CAT size
in range with irresistible psychic energy,
forcing all mundane living beings who can
perceive the target to become obsessed
with it. When attempting to exert this
influence on a supernatural being while
this power is active, roll PSYCHE to
determine success. Beings may fight one
another over the target or go to great
lengths to claim or obtain it.<br><br>
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
		<div class="tooltip-title">SPIKE</div>
		<div class="power">
			<div class="tooltip-title">SPIKE</div>
			<div class="tags">Charm, Short, Instant, 1/Scene</div>
			<div class="description">
				Flood a living being’s bloodstream with a cocktail of
chemicals and sugars, overloading their nervous system. A
mundane being targeted this way experiences a warm bliss
before experiencing full body convulsions and suffers a fatal
heart attack.<br><br>
When you target yourself or an allied exorcist targeted this
way, your synapses and positive emotions go into overload,
primed for their next action. The next action the target takes
gains +1D (Max +3D) for each of the following questions they
can answer “yes” to:<br><br>
- Have you indulged in a vice this scene?<br><br>
- Is this a feeling you’re willing to chase again?<br><br>
- Have you recently suffered and are desperate for relief?<br><br>
The target gains the Overdose hook once for every question
they could answer “yes” to. If this fills out the Overdose
affliction hook, they may have it replace an affliction they
currently have that affects their mental or emotional state.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
