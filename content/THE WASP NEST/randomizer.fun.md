
<style>
button {
    background-color: #000000;
    color: #00FF00;
    border: 1px solid #00FF00;
    padding: 5px 10px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}

#checks {
	width: 50%;

	padding-left: 2rem;

}

#printout {
    border: 2px solid #00FF00;
    width: 50%;

    padding: 10px;
}
</style>

Click "randomize" to create a completely random exorcist.

<div id="checks">
	<input type="checkbox" id="gff-check">
	<label for="gff-check">Include Games for Freaks content</label>
</div>

<button id="randomize">Randomize</button>

YOUR EXORCIST:

<div id="printout"></div>

<script>

const button = document.getElementById("randomize");
const printout = document.getElementById("printout");

const gffCheck = document.getElementById("gff-check");

const baseBlasphemies = [
    "Tension",
    "Ardence",
    "Flux",
    "Vector",
    "Gate",
    "Smother",
    "Whisper",
    "Edit",
    "Bind",
    "Palace",
    "Jaunt",
    "Sympathy"
]

const gffBlasphemies = [
    "Tongue",
    "Track",
    "Wire",
    "Mother"
]

const baseAgendas = [
    "Beast",
    "Doomed",
    "Firebug",
    "Guardian",
    "Loner",
    "Hardline",
    "Machine",
    "Moth",
    "Torch",
    "Temperance",
    "Shadow",
    "Sorcerer",
    "Songbird",
    "Survivor",
    "Demon"
]

const gffAgendas = [
    "Doll",
    "Cradle",
    "Broken"
]

button.addEventListener("click", Randomize);

function Randomize() {
	let fullBlasphemyList = [];
    for (b of baseBlasphemies) {
        fullBlasphemyList.push(b);
    }

    if (gffCheck.checked) {
        for (b of gffBlasphemies) {
            fullBlasphemyList.push(b);
        }
    }

    blasphemyResult = Math.floor(Math.random() * fullBlasphemyList.length);

    let fullAgendaList = [];
    for (a of baseAgendas) {
        fullAgendaList.push(a);
    }

        if (gffCheck.checked) {
        for (b of gffAgendas) {
            fullAgendaList.push(b);
        }
    }

    agendaResult = Math.floor(Math.random() * fullAgendaList.length);

    skills = [0,0,0,1,1,1,1,1,2,2];

    shuffle(skills);

    printout.innerHTML = `
    BLSPH: ${fullBlasphemyList[blasphemyResult]}<br>
    AGND:  ${fullAgendaList[agendaResult]}<br><br>
    
    <table>
        <tr>
            <td>FORCE:</td>
            <td>${"◉".repeat(skills[0])}${"⭘".repeat(3-skills[0])}</td>
        </tr>
        <tr>
            <td>CONDITIONING:</td>
            <td>${"◉".repeat(skills[1])}${"⭘".repeat(3-skills[1])}</td>
        </tr>
        <tr>
            <td>COORDINATION:</td>
            <td>${"◉".repeat(skills[2])}${"⭘".repeat(3-skills[2])}</td>
        </tr>
        <tr>
            <td>COVERT:</td>
            <td>${"◉".repeat(skills[3])}${"⭘".repeat(3-skills[3])}</td>
        </tr>
        <tr>
            <td>INTERFACING:</td>
            <td>${"◉".repeat(skills[4])}${"⭘".repeat(3-skills[4])}</td>
        </tr>
        <tr>
            <td>INVESTIGATION:</td>
            <td>${"◉".repeat(skills[5])}${"⭘".repeat(3-skills[5])}</td>
        </tr>
        <tr>
            <td>SURVEILLANCE:</td>
            <td>${"◉".repeat(skills[6])}${"⭘".repeat(3-skills[6])}</td>
        </tr>
        <tr>
            <td>NEGOTIATION:</td>
            <td>${"◉".repeat(skills[7])}${"⭘".repeat(3-skills[7])}</td>
        </tr>
        <tr>
            <td>AUTHORITY:</td>
            <td>${"◉".repeat(skills[8])}${"⭘".repeat(3-skills[8])}</td>
        </tr>
        <tr>
            <td>CONNECTION:</td>
            <td>${"◉".repeat(skills[9])}${"⭘".repeat(3-skills[9])}</td>
        </tr>
    </table>
    `
}

function shuffle(array) {
    for (let i = array.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));

        [array[i], array[j]] = [array[j], array[i]];
    }  
}

</script>