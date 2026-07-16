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

	background: linear-gradient(145deg, #202020, #505050);

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
	background-image: linear-gradient(145deg, #202020, #505050);
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
<div class="infobox-title">Husk</div>

<br>
<img src="Husk Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Husk** is a mirrored [[Blasphemies|Blasphemy]].

It is concerned with the things left behind by living beings.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">SO WITHOUT</div>
		<div class="passive">
			<div class="tooltip-title">SO WITHOUT</div>
			<div class="tags">Passive</div>
			<div class="description">
				You are empty. You do not bleed and are
resistant to mundane pain. You do not need to breathe.
You lack a psychic presence through the perception of
other beings and cannot have your mind read or entered.
Whenever you gain sin marks they are never visible and
when you imago you become a <b>Shell</b> instead.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #505050">
		<div class="tooltip-title">SHELL</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #505050">
			<div class="tooltip-title">SHELL</div>
			<div class="tags">Object</div>
			<div class="description">
				<i>Something once alive, now empty.</i><br><br>
<b>Shell(sin):</b> Execution Talisman 1<br><br>
<i>Shells do not move from the location they
were birthed and will crumble at attempts
to move them.<br><br>
They take on a form of the exorcist’s choice,
but are almost always paper thin and
empty regardless of size.</i><br><br>
<b>Reactions:</b><br><br>
<b>Silence (1-6):</b> One exorcist may observe
the Shell and relive a memory they had
with the exorcist that birthed the Shell.
They take 1 non-lethal stress.
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
		<div class="tooltip-title">CHAFF</div> 
		<div class="power">
			<div class="tooltip-title">CHAFF</div>
			<div class="tags">Summon, Short</div>
			<div class="description">
				Leave behind psychic husks that are even
visible to the mundane. Select yourself or any
other sentient being that you can touch. You
create a number of near-identical duplicates of
your target equal to your ½ CAT. You can place
them anywhere within range and move them as
you please, but they cannot move on their own
and cannot emote or speak. They can however
be placed in a way that defies gravity such as
on ceilings or walls without difficulty. When a
creature other than you touches them, the
duplicate is revealed to be hollow and paper
thin before it crinkles away.<br><br>
For the first time in a scene when you would
take stress after triggering this power and a
husk of yourself is still intact, you may negate
that instance of stress and crumple away,
having been a husk all along. The husk of your
body that is still intact is revealed to be you. You
cannot trigger this against severe attacks.<br><br>
This may easily affect the parameter of rolls
such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">MOLT</div>
		<div class="power">
			<div class="tooltip-title">MOLT</div>
			<div class="tags">Instant, 1/Mission</div>
			<div class="description">
				Molt from your own skin, leaving behind
everything you once were. When you use this
ability you must do so as a reaction to taking 3
or more stress at once OR by taking 2 stress.
Shedding your skin allows you to remove one
affliction of choice on yourself and also restores
limbs and removes scars that have been
afflicted on previous missions (limbs loss or
scars afflicted on the current mission will not be
removed.)<br><br>
Roll PSYCHE. On a failure, you must answer the
following question truthfully: What is an
important memory you have? The admin
removes that memory from you.<br><br>
Gain or grant +1D on the next action that takes
advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">THIN</div>
		<div class="power">
			<div class="tooltip-title">THIN</div>
			<div class="tags">Transmute, CAT Area, 1 Scene</div>
			<div class="description">
				You drastically thin the air in a CAT area
centered on yourself:<br><br>
- Humans inside asphyxiate and die in minutes<br><br>
- Supernatural beings, including exorcists, that
need to breathe find it hard to function or
focus.<br><br>
- Fire and other sources of combustion are
snuffed out and cannot be reignited<br><br>
- Exorcists suffer 1 stress after taking an action
if they need to breathe.<br><br>
Gain or grant +1D to actions that take
advantage of this power while it is in effect. This
power may easily effect the difficulty of rolls
such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DISEMBOWEL</div>
		<div class="power">
			<div class="tooltip-title">DISEMBOWEL</div>
			<div class="tags">Transmute, Short, 1/Scene</div>
			<div class="description">
				Pull everything meaningful out of something or
someone. Select a human being or an object with
internal components up to your CAT+1 in size. For a
human target you may pull out either:<br><br>
- A vital organ of choice which teleports into your
hand, causing them to die of injuries if relevant.<br><br>
- One important memory or feeling of the admin’s
choice which you can analyze. This leaves the
target insensate, motionless, and emotionless
until you return it or when they are no longer in
range. They may return disoriented, confused,
and scared.<br><br>
For an object you pull out a vital component of it such
as the engine of a car or the sim card inside of a cell
phone. You may specify what you target when you
use this ability and the Admin determines the final
results. Gain or grant +1D to the next roll that takes
advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DREAD</div>
		<div class="power">
			<div class="tooltip-title">DREAD</div>
			<div class="tags">Curse, CAT Distance, 1 Scene</div>
			<div class="description">
				Select a target within range that you can see. For
as long as you can maintain line of sight with the
target, both of you become unable to see,
perceive, or communicate with any other living
beings except for each other. This may cause
humans to feel confused, scared, or a deep sense
of dread. In a conflict scene your target may
target you more or create complications and
threats focused around you.<br><br>
Gain or grant +1D to the roll that takes advantage
of this power. This power may easily affect the
parameter of rolls such as difficulty or risk.<br><br>
This effect ends early if you take an injury and
have 2 or more injuries as a result.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
