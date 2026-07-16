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

	background: linear-gradient(145deg, #083622, #1cc37b);

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
	background-image: linear-gradient(145deg, #083622, #1cc37b);
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
<div class="infobox-title">Guilt</div>

<br>
<img src="Guilt Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Guilt** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with gaining power from guilt and shame.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">PESSIMIST</div>
		<div class="passive">
			<div class="tooltip-title">PESSIMIST</div>
			<div class="tags">Passive</div>
			<div class="description">
				Your max Pathos increases by ½ CAT+1.
You also gain 1 Pathos when you aid an allied exorcist
through set-up or teamwork and they either: fail the
resulting roll ; gain an injury as a result of that action;
or roll a 1 on the final result.<br><br>
When a session ends, you keep half your current pathos
(rounding up) instead of clearing it. You may no longer
activate Divine Agony but instead use Pathos for effects
on the Contrition table and to enhance your abilities.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #1cc37b">
		<div class="tooltip-title">CONTRITION</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #1cc37b">
			<div class="tooltip-title">CONTRITION</div>
			<div class="tags">Table</div>
			<div class="description">
				Spend the indicated amount of Pathos to
activate any of the following effects.<br><br>
(1) Gain +1D on a roll you make.<br><br>
(2) Negate the effects of all afflictions you
have for 2d3 minutes.<br><br>
(3) Regain 1 psyche burst.<br><br>
(6) Take 1d3+1 stress. On your next risky roll
to inflict harm or violence, you deal +2
slashes and roll the risk die twice, taking the
highest number. No one can tell what blood
is yours and what isn’t (1/rest).
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
		<div class="tooltip-title">MARTYR</div> 
		<div class="power">
			<div class="tooltip-title">MARTYR</div>
			<div class="tags">Instant, CAT Range, 1(+)/Scene</div>
			<div class="description">
				Once a scene, you redirect a harmful or violent action
occurring in CAT range that targets another living
being to yourself instead, suffering all effects the
intended targets would have suffered. Then answer
the following questions:<br><br>
- Are you within plain sight of the attacker?<br><br>
- Are you atoning for a previous mistake?<br><br>
- Would the person you’re protecting weep for
you?<br><br>
- Does the person you’re protecting remind
you of someone you couldn’t save?<br><br>
For every yes, reduce the stress you receive from this
action by 1.<br><br>
You may not trigger this against Severe Attacks.<br><br>
If you make a roll with no successes in the same
scene, you may use this power again.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">HEAVY</div>
		<div class="power">
			<div class="tooltip-title">HEAVY</div>
			<div class="tags">Transmute, Close, Until Rest</div>
			<div class="description">
				You temporarily increase the weight of an object
as if it were +1 CAT larger in size. You may spend 1
pathos when you use this power to increase this by
+1 CAT, up to a max of 3 times. You may only target
objects equal to your CAT size or lower. Roll
PSYCHE for creative uses of this power.<br><br>
Gain +1D when you or an ally next acts to take
advantage of this power.<br><br>
This power ends early on all targets if you have 0
pathos at the end of a scene. This power may
easily affect the parameters of rolls, such as
difficulty and risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BLAME</div>
		<div class="power">
			<div class="tooltip-title">BLAME</div>
			<div class="tags">Instant, 1/Rest</div>
			<div class="description">
				When something goes wrong due to someone’s risky
actions, you may supernaturally change the order of
events so that you are somehow at fault. No one except
you remembers the original course of events.<br><br>
When you do so, explain how the consequences are
your fault, and gain 1 pathos for each of the questions
you can answer “yes” to:<br><br>
- Are the consequences severe and difficult to deal
with?<br><br>
- Does the reason why it’s your fault make sense?<br><br>
- Do your allies think you are prone to mistakes?<br><br>
- Could you have prevented things from going
wrong in the first place?
You may choose to gain +1D to your next action to try
and rectify your mistake.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">COLLAPSE</div>
		<div class="power">
			<div class="tooltip-title">COLLAPSE</div>
			<div class="tags">Transmute, 1 Scene</div>
			<div class="description">
				You cause everything to fall apart. In a CAT area
around you, select one of the following effects.<br><br>
- <b>Fall:</b> Objects of your choice of CAT size or
smaller fall apart into their individual pieces, and
cannot be put back together for the rest of the
scene, through supernatural means or
otherwise.<br><br>
- <b>Cease:</b> Inertia slows to a stop for things of your
choice. Cars in motion stop moving, birds drop
to the ground, and objects moving through the
air stop abruptly when launched or fired.<br><br>
- <b>Still:</b> Living beings of your choice find It hard to
find motivation, and often lose their trains of
thought. They become lethargic and fatigued.<br><br>
Gain or grant +1D when you or an ally next act to
take advantage of this power.<br><br>
If you have 0 pathos during this power, it ends
early.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FIZZLE</div>
		<div class="power">
			<div class="tooltip-title">FIZZLE</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				This power does NOT take a psyche burst. You
cause any action you see within range to “fail”,
rolling PSYCHE if targeting a supernatural effect or
action and spending 1 Pathos on a success. You
may not trigger this power against Severe Attacks.<br><br>
This could cause a SINs attack to miss, a gun to
misfire, or a person’s speech to falter in front of a
large crowd. This can range anywhere from
mundane tasks to complicated actions.<br><br>
You may only use this power if you have at least 3
pathos.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
