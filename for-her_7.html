<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For You</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,500;0,9..144,600;1,9..144,500&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;500&family=Caveat:wght@500;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --ivory:#FBF8F4;
    --ink:#2B2530;
    --ink-soft:#6B6270;
    --rose:#FF7A9C;
    --rose-soft:#FFD9E2;
    --violet:#6C5CE7;
    --violet-soft:#E7E3FB;
    --glass:rgba(255,255,255,0.65);
    --line:rgba(43,37,48,0.1);
  }

  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--ivory);
    color:var(--ink);
    font-family:'Inter',sans-serif;
    overflow-x:hidden;
    -webkit-font-smoothing:antialiased;
  }
  ::selection{background:var(--rose-soft);}

  .section{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    padding:80px 24px;
    position:relative;
    text-align:center;
  }

  .reveal{
    opacity:0;
    transform:translateY(28px);
    transition:opacity 0.8s cubic-bezier(.22,1,.36,1), transform 0.8s cubic-bezier(.22,1,.36,1);
  }
  .reveal.in-view{
    opacity:1;
    transform:translateY(0);
  }

  .eyebrow{
    display:inline-block;
    font-family:'Caveat',cursive;
    font-weight:600;
    font-size:22px;
    color:var(--ink);
    background:var(--rose-soft);
    padding:5px 18px 8px;
    border-radius:2px;
    transform:rotate(-2.5deg);
    margin-bottom:22px;
    box-shadow:0 2px 5px rgba(43,37,48,0.1);
  }
  .eyebrow.tilt-right{ transform:rotate(2deg); background:var(--violet-soft); }

  h1,h2{
    font-family:'Fraunces',serif;
    font-weight:500;
    line-height:1.1;
  }

  /* ---------- Waveform (signature element) ---------- */
  .waveform{
    display:flex;
    align-items:center;
    justify-content:center;
    gap:4px;
    height:60px;
  }
  .waveform span{
    width:4px;
    border-radius:3px;
    background:linear-gradient(180deg,var(--rose),var(--violet));
    animation:wave 1.4s ease-in-out infinite;
  }
  @keyframes wave{
    0%,100%{transform:scaleY(0.3);}
    50%{transform:scaleY(1);}
  }

  /* ---------- Hero ---------- */
  .hero h1{
    font-size:clamp(38px,7vw,72px);
    max-width:820px;
    margin-bottom:20px;
  }
  .hero h1 em{ font-style:italic; color:var(--rose); }
  .hero p{
    font-size:17px;
    color:var(--ink-soft);
    max-width:460px;
    margin-bottom:40px;
  }
  .scroll-hint{
    position:absolute;
    bottom:36px;
    font-family:'JetBrains Mono',monospace;
    font-size:11px;
    color:var(--ink-soft);
    letter-spacing:0.08em;
    text-transform:uppercase;
    animation:bob 2s ease-in-out infinite;
  }
  @keyframes bob{ 0%,100%{transform:translateY(0);} 50%{transform:translateY(8px);} }

  .section h2{
    font-size:clamp(28px,4.5vw,44px);
    max-width:640px;
    margin-bottom:14px;
  }
  .section .sub{
    color:var(--ink-soft);
    font-size:15px;
    max-width:440px;
    margin-bottom:56px;
  }

  /* ---------- Riddle stage ---------- */
  .riddle-card{
    max-width:460px;
    width:100%;
    background:var(--glass);
    border:1px solid var(--line);
    border-radius:24px;
    padding:40px 34px 32px;
    backdrop-filter:blur(6px);
    text-align:left;
    transform:rotate(-0.6deg);
  }
  .riddle-index{
    font-family:'JetBrains Mono',monospace;
    font-size:11px;
    letter-spacing:0.06em;
    color:var(--ink-soft);
    margin-bottom:20px;
    text-align:center;
  }
  .riddle-question{
    font-family:'Fraunces',serif;
    font-style:italic;
    font-weight:500;
    font-size:clamp(19px,3vw,23px);
    line-height:1.5;
    color:var(--ink);
    text-align:center;
    margin-bottom:30px;
    min-height:96px;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .riddle-guess-row{
    display:flex;
    align-items:center;
    gap:10px;
    border-bottom:1px solid var(--line);
    padding-bottom:10px;
    margin-bottom:22px;
  }
  .riddle-guess-row input{
    flex:1;
    border:none;
    background:transparent;
    outline:none;
    font-family:'Inter',sans-serif;
    font-size:14.5px;
    color:var(--ink);
  }
  .riddle-guess-row input::placeholder{ color:var(--ink-soft); }
  .riddle-actions{ display:flex; justify-content:center; }
  .riddle-reveal-btn{
    font-family:'Inter',sans-serif;
    font-weight:600;
    font-size:13.5px;
    background:var(--ink);
    color:#fff;
    border:none;
    padding:12px 26px;
    border-radius:100px;
    cursor:pointer;
    transition:transform 0.2s ease;
  }
  .riddle-reveal-btn:hover{ transform:translateY(-1px); }
  .riddle-answer{
    margin-top:20px;
    padding:16px 18px;
    border-radius:14px;
    background:linear-gradient(145deg,var(--rose-soft),var(--violet-soft));
    text-align:center;
    opacity:0;
    transform:translateY(8px);
    max-height:0;
    overflow:hidden;
    transition:opacity 0.5s ease, transform 0.5s ease, max-height 0.5s ease, margin 0.5s ease;
  }
  .riddle-answer.show{ opacity:1; transform:translateY(0); max-height:160px; }
  .riddle-answer .word{
    font-family:'Fraunces',serif;
    font-weight:600;
    font-size:17px;
    margin-bottom:4px;
  }
  .riddle-answer .tag{
    font-size:12.5px;
    color:var(--ink-soft);
  }
  .riddle-nav{
    display:flex;
    align-items:center;
    justify-content:center;
    gap:18px;
    margin-top:26px;
  }
  .riddle-nav button{
    background:none;
    border:none;
    cursor:pointer;
    color:var(--ink-soft);
    display:flex;
    align-items:center;
    justify-content:center;
    padding:6px;
    transition:color 0.2s ease;
  }
  .riddle-nav button:hover{ color:var(--ink); }
  .riddle-nav svg{ width:18px; height:18px; }
  .riddle-dots{ display:flex; gap:6px; }
  .riddle-dots span{
    width:6px; height:6px;
    border-radius:999px;
    background:var(--line);
    transition:width 0.3s ease, background 0.3s ease;
  }
  .riddle-dots span.active{ width:18px; background:var(--rose); }

  /* ---------- Slide to send (game two) ---------- */
  .slide-wrap{ display:flex; flex-direction:column; align-items:center; gap:26px; }
  .slide-track{
    position:relative;
    width:min(340px,86vw);
    height:64px;
    border-radius:999px;
    background:var(--glass);
    border:1px solid var(--line);
    overflow:hidden;
  }
  .slide-fill{
    position:absolute;
    top:0; left:0; height:100%; width:0;
    background:linear-gradient(90deg,var(--rose),var(--violet));
    border-radius:inherit;
  }
  .slide-label{
    position:absolute;
    inset:0;
    display:flex;
    align-items:center;
    justify-content:center;
    font-family:'JetBrains Mono',monospace;
    font-size:12.5px;
    letter-spacing:0.04em;
    color:var(--ink-soft);
    pointer-events:none;
    transition:opacity 0.25s ease;
  }
  .slide-handle{
    position:absolute;
    top:6px; left:6px;
    width:52px; height:52px;
    border-radius:50%;
    background:var(--ink);
    display:flex;
    align-items:center;
    justify-content:center;
    cursor:grab;
    touch-action:none;
    user-select:none;
    box-shadow:0 6px 16px rgba(43,37,48,0.3);
    z-index:2;
    transition:left 0.35s cubic-bezier(.22,1,.36,1);
  }
  .slide-handle.dragging{ transition:none; cursor:grabbing; }
  .slide-handle svg{ width:18px; height:18px; fill:#fff; pointer-events:none; }

  .slide-reveal{
    max-width:420px;
    padding:22px 26px;
    background:var(--glass);
    border:1px solid var(--line);
    border-radius:18px;
    font-size:15px;
    line-height:1.6;
    opacity:0;
    transform:translateY(12px);
    transition:opacity 0.6s ease, transform 0.6s ease;
    display:none;
  }
  .slide-reveal.show{ display:block; opacity:1; transform:translateY(0); }

  /* ---------- Final CTA — voice bubble ---------- */
  .bubble{
    background:linear-gradient(145deg,var(--violet),#8B7FF0);
    color:#fff;
    border-radius:26px 26px 26px 6px;
    padding:26px 28px;
    max-width:380px;
    width:100%;
    text-align:left;
    box-shadow:0 20px 50px rgba(108,92,231,0.35);
    margin-bottom:36px;
    transform:rotate(0.8deg);
  }
  .bubble-top{ display:flex; align-items:center; gap:14px; }
  .bubble-mic{
    width:40px;height:40px;
    border-radius:50%;
    background:rgba(255,255,255,0.2);
    display:flex; align-items:center; justify-content:center;
    flex-shrink:0;
  }
  .bubble-mic svg{ width:18px; height:18px; fill:#fff; }
  .bubble-wave{ flex:1; display:flex; align-items:center; gap:3px; height:28px; }
  .bubble-wave span{ width:3px; border-radius:2px; background:rgba(255,255,255,0.85); }
  .bubble-time{ font-family:'JetBrains Mono',monospace; font-size:11px; color:rgba(255,255,255,0.7); }
  .bubble p{ margin-top:16px; font-size:14.5px; line-height:1.55; color:rgba(255,255,255,0.95); }

  .cta-btn{
    font-family:'Inter',sans-serif;
    font-weight:600;
    font-size:15px;
    background:var(--ink);
    color:#fff;
    border:none;
    padding:16px 34px;
    border-radius:100px;
    cursor:pointer;
    display:inline-flex;
    align-items:center;
    gap:10px;
    text-decoration:none;
    transition:transform 0.25s ease, box-shadow 0.25s ease;
    box-shadow:0 8px 24px rgba(43,37,48,0.25);
  }
  .cta-btn:hover{ transform:translateY(-2px); box-shadow:0 12px 30px rgba(43,37,48,0.3); }
  .cta-btn:active{ transform:translateY(0); }

  .footer-note{
    margin-top:22px;
    font-family:'JetBrains Mono',monospace;
    font-size:11.5px;
    color:var(--ink-soft);
    letter-spacing:0.03em;
  }

  #confetti-canvas{ position:fixed; inset:0; pointer-events:none; z-index:999; }

  .signature{
    font-family:'Caveat',cursive;
    font-weight:600;
    font-size:26px;
    color:var(--ink-soft);
    margin-top:30px;
    transform:rotate(-1.5deg);
  }

  /* ---------- Memory match game ---------- */
  .memory-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:12px;
    max-width:420px;
    width:100%;
  }
  .memory-card{ perspective:800px; aspect-ratio:1/1; cursor:pointer; }
  .memory-inner{
    position:relative;
    width:100%; height:100%;
    transition:transform 0.5s cubic-bezier(.22,1,.36,1);
    transform-style:preserve-3d;
  }
  .memory-card.flipped .memory-inner{ transform:rotateY(180deg); }
  .memory-face{
    position:absolute;
    inset:0;
    border-radius:14px;
    display:flex;
    align-items:center;
    justify-content:center;
    backface-visibility:hidden;
  }
  .memory-front{
    background:var(--glass);
    border:1px solid var(--line);
  }
  .memory-front::after{
    content:'';
    width:14px;height:14px;
    border-radius:50%;
    background:var(--rose-soft);
  }
  .memory-back{
    background:linear-gradient(145deg,var(--rose-soft),var(--violet-soft));
    transform:rotateY(180deg);
  }
  .memory-back svg{ width:22px; height:22px; stroke:var(--ink); }
  .memory-card.matched{ opacity:0.4; cursor:default; }
  .memory-status{
    margin-top:26px;
    font-family:'JetBrains Mono',monospace;
    font-size:12px;
    color:var(--ink-soft);
  }
  .memory-win{
    margin-top:20px;
    font-family:'Caveat',cursive;
    font-size:24px;
    color:var(--ink);
    opacity:0;
    transform:translateY(8px);
    transition:opacity 0.5s ease, transform 0.5s ease;
  }
  .memory-win.show{ opacity:1; transform:translateY(0); }

  /* ---------- Day check-in ---------- */
  .day-card{
    max-width:440px;
    width:100%;
    background:var(--glass);
    border:1px solid var(--line);
    border-radius:22px;
    padding:32px;
    transform:rotate(0.5deg);
  }
  .day-card textarea{
    width:100%;
    min-height:100px;
    border:none;
    background:transparent;
    border-bottom:1px solid var(--line);
    resize:none;
    font-family:'Inter',sans-serif;
    font-size:14.5px;
    color:var(--ink);
    outline:none;
    padding-bottom:14px;
    margin-bottom:22px;
  }
  .day-card textarea::placeholder{ color:var(--ink-soft); }

  @media (max-width:520px){
    .riddle-card{ padding:32px 24px 26px; }
    .section{ padding:64px 20px; }
  }

  @media (prefers-reduced-motion: reduce){
    *{ animation-duration:0.001ms !important; animation-iteration-count:1 !important; transition-duration:0.001ms !important; }
    html{ scroll-behavior:auto; }
    .reveal{ opacity:1; transform:none; }
  }

  button:focus-visible, .flip-card:focus-visible, .slide-handle:focus-visible, .cta-btn:focus-visible{
    outline:2px solid var(--violet);
    outline-offset:3px;
  }
</style>
</head>
<body>

<canvas id="confetti-canvas"></canvas>

<!-- HERO -->
<section class="section hero">
  <div class="eyebrow">ok this is a little much, I know</div>
  <div class="waveform" id="hero-wave" style="margin-bottom:28px;"></div>
  <h1>Hey <em>you</em>.<br>I built you a whole website.</h1>
  <p>Instead of just asking normally, apparently. There's a couple of games first, then the actual point. No pressure, just scroll.</p>
  <span class="scroll-hint">scroll ↓</span>
</section>

<!-- RIDDLE GAME -->
<section class="section">
  <div class="reveal">
    <div class="eyebrow">game one, obviously</div>
    <h2>Solve me first.</h2>
    <p class="sub">Four riddles I wrote at 1am. Guess if you want, or just peek — I won't know either way.</p>
  </div>

  <div class="riddle-card reveal">
    <div class="riddle-index" id="riddleIndex">01 / 04</div>
    <div class="riddle-question" id="riddleQuestion"></div>
    <div class="riddle-guess-row">
      <span aria-hidden="true">✎</span>
      <input type="text" id="riddleInput" placeholder="type your guess (optional)" autocomplete="off">
    </div>
    <div class="riddle-actions">
      <button class="riddle-reveal-btn" id="riddleRevealBtn">Reveal</button>
    </div>
    <div class="riddle-answer" id="riddleAnswer">
      <div class="word" id="riddleWord"></div>
      <div class="tag" id="riddleTag"></div>
    </div>
    <div class="riddle-nav">
      <button id="riddlePrev" aria-label="Previous riddle">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M15 6l-6 6 6 6"/></svg>
      </button>
      <div class="riddle-dots" id="riddleDots"></div>
      <button id="riddleNext" aria-label="Next riddle">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M9 6l6 6-6 6"/></svg>
      </button>
    </div>
  </div>
</section>

<!-- SLIDE TO SEND GAME -->
<section class="section">
  <div class="reveal">
    <div class="eyebrow tilt-right">one more, promise</div>
    <h2>Slide it over.</h2>
    <p class="sub">You know this gesture from somewhere. Old phones had it right.</p>
  </div>
  <div class="slide-wrap reveal">
    <div class="slide-track" id="slideTrack">
      <div class="slide-fill" id="slideFill"></div>
      <span class="slide-label" id="slideLabel">slide to hear something</span>
      <div class="slide-handle" id="slideHandle" role="slider" tabindex="0"
           aria-label="Slide to reveal a message, or press Enter"
           aria-valuemin="0" aria-valuemax="100" aria-valuenow="0">
        <svg viewBox="0 0 24 24"><path d="M12 14a3 3 0 003-3V6a3 3 0 00-6 0v5a3 3 0 003 3zm5-3a5 5 0 01-10 0H5a7 7 0 006 6.92V21h2v-3.08A7 7 0 0019 11h-2z"/></svg>
      </div>
    </div>
    <div class="slide-reveal" id="slideReveal">
      Reading your texts is great. It's just not quite the same as hearing you laugh at your own jokes bwahhahahah.
    </div>
  </div>
</section>

<!-- MEMORY MATCH GAME -->
<section class="section">
  <div class="reveal">
    <div class="eyebrow">okay one more, for real</div>
    <h2>Match them up.</h2>
    <p class="sub">Six pairs. No timer, no pressure, take your time.</p>
  </div>
  <div class="memory-grid reveal" id="memoryGrid"></div>
  <div class="memory-status" id="memoryStatus">0 / 6 matched</div>
  <div class="memory-win" id="memoryWin">okay you're actually good at this. keep scrolling.</div>
</section>

<!-- DAY CHECK-IN -->
<section class="section">
  <div class="reveal">
    <div class="eyebrow tilt-right">before you go</div>
    <h2>How was your day?</h2>
    <p class="sub">Type it here to warm up, or skip straight to telling me properly.</p>
  </div>
  <div class="day-card reveal">
    <textarea id="dayInput" placeholder="it was... (tell me literally anything)"></textarea>
    <div class="riddle-actions">
      <a class="riddle-reveal-btn" style="text-decoration:none;" href="https://instagram.com" target="_blank" rel="noopener noreferrer" id="dayBtn">Tell me properly</a>
    </div>
  </div>
</section>

<!-- FINAL CTA -->
<section class="section">
  <div class="reveal">
    <div class="eyebrow">ok, the actual point</div>
    <h2 style="margin-bottom:36px;">Your turn to press record.</h2>
  </div>

  <div class="bubble reveal">
    <div class="bubble-top">
      <div class="bubble-mic">
        <svg viewBox="0 0 24 24"><path d="M12 14a3 3 0 003-3V6a3 3 0 00-6 0v5a3 3 0 003 3zm5-3a5 5 0 01-10 0H5a7 7 0 006 6.92V21h2v-3.08A7 7 0 0019 11h-2z"/></svg>
      </div>
      <div class="bubble-wave" id="bubble-wave"></div>
      <span class="bubble-time">0:07</span>
    </div>
    <p>Tell me about your day, sing something, narrate what you're doing right now  I don't mind. I just want the version of you that doesn't fit in text bubbles.</p>
  </div>

  <a class="cta-btn reveal" id="ctaBtn" href="https://instagram.com" target="_blank" rel="noopener noreferrer">
    Send me a voice note
    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M13 6l6 6-6 6"/></svg>
  </a>
  <span class="footer-note reveal">no rush. whenever you feel like it.</span>
  <div class="signature reveal">ab to vn dedooo beby</div>
</section>

<script>
// ---------- Waveform generator ----------
function buildWave(el, bars, minH, maxH){
  el.innerHTML = "";
  for(let i=0;i<bars;i++){
    const s = document.createElement("span");
    const h = Math.random()*(maxH-minH)+minH;
    s.style.height = h+"px";
    s.style.animationDelay = (Math.random()*1.2)+"s";
    el.appendChild(s);
  }
}
buildWave(document.getElementById("hero-wave"), 28, 10, 55);

const bWave = document.getElementById("bubble-wave");
for(let i=0;i<24;i++){
  const s = document.createElement("span");
  s.style.height = (Math.random()*20+4)+"px";
  s.style.background = "rgba(255,255,255,"+(0.4+Math.random()*0.5)+")";
  bWave.appendChild(s);
}

// ---------- Riddle stage ----------
const riddles = [
  {
    q: "I have a spine but no bones, pages but I never turn myself. You leave me open on your chest most nights and fall asleep before the next chapter. What am I?",
    a: "A book",
    tag: ""
  },
  {
    q: "I'm brewed hot, but by the time you actually remember I exist, I've gone lukewarm. What am I?",
    a: "Your coffee",
    tag: ""
  },
  {
    q: "I have a beat but no body, and I come in at least three different settings depending on how ridiculous the joke was. What am I?",
    a: "Your laugh",
    tag: ""
  },
  {
    q: "I take seconds to make, but I can outlast the silence after a goodnight text. I cost nothing, yet somehow feel like a small gift. What am I?",
    a: "A voice note",
    tag: "Funny you should guess that one. Keep scrolling."
  }
];

let ri = 0;
const riddleQuestion = document.getElementById("riddleQuestion");
const riddleIndex = document.getElementById("riddleIndex");
const riddleInput = document.getElementById("riddleInput");
const riddleAnswer = document.getElementById("riddleAnswer");
const riddleWord = document.getElementById("riddleWord");
const riddleTag = document.getElementById("riddleTag");
const riddleRevealBtn = document.getElementById("riddleRevealBtn");
const riddleDots = document.getElementById("riddleDots");
const riddlePrev = document.getElementById("riddlePrev");
const riddleNext = document.getElementById("riddleNext");

riddles.forEach((_, i)=>{
  const dot = document.createElement("span");
  if(i === 0) dot.classList.add("active");
  riddleDots.appendChild(dot);
});

function renderRiddle(){
  const r = riddles[ri];
  riddleQuestion.textContent = r.q;
  riddleIndex.textContent = "0"+(ri+1)+" / 0"+riddles.length;
  riddleInput.value = "";
  riddleAnswer.classList.remove("show");
  riddleWord.textContent = r.a;
  riddleTag.textContent = r.tag;
  riddleTag.style.display = r.tag ? "block" : "none";
  [...riddleDots.children].forEach((d,i)=> d.classList.toggle("active", i===ri));
}
renderRiddle();

function revealRiddle(){
  riddleAnswer.classList.add("show");
}
function goTo(i){
  ri = (i + riddles.length) % riddles.length;
  renderRiddle();
}

riddleRevealBtn.addEventListener("click", revealRiddle);
riddleInput.addEventListener("keydown", e=>{ if(e.key === "Enter") revealRiddle(); });
riddlePrev.addEventListener("click", ()=> goTo(ri-1));
riddleNext.addEventListener("click", ()=> goTo(ri+1));

// ---------- Memory match game ----------
const MEMORY_ICONS = {
  coffee: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M4 9h13v6a4 4 0 01-4 4H8a4 4 0 01-4-4V9z"/><path d="M17 10h1.5a2.5 2.5 0 010 5H17"/><path d="M8 4c0 1-1 1-1 2M12 4c0 1-1 1-1 2"/></svg>',
  book: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M3 6c2-1 5-1 7 0v13c-2-1-5-1-7 0V6z"/><path d="M21 6c-2-1-5-1-7 0v13c2-1 5-1 7 0V6z"/></svg>',
  eq: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="9" x2="5" y2="15"/><line x1="10" y1="5" x2="10" y2="19"/><line x1="15" y1="8" x2="15" y2="16"/><line x1="20" y1="10" x2="20" y2="14"/></svg>',
  headphones: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M4 13v-1a8 8 0 0116 0v1"/><rect x="2" y="13" width="5" height="7" rx="2"/><rect x="17" y="13" width="5" height="7" rx="2"/></svg>',
  umbrella: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3a9 9 0 019 9H3a9 9 0 019-9z"/><line x1="12" y1="3" x2="12" y2="18"/><path d="M12 18a2 2 0 01-4 0"/></svg>',
  spark: '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2l1.8 6.2L20 10l-6.2 1.8L12 18l-1.8-6.2L4 10l6.2-1.8L12 2z"/></svg>'
};

function shuffle(arr){
  for(let i = arr.length - 1; i > 0; i--){
    const j = Math.floor(Math.random() * (i + 1));
    [arr[i], arr[j]] = [arr[j], arr[i]];
  }
  return arr;
}

const memoryGrid = document.getElementById("memoryGrid");
const memoryStatus = document.getElementById("memoryStatus");
const memoryWin = document.getElementById("memoryWin");
const iconKeys = Object.keys(MEMORY_ICONS);
const deck = shuffle([...iconKeys, ...iconKeys]);

let firstCard = null, secondCard = null, lockBoard = false, matches = 0;

deck.forEach((key)=>{
  const card = document.createElement("div");
  card.className = "memory-card";
  card.dataset.icon = key;
  card.innerHTML =
    '<div class="memory-inner">' +
      '<div class="memory-face memory-front"></div>' +
      '<div class="memory-face memory-back">' + MEMORY_ICONS[key] + '</div>' +
    '</div>';
  card.addEventListener("click", ()=> flipMemoryCard(card));
  memoryGrid.appendChild(card);
});

function flipMemoryCard(card){
  if(lockBoard || card.classList.contains("flipped") || card.classList.contains("matched")) return;
  card.classList.add("flipped");

  if(!firstCard){
    firstCard = card;
    return;
  }
  secondCard = card;
  lockBoard = true;

  if(firstCard.dataset.icon === secondCard.dataset.icon){
    firstCard.classList.add("matched");
    secondCard.classList.add("matched");
    matches++;
    memoryStatus.textContent = matches + " / 6 matched";
    resetMemoryTurn();
    if(matches === iconKeys.length){
      memoryWin.classList.add("show");
    }
  } else {
    setTimeout(()=>{
      firstCard.classList.remove("flipped");
      secondCard.classList.remove("flipped");
      resetMemoryTurn();
    }, 700);
  }
}

function resetMemoryTurn(){
  [firstCard, secondCard] = [null, null];
  lockBoard = false;
}

// ---------- Slide to send ----------
const track = document.getElementById("slideTrack");
const handle = document.getElementById("slideHandle");
const fill = document.getElementById("slideFill");
const slideLabel = document.getElementById("slideLabel");
const slideReveal = document.getElementById("slideReveal");

const PAD = 6, SIZE = 52;
let maxLeft = 0, dragging = false, startX = 0, startLeft = PAD, slideDone = false;

function setupSlide(){
  maxLeft = track.clientWidth - SIZE - PAD;
}
setupSlide();
window.addEventListener("resize", setupSlide);

function setHandle(left, animate){
  handle.style.left = left + "px";
  const progress = Math.max(0, Math.min(1, (left-PAD)/(maxLeft-PAD)));
  fill.style.width = (left + SIZE/2) + "px";
  slideLabel.style.opacity = Math.max(1 - progress*1.6, 0);
  handle.setAttribute("aria-valuenow", Math.round(progress*100));
}

function completeSlide(){
  if(slideDone) return;
  slideDone = true;
  setHandle(maxLeft);
  track.classList.add("completed");
  slideReveal.classList.add("show");
}

function resetSlide(){
  setHandle(PAD);
}

handle.addEventListener("pointerdown", (e)=>{
  if(slideDone) return;
  dragging = true;
  handle.classList.add("dragging");
  startX = e.clientX;
  startLeft = handle.offsetLeft;
  handle.setPointerCapture(e.pointerId);
});
handle.addEventListener("pointermove", (e)=>{
  if(!dragging) return;
  const delta = e.clientX - startX;
  const newLeft = Math.min(Math.max(startLeft + delta, PAD), maxLeft);
  setHandle(newLeft);
});
handle.addEventListener("pointerup", ()=>{
  if(!dragging) return;
  dragging = false;
  handle.classList.remove("dragging");
  const progress = (handle.offsetLeft - PAD) / (maxLeft - PAD);
  if(progress > 0.85){ completeSlide(); } else { resetSlide(); }
});
handle.addEventListener("keydown", (e)=>{
  if(e.key === "Enter" || e.key === " "){ e.preventDefault(); completeSlide(); }
  if(e.key === "ArrowRight"){ setHandle(Math.min(handle.offsetLeft + 24, maxLeft)); }
  if(e.key === "ArrowLeft"){ setHandle(Math.max(handle.offsetLeft - 24, PAD)); }
});

// ---------- Scroll reveal ----------
const revealEls = document.querySelectorAll(".reveal");
const io = new IntersectionObserver((entries)=>{
  entries.forEach(entry=>{
    if(entry.isIntersecting){
      entry.target.classList.add("in-view");
      io.unobserve(entry.target);
    }
  });
}, { threshold: 0.2 });
revealEls.forEach(el=> io.observe(el));

// ---------- Confetti on final CTA click ----------
const ctaBtn = document.getElementById("ctaBtn");
const canvas = document.getElementById("confetti-canvas");
const ctx = canvas.getContext("2d");
let W, H;
function resizeCanvas(){ W = canvas.width = innerWidth; H = canvas.height = innerHeight; }
resizeCanvas();
window.addEventListener("resize", resizeCanvas);

const colors = ["#FF7A9C","#6C5CE7","#FFD9E2","#E7E3FB","#2B2530"];
let particles = [];
function burst(){
  particles = [];
  for(let i=0;i<90;i++){
    particles.push({
      x: W/2, y: H*0.6,
      vx: (Math.random()-0.5)*10,
      vy: Math.random()*-10-4,
      size: Math.random()*6+4,
      color: colors[Math.floor(Math.random()*colors.length)],
      rot: Math.random()*360,
      vr: (Math.random()-0.5)*10,
      life: 100
    });
  }
  requestAnimationFrame(tick);
}
function tick(){
  ctx.clearRect(0,0,W,H);
  particles.forEach(p=>{
    p.x += p.vx; p.y += p.vy; p.vy += 0.35; p.rot += p.vr; p.life--;
    ctx.save();
    ctx.translate(p.x,p.y);
    ctx.rotate(p.rot*Math.PI/180);
    ctx.fillStyle = p.color;
    ctx.globalAlpha = Math.max(p.life/100,0);
    ctx.fillRect(-p.size/2,-p.size/2,p.size,p.size);
    ctx.restore();
  });
  particles = particles.filter(p=>p.life>0);
  if(particles.length>0) requestAnimationFrame(tick);
  else ctx.clearRect(0,0,W,H);
}
ctaBtn.addEventListener("click", ()=>{ burst(); });
</script>
</body>
</html>
