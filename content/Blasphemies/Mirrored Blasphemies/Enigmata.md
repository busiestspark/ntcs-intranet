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

	background: linear-gradient(145deg, #2f274a, #615299);

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
	background-image: linear-gradient(145deg, #2f274a, #615299);
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
<div class="infobox-title">Enigmata</div>

<br>
<img src="Enigmata Card.jpg" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Dillon Nguyen, from the Harpocrates Dossier</div>
</div>

**Enigmata** is a mirrored [[Blasphemies|Blasphemy]].

It is concerned with the obfuscation of knowledge.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">SO BELOW</div>
		<div class="passive">
			<div class="tooltip-title">SO BELOW</div>
			<div class="tags">Passive</div>
			<div class="description">
				You gain the Sanctum passive from the
Palace blasphemy. It no longer grants an extra
resting die and is both unnavigable and dangerous
to beings that enter it, including you. It contains a
hostile tulpa that you do not control, but you decide
its shape and appearance. Many of your Enigmata
powers give you the “Descent” hook.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #615299">
		<div class="tooltip-title">DESCENT</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #615299">
			<div class="tooltip-title">DESCENT</div>
			<div class="tags">Hook</div>
			<div class="description">
				When you gain it roll 1d3 to determine
its effects. You only possess 1 version of
descent at any time and it cannot be
removed or avoided during a mission.
You may choose not to remove it at the
end of the mission.<br><br>
<b>(1)</b> 1/scene at the Admin’s choice, the
admin may trigger one of your enigmata
powers without spending a psyche
burst. They choose the target and effect.<br><br>
<b>(2)</b> 1/rest for 1 scene of the Admin’s
choice, you lose the ability to
communicate intelligibly with others.
You may bypass this by taking 2 stress
each time you attempt to do so.<br><br>
<b>(3)</b> When you finish a rest with the party
you return from it in an entirely different
location. When you move from scene to
scene with the party the admin rolls a
fate die. On a 1 you end up in an entirely
different location than intended.
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
		<div class="tooltip-title">RIDDLE</div> 
		<div class="power">
			<div class="tooltip-title">RIDDLE</div>
			<div class="tags">Charm, Transmute, 1 Scene</div>
			<div class="description">
				For the rest of the scene you have the ability
to render information useless, jumbled, and
incoherent until rest. Whenever you touch
something that has information whether it is
written, recorded, or digitally uploaded, you
have the ability to make this information
impossible to access from the corrupted
source. Psychic abilities that provide
omniscience or the ability to perceive
supernaturally hidden things will not bypass
this.<br><br>
You may make it so that any changes made
during this scene are permanent by taking
the Descent hook for each instance you
corrupt a source of recorded information.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SINK</div>
		<div class="power">
			<div class="tooltip-title">SINK</div>
			<div class="tags">Transmute, CAT Area, 1 Scene, 1/Mission</div>
			<div class="description">
				You peel back the assumed state of reality for you and every
other being of your choice up to a CAT area centered on yourself.
All of you sink, moving into a layer of reality beneath your current
one. At the end of the scene every being returns to the original
world, floating back up. In this layer of reality, everything is
similar except for the following differences:<br><br>
- Every supernatural being that has sunken has a temporary
execution talisman of 3. When a living being would die they
instead float back to the original world.<br><br>
- Exorcists can hurt one another.<br><br>
- There are no living things present except for beings who
have sunken. The hostile tulpa who lives in your mind
has manifested here as well, and is slowly hunting you.<br><br>
- Changes made in this world do not affect the original world,
and tension and pressure do not increase while sunken.<br><br>
When you float, you reappear in the investigation zone in a safe
location of the Admin’s choice within a far distance from the
original location where you sank. This power may easily affect the
parameter of rolls such as difficulty or risk.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">IMPRISON</div>
		<div class="power">
			<div class="tooltip-title">IMPRISON</div>
			<div class="tags">Touch, 1/Rest</div>
			<div class="description">
				Touch a creature to shunt both of your consciousnesses
into your Sanctum. Roll for PSYCHE when targeting a
supernatural being, only spending a psyche burst upon
success. While within the Sanctum, your hostile tulpa
actively hunts both you and the target. The power ends
when either you or the target are harmed by the tulpa. While
inside of your Sanctum, the time outside of your mind is
slowed down to a near stop until this power resolves.<br><br>
- If you were harmed first, take 1d3+1 stress and gain the
Descent Hook. If your target was harmed first, they
become extremely disoriented upon returning to reality,
granting +1D to the next ½ CAT rolls to take advantage of
this power. This may also affect the parameter of rolls such
as difficulty or risk.<br><br>
- You gain a pool of +1D equal to the number of times you’ve
taken a resting scene and explored your Sanctum during it
before you triggered this power (Max +3D). You may
spend these dice on any actions to avoid your tulpa while
this power is active.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">CIPHER</div>
		<div class="power">
			<div class="tooltip-title">CIPHER</div>
			<div class="tags">Instant, Touch, 1 Scene, 1/Scene</div>
			<div class="description">
				You create a cognito hazardous glyph on any surface that
is smaller than the palm of your hand, and may be placed
on anything such as an object, piece of clothing, or on the
surface of your body. Create a talisman equal to your
½ CAT. Whenever a being looks at it and trigger its effects,
slash the talisman once. This power ends when the
talisman is fully slashed. You determine its effect from the
following:<br><br>
<b>Latching:</b> The cognitohazard is not particularly dangerous
but lingers in the mind of anyone who sees it. Gain or grant
+1D to track, follow, or ascertain the nature of living beings
that have looked at the glyph.<br><br>
<b>Disturbing:</b> All living beings will actively avoid looking at
this symbol and subconsciously and have intense
migraines upon forcing themselves to do so. The glyph now
lasts regardless of how many beings look at it.<br><br>
<b>Harmful:</b> The cognitohazard causes damage to the brain of
anyone who perceives it. This critically injures mundane
humans and is painful to supernatural beings. Enemies
who look at it for the first time take damage equal to a
PSYCHE roll. Take the Descent hook for every time you roll
for PSYCHE this way after your first roll. If you are already
in descent take 1d3+1 stress per instance instead.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="HD Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">MNEMOS</div>
		<div class="power">
			<div class="tooltip-title">MNEMOS</div>
			<div class="tags">Transmute, Close, 1/Scene</div>
			<div class="description">
				You cause a number of living being’s memories within range
equal to your CAT to rapidly fail and cascade in front of you.
They become insensate for exactly 11 seconds and forget
everything they've heard or seen in the last 66 seconds. Then
your admin rolls a fate die.<br><br>
<b>(1)</b> Mundane humans die of brain injuries at any point after the
scene ends at a moment of the admin’s choosing. Supernatural
beings regain their memory when the scene ends but take 1
slash on their execution talisman when the scene ends. Your
tulpa mocks you.<br><br>
<b>(2)</b> All beings regain their memories after you take a rest.<br><br>
<b>(3)</b> Your brain bleeds from the overexertion caused by this
ability. Take 1d3 non-lethal stress and when you take the
Descent hook from this power tick it up by 1 as well.<br><br>
Take the Descent hook. Gain or grant +1D to the next
roll that takes advantage of this power.
			</div>
			<div class="credit">From the Harpocrates Dossier 2.2</div>
		</div>
	</div>
</div>
