<!doctype html>
<html lang="en">
<head>
  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=AW-17930508850"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'AW-17930508850');
  </script>

  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />

  <!-- ✅ CHANGE THESE 2 -->
  <title>Mobile Tire Repair Vancouver | Flat Tire Repair & Tire Change (24/7)</title>
  <meta name="description" content="Mobile tire repair in Vancouver. Flat tire repair, tire swaps, balancing & roadside help. Serving Vancouver, Burnaby, Richmond, Surrey + North Shore. Call PHONE_NUMBER_HERE." />
  <link rel="canonical" href="https://DOMAIN_HERE/" />

  <meta name="robots" content="index, follow, max-image-preview:large" />
  <meta name="theme-color" content="#010204" />

  <!-- Open Graph -->
  <meta property="og:title" content="Mobile Tire Repair Vancouver | 24/7 Mobile Tire Service" />
  <meta property="og:description" content="Flat repair • Tire swaps • Balancing • Roadside help across Vancouver + Lower Mainland. Call PHONE_NUMBER_HERE." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://DOMAIN_HERE/" />
  <meta property="og:image" content="https://DOMAIN_HERE/og-image.jpg" />

  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Mobile Tire Repair Vancouver | 24/7" />
  <meta name="twitter:description" content="Mobile flat tire repair & tire service across Vancouver + Lower Mainland. Call PHONE_NUMBER_HERE." />
  <meta name="twitter:image" content="https://DOMAIN_HERE/og-image.jpg" />

  <!-- (FAST) System font stack: remove Google Fonts + Font Awesome + AOS -->
  <style>
    :root{
      --cyan:#00f2ff;
      --bg:#010204;
      --glass: rgba(255,255,255,.06);
      --glass2: rgba(255,255,255,.09);
      --border: rgba(255,255,255,.12);
      --muted: rgba(255,255,255,.74);
      --green:#22c55e;
      --shadow: 0 25px 80px rgba(0,0,0,.65);
      --glow: 0 0 50px rgba(0,242,255,.35);
    }
    *{box-sizing:border-box;margin:0;padding:0}
    html{scroll-behavior:smooth; scroll-padding-top:140px;}
    body{
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      background: var(--bg);
      color:#fff;
      overflow-x:hidden;
      line-height:1.6;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
    }
    a{color:inherit}
    .container{max-width:1200px;margin:0 auto;padding:0 20px}
    main{padding-top:72px}

    /* Background */
    .bg-aurora{
      position:fixed; inset:-40%;
      background:
        radial-gradient(circle at 20% 30%, rgba(0,242,255,.14), transparent 40%),
        radial-gradient(circle at 80% 40%, rgba(34,197,94,.10), transparent 45%),
        radial-gradient(circle at 50% 80%, rgba(255,255,255,.06), transparent 50%);
      filter: blur(30px);
      opacity:.9;
      z-index:-3;
      animation: auroraMove 14s ease-in-out infinite alternate;
      pointer-events:none;
    }
    @keyframes auroraMove{
      from{ transform: translate3d(-2%, -2%, 0) scale(1.02); }
      to{ transform: translate3d(2%, 2%, 0) scale(1.08); }
    }

    /* Poster always, video desktop-only */
    .video-container{position:fixed; inset:0; z-index:-4; background:#000; overflow:hidden;}
    .video-container picture, .video-container img{
      position:absolute; inset:0;
      width:100%; height:100%;
      object-fit:cover;
      opacity:.40;
      filter:saturate(.65) contrast(1.1);
    }
    .bg-video{display:none;}
    @media (min-width: 901px){
      .bg-video{display:block; width:100%;height:100%;object-fit:cover;opacity:.40;filter:saturate(.65) contrast(1.1);}
      .video-container picture{display:none;}
    }

    .vignette{
      position:fixed; inset:0; z-index:-2; pointer-events:none;
      background:
        radial-gradient(circle at 50% 30%, rgba(0,0,0,0) 15%, rgba(1,2,4,.90) 70%),
        linear-gradient(to bottom, rgba(1,2,4,.25), rgba(1,2,4,.95));
    }

    /* Ticker */
    .ticker{
      width:100%;
      background: rgba(0,0,0,.92);
      border-bottom:1px solid rgba(0,242,255,.55);
      color: var(--cyan);
      font-weight:800;
      text-transform:uppercase;
      font-size:10px;
      padding:12px 0;
      position:fixed;
      top:0;
      z-index:3000;
      overflow:hidden;
    }
    .ticker-content{display:inline-block;white-space:nowrap;animation:ticker 28s linear infinite;}
    .ticker-content span{padding-right:50px;}
    @keyframes ticker{0%{transform:translateX(0)}100%{transform:translateX(-50%)}}

    /* Mini nav */
    .mini-nav{
      position:fixed;
      top:44px;
      left:50%;
      transform:translateX(-50%);
      z-index:2900;
      display:flex;
      gap:10px;
      flex-wrap:wrap;
      justify-content:center;
      padding:10px 14px;
      border-radius:999px;
      background: rgba(0,0,0,.55);
      border: 1px solid rgba(0,242,255,.22);
      backdrop-filter: blur(12px);
      box-shadow: 0 10px 30px rgba(0,0,0,.35);
    }
    .mini-nav a{
      font-size:10px;
      letter-spacing:2px;
      font-weight:800;
      text-transform:uppercase;
      text-decoration:none;
      color: var(--cyan);
      opacity:.95;
      padding:6px 10px;
      border-radius:999px;
      transition:.2s;
    }
    .mini-nav a:hover{background: rgba(0,242,255,.10); transform: translateY(-1px);}

    /* Dock */
    .dock{
      position:fixed;
      bottom:22px;
      left:50%;
      transform:translateX(-50%);
      z-index:3500;
      display:flex;
      gap:10px;
      align-items:center;
      padding:10px 12px;
      border-radius:999px;
      background: rgba(15,15,15,.86);
      border:1px solid rgba(255,255,255,.12);
      backdrop-filter: blur(18px);
      box-shadow: var(--shadow);
    }
    .round-btn{
      width:50px; height:50px;
      display:flex; align-items:center; justify-content:center;
      border-radius:50%;
      text-decoration:none;
      border:1px solid rgba(255,255,255,.12);
      transition:.2s;
      position:relative;
      overflow:hidden;
    }
    .round-btn:hover{transform: translateY(-2px);}
    .round-btn svg{display:block}
    .call-btn{background: var(--green); color:#000;}
    .call-btn::after{
      content:"";
      position:absolute; inset:0;
      border-radius:50%;
      background: var(--green);
      z-index:-1;
      animation: ping 1.9s infinite;
    }
    @keyframes ping{0%{transform:scale(1);opacity:.7}100%{transform:scale(1.85);opacity:0}}
    .text-btn{background: var(--cyan); color:#000;}
    .get-quote{
      height:50px;
      padding:0 18px;
      border-radius:999px;
      display:flex;
      align-items:center;
      font-weight:900;
      font-size:10px;
      text-transform:uppercase;
      letter-spacing:2px;
      text-decoration:none;
      background: rgba(255,255,255,.06);
      border:1px solid rgba(255,255,255,.12);
      transition:.2s;
    }
    .get-quote:hover{transform: translateY(-2px); background: rgba(255,255,255,.10);}

    /* Hero */
    .hero{
      min-height:100vh;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding-top:40px;
      position:relative;
    }
    .badge{
      display:inline-flex; align-items:center; gap:10px;
      padding:10px 14px;
      border-radius:999px;
      border:1px solid rgba(0,242,255,.25);
      background: rgba(0,242,255,.08);
      box-shadow: var(--glow);
      font-weight:900;
      letter-spacing:4px;
      font-size:10px;
      text-transform:uppercase;
    }
    .badge .dot{
      width:10px;height:10px;border-radius:50%;
      background: var(--green);
      box-shadow: 0 0 18px rgba(34,197,94,.7);
      animation: dotPulse 1.2s ease-in-out infinite;
    }
    @keyframes dotPulse{0%,100%{transform:scale(1);opacity:1}50%{transform:scale(1.35);opacity:.7}}

    .hero h1{
      font-size: clamp(3.2rem, 14vw, 8.2rem);
      font-weight: 800;
      letter-spacing: -4px;
      line-height: .85;
      margin: 18px 0 10px;
    }
    .glow-text{
      background: linear-gradient(90deg, #00f2ff, #22c55e, #00f2ff);
      background-size: 200% 200%;
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      text-shadow: 0 0 40px rgba(0,242,255,.25);
      animation: gradientShift 4s ease-in-out infinite;
    }
    @keyframes gradientShift{
      0%{background-position:0% 50%}
      50%{background-position:100% 50%}
      100%{background-position:0% 50%}
    }
    .hero-sub{
      max-width: 860px;
      margin-top: 14px;
      padding: 16px 20px;
      border-radius: 14px;
      background: linear-gradient(180deg, rgba(0,242,255,.10), rgba(255,255,255,.04));
      border: 1px solid rgba(0,242,255,.30);
      color:#eaffff;
      font-weight: 600;
      letter-spacing: .6px;
      box-shadow: 0 18px 60px rgba(0,242,255,.10);
      position:relative;
      overflow:hidden;
    }
    .hero-sub::before{
      content:"";
      position:absolute;
      top:-40px; left:-40px;
      width:140px;height:140px;
      background: radial-gradient(circle, rgba(0,242,255,.35), transparent 60%);
      filter: blur(2px);
      opacity:.7;
      animation: floatBlob 6s ease-in-out infinite;
    }
    @keyframes floatBlob{
      0%,100%{transform:translate(0,0)}
      50%{transform:translate(520px, 18px)}
    }

    .cta-row{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;margin-top:22px;}
    .cta{
      display:inline-flex; align-items:center; justify-content:center; gap:12px;
      padding:18px 26px;
      border-radius:14px;
      font-weight: 900;
      text-transform:uppercase;
      letter-spacing:2px;
      text-decoration:none;
      border:1px solid rgba(255,255,255,.12);
      min-width: 270px;
      transition:.2s;
      position:relative;
      overflow:hidden;
      box-shadow: 0 18px 60px rgba(0,0,0,.4);
    }
    .cta:hover{transform: translateY(-2px);}
    .cta.call{
      background: linear-gradient(135deg, rgba(34,197,94,1), rgba(34,197,94,.65));
      color:#000;
    }
    .cta.text{
      background: linear-gradient(135deg, rgba(0,242,255,1), rgba(0,242,255,.6));
      color:#000;
    }
    .cta::after{
      content:"";
      position:absolute; inset:-60px;
      background: linear-gradient(90deg, transparent, rgba(255,255,255,.25), transparent);
      transform: rotate(25deg) translateX(-120%);
      animation: shine 3.2s ease-in-out infinite;
    }
    @keyframes shine{
      0%{transform: rotate(25deg) translateX(-120%);}
      45%{transform: rotate(25deg) translateX(120%);}
      100%{transform: rotate(25deg) translateX(120%);}
    }

    .brand-row{display:flex;flex-wrap:wrap;justify-content:center;gap:12px;margin:26px 0 8px;opacity:.78;}
    .brand-tag{
      border:1px solid rgba(255,255,255,.12);
      background: rgba(255,255,255,.04);
      padding:10px 16px;
      border-radius:999px;
      font-size:11px;
      font-weight:900;
      text-transform:uppercase;
      letter-spacing:1px;
      transition:.2s;
    }
    .brand-tag:hover{transform: translateY(-2px); border-color: rgba(0,242,255,.35); box-shadow: var(--glow);}

    /* Sections */
    .section-card{
      background: rgba(255,255,255,.06);
      border:1px solid rgba(255,255,255,.12);
      border-radius:18px;
      padding:34px;
      backdrop-filter: blur(14px);
      box-shadow: 0 18px 70px rgba(0,0,0,.45);
      position:relative;
      overflow:hidden;
    }
    .section-card::before{
      content:"";
      position:absolute; inset:-2px;
      background: linear-gradient(120deg, rgba(0,242,255,.16), transparent 45%, rgba(34,197,94,.10));
      opacity:.9;
      pointer-events:none;
    }
    .section-card > *{position:relative;}
    .muted{color: rgba(255,255,255,.74);}

    .grid{
      display:grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap:18px;
      margin: 48px 0 26px;
    }
    .card{
      background: rgba(255,255,255,.05);
      border:1px solid rgba(255,255,255,.12);
      border-radius:18px;
      padding:28px;
      backdrop-filter: blur(12px);
      box-shadow: 0 18px 60px rgba(0,0,0,.35);
      transition:.2s;
      position:relative;
      overflow:hidden;
      min-height: 200px;
    }
    .card:hover{transform: translateY(-4px); border-color: rgba(0,242,255,.25);}
    .icon{
      width:34px;height:34px; margin-bottom:14px;
      color: var(--cyan);
    }
    .card h3{letter-spacing:2px;text-transform:uppercase;margin-bottom:10px;}

    /* Reviews: desktop scroll, mobile swipe */
    .reviews-wrap{
      margin: 40px 0 110px;
      padding: 40px 0;
      border-top:1px solid rgba(255,255,255,.10);
      border-bottom:1px solid rgba(255,255,255,.10);
      overflow:hidden;
      background: rgba(0,0,0,.18);
    }
    .reviews-track{
      display:inline-flex;
      gap:16px;
      padding-left: 18px;
      animation: reviewsScroll 60s linear infinite;
      will-change: transform;
    }
    @keyframes reviewsScroll{
      0%{transform: translateX(0)}
      100%{transform: translateX(-50%)}
    }
    .review{
      width: 320px;
      padding: 22px;
      border-radius: 18px;
      border:1px solid rgba(255,255,255,.12);
      background: rgba(255,255,255,.05);
      backdrop-filter: blur(12px);
      box-shadow: 0 18px 60px rgba(0,0,0,.35);
      flex: 0 0 auto;
    }
    .stars{
      color:#facc15;
      font-size:14px;
      margin-bottom:10px;
      display:flex; gap:4px; align-items:center;
    }
    .star{width:16px;height:16px; display:inline-block;}
    .review .who{margin-top:12px;color:var(--cyan);font-weight:900;font-size:11px;letter-spacing:1px;text-transform:uppercase;}

    /* Form */
    .form input, .form textarea{
      width:100%;
      background: rgba(0,0,0,.22);
      border: 1px solid rgba(255,255,255,.12);
      border-radius: 12px;
      padding: 14px 14px;
      color:#fff;
      outline:none;
      margin-top:10px;
      transition:.2s;
    }
    .form input:focus, .form textarea:focus{
      border-color: rgba(0,242,255,.45);
      box-shadow: 0 0 0 4px rgba(0,242,255,.12);
    }
    .form label{display:block;margin-top:14px;color:rgba(255,255,255,.78);font-weight:700;font-size:12px;letter-spacing:1px;text-transform:uppercase;}
    .submit{
      width:100%;
      margin-top:18px;
      border:none;
      border-radius:14px;
      padding: 16px 18px;
      font-weight: 900;
      text-transform:uppercase;
      letter-spacing:2px;
      cursor:pointer;
      color:#000;
      background: linear-gradient(135deg, rgba(0,242,255,1), rgba(0,242,255,.65));
      box-shadow: 0 18px 70px rgba(0,242,255,.16);
      transition:.2s;
    }
    .submit:hover{transform: translateY(-2px);}

    footer{
      padding: 40px 0 160px;
      text-align:center;
      color: rgba(255,255,255,.7);
    }
    footer a{color: var(--cyan); text-decoration:none; font-weight:900;}

    /* Performance on mobile */
    @media (max-width: 900px){
      .mini-nav, .dock, .section-card, .card, .review{backdrop-filter:none !important;}
      .bg-aurora{filter: blur(14px); opacity:.6;}
      .ticker-content{animation:none !important;} /* stop CPU */
      .reviews-track{animation:none !important; display:flex; overflow-x:auto; padding: 0 18px; gap:12px;}
      .reviews-track::-webkit-scrollbar{display:none;}
      .review{width:280px;}
    }

    @media (prefers-reduced-motion: reduce){
      .ticker-content, .reviews-track, .cta::after, .bg-aurora, .badge .dot, .hero-sub::before{animation:none !important;}
      .call-btn::after{animation:none !important;}
      html{scroll-behavior:auto;}
    }

    @media (max-width: 600px){
      main{ padding-top: 140px; }
      .mini-nav{
        top: 52px;
        width: calc(100% - 16px);
        padding: 8px 10px;
        gap: 8px;
        flex-wrap: nowrap;
        overflow-x: auto;
        justify-content: flex-start;
        -webkit-overflow-scrolling: touch;
      }
      .mini-nav::-webkit-scrollbar{ display:none; }
      .mini-nav a{
        font-size: 9px;
        letter-spacing: 1px;
        padding: 6px 10px;
        white-space: nowrap;
      }
      .hero{ padding-top: 18px; }
    }
  </style>

  <!-- LocalBusiness + FAQ Schema -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"LocalBusiness",
    "name":"Mobile Tire Repair Vancouver",
    "url":"https://DOMAIN_HERE/",
    "telephone":"PHONE_NUMBER_HERE",
    "priceRange":"$$",
    "areaServed":[
      "Vancouver, BC",
      "Burnaby, BC",
      "Richmond, BC",
      "Surrey, BC",
      "New Westminster, BC",
      "Coquitlam, BC",
      "Port Coquitlam, BC",
      "Port Moody, BC",
      "North Vancouver, BC",
      "West Vancouver, BC",
      "Delta, BC",
      "Langley, BC"
    ],
    "address":{
      "@type":"PostalAddress",
      "addressLocality":"Vancouver",
      "addressRegion":"BC",
      "addressCountry":"CA"
    },
    "openingHoursSpecification":[{
      "@type":"OpeningHoursSpecification",
      "dayOfWeek":["Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"],
      "opens":"00:00","closes":"23:59"
    }]
  }
  </script>

  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"FAQPage",
    "mainEntity":[
      {"@type":"Question","name":"Do you offer mobile flat tire repair in Vancouver?","acceptedAnswer":{"@type":"Answer","text":"Yes. We provide mobile flat tire repair across Vancouver and the Lower Mainland. Call or text with your location and tire size."}},
      {"@type":"Question","name":"Can you repair sidewall damage?","acceptedAnswer":{"@type":"Answer","text":"Most sidewall damage is not repairable for safety reasons. We’ll inspect and advise the safest option."}},
      {"@type":"Question","name":"What info should I send for the fastest quote?","acceptedAnswer":{"@type":"Answer","text":"Send your tire size (example: 225/65R17), your exact location, and whether it’s a flat repair or tire swap."}},
      {"@type":"Question","name":"Do you serve Burnaby, Richmond, Surrey, or the North Shore?","acceptedAnswer":{"@type":"Answer","text":"Yes—coverage depends on availability. Call or text to confirm same-day dispatch."}}
    ]
  }
  </script>
</head>

<body>

  <div class="bg-aurora" aria-hidden="true"></div>

  <!-- Poster (mobile + initial), video only desktop -->
  <div class="video-container" aria-hidden="true">
    <picture>
      <source srcset="sprinter-poster.webp" type="image/webp">
      <img src="sprinter-poster.jpg" alt="" loading="eager" fetchpriority="high" decoding="async">
    </picture>

    <video class="bg-video" autoplay muted loop playsinline preload="none" poster="sprinter-poster.jpg">
      <source src="sprinter-bg.mp4" type="video/mp4">
    </video>
  </div>
  <div class="vignette" aria-hidden="true"></div>

  <!-- Ticker -->
  <div class="ticker" role="status" aria-label="Service ticker">
    <div class="ticker-content">
      <span>🚨 EMERGENCY 24/7 SERVICE AVAILABLE</span>
      <span>• MOBILE TIRE CHANGE</span>
      <span>• FLAT REPAIR</span>
      <span>• OFF-RIM BALANCING</span>
      <span>• SERVING VANCOUVER • BURNABY • RICHMOND • SURREY • NORTH SHORE</span>
      <span>• CALL/TEXT PHONE_NUMBER_HERE</span>
      <span>• CALL/TEXT PHONE_NUMBER_HERE</span>
    </div>
  </div>

  <!-- Mini sitelinks -->
  <nav class="mini-nav" aria-label="Site links">
    <a href="#services">Services</a>
    <a href="#areas">Areas</a>
    <a href="#reviews">Reviews</a>
    <a href="#faq">FAQ</a>
    <a href="#quote">Get Quote</a>
  </nav>

  <!-- Sticky dock -->
  <div class="dock" aria-label="Quick actions">
    <a href="tel:PHONE_NUMBER_HERE" class="round-btn call-btn" aria-label="Call">
      <!-- phone icon -->
      <svg width="22" height="22" viewBox="0 0 24 24" fill="none" aria-hidden="true">
        <path d="M22 16.9v3a2 2 0 0 1-2.2 2c-8.5-.9-15.2-7.6-16.1-16.1A2 2 0 0 1 5.7 2h3a2 2 0 0 1 2 1.7c.1.9.3 1.8.6 2.6a2 2 0 0 1-.5 2.1L10 9.2a14.6 14.6 0 0 0 4.8 4.8l.8-.8a2 2 0 0 1 2.1-.5c.8.3 1.7.5 2.6.6A2 2 0 0 1 22 16.9Z"
          stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </a>

    <a href="sms:PHONE_NUMBER_HERE?&body=Hi!%20I%20need%20mobile%20tire%20service%20in%20Vancouver.%20My%20tire%20size%20is%20_____%20and%20my%20location%20is%20_____." class="round-btn text-btn" aria-label="Text for a quote">
      <!-- chat icon -->
      <svg width="22" height="22" viewBox="0 0 24 24" fill="none" aria-hidden="true">
        <path d="M21 15a4 4 0 0 1-4 4H8l-5 3V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v8Z"
          stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M8 10h8M8 14h5"
          stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </a>

    <a href="#quote" class="get-quote" aria-label="Jump to quote form">Get Quote</a>
  </div>

  <main class="container" id="main">

    <!-- Hidden machine-readable phone -->
    <div itemscope itemtype="https://schema.org/LocalBusiness" style="display:none;">
      <span itemprop="name">Mobile Tire Repair Vancouver</span>
      <a itemprop="telephone" href="tel:PHONE_NUMBER_HERE">PHONE_NUMBER_HERE</a>
      <span itemprop="address" itemscope itemtype="https://schema.org/PostalAddress">
        <span itemprop="addressLocality">Vancouver</span>,
        <span itemprop="addressRegion">BC</span>,
        <span itemprop="addressCountry">CA</span>
      </span>
      <link itemprop="url" href="https://DOMAIN_HERE/">
    </div>

    <!-- HERO -->
    <section class="hero">
      <div class="badge">
        <span class="dot"></span>
        VANCOUVER • MOBILE • 24/7
      </div>

      <h1>MOBILE TIRE<br><span class="glow-text">REPAIR VANCOUVER</span></h1>

      <div class="hero-sub">
        🚗 <strong>FLAT TIRE REPAIR</strong> • <strong>TIRE CHANGE AT HOME</strong> • <strong>BALANCING</strong><br>
        Serving <strong>Vancouver • Burnaby • Richmond • Surrey • New West • North Shore</strong>
        — call/text for dispatch.
      </div>

      <div class="cta-row">
        <a class="cta call" href="tel:PHONE_NUMBER_HERE" aria-label="Call">
          <!-- small phone -->
          <svg class="icon" viewBox="0 0 24 24" fill="none" aria-hidden="true" style="width:22px;height:22px;color:#000;margin:0;">
            <path d="M22 16.9v3a2 2 0 0 1-2.2 2c-8.5-.9-15.2-7.6-16.1-16.1A2 2 0 0 1 5.7 2h3a2 2 0 0 1 2 1.7c.1.9.3 1.8.6 2.6a2 2 0 0 1-.5 2.1L10 9.2a14.6 14.6 0 0 0 4.8 4.8l.8-.8a2 2 0 0 1 2.1-.5c.8.3 1.7.5 2.6.6A2 2 0 0 1 22 16.9Z"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          Call <span class="phone-visible">PHONE_NUMBER_HERE</span>
        </a>

        <a class="cta text" href="sms:PHONE_NUMBER_HERE?&body=Hi!%20I%20need%20mobile%20tire%20service%20in%20Vancouver.%20My%20tire%20size%20is%20_____%20and%20my%20location%20is%20_____." aria-label="Text for a quote">
          <!-- small chat -->
          <svg class="icon" viewBox="0 0 24 24" fill="none" aria-hidden="true" style="width:22px;height:22px;color:#000;margin:0;">
            <path d="M21 15a4 4 0 0 1-4 4H8l-5 3V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v8Z"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M8 10h8M8 14h5"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          Text For Quote
        </a>
      </div>

      <div style="margin-top:10px; font-size:12px; color:#aaa; letter-spacing:1px;">
        Fastest: text your <strong>tire size</strong> (ex: 225/65R17) + <strong>location</strong>
      </div>

      <div class="brand-row" aria-label="Tire brands">
        <div class="brand-tag">Michelin</div>
        <div class="brand-tag">Bridgestone</div>
        <div class="brand-tag">Pirelli</div>
        <div class="brand-tag">Continental</div>
        <div class="brand-tag">Goodyear</div>
      </div>
    </section>

    <!-- SEO AUTHORITY BLOCK -->
    <section class="section-card" style="margin-top:-40px;">
      <h2 style="letter-spacing:2px;text-transform:uppercase;margin-bottom:10px;">
        Tire Repair Near You — Vancouver Mobile Dispatch
      </h2>
      <p class="muted">
        If you searched <strong>“tire repair near me”</strong> or <strong>“flat tire repair Vancouver”</strong>,
        we come to your location fast. Call or text
        <a href="tel:PHONE_NUMBER_HERE" style="color:var(--cyan);font-weight:900;" itemprop="telephone">PHONE_NUMBER_HERE</a>
        with your tire size and exact location for the quickest quote/dispatch.
      </p>
      <p class="muted" style="margin-top:10px;">
        Services include puncture repair, tire swaps, and balancing when applicable.
        We serve Vancouver + the Lower Mainland (Burnaby, Richmond, Surrey, New Westminster, Coquitlam, North Vancouver, West Vancouver, Delta, Langley).
      </p>
    </section>

    <!-- SERVICES -->
    <section id="services" style="margin-top:36px;">
      <div class="grid" aria-label="Services">

        <div class="card">
          <svg class="icon" viewBox="0 0 24 24" fill="none" aria-hidden="true">
            <path d="M14.7 6.3 17.7 9.3M8.5 12.5l3-3m-6 10 6-6m8-1-3 3"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M7 7h4l6 6-4 4-6-6V7Z"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <h3>Flat Tire Repair</h3>
          <p class="muted">Punctures & slow leaks. Mobile support at home, work, or roadside. Safety-first inspection.</p>
        </div>

        <div class="card">
          <svg class="icon" viewBox="0 0 24 24" fill="none" aria-hidden="true">
            <path d="M12 2v20M4 6h16M6 10h12M8 14h8M10 18h4"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <h3>Seasonal Tire Swap</h3>
          <p class="muted">Winter/summer swaps done on-site. Clean, fast, and professional—no shop waiting.</p>
        </div>

        <div class="card">
          <svg class="icon" viewBox="0 0 24 24" fill="none" aria-hidden="true">
            <path d="M12 3l3 6 6 .8-4.5 4.2 1.2 6-5.7-3-5.7 3 1.2-6L3 9.8 9 9l3-6Z"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <h3>Balancing</h3>
          <p class="muted">Computer balancing for smooth driving and reduced vibration. Ask availability for your setup.</p>
        </div>

      </div>
    </section>

    <!-- AREAS -->
    <section id="areas" class="section-card">
      <h3 style="letter-spacing:2px;text-transform:uppercase;margin-bottom:10px;">Areas We Serve</h3>
      <p class="muted">
        Vancouver (Downtown, East Van, Kitsilano, UBC), Burnaby, Richmond, Surrey, New Westminster,
        Coquitlam, Port Coquitlam, Port Moody, Delta, Langley — plus North Vancouver & West Vancouver when available.
      </p>
    </section>

    <!-- REVIEWS -->
    <section id="reviews" class="reviews-wrap" aria-label="Customer reviews">
      <div class="container">
        <h3 style="letter-spacing:2px;text-transform:uppercase;margin-bottom:14px;">Real Results</h3>
      </div>

      <div class="reviews-track" aria-hidden="true">
        <!-- star svg -->
        <template id="starTpl"></template>

        <div class="review">
          <div class="stars">
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
          </div>
          <p>"Professional, fast, and fair pricing. Came to my driveway and finished quickly."</p>
          <div class="who">Mike R. • Verified</div>
        </div>

        <div class="review">
          <div class="stars">
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
          </div>
          <p>"Saved me from a flat and got me back on the road fast. Highly recommended."</p>
          <div class="who">Sarah J. • Verified</div>
        </div>

        <div class="review">
          <div class="stars">
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
          </div>
          <p>"On-time, clean work, and fair price. Will use again for a seasonal swap."</p>
          <div class="who">Alex P. • Verified</div>
        </div>

        <div class="review">
          <div class="stars">
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
          </div>
          <p>"Quick response and super professional. Texted my tire size and they handled the rest."</p>
          <div class="who">Nadia K. • Verified</div>
        </div>

        <!-- Duplicate set for seamless desktop scroll -->
        <div class="review">
          <div class="stars">
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
          </div>
          <p>"Professional, fast, and fair pricing. Came to my driveway and finished quickly."</p>
          <div class="who">Mike R. • Verified</div>
        </div>

        <div class="review">
          <div class="stars">
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
          </div>
          <p>"Saved me from a flat and got me back on the road fast. Highly recommended."</p>
          <div class="who">Sarah J. • Verified</div>
        </div>

        <div class="review">
          <div class="stars">
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
          </div>
          <p>"On-time, clean work, and fair price. Will use again for a seasonal swap."</p>
          <div class="who">Alex P. • Verified</div>
        </div>

        <div class="review">
          <div class="stars">
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
            <svg class="star" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2l3 7h7l-5.6 4.1 2.1 7L12 16.7 5.5 20.2l2.1-7L2 9h7l3-7z"/></svg>
          </div>
          <p>"Quick response and super professional. Texted my tire size and they handled the rest."</p>
          <div class="who">Nadia K. • Verified</div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="section-card">
      <h3 style="letter-spacing:2px;text-transform:uppercase;margin-bottom:12px;">FAQ</h3>
      <div style="display:grid;gap:14px;">
        <div>
          <strong>Do you offer mobile flat tire repair in Vancouver?</strong>
          <div class="muted">Yes. We come to your location across Vancouver and the Lower Mainland. Call or text for dispatch.</div>
        </div>
        <div>
          <strong>Can you repair sidewall damage?</strong>
          <div class="muted">Usually no (safety). We’ll inspect and recommend the safest option.</div>
        </div>
        <div>
          <strong>What should I send for the fastest quote?</strong>
          <div class="muted">Tire size (ex: 225/65R17), exact location, and service needed (flat repair or tire swap).</div>
        </div>
        <div>
          <strong>Do you serve Burnaby, Richmond, Surrey, or the North Shore?</strong>
          <div class="muted">Yes—call/text to confirm coverage and dispatch time.</div>
        </div>
      </div>
    </section>

    <!-- QUOTE -->
    <section id="quote" style="padding: 44px 0 20px;">
      <div class="section-card" style="max-width:720px;margin:0 auto;border-color: rgba(0,242,255,.32);">
        <h3 style="text-align:center;letter-spacing:2px;text-transform:uppercase;margin-bottom:10px;">Request Dispatch</h3>
        <p class="muted" style="text-align:center;margin-bottom:18px;">
          Fastest: include <strong>tire size</strong> + <strong>location</strong> + <strong>service needed</strong>.
        </p>

        <form class="form" onsubmit="sendEmail(event)">
          <label for="cName">Name</label>
          <input type="text" id="cName" name="name" placeholder="Your Name" required>

          <label for="cPhone">Phone</label>
          <input type="tel" id="cPhone" name="phone" inputmode="tel" placeholder="Your Phone Number" required>

          <label for="cDetails">Details</label>
          <textarea id="cDetails" name="details" rows="4" placeholder="Tire size (ex: 225/65R17) + location + flat repair or tire swap"></textarea>

          <button type="submit" class="submit">Send Request</button>

          <div style="margin-top:14px;text-align:center;color:rgba(255,255,255,.7);font-size:12px;">
            Or call now: <a href="tel:PHONE_NUMBER_HERE" style="color:var(--cyan);font-weight:900;" itemprop="telephone">PHONE_NUMBER_HERE</a>
          </div>
        </form>
      </div>
    </section>

    <footer>
      <div style="font-weight:900;letter-spacing:1px;">Mobile Tire Repair Vancouver</div>
      <div style="margin-top:6px;">Serving Vancouver, BC + Lower Mainland</div>
      <div style="margin-top:10px;">
        Call/Text: <a href="tel:PHONE_NUMBER_HERE">PHONE_NUMBER_HERE</a>
      </div>
      <div style="margin-top:10px; font-size:12px; opacity:.85;">
        Keywords: mobile tire repair vancouver • flat tire repair vancouver • tire repair near me • tire change at home vancouver
      </div>
    </footer>
  </main>

  <script>
    function sendEmail(e){
      e.preventDefault();
      const name = encodeURIComponent(document.getElementById('cName').value);
      const phone = encodeURIComponent(document.getElementById('cPhone').value);
      const details = encodeURIComponent(document.getElementById('cDetails').value);

      const body =
        `Client: ${name}%0D%0A` +
        `Phone: ${phone}%0D%0A` +
        `Details: ${details}%0D%0A` +
        `Service Area: Vancouver / Lower Mainland`;

      window.location.href = `mailto:mirzaartslan@gmail.com?subject=Mobile%20Tire%20Service%20Request%20(Vancouver)&body=${body}`;
    }
  </script>
</body>
</html>
