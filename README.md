 lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MSHALE TECH – CYBER SERVICES</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg: #0f172a;           /* slate-900 */
      --bg-soft:#0b1228;       /* deeper navy */
      --card:#111827;          /* gray-900 */
      --muted:#94a3b8;         /* slate-400 */
      --text:#e5e7eb;          /* gray-200 */
      --brand:#22d3ee;         /* cyan-400 */
      --brand-2:#a78bfa;       /* violet-400 */
      --acc:#34d399;           /* emerald-400 */
      --warn:#f59e0b;          /* amber-500 */
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius: 18px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;height:100%;background: radial-gradient(1100px 600px at 10% -10%,rgba(34,211,238,.15),transparent 60%), radial-gradient(900px 600px at 100% 0,rgba(167,139,250,.15),transparent 60%), var(--bg); color:var(--text); font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;}
    a{color:inherit; text-decoration:none}
    .container{max-width:1100px; margin:0 auto; padding: 28px 18px}
    .pill{display:inline-flex; gap:8px; align-items:center; padding:8px 12px; border-radius:999px; background: linear-gradient(90deg, rgba(34,211,238,.12), rgba(167,139,250,.12)); border:1px solid rgba(255,255,255,.08); color:var(--muted); font-weight:600; letter-spacing:.2px}
    .hero{padding:76px 0 36px}
    .hero h1{font-size: clamp(28px, 5vw, 56px); line-height:1.05; margin:14px 0; font-weight:800;}
    .grad{background: linear-gradient(90deg,var(--brand),var(--brand-2)); -webkit-background-clip:text; background-clip:text; color:transparent}
    .hero p{max-width:720px; color:var(--muted); font-size: clamp(14px, 2.4vw, 18px)}.cta{display:flex; gap:12px; flex-wrap:wrap; margin-top:26px}
