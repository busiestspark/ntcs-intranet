---
unlisted: true
---

[[Intranet Login|Return to login]]

<div style="color: yellow">
✉ You have <b>1</b> new message since <b>July 16th, 2026</b>.
</div>

# Recent Messages

<div class="email-wrapper" style="--email-color: #FFFF00">
<button type="button" class="email">
	<div style="display: flex; width: 100%; justify-content: space-between; align-items: center;">
		<div style="text-align: left; padding-left: 30px;">
			<div style="font-size: 0.85rem; color: var(--email-text-muted);">wasp@castle.cain</div>
			<div>check this shit out</div>
		</div>
		<div>
			<span class="time-elapsed" data-date="2026-07-16"></span>
			<b>July 16th, 2026</b>
		</div>
	</div>
</button>
<div class="email-content">
	<b>TO:</b> all<br>
	<b>FROM:</b> <a href="WASP" style="color: var(--email-border);">wasp@castle.cain</a><br>
	<b>SUBJECT:</b> check this shit out<br><br>
sup chucklenuts<br><br>
liking the intranet so far? no? well im boutta change that<br><br>
i added a little smth smth to the front page for ~trusted users~
<br><br>
FUN BUTTON -> 𓆤
<br><br>
it doesnt have much atm but trust me this shits gonna be gas when it gets off the ground. im talkin like. coolmathgames type shit if any of you remember that
<br><br>
oh btw if you tell the execs about this i will personally tp into your room and kick you in the cunt
<br><br>
cool? sweet
</div>
</div>

# Older Messages

<div class="email-wrapper" style="--email-color: #00FF00">
<button type="button" class="email">
	<div style="display: flex; width: 100%; justify-content: space-between; align-items: center;">
		<div style="text-align: left; padding-left: 30px;">
			<div style="font-size: 0.85rem; color: var(--email-text-muted);">emorrow@castle.cain</div>
			<div>New Intranet Access</div>
		</div>
		<div>
			<span class="time-elapsed" data-date="2026-07-01"></span>
			<b>July 1st, 2026</b>
		</div>
	</div>
</button>
<div class="email-content">
	<b>TO:</b> all<br>
	<b>FROM:</b> <a href="Emmanuel Morrow" style="color: var(--email-border);">emorrow@castle.cain</a><br>
	<b>SUBJECT:</b> New Intranet Access<br><br>
Good evening, exorcists.

I've recently approved access to the organization's internal computer network (CAIN Intranet). It may seem a tad dated to you, but the techs assure me that it is the best way of keeping our data secure.

The intranet is somewhat limited at present as it is accessible by all members of the organization. It's part of a new "open information policy" being implemented, but all you need to know right now is that we're working on approving more files for the system.

Feel free to send me an email (Read: Discord Message) if there are any files that you would like to request access to or if there is any personal information that would like to revoke from the system. They do not necessarily have to be files that are already referenced in the system; I'll do my best to dig up whatever you need.

With introductions out of the way, feel free to poke around and see how the intranet works.

Regards,
Emmanuel Morrow, Senior Operation Advisor
</div>
</div>

---

<div style="text-align: center">This is the end of your inbox.</div>

<script>
var coll = document.getElementsByClassName("email");
var i;

for (i = 0; i < coll.length; i++) {
	coll[i].addEventListener("click", function() {
		this.classList.toggle("active");
		var content = this.nextElementSibling;
	    if (this.classList.contains("active")) {
	      content.style.maxHeight = content.scrollHeight + "px";
	      content.style.paddingTop = "18px";
	      content.style.paddingBottom = "18px";
	    } else {
	      content.style.maxHeight = "0px";
	      content.style.paddingTop = "0px";
	      content.style.paddingBottom = "0px";
	    }
	});
}

document.addEventListener("DOMContentLoaded", function() {
	const timeLabels = document.querySelectorAll(".time-elapsed");

	timeLabels.forEach(label => {
		const emailDate = new Date(label.getAttribute("data-date"));
		const today = new Date();

		const differenceInMs = today - emailDate;

		const minutes = Math.floor(differenceInMs / (1000 * 60));
		const hours = Math.floor(differenceInMs / (1000 * 60 * 60));
		const days = Math.floor(differenceInMs / (1000 * 60 * 60 * 24));

		let relativeTimeString = "";

	    if (days >= 7) {
	      relativeTimeString = `(${Math.floor(days / 7)}w) `;
	    } else if (days > 0) {
	      relativeTimeString = `(${days}d) `;
	    } else if (hours > 0) {
	      relativeTimeString = `(${hours}h) `;
	    } else {
	      relativeTimeString = `(${minutes}m) `;
	    }

		label.innerText = relativeTimeString;
		label.style.color = "rgb(from inherit calc(r - 128) calc(g - 128) calc(b - 128) / a)";
		label.style.marginRight = "5px";
	});
});
</script>