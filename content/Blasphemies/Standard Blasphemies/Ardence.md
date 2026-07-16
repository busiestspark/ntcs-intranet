---
tags: Blasphemy
image: "[[Ardence Card.png]]"
blsphID: "2"
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

	background: linear-gradient(145deg, #200000, #8B0000);

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
	background-image: linear-gradient(145deg, #200000, #8B0000);
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
<div class="infobox-title">Ardence</div>

<br>
<img src="Ardence Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

**Ardence** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the explosive application of heat and the manipulation of thermal energy.
# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">INNER FURNACE</div>
		<div class="passive">
			<div class="tooltip-title">INNER FURNACE</div>
			<div class="tags">Passive</div>
			<div class="description">
				You can take an Unstable Power hook as part of
using any Ardence power to increase the CAT of the power
up to +2. When the hook fills up, you burn up from the
inside, gaining an injury and ending the hook. If this injury
would kill you, you explode in an area equal to your CAT,
annihilating yourself and everything inside in a massive
explosion. Nothing can survive this.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #101010);">
		<div class="tooltip-title">VOID FURNACE</div>
		<div class="quirk" style="background-image: linear-gradient(145deg, #200020, #101010);">
			<div class="tooltip-title">VOID FURNACE</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Your powers focus on the cold at the end of the universe, the fathomless
emptiness of entropy. This changes the following:<br><br>
• <b>Pallor:</b> You are always cold to the touch and can’t be warmed up. You can’t
suffer negative effects or harm due to cold weather or temperature (even
extreme cold), but you still feel it. You subtract 1 from all your resting rolls if the
area where you are resting isn’t warm.<br><br>
• <b>Void Affinity:</b> No power you take can ever produce heat.<br><br>
• <b>Rise from Abyss:</b> Your powers from this blasphemy increase in potency
increase the closer you are to death. They gain +1 CAT in all capabilities if you
have an injury, a further +1 CAT if you have two or more, and a further +1 CAT if
another exorcist has died this mission.<br><br>
• <b>Collapse:</b> If you die, your body snap freezes and begins collapsing into a non-
space. Touching it without protection can inflict incredible harm from the cold
(around 3-4 stress). It will require special removal by CAIN, therefore it cannot be
recovered by your compatriots.<br><br>
Replace <b>Fury</b> with <b>Blackmatter</b>.<br><br>
Replace <b>Sabre</b> with <b>Nihil</b>.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010);">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BLACK MATTER</div>
		<div class="power" style="background-image: linear-gradient(145deg, #000000, #101010);">
			<div class="tooltip-title">BLACK MATTER</div>
			<div class="tags">Instant, Long</div>
			<div class="description">
				You instantly disperse heat in an area,
creating a killing flash freeze at a location in
range with a blast area up to ½ CAT. This
inflicts harm on anything living in the area
and instantly freezes liquids and
environments, causing damage. Roll
PSYCHE for its effects, and only spend a
psyche burst on success.<br><br>
When you use this power, you may inflict 1
nonlethal but irreducible stress on yourself
to gain +1D on the roll as your body partly
freezes over. If you do, increase the
nonlethal stress suffered the next time you
use this power by +1. This effect stacks but
resets when you rest.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010);">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">NIHIL</div>
		<div class="power" style="background-image: linear-gradient(145deg, #000000, #101010);">
			<div class="tooltip-title">NIHIL</div>
			<div class="tags">Instant, Melee</div>
			<div class="description">
				By placing your palms outwards, you release
a terrifying annihilative force at hand’s reach,
affecting a base 1/2 CAT area immediately
adjacent to you. Roll PSYCHE for its effects,
and only spend a psyche burst on success.
This force is tremendous but slow, giving it the
following:<br><br>
• It gains +2D when rolling to blast
through immobile targets (living or
nonliving), walls, constructions, or
inanimate objects.<br><br>
• Unless you are set up by another
exorcist, using this power when a roll is
risky is always hard
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
		<div class="tooltip-title">FURY</div> 
		<div class="power">
			<div class="tooltip-title">FURY</div>
			<div class="tags">Instant, Long</div>
			<div class="description">
				You can create a fierce blast of destructive
