---
tags:
  - Blasphemy
image: "[[Sympathy Card.png]]"
blsphID: "12"
---
<style>

table, td {
	color: white;
}

tr {
	border: none;
}

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
<div class="infobox-title">Sympathy</div>

<br>
<img src="Sympathy Card.png" alt="IMAGE NOT FOUND">
<div style="font-size: 0.85rem; padding-left: 2rem; text-align: right;">Art by Tom Bloom, from the CAIN Sourcebook</div>
</div>

**Sympathy** is a standard [[Blasphemies|Blasphemy]].

It is concerned with the subconscious impressions and inherent qualities of inanimate objects.

# Abilities

<div class="section-background">
	<div class="section-header">
	Passives
	</div>
</div>

<div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center;">
	<div class="tooltip">
		<div class="tooltip-title">RESONANCE</div>
		<div class="passive">
			<div class="tooltip-title">RESONANCE</div>
			<div class="tags">Passive</div>
			<div class="description">
				At the start of the mission, roll on the
resonance table. Roll 1d3, then 1d6, then check the
resonance tables. When
you are making an action roll and you are using an
item you are resonant with, you gain a +1D bonus. You
can spend a psyche burst any time to roll an
additional resonance. You can keep up to three at a
time, and only benefit from one at a time.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #8B008B">
		<div class="tooltip-title">RESONANCES</div>
		<div class="passive" style="background-image: linear-gradient(145deg, #000000, #101010); border: 2px solid #8B008B; width: 210%;">
			<div class="tooltip-title">RESONANCES</div>
			<div class="tags">Roll 1d3, then 1d6</div>
			<div class="description">
				<table>
					<tr>
						<td>11 Phones</td>
						<td>21 Balls</td>
						<td>31 Ropes</td>
					</tr>
					<tr>
						<td>12 Lights</td>
						<td>22 Guns</td>
						<td>32 Hammers</td>
					</tr>
					<tr>
						<td>13 Knives</td>
						<td>23 Mugs</td>
						<td>33 Cars</td>
					</tr>
					<tr>
						<td>14 Keys</td>
						<td>24 Computers</td>
						<td>34 Doors</td>
					</tr>
					<tr>
						<td>15 Books</td>
						<td>25 Shoes</td>
						<td>35 Bags</td>
					</tr>
					<tr>
						<td>16 Baseball Bats</td>
						<td>26 Power Tools</td>
						<td>36 Gloves</td>
					</tr>
				</table>
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip" style="background-image: linear-gradient(145deg, #003030, #8B008B);">
		<div class="tooltip-title">LOCUS</div>
		<div class="quirk">
			<div class="tooltip-title">LOCUS</div>
			<div class="tags">Quirk</div>
			<div class="description">
				You specialize in a particular object,
but have aversion to others. Choose an
object on the list of resonances. You
are automatically resonant with that
object, but find activities that involve
any of the other objects on that list
hard by default. Actions are also hard
when you are touching, wearing, or in
hand’s reach of those objects. You can
swap this focus around at the start of
each hunt, or when you rest.
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
		<div class="tooltip-title">AMPLIFY</div> 
		<div class="power">
			<div class="tooltip-title">AMPLIFY</div>
			<div class="tags">1 Scene, Summon, Adjacent</div>
			<div class="description">
				You can expand the mundane properties of a
regular non-weapon item to extreme levels. You
touch a mundane object up to CAT size. For the
scene, you automatically have resonance with it,
and its properties are enhanced to extreme levels,
as if they were up to your CAT in scale. For
example:<br><br>
• A car’s speed, handling, and resilience<br><br>
• A light’s brightness and intensity, and the area
it illuminates<br><br>
• A door’s ability to lock and withstand force<br><br>
This can easily affect the difficulty and risk of rolls.
The object is still mundane.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">BOND</div>
		<div class="power">
			<div class="tooltip-title">BOND</div>
			<div class="tags">1 Scene, Charm</div>
			<div class="description">
				For the scene, you can bond incredibly tightly
with an item you are holding in one or both hands.<br><br>
• You are now resonant with that item. It is still
mundane<br><br>
• You can now use it as a mundane cutting or
bludgeoning weapon even if it wouldn’t
normally be a weapon. It has about the power
of a CAT 0 bat or sword<br><br>
• The item becomes virtually indestructible, and
you can cause the item to recall to your hand,
flying through the air, from within short
distance<br><br>
• You can discharge this power to make a strike
with the object, granting it supernatural
destructive power equal to CAT. Roll PSYCHE
for its effects (it gains +1D on the roll as
normal due to resonance). Then end this effect
and destroy the item
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">DIPLOMACY</div>
		<div class="power">
			<div class="tooltip-title">DIPLOMACY</div>
			<div class="tags">Instant, Short</div>
			<div class="description">
				You make a simple request of an object as if it was
a person, or ask it a simple yes or no question.<br><br>
For example, you can ask a door to open or hold
shut (even if it couldn’t normally lock, or you don’t
have the key), a computer to turn off or find
information for you, or a car to turn on without a
key or drive by itself.<br><br>
If you need to make a roll for this, roll PSYCHE or
use a social action, such as negotiation or
authority.<br><br>
You can affect objects up to CAT size with this.
Objects asked questions can answer only with yes
or no answers and can’t actually vocalize.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Free Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">PSYCHOMETRY</div>
		<div class="power">
			<div class="tooltip-title">PSYCHOMETRY</div>
			<div class="tags">Instant, Adjacent</div>
			<div class="description">
				You can touch objects to remotely view their
memories. You can view back a number of days
equal to your CAT. Roll PSYCHE, then ask a question
plus an additional question per success.<br><br>
• Where has this object been?<br><br>
• Who has touched this object?<br><br>
• What has this object been used for?<br><br>
• What else is this object connected to?<br><br>
Memories of an object are impressionistic and
imprecise, and they are only usually ‘aware’ of their
very immediate surroundings.<br><br>
After using this power, lose its use until you rest.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
	<div class="tooltip">
		<img src="Psyche Burst.png" alt="1 Psyche Burst" style="height: 2rem;">
		<div class="tooltip-title">ALLIANCE</div>
		<div class="power">
			<div class="tooltip-title">ALLIANCE</div>
			<div class="tags">1 Scene, Summon, Short</div>
			<div class="description">
				An object up to CAT size in short range can now
take action to set up an ally, rolling 1d6, or PSYCHE
if you are resonant with that object. The object can
take or cause consequences as normal from these
actions.<br><br>
Allies have to be able to interact with it or use the
object to gain its benefits. The object doesn’t gain
the ability to actually move or animate in any way,
but fortune simply bends around it.
			</div>
			<div class="credit">From CAIN 1.4</div>
		</div>
	</div>
</div>