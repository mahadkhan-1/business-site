<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SF Auto Detail | Premium Auto Detailing — San Francisco</title>
  <meta name="description" content="San Francisco's premier hand-crafted auto detailing. Any make, any model, including motorcycles. Call 415-776-1844 to book.">

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- GSAP + ScrollTrigger -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>

  <style>
    /* ── DESIGN TOKENS ─────────────────────────────── */
    :root {
      --gold:        #C8A84B;
      --gold-bright: #E2C46A;
      --gold-pale:   #F4E4B0;
      --gold-dim:    rgba(200,168,75,.12);
      --ink:         #080807;
      --surface-1:   #0E0D0B;
      --surface-2:   #161410;
      --surface-3:   #1E1B14;
      --white:       #F6F4EE;
      --muted:       #7A7060;
      --muted-light: #A89E8A;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; font-size: 16px; }

    body {
      background: var(--ink);
      color: var(--white);
      font-family: 'DM Sans', sans-serif;
      font-weight: 300;
      overflow-x: hidden;
      -webkit-font-smoothing: antialiased;
    }

    /* Fine grain overlay */
    body::after {
      content: '';
      position: fixed; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='300' height='300'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='.035'/%3E%3C/svg%3E");
      pointer-events: none;
      z-index: 9999;
    }

    /* Scrollbar */
    ::-webkit-scrollbar { width: 3px; }
    ::-webkit-scrollbar-track { background: var(--ink); }
    ::-webkit-scrollbar-thumb { background: var(--gold); border-radius: 2px; }

    /* ── TYPOGRAPHY ─────────────────────────────────── */
    .f-display { font-family: 'Cormorant Garamond', Georgia, serif; }

    /* ── NAV ─────────────────────────────────────────── */
    #nav {
      position: fixed; top: 0; left: 0; right: 0;
      z-index: 1000;
      padding: 1.6rem 2rem;
      transition: padding .4s ease, background .4s ease, border-color .4s ease;
      border-bottom: 1px solid transparent;
    }
    #nav.solid {
      background: rgba(8,8,7,.94);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      padding: 1rem 2rem;
      border-bottom-color: rgba(200,168,75,.12);
    }
    .nav-inner {
      max-width: 1320px; margin: 0 auto;
      display: flex; align-items: center; justify-content: space-between;
    }
    .logo {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.5rem; font-weight: 600;
      letter-spacing: .04em; color: var(--gold);
      text-decoration: none; line-height: 1;
    }
    .logo em { color: var(--white); font-style: normal; }
    .nav-links { display: flex; align-items: center; gap: 2.5rem; }
    .nav-a {
      font-size: .68rem; font-weight: 500;
      letter-spacing: .16em; text-transform: uppercase;
      color: var(--muted); text-decoration: none;
      transition: color .3s;
    }
    .nav-a:hover { color: var(--gold); }
    .nav-cta {
      font-size: .65rem; font-weight: 600;
      letter-spacing: .14em; text-transform: uppercase;
      background: var(--gold); color: var(--ink);
      padding: .6rem 1.4rem; text-decoration: none;
      transition: background .3s, transform .2s, box-shadow .3s;
    }
    .nav-cta:hover {
      background: var(--gold-bright);
      transform: translateY(-1px);
      box-shadow: 0 8px 24px rgba(200,168,75,.28);
    }
    /* Hamburger */
    #ham { display: none; flex-direction: column; gap: 5px; cursor: pointer; background: none; border: none; }
    #ham span { display: block; width: 22px; height: 1.5px; background: var(--white); transition: .3s; }
    #ham.open span:nth-child(1) { transform: translateY(6.5px) rotate(45deg); }
    #ham.open span:nth-child(2) { opacity: 0; }
    #ham.open span:nth-child(3) { transform: translateY(-6.5px) rotate(-45deg); }

    /* Mobile menu overlay */
    #mobile-menu {
      position: fixed; inset: 0;
      background: var(--ink);
      z-index: 900;
      display: flex; flex-direction: column;
      justify-content: center;
      padding: 2rem;
      transform: translateX(100%);
      transition: transform .5s cubic-bezier(.77,0,.18,1);
    }
    #mobile-menu.open { transform: translateX(0); }
    .mm-link {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(2.5rem, 8vw, 4rem);
      font-weight: 600; color: var(--white);
      text-decoration: none; line-height: 1.2;
      border-bottom: 1px solid rgba(255,255,255,.06);
      padding: 1.2rem 0;
      transition: color .3s, padding-left .4s;
    }
    .mm-link:hover { color: var(--gold); padding-left: .5rem; }

    /* ── HERO ──────────────────────────────────────── */
    #hero {
      position: relative; min-height: 100vh;
      display: flex; align-items: center;
      overflow: hidden;
    }
    .hero-mesh {
      position: absolute; inset: 0;
      background:
        radial-gradient(ellipse 70% 60% at 15% 55%, rgba(200,168,75,.07) 0%, transparent 65%),
        radial-gradient(ellipse 50% 40% at 85% 20%, rgba(200,168,75,.04) 0%, transparent 55%),
        linear-gradient(160deg, #0a0901 0%, #060605 60%, #0c0b07 100%);
    }
    .hero-grid-lines {
      position: absolute; inset: 0;
      background-image:
        linear-gradient(rgba(200,168,75,.025) 1px, transparent 1px),
        linear-gradient(90deg, rgba(200,168,75,.025) 1px, transparent 1px);
      background-size: 70px 70px;
    }
    .hero-big-text {
      position: absolute;
      right: -3vw; bottom: -5vw;
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(14rem, 28vw, 32rem);
      font-weight: 700; line-height: .85;
      color: rgba(200,168,75,.028);
      user-select: none; pointer-events: none;
      letter-spacing: -.04em;
    }
    /* Animated gold line */
    .hero-line-h {
      position: absolute; left: 0; right: 0;
      height: 1px;
      background: linear-gradient(90deg, transparent 0%, rgba(200,168,75,.35) 30%, rgba(200,168,75,.35) 70%, transparent 100%);
    }
    .hero-line-h.top { top: 0; }
    .hero-line-h.bot { bottom: 0; }

    .hero-content {
      position: relative; z-index: 2;
      max-width: 1320px; margin: 0 auto;
      padding: 7rem 2rem 12rem;
      width: 100%;
    }
    .hero-eyebrow {
      font-size: .62rem; font-weight: 600;
      letter-spacing: .35em; text-transform: uppercase;
      color: var(--gold); margin-bottom: 1.4rem;
      display: flex; align-items: center; gap: .8rem;
    }
    .hero-eyebrow::before {
      content: ''; display: block;
      width: 30px; height: 1px; background: var(--gold);
    }
    .hero-h1 {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(3.8rem, 8.5vw, 9rem);
      font-weight: 600; line-height: .92;
      letter-spacing: -.025em;
      margin-bottom: 2rem;
    }
    .hero-h1 .italic { font-style: italic; color: var(--gold); }
    .hero-divider {
      width: 56px; height: 1.5px;
      background: linear-gradient(90deg, var(--gold), rgba(200,168,75,.2));
      margin-bottom: 1.8rem;
    }
    .hero-sub {
      font-size: .88rem; color: var(--muted-light);
      line-height: 1.85; max-width: 430px;
      margin-bottom: 2.8rem; font-weight: 300;
    }
    .hero-btns { display: flex; gap: .9rem; flex-wrap: wrap; align-items: center; }

    /* Buttons */
    .btn-gold {
      display: inline-flex; align-items: center; gap: .6rem;
      background: var(--gold); color: var(--ink);
      font-size: .68rem; font-weight: 600;
      letter-spacing: .15em; text-transform: uppercase;
      padding: 1rem 2rem; text-decoration: none;
      transition: background .3s, transform .25s, box-shadow .3s;
      position: relative; overflow: hidden;
    }
    .btn-gold::after {
      content: ''; position: absolute;
      top: 0; left: -100%; width: 60%; height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255,255,255,.18), transparent);
      transition: left .5s;
    }
    .btn-gold:hover::after { left: 130%; }
    .btn-gold:hover {
      background: var(--gold-bright);
      transform: translateY(-2px);
      box-shadow: 0 12px 32px rgba(200,168,75,.3);
    }
    .btn-outline {
      display: inline-flex; align-items: center; gap: .6rem;
      border: 1px solid rgba(200,168,75,.35); color: var(--gold);
      font-size: .68rem; font-weight: 500;
      letter-spacing: .15em; text-transform: uppercase;
      padding: 1rem 1.8rem; text-decoration: none;
      transition: border-color .3s, background .3s, transform .25s;
    }
    .btn-outline:hover {
      border-color: var(--gold);
      background: var(--gold-dim);
      transform: translateY(-2px);
    }

    /* Hero stats bar */
    .hero-stats {
      position: absolute; bottom: 0; left: 0; right: 0;
      background: rgba(6,6,5,.65);
      backdrop-filter: blur(12px); -webkit-backdrop-filter: blur(12px);
      border-top: 1px solid rgba(200,168,75,.1);
    }
    .stats-inner {
      max-width: 1320px; margin: 0 auto;
      display: grid; grid-template-columns: repeat(4, 1fr);
      padding: 1.4rem 2rem;
    }
    .stat-item {
      text-align: center; padding: .4rem;
      border-right: 1px solid rgba(255,255,255,.05);
    }
    .stat-item:last-child { border-right: none; }
    .stat-num {
      font-family: 'Cormorant Garamond', serif;
      font-size: 2.2rem; font-weight: 600;
      color: var(--gold); line-height: 1;
      margin-bottom: .3rem;
    }
    .stat-lbl {
      font-size: .58rem; letter-spacing: .2em;
      text-transform: uppercase; color: var(--muted);
    }

    /* ── MARQUEE ─────────────────────────────────────── */
    .marquee-wrap {
      background: var(--gold); overflow: hidden;
      padding: .85rem 0;
    }
    .marquee-track {
      display: flex; gap: 0;
      width: max-content;
      animation: mq 30s linear infinite;
    }
    .mq-item {
      display: flex; align-items: center; gap: 2rem;
      padding: 0 2rem;
      font-size: .62rem; font-weight: 600;
      letter-spacing: .22em; text-transform: uppercase;
      color: var(--ink); white-space: nowrap;
    }
    .mq-dot { width: 3px; height: 3px; background: var(--ink); border-radius: 50%; opacity: .45; }
    @keyframes mq {
      from { transform: translateX(0); }
      to   { transform: translateX(-50%); }
    }

    /* ── SECTION ANATOMY ────────────────────────────── */
    .section-eyebrow {
      font-size: .6rem; font-weight: 600;
      letter-spacing: .32em; text-transform: uppercase;
      color: var(--gold);
      display: flex; align-items: center; gap: .75rem;
    }
    .section-eyebrow::before {
      content: ''; width: 24px; height: 1px; background: var(--gold);
    }
    .section-title {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(2.4rem, 5vw, 4.4rem);
      font-weight: 600; line-height: 1.05;
      letter-spacing: -.018em;
    }
    .section-title em { font-style: italic; color: var(--gold); }
    .gold-rule {
      width: 44px; height: 1.5px;
      background: linear-gradient(90deg, var(--gold), transparent);
    }

    /* ── SERVICE CARDS ──────────────────────────────── */
    #services { background: var(--surface-1); }

    .card {
      background: var(--surface-2);
      border: 1px solid rgba(255,255,255,.04);
      position: relative; overflow: hidden;
      transition: transform .35s ease, border-color .35s ease, box-shadow .35s ease;
      display: flex; flex-direction: column;
    }
    .card::before {
      content: '';
      position: absolute; top: 0; left: 0; right: 0;
      height: 2px;
      background: linear-gradient(90deg, var(--gold) 0%, rgba(200,168,75,.2) 60%, transparent 100%);
      opacity: 0; transition: opacity .35s;
    }
    .card:hover { transform: translateY(-5px); border-color: rgba(200,168,75,.18); box-shadow: 0 24px 64px rgba(0,0,0,.5); }
    .card:hover::before { opacity: 1; }
    .card.featured {
      background: linear-gradient(145deg, #1C1608 0%, #120E05 100%);
      border-color: rgba(200,168,75,.22);
    }
    .card.featured::before { opacity: 1; }
    .card.crown {
      background: linear-gradient(145deg, #201700 0%, #0e0b00 100%);
      border-color: rgba(200,168,75,.35);
    }
    .card.crown::before { opacity: 1; height: 3px; }

    .tier-pill {
      display: inline-block;
      font-size: .58rem; font-weight: 600;
      letter-spacing: .18em; text-transform: uppercase;
      padding: .28rem .7rem;
    }
    .tier-base   { background: rgba(255,255,255,.05); color: var(--muted-light); }
    .tier-plus   { background: rgba(200,168,75,.1);  color: var(--gold); }
    .tier-elite  { background: rgba(200,168,75,.17); color: var(--gold-bright); }
    .tier-sig    { background: rgba(200,168,75,.25); color: var(--gold-pale); border: 1px solid rgba(200,168,75,.3); }
    .tier-crown  { background: var(--gold); color: var(--ink); }

    .card-name {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.65rem; font-weight: 600; line-height: 1.15;
    }
    .card-from { font-size: .58rem; letter-spacing: .12em; text-transform: uppercase; color: var(--muted); }
    .card-price {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.8rem; font-weight: 600; color: var(--gold);
    }

    .inc-label {
      font-size: .62rem; font-weight: 600;
      letter-spacing: .1em; color: var(--gold); text-transform: uppercase;
      margin-bottom: .6rem;
    }
    .feature-row {
      display: flex; align-items: flex-start; gap: .55rem;
      font-size: .76rem; color: rgba(246,244,238,.6); line-height: 1.55;
      margin-bottom: .48rem;
    }
    .feature-row .dash { color: var(--gold); flex-shrink: 0; margin-top: 1px; font-size: .8rem; }

    /* Price grid inside card */
    .price-grid {
      display: grid; grid-template-columns: repeat(3, 1fr);
      gap: 1px; background: rgba(255,255,255,.05);
      margin-top: auto;
    }
    .pg-cell { background: rgba(0,0,0,.35); padding: .8rem .5rem; text-align: center; }
    .pg-size  { font-size: .54rem; letter-spacing: .14em; text-transform: uppercase; color: var(--muted); margin-bottom: .22rem; }
    .pg-val   { font-family: 'Cormorant Garamond', serif; font-size: 1.3rem; font-weight: 600; color: var(--gold); }

    /* Notes bar */
    .notes-bar {
      background: var(--surface-3);
      border: 1px solid rgba(255,255,255,.04);
      border-top: 2px solid rgba(200,168,75,.15);
    }
    .note-item {
      font-size: .72rem; color: var(--muted-light); line-height: 1.6;
      padding-left: 1.1rem; position: relative;
    }
    .note-item::before {
      content: '·'; position: absolute; left: 0;
      color: var(--gold); font-size: 1rem;
    }

    /* ── FEATURES / WHY US ───────────────────────────── */
    #why { background: var(--ink); }

    .why-card {
      padding: 2.4rem 2rem;
      border: 1px solid rgba(255,255,255,.04);
      background: var(--surface-1);
      transition: border-color .3s, background .3s, transform .3s;
    }
    .why-card:hover {
      border-color: rgba(200,168,75,.15);
      background: rgba(200,168,75,.025);
      transform: translateY(-3px);
    }
    .why-icon {
      width: 46px; height: 46px;
      border: 1px solid rgba(200,168,75,.28);
      display: flex; align-items: center; justify-content: center;
      color: var(--gold); margin-bottom: 1.4rem;
    }
    .why-title {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.15rem; font-weight: 600; margin-bottom: .6rem;
    }
    .why-desc { font-size: .76rem; color: var(--muted); line-height: 1.7; }

    /* ── CERAMIC BAR ───────────────────────────────── */
    #ceramic-bar {
      background: var(--surface-2);
      border-top: 1px solid rgba(200,168,75,.1);
      border-bottom: 1px solid rgba(200,168,75,.1);
    }

    /* ── CTA ───────────────────────────────────────── */
    #cta {
      position: relative; overflow: hidden;
      background: var(--surface-1);
    }
    .cta-radial {
      position: absolute; inset: 0;
      background: radial-gradient(ellipse 80% 80% at 50% 50%, rgba(200,168,75,.07) 0%, transparent 68%);
      pointer-events: none;
    }
    .cta-rings {
      position: absolute; inset: 0;
      background-image:
        radial-gradient(ellipse 70% 55% at 50% 50%, transparent 60%, rgba(200,168,75,.03) 62%, transparent 64%),
        radial-gradient(ellipse 50% 40% at 50% 50%, transparent 70%, rgba(200,168,75,.02) 72%, transparent 74%);
      pointer-events: none;
    }
    .phone-big {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(2.8rem, 7vw, 5.5rem);
      font-weight: 600; color: var(--gold);
      letter-spacing: .03em; line-height: 1;
      text-decoration: none;
      display: inline-block;
      transition: color .3s, letter-spacing .3s;
    }
    .phone-big:hover { color: var(--gold-bright); letter-spacing: .06em; }

    /* ── FOOTER ────────────────────────────────────── */
    footer {
      background: var(--ink);
      border-top: 1px solid rgba(255,255,255,.04);
    }
    .foot-logo {
      font-family: 'Cormorant Garamond', serif;
      font-size: 2.1rem; font-weight: 600; color: var(--gold);
    }
    .foot-logo em { font-style: normal; color: var(--white); }
    .foot-col-label {
      font-size: .58rem; font-weight: 600;
      letter-spacing: .22em; text-transform: uppercase;
      color: var(--gold); margin-bottom: 1.3rem;
    }
    .foot-link {
      display: block; font-size: .78rem; color: var(--muted);
      text-decoration: none; margin-bottom: .65rem;
      transition: color .3s;
    }
    .foot-link:hover { color: var(--white); }

    /* ── REVEAL CLASSES (pre-animation state) ──────── */
    .js-fade     { opacity: 0; }
    .js-up       { opacity: 0; transform: translateY(36px); }
    .js-left     { opacity: 0; transform: translateX(-28px); }
    .js-right    { opacity: 0; transform: translateX(28px); }
    .js-scale    { opacity: 0; transform: scale(.95); }

    /* ── BURNING MAN BADGE ─────────────────────────── */
    .bm-badge {
      display: inline-flex; align-items: center; gap: .45rem;
      background: rgba(255,130,0,.09);
      border: 1px solid rgba(255,130,0,.22);
      color: #FF9B30;
      font-size: .62rem; font-weight: 500;
      letter-spacing: .1em; text-transform: uppercase;
      padding: .3rem .9rem; line-height: 1;
    }

    /* ── RESPONSIVE ────────────────────────────────── */
    @media (max-width: 1024px) {
      .stats-inner { grid-template-columns: repeat(2, 1fr); }
      .stat-item:nth-child(2) { border-right: none; }
    }
    @media (max-width: 768px) {
      #nav .nav-links { display: none; }
      #ham { display: flex; }
      .hero-h1 { font-size: clamp(3rem, 12vw, 5rem); }
      .stats-inner { grid-template-columns: repeat(2, 1fr); gap: .5rem; }
      .about-cols { flex-direction: column !important; }
      .foot-cols { flex-direction: column !important; gap: 2.5rem !important; }
    }
    @media (max-width: 480px) {
      .hero-btns { flex-direction: column; align-items: flex-start; }
    }
  </style>
