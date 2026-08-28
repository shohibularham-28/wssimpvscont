<!DOCTYPE html>
<html lang="en" translate="no">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Tense Case File — Present Simple &amp; Present Continuous</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Special+Elite&family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@500;700&display=swap" rel="stylesheet">
<style>
  :root{
    --ink:#161A24;
    --navy:#1B2540;
    --navy-deep:#121729;
    --paper:#F3ECDA;
    --paper-dark:#E7DDC2;
    --brass:#C9A227;
    --brass-light:#E4C862;
    --red:#B23A48;
    --red-light:#D6707C;
    --green:#4F7942;
    --green-light:#7FAE6C;
    --text:#21232B;
    --muted:#6B6656;
    --shadow: 0 10px 30px rgba(0,0,0,.25);
    --radius: 14px;
  }
  *{box-sizing:border-box;}
  html,body{margin:0;padding:0;}
  body{
    font-family:'Inter',sans-serif;
    background:
      radial-gradient(circle at 15% 10%, rgba(201,162,39,.08), transparent 40%),
      radial-gradient(circle at 85% 90%, rgba(178,58,72,.08), transparent 40%),
      var(--navy-deep);
    color:var(--text);
    min-height:100vh;
    -webkit-font-smoothing:antialiased;
  }
  .app{
    max-width:1100px;
    margin:0 auto;
    padding:22px 18px 60px;
  }

  /* ---------- HEADER ---------- */
  .header{
    background:var(--navy);
    border:1px solid rgba(201,162,39,.35);
    border-radius:var(--radius);
    padding:22px 26px;
    box-shadow:var(--shadow);
    position:relative;
    overflow:hidden;
    margin-bottom:18px;
  }
  .header::before{
    content:"";
    position:absolute; inset:0;
    background-image:repeating-linear-gradient(0deg, rgba(255,255,255,.02) 0 1px, transparent 1px 3px);
    pointer-events:none;
  }
  .case-label{
    font-family:'JetBrains Mono',monospace;
    color:var(--brass-light);
    font-size:12px;
    letter-spacing:.14em;
    text-transform:uppercase;
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-bottom:8px;
  }
  .case-label .id{border:1px solid var(--brass); padding:2px 8px; border-radius:4px;}
  .title{
    font-family:'Special Elite', 'Courier New', monospace;
    color:var(--paper);
    font-size:clamp(22px,4vw,34px);
    margin:0 0 4px;
    letter-spacing:.02em;
  }
  .subtitle{
    color:#B9C0D6;
    font-size:14px;
    margin:0 0 16px;
  }
  .status-row{
    display:flex; flex-wrap:wrap; gap:14px; align-items:center; justify-content:space-between;
  }
  .score-pill{
    font-family:'JetBrains Mono',monospace;
    background:var(--brass);
    color:var(--navy-deep);
    font-weight:700;
    padding:8px 16px;
    border-radius:999px;
    font-size:15px;
    box-shadow:0 3px 0 rgba(0,0,0,.25);
    white-space:nowrap;
  }
  .progress-track{
    flex:1;
    min-width:180px;
    height:10px;
    background:rgba(255,255,255,.08);
    border-radius:999px;
    overflow:hidden;
    border:1px solid rgba(255,255,255,.15);
  }
  .progress-fill{
    height:100%;
    background:linear-gradient(90deg, var(--brass), var(--brass-light));
    width:0%;
    transition:width .6s cubic-bezier(.4,0,.2,1);
  }
  .progress-text{
    font-family:'JetBrains Mono',monospace;
    font-size:12px;
    color:#B9C0D6;
    white-space:nowrap;
  }

  /* ---------- STUDENT INFO ---------- */
  .student-info{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    margin-top:14px;
    margin-bottom:2px;
  }
  .student-field{
    flex:1;
    min-width:160px;
    display:flex;
    align-items:center;
    background:rgba(255,255,255,.06);
    border:1px solid rgba(201,162,39,.35);
    border-radius:8px;
    padding:0 12px;
  }
  .student-field label{
    font-family:'JetBrains Mono',monospace;
    font-size:11px;
    color:var(--brass-light);
    text-transform:uppercase;
    letter-spacing:.08em;
    white-space:nowrap;
    margin-right:8px;
  }
  .student-field input{
    flex:1;
    background:transparent;
    border:none;
    outline:none;
    color:var(--paper);
    font-family:'Inter',sans-serif;
    font-size:14px;
    padding:9px 0;
  }
  .student-field input::placeholder{color:#8A93B3;}

  /* ---------- STAGE NAV ---------- */
  .stage-nav{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(88px,1fr));
    gap:8px;
    margin-bottom:18px;
  }
  .stage-tab{
    background:var(--paper);
    border:2px solid var(--paper-dark);
    border-radius:10px;
    padding:10px 6px;
    text-align:center;
    cursor:pointer;
    font-family:'JetBrains Mono',monospace;
    font-size:11px;
    color:var(--muted);
    transition:transform .15s ease, box-shadow .15s ease, border-color .15s ease;
    user-select:none;
  }
  .stage-tab .icon{font-size:16px; display:block; margin-bottom:3px;}
  .stage-tab .name{display:block; font-weight:600; font-size:10.5px; line-height:1.3;}
  .stage-tab.locked{
    cursor:not-allowed;
    opacity:.55;
    background:repeating-linear-gradient(45deg, var(--paper) 0 6px, var(--paper-dark) 6px 12px);
  }
  .stage-tab.current{
    border-color:var(--brass);
    box-shadow:0 0 0 3px rgba(201,162,39,.25);
    transform:translateY(-2px);
  }
  .stage-tab.completed{
    border-color:var(--green);
    background:#EAF0E4;
  }
  .stage-tab.completed .icon{color:var(--green);}

  /* ---------- CASE PAGE ---------- */
  .case-page{
    background:var(--paper);
    border-radius:var(--radius);
    box-shadow:var(--shadow);
    padding:28px clamp(16px,4vw,40px) 36px;
    position:relative;
    border:1px solid var(--paper-dark);
  }
  .case-page.animate-in{
    animation:pageIn .3s ease;
  }
  @keyframes pageIn{
    from{opacity:0; transform:translateY(8px);}
    to{opacity:1; transform:translateY(0);}
  }
  .paperclip{
    position:absolute;
    top:-14px; left:28px;
    width:34px; height:52px;
    border:5px solid #8b8f9b;
    border-radius:16px;
    background:transparent;
    box-shadow: inset 0 0 0 5px var(--paper-dark) , 0 4px 5px rgba(0,0,0,.25);
    transform:rotate(-8deg);
  }
  .stage-heading{
    display:flex; align-items:baseline; gap:12px; flex-wrap:wrap;
    border-bottom:2px dashed var(--paper-dark);
    padding-bottom:14px;
    margin-bottom:22px;
  }
  .stage-heading h2{
    font-family:'Special Elite', monospace;
    font-size:clamp(20px,3vw,28px);
    margin:0;
    color:var(--ink);
  }
  .stage-points{
    font-family:'JetBrains Mono',monospace;
    background:var(--navy);
    color:var(--brass-light);
    padding:4px 10px;
    border-radius:6px;
    font-size:12px;
  }
  .explain{
    background:#fff;
    border:1px solid var(--paper-dark);
    border-left:5px solid var(--brass);
    border-radius:8px;
    padding:16px 20px;
    margin-bottom:24px;
    font-size:14.5px;
    line-height:1.65;
  }
  .explain h3{margin:0 0 6px; font-size:15px; color:var(--navy);}
  .explain ul{margin:6px 0 10px 20px; padding:0;}
  .explain .ex{
    display:block;
    font-style:italic;
    color:var(--navy);
    margin:4px 0;
    padding-left:10px;
    border-left:3px solid var(--green-light);
  }
  .explain hr{border:none; border-top:1px dashed var(--paper-dark); margin:14px 0;}

  /* ---------- STAGE 1 ILLUSTRATION ---------- */
  .stage-hero-container {
    display: flex;
    align-items: center;
    gap: 20px;
    background: #fffdf5;
    border: 1px solid var(--paper-dark);
    border-radius: 12px;
    padding: 16px 20px;
    margin-bottom: 24px;
    box-shadow: 0 4px 12px rgba(0,0,0,.04);
  }
  .stage-hero-img {
    width: 110px;
    height: 110px;
    object-fit: cover;
    border-radius: 50%;
    border: 3px solid var(--brass);
    flex-shrink: 0;
    box-shadow: 0 4px 8px rgba(0,0,0,.1);
  }
  .stage-hero-text h3 {
    margin: 0 0 6px;
    font-family: 'Special Elite', monospace;
    color: var(--navy);
    font-size: 18px;
  }
  .stage-hero-text p {
    margin: 0;
    font-size: 14px;
    line-height: 1.5;
    color: var(--muted);
  }
  @media(max-width: 600px){
    .stage-hero-container{ flex-direction: column; text-align: center; }
  }

  /* ---------- QUESTIONS ---------- */
  .question{
    background:#fff;
    border:1px solid var(--paper-dark);
    border-radius:10px;
    padding:16px 18px;
    margin-bottom:14px;
    transition:box-shadow .2s ease, border-color .2s ease;
  }
  .question.correct{border-color:var(--green); box-shadow:0 0 0 3px rgba(79,121,66,.12);}
  .question.incorrect{border-color:var(--red); box-shadow:0 0 0 3px rgba(178,58,72,.12);}
  .q-num{
    font-family:'JetBrains Mono',monospace;
    font-size:11px;
    color:var(--muted);
    text-transform:uppercase;
    letter-spacing:.08em;
    margin-bottom:6px;
    display:block;
  }
  .q-prompt{font-size:15px; font-weight:600; margin-bottom:12px; line-height:1.5;}
  .options{display:flex; flex-direction:column; gap:8px;}
  .option{
    display:flex; align-items:center; gap:10px;
    padding:10px 12px;
    border:1.5px solid var(--paper-dark);
    border-radius:8px;
    cursor:pointer;
    font-size:14.5px;
    transition:background .15s ease, border-color .15s ease;
    background:#fdfcf8;
  }
  .option:hover{border-color:var(--brass);}
  .option input{accent-color:var(--navy);}
  .option.picked{border-color:var(--navy); background:#eef0f7;}
  .text-input{
    width:100%;
    padding:11px 14px;
    border:1.5px solid var(--paper-dark);
    border-radius:8px;
    font-size:14.5px;
    font-family:'Inter',sans-serif;
    background:#fdfcf8;
  }
  .text-input:focus{outline:none; border-color:var(--navy);}
  .feedback{
    margin-top:10px;
    font-size:13.5px;
    padding:9px 12px;
    border-radius:7px;
    display:none;
    line-height:1.5;
  }
  .feedback.show{display:block;}
  .feedback.ok{background:#E9F2E4; color:#345226; border:1px solid var(--green);}
  .feedback.bad{background:#F7E7E9; color:#6E2530; border:1px solid var(--red);}

  /* ---------- DRAG AND DROP CLASSIFY ---------- */
  .dnd-wrapper{
    display:flex;
    flex-direction:column;
    gap:16px;
    margin-top:10px;
  }
  .dnd-pool-box{
    background:#f5efe2;
    border:2px dashed var(--paper-dark);
    border-radius:10px;
    padding:14px;
    min-height:70px;
    transition:border-color .15s ease, background-color .15s ease;
  }
  .dnd-pool-label{
    font-family:'JetBrains Mono',monospace;
    font-size:11px;
    color:var(--muted);
    text-transform:uppercase;
    margin-bottom:10px;
    display:flex;
    justify-content:space-between;
    align-items:center;
  }
  .dnd-pool-items{
    display:flex;
    flex-wrap:wrap;
    gap:8px;
    min-height:38px;
  }
  .dnd-zones{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:14px;
  }
  @media (max-width: 600px){
    .dnd-zones{ grid-template-columns:1fr; }
  }
  .dnd-zone{
    background:#ffffff;
    border:2px dashed var(--paper-dark);
    border-radius:10px;
    padding:14px;
    min-height:160px;
    transition:background-color .15s ease, border-color .15s ease;
    display:flex;
    flex-direction:column;
  }
  .dnd-zone.drag-over, .dnd-pool-box.drag-over{
    background:#F3F6FA;
    border-color:var(--navy);
  }
  .dnd-zone-title{
    font-family:'JetBrains Mono',monospace;
    font-weight:700;
    font-size:13px;
    padding:6px 10px;
    border-radius:6px;
    margin-bottom:10px;
    text-align:center;
    letter-spacing:.04em;
  }
  .dnd-zone-title.simple{ background:#E8EEF8; color:var(--navy); }
  .dnd-zone-title.continuous{ background:#E5F2E8; color:var(--green); }
  .dnd-zone-items{
    flex:1;
    display:flex;
    flex-wrap:wrap;
    align-content:flex-start;
    gap:8px;
    padding:4px;
    min-height:90px;
  }
  .dnd-chip{
    font-family:'JetBrains Mono',monospace;
    font-size:13px;
    font-weight:500;
    padding:8px 14px;
    border-radius:8px;
    border:1.5px solid var(--paper-dark);
    background:#ffffff;
    color:var(--ink);
    cursor:grab;
    user-select:none;
    box-shadow:0 2px 4px rgba(0,0,0,.06);
    transition:border-color .15s ease, background-color .15s ease, box-shadow .15s ease;
    display:inline-flex;
    align-items:center;
    gap:6px;
  }
  .dnd-chip:active{ cursor:grabbing; }
  .dnd-chip:hover{ border-color:var(--brass); }
  .dnd-chip.dragging{ opacity:0.3; }
  .dnd-chip.selected-chip{
    border-color:var(--brass);
    background:var(--brass-light);
    box-shadow:0 0 0 3px rgba(201,162,39,.3);
  }
  .dnd-chip.item-correct{
    border-color:var(--green);
    background:#EAF0E4;
    color:#2B4C1E;
  }
  .dnd-chip.item-incorrect{
    border-color:var(--red);
    background:#F7E7E9;
    color:#6E2530;
  }

  /* ---------- BUTTONS ---------- */
  .btn{
    font-family:'Inter',sans-serif;
    font-weight:700;
    font-size:14.5px;
    padding:13px 26px;
    border-radius:999px;
    border:none;
    cursor:pointer;
    transition:transform .12s ease, box-shadow .12s ease;
    box-shadow:0 4px 0 rgba(0,0,0,.25);
  }
  .btn:active{transform:translateY(3px); box-shadow:0 1px 0 rgba(0,0,0,.25);}
  .btn:disabled{opacity:.5; cursor:not-allowed;}
  .btn-primary{background:var(--navy); color:var(--paper);}
  .btn-gold{background:var(--brass); color:var(--navy-deep);}
  .btn-red{background:var(--red); color:#fff;}
  .btn-row{display:flex; justify-content:center; margin-top:20px;}

  /* ---------- STAMP / COMPLETE ---------- */
  .stamp-overlay{
    position:fixed; inset:0;
    background:rgba(18,23,41,.55);
    display:none;
    align-items:center; justify-content:center;
    z-index:50;
    animation:fadeIn .2s ease;
  }
  .stamp-overlay.show{display:flex;}
  @keyframes fadeIn{from{opacity:0;} to{opacity:1;}}
  .stamp-card{
    background:var(--paper);
    border-radius:var(--radius);
    padding:34px 30px;
    text-align:center;
    max-width:420px;
    width:90%;
    box-shadow:var(--shadow);
    border:3px solid var(--brass);
    animation:stampIn .35s cubic-bezier(.2,1.4,.4,1);
  }
  @keyframes stampIn{
    from{transform:scale(.5) rotate(-12deg); opacity:0;}
    to{transform:scale(1) rotate(0deg); opacity:1;}
  }
  .stamp-card .big-icon{font-size:46px; margin-bottom:8px;}
  .stamp-card h3{
    font-family:'Special Elite', monospace;
    font-size:24px;
    margin:0 0 10px;
    color:var(--navy);
  }
  .stamp-card .score-line{
    font-family:'JetBrains Mono',monospace;
    font-size:16px;
    background:var(--navy);
    color:var(--brass-light);
    padding:8px 14px;
    border-radius:8px;
    display:inline-block;
    margin-bottom:18px;
  }

  /* ---------- FINAL RESULT ---------- */
  .final-score{
    font-family:'Special Elite', monospace;
    font-size:clamp(48px,10vw,72px);
    text-align:center;
    color:var(--navy);
    margin:6px 0 2px;
  }
  .final-score span{font-size:.4em; color:var(--muted);}
  .category-banner{
    text-align:center;
    padding:18px;
    border-radius:10px;
    margin:18px 0;
    font-family:'Special Elite',monospace;
  }
  .stage-results{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
    gap:10px;
    margin:20px 0;
  }
  .stage-result-item{
    background:#fff;
    border:1px solid var(--paper-dark);
    border-radius:8px;
    padding:10px 12px;
    font-family:'JetBrains Mono',monospace;
    font-size:13px;
    text-align:center;
  }
  .stage-result-item b{display:block; font-size:16px; color:var(--navy); margin-top:2px;}

  .locked-note{
    text-align:center;
    color:var(--muted);
    padding:60px 20px;
    font-family:'JetBrains Mono',monospace;
  }

  @media (max-width:700px){
    .stage-nav{grid-template-columns:repeat(4,1fr);}
    .stage-tab .name{display:none;}
  }
</style>
</head>
<body>

<div class="app">

  <div class="header">
    <div class="case-label">
      <span>🕵️ Grammar Investigation Bureau</span>
      <span class="id">CASE #PS-PC-01</span>
    </div>
    <h1 class="title">The Tense Case File</h1>
    <p class="subtitle">Present Simple &amp; Present Continuous — complete each stage of the case to close the file.</p>
    <div class="student-info">
      <div class="student-field">
        <label for="studentName">Name</label>
        <input type="text" id="studentName" placeholder="Enter your name..." oninput="updateStudentInfo()">
      </div>
      <div class="student-field">
        <label for="studentClass">Class</label>
        <input type="text" id="studentClass" placeholder="Enter your class..." oninput="updateStudentInfo()">
      </div>
    </div>
    <div class="status-row">
      <div class="progress-track"><div class="progress-fill" id="progressFill"></div></div>
      <span class="progress-text" id="progressText">Stage 1 of 7</span>
      <span class="score-pill" id="scorePill">SCORE: 0 / 122</span>
    </div>
  </div>

  <div class="stage-nav" id="stageNav"></div>

  <div id="stageContainer"></div>

</div>

<div class="stamp-overlay" id="stampOverlay">
  <div class="stamp-card" id="stampCard"></div>
</div>

<script>
/* ============================================================
   DATA
   ============================================================ */
const norm = s => (s||"").toString().trim().toLowerCase()
  .replace(/[.!?]+$/,"")
  .replace(/\s+/g," ")
  .replace(/’/g,"'");

const stages = [
  {
    id:1, name:"Understanding", icon:"🔍", max:12, perQ:2,
    title:"Stage 1 — Understanding Tense Forms",
    heroImage: "data:image/png;base64,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",
    heroTitle: "Detective Field Notes",
    heroDesc: "Welcome to the Grammar Investigation Bureau! Review the basic clues below before you start interrogating the sentences.",
    explain:`
      <h3>Present Simple</h3>
      <p>Used for routines, habits, repeated actions, and general facts.</p>
      <span class="ex">I go to school every day.</span>
      <span class="ex">She plays badminton on Sundays.</span>
      <hr>
      <h3>Present Continuous</h3>
      <p>Used for actions happening right now and temporary activities.</p>
      <span class="ex">I am doing my homework now.</span>
      <span class="ex">They are playing football at the moment.</span>
    `,
    questions:[
      {type:"mc", prompt:"Which sentence describes a routine?",
        options:["She plays badminton on Sundays.","She is playing badminton right now.","She played badminton yesterday."],
        correct:0, explain:"Routines use the Present Simple tense: plays."},
      {type:"mc", prompt:"Which sentence describes an action happening right now?",
        options:["They play football every weekend.","They are playing football at the moment.","They played football last week."],
        correct:1, explain:"Ongoing actions use the Present Continuous tense: are playing."},
      {type:"mc", prompt:"Which time marker typically goes with the Present Simple?",
        options:["right now","usually","at the moment"],
        correct:1, explain:"\"Usually\" indicates a habit, which pairs with the Present Simple."},
      {type:"mc", prompt:"Which time marker typically goes with the Present Continuous?",
        options:["every day","always","at the moment"],
        correct:2, explain:"\"At the moment\" refers to things happening right now, pairing with the Present Continuous."},
      {type:"mc", prompt:"What happens to the verb for he/she/it subjects in the Present Simple?",
        options:["We add -s or -es","We remove the last letter","We add -ing"],
        correct:0, explain:"For he/she/it, we add -s or -es: play → plays, watch → watches."},
      {type:"classify", prompt:"Drag & Drop each time marker into the correct tense box below (or tap an item, then tap a box).",
        items:[
          {text:"every day", correct:0},
          {text:"usually", correct:0},
          {text:"on Mondays", correct:0},
          {text:"always", correct:0},
          {text:"right now", correct:1},
          {text:"at the moment", correct:1},
          {text:"now", correct:1},
          {text:"currently", correct:1}
        ],
        explain:"Present Simple: every day, usually, on Mondays, always. Present Continuous: right now, at the moment, now, currently."}
    ]
  },
  {
    id:2, name:"Pres. Simple", icon:"📘", max:20, perQ:2,
    title:"Stage 2 — Mastering Present Simple (Murphy Style)",
    explain:`
      <h3>Complete the sentences using the Present Simple (e.g., I work / she works)</h3>
      <p>Pay attention to the situation/context and write the correct verb form in the blank.</p>
      <span class="ex">Water (boil) at 100 degrees Celsius. → boils</span>
      <span class="ex">Julia (not / drink) coffee very often. → doesn't drink</span>
    `,
    questions:[
      {type:"text", prompt:"1. \"The sun ___ (rise) in the east.\"", accept:["rises"], explain:"General facts use the Present Simple with -s: rises."},
      {type:"text", prompt:"2. \"Ann ___ (not / drink) coffee very often.\"", accept:["doesn't drink","does not drink"], explain:"Third-person singular negative uses doesn't + base verb."},
      {type:"text", prompt:"3. \"Badminton? I ___ (play) it a lot on weekends.\"", accept:["play"], explain:"Habits with the subject 'I' use the base verb: play."},
      {type:"text", prompt:"4. \"Excuse me, do you ___ (speak) English?\"", accept:["speak"], explain:"In questions with 'Do you', use the base verb: speak."},
      {type:"text", prompt:"5. \"My parents ___ (live) in a very small apartment.\"", accept:["live"], explain:"Plural subjects like 'My parents' take the base verb: live."},
      {type:"text", prompt:"6. \"It ___ (take) me twenty minutes to walk to work.\"", accept:["takes"], explain:"The third-person singular subject 'It' requires -s: takes."},
      {type:"text", prompt:"7. \"Where ___ (your father / work)?\" (Write: aux - subject - verb)", accept:["does your father work"], explain:"Present Simple question pattern: Question word + does + subject + base verb."},
      {type:"text", prompt:"8. \"Categorically, she ___ (not / like) maths classes.\"", accept:["doesn't like","does not like"], explain:"Negative form for 'she' uses doesn't like."},
      {type:"text", prompt:"9. \"The banks here ___ (open) at 9 o'clock in the morning.\"", accept:["open"], explain:"Plural subject 'The banks' takes the base verb: open."},
      {type:"text", prompt:"10. \"What time ___ (the shops / close) on Saturdays?\" (Write: aux - subject - verb)", accept:["do the shops close"], explain:"Question pattern with plural subject 'shops': do + subject + base verb."}
    ]
  },
  {
    id:3, name:"Pres. Cont.", icon:"📗", max:20, perQ:2,
    title:"Stage 3 — Mastering Present Continuous (Murphy Style)",
    explain:`
      <h3>Complete the sentences using the Present Continuous (e.g., is working / are playing)</h3>
      <p>Look at the situation. What is happening at the time of speaking?</p>
      <span class="ex">Please be quiet. I (work). → am working</span>
      <span class="ex">Look! Somebody (swim) in the river. → is swimming</span>
    `,
    questions:[
      {type:"text", prompt:"1. \"Listen! Someone ___ (play) the guitar next door.\"", accept:["is playing"], explain:"Actions happening now use is + verb-ing: is playing."},
      {type:"text", prompt:"2. \"Please don't make so much noise. I ___ (try) to work.\"", accept:["am trying"], explain:"Temporary ongoing activity happening right now: am trying."},
      {type:"text", prompt:"3. \"Where is Mark?\" — \"He ___ (have) a shower at the moment.\"", accept:["is having"], explain:"Action happening right now: is having."},
      {type:"text", prompt:"4. \"Look outside! It ___ (snow), we can build a snowman.\"", accept:["is snowing"], explain:"Observed ongoing event: is snowing."},
      {type:"text", prompt:"5. \"Why ___ you ___ (wear) a coat today? It's quite warm!\" (Write: aux - subject - verb-ing)", accept:["are you wearing"], explain:"Present Continuous question: Are + subject + verb-ing."},
      {type:"text", prompt:"6. \"You ___ (not / listen) to me! What are you thinking about?\"", accept:["aren't listening","are not listening"], explain:"Present Continuous negative: are not / aren't listening."},
      {type:"text", prompt:"7. \"The population of the world ___ (increase) very fast nowadays.\"", accept:["is increasing"], explain:"Changing trends happening nowadays use the Present Continuous: is increasing."},
      {type:"text", prompt:"8. \"Hurry up! The train ___ (come).\"", accept:["is coming"], explain:"Event happening right now: is coming."},
      {type:"text", prompt:"9. \"I ___ (not / work) this week. I'm on vacation.\"", accept:["am not working","m not working"], explain:"Temporary situation this week: am not working."},
      {type:"text", prompt:"10. \"What ___ your brother ___ (do) these days?\" (Write: aux - subject - verb-ing)", accept:["is your brother doing"], explain:"Temporary situation around the present time: is your brother doing."}
    ]
  },
  {
    id:4, name:"Tense Battle", icon:"⚔️", max:20, perQ:2,
    title:"Stage 4 — Present Simple vs Present Continuous (Murphy Style)",
    explain:`
      <h3>Present Simple (I do) vs Present Continuous (I am doing)</h3>
      <p>Choose the correct verb form for each situation based on whether it is a routine/permanent fact or a temporary ongoing action.</p>
      <span class="ex">Normally I live in London, but this month I (live) in Paris. → am living</span>
      <span class="ex">My brother usually (work) hard, but today he is relaxing. → works</span>
    `,
    questions:[
      {type:"text", prompt:"1. \"Let's go out. It ___ (not / rain) right now.\"", accept:["isn't raining","is not raining"], explain:"Action happening at the moment of speaking: isn't raining."},
      {type:"text", prompt:"2. \"Julia is good at languages. She ___ (speak) four languages fluently.\"", accept:["speaks"], explain:"Permanent skill/fact: Present Simple -> speaks."},
      {type:"text", prompt:"3. \"Can you ring back later? We ___ (have) dinner at the moment.\"", accept:["are having"], explain:"Temporary action happening right now: are having."},
      {type:"text", prompt:"4. \"Usually, Kate ___ (drive) to work, but today she is taking the bus.\"", accept:["drives"], explain:"Habitual routine: Present Simple -> drives."},
      {type:"text", prompt:"5. \"Look at that man! What ___ he ___ (do) by the window?\" (Write: aux - subject - verb-ing)", accept:["is he doing"], explain:"Action happening right now: is he doing."},
      {type:"text", prompt:"6. \"The earth ___ (go) round the sun once every 365 days.\"", accept:["goes"], explain:"Scientific fact / general truth: Present Simple -> goes."},
      {type:"text", prompt:"7. \"I ___ (want) to buy a new laptop, but I don't have enough money.\"", accept:["want"], explain:"Stative verb (desire), not normally used in the continuous form: want."},
      {type:"text", prompt:"8. \"Ron is in London right now. He ___ (stay) at the Grand Hotel.\"", accept:["is staying"], explain:"Temporary lodging: Present Continuous -> is staying."},
      {type:"text", prompt:"9. \"Vegetarians ___ (not / eat) meat.\"", accept:["don't eat","do not eat"], explain:"General rule / fact about a group: Present Simple -> don't eat."},
      {type:"text", prompt:"10. \"Be quiet! I ___ (try) to concentrate on my book.\"", accept:["am trying"], explain:"Action happening at the time of speaking: am trying."}
    ]
  },
  {
    id:5, name:"Detective", icon:"🕵️", max:15, perQ:3,
    title:"Stage 5 — Grammar Detective",
    explain:`
      <h3>Spot the mistake, fix the file</h3>
      <p>Each sentence below contains one grammar mistake. Type the corrected sentence. Watch out for: incorrect do/does, incorrect am/is/are, missing -s, wrong -ing forms, or wrong tense choices.</p>
      <span class="ex">Incorrect: She is usually getting up at 5 a.m.</span>
      <span class="ex">Correct: She usually gets up at 5 a.m.</span>
    `,
    questions:[
      {type:"text", prompt:"Find and fix the mistake: \"She is usually getting up at 5 a.m.\"", accept:["she usually gets up at 5 a.m","she usually gets up at 5am"], explain:"Routines use the Present Simple: she usually gets up at 5 a.m."},
      {type:"text", prompt:"Find and fix the mistake: \"He don't like tea.\"", accept:["he doesn't like tea","he does not like tea"], explain:"For the subject 'he', use doesn't: he doesn't like tea."},
      {type:"text", prompt:"Find and fix the mistake: \"They is playing in the garden.\"", accept:["they are playing in the garden"], explain:"For the subject 'they', use are: they are playing in the garden."},
      {type:"text", prompt:"Find and fix the mistake: \"I am study English now.\"", accept:["i am studying english now"], explain:"After am/is/are we need the verb-ing form: I am studying English now."},
      {type:"text", prompt:"Find and fix the mistake: \"She work in a bank.\"", accept:["she works in a bank"], explain:"For the subject 'she', add -s: she works in a bank."}
    ]
  },
  {
    id:6, name:"Final", icon:"🏁", max:15, perQ:3,
    title:"Stage 6 — Final Challenge",
    explain:`
      <h3>Case closing page</h3>
      <p>These questions combine all material from the previous case files. Read carefully — some questions are trickier than before.</p>
    `,
    questions:[
      {type:"mc", prompt:"Which sentence is correct?",
        options:["She don't works today.","She doesn't work today.","She not works today."],
        correct:1, explain:"For 'she', use doesn't + base verb: doesn't work."},
      {type:"text", prompt:"My brother usually ___ (drive) to work, but today he ___ (walk).", accept:["drives, is walking","drives is walking"], explain:"Routine → drives (Present Simple). Today, something different → is walking (Present Continuous)."},
      {type:"mc", prompt:"Complete: \"Right now, the children ___\"",
        options:["play outside every day.","are playing outside.","plays outside."],
        correct:1, explain:"\"Right now\" requires the Present Continuous: are playing outside."},
      {type:"text", prompt:"Every winter, it ___ (snow) here.", accept:["snows"], explain:"Repeated seasonal fact → Present Simple: snows."},
      {type:"mc", prompt:"Which time marker matches the Present Continuous?",
        options:["every week","at the moment","usually"],
        correct:1, explain:"\"At the moment\" describes the present time, matching the Present Continuous."}
    ]
  },
  {
    id:7, name:"Time Clues", icon:"⏱️", max:20, perQ:2,
    title:"Stage 7 — Advanced Time Clues (Expert Level)",
    explain:`
      <h3>Beyond the basics</h3>
      <p>Most time markers are easy to guess — but some depend on <b>meaning</b>, not just form. Study these advanced cases closely.</p>
      <span class="ex">This week I usually go to the gym on Tuesdays. (routine, Present Simple)</span>
      <span class="ex">This week I am staying with my parents. (temporary, Present Continuous)</span>
      <hr>
      <p><b>Tricky time expressions:</b></p>
      <ul>
        <li><b>always / constantly / forever</b> — can indicate a habit (Present Simple) OR an annoying repeated action (Present Continuous with a complaining tone).</li>
        <li><b>nowadays / these days / currently / at present</b> — usually indicate a changing situation or trend → Present Continuous.</li>
        <li><b>this week / this month / this year</b> — depend on context: fixed routine → Present Simple; temporary arrangement → Present Continuous.</li>
        <li><b>increasingly / more and more / day by day</b> — describe continuous ongoing change → Present Continuous.</li>
        <li><b>as a rule / on the whole / generally</b> — describe general truths → Present Simple.</li>
      </ul>
      <span class="ex">He is always losing his keys! (annoyance, Present Continuous)</span>
      <span class="ex">He always locks the door before bed. (habit, Present Simple)</span>
    `,
    questions:[
      {type:"mc", prompt:"\"He is constantly interrupting me when I speak!\" — why is the Present Continuous used here even though \"constantly\" often indicates a habit?",
        options:["Because the speaker is explaining a fixed schedule","Because the speaker is expressing annoyance at a repeated behavior","Because the action is happening at this exact second"],
        correct:1, explain:"With always/constantly/forever, the Present Continuous can express irritation at something happening too often — not a neutral routine."},
      {type:"text", prompt:"Choose the best time expression: \"___, more people are working from home than ten years ago.\" (a trend, not a fixed fact)", accept:["nowadays","these days","currently","at present"], explain:"Words like \"nowadays\" or \"these days\" describe an evolving trend, pairing with the Present Continuous: are working."},
      {type:"mc", prompt:"\"The company ___ its profits every quarter.\" Which time marker fits best with the Present Simple here?",
        options:["is currently reviewing","reviews, as a rule,","is reviewing at the moment"],
        correct:1, explain:"\"As a rule\" indicates a repeated general procedure — a fact about the company, so it uses the Present Simple: reviews."},
      {type:"text", prompt:"\"Traffic in the city centre ___ (get) worse ___.\" Fill in BOTH the verb and a suitable time marker for an ongoing change.", accept:["is getting, day by day","is getting day by day","is getting, more and more","is getting more and more"], explain:"\"Day by day\" or \"more and more\" indicate gradual ongoing change → Present Continuous: is getting."},
      {type:"mc", prompt:"Which sentence correctly uses \"this month\" for a TEMPORARY arrangement rather than a routine?",
        options:["This month, the library closes at 6 p.m. every day, as usual.","This month, I am closing the shop early because of renovations.","This month, she closes her laptop at midnight, as she always does."],
        correct:1, explain:"\"This month\" describes a temporary change from the norm → Present Continuous: am closing. Other options describe unchanging routines."},
      {type:"text", prompt:"\"Scientists warn that global sea levels ___ (rise) ___.\" Complete with a verb and a time expression showing continuous change.", accept:["are rising increasingly","are rising, increasingly","are rising more and more","are rising, more and more"], explain:"\"Increasingly\" / \"more and more\" show an ongoing trend → Present Continuous: are rising."},
      {type:"mc", prompt:"\"On the whole, the new policy ___ well among staff.\" Which fits best?",
        options:["is working","works","is going to work"],
        correct:1, explain:"\"On the whole\" introduces a general evaluation/fact, which uses the Present Simple: works."},
      {type:"text", prompt:"\"She ___ (leave) her dirty dishes in the sink ___ — it's driving me crazy!\" Complete with the correct verb and time marker.", accept:["is always leaving","is forever leaving","is constantly leaving"], explain:"Always/forever/constantly + Present Continuous expresses annoyance at a repeated habit: is always leaving."},
      {type:"mc", prompt:"Which time marker is TYPICALLY NOT compatible with the Present Continuous?",
        options:["at present","every other day","increasingly"],
        correct:1, explain:"\"Every other day\" describes a repeating fixed schedule — a routine — so it pairs with the Present Simple, not the Present Continuous."},
      {type:"text", prompt:"\"___, the number of electric cars on our roads ___ (grow) rapidly.\" Complete with a matching opening time marker and the verb.", accept:["currently, is growing","currently is growing","nowadays, is growing","nowadays is growing","at present, is growing","at present is growing"], explain:"\"Currently\", \"nowadays\", or \"at present\" all refer to present-day trends → Present Continuous: is growing."}
    ]
  }
];

const TOTAL_MAX = stages.reduce((a,s)=>a+s.max,0);

/* ============================================================
   STATE
   ============================================================ */
const state = {
  studentName: '',
  studentClass: '',
  currentIndex: 0,
  unlocked: stages.map((s,i) => i===0),
  completed: stages.map(() => false),
  stageScores: stages.map(() => 0),
  answers: stages.map(s => new Array(s.questions.length).fill(null)),
  correctSet: stages.map(() => new Set()),
  finished: false,
  selectedChip: null // For tap-to-move feature {si, qi, ii}
};

let animateStageSwitch = true;

/* ============================================================
   RENDER: HEADER / NAV
   ============================================================ */
function totalScore(){ return state.stageScores.reduce((a,b)=>a+b,0); }

function updateStudentInfo(){
  state.studentName = document.getElementById('studentName').value;
  state.studentClass = document.getElementById('studentClass').value;
}
function escapeHtml(s){
  return (s||"").replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
}

function renderHeader(){
  const completedCount = state.completed.filter(Boolean).length;
  document.getElementById('progressFill').style.width = (completedCount/stages.length*100)+'%';
  document.getElementById('progressText').textContent =
    state.finished ? 'Case Closed' : `Stage ${state.currentIndex+1} of ${stages.length}`;
  document.getElementById('scorePill').textContent = `SCORE: ${totalScore()} / ${TOTAL_MAX}`;
}

function renderNav(){
  const nav = document.getElementById('stageNav');
  nav.innerHTML = '';
  stages.forEach((s,i)=>{
    const div = document.createElement('div');
    let cls = 'stage-tab';
    let icon = s.icon;
    if(state.completed[i]){ cls += ' completed'; icon='✅'; }
    else if(!state.unlocked[i]){ cls += ' locked'; icon='🔒'; }
    else if(i===state.currentIndex && !state.finished){ cls += ' current'; icon='🔓'; }
    div.className = cls;
    div.innerHTML = `<span class="icon">${icon}</span><span class="name">${s.name}</span>`;
    if(state.unlocked[i]){
      div.addEventListener('click', ()=>{ 
        if(state.currentIndex !== i){
          animateStageSwitch = true;
          state.currentIndex = i; 
          renderAll();
        }
      });
    }
    nav.appendChild(div);
  });
}

/* ============================================================
   RENDER: STAGE CONTENT
   ============================================================ */
function renderStage(){
  const container = document.getElementById('stageContainer');
  if(state.finished){
    renderFinalResult(container);
    return;
  }
  const idx = state.currentIndex;
  const stage = stages[idx];
  if(!state.unlocked[idx]){
    container.innerHTML = `<div class="case-page"><div class="locked-note">🔒 This stage is still sealed. Complete the previous stage to unlock it.</div></div>`;
    return;
  }

  const pageAnimClass = animateStageSwitch ? 'animate-in' : '';
  animateStageSwitch = false; // Reset after rendering once

  let html = `<div class="case-page ${pageAnimClass}"><div class="paperclip"></div>`;
  html += `<div class="stage-heading"><h2>${stage.title}</h2><span class="stage-points">${stage.max} pts</span></div>`;
  
  // Render Stage 1 Hero Illustration if available
  if(stage.heroImage){
    html += `
      <div class="stage-hero-container">
        <img src="${stage.heroImage}" alt="${stage.heroTitle}" class="stage-hero-img">
        <div class="stage-hero-text">
          <h3>${stage.heroTitle}</h3>
          <p>${stage.heroDesc}</p>
        </div>
      </div>
    `;
  }

  html += `<div class="explain">${stage.explain}</div>`;

  stage.questions.forEach((q,qi)=>{
    const isCorrect = state.correctSet[idx].has(qi);
    const userAnswer = state.answers[idx][qi];

    html += `<div class="question" id="q-${idx}-${qi}"><span class="q-num">Question ${qi+1} of ${stage.questions.length} — ${stage.perQ} pts</span>`;
    html += `<div class="q-prompt">${q.prompt}</div>`;

    if(q.type === 'mc'){
      html += `<div class="options">`;
      q.options.forEach((opt,oi)=>{
        const picked = userAnswer === oi ? 'picked' : '';
        html += `<label class="option ${picked}"><input type="radio" name="opt-${idx}-${qi}" value="${oi}" ${userAnswer===oi?'checked':''} onchange="selectOption(${idx},${qi},${oi})"> ${opt}</label>`;
      });
      html += `</div>`;
    } else if(q.type === 'classify'){
      const ans = Array.isArray(userAnswer) ? userAnswer : new Array(q.items.length).fill(null);
      const isCompleted = state.completed[idx] && state.correctSet[idx].size === stage.questions.length;
      
      const poolItems = [];
      const zone0Items = [];
      const zone1Items = [];

      q.items.forEach((item, ii) => {
        const zone = ans[ii];
        const itemObj = { text: item.text, index: ii, correct: item.correct, picked: zone };
        if (zone === 0) zone0Items.push(itemObj);
        else if (zone === 1) zone1Items.push(itemObj);
        else poolItems.push(itemObj);
      });

      const buildChip = (itemObj) => {
        const ii = itemObj.index;
        let itemClass = 'dnd-chip';
        if (state.selectedChip && state.selectedChip.si === idx && state.selectedChip.qi === qi && state.selectedChip.ii === ii) {
          itemClass += ' selected-chip';
        }
        if (isCompleted && itemObj.picked !== null && itemObj.picked !== undefined) {
          itemClass += itemObj.picked === itemObj.correct ? ' item-correct' : ' item-incorrect';
        }
        
        const dragAttr = !isCompleted ? `draggable="true" ondragstart="handleDragStart(event, ${idx}, ${qi}, ${ii})" ondragend="handleDragEnd(event)"` : '';
        const clickAttr = !isCompleted ? `onclick="handleChipClick(event, ${idx}, ${qi}, ${ii})"` : '';

        return `<div class="${itemClass}" ${dragAttr} ${clickAttr} id="chip-${idx}-${qi}-${ii}">
          <span>✋</span> <span>${escapeHtml(itemObj.text)}</span>
        </div>`;
      };

      html += `<div class="dnd-wrapper">`;
      
      // Unsorted Card Pool
      html += `<div class="dnd-pool-box" ondragover="handleDragOver(event)" ondragenter="handleDragEnter(event)" ondragleave="handleDragLeave(event)" ondrop="handleDrop(event, ${idx}, ${qi}, null)" onclick="handleZoneClick(event, ${idx}, ${qi}, null)">
        <div class="dnd-pool-label">
          <span>📦 Card Pool (Drag or Tap from here)</span>
          <span>${poolItems.length} remaining</span>
        </div>
        <div class="dnd-pool-items">
          ${poolItems.length === 0 ? '<span style="font-size:12px; color:var(--muted); font-style:italic;">All items sorted!</span>' : poolItems.map(buildChip).join('')}
        </div>
      </div>`;

      // Target Zones
      html += `<div class="dnd-zones">`;
      
      // Zone 0: Present Simple
      html += `<div class="dnd-zone" ondragover="handleDragOver(event)" ondragenter="handleDragEnter(event)" ondragleave="handleDragLeave(event)" ondrop="handleDrop(event, ${idx}, ${qi}, 0)" onclick="handleZoneClick(event, ${idx}, ${qi}, 0)">
        <div class="dnd-zone-title simple">📘 Present Simple Zone</div>
        <div class="dnd-zone-items">
          ${zone0Items.map(buildChip).join('')}
        </div>
      </div>`;

      // Zone 1: Present Continuous
      html += `<div class="dnd-zone" ondragover="handleDragOver(event)" ondragenter="handleDragEnter(event)" ondragleave="handleDragLeave(event)" ondrop="handleDrop(event, ${idx}, ${qi}, 1)" onclick="handleZoneClick(event, ${idx}, ${qi}, 1)">
        <div class="dnd-zone-title continuous">📗 Present Continuous Zone</div>
        <div class="dnd-zone-items">
          ${zone1Items.map(buildChip).join('')}
        </div>
      </div>`;

      html += `</div>`; // end dnd-zones
      html += `</div>`; // end dnd-wrapper

    } else {
      html += `<input type="text" class="text-input" id="input-${idx}-${qi}" placeholder="Type your answer here..." value="${userAnswer ? userAnswer.replace(/"/g,'&quot;') : ''}" oninput="typeAnswer(${idx},${qi},this.value)">`;
    }

    html += `<div class="feedback ${isCorrect?'ok show':''}" id="fb-${idx}-${qi}">`;
    if(isCorrect){
      html += `✅ Correct! ${q.explain}`;
    }
    html += `</div>`;
    html += `</div>`;
  });

  html += `<div class="btn-row">`;
  const allCorrectNow = state.correctSet[idx].size === stage.questions.length;
  if(state.completed[idx] && allCorrectNow){
    if(idx === stages.length-1){
      html += `<button class="btn btn-gold" onclick="showFinal()">🏁 View Final Results</button>`;
    } else {
      html += `<button class="btn btn-gold" onclick="goNextStage()">Proceed to Next Stage →</button>`;
    }
  } else if(state.completed[idx] && !allCorrectNow){
    const label = idx === stages.length-1 ? 'RE-CHECK & SUBMIT' : 'Re-check My Answers';
    html += `<button class="btn ${idx===stages.length-1?'btn-red':'btn-primary'}" onclick="checkStage()">${label}</button>`;
    if(idx === stages.length-1){
      html += `<button class="btn btn-gold" onclick="showFinal()">🏁 View Final Results</button>`;
    } else {
      html += `<button class="btn btn-gold" onclick="goNextStage()">Proceed to Next Stage →</button>`;
    }
  } else {
    const label = idx === stages.length-1 ? 'SUBMIT FINAL ANSWERS' : 'Check My Answer';
    html += `<button class="btn ${idx===stages.length-1?'btn-red':'btn-primary'}" onclick="checkStage()">${label}</button>`;
  }
  html += `</div>`;
  html += `</div>`;

  container.innerHTML = html;
}

function selectOption(si,qi,oi){
  state.answers[si][qi] = oi;
}
function typeAnswer(si,qi,val){
  state.answers[si][qi] = val;
}

/* ============================================================
   DRAG AND DROP HANDLERS
   ============================================================ */
let draggedData = null;

function handleDragStart(e, si, qi, ii) {
  draggedData = { si, qi, ii };
  e.dataTransfer.setData('text/plain', JSON.stringify({ si, qi, ii }));
  e.dataTransfer.effectAllowed = 'move';
  const chip = e.target.closest('.dnd-chip');
  if (chip) chip.classList.add('dragging');
}

function handleDragEnd(e) {
  const chip = e.target.closest('.dnd-chip');
  if (chip) chip.classList.remove('dragging');
  document.querySelectorAll('.drag-over').forEach(el => el.classList.remove('drag-over'));
  draggedData = null;
}

function handleDragOver(e) {
  e.preventDefault();
  e.dataTransfer.dropEffect = 'move';
}

function handleDragEnter(e) {
  e.preventDefault();
  const zone = e.currentTarget;
  if (zone.classList.contains('dnd-zone') || zone.classList.contains('dnd-pool-box')) {
    zone.classList.add('drag-over');
  }
}

function handleDragLeave(e) {
  const zone = e.currentTarget;
  if (!zone.contains(e.relatedTarget)) {
    zone.classList.remove('drag-over');
  }
}

function handleDrop(e, si, qi, targetZone) {
  e.preventDefault();
  e.stopPropagation();
  const zoneEl = e.currentTarget;
  zoneEl.classList.remove('drag-over');

  let data = draggedData;
  if (!data) {
    try {
      data = JSON.parse(e.dataTransfer.getData('text/plain'));
    } catch(err) {}
  }

  if (data && data.si === si && data.qi === qi) {
    moveChipToZone(si, qi, data.ii, targetZone);
  }
  draggedData = null;
}

// Tap-to-Move support for mobile and convenience
function handleChipClick(e, si, qi, ii) {
  e.stopPropagation();
  if (state.completed[si] && state.correctSet[si].size === stages[si].questions.length) return;

  if (state.selectedChip && state.selectedChip.si === si && state.selectedChip.qi === qi && state.selectedChip.ii === ii) {
    state.selectedChip = null;
  } else {
    state.selectedChip = { si, qi, ii };
  }
  renderStage();
}

function handleZoneClick(e, si, qi, targetZone) {
  if (state.completed[si] && state.correctSet[si].size === stages[si].questions.length) return;
  if (state.selectedChip && state.selectedChip.si === si && state.selectedChip.qi === qi) {
    moveChipToZone(si, qi, state.selectedChip.ii, targetZone);
    state.selectedChip = null;
  }
}

function moveChipToZone(si, qi, ii, targetZone) {
  const len = stages[si].questions[qi].items.length;
  if (!Array.isArray(state.answers[si][qi])) {
    state.answers[si][qi] = new Array(len).fill(null);
  }
  state.answers[si][qi][ii] = targetZone;
  renderStage();
}

/* ============================================================
   CHECK ANSWERS
   ============================================================ */
function checkStage(){
  const idx = state.currentIndex;
  const stage = stages[idx];
  let allAnswered = true;

  stage.questions.forEach((q,qi)=>{
    const a = state.answers[idx][qi];
    if(q.type === 'classify'){
      if(!Array.isArray(a) || a.some(v => v === null || v === undefined)){
        allAnswered = false;
      }
    } else if(a === null || a === undefined || a === ''){
      allAnswered = false;
    }
  });

  if(!allAnswered){
    flashStamp('⚠️','Hold on, Detective.','Please answer all questions before checking.', 'var(--red)');
    return;
  }

  let correctCount = 0;
  stage.questions.forEach((q,qi)=>{
    const a = state.answers[idx][qi];
    let isCorrect = false;
    if(q.type === 'mc'){
      isCorrect = a === q.correct;
    } else if(q.type === 'classify'){
      isCorrect = Array.isArray(a) && q.items.every((item,ii) => a[ii] === item.correct);
    } else {
      isCorrect = q.accept.some(acc => norm(acc) === norm(a));
    }
    const qDiv = document.getElementById(`q-${idx}-${qi}`);
    const fbDiv = document.getElementById(`fb-${idx}-${qi}`);
    qDiv.classList.remove('correct','incorrect');
    if(isCorrect){
      state.correctSet[idx].add(qi);
      qDiv.classList.add('correct');
      fbDiv.className = 'feedback ok show';
      fbDiv.innerHTML = `✅ Correct! ${q.explain}`;
      correctCount++;
    } else {
      state.correctSet[idx].delete(qi);
      qDiv.classList.add('incorrect');
      fbDiv.className = 'feedback bad show';
      fbDiv.innerHTML = `❌ Incorrect. ${q.explain}`;
    }
  });

  state.stageScores[idx] = state.correctSet[idx].size * stage.perQ;
  renderHeader();

  const allCorrect = state.correctSet[idx].size === stage.questions.length;

  state.completed[idx] = true;
  if(idx+1 < stages.length){ state.unlocked[idx+1] = true; }
  renderNav();

  setTimeout(()=>{
    if(idx === stages.length-1){
      flashStamp('🏁','Case Closed!', `Stage Score: ${state.stageScores[idx]} / ${stage.max}`, 'var(--green)', ()=>{ showFinal(); });
    } else if(allCorrect){
      flashStamp('🎉','Stage Cleared!', `Stage Score: ${state.stageScores[idx]} / ${stage.max}`, 'var(--green)');
    } else {
      flashStamp('📋','Stage Completed', `Stage Score: ${state.stageScores[idx]} / ${stage.max} — Fix the ❌ answers and tap "Re-check My Answers" to raise your score, or proceed to the next stage.`, 'var(--brass)');
    }
  }, 350);
  renderStageButtonsOnly();
}

function renderStageButtonsOnly(){
  renderStage();
}

function goNextStage(){
  if(state.currentIndex+1 < stages.length){
    animateStageSwitch = true;
    state.currentIndex++;
    renderAll();
  }
}

/* ============================================================
   STAMP OVERLAY
   ============================================================ */
function flashStamp(icon,title,line,color,onClose){
  const overlay = document.getElementById('stampOverlay');
  const card = document.getElementById('stampCard');
  card.style.borderColor = color;
  card.innerHTML = `
    <div class="big-icon">${icon}</div>
    <h3 style="color:${color}">${title}</h3>
    <div class="score-line">${line}</div>
    <div><button class="btn btn-primary" id="stampCloseBtn">Continue</button></div>
  `;
  overlay.classList.add('show');
  document.getElementById('stampCloseBtn').onclick = () => {
    overlay.classList.remove('show');
    if(onClose) onClose();
  };
}

/* ============================================================
   FINAL RESULT
   ============================================================ */
function showFinal(){
  state.finished = true;
  renderAll();
}

function getCategory(score){
  if(score >= 105) return {icon:'🥇', name:'GRAMMAR CHAMPION!', text:'Outstanding! You have a rock-solid understanding of the Present Simple and Present Continuous.', color:'var(--brass)'};
  if(score >= 85) return {icon:'🥈', name:'GRAMMAR EXPERT!', text:'Great job! You have a very good grasp of the differences between both tenses.', color:'#8FA6C7'};
  if(score >= 65) return {icon:'🥉', name:'GOOD PROGRESS!', text:'Good work! You know the basics, but you could use a bit more practice.', color:'#B98354'};
  if(score >= 45) return {icon:'📚', name:'KEEP LEARNING!', text:'You are making progress. Review the rules and try practicing again.', color:'var(--navy)'};
  return {icon:'🔄', name:'TRY AGAIN!', text:"Don't be discouraged! Review the material and try working through the case file once more.", color:'var(--red)'};
}

function renderFinalResult(container){
  const score = totalScore();
  const cat = getCategory(score);
  let html = `<div class="case-page animate-in"><div class="paperclip"></div>`;
  const nameLine = (state.studentName || state.studentClass)
    ? `<p style="font-family:'JetBrains Mono',monospace; font-size:13px; color:var(--muted); margin:4px 0 0;">
         ${state.studentName ? 'Detective: <b>'+escapeHtml(state.studentName)+'</b>' : ''}
         ${state.studentName && state.studentClass ? ' &nbsp;|&nbsp; ' : ''}
         ${state.studentClass ? 'Class: <b>'+escapeHtml(state.studentClass)+'</b>' : ''}
       </p>`
    : '';

  html += `<div style="text-align:center;">
      <div style="font-size:40px;">🎉</div>
      <h2 style="font-family:'Special Elite',monospace; margin:6px 0;">Congratulations, Detective!</h2>
      <p style="color:var(--muted); margin-top:0;">You have successfully closed this Tense Case File.</p>
      ${nameLine}
      <div class="final-score">${score}<span> / ${TOTAL_MAX}</span></div>
    </div>`;

  html += `<div class="category-banner" style="background:${cat.color}22; border:2px solid ${cat.color};">
      <div style="font-size:34px;">${cat.icon}</div>
      <h3 style="margin:6px 0; color:${cat.color};">${cat.name}</h3>
      <p style="margin:0; color:var(--text);">${cat.text}</p>
    </div>`;

  html += `<h3 style="font-family:'Special Elite',monospace;">Results Per Stage</h3>`;
  html += `<div class="stage-results">`;
  stages.forEach((s,i)=>{
    html += `<div class="stage-result-item">Stage ${i+1}: ${s.name}<b>${state.stageScores[i]} / ${s.max}</b></div>`;
  });
  html += `</div>`;

  html += `<div class="btn-row"><button class="btn btn-gold" onclick="restartAll()">🔄 Start Again</button></div>`;
  html += `</div>`;
  container.innerHTML = html;
}

function restartAll(){
  animateStageSwitch = true;
  state.currentIndex = 0;
  state.unlocked = stages.map((s,i) => i===0);
  state.completed = stages.map(() => false);
  state.stageScores = stages.map(() => 0);
  state.answers = stages.map(s => new Array(s.questions.length).fill(null));
  state.correctSet = stages.map(() => new Set());
  state.finished = false;
  state.selectedChip = null;
  renderAll();
}

/* ============================================================
   MASTER RENDER
   ============================================================ */
function renderAll(){
  renderHeader();
  renderNav();
  renderStage();
}

renderAll();
</script>
</body>
</html>
