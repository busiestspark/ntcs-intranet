
\> safecracker.sh "Psychometry Reports" -v
\> Running on dir: "Psychometry Reports"
\> Logging Progress:

<div id="progress" class="redacted"></div>

<script>

const meter = document.getElementById("progress");

const progress = 2;

meter.innerHTML = `
[<span>${"X".repeat(Math.floor(progress/2))}</span>${"-".repeat(50 - Math.floor(progress/2))}]<br>
${progress}%
`

</script>