</head>
<body>

<!-- ═══════════════════════ NAVIGATION ═══════════════════════ -->
<nav id="nav">
  <div class="nav-inner">
    <a href="#" class="logo">SF <em>Auto</em> Detail</a>
    <div class="nav-links">
      <a href="#services" class="nav-a">Services</a>
      <a href="#pricing" class="nav-a">Pricing</a>
      <a href="#why" class="nav-a">Why Us</a>
      <a href="tel:4157761844" class="nav-cta">☎ 415-776-1844</a>
    </div>
    <button id="ham" aria-label="Menu" onclick="toggleMenu()">
      <span></span><span></span><span></span>
    </button>
  </div>
</nav>

<!-- Mobile menu -->
<div id="mobile-menu">
  <a href="#services" class="mm-link" onclick="toggleMenu()">Services</a>
  <a href="#pricing" class="mm-link" onclick="toggleMenu()">Pricing</a>
  <a href="#why" class="mm-link" onclick="toggleMenu()">Why Us</a>
  <a href="tel:4157761844" class="mm-link" onclick="toggleMenu()" style="color:var(--gold)">415-776-1844</a>
</div>


<!-- ═══════════════════════ HERO ═══════════════════════════ -->
<section id="hero">
  <div class="hero-mesh"></div>
  <div class="hero-grid-lines"></div>
  <div class="hero-big-text">SF</div>
  <div class="hero-line-h top"></div>
  <div class="hero-line-h bot"></div>

  <div class="hero-content">
    <p class="hero-eyebrow" id="h-eye">San Francisco · Any Make · Any Model</p>

    <h1 class="hero-h1">
      <span class="h1-l1" style="display:block">Premium Auto</span>
      <span class="h1-l2 italic" style="display:block">Detailing</span>
      <span class="h1-l3" style="display:block">Excellence</span>
    </h1>

    <div class="hero-divider" id="h-div"></div>

    <p class="hero-sub" id="h-sub">
      Hand-crafted care for every vehicle — cars, SUVs, trucks, and motorcycles. From a quick hand wash to a full multi-stage detail, we deliver perfection.
    </p>

    <div class="hero-btns" id="h-btns">
      <a href="tel:4157761844" class="btn-gold">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M6.6 10.8c1.4 2.8 3.8 5.1 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.6.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1h3.5c.6 0 1 .4 1 1 0 1.3.2 2.5.6 3.6.1.3 0 .7-.2 1L6.6 10.8z"/></svg>
        Book Now · 415-776-1844
      </a>
      <a href="#services" class="btn-outline">
        Explore Services
        <svg width="12" height="12" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
      </a>
    </div>
  </div>

  <!-- Stats bar -->
  <div class="hero-stats">
    <div class="stats-inner">
      <div class="stat-item">
        <div class="stat-num">8</div>
        <div class="stat-lbl">Service Packages</div>
      </div>
      <div class="stat-item">
        <div class="stat-num" style="font-size:1.5rem;padding-top:.35rem">SF</div>
        <div class="stat-lbl">Local & Proud</div>
      </div>
      <div class="stat-item">
        <div class="stat-num" style="font-size:1.5rem;padding-top:.35rem">Any</div>
        <div class="stat-lbl">Make & Model</div>
      </div>
      <div class="stat-item">
        <div class="stat-num" style="font-size:1.1rem;padding-top:.6rem;letter-spacing:.05em">★★★★★</div>
        <div class="stat-lbl">Premium Quality</div>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════════════════ MARQUEE ════════════════════════ -->
