Please log in to your intranet email.

<form id="passkeyForm">
	<label for="userInput">Enter your passkey:</label>
	<input type="password" id="userInput" autocomplete='off' placeholder='******' required>
	<button type="submit">Log In</button>
</form>

<script>
	document.getElementById('passkeyForm').addEventListener('submit', function(event) {
		event.preventDefault();

		const input = document.getElementById('userInput').value.trim().toLowerCase();

		if (input === 'kingofcups') {
			window.location.href = 'inbox/bwilliams@castle.cain';
		} else if (input === 'bombshell') {
			window.location.href = 'inbox/fennik@castle.cain';
		} else if (input === 'briefcase') {
			window.location.href = 'inbox/hpenmire@castle.cain';
		} else if (input === 'silvertongue') {
			window.location.href = 'inbox/jmckinley@castle.cain';
		} else if (input === 'snowranger') {
			window.location.href = 'inbox/vagabond@castle.cain';
		} else if (input === 'overdose') {
			window.location.href = 'inbox/vokonoi@castle.cain';
		} else {
			alert('Invalid Code.');
		}
	});
</script>

<br>
<div style="padding-right: calc(400px);">
<div style="color: yellow; border: 1px solid yellow; padding: 1rem;">NOTICE<br><br>CAIN does not take responsibility for breaches of privacy resulting from misplaced passkeys.
</div>
</div>


