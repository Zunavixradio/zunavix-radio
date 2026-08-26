<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZUNAVIX RADIO | DJ Spotlight & Nightlife</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      background: #090611;
      color: #f0f0f5;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      padding-bottom: 50px;
    }
    header {
      text-align: center;
      padding: 25px 15px;
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
      background: rgba(18, 11, 31, 0.9);
    }
    .logo {
      font-size: 24px;
      font-weight: 900;
      letter-spacing: 2px;
      background: linear-gradient(45deg, #ff007f, #7928ca, #00d4ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .tagline { font-size: 12px; color: #8f8fa3; margin-top: 4px; }
    .container { max-width: 450px; margin: 0 auto; padding: 20px 15px; }
    .player-card {
      background: linear-gradient(135deg, rgba(255, 0, 128, 0.12), rgba(121, 40, 202, 0.18));
      border: 1px solid rgba(255, 255, 255, 0.15);
      border-radius: 20px;
      padding: 20px;
      text-align: center;
      margin-bottom: 25px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.6);
    }
    .badge {
      display: inline-block;
      background: #ff0055;
      font-size: 10px;
      font-weight: 800;
      padding: 4px 10px;
      border-radius: 12px;
      margin-bottom: 10px;
    }
    audio { width: 100%; margin: 15px 0 5px; outline: none; filter: invert(0.85); }
    h2 { font-size: 16px; margin: 20px 0 10px; color: #fff; }
    .promo-card {
      background: rgba(255, 255, 255, 0.04);
      border: 1px solid rgba(255, 255, 255, 0.08);
      border-radius: 14px;
      padding: 14px;
      margin-bottom: 10px;
      display: flex;
      gap: 12px;
      align-items: center;
    }
    .promo-icon {
      width: 44px;
      height: 44px;
      background: rgba(255, 255, 255, 0.08);
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 20px;
      flex-shrink: 0;
    }
    .promo-info h3 { font-size: 14px; margin-bottom: 2px; }
    .promo-info p { font-size: 11px; color: #a0a0b2; }
    .cta-box {
      background: linear-gradient(135deg, #7928ca, #ff007f);
      border-radius: 16px;
      padding: 20px 15px;
      text-align: center;
      margin-top: 30px;
    }
    .cta-box h3 { font-size: 16px; margin-bottom: 6px; }
    .cta-box p { font-size: 11px; color: rgba(255,255,255,0.85); margin-bottom: 12px; }
    .btn-promo {
      background: #ffffff;
      color: #090611;
      padding: 10px 20px;
      border-radius: 20px;
      font-weight: 700;
      font-size: 12px;
      text-decoration: none;
      display: inline-block;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">ZUNAVIX RADIO</div>
    <div class="tagline">The Pulse of DJs, Nightclubs & Fresh Sound</div>
  </header>

  <div class="container">
    <div class="player-card">
      <span class="badge">● LIVE ON AIR 24/7</span>
      <h3 style="font-size: 16px; margin-bottom: 4px;">Zunavix Stream Live</h3>
      <p style="font-size: 11px; color: #a0a0b2;">Club Mixes & High-Energy Beats</p>
      
      <audio controls autoplay>
        <source src="https://stream.zeno.fm/f3wvbbqmdg8uv" type="audio/mpeg">
      </audio>
    </div>

    <h2>🎧 DJ Spotlight</h2>
    <div class="promo-card">
      <div class="promo-icon">🎛️</div>
      <div class="promo-info">
        <h3>Featured DJ Mix</h3>
        <p>1-Hour Weekend Club Electro Mix.</p>
      </div>
    </div>

    <h2>🪩 Club & Events</h2>
    <div class="promo-card">
      <div class="promo-icon">🍸</div>
      <div class="promo-info">
        <h3>Club Night Highlights</h3>
        <p>Featured VIP Lounge & Event Booking.</p>
      </div>
    </div>

    <div class="cta-box">
      <h3>Get Your Music or Club Featured!</h3>
      <p>Radio Airplay • DJ Spotlight • Event Promos</p>
      <a href="https://instagram.com" target="_blank" class="btn-promo">Book Promotion</a>
    </div>
  </div>

</body>
</html>


