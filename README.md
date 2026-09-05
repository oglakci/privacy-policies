<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yasar Oglakci — Uygulamalar</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: #0A0A0A; color: #fff; min-height: 100vh; display: flex; flex-direction: column; justify-content: center; padding: 48px 24px; }
  .container { max-width: 680px; margin: 0 auto; width: 100%; }
  .header { margin-bottom: 64px; }
  .header p { color: #333; font-size: 12px; text-transform: uppercase; letter-spacing: 3px; margin-bottom: 10px; }
  .header h1 { font-size: 40px; font-weight: 700; letter-spacing: -1.5px; line-height: 1.1; }
  .header h1 span { color: #333; }
  .apps { display: flex; gap: 20px; align-items: center; margin-bottom: 64px; flex-wrap: wrap; }
  .app { display: flex; flex-direction: column; align-items: center; gap: 10px; text-decoration: none; color: #fff; opacity: 0.7; transition: opacity 0.2s; }
  .app:hover { opacity: 1; }
  .icon-wrap { width: 52px; height: 52px; border-radius: 14px; display: flex; align-items: center; justify-content: center; }
  .app span { font-size: 11px; color: #555; text-align: center; }
  .footer-links { display: flex; gap: 16px; align-items: center; }
  .footer-links a { color: #333; text-decoration: none; font-size: 12px; transition: color 0.2s; }
  .footer-links a:hover { color: #888; }
  .dot { width: 3px; height: 3px; background: #333; border-radius: 50%; }
</style>
</head>
<body>
<div class="container">

  <div class="header">
    <p>Uygulamalar</p>
    <h1>7 uygulama.<br><span>Bir geliştirici.</span></h1>
  </div>

  <div class="apps">

    <a class="app" href="debtly.html">
      <div class="icon-wrap" style="background:#0D2E1E;">
        <svg width="26" height="26" viewBox="0 0 28 28" fill="none">
          <circle cx="14" cy="14" r="10" stroke="#10B981" stroke-width="2"/>
          <path d="M14 8v2M14 18v2M10 12h4a2 2 0 010 4h-4" stroke="#10B981" stroke-width="1.8" stroke-linecap="round"/>
        </svg>
      </div>
      <span>Debtly</span>
    </a>

    <a class="app" href="kasa.html">
      <div class="icon-wrap" style="background:#2E1F00;">
        <svg width="26" height="26" viewBox="0 0 28 28" fill="none">
          <rect x="6" y="8" width="16" height="13" rx="2" stroke="#F4A100" stroke-width="2"/>
          <circle cx="14" cy="14" r="3" stroke="#F4A100" stroke-width="1.8"/>
          <path d="M6 12h2M20 12h2" stroke="#F4A100" stroke-width="1.8" stroke-linecap="round"/>
        </svg>
      </div>
      <span>Kasa</span>
    </a>

    <a class="app" href="falhanim.html">
      <div class="icon-wrap" style="background:#1A0F30;">
        <svg width="26" height="26" viewBox="0 0 28 28" fill="none">
          <path d="M14 5C10 5 7 8 7 12c0 2.5 1.2 4.7 3 6l1 5h6l1-5c1.8-1.3 3-3.5 3-6 0-4-3-7-7-7z" stroke="#E7BC5A" stroke-width="1.8" stroke-linejoin="round"/>
          <path d="M11 23h6" stroke="#E7BC5A" stroke-width="1.8" stroke-linecap="round"/>
        </svg>
      </div>
      <span>Falhanım</span>
    </a>

    <a class="app" href="gebeyim.html">
      <div class="icon-wrap" style="background:#2E0A10;">
        <svg width="26" height="26" viewBox="0 0 28 28" fill="none">
          <circle cx="14" cy="10" r="3" stroke="#F43F5E" stroke-width="1.8"/>
          <path d="M10 15c0-2.2 1.8-4 4-4s4 1.8 4 4v2c0 1.1-.9 2-2 2h-4c-1.1 0-2-.9-2-2v-2z" stroke="#F43F5E" stroke-width="1.8"/>
          <circle cx="14" cy="19" r="2" stroke="#F43F5E" stroke-width="1.5"/>
        </svg>
      </div>
      <span>Gebeyim!</span>
    </a>

    <a class="app" href="biparmak.html">
      <div class="icon-wrap" style="background:#2E1500;">
        <svg width="26" height="26" viewBox="0 0 28 28" fill="none">
          <circle cx="14" cy="14" r="3" fill="#FF6B35"/>
          <circle cx="14" cy="14" r="6" stroke="#FF6B35" stroke-width="1.5" stroke-opacity="0.5"/>
          <circle cx="14" cy="14" r="9" stroke="#FF6B35" stroke-width="1" stroke-opacity="0.25"/>
        </svg>
      </div>
      <span>Bi'Parmak</span>
    </a>

    <a class="app" href="yaprak.html">
      <div class="icon-wrap" style="background:#0A1F14;">
        <svg width="26" height="26" viewBox="0 0 28 28" fill="none">
          <path d="M8 20c2-6 8-10 13-12C19 14 15 20 8 20z" stroke="#2D6A4F" stroke-width="1.8" fill="#2D6A4F" fill-opacity="0.3" stroke-linejoin="round"/>
          <path d="M8 20c1-3 3-5 5-6" stroke="#2D6A4F" stroke-width="1.5" stroke-linecap="round"/>
        </svg>
      </div>
      <span>Yaprak</span>
    </a>

    <a class="app" href="glug.html">
      <div class="icon-wrap" style="background:#021A18;">
        <svg width="26" height="26" viewBox="0 0 28 28" fill="none">
          <path d="M14 6c0 0-7 6-7 11a7 7 0 0014 0c0-5-7-11-7-11z" stroke="#0D9488" stroke-width="1.8" stroke-linejoin="round"/>
          <path d="M11 18c1 1.5 4 2 5 1" stroke="#0D9488" stroke-width="1.5" stroke-linecap="round"/>
        </svg>
      </div>
      <span>Glug</span>
    </a>

  </div>

  <div class="footer-links">
    <a href="terms.html">Kullanım Şartları</a>
    <div class="dot"></div>
    <a href="mailto:oglakcci@gmail.com">İletişim</a>
    <div class="dot"></div>
    <a href="#">© 2026</a>
  </div>

</div>
</body>
</html>
