<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pilates is the Answer | Stacey Jernigan, M.S., M.T., NCPT</title>
<meta name="description" content="Private Pilates training, instructor mentoring, and continuing education with Master Trainer Stacey Jernigan in Sarasota, FL.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,400;0,9..144,500;0,9..144,600;1,9..144,400;1,9..144,500&family=Work+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --sand: #E7DFCE;
    --sand-deep: #DCD2BB;
    --cream: #F8F3E7;
    --white: #FFFDF8;
    --ink: #2E2A22;
    --ink-soft: #5A5346;
    --forest: #4B5D45;
    --forest-deep: #384732;
    --ochre: #BD7B3B;
    --ochre-soft: #E3B98A;
    --line: #A9805A;
    --radius: 2px;
  }

  *{ box-sizing: border-box; margin:0; padding:0; }

  html{ scroll-behavior: smooth; }

  body{
    background: var(--sand);
    color: var(--ink);
    font-family: 'Work Sans', sans-serif;
    font-weight: 400;
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
  }

  h1,h2,h3,h4{
    font-family: 'Fraunces', serif;
    font-weight: 500;
    line-height: 1.1;
    letter-spacing: -0.01em;
    color: var(--ink);
  }

  a{ color: inherit; text-decoration:none; }
  button{ font-family: inherit; cursor: pointer; }
  img{ max-width:100%; display:block; }

  :focus-visible{
    outline: 2px solid var(--ochre);
    outline-offset: 3px;
  }

  .eyebrow{
    font-family: 'Work Sans', sans-serif;
    font-size: 0.78rem;
    letter-spacing: 0.16em;
    text-transform: uppercase;
    color: var(--forest);
    font-weight: 600;
  }

  .wrap{
    max-width: 1120px;
    margin: 0 auto;
    padding: 0 32px;
  }

  /* ---------- NAV ---------- */
  header.site-nav{
    position: sticky;
    top:0;
    z-index: 100;
    background: rgba(231,223,206,0.92);
    backdrop-filter: blur(8px);
    border-bottom: 1px solid rgba(46,42,34,0.1);
  }

  .nav-inner{
    max-width: 1120px;
    margin: 0 auto;
    padding: 14px 32px;
    display:flex;
    align-items:center;
    justify-content: space-between;
  }

  .brand{
    display:flex;
    align-items:center;
    gap:12px;
  }

  .brand svg{ width:38px; height:38px; flex-shrink:0; }

  .brand-text{
    display:flex;
    flex-direction: column;
    line-height:1.15;
  }

  .brand-text .name{
    font-family:'Fraunces', serif;
    font-style: italic;
    font-size: 1.15rem;
    font-weight:500;
  }

  .brand-text .sub{
    font-size: 0.68rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--ink-soft);
  }

  nav.links{
    display:flex;
    align-items:center;
    gap: 6px;
  }

  nav.links > a, .dropdown > button{
    font-size: 0.9rem;
    font-weight:500;
    padding: 10px 14px;
    border-radius: var(--radius);
    background:none;
    border:none;
    color: var(--ink);
    display:flex;
    align-items:center;
    gap:5px;
    transition: color .15s ease;
  }

  nav.links > a:hover, .dropdown > button:hover{ color: var(--forest); }

  .dropdown{ position:relative; }
  .dropdown > button svg{ width:9px; height:9px; transition: transform .2s ease; }
  .dropdown.open > button svg{ transform: rotate(180deg); }

  .dropdown-menu{
    position:absolute;
    top: calc(100% + 6px);
    left:50%;
    transform: translateX(-50%) translateY(-6px);
    background: var(--white);
    border: 1px solid rgba(46,42,34,0.1);
    box-shadow: 0 12px 28px rgba(46,42,34,0.14);
    min-width: 240px;
    padding: 8px;
    opacity:0;
    visibility:hidden;
    transition: opacity .18s ease, transform .18s ease;
  }

  .dropdown.open .dropdown-menu{
    opacity:1;
    visibility:visible;
    transform: translateX(-50%) translateY(0);
  }

  .dropdown-menu a{
    display:block;
    padding: 10px 12px;
    font-size: 0.87rem;
    border-radius: var(--radius);
  }
  .dropdown-menu a:hover{ background: var(--cream); color: var(--forest); }

  .nav-cta{
    background: var(--forest);
    color: var(--white) !important;
    margin-left: 6px;
  }
  .nav-cta:hover{ background: var(--forest-deep); color: var(--white); }

  .nav-toggle{
    display:none;
    background:none;
    border:none;
    width: 32px; height:24px;
    position:relative;
  }
  .nav-toggle span, .nav-toggle span::before, .nav-toggle span::after{
    content:'';
    position:absolute;
    left:0; right:0;
    height:2px;
    background: var(--ink);
    transition: all .2s ease;
  }
  .nav-toggle span{ top:11px; }
  .nav-toggle span::before{ top:-8px; }
  .nav-toggle span::after{ top:8px; }

  /* ---------- SECTION DIVIDER (signature spring line) ---------- */
  .divider{
    display:block;
    width:100%;
    height: 36px;
  }
  .divider svg{ width:100%; height:100%; display:block; }

  /* ---------- HERO ---------- */
  .hero{
    position:relative;
    overflow:hidden;
    padding: 100px 0 70px;
  }

  .hero-inner{
    display:grid;
    grid-template-columns: 1.05fr 0.95fr;
    gap: 48px;
    align-items:center;
  }

  .hero h1{
    font-size: clamp(2.4rem, 4.6vw, 3.7rem);
    margin: 18px 0 22px;
  }
  .hero h1 em{
    font-style: italic;
    color: var(--forest);
  }

  .hero p.lede{
    font-size: 1.08rem;
    color: var(--ink-soft);
    max-width: 46ch;
    margin-bottom: 34px;
  }

  .btn-row{ display:flex; gap:14px; flex-wrap:wrap; }

  .btn{
    display:inline-block;
    padding: 14px 26px;
    font-size: 0.92rem;
    font-weight:600;
    border-radius: var(--radius);
    border: 1.5px solid var(--ink);
    transition: all .18s ease;
  }
  .btn-primary{
    background: var(--forest);
    border-color: var(--forest);
    color: var(--white);
  }
  .btn-primary:hover{ background: var(--forest-deep); border-color: var(--forest-deep); }
  .btn-ghost{
    background: transparent;
    color: var(--ink);
  }
  .btn-ghost:hover{ background: var(--ink); color: var(--sand); }

  .hero-art{
    position:relative;
    aspect-ratio: 1/1.05;
  }
  .hero-art svg{ width:100%; height:100%; }

  .draw-path{
    stroke-dasharray: 1400;
    stroke-dashoffset: 1400;
    animation: draw 2.6s ease forwards .3s;
  }
  @media (prefers-reduced-motion: reduce){
    .draw-path{ animation: none; stroke-dashoffset:0; }
  }
  @keyframes draw{ to{ stroke-dashoffset:0; } }

  /* ---------- GENERIC SECTION ---------- */
  section{ padding: 86px 0; position: relative; }
  section .eyebrow{ margin-bottom: 14px; }
  section h2{ font-size: clamp(1.9rem, 3.2vw, 2.6rem); margin-bottom: 28px; }

  /* ---------- ABOUT ---------- */
  #about{ background: var(--cream); }
  .about-grid{
    display:grid;
    grid-template-columns: 0.85fr 1.15fr;
    gap: 56px;
    align-items:start;
  }

  .portrait-frame{
    position: sticky;
    top: 100px;
    aspect-ratio: 4/5;
    background: var(--sand-deep);
    border-radius: var(--radius);
    display:flex;
    align-items:center;
    justify-content:center;
    flex-direction: column;
    gap: 14px;
    border: 1px solid rgba(46,42,34,0.12);
  }
  .portrait-frame svg{ width: 40%; }
  .portrait-frame span{
    font-size: 0.72rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--ink-soft);
    text-align:center;
    padding: 0 30px;
  }

  .credentials{
    font-size: 0.8rem;
    letter-spacing: 0.04em;
    color: var(--forest);
    font-weight: 600;
    margin-bottom: 22px;
    text-transform: uppercase;
  }

  .bio p{ margin-bottom: 18px; color: var(--ink-soft); font-size: 1rem; max-width: 62ch; }
  .bio strong{ color: var(--ink); font-weight: 600; }

  blockquote.pull{
    font-family: 'Fraunces', serif;
    font-style: italic;
    font-size: clamp(1.35rem, 2.4vw, 1.7rem);
    color: var(--forest-deep);
    border-left: 3px solid var(--ochre);
    padding: 4px 0 4px 26px;
    margin: 34px 0;
    line-height: 1.4;
  }
  blockquote.pull cite{
    display:block;
    font-family: 'Work Sans', sans-serif;
    font-style: normal;
    font-size: 0.78rem;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    color: var(--ink-soft);
    margin-top: 10px;
  }

  /* ---------- SERVICES ---------- */
  #services{ background: var(--sand); }
  .service-grid{
    display:grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 18px;
  }

  .service-card{
    background: var(--white);
    border: 1px solid rgba(46,42,34,0.1);
    border-radius: var(--radius);
    padding: 30px;
    scroll-margin-top: 100px;
    transition: border-color .18s ease, transform .18s ease;
  }
  .service-card:hover{ border-color: var(--ochre); transform: translateY(-3px); }

  .service-num{
    font-family:'Fraunces', serif;
    font-style: italic;
    font-size: 0.95rem;
    color: var(--ochre);
    margin-bottom: 12px;
    display:block;
  }

  .service-card h3{ font-size: 1.3rem; margin-bottom: 12px; }
  .service-card p{ color: var(--ink-soft); font-size: 0.95rem; }

  /* ---------- TESTIMONIALS ---------- */
  #testimonials{ background: var(--forest-deep); color: var(--white); }
  #testimonials .eyebrow{ color: var(--ochre-soft); }
  #testimonials h2{ color: var(--white); }
  #testimonials .section-note{
    color: rgba(255,253,248,0.65);
    font-size: 0.85rem;
    margin-top: -14px;
    margin-bottom: 34px;
  }

  .testi-grid{
    display:grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
  }

  .testi-card{
    background: rgba(255,253,248,0.06);
    border: 1px solid rgba(255,253,248,0.14);
    border-radius: var(--radius);
    padding: 28px;
  }
  .testi-card p{
    font-family: 'Fraunces', serif;
    font-style: italic;
    font-size: 1.05rem;
    line-height:1.5;
    margin-bottom: 18px;
  }
  .testi-card .who{ font-size: 0.8rem; letter-spacing: 0.05em; color: var(--ochre-soft); text-transform: uppercase; }

  /* ---------- PRICING ---------- */
  #pricing{ background: var(--cream); text-align:center; }
  #pricing .wrap{ max-width: 720px; }
  #pricing h2{ margin-bottom: 16px; }
  #pricing p{ color: var(--ink-soft); font-size: 1.05rem; margin-bottom: 32px; }
  .price-panel{
    background: var(--white);
    border: 1px dashed var(--line);
    border-radius: var(--radius);
    padding: 46px 32px;
  }

  /* ---------- CONTACT ---------- */
  #contact{ background: var(--sand); }
  .contact-grid{
    display:grid;
    grid-template-columns: 0.9fr 1.1fr;
    gap: 56px;
  }

  .contact-info p{ color: var(--ink-soft); margin-bottom: 26px; max-width: 42ch; }
  .info-row{ margin-bottom: 22px; }
  .info-row .label{
    font-size: 0.72rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--forest);
    font-weight: 600;
    margin-bottom: 4px;
  }
  .info-row .value{ font-size: 1rem; }

  .podcast-tag{
    display:inline-flex;
    align-items:center;
    gap:10px;
    margin-top: 8px;
    padding: 12px 16px;
    background: var(--white);
    border-radius: var(--radius);
    border: 1px solid rgba(46,42,34,0.1);
    font-size: 0.88rem;
  }

  form.contact-form{
    background: var(--white);
    border: 1px solid rgba(46,42,34,0.1);
    border-radius: var(--radius);
    padding: 32px;
    display:grid;
    gap: 18px;
  }

  .field label{
    display:block;
    font-size: 0.78rem;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: var(--ink-soft);
    margin-bottom: 6px;
    font-weight: 600;
  }
  .field input, .field textarea{
    width:100%;
    padding: 12px 14px;
    border: 1px solid rgba(46,42,34,0.2);
    border-radius: var(--radius);
    background: var(--sand);
    font-family: inherit;
    font-size: 0.95rem;
    color: var(--ink);
  }
  .field textarea{ resize: vertical; min-height: 110px; }
  .field input:focus, .field textarea:focus{ outline: 2px solid var(--ochre); outline-offset: 1px; border-color: transparent; }

  form.contact-form .btn{ width: max-content; border:none; }

  /* ---------- FOOTER ---------- */
  footer{
    background: var(--ink);
    color: rgba(255,253,248,0.75);
    padding: 44px 0 30px;
  }
  .footer-inner{
    display:flex;
    justify-content: space-between;
    align-items:center;
    flex-wrap:wrap;
    gap: 18px;
  }
  .footer-brand{ display:flex; align-items:center; gap:10px; }
  .footer-brand svg{ width:26px; height:26px; }
  .footer-brand span{ font-family:'Fraunces', serif; font-style: italic; color: var(--white); }
  footer .socials{ display:flex; gap: 16px; }
  footer .socials a{ font-size: 0.85rem; color: rgba(255,253,248,0.75); }
  footer .socials a:hover{ color: var(--ochre-soft); }
  footer .copy{ font-size: 0.78rem; color: rgba(255,253,248,0.45); margin-top: 18px; text-align:center; }

  /* ---------- RESPONSIVE ---------- */
  @media (max-width: 880px){
    nav.links{
      position:fixed;
      top: 63px; left:0; right:0;
      background: var(--sand);
      flex-direction: column;
      align-items: stretch;
      padding: 10px 20px 24px;
      border-bottom: 1px solid rgba(46,42,34,0.1);
      display:none;
      gap:0;
    }
    nav.links.mobile-open{ display:flex; }
    .dropdown{ width:100%; }
    .dropdown > button{ width:100%; justify-content: space-between; }
    .dropdown-menu{
      position:static;
      transform:none;
      box-shadow:none;
      border:none;
      display:none;
      width:100%;
      padding-left: 10px;
      opacity:1; visibility:visible;
    }
    .dropdown.open .dropdown-menu{ display:block; }
    .nav-cta{ margin-left:0; margin-top:8px; text-align:center; }
    .nav-toggle{ display:block; }

    .hero-inner{ grid-template-columns: 1fr; }
    .hero-art{ order:-1; max-width: 320px; margin: 0 auto; }

    .about-grid{ grid-template-columns: 1fr; }
    .portrait-frame{ position:static; max-width: 280px; margin: 0 auto 20px; }

    .service-grid{ grid-template-columns: 1fr; }
    .testi-grid{ grid-template-columns: 1fr; }
    .contact-grid{ grid-template-columns: 1fr; }
  }

  @media (max-width: 480px){
    .wrap, .nav-inner{ padding-left: 20px; padding-right:20px; }
    .hero{ padding: 70px 0 50px; }
    section{ padding: 60px 0; }
  }
