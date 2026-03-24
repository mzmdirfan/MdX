<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>S. Mohamed Suhail & M. Aafiyathul Marliya – Wedding Invitation</title>
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=Cormorant+Garamond:ital,wght@0,300;0,400;1,300&family=Amiri:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
<style>
  :root {
    --gold: #c9a84c;
    --gold-light: #e8d5a3;
    --gold-dark: #8b6914;
    --rose: #d4a0a0;
    --rose-light: #f5e8e8;
    --rose-dark: #8b4f4f;
    --cream: #fdf8f2;
    --cream-dark: #f0e6d6;
    --brown: #5a3e2b;
    --brown-light: #8b6554;
    --white: #ffffff;
    --shadow: rgba(90,62,43,0.18);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'Cormorant Garamond', serif;
    background: var(--cream);
    color: var(--brown);
    overflow-x: hidden;
    cursor: default;
  }

  /* ===== PARTICLES / PETAL CANVAS ===== */
  #petals-canvas {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    pointer-events: none;
    z-index: 0;
  }

  /* ===== LOADING SCREEN ===== */
  #loading {
    position: fixed;
    inset: 0;
    background: var(--cream);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    z-index: 9999;
    transition: opacity 0.8s ease, visibility 0.8s ease;
  }
  #loading.hidden { opacity: 0; visibility: hidden; }
  .loading-bismillah {
    font-family: 'Amiri', serif;
    font-size: clamp(1.5rem, 5vw, 2.5rem);
    color: var(--gold);
    animation: pulse 1.5s ease-in-out infinite;
    text-align: center;
    padding: 0 1rem;
  }
  .loading-ring {
    width: 60px; height: 60px;
    border: 3px solid var(--gold-light);
    border-top-color: var(--gold);
    border-radius: 50%;
    animation: spin 1s linear infinite;
    margin-top: 1.5rem;
  }
  @keyframes spin { to { transform: rotate(360deg); } }
  @keyframes pulse { 0%,100%{opacity:1;} 50%{opacity:0.5;} }

  /* ===== WRAPPER ===== */
  #page {
    position: relative;
    z-index: 1;
    opacity: 0;
    transition: opacity 1s ease;
  }
  #page.visible { opacity: 1; }

  /* ===== DECORATIVE BORDER FRAME ===== */
  .frame-border {
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 500;
    border: 12px solid transparent;
    border-image: repeating-linear-gradient(45deg, var(--gold), var(--gold) 6px, transparent 6px, transparent 14px) 12;
    opacity: 0.25;
  }

  /* ===== HERO SECTION ===== */
  #hero {
    min-height: 100vh;
    background: linear-gradient(160deg, #fdf4ec 0%, #f5e8d8 40%, #ede0cc 100%);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 5rem 1.5rem 4rem;
    position: relative;
    overflow: hidden;
  }

  /* Decorative corner roses (CSS-drawn) */
  .corner-deco {
    position: absolute;
    width: 200px; height: 200px;
    opacity: 0.18;
    background: radial-gradient(circle, var(--rose) 20%, transparent 70%);
    border-radius: 50%;
  }
  .corner-deco.tl { top: -60px; left: -60px; }
  .corner-deco.tr { top: -60px; right: -60px; }
  .corner-deco.bl { bottom: -60px; left: -60px; }
  .corner-deco.br { bottom: -60px; right: -60px; }

  .bismillah-text {
    font-family: 'Amiri', serif;
    font-size: clamp(1.2rem, 4vw, 2rem);
    color: var(--gold-dark);
    margin-bottom: 1rem;
    letter-spacing: 0.05em;
    animation: fadeDown 1s ease both;
  }

  .lantern-row {
    display: flex;
    gap: clamp(1.5rem, 5vw, 3rem);
    justify-content: center;
    margin-bottom: 1.5rem;
    animation: fadeDown 1s ease 0.2s both;
  }
  .lantern {
    width: clamp(36px, 6vw, 56px);
    animation: sway 4s ease-in-out infinite;
    filter: drop-shadow(0 4px 8px rgba(201,168,76,0.4));
  }
  .lantern:nth-child(2) { animation-delay: -2s; }
  .lantern:nth-child(3) { animation-delay: -1s; }
  @keyframes sway {
    0%,100%{ transform: rotate(-6deg); }
    50%{ transform: rotate(6deg); }
  }

  .quran-quote {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: clamp(0.85rem, 2.5vw, 1.1rem);
    color: var(--brown-light);
    margin-bottom: 2rem;
    animation: fadeDown 1s ease 0.35s both;
    max-width: 360px;
  }
  .quran-quote span { color: var(--gold-dark); font-weight: 600; }

  .couple-names {
    animation: fadeDown 1s ease 0.5s both;
    margin-bottom: 1rem;
  }
  .groom-name {
    font-family: 'Great Vibes', cursive;
    font-size: clamp(2.8rem, 9vw, 5.5rem);
    color: var(--brown);
    line-height: 1.1;
    text-shadow: 2px 4px 12px rgba(90,62,43,0.15);
  }
  .ampersand {
    font-family: 'Great Vibes', cursive;
    font-size: clamp(2rem, 6vw, 3.5rem);
    color: var(--gold);
    display: block;
    line-height: 1.2;
  }
  .bride-name {
    font-family: 'Great Vibes', cursive;
    font-size: clamp(2.8rem, 9vw, 5.5rem);
    color: var(--brown);
    line-height: 1.1;
    text-shadow: 2px 4px 12px rgba(90,62,43,0.15);
  }

  .gold-divider {
    width: clamp(120px, 40vw, 260px);
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
    margin: 1.5rem auto;
    animation: fadeDown 1s ease 0.7s both;
  }

  .event-date-box {
    animation: fadeDown 1s ease 0.85s both;
    margin-bottom: 1.5rem;
  }
  .date-label {
    font-family: 'Playfair Display', serif;
    font-size: clamp(0.85rem, 2.5vw, 1.1rem);
    letter-spacing: 0.3em;
    color: var(--brown-light);
    text-transform: uppercase;
    margin-bottom: 0.4rem;
  }
  .date-big {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.5rem, 8vw, 5rem);
    font-weight: 600;
    color: var(--gold-dark);
    line-height: 1;
    letter-spacing: -0.02em;
  }
  .date-details {
    display: flex;
    gap: 1.5rem;
    justify-content: center;
    align-items: center;
    margin-top: 0.4rem;
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(1rem, 3vw, 1.3rem);
    color: var(--brown-light);
  }
  .date-details .sep { color: var(--gold); font-size: 1.4em; }

  .venue-text {
    font-family: 'Playfair Display', serif;
    font-size: clamp(0.9rem, 2.5vw, 1.15rem);
    color: var(--brown);
    margin-bottom: 1.5rem;
    animation: fadeDown 1s ease 1s both;
    letter-spacing: 0.08em;
  }

  .dua-arabic {
    font-family: 'Amiri', serif;
    font-size: clamp(1rem, 3vw, 1.4rem);
    color: var(--gold-dark);
    line-height: 2;
    animation: fadeDown 1s ease 1.1s both;
    margin-bottom: 2rem;
    text-align: center;
  }

  .hero-illustration {
    width: clamp(180px, 45vw, 340px);
    margin-top: 1.5rem;
    animation: fadeUp 1s ease 1.2s both;
    filter: drop-shadow(0 12px 24px rgba(90,62,43,0.2));
  }

  .scroll-hint {
    position: absolute;
    bottom: 1.5rem;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.4rem;
    color: var(--gold-dark);
    font-size: 0.75rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    animation: bounce 2s ease infinite;
    opacity: 0.7;
  }
  .scroll-hint svg { width: 20px; }
  @keyframes bounce { 0%,100%{ transform: translateX(-50%) translateY(0); } 50%{ transform: translateX(-50%) translateY(8px); } }

  @keyframes fadeDown { from { opacity:0; transform: translateY(-24px); } to { opacity:1; transform: translateY(0); } }
  @keyframes fadeUp   { from { opacity:0; transform: translateY(24px); }  to { opacity:1; transform: translateY(0); } }
  @keyframes fadeIn   { from { opacity:0; }                               to { opacity:1; } }

  /* ===== SECTION BASE ===== */
  section {
    padding: clamp(3rem, 8vw, 6rem) clamp(1rem, 5vw, 3rem);
    max-width: 1100px;
    margin: 0 auto;
  }

  .section-heading {
    text-align: center;
    margin-bottom: 3rem;
  }
  .section-heading .subtitle {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    color: var(--gold);
    font-size: clamp(0.85rem, 2.5vw, 1rem);
    letter-spacing: 0.3em;
    text-transform: uppercase;
    display: block;
    margin-bottom: 0.5rem;
  }
  .section-heading h2 {
    font-family: 'Great Vibes', cursive;
    font-size: clamp(2.5rem, 7vw, 4rem);
    color: var(--brown);
    line-height: 1.2;
  }
  .section-heading .ornament {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1rem;
    margin-top: 0.75rem;
  }
  .section-heading .ornament hr {
    width: 60px;
    border: none;
    border-top: 1.5px solid var(--gold-light);
  }
  .section-heading .ornament .diamond {
    width: 8px; height: 8px;
    background: var(--gold);
    transform: rotate(45deg);
  }

  /* ===== EVENTS SECTION ===== */
  #events { background: linear-gradient(180deg, var(--cream) 0%, var(--cream-dark) 100%); border-radius: 2rem; max-width: 100%; padding: clamp(3rem,8vw,6rem) 0; }
  #events > * { max-width: 1100px; margin-left: auto; margin-right: auto; padding: 0 clamp(1rem,5vw,3rem); }

  .events-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(min(280px, 100%), 1fr));
    gap: 2rem;
    padding: 0 clamp(1rem,5vw,3rem);
    max-width: 1100px;
    margin: 0 auto;
  }
  .event-card {
    background: white;
    border-radius: 1.5rem;
    padding: 2.5rem 2rem;
    text-align: center;
    box-shadow: 0 8px 32px var(--shadow);
    border: 1.5px solid var(--gold-light);
    position: relative;
    overflow: hidden;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .event-card::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, rgba(201,168,76,0.07) 0%, transparent 60%);
    pointer-events: none;
  }
  .event-card:hover { transform: translateY(-6px); box-shadow: 0 18px 48px var(--shadow); }
  .event-card .card-icon {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    display: block;
  }
  .event-card h3 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(1.2rem, 3vw, 1.6rem);
    color: var(--brown);
    margin-bottom: 0.5rem;
  }
  .event-card .event-time {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(0.9rem, 2.5vw, 1.1rem);
    color: var(--gold-dark);
    font-style: italic;
    margin-bottom: 1rem;
  }
  .event-card p {
    font-size: clamp(0.85rem, 2vw, 1rem);
    color: var(--brown-light);
    line-height: 1.7;
  }
  .event-card .event-badge {
    display: inline-block;
    background: linear-gradient(135deg, var(--gold), var(--gold-dark));
    color: white;
    font-family: 'Cormorant Garamond', serif;
    font-size: 0.78rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    padding: 0.3rem 0.9rem;
    border-radius: 2rem;
    margin-top: 1rem;
  }

  /* ===== COUNTDOWN ===== */
  #countdown-section {
    background: linear-gradient(135deg, #3b2512 0%, #5a3e2b 50%, #3b2512 100%);
    padding: clamp(3rem,8vw,6rem) clamp(1rem,5vw,3rem);
    text-align: center;
    max-width: 100%;
    position: relative;
    overflow: hidden;
  }
  #countdown-section::before {
    content: '';
    position: absolute;
    inset: 0;
    background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23c9a84c' fill-opacity='0.06'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
  }
  #countdown-section .inner { position: relative; max-width: 800px; margin: 0 auto; }
  #countdown-section .section-heading .subtitle { color: var(--gold-light); }
  #countdown-section .section-heading h2 { color: var(--gold-light); }
  #countdown-section .section-heading .ornament hr { border-top-color: rgba(201,168,76,0.4); }
  #countdown-section .section-heading .ornament .diamond { background: var(--gold); }

  .countdown-grid {
    display: flex;
    justify-content: center;
    gap: clamp(1rem, 4vw, 2.5rem);
    flex-wrap: wrap;
    margin-top: 2rem;
  }
  .count-box {
    background: rgba(255,255,255,0.06);
    border: 1.5px solid rgba(201,168,76,0.35);
    border-radius: 1rem;
    padding: clamp(1rem, 3vw, 1.8rem) clamp(1.2rem, 4vw, 2.2rem);
    min-width: clamp(80px, 18vw, 120px);
    backdrop-filter: blur(6px);
    transition: transform 0.2s ease;
  }
  .count-box:hover { transform: scale(1.05); }
  .count-num {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.5rem, 7vw, 4.5rem);
    font-weight: 600;
    color: var(--gold);
    line-height: 1;
    display: block;
  }
  .count-label {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(0.75rem, 2vw, 0.95rem);
    color: rgba(232,213,163,0.8);
    letter-spacing: 0.2em;
    text-transform: uppercase;
    margin-top: 0.4rem;
    display: block;
  }

  /* ===== COUPLE STORY ===== */
  #story { max-width: 100%; background: var(--rose-light); padding: clamp(3rem,8vw,6rem) 0; }
  #story > .inner { max-width: 1100px; margin: 0 auto; padding: 0 clamp(1rem,5vw,3rem); }

  .story-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(min(300px,100%), 1fr));
    gap: 2.5rem;
    margin-top: 2rem;
  }
  .story-card {
    background: white;
    border-radius: 1.5rem;
    padding: 2.5rem 2rem;
    text-align: center;
    box-shadow: 0 4px 24px rgba(212,160,160,0.18);
    border: 1.5px solid rgba(212,160,160,0.35);
    transition: transform 0.3s ease;
  }
  .story-card:hover { transform: translateY(-5px); }
  .story-avatar {
    width: clamp(90px, 20vw, 130px);
    height: clamp(90px, 20vw, 130px);
    border-radius: 50%;
    border: 4px solid var(--gold-light);
    margin: 0 auto 1.2rem;
    overflow: hidden;
    background: linear-gradient(135deg, var(--rose-light), var(--cream-dark));
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
  }
  .story-card h3 {
    font-family: 'Great Vibes', cursive;
    font-size: clamp(1.8rem, 5vw, 2.5rem);
    color: var(--brown);
    margin-bottom: 0.3rem;
  }
  .story-card .role {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    color: var(--gold-dark);
    font-size: clamp(0.85rem, 2vw, 1rem);
    margin-bottom: 1rem;
    letter-spacing: 0.15em;
  }
  .story-card p {
    font-size: clamp(0.88rem, 2vw, 1rem);
    color: var(--brown-light);
    line-height: 1.8;
  }
  .story-heart {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
    color: var(--rose-dark);
    animation: heartbeat 1.5s ease infinite;
    margin: auto;
  }
  @keyframes heartbeat { 0%,100%{ transform: scale(1); } 50%{ transform: scale(1.2); } }

  /* ===== GALLERY SECTION ===== */
  #gallery { max-width: 100%; padding: clamp(3rem,8vw,6rem) 0; }
  #gallery > .inner { max-width: 1100px; margin: 0 auto; padding: 0 clamp(1rem,5vw,3rem); }

  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(min(220px,100%), 1fr));
    gap: 1rem;
  }
  .gallery-item {
    border-radius: 1rem;
    overflow: hidden;
    aspect-ratio: 4/3;
    background: linear-gradient(135deg, var(--rose-light), var(--cream-dark));
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
    cursor: pointer;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    position: relative;
    border: 1.5px solid var(--gold-light);
  }
  .gallery-item:hover { transform: scale(1.04); box-shadow: 0 10px 32px var(--shadow); }
  .gallery-item .overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, rgba(201,168,76,0.15), rgba(90,62,43,0.25));
    opacity: 0;
    transition: opacity 0.3s;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    color: white;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
  }
  .gallery-item:hover .overlay { opacity: 1; }
  .gallery-item:first-child { grid-column: span 2; aspect-ratio: 16/9; font-size: 5rem; }

  /* ===== WISHES SECTION ===== */
  #wishes { max-width: 100%; background: linear-gradient(160deg, var(--cream-dark), var(--cream)); padding: clamp(3rem,8vw,6rem) 0; }
  #wishes > .inner { max-width: 900px; margin: 0 auto; padding: 0 clamp(1rem,5vw,3rem); }

  .wishes-form {
    background: white;
    border-radius: 1.5rem;
    padding: clamp(1.5rem, 5vw, 3rem);
    box-shadow: 0 8px 32px var(--shadow);
    border: 1.5px solid var(--gold-light);
    margin-bottom: 2.5rem;
  }
  .wishes-form h3 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(1.2rem, 3vw, 1.6rem);
    color: var(--brown);
    margin-bottom: 1.5rem;
    text-align: center;
  }
  .form-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin-bottom: 1rem;
  }
  @media (max-width: 480px) { .form-row { grid-template-columns: 1fr; } }
  .form-group { display: flex; flex-direction: column; gap: 0.4rem; }
  .form-group label {
    font-family: 'Cormorant Garamond', serif;
    font-size: 0.85rem;
    color: var(--brown-light);
    letter-spacing: 0.1em;
    text-transform: uppercase;
  }
  .form-group input,
  .form-group textarea,
  .form-group select {
    border: 1.5px solid var(--gold-light);
    border-radius: 0.6rem;
    padding: 0.7rem 1rem;
    font-family: 'Cormorant Garamond', serif;
    font-size: 1rem;
    color: var(--brown);
    background: var(--cream);
    outline: none;
    transition: border-color 0.2s, box-shadow 0.2s;
    width: 100%;
  }
  .form-group input:focus,
  .form-group textarea:focus,
  .form-group select:focus {
    border-color: var(--gold);
    box-shadow: 0 0 0 3px rgba(201,168,76,0.12);
  }
  .form-group textarea { min-height: 100px; resize: vertical; }
  .btn-primary {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: linear-gradient(135deg, var(--gold), var(--gold-dark));
    color: white;
    font-family: 'Cormorant Garamond', serif;
    font-size: 1rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 0.9rem 2.5rem;
    border: none;
    border-radius: 3rem;
    cursor: pointer;
    transition: transform 0.2s, box-shadow 0.2s;
    box-shadow: 0 4px 16px rgba(139,105,20,0.3);
    width: 100%;
    justify-content: center;
    margin-top: 0.5rem;
  }
  .btn-primary:hover { transform: translateY(-2px); box-shadow: 0 8px 24px rgba(139,105,20,0.4); }
  .btn-primary:active { transform: translateY(0); }

  .wish-cards {
    display: flex;
    flex-direction: column;
    gap: 1.2rem;
  }
  .wish-card {
    background: white;
    border-radius: 1rem;
    padding: 1.5rem;
    box-shadow: 0 4px 16px var(--shadow);
    border-left: 4px solid var(--gold);
    transition: transform 0.2s;
    animation: slideIn 0.5s ease both;
  }
  .wish-card:hover { transform: translateX(4px); }
  @keyframes slideIn { from { opacity:0; transform: translateX(-20px); } to { opacity:1; transform: translateX(0); } }
  .wish-card .wish-author {
    font-family: 'Playfair Display', serif;
    font-size: 1rem;
    color: var(--brown);
    font-weight: 600;
    margin-bottom: 0.3rem;
  }
  .wish-card .wish-relation {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    color: var(--gold-dark);
    font-size: 0.85rem;
    margin-bottom: 0.6rem;
  }
  .wish-card p {
    font-size: 0.95rem;
    color: var(--brown-light);
    line-height: 1.7;
  }

  /* ===== MAP / LOCATION SECTION ===== */
  #location { max-width: 100%; background: var(--cream-dark); padding: clamp(3rem,8vw,6rem) 0; }
  #location > .inner { max-width: 900px; margin: 0 auto; padding: 0 clamp(1rem,5vw,3rem); }

  .location-card {
    background: white;
    border-radius: 1.5rem;
    overflow: hidden;
    box-shadow: 0 8px 32px var(--shadow);
    border: 1.5px solid var(--gold-light);
  }
  .location-map {
    width: 100%;
    height: clamp(200px, 40vw, 340px);
    background: linear-gradient(135deg, #e8f0e8 0%, #d8e8d0 100%);
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    overflow: hidden;
  }
  .map-placeholder {
    text-align: center;
    color: var(--brown-light);
  }
  .map-placeholder .map-pin {
    font-size: 4rem;
    display: block;
    animation: pin-drop 1s ease both;
  }
  @keyframes pin-drop { from{ transform: translateY(-40px) scale(1.5); opacity:0; } to{ transform: translateY(0) scale(1); opacity:1; } }
  .map-placeholder p { font-size: 1rem; margin-top: 0.5rem; font-family: 'Cormorant Garamond', serif; }

  /* Map grid lines decoration */
  .location-map::before {
    content: '';
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(rgba(90,62,43,0.08) 1px, transparent 1px),
      linear-gradient(90deg, rgba(90,62,43,0.08) 1px, transparent 1px);
    background-size: 40px 40px;
  }
  .location-info {
    padding: 2rem;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.5rem;
  }
  @media (max-width: 480px) { .location-info { grid-template-columns: 1fr; } }
  .location-detail h4 {
    font-family: 'Playfair Display', serif;
    font-size: 0.85rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold-dark);
    margin-bottom: 0.4rem;
  }
  .location-detail p {
    font-size: clamp(0.9rem, 2vw, 1.05rem);
    color: var(--brown);
    line-height: 1.6;
  }
  .btn-directions {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: white;
    color: var(--gold-dark);
    font-family: 'Cormorant Garamond', serif;
    font-size: 0.95rem;
    letter-spacing: 0.1em;
    padding: 0.7rem 1.8rem;
    border: 1.5px solid var(--gold);
    border-radius: 3rem;
    cursor: pointer;
    text-decoration: none;
    transition: all 0.2s;
    margin-top: 0.5rem;
  }
  .btn-directions:hover { background: var(--gold); color: white; }

  /* ===== RSVP ===== */
  #rsvp { max-width: 100%; background: linear-gradient(160deg, var(--cream), var(--rose-light)); padding: clamp(3rem,8vw,6rem) 0; }
  #rsvp > .inner { max-width: 700px; margin: 0 auto; padding: 0 clamp(1rem,5vw,3rem); }

  .rsvp-card {
    background: white;
    border-radius: 2rem;
    padding: clamp(2rem, 6vw, 3.5rem);
    box-shadow: 0 12px 48px var(--shadow);
    border: 1.5px solid var(--gold-light);
    text-align: center;
  }
  .rsvp-card .dua {
    font-family: 'Amiri', serif;
    font-size: clamp(1rem, 3vw, 1.4rem);
    color: var(--gold-dark);
    margin-bottom: 1.5rem;
  }
  .rsvp-card p {
    font-size: clamp(0.9rem, 2.5vw, 1.1rem);
    color: var(--brown-light);
    line-height: 1.8;
    margin-bottom: 2rem;
  }
  .rsvp-btns {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
  }
  .btn-yes {
    background: linear-gradient(135deg, var(--gold), var(--gold-dark));
    color: white;
    font-family: 'Cormorant Garamond', serif;
    font-size: 1rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    padding: 0.9rem 2.5rem;
    border: none;
    border-radius: 3rem;
    cursor: pointer;
    transition: transform 0.2s, box-shadow 0.2s;
    box-shadow: 0 4px 16px rgba(139,105,20,0.3);
  }
  .btn-yes:hover { transform: translateY(-2px); box-shadow: 0 8px 24px rgba(139,105,20,0.4); }
  .btn-no {
    background: white;
    color: var(--brown-light);
    font-family: 'Cormorant Garamond', serif;
    font-size: 1rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    padding: 0.9rem 2.5rem;
    border: 1.5px solid var(--rose);
    border-radius: 3rem;
    cursor: pointer;
    transition: all 0.2s;
  }
  .btn-no:hover { background: var(--rose-light); }
  .rsvp-success {
    display: none;
    padding: 2rem;
    background: linear-gradient(135deg, rgba(201,168,76,0.1), rgba(212,160,160,0.1));
    border-radius: 1rem;
    border: 1.5px solid var(--gold-light);
    font-family: 'Great Vibes', cursive;
    font-size: clamp(1.5rem, 4vw, 2rem);
    color: var(--brown);
  }

  /* ===== FOOTER ===== */
  footer {
    background: linear-gradient(135deg, #3b2512, #5a3e2b);
    color: var(--gold-light);
    text-align: center;
    padding: clamp(2.5rem, 6vw, 4rem) clamp(1rem, 5vw, 3rem);
    position: relative;
    overflow: hidden;
  }
  footer::before {
    content: '';
    position: absolute;
    inset: 0;
    background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23c9a84c' fill-opacity='0.06'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
  }
  footer > * { position: relative; }
  footer .footer-names {
    font-family: 'Great Vibes', cursive;
    font-size: clamp(1.8rem, 5vw, 3rem);
    color: var(--gold);
    margin-bottom: 0.5rem;
  }
  footer .footer-date {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(0.9rem, 2.5vw, 1.1rem);
    color: var(--gold-light);
    letter-spacing: 0.2em;
    margin-bottom: 1rem;
    opacity: 0.8;
  }
  footer .footer-dua {
    font-family: 'Amiri', serif;
    font-size: clamp(0.9rem, 2.5vw, 1.2rem);
    color: var(--gold);
    line-height: 2;
    margin-bottom: 1.5rem;
  }
  footer .footer-copy {
    font-size: 0.75rem;
    opacity: 0.4;
    letter-spacing: 0.1em;
  }
  .footer-hearts {
    display: flex;
    gap: 0.5rem;
    justify-content: center;
    margin-bottom: 1rem;
    font-size: 1.2rem;
  }
  .footer-hearts span { animation: heartbeat 1.5s ease infinite; }
  .footer-hearts span:nth-child(2) { animation-delay: 0.3s; }
  .footer-hearts span:nth-child(3) { animation-delay: 0.6s; }

  /* ===== NAV ===== */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 300;
    background: rgba(253,248,242,0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid rgba(201,168,76,0.2);
    padding: 0 clamp(1rem, 5vw, 3rem);
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 60px;
    transform: translateY(-100%);
    transition: transform 0.4s ease;
  }
  nav.visible { transform: translateY(0); }
  .nav-logo {
    font-family: 'Great Vibes', cursive;
    font-size: 1.5rem;
    color: var(--gold-dark);
    text-decoration: none;
  }
  .nav-links {
    display: flex;
    gap: clamp(1rem, 3vw, 2rem);
    list-style: none;
  }
  .nav-links a {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(0.8rem, 2vw, 0.95rem);
    color: var(--brown-light);
    text-decoration: none;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--gold-dark); }
  @media (max-width: 600px) {
    .nav-links { display: none; }
  }

  /* ===== SCROLL REVEAL ===== */
  .reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.visible { opacity: 1; transform: translateY(0); }
  .reveal-left {
    opacity: 0;
    transform: translateX(-30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal-left.visible { opacity: 1; transform: translateX(0); }
  .reveal-right {
    opacity: 0;
    transform: translateX(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal-right.visible { opacity: 1; transform: translateX(0); }

  /* ===== MUSIC TOGGLE ===== */
  #music-btn {
    position: fixed;
    bottom: 1.5rem;
    right: 1.5rem;
    z-index: 400;
    width: 50px; height: 50px;
    border-radius: 50%;
    background: linear-gradient(135deg, var(--gold), var(--gold-dark));
    border: none;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.3rem;
    box-shadow: 0 4px 18px rgba(139,105,20,0.4);
    transition: transform 0.2s;
    color: white;
  }
  #music-btn:hover { transform: scale(1.1); }
  #music-btn.playing { animation: glow 2s ease infinite; }
  @keyframes glow { 0%,100%{ box-shadow: 0 4px 18px rgba(139,105,20,0.4); } 50%{ box-shadow: 0 4px 32px rgba(201,168,76,0.7); } }

  /* ===== TOAST ===== */
  .toast {
    position: fixed;
    bottom: 5rem;
    left: 50%;
    transform: translateX(-50%) translateY(20px);
    background: var(--brown);
    color: var(--gold-light);
    font-family: 'Cormorant Garamond', serif;
    font-size: 1rem;
    padding: 0.8rem 2rem;
    border-radius: 3rem;
    opacity: 0;
    transition: all 0.4s ease;
    pointer-events: none;
    z-index: 600;
    white-space: nowrap;
  }
  .toast.show { opacity: 1; transform: translateX(-50%) translateY(0); }

  /* ===== RESPONSIVE TWEAKS ===== */
  @media (max-width: 768px) {
    .story-heart { display: none; }
  }

  /* ===== LIGHTBOX ===== */
  .lightbox {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.88);
    z-index: 700;
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    visibility: hidden;
    transition: all 0.3s;
  }
  .lightbox.open { opacity: 1; visibility: visible; }
  .lightbox-content {
    background: white;
    border-radius: 1rem;
    padding: 2rem;
    max-width: 500px;
    width: 90%;
    text-align: center;
    transform: scale(0.9);
    transition: transform 0.3s;
    font-size: 6rem;
    border: 2px solid var(--gold-light);
  }
  .lightbox.open .lightbox-content { transform: scale(1); }
  .lightbox-close {
    position: absolute;
    top: 1rem; right: 1rem;
    background: white;
    border: none;
    border-radius: 50%;
    width: 40px; height: 40px;
    font-size: 1.2rem;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--brown);
    transition: transform 0.2s;
  }
  .lightbox-close:hover { transform: rotate(90deg); }

  /* ===== MUSLIM GEOMETRIC PATTERN DIVIDER ===== */
  .pattern-divider {
    width: 100%;
    height: 40px;
    overflow: hidden;
    position: relative;
  }
  .pattern-divider svg {
    width: 100%;
    height: 100%;
  }
</style>
</head>
<body>
    <audio id="bg-music" src="music/nikah_song.mp3.mpeg" loop></audio>

<!-- Loading -->
<div id="loading">
  <div class="loading-bismillah">بِسْمِ اللهِ الرَّحْمٰنِ الرَّحِيْمِ</div>
  <div class="loading-ring"></div>
</div>

<!-- Frame -->
<div class="frame-border"></div>

<!-- Nav -->
<nav id="main-nav">
  <a href="#hero" class="nav-logo">Suhail & Marliya</a>
  <ul class="nav-links">
    <li><a href="#events">Events</a></li>
    <li><a href="#countdown-section">Countdown</a></li>
    <li><a href="#story">Our Story</a></li>
    <li><a href="#wishes">Wishes</a></li>
    <li><a href="#location">Location</a></li>
    <li><a href="#rsvp">RSVP</a></li>
  </ul>
</nav>

<!-- Petal Canvas -->
<canvas id="petals-canvas"></canvas>

<!-- Main Page -->
<div id="page">

  <!-- ===== HERO ===== -->
  <section id="hero">
    <div class="corner-deco tl"></div>
    <div class="corner-deco tr"></div>
    <div class="corner-deco bl"></div>
    <div class="corner-deco br"></div>

    <div class="bismillah-text">بِسْمِ اللهِ الرَّحْمٰنِ الرَّحِيْمِ</div>

    <!-- Lanterns SVG -->
    <div class="lantern-row">
      <svg class="lantern" viewBox="0 0 48 80" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect x="19" y="0" width="10" height="6" rx="2" fill="#c9a84c"/>
        <rect x="22" y="6" width="4" height="8" fill="#c9a84c"/>
        <path d="M10 20 Q10 14 24 14 Q38 14 38 20 L38 56 Q38 62 24 62 Q10 62 10 56 Z" fill="#c9a84c"/>
        <rect x="8" y="18" width="32" height="4" rx="2" fill="#8b6914"/>
        <rect x="8" y="54" width="32" height="4" rx="2" fill="#8b6914"/>
        <rect x="20" y="22" width="8" height="32" rx="1" fill="rgba(255,240,180,0.35)"/>
        <ellipse cx="24" cy="38" rx="6" ry="10" fill="rgba(255,220,80,0.25)"/>
        <rect x="22" y="62" width="4" height="10" fill="#c9a84c"/>
        <circle cx="24" cy="73" r="3" fill="#8b6914"/>
      </svg>
      <svg class="lantern" viewBox="0 0 48 80" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect x="19" y="0" width="10" height="6" rx="2" fill="#c9a84c"/>
        <rect x="22" y="6" width="4" height="8" fill="#c9a84c"/>
        <path d="M10 20 Q10 14 24 14 Q38 14 38 20 L38 56 Q38 62 24 62 Q10 62 10 56 Z" fill="#c9a84c"/>
        <rect x="8" y="18" width="32" height="4" rx="2" fill="#8b6914"/>
        <rect x="8" y="54" width="32" height="4" rx="2" fill="#8b6914"/>
        <rect x="20" y="22" width="8" height="32" rx="1" fill="rgba(255,240,180,0.35)"/>
        <ellipse cx="24" cy="38" rx="6" ry="10" fill="rgba(255,220,80,0.25)"/>
        <rect x="22" y="62" width="4" height="10" fill="#c9a84c"/>
        <circle cx="24" cy="73" r="3" fill="#8b6914"/>
      </svg>
      <svg class="lantern" viewBox="0 0 48 80" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect x="19" y="0" width="10" height="6" rx="2" fill="#c9a84c"/>
        <rect x="22" y="6" width="4" height="8" fill="#c9a84c"/>
        <path d="M10 20 Q10 14 24 14 Q38 14 38 20 L38 56 Q38 62 24 62 Q10 62 10 56 Z" fill="#c9a84c"/>
        <rect x="8" y="18" width="32" height="4" rx="2" fill="#8b6914"/>
        <rect x="8" y="54" width="32" height="4" rx="2" fill="#8b6914"/>
        <rect x="20" y="22" width="8" height="32" rx="1" fill="rgba(255,240,180,0.35)"/>
        <ellipse cx="24" cy="38" rx="6" ry="10" fill="rgba(255,220,80,0.25)"/>
        <rect x="22" y="62" width="4" height="10" fill="#c9a84c"/>
        <circle cx="24" cy="73" r="3" fill="#8b6914"/>
      </svg>
    </div>

    <div class="quran-quote">
      "And We Created You In Pairs"<br>
      <span>— Quran 78:8</span>
    </div>

    <div class="couple-names">
      <div class="groom-name">S. Mohamed Suhail</div>
      <span class="ampersand">&</span>
      <div class="bride-name">M. Aafiyathul Marliya</div>
    </div>

    <div class="gold-divider"></div>

    <div class="event-date-box">
      <div class="date-label">April · 2026</div>
      <div class="date-big">12</div>
      <div class="date-details">
        <span>Sunday</span>
        <span class="sep">◆</span>
        <span>10:00 AM</span>
      </div>
    </div>

    <div class="venue-text">Vembadi Pallivasal, Tenkasi</div>

    <div class="dua-arabic">بَارَكَ اللهُ لَكَ، وَبَارَكَ عَلَيْكَ، وَجَمَعَ بَيْنَكُمَا فِي خَيْرٍ</div>

    <!-- Couple Illustration SVG -->
    <svg class="hero-illustration" viewBox="0 0 340 220" fill="none" xmlns="http://www.w3.org/2000/svg">
      <!-- Arch / Gate -->
      <rect x="60" y="40" width="8" height="150" rx="4" fill="#d4b896"/>
      <rect x="272" y="40" width="8" height="150" rx="4" fill="#d4b896"/>
      <path d="M68 40 Q200 -10 272 40" stroke="#d4b896" stroke-width="8" fill="none"/>
      <!-- Curtains -->
      <path d="M68 40 Q80 80 72 150" stroke="#f0d8c8" stroke-width="18" fill="none" stroke-linecap="round"/>
      <path d="M272 40 Q260 80 268 150" stroke="#f0d8c8" stroke-width="18" fill="none" stroke-linecap="round"/>
      <!-- Ground flowers -->
      <ellipse cx="100" cy="195" rx="35" ry="10" fill="#c8e8b8" opacity="0.6"/>
      <ellipse cx="240" cy="195" rx="35" ry="10" fill="#c8e8b8" opacity="0.6"/>
      <!-- Groom (left) -->
      <!-- body -->
      <rect x="130" y="120" width="36" height="60" rx="8" fill="#8b6554"/>
      <!-- jacket -->
      <rect x="132" y="120" width="32" height="50" rx="6" fill="#5a3e2b"/>
      <!-- shirt white -->
      <rect x="143" y="120" width="10" height="30" fill="#f8f8f8"/>
      <!-- bow tie -->
      <path d="M146 123 L148 126 L150 123 L148 126 Z" fill="#3b2512" stroke="#3b2512" stroke-width="1"/>
      <!-- head -->
      <circle cx="148" cy="108" r="16" fill="#d4967a"/>
      <!-- hair -->
      <path d="M132 105 Q148 92 164 105" fill="#3b2512"/>
      <!-- legs -->
      <rect x="133" y="178" width="14" height="28" rx="4" fill="#3b2512"/>
      <rect x="149" y="178" width="14" height="28" rx="4" fill="#3b2512"/>
      <!-- shoes -->
      <ellipse cx="140" cy="207" rx="9" ry="4" fill="#2a1a0a"/>
      <ellipse cx="156" cy="207" rx="9" ry="4" fill="#2a1a0a"/>

      <!-- Bride (right) -->
      <!-- hijab -->
      <ellipse cx="196" cy="106" rx="18" ry="20" fill="#e8d0c0"/>
      <path d="M178 110 Q180 140 186 160 Q196 165 206 160 Q212 140 214 110" fill="#e8d0c0"/>
      <!-- face -->
      <circle cx="196" cy="104" r="12" fill="#d4967a"/>
      <!-- dress -->
      <path d="M186 130 Q180 155 178 200 L214 200 Q212 155 206 130 Z" fill="#f5e8e0"/>
      <!-- dress detail -->
      <path d="M186 130 Q196 145 206 130" stroke="#e8d0c0" stroke-width="2" fill="none"/>
      <!-- arms / bouquet -->
      <path d="M178 145 Q165 155 162 170" stroke="#e8d0c0" stroke-width="8" stroke-linecap="round" fill="none"/>
      <!-- bouquet -->
      <circle cx="158" cy="173" r="10" fill="#f4a0a0"/>
      <circle cx="165" cy="170" r="8" fill="#e87878"/>
      <circle cx="155" cy="168" r="7" fill="#f4a0a0"/>
      <rect x="161" y="178" width="4" height="14" rx="2" fill="#6a9e5a"/>

      <!-- Joined hands -->
      <ellipse cx="172" cy="165" rx="8" ry="5" fill="#d4967a" opacity="0.7"/>

      <!-- Flowers decoration top -->
      <circle cx="90" cy="35" r="12" fill="#f4a0a0" opacity="0.5"/>
      <circle cx="260" cy="35" r="14" fill="#f4a0a0" opacity="0.5"/>
      <circle cx="80" cy="20" r="8" fill="#f8c0c0" opacity="0.4"/>
      <circle cx="265" cy="18" r="9" fill="#f8c0c0" opacity="0.4"/>
    </svg>

    <div class="scroll-hint">
      <span>Scroll</span>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
        <path d="M12 5v14M5 12l7 7 7-7"/>
      </svg>
    </div>
  </section>

  <!-- Pattern Divider -->
  <div class="pattern-divider">
    <svg viewBox="0 0 1200 40" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <pattern id="islamic" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
          <polygon points="20,2 38,10 38,30 20,38 2,30 2,10" fill="none" stroke="#c9a84c" stroke-width="0.8" opacity="0.4"/>
          <circle cx="20" cy="20" r="4" fill="none" stroke="#c9a84c" stroke-width="0.8" opacity="0.3"/>
        </pattern>
      </defs>
      <rect width="1200" height="40" fill="url(#islamic)"/>
    </svg>
  </div>

  <!-- ===== EVENTS ===== -->
  <div id="events">
    <div class="section-heading reveal">
      <span class="subtitle">Join Us For</span>
      <h2>Wedding Celebrations</h2>
      <div class="ornament">
        <hr><div class="diamond"></div><hr>
      </div>
    </div>
    <div class="events-grid">
      <div class="event-card reveal">
        <span class="card-icon">🌸</span>
        <h3>Nikah Ceremony</h3>
        <div class="event-time">Sunday, April 12, 2026 · 10:00 AM</div>
        <p>The sacred Nikah ceremony binding two hearts together in the blessings of Allah. Families and close relatives are warmly invited.</p>
        <div class="event-badge">Main Event</div>
      </div>
      <div class="event-card reveal" style="transition-delay:0.15s">
        <span class="card-icon">🕌</span>
        <h3>Walima Reception</h3>
        <div class="event-time">Following the Nikah · Afternoon</div>
        <p>Celebrate with us at the Walima feast. A joyful gathering of family, friends, and loved ones to share in our happiness.</p>
        <div class="event-badge">Reception</div>
      </div>
      <div class="event-card reveal" style="transition-delay:0.3s">
        <span class="card-icon">🌙</span>
        <h3>Evening Gathering</h3>
        <div class="event-time">April 12, 2026 · Evening</div>
        <p>An intimate evening of prayers, blessings, and celebration with our dearest guests. Traditional music and warm hospitality await.</p>
        <div class="event-badge">Celebration</div>
      </div>
    </div>
  </div>

  <!-- Pattern Divider -->
  <div class="pattern-divider">
    <svg viewBox="0 0 1200 40" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
      <rect width="1200" height="40" fill="url(#islamic)"/>
    </svg>
  </div>

  <!-- ===== COUNTDOWN ===== -->
  <div id="countdown-section">
    <div class="inner">
      <div class="section-heading reveal">
        <span class="subtitle">Until The Big Day</span>
        <h2>Counting Down</h2>
        <div class="ornament">
          <hr><div class="diamond"></div><hr>
        </div>
      </div>
      <div class="countdown-grid">
        <div class="count-box reveal">
          <span class="count-num" id="cd-days">00</span>
          <span class="count-label">Days</span>
        </div>
        <div class="count-box reveal" style="transition-delay:0.1s">
          <span class="count-num" id="cd-hours">00</span>
          <span class="count-label">Hours</span>
        </div>
        <div class="count-box reveal" style="transition-delay:0.2s">
          <span class="count-num" id="cd-mins">00</span>
          <span class="count-label">Minutes</span>
        </div>
        <div class="count-box reveal" style="transition-delay:0.3s">
          <span class="count-num" id="cd-secs">00</span>
          <span class="count-label">Seconds</span>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== STORY ===== -->
  <div id="story">
    <div class="inner">
      <div class="section-heading reveal">
        <span class="subtitle">Two Souls, One Destiny</span>
        <h2>Our Story</h2>
        <div class="ornament">
          <hr><div class="diamond"></div><hr>
        </div>
      </div>
      <div class="story-grid">
        <div class="story-card reveal-left">
          <div class="story-avatar">🤵</div>
          <h3>S. Mohamed Suhail</h3>
          <div class="role">The Groom</div>
          <p>A man of faith, warmth, and unwavering integrity. His love and dedication are a reflection of the beautiful values instilled in him by his family. Today he takes the greatest step of his life, with gratitude in his heart and a smile that never fades.</p>
        </div>
        <div class="story-heart reveal">❤️</div>
        <div class="story-card reveal-right">
          <div class="story-avatar">👰</div>
          <h3>M. Aafiyathul Marliya</h3>
          <div class="role">The Bride</div>
          <p>Graceful, kind, and full of light — Marliya brings joy to everyone around her. Her strength, her smile, and her gentle nature make her the perfect partner. She walks into this new chapter with beauty, love, and Allah's blessings.</p>
        </div>
      </div>

      <div class="gold-divider" style="margin-top:3rem;"></div>

      <!-- Timeline -->
      <div class="section-heading reveal" style="margin-top:3rem; margin-bottom:2rem;">
        <span class="subtitle">Our Journey</span>
        <h2>A Love Story</h2>
      </div>
      <div style="max-width:600px; margin:0 auto;">
        <div style="position:relative; padding-left:2.5rem;">
          <div style="position:absolute; left:0.7rem; top:0; bottom:0; width:2px; background:linear-gradient(180deg, var(--gold-light), var(--rose-light));"></div>

          <div class="reveal" style="margin-bottom:2rem; position:relative;">
            <div style="position:absolute; left:-1.85rem; top:0.3rem; width:14px; height:14px; border-radius:50%; background:var(--gold); border:3px solid white; box-shadow:0 0 0 3px var(--gold-light);"></div>
            <div class="event-card" style="border-left:4px solid var(--gold); margin:0;">
              <h3 style="font-size:1rem;">💫 The Beginning</h3>
              <div class="event-time">The Families Meet</div>
              <p style="font-size:0.9rem;">Two families came together, guided by faith and trust, to explore a beautiful union. Hearts opened, du'as were made.</p>
            </div>
          </div>

          <div class="reveal" style="margin-bottom:2rem; position:relative; transition-delay:0.15s;">
            <div style="position:absolute; left:-1.85rem; top:0.3rem; width:14px; height:14px; border-radius:50%; background:var(--rose-dark); border:3px solid white; box-shadow:0 0 0 3px rgba(212,160,160,0.4);"></div>
            <div class="event-card" style="border-left:4px solid var(--rose-dark); margin:0;">
              <h3 style="font-size:1rem;">🌹 The Agreement</h3>
              <div class="event-time">A Promise Made</div>
              <p style="font-size:0.9rem;">With the blessings of Allah and the approval of their families, Suhail and Marliya agreed to build a life together, rooted in faith.</p>
            </div>
          </div>

          <div class="reveal" style="position:relative; transition-delay:0.3s;">
            <div style="position:absolute; left:-1.85rem; top:0.3rem; width:14px; height:14px; border-radius:50%; background:var(--gold-dark); border:3px solid white; box-shadow:0 0 0 3px var(--gold-light);"></div>
            <div class="event-card" style="border-left:4px solid var(--gold-dark); margin:0;">
              <h3 style="font-size:1rem;">💍 April 12, 2026</h3>
              <div class="event-time">The Wedding Day</div>
              <p style="font-size:0.9rem;">The day two hearts become one. A Nikah celebrated in joy, surrounded by loved ones, under the blessing skies of Tenkasi.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== GALLERY ===== -->
  <section id="gallery">
    <div class="inner">
      <div class="section-heading reveal">
        <span class="subtitle">Memories & Moments</span>
        <h2>Wedding Gallery</h2>
        <div class="ornament">
          <hr><div class="diamond"></div><hr>
        </div>
      </div>
    </div>
    <div class="gallery-grid" style="max-width:1100px; margin:0 auto; padding:0 clamp(1rem,5vw,3rem);">
      <div class="gallery-item reveal" data-emoji="💒" onclick="openLightbox('The Venue','Vembadi Pallivasal, Tenkasi — a beautiful setting for a beautiful union.')">
        <span style="font-size:5rem;">💒</span>
        <div class="overlay">The Venue</div>
      </div>
      <div class="gallery-item reveal" data-emoji="💍" onclick="openLightbox('The Rings','Two rings, one promise — a lifetime of love and loyalty.')" style="transition-delay:0.1s;">
        <span style="font-size:3rem;">💍</span>
        <div class="overlay">The Rings</div>
      </div>
      <div class="gallery-item reveal" onclick="openLightbox('The Flowers','Roses in bloom for a day that blooms with love.')" style="transition-delay:0.2s;">
        <span style="font-size:3rem;">🌸</span>
        <div class="overlay">The Flowers</div>
      </div>
      <div class="gallery-item reveal" onclick="openLightbox('Family Blessings','Surrounded by family, wrapped in du\'as and love.')" style="transition-delay:0.3s;">
        <span style="font-size:3rem;">🤲</span>
        <div class="overlay">Family Blessings</div>
      </div>
      <div class="gallery-item reveal" onclick="openLightbox('The Lanterns','Golden lanterns lighting the way to a blessed new chapter.')" style="transition-delay:0.4s;">
        <span style="font-size:3rem;">🏮</span>
        <div class="overlay">The Lanterns</div>
      </div>
      <div class="gallery-item reveal" onclick="openLightbox('Sweet Beginnings','A sweet start to a beautiful journey together.')" style="transition-delay:0.5s;">
        <span style="font-size:3rem;">🎂</span>
        <div class="overlay">Sweet Beginnings</div>
      </div>
    </div>
  </section>

  <!-- ===== WISHES ===== -->
  <div id="wishes">
    <div class="inner">
      <div class="section-heading reveal">
        <span class="subtitle">Share Your Love</span>
        <h2>Wedding Wishes</h2>
        <div class="ornament">
          <hr><div class="diamond"></div><hr>
        </div>
      </div>

      <div class="wishes-form reveal">
        <h3>💌 Leave a Wish for the Couple</h3>
        <div class="form-row">
          <div class="form-group">
            <label>Your Name</label>
            <input type="text" id="wish-name" placeholder="Your beautiful name" />
          </div>
          <div class="form-group">
            <label>Relation</label>
            <select id="wish-relation">
              <option value="Family">Family</option>
              <option value="Friend">Friend</option>
              <option value="Colleague">Colleague</option>
              <option value="Neighbour">Neighbour</option>
              <option value="Guest">Guest</option>
            </select>
          </div>
        </div>
        <div class="form-group" style="margin-bottom:1rem;">
          <label>Your Wish / Du'a</label>
          <textarea id="wish-text" placeholder="Share your heartfelt wishes and du'as for the couple..."></textarea>
        </div>
        <button class="btn-primary" onclick="submitWish()">
          <span>💛</span> Send Your Wishes
        </button>
      </div>

      <div class="wish-cards" id="wish-list"></div>
    </div>
  </div>

  <!-- ===== LOCATION ===== -->
  <div id="location">
    <div class="inner">
      <div class="section-heading reveal">
        <span class="subtitle">Find Your Way To Us</span>
        <h2>Venue & Location</h2>
        <div class="ornament">
          <hr><div class="diamond"></div><hr>
        </div>
      </div>

      <div class="location-card reveal">
        <div class="location-map">
          <div class="map-placeholder">
            <span class="map-pin">📍</span>
            <p style="font-size:1.1rem; color:var(--brown); font-weight:600;">Vembadi Pallivasal</p>
            <p>Tenkasi, Tamil Nadu</p>
          </div>
        </div>
        <div class="location-info">
          <div class="location-detail">
            <h4>Venue</h4>
            <p>Vembadi Pallivasal<br>Tenkasi, Tamil Nadu, India</p>
          </div>
          <div class="location-detail">
            <h4>Date & Time</h4>
            <p>Sunday, April 12, 2026<br>10:00 AM onwards</p>
          </div>
          <div class="location-detail">
            <h4>Dress Code</h4>
            <p>Formal / Traditional attire<br>Ladies: Modest dress</p>
          </div>
          <div class="location-detail">
            <h4>Contact</h4>
            <p>For queries, reach out to<br>the wedding family</p>
          </div>
        </div>
        <div style="padding:0 2rem 2rem; text-align:center;">
          <a class="btn-directions" href="https://maps.google.com/?q=Tenkasi,Tamil+Nadu,India" target="_blank">
            🗺️ Get Directions
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== RSVP ===== -->
  <div id="rsvp">
    <div class="inner">
      <div class="section-heading reveal">
        <span class="subtitle">Let Us Know</span>
        <h2>RSVP</h2>
        <div class="ornament">
          <hr><div class="diamond"></div><hr>
        </div>
      </div>

      <div class="rsvp-card reveal">
        <div class="dua">بَارَكَ اللهُ لَكُمْ</div>
        <p>We humbly request the honour of your presence at our wedding celebration. Your blessings and du'as mean the world to us. Please let us know if you'll be joining us on this beautiful day.</p>

        <div id="rsvp-form">
          <div style="display:flex; flex-direction:column; gap:1rem; max-width:400px; margin:0 auto 1.5rem;">
            <div class="form-group">
              <label>Your Name</label>
              <input type="text" id="rsvp-name" placeholder="Your name" />
            </div>
            <div class="form-group">
              <label>Number of Guests</label>
              <select id="rsvp-guests">
                <option value="1">Just me (1)</option>
                <option value="2">2 guests</option>
                <option value="3">3 guests</option>
                <option value="4">4 guests</option>
                <option value="5+">5+ guests</option>
              </select>
            </div>
          </div>
          <div class="rsvp-btns">
            <button class="btn-yes" onclick="sendRSVP(true)">💛 Yes, I'll Be There!</button>
            <button class="btn-no" onclick="sendRSVP(false)">Unable to Attend</button>
          </div>
        </div>

        <div class="rsvp-success" id="rsvp-success">
          JazakAllahu Khairan! 🌸<br>
          <span style="font-family:'Cormorant Garamond',serif; font-size:1rem; color:var(--brown-light);">We can't wait to celebrate with you!</span>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== FOOTER ===== -->
  <footer>
    <div class="footer-hearts">
      <span>🌸</span><span>❤️</span><span>🌸</span>
    </div>
    <div class="footer-names">S. Mohamed Suhail & M. Aafiyathul Marliya</div>
    <div class="footer-date">Sunday · April 12, 2026 · Tenkasi</div>
    <div class="footer-dua">بَارَكَ اللهُ لَكَ، وَبَارَكَ عَلَيْكَ، وَجَمَعَ بَيْنَكُمَا فِي خَيْرٍ</div>
    <div class="footer-copy">May Allah bless this union with love, mercy, and happiness · Ameen</div>
  </footer>

</div><!-- end #page -->

<!-- Music Button -->
<button id="music-btn" title="Toggle music" onclick="toggleMusic()">🎵</button>

<!-- Toast -->
<div class="toast" id="toast"></div>

<!-- Lightbox -->
<div class="lightbox" id="lightbox" onclick="closeLightbox(event)">
  <button class="lightbox-close" onclick="closeLightbox()">✕</button>
  <div class="lightbox-content">
    <div id="lb-emoji" style="font-size:5rem; margin-bottom:1rem;"></div>
    <h3 id="lb-title" style="font-family:'Playfair Display',serif; color:var(--brown); font-size:1.4rem; margin-bottom:0.5rem;"></h3>
    <p id="lb-desc" style="font-family:'Cormorant Garamond',serif; color:var(--brown-light); font-size:1rem;"></p>
  </div>
</div>

<script>
/* ===== LOADING ===== */
window.addEventListener('load', () => {
  setTimeout(() => {
    document.getElementById('loading').classList.add('hidden');
    document.getElementById('page').classList.add('visible');
    initPetals();
  }, 1800);
});

/* ===== NAV SHOW ON SCROLL ===== */
const nav = document.getElementById('main-nav');
window.addEventListener('scroll', () => {
  if (window.scrollY > 80) nav.classList.add('visible');
  else nav.classList.remove('visible');
});

/* ===== SCROLL REVEAL ===== */
const revealEls = document.querySelectorAll('.reveal, .reveal-left, .reveal-right');
const observer = new IntersectionObserver((entries) => {
  entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); } });
}, { threshold: 0.12 });
revealEls.forEach(el => observer.observe(el));