<div class="marquee-wrap">
  <div class="marquee-track">
    <div class="mq-item">Exterior Hand Wash<span class="mq-dot"></span></div>
    <div class="mq-item">Leather Conditioning<span class="mq-dot"></span></div>
    <div class="mq-item">Orbital Wax<span class="mq-dot"></span></div>
    <div class="mq-item">Paint Correction<span class="mq-dot"></span></div>
    <div class="mq-item">Oxidation Removal<span class="mq-dot"></span></div>
    <div class="mq-item">Interior Detailing<span class="mq-dot"></span></div>
    <div class="mq-item">Ceramic Coating Available<span class="mq-dot"></span></div>
    <div class="mq-item">Motorcycles Welcome<span class="mq-dot"></span></div>
    <div class="mq-item">Post Burning Man Specialists<span class="mq-dot"></span></div>
    <div class="mq-item">Tire Conditioning<span class="mq-dot"></span></div>
    <!-- Duplicate for seamless loop -->
    <div class="mq-item">Exterior Hand Wash<span class="mq-dot"></span></div>
    <div class="mq-item">Leather Conditioning<span class="mq-dot"></span></div>
    <div class="mq-item">Orbital Wax<span class="mq-dot"></span></div>
    <div class="mq-item">Paint Correction<span class="mq-dot"></span></div>
    <div class="mq-item">Oxidation Removal<span class="mq-dot"></span></div>
    <div class="mq-item">Interior Detailing<span class="mq-dot"></span></div>
    <div class="mq-item">Ceramic Coating Available<span class="mq-dot"></span></div>
    <div class="mq-item">Motorcycles Welcome<span class="mq-dot"></span></div>
    <div class="mq-item">Post Burning Man Specialists<span class="mq-dot"></span></div>
    <div class="mq-item">Tire Conditioning<span class="mq-dot"></span></div>
  </div>
