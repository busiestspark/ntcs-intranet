---
title: CAIN Intranet
tags:
  - Hub
---
<style>
.modal {
	display: none;
	position: fixed;
	z-index: 1;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	overflow: auto;
	background-color: #000000;
	background-color: rgba(0,0,0,0.4);
}

.modal-content {
	background-color: #000000;
	margin: 15% auto;
	padding: 20px;
	border: 1px solid #00FF00;
	border-radius: 5px;
	width: 60%;
	text-align: center;
	color: white;
}

.close {
    background-color: #002000;
    color: #00FF00;
    border: 1px solid #00FF00;
    padding: 5px 10px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    margin: 1.5rem;
}

.close:hover,
.close:focus {
	background-color: #004000;
}
</style>


<div id="content-warning" class="modal">
	<div class="modal-content">
		CAIN is the property of Tom Bloom/CHASM ©2026. This site is NOT AFFILIATED and everything on it should be considered a "fanwork" of the original material and does not intend to undermine the original material in any way.<br><br>
		This website contains MATURE THEMES. If you are not comfortable with discussion of VIOLENCE, LIGHT SEXUALIZATION, or MENTAL ILLNESS, then <i>DO NOT PROCEED.</i>
		<button class="close">I ACCEPT THE RISK</button>
	</div>
</div>


<div style="text-align: center;">
<pre>
/\
/  \
/    \
/      \
/        \
/          \
/            \
----------------
----------------
\############/
\##########/
\########/
\######/
\####/
\##/
\/

AS ABOVE, SO BELOW
</pre>
</div>
<hr>

<div style="display: flex; justify-content: space-between;">
	<div>
	CAIN-NET v0.6.1 beta<br>
	<a href="Changelog">View Changelog</a><br><br>
	<a href="Intranet Login">Log in to your intranet account here.</a>
	</div>
	<div style="text-align: right;">
	<a href="Credits">View Credits</a><br><br>
	<a href="WASP_NEST.home" style="color: yellow;">𓆤</a>
	</div>
</div>

Welcome to the CAIN Intranet.

This system serves as an archive for CAIN documents and is freely accessible by authorized CAIN personnel from any intranet[^1]-enabled devices.

Use the links below to access specific document categories, or browse the database at the bottom of this page.

![[Hub Index.base]]

---
# Database

![[Data.base]]

[^1]:: "Intranet" refers to the exclusive ecosystem of CAIN-sanctioned devices. Attempting to access CAIN systems using an outside device or vice versa is a CLASS-A breach of Veil Protocol and may result in immediate termination.

<script>
var modal = document.getElementById("content-warning");
var close = document.getElementsByClassName("close")[0];

window.addEventListener("DOMContentLoaded", () => {
	if (document.referrer == null || document.referrer.indexOf(window.location.hostname) < 0) {
		modal.style.display = "block";
	}
})

close.onclick = function() {
	modal.style.display = "none";
}
</script>