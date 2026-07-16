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

	background: linear-gradient(145deg, #400040, #FF00FF);

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
	background-image: linear-gradient(145deg, #400040, #FF00FF);
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
<div class="infobox-title">Physic</div>

<br>
<img src="Physic Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Physic** is an untempered [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of natural healing.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">BLOODHOUND</div>
		<div class="passive">
			<div class="tooltip-title">BLOODHOUND</div>
			<div class="tags">Passive</div>
			<div class="description">
				Within CAT+2 distance, you always know where
an allied Exorcist is if they have at least 1 injury. You gain
+1D on actions to track enemies with half or more of their
execution talisman slashed. Some of your powers grant
you or the target the Necrosis hook.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #FF00FF">
		<div class="tooltip-title">NECROSIS</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #FF00FF">
			<div class="tooltip-title">NECROSIS</div>
			<div class="tags">Hook</div>
			<div class="description">
				Your psychic abilities
reject the natural order. When this
hook fills up, things return to how
they should have been.<br><br>
• Your previous wounds or injuries
begin to open up again. Roll the
fate die and take (1): 5 stress
(2-3): 4 stress (4+): 4 non-lethal
stress.<br><br>
• Roll two dice, taking the lower
result for a permanent scar which
resembles stitches burst open on
your (1d6):<br><br>
- 1: Neck<br>
- 2: Elbows<br>
- 3: Wrists<br>
- 4: Knees<br>
- 5: Ankles<br>
- 6: Spine<br><br>
Rolling double 1’s will result in
instant death, as your tendons
snap and body falls apart from the
strain.
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
		<div class="tooltip-title">CURE</div> 
		<div class="power">
			<div class="tooltip-title">CURE</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				You rearrange and revert the physical traumas on a
target in range. Roll for PSYCHE, adding 1d3 to the
total number of successes. Remove that number of
stress from the target. If this would overheal (reduce
the number of slashes below 0) you may choose to
remove an injury from the target and continue
removing stress as if the talisman was fully slashed.
Removing an injury this way grants the Necrosis hook
to your target. You may only use this on an allied
exorcist once per rest.<br><br>
When you may also target a CAT group of humans
instead, you instantly cure them of any psychic
phenomenon affecting them, along with physical
ailments or injuries. These effects return to them at the
end of the scene.<br><br>
When targeting a supernatural non-player creature,
add ½ CAT segments to their execution talisman. The
next time that NPC would take a reaction, they falter
as their healing comes undone, rolling the risk die
twice and choosing the higher result.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">REMOVE</div>
		<div class="power">
			<div class="tooltip-title">REMOVE</div>
			<div class="tags">Curse, CAT Distance, Until Rest</div>
			<div class="description">
				Remove an aspect of pain or trauma from a creature of your choice.
This may seamlessly remove a traumatic or painful memory that you
are aware of from any being until rest.<br><br>
Alternatively, once per hunt you may use this power when all of the
following conditions have been met:<br><br>
• You meet at least 1 requirement for the Nail of Abel.<br><br>
• The Sin has 1 or more of its execution talisman slashed.<br><br>
• You know one Trauma question that you have not used to counter
a reaction yet.<br><br>
You erase a memory of an intense trauma that the Sin was born
from. Restore 2 segments on the Sin’s execution talisman, then the
admin selects 1 domain the sin has access to (picking the one that
may best match or narratively coincides with the removed trauma if
possible). The sin may not use abilities or powers granted to it by
that domain until rest.<br><br>
You may no longer use the trauma question selected to counter this
sin’s reaction until rest. The sin ends this power early when you
encounter it in its palace, as its memories flood back to it: you may
gain the Necrosis hook twice to suppress this.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">WOUND</div>
		<div class="power">
			<div class="tooltip-title">WOUND</div>
			<div class="tags">Instant, Short, 1/Scene</div>
			<div class="description">
				Reverse the flow of your healing abilities and pull on
broken threads, creating devastating entropic
wounds. This instantly kills mundane humans,
leaving them with lesions, cut marks, or any injuries
of your choice. When targeting a supernatural
creature, roll PSYCHE for damage as you
deteriorate and injure a section of your target’s
physical form. This power gains +1D bonus die on
the roll for each of the following questions you can
answer “yes” to (max +3D).<br><br>
• Are you able to touch a part of your target that is
vital or important to them?<br><br>
• Have you previously healed or used healing
abilities on the target?<br><br>
• Are you willing to rip yourself to pieces to Wipe
the Stain? (Gain the Necrosis hook if you answer
“yes”)
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">TRIAGE</div>
		<div class="power">
			<div class="tooltip-title">TRIAGE</div>
			<div class="tags">Charm, CAT+1 Area, 1 Scene, 1/Rest</div>
			<div class="description">
				You may only use this ability if an ally within range has 2
or more injuries. Psychically connect your healing
abilities to the sinseed of every allied exorcist within a
CAT+1 area. Through overworking your synapses to
project your abilities over a wide area, the following
effects persist for the duration of the scene:<br><br>
• The exorcist with the most injuries at any moment
heals +1 stress from healing abilities or consumables.
(ties trigger on all exorcist who fulfill this requirement)<br><br>
• Whenever an allied exorcist is on the brink of death,
psychic threads always lead a path to reach them for
another allied exorcist. Reaching them is never
impossible.<br><br>
• Up to ½ CAT times during the duration of this power,
any allied exorcist that takes actions to stabilize, aid, or
heal another may revert an affliction on their target to
a fully slashed hook and tick that hook down by 1.<br><br>
When this ability ends, fully slash the Necrosis hook
on yourself.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">MEND</div>
		<div class="power">
			<div class="tooltip-title">MEND</div>
			<div class="tags">Transmute, Instant</div>
			<div class="description">
				You repair any broken object that is your
CAT size or smaller. You must know what
the object looked like before it was
destroyed or broken. Mundane humans
that have seen this happen are convinced
that the object was never broken in the
first place, and will not be suspicious of you.<br><br>
You may gain or grant +1D when you or
any ally next acts to take advantage of this
power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