</div>


<!-- ══════════════════════ SERVICES ═══════════════════════ -->
<section id="services" style="padding: 7rem 0 5rem">
  <div style="max-width:1320px;margin:0 auto;padding:0 2rem">

    <!-- Header -->
    <div style="margin-bottom:4.5rem">
      <p class="section-eyebrow js-up" style="margin-bottom:1rem">Our Services</p>
      <h2 class="section-title js-up" style="max-width:580px;margin-bottom:1.4rem">
        Every Vehicle<br>Deserves <em>Perfection</em>
      </h2>
      <div class="gold-rule js-up" style="margin-bottom:1.4rem"></div>
      <p class="js-up" style="font-size:.85rem;color:var(--muted-light);max-width:480px;line-height:1.85">
        Hand-crafted technique, premium products, and uncompromising attention to detail — from a quick wash to a show-ready multi-stage polish.
      </p>
    </div>

    <!-- ── CARDS GRID ── -->
    <div id="pricing" style="display:grid;grid-template-columns:repeat(auto-fill,minmax(330px,1fr));gap:1.5rem;margin-bottom:2rem">

      <!-- 1 · SF Car Wash -->
      <div class="card svc-card" style="padding:2.4rem">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:1.4rem">
          <div>
            <span class="tier-pill tier-base" style="margin-bottom:.65rem;display:inline-block">Essential</span>
            <div class="card-name">SF Car Wash</div>
          </div>
          <div style="text-align:right">
            <div class="card-from">From</div>
            <div class="card-price">$75</div>
          </div>
        </div>
        <div style="flex:1">
          <div class="inc-label">Includes</div>
          <div class="feature-row"><span class="dash">—</span>Exterior hand wash</div>
          <div class="feature-row"><span class="dash">—</span>Spray wax rinse</div>
          <div class="feature-row"><span class="dash">—</span>Wheel-well cleaning</div>
          <div class="feature-row"><span class="dash">—</span>Interior vacuuming (including trunk)</div>
          <div class="feature-row"><span class="dash">—</span>Glass cleaning</div>
          <div class="feature-row"><span class="dash">—</span>Dry with microfiber towel</div>
        </div>
        <div class="price-grid" style="margin-top:1.8rem">
          <div class="pg-cell"><div class="pg-size">Small</div><div class="pg-val">$75</div></div>
          <div class="pg-cell"><div class="pg-size">Medium</div><div class="pg-val">$85</div></div>
          <div class="pg-cell"><div class="pg-size">Large</div><div class="pg-val">$95</div></div>
        </div>
      </div>

      <!-- 2 · SF Deluxe Car Wash -->
      <div class="card svc-card" style="padding:2.4rem">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:1.4rem">
          <div>
            <span class="tier-pill tier-plus" style="margin-bottom:.65rem;display:inline-block">Premium</span>
            <div class="card-name">SF Deluxe Wash</div>
          </div>
          <div style="text-align:right">
            <div class="card-from">From</div>
            <div class="card-price">$180</div>
          </div>
        </div>
        <div style="flex:1">
          <div class="inc-label" style="color:var(--muted-light)">SF Car Wash +</div>
          <div class="feature-row"><span class="dash">—</span>Spray paint body gloss</div>
          <div class="feature-row"><span class="dash">—</span>Carpet / floor mat spot cleaning</div>
          <div class="feature-row"><span class="dash">—</span>Leather conditioning</div>
          <div class="feature-row"><span class="dash">—</span>Tire conditioning</div>
        </div>
        <div class="price-grid" style="margin-top:1.8rem">
          <div class="pg-cell"><div class="pg-size">Small</div><div class="pg-val">$180</div></div>
          <div class="pg-cell"><div class="pg-size">Medium</div><div class="pg-val">$220</div></div>
          <div class="pg-cell"><div class="pg-size">Large</div><div class="pg-val">$260</div></div>
        </div>
      </div>

      <!-- 3 · SF Ultimate Car Wash -->
      <div class="card svc-card" style="padding:2.4rem">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:1.4rem">
          <div>
            <span class="tier-pill tier-plus" style="margin-bottom:.65rem;display:inline-block">Premium+</span>
            <div class="card-name">SF Ultimate Wash</div>
          </div>
          <div style="text-align:right">
            <div class="card-from">From</div>
            <div class="card-price">$300</div>
          </div>
        </div>
        <div style="flex:1">
          <div class="inc-label" style="color:var(--muted-light)">SF Deluxe +</div>
          <div class="feature-row"><span class="dash">—</span>Exterior hand waxing</div>
          <div class="feature-row"><span class="dash">—</span>Interior minor spot touch-up</div>
          <div class="feature-row"><span class="dash">—</span>Complete glass cleaning</div>
        </div>
        <div class="price-grid" style="margin-top:1.8rem">
          <div class="pg-cell"><div class="pg-size">Small</div><div class="pg-val">$300</div></div>
          <div class="pg-cell"><div class="pg-size">Medium</div><div class="pg-val">$340</div></div>
          <div class="pg-cell"><div class="pg-size">Large</div><div class="pg-val">$360</div></div>
        </div>
      </div>

      <!-- 4 · SF Hand Wax -->
      <div class="card svc-card" style="padding:2.4rem">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:1.4rem">
          <div>
            <span class="tier-pill tier-elite" style="margin-bottom:.65rem;display:inline-block">Elite</span>
            <div class="card-name">SF Hand Wax</div>
          </div>
          <div style="text-align:right">
            <div class="card-from">From</div>
            <div class="card-price">$450</div>
          </div>
        </div>
        <div style="flex:1">
          <div class="inc-label" style="color:var(--muted-light)">SF Deluxe +</div>
          <div class="feature-row"><span class="dash">—</span>Oxidation removal</div>
          <div class="feature-row"><span class="dash">—</span>1-stage orbital wax</div>
        </div>
        <div class="price-grid" style="margin-top:1.8rem">
          <div class="pg-cell"><div class="pg-size">Small</div><div class="pg-val">$450</div></div>
          <div class="pg-cell"><div class="pg-size">Medium</div><div class="pg-val">$480</div></div>
          <div class="pg-cell"><div class="pg-size">Large</div><div class="pg-val">$550</div></div>
        </div>
      </div>

      <!-- 5 · SF Mini Detail -->
      <div class="card svc-card" style="padding:2.4rem">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:1.4rem">
          <div>
            <span class="tier-pill tier-elite" style="margin-bottom:.65rem;display:inline-block">Elite</span>
            <div class="card-name">SF Mini Detail</div>
          </div>
          <div style="text-align:right">
            <div class="card-from">From</div>
            <div class="card-price">$450</div>
          </div>
        </div>
        <div style="flex:1">
          <div class="inc-label">Includes</div>
          <div class="feature-row"><span class="dash">—</span>Interior reconditioning</div>
          <div class="feature-row"><span class="dash">—</span>Carpet & fabric seat shampooing + complete dry</div>
          <div class="feature-row"><span class="dash">—</span>Panel cream protection</div>
          <div class="feature-row"><span class="dash">—</span>Leather/vinyl complete clean & protection</div>
          <div class="feature-row"><span class="dash">—</span>SF Car Wash included</div>
          <div style="font-size:.68rem;color:var(--muted);font-style:italic;margin-top:.8rem;line-height:1.7">
            Add-ons: seatbelt cleaning, sand / dog hair removal, window repair, ceiling cleaning
          </div>
        </div>
        <div class="price-grid" style="margin-top:1.8rem">
          <div class="pg-cell"><div class="pg-size">Small</div><div class="pg-val">$450</div></div>
          <div class="pg-cell"><div class="pg-size">Medium</div><div class="pg-val">$480</div></div>
          <div class="pg-cell"><div class="pg-size">Large</div><div class="pg-val">$550</div></div>
        </div>
      </div>

      <!-- 6 · SF Detail (Signature) -->
      <div class="card featured svc-card" style="padding:2.4rem">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:1.4rem">
          <div>
            <span class="tier-pill tier-sig" style="margin-bottom:.65rem;display:inline-block">★ Signature</span>
            <div class="card-name">SF Detail</div>
          </div>
          <div style="text-align:right">
            <div class="card-from">From</div>
            <div class="card-price">$650</div>
          </div>
        </div>
        <div style="flex:1">
          <div class="inc-label">Includes</div>
          <div class="feature-row"><span class="dash">—</span>All SF Car Wash services</div>
          <div class="feature-row"><span class="dash">—</span>All SF Mini Detail services</div>
          <div class="feature-row"><span class="dash">—</span>Hand wax</div>
          <div class="feature-row"><span class="dash">—</span>Full rubber protection</div>
        </div>
        <div class="price-grid" style="margin-top:1.8rem">
          <div class="pg-cell"><div class="pg-size">Small</div><div class="pg-val">$650</div></div>
          <div class="pg-cell"><div class="pg-size">Medium</div><div class="pg-val">$680</div></div>
          <div class="pg-cell"><div class="pg-size">Large</div><div class="pg-val">$690</div></div>
        </div>
      </div>

      <!-- 7 · SF Full Detail -->
      <div class="card featured svc-card" style="padding:2.4rem">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:1.4rem">
          <div>
            <span class="tier-pill tier-sig" style="margin-bottom:.65rem;display:inline-block">★★ Full</span>
            <div class="card-name">SF Full Detail</div>
          </div>
          <div style="text-align:right">
            <div class="card-from">From</div>
            <div class="card-price">$780</div>
          </div>
        </div>
        <div style="flex:1">
          <div class="inc-label">Includes</div>
          <div class="feature-row"><span class="dash">—</span>Oxidation removal</div>
          <div class="feature-row"><span class="dash">—</span>One-stage orbital wax</div>
          <div class="feature-row"><span class="dash">—</span>Full rubber protection</div>
          <div class="feature-row"><span class="dash">—</span>Scuff removal</div>
          <div class="feature-row"><span class="dash">—</span>SF Mini Detail included</div>
          <div style="margin-top:1rem">
            <span class="bm-badge">🔥 Great post-Burning Man cleanup!</span>
          </div>
        </div>
        <div class="price-grid" style="margin-top:1.8rem">
          <div class="pg-cell"><div class="pg-size">Small</div><div class="pg-val">$780</div></div>
          <div class="pg-cell"><div class="pg-size">Medium</div><div class="pg-val">$890</div></div>
          <div class="pg-cell"><div class="pg-size">Large</div><div class="pg-val">$990</div></div>
        </div>
      </div>

      <!-- 8 · SF Super Detail (Crown Jewel — spans 2 cols on large screens) -->
      <div class="card crown svc-card" style="padding:2.4rem">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:1.4rem;flex-wrap:wrap;gap:.8rem">
          <div>
            <span class="tier-pill tier-crown" style="margin-bottom:.65rem;display:inline-block">★★★ Crown Jewel</span>
            <div class="card-name" style="font-size:2rem">SF Super Detail</div>
          </div>
          <div style="text-align:right">
            <div class="card-from">Starting at</div>
            <div class="card-price" style="font-size:2.4rem">$1,090</div>
          </div>
        </div>
        <div style="flex:1">
          <div class="inc-label">The Ultimate Treatment</div>
          <div class="feature-row"><span class="dash">—</span>Oxidation removal</div>
          <div class="feature-row"><span class="dash">—</span>Three-stage polish</div>
          <div class="feature-row"><span class="dash">—</span>Orbital wax</div>
          <div class="feature-row"><span class="dash">—</span>Free swirl mark removal</div>
          <div class="feature-row"><span class="dash">—</span>Special leather protection or fiber cloth seat treatment</div>
          <div style="background:rgba(200,168,75,.07);border:1px solid rgba(200,168,75,.18);padding:.9rem 1rem;margin-top:1.2rem;font-size:.73rem;color:rgba(246,244,238,.7);line-height:1.7">
            ⚠ Pricing varies by vehicle specifics — please call to confirm your quote before booking.
          </div>
        </div>
        <div style="margin-top:1.8rem">
          <a href="tel:4157761844" class="btn-gold" style="width:100%;justify-content:center">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M6.6 10.8c1.4 2.8 3.8 5.1 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.6.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1h3.5c.6 0 1 .4 1 1 0 1.3.2 2.5.6 3.6.1.3 0 .7-.2 1L6.6 10.8z"/></svg>
            Call for Your Custom Quote · 415-776-1844
          </a>
        </div>
      </div>

    </div><!-- /grid -->

    <!-- Notes bar -->
    <div class="notes-bar js-up" style="padding:2rem 2.4rem;margin-top:.5rem">
      <div style="font-size:.6rem;font-weight:600;letter-spacing:.22em;text-transform:uppercase;color:var(--gold);margin-bottom:1.1rem">Important Notes</div>
      <div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:.7rem .5rem">
        <div class="note-item">Prices vary by vehicle size: Small / Medium / Large</div>
        <div class="note-item">2-Door Coupes are priced as Medium</div>
        <div class="note-item">Includes all makes, models &amp; motorcycles</div>
        <div class="note-item">Ceramic Coating available — call to request</div>
        <div class="note-item">Motor cleaning is <em>not</em> available</div>
        <div class="note-item">Call 415-776-1844 to schedule your appointment</div>
      </div>
    </div>

  </div>