energy at a location in range with a blast
area up to CAT. When you use this power,
roll PSYCHE and answer the following
questions, gaining +1D for each ‘yes’ answer,
only spending a Psyche Burst on success.<br><br>
• Are you willing to cause indiscriminate
harm, not caring what you destroy, burn,
or incinerate?<br><br>
• Are you willing to let your anger control
the outcome?<br><br>
Whatever question you answer ‘yes’ on, it
affects the outcome of the action - no matter
the roll. In addition, if you answered at least
one ‘yes’, the area is ALWAYS equal to max
CAT, and allies in the area or in short
distance to you take 2 stress, which cannot
be ignored.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">VOID</div>
		<div class="power">
			<div class="tooltip-title">VOID</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				You create a flash vacuum by burning the air away.
The void creates a loud thunderclap, affecting an
area up to CAT, excluding you. Choose one of the
following effects, then you may gain or grant +1D
when you or any ally next acts to take advantage of
this power:<br><br>
• <b>Weak:</b> Sucks in loose objects not held, worn, or
bolted down.<br><br>
• <b>Medium:</b> All humans and exorcists in the area
are thrown off their feet and pulled in, excluding
you.<br><br>
• <b>Strong:</b> Sins and vehicles up to CAT size are
thrown off balance or pulled depending on their
size. Glass is shattered. The thunderclap is
momentarily deafening.<br><br>
This power may affect the parameters of rolls, such
as difficulty and risk.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">HELL</div>
		<div class="power">
			<div class="tooltip-title">HELL</div>
			<div class="tags">Until Rest, Transmute, Adjacent</div>
			<div class="description">
				You may dump energy into the ground and anything
touching the ground in an area determined by
CAT+2, choosing hot or cold. Choose one of the
following effects, which lasts until you rest. You may
gain or grant +1D when you or any ally next acts to
take advantage of this power:<br><br>
• <b>Simmer:</b> Discomfort for humans, lowered or
raised temperature, hot or cold surfaces, etc.<br><br>
• <b>Poach:</b> Major discomfort for humans, who
cannot remain in the area, and discomfort for
sins and exorcists. Freeze or boil water, pipes,
crack glass, etc.<br><br>
• <b>Boil:</b> Deadly to humans, sins and exorcists take
2 stress if they remain in the area for longer than
a scene. Light fires or freeze the air in rooms,
melt windows or burn doors, or freeze objects.<br><br>
This power may affect the parameters of rolls, such
as difficulty and risk.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SABRE</div>
		<div class="power">
			<div class="tooltip-title">SABRE</div>
			<div class="tags">Instant, CAT Range</div>
			<div class="description">
				Release a blast of energy in a highly destructive
beam. The beam goes in a straight line in a range
equal to CAT, piercing through walls, doors, and
obstructions effortlessly. It is extremely loud and
bright. Roll PSYCHE for its effects, only spending
a psyche burst on success.<br><br>
You may optionally lift the limiter on this ability
when using it. If you do, for every ‘6’ result you
roll when using ability, this ability inflicts 1 extra
slash on a talisman, but you also take 2 stress,
which could kill you or cause you an injury. This
stress cannot be reduced or ignored in any way.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div style="color: white; font-size: 2rem; margin-right: 5px;">
		+
		</div>
		<div class="tooltip-title">STORM</div>
		<div class="power">
			<div class="tooltip-title">STORM</div>
			<div class="tags">Entire Hunt, Transmute, Extreme</div>
			<div class="description">
				You can spend any number of psyche bursts to send potential
energy into the atmosphere, affecting a microclimate in an area
equal to CAT+2, with a maximum of CAT 7. Choose one of the
below, plus one more per psyche burst spent. The chosen
effects last for the whole mission or until dismissed.<br><br>
• <b>Clear:</b> Clear the skies in the area, canceling any weather
(including the below).<br><br>
• <b>Rain:</b> Rain drenches the area for the duration of an intensity
you choose (drizzle, pouring, torrential).<br><br>
• <b>Cold:</b> The air freezes, freezing water and icing over roads
and paths. Any precipitation becomes snow.<br><br>
• <b>Fog:</b> Thick fog rolls in, limiting visibility.<br><br>
• <b>Gale:</b> Whipping wind rolls through the area, blowing away
fog, smoke, or dust, and making it hard to hear or be outside.<br><br>
This power may easily effect the parameters of rolls, such as
difficulty and risk.<br><br>
Once used, lose the use of this power until you rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>
