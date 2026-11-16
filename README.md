# Pablo-Emilio-Escobar-Gaviria

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PABLO ARCHIVE | Historical Database</title>
<style>
:root {
  --green:#00ff88;
  --bg:#050807;
  --panel:#0b1210;
  --muted:#81938a;
  --red:#ff4141;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;background:var(--bg);color:#d8e5dc;
  font-family:Consolas,monospace;
}
header{
  padding:22px 8%;border-bottom:1px solid #183326;
  display:flex;justify-content:space-between;align-items:center;
  flex-wrap:wrap;gap:15px;
}
.logo{color:var(--green);font-size:20px;font-weight:bold;letter-spacing:3px}
.status{color:var(--red);font-size:11px;letter-spacing:2px}
nav{display:flex;gap:20px;flex-wrap:wrap}
nav a{color:var(--muted);text-decoration:none;font-size:12px}
nav a:hover{color:var(--green)}
main{max-width:1050px;margin:auto;padding:35px 20px}
.hero{padding:65px 0 55px}
.tag{color:var(--green);font-size:12px;letter-spacing:3px}
h1{font-size:clamp(36px,8vw,70px);margin:15px 0;color:#fff}
h1 span{color:var(--green)}
.subtitle{color:var(--muted);line-height:1.7;max-width:650px}
.stamp{
  display:inline-block;border:2px solid var(--red);color:var(--red);
  padding:8px 14px;transform:rotate(-3deg);font-weight:bold;
  margin-top:22px;letter-spacing:3px
}
.section{margin:55px 0;scroll-margin-top:25px}
.section-title{
  color:var(--green);font-size:19px;
  border-bottom:1px solid #183326;padding-bottom:12px;
  margin-bottom:22px
}
.panel{
  background:var(--panel);border:1px solid #183326;
  padding:22px;margin:15px 0;border-radius:4px
}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:15px}
.label{color:var(--muted);font-size:11px;letter-spacing:2px}
.value{font-size:18px;color:var(--green);margin-top:9px}
p{line-height:1.7}
.timeline{border-left:2px solid #1d7048;padding-left:22px}
.event{position:relative;margin:25px 0}
.event:before{
  content:"";position:absolute;left:-29px;top:5px;
  width:10px;height:10px;background:var(--green);border-radius:50%
}
.year{color:var(--green);font-weight:bold}
.small{font-size:12px;color:var(--muted)}
button{
  background:transparent;color:var(--green);border:1px solid var(--green);
  padding:10px 15px;font-family:inherit;cursor:pointer
}
button:hover{background:var(--green);color:#001108}
.quiz-answer{margin-top:12px;color:var(--green)}
#terminal{
  background:#020504;border:1px solid #1c583a;padding:18px;
  min-height:280px;box-shadow:0 0 25px #00ff8810
}
#output{height:220px;overflow-y:auto;white-space:pre-wrap;line-height:1.6;font-size:13px}
.prompt{color:var(--green)}
.input-line{display:flex;gap:10px;margin-top:15px}
#command{
  flex:1;min-width:0;background:transparent;border:0;
  border-bottom:1px solid #286344;color:white;
  outline:none;font-family:inherit;padding:10px
}
a.source{color:var(--green);display:block;margin:12px 0}
footer{
  border-top:1px solid #183326;padding:25px;text-align:center;
  color:var(--muted);font-size:11px
}
@media(max-width:600px){
  header{padding:18px}
  nav{gap:12px}
  main{padding:20px 16px}
  .hero{padding:45px 0}
}
</style>
</head>
<body>

<header>
  <div class="logo">PABLO ARCHIVE</div>
  <div class="status">● ARCHIVE ONLINE</div>
  <nav>
    <a href="#profile">PROFILE</a>
    <a href="#timeline">TIMELINE</a>
    <a href="#history">HISTORY</a>
    <a href="#terminal-section">TERMINAL</a>
  </nav>
</header>

<main>
<section class="hero">
  <div class="tag">INDEPENDENT HISTORICAL DATABASE // 001</div>
  <h1>THE <span>MEDELLÍN</span><br>ARCHIVE</h1>
  <p class="subtitle">
    A historical archive documenting Pablo Escobar, the Medellín Cartel,
    and the impact of the Colombian drug trade during the late 20th century.
  </p>
  <div class="stamp">HISTORICAL RECORD</div>
</section>

<section class="section" id="profile">
  <div class="section-title">01 // SUBJECT PROFILE</div>
  <div class="grid">
    <div class="panel">
      <div class="label">SUBJECT</div>
      <div class="value">Pablo Escobar</div>
    </div>
    <div class="panel">
      <div class="label">BORN</div>
      <div class="value">1 December 1949</div>
    </div>
    <div class="panel">
      <div class="label">BIRTHPLACE</div>
      <div class="value">Rionegro, Colombia</div>
    </div>
    <div class="panel">
      <div class="label">DIED</div>
      <div class="value">2 December 1993</div>
    </div>
  </div>
  <div class="panel">
    <p>
      Pablo Escobar was a Colombian drug trafficker and the principal leader
      of the Medellín Cartel. His criminal organization became one of the
      most powerful in the international cocaine trade. Its violence,
      corruption and attacks caused immense suffering in Colombia.
    </p>
  </div>
</section>