</style>
</head>
<body>

<header class="site-nav">
  <div class="nav-inner">
    <a href="#top" class="brand">
      <svg viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <circle cx="20" cy="20" r="19" stroke="#4B5D45" stroke-width="1.4"/>
        <path d="M9 24C12 15 15 15 17 20C19 25 22 25 24 20C26 15 29 15 31 20" stroke="#BD7B3B" stroke-width="1.8" stroke-linecap="round"/>
      </svg>
      <span class="brand-text">
        <span class="name">Pilates is the Answer</span>
        <span class="sub">Stacey Jernigan, NCPT</span>
      </span>
    </a>

    <button class="nav-toggle" aria-label="Toggle navigation" aria-expanded="false" id="navToggle"><span></span></button>

    <nav class="links" id="navLinks">
      <a href="#about">About Me</a>
      <div class="dropdown" id="servicesDropdown">
        <button aria-haspopup="true" aria-expanded="false" id="servicesBtn">
          Services
          <svg viewBox="0 0 10 6" fill="none"><path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.4"/></svg>
        </button>
        <div class="dropdown-menu">
          <a href="#pilates-training">Pilates Training</a>
          <a href="#master-trainer-mentoring">Master Trainer Mentoring</a>
          <a href="#cec-workshop">CEC Workshop</a>
          <a href="#core360">Core360 Mat Certification</a>
        </div>
      </div>
      <a href="#testimonials">Testimonials</a>
      <a href="#pricing">Pricing</a>
      <a href="#contact" class="nav-cta">Contact</a>
    </nav>
  </div>
