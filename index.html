<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Truppführer QS3 – Prüfungstraining</title>
<style>
  :root{
    --bg:#15171c; --panel:#1d2027; --panel-2:#23272f; --line:#33373f;
    --ink:#eef0f3; --ink-soft:#aab0bb; --ink-dim:#787f8c;
    --red:#e2231a; --red-deep:#a8160f; --warn:#f4d000;
    --ok:#3ec98a; --teil:#f4c000; --no:#ff6b5e;
    --radius:14px; --shadow:0 18px 40px -18px rgba(0,0,0,.7);
    --mono:ui-monospace,"SFMono-Regular",Menlo,Consolas,monospace;
    --sans:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  }
  *{box-sizing:border-box}
  html,body{margin:0}
  body{font-family:var(--sans);
    background:radial-gradient(1100px 500px at 80% -10%, rgba(226,35,26,.10), transparent 60%),var(--bg);
    color:var(--ink);min-height:100vh;line-height:1.55;-webkit-font-smoothing:antialiased;}
  .wrap{max-width:860px;margin:0 auto;padding:22px 18px 80px}
  a{color:var(--warn)}

  header{margin-bottom:18px}
  .stripe{height:8px;border-radius:4px;
    background:repeating-linear-gradient(135deg,var(--warn) 0 16px,#1a1c22 16px 32px);margin-bottom:16px;}
  .eyebrow{font-family:var(--mono);font-size:.72rem;letter-spacing:.22em;text-transform:uppercase;color:var(--red);font-weight:700;}
  h1{font-size:1.7rem;margin:.18em 0 .1em;letter-spacing:-.01em}
  .sub{color:var(--ink-soft);font-size:.92rem;margin:0}

  .tabs{display:flex;gap:8px;margin:18px 0 16px}
  .tab{flex:1;appearance:none;border:1px solid var(--line);background:var(--panel);color:var(--ink-soft);
    font-family:var(--mono);font-size:.74rem;letter-spacing:.1em;text-transform:uppercase;font-weight:700;
    padding:12px 8px;border-radius:11px;cursor:pointer;transition:.15s;}
  .tab:hover{color:var(--ink)}
  .tab[aria-selected="true"]{background:linear-gradient(180deg,var(--red),var(--red-deep));border-color:var(--red-deep);color:#fff;box-shadow:var(--shadow);}
  .tab:focus-visible{outline:3px solid var(--warn);outline-offset:2px}

  .view{display:none}
  .view.active{display:block;animation:fade .25s ease}
  @keyframes fade{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}

  .chips{display:flex;flex-wrap:wrap;gap:7px;margin-bottom:8px;align-items:center}
  .chips .div{flex-basis:100%;height:0;margin:2px 0}
  .chips .mini{font-family:var(--mono);font-size:.66rem;letter-spacing:.12em;text-transform:uppercase;color:var(--ink-dim);margin-right:2px}
  .chip{border:1px solid var(--line);background:var(--panel);color:var(--ink-soft);font-size:.8rem;
    padding:6px 11px;border-radius:999px;cursor:pointer;transition:.15s;}
  .chip:hover{color:var(--ink)}
  .chip[aria-pressed="true"]{background:var(--ink);color:#15171c;border-color:var(--ink);font-weight:600}
  .chip.sp[aria-pressed="true"]{background:var(--warn);border-color:var(--warn);color:#15171c}
  .chip:focus-visible{outline:3px solid var(--warn);outline-offset:2px}

  .meta{display:flex;justify-content:space-between;align-items:center;gap:10px;margin:14px 0 10px}
  .badge{font-family:var(--mono);font-size:.7rem;letter-spacing:.1em;text-transform:uppercase;color:var(--warn);
    border:1px solid var(--line);padding:4px 9px;border-radius:7px;background:var(--panel);}
  .count{font-family:var(--mono);font-size:.78rem;color:var(--ink-dim);display:flex;align-items:center;gap:8px}
  .flag{font-size:.95rem}
  .dot{width:9px;height:9px;border-radius:50%;display:inline-block}
  .dot.richtig{background:var(--ok)} .dot.teils{background:var(--teil)} .dot.falsch{background:var(--no)}

  .card{perspective:1600px;cursor:pointer;user-select:none;height:clamp(280px,42vh,400px);}
  .card-inner{position:relative;width:100%;height:100%;transition:transform .55s cubic-bezier(.2,.7,.2,1);transform-style:preserve-3d;}
  .card.flipped .card-inner{transform:rotateY(180deg)}
  .face{position:absolute;inset:0;backface-visibility:hidden;-webkit-backface-visibility:hidden;border-radius:var(--radius);
    border:1px solid var(--line);padding:24px;display:flex;flex-direction:column;box-shadow:var(--shadow);overflow:auto;}
  .face-q{background:linear-gradient(180deg,var(--panel),var(--panel-2))}
  .face-a{background:linear-gradient(180deg,#20232b,#191c22);transform:rotateY(180deg);border-color:#3a2422}
  .face .tag{font-family:var(--mono);font-size:.7rem;letter-spacing:.16em;text-transform:uppercase;font-weight:700;margin-bottom:14px;}
  .face-q .tag{color:var(--red)} .face-a .tag{color:var(--ok)}
  .face .body{font-size:1.16rem;font-weight:500;margin:auto 0}
  .face-a .body{font-size:1.02rem;font-weight:400;color:#f0eceb;line-height:1.6}
  .readmore{margin-top:14px}
  .readmore a{font-family:var(--mono);font-size:.78rem;text-decoration:none;border-bottom:1px dotted var(--warn)}
  .hint{margin-top:12px;font-size:.74rem;color:var(--ink-dim);font-family:var(--mono);letter-spacing:.04em}
  .card:focus-visible{outline:3px solid var(--warn);outline-offset:4px;border-radius:18px}

  /* tracker */
  .tracker{margin-top:14px;border:1px solid var(--line);background:var(--panel);border-radius:12px;padding:12px 14px}
  .trow{display:flex;flex-wrap:wrap;gap:8px;align-items:center}
  .tlbl{font-family:var(--mono);font-size:.68rem;letter-spacing:.1em;text-transform:uppercase;color:var(--ink-dim);margin-right:2px}
  .sbtn{appearance:none;border:1px solid var(--line);background:var(--panel-2);color:var(--ink-soft);
    font-size:.82rem;font-weight:600;padding:7px 12px;border-radius:9px;cursor:pointer;transition:.13s;}
  .sbtn:hover{color:var(--ink)}
  .sbtn:focus-visible{outline:3px solid var(--warn);outline-offset:2px}
  .sbtn.star.on{background:#2b2718;border-color:#6b5d20;color:var(--warn)}
  .sbtn.richtig.on{background:#1c2a24;border-color:#2f6e51;color:var(--ok)}
  .sbtn.teils.on{background:#2a2614;border-color:#6e5e2f;color:var(--teil)}
  .sbtn.falsch.on{background:#2a1d1c;border-color:#7a3a36;color:var(--no)}
  .note-area{width:100%;margin-top:10px;background:var(--panel-2);border:1px solid var(--line);color:var(--ink);
    border-radius:9px;padding:10px 12px;font-family:var(--sans);font-size:.92rem;resize:vertical;min-height:46px;}
  .note-area:focus-visible{outline:2px solid var(--warn);outline-offset:0}

  .nav{display:flex;gap:8px;margin-top:14px}
  .btn{appearance:none;border:1px solid var(--line);background:var(--panel);color:var(--ink);
    font-family:var(--mono);font-size:.8rem;letter-spacing:.08em;text-transform:uppercase;font-weight:700;
    padding:12px 16px;border-radius:11px;cursor:pointer;transition:.12s;}
  .btn:hover{background:var(--panel-2)} .btn:active{transform:translateY(1px)}
  .btn:focus-visible{outline:3px solid var(--warn);outline-offset:2px}
  .btn.grow{flex:1}
  .btn.red{background:linear-gradient(180deg,var(--red),var(--red-deep));border-color:var(--red-deep);color:#fff}
  .btn.ok{border-color:#2f6e51;color:var(--ok)} .btn.ok:hover{background:#1c2a24}
  .btn.teil{border-color:#6e5e2f;color:var(--teil)} .btn.teil:hover{background:#2a2614}
  .btn.no{border-color:#7a3a36;color:var(--no)} .btn.no:hover{background:#2a1d1c}

  .placeholder{border:1px dashed var(--line);border-radius:var(--radius);padding:40px 20px;text-align:center;color:var(--ink-dim);
    background:var(--panel);min-height:200px;display:flex;flex-direction:column;justify-content:center;gap:6px}

  /* exam */
  .exam-intro{border:1px solid var(--line);background:var(--panel);border-radius:var(--radius);padding:26px;text-align:center;box-shadow:var(--shadow);}
  .exam-intro h2{margin:0 0 6px;font-size:1.3rem}
  .exam-intro p{color:var(--ink-soft);margin:0 auto 20px;max-width:48ch;font-size:.95rem}
  .progress{display:flex;gap:6px;margin-bottom:14px}
  .pip{flex:1;height:6px;border-radius:3px;background:var(--line)}
  .pip.done{background:var(--ok)} .pip.half{background:var(--teil)} .pip.fail{background:var(--no)} .pip.curr{background:var(--warn)}
  .qbox{border:1px solid var(--line);background:linear-gradient(180deg,var(--panel),var(--panel-2));border-radius:var(--radius);
    padding:22px;box-shadow:var(--shadow);min-height:230px;display:flex;flex-direction:column;}
  .qhead{display:flex;justify-content:space-between;align-items:center;gap:10px}
  .qbox .q{font-size:1.18rem;font-weight:500;margin:12px 0}
  .answer{margin-top:14px;padding-top:14px;border-top:1px dashed var(--line);color:#f0eceb;font-size:1rem;line-height:1.6;}
  .answer .tag{font-family:var(--mono);font-size:.7rem;letter-spacing:.16em;text-transform:uppercase;color:var(--ok);font-weight:700;display:block;margin-bottom:8px}

  .result{border:1px solid var(--line);background:var(--panel);border-radius:var(--radius);padding:26px;box-shadow:var(--shadow)}
  .scoreline{display:flex;gap:18px;flex-wrap:wrap;margin-bottom:6px}
  .sc{display:flex;flex-direction:column}
  .sc b{font-size:2rem;font-weight:800;line-height:1}
  .sc.ok b{color:var(--ok)} .sc.teil b{color:var(--teil)} .sc.no b{color:var(--no)}
  .sc span{font-family:var(--mono);font-size:.68rem;letter-spacing:.1em;text-transform:uppercase;color:var(--ink-dim)}
  .verdict{font-family:var(--mono);text-transform:uppercase;letter-spacing:.1em;font-weight:700;margin:14px 0 16px}

  /* overview list */
  .ovlist{list-style:none;padding:0;margin:14px 0 0;display:flex;flex-direction:column;gap:12px}
  .ovcard{border:1px solid var(--line);background:var(--panel);border-radius:12px;padding:16px}
  .ovcard .top{display:flex;justify-content:space-between;gap:10px;align-items:flex-start}
  .ovcard .qt{font-weight:600;margin:0 0 4px}
  .ovcard .tp{font-family:var(--mono);font-size:.66rem;letter-spacing:.1em;text-transform:uppercase;color:var(--ink-dim)}
  .ovcard details{margin-top:10px}
  .ovcard summary{cursor:pointer;font-family:var(--mono);font-size:.74rem;color:var(--warn);letter-spacing:.05em}
  .ovcard .ans{margin-top:8px;color:#e8e6e5;font-size:.95rem;line-height:1.55}
  .ovcard .ans a{font-family:var(--mono);font-size:.78rem;text-decoration:none;border-bottom:1px dotted var(--warn)}
  .ovcard .ctrls{display:flex;flex-wrap:wrap;gap:7px;margin-top:12px;align-items:center}
  .ovnote{font-family:var(--mono);font-size:.66rem;letter-spacing:.1em;text-transform:uppercase;color:var(--ink-dim);margin:12px 0 4px}

  footer{margin-top:34px;text-align:center;color:var(--ink-dim);font-size:.76rem;font-family:var(--mono);line-height:1.7}

  @media (max-width:520px){h1{font-size:1.4rem}.face .body{font-size:1.04rem}.tab{font-size:.62rem;padding:11px 4px}}
  @media (prefers-reduced-motion:reduce){.card-inner{transition:none}.view.active{animation:none}}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <div class="stripe"></div>
    <div class="eyebrow">Feuerwehr · QS3 · Theorie</div>
    <h1>Truppführer – Prüfungstraining</h1>
    <p class="sub">Karteikarten zum Lernen, eine Prüfungssimulation und eine Übersicht für markierte Fragen, Bewertungen und Notizen.</p>
  </header>

  <div class="tabs" role="tablist">
    <button class="tab" id="tab-cards" role="tab" aria-selected="true" aria-controls="view-cards">Karteikarten</button>
    <button class="tab" id="tab-exam" role="tab" aria-selected="false" aria-controls="view-exam">Prüfung</button>
    <button class="tab" id="tab-over" role="tab" aria-selected="false" aria-controls="view-over">Übersicht</button>
  </div>

  <!-- KARTEIKARTEN -->
  <section class="view active" id="view-cards" role="tabpanel" aria-labelledby="tab-cards">
    <div class="chips" id="chips"></div>
    <div id="card-stage"></div>
  </section>

  <!-- PRÜFUNG -->
  <section class="view" id="view-exam" role="tabpanel" aria-labelledby="tab-exam">
    <div id="exam-stage"></div>
  </section>

  <!-- ÜBERSICHT -->
  <section class="view" id="view-over" role="tabpanel" aria-labelledby="tab-over">
    <div class="chips" id="ov-chips"></div>
    <div id="ov-stage"></div>
  </section>

  <footer>
    Markierungen, Bewertungen &amp; Notizen werden lokal im Browser gespeichert (am besten die Datei herunterladen &amp; öffnen).<br>
    Lernhilfe ohne Gewähr · maßgeblich sind FwDV, Landesrecht &amp; die Vorgaben deiner Feuerwehr.
  </footer>
</div>

<script>
/* =================== DATEN (q=Frage, a=Antwort, t=Thema, l=Nachlese-Suchbegriff) =================== */
let CARDS = [];   // wird aus dem Ordner /questions geladen

/* =================== HELFER =================== */
const $ = s => document.querySelector(s);
let TOPICS = [];
function shuffle(a){const r=a.slice();for(let i=r.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[r[i],r[j]]=[r[j],r[i]];}return r;}
function cid(c){const s=c.t+"|"+c.q;let h=0;for(let i=0;i<s.length;i++){h=(h*31+s.charCodeAt(i))|0;}return "c"+(h>>>0).toString(36);}
let byId = {};
function wiki(term){return "https://de.wikipedia.org/wiki/"+encodeURIComponent(term.replace(/ /g,"_"));}
function esc(s){return s.replace(/[&<>"]/g,m=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[m]));}

/* =================== SPEICHER =================== */
const SKEY="tf_qs3_v2";
const store={data:{mark:{},status:{},note:{}}};
store.load=function(){try{const r=localStorage.getItem(SKEY);if(r){const d=JSON.parse(r);this.data.mark=d.mark||{};this.data.status=d.status||{};this.data.note=d.note||{};}}catch(e){}};
store.save=function(){try{localStorage.setItem(SKEY,JSON.stringify(this.data));}catch(e){}};
store.load();
const isMarked=id=>!!store.data.mark[id];
const getStatus=id=>store.data.status[id]||"";
const getNote=id=>store.data.note[id]||"";
function setMark(id,v){if(v)store.data.mark[id]=1;else delete store.data.mark[id];store.save();afterChange(id);}
function setStatus(id,v){if(getStatus(id)===v){delete store.data.status[id];}else{store.data.status[id]=v;}store.save();afterChange(id);}
function setNote(id,v){if(v.trim())store.data.note[id]=v;else delete store.data.note[id];store.save();afterChange(id,true);}
function afterChange(id,fromNote){
  if($("#view-cards").classList.contains("active")) updateTracker();
  if($("#view-over").classList.contains("active")){ buildOvChips(); if(!fromNote) renderOverview(); }
}

/* =================== TABS =================== */
const tabCards=$("#tab-cards"), tabExam=$("#tab-exam"), tabOver=$("#tab-over");
function selectTab(which){
  [["cards",tabCards,"view-cards"],["exam",tabExam,"view-exam"],["over",tabOver,"view-over"]].forEach(([k,btn,id])=>{
    const on=k===which; btn.setAttribute("aria-selected",on); $("#"+id).classList.toggle("active",on);
  });
}
tabCards.onclick=()=>selectTab("cards");
tabExam.onclick=()=>{selectTab("exam"); if(!examState.started) renderExamIntro();};
tabOver.onclick=()=>{selectTab("over"); buildOvChips(); renderOverview();};

/* =================== KARTEIKARTEN =================== */
let filter="ALLE", deck=[], idx=0;
const SPECIALS=[["MARK","★ Markiert"],["ST_richtig","✓ Richtig"],["ST_teils","~ Teils"],["ST_falsch","✗ Falsch"]];

function buildChips(){
  const box=$("#chips"); box.innerHTML="";
  const mk=(val,label,sp)=>{const b=document.createElement("button");b.className="chip"+(sp?" sp":"");
    b.textContent=label;b.setAttribute("aria-pressed",val===filter);
    b.onclick=()=>{filter=val;buildDeck();buildChips();};return b;};
  box.appendChild(mk("ALLE","Alle Themen"));
  TOPICS.forEach(t=>box.appendChild(mk(t,t)));
  const d=document.createElement("span");d.className="div";box.appendChild(d);
  const lab=document.createElement("span");lab.className="mini";lab.textContent="Eigene Auswahl:";box.appendChild(lab);
  SPECIALS.forEach(([v,l])=>box.appendChild(mk(v,l,true)));
}
function deckFor(f){
  if(f==="ALLE")return CARDS.slice();
  if(f==="MARK")return CARDS.filter(c=>isMarked(c.id));
  if(f==="ST_richtig")return CARDS.filter(c=>getStatus(c.id)==="richtig");
  if(f==="ST_teils")return CARDS.filter(c=>getStatus(c.id)==="teils");
  if(f==="ST_falsch")return CARDS.filter(c=>getStatus(c.id)==="falsch");
  return CARDS.filter(c=>c.t===f);
}
function buildDeck(){deck=shuffle(deckFor(filter));idx=0;renderCardStage();}

function renderCardStage(){
  const stage=$("#card-stage");
  if(deck.length===0){
    stage.innerHTML=`<div class="placeholder"><div style="font-size:1.4rem">∅</div>
      <div>Keine Karten in dieser Auswahl.</div>
      <div style="font-size:.85rem">Markiere Fragen mit ★ oder bewerte sie, dann erscheinen sie hier.</div></div>`;
    return;
  }
  stage.innerHTML=`
    <div class="meta">
      <span class="badge" id="card-topic">–</span>
      <span class="count"><span id="card-flags"></span><span id="card-count">0 / 0</span></span>
    </div>
    <div class="card" id="card" tabindex="0" role="button" aria-label="Karte umdrehen">
      <div class="card-inner">
        <div class="face face-q"><span class="tag">Frage</span><div class="body" id="q-text"></div>
          <div class="hint">Klick / Leertaste = Antwort · ← → = blättern</div></div>
        <div class="face face-a"><span class="tag">Antwort</span><div class="body" id="a-text"></div>
          <div class="readmore" id="a-link"></div><div class="hint">Klick = zurück zur Frage</div></div>
      </div>
    </div>
    <div class="tracker">
      <div class="trow">
        <span class="tlbl">Status</span>
        <button class="sbtn star" id="t-star">★ Merken</button>
        <button class="sbtn richtig" data-s="richtig">Richtig</button>
        <button class="sbtn teils" data-s="teils">Teils richtig</button>
        <button class="sbtn falsch" data-s="falsch">Falsch</button>
      </div>
      <textarea class="note-area" id="t-note" placeholder="Notiz zu dieser Frage …"></textarea>
    </div>
    <div class="nav">
      <button class="btn grow" id="prev">‹ Zurück</button>
      <button class="btn" id="shuffle">Mischen</button>
      <button class="btn grow red" id="next">Weiter ›</button>
    </div>`;
  const cardEl=$("#card");
  cardEl.onclick=()=>cardEl.classList.toggle("flipped");
  cardEl.onkeydown=e=>{
    if(e.key===" "||e.key==="Enter"){e.preventDefault();cardEl.classList.toggle("flipped");}
    else if(e.key==="ArrowRight"){e.preventDefault();nextCard();}
    else if(e.key==="ArrowLeft"){e.preventDefault();prevCard();}};
  $("#next").onclick=nextCard; $("#prev").onclick=prevCard;
  $("#shuffle").onclick=()=>{deck=shuffle(deck);idx=0;renderCard();};
  $("#t-star").onclick=()=>{const id=deck[idx].id;setMark(id,!isMarked(id));};
  document.querySelectorAll(".tracker .sbtn[data-s]").forEach(b=>b.onclick=()=>setStatus(deck[idx].id,b.dataset.s));
  $("#t-note").addEventListener("input",e=>setNote(deck[idx].id,e.target.value));
  renderCard();
}
function renderCard(){
  if(deck.length===0)return;
  const c=deck[idx];
  $("#card").classList.remove("flipped");
  setTimeout(()=>{
    $("#q-text").textContent=c.q;
    $("#a-text").textContent=c.a;
    $("#a-link").innerHTML=`<a href="${wiki(c.l)}" target="_blank" rel="noopener">↗ Bei Wikipedia nachlesen</a>`;
    $("#card-topic").textContent=c.t;
    $("#card-count").textContent=`${idx+1} / ${deck.length}`;
    $("#t-note").value=getNote(c.id);
    updateTracker();
  },70);
}
function updateTracker(){
  if(deck.length===0)return;
  const c=deck[idx], st=getStatus(c.id), mk=isMarked(c.id);
  const star=$("#t-star"); if(star){star.classList.toggle("on",mk); star.textContent=mk?"★ Gemerkt":"★ Merken";}
  document.querySelectorAll(".tracker .sbtn[data-s]").forEach(b=>b.classList.toggle("on",b.dataset.s===st));
  const flags=$("#card-flags");
  if(flags){let h=""; if(mk)h+='<span class="flag" title="markiert">★</span>'; if(st)h+=`<span class="dot ${st}" title="${st}"></span>`; flags.innerHTML=h;}
}
function nextCard(){idx=(idx+1)%deck.length;renderCard();}
function prevCard(){idx=(idx-1+deck.length)%deck.length;renderCard();}

/* Initialisierung erfolgt in loadData() nach dem Laden der Fragen */

/* =================== PRÜFUNG =================== */
const EXAM_N=5;
let examState={started:false,items:[],pos:0,results:[]};
const stage=$("#exam-stage");
function renderExamIntro(){
  examState.started=false;
  stage.innerHTML=`<div class="exam-intro"><h2>Prüfungssimulation</h2>
    <p>Du ziehst dir ${EXAM_N} zufällige Fragen aus dem Stapel – quer durch alle Themen. Antworte laut, decke die Musterantwort auf und bewerte ehrlich. Die Bewertung wird in der Übersicht gespeichert.</p>
    <button class="btn red" id="start-exam">${EXAM_N} Fragen ziehen</button></div>`;
  $("#start-exam").onclick=startExam;
}
function startExam(){examState={started:true,items:shuffle(CARDS).slice(0,EXAM_N),pos:0,results:[]};renderQuestion();}
function pips(){
  let h='<div class="progress">';
  for(let i=0;i<EXAM_N;i++){let c="pip";
    if(i<examState.results.length){const g=examState.results[i].grade;c+=g==="richtig"?" done":g==="teils"?" half":" fail";}
    else if(i===examState.pos)c+=" curr";
    h+=`<div class="${c}"></div>`;}
  return h+"</div>";
}
function renderQuestion(){
  const c=examState.items[examState.pos], mk=isMarked(c.id);
  stage.innerHTML=pips()+`
    <div class="qbox">
      <div class="qhead"><span class="badge">Frage ${examState.pos+1} / ${EXAM_N} · ${c.t}</span>
        <button class="sbtn star ${mk?'on':''}" id="ex-star">${mk?'★':'☆'} Merken</button></div>
      <div class="q">${esc(c.q)}</div>
      <div id="ans-slot"></div>
      <div class="nav" id="exam-nav"><button class="btn red grow" id="reveal">Antwort zeigen</button></div>
    </div>`;
  $("#ex-star").onclick=()=>{setMark(c.id,!isMarked(c.id));const on=isMarked(c.id);const b=$("#ex-star");b.classList.toggle("on",on);b.textContent=(on?"★":"☆")+" Merken";};
  $("#reveal").onclick=reveal;
}
function reveal(){
  const c=examState.items[examState.pos];
  $("#ans-slot").innerHTML=`<div class="answer"><span class="tag">Musterantwort</span>${esc(c.a)}
     <div class="readmore" style="margin-top:10px"><a href="${wiki(c.l)}" target="_blank" rel="noopener">↗ Bei Wikipedia nachlesen</a></div></div>`;
  $("#exam-nav").innerHTML=`
    <button class="btn ok grow" data-g="richtig">✓ Richtig</button>
    <button class="btn teil grow" data-g="teils">~ Teils</button>
    <button class="btn no grow" data-g="falsch">✗ Falsch</button>`;
  document.querySelectorAll("#exam-nav .btn").forEach(b=>b.onclick=()=>grade(b.dataset.g));
}
function grade(g){
  const c=examState.items[examState.pos];
  examState.results.push({id:c.id,q:c.q,t:c.t,grade:g});
  setStatus(c.id, getStatus(c.id)===g?g:g); // setStatus toggelt; hier hart setzen:
  store.data.status[c.id]=g; store.save();
  examState.pos++;
  examState.pos<EXAM_N?renderQuestion():renderResult();
}
function renderResult(){
  const r=examState.results;
  const nR=r.filter(x=>x.grade==="richtig").length;
  const nT=r.filter(x=>x.grade==="teils").length;
  const nF=r.filter(x=>x.grade==="falsch").length;
  const score=nR+nT*0.5, passed=score>=4;
  let list="";
  r.forEach(x=>{const g=x.grade;const sym=g==="richtig"?"✓":g==="teils"?"~":"✗";
    list+=`<li><span class="mark ${g==='richtig'?'y':g==='falsch'?'n':''}" style="${g==='teils'?'background:#2a2614;color:var(--teil);border:1px solid #6e5e2f':''}">${sym}</span>
      <div><b>${esc(x.q)}</b><span>${x.t}</span></div></li>`;});
  stage.innerHTML=`<div class="result">
    <div class="scoreline">
      <div class="sc ok"><b>${nR}</b><span>Richtig</span></div>
      <div class="sc teil"><b>${nT}</b><span>Teils</span></div>
      <div class="sc no"><b>${nF}</b><span>Falsch</span></div>
    </div>
    <div class="verdict" style="color:${passed?'var(--ok)':'var(--no)'}">${passed?'Gut vorbereitet · '+score+' / '+EXAM_N:'Noch üben · '+score+' / '+EXAM_N}</div>
    <ul class="review" style="list-style:none;padding:0;margin:0 0 20px">${list}</ul>
    <div class="nav">
      <button class="btn red grow" id="again">Neue Prüfung ziehen</button>
      <button class="btn grow" id="toover">Falsche ansehen</button>
    </div></div>
    <style>.review li{display:flex;gap:12px;align-items:flex-start;padding:12px 0;border-top:1px solid var(--line);font-size:.92rem}
    .review .mark{flex:none;width:22px;height:22px;border-radius:6px;display:grid;place-items:center;font-weight:800;font-size:.8rem;margin-top:1px}
    .review .mark.y{background:#1c2a24;color:var(--ok);border:1px solid #2f6e51}
    .review .mark.n{background:#2a1d1c;color:var(--no);border:1px solid #7a3a36}
    .review b{display:block;color:var(--ink)} .review span{color:var(--ink-dim)}</style>`;
  $("#again").onclick=startExam;
  $("#toover").onclick=()=>{ovCat="ST_falsch";selectTab("over");buildOvChips();renderOverview();};
}

/* =================== ÜBERSICHT =================== */
let ovCat="MARK";
const OV_CATS=[["MARK","★ Markiert"],["ST_richtig","✓ Richtig"],["ST_teils","~ Teils richtig"],["ST_falsch","✗ Falsch"],["NOTE","✎ Mit Notiz"]];
function ovCount(cat){
  if(cat==="MARK")return CARDS.filter(c=>isMarked(c.id)).length;
  if(cat==="NOTE")return CARDS.filter(c=>getNote(c.id)).length;
  return CARDS.filter(c=>getStatus(c.id)===cat.replace("ST_","")).length;
}
function ovList(cat){
  if(cat==="MARK")return CARDS.filter(c=>isMarked(c.id));
  if(cat==="NOTE")return CARDS.filter(c=>getNote(c.id));
  return CARDS.filter(c=>getStatus(c.id)===cat.replace("ST_",""));
}
function buildOvChips(){
  const box=$("#ov-chips");box.innerHTML="";
  OV_CATS.forEach(([v,l])=>{const b=document.createElement("button");b.className="chip sp";
    b.textContent=`${l} (${ovCount(v)})`;b.setAttribute("aria-pressed",v===ovCat);
    b.onclick=()=>{ovCat=v;buildOvChips();renderOverview();};box.appendChild(b);});
}
function renderOverview(){
  const st=$("#ov-stage"), items=ovList(ovCat);
  const catLabel=(OV_CATS.find(x=>x[0]===ovCat)||[])[1]||"";
  if(items.length===0){
    st.innerHTML=`<div class="placeholder"><div style="font-size:1.4rem">∅</div>
      <div>Noch nichts unter „${catLabel}“.</div>
      <div style="font-size:.85rem">Markiere und bewerte Karten im Reiter „Karteikarten“ oder in der Prüfung.</div></div>`;
    return;
  }
  let head=`<div class="nav" style="margin:14px 0 4px"><button class="btn red" id="ov-study">Diese ${items.length} als Karteikarten üben</button></div>`;
  let html=head+`<ul class="ovlist">`;
  items.forEach(c=>{
    const st0=getStatus(c.id), note=getNote(c.id), mk=isMarked(c.id);
    html+=`<li class="ovcard" data-id="${c.id}">
      <div class="top">
        <div><div class="qt">${esc(c.q)}</div><div class="tp">${c.t}</div></div>
        <div>${mk?'<span class="flag" title="markiert">★</span>':''}${st0?`<span class="dot ${st0}"></span>`:''}</div>
      </div>
      <details><summary>Antwort anzeigen</summary>
        <div class="ans">${esc(c.a)}<div style="margin-top:8px"><a href="${wiki(c.l)}" target="_blank" rel="noopener">↗ Bei Wikipedia nachlesen</a></div></div>
      </details>
      <div class="ctrls">
        <button class="sbtn star ${mk?'on':''}" data-act="star">★</button>
        <button class="sbtn richtig ${st0==='richtig'?'on':''}" data-act="richtig">Richtig</button>
        <button class="sbtn teils ${st0==='teils'?'on':''}" data-act="teils">Teils</button>
        <button class="sbtn falsch ${st0==='falsch'?'on':''}" data-act="falsch">Falsch</button>
      </div>
      <div class="ovnote">Notiz</div>
      <textarea class="note-area" data-act="note" placeholder="Notiz zu dieser Frage …">${esc(note)}</textarea>
    </li>`;
  });
  html+=`</ul>`;
  st.innerHTML=html;
  $("#ov-study").onclick=()=>{filter=ovCat;buildDeck();buildChips();selectTab("cards");window.scrollTo({top:0,behavior:"smooth"});};
  st.querySelectorAll(".ovcard").forEach(li=>{
    const id=li.dataset.id;
    li.querySelector('[data-act="star"]').onclick=()=>setMark(id,!isMarked(id));
    li.querySelector('[data-act="richtig"]').onclick=()=>setStatus(id,"richtig");
    li.querySelector('[data-act="teils"]').onclick=()=>setStatus(id,"teils");
    li.querySelector('[data-act="falsch"]').onclick=()=>setStatus(id,"falsch");
    li.querySelector('[data-act="note"]').addEventListener("input",e=>setNote(id,e.target.value));
  });
}

/* =================== FRAGEN AUS /questions LADEN =================== */
async function loadData(){
  try{
    const mf = await (await fetch('questions/manifest.json',{cache:'no-store'})).json();
    const all = [];
    for(const fn of (mf.topics||[])){
      const data = await (await fetch('questions/'+fn,{cache:'no-store'})).json();
      const topic = data.topic || fn;
      (data.cards||[]).forEach(c=>{ if(c && c.q && c.a) all.push({t:topic, q:c.q, a:c.a, l:c.l||''}); });
    }
    CARDS = all;
    CARDS.forEach(c=>c.id=cid(c));
    byId = Object.fromEntries(CARDS.map(c=>[c.id,c]));
    TOPICS = [...new Set(CARDS.map(c=>c.t))];
    buildChips();
    buildDeck();
  }catch(e){
    console.error(e);
    const el=document.getElementById('card-stage');
    if(el) el.innerHTML =
      '<div class="placeholder"><div style="font-size:1.6rem">&#9888;&#65039;</div>'+
      '<div>Die Fragen konnten nicht geladen werden.</div>'+
      '<div style="font-size:.85rem;max-width:46ch;margin:0 auto">Diese Seite muss \u00fcber eine Web-Adresse ge\u00f6ffnet werden '+
      '(z.\u202fB. die GitHub-Pages-URL), nicht per Doppelklick auf die Datei. '+
      'Zum lokalen Testen einen kleinen Webserver nutzen, z.\u202fB. im Projektordner: '+
      '<code>python3 -m http.server</code> und dann <code>http://localhost:8000</code> \u00f6ffnen.</div></div>';
  }
}
loadData();

</script>
</body>
</html>
