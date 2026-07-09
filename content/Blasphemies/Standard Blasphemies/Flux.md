---
tags: Blasphemy
image: "[[Flux Card.png]]"
blsphID: "3"
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

	background: linear-gradient(145deg, #000000, #8B0000);

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
	background-image: linear-gradient(145deg, #000000, #8B0000);
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
<div class="infobox-title">Flux</div>

<br>
<img src="Flux Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

<div style="padding-right: calc(400px);">
<div style="color: yellow; border: 1px solid yellow; padding: 1rem; width: 90%;">⚠ CAUTION<br><br>All manipulation of time must ultimately adhere to the "GYRE 2" temporal code. Deliberate attempts to alter time in a way that subvert this standard are to be considered a CLASS-A breach of the <a href="Veil Protocol" style="color: yellow;">Veil Protocol.</a></div>
</div>

**Flux** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the manipulation of time.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">STEAL TIME</div>
		<div class="passive">
			<div class="tooltip-title">STEAL TIME</div>
			<div class="tags">Passive</div>
			<div class="description">
				For one rest per hunt, anyone
in your group may re-roll all their
resting dice, taking the second result
as final. This may cause them déjà vu.
Please reassure them.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #8B0000">
		<div class="tooltip-title">TEMPORAL INSTABILITY</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #8B0000">
			<div class="tooltip-title">TEMPORAL INSTABILITY</div>
			<div class="tags">Hook</div>
			<div class="description">
				Many of your powers give you this hook.
When the hook resolves, roll 1d6:<br><br>
1. Permanently add to your agenda ‘Prove
that you are the real you.” If you gain this
result again, you immediately suffer sin
overflow.<br><br>
2. Mysterious injuries open up. You take an
injury, which could kill you.<br><br>
3. You disappear until rest. You return if
there’s a conflict scene (and right away if
one is ongoing). You have no memory of
where you were. When you return, you take
2 stress.<br><br>
4. You find you are wearing someone else’s
clothes. Erase your entire kit this mission,
but regain any spent kit points.<br><br>
5. Your body is different. For the remainder
of this mission, pick a skill you have 1 or
more dice in. It now rolls 0d. After the
mission, you have time to train and get used
to this, reverting this effect, though keeping
any physical changes.<br><br>
6. Your face looks a little different. The
changes are permanent.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #8B0000);">
		<div class="tooltip-title">CLOCK STOPPER</div>
		<div class="quirk">
			<div class="tooltip-title">CLOCK STOPPER</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You can use the Stop power without spending any
psyche bursts, lasting a full minute, and it does not
cause temporal instability. Using the power this way
‘steals time’ from your future lifespan and
supernaturally ages you.<br><br>
Draw an actual clock on your sheet, starting at 12:00
noon, then advance time by 1d3 hours. Also advance
the clock by 1 hour if you suffer sin overflow, or you
may advance it any time you would gain temporal
instability (1 hour for 1 temporal instability). This
clock cannot be affected in any other way.<br><br>
Each hour from 12-5pm ages you 1d3 years. Each
hour from 6-9 ages you around 1d6+2 years, and
each hour from 10-12 ages you around 2d6+8. This
has no effect on your abilities. At midnight, you die
of old age (this cannot be ignored).
			</div>
			<div class="credit">From Games for Freaks Vol. 4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #200020, #8B0000);">
		<div class="tooltip-title">TIME SPLITTER</div>
		<div class="quirk">
			<div class="tooltip-title">TIME SPLITTER</div>
			<div class="tags">Quirk</div>
			<div class="description">
				Once a hunt, without spending a psyche burst, you
may cause a temporal fracture when undertaking
any course of action. This fracture ends when an
action roll is made, when you would die or suffer
sin overflow, or after exactly 777 seconds have
expired in the fiction.<br><br>
This activity takes place in an alternate timeline, in
which everything is otherwise exactly the same.
When the fracture expires, you revert to the main
timeline, undoing all outcomes, resources spent,
harm taken, or consequences, but keeping any
knowledge or memory from the alternate timeline.
You or an ally may take +1D on the next roll that
takes advantage of this information. Then play
forward as normal.
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
		<div class="tooltip-title">REVERSAL</div> 
		<div class="power">
			<div class="tooltip-title">REVERSAL</div>
			<div class="tags">Instant, Adjacent</div>
			<div class="description">
				By touching an object up to CAT size, you can
reverse its passage through time for the last hour.<br><br>
• This could physically move the object, revert
damage on an object, etc.<br><br>
• It can still affect the physical world, so anything
in a reversing object’s way would get hit, and
anything placed on it will move with it.<br><br>
• If it would cause damage or impact, roll
PSYCHE for it<br><br>
• It cannot reverse life on non-living matter, such
as corpses, but can temporarily move them and
revert damage as if they were alive.<br><br>
You can stop this effect by willing it, but to resume
it requires using this power again.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div style="color: white; font-size: 2rem; margin-right: 5px;">
		+
		</div>
		<div class="tooltip-title">STOP</div>
		<div class="power">
			<div class="tooltip-title">STOP</div>
			<div class="tags">Instant, Transmute, Self</div>
			<div class="description">
				You spend up to three psyche bursts to stop
local time in an area around you equal to CAT.
Roll 1d6 per psyche burst spent and add them
together - that is how many seconds you have.
Anything that enters this area is immediately
affected (including anything put into or out of
the area), but time flows normally outside the
area. In this stopped time, you are unaffected
and:<br><br>
• you cannot use psychic powers, but neither
can you be affected by them. Any power
currently active from you or affecting you
other than this one dissipates.<br><br>
• you can perform one activity or course of
action that fits in the duration. After you
would make an action roll for anything, the
effect ends no matter what.<br><br>
<b>Then, gain temporal instability.</b>
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">QUICKENING</div>
		<div class="power">
			<div class="tooltip-title">QUICKENING</div>
			<div class="tags">Instant, Adjacent</div>
			<div class="description">
				You can accelerate the natural healing of your
body or those of others, giving you the
following benefits:<br><br>
• Immediately heal 1d3 stress on yourself or
another target. If your target is injured,
increase this by +1.<br><br>
• You may heal a CAT sized group of dying
or injured humans in short range. Dying
humans are stabilized and are no longer in
danger of expiring, but fall unconscious.
Otherwise, badly injured humans are
healed to the point of being able to
(slowly) move by themselves. Minor
injuries are fully healed.<br><br>
<b>Then, gain temporal instability</b>
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">SCHISM</div>
		<div class="power">
			<div class="tooltip-title">SCHISM</div>
			<div class="tags">1 Scene, Transmute, Adjacent</div>
			<div class="description">
				You can create a bubble of altered time equal to CAT
area, opening a window into one day in the past or
future from the moment the bubble was created.
Gain or grant +1D when you or any ally next acts to
take advantage of this power:<br><br>
• The state of the area inside the bubble is confined
only to the bubble and includes objects or people
inside. You and allies can enter or exit the bubble
at will.<br><br>
• Supernatural beings, including exorcists, in the
present timeline caught in the bubble when it is
created are unaffected. Humans and the ‘present’
timeline world caught in the bubble are ‘paused’,
cease existing for its duration, and have no
memory of the incident.<br><br>
• Things removed from the bubble from the past or
future timeline, including living beings, simply
disappear until they move back into the bubble.<br><br>
The bubble represents an ‘alternate’ timeline, so
anything altered inside of it will not show up in the
present or future timeline (i.e. leaving an object in a
past timeline will not have it show up in the present).
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">STUTTER</div>
		<div class="power">
			<div class="tooltip-title">STUTTER</div>
			<div class="tags">Instant, CAT Range</div>
			<div class="description">
				You can briefly reverse time in order to alter
causality for any event that happened as a
result of an action roll made by you or a visible
ally in CAT range, instantly after you see the
result. Re-roll the action roll completely, taking
the second result as final.<br><br>
When you use this power, <b>gain temporal
instability.</b> If you use it again before you rest,
<b>gain 1d3 temporal instability instead.</b>
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>