</header>

<main id="top">

  <!-- HERO -->
  <section class="hero">
    <div class="wrap hero-inner">
      <div>
        <p class="eyebrow">Private Pilates Practice &middot; Sarasota, FL</p>
        <h1>Change happens<br>through <em>movement</em>.</h1>
        <p class="lede">Private Pilates training, instructor mentoring, and continuing education with Stacey Jernigan, M.S., M.T., NCPT &mdash; built around one belief: the right movement, at the right time, can change everything.</p>
        <div class="btn-row">
          <a href="#about" class="btn btn-primary">Meet Stacey</a>
          <a href="#contact" class="btn btn-ghost">Get in Touch</a>
        </div>
      </div>
      <div class="hero-art" aria-hidden="true">
        <svg viewBox="0 0 400 420" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path class="draw-path" d="M40 60 C 120 20, 160 100, 100 140 C 40 180, 80 240, 160 220 C 240 200, 220 130, 300 150 C 360 166, 350 230, 300 260 C 250 290, 260 350, 340 360"
            stroke="#4B5D45" stroke-width="2.5" stroke-linecap="round"/>
          <circle cx="40" cy="60" r="6" fill="#BD7B3B"/>
          <circle cx="340" cy="360" r="6" fill="#BD7B3B"/>
          <path d="M60 395 C 120 380, 260 380, 330 400" stroke="#A9805A" stroke-width="1.2" stroke-dasharray="3 6" opacity="0.6"/>
        </svg>
      </div>
    </div>
  </section>

  <div class="divider" aria-hidden="true">
    <svg viewBox="0 0 1200 36" preserveAspectRatio="none"><path d="M0 18 Q 30 2, 60 18 T 120 18 T 180 18 T 240 18 T 300 18 T 360 18 T 420 18 T 480 18 T 540 18 T 600 18 T 660 18 T 720 18 T 780 18 T 840 18 T 900 18 T 960 18 T 1020 18 T 1080 18 T 1140 18 T 1200 18" stroke="#A9805A" stroke-width="1.4" fill="none" opacity="0.5"/></svg>
  </div>

  <!-- ABOUT -->
  <section id="about">
    <div class="wrap about-grid">
      <div class="portrait-frame">
        <svg viewBox="0 0 100 100" fill="none" aria-hidden="true">
          <circle cx="50" cy="50" r="46" stroke="#4B5D45" stroke-width="1.2" stroke-dasharray="4 5"/>
          <text x="50" y="58" text-anchor="middle" font-family="Fraunces, serif" font-style="italic" font-size="30" fill="#4B5D45">SJ</text>
        </svg>
        <span>Portrait coming soon</span>
      </div>

      <div>
        <p class="eyebrow">About Stacey</p>
        <h2>Stacey Jernigan, M.S., M.T., NCPT</h2>
        <p class="credentials">M.S. Human Development &amp; Family Studies &nbsp;&middot;&nbsp; Master Trainer &nbsp;&middot;&nbsp; Nationally Certified Pilates Teacher</p>

        <div class="bio">
          <p>I've been teaching Pilates for over a decade, but my journey started after a serious car accident left me dealing with chronic back pain. When a friend suggested I try Pilates Reformer, I was skeptical. But after just one session, I couldn't believe how much better my back felt. I was hooked, and I knew I wanted to learn everything I could so I could help others experience that same transformation.</p>

          <p>With a Master's degree in Human Development and Family Studies, I've always loved working with people and helping them discover what they're capable of. Throughout my career, I've had the privilege of working with clients of all ages and abilities &mdash; from a <strong>12-year-old dancer</strong> looking to improve her performance, to a <strong>teenager with Polio</strong> building strength and mobility, to an <strong>NFL athlete</strong> focused on speed and agility, and an <strong>88-year-old</strong> wanting better posture, balance, and even a stronger golf game. Every client has taught me something, and I love creating sessions that meet each person where they are.</p>

          <blockquote class="pull">
            "Change happens through movement, and movement heals."
            <cite>Joseph Pilates</cite>
          </blockquote>

          <p>In addition to Pilates, I have experience in Mommy and Me Fitness, Senior Fitness, and athlete-specific training. After several years of teaching private and group classes, I became a Master Trainer, and mentoring future Pilates instructors has become one of my greatest passions. Watching my students grow into confident, knowledgeable teachers is incredibly rewarding.</p>

          <p>When I'm not teaching, you'll usually find me with my amazing son, who keeps me laughing and on my toes every day. I also love paddleboarding, listening to music, spending time at the beach, and enjoying all that life in Sarasota has to offer.</p>

          <p>Whether I'm teaching a client, mentoring an instructor, or co-hosting the <strong>Pilates Is the Answer</strong> podcast with my talented colleague Pearl, my goal is to help as many people as possible discover the healing power of Pilates. It has the ability to change lives in ways you never expect &mdash; and sometimes, it really is the answer to questions you didn't even know you had.</p>
        </div>
      </div>
    </div>
  </section>

  <div class="divider" aria-hidden="true">
    <svg viewBox="0 0 1200 36" preserveAspectRatio="none"><path d="M0 18 Q 30 34, 60 18 T 120 18 T 180 18 T 240 18 T 300 18 T 360 18 T 420 18 T 480 18 T 540 18 T 600 18 T 660 18 T 720 18 T 780 18 T 840 18 T 900 18 T 960 18 T 1020 18 T 1080 18 T 1140 18 T 1200 18" stroke="#A9805A" stroke-width="1.4" fill="none" opacity="0.5"/></svg>
  </div>

  <!-- SERVICES -->
  <section id="services">
    <div class="wrap">
      <p class="eyebrow">What I Offer</p>
      <h2>Services</h2>
      <div class="service-grid">

        <div class="service-card" id="pilates-training">
          <span class="service-num">01</span>
          <h3>Pilates Training</h3>
          <p>Private, one-on-one Pilates sessions tailored to your body, your goals, and where you are today &mdash; whether that's recovering from injury, building core strength, or training for peak performance.</p>
        </div>

        <div class="service-card" id="master-trainer-mentoring">
          <span class="service-num">02</span>
          <h3>Master Trainer Mentoring</h3>
          <p>One-on-one mentoring for instructors ready to deepen their practice and sharpen their teaching, guided by more than a decade of hands-on experience across every kind of client.</p>
        </div>

        <div class="service-card" id="cec-workshop">
          <span class="service-num">03</span>
          <h3>CEC Workshop</h3>
          <p>Continuing education workshops for certified instructors looking to expand their skill set, stay current, and earn CECs toward recertification.</p>
        </div>

        <div class="service-card" id="core360">
          <span class="service-num">04</span>
          <h3>Core360 Mat Certification</h3>
          <p>A comprehensive mat certification program preparing new instructors to teach with clarity, confidence, and a strong foundation in the fundamentals.</p>
        </div>

      </div>
    </div>
  </section>

  <div class="divider" aria-hidden="true">
    <svg viewBox="0 0 1200 36" preserveAspectRatio="none"><path d="M0 18 Q 30 2, 60 18 T 120 18 T 180 18 T 240 18 T 300 18 T 360 18 T 420 18 T 480 18 T 540 18 T 600 18 T 660 18 T 720 18 T 780 18 T 840 18 T 900 18 T 960 18 T 1020 18 T 1080 18 T 1140 18 T 1200 18" stroke="#E3B98A" stroke-width="1.4" fill="none" opacity="0.7"/></svg>
  </div>

  <!-- TESTIMONIALS -->
  <section id="testimonials">
    <div class="wrap">
      <p class="eyebrow">Client Stories</p>
      <h2>Testimonials</h2>
      <p class="section-note">Sample testimonials shown below &mdash; swap in quotes from your own clients.</p>
      <div class="testi-grid">
        <div class="testi-card">
          <p>"I came to Stacey after months of lower back pain that nothing else had fixed. Within a few sessions I felt stronger and more in control of my own body than I had in years."</p>
          <div class="who">Private client, back rehabilitation</div>
        </div>
        <div class="testi-card">
          <p>"Stacey's mentoring changed how I teach. She has a way of explaining the 'why' behind every cue that made me a far more confident instructor."</p>
          <div class="who">Instructor, Master Trainer Mentoring</div>
        </div>
        <div class="testi-card">
          <p>"At 70, I didn't expect Pilates to change my golf game &mdash; but my balance and posture are the best they've been in decades."</p>
          <div class="who">Private client, senior fitness</div>
        </div>
      </div>
    </div>
  </section>

  <!-- PRICING -->
  <section id="pricing">
    <div class="wrap">
      <p class="eyebrow">Investment</p>
      <h2>Pricing</h2>
      <p>Every body is different, and so is every plan. Reach out for current rates on private sessions, mentoring, and workshops.</p>
      <div class="price-panel">
        <p style="color:var(--ink-soft); margin-bottom:22px;">Pricing details coming soon.</p>
        <a href="#contact" class="btn btn-primary">Request Pricing</a>
      </div>
    </div>
  </section>

  <div class="divider" aria-hidden="true">
    <svg viewBox="0 0 1200 36" preserveAspectRatio="none"><path d="M0 18 Q 30 34, 60 18 T 120 18 T 180 18 T 240 18 T 300 18 T 360 18 T 420 18 T 480 18 T 540 18 T 600 18 T 660 18 T 720 18 T 780 18 T 840 18 T 900 18 T 960 18 T 1020 18 T 1080 18 T 1140 18 T 1200 18" stroke="#A9805A" stroke-width="1.4" fill="none" opacity="0.5"/></svg>
  </div>

  <!-- CONTACT -->
  <section id="contact">
    <div class="wrap contact-grid">
      <div class="contact-info">
        <p class="eyebrow">Get In Touch</p>
        <h2>Contact</h2>
        <p>Have a question about private training, mentoring, or upcoming workshops? Send a message and I'll get back to you soon.</p>

        <div class="info-row">
          <div class="label">Email</div>
          <div class="value">hello@pilatesistheanswer.com</div>
        </div>
        <div class="info-row">
          <div class="label">Location</div>
          <div class="value">Sarasota, FL</div>
        </div>
        <div class="info-row">
          <div class="label">Instagram</div>
          <div class="value">@pilatesistheanswer</div>
        </div>

        <div class="podcast-tag">🎙️ Catch the <strong>Pilates Is the Answer</strong> podcast, co-hosted with Pearl</div>
      </div>

      <form class="contact-form" action="mailto:hello@pilatesistheanswer.com" method="post" enctype="text/plain">
        <div class="field">
          <label for="name">Name</label>
          <input type="text" id="name" name="name" required>
        </div>
        <div class="field">
          <label for="email">Email</label>
          <input type="email" id="email" name="email" required>
        </div>
        <div class="field">
          <label for="message">Message</label>
          <textarea id="message" name="message" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Send Message</button>
      </form>
    </div>
  </section>

