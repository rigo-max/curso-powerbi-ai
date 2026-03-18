<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Power BI + IA — Curso Completo</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;600;700;800&family=IBM+Plex+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0a0f;
    --surface: #111118;
    --surface2: #16161f;
    --border: #1e1e2e;
    --accent: #f5a623;
    --accent2: #e8336d;
    --accent3: #00d4aa;
    --accent4: #6c63ff;
    --text: #e8e8f0;
    --text-dim: #8888a8;
    --text-muted: #55556a;
    --gold: #f5a623;
    --glow: rgba(245,166,35,0.15);
  }

  * { margin:0; padding:0; box-sizing:border-box; }

  body {
    font-family: 'IBM Plex Sans', sans-serif;
    background: var(--bg);
    color: var(--text);
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* ─── VOICE BAR ─── */
  .voice-bar {
    position: fixed;
    bottom: 0; left: 0; right: 0;
    background: #0d0d18;
    border-top: 1px solid var(--border);
    padding: 10px 24px;
    display: flex;
    align-items: center;
    gap: 14px;
    z-index: 1000;
    box-shadow: 0 -4px 24px rgba(0,0,0,0.5);
  }

  .voice-icon {
    font-size: 20px;
    animation: none;
  }

  .voice-icon.speaking {
    animation: speakPulse 0.8s infinite alternate;
  }

  @keyframes speakPulse {
    from { transform: scale(1); filter: brightness(1); }
    to   { transform: scale(1.2); filter: brightness(1.5); }
  }

  .voice-label {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: var(--text-muted);
    letter-spacing: 1px;
    text-transform: uppercase;
    min-width: 80px;
  }

  .voice-text-preview {
    flex: 1;
    font-size: 12px;
    color: var(--text-dim);
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    font-style: italic;
  }

  .voice-controls {
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .voice-btn {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 6px 14px;
    color: var(--text-dim);
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    cursor: pointer;
    transition: all 0.2s;
    letter-spacing: 0.5px;
  }

  .voice-btn:hover { border-color: var(--accent); color: var(--accent); }
  .voice-btn.active { background: rgba(245,166,35,0.15); border-color: var(--accent); color: var(--accent); }
  .voice-btn.stop-btn:hover { border-color: var(--accent2); color: var(--accent2); }

  .voice-speed {
    display: flex;
    align-items: center;
    gap: 6px;
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    color: var(--text-muted);
  }

  .voice-speed input[type=range] {
    width: 70px;
    accent-color: var(--accent);
  }

  .voice-toggle {
    background: none;
    border: 1px solid var(--border);
    border-radius: 50%;
    width: 32px; height: 32px;
    display: flex; align-items: center; justify-content: center;
    cursor: pointer;
    color: var(--text-muted);
    font-size: 14px;
    transition: all 0.2s;
  }

  .voice-toggle:hover { border-color: var(--accent2); color: var(--accent2); }

  /* ─── HEADER HERO ─── */
  .hero {
    position: relative;
    padding: 80px 40px 60px;
    text-align: center;
    overflow: hidden;
    border-bottom: 1px solid var(--border);
  }

  .hero::before {
    content: '';
    position: absolute;
    top: -100px; left: 50%;
    transform: translateX(-50%);
    width: 600px; height: 600px;
    background: radial-gradient(ellipse, rgba(245,166,35,0.12) 0%, transparent 70%);
    pointer-events: none;
  }

  .hero-badge {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: rgba(245,166,35,0.1);
    border: 1px solid rgba(245,166,35,0.3);
    border-radius: 100px;
    padding: 6px 18px;
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: var(--accent);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 28px;
  }

  .hero-badge::before {
    content: '';
    width: 8px; height: 8px;
    border-radius: 50%;
    background: var(--accent);
    animation: pulse 2s infinite;
  }

  @keyframes pulse {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.5; transform: scale(0.8); }
  }

  .hero h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(42px, 7vw, 80px);
    font-weight: 800;
    line-height: 1;
    letter-spacing: -2px;
    margin-bottom: 16px;
  }

  .hero h1 span.gold { color: var(--accent); }
  .hero h1 span.pink { color: var(--accent2); }

  .hero-sub {
    font-size: 17px;
    color: var(--text-dim);
    max-width: 600px;
    margin: 0 auto 40px;
    line-height: 1.7;
  }

  .hero-stats {
    display: flex;
    justify-content: center;
    gap: 40px;
    flex-wrap: wrap;
  }

  .stat { text-align: center; }

  .stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 32px;
    font-weight: 800;
    color: var(--accent);
    display: block;
  }

  .stat-label {
    font-size: 12px;
    color: var(--text-muted);
    text-transform: uppercase;
    letter-spacing: 1.5px;
    font-family: 'Space Mono', monospace;
  }

  /* ─── LAYOUT ─── */
  .layout {
    display: grid;
    grid-template-columns: 280px 1fr;
    min-height: calc(100vh - 320px);
  }

  /* ─── SIDEBAR ─── */
  .sidebar {
    background: var(--surface);
    border-right: 1px solid var(--border);
    padding: 24px 0;
    position: sticky;
    top: 0;
    height: 100vh;
    overflow-y: auto;
  }

  .sidebar::-webkit-scrollbar { width: 4px; }
  .sidebar::-webkit-scrollbar-thumb { background: var(--border); border-radius: 2px; }

  .sidebar-title {
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    color: var(--text-muted);
    letter-spacing: 2px;
    text-transform: uppercase;
    padding: 0 20px 16px;
    border-bottom: 1px solid var(--border);
    margin-bottom: 8px;
  }

  .module-nav { list-style: none; }

  .module-btn {
    width: 100%;
    background: none;
    border: none;
    text-align: left;
    padding: 10px 20px;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 10px;
    transition: all 0.2s;
    border-left: 3px solid transparent;
  }

  .module-btn:hover { background: var(--surface2); }

  .module-btn.active {
    background: var(--glow);
    border-left-color: var(--accent);
  }

  .module-btn.active .mod-num { color: var(--accent); }
  .module-btn.active .mod-name { color: var(--text); }

  .mod-num {
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    color: var(--text-muted);
    min-width: 28px;
  }

  .mod-name {
    font-size: 13px;
    color: var(--text-dim);
    line-height: 1.3;
    font-weight: 500;
  }

  .mod-tag {
    margin-left: auto;
    font-size: 9px;
    padding: 2px 7px;
    border-radius: 100px;
    font-family: 'Space Mono', monospace;
  }

  .tag-new { background: rgba(0,212,170,0.15); color: var(--accent3); }
  .tag-ai  { background: rgba(108,99,255,0.15); color: var(--accent4); }
  .tag-pro { background: rgba(232,51,109,0.15); color: var(--accent2); }

  /* ─── MAIN CONTENT ─── */
  .main {
    padding: 40px 48px;
    max-width: 900px;
    padding-bottom: 80px;
  }

  .module-content { display: none; animation: fadeIn 0.3s ease; }
  .module-content.active { display: block; }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .mod-header {
    margin-bottom: 36px;
    padding-bottom: 28px;
    border-bottom: 1px solid var(--border);
  }

  .mod-eyebrow {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: var(--accent);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 12px;
  }

  .mod-title {
    font-family: 'Syne', sans-serif;
    font-size: clamp(28px, 4vw, 42px);
    font-weight: 800;
    letter-spacing: -1px;
    line-height: 1.1;
    margin-bottom: 14px;
  }

  .mod-desc {
    color: var(--text-dim);
    font-size: 15px;
    line-height: 1.7;
    max-width: 700px;
  }

  /* ─── CARDS ─── */
  .cards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 16px;
    margin: 28px 0;
  }

  .card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 22px;
    transition: all 0.25s;
    position: relative;
    overflow: hidden;
  }

  .card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: var(--card-color, var(--accent));
    opacity: 0;
    transition: opacity 0.25s;
  }

  .card:hover { border-color: rgba(245,166,35,0.3); transform: translateY(-2px); }
  .card:hover::before { opacity: 1; }

  .card-icon { font-size: 28px; margin-bottom: 12px; display: block; }

  .card-title {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 15px;
    margin-bottom: 8px;
    color: var(--text);
  }

  .card-text { font-size: 13px; color: var(--text-dim); line-height: 1.6; }

  /* ─── SECTION TITLES ─── */
  h2.section {
    font-family: 'Syne', sans-serif;
    font-size: 22px;
    font-weight: 700;
    margin: 36px 0 16px;
    color: var(--text);
    display: flex;
    align-items: center;
    gap: 10px;
  }

  h2.section::after { content: ''; flex: 1; height: 1px; background: var(--border); }

  h3.subsection {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 700;
    margin: 24px 0 10px;
    color: var(--accent);
  }

  p.body { font-size: 14px; color: var(--text-dim); line-height: 1.8; margin-bottom: 16px; }

  /* ─── CODE BLOCKS ─── */
  .code-block {
    background: #0d0d14;
    border: 1px solid var(--border);
    border-radius: 10px;
    margin: 16px 0;
    overflow: hidden;
  }

  .code-bar {
    background: var(--surface);
    padding: 8px 16px;
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    color: var(--text-muted);
    letter-spacing: 1px;
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .code-dot { width: 10px; height: 10px; border-radius: 50%; }
  .dot-r { background: #ff5f57; }
  .dot-y { background: #febc2e; }
  .dot-g { background: #28c840; }
  .code-bar span { margin-left: 6px; }

  pre {
    padding: 20px;
    font-family: 'Space Mono', monospace;
    font-size: 12px;
    line-height: 1.7;
    color: #c9d1d9;
    overflow-x: auto;
  }

  .kw  { color: #ff7b72; }
  .fn  { color: #d2a8ff; }
  .str { color: #a5d6ff; }
  .cm  { color: #555a6f; }
  .num { color: #79c0ff; }
  .op  { color: #f5a623; }

  /* ─── STEPS ─── */
  .steps { counter-reset: step; margin: 20px 0; }

  .step { display: flex; gap: 16px; margin-bottom: 20px; position: relative; }

  .step::before {
    counter-increment: step;
    content: counter(step);
    min-width: 32px; height: 32px;
    background: rgba(245,166,35,0.1);
    border: 1px solid rgba(245,166,35,0.3);
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: var(--accent);
    font-weight: 700;
    flex-shrink: 0;
    margin-top: 2px;
  }

  .step-body { flex: 1; }
  .step-title { font-weight: 600; font-size: 14px; margin-bottom: 6px; color: var(--text); }
  .step-text  { font-size: 13px; color: var(--text-dim); line-height: 1.7; }

  /* ─── TIPS ─── */
  .tip {
    display: flex;
    gap: 14px;
    background: rgba(0,212,170,0.07);
    border: 1px solid rgba(0,212,170,0.2);
    border-radius: 10px;
    padding: 16px 18px;
    margin: 20px 0;
  }

  .tip-icon { font-size: 20px; flex-shrink: 0; margin-top: 1px; }

  .tip-body strong {
    display: block;
    font-size: 13px;
    color: var(--accent3);
    margin-bottom: 4px;
    font-family: 'Space Mono', monospace;
  }

  .tip-body p { font-size: 13px; color: var(--text-dim); line-height: 1.6; margin: 0; }

  .warn { background: rgba(232,51,109,0.07); border-color: rgba(232,51,109,0.2); }
  .warn .tip-body strong { color: var(--accent2); }

  /* ─── TABLE ─── */
  .table-wrap { overflow-x: auto; margin: 20px 0; }

  table { width: 100%; border-collapse: collapse; font-size: 13px; }

  th {
    background: var(--surface);
    padding: 12px 16px;
    text-align: left;
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: var(--text-muted);
    letter-spacing: 1px;
    text-transform: uppercase;
    border-bottom: 2px solid var(--border);
  }

  td {
    padding: 12px 16px;
    border-bottom: 1px solid var(--border);
    color: var(--text-dim);
    line-height: 1.5;
  }

  td strong { color: var(--accent); font-size: 12px; font-family: 'Space Mono', monospace; }
  tr:hover td { background: rgba(255,255,255,0.02); }

  /* ─── HIGHLIGHT BOX ─── */
  .highlight {
    background: linear-gradient(135deg, rgba(245,166,35,0.08), rgba(108,99,255,0.08));
    border: 1px solid rgba(245,166,35,0.2);
    border-radius: 12px;
    padding: 24px;
    margin: 24px 0;
  }

  .highlight-title { font-family: 'Syne', sans-serif; font-size: 16px; font-weight: 700; color: var(--accent); margin-bottom: 10px; }
  .highlight p { font-size: 14px; color: var(--text-dim); line-height: 1.7; margin: 0; }

  /* ─── TAGS LIST ─── */
  .tags { display: flex; flex-wrap: wrap; gap: 8px; margin: 16px 0; }

  .tag {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 5px 12px;
    font-size: 12px;
    color: var(--text-dim);
    font-family: 'Space Mono', monospace;
  }

  /* ─── PROGRESS BAR ─── */
  .progress-bar { height: 3px; background: var(--border); border-radius: 2px; margin: 12px 0 6px; overflow: hidden; }
  .progress-fill { height: 100%; border-radius: 2px; background: linear-gradient(90deg, var(--accent), var(--accent2)); }

  /* ─── NAV FOOTER ─── */
  .mod-nav-footer {
    display: flex;
    gap: 12px;
    margin-top: 48px;
    padding-top: 24px;
    border-top: 1px solid var(--border);
  }

  .nav-btn {
    flex: 1;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 14px 20px;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 10px;
    transition: all 0.2s;
    color: var(--text-dim);
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 13px;
  }

  .nav-btn:hover { border-color: rgba(245,166,35,0.4); color: var(--text); background: var(--glow); }
  .nav-btn.next { justify-content: flex-end; }
  .nav-btn .arrow { font-size: 18px; color: var(--accent); }

  /* ─── RESPONSIVE ─── */
  @media (max-width: 768px) {
    .layout { grid-template-columns: 1fr; }
    .sidebar { height: auto; position: static; }
    .main { padding: 28px 20px 80px; }
    .hero { padding: 50px 20px 40px; }
    .voice-bar { padding: 8px 12px; gap: 8px; }
    .voice-speed { display: none; }
  }
</style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <div class="hero-badge">Curso Completo · 2025</div>
  <h1>Power BI<br><span class="gold">+</span> Inteligencia <span class="pink">Artificial</span></h1>
  <p class="hero-sub">Desde cero hasta dashboards con IA integrada. Aprende a analizar datos con Copilot, DAX inteligente, ML y narrativas automáticas.</p>
  <div class="hero-stats">
    <div class="stat"><span class="stat-num">12</span><span class="stat-label">Módulos</span></div>
    <div class="stat"><span class="stat-num">80+</span><span class="stat-label">Lecciones</span></div>
    <div class="stat"><span class="stat-num">15+</span><span class="stat-label">Labs prácticos</span></div>
    <div class="stat"><span class="stat-num">∞</span><span class="stat-label">Nivel pro</span></div>
  </div>
</div>

<!-- LAYOUT -->
<div class="layout">

  <!-- SIDEBAR -->
  <nav class="sidebar">
    <div class="sidebar-title">Módulos del Curso</div>
    <ul class="module-nav">
      <li><button class="module-btn active" onclick="showModule(0)"><span class="mod-num">01</span><span class="mod-name">Introducción a Power BI</span></button></li>
      <li><button class="module-btn" onclick="showModule(1)"><span class="mod-num">02</span><span class="mod-name">Conectar & Transformar Datos</span></button></li>
      <li><button class="module-btn" onclick="showModule(2)"><span class="mod-num">03</span><span class="mod-name">Modelado de Datos</span></button></li>
      <li><button class="module-btn" onclick="showModule(3)"><span class="mod-num">04</span><span class="mod-name">DAX: Lenguaje de Medidas</span></button></li>
      <li><button class="module-btn" onclick="showModule(4)"><span class="mod-num">05</span><span class="mod-name">Visualizaciones Avanzadas</span></button></li>
      <li><button class="module-btn" onclick="showModule(5)"><span class="mod-num">06</span><span class="mod-name">Power BI Copilot IA</span><span class="mod-tag tag-ai">IA</span></button></li>
      <li><button class="module-btn" onclick="showModule(6)"><span class="mod-num">07</span><span class="mod-name">Smart Narratives & Q&A</span><span class="mod-tag tag-ai">IA</span></button></li>
      <li><button class="module-btn" onclick="showModule(7)"><span class="mod-num">08</span><span class="mod-name">Machine Learning con Azure</span><span class="mod-tag tag-pro">PRO</span></button></li>
      <li><button class="module-btn" onclick="showModule(8)"><span class="mod-num">09</span><span class="mod-name">Análisis de Sentimiento NLP</span><span class="mod-tag tag-ai">IA</span></button></li>
      <li><button class="module-btn" onclick="showModule(9)"><span class="mod-num">10</span><span class="mod-name">Anomaly Detection</span><span class="mod-tag tag-new">NEW</span></button></li>
      <li><button class="module-btn" onclick="showModule(10)"><span class="mod-num">11</span><span class="mod-name">Power BI Service & Publicación</span></button></li>
      <li><button class="module-btn" onclick="showModule(11)"><span class="mod-num">12</span><span class="mod-name">Proyecto Final Integrador</span><span class="mod-tag tag-pro">PRO</span></button></li>
    </ul>
  </nav>

  <!-- MAIN -->
  <main class="main">

    <!-- ═══ MÓDULO 01 ═══ -->
    <div class="module-content active" id="mod-0">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 01 · Fundamentos</div>
        <h1 class="mod-title">Introducción a Power BI</h1>
        <p class="mod-desc">Entiende el ecosistema completo de Power BI, sus herramientas y la nueva era de análisis potenciado por inteligencia artificial.</p>
      </div>
      <h2 class="section">¿Qué es Power BI?</h2>
      <p class="body">Power BI es la plataforma de Business Intelligence de Microsoft que permite conectar, transformar, modelar y visualizar datos de cualquier fuente. En 2024–2025, Microsoft integró Copilot (su IA generativa basada en GPT-4) directamente en Power BI, revolucionando la forma en que creamos reportes.</p>
      <div class="cards-grid">
        <div class="card" style="--card-color: #f5a623;"><span class="card-icon">🖥️</span><div class="card-title">Power BI Desktop</div><div class="card-text">Herramienta gratuita para Windows. Aquí creas los modelos, medidas DAX y visualizaciones.</div></div>
        <div class="card" style="--card-color: #6c63ff;"><span class="card-icon">☁️</span><div class="card-title">Power BI Service</div><div class="card-text">Plataforma web (app.powerbi.com) para publicar, compartir y colaborar en reportes.</div></div>
        <div class="card" style="--card-color: #00d4aa;"><span class="card-icon">📱</span><div class="card-title">Power BI Mobile</div><div class="card-text">Apps iOS/Android para consumir dashboards desde cualquier lugar.</div></div>
        <div class="card" style="--card-color: #e8336d;"><span class="card-icon">🤖</span><div class="card-title">Power BI Copilot</div><div class="card-text">IA generativa que crea reportes, escribe DAX y responde preguntas en lenguaje natural.</div></div>
      </div>
      <h2 class="section">Ecosistema Microsoft + IA</h2>
      <div class="table-wrap"><table><thead><tr><th>Componente</th><th>Función</th><th>IA integrada</th></tr></thead><tbody>
        <tr><td><strong>Power Query</strong></td><td>ETL: Extracción, transformación y carga de datos</td><td>Copilot genera transformaciones</td></tr>
        <tr><td><strong>DAX</strong></td><td>Lenguaje de cálculo para medidas y columnas</td><td>Copilot escribe y explica DAX</td></tr>
        <tr><td><strong>Azure ML</strong></td><td>Modelos de Machine Learning en la nube</td><td>Predicciones en tiempo real</td></tr>
        <tr><td><strong>Cognitive Services</strong></td><td>APIs de IA (visión, texto, voz)</td><td>NLP, sentimiento, OCR</td></tr>
        <tr><td><strong>Fabric</strong></td><td>Plataforma unificada de datos</td><td>Copilot for Data Engineering</td></tr>
      </tbody></table></div>
      <h2 class="section">Instalación y Configuración</h2>
      <div class="steps">
        <div class="step"><div class="step-body"><div class="step-title">Descargar Power BI Desktop</div><div class="step-text">Ve a powerbi.microsoft.com o descárgalo desde Microsoft Store. Es gratuito para uso individual. Requiere Windows 8.1 o superior.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Crear cuenta Microsoft 365</div><div class="step-text">Regístrate con tu correo corporativo o personal. Para Copilot necesitas licencia Power BI Pro o Premium Per User.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Activar características de IA</div><div class="step-text">En Power BI Desktop → Archivo → Opciones → Características de versión preliminar → Activa Copilot y Quick Measure Suggestions.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Primer reporte en 5 minutos</div><div class="step-text">Abre Power BI Desktop → Obtener datos → Excel → selecciona cualquier archivo con datos tabulares → ya tienes tu primer dataset.</div></div></div>
      </div>
      <div class="tip"><div class="tip-icon">💡</div><div class="tip-body"><strong>TIP PRO</strong><p>Usa Power BI Desktop en modo Desarrollador para ver el JSON interno del modelo. Esto te ayudará enormemente cuando trabajes con proyectos grandes.</p></div></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" disabled><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(1)">Siguiente: Conectar Datos <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 02 ═══ -->
    <div class="module-content" id="mod-1">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 02 · ETL</div>
        <h1 class="mod-title">Conectar & Transformar Datos</h1>
        <p class="mod-desc">Power Query es el motor ETL de Power BI. Aprende a conectar más de 100 fuentes y transformar datos sucios en oro analítico.</p>
      </div>
      <h2 class="section">Fuentes de Datos Principales</h2>
      <div class="tags"><span class="tag">Excel / CSV</span><span class="tag">SQL Server</span><span class="tag">PostgreSQL</span><span class="tag">Google Sheets</span><span class="tag">SharePoint</span><span class="tag">Salesforce</span><span class="tag">REST API</span><span class="tag">JSON / XML</span><span class="tag">Azure SQL</span><span class="tag">SAP HANA</span><span class="tag">Fabric</span><span class="tag">Dataverse</span><span class="tag">Web Scraping</span><span class="tag">Oracle DB</span><span class="tag">MySQL</span></div>
      <h2 class="section">Power Query: El Editor M</h2>
      <p class="body">Cada transformación en Power Query genera código M, el Power Query Formula Language. Copilot puede escribir estas transformaciones en lenguaje natural.</p>
      <div class="code-block"><div class="code-bar"><div class="code-dot dot-r"></div><div class="code-dot dot-y"></div><div class="code-dot dot-g"></div><span>Power Query M — Transformación de ventas</span></div><pre><span class="kw">let</span>
    Origen = <span class="fn">Excel.Workbook</span>(<span class="fn">File.Contents</span>(<span class="str">"ventas2024.xlsx"</span>), <span class="kw">null</span>, <span class="kw">true</span>),
    Ventas_Sheet = Origen{[<span class="fn">Item</span>=<span class="str">"Ventas"</span>]}[<span class="fn">Data</span>],
    Encabezados = <span class="fn">Table.PromoteHeaders</span>(Ventas_Sheet),
    SinNulos = <span class="fn">Table.SelectRows</span>(Encabezados, each [Monto] <span class="op">&lt;&gt;</span> <span class="kw">null</span>),
    ConCategoria = <span class="fn">Table.AddColumn</span>(SinNulos, <span class="str">"Categoria"</span>, each
        <span class="kw">if</span> [Monto] <span class="op">&gt;</span> <span class="num">10000</span> <span class="kw">then</span> <span class="str">"Premium"</span>
        <span class="kw">else if</span> [Monto] <span class="op">&gt;</span> <span class="num">5000</span> <span class="kw">then</span> <span class="str">"Estándar"</span>
        <span class="kw">else</span> <span class="str">"Básico"</span>)
<span class="kw">in</span> ConCategoria</pre></div>
      <h2 class="section">Copilot en Power Query</h2>
      <div class="highlight"><div class="highlight-title">🤖 Cómo usar Copilot para transformar datos</div><p>En el Editor de Power Query, haz clic en Transformar datos con Copilot y escribe en lenguaje natural lo que necesitas. Copilot generará el código M automáticamente.</p></div>
      <div class="steps">
        <div class="step"><div class="step-body"><div class="step-title">Unpivot — Despivotar columnas</div><div class="step-text">Convierte columnas en filas. Esencial cuando tienes meses como columnas en lugar de una columna Mes con valores.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Merge Queries — Combinar tablas</div><div class="step-text">Equivalente al JOIN de SQL. Une tablas por una columna en común. Tipos: Inner, Left Outer, Right Outer, Full Outer, Anti.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Group By — Agrupar</div><div class="step-text">Agrupa filas y aplica funciones de agregación como Suma, Conteo, Promedio, Mínimo y Máximo.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Custom Functions — Funciones personalizadas</div><div class="step-text">Crea funciones M reutilizables para aplicar la misma transformación a múltiples tablas.</div></div></div>
      </div>
      <div class="tip warn"><div class="tip-icon">⚠️</div><div class="tip-body"><strong>IMPORTANTE: Query Folding</strong><p>Cuando te conectas a bases de datos SQL, Power Query puede delegar las transformaciones al servidor. Mantén el Query Folding activo para maximizar el rendimiento.</p></div></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(0)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(2)">Siguiente: Modelado <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 03 ═══ -->
    <div class="module-content" id="mod-2">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 03 · Modelo de Datos</div>
        <h1 class="mod-title">Modelado de Datos</h1>
        <p class="mod-desc">Un buen modelo es la base de todo. Aprende a construir modelos en estrella, dimensiones y tablas de hechos que potencian el rendimiento.</p>
      </div>
      <h2 class="section">El Modelo en Estrella</h2>
      <p class="body">El modelo en estrella es el estándar de la industria para Power BI. Consiste en una tabla central de hechos rodeada de tablas de dimensiones como clientes, productos, fechas y geografía.</p>
      <div class="cards-grid">
        <div class="card" style="--card-color: #f5a623;"><span class="card-icon">📊</span><div class="card-title">Tabla de Hechos</div><div class="card-text">Contiene las métricas numéricas como ventas, cantidades y costos, además de las claves foráneas hacia las dimensiones.</div></div>
        <div class="card" style="--card-color: #6c63ff;"><span class="card-icon">🗂️</span><div class="card-title">Tabla de Dimensión</div><div class="card-text">Contiene atributos descriptivos: nombres, categorías, jerarquías. Son las tablas de contexto del análisis.</div></div>
        <div class="card" style="--card-color: #00d4aa;"><span class="card-icon">📅</span><div class="card-title">Tabla de Fechas</div><div class="card-text">La dimensión más importante. Debe tener un rango continuo de fechas con atributos como Año, Trimestre, Mes y Semana.</div></div>
      </div>
      <h2 class="section">Relaciones y Cardinalidad</h2>
      <div class="table-wrap"><table><thead><tr><th>Tipo</th><th>Cardinalidad</th><th>Cuándo usarla</th><th>Rendimiento</th></tr></thead><tbody>
        <tr><td><strong>1:N</strong></td><td>Uno a Muchos</td><td>Dim a Fact (estándar)</td><td>Óptimo</td></tr>
        <tr><td><strong>N:1</strong></td><td>Muchos a Uno</td><td>Fact a Dim (inverso)</td><td>Óptimo</td></tr>
        <tr><td><strong>1:1</strong></td><td>Uno a Uno</td><td>Tablas de extensión</td><td>Bueno</td></tr>
        <tr><td><strong>N:M</strong></td><td>Muchos a Muchos</td><td>Casos especiales</td><td>Evitar</td></tr>
      </tbody></table></div>
      <div class="tip"><div class="tip-icon">🎯</div><div class="tip-body"><strong>REGLA DE ORO</strong><p>Las relaciones siempre deben fluir de las tablas de dimensiones hacia las tablas de hechos. Nunca crear relaciones bidireccionales a menos que sea absolutamente necesario.</p></div></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(1)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(3)">Siguiente: DAX <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 04 ═══ -->
    <div class="module-content" id="mod-3">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 04 · Cálculos</div>
        <h1 class="mod-title">DAX: Lenguaje de Medidas</h1>
        <p class="mod-desc">DAX, Data Analysis Expressions, es el corazón analítico de Power BI. Desde SUM hasta CALCULATE, aprende a dominar el lenguaje de fórmulas más potente del BI moderno.</p>
      </div>
      <h2 class="section">Conceptos Fundamentales</h2>
      <div class="cards-grid">
        <div class="card" style="--card-color: #f5a623;"><span class="card-icon">📐</span><div class="card-title">Medidas</div><div class="card-text">Cálculos dinámicos que se recalculan según el contexto del filtro. Son el tipo más común y recomendado.</div></div>
        <div class="card" style="--card-color: #e8336d;"><span class="card-icon">📋</span><div class="card-title">Columnas Calculadas</div><div class="card-text">Se calculan fila por fila durante la carga. Ocupan memoria en el modelo. Úsalas solo para atributos estáticos.</div></div>
        <div class="card" style="--card-color: #6c63ff;"><span class="card-icon">🗃️</span><div class="card-title">Tablas Calculadas</div><div class="card-text">Tablas generadas completamente por DAX. Útiles para tablas de parámetros, fechas o resultados intermedios.</div></div>
      </div>
      <h2 class="section">CALCULATE — La función más poderosa</h2>
      <div class="code-block"><div class="code-bar"><div class="code-dot dot-r"></div><div class="code-dot dot-y"></div><div class="code-dot dot-g"></div><span>DAX — CALCULATE con múltiples contextos</span></div><pre><span class="cm">// Ventas totales</span>
Total Ventas = <span class="fn">SUM</span>(Ventas[Monto])

<span class="cm">// Ventas solo de Lima</span>
Ventas Lima = <span class="fn">CALCULATE</span>([Total Ventas], DimCiudad[Ciudad] = <span class="str">"Lima"</span>)

<span class="cm">// Ventas del año anterior</span>
Ventas Año Anterior = <span class="fn">CALCULATE</span>([Total Ventas], <span class="fn">SAMEPERIODLASTYEAR</span>(DimFecha[Date]))

<span class="cm">// Porcentaje de crecimiento</span>
% Crecimiento = <span class="fn">DIVIDE</span>([Total Ventas] - [Ventas Año Anterior], [Ventas Año Anterior], <span class="num">0</span>)</pre></div>
      <div class="highlight"><div class="highlight-title">🤖 Quick Measure Suggestions con IA</div><p>Desde el panel de datos, clic derecho en Nueva medida rápida, luego Copilot. Describe lo que necesitas en español y Copilot genera el DAX con manejo de errores automáticamente.</p></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(2)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(4)">Siguiente: Visualizaciones <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 05 ═══ -->
    <div class="module-content" id="mod-4">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 05 · Visualización</div>
        <h1 class="mod-title">Visualizaciones Avanzadas</h1>
        <p class="mod-desc">Más allá de los gráficos de barra. Aprende a elegir la visualización correcta, usar visuals de AppSource y crear dashboards ejecutivos.</p>
      </div>
      <h2 class="section">Catálogo de Visualizaciones</h2>
      <div class="cards-grid">
        <div class="card"><span class="card-icon">📊</span><div class="card-title">Barras y Columnas</div><div class="card-text">Comparación de categorías. Ideal para rankings, top N y comparaciones período a período.</div></div>
        <div class="card"><span class="card-icon">📈</span><div class="card-title">Líneas y Área</div><div class="card-text">Tendencias en el tiempo. Combina con banda de confianza para forecasting.</div></div>
        <div class="card"><span class="card-icon">🗺️</span><div class="card-title">Mapas</div><div class="card-text">Visualización geoespacial. Mapa coroplético, burbujas y heat map por región.</div></div>
        <div class="card"><span class="card-icon">🎯</span><div class="card-title">Key Influencers IA</div><div class="card-text">Visual de IA nativo que analiza qué factores influyen más en una métrica objetivo.</div></div>
        <div class="card"><span class="card-icon">🔮</span><div class="card-title">Decomposition Tree</div><div class="card-text">Análisis drill-down automático con IA que encuentra los mayores contribuidores.</div></div>
        <div class="card"><span class="card-icon">📉</span><div class="card-title">Cascada Waterfall</div><div class="card-text">Muestra cómo un valor inicial aumenta o disminuye a través de una serie de cambios.</div></div>
      </div>
      <div class="tip"><div class="tip-icon">🎨</div><div class="tip-body"><strong>DISEÑO PRO</strong><p>Usa temas personalizados en formato JSON para aplicar la paleta de colores corporativa a todo el reporte automáticamente.</p></div></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(3)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(5)">Siguiente: Copilot IA <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 06 ═══ -->
    <div class="module-content" id="mod-5">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 06 · IA Generativa</div>
        <h1 class="mod-title">Power BI Copilot</h1>
        <p class="mod-desc">Copilot transforma el BI. Crea reportes completos desde una descripción, genera DAX con lenguaje natural y obtén resúmenes ejecutivos automáticos.</p>
      </div>
      <h2 class="section">Capacidades de Copilot en Power BI</h2>
      <div class="cards-grid">
        <div class="card" style="--card-color: #6c63ff;"><span class="card-icon">📝</span><div class="card-title">Crear páginas de reporte</div><div class="card-text">Describe lo que quieres y Copilot genera la página completa con visuals, KPIs y filtros.</div></div>
        <div class="card" style="--card-color: #00d4aa;"><span class="card-icon">🧮</span><div class="card-title">Generar medidas DAX</div><div class="card-text">Escribe en español y Copilot produce el código DAX correcto automáticamente.</div></div>
        <div class="card" style="--card-color: #f5a623;"><span class="card-icon">📄</span><div class="card-title">Resumen ejecutivo automático</div><div class="card-text">Copilot analiza el reporte y genera un párrafo ejecutivo describiendo las tendencias más importantes.</div></div>
        <div class="card" style="--card-color: #e8336d;"><span class="card-icon">💬</span><div class="card-title">Responder preguntas</div><div class="card-text">Pregunta en lenguaje natural y Copilot consulta el modelo respondiendo con datos reales.</div></div>
      </div>
      <div class="highlight"><div class="highlight-title">🔑 Licenciamiento para Copilot</div><p>Copilot en Power BI requiere Power BI Premium Per User o workspace en capacidad Premium. El costo es aproximadamente 20 dólares por usuario al mes. En 2025, Microsoft habilitó Copilot también en capacidades Fabric F64.</p></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(4)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(6)">Siguiente: Smart Narratives <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 07 ═══ -->
    <div class="module-content" id="mod-6">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 07 · IA Nativa</div>
        <h1 class="mod-title">Smart Narratives & Q&A</h1>
        <p class="mod-desc">Las funciones de IA nativas de Power BI que transforman datos en insights automáticos y permiten consultas en lenguaje natural.</p>
      </div>
      <h2 class="section">Smart Narratives</h2>
      <p class="body">El visual de Narrativas Inteligentes genera automáticamente párrafos en lenguaje natural que describen los datos del reporte. Se actualiza en tiempo real cuando cambias filtros.</p>
      <h2 class="section">Q&A: Preguntas en Lenguaje Natural</h2>
      <p class="body">Q&A permite a usuarios no técnicos hacer preguntas sobre los datos usando lenguaje coloquial. Power BI interpreta la pregunta y genera el visual adecuado automáticamente.</p>
      <h2 class="section">Key Influencers Visual</h2>
      <p class="body">Uno de los visuals de IA más potentes. Analiza estadísticamente qué factores tienen mayor impacto en una métrica objetivo usando regresión y correlación automática.</p>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(5)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(7)">Siguiente: Machine Learning <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 08 ═══ -->
    <div class="module-content" id="mod-7">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 08 · ML Avanzado</div>
        <h1 class="mod-title">Machine Learning con Azure</h1>
        <p class="mod-desc">Integra modelos de Machine Learning reales en Power BI usando Azure ML y AutoML. Predicciones, clasificación y regresión directamente en tus reportes.</p>
      </div>
      <h2 class="section">AutoML en Power BI Dataflows</h2>
      <p class="body">Power BI Premium permite entrenar modelos de Machine Learning directamente desde Dataflows sin escribir código. Esto es AutoML integrado, Automated Machine Learning.</p>
      <div class="steps">
        <div class="step"><div class="step-body"><div class="step-title">Crear un Dataflow</div><div class="step-text">En Power BI Service ve a Nuevo Dataflow. Conecta tu fuente de datos históricos con una columna objetivo o target.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Aplicar modelos de ML</div><div class="step-text">En el Dataflow ve a Machine Learning y selecciona Agregar modelo. Elige entre Predicción Binaria, Clasificación General o Regresión.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Configurar el entrenamiento</div><div class="step-text">Selecciona la columna objetivo, las columnas de entrada o features, y el período de entrenamiento. Power BI entrena el modelo automáticamente.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Aplicar predicciones</div><div class="step-text">Una vez entrenado, aplica el modelo a datos nuevos. Power BI agrega columnas de predicción y probabilidad directamente en el Dataflow.</div></div></div>
      </div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(6)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(8)">Siguiente: Análisis NLP <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 09 ═══ -->
    <div class="module-content" id="mod-8">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 09 · NLP & Texto</div>
        <h1 class="mod-title">Análisis de Sentimiento y NLP</h1>
        <p class="mod-desc">Transforma texto no estructurado como reseñas, encuestas y tickets de soporte en insights accionables usando IA de lenguaje natural integrada en Power BI.</p>
      </div>
      <h2 class="section">Azure Cognitive Services en Power Query</h2>
      <p class="body">Power BI tiene conectores nativos con Azure Cognitive Services para análisis de texto. Puedes procesar miles de registros de texto directamente en Power Query sin código adicional.</p>
      <div class="cards-grid">
        <div class="card" style="--card-color: #00d4aa;"><span class="card-icon">⭐</span><div class="card-title">Análisis de Reseñas</div><div class="card-text">Procesa miles de reseñas y clasifica automáticamente en Positivo, Negativo o Neutro con score de cero a uno.</div></div>
        <div class="card" style="--card-color: #f5a623;"><span class="card-icon">🎫</span><div class="card-title">Clasificación de Tickets</div><div class="card-text">Categoriza automáticamente tickets de soporte por tema. Reduce tiempo de enrutamiento.</div></div>
        <div class="card" style="--card-color: #6c63ff;"><span class="card-icon">💬</span><div class="card-title">Análisis de Encuestas</div><div class="card-text">Convierte respuestas abiertas de NPS en datos cuantitativos analizables con filtros y gráficos.</div></div>
        <div class="card" style="--card-color: #e8336d;"><span class="card-icon">📰</span><div class="card-title">Monitoreo de Marca</div><div class="card-text">Analiza el sentimiento sobre tu marca en redes sociales y noticias en tiempo real.</div></div>
      </div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(7)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(9)">Siguiente: Anomaly Detection <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 10 ═══ -->
    <div class="module-content" id="mod-9">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 10 · Detección IA</div>
        <h1 class="mod-title">Anomaly Detection</h1>
        <p class="mod-desc">Power BI detecta automáticamente anomalías en series de tiempo usando IA. Identifica picos, caídas y comportamientos inesperados sin configuración compleja.</p>
      </div>
      <h2 class="section">Detección de Anomalías Nativa</h2>
      <p class="body">En cualquier gráfico de líneas de Power BI puedes activar la detección de anomalías con un solo clic. El algoritmo usa Isolation Forest más modelos estadísticos para identificar puntos fuera de lo normal.</p>
      <div class="steps">
        <div class="step"><div class="step-body"><div class="step-title">Activar en gráfico de líneas</div><div class="step-text">Selecciona el gráfico, ve al Panel de Análisis y busca Buscar anomalías para activarlo. Los puntos anómalos aparecerán marcados automáticamente.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Ajustar sensibilidad</div><div class="step-text">Desliza el control de Sensibilidad del uno al cien. Mayor sensibilidad significa más puntos marcados. Ajusta según el nivel de ruido de tus datos.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Drill-down en anomalía</div><div class="step-text">Haz clic en un punto anómalo para ver por qué es anómalo. Power BI analiza las dimensiones relacionadas y muestra qué segmentos contribuyeron más.</div></div></div>
      </div>
      <div class="highlight"><div class="highlight-title">🎯 Casos de Uso</div><p>Finanzas para detectar transacciones fuera de patrón. Operaciones para alertar cuando una métrica de producción sale del rango esperado. E-commerce para identificar días de ventas inusualmente bajas o altas.</p></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(8)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(10)">Siguiente: Publicación <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 11 ═══ -->
    <div class="module-content" id="mod-10">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 11 · Despliegue</div>
        <h1 class="mod-title">Power BI Service & Publicación</h1>
        <p class="mod-desc">Publica tus reportes, configura actualizaciones automáticas, gestiona permisos y comparte con stakeholders de forma segura.</p>
      </div>
      <h2 class="section">Flujo de Publicación</h2>
      <div class="steps">
        <div class="step"><div class="step-body"><div class="step-title">Publicar desde Desktop</div><div class="step-text">Archivo, Publicar, selecciona workspace destino. El archivo pbix se sube al Service incluyendo modelo de datos y reportes.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Configurar credenciales</div><div class="step-text">En el Service ve a Dataset, Configuración, Credenciales del origen de datos. Ingresa las credenciales para que el Service pueda actualizar datos.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Programar actualización</div><div class="step-text">Configura la frecuencia de actualización, hasta 8 veces por día en Power BI Pro y 48 veces en Premium. Activa notificaciones de fallo.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Row Level Security</div><div class="step-text">RLS permite que distintos usuarios vean solo los datos que les corresponden. Un gerente de Lima ve solo datos de Lima, el de Arequipa solo los suyos.</div></div></div>
      </div>
      <div class="tip"><div class="tip-icon">🚀</div><div class="tip-body"><strong>DEPLOYMENT PIPELINE</strong><p>Para entornos corporativos usa Deployment Pipelines con etapas de Desarrollo, Pruebas y Producción. Permite promover cambios entre entornos manteniendo configuraciones separadas. Disponible en Power BI Premium.</p></div></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(9)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(11)">Siguiente: Proyecto Final <span class="arrow">→</span></button>
      </div>
    </div>

    <!-- ═══ MÓDULO 12 ═══ -->
    <div class="module-content" id="mod-11">
      <div class="mod-header">
        <div class="mod-eyebrow">Módulo 12 · Proyecto Integrador</div>
        <h1 class="mod-title">Proyecto Final: Dashboard Ejecutivo con IA</h1>
        <p class="mod-desc">Integra todo lo aprendido construyendo un dashboard ejecutivo real con Copilot, DAX avanzado, Machine Learning y narrativas automáticas para una empresa retail peruana.</p>
      </div>
      <div class="highlight"><div class="highlight-title">📋 Descripción del Proyecto</div><p>Empresa RetailAndina SAC, cadena de tiendas con 50 locales en Lima y provincias. El objetivo es un Dashboard ejecutivo con KPIs de ventas, predicción de demanda, análisis de sentimiento de reseñas y alertas de anomalías. Tecnologías: Power BI Desktop, Service, Copilot, Azure ML y Cognitive Services.</p></div>
      <h2 class="section">Arquitectura del Proyecto</h2>
      <div class="steps">
        <div class="step"><div class="step-body"><div class="step-title">Página 1: Executive Overview</div><div class="step-text">KPIs principales de Ventas, Margen, Unidades y NPS. Gráfico de tendencia con anomaly detection. Smart Narrative con resumen automático.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Página 2: Análisis de Ventas</div><div class="step-text">Matrix de ventas por categoría y región con formato condicional. Gráfico de cascada P&L. Ranking de tiendas. Forecast 90 días.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Página 3: Inteligencia de Clientes</div><div class="step-text">Segmentación por clustering de Machine Learning. Análisis de sentimiento de reseñas. Word cloud de temas. Key Influencers del NPS. Churn prediction score.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Página 4: Mapa Geográfico</div><div class="step-text">Mapa de calor de ventas por distrito de Lima. Burbujas por tienda con ventas y margen. Drill-through a detalle de tienda individual.</div></div></div>
        <div class="step"><div class="step-body"><div class="step-title">Página 5: Q&A y Copilot</div><div class="step-text">Visual Q&A para consultas libres. Panel Copilot activo. Botones de preguntas frecuentes para usuarios no técnicos.</div></div></div>
      </div>
      <div class="tip"><div class="tip-icon">🎓</div><div class="tip-body"><strong>¡FELICIDADES! CURSO COMPLETADO</strong><p>Has recorrido los 12 módulos del curso de Power BI más Inteligencia Artificial. La certificación recomendada es Microsoft PL-300, Power BI Data Analyst Associate, y DP-600, Fabric Analytics Engineer. Ambos exámenes usan exactamente los conceptos de este curso.</p></div></div>
      <div class="mod-nav-footer">
        <button class="nav-btn" onclick="showModule(10)"><span class="arrow">←</span> Anterior</button>
        <button class="nav-btn next" onclick="showModule(0)">Volver al inicio <span class="arrow">↑</span></button>
      </div>
    </div>

  </main>
</div>

<!-- ─── VOICE BAR ─── -->
<div class="voice-bar" id="voiceBar">
  <span class="voice-icon" id="voiceIcon">🎙️</span>
  <span class="voice-label" id="voiceLabel">Listo</span>
  <span class="voice-text-preview" id="voicePreview">Selecciona un módulo para escuchar la lectura automática...</span>
  <div class="voice-controls">
    <div class="voice-speed">
      <span>Vel:</span>
      <input type="range" id="speedRange" min="0.6" max="1.8" step="0.1" value="1.0" oninput="updateSpeed(this.value)">
      <span id="speedVal">1.0x</span>
    </div>
    <button class="voice-btn" id="playBtn" onclick="togglePlay()">▶ Leer</button>
    <button class="voice-btn stop-btn" onclick="stopVoice()">■ Stop</button>
    <button class="voice-toggle" id="voiceToggle" onclick="toggleVoiceEnabled()" title="Activar/desactivar voz automática">🔊</button>
  </div>
</div>

<script>
  // ─── MODULE NAVIGATION ───
  const modules = document.querySelectorAll('.module-content');
  const buttons = document.querySelectorAll('.module-btn');

  function showModule(index) {
    modules.forEach(m => m.classList.remove('active'));
    buttons.forEach(b => b.classList.remove('active'));
    modules[index].classList.add('active');
    buttons[index].classList.add('active');
    window.scrollTo({ top: document.querySelector('.layout').offsetTop, behavior: 'smooth' });
    if (voiceEnabled) {
      setTimeout(() => readCurrentModule(), 600);
    }
  }

  // ─── VOICE ENGINE ───
  let synth = window.speechSynthesis;
  let currentUtterance = null;
  let voiceEnabled = true;
  let selectedVoice = null;
  let speechRate = 1.0;
  let isPlaying = false;

  function getSpanishVoice() {
    const voices = synth.getVoices();
    // Priority: es-PE > es-419 > es-ES > any Spanish
    const priorities = ['es-PE','es-419','es-MX','es-US','es-AR','es-ES','es'];
    for (const lang of priorities) {
      const v = voices.find(v => v.lang.startsWith(lang));
      if (v) return v;
    }
    return voices.find(v => v.lang.startsWith('es')) || voices[0];
  }

  function getModuleText(index) {
    const mod = document.getElementById('mod-' + index);
    if (!mod) return '';
    // Extract clean text: title + description + all readable text (skip code blocks)
    let text = '';
    const eyebrow = mod.querySelector('.mod-eyebrow');
    const title   = mod.querySelector('.mod-title');
    const desc    = mod.querySelector('.mod-desc');
    if (eyebrow) text += eyebrow.textContent + '. ';
    if (title)   text += title.textContent + '. ';
    if (desc)    text += desc.textContent + '. ';

    // Walk paragraphs and headings, skip code blocks
    const walker = document.createTreeWalker(mod, NodeFilter.SHOW_TEXT, {
      acceptNode(node) {
        const p = node.parentElement;
        // Skip code blocks, already read header
        if (p.closest('pre, .code-block, .mod-header, .mod-eyebrow, .mod-title, .mod-desc')) return NodeFilter.FILTER_REJECT;
        if (p.closest('.mod-nav-footer')) return NodeFilter.FILTER_REJECT;
        const txt = node.textContent.trim();
        if (!txt || txt.length < 3) return NodeFilter.FILTER_REJECT;
        return NodeFilter.FILTER_ACCEPT;
      }
    });

    const parts = [];
    let node;
    while ((node = walker.nextNode())) {
      const t = node.textContent.trim();
      if (t) parts.push(t);
    }
    text += parts.join(' ');
    // Clean up excessive whitespace
    return text.replace(/\s+/g, ' ').trim();
  }

  function getActiveModuleIndex() {
    for (let i = 0; i < modules.length; i++) {
      if (modules[i].classList.contains('active')) return i;
    }
    return 0;
  }

  function readCurrentModule() {
    stopVoice();
    const idx  = getActiveModuleIndex();
    const text = getModuleText(idx);
    if (!text) return;
    speakText(text);
  }

  function speakText(text) {
    if (!synth) return;
    stopVoice();

    currentUtterance = new SpeechSynthesisUtterance(text);
    currentUtterance.lang  = 'es-PE';
    currentUtterance.rate  = speechRate;
    currentUtterance.pitch = 1.05;
    currentUtterance.volume = 1;

    if (!selectedVoice) selectedVoice = getSpanishVoice();
    if (selectedVoice) currentUtterance.voice = selectedVoice;

    currentUtterance.onstart = () => {
      isPlaying = true;
      document.getElementById('voiceIcon').classList.add('speaking');
      document.getElementById('voiceLabel').textContent = 'Leyendo...';
      document.getElementById('voicePreview').textContent = text.substring(0, 80) + '...';
      document.getElementById('playBtn').textContent = '⏸ Pausar';
      document.getElementById('playBtn').classList.add('active');
    };

    currentUtterance.onend = currentUtterance.onerror = () => {
      isPlaying = false;
      document.getElementById('voiceIcon').classList.remove('speaking');
      document.getElementById('voiceLabel').textContent = 'Listo';
      document.getElementById('playBtn').textContent = '▶ Leer';
      document.getElementById('playBtn').classList.remove('active');
    };

    synth.speak(currentUtterance);
  }

  function stopVoice() {
    synth.cancel();
    isPlaying = false;
    if (currentUtterance) currentUtterance = null;
    document.getElementById('voiceIcon').classList.remove('speaking');
    document.getElementById('voiceLabel').textContent = 'Listo';
    document.getElementById('playBtn').textContent = '▶ Leer';
    document.getElementById('playBtn').classList.remove('active');
  }

  function togglePlay() {
    if (synth.speaking && !synth.paused) {
      synth.pause();
      isPlaying = false;
      document.getElementById('voiceIcon').classList.remove('speaking');
      document.getElementById('voiceLabel').textContent = 'Pausado';
      document.getElementById('playBtn').textContent = '▶ Continuar';
    } else if (synth.paused) {
      synth.resume();
      isPlaying = true;
      document.getElementById('voiceIcon').classList.add('speaking');
      document.getElementById('voiceLabel').textContent = 'Leyendo...';
      document.getElementById('playBtn').textContent = '⏸ Pausar';
    } else {
      readCurrentModule();
    }
  }

  function updateSpeed(val) {
    speechRate = parseFloat(val);
    document.getElementById('speedVal').textContent = speechRate.toFixed(1) + 'x';
    if (synth.speaking) {
      readCurrentModule(); // restart with new speed
    }
  }

  function toggleVoiceEnabled() {
    voiceEnabled = !voiceEnabled;
    const btn = document.getElementById('voiceToggle');
    btn.textContent = voiceEnabled ? '🔊' : '🔇';
    btn.title = voiceEnabled ? 'Desactivar voz automática' : 'Activar voz automática';
    if (!voiceEnabled) stopVoice();
  }

  // Load voices (Chrome needs this event)
  if (synth.onvoiceschanged !== undefined) {
    synth.onvoiceschanged = () => { selectedVoice = getSpanishVoice(); };
  }

  // Auto-read first module on load
  window.addEventListener('load', () => {
    setTimeout(() => {
      selectedVoice = getSpanishVoice();
      if (voiceEnabled) readCurrentModule();
    }, 1500);
  });
</script>
</body>
</html>
