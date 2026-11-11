<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Magik AI Studio — 100 modèles</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Space+Grotesk:wght@500;600;700&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#07050e;
  --panel:rgba(255,255,255,.035);
  --panel2:rgba(255,255,255,.06);
  --border:rgba(255,255,255,.08);
  --text:#e9e6f2;
  --muted:#8b87a3;
  --accent:#a855f7;
  --accent2:#6366f1;
  --accent3:#22d3ee;
}
html,body{height:100%}
body{
  font-family:'Inter',system-ui,-apple-system,sans-serif;
  background:var(--bg);
  color:var(--text);
  overflow:hidden;
  -webkit-font-smoothing:antialiased;
  text-rendering:optimizeLegibility;
}
/* ---------- Ambiance ---------- */
body::before{
  content:'';position:fixed;inset:-25%;z-index:0;pointer-events:none;
  background:
    radial-gradient(620px 620px at 12% 18%, rgba(168,85,247,.20), transparent 62%),
    radial-gradient(720px 720px at 88% 12%, rgba(99,102,241,.16), transparent 62%),
    radial-gradient(760px 760px at 72% 92%, rgba(34,211,238,.10), transparent 62%),
    radial-gradient(500px 500px at 35% 85%, rgba(244,114,182,.08), transparent 62%);
  filter:blur(30px);
  animation:drift 24s ease-in-out infinite alternate;
}
body::after{
  content:'';position:fixed;inset:0;z-index:0;pointer-events:none;opacity:.35;
  background-image:linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),
                   linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);
  background-size:56px 56px;
  mask-image:radial-gradient(circle at 50% 40%, #000 0%, transparent 78%);
}
@keyframes drift{
  0%{transform:translate3d(0,0,0) scale(1)}
  100%{transform:translate3d(2%,-2%,0) scale(1.06)}
}
::-webkit-scrollbar{width:9px;height:9px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:rgba(255,255,255,.10);border-radius:99px;border:2px solid transparent;background-clip:padding-box}
::-webkit-scrollbar-thumb:hover{background:rgba(168,85,247,.45);background-clip:padding-box}

/* ---------- Layout ---------- */
.app{display:flex;height:100vh;height:100dvh;position:relative;z-index:1}

