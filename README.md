<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Wags & Whiskers Pet Sitting</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,600;9..144,700&family=Work+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #EDF0E4;
    --bg-panel: #FFFFFF;
    --ink: #1F2B22;
    --ink-soft: #4B5C4E;
    --marigold: #E8A33D;
    --coral: #E2685A;
    --line: #D3DAC7;
  }
  *{ box-sizing: border-box; margin:0; padding:0; }
  body{
    background: var(--bg);
    color: var(--ink);
    font-family: 'Work Sans', sans-serif;
    line-height: 1.5;
  }
  h1, h2, .display{
    font-family: 'Fraunces', serif;
  }
  .wrap{
    max-width: 780px;
    margin: 0 auto;
    padding: 0 24px;
  }

  /* Header */
  header{
    padding: 28px 0 8px;
  }
  header .wrap{
    display:flex;
    align-items:center;
    justify-content:space-between;
  }
  .logo{
    font-family:'Fraunces', serif;
    font-weight:700;
    font-size: 1.25rem;
    letter-spacing: -0.01em;
  }
  .logo span{ color: var(--marigold); }

  /* Hero */
  .hero{
    padding: 56px 0 24px;
    text-align:center;
  }
  .eyebrow{
    font-size: 0.8rem;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--coral);
    font-weight:600;
    margin-bottom: 14px;
  }
  .hero h1{
    font-size: clamp(2.2rem, 5vw, 3.4rem);
    font-weight: 600;
    line-height: 1.08;
    letter-spacing: -0.01em;
    margin-bottom: 18px;
  }
  .hero p{
    color: var(--ink-soft);
    font-size: 1.05rem;
    max-width: 480px;
    margin: 0 auto 40px;
  }

  /* Paw trail leading to the button — the signature element */
  .paw-trail{
    display:flex;
    justify-content:center;
    gap: 22px;
    margin-bottom: 6px;
  }
  .paw-trail svg{
    width: 20px;
    height: 20px;
    fill: var(--marigold);
    opacity: 0.55;
  }
  .paw-trail svg:nth-child(2){ transform: translateY(10px) rotate(-8deg); opacity:0.7; }
  .paw-trail svg:nth-child(3){ transform: translateY(2px) rotate(6deg); opacity:0.85; }
  .paw-trail svg:nth-child(4){ transform: translateY(8px) rotate(-4deg); opacity:1; fill: var(--coral); }

  .cta-btn{
    display:inline-block;
    background: var(--coral);
    color: #fff;
    font-family:'Work Sans', sans-serif;
    font-weight:600;
    font-size: 1rem;
    text-decoration:none;
    padding: 16px 36px;
    border-radius: 999px;
    box-shadow: 0 6px 0 #b64c40;
    transition: transform 0.12s ease, box-shadow 0.12s ease;
  }
  .cta-btn:hover{
    transform: translateY(2px);
    box-shadow: 0 4px 0 #b64c40;
  }
  .cta-btn:active{
    transform: translateY(6px);
    box-shadow: 0 0 0 #b64c40;
  }
  .cta-note{
    margin-top: 14px;
    font-size: 0.85rem;
    color: var(--ink-soft);
  }

  /* Services */
  .services{
    padding: 56px 0;
  }
  .services h2{
    font-size: 1.6rem;
    font-weight:600;
    text-align:center;
    margin-bottom: 32px;
  }
  .service-grid{
    display:grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px;
  }
  .service-card{
    background: var(--bg-panel);
    border: 1px solid var(--line);
    border-radius: 16px;
    padding: 24px 18px;
    text-align:center;
  }
  .service-card .icon{
    font-size: 1.8rem;
    margin-bottom: 10px;
  }
  .service-card h3{
    font-family:'Fraunces', serif;
    font-size: 1.05rem;
    font-weight:600;
    margin-bottom: 6px;
  }
  .service-card p{
    font-size: 0.88rem;
    color: var(--ink-soft);
  }

  /* About strip */
  .about{
    padding: 48px 0 64px;
    text-align:center;
  }
  .about p{
    max-width: 520px;
    margin: 0 auto;
    color: var(--ink-soft);
  }
  .about strong{ color: var(--ink); }

  footer{
    border-top: 1px solid var(--line);
    padding: 24px 0 40px;
    text-align:center;
    font-size: 0.82rem;
    color: var(--ink-soft);
  }

  @media (max-width: 600px){
    .service-grid{ grid-template-columns: 1fr; }
    .paw-trail{ gap: 14px; }
  }