</main>

<footer>
  <div class="wrap footer-inner">
    <div class="footer-brand">
      <svg viewBox="0 0 40 40" fill="none" aria-hidden="true">
        <circle cx="20" cy="20" r="19" stroke="#E3B98A" stroke-width="1.2"/>
        <path d="M9 24C12 15 15 15 17 20C19 25 22 25 24 20C26 15 29 15 31 20" stroke="#BD7B3B" stroke-width="1.6" stroke-linecap="round"/>
      </svg>
      <span>Pilates is the Answer</span>
    </div>
    <div class="socials">
      <a href="#">Instagram</a>
      <a href="#">Podcast</a>
      <a href="#contact">Contact</a>
    </div>
  </div>
  <p class="copy">&copy; <span id="year"></span> Stacey Jernigan &middot; Pilates is the Answer. All rights reserved.</p>
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();

  // Mobile nav toggle
  const navToggle = document.getElementById('navToggle');
  const navLinks = document.getElementById('navLinks');
  navToggle.addEventListener('click', () => {
    const isOpen = navLinks.classList.toggle('mobile-open');
    navToggle.setAttribute('aria-expanded', isOpen);
  });

  // Services dropdown
  const dropdown = document.getElementById('servicesDropdown');
  const servicesBtn = document.getElementById('servicesBtn');
  servicesBtn.addEventListener('click', (e) => {
    e.stopPropagation();
    const isOpen = dropdown.classList.toggle('open');
    servicesBtn.setAttribute('aria-expanded', isOpen);
  });
  document.addEventListener('click', (e) => {
    if(!dropdown.contains(e.target)){
      dropdown.classList.remove('open');
      servicesBtn.setAttribute('aria-expanded', false);
    }
  });
  // Close mobile menu & dropdown after clicking a link
  document.querySelectorAll('nav.links a').forEach(a => {
    a.addEventListener('click', () => {
      navLinks.classList.remove('mobile-open');
      dropdown.classList.remove('open');
    });
  });
</script>

</body>
</html>