</section>


<!-- ══════════════════════ WHY CHOOSE US ═══════════════════ -->
<section id="why" style="padding:7rem 0">
  <div style="max-width:1320px;margin:0 auto;padding:0 2rem">

    <div class="about-cols" style="display:flex;gap:5rem;align-items:center">

      <!-- Left copy -->
      <div style="flex:0 0 auto;width:100%;max-width:460px">
        <p class="section-eyebrow js-up" style="margin-bottom:1rem">Why Choose Us</p>
        <h2 class="section-title js-up" style="margin-bottom:1.2rem">
          The City's Most<br><em>Trusted</em> Detail
        </h2>
        <div class="gold-rule js-up" style="margin-bottom:1.6rem"></div>
        <p class="js-up" style="font-size:.86rem;color:var(--muted-light);line-height:1.95;margin-bottom:1.4rem">
          San Francisco Auto Detail combines meticulous hand-crafted technique with professional-grade products and a genuine love for vehicles. We believe every car deserves to look its absolute best.
        </p>
        <p class="js-up" style="font-size:.86rem;color:var(--muted-light);line-height:1.95;margin-bottom:2.5rem">
          From your daily commuter to your prized weekend ride, we service any make and model — including motorcycles. Post Burning Man? We've got you covered.
        </p>
        <div class="js-up" style="display:flex;gap:1rem;flex-wrap:wrap">
          <a href="tel:4157761844" class="btn-gold">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M6.6 10.8c1.4 2.8 3.8 5.1 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.6.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1h3.5c.6 0 1 .4 1 1 0 1.3.2 2.5.6 3.6.1.3 0 .7-.2 1L6.6 10.8z"/></svg>
            Call 415-776-1844
          </a>
          <a href="#services" class="btn-outline">See Packages</a>
        </div>
      </div>

      <!-- Right grid -->
      <div style="flex:1;display:grid;grid-template-columns:1fr 1fr;gap:1rem">
        <div class="why-card why-c">
          <div class="why-icon">
            <svg width="20" height="20" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path d="M7 11.5V14m0-2.5V9m0 2.5H9.5m-2.5 0H5m14 0c0 4.418-3.134 8-7 8s-7-3.582-7-8 3.134-8 7-8 7 3.582 7 8z"/></svg>
          </div>
          <div class="why-title">Hand-Crafted Only</div>
          <div class="why-desc">Every wash is done entirely by hand using premium microfiber tools — no automated machines, ever.</div>
        </div>
        <div class="why-card why-c">
          <div class="why-icon">
            <svg width="20" height="20" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
          </div>
          <div class="why-title">Paint-Safe Techniques</div>
          <div class="why-desc">We protect your clear coat and finish with techniques designed to enhance, not harm, your paint.</div>
        </div>
        <div class="why-card why-c">
          <div class="why-icon">
            <svg width="20" height="20" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
          </div>
          <div class="why-title">All Vehicles</div>
          <div class="why-desc">Cars, SUVs, trucks, and motorcycles — any make, any model, any size.</div>
        </div>
        <div class="why-card why-c">
          <div class="why-icon">
            <svg width="20" height="20" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          </div>
          <div class="why-title">SF Local</div>
          <div class="why-desc">Proudly rooted in San Francisco — local business, local pride, and a local standard of excellence.</div>
        </div>
        <div class="why-card why-c" style="grid-column:span 2">
          <div class="why-icon">
            <svg width="20" height="20" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
          </div>
          <div class="why-title">Ceramic Coating on Request</div>
          <div class="why-desc">Want the ultimate long-term paint protection? We offer ceramic coating as a premium add-on. Call us to discuss options and pricing for your specific vehicle.</div>
        </div>
      </div>

    </div>
  </div>
