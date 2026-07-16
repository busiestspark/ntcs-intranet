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

	background: linear-gradient(145deg, #9e9e00, #feff01);

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
	background-image: linear-gradient(145deg, #9e9e00, #feff01);
}

.tooltip-title {
	font-family: Cuasigothic;
	font-size: 1.5rem;

	text-align: center;

	background: linear-gradient(gray, black);

	-webkit-background-clip: text;
	background-clip: text;
	
	color: transparent;
}

.tags {
	font-family: Arial;
	font-weight: bold;
	font-style: italic;
	color: rgba(0,0,0,0.8);

	text-align: center;
	
	margin-top: 5px;
}

.description {
	font-family: Arial;
	color: black;
	margin-top: 10px;
}

.credit {
	width: 100%;

	font-family: Arial;
	font-style: italic;
	text-align: right;
	color: rgba(0,0,0,0.6);

	margin-top: 5px;
}
</style>

<div class="infobox" >
<div class="infobox-title">Valence</div>

<br>
<img src="Valence Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Valence** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of bonds.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">ADEPT</div>
		<div class="passive">
			<div class="tooltip-title">ADEPT</div>
			<div class="tags">Passive</div>
			<div class="description">
				When you use a power with the Transmute tag
you may take 2 stress to increase the CAT of that power
by 1. If you do, gain the Hubris hook.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #feff01">
		<div class="tooltip-title" style="background: linear-gradient(white, gray); -webkit-background-clip: text; background-clip: text;">HUBRIS</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #feff01">
			<div class="tooltip-title" style="background: linear-gradient(white, gray); -webkit-background-clip: text; background-clip: text;">HUBRIS</div>
			<div class="tags" style="color: rgba(255,255,255,0.8);">Hook</div>
			<div class="description" style="color: white">
				Your passive gives you this
hook upon activating it. When this
hook fills up, you gain the Hubris
condition. Whenever you use one of
your Transmute or Valence powers
the Admin may:<br><br>
1. Make it select another valid
target within range of you.<br><br>
2. Select a different Transmute
or Valence power you
possess on your intended
target. (You still choose the
effects of the newly selected
power but may not dismiss it
early).<br><br>
3. Reduce its CAT to 0.<br><br>
After the Admin takes this action,
remove this condition.
			</div>
			<div class="credit" style="color: rgba(255,255,255,0.6);">From the Harpocrates Dossier 2.2</div>
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
		<div class="tooltip-title">FUSE</div> 
		<div class="power">
			<div class="tooltip-title">FUSE</div>
			<div class="tags">Transmute, Short, 1 Scene</div>
			<div class="description">
				Bond any surface to another on a molecular
and psychic level. Select 2 targets, which can
be either objects or creatures, but must be
touching each other when you use this power.
Roll PSYCHE when targeting one or more
unwilling targets, only consuming a psyche
burst on a success.<br><br>
You fuse the point of contact between the two
targets. While fused, nothing can remove the
surfaces from one another until the end of the
scene. This does not render either target
indestructible or immune to harm however.<br><br>
Gain or grant +1D when you or any ally next
acts to take advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">ALCHEMY</div>
		<div class="power">
			<div class="tooltip-title">ALCHEMY</div>
			<div class="tags">Transmute, Touch, 1 Scene</div>
			<div class="description">
				Change the composition of anything you can touch.
Touch an object that is equal to your CAT size or smaller.
You may choose to change 1 material of that object [The
copper in an electronic device, water in a cup, the metal
of a car, etc.] and change it into one of the following at
the same temperature of the original material:<br><br>
• Gold<br>
• Iron<br>
• Water<br>
• Glass<br>
• Oxygen<br>
• Mercury<br>
• Salt<br>
• Aluminum<br><br>
This effect only lasts until the end of the scene. Gain or
grant +1D to yourself or an ally when taking advantage of
this power while it is in effect. You may choose a material
not on this list to any approved by your Admin by
activating the Hubris passive for this ability. Based on the
rarity or danger of the material you choose the Admin
may immediately slash your Hubris hook by 1, 2, or 3.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DISSOLVE</div>
		<div class="power">
			<div class="tooltip-title">DISSOLVE</div>
			<div class="tags">Curse, CAT+1 Distance, Until Rest</div>
			<div class="description">
				Disintegrate the bonds between anybody
temporarily. Select two targets that know each
other within CAT+1 range. Other exorcists,
binders, humans, sins, and traces are all valid
targets, including dead ones.<br><br>
Until you rest, the two targets forget everything
they know and remember about each other, as if
they had never met. This temporarily pauses
psychic hooks afflicted by sins or traces until they
are encountered again, sever someone’s psychic
connection to someone else, and makes the
target’s faces and voices unfamiliar to one another.<br><br>
After you rest, both target’s memories return to
normal and all effects of this power end.<br><br>
You are a valid target for this power. If you
choose yourself as a target, you may not end
this effect early.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CATALYZE</div>
		<div class="power">
			<div class="tooltip-title">CATALYZE</div>
			<div class="tags">Instant, CAT Distance, 1/Scene</div>
			<div class="description">
				Psychically remove the space between “now” and “then”, and
accelerate the inevitable. You can speed up or begin any
“reaction”: chemical, kinetic, emotional, within CAT distance to
various effects. Pick one of the following options and describe
your intended course of action, to which your admin
determines its final effects:<br><br>
• <b>Heat:</b> Jump start a potential reaction that normally requires
a trigger or long period of time. This can trigger and
potentially combust dormant materials such as gunpowder,
fuel, or batteries. It may also remove an individual's
hesitation, someone on the verge of acting or speaking
follows through immediately, bypassing doubt or fear.<br><br>
• <b>Chain:</b> Accelerate the strength and propagation of an active
reaction. Explosions, bullets, and chemical reactions are
violently accelerated and may increase in force or effect.
Mild acids accelerate into active corrosives. When applied
to a living being it amplifies a current state of reaction, fear
turning into panic, a moment of relief into fully relaxed, or
spiking adrenaline into dizzying levels.<br><br>
This may easily affect the parameter of rolls such as difficulty or
risk, and may be used alongside your own or your other allies
actions if relevant.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TEMPER</div>
		<div class="power">
			<div class="tooltip-title">TEMPER</div>
			<div class="tags">Transmute, Curse, 1 Scene</div>
			<div class="description">
				Alter the strength and rigidity of emotions and objects alike.
You may choose to target a CAT amount of people within
range or an object equal to your CAT size or smaller. Apply one
of the following effects:<br><br>
• <b>Brittle:</b> A creature’s current emotion becomes less intense,
more prone to change from external influences, and
impacting the decisions of the creature less. An object
becomes extremely brittle, and easier to destroy or break,
anything thin with any weight on it may suddenly break or
shatter.<br><br>
• <b>Harden:</b> A creature’s current emotion becomes more
intense, harder to get rid of or change moods from, and
impacting the decisions of the creature more heavily. An
object becomes dense and durable, much harder to
destroy or break, and can withstand more force than it
normally would.<br><br>
This power may easily affect the parameters of rolls, such as
difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