/* ===== COUNTDOWN ===== */
const weddingDate = new Date('2026-04-12T10:00:00');
function updateCountdown() {
  const now = new Date();
  const diff = weddingDate - now;
  if (diff <= 0) {
    document.getElementById('cd-days').textContent = '00';
    document.getElementById('cd-hours').textContent = '00';
    document.getElementById('cd-mins').textContent = '00';
    document.getElementById('cd-secs').textContent = '00';
    return;
  }
  const d = Math.floor(diff / (1000*60*60*24));
  const h = Math.floor((diff % (1000*60*60*24)) / (1000*60*60));
  const m = Math.floor((diff % (1000*60*60)) / (1000*60));
  const s = Math.floor((diff % (1000*60)) / 1000);
  document.getElementById('cd-days').textContent  = String(d).padStart(2,'0');
  document.getElementById('cd-hours').textContent = String(h).padStart(2,'0');
  document.getElementById('cd-mins').textContent  = String(m).padStart(2,'0');
  document.getElementById('cd-secs').textContent  = String(s).padStart(2,'0');
}
updateCountdown();
setInterval(updateCountdown, 1000);

/* ===== FALLING PETALS ===== */
const canvas = document.getElementById('petals-canvas');
const ctx = canvas.getContext('2d');
let petals = [];

