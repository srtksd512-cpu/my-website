<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pawsome &mdash; A Pet Shop That Feels Like Play</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&family=Baloo+2:wght@500;600;700;800&family=Poppins:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --sun:#FFC93C;
    --coral:#FF6B6B;
    --mint:#3FD9C4;
    --grape:#7C5CFC;
    --sky:#4FB8FF;
    --cream:#FFF7EC;
    --ink:#241E3C;
    --ink-soft:#5B5470;
    --paper:#FFFFFF;
    --shadow-grape: rgba(124,92,252,.28);
    --radius-lg: 32px;
    --radius-md: 22px;
  }

  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--cream);
    color:var(--ink);
    font-family:'Poppins',sans-serif;
    overflow-x:hidden;
    -webkit-font-smoothing:antialiased;
  }
  h1,h2,h3,.display{font-family:'Baloo 2',cursive;}
  a{text-decoration:none;color:inherit;}
  ul{list-style:none;}
  img,svg{display:block;}

  @media (prefers-reduced-motion: reduce){
    *{animation-duration:0.001ms !important; animation-iteration-count:1 !important; transition-duration:0.001ms !important; scroll-behavior:auto !important;}
  }

  .wrap{max-width:1180px;margin:0 auto;padding:0 32px;}

  /* ---------- background blobs ---------- */
  .blob-field{position:fixed;inset:0;z-index:0;overflow:hidden;pointer-events:none;}
  .blob{position:absolute;border-radius:50%;filter:blur(2px);opacity:.35;animation:drift 22s ease-in-out infinite;}
  .blob.b1{width:420px;height:420px;background:radial-gradient(circle at 30% 30%, var(--sun), transparent 70%);top:-120px;left:-100px;animation-duration:26s;}
  .blob.b2{width:360px;height:360px;background:radial-gradient(circle at 30% 30%, var(--mint), transparent 70%);top:40%;right:-140px;animation-duration:32s;animation-delay:-6s;}
  .blob.b3{width:300px;height:300px;background:radial-gradient(circle at 30% 30%, var(--coral), transparent 70%);bottom:-80px;left:20%;animation-duration:24s;animation-delay:-12s;}
  @keyframes drift{
    0%,100%{transform:translate(0,0) scale(1);}
    33%{transform:translate(30px,-40px) scale(1.08);}
    66%{transform:translate(-25px,25px) scale(0.95);}
  }

  /* ---------- nav ---------- */
  header{position:sticky;top:0;z-index:50;backdrop-filter:blur(10px);background:rgba(255,247,236,.78);border-bottom:1px solid rgba(36,30,60,.06);}
  nav{display:flex;align-items:center;justify-content:space-between;padding:18px 0;}
  .logo{display:flex;align-items:center;gap:10px;font-family:'Baloo 2';font-weight:700;font-size:1.4rem;}
  .logo-mark{width:38px;height:38px;border-radius:12px;background:linear-gradient(135deg,var(--coral),var(--grape));display:flex;align-items:center;justify-content:center;box-shadow:0 6px 14px var(--shadow-grape);transform:rotate(-6deg);}
  .logo-mark svg{width:22px;height:22px;}
  .nav-links{display:flex;gap:34px;font-weight:500;color:var(--ink-soft);}
  .nav-links a{position:relative;padding:4px 0;transition:color .2s;}
  .nav-links a:hover{color:var(--ink);}
  .nav-links a::after{content:'';position:absolute;left:0;bottom:-2px;width:0;height:2px;background:var(--coral);transition:width .25s;}
  .nav-links a:hover::after{width:100%;}
  .nav-cta{background:var(--ink);color:var(--cream);padding:12px 22px;border-radius:100px;font-weight:600;font-size:.92rem;box-shadow:0 8px 18px rgba(36,30,60,.18);transition:transform .2s ease, box-shadow .2s ease;}
  .nav-cta:hover{transform:translateY(-2px);box-shadow:0 12px 22px rgba(36,30,60,.25);}
  .burger{display:none;}

  /* ---------- hero ---------- */
  .hero{position:relative;z-index:1;padding:76px 0 40px;}
  .hero-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:40px;align-items:center;}
  .eyebrow-chip{display:inline-flex;align-items:center;gap:8px;background:var(--paper);border:1px solid rgba(36,30,60,.08);padding:8px 16px 8px 8px;border-radius:100px;font-size:.85rem;font-weight:600;color:var(--ink-soft);box-shadow:0 6px 16px rgba(36,30,60,.06);margin-bottom:22px;}
  .eyebrow-chip .dot{width:26px;height:26px;border-radius:50%;background:linear-gradient(135deg,var(--sun),var(--coral));display:flex;align-items:center;justify-content:center;font-size:14px;}
  .hero h1{font-size:clamp(2.6rem,4.6vw,4rem);line-height:1.04;font-weight:700;letter-spacing:-0.01em;}
  .hero h1 .accent{color:var(--coral);}
  .hero p.lede{margin:22px 0 32px;font-size:1.12rem;color:var(--ink-soft);max-width:480px;line-height:1.6;}
  .hero-actions{display:flex;gap:16px;align-items:center;flex-wrap:wrap;}
  .btn-primary{background:linear-gradient(135deg,var(--coral),#FF8E6E);color:#fff;padding:16px 30px;border-radius:100px;font-weight:600;font-size:1rem;box-shadow:0 14px 28px rgba(255,107,107,.35);transition:transform .22s ease, box-shadow .22s ease;}
  .btn-primary:hover{transform:translateY(-3px) scale(1.02);box-shadow:0 18px 34px rgba(255,107,107,.45);}
  .btn-ghost{display:flex;align-items:center;gap:10px;font-weight:600;color:var(--ink);padding:16px 6px;}
  .play-ring{width:44px;height:44px;border-radius:50%;border:2px solid var(--ink);display:flex;align-items:center;justify-content:center;transition:background .2s, color .2s;}
  .btn-ghost:hover .play-ring{background:var(--ink);color:var(--cream);}

  .trust-row{display:flex;gap:28px;margin-top:44px;}
  .trust-row .stat b{font-family:'Baloo 2';font-size:1.5rem;display:block;}
  .trust-row .stat span{font-size:.82rem;color:var(--ink-soft);}

  /* hero 3D stage */
  .stage{position:relative;height:480px;perspective:1400px;}
  .stage-card{position:absolute;border-radius:var(--radius-lg);box-shadow:0 30px 60px -18px rgba(36,30,60,.35);transform-style:preserve-3d;transition:transform .15s ease-out;}
  .card-main{width:300px;height:360px;top:40px;left:100px;background:linear-gradient(160deg,var(--grape),#5A3FD6);z-index:3;display:flex;align-items:flex-end;padding:26px;color:#fff;animation:floaty 6s ease-in-out infinite;}
  .card-main .cap{position:relative;z-index:2;}
  .card-main .cap b{font-family:'Baloo 2';font-size:1.3rem;display:block;}
  .card-main .cap span{font-size:.85rem;opacity:.85;}
  .badge-float{position:absolute;top:20px;right:20px;background:rgba(255,255,255,.18);backdrop-filter:blur(6px);padding:8px 14px;border-radius:100px;font-size:.78rem;font-weight:600;color:#fff;}

  .card-side{width:200px;height:240px;background:var(--mint);z-index:2;animation:floaty 7s ease-in-out infinite;animation-delay:-2s;}
  .card-side.left{top:0;left:-30px;background:linear-gradient(160deg,var(--sun),#FFB020);}
  .card-side.right{bottom:-10px;right:-20px;background:linear-gradient(160deg,var(--sky),#2E9BFF);}

  @keyframes floaty{0%,100%{transform:translateY(0) rotate(var(--r,0deg));}50%{transform:translateY(-16px) rotate(var(--r,0deg));}}
  .card-side.left{--r:-6deg;}
  .card-side.right{--r:5deg;}
  .card-main{--r:2deg;}

  .paw-orbit{position:absolute;inset:0;pointer-events:none;}
  .paw-orbit svg{position:absolute;opacity:.9;}

  /* ---------- marquee ---------- */
  .marquee-wrap{position:relative;z-index:1;background:var(--ink);padding:18px 0;overflow:hidden;transform:rotate(-1.2deg);margin:64px 0;}
  .marquee{display:flex;gap:48px;white-space:nowrap;animation:scroll 26s linear infinite;width:max-content;}
  .marquee span{color:var(--cream);font-family:'Baloo 2';font-weight:600;font-size:1.1rem;display:flex;align-items:center;gap:14px;}
  .marquee span::after{content:'✦';color:var(--coral);}
  @keyframes scroll{from{transform:translateX(0);}to{transform:translateX(-50%);}}

  /* ---------- section heads ---------- */
  section{position:relative;z-index:1;}
  .sec-pad{padding:60px 0;}
  .sec-head{display:flex;justify-content:space-between;align-items:flex-end;margin-bottom:40px;gap:20px;flex-wrap:wrap;}
  .sec-head h2{font-size:clamp(2rem,3.4vw,2.7rem);font-weight:700;max-width:520px;line-height:1.12;}
  .sec-head p{color:var(--ink-soft);max-width:340px;line-height:1.6;}

  /* ---------- categories (tilt cards) ---------- */
  .cat-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:22px;perspective:1200px;}
  .cat-card{position:relative;border-radius:var(--radius-md);padding:26px 22px;height:230px;display:flex;flex-direction:column;justify-content:space-between;color:#fff;overflow:hidden;transform-style:preserve-3d;transition:transform .12s ease-out, box-shadow .3s;box-shadow:0 18px 32px -14px rgba(36,30,60,.3);cursor:pointer;}
  .cat-card:hover{box-shadow:0 26px 44px -14px rgba(36,30,60,.4);}
  .cat-card .icon-wrap{width:56px;height:56px;border-radius:16px;background:rgba(255,255,255,.22);display:flex;align-items:center;justify-content:center;transform:translateZ(30px);}
  .cat-card .icon-wrap svg{width:30px;height:30px;}
  .cat-card .meta{transform:translateZ(20px);}
  .cat-card .meta b{font-family:'Baloo 2';font-size:1.2rem;display:block;}
  .cat-card .meta span{font-size:.82rem;opacity:.85;}
  .cat-card .glow{position:absolute;width:160px;height:160px;border-radius:50%;background:rgba(255,255,255,.18);top:-60px;right:-60px;}
  .cat-c1{background:linear-gradient(150deg,var(--coral),#FF9270);}
  .cat-c2{background:linear-gradient(150deg,var(--grape),#9A7CFF);}
  .cat-c3{background:linear-gradient(150deg,var(--mint),#20BFA9);}
  .cat-c4{background:linear-gradient(150deg,var(--sky),#2E7CFF);}

  /* ---------- products ---------- */
  .prod-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:26px;}
  .prod-card{background:var(--paper);border-radius:var(--radius-md);padding:20px;box-shadow:0 14px 30px -16px rgba(36,30,60,.22);transition:transform .35s ease, box-shadow .35s ease;position:relative;}
  .prod-card:hover{transform:translateY(-10px);box-shadow:0 26px 44px -16px rgba(36,30,60,.3);}
  .prod-visual{height:190px;border-radius:16px;position:relative;overflow:hidden;margin-bottom:18px;display:flex;align-items:center;justify-content:center;}
  .prod-visual svg{width:78%;height:78%;filter:drop-shadow(0 14px 16px rgba(36,30,60,.22));}
  .prod-visual::before{content:'';position:absolute;inset:0;opacity:.9;}
  .pv1{background:linear-gradient(160deg,#FFE39A,var(--sun));}
  .pv2{background:linear-gradient(160deg,#BFE9FF,var(--sky));}
  .pv3{background:linear-gradient(160deg,#D9CCFF,var(--grape));}
  .pv4{background:linear-gradient(160deg,#B9F5EA,var(--mint));}
  .pv5{background:linear-gradient(160deg,#FFC2BC,var(--coral));}
  .pv6{background:linear-gradient(160deg,#FFD9E8,#FF7FB0);}
  .tag-new{position:absolute;top:14px;left:14px;background:var(--ink);color:#fff;font-size:.72rem;font-weight:600;padding:6px 12px;border-radius:100px;z-index:2;}
  .prod-title{font-weight:600;font-size:1.02rem;margin-bottom:4px;}
  .prod-sub{font-size:.85rem;color:var(--ink-soft);margin-bottom:14px;}
  .prod-foot{display:flex;justify-content:space-between;align-items:center;}
  .price{font-family:'Baloo 2';font-weight:700;font-size:1.25rem;}
  .add-btn{width:42px;height:42px;border-radius:50%;background:var(--cream);border:1px solid rgba(36,30,60,.1);display:flex;align-items:center;justify-content:center;transition:background .2s, transform .2s, color .2s;}
  .add-btn:hover{background:var(--coral);color:#fff;transform:rotate(90deg);}

  /* ---------- why us / stats 3D tiles ---------- */
  .why-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:26px;align-items:stretch;}
  .why-copy{background:linear-gradient(155deg,var(--ink),#352A5E);border-radius:var(--radius-lg);padding:46px;color:var(--cream);position:relative;overflow:hidden;}
  .why-copy h2{font-size:clamp(1.9rem,3vw,2.4rem);margin-bottom:16px;}
  .why-copy p{color:rgba(255,247,236,.75);line-height:1.7;max-width:420px;margin-bottom:28px;}
  .why-list{display:grid;gap:16px;}
  .why-list li{display:flex;gap:14px;align-items:flex-start;}
  .why-list .num{font-family:'Baloo 2';font-weight:700;color:var(--sun);}
  .why-list b{display:block;font-weight:600;}
  .why-list span{font-size:.85rem;color:rgba(255,247,236,.65);}
  .orb{position:absolute;width:300px;height:300px;border-radius:50%;background:radial-gradient(circle,rgba(255,201,60,.25),transparent 70%);bottom:-120px;right:-100px;}

  .stat-tiles{display:grid;grid-template-rows:repeat(2,1fr);gap:26px;}
  .tile{border-radius:var(--radius-md);padding:30px;display:flex;flex-direction:column;justify-content:space-between;box-shadow:0 16px 30px -16px rgba(36,30,60,.25);}
  .tile.t1{background:var(--sun);}
  .tile.t2{background:var(--mint);}
  .tile b{font-family:'Baloo 2';font-size:2.4rem;}
  .tile span{font-weight:500;color:rgba(36,30,60,.7);}

  /* ---------- testimonials ---------- */
  .test-track{display:flex;gap:22px;overflow-x:auto;padding-bottom:10px;scroll-snap-type:x mandatory;}
  .test-track::-webkit-scrollbar{height:6px;}
  .test-track::-webkit-scrollbar-thumb{background:rgba(36,30,60,.15);border-radius:10px;}
  .test-card{flex:0 0 320px;background:var(--paper);border-radius:var(--radius-md);padding:28px;box-shadow:0 14px 28px -16px rgba(36,30,60,.2);scroll-snap-align:start;}
  .stars{color:var(--sun);font-size:1rem;margin-bottom:14px;letter-spacing:2px;}
  .test-card p{color:var(--ink-soft);line-height:1.6;margin-bottom:20px;font-size:.95rem;}
  .test-who{display:flex;align-items:center;gap:12px;}
  .avatar{width:42px;height:42px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:'Baloo 2';font-weight:700;color:#fff;}
  .a1{background:var(--coral);} .a2{background:var(--grape);} .a3{background:var(--sky);} .a4{background:#20BFA9;}
  .test-who b{display:block;font-size:.92rem;}
  .test-who span{font-size:.78rem;color:var(--ink-soft);}

  /* ---------- CTA ---------- */
  .cta-band{background:linear-gradient(120deg,var(--coral),var(--grape));border-radius:var(--radius-lg);padding:64px 56px;display:flex;justify-content:space-between;align-items:center;gap:30px;color:#fff;position:relative;overflow:hidden;flex-wrap:wrap;}
  .cta-band h2{font-size:clamp(1.9rem,3.4vw,2.6rem);max-width:480px;line-height:1.15;}
  .cta-band .btn-primary{background:#fff;color:var(--ink);box-shadow:0 14px 28px rgba(0,0,0,.2);}
  .cta-band .btn-primary:hover{box-shadow:0 18px 34px rgba(0,0,0,.28);}
  .cta-paw{position:absolute;opacity:.15;}

  /* ---------- footer ---------- */
  footer{padding:54px 0 30px;color:var(--ink-soft);}
  .foot-grid{display:grid;grid-template-columns:1.4fr 1fr 1fr 1fr;gap:30px;padding-bottom:36px;border-bottom:1px solid rgba(36,30,60,.08);}
  .foot-grid h4{font-family:'Baloo 2';color:var(--ink);margin-bottom:14px;font-size:1rem;}
  .foot-grid li{margin-bottom:10px;font-size:.9rem;}
  .foot-grid li a:hover{color:var(--coral);}
  .foot-bottom{display:flex;justify-content:space-between;align-items:center;padding-top:22px;font-size:.85rem;flex-wrap:wrap;gap:12px;}
  .foot-bottom .socials{display:flex;gap:12px;}
  .foot-bottom .socials a{width:36px;height:36px;border-radius:50%;background:var(--paper);border:1px solid rgba(36,30,60,.08);display:flex;align-items:center;justify-content:center;transition:background .2s,color .2s;}
  .foot-bottom .socials a:hover{background:var(--ink);color:#fff;}

  @media (max-width:1000px){
    .hero-grid{grid-template-columns:1fr;}
    .stage{margin-top:20px;height:380px;}
    .cat-grid{grid-template-columns:repeat(2,1fr);}
    .prod-grid{grid-template-columns:repeat(2,1fr);}
    .why-grid{grid-template-columns:1fr;}
    .foot-grid{grid-template-columns:1fr 1fr;gap:28px;}
    .nav-links{display:none;}
  }
  @media (max-width:600px){
    .cat-grid{grid-template-columns:1fr;}
    .prod-grid{grid-template-columns:1fr;}
    .foot-grid{grid-template-columns:1fr;}
    .cta-band{padding:44px 26px;}
  }
</style>
</head>
<body>

<div class="blob-field">
  <div class="blob b1"></div>
  <div class="blob b2"></div>
  <div class="blob b3"></div>
</div>

<header>
  <div class="wrap">
    <nav>
      <div class="logo">
        <div class="logo-mark">
          <svg viewBox="0 0 24 24" fill="none"><path d="M12 21c-4-1.5-8-4.7-8-9a4 4 0 0 1 7-2.6A4 4 0 0 1 18 12c0 4.3-4 7.5-6 9z" fill="#fff"/></svg>
        </div>
        Pawsome
      </div>
      <ul class="nav-links">
        <li><a href="#shop">Shop</a></li>
        <li><a href="#why">Why us</a></li>
        <li><a href="#reviews">Reviews</a></li>
        <li><a href="#faq">Support</a></li>
      </ul>
      <a href="#shop" class="nav-cta">Start shopping</a>
    </nav>
  </div>
</header>

<main>
  <!-- HERO -->
  <section class="hero">
    <div class="wrap hero-grid">
      <div>
        <div class="eyebrow-chip"><span class="dot">🐾</span> Loved by 40,000+ pet parents</div>
        <h1>Everything your pet needs, <span class="accent">wrapped in joy.</span></h1>
        <p class="lede">Fresh food, comfy beds, and toys that actually get used — hand-picked and shipped to your door in colors as playful as your pet's personality.</p>
        <div class="hero-actions">
          <a href="#shop" class="btn-primary">Shop the collection</a>
          <a href="#why" class="btn-ghost"><span class="play-ring">▶</span> See how it works</a>
        </div>
        <div class="trust-row">
          <div class="stat"><b>40k+</b><span>Happy households</span></div>
          <div class="stat"><b>4.9★</b><span>Average rating</span></div>
          <div class="stat"><b>24h</b><span>Dispatch time</span></div>
        </div>
      </div>

      <div class="stage" id="stage">
        <div class="stage-card card-side left">
          <svg viewBox="0 0 200 240" width="200" height="240">
            <rect width="200" height="240" rx="22" fill="none"/>
            <circle cx="100" cy="95" r="46" fill="rgba(255,255,255,.25)"/>
            <path d="M75 96c0-16 11-28 25-28s25 12 25 28-11 34-25 34-25-18-25-34z" fill="#fff"/>
            <circle cx="88" cy="90" r="4" fill="#241E3C"/>
            <circle cx="112" cy="90" r="4" fill="#241E3C"/>
            <path d="M92 104q8 8 16 0" stroke="#241E3C" stroke-width="3" fill="none" stroke-linecap="round"/>
            <path d="M65 70 55 48 78 60z" fill="#fff"/>
            <path d="M135 70 145 48 122 60z" fill="#fff"/>
          </svg>
        </div>
        <div class="stage-card card-main">
          <div class="badge-float">🐶 Best seller</div>
          <div class="cap">
            <b>Cloud Nap Bed</b>
            <span>Orthopedic comfort, 6 colorways</span>
          </div>
        </div>
        <div class="stage-card card-side right">
          <svg viewBox="0 0 200 240" width="200" height="240">
            <circle cx="100" cy="120" r="50" fill="rgba(255,255,255,.28)"/>
            <ellipse cx="100" cy="120" rx="38" ry="34" fill="#fff"/>
            <path d="M68 96 60 74 84 90z" fill="#fff"/>
            <path d="M132 96 140 74 116 90z" fill="#fff"/>
            <circle cx="88" cy="118" r="4" fill="#241E3C"/>
            <circle cx="112" cy="118" r="4" fill="#241E3C"/>
            <path d="M100 126v6" stroke="#241E3C" stroke-width="3" stroke-linecap="round"/>
            <path d="M84 138q16 10 32 0" stroke="#241E3C" stroke-width="3" fill="none" stroke-linecap="round"/>
          </svg>
        </div>
        <div class="paw-orbit">
          <svg width="30" height="30" viewBox="0 0 24 24" style="top:10%;left:6%;" fill="var(--sun)"><circle cx="12" cy="12" r="10"/></svg>
          <svg width="18" height="18" viewBox="0 0 24 24" style="bottom:8%;left:16%;" fill="var(--coral)"><circle cx="12" cy="12" r="10"/></svg>
        </div>
      </div>
    </div>
  </section>

  <div class="marquee-wrap">
    <div class="marquee">
      <span>Free shipping over $40</span>
      <span>Vet-approved nutrition</span>
      <span>30-day happy paw guarantee</span>
      <span>New arrivals weekly</span>
      <span>Free shipping over $40</span>
      <span>Vet-approved nutrition</span>
      <span>30-day happy paw guarantee</span>
      <span>New arrivals weekly</span>
    </div>
  </div>

  <!-- CATEGORIES -->
  <section class="sec-pad" id="shop">
    <div class="wrap">
      <div class="sec-head">
        <h2>Shop by who you're spoiling</h2>
        <p>Curated edits for every kind of housemate, from goldfish to Great Danes.</p>
      </div>
      <div class="cat-grid">
        <div class="cat-card cat-c1 tilt">
          <div class="glow"></div>
          <div class="icon-wrap"><svg viewBox="0 0 24 24" fill="#fff"><path d="M4.5 9.5a2 2 0 1 1 0-4 2 2 0 0 1 0 4Zm15 0a2 2 0 1 1 0-4 2 2 0 0 1 0 4ZM8.5 6a2 2 0 1 1 0-4 2 2 0 0 1 0 4Zm7 0a2 2 0 1 1 0-4 2 2 0 0 1 0 4ZM12 20c-4 0-7-2.5-7-6.2C5 10.5 8.1 9 12 9s7 1.5 7 4.8c0 3.7-3 6.2-7 6.2Z"/></svg></div>
          <div class="meta"><b>Dogs</b><span>128 products</span></div>
        </div>
        <div class="cat-card cat-c2 tilt">
          <div class="glow"></div>
          <div class="icon-wrap"><svg viewBox="0 0 24 24" fill="#fff"><path d="M6 3 4 9l4-1 1 4-4 1 2 8h10l2-8-4-1 1-4 4 1-2-6-5 2-2-2-5 2Z"/></svg></div>
          <div class="meta"><b>Cats</b><span>94 products</span></div>
        </div>
        <div class="cat-card cat-c3 tilt">
          <div class="glow"></div>
          <div class="icon-wrap"><svg viewBox="0 0 24 24" fill="#fff"><path d="M3 12c4-6 14-6 18 0-4 6-14 6-18 0Zm9-2.5A2.5 2.5 0 1 0 12 14.5 2.5 2.5 0 0 0 12 9.5Z"/></svg></div>
          <div class="meta"><b>Small pets</b><span>56 products</span></div>
        </div>
        <div class="cat-card cat-c4 tilt">
          <div class="glow"></div>
          <div class="icon-wrap"><svg viewBox="0 0 24 24" fill="#fff"><path d="M12 2c3 3 6 6.5 6 10.5A6 6 0 0 1 6 12.5C6 8.5 9 5 12 2Z"/></svg></div>
          <div class="meta"><b>Aquatics</b><span>37 products</span></div>
        </div>
      </div>
    </div>
  </section>

  <!-- PRODUCTS -->
  <section class="sec-pad">
    <div class="wrap">
      <div class="sec-head">
        <h2>This week's most-loved finds</h2>
        <p>Restocked fast — these rarely sit in the cart for long.</p>
      </div>
      <div class="prod-grid">

        <div class="prod-card">
          <span class="tag-new">New</span>
          <div class="prod-visual pv1">
            <svg viewBox="0 0 120 120"><circle cx="60" cy="60" r="46" fill="#fff" opacity=".9"/><path d="M40 60c0-14 9-24 20-24s20 10 20 24-9 28-20 28-20-14-20-28z" fill="#FFB020"/><circle cx="52" cy="54" r="4" fill="#241E3C"/><circle cx="68" cy="54" r="4" fill="#241E3C"/></svg>
          </div>
          <div class="prod-title">Sunset Kibble Blend</div>
          <div class="prod-sub">Grain-free, salmon &amp; sweet potato</div>
          <div class="prod-foot"><span class="price">$24</span><span class="add-btn">+</span></div>
        </div>

        <div class="prod-card">
          <div class="prod-visual pv2">
            <svg viewBox="0 0 120 120"><ellipse cx="60" cy="66" rx="42" ry="30" fill="#fff" opacity=".9"/><circle cx="46" cy="52" r="7" fill="#2E9BFF"/><circle cx="74" cy="52" r="7" fill="#2E9BFF"/><rect x="40" y="70" width="40" height="10" rx="5" fill="#2E9BFF"/></svg>
          </div>
          <div class="prod-title">Whistle Rope Toy Set</div>
          <div class="prod-sub">3-piece, natural cotton</div>
          <div class="prod-foot"><span class="price">$16</span><span class="add-btn">+</span></div>
        </div>

        <div class="prod-card">
          <span class="tag-new">New</span>
          <div class="prod-visual pv3">
            <svg viewBox="0 0 120 120"><rect x="24" y="40" width="72" height="46" rx="16" fill="#fff" opacity=".9"/><circle cx="45" cy="63" r="6" fill="#7C5CFC"/><circle cx="75" cy="63" r="6" fill="#7C5CFC"/><path d="M50 76q10 8 20 0" stroke="#7C5CFC" stroke-width="4" fill="none" stroke-linecap="round"/></svg>
          </div>
          <div class="prod-title">Cloud Nap Bed</div>
          <div class="prod-sub">Orthopedic memory foam</div>
          <div class="prod-foot"><span class="price">$68</span><span class="add-btn">+</span></div>
        </div>

        <div class="prod-card">
          <div class="prod-visual pv4">
            <svg viewBox="0 0 120 120"><circle cx="60" cy="60" r="40" fill="#fff" opacity=".9"/><path d="M40 55c8-10 32-10 40 0" stroke="#20BFA9" stroke-width="5" fill="none" stroke-linecap="round"/><circle cx="50" cy="65" r="5" fill="#20BFA9"/><circle cx="70" cy="65" r="5" fill="#20BFA9"/></svg>
          </div>
          <div class="prod-title">Bubble Stream Fountain</div>
          <div class="prod-sub">Quiet-flow, self-filtering</div>
          <div class="prod-foot"><span class="price">$39</span><span class="add-btn">+</span></div>
        </div>

        <div class="prod-card">
          <div class="prod-visual pv5">
            <svg viewBox="0 0 120 120"><path d="M60 22c14 14 30 24 30 44a30 30 0 0 1-60 0c0-20 16-30 30-44Z" fill="#fff" opacity=".9"/><circle cx="52" cy="72" r="4" fill="#FF6B6B"/><circle cx="68" cy="72" r="4" fill="#FF6B6B"/></svg>
          </div>
          <div class="prod-title">Cozy Cave Hoodie</div>
          <div class="prod-sub">Fleece-lined, 5 sizes</div>
          <div class="prod-foot"><span class="price">$22</span><span class="add-btn">+</span></div>
        </div>

        <div class="prod-card">
          <span class="tag-new">New</span>
          <div class="prod-visual pv6">
            <svg viewBox="0 0 120 120"><rect x="30" y="30" width="60" height="60" rx="20" fill="#fff" opacity=".9"/><circle cx="60" cy="60" r="14" fill="#FF7FB0"/></svg>
          </div>
          <div class="prod-title">Puzzle Feeder Bowl</div>
          <div class="prod-sub">Slows eating, boosts play</div>
          <div class="prod-foot"><span class="price">$18</span><span class="add-btn">+</span></div>
        </div>

      </div>
    </div>
  </section>

  <!-- WHY US -->
  <section class="sec-pad" id="why">
    <div class="wrap why-grid">
      <div class="why-copy">
        <div class="orb"></div>
        <h2>Built by pet people, for pet people.</h2>
        <p>We test every bed, toy, and bowl with our own dogs, cats, and one very opinionated cockatiel before it ever reaches your cart.</p>
        <ul class="why-list">
          <li><span class="num">01</span><div><b>Vet-reviewed sourcing</b><span>Every food and supplement is checked against current nutrition guidelines.</span></div></li>
          <li><span class="num">02</span><div><b>Fast, low-stress delivery</b><span>Most orders ship same day and land within 48 hours.</span></div></li>
          <li><span class="num">03</span><div><b>Real return policy</b><span>If your pet turns their nose up, we'll take it back — no questions.</span></div></li>
        </ul>
      </div>
      <div class="stat-tiles">
        <div class="tile t1"><b>4.9 / 5</b><span>from 12,400 verified reviews</span></div>
        <div class="tile t2"><b>98%</b><span>of orders arrive within 2 days</span></div>
      </div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section class="sec-pad" id="reviews">
    <div class="wrap">
      <div class="sec-head">
        <h2>What pet parents are saying</h2>
      </div>
      <div class="test-track">
        <div class="test-card">
          <div class="stars">★★★★★</div>
          <p>"The Cloud Nap Bed disappeared under my Labrador within five minutes — in the best way. He hasn't slept anywhere else since."</p>
          <div class="test-who"><div class="avatar a1">M</div><div><b>Maya R.</b><span>Dog mom to Biscuit</span></div></div>
        </div>
        <div class="test-card">
          <div class="stars">★★★★★</div>
          <p>"Fast shipping, and the puzzle feeder actually slowed my cat's eating down. Small change, huge difference."</p>
          <div class="test-who"><div class="avatar a2">D</div><div><b>Devan K.</b><span>Cat dad to Miso</span></div></div>
        </div>
        <div class="test-card">
          <div class="stars">★★★★★</div>
          <p>"Their aquarium fountain is whisper quiet. My betta fish has never looked more chill."</p>
          <div class="test-who"><div class="avatar a3">L</div><div><b>Lena P.</b><span>Fish keeper</span></div></div>
        </div>
        <div class="test-card">
          <div class="stars">★★★★★</div>
          <p>"Ordered the wrong size hoodie and support swapped it same day. That kind of service keeps me coming back."</p>
          <div class="test-who"><div class="avatar a4">J</div><div><b>Jordan T.</b><span>Rescue foster</span></div></div>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="sec-pad">
    <div class="wrap">
      <div class="cta-band">
        <h2>Your pet's next favorite thing is one click away.</h2>
        <a href="#shop" class="btn-primary">Browse the shop</a>
      </div>
    </div>
  </section>
</main>

<footer id="faq">
  <div class="wrap">
    <div class="foot-grid">
      <div>
        <div class="logo" style="margin-bottom:14px;">
          <div class="logo-mark"><svg viewBox="0 0 24 24" fill="none"><path d="M12 21c-4-1.5-8-4.7-8-9a4 4 0 0 1 7-2.6A4 4 0 0 1 18 12c0 4.3-4 7.5-6 9z" fill="#fff"/></svg></div>
          Pawsome
        </div>
        <p style="max-width:260px;font-size:.9rem;line-height:1.6;">Colorful, thoughtful essentials for every pet under your roof.</p>
      </div>
      <div>
        <h4>Shop</h4>
        <ul><li><a href="#">Dogs</a></li><li><a href="#">Cats</a></li><li><a href="#">Small pets</a></li><li><a href="#">Aquatics</a></li></ul>
      </div>
      <div>
        <h4>Company</h4>
        <ul><li><a href="#">About</a></li><li><a href="#">Careers</a></li><li><a href="#">Sustainability</a></li></ul>
      </div>
      <div>
        <h4>Support</h4>
        <ul><li><a href="#">Shipping</a></li><li><a href="#">Returns</a></li><li><a href="#">Contact us</a></li></ul>
      </div>
    </div>
    <div class="foot-bottom">
      <span>© 2026 Pawsome Pet Co. All rights reserved.</span>
      <div class="socials">
        <a href="#">𝕏</a><a href="#">◎</a><a href="#">f</a>
      </div>
    </div>
  </div>
</footer>

<script>
  // 3D tilt for hero stage
  const stage = document.getElementById('stage');
  if (stage) {
    stage.addEventListener('mousemove', (e) => {
      const rect = stage.getBoundingClientRect();
      const x = (e.clientX - rect.left) / rect.width - 0.5;
      const y = (e.clientY - rect.top) / rect.height - 0.5;
      stage.querySelectorAll('.stage-card').forEach((card, i) => {
        const depth = (i + 1) * 6;
        card.style.transform = `rotateY(${x * depth}deg) rotateX(${-y * depth}deg)`;
      });
    });
    stage.addEventListener('mouseleave', () => {
      stage.querySelectorAll('.stage-card').forEach(card => card.style.transform = '');
    });
  }

  // 3D tilt for category cards
  document.querySelectorAll('.tilt').forEach(card => {
    card.addEventListener('mousemove', (e) => {
      const rect = card.getBoundingClientRect();
      const x = (e.clientX - rect.left) / rect.width - 0.5;
      const y = (e.clientY - rect.top) / rect.height - 0.5;
      card.style.transform = `rotateY(${x * 14}deg) rotateX(${-y * 14}deg) translateY(-4px)`;
    });
    card.addEventListener('mouseleave', () => { card.style.transform = ''; });
  });

  // gentle reveal for sections on scroll
  const io = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.style.opacity = 1;
        entry.target.style.transform = 'translateY(0)';
      }
    });
  }, { threshold: 0.15 });

  document.querySelectorAll('.prod-card, .cat-card, .test-card, .tile').forEach(el => {
    el.style.opacity = 0;
    el.style.transform = 'translateY(24px)';
    el.style.transition = 'opacity .6s ease, transform .6s ease';
    io.observe(el);
  });
</script>

</body>
</html># my-website
