<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>AZAD AUDIO — Electronics & Sound</title>
  <meta name="description" content="AZAD AUDIO — Professional speakers, amplifiers, microphones, and accessories. WhatsApp +91 89497 43963 • HR.Azadaudio@gmail.com"/>
  <style>
    :root{
      --bg:#0e0e0f;        /* near-black */
      --card:#141417;      /* dark card */
      --muted:#9aa0a6;     /* muted text */
      --text:#f7f7f7;      /* primary text */
      --brand:#e31b23;     /* bold red */
      --brand-2:#c4121a;   /* darker red */
      --accent:#cfd8dc;    /* light grey */
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,"Helvetica Neue",Arial,"Apple Color Emoji","Segoe UI Emoji";}
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block}
    .container{max-width:1200px;margin:0 auto;padding:0 20px}/* Header */
header{position:sticky;top:0;z-index:50;background:rgba(14,14,15,.7);backdrop-filter:blur(8px);border-bottom:1px solid rgba(255,255,255,.06)}
.nav{display:flex;align-items:center;justify-content:space-between;padding:14px 0}
.nav-links{display:flex;gap:20px}
.nav a{font-weight:600;color:#eaeaea;opacity:.9}
.nav a:hover{opacity:1;color:#fff}
.cta{display:inline-flex;align-items:center;gap:8px;background:var(--brand);padding:10px 16px;border-radius:999px;font-weight:700;box-shadow:0 10px 20px rgba(227,27,35,.25)}
.cta:hover{background:var(--brand-2)}

/* Logo */
.logo{display:flex;align-items:center;gap:12px}
.logo-word{font-weight:900;letter-spacing:.5px}
.logo-word b{color:var(--brand)}
.tag{color:var(--muted);font-size:.85rem}

/* Hero */
.hero{position:relative;isolation:isolate}
.hero::before{content:"";position:absolute;inset:0;background:radial-gradient(1200px 500px at 50% -10%,rgba(227,27,35,.35),transparent 60%),
                               radial-gradient(600px 400px at 95% 10%,rgba(227,27,35,.18),transparent 60%),
                               linear-gradient(180deg,rgba(255,255,255,.06),transparent 40%)}
.hero-inner{display:grid;grid-template-columns:1.2fr .8fr;gap:40px;align-items:center;padding:64px 0}
.hero h1{font-size:clamp(32px,5vw,56px);line-height:1.04;margin:0}
.hero p{color:var(--accent);font-size:clamp(16px,2vw,18px)}
.pill{display:inline-block;margin-top:14px;padding:8px 12px;border:1px solid rgba(255,255,255,.15);border-radius:999px;font-size:.9rem;color:#eaeaea}
.hero-card{background:linear-gradient(180deg,#151519,#0f0f12);border:1px solid rgba(255,255,255,.06);border-radius:20px;padding:18px;box-shadow:0 10px 30px rgba(0,0,0,.35)}

/* Sections */
section{padding:72px 0;border-top:1px solid rgba(255,255,255,.06)}
h2{font-size:clamp(22px,3vw,32px);margin:0 0 22px}
.grid{display:grid;gap:22px}
@media (min-width: 860px){.grid.cols-3{grid-template-columns:repeat(3,1fr)}}
@media (min-width: 680px){.grid.cols-2{grid-template-columns:repeat(2,1fr)}}
.card{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:16px;overflow:hidden}
.card .body{padding:16px}
.price{font-weight:800;color:#fff}
.muted{color:var(--muted)}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;background:#1b1b1f;border:1px solid rgba(255,255,255,.08);padding:10px 14px;border-radius:12px;font-weight:700}
.btn:hover{border-color:rgba(255,255,255,.18)}
.btn-red{background:var(--brand);border-color:transparent}
.btn-red:hover{background:var(--brand-2)}

/* Footer */
footer{border-top:1px solid rgba(255,255,255,.06);padding:24px 0;color:var(--muted)}

/* Product badges */
.badge{display:inline-block;padding:6px 10px;border-radius:999px;border:1px solid rgba(255,255,255,.12);font-size:.75rem;color:#dfe3e6}

  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="container nav">
      <a href="#top" class="logo" aria-label="AZAD AUDIO home">
        <!-- Inline SVG logo: stylized speaker + waves -->
        <svg width="36" height="36" viewBox="0 0 64 64" fill="none" aria-hidden="true">
          <defs>
            <linearGradient id="g" x1="0" y1="0" x2="1" y2="1">
              <stop offset="0%" stop-color="#e31b23"/>
              <stop offset="100%" stop-color="#c4121a"/>
            </linearGradient>
          </defs>
          <rect x="8" y="14" width="20" height="36" rx="4" fill="url(#g)"/>
          <polygon points="28,24 40,20 40,44 28,40" fill="#f2f2f2" opacity=".9"/>
          <path d="M44 22c6 6 6 14 0 20" stroke="#f7f7f7" stroke-width="3" stroke-linecap="round" fill="none"/>
          <path d="M49 18c9 9 9 22 0 31" stroke="#e31b23" stroke-width="3" stroke-linecap="round" fill="none"/>
        </svg>
        <div>
          <div class="logo-word">AZAD <b>AUDIO</b></div>
          <div class="tag">Sound • Electronics</div>
        </div>
      </a>
      <nav class="nav-links">
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <a class="cta" href="https://wa.me/918949743963" target="_blank" rel="noopener">WhatsApp</a>
      </nav>
    </div>
  </header>  <!-- Hero -->  <section class="hero" id="top">
    <div class="container hero-inner">
      <div>
        <span class="pill">Trusted audio store</span>
        <h1>Powerful Sound. Professional Gear.</h1>
        <p>Speakers, amplifiers, microphones, mixers & accessories — selected for reliability and real-world performance.</p>
        <div style="display:flex;gap:12px;margin-top:18px;flex-wrap:wrap">
          <a class="btn-red" href="#products">Shop products</a>
          <a class="btn" href="mailto:HR.Azadaudio@gmail.com">Email us</a>
        </div>
      </div>
      <div class="hero-card">
        <img alt="Showcase equipment" src="https://images.unsplash.com/photo-1546443046-ed1ce6ffd1a9?q=80&w=1200&auto=format&fit=crop" />
      </div>
    </div>
  </section>  <!-- Products -->  <section id="products">
    <div class="container">
      <h2>Featured Products</h2>
      <div class="grid cols-3">
        <article class="card">
          <img src="https://images.unsplash.com/photo-1580894741223-6c4b2c8f5f05?q=80&w=1200&auto=format&fit=crop" alt="High Bass Speaker"/>
          <div class="body">
            <div class="badge">Speakers</div>
            <h3 style="margin:10px 0 6px">High Bass Speaker</h3>
            <div class="muted">12" woofer • 500W RMS</div>
            <div class="price" style="margin:10px 0">₹4,999</div>
            <a class="btn" href="https://wa.me/918949743963?text=I'm%20interested%20in%20High%20Bass%20Speaker" target="_blank" rel="noopener">Enquire on WhatsApp</a>
          </div>
        </article>
        <article class="card">
          <img src="https://images.unsplash.com/photo-1519671482749-fd09be7ccebf?q=80&w=1200&auto=format&fit=crop" alt="Professional Amplifier"/>
          <div class="body">
            <div class="badge">Amplifiers</div>
            <h3 style="margin:10px 0 6px">Professional Amplifier</h3>
            <div class="muted">2×350W • Class-AB</div>
            <div class="price" style="margin:10px 0">₹7,499</div>
            <a class="btn" href="https://wa.me/918949743963?text=I'm%20interested%20in%20Professional%20Amplifier" target="_blank" rel="noopener">Enquire on WhatsApp</a>
          </div>
        </article>
        <article class="card">
          <img src="https://images.unsplash.com/photo-1581276879432-15a19d654956?q=80&w=1200&auto=format&fit=crop" alt="Studio Microphone"/>
          <div class="body">
            <div class="badge">Microphones</div>
            <h3 style="margin:10px 0 6px">Studio Microphone</h3>
            <div class="muted">Large diaphragm • XLR</div>
            <div class="price" style="margin:10px 0">₹2,199</div>
            <a class="btn" href="https://wa.me/918949743963?text=I'm%20interested%20in%20Studio%20Microphone" target="_blank" rel="noopener">Enquire on WhatsApp</a>
          </div>
        </article>
      </div>
    </div>
  </section>  <!-- Categories -->  <section>
    <div class="container">
      <h2>Shop by Category</h2>
      <div class="grid cols-3">
        <div class="card"><div class="body"><strong>Speakers</strong><div class="muted">PA, portable, column</div></div></div>
        <div class="card"><div class="body"><strong>Amplifiers</strong><div class="muted">PA, power, integrated</div></div></div>
        <div class="card"><div class="body"><strong>Microphones</strong><div class="muted">Wired, wireless, lavalier</div></div></div>
      </div>
    </div>
  </section>  <!-- About -->  <section id="about">
    <div class="container">
      <h2>About AZAD AUDIO</h2>
      <div class="grid cols-2">
        <div class="card"><div class="body">
          <p>We help events, institutions, and creators sound their best. From compact portable systems to permanent installs, our focus is reliable audio that performs every day.</p>
          <ul style="margin:8px 0 0 18px;color:var(--accent)">
            <li>Curated gear from trusted manufacturers</li>
            <li>Setup guidance and after-sales support</li>
            <li>Competitive pricing for projects and bulk</li>
          </ul>
        </div></div>
        <div class="card"><div class="body">
          <p><strong>Business hours</strong><br/>Mon–Sat: 10:00–19:00</p>
          <p class="muted">Need a quote? Send us your list on WhatsApp — we usually respond quickly.</p>
          <a class="btn-red" href="https://wa.me/918949743963" target="_blank" rel="noopener">Chat on WhatsApp</a>
        </div></div>
      </div>
    </div>
  </section>  <!-- Contact -->  <section id="contact">
    <div class="container">
      <h2>Contact</h2>
      <div class="grid cols-2">
        <div class="card"><div class="body">
          <p><strong>Call / WhatsApp</strong><br/><a href="https://wa.me/918949743963" target="_blank" rel="noopener">+91 89497 43963</a></p>
          <p><strong>Email</strong><br/><a href="mailto:HR.Azadaudio@gmail.com">HR.Azadaudio@gmail.com</a></p>
        </div></div>
        <div class="card"><div class="body">
          <p class="muted">Prefer a quick message? Use WhatsApp — share your requirements and we'll suggest the right gear.</p>
          <a class="btn" href="#top">Back to top</a>
        </div></div>
      </div>
    </div>
  </section>  <footer>
    <div class="container" style="display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap">
      <div>© <span id="year"></span> AZAD AUDIO. All rights reserved.</div>
      <div class="muted">Made with ♥ for clear sound.</div>
    </div>
  </footer>  <script>
    // Set current year
    document.getElementById('year').textContent = new Date().getFullYear();
    // Smooth scroll for in-page links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click',e=>{
        const id=a.getAttribute('href');
        if(id.length>1){e.preventDefault();document.querySelector(id).scrollIntoView({behavior:'smooth'});} 
      });
    });
  </script></body>
</html>