.btn{padding:14px 18px; border-radius:12px; font-weight:700; border:1px solid rgba(255,255,255,.12); background:linear-gradient(180deg, rgba(255,255,255,.08), rgba(255,255,255,.04)); backdrop-filter: blur(6px); box-shadow:var(--shadow); transition:.2s transform, .2s box-shadow}
.btn:hover{transform:translateY(-1px); box-shadow:0 16px 40px rgba(0,0,0,.45)}
.btn.primary{background: linear-gradient(90deg,var(--brand),var(--brand-2)); color:#0b1228; border: none}
.btn.ghost{color:var(--text)}

.section{padding:38px 0}
.section h2{font-size: clamp(22px, 3vw, 34px); margin: 0 0 14px;}
.sub{color:var(--muted); margin-top:4px}

.grid{display:grid; gap:16px}
@media (min-width:700px){ .grid.cols-3{grid-template-columns: repeat(3, 1fr)} }
@media (min-width:900px){ .grid.cols-4{grid-template-columns: repeat(4, 1fr)} }

.card{background: linear-gradient(180deg, rgba(17,24,39,1), rgba(11,18,40,1)); border:1px solid rgba(255,255,255,.06); padding:18px; border-radius: var(--radius); box-shadow: var(--shadow); position:relative; overflow:hidden}
.card .tick{position:absolute; right:10px; top:10px; opacity:.25}
.card h3{font-size:17px; margin:2px 0 6px}
.card p{color:var(--muted); font-size:14px; margin:0}

.pricing{display:grid; gap:16px}
@media (min-width:800px){ .pricing{grid-template-columns: repeat(5,1fr)} }
.price{background:linear-gradient(180deg, rgba(17,24,39,1), rgba(27,38,79,1)); border:1px solid rgba(255,255,255,.08); border-radius: var(--radius); padding:18px; box-shadow:var(--shadow)}
.price h4{margin:4px 0 6px; font-size:18px}
.price .amt{font-size:26px; font-weight:800}

.notice{margin-top:8px; font-size:14px; color:var(--muted)}

.footer{margin-top:48px; padding:26px 0 40px; border-top:1px solid rgba(255,255,255,.08); color:var(--muted)}
.badge{display:inline-flex; align-items:center; gap:8px; padding:10px 12px; border:1px dashed rgba(255,255,255,.18); border-radius:12px; color:var(--text)}

.tag{display:inline-flex; align-items:center; gap:8px; font-weight:700; color:var(--acc)}
.tag svg{opacity:.9}

  </style>
</head>
<body>
  <header class="container hero">
    <span class="pill">MSHALE TECH • Online Cyber Services</span>
    <h1><span class="grad">Stay Connected</span> & Get Your Digital Tasks Done Right</h1>
    <p>Fast, reliable help with common eCitizen & cyber services in Kenya — from HELB to KRA, SHIF, NSSF, passport, driving licence applications, and more. Chat us on WhatsApp to get started.</p>
    <div class="cta">
      <a class="btn primary" href="https://wa.me/254729829406" target="_blank" rel="noopener">Chat on WhatsApp</a>
      <a class="btn ghost" href="#services">View Services</a>
    </div>
  </header>  <main class="container">
    <!-- SERVICES -->
    <section id="services" class="section">
      <h2>Cyber Services</h2>
      <p class="sub">Legit, client‑authorized support only. We assist with official applications and profile updates.</p><div class="grid cols-3" style="margin-top:16px">
    <!-- Each card is a service -->
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>HELB – Change Payment Method</h3>
      <p>Switch between M‑Pesa ↔ Bank, or update bank details.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>HELB Profile Update (100%)</h3>
      <p>Complete and verify your portal profile.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Inter‑Institutional Transfer</h3>
      <p>Guidance through the official process.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>HELB Application</h3>
      <p>New applications and support with required docs.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>KRA PIN Registration</h3>
      <p>Get your KRA PIN and iTax setup.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>SHA/SHIF Registration</h3>
      <p>Enroll and update dependants where applicable.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>NSSF Registration</h3>
      <p>Create or update your NSSF account.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Police Clearance (Good Conduct)</h3>
      <p>Help booking and preparing for your eCitizen application.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Driving Licence</h3>
      <p>New DL application & renewal assistance.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>TSC Number Application</h3>
      <p>Step‑by‑step guidance and document checklist.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Passport Application</h3>
      <p>eCitizen form guidance and appointment booking.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>eTIMS Account Creation</h3>
      <p>Set up your eTIMS account correctly.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>CRB Clearance Guidance</h3>
      <p>Support to request your CRB status & clearance.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Social Media Boosting</h3>
      <p>Panel/software setup & account management.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Birth Certificate Application</h3>
      <p>Assist with online application & follow‑up.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Document Assistance</h3>
      <p>Corrections & updates when officially authorized.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Premium Apps (No Subscriptions)</h3>
      <p>One‑time setup for selected apps.</p>
    </article>
    <article class="card">
      <svg class="tick" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M20 6L9 17l-5-5"/></svg>
      <h3>Marriage Certificate Application</h3>
      <p>Guidance on the application process.</p>
    </article>
  </div>
  <p class="notice">Note: First come, first served.</p>
</section>

<!-- VPN PACKAGES -->
<section class="section" id="vpn">
  <div class="tag" style="margin-bottom:8px">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><path d="M2 12h20M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
    AIRTEL Unlimited – VPN Files Available
  </div>
  <h2>Stay Connected</h2>
  <p class="sub">HTTP Injector • HTTP Custom • Dark Tunnel • v2ray (EV2ray)</p>

  <div class="pricing" style="margin-top:16px">
    <div class="price"><h4>4 Days</h4><div class="amt">KSh 50</div></div>
    <div class="price"><h4>1 Week</h4><div class="amt">KSh 80</div></div>
    <div class="price"><h4>10 Days</h4><div class="amt">KSh 100</div></div>
    <div class="price"><h4>15 Days</h4><div class="amt">KSh 150</div></div>
    <div class="price"><h4>30 Days</h4><div class="amt">KSh 300</div></div>
  </div>

  <div class="cta" style="margin-top:18px">
    <a class="btn primary" href="https://wa.me/254729829406" target="_blank" rel="noopener">Order on WhatsApp</a>
    <a class="btn" href="#contact">See Contact</a>
  </div>
  <p class="notice">Powered by <strong>MSHALE‑TECH</strong> 🔥🤝✅♨️</p>
</section>

<!-- CONTACT -->
<section id="contact" class="section">
  <h2>Contact</h2>
  <p class="sub">Have a question? Message us and we’ll guide you through the right process.</p>
  <div class="cta" style="margin-top:12px">
    <a class="btn primary" href="https://wa.me/254729829406" target="_blank" rel="noopener">WhatsApp: +254 729 829 406</a>
    <a class="btn ghost" href="#services">Back to Services</a>
  </div>
</section>

  </main>  <footer class="container footer">
    <div class="badge">
      <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20 7l-8 10-5-5"/></svg>
      Legit, client‑authorized support only • © <span id="year"></span> Mshale Tech
    </div>
  </footer>  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script></body>