function resize() {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
}
resize();
window.addEventListener('resize', resize);

function initPetals() {
  petals = [];
  for (let i = 0; i < 28; i++) {
    petals.push(createPetal(true));
  }
  animatePetals();
}

function createPetal(randomY = false) {
  const colors = ['rgba(212,160,160,0.55)', 'rgba(248,192,192,0.45)', 'rgba(232,213,163,0.4)', 'rgba(201,168,76,0.3)', 'rgba(244,192,192,0.5)'];
  return {
    x: Math.random() * canvas.width,
    y: randomY ? Math.random() * canvas.height : -20,
    size: 8 + Math.random() * 14,
    color: colors[Math.floor(Math.random() * colors.length)],
    speedY: 0.5 + Math.random() * 1,
    speedX: (Math.random() - 0.5) * 0.6,
    rotation: Math.random() * Math.PI * 2,
    rotSpeed: (Math.random() - 0.5) * 0.04,
    opacity: 0.4 + Math.random() * 0.5,
  };
}

function drawPetal(p) {
  ctx.save();
  ctx.translate(p.x, p.y);
  ctx.rotate(p.rotation);
  ctx.globalAlpha = p.opacity;
  ctx.fillStyle = p.color;
  ctx.beginPath();
  ctx.ellipse(0, 0, p.size * 0.5, p.size, 0, 0, Math.PI * 2);
  ctx.fill();
  ctx.restore();
}