</section>


<!-- ══════════════════ CERAMIC ADD-ON BAR ════════════════════ -->
<div id="ceramic-bar" style="padding:2.8rem 0">
  <div style="max-width:1320px;margin:0 auto;padding:0 2rem;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:1.5rem">
    <div>
      <div class="section-eyebrow js-up" style="margin-bottom:.5rem">Premium Add-On</div>
      <div class="f-display js-up" style="font-size:1.9rem;font-weight:600">Ceramic Coating</div>
      <div class="js-up" style="font-size:.78rem;color:var(--muted-light);margin-top:.35rem">Long-lasting paint protection · Available by appointment · Call to request pricing</div>
    </div>
    <a href="tel:4157761844" class="btn-gold js-up">
      Request Ceramic Coating →
    </a>
  </div>
</div>


<!-- ════════════════════════ CTA ══════════════════════════ -->
<section id="cta" style="padding:10rem 0">
  <div class="cta-radial"></div>
  <div class="cta-rings"></div>
  <div style="position:relative;z-index:2;max-width:800px;margin:0 auto;padding:0 2rem;text-align:center">
    <p class="section-eyebrow js-up" style="justify-content:center;margin-bottom:1.4rem">Ready to Book?</p>
    <h2 class="section-title js-up" style="margin-bottom:1.3rem">
      Call Now to Make<br><em>Your Appointment</em>
    </h2>
    <div class="gold-rule js-up" style="margin:0 auto 1.8rem;background:linear-gradient(90deg,transparent,var(--gold),transparent);width:60px"></div>
    <p class="js-up" style="font-size:.86rem;color:var(--muted-light);line-height:1.9;max-width:420px;margin:0 auto 2.8rem">
      San Francisco's premier auto detailing service is just one call away. Any make, any model, any size. We'll have your vehicle looking flawless.
    </p>
    <div class="js-up" style="margin-bottom:2.2rem">
      <a href="tel:4157761844" class="phone-big">415-776-1844</a>
    </div>
    <div class="js-up">
      <a href="tel:4157761844" class="btn-gold" style="font-size:.75rem;padding:1.1rem 3rem;display:inline-flex">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M6.6 10.8c1.4 2.8 3.8 5.1 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.6.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1h3.5c.6 0 1 .4 1 1 0 1.3.2 2.5.6 3.6.1.3 0 .7-.2 1L6.6 10.8z"/></svg>
        Book Your Appointment Today
      </a>
    </div>
  </div>
