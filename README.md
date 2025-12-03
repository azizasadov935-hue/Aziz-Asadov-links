# Aziz-Asadov-links
“Shaxsiy va kanallar uchun tezkor link sahifasi”
<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<title>Aziz Asadov — Havolalar</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#243b6b">
<style>
  :root{
    --bg-1:#4b6cb7;
    --bg-2:#182848;
    --card-bg: rgba(255,255,255,0.10);
    --card-hover: rgba(255,255,255,0.22);
    --accent: #ffd166;
  }
  *{box-sizing:border-box}
  body{
    margin:0;
    font-family:Inter, Arial, sans-serif;
    background: linear-gradient(135deg, var(--bg-1), var(--bg-2));
    color:#fff;
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    padding:20px;
  }

  .container{
    width:100%;
    max-width:460px;
    background:rgba(255,255,255,0.07);
    border-radius:20px;
    padding:32px;
    text-align:center;
    backdrop-filter: blur(8px);
    box-shadow: 0 10px 30px rgba(0,0,0,0.35);
    animation:fadeIn 450ms ease both;
  }

  .avatar{
    width:120px;
    height:120px;
    border-radius:50%;
    object-fit:cover;
    border:4px solid rgba(255,255,255,0.18);
    margin:0 auto 14px;
    display:block;
    background:#222;
    box-shadow:0 6px 18px rgba(0,0,0,0.35);
    transform:translateY(-6px);
    animation:popIn 420ms ease both;
  }

  h1{
    margin:6px 0 18px;
    font-size:20px;
    letter-spacing:0.2px;
    font-weight:700;
  }
  p.subtitle{
    margin:0 0 18px;
    font-size:13px;
    color:rgba(255,255,255,0.85);
  }

  .links{
    display:flex;
    flex-direction:column;
    gap:12px;
    margin-top:6px;
  }

  .link-card{
    display:flex;
    gap:12px;
    align-items:center;
    text-decoration:none;
    color:inherit;
    background:var(--card-bg);
    padding:12px 14px;
    border-radius:12px;
    transition:transform 220ms ease, background 220ms ease, box-shadow 220ms ease;
    box-shadow: 0 6px 18px rgba(20,30,60,0.12);
    transform:translateY(8px);
    opacity:0;
    animation:slideUp 420ms forwards;
  }

  .link-card:hover{
    transform:translateY(0) scale(1.02);
    background:var(--card-hover);
    box-shadow: 0 12px 30px rgba(10,20,40,0.18);
  }

  .icon{
    width:42px;
    height:42px;
    min-width:42px;
    border-radius:10px;
    background:linear-gradient(180deg, rgba(255,255,255,0.06), rgba(255,255,255,0.02));
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:18px;
    color:var(--accent);
    flex-shrink:0;
    border:1px solid rgba(255,255,255,0.03);
  }

  .label{
    text-align:left;
    flex:1;
    font-weight:600;
    font-size:15px;
  }
  .meta{
    font-size:12px;
    color:rgba(255,255,255,0.7);
    margin-top:4px;
    font-weight:500;
  }

  /* per-item animation delays via CSS variable --i */
  .link-card{ animation-delay: calc(var(--i) * 0.08s); }

  @keyframes fadeIn { from{opacity:0; transform:translateY(6px)} to{opacity:1; transform:translateY(0)} }
  @keyframes popIn { 0%{transform:scale(0.6) translateY(-6px); opacity:0} 100%{transform:scale(1) translateY(0); opacity:1} }
  @keyframes slideUp { to{opacity:1; transform:translateY(0)} }

  /* Responsive tweaks */
  @media (max-width:420px){
    .container{ padding:22px; border-radius:16px;}
    .avatar{width:100px;height:100px}
    .link-card{padding:10px}
  }
</style>
</head>
<body>

<div class="container" role="main" aria-labelledby="owner-name">
  <img class="avatar" src="https://i.postimg.cc/NjF4S52Y/IMG-20251129-161207-559.webp" alt="Aziz Asadov profiling rasmi">

  <h1 id="owner-name">Aziz Asadov</h1>
  <p class="subtitle">Linklar — tezkor va xavfsiz</p>

  <div class="links">
    <a class="link-card" href="https://t.me/arbitragefinder1" target="_blank" rel="noopener noreferrer" style="--i:1" aria-label="Arbitrage kanali — yangi imkoniyatlar">
      <div class="icon">📈</div>
      <div>
        <div class="label">Arbitrage Kanali</div>
        <div class="meta">Telegram kanal</div>
      </div>
    </a>

    <a class="link-card" href="https://t.me/azikkuuu" target="_blank" rel="noopener noreferrer" style="--i:2" aria-label="Shaxsiy telegram — Aziz Asadov">
      <div class="icon">👤</div>
      <div>
        <div class="label">Shaxsiy Telegram</div>
        <div class="meta">@azikkuuu</div>
      </div>
    </a>

    <a class="link-card" href="https://t.me/Uzbekiston_elonlari_official" target="_blank" rel="noopener noreferrer" style="--i:3" aria-label="Oʻzbekiston e'lonlari guruhi">
      <div class="icon">👥</div>
      <div>
        <div class="label">Telegram Guruh</div>
        <div class="meta">Uzbekiston elonlari</div>
      </div>
    </a>

    <a class="link-card" href="https://t.me/top1secret_bot?start=REF5093707534509370" target="_blank" rel="noopener noreferrer" style="--i:4" aria-label="TOP 1% Secret — ro'yxatdan o‘tish">
      <div class="icon">🔒</div>
      <div>
        <div class="label">TOP 1% Secret — Ro‘yxatdan O‘tish</div>
        <div class="meta">Bot orqali sign-up</div>
      </div>
    </a>

    <a class="link-card" href="tel:+998505033441" style="--i:5" aria-label="Telefon raqam — +998 50 503 34 41">
      <div class="icon">📞</div>
      <div>
        <div class="label">+998 50 503 34 41</div>
        <div class="meta">Qo'ng'iroq yoki SMS</div>
      </div>
    </a>
  </div>
</div>

</body>
</html>