function animatePetals() {
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  petals.forEach((p, i) => {
    drawPetal(p);
    p.y += p.speedY;
    p.x += p.speedX + Math.sin(p.y * 0.01) * 0.3;
    p.rotation += p.rotSpeed;
    if (p.y > canvas.height + 30) {
      petals[i] = createPetal(false);
    }
  });
  requestAnimationFrame(animatePetals);
}
/*=====music=====*/

const music = document.getElementById("bg-music");
const btn = document.getElementById("music-btn");

function toggleMusic() {
  if (music.paused) {
    music.play();
    btn.textContent = '🔊';
    btn.classList.add('playing');
    showToast('🎵 Music playing...');
  } else {
    music.pause();
    btn.textContent = '🎵';
    btn.classList.remove('playing');
    showToast('Music paused');
  }
}


/* ===== TOAST ===== */
function showToast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 3000);
}

/* ===== WISHES ===== */
const defaultWishes = [
  { name: 'Fatimah', relation: 'Family', text: 'May Allah bless your union with love, mercy and understanding. Wishing you a lifetime of happiness together! Ameen 🌸' },
  { name: 'Ibrahim', relation: 'Friend', text: 'Mabrook to my dear friend! May your home be filled with joy and your hearts with gratitude. JazakAllahu Khairan.' },
  { name: 'Ayesha Banu', relation: 'Neighbour', text: 'A beautiful couple, a blessed beginning! May Allah grant you both Jannah together. Ameen ❤️' },
];

