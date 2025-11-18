<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Deep Blue Games Hub</title>```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Deep Blue Games Hub</title>

  <!-- Comfortaa font -->

  <!-- Comfortaa font -->
  <link href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;700&display=swap" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;700&display=swap" rel="stylesheet"/>

  <style>
    /* =========================
       THEME VARIABLES
       ========================= */
    :root{
      --blue-0:#081128;
      --blue-1:#0e1a47;
      --blue-2:#10235a;
      --blue-3:#13306f;
      --blue-4:#17408f;
      --accent:#67d1ff;
      --accent-2:#7fffd4;
      --

  <style>
    /* =========================
       THEME VARIABLES
       ========================= */
    :root{
      --blue-0:#081128;
      --blue-1:#0e1a47;
      --blue-2:#10235a;
      --blue-3:#13306f;
      --blue-4:#17408f;
      --accent:#67d1ff;
      --accent-2:#7fffd4;
      --text:#e8f0ff;

      --radius:16px;
      --radius-sm:10px;
      --shadow: 0 20px 40px rgba(0,0,0,.35);
      --shadow-soft: 0 8px 24px rgba(0,0,0,.25);
      --glass: rgba(255,255,255,.06);
     text:#e8f0ff;

      --radius:16px;
      --radius-sm:10px;
      --shadow: 0 20px 40px rgba(0,0,0,.35);
      --shadow-soft: 0 8px 24px rgba(0,0,0,.25);
      --glass: rgba(255,255,255,.06);
      --glass-strong: --glass-strong: rgba(255,255,255,.12);

      --dur-xfast:.18s;
      --dur-fast:.25s;
      --dur:.45s;
      --dur-slow:.9s;
      --ease: cubic-bezier(.22,.61,.36,1);
    }

    html,body{
      height:100%;
      margin:0;
      background:
        radial-gradient(1200px 800px at 20% 20 rgba(255,255,255,.12);

      --dur-xfast:.18s;
      --dur-fast:.25s;
      --dur:.45s;
      --dur-slow:.9s;
      --ease: cubic-bezier(.22,.61,.36,1);
    }

    html,body{
      height:100%;
      margin:0;
      background:
        radial-gradient(1200px 800px at 20% 20%, var(--blue-4)%, var(--blue-4) 0%, var(--blue-2) 35%, var(--blue-1) 60%, var(--blue-0) 100%);
      color:var(--text);
      font-family:'Comfortaa', system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans";
      overflow:hidden;
    }

    /* =========================
       BACKGROUND LAYERS
       ========================= */
    .bg{
      position:fixed;
      inset:0;
      z-index:-2;
      pointer-events:none;
      filter:saturate(105%) contrast(105%);
    }
    .bg-gradient{
      position 0%, var(--blue-2) 35%, var(--blue-1) 60%, var(--blue-0) 100%);
      color:var(--text);
      font-family:'Comfortaa', system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans";
      overflow:hidden;
    }

    /* =========================
       BACKGROUND LAYERS
       ========================= */
    .bg{
      position:fixed;
      inset:0;
      z-index:-2;
      pointer-events:none;
      filter:saturate(105%) contrast(105%);
    }
    .bg-gradient{
      position:absolute;
     :absolute;
      inset:0;
      background:
        radial-gradient(1200px 900px at 12% 88%, rgba(103,209,255,.08), transparent 60%),
        radial-gradient(1000px 700px at 86% 12%, rgba(127,255,212,.06), transparent 60%);
      mix-blend-mode:screen;
    }
    canvas#particles{
      position:absolute;
      inset:0;
 inset:0;
      background:
        radial-gradient(1200px 900px at 12% 88%, rgba(103,209,255,.08), transparent 60%),
        radial-gradient(1000px 700px at 86% 12%, rgba(127,255,212,.06), transparent 60%);
      mix-blend-mode:screen;
    }
    canvas#particles{
      position:absolute;
      inset:0;
    }

    /* =========================
       APP    }

    /* =========================
       APP SURFACE
       ========================= */
    .app{
      position:relative;
      height:100%;
      overflow:auto;
      backdrop-filter: blur(6px);
    }

    /* =========================
       HEADER
       ========================= */
    header{
      position:sticky;
      top:0;
      z-index:5;
      margin:24px auto 0;
      max-width:1200px;
      padding:16px 16px;
      border-radius:var(--radius);
      background:linear-gradient(180deg, rgba(255,255,255,.10), rgba(255, SURFACE
       ========================= */
    .app{
      position:relative;
      height:100%;
      overflow:auto;
      backdrop-filter: blur(6px);
    }

    /* =========================
       HEADER
       ========================= */
    header{
      position:sticky;
      top:0;
      z-index:5;
      margin:24px auto 0;
      max-width:1200px;
      padding:16px 16px;
      border-radius:var(--radius);
      background:linear-gradient(180deg, rgba(255,255,255255,255,.04));
      box-shadow: var(--shadow-soft);
      border:1px solid rgba(255,255,255,.12);
      display:flex;
      align-items:center;
      gap:14px;
    }
    header .logo{
      width:44px;height:44px;border-radius:12px;
      background: conic-gradient(from 120deg, var(--accent), var(--accent-2), var(--blue-4), var(--accent));
      box-shadow: 0 8px 20px rgba(103,209,255,.25);
      animation: spinSoft 14s linear,.10), rgba(255,255,255,.04));
      box-shadow: var(--shadow-soft);
      border:1px solid rgba(255,255,255,.12);
      display:flex;
      align-items:center;
      gap:14px;
    }
    header .logo{
      width:44px;height:44px;border-radius:12px;
      background: conic-gradient(from 120deg, var(--accent), var(--accent-2), var(--blue-4), var(--accent));
      box-shadow: 0 8px 20px rgba(103,209,255,.25);
      animation: spinSoft 14s linear infinite;
    }
 infinite;
    }
    header h1{
      margin:0;
      font-size:1.4rem;
      letter-spacing:.5px;
      font-weight:700;
      text-shadow:0 2px 14px rgba(103,209,255,.25);
    }
    header .spacer{flex:1;}
    header .actions{
      display:flex; gap:10px; align-items:center;
      flex-wrap:wrap;
    }

    /* =========================
       CONTROLS
       ========================= */
    .control{
      display:flex;
      align-items:center;
         header h1{
      margin:0;
      font-size:1.4rem;
      letter-spacing:.5px;
      font-weight:700;
      text-shadow:0 2px 14px rgba(103,209,255,.25);
    }
    header .spacer{flex:1;}
    header .actions{
      display:flex; gap:10px; align-items:center;
      flex-wrap:wrap;
    }

    /* =========================
       CONTROLS
       ========================= */
    .control{
      display:flex;
      align-items:center;
      gap:10px;
      gap:10px;
      padding:8px 10px;
      border-radius:var(--radius-sm);
      background: var(--glass);
      border:1px solid rgba(255,255,255,.14);
      transition: background var(--dur) var(--ease), transform var(--dur) var(--ease), box-shadow var(--dur) var(--ease);
    }
    .control:focus-within{
      background: var(--glass-strong);
      transform: translateY(-1px padding:8px 10px;
      border-radius:var(--radius-sm);
      background: var(--glass);
      border:1px solid rgba(255,255,255,.14);
      transition: background var(--dur) var(--ease), transform var(--dur) var(--ease), box-shadow var(--dur) var(--ease);
    }
    .control:focus-within{
      background: var(--glass-strong);
      transform: translateY(-1px);
      box-shadow);
      box-shadow: 0 12px 30px rgba(0,0,0,.25);
    }
    .control input{
      flex:1;
      min-width:260px;
      padding:10px 12px;
      color:var(--text);
      background:transparent;
      border:0;
      outline:none;
      font-size:.98rem;
    }
    .control button{
      padding: 0 12px 30px rgba(0,0,0,.25);
    }
    .control input{
      flex:1;
      min-width:260px;
      padding:10px 12px;
      color:var(--text);
      background:transparent;
      border:0;
      outline:none;
      font-size:.98rem;
    }
    .control button{
      padding:10px 14px;
      border:0;
      border-radius:12px;
      color:#041224;
      background: linear-gradient(180deg, var(--accent) 0%, #a0e7ff 100%);
      box-shadow: 0 8px 18px rgba(103,209,255,.35);
      font-weight:700;
      transition: transform var(--dur-fast) var(--:10px 14px;
      border:0;
      border-radius:12px;
      color:#041224;
      background: linear-gradient(180deg, var(--accent) 0%, #a0e7ff 100%);
      box-shadow: 0 8px 18px rgba(103,209,255,.35);
      font-weight:700;
      transition: transform var(--dur-fast) var(--ease), box-shadow var(--dur-fast)ease), box-shadow var(--dur-fast) var(--ease), filter var(--dur-fast) var(--ease);
      cursor:pointer;
    }
    .control button:hover{ transform: translateY(-2px) scale(1.02); }
    .control button:active{ transform: translateY(0) scale(.98); box-shadow: 0 6px 14px rgba(103,209,255,.28); }

    /* =========================
       CONTENT
       ================= var(--ease), filter var(--dur-fast) var(--ease);
      cursor:pointer;
    }
    .control button:hover{ transform: translateY(-2px) scale(1.02); }
    .control button:active{ transform: translateY(0) scale(.98); box-shadow: 0 6px 14px rgba(103,209,255,.28); }

    /* =========================
       CONTENT
       ========================= */
    .content{
      max-width:1200px;
      margin:22px auto 60px;
      padding:0 8px;
    }

    .grid{
      display:grid;
      grid-template-columns: repeat(12, 1fr);
      gap:16px;
    }
    @media (max-width: 1100px){
      .grid{ grid-template-columns: repeat(8, 1fr); }
    }
    @media (max-width: 860px){
      .grid{ grid-template-columns: repeat(6, 1fr); }
    }
    @media (max-width: 640======== */
    .content{
      max-width:1200px;
      margin:22px auto 60px;
      padding:0 8px;
    }

    .grid{
      display:grid;
      grid-template-columns: repeat(12, 1fr);
      gap:16px;
    }
    @media (max-width: 1100px){
      .grid{ grid-template-columns: repeat(8, 1fr); }
    }
    @media (max-width: 860px){
      .grid{ grid-template-columns: repeat(6, 1fr); }
    }
    @media (max-width: 640px){
      .gridpx){
      .grid{ grid-template-columns: repeat(2, 1fr); }
    }

    /* =========================
       CARD
       ========================= */
    .card{
      grid-column: span 4;
      background: linear-gradient(180deg, rgba(255,255,255,.08), rgba{ grid-template-columns: repeat(2, 1fr); }
    }

    /* =========================
       CARD
       ========================= */
    .card{
      grid-column: span 4;
      background: linear-gradient(180deg, rgba(255,255,255,.08), rgba(255,255,255,.04));
      border:1px solid rgba(255,255,255,.14);
      border-radius:var(--radius);
      box-shadow: var(--shadow-soft);
      overflow:hidden;
      position:relative;
      display:flex;
      flex-direction:column;
      min-height:280px;
     (255,255,255,.04));
      border:1px solid rgba(255,255,255,.14);
      border-radius:var(--radius);
      box-shadow: var(--shadow-soft);
      overflow:hidden;
      position:relative;
      display:flex;
      flex-direction:column;
      min-height:280px;
      transform: translate transform: translateZ(0);
      transition: transform var(--dur) var(--ease), box-shadow var(--dur) var(--ease), border-color var(--dur) var(--ease);
    }
    .card:hover{
      transform: translateY(-3px);
      box-shadow: 0 20px 40px rgba(0,0,0,.35);
      border-color: rgba(255,255,255,.22);
    }
    .card header{
      position:relative;
      margin:0;
     Z(0);
      transition: transform var(--dur) var(--ease), box-shadow var(--dur) var(--ease), border-color var(--dur) var(--ease);
    }
    .card:hover{
      transform: translateY(-3px);
      box-shadow: 0 20px 40px rgba(0,0,0,.35);
      border-color: rgba(255,255,255,.22);
    }
    .card header{
      position:relative;
      margin:0;
      border-radius:0;
      padding:10px 14px;
      background: linear-gradient(180deg, rgba(255,255,255,.08), rgba(255,255,255,.02));
      border-bottom:1px solid rgba(255,255,255,.12);
      box-shadow:none;
      display:flex; gap:10px; align-items:center; justify-content:space-between;
    }
    .card header .title{
      display:flex; align-items:center; gap:10px;
    }
    .card header .logo{
      width:36px;height:36px border-radius:0;
      padding:10px 14px;
      background: linear-gradient(180deg, rgba(255,255,255,.08), rgba(255,255,255,.02));
      border-bottom:1px solid rgba(255,255,255,.12);
      box-shadow:none;
      display:flex; gap:10px; align-items:center; justify-content:space-between;
    }
    .card header .title{
      display:flex; align-items:center; gap:10px;
    }
    .card header .logo{
      width:36px;height:36px;border-radius:10px;
      background: linear-gradient(135deg, var(--accent) 0%, var(--accent-2) 100%);
      animation: none;
      box-shadow: 0 6px 12px rgba(103,209,255,.25);
    }
    .card header h2{
      margin:0;
      font-size:1.05rem;
      letter-spacing:.3px;
      font-weight:700;
      max-width: 60ch;
      overflow:hidden; text-overflow:ellipsis; white-space:nowrap;
   ;border-radius:10px;
      background: linear-gradient(135deg, var(--accent) 0%, var(--accent-2) 100%);
      animation: none;
      box-shadow: 0 6px 12px rgba(103,209,255,.25);
    }
    .card header h2{
      margin:0;
      font-size:1.05rem;
      letter-spacing:.3px;
      font-weight:700;
      max-width: 60ch;
      overflow:hidden; text-overflow:ellipsis; white-space:nowrap;
    }
    .card .frame }
    .card .frame{
      position:relative;
      flex:1;
      background: radial-gradient(500px 300px at 50% 50%, rgba(103,209,255,.06), rgba(255,255,255,0) 65%);
      display:flex;
      align-items:center;
      justify-content:center;
      overflow:hidden;
    }
    .card iframe{
      width:100%;
      height:100%;
      border:0;
     {
      position:relative;
      flex:1;
      background: radial-gradient(500px 300px at 50% 50%, rgba(103,209,255,.06), rgba(255,255,255,0) 65%);
      display:flex;
      align-items:center;
      justify-content:center;
      overflow:hidden;
    }
    .card iframe{
      width:100%;
      height:100%;
      border:0;
      background:#081 background:#081431;
      transform: scale(1) translateZ(0);
      transition: transform var(--dur-slow) var(--ease), filter var(--dur-slow) var(--ease), box-shadow var(--dur) var(--ease);
    }
    .card:hover iframe{
      transform: scale(1.01);
      filter: saturate(110%);
    }
    .tools{
      display:flex;
      gap:8px;
      align-items:center;
    }
    .btn-icon{
      width:38px;height:38px;border-radius:12px;border:1px solid rgba(255,431;
      transform: scale(1) translateZ(0);
      transition: transform var(--dur-slow) var(--ease), filter var(--dur-slow) var(--ease), box-shadow var(--dur) var(--ease);
    }
    .card:hover iframe{
      transform: scale(1.01);
      filter: saturate(110%);
    }
    .tools{
      display:flex;
      gap:8px;
      align255,255,.16);
      background: rgba(255,255,255,.08);
      display:grid; place-items:center;
      cursor:pointer;
      transition: transform var(--dur-fast) var(--ease), background var(--dur-fast) var(--ease), border-color var(--dur-fast) var(--ease);
    }
    .btn-icon:hover{ transform: translateY(-2px); background: rgba(255,255,255,.14); border-color: rgba(255,255,255,.24); }
    .btn-icon svg{ width:20px;height:20px; fill:var(--text); opacity:.9; }

    /* =========================
       EMPTY STATE
       ========================= */
    .empty{
      grid-column: 1 / -1;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      padding:40px 20px;
      color:#b9c7ff;
      background: linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.03));
      border:1px dashed rgba(255,255,255,.18);
      border-radius:var(--radius);
    }

    /* =========================
       FOOTER
       ========================= */
    footer{
      max-width:1200px;
      margin:20px auto 60px;
      padding:16px 20px;
      border-radius:var(--radius);
      border:1px solid rgba(255,255,255,.12);
      background: linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.03));
      box-shadow: var(--shadow-soft);
      font-size:.92rem;
    }

    /* =========================
       TOAST
       ========================= */
    .toast{
      position:fixed;
      bottom:22px; left:50%;
      transform: translateX(-50%) translateY(20px);
      background: rgba(14,26,71,.85);
      color:var(--text);
      border:1px solid rgba(255,255,255,.16);
      border-radius:14px;
      padding:12px 16px;
      box-shadow: var(--shadow);
      opacity:0;
      pointer-events:none;
      transition: opacity var(--dur) var(--ease), transform var(--dur) var(--ease);
      z-index:20;
    }
    .toast.show{
      opacity:1;
      transform: translateX(-50%) translateY(0);
    }

    /* =========================
       ANIMATIONS
       ========================= */
    @keyframes spinSoft{
      0%{ transform: rotate(0deg); }
      100%{ transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <!-- Background -->
  <div class="bg" aria-hidden="true">
    <canvas id="particles"></canvas>
    <div class="bg-gradient"></div>
  </div>

  <div class="app" id="app">
    <!-- Header -->
    <header>
      <div class="logo" aria-hidden="true"></div>
      <h1>Deep Blue Games Hub</h1>
      <div class="spacer"></div>
      <div class="actions">
        <div class="control" aria-label="Add game by URL">
          <input id="gameUrl" type="url" placeholder="Paste game URL (https://...)" autocomplete="off" inputmode="url" />
          <button id="addBtn" title="Add game">Add game</button>
        </div>
        <div class="control" aria-label="Layout and theme">
          <button id="layoutBtn" title="Toggle layout">Layout</button>
          <button id="clearBtn" title="Clear all">Clear</button>
        </div>
      </div>
    </header>

    <!-- Content -->
    <main class="content">
      <section aria-label="Games grid">
        <div id="grid" class="grid">
          <div id="emptyState" class="empty">
            <div>
              <h2 style="margin:0 0 8px">No games yet</h2>
              <p style="margin:0">Paste a URL and press Add game. Supports itch.io, Google Sites, JS demos, web emulators, or any embeddable site.</p>
            </div>
          </div>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer>
      <p><strong>Tip:</strong> Drag cards to reorder. Your games are saved to your browser. Background responds to your cursor.</p>
    </footer>
  </div>

  <!-- Toast -->