</section>


<!-- ═══════════════════════ FOOTER ════════════════════════ -->
<footer style="padding:4.5rem 0 2rem">
  <div style="max-width:1320px;margin:0 auto;padding:0 2rem">
    <div class="foot-cols" style="display:flex;gap:4rem;margin-bottom:4rem;flex-wrap:wrap">

      <!-- Brand col -->
      <div style="flex:2;min-width:220px">
        <div class="foot-logo" style="margin-bottom:1rem">SF <em>Auto</em> Detail</div>
        <p style="font-size:.78rem;color:var(--muted);line-height:1.9;max-width:280px;margin-bottom:1.4rem">
          Premium hand-crafted auto detailing for every make and model — including motorcycles — in the heart of San Francisco.
        </p>
        <div style="font-size:.62rem;color:rgba(200,168,75,.45);letter-spacing:.12em">Any Make · Any Model · Any Size</div>
      </div>

      <!-- Services col -->
      <div style="flex:1;min-width:140px">
        <div class="foot-col-label">Packages</div>
        <a href="#pricing" class="foot-link">SF Car Wash</a>
        <a href="#pricing" class="foot-link">SF Deluxe Wash</a>
        <a href="#pricing" class="foot-link">SF Ultimate Wash</a>
        <a href="#pricing" class="foot-link">SF Mini Detail</a>
        <a href="#pricing" class="foot-link">SF Full Detail</a>
        <a href="#pricing" class="foot-link">SF Super Detail</a>
      </div>

      <!-- Contact col -->
      <div style="flex:1;min-width:160px">
        <div class="foot-col-label">Contact</div>
        <div style="margin-bottom:1.4rem">
          <div style="font-size:.58rem;letter-spacing:.15em;text-transform:uppercase;color:var(--muted);margin-bottom:.3rem">Phone</div>
          <a href="tel:4157761844" style="font-family:'Cormorant Garamond',serif;font-size:1.6rem;font-weight:600;color:var(--gold);text-decoration:none;transition:color .3s" onmouseover="this.style.color='var(--gold-bright)'" onmouseout="this.style.color='var(--gold)'">415-776-1844</a>
        </div>
        <div style="margin-bottom:1rem">
          <div style="font-size:.58rem;letter-spacing:.15em;text-transform:uppercase;color:var(--muted);margin-bottom:.3rem">Location</div>
          <div style="font-size:.8rem;color:var(--white)">San Francisco, CA</div>
        </div>
        <div>
          <div style="font-size:.58rem;letter-spacing:.15em;text-transform:uppercase;color:var(--muted);margin-bottom:.3rem">Booking</div>
          <div style="font-size:.8rem;color:var(--white)">By appointment · Call to schedule</div>
        </div>
      </div>

    </div>

    <!-- Bottom bar -->
    <div style="border-top:1px solid rgba(255,255,255,.04);padding-top:1.8rem;display:flex;justify-content:space-between;flex-wrap:wrap;gap:1rem">
      <div style="font-size:.65rem;color:rgba(255,255,255,.18)">© 2025 SF Auto Detail · San Francisco, California · All rights reserved</div>
      <div style="font-size:.65rem;color:rgba(255,255,255,.18)">Motor cleaning not available · Ceramic coating by appointment only</div>
    </div>
  </div>
