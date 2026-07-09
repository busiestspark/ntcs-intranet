---
tags:
  - Blasphemy
image: "[[Jaunt Card.png]]"
blsphID: "11"
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

	background: linear-gradient(145deg, #200020, #8B008B);

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
	background-image: linear-gradient(145deg, #200020, #8B008B);
}

.quirk {
	background-image: linear-gradient(145deg, #003030, #8B008B);
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
<div class="infobox-title">Jaunt</div>

<br>
<img src="Jaunt Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

<div style="padding-right: calc(400px);">
<div style="border: 1px solid #00FF00; padding: 1rem; width: 90%;">ⓘ FACT<br><br>Use of Blasphemies on CAIN personnel, even for "recreational purposes", is strictly prohibited.</div>
</div>

**Jaunt** is a standard [[Blasphemies|Blasphemy]].

It is concerned with possession and the manipulation of consciousness.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">GHOSTWIRE</div>
		<div class="passive">
			<div class="tooltip-title">GHOSTWIRE</div>
			<div class="tags">Passive</div>
			<div class="description">
				You can join your mind telepathically with a
number of other willing people you touch equal to
CAT. While within long distance of each other, you can
talk telepathically, and sense each other’s ambient
emotional state. This effect lasts until you use it again,
until someone becomes unconscious, or until you or
another person closes the connection.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #003030, #8B008B);">
		<div class="tooltip-title">CORPUS</div>
		<div class="quirk">
			<div class="tooltip-title">CORPUS</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You specialize in the bodies of the recently
deceased. Once a scene, when you touch a
corpse, you can tell exactly how long ago it
died, and get brief visions of its death,
granting you +1D when next you act on the
answers in the same scene.<br><br>
Additionally, you can use the possession
power on corpses without spending a
psyche burst, and you can use the desecrate
power on living, but unconscious humans.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #003030, #8B008B);">
		<div class="tooltip-title">HOLLOW</div>
		<div class="quirk">
			<div class="tooltip-title">HOLLOW</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You specialize in the incorporeal remnants of
psyche.<br><br>
You can use the Geist blasphemy power
without spending a psyche burst, once
between rests.<br><br>
If you have only one passenger from the
Passenger power, they can now use psychic
powers using your body, and you can use
powers normally. When they use a power, you
take any effects or consequences as if you
used the power, though they spend any
resources (sin, bursts, etc). These powers
immediately end if your passenger exits.
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #003030, #8B008B);">
		<div class="tooltip-title">SILVER SIGHT</div>
		<div class="quirk">
			<div class="tooltip-title">SILVER SIGHT</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You are completely blind, but permanently benefit
from the <b>Threads</b> power from this blasphemy and
gain it for free. It can overlap with other powers.
Since you are used to seeing this way, actions
against living things are not hard for you, but other
actions that require sight are. If you participate in
teamwork or gain setup, you can ignore this
restriction in addition to the normal benefits of
teamwork or setup.<br><br>
In addition, your extreme sensitivity to grace lets
you immediately sense (with some imprecision) if
anyone in a ½ CAT area centered on you has any
psychic sensitivity, and how much, or if there are
any supernatural beings in a similar area, how
close they are, and how strong they are.
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
		<div class="tooltip-title">POSSESSION</div> 
		<div class="power">
			<div class="tooltip-title">POSSESSION</div>
			<div class="tags">1 Scene, Curse, Short</div>
			<div class="description">
				You can shunt your perception out of your body to
possess a human, animal, or corpse (in good
condition) you can see in range for a scene.
Supernatural beings are immune to this effect.
Unwilling humans might require rolling PSYCHE to
possess successfully.<br><br>
• While possessing another your real body is
insensate and defenseless<br><br>
• For humans and animals, you cannot force a
target to harm itself or take action that would
indirectly cause it to come to harm<br><br>
• Actions that the target takes use your skills, but
the target’s body or equipment, which might
change the circumstances<br><br>
You are kicked out of the body if it takes harm. Gain
or grant +1D on the next roll by yourself or an ally
taking advantage of this power.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">GEIST</div>
		<div class="power">
			<div class="tooltip-title">GEIST</div>
			<div class="tags">1 Scene, Self</div>
			<div class="description">
				You can shunt your perception out of your body
and roam for CAT+2 range, becoming a being
made of purely psychic energy.<br><br>
• While practicing this power, your real body is
insensate and defenseless<br><br>
• You can fly at CAT speed, are invisible to
those not psychically sensitive, and may pass
through walls, floors, and objects easily while
in this form.<br><br>
• You cannot interact with or be affected by the
physical world. You cannot use or benefit
from your own psychic powers, but psychic
powers or effects from others can still affect
you.<br><br>
If your form is destroyed somehow (by a
supernatural force), you take 1 stress, this power
ends, and you can’t use this power again until
the scene passes.<br><br>
This power may easily affect the parameters of
rolls, such as difficulty and risk.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">THREADS</div>
		<div class="power">
			<div class="tooltip-title">THREADS</div>
			<div class="tags">Until Rest, Charm, Self</div>
			<div class="description">
				You can sense the unseen world of traces of
grace. Upon using this power, you close your eyes
and can see through your eyelids the patterns the
soul leaves in the environment.<br><br>
• You gain the ability to see living beings, even
through walls, for CAT range<br><br>
• You can see the traces a sin or someone strong
in grace such as an exorcist leaves, like a faint
trail of light through the air.<br><br>
• You gain +1D on actions to track or locate
living beings or traces of sins in the area.
However, you cannot see any non-living matter
(you are effectively blind) while maintaining
this power, and find actions that rely on sight
hard<br><br>
This power ends when you open your eyes or
when you rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PASSENGER</div>
		<div class="power">
			<div class="tooltip-title">PASSENGER</div>
			<div class="tags">1 Scene, Curses, Extreme</div>
			<div class="description">
				You choose a group of willing humans or exorcists
with a group size equal or less than ½ CAT in
extreme range, who must be able to either hear
you (even telepathically) or see you. You pull their
psychic presence into your body for the duration.
Their bodies become limp, vulnerable and
insensate. However:<br><br>
• they now share control of your body with you,
including all senses.<br><br>
• You can surrender control of your body to them
to allow them to make action rolls using their
skills or abilities, but your body (gear, access,
etc).<br><br>
• You can set them up as normal or aid them on
these skills.<br><br>
They cannot use psychic powers while possessing
you this way, and you suffer any harm or
consequences from their actions.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DESECRATE</div>
		<div class="power">
			<div class="tooltip-title">DESECRATE</div>
			<div class="tags">Instant, Adjacent</div>
			<div class="description">
				You can force a semblance of life into the corpses of
up to a CAT sized group of humans or exorcists by
touching them on the eyes. You may ask the
corpse(s) three questions total (no matter how many
you animate), after which the effect ends and they
become dead again. It also expires if pressure
increases.<br><br>
• You can’t use this power on the same corpse(s)
more than once<br><br>
• The power does not return life to the body, but
accesses the body’s memories. If the head or
brain is missing, or the body lacks a tongue, etc,
this power will not work as well.<br><br>
• A corpse is obligated to answer truthfully, but can
only speak to the realm of its knowledge and
memories before it died. It may have only partial
knowledge of a situation or may speak according
to its own viewpoint.<br><br>
Then lose the use of this power until you rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>