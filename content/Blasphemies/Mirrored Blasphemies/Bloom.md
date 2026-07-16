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

	background: linear-gradient(145deg, #66394d, #bf6a91);

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
	background-image: linear-gradient(145deg, #66394d, #bf6a91);
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
<div class="infobox-title">Bloom</div>

<br>
<img src="Bloom Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Bloom** is a mirrored [[Blasphemies|Blasphemy]].

It is concerned with growth and living beings.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">AS WITHIN</div>
		<div class="passive">
			<div class="tooltip-title">AS WITHIN</div>
			<div class="tags">Passive</div>
			<div class="description">
				You possess untapped potential. Whenever you
gain sin you relieve the same amount of stress. Whenever
you gain a sin mark you may choose to evolve it for free.
This may stack with other abilities. It is never painful when
you sin overflow.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #bf6a91">
		<div class="tooltip-title">POTENTIAL</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #bf6a91">
			<div class="tooltip-title">POTENTIAL</div>
			<div class="tags">Passive</div>
			<div class="description">
				When you imago, you retain
full control over your new
form and are not hostile to other exorcists
by default until the
end of the mission. After that, the admin
takes control.
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
		<div class="tooltip-title">FLIT</div> 
		<div class="power">
			<div class="tooltip-title">FLIT</div>
			<div class="tags">Charm, 1 Scene, 1/Rest</div>
			<div class="description">
				You pass through attention like the wind. For
the rest of the scene, up to a number times
equal to your ½ CAT, you may make it so that
any action you take does not trigger the
attention or notice of any other being for the
duration of that action. This may allow it so
that reactions from enemies cannot inflict
stress on specifically you during your action,
humans do not notice your presence, or any
other creative uses that may require a
PSYCHE roll. You do not become invisible,
only unimportant for a breath.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Plus Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">METASTASIZE</div>
		<div class="power">
			<div class="tooltip-title">METASTASIZE</div>
			<div class="tags">Instant, Touch, 1/Rest</div>
			<div class="description">
				Transmute the form of a living being into its next
state. When targeting an exorcist you may grant
them a new sin mark or “transform” one of their
existing sin marks, removing one ability of choice on
that mark and rolling per usual to determine the new
one. The selected exorcist may gain 1d3+1 sin during
this transformation to select location first.<br><br>
If selecting a mundane human make a fate roll. (1):
They become a drifter of the Admin’s choice (2-5):
They to suffer degenerative disorders and internal
bleeding as their body rapidly decays (6): They
become psychically sensitive as a sinseed emerges
within their body. You may reroll this die by spending
an additional psyche burst, up to twice.<br><br>
This may easily affect the parameter of rolls such as
difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SCION</div>
		<div class="power">
			<div class="tooltip-title">SCION</div>
			<div class="tags">Charm, Touch, 1 Scene, 1/Rest</div>
			<div class="description">
				This power does NOT cost a psyche
burst to use. Imprint your psychic
signature onto the soul of another willing
exorcist. Select one of your blasphemy
powers or sin marks. You grant an ally in
range your selected option for the
duration of the scene. If granting a
blasphemy power you also temporarily
grant any passive required for the power
to function to your targets. For palaces
and bound sins, you share your own
palace or bound sin instead of generating
entirely new ones. You may choose to
grant an additional choice of blasphemy
power or sin mark by gaining 1 sin, up to
a max of 2 times.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BLOSSOM</div>
		<div class="power">
			<div class="tooltip-title">BLOSSOM</div>
			<div class="tags">Instant, CAT Area, 1/Scene</div>
			<div class="description">
				Cause organic matter of your choice to
violently grow up to a CAT area centered on
yourself. Plant life and vegetation may grow to
extremely large sizes which can change the
scene drastically. Mundane living beings of
your choice inside of this area quickly develop
massive tumors that burst open, age a few
years, and change in physically traumatic ways.
Roll PSYCHE for creative uses of this power.<br><br>
Gain or grant +1D to the next roll that takes
advantage of this power. This may easily affect
the parameter or rolls such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">POLLEN</div>
		<div class="power">
			<div class="tooltip-title">POLLEN</div>
			<div class="tags">Charm, 1 Scene</div>
			<div class="description">
				Summon scales, petals, particulates, or small
flying insects from any part of your body which
you control for the duration. You decide the
appearance and shape of your pollen but it is
always small enough to get through small
cracks or crevices. The total size of the cloud is
no larger than your CAT in size, but you may
control its shape and form at will, even
choosing to separate it into smaller clouds.<br><br>
These clouds can manipulate objects as if they
were your own hands, using your skill checks
when required for rolls, and can travel up to a
far distance away from you. Your cloud can be
used to obscure or hide, to distract other
creatures, or offensively. Roll PSYCHE for
creative uses of this power. If used offensively,
the pollen dissipates and this power ends early
after that action resolves.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