function renderWishes(wishes) {
  const list = document.getElementById('wish-list');
  list.innerHTML = wishes.map(w => `
    <div class="wish-card">
      <div class="wish-author">💛 ${w.name}</div>
      <div class="wish-relation">${w.relation}</div>
      <p>${w.text}</p>
    </div>
  `).join('');
}

renderWishes(defaultWishes);


 function submitWish() {
  const name = document.getElementById('wish-name').value.trim();
  const relation = document.getElementById('wish-relation').value;
  const text = document.getElementById('wish-text').value.trim();

  if (!name || !text) {
    showToast('Please fill in your name and wish 💛');
    return;
  }

  const formData = new FormData();
  formData.append("name", name);
  formData.append("relation", relation);
  formData.append("text", text);

  fetch("https://script.google.com/macros/s/AKfycby6XP04xdIRPg_cWJvKH7-V1_7FFObtxFBlhTQs5kqYxzwNgN7zlps3Nbc2ATY9uvU/exec", {
    method: "POST",
    body: formData
  })
  .then(() => {
    defaultWishes.unshift({ name, relation, text });
    renderWishes(defaultWishes);

    document.getElementById('wish-name').value = '';
    document.getElementById('wish-text').value = '';

    showToast('Wish saved successfully 💛');
  })
  .catch(err => {
    console.error(err);
    showToast('Error saving wish 😢');
  });
}