/* ---------- Sidebar ---------- */
.sidebar{
  width:332px;flex:0 0 332px;display:flex;flex-direction:column;
  background:rgba(11,8,20,.72);
  backdrop-filter:blur(26px);-webkit-backdrop-filter:blur(26px);
  border-right:1px solid var(--border);
}
.brand{display:flex;align-items:center;gap:12px;padding:20px 18px 16px}
.logo{
  width:42px;height:42px;border-radius:14px;flex:0 0 auto;
  background:linear-gradient(135deg,#a855f7,#6366f1 52%,#22d3ee);
  display:grid;place-items:center;font-size:20px;color:#fff;
  box-shadow:0 10px 30px rgba(124,58,237,.45), inset 0 1px 0 rgba(255,255,255,.35);
  position:relative;overflow:hidden;
}
.logo::after{
  content:'';position:absolute;inset:0;
  background:linear-gradient(120deg,transparent 30%,rgba(255,255,255,.5) 50%,transparent 70%);
  transform:translateX(-120%);animation:sheen 4.5s ease-in-out infinite;
}
@keyframes sheen{0%,70%{transform:translateX(-120%)}100%{transform:translateX(120%)}}
.brand-txt h1{font-family:'Space Grotesk',sans-serif;font-size:17.5px;font-weight:700;letter-spacing:-.4px;line-height:1.1}
.brand-txt h1 span{
  background:linear-gradient(90deg,#c084fc,#818cf8,#22d3ee);
  -webkit-background-clip:text;background-clip:text;color:transparent;
}
.brand-txt p{font-size:10.5px;color:var(--muted);margin-top:3px;letter-spacing:.4px;text-transform:uppercase;font-weight:500}

.search{position:relative;margin:0 14px 12px}
.search svg{position:absolute;left:12px;top:50%;transform:translateY(-50%);opacity:.45;pointer-events:none}
.search input{
  width:100%;padding:11px 34px 11px 37px;border-radius:12px;
  border:1px solid var(--border);background:rgba(255,255,255,.04);
  color:var(--text);font-size:13.5px;font-family:inherit;outline:none;transition:.2s;
}
.search input::placeholder{color:#615d78}
.search input:focus{border-color:rgba(168,85,247,.55);background:rgba(168,85,247,.06);box-shadow:0 0 0 3px rgba(168,85,247,.10)}
.search kbd{
  position:absolute;right:10px;top:50%;transform:translateY(-50%);
  font-size:9.5px;padding:2px 5px;border-radius:5px;border:1px solid var(--border);
  color:#615d78;font-family:inherit;pointer-events:none;
}

.chips{display:flex;gap:6px;overflow-x:auto;padding:0 14px 12px;scrollbar-width:none}
.chips::-webkit-scrollbar{display:none}
.chip{
  flex:0 0 auto;padding:6px 11px;border-radius:99px;font-size:11.5px;font-weight:500;
  border:1px solid var(--border);background:rgba(255,255,255,.03);color:var(--muted);
  cursor:pointer;transition:.18s;white-space:nowrap;font-family:inherit;
}
.chip:hover{color:var(--text);border-color:rgba(255,255,255,.2);background:rgba(255,255,255,.06)}
.chip.active{
  background:linear-gradient(135deg,#a855f7,#6366f1);color:#fff;border-color:transparent;
  box-shadow:0 5px 18px rgba(124,58,237,.4);font-weight:600;
}

.model-list{flex:1;overflow-y:auto;padding:2px 10px 14px}
.model-item{
  width:100%;display:flex;align-items:center;gap:10px;padding:9px 10px;
  border-radius:11px;border:1px solid transparent;background:transparent;
  cursor:pointer;text-align:left;color:var(--text);transition:.15s;
  position:relative;font-family:inherit;margin-bottom:1px;
}
.model-item:hover{background:rgba(255,255,255,.055)}
.model-item.active{
  background:linear-gradient(90deg,rgba(168,85,247,.17),rgba(99,102,241,.06));
  border-color:rgba(168,85,247,.32);
}
.model-item.active::before{
  content:'';position:absolute;left:0;top:22%;bottom:22%;width:3px;border-radius:3px;
  background:linear-gradient(#a855f7,#22d3ee);box-shadow:0 0 10px rgba(168,85,247,.8);
}
.dot{
  width:8px;height:8px;border-radius:50%;background:var(--c);flex:0 0 auto;
  box-shadow:0 0 10px var(--c);
}
.mi-main{min-width:0;flex:1}
.mi-name{
  font-size:12.8px;font-weight:600;letter-spacing:-.1px;display:block;
  white-space:nowrap;overflow:hidden;text-overflow:ellipsis;
}
.mi-sub{font-size:10.3px;color:var(--muted);display:block;margin-top:2px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.speed{display:flex;align-items:flex-end;gap:2px;height:13px;flex:0 0 auto;opacity:.85}
.speed i{width:2.5px;border-radius:2px;background:rgba(255,255,255,.14);transition:.2s}
.speed i:nth-child(1){height:4px}
.speed i:nth-child(2){height:6px}
.speed i:nth-child(3){height:8px}
.speed i:nth-child(4){height:10px}
.speed i:nth-child(5){height:13px}
.speed i.on{background:var(--c);box-shadow:0 0 6px var(--c)}
.no-result{padding:30px 16px;text-align:center;font-size:12.5px;color:var(--muted)}

.sidebar-foot{
  display:flex;align-items:center;justify-content:space-between;
  padding:11px 18px;border-top:1px solid var(--border);
  font-size:11px;color:var(--muted);letter-spacing:.2px;
}
.live{display:flex;align-items:center;gap:6px;font-weight:600;color:#4ade80;font-size:10.5px}
.live::before{
  content:'';width:6px;height:6px;border-radius:50%;background:#4ade80;
  box-shadow:0 0 8px #4ade80;animation:pulse 1.8s infinite;
}
@keyframes pulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.4;transform:scale(.75)}}

/* ---------- Main ---------- */
.main{flex:1;display:flex;flex-direction:column;min-width:0;position:relative}

.topbar{
  display:flex;align-items:center;gap:14px;padding:14px 22px;
  border-bottom:1px solid var(--border);
  background:rgba(10,7,18,.5);backdrop-filter:blur(18px);
  position:relative;z-index:5;
}
.model-head{display:flex;align-items:center;gap:12px;min-width:0;flex:1}
.avatar-model{
  width:38px;height:38px;border-radius:12px;flex:0 0 auto;display:grid;place-items:center;
  font-family:'Space Grotesk',sans-serif;font-weight:700;font-size:16px;color:#fff;
  box-shadow:0 6px 20px rgba(0,0,0,.4), inset 0 1px 0 rgba(255,255,255,.3);
  transition:.3s;
}
.head-name{font-size:14.5px;font-weight:600;letter-spacing:-.2px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.head-meta{font-size:11px;color:var(--muted);margin-top:2px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.topbar-actions{display:flex;gap:8px;align-items:center}
.btn-ghost{
  padding:8px 14px;border-radius:10px;border:1px solid var(--border);
  background:rgba(255,255,255,.04);color:var(--text);font-size:12.3px;font-weight:500;
  cursor:pointer;transition:.18s;font-family:inherit;white-space:nowrap;
}
.btn-ghost:hover{background:rgba(255,255,255,.09);border-color:rgba(255,255,255,.2)}
.icon-btn{
  display:none;place-items:center;width:38px;height:38px;border-radius:11px;
  border:1px solid var(--border);background:rgba(255,255,255,.04);color:var(--text);
  cursor:pointer;font-size:16px;transition:.18s;font-family:inherit;
}
.icon-btn:hover{background:rgba(255,255,255,.09)}

/* ---------- Chat ---------- */
.chat{flex:1;overflow-y:auto;padding:26px 22px 8px;scroll-behavior:smooth}
.chat-inner{max-width:840px;margin:0 auto;display:flex;flex-direction:column;gap:20px;padding-bottom:8px}

.msg{display:flex;gap:12px;animation:rise .38s cubic-bezier(.2,.7,.3,1) both}
@keyframes rise{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:none}}
.avatar{
  width:34px;height:34px;border-radius:11px;flex:0 0 auto;display:grid;place-items:center;
  font-size:13px;font-weight:700;font-family:'Space Grotesk',sans-serif;
}
.msg.user .avatar{background:linear-gradient(135deg,#334155,#1e293b);border:1px solid rgba(255,255,255,.12);color:#cbd5e1}
.msg.ai .avatar{
  background:linear-gradient(135deg,#a855f7,#6366f1);color:#fff;
  box-shadow:0 6px 20px rgba(124,58,237,.45);
}
.bubble{
  flex:1;min-width:0;background:rgba(255,255,255,.033);
  border:1px solid rgba(255,255,255,.06);border-radius:15px;padding:12px 15px;
  position:relative;
}
.msg.user .bubble{
  background:linear-gradient(135deg,rgba(168,85,247,.14),rgba(99,102,241,.07));
  border-color:rgba(168,85,247,.24);
}
.msg-name{
  font-size:11.5px;font-weight:600;color:#a9a4c2;margin-bottom:6px;
  display:flex;align-items:center;gap:8px;
}
.badge-mini{
  font-size:9px;padding:1.5px 6px;border-radius:5px;font-weight:600;
  background:rgba(168,85,247,.18);color:#c4b5fd;border:1px solid rgba(168,85,247,.25);
}
.content{font-size:14.3px;line-height:1.68;color:#ddd9ea;word-wrap:break-word;overflow-wrap:anywhere}
.content strong{color:#fff;font-weight:600}
.content code{
  background:rgba(255,255,255,.09);padding:1.5px 5px;border-radius:5px;
  font-family:ui-monospace,'SF Mono',Menlo,monospace;font-size:.87em;color:#c4b5fd;
}
.content pre{
  background:rgba(0,0,0,.42);border:1px solid rgba(255,255,255,.08);border-radius:11px;
  padding:13px 15px;overflow-x:auto;margin:10px 0;line-height:1.55;
}
.content pre code{background:none;padding:0;color:#d8d4e8;font-size:12.8px}
.cursor{
  display:inline-block;width:7px;height:15px;background:#a855f7;border-radius:1px;
  vertical-align:-2px;margin-left:2px;animation:blink .9s step-end infinite;
}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.msg-actions{display:flex;gap:6px;margin-top:9px;opacity:0;transition:.2s}
.bubble:hover .msg-actions{opacity:1}
.mini-btn{
  font-size:10.5px;padding:4px 9px;border-radius:7px;border:1px solid var(--border);
  background:rgba(255,255,255,.04);color:var(--muted);cursor:pointer;
  font-family:inherit;transition:.16s;
}
.mini-btn:hover{color:var(--text);background:rgba(255,255,255,.1)}

/* ---------- Empty state ---------- */
.empty{display:flex;flex-direction:column;align-items:center;text-align:center;padding:46px 16px 20px;animation:rise .5s both}
.empty-orb{
  width:74px;height:74px;border-radius:24px;display:grid;place-items:center;font-size:32px;
  background:linear-gradient(135deg,#a855f7,#6366f1 55%,#22d3ee);
  box-shadow:0 20px 60px rgba(124,58,237,.5), inset 0 1px 0 rgba(255,255,255,.4);
  margin-bottom:22px;animation:float 5s ease-in-out infinite;
}
@keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-9px)}}
.empty h2{font-family:'Space Grotesk',sans-serif;font-size:25px;font-weight:700;letter-spacing:-.6px;margin-bottom:10px}
.grad{background:linear-gradient(90deg,#c084fc,#818cf8,#22d3ee);-webkit-background-clip:text;background-clip:text;color:transparent}
.empty p{font-size:13.6px;color:var(--muted);max-width:440px;line-height:1.65;margin-bottom:26px}
.suggests{display:grid;grid-template-columns:repeat(2,1fr);gap:9px;width:100%;max-width:560px}
.sugg{
  text-align:left;padding:12px 14px;border-radius:12px;border:1px solid var(--border);
  background:rgba(255,255,255,.032);color:#cfcbe0;font-size:12.4px;line-height:1.45;
  cursor:pointer;transition:.18s;font-family:inherit;
}
.sugg:hover{background:rgba(168,85,247,.10);border-color:rgba(168,85,247,.35);transform:translateY(-2px)}
.sugg b{display:block;font-size:10px;color:#8b5cf6;letter-spacing:.6px;text-transform:uppercase;margin-bottom:4px;font-weight:700}

/* ---------- Composer ---------- */
.composer{padding:10px 22px 18px;background:linear-gradient(to top,rgba(7,5,14,.95) 30%,transparent)}
.composer-inner{max-width:840px;margin:0 auto}
.controls{display:flex;gap:20px;align-items:center;padding:0 4px 10px;flex-wrap:wrap}
.ctl{display:flex;align-items:center;gap:9px;font-size:10.8px;color:var(--muted);font-weight:500;letter-spacing:.2px}
.ctl span{color:#c4b5fd;font-variant-numeric:tabular-nums;min-width:36px;font-size:10.5px}
input[type=range]{
  -webkit-appearance:none;appearance:none;width:88px;height:3px;border-radius:99px;
  background:rgba(255,255,255,.12);outline:none;cursor:pointer;
}
input[type=range]::-webkit-slider-thumb{
  -webkit-appearance:none;width:12px;height:12px;border-radius:50%;
  background:linear-gradient(135deg,#c084fc,#818cf8);
  box-shadow:0 0 10px rgba(168,85,247,.7);cursor:pointer;transition:.15s;
}
input[type=range]::-webkit-slider-thumb:hover{transform:scale(1.2)}
input[type=range]::-moz-range-thumb{
  width:12px;height:12px;border:none;border-radius:50%;
  background:linear-gradient(135deg,#c084fc,#818cf8);box-shadow:0 0 10px rgba(168,85,247,.7);
}
.input-wrap{
  display:flex;align-items:flex-end;gap:10px;
  background:rgba(255,255,255,.045);border:1px solid var(--border);
  border-radius:17px;padding:9px 9px 9px 16px;transition:.2s;
}
.input-wrap:focus-within{
  border-color:rgba(168,85,247,.5);background:rgba(168,85,247,.05);
  box-shadow:0 0 0 4px rgba(168,85,247,.09), 0 14px 44px rgba(0,0,0,.45);
}
textarea{
  flex:1;background:none;border:none;outline:none;color:var(--text);
  font-family:inherit;font-size:14.4px;resize:none;max-height:170px;line-height:1.58;
  padding:7px 0;scrollbar-width:thin;
}
textarea::placeholder{color:#5d5975}
.send{
  width:42px;height:42px;border-radius:13px;border:none;flex:0 0 auto;
  background:linear-gradient(135deg,#a855f7,#6366f1);color:#fff;cursor:pointer;
  display:grid;place-items:center;transition:.18s;
  box-shadow:0 7px 22px rgba(124,58,237,.45);
}
.send:hover:not(:disabled){transform:translateY(-2px) scale(1.04);box-shadow:0 12px 30px rgba(124,58,237,.6)}
.send:active:not(:disabled){transform:translateY(0) scale(.97)}
.send:disabled{opacity:.35;cursor:not-allowed;box-shadow:none}
.hint{text-align:center;font-size:10.3px;color:#514d66;margin-top:9px;letter-spacing:.2px}

.overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.62);backdrop-filter:blur(4px);z-index:40}

/* ---------- Responsive ---------- */
@media (max-width:900px){
  .sidebar{
    position:fixed;left:0;top:0;bottom:0;z-index:50;width:302px;flex-basis:302px;
    transform:translateX(-101%);transition:transform .3s cubic-bezier(.2,.7,.3,1);
  }
  .sidebar.open{transform:none;box-shadow:20px 0 60px rgba(0,0,0,.6)}
  .overlay.show{display:block}
  .icon-btn{display:grid}
  .suggests{grid-template-columns:1fr}
  .composer{padding:8px 14px 14px}
  .chat{padding:20px 14px 6px}
  .topbar{padding:12px 14px}
  .btn-ghost .label{display:none}
}
</style>
</head>
<body>

<div class="app">
  <div class="overlay" id="overlay"></div>

  <!-- ============ SIDEBAR ============ -->
  <aside class="sidebar" id="sidebar">
    <div class="brand">
      <div class="logo">✦</div>
      <div class="brand-txt">
        <h1>Magik <span>AI</span> Studio</h1>
        <p>100 modèles · v4.0</p>
      </div>
    </div>

    <div class="search">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round">
        <circle cx="11" cy="11" r="7"></circle><path d="M20 20l-3.5-3.5"></path>
      </svg>
      <input id="search" type="text" placeholder="Rechercher un modèle…" autocomplete="off">
      <kbd>⌘K</kbd>
    </div>

    <div class="chips" id="chips"></div>
    <div class="model-list" id="modelList"></div>

    <div class="sidebar-foot">
      <span id="countLabel">100 modèles</span>
      <span class="live">En ligne</span>
    </div>
  </aside>

  <!-- ============ MAIN ============ -->
  <main class="main">
    <header class="topbar">
      <button class="icon-btn" id="menuBtn" aria-label="Menu">☰</button>
      <div class="model-head">
        <div class="avatar-model" id="headAvatar">M</div>
        <div style="min-width:0">
          <div class="head-name" id="headName">Magik Mind 4 Ultra</div>
          <div class="head-meta" id="headMeta">Raisonnement · 256K · 1.2T</div>
        </div>
      </div>
      <div class="topbar-actions">
        <button class="btn-ghost" id="clearBtn">✦ <span class="label">Nouvelle conversation</span></button>
      </div>
    </header>

    <section class="chat" id="chat">
      <div class="chat-inner" id="chatInner"></div>
    </section>

    <div class="composer">
      <div class="composer-inner">
        <div class="controls">
          <label class="ctl">Créativité
            <input type="range" id="temp" min="0" max="100" value="65">
            <span id="tempVal">0.65</span>
          </label>
          <label class="ctl">Tokens max
            <input type="range" id="tokens" min="256" max="8192" step="256" value="2048">
            <span id="tokVal">2048</span>
          </label>
        </div>
        <div class="input-wrap">
          <textarea id="input" rows="1" placeholder="Écris ton message à Magik AI Studio…"></textarea>
          <button class="send" id="sendBtn" title="Envoyer" aria-label="Envoyer">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M12 19V5"></path><path d="M5 12l7-7 7 7"></path>
            </svg>
          </button>
        </div>
        <div class="hint">Entrée pour envoyer · Maj + Entrée pour un saut de ligne</div>
      </div>
    </div>
  </main>
</div>

<script>
/* ============================================================
   MAGIK AI STUDIO — 100 MODÈLES
   ============================================================ */

const CATS = {
  reasoning:{label:'Raisonnement', color:'#a855f7'},
  code:     {label:'Code',         color:'#22d3ee'},
  creative: {label:'Créatif',      color:'#f472b6'},
  vision:   {label:'Vision',       color:'#fbbf24'},
  multi:    {label:'Multimodal',   color:'#34d399'},
  fast:     {label:'Rapide',       color:'#60a5fa'},
  open:     {label:'Open Source',  color:'#a3e635'},
  special:  {label:'Spécialisé',   color:'#fb7185'}
};

/* [nom, catégorie, contexte, vitesse(1-5), paramètres, description] */
const RAW = [
  /* ---- Raisonnement (15) ---- */
  ["Magik Mind 4 Ultra","reasoning","256K",4,"1.2T","Le raisonnement le plus profond de la gamme Magik."],
  ["Magik Mind 4","reasoning","200K",5,"480B","Équilibre parfait entre puissance et vitesse."],
  ["Magik Mind 4 Mini","reasoning","128K",5,"32B","Compact mais redoutable en logique."],
  ["DeepThink R2","reasoning","180K",3,"670B","Chaîne de pensée étendue pour problèmes complex
