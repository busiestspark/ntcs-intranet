---
unlisted: true
---

[[Intranet Login|Return to login]]

<div style="color: yellow">
✉ You have <b>1</b> new message since <b>July 1st, 2026</b>.
</div>

# Recent Messages

<div>
<button type="button" class="email">
	<div style="display: flex; width: 100%; justify-content: space-between; align-items: center;">
		<div style="text-align: left; padding-left: 30px;">
			<div style="font-size: 0.85rem; color: #008000;">emorrow@castle.cain</div>
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
	<b>FROM:</b> <a href="Emmanuel Morrow">emorrow@castle.cain</a><br>
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

# Older Messages



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
		label.style.color = "#008000";
		label.style.marginRight = "5px";
	});
});
</script>