</footer>


<!-- ═══════════════════════ SCRIPTS ════════════════════════ -->
<script>
  /* ── Register plugin ─────────────────────────────── */
  gsap.registerPlugin(ScrollTrigger);

  /* ── NAV scroll ──────────────────────────────────── */
  const nav = document.getElementById('nav');
  window.addEventListener('scroll', () => {
    nav.classList.toggle('solid', window.scrollY > 60);
  }, { passive: true });

  /* ── Mobile menu ─────────────────────────────────── */
  function toggleMenu() {
    const mm  = document.getElementById('mobile-menu');
    const ham = document.getElementById('ham');
    mm.classList.toggle('open');
    ham.classList.toggle('open');
  }

  /* ── HERO entrance timeline ──────────────────────── */
  const htl = gsap.timeline({ delay: 0.15 });
  htl
    .from('#h-eye',  { opacity: 0, y: 16, duration: .7, ease: 'power3.out' })
    .from('.h1-l1',  { opacity: 0, y: 55, duration: .9, ease: 'power4.out' }, '-=.3')
    .from('.h1-l2',  { opacity: 0, y: 55, duration: .9, ease: 'power4.out' }, '-=.65')
    .from('.h1-l3',  { opacity: 0, y: 55, duration: .9, ease: 'power4.out' }, '-=.65')
    .from('#h-div',  { scaleX: 0, transformOrigin: 'left', duration: .8, ease: 'power3.out' }, '-=.5')
    .from('#h-sub',  { opacity: 0, y: 18, duration: .7, ease: 'power3.out' }, '-=.55')
    .from('#h-btns > *', { opacity: 0, y: 14, stagger: .14, duration: .65, ease: 'power3.out' }, '-=.45')
    .from('.stat-item', { opacity: 0, y: 18, stagger: .08, duration: .55, ease: 'power3.out' }, '-=.3')
    .from('.hero-big-text', { opacity: 0, scale: 1.08, duration: 2.2, ease: 'power3.out' }, 0);

  /* ── Parallax big text ───────────────────────────── */
  gsap.to('.hero-big-text', {
    yPercent: -18,
    ease: 'none',
    scrollTrigger: { trigger: '#hero', start: 'top top', end: 'bottom top', scrub: true }
  });

  /* ── Scroll-reveal helper ────────────────────────── */
  function reveal(selector, vars = {}) {
    gsap.utils.toArray(selector).forEach(el => {
      gsap.from(el, {
        ...{ opacity: 0, y: 38, duration: .85, ease: 'power3.out' },
        ...vars,
        scrollTrigger: {
          trigger: el,
          start: 'top 87%',
          toggleActions: 'play none none none'
        }
      });
    });
  }

  /* ── Service cards staggered reveal ─────────────── */
  gsap.from('.svc-card', {
    opacity: 0, y: 50, duration: .8, stagger: .09,
    ease: 'power3.out',
    scrollTrigger: { trigger: '#pricing', start: 'top 80%', toggleActions: 'play none none none' }
  });

  /* ── Why cards stagger ───────────────────────────── */
  gsap.from('.why-c', {
    opacity: 0, y: 32, duration: .7, stagger: .1,
    ease: 'power3.out',
    scrollTrigger: { trigger: '#why', start: 'top 78%', toggleActions: 'play none none none' }
  });

  /* ── Generic .js-up elements ─────────────────────── */
  reveal('.js-up');
  reveal('.js-fade', { y: 0 });
  reveal('.js-left',  { x: -28, y: 0 });
  reveal('.js-right', { x: 28, y: 0 });

  /* ── Gold rules scale-in ─────────────────────────── */
  gsap.utils.toArray('.gold-rule').forEach(el => {
    gsap.from(el, {
      scaleX: 0, transformOrigin: 'left',
      duration: 1, ease: 'power3.out',
      scrollTrigger: { trigger: el, start: 'top 88%', toggleActions: 'play none none none' }
    });
  });

  /* ── Phone number hover ──────────────────────────── */
  const ph = document.querySelector('.phone-big');
  if (ph) {
    ph.addEventListener('mouseenter', () =>
      gsap.to(ph, { scale: 1.04, duration: .3, ease: 'power2.out' }));
    ph.addEventListener('mouseleave', () =>
      gsap.to(ph, { scale: 1, duration: .3, ease: 'power2.out' }));
  }

  /* ── Smooth scroll for anchor links ─────────────── */
  document.querySelectorAll('a[href^="#"]').forEach(a => {
    a.addEventListener('click', e => {
      const target = document.querySelector(a.getAttribute('href'));
      if (!target) return;
      e.preventDefault();
      gsap.to(window, {
        duration: 1.2,
        scrollTo: { y: target, offsetY: 80 },
        ease: 'power4.inOut'
      });
    });
  });
</script>

<!-- GSAP ScrollTo plugin for smooth anchor scrolling -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollToPlugin.min.js"></script>
<script>
  // Re-register after ScrollTo loads
  gsap.registerPlugin(ScrollTrigger);
</script>

</body>
</html>