/* ===== RSVP ===== */
function sendRSVP(attending) {
  const name = document.getElementById('rsvp-name').value.trim();
  if (!name) { showToast('Please enter your name 💛'); return; }
  const guests = document.getElementById('rsvp-guests').value;
  if (attending) {
    showToast(`Mabrook! We can't wait to see you, ${name}! 🌸`);
    document.getElementById('rsvp-form').style.display = 'none';
    document.getElementById('rsvp-success').style.display = 'block';
  } else {
    showToast(`We'll miss you, ${name}. Thank you for letting us know. 💛`);
    document.getElementById('rsvp-form').style.display = 'none';
    document.getElementById('rsvp-success').style.display = 'block';
    document.getElementById('rsvp-success').innerHTML = `
      JazakAllahu Khairan, ${name}! 🌸<br>
      <span style="font-family:'Cormorant Garamond',serif; font-size:1rem; color:var(--brown-light);">Your prayers and du'as are always welcome even from afar.</span>
    `;
  }
}

/* ===== LIGHTBOX ===== */
const galleryData = [
  { emoji: '💒', title: 'The Venue', desc: 'Vembadi Pallivasal, Tenkasi — a beautiful setting for a beautiful union.' },
  { emoji: '💍', title: 'The Rings', desc: 'Two rings, one promise — a lifetime of love and loyalty.' },
  { emoji: '🌸', title: 'The Flowers', desc: 'Roses in bloom for a day that blooms with love.' },
  { emoji: '🤲', title: 'Family Blessings', desc: "Surrounded by family, wrapped in du'as and love." },
  { emoji: '🏮', title: 'The Lanterns', desc: 'Golden lanterns lighting the way to a blessed new chapter.' },
  { emoji: '🎂', title: 'Sweet Beginnings', desc: 'A sweet start to a beautiful journey together.' },
];

function openLightbox(title, desc) {
  const data = galleryData.find(g => g.title === title) || { emoji: '💒', title, desc };
  document.getElementById('lb-emoji').textContent = data.emoji;
  document.getElementById('lb-title').textContent = data.title;
  document.getElementById('lb-desc').textContent = data.desc;
  document.getElementById('lightbox').classList.add('open');
}

function closeLightbox(e) {
  if (!e || e.target === document.getElementById('lightbox') || e.currentTarget.classList.contains('lightbox-close')) {
    document.getElementById('lightbox').classList.remove('open');
  }
}
</script>
</body>
</html>