<section class="section" id="timeline">
  <div class="section-title">02 // HISTORICAL TIMELINE</div>
  <div class="panel timeline">
    <div class="event">
      <div class="year">1949</div>
      <p>Pablo Escobar is born in Rionegro, Colombia.</p>
    </div>
    <div class="event">
      <div class="year">1970s</div>
      <p>His criminal activities expand and the Medellín Cartel develops.</p>
    </div>
    <div class="event">
      <div class="year">1980s</div>
      <p>The cartel becomes internationally notorious. Colombia experiences
      escalating violence and political instability.</p>
    </div>
    <div class="event">
      <div class="year">1991</div>
      <p>Escobar surrenders to Colombian authorities and is imprisoned.</p>
    </div>
    <div class="event">
      <div class="year">1992</div>
      <p>He escapes from the prison where he had been held.</p>
    </div>
    <div class="event">
      <div class="year">1993</div>
      <p>Escobar is killed in Medellín on 2 December.</p>
    </div>
  </div>
</section>

<section class="section" id="history">
  <div class="section-title">03 // THE MEDELLÍN CARTEL</div>
  <div class="panel">
    <p>
      The Medellín Cartel was a major Colombian criminal organization
      involved in cocaine production and trafficking. During the 1980s,
      it used violence, intimidation and corruption to influence public
      institutions and challenge the Colombian state.
    </p>
    <p>
      Its history is also the history of victims: journalists, judges,
      police officers, politicians and ordinary civilians affected by
      organized crime and political violence.
    </p>
    <p class="small">ARCHIVE NOTE: Historical explanation, not glorification.</p>
  </div>
</section>

<section class="section" id="quiz">
  <div class="section-title">04 // FACT OR FICTION</div>
  <div class="panel">
    <p><b>Statement:</b> Pablo Escobar was the leader of the Medellín Cartel.</p>
    <button onclick="answer(true)">FACT</button>
    <button onclick="answer(false)">FICTION</button>
    <div id="quiz-result" class="quiz-answer"></div>
  </div>
</section>

<section class="section" id="terminal-section">
  <div class="section-title">05 // ARCHIVE TERMINAL</div>
  <div id="terminal">
    <div id="output">PABLO ARCHIVE TERMINAL v2.0
Independent historical research interface.
Type "help" to display available commands.

</div>
    <div class="input-line">
      <span class="prompt">archive://</span>
      <input id="command" placeholder="Enter command..." autocomplete="off">
      <button onclick="runCommand()">EXECUTE</button>
    </div>
  </div>
  <p class="small">SIMULATED TERMINAL // EDUCATIONAL USE ONLY</p>
</section>

<section class="section" id="sources">
  <div class="section-title">06 // RESEARCH SOURCES</div>
  <div class="panel">
    <a class="source" href="https://www.britannica.com/biography/Pablo-Escobar" target="_blank">[01] Encyclopaedia Britannica - Pablo Escobar</a>
    <a class="source" href="https://www.archives.gov/" target="_blank">[02] US National Archives</a>
    <a class="source" href="https://www.banrepcultural.org/" target="_blank">[03] Banco de la República - Cultural Archive</a>
  </div>
</section>
</main>

<footer>
PABLO ARCHIVE // INDEPENDENT HISTORICAL PROJECT<br>
NOT AN OFFICIAL GOVERNMENT DATABASE
</footer>

<script>
function answer(correct){
  document.getElementById("quiz-result").textContent =
    correct ? "CORRECT. This is a historical fact." :
    "INCORRECT. Escobar was the leader of the Medellín Cartel.";
}

const output = document.getElementById("output");
const input = document.getElementById("command");

const commands = {
  help: `AVAILABLE COMMANDS:

help       - Show command list
profile    - Subject biography
timeline   - Historical timeline
cartel     - Medellín Cartel overview
locations  - Historical locations
sources    - Research references
clear      - Clear terminal`,

  profile: `SUBJECT: PABLO ESCOBAR
BORN: 1 DECEMBER 1949
BIRTHPLACE: RIONEGRO, COLOMBIA
DIED: 2 DECEMBER 1993
ROLE: LEADER OF THE MEDELLÍN CARTEL

STATUS: DECEASED
RECORD TYPE: HISTORICAL`,

  timeline: `1949 - Escobar is born.
1970s - Medellín Cartel expands.
1980s - Cartel violence escalates.
1991 - Escobar surrenders.
1992 - Escobar escapes prison.
1993 - Escobar dies in Medellín.`,

  cartel: `MEDELLÍN CARTEL

A Colombian criminal organization involved
in international cocaine trafficking.

Its activities contributed to widespread
violence, corruption and civilian suffering.

PERIOD: Mainly 1970s-1990s
LOCATION: Colombia`,

  locations: `HISTORICAL GEOGRAPHY

RIONEGRO - Escobar's birthplace.
MEDELLÍN - City associated with the cartel.
COLOMBIA - Main historical setting.

These are general historical locations,
not operational directions.`,

  sources: `RESEARCH DATABASE

Encyclopaedia Britannica:
https://www.britannica.com/biography/Pablo-Escobar

US National Archives:
https://www.archives.gov/

Banco de la República:
https://www.banrepcultural.org/`
};

function runCommand(){
  const cmd = input.value.trim().toLowerCase();
  if(!cmd) return;

  const line = document.createElement("div");
  line.textContent = "archive:// " + cmd;
  output.appendChild(line);

  if(cmd === "clear"){
    output.textContent = "TERMINAL CLEARED.\nType help for commands.\n";
  } else {
    const result = commands[cmd] || "ERROR: Unknown command. Type help.";
    const response = document.createElement("div");
    response.style.color = "#00ff88";
    response.style.marginBottom = "15px";
    response.textContent = result;
    output.appendChild(response);
  }

  input.value = "";
  output.scrollTop = output.scrollHeight;
}

input.addEventListener("keydown", function(event){
  if(event.key === "Enter") runCommand();
});
</script>
</body>
</html>
