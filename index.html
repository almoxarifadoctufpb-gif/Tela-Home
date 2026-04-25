<!DOCTYPE html>
<html lang="pt-BR" data-theme="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>VULPS+ · Painel de Desempenho</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    /* ========== VARIÁVEIS E ESTILOS BASE (IDÊNTICO AO VULPS+) ========== */
    *,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
    :root{
      --accent-primary:#00D9E8;--accent-strong:#007F8C;
      --accent-soft:rgba(0,217,232,0.12);--accent-glow:rgba(0,217,232,0.25);
      --accent-glass:rgba(0,217,232,0.08);--bg-primary:#0D141C;--bg-secondary:#0F1720;
      --bg-card:#121C26;--bg-sidebar:#0A1118;--text-primary:#F0F8FF;
      --text-secondary:#B0E5EB;--text-muted:#7FB8C0;--border-light:#1F2E3A;
      --border-hover:#00D9E8;--success:#22C55E;--danger:#EF4444;--warning:#F59E0B;
      --radius-sm:14px;--radius-lg:28px;--card-shadow:0 8px 32px rgba(0,0,0,0.4);
      --card-shadow-hover:0 16px 40px rgba(0,217,232,0.12);
      --card-shadow-light:0 4px 16px rgba(0,0,0,0.2);
      --sidebar-width:260px;
      --btn-bg:#1a2230;--btn-text:#fff;--btn-border:var(--border-light);
    }
    html[data-theme="light"]{
      --accent-primary:#008B9A;--accent-strong:#00626B;
      --accent-soft:rgba(0,139,154,0.1);--accent-glow:rgba(0,139,154,0.2);
      --bg-primary:#F5FAFC;--bg-secondary:#E8F4F8;--bg-card:#FFFFFF;
      --bg-sidebar:#EDF5F8;--text-primary:#0A1A1F;--text-secondary:#1A3D47;
      --text-muted:#4A7B85;--border-light:#D0E4EC;
      --card-shadow:0 8px 32px rgba(0,0,0,0.06);
      --card-shadow-hover:0 16px 40px rgba(0,139,154,0.12);
      --card-shadow-light:0 4px 16px rgba(0,0,0,0.04);
      --btn-bg:#ffffff;--btn-text:#0A1A1F;--btn-border:#D0E4EC;
    }
    html[data-theme="tema-1"]{
      --accent-primary:#F59E0B;--accent-strong:#B45309;
      --accent-soft:rgba(245,158,11,0.12);--accent-glow:rgba(245,158,11,0.3);
      --bg-primary:#1C140D;--bg-secondary:#241A0F;--bg-card:#2A1F12;
      --bg-sidebar:#160F09;--text-primary:#FDF8F0;--text-secondary:#E8D5B7;
      --text-muted:#C4A97A;--border-light:#3B2E1A;
      --card-shadow:0 8px 32px rgba(0,0,0,0.5);
      --card-shadow-hover:0 16px 40px rgba(245,158,11,0.15);
      --card-shadow-light:0 4px 16px rgba(0,0,0,0.25);
      --btn-bg:#2A1F12;--btn-text:#FDF8F0;--btn-border:#3B2E1A;
    }
    html[data-theme="tema-2"]{
      --accent-primary:#8B5CF6;--accent-strong:#6D28D9;
      --accent-soft:rgba(139,92,246,0.12);--accent-glow:rgba(139,92,246,0.25);
      --bg-primary:#13111C;--bg-secondary:#181623;--bg-card:#1E1B2A;
      --bg-sidebar:#0E0C16;--text-primary:#F2F0FF;--text-secondary:#C7C0EA;
      --text-muted:#9F94C8;--border-light:#2E2840;
      --card-shadow:0 8px 32px rgba(0,0,0,0.5);
      --card-shadow-hover:0 16px 40px rgba(139,92,246,0.15);
      --card-shadow-light:0 4px 16px rgba(0,0,0,0.25);
      --btn-bg:#1E1B2A;--btn-text:#F2F0FF;--btn-border:#2E2840;
    }
    html[data-theme="minimal"]{
      --accent-primary:#4a6cf7;--accent-strong:#3b5de7;
      --accent-soft:rgba(74,108,247,0.08);--accent-glow:transparent;
      --accent-glass:transparent;--bg-primary:#f7f7f7;--bg-secondary:#ffffff;
      --bg-card:#ffffff;--bg-sidebar:#ffffff;--text-primary:#222222;
      --text-secondary:#555555;--text-muted:#888888;--border-light:#e5e5e5;
      --border-hover:#dcdcdc;--card-shadow:none;--card-shadow-hover:none;--card-shadow-light:none;
      --btn-bg:#ffffff;--btn-text:#222222;--btn-border:#e5e5e5;
    }
    body{
      font-family:'Segoe UI','Inter',system-ui,-apple-system,sans-serif;
      background:var(--bg-primary);color:var(--text-primary);line-height:1.6;
      transition:background-color 0.3s,color 0.3s;-webkit-font-smoothing:antialiased;
      overflow-x:hidden;display:flex;min-height:100vh;
    }
    #hamburgerBtn{
      display:flex;align-items:center;justify-content:center;position:fixed;top:12px;left:12px;
      z-index:110;width:48px;height:48px;border-radius:50%;background:var(--bg-card);
      border:1.5px solid var(--border-light);color:var(--text-primary);font-size:1.4rem;
      cursor:pointer;box-shadow:var(--card-shadow-light);transition:all 0.3s;
      -webkit-tap-highlight-color:transparent;
    }
    #hamburgerBtn:hover{border-color:var(--accent-primary);box-shadow:var(--card-shadow-hover)}
    #sidebar{
      position:fixed;left:0;top:0;height:100vh;width:var(--sidebar-width);
      background:var(--bg-sidebar);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);
      border-right:1px solid var(--border-light);padding:24px 16px;display:flex;
      flex-direction:column;gap:6px;z-index:100;overflow-y:auto;
      transition:transform 0.35s cubic-bezier(0.4,0,0.2,1);
      box-shadow:1px 0 20px rgba(0,0,0,0.1);transform:translateX(-100%);
    }
    #sidebar.open{transform:translateX(0)}
    #sidebar .sidebar-header{padding:0 8px 24px 8px;border-bottom:1px solid var(--border-light);margin-bottom:12px;display:flex;align-items:center;justify-content:space-between}
    #sidebar .sidebar-header h2{font-size:1.6rem;font-weight:700;background:linear-gradient(135deg,var(--text-primary) 0%,var(--accent-primary) 80%);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin:0;letter-spacing:1px}
    #closeSidebarBtn{display:none;align-items:center;justify-content:center;width:36px;height:36px;border-radius:50%;background:transparent;border:1px solid var(--border-light);color:var(--text-muted);cursor:pointer;font-size:1.2rem;transition:all 0.2s;-webkit-tap-highlight-color:transparent}
    #closeSidebarBtn:hover{color:var(--danger);border-color:var(--danger)}
    .sidebar-btn{
      display:flex;align-items:center;gap:14px;padding:14px 18px;border-radius:40px;
      background:transparent;border:1.5px solid transparent;color:var(--text-primary);
      font-weight:500;font-size:0.95rem;cursor:pointer;transition:all 0.25s;width:100%;
      text-align:left;position:relative;overflow:hidden;min-height:48px;
      -webkit-tap-highlight-color:transparent;
    }
    .sidebar-btn i{width:22px;font-size:1.2rem;color:var(--accent-primary);text-align:center}
    .sidebar-btn:hover{
      background:var(--accent-soft);border-color:var(--accent-primary);
      transform:translateX(6px);box-shadow:0 4px 15px rgba(0,217,232,0.1);
    }
    .external-links{display:flex;gap:12px;margin-top:16px;flex-wrap:wrap}
    .btn-external{padding:10px 14px;border-radius:10px;background:var(--accent-primary);color:#fff;text-decoration:none;font-size:0.9rem;font-weight:600;transition:0.2s;display:inline-flex;align-items:center;justify-content:center;gap:6px;min-height:44px}
    .pix-card{display:flex;flex-direction:column;gap:12px;padding:16px 18px;border-radius:16px;background:var(--bg-card);border:1px solid var(--border-light);box-shadow:var(--card-shadow);margin-top:16px}
    .pix-icon{width:36px;height:36px;border-radius:10px;display:flex;align-items:center;justify-content:center;background:var(--accent-soft);flex-shrink:0;margin-bottom:4px}
    .pix-svg{width:20px;height:20px;fill:var(--accent-primary)}
    .pix-text{color:var(--text-primary);font-size:0.89rem;line-height:1.5}
    .pix-copy-btn{align-self:stretch;border:none;cursor:pointer;padding:10px 12px;border-radius:10px;background:var(--accent-primary);color:#fff;font-weight:600;font-size:0.85rem;transition:0.2s;min-height:44px}
    #sidebarOverlay{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,0.6);backdrop-filter:blur(4px);z-index:99;opacity:0;pointer-events:none;transition:opacity 0.35s}
    #sidebarOverlay.active{opacity:1;pointer-events:auto}
    .app-container{flex:1;max-width:960px;margin:0 auto;padding:24px 16px 32px;display:flex;flex-direction:column;gap:24px;width:100%}
    .app-header{display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;padding:8px 0 16px;border-bottom:2px solid var(--accent-primary);gap:12px}
    .header-brand{display:flex;align-items:center;gap:12px;flex:1;min-width:0}
    .app-logo{height:clamp(36px,5vw,48px);width:auto;object-fit:contain;border-radius:12px;transition:transform 0.3s;filter:drop-shadow(0 4px 8px rgba(0,217,232,0.3))}
    .brand-text h1{font-weight:700;font-size:clamp(1.3rem,2.5vw,2rem);letter-spacing:-0.02em;background:linear-gradient(135deg,var(--text-primary) 0%,var(--accent-primary) 80%);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;line-height:1.2}
    .brand-text p{color:var(--text-secondary);font-size:clamp(0.75rem,1.2vw,0.9rem);font-weight:500;opacity:0.8}
    .header-actions{display:flex;gap:8px;flex-shrink:0}
    .btn{
      padding:0.6rem 1.4rem;border-radius:40px;font-weight:600;cursor:pointer;
      transition:all 0.25s;display:inline-flex;align-items:center;gap:0.4rem;
      font-size:0.95rem;min-height:44px;border:1px solid var(--btn-border);
      background:var(--btn-bg);color:var(--btn-text);
    }
    .btn-primary{background:linear-gradient(135deg,var(--accent-primary),var(--accent-strong));border:none;color:#fff;}
    .btn-outline{background:transparent;border:1.5px solid var(--border-light);color:var(--text-primary);}
    .card{background:var(--bg-card);border-radius:var(--radius-lg);padding:24px 22px;box-shadow:var(--card-shadow);border:1px solid var(--border-light);transition:all 0.3s;margin-bottom:24px}
    .card:hover{box-shadow:var(--card-shadow-hover);border-color:var(--border-hover)}
    .painel-controle{display:flex;flex-wrap:wrap;gap:1.5rem;align-items:flex-end}
    .controle-grupo{display:flex;flex-direction:column;gap:0.4rem;flex:1;min-width:200px}
    .controle-grupo label{font-weight:600;font-size:0.9rem;color:var(--text-secondary)}
    select,input[type="text"],input[type="number"]{padding:0.7rem 1rem;border:1.5px solid var(--border-light);border-radius:var(--radius-sm);font-size:0.95rem;background:var(--bg-secondary);color:var(--text-primary);transition:all 0.2s;box-shadow:inset 0 2px 6px rgba(0,0,0,0.1);appearance:none;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='%237FB8C0' stroke-width='2'%3E%3Cpolyline points='6 9 12 15 18 9'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:right 14px center;background-size:16px;padding-right:40px;cursor:pointer}
    select:focus,input:focus{outline:none;border-color:var(--accent-primary);box-shadow:0 0 0 4px var(--accent-soft)}
    .timer-display{font-size:3.8rem;font-weight:700;font-variant-numeric:tabular-nums;letter-spacing:1px;background:var(--bg-secondary);padding:0.5rem 1.5rem;border-radius:var(--radius-sm);display:inline-block;min-width:200px;text-align:center;border:1px solid var(--border-light);box-shadow:inset 0 2px 6px rgba(0,0,0,0.1);line-height:1.2}
    .timer-type-selector{display:flex;gap:4px;background:var(--bg-secondary);border-radius:40px;padding:3px}
    .timer-type-btn{padding:5px 12px;border-radius:40px;border:none;background:transparent;color:var(--text-muted);font-weight:600;font-size:0.8rem;cursor:pointer;transition:all 0.2s}
    .timer-type-btn.active{background:var(--accent-primary);color:#fff}
    table{width:100%;border-collapse:collapse;background:var(--bg-card);border-radius:var(--radius-lg);overflow:hidden;box-shadow:var(--card-shadow);border:1px solid var(--border-light)}
    th{background:var(--bg-secondary);text-align:left;padding:0.9rem 1rem;font-weight:600;color:var(--text-primary)}
    td{padding:0.8rem 1rem;border-top:1px solid var(--border-light)}
    tbody tr:nth-child(even){background:var(--bg-secondary);}
    .badge{display:inline-block;padding:0.25rem 0.8rem;border-radius:99px;font-size:0.8rem;font-weight:600}
    .badge-low{background:rgba(239,68,68,0.2);color:var(--danger)}
    .badge-mid{background:rgba(245,158,11,0.2);color:var(--warning)}
    .badge-high{background:rgba(34,197,94,0.2);color:var(--success)}
    .btn-excluir{background:none;border:none;cursor:pointer;font-size:1.2rem;padding:0.3rem 0.6rem;border-radius:0.5rem;color:var(--text-muted);transition:all 0.2s}
    .btn-excluir:hover{background:rgba(239,68,68,0.15);color:var(--danger)}
    .adicionar-area{display:flex;gap:1rem;align-items:flex-end;margin-top:1.5rem;flex-wrap:wrap}
    /* ========== MODO FOCO IMERSIVO ========== */
    .focus-overlay {
      position: fixed; top: 0; left: 0; width: 100vw; height: 100vh;
      background: rgba(0,0,0,0.85); backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px); z-index: 9999;
      display: flex; flex-direction: column; align-items: center; justify-content: center;
      opacity: 0; pointer-events: none; transition: opacity 0.5s cubic-bezier(0.4,0,0.2,1);
    }
    .focus-overlay.active { opacity: 1; pointer-events: auto; }
    .focus-container { text-align: center; }
    .focus-logo {
      display: block; margin: 0 auto 20px; width: 120px; height: auto;
      opacity: 0.8; filter: drop-shadow(0 0 20px var(--accent-primary));
    }
    .focus-ring-container {
      position: relative; width: 240px; height: 240px; margin: 0 auto 20px;
    }
    canvas#focusRingCanvas {
      position: absolute; top: 0; left: 0; width: 100%; height: 100%;
    }
    .focus-timer {
      position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);
      font-size: clamp(3rem, 8vw, 5rem); font-weight: 800;
      font-variant-numeric: tabular-nums; letter-spacing: 4px;
      color: var(--text-primary); text-shadow: 0 0 30px var(--accent-primary);
      z-index: 3; white-space: nowrap;
    }
    .focus-session-label {
      font-size: 1.2rem; color: var(--accent-primary); margin-top: 10px;
      display: flex; align-items: center; justify-content: center; gap: 10px;
    }
    .focus-controls { display: flex; gap: 20px; margin-top: 30px; }
    .focus-btn {
      width: 60px; height: 60px; border-radius: 50%; border: 2px solid var(--border-light);
      background: rgba(255,255,255,0.05); color: #fff; font-size: 1.5rem;
      cursor: pointer; transition: all 0.3s; display: flex; align-items: center; justify-content: center;
    }
    .focus-btn:hover { background: var(--accent-soft); border-color: var(--accent-primary); box-shadow: 0 0 30px var(--accent-glow); }
    .focus-exit { position: absolute; top: 30px; right: 30px; background: none; border: none; color: var(--text-muted); font-size: 1.5rem; cursor: pointer; transition: color 0.2s; z-index: 2; }
    .focus-exit:hover { color: var(--danger); }
    /* ========== MANIFESTO E BANNER ========== */
    #vulps-manifesto-overlay{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,0.7);backdrop-filter:blur(6px);z-index:1200;display:flex;align-items:center;justify-content:center;padding:16px;opacity:0;visibility:hidden;transition:opacity 0.35s,visibility 0.35s}
    #vulps-manifesto-overlay.vulps-manifesto-open{opacity:1;visibility:visible}
    .vulps-donation-banner{position:fixed;bottom:24px;right:24px;z-index:90;max-width:300px;background:var(--bg-card);border:1px solid var(--border-light);border-radius:16px;padding:16px;box-shadow:0 8px 32px rgba(0,0,0,0.5);color:var(--text-primary)}
    /* ========== RESPONSIVIDADE ========== */
    @media (max-width: 47.99em) { #closeSidebarBtn{display:flex} }
    @media (min-width: 48em) {
      #hamburgerBtn{display:none} #sidebar{transform:translateX(0);position:fixed;z-index:50} #sidebarOverlay{display:none}
      body{padding-left:var(--sidebar-width)} .app-container{padding:28px 20px 32px}
    }
    @media (min-width: 64em) { .app-container{max-width:960px;padding:32px 24px;margin:0 auto} }
  </style>
</head>
<body>
  <button id="hamburgerBtn"><i class="fas fa-bars"></i></button>
  <div id="sidebarOverlay"></div>
  <div id="sidebar">
    <div class="sidebar-header"><h2>VULPS+</h2><button id="closeSidebarBtn"><i class="fas fa-times"></i></button></div>
    <button class="sidebar-btn" onclick="navigateTo('#')"><i class="fas fa-calendar-alt"></i>Planejamento</button>
    <button class="sidebar-btn" onclick="navigateTo('#')"><i class="fas fa-file-pdf"></i>Leitor de PDF</button>
    <button class="sidebar-btn" onclick="navigateTo('#')"><i class="fas fa-brain"></i>Ank - Memory</button>
    <button class="sidebar-btn" onclick="navigateTo('#')"><i class="fas fa-users"></i>Mentoria</button>
    <button class="sidebar-btn" onclick="navigateTo('#')"><i class="fas fa-book"></i>Clube do PDF</button>
    <div class="external-links">
      <a href="#" class="btn-external"><i class="fas fa-balance-scale"></i> Controle das Leis</a>
      <a href="#" class="btn-external"><i class="fas fa-calendar-check"></i> Planejador</a>
    </div>
    <div class="pix-card">
      <div class="pix-icon"><svg viewBox="0 0 24 24" class="pix-svg"><path d="M12 2l3 3-3 3-3-3 3-3zm7 7l3 3-3 3-3-3 3-3zM5 9l3 3-3 3-3-3 3-3zm7 7l3 3-3 3-3-3 3-3z"/></svg></div>
      <p class="pix-text">Gostou? Apoie com um PIX de qualquer valor e ajude a manter o projeto no ar.</p>
      <button class="pix-copy-btn">Copiar chave PIX</button>
    </div>
  </div>

  <div class="app-container" id="mainContent">
    <div class="app-header">
      <div class="header-brand">
        <img src="https://i.ibb.co/LzCwL9bX/ChatGPT_Image.png" alt="VULPS+" class="app-logo">
        <div class="brand-text"><h1>VULPS+</h1><p>Painel de Desempenho</p></div>
      </div>
      <div class="header-actions">
        <button id="focusModeToggle" class="btn btn-outline"><i class="fas fa-expand"></i> Foco</button>
        <button id="theme-toggle" class="btn btn-outline"><i class="fas fa-moon"></i> <span>Escuro</span></button>
        <button id="quemSomosBtn" class="btn btn-outline"><i class="fas fa-users"></i> Quem Somos</button>
      </div>
    </div>

    <div class="card" style="text-align:center;" id="timerCard">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px;flex-wrap:wrap;gap:12px;">
        <div class="controle-grupo" style="text-align:left;">
          <label>Disciplina</label>
          <select id="disciplinaSelect"><option value="">-- Selecione --</option></select>
        </div>
        <div class="timer-type-selector">
          <button class="timer-type-btn active" data-type="Teoria"><i class="fas fa-book-open"></i> Teoria</button>
          <button class="timer-type-btn" data-type="Questões"><i class="fas fa-question-circle"></i> Questões</button>
          <button class="timer-type-btn" data-type="Revisão"><i class="fas fa-sync-alt"></i> Revisão</button>
          <button class="timer-type-btn" data-type="Pausa"><i class="fas fa-coffee"></i> Pausa</button>
        </div>
      </div>
      <div class="timer-display" id="timerDisplay">00:00:00</div>
      <div style="margin:12px 0;color:var(--accent-primary);font-weight:600;" id="pomodoroIndicator">
        <i class="fas fa-clock"></i> Sessão: <span id="sessionTypeLabel">Teoria</span>
      </div>
      <div style="display:flex;justify-content:center;gap:12px;">
        <button id="timerStart" class="btn btn-primary"><i class="fas fa-play"></i> Iniciar</button>
        <button id="timerPause" class="btn btn-outline"><i class="fas fa-pause"></i> Pausar</button>
        <button id="timerReset" class="btn btn-outline"><i class="fas fa-redo"></i> Zerar</button>
      </div>
    </div>

    <div style="margin-bottom:1rem;"><input type="text" id="filtroTabela" placeholder="Filtrar disciplinas..." style="padding:0.7rem 1.2rem;border-radius:2rem;border:1px solid var(--border-light);background:var(--bg-secondary);color:var(--text-primary);width:100%;max-width:300px;"></div>
    <table id="tabelaDisciplinas">
      <thead><tr><th>Disciplina</th><th>Certas</th><th>Erradas</th><th>Total</th><th>% Acerto</th><th>Status</th><th>Horas</th><th></th></tr></thead>
      <tbody></tbody>
    </table>
    <div class="adicionar-area">
      <select id="novaDisciplinaSelect" style="min-width:280px;"><option value="">-- Adicionar nova disciplina --</option></select>
      <button id="addDisciplinaBtn" class="btn btn-primary"><i class="fas fa-plus"></i> Adicionar</button>
      <span id="msgAdicionar" style="color:var(--accent-primary);margin-left:0.5rem;"></span>
    </div>
  </div>

  <!-- MODO FOCO IMERSIVO -->
  <div class="focus-overlay" id="focusOverlay">
    <button class="focus-exit" id="exitFocusBtn"><i class="fas fa-times"></i></button>
    <div class="focus-container">
      <img src="https://i.ibb.co/LzCwL9bX/ChatGPT_Image.png" alt="VULPS+" class="focus-logo">
      <div class="focus-ring-container">
        <canvas id="focusRingCanvas" width="240" height="240"></canvas>
        <div class="focus-timer" id="focusTimerDisplay">00:00:00</div>
      </div>
      <div class="focus-session-label">
        <i class="fas fa-clock"></i> <span id="focusSessionLabel">Teoria</span> · Ciclo <span id="focusCycleCount">1</span>
      </div>
      <div class="focus-controls">
        <button class="focus-btn" id="focusTimerStart"><i class="fas fa-play"></i></button>
        <button class="focus-btn" id="focusTimerPause"><i class="fas fa-pause"></i></button>
      </div>
    </div>
  </div>

  <div id="vulps-manifesto-overlay"><div class="manifesto-card" style="background:var(--bg-card);max-width:500px;width:100%;border-radius:24px;padding:32px;border:2px solid var(--accent-primary);box-shadow:0 24px 48px rgba(0,0,0,0.6);position:relative;"><button class="manifesto-close" id="closeManifestoBtn"><i class="fas fa-times"></i></button><h2 style="margin-bottom:16px;">Manifesto VULP+</h2><p>Acreditamos no estudo colaborativo, acessível e de qualidade.</p></div></div>
  <div class="vulps-donation-banner" id="donationBanner"><p style="margin-bottom:8px;">Apoie o projeto</p><button class="pix-copy-btn">Copiar PIX</button></div>

  <script>
    const disciplinasPredefinidas = ["Língua Portuguesa","Matemática Básica","Raciocínio Lógico-Matemático","Noções de Informática","Atualidades","Redação Oficial","Língua Inglesa","Língua Espanhola","Matemática Financeira","Estatística","Geografia do Brasil","História do Brasil","Noções de Administração Pública","Noções de Arquivologia","Noções de Gestão de Pessoas","Noções de Administração Financeira e Orçamentária (AFO)","Noções de Contabilidade Pública","Noções de Direito Constitucional","Noções de Direito Administrativo","Direito Constitucional","Direito Administrativo","Direito Penal","Direito Processual Penal","Direito Civil","Direito Processual Civil","Direito Tributário","Direito do Trabalho","Direito Processual do Trabalho","Direito Empresarial (Comercial)","Direito do Consumidor","Direito Ambiental","Direito da Criança e do Adolescente (ECA)","Direito Internacional Público","Direito Internacional Privado","Direito Previdenciário","Direito Eleitoral","Direito Financeiro","Direito Urbanístico","Direito Marítimo","Direito Digital","Direito Agrário","Legislação Especial","Ética Profissional e Estatuto da OAB","Administração Geral","Administração Pública","Gestão de Pessoas","Administração de Materiais","Administração Financeira e Orçamentária","Contabilidade Geral","Contabilidade de Custos","Contabilidade Pública","Análise de Demonstrações Contábeis","Auditoria","Economia","Microeconomia","Macroeconomia","Economia Brasileira","Economia Internacional","Finanças Públicas","Marketing","Logística","Planejamento Estratégico","Informática (Conceitos Básicos)","Segurança da Informação","Banco de Dados","Desenvolvimento de Software","Engenharia de Software","Governança de TI","Gestão de Projetos (PMBOK)","Ciência de Dados","Inteligência Artificial","Redes de Computadores","Arquitetura de Computadores","Sistemas Operacionais","Biologia","Física","Química","Ciências da Natureza","Engenharia Civil","Engenharia Elétrica","Engenharia Mecânica","Saúde Pública","Enfermagem","Farmácia","Odontologia","Psicologia","Serviço Social","Medicina","Fisioterapia","Nutrição","Educação Física","Arquitetura","Biblioteconomia","Museologia","Comunicação Social","Jornalismo","Relações Internacionais","Estatística Aplicada","Matemática Financeira Avançada","Raciocínio Lógico Avançado"];
    let data = JSON.parse(localStorage.getItem('vulps_discipline_data')) || {};
    if (Object.keys(data).length === 0) {
      disciplinasPredefinidas.slice(0, 10).forEach(d => data[d] = { certas: 0, erradas: 0, horasMinutos: 0 });
      salvarDados();
    }
    function salvarDados() { localStorage.setItem('vulps_discipline_data', JSON.stringify(data)); }

    const selectDisciplina = document.getElementById('disciplinaSelect');
    const timerDisplay = document.getElementById('timerDisplay');
    const focusTimerDisplay = document.getElementById('focusTimerDisplay');
    const filtroInput = document.getElementById('filtroTabela');
    const tbody = document.querySelector('#tabelaDisciplinas tbody');
    const novaSelect = document.getElementById('novaDisciplinaSelect');
    const addBtn = document.getElementById('addDisciplinaBtn');
    const msgAdicionar = document.getElementById('msgAdicionar');
    const focusOverlay = document.getElementById('focusOverlay');
    const focusCycleCount = document.getElementById('focusCycleCount');
    const focusRingCanvas = document.getElementById('focusRingCanvas');
    let timerInterval = null, segundos = 0, pomodoroActive = true, pomodoroCount = 1, focusModeActive = false;
    let ciclo30min = 0;

    function atualizarSelects() {
      const nomes = Object.keys(data).sort();
      selectDisciplina.innerHTML = '<option value="">-- Selecione --</option>' + nomes.map(d => `<option value="${d}">${d}</option>`).join('');
      const disponiveis = disciplinasPredefinidas.filter(d => !(d in data));
      novaSelect.innerHTML = '<option value="">-- Adicionar nova disciplina --</option>' + disponiveis.map(d => `<option value="${d}">${d}</option>`).join('');
    }
    function getDisciplina(nome) { return data[nome] || { certas:0, erradas:0, horasMinutos:0 }; }
    function calcularPercentual(nome) { const d = getDisciplina(nome); const t = d.certas + d.erradas; return t ? (d.certas/t)*100 : 0; }
    function getStatus(p) { if(p>=81) return 'Avançado'; if(p>=61) return 'Intermediário'; return 'Base em construção'; }
    function excluirDisciplina(nome) {
      if(!confirm(`Excluir "${nome}"?`)) return;
      delete data[nome]; salvarDados(); atualizarSelects(); renderizarTabela();
      if(selectDisciplina.value === nome) selectDisciplina.value = '';
    }
    window.excluirDisciplina = excluirDisciplina;

    function renderizarTabela(filtro='') {
      const disciplinas = Object.keys(data).sort();
      const filtradas = disciplinas.filter(d => d.toLowerCase().includes(filtro.toLowerCase()));
      tbody.innerHTML = filtradas.map(nome => {
        const d = getDisciplina(nome); const total = d.certas + d.erradas;
        const perc = total ? ((d.certas/total)*100).toFixed(1) : 0;
        const status = getStatus(perc); const horas = ((d.horasMinutos||0)/60).toFixed(1);
        const badgeClass = status === 'Avançado' ? 'badge-high' : (status === 'Intermediário' ? 'badge-mid' : 'badge-low');
        return `<tr><td>${nome}</td><td>${d.certas}</td><td>${d.erradas}</td><td>${total}</td><td>${perc}%</td><td><span class="badge ${badgeClass}">${status}</span></td><td>${horas}h</td><td><button class="btn-excluir" onclick="excluirDisciplina('${nome}')"><i class="fas fa-trash-alt"></i></button></td></tr>`;
      }).join('');
    }

    function atualizarTimer() {
      const h=Math.floor(segundos/3600), m=Math.floor((segundos%3600)/60), s=segundos%60;
      const txt = `${String(h).padStart(2,'0')}:${String(m).padStart(2,'0')}:${String(s).padStart(2,'0')}`;
      timerDisplay.textContent = txt;
      focusTimerDisplay.textContent = txt;
    }

    function drawFocusRing() {
      if (!focusRingCanvas || !focusModeActive) return;
      const ctx = focusRingCanvas.getContext('2d');
      const w = focusRingCanvas.width, h = focusRingCanvas.height, cx = w/2, cy = h/2, r = 100;
      const progress = ciclo30min / 1800;
      ctx.clearRect(0, 0, w, h);
      ctx.beginPath(); ctx.arc(cx, cy, r, 0, 2*Math.PI); ctx.strokeStyle = 'rgba(255,255,255,0.1)'; ctx.lineWidth = 12; ctx.stroke();
      const accent = getComputedStyle(document.documentElement).getPropertyValue('--accent-primary').trim() || '#00D9E8';
      const grad = ctx.createLinearGradient(0, 0, w, h); grad.addColorStop(0, accent); grad.addColorStop(1, '#ffffff');
      ctx.beginPath(); ctx.arc(cx, cy, r, -Math.PI/2, -Math.PI/2 + (2*Math.PI*progress)); ctx.strokeStyle = grad; ctx.lineWidth = 12; ctx.lineCap = 'round'; ctx.stroke();
      const angle = -Math.PI/2 + (2*Math.PI*progress);
      ctx.beginPath(); ctx.arc(cx + r*Math.cos(angle), cy + r*Math.sin(angle), 6, 0, 2*Math.PI); ctx.fillStyle = '#ffffff'; ctx.shadowColor = accent; ctx.shadowBlur = 15; ctx.fill(); ctx.shadowBlur = 0;
    }

    function updateCiclo30min() {
      ciclo30min = segundos % 1800;
      const ciclo = Math.floor(segundos / 1800) + 1;
      if (focusModeActive) {
        focusCycleCount.textContent = ciclo;
        drawFocusRing();
      }
    }

    document.getElementById('timerStart').onclick = () => {
      if (timerInterval) return;
      timerInterval = setInterval(() => { segundos++; atualizarTimer(); updateCiclo30min(); if (pomodoroActive && segundos % 1500 === 0) { clearInterval(timerInterval); timerInterval = null; alert(`🍅 Pomodoro ${pomodoroCount++} concluído! Hora da pausa de 5 min.`); } }, 1000);
    };
    document.getElementById('timerPause').onclick = () => {
      clearInterval(timerInterval); timerInterval = null;
      const nome = selectDisciplina.value;
      if (nome && segundos > 0) { const minutos = Math.round(segundos / 60); data[nome].horasMinutos = (data[nome].horasMinutos || 0) + minutos; salvarDados(); renderizarTabela(filtroInput.value); }
      segundos = 0; atualizarTimer(); ciclo30min = 0; updateCiclo30min();
    };
    document.getElementById('timerReset').onclick = () => { clearInterval(timerInterval); timerInterval = null; segundos = 0; atualizarTimer(); ciclo30min = 0; updateCiclo30min(); };

    document.getElementById('focusModeToggle').onclick = () => { focusOverlay.classList.add('active'); focusModeActive = true; updateCiclo30min(); };
    document.getElementById('exitFocusBtn').onclick = () => { focusOverlay.classList.remove('active'); focusModeActive = false; };
    document.getElementById('focusTimerStart').onclick = document.getElementById('timerStart').onclick;
    document.getElementById('focusTimerPause').onclick = document.getElementById('timerPause').onclick;

    document.querySelectorAll('.timer-type-btn').forEach(b => {
      b.onclick = () => {
        document.querySelectorAll('.timer-type-btn').forEach(x => x.classList.remove('active'));
        b.classList.add('active');
        document.getElementById('sessionTypeLabel').textContent = b.dataset.type;
        document.getElementById('focusSessionLabel').textContent = b.dataset.type;
        pomodoroActive = b.dataset.type !== 'Pausa';
      };
    });

    filtroInput.addEventListener('input', e => renderizarTabela(e.target.value));
    addBtn.onclick = () => {
      const nova = novaSelect.value;
      if (!nova) return;
      if (data[nova]) { msgAdicionar.textContent = 'Já existe.'; return; }
      data[nova] = { certas:0, erradas:0, horasMinutos:0 };
      salvarDados(); atualizarSelects(); renderizarTabela(filtroInput.value);
      novaSelect.value = ''; msgAdicionar.textContent = `"${nova}" adicionada!`;
      setTimeout(() => msgAdicionar.textContent = '', 3000);
    };

    (function(){
      const html = document.documentElement;
      const themes = ['dark','light','tema-1','tema-2','minimal'];
      let cur = localStorage.getItem('theme') || 'dark';
      html.setAttribute('data-theme', cur);
      document.getElementById('theme-toggle').onclick = () => { let idx = themes.indexOf(cur); idx = (idx + 1) % themes.length; cur = themes[idx]; html.setAttribute('data-theme', cur); localStorage.setItem('theme', cur); };
      const sidebar = document.getElementById('sidebar');
      const overlay = document.getElementById('sidebarOverlay');
      document.getElementById('hamburgerBtn').onclick = () => { sidebar.classList.add('open'); overlay.classList.add('active'); };
      document.getElementById('closeSidebarBtn').onclick = () => { sidebar.classList.remove('open'); overlay.classList.remove('active'); };
      overlay.onclick = () => { sidebar.classList.remove('open'); overlay.classList.remove('active'); };
      document.getElementById('quemSomosBtn').onclick = () => document.getElementById('vulps-manifesto-overlay').classList.add('vulps-manifesto-open');
      document.getElementById('closeManifestoBtn').onclick = () => document.getElementById('vulps-manifesto-overlay').classList.remove('vulps-manifesto-open');
      document.querySelectorAll('.pix-copy-btn').forEach(b => b.onclick = () => { navigator.clipboard.writeText('sua-chave-pix-aqui'); alert('Chave PIX copiada!'); });
      window.navigateTo = url => window.location.href = url;
    })();

    atualizarSelects();
    renderizarTabela();
    atualizarTimer();
  </script>
</body>
</html>
