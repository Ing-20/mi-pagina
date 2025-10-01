<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Para ti 🌼</title>
  <style>
    /* Estilos simples y responsivos */
    html,body{height:100%;margin:0;font-family:Inter, system-ui, Arial, sans-serif;background:linear-gradient(180deg,#fffaf0,#fff7e6);}
    .wrap{min-height:100%;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:2rem;text-align:center}
    .card{background:rgba(255,255,255,0.85);backdrop-filter:blur(6px);border-radius:16px;padding:1.6rem;max-width:720px;box-shadow:0 8px 30px rgba(0,0,0,0.08)}
    h1{margin:0 0 .4rem;font-size:1.8rem;color:#2b2b2b}
    p{margin:.2rem 0 1rem;color:#444}
    .flowers{display:flex;gap:.6rem;flex-wrap:wrap;justify-content:center;margin-bottom:1rem}
    .flower{width:64px;height:64px;border-radius:50%;display:inline-grid;place-items:center;font-size:28px;transform-origin:center;animation:float 4s ease-in-out infinite}
    .flower:nth-child(1){transform:rotate(-6deg)}
    .flower:nth-child(2){transform:rotate(8deg);animation-delay:.4s}
    .flower:nth-child(3){transform:rotate(-2deg);animation-delay:.8s}
    @keyframes float{0%{transform:translateY(0)}50%{transform:translateY(-8px)}100%{transform:translateY(0)}}
    .btn{display:inline-block;padding:.6rem 1rem;border-radius:999px;background:#ffd54a;color:#222;text-decoration:none;font-weight:600;box-shadow:0 6px 18px rgba(255,165,0,0.12)}
    footer{margin-top:1rem;font-size:.82rem;color:#666}
    /* accesibilidad y tamaño en móviles */
    @media (max-width:420px){h1{font-size:1.4rem}.flower{width:54px;height:54px;font-size:24px}}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" role="main" aria-labelledby="title">
      <div class="flowers" aria-hidden="true">
        <!-- Puedes reemplazar los emojis por imágenes si quieres -->
        <div class="flower">🌼</div>
        <div class="flower">💛</div>
        <div class="flower">🌼</div>
      </div>

      <h1 id="title">Para ti, mi alegría</h1>
      <p>Desde que llegaste, mis días florecen. Gracias por ser mi luz amarilla.</p>

      <a class="btn" href="https://wa.me/?text=Te%20env%C3%ADo%20algo%20bonito%20%F0%9F%8C%BC" target="_blank" rel="noopener">Compartir en WhatsApp</a>

      <footer>Con cariño — <strong>Tu nombre</strong></footer>
    </div>
  </div>
</body>
</html>
