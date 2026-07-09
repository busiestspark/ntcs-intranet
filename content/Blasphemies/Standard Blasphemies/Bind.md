---
tags:
  - Blasphemy
image: "[[Bind Card.png]]"
blsphID: "9"
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

	background-image: linear-gradient(145deg, #000020, #00008B);

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
	background-image: linear-gradient(145deg, #000020, #00008B);
}

.quirk {
	background-image: linear-gradient(145deg, #200020, #00008B);
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
<div class="infobox-title">Bind</div>

<br>
<img src="Bind Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

<div style="padding-right: calc(400px);">
<div style="color: red; border: 1px solid red; padding: 1rem; width: 90%;" margin-right: 1rem;"">⚠ WARNING<br><br>BINDING IS A HERETICAL PRACTICE AND IS PUNISHABLE BY IMMEDIATE EXECUTION. ONLY REGISTERED EXORCISTS WITH PROPER AUTHORIZATION ARE APPROVED TO PRACTICE BINDING.</div> 
</div>

**Bind** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the binding of Sins and other psychic entities as familiars. 

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">SIN BINDING</div>
		<div class="passive">
			<div class="tooltip-title">SIN BINDING</div>
			<div class="tags">Passive</div>
			<div class="description">
				You have the forbidden ability to bind Sins. You
have the obedient essence of a minor sin bound to you,
under your control.<br><br>
Your <b>Bound Sin</b> is animalistic in form and
ability - you can determine what form it
takes. It can understand language but cannot
speak, and is invisible to humans.<br><br>
It can follow you around at short distance,
follow simple orders, and uses your skills to
do anything. Its general capabilities are CAT
0.<br><br>
If it takes any stress, it is banished for the
remainder of the scene, however you can
psychically absorb all stress taken for it
instead to prevent this effect.<br><br>
In a conflict scene, you may sacrifice your
ability to act on your turn to allow your sin to
act instead, giving it commands. Otherwise it
doesn’t act independently in these scenes.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<div class="tooltip-title">SIN EVOLVE</div>
		<div class="passive">
			<div class="tooltip-title">SIN EVOLVE</div>
			<div class="tags">Passive</div>
			<div class="description">
				Your bound sins increase in ability as you gain category.<br><br>
• <b>CAT 2+:</b> Your sins gain the ability to speak and develop a
humanlike intelligence. Only psychically sensitive people
can hear them.<br><br>
• <b>CAT 3+:</b> Your sins can take on a humanlike form, or take
on a larger animal-like form, or switch between these forms.
Both forms are still only visible to exorcists and other sins,
and are purely aesthetic.<br><br>
• <b>CAT 4+:</b> Your bound sins can appear visible and audible to
humans. Graceless humans typically find this traumatic (roll
PSYCHE for any effects).<br><br>
• <b>CAT 5+:</b> You can have two active sins out at once. Any
action you take with them must apply to one or the other.
Failing to absorb stress for an action taken by a sin
banishes both of them.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip">
		<div class="tooltip-title">MENAGERIE</div>
		<div class="passive">
			<div class="tooltip-title">MENAGERIE</div>
			<div class="tags">Passive</div>
			<div class="description">
				When you defeat a sin during a hunt, you may bind it as a new
bound sin during a rest. This applies even for minor sins or foes
with the type ‘sin’, such as Traces. Doing so typically requires
approval from the Temerity Office of Stability (which can
sometimes be waived). A captive sin is mechanically identical to
your original bound sin but may differ in aesthetics and
personality. You can swap your active bound sin in and out,
including your original bound sin, and keep up to six. Inactive
sins retract into a dormant state inside your sin seed.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #00008B);">
		<div class="tooltip-title">WRETCHED HOST</div>
		<div class="quirk">
			<div class="tooltip-title">WRETCHED HOST</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You <b>don’t have a bound sin.</b> Instead, you are a former type II sin
host, where the sin is fused to your flesh and is part of you.<br><br>
You gain the <b>Surrender</b> blasphemy power for free, it loses the
charm tag, and its effects can stack up to three times on you.
Instead of costing Psyche burst, it always costs 1 sin to activate.<br><br>
All powers that would apply to your sin instead apply to you, and
physically transform you.
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
		<div class="tooltip-title">SIN STRIKE</div> 
		<div class="power">
			<div class="tooltip-title">SIN STRIKE</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				You can command an active sin
to attack by spending a psyche
burst as long as both your sin
and its target are in range, and
you can communicate with it.
Roll PSYCHE for its effects. The
attack has supernatural
potency.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">HORDE SPIRIT</div> 
		<div class="power">
			<div class="tooltip-title">HORDE SPIRIT</div>
			<div class="tags">1 Scene, Self</div>
			<div class="description">
				You empower your sin for one scene. The next
time it takes action for traversal or movement, it
gains +1D. As part of this action:<br><br>
• You can transform it into the form of a
vehicle or rideable creature of up to CAT
size for the rest of the scene. It can go
about CAT speed, becomes partly visible to
humans and has room for a ½ CAT size
group of human or exorcist passengers.<br><br>
• It can glide a short distance while in
vehicle form, with or without passengers
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">FORBIDDEN SPIRIT</div>
		<div class="power">
			<div class="tooltip-title">FORBIDDEN SPIRIT</div>
			<div class="tags">Instant, Self</div>
			<div class="description">
				You can empower your sin for one action. As
part of this action:<br><br>
• You lift limiters on your spirit. The action
gains +1D and causes it to undergo a
monstrous transformation similar to its
original form. It becomes a size equal to
CAT+1 and can easily move, lift, strike, or
throw objects or beings of an equal size. Roll
PSYCHE for its effects. After the action, it
reverts to its normal size.<br><br>
• When absorbing stress for your sin as a
conseqeuence of this action, take 1 less.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">HUNTER SPIRIT</div>
		<div class="power">
			<div class="tooltip-title">HUNTER SPIRIT</div>
			<div class="tags">1 Scene, Self</div>
			<div class="description">
				You empower your sin for one scene. The next time it
takes action for tracking or observation, it gains +1D.
As part of this action:<br><br>
• It can now separate from you up to extreme range
when released<br><br>
• You can communicate telepathically with it<br><br>
• It gains the ability to fly and see and smell
extremely well - it can also see in the dark and in
the thermal spectrum, and clearly up to long
range.<br><br>
• You can concentrate, dissociating from your body,
and becoming extremely vulnerable. While
concentrating this way, however, you can use
your sin’s senses instead of your own. You can
engage and disengage this effect at will for the
scene.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SURRENDER</div>
		<div class="power">
			<div class="tooltip-title">SURRENDER</div>
			<div class="tags">Until Rest, Charm, Self</div>
			<div class="description">
				You draw on your sin’s energy to partially fuse with
its essence. Your body mutates slightly to
accommodate this change. Immediately manifest a
temporary sin mark and roll for the location and
ability, which you gain until you end this ability early
or rest. You may gain 1 sin to re-roll the mark ability,
any number of times, any time while this power is
active.<br><br>
If you hit sin overflow while this effect is active and
successfully resist, you manifest the chosen sin mark
permanently instead of rolling for it.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PENUMBRA</div>
		<div class="power">
			<div class="tooltip-title">PENUMBRA</div>
			<div class="tags">Until Rest, Summon, Adjacent</div>
			<div class="description">
				You create an area drawn as a large circle, encircling
up to a CAT+1 size area, and choosing a type from the
below list. The prison takes only a moment to create,
but takes a few minutes to activate and for its effects
to take place. It lasts until you rest or until used again.<br><br>
• A <b>white mantle</b> prevents entrance by Sins, but
allows humans and exorcists to pass normally.<br><br>
• A <b>black mantle</b> prevents entrance by humans or
exorcists. In addition, humans will (generally) be
unable to see into the area and will act as if the
area doesn’t exist.<br><br>
• You can invert this effect if you so choose,
preventing exit instead of entrance.<br><br>
The prison can be broken by a determined
supernatural attacker, but has a 4+CAT talisman for
durability, taking stress like an execution talisman.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>