</style>
</head>
<body>

<header>
  <div class="wrap">
    <div class="logo">Wags<span>&</span>Whiskers</div>
  </div>
</header>

<section class="hero">
  <div class="wrap">
    <div class="eyebrow">Pet sitting & dog walking</div>
    <h1>Someone your pet<br>already trusts.</h1>
    <p>Drop-ins, walks, and overnight stays for dogs and cats — booked in under a minute, handled with actual care.</p>

    <div class="paw-trail">
      <svg viewBox="0 0 24 24"><ellipse cx="12" cy="17" rx="6" ry="5"/><ellipse cx="5" cy="8" rx="2.2" ry="3"/><ellipse cx="10" cy="5" rx="2.2" ry="3"/><ellipse cx="15" cy="5" rx="2.2" ry="3"/><ellipse cx="19" cy="8" rx="2.2" ry="3"/></svg>
      <svg viewBox="0 0 24 24"><ellipse cx="12" cy="17" rx="6" ry="5"/><ellipse cx="5" cy="8" rx="2.2" ry="3"/><ellipse cx="10" cy="5" rx="2.2" ry="3"/><ellipse cx="15" cy="5" rx="2.2" ry="3"/><ellipse cx="19" cy="8" rx="2.2" ry="3"/></svg>
      <svg viewBox="0 0 24 24"><ellipse cx="12" cy="17" rx="6" ry="5"/><ellipse cx="5" cy="8" rx="2.2" ry="3"/><ellipse cx="10" cy="5" rx="2.2" ry="3"/><ellipse cx="15" cy="5" rx="2.2" ry="3"/><ellipse cx="19" cy="8" rx="2.2" ry="3"/></svg>
      <svg viewBox="0 0 24 24"><ellipse cx="12" cy="17" rx="6" ry="5"/><ellipse cx="5" cy="8" rx="2.2" ry="3"/><ellipse cx="10" cy="5" rx="2.2" ry="3"/><ellipse cx="15" cy="5" rx="2.2" ry="3"/><ellipse cx="19" cy="8" rx="2.2" ry="3"/></svg>
    </div>

    <!-- Replace the href below with your real Google Form link -->
    <a class="cta-btn" href="https://forms.gle/REPLACE_WITH_YOUR_FORM" target="_blank" rel="noopener">Book a visit</a>
    <div class="cta-note">Opens our booking form — takes about 2 minutes.</div>
  </div>
</section>

<section class="services">
  <div class="wrap">
    <h2>What we do</h2>
    <div class="service-grid">
      <div class="service-card">
        <div class="icon">🐕</div>
        <h3>Dog walks</h3>
        <p>30 or 60 minute walks, solo or with the neighborhood pack.</p>
      </div>
      <div class="service-card">
        <div class="icon">🏠</div>
        <h3>Drop-in visits</h3>
        <p>Feeding, litter, medication, and playtime while you're out.</p>
      </div>
      <div class="service-card">
        <div class="icon">🌙</div>
        <h3>Overnight stays</h3>
        <p>Someone in the house overnight so your pet isn't ever alone.</p>
      </div>
    </div>
  </div>
</section>

<section class="about">
  <div class="wrap">
    <p><strong>Local, insured, and genuinely pet-obsessed.</strong> Every visit gets a photo update, so you always know your pet is doing fine.</p>
  </div>
</section>

<footer>
  <div class="wrap">
    © 2026 Wags & Whiskers Pet Sitting · wagswhiskerspet.com
  </div>
</footer>

</body>
</html>
