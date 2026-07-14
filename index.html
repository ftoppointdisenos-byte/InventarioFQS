<style>
  #inv-root {
    --ink: #0D3049;
    --ink-soft: #4B6C82;
    --ink-faint: #94AEBF;
    --paper: #F3F8FC;
    --paper-line: #DAE7F0;
    --gold: #2E8FD6;
    --gold-bg: #E5F2FB;
    --teal: #0E7C9E;
    --teal-bg: #E1F1F6;
    --green: #1F8A4C;
    --green-bg: #E4F4EA;
    --orange: #C96A1B;
    --orange-bg: #FBEEE1;
    --red: #B23A48;
    --red-bg: #FBEBEC;
    --white: #FFFFFF;
    font-family: 'Inter', -apple-system, sans-serif;
    color: var(--ink);
    background: var(--paper);
    max-width: 100%;
    box-sizing: border-box;
    position: relative;
    border-radius: 18px;
    overflow: hidden;
    box-shadow: 0 1px 2px rgba(13,48,73,0.07), 0 24px 48px -28px rgba(13,48,73,0.28);
  }
  #inv-root * { box-sizing: border-box; }
  #inv-root .mono { font-family: 'IBM Plex Mono', monospace; }

  #inv-root .header {
    padding: 26px 28px 18px;
    border-bottom: 2px solid var(--ink);
    background: var(--ink);
    color: var(--white);
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    flex-wrap: wrap;
    gap: 16px;
  }
  #inv-root .header h1 {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 27px;
    font-weight: 700;
    margin: 0;
    letter-spacing: -0.02em;
    color: var(--white);
  }
  #inv-root .header .eyebrow {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--white);
    opacity: 0.75;
    margin-bottom: 4px;
  }
  #inv-root .header-meta {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 12px;
    color: var(--white);
    opacity: 0.85;
    text-align: right;
  }
  #inv-root .session-info { margin-top: 4px; font-size: 11.5px; }
  #inv-root .session-info a { color: var(--white); opacity: 0.85; text-decoration: underline; cursor: pointer; }
  #inv-root .session-info a:hover { opacity: 1; }

  #inv-root .login-overlay {
    position: fixed; inset: 0; z-index: 90;
    display: flex; overflow: hidden;
  }
  #inv-root .login-panel-left {
    flex: 1.15; min-width: 0;
    background: linear-gradient(155deg, #123B57 0%, #0D3049 55%, #082230 100%);
    color: var(--white); padding: 44px 40px;
    display: flex; flex-direction: column; justify-content: space-between;
    position: relative; overflow: hidden; overflow-y: auto;
  }
  #inv-root .login-hex-deco {
    position: absolute; right: -90px; bottom: -90px;
    width: 340px; height: 340px; opacity: 0.35; pointer-events: none;
  }
  #inv-root .login-brand-logo { height: 34px; width: auto; filter: brightness(0) invert(1); position: relative; z-index: 1; }
  #inv-root .login-headline { position: relative; z-index: 1; }
  #inv-root .login-headline h1 {
    font-family: 'Space Grotesk', sans-serif; font-size: 38px; font-weight: 700;
    margin: 26px 0 10px; letter-spacing: -0.01em; line-height: 1.05;
  }
  #inv-root .login-headline p { font-size: 14.5px; color: rgba(255,255,255,0.72); margin: 0; }
  #inv-root .login-headline .accent { color: #6BBBEF; font-weight: 600; }
  #inv-root .login-foot-note { position: relative; z-index: 1; font-size: 11.5px; color: rgba(255,255,255,0.45); }

  #inv-root .login-panel-right {
    flex: 1; min-width: 0; background: var(--paper);
    display: flex; align-items: center; justify-content: center; padding: 40px 28px;
    overflow-y: auto;
  }
  #inv-root .login-box { width: 100%; max-width: 340px; text-align: center; }
  #inv-root .login-icon-badge {
    width: 54px; height: 54px; border-radius: 50%; background: var(--gold-bg);
    display: flex; align-items: center; justify-content: center; margin: 0 auto 18px;
  }
  #inv-root .login-box h2 { font-family: 'Space Grotesk', sans-serif; font-size: 20px; margin: 0 0 4px; color: var(--ink); }
  #inv-root .login-box p.login-sub { font-size: 13px; color: var(--ink-soft); margin: 0 0 26px; }
  #inv-root .login-box .field { text-align: left; margin-bottom: 16px; }
  #inv-root .login-box .field label {
    display: block; font-size: 11px; text-transform: uppercase; letter-spacing: 0.06em;
    color: var(--ink-soft); margin-bottom: 6px;
  }
  #inv-root .field-icon-wrap { position: relative; }
  #inv-root .field-icon-wrap svg.field-icon {
    position: absolute; left: 11px; top: 50%; transform: translateY(-50%); pointer-events: none;
  }
  #inv-root .login-box select, #inv-root .login-box input {
    width: 100%; font-family: 'Inter', sans-serif; font-size: 14px;
    padding: 10px 10px 10px 34px; border: 1.5px solid var(--paper-line); border-radius: 8px;
    background: var(--white);
  }
  #inv-root .login-box select:focus, #inv-root .login-box input:focus { outline: none; border-color: var(--gold); }
  #inv-root #login-pass { padding-right: 36px; }
  #inv-root .pw-toggle {
    position: absolute; right: 6px; top: 50%; transform: translateY(-50%);
    background: none; border: none; cursor: pointer; color: var(--ink-faint); padding: 6px;
    display: flex; align-items: center;
  }
  #inv-root .pw-toggle:hover { color: var(--ink); }
  #inv-root .login-error {
    background: var(--red-bg); color: var(--red); font-size: 12.5px;
    padding: 8px 10px; border-radius: 6px; margin-top: 4px; margin-bottom: 4px; text-align: left;
  }
  #inv-root .login-box .btn-primary { background: var(--gold); }

  @media (max-width: 760px) {
    #inv-root .login-panel-left { display: none; }
  }

  #inv-root .stats {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 14px;
    padding: 22px 28px 6px;
  }
  #inv-root .stat {
    background: var(--white);
    border: 1px solid var(--paper-line);
    border-radius: 12px;
    padding: 16px 18px;
    box-shadow: 0 1px 2px rgba(13,48,73,0.04);
  }
  #inv-root .stat-label {
    font-size: 10.5px;
    text-transform: uppercase;
    letter-spacing: 0.07em;
    color: var(--ink-soft);
    margin-bottom: 6px;
  }
  #inv-root .stat-value {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 18px;
    font-weight: 600;
  }
  #inv-root .stat-value.gold { color: var(--gold); }
  #inv-root .stat-value.teal { color: var(--teal); }
  #inv-root .stat-value.red { color: var(--red); }
  #inv-root .stat-sub { font-size: 11px; color: var(--gold); margin-top: 4px; font-weight: 600; }
  #inv-root .storage-banner {
    margin: 16px 28px 0;
    padding: 10px 16px;
    font-size: 12.5px;
    border-radius: 8px;
  }
  #inv-root .storage-banner.info { background: var(--teal-bg); color: var(--teal); }
  #inv-root .storage-banner.warning { background: var(--red-bg); color: var(--red); }

  #inv-root .toolbar {
    padding: 22px 28px 18px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 12px;
    flex-wrap: wrap;
  }
  #inv-root .toolbar-left { display: flex; gap: 10px; flex-wrap: wrap; align-items: center; }
  #inv-root .search {
    font-family: 'Inter', sans-serif;
    font-size: 14px;
    padding: 9px 14px;
    border: 1.5px solid var(--paper-line);
    border-radius: 6px;
    background: var(--white);
    width: 240px;
    max-width: 55vw;
  }
  #inv-root .search:focus { outline: none; border-color: var(--ink); }
  #inv-root select.cat-filter {
    font-family: 'Inter', sans-serif;
    font-size: 13px;
    padding: 9px 10px;
    border: 1.5px solid var(--paper-line);
    border-radius: 6px;
    background: var(--white);
    color: var(--ink-soft);
  }
  #inv-root .btn {
    font-family: 'Inter', sans-serif;
    font-size: 14px;
    font-weight: 600;
    padding: 10px 18px;
    border-radius: 6px;
    border: none;
    cursor: pointer;
    transition: transform 0.08s ease, opacity 0.15s ease, background 0.15s ease;
    white-space: nowrap;
  }
  #inv-root .btn:active { transform: scale(0.97); }
  #inv-root .btn-primary { background: var(--ink); color: var(--white); }
  #inv-root .btn-primary:hover { opacity: 0.88; }
  #inv-root .btn-ghost { background: transparent; color: var(--ink-soft); border: 1.5px solid var(--paper-line); }
  #inv-root .btn-ghost:hover { border-color: var(--ink); color: var(--ink); }
  #inv-root .btn-danger { background: var(--red); color: var(--white); }
  #inv-root .btn-danger:hover { opacity: 0.88; }
  #inv-root .btn-sm { padding: 7px 13px; font-size: 13px; }

  #inv-root .form-panel {
    margin: 4px 28px 20px;
    padding: 20px;
    background: var(--white);
    border: 1.5px solid var(--paper-line);
    border-radius: 12px;
    box-shadow: 0 1px 2px rgba(13,48,73,0.05);
    display: none;
  }
  #inv-root .form-panel.open { display: block; }
  #inv-root .form-panel-title {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 15px;
    font-weight: 700;
    margin-bottom: 14px;
  }
  #inv-root .form-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
    gap: 12px;
    align-items: end;
  }
  #inv-root .field label {
    display: block;
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    color: var(--ink-soft);
    margin-bottom: 6px;
  }
  #inv-root .field .hint { font-size: 10.5px; color: var(--ink-faint); margin-top: 4px; text-transform: none; letter-spacing: 0; }
  #inv-root .image-field { display: flex; align-items: center; gap: 14px; }
  #inv-root .image-preview {
    width: 88px; height: 88px; border-radius: 8px; overflow: hidden;
    background: var(--paper); border: 1.5px dashed var(--paper-line);
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0; color: var(--ink-faint); font-size: 11px; text-align: center;
  }
  #inv-root .image-preview img { width: 100%; height: 100%; object-fit: cover; display: block; }
  #inv-root .image-actions { display: flex; gap: 8px; align-items: center; }
  #inv-root .image-actions input[type="file"] { display: none; }
  #inv-root .thumb {
    width: 62px; height: 62px; border-radius: 8px; object-fit: cover;
    margin-right: 12px; vertical-align: middle; border: 1.5px solid var(--paper-line);
    cursor: zoom-in; flex-shrink: 0;
  }
  #inv-root .thumb-placeholder {
    width: 62px; height: 62px; border-radius: 8px; margin-right: 12px;
    background: var(--paper); border: 1.5px dashed var(--paper-line);
    display: inline-flex; align-items: center; justify-content: center;
    vertical-align: middle; color: var(--ink-faint); font-size: 20px; flex-shrink: 0;
  }
  #inv-root .name-cell-inner { display: flex; align-items: center; }
  #inv-root .desc-cell {
    font-size: 12.5px; color: var(--ink-soft); max-width: 280px;
    overflow: hidden; text-overflow: ellipsis; white-space: nowrap; cursor: help;
  }
  #inv-root .lightbox {
    position: fixed; inset: 0; background: rgba(22,35,61,0.75);
    display: none; align-items: center; justify-content: center; z-index: 55; cursor: zoom-out;
  }
  #inv-root .lightbox.open { display: flex; }
  #inv-root .lightbox img { max-width: 80vw; max-height: 80vh; border-radius: 10px; }
  #inv-root .field input {
    width: 100%;
    font-family: 'Inter', sans-serif;
    font-size: 14px;
    padding: 9px 10px;
    border: 1.5px solid var(--paper-line);
    border-radius: 6px;
  }
  #inv-root .field input:focus { outline: none; border-color: var(--ink); }
  #inv-root .field input.err { border-color: var(--red); }
  #inv-root .field select {
    width: 100%;
    font-family: 'Inter', sans-serif;
    font-size: 14px;
    padding: 9px 10px;
    border: 1.5px solid var(--paper-line);
    border-radius: 6px;
    background: var(--white);
    color: var(--ink);
  }
  #inv-root .field select:focus { outline: none; border-color: var(--ink); }
  #inv-root .form-actions {
    margin-top: 14px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  #inv-root .form-actions-right { display: flex; gap: 10px; }
  #inv-root .live-margin {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 13px;
    color: var(--ink-soft);
  }
  #inv-root .live-margin span { font-weight: 700; }

  #inv-root table { width: 100%; border-collapse: collapse; }
  #inv-root .check-col { width: 34px; text-align: center !important; padding-left: 14px !important; padding-right: 4px !important; }
  #inv-root .check-col input[type="checkbox"] { width: 15px; height: 15px; cursor: pointer; accent-color: var(--ink); vertical-align: middle; }
  #inv-root thead th {
    text-align: left;
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    color: var(--ink-soft);
    padding: 10px 10px;
    border-bottom: 1.5px solid var(--ink);
    cursor: pointer;
    user-select: none;
    white-space: nowrap;
    position: sticky;
    top: 0;
    background: var(--paper);
  }
  #inv-root thead th:hover { color: var(--ink); }
  #inv-root thead th.num, #inv-root td.num { text-align: right; }
  #inv-root tbody td {
    padding: 12px 10px;
    border-bottom: 1px solid var(--paper-line);
    font-size: 14px;
    vertical-align: middle;
  }
  #inv-root tbody tr:hover { background: rgba(184,144,63,0.06); }
  #inv-root td.name-cell { font-weight: 600; }
  #inv-root td.name-cell .sku { display: block; font-family: 'IBM Plex Mono', monospace; font-weight: 400; font-size: 11px; color: var(--ink-faint); margin-top: 2px; }
  #inv-root .cat-badge {
    display: inline-block;
    font-size: 11px;
    padding: 3px 9px;
    border-radius: 20px;
    background: var(--gold-bg);
    color: var(--gold);
    font-weight: 600;
  }
  #inv-root .stock-badge {
    display: inline-block;
    font-size: 11px;
    padding: 3px 9px;
    border-radius: 20px;
    font-weight: 600;
    margin-left: 8px;
  }
  #inv-root .stock-badge.ok { background: var(--teal-bg); color: var(--teal); }
  #inv-root .stock-badge.low { background: var(--gold-bg); color: var(--gold); }
  #inv-root .stock-badge.out { background: var(--red-bg); color: var(--red); }
  #inv-root .margin-pos { color: var(--teal); font-weight: 600; }
  #inv-root .margin-neg { color: var(--red); font-weight: 600; }
  #inv-root .row-actions { display: flex; gap: 6px; justify-content: flex-end; }
  #inv-root .icon-btn {
    background: none; border: none; cursor: pointer;
    color: var(--ink-soft); font-size: 12.5px; padding: 5px 8px;
    border-radius: 5px;
  }
  #inv-root .icon-btn:hover { background: var(--paper-line); color: var(--ink); }
  #inv-root .icon-btn.danger:hover { background: var(--red-bg); color: var(--red); }

  #inv-root tfoot td {
    padding: 12px 10px;
    font-family: 'IBM Plex Mono', monospace;
    font-size: 13px;
    font-weight: 700;
    border-top: 2px solid var(--ink);
  }

  #inv-root .empty {
    margin: 4px 28px 28px;
    padding: 56px 28px;
    text-align: center;
    color: var(--ink-soft);
    background: var(--white);
    border: 1px solid var(--paper-line);
    border-radius: 14px;
    box-shadow: 0 1px 2px rgba(13,48,73,0.05);
  }
  #inv-root .empty-title { font-family: 'Space Grotesk', sans-serif; font-size: 18px; color: var(--ink); margin-bottom: 6px; }

  #inv-root .table-wrap {
    margin: 4px 28px 28px;
    background: var(--white);
    border: 1px solid var(--paper-line);
    border-radius: 14px;
    box-shadow: 0 1px 2px rgba(13,48,73,0.05), 0 16px 32px -24px rgba(13,48,73,0.2);
    overflow-x: auto;
    max-height: 560px;
    overflow-y: auto;
  }

  #inv-root .footer-note {
    padding: 0 28px 22px;
    font-size: 12px;
    color: var(--ink-faint);
  }

  #inv-root .wh-select {
    font-family: 'Inter', sans-serif;
    font-size: 12.5px;
    padding: 5px 8px;
    border-radius: 6px;
    border: 1.5px solid var(--paper-line);
    background: var(--white);
    color: var(--ink-soft);
    max-width: 150px;
  }
  #inv-root .wh-select:focus { outline: none; border-color: var(--ink); color: var(--ink); }
  #inv-root .wh-new-inline {
    display: flex; gap: 6px; align-items: center;
  }
  #inv-root .wh-new-inline input {
    font-family: 'Inter', sans-serif;
    font-size: 12.5px;
    padding: 5px 8px;
    border-radius: 6px;
    border: 1.5px solid var(--ink);
    max-width: 130px;
  }
  #inv-root .modal-overlay {
    position: fixed; inset: 0; background: rgba(22,35,61,0.45);
    display: none; align-items: center; justify-content: center; z-index: 50;
  }
  #inv-root .modal-overlay.open { display: flex; }
  #inv-root .modal-box {
    background: var(--white); border-radius: 10px; padding: 22px; width: 320px;
    box-shadow: 0 12px 32px rgba(22,35,61,0.25);
  }
  #inv-root .modal-title { font-family: 'Space Grotesk', sans-serif; font-weight: 700; font-size: 16px; margin-bottom: 8px; }
  #inv-root .modal-body { font-size: 13.5px; color: var(--ink-soft); margin-bottom: 18px; }
  #inv-root .modal-actions { display: flex; justify-content: flex-end; gap: 10px; }

  /* Historial */
  #inv-root .history-box { width: 560px; max-width: 92vw; max-height: 80vh; display: flex; flex-direction: column; }
  #inv-root .history-head { display: flex; justify-content: space-between; align-items: flex-start; gap: 12px; margin-bottom: 14px; flex-wrap: wrap; }
  #inv-root .history-count { font-size: 12px; color: var(--ink-faint); }
  #inv-root .history-list { overflow-y: auto; flex: 1; display: flex; flex-direction: column; gap: 10px; padding-right: 4px; }
  #inv-root .hist-entry { border: 1.5px solid var(--paper-line); border-radius: 8px; padding: 10px 12px; }
  #inv-root .hist-top { display: flex; align-items: center; gap: 8px; flex-wrap: wrap; margin-bottom: 4px; }
  #inv-root .hist-name { font-weight: 600; font-size: 13.5px; flex: 1; min-width: 0; }
  #inv-root .hist-user { font-size: 11px; color: var(--ink-faint); margin-bottom: 2px; }
  #inv-root .hist-time { font-family: 'IBM Plex Mono', monospace; font-size: 11px; color: var(--ink-faint); white-space: nowrap; }
  #inv-root .hist-badge { font-size: 10px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.04em; padding: 3px 8px; border-radius: 20px; }
  #inv-root .hist-badge.create { background: var(--teal-bg); color: var(--teal); }
  #inv-root .hist-badge.update { background: var(--gold-bg); color: var(--gold); }
  #inv-root .hist-badge.delete { background: var(--red-bg); color: var(--red); }
  #inv-root .hist-changes { margin: 6px 0 0; padding-left: 18px; font-size: 12.5px; color: var(--ink-soft); }
  #inv-root .hist-changes li { margin-bottom: 2px; }
  #inv-root .hist-changes b { color: var(--ink); }
  #inv-root .hist-empty { text-align: center; padding: 40px 10px; color: var(--ink-faint); font-size: 13px; }

  /* Gestor de categorías */
  #inv-root .cat-manage-row {
    display: flex; justify-content: space-between; align-items: center;
    padding: 11px 12px; border: 1px solid var(--paper-line); border-radius: 8px; margin-bottom: 8px;
  }
  #inv-root .cat-manage-name { font-weight: 600; font-size: 13.5px; color: var(--ink); }
  #inv-root .cat-manage-count { font-size: 11.5px; color: var(--ink-faint); margin-left: 8px; }
  #inv-root .cat-manage-del {
    background: var(--red-bg); color: var(--red); border: none; border-radius: 6px;
    padding: 5px 12px; font-size: 12px; font-weight: 600; cursor: pointer; font-family: inherit;
  }
  #inv-root .cat-manage-del:hover { background: #F5D5D8; }
  #inv-root .cat-manage-lock { font-size: 11px; color: var(--ink-faint); font-style: italic; }

  #inv-root .cat-item {
    display: flex; align-items: center; justify-content: space-between;
    padding: 10px 12px; border: 1.5px solid var(--paper-line); border-radius: 8px; margin-bottom: 8px;
  }
  #inv-root .cat-item-name { font-weight: 600; font-size: 13.5px; }
  #inv-root .cat-item-count { font-size: 11px; color: var(--ink-faint); margin-left: 8px; font-weight: 400; }
  #inv-root .cat-item-del {
    background: none; border: none; color: var(--ink-faint); cursor: pointer; font-size: 18px;
    line-height: 1; padding: 2px 6px;
  }
  #inv-root .cat-item-del:hover { color: var(--red); }
  #inv-root .cat-item-del:disabled { opacity: 0.3; cursor: not-allowed; }

  /* Cotización */
  #inv-root .quote-bar {
    position: fixed; left: 50%; bottom: 24px; transform: translateX(-50%);
    background: var(--ink); color: var(--white);
    padding: 12px 14px 12px 20px; border-radius: 12px;
    box-shadow: 0 12px 32px rgba(13,48,73,0.35);
    display: flex; align-items: center; gap: 20px; z-index: 40;
    font-size: 13.5px;
  }
  #inv-root .quote-item { display: flex; align-items: center; gap: 10px; padding: 9px 4px; border-bottom: 1px solid var(--paper-line); }
  #inv-root .quote-item-thumb { width: 44px; height: 44px; border-radius: 6px; object-fit: cover; border: 1px solid var(--paper-line); flex-shrink: 0; }
  #inv-root .quote-item-thumb-placeholder {
    width: 44px; height: 44px; border-radius: 6px; background: var(--paper); border: 1px dashed var(--paper-line);
    flex-shrink: 0; display: flex; align-items: center; justify-content: center; color: var(--ink-faint); font-size: 15px;
  }
  #inv-root .quote-item-info { flex: 1; min-width: 0; }
  #inv-root .quote-item-name { font-weight: 600; font-size: 13px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  #inv-root .quote-item-sku { font-size: 11px; color: var(--ink-faint); font-family: 'IBM Plex Mono', monospace; }
  #inv-root .quote-item-qty { text-align: center; flex-shrink: 0; }
  #inv-root .quote-item-qty label { display: block; font-size: 9.5px; text-transform: uppercase; color: var(--ink-faint); margin-bottom: 3px; }
  #inv-root .quote-item-qty input {
    width: 48px; text-align: center; padding: 5px 4px; border: 1.5px solid var(--paper-line);
    border-radius: 6px; font-size: 13px; font-family: 'Inter', sans-serif;
  }
  #inv-root .quote-item-price, #inv-root .quote-item-subtotal {
    font-family: 'IBM Plex Mono', monospace; font-size: 12.5px; width: 82px; text-align: right; flex-shrink: 0;
  }
  #inv-root .quote-item-subtotal { font-weight: 700; color: var(--green); }
  #inv-root .quote-item-remove {
    background: none; border: none; color: var(--ink-faint); cursor: pointer; font-size: 18px;
    line-height: 1; padding: 2px 4px; flex-shrink: 0;
  }
  #inv-root .quote-item-remove:hover { color: var(--red); }
  #inv-root .quote-unpriced-note {
    font-size: 11.5px; color: var(--ink-faint); background: var(--paper);
    padding: 8px 10px; border-radius: 6px; margin-top: 8px;
  }
  #inv-root .quote-total-row {
    display: flex; justify-content: space-between; align-items: center;
    padding: 14px 4px 4px; border-top: 2px solid var(--ink); margin-top: 4px;
    font-weight: 700; font-size: 17px; font-family: 'Space Grotesk', sans-serif;
  }
  #inv-root .quote-total-row span:last-child { color: var(--green); }
  #inv-root .quote-comercial-row {
    margin-top: 14px; padding-top: 12px; border-top: 1px solid var(--paper-line);
  }
  #inv-root .quote-comercial-row label {
    display: block; font-size: 11px; text-transform: uppercase; letter-spacing: 0.06em;
    color: var(--ink-soft); margin-bottom: 6px;
  }
  #inv-root .quote-comercial-row select {
    width: 100%; font-family: 'Inter', sans-serif; font-size: 14px;
    padding: 9px 10px; border: 1.5px solid var(--paper-line); border-radius: 6px;
  }

  @media (max-width: 640px) {
    #inv-root .quote-bar { left: 12px; right: 12px; transform: none; flex-direction: column; align-items: stretch; gap: 10px; }
    #inv-root .quote-item-price { display: none; }
  }

  /* Toast */
  #inv-root .toast {
    position: fixed; bottom: 24px; left: 50%; transform: translateX(-50%) translateY(20px);
    background: var(--ink); color: var(--white); padding: 11px 20px; border-radius: 8px;
    font-size: 13.5px; opacity: 0; pointer-events: none; transition: all 0.25s ease; z-index: 60;
  }
  #inv-root .toast.show { opacity: 1; transform: translateX(-50%) translateY(0); }

  @media (max-width: 720px) {
    #inv-root .stats { grid-template-columns: repeat(2, 1fr); }
    #inv-root .form-grid { grid-template-columns: 1fr 1fr; }
    #inv-root .header { flex-direction: column; align-items: flex-start; }
    #inv-root .table-wrap { max-height: none; }
  }
</style>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>

<div id="inv-root">
  <div class="header">
    <div style="display:flex; align-items:center; gap:16px;">
      <img src="data:image/png;base64,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" alt="FQS" style="height:40px; width:auto; display:block; filter: brightness(0) invert(1);">
      <div>
        <div class="eyebrow">Control de existencias</div>
        <h1>Inventario</h1>
      </div>
    </div>
    <div class="header-meta">
      <div id="inv-datestamp"></div>
      <div class="session-info" id="session-info" style="display:none;">
        <span id="session-user-label"></span> · <a href="javascript:void(0)" id="btn-logout">Cerrar sesión</a>
      </div>
    </div>
  </div>

  <div class="login-overlay" id="login-overlay">
    <div class="login-panel-left">
      <div>
        <img src="data:image/png;base64,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" alt="FQS" class="login-brand-logo">
        <div class="login-headline">
          <h1>Inventario</h1>
          <p>Controla. Administra. <span class="accent">Optimiza.</span></p>
        </div>
      </div>
      <svg class="login-hex-deco" viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
        <polygon points="100,6 176,50 176,138 100,182 24,138 24,50" stroke="#FFFFFF" stroke-width="2"/>
        <polygon points="100,46 144,70 144,118 100,142 56,118 56,70" stroke="#6BBBEF" stroke-width="1.5"/>
      </svg>
      <div class="login-foot-note">FQS · Fine Quality Sound</div>
    </div>

    <div class="login-panel-right">
      <div class="login-box">
        <div class="login-icon-badge">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="5" y="11" width="14" height="10" rx="2" stroke="#2E8FD6" stroke-width="1.8"/>
            <path d="M8 11V7a4 4 0 0 1 8 0v4" stroke="#2E8FD6" stroke-width="1.8" stroke-linecap="round"/>
            <circle cx="12" cy="16" r="1.6" fill="#2E8FD6"/>
          </svg>
        </div>
        <h2>Iniciar sesión</h2>
        <p class="login-sub">Ingresa tus datos para continuar</p>

        <div class="field">
          <label>Usuario</label>
          <div class="field-icon-wrap">
            <svg class="field-icon" width="15" height="15" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <circle cx="12" cy="8" r="3.5" stroke="#94AEBF" stroke-width="1.8"/>
              <path d="M4.5 20c1.2-3.6 4.2-5.5 7.5-5.5s6.3 1.9 7.5 5.5" stroke="#94AEBF" stroke-width="1.8" stroke-linecap="round"/>
            </svg>
            <select id="login-user">
              <option value="">Selecciona tu usuario</option>
              <option value="administrativo">Administrativo</option>
              <option value="comercial">Comercial</option>
            </select>
          </div>
        </div>

        <div class="field">
          <label>Contraseña</label>
          <div class="field-icon-wrap">
            <svg class="field-icon" width="15" height="15" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="5" y="11" width="14" height="9" rx="2" stroke="#94AEBF" stroke-width="1.8"/>
              <path d="M8 11V8a4 4 0 0 1 8 0v3" stroke="#94AEBF" stroke-width="1.8" stroke-linecap="round"/>
            </svg>
            <input type="password" id="login-pass" placeholder="Contraseña" autocomplete="current-password">
            <button type="button" class="pw-toggle" id="pw-toggle" tabindex="-1">
              <svg id="pw-icon-show" width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M2 12s3.6-7 10-7 10 7 10 7-3.6 7-10 7-10-7-10-7Z" stroke="currentColor" stroke-width="1.8"/>
                <circle cx="12" cy="12" r="3" stroke="currentColor" stroke-width="1.8"/>
              </svg>
              <svg id="pw-icon-hide" width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="display:none;">
                <path d="M3 3l18 18M10.6 10.6a3 3 0 0 0 4.2 4.2M6.6 6.7C4 8.3 2 12 2 12s3.6 7 10 7c1.8 0 3.4-.4 4.7-1.1M17.5 17.4C19.8 15.7 22 12 22 12s-1.2-2.4-3.3-4.4" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/>
              </svg>
            </button>
          </div>
        </div>

        <div class="login-error" id="login-error" style="display:none;"></div>
        <button class="btn btn-primary" id="login-submit" style="width:100%; margin-top:6px;">Iniciar sesión</button>
      </div>
    </div>
  </div>

  <div class="storage-banner" id="storage-banner" style="display:none;"></div>

  <div class="stats">
    <div class="stat">
      <div class="stat-label">Productos</div>
      <div class="stat-value mono" id="stat-count">0</div>
      <div class="stat-sub" id="stat-pending" style="display:none;"></div>
    </div>
    <div class="stat">
      <div class="stat-label">Unidades totales</div>
      <div class="stat-value mono" id="stat-units">0</div>
    </div>
    <div class="stat">
      <div class="stat-label">Valor en costo</div>
      <div class="stat-value mono" id="stat-cost">$ 0</div>
    </div>
    <div class="stat">
      <div class="stat-label">Valor en venta</div>
      <div class="stat-value mono gold" id="stat-sale">$ 0</div>
    </div>
    <div class="stat">
      <div class="stat-label">Margen promedio</div>
      <div class="stat-value mono teal" id="stat-margin">0%</div>
    </div>
  </div>

  <div class="toolbar">
    <div class="toolbar-left">
      <input type="text" class="search" id="inv-search" placeholder="Buscar por nombre, SKU o proveedor…">
      <select class="cat-filter" id="cat-filter">
        <option value="">Todas las categorías</option>
      </select>
      <select class="cat-filter" id="wh-filter">
        <option value="">Todas las bodegas</option>
      </select>
    </div>
    <div style="display:flex; gap:10px;">
      <button class="btn btn-ghost" id="btn-categories">Categorías</button>
      <button class="btn btn-ghost" id="btn-history">Historial</button>
      <button class="btn btn-ghost" id="btn-export">Exportar Excel</button>
      <button class="btn btn-ghost" id="btn-export-pdf">Descargar PDF</button>
      <button class="btn btn-primary" id="btn-toggle-form">+ Agregar producto</button>
    </div>
  </div>

  <div class="form-panel" id="form-panel">
    <div class="form-panel-title" id="form-title">Nuevo producto</div>
    <div class="form-grid">
      <div class="field">
        <label>Nombre *</label>
        <input type="text" id="f-name" placeholder="Ej: Panel acústico 60x60">
      </div>
      <div class="field">
        <label>Categoría</label>
        <input type="text" id="f-cat" list="cat-list" placeholder="Ej: Acústica">
        <datalist id="cat-list"></datalist>
      </div>
      <div class="field">
        <label>SKU / código</label>
        <input type="text" id="f-sku" placeholder="Opcional">
      </div>
      <div class="field">
        <label>Precio compra</label>
        <input type="number" id="f-cost" placeholder="Déjalo vacío si no lo sabes" min="0">
      </div>
      <div class="field">
        <label>Precio venta</label>
        <input type="number" id="f-sale" placeholder="Déjalo vacío si no lo sabes" min="0">
      </div>
      <div class="field">
        <label>Precio Mercado Libre</label>
        <input type="number" id="f-meli" placeholder="Opcional" min="0">
      </div>
      <div class="field">
        <label>Precio redes / Shopify</label>
        <input type="number" id="f-redes" placeholder="Opcional" min="0">
      </div>
      <div class="field">
        <label>Stock</label>
        <input type="number" id="f-stock" placeholder="0" min="0">
      </div>
    </div>
    <div class="field" style="margin-top:12px;">
      <label>Descripción</label>
      <textarea id="f-descripcion" placeholder="Características, detalles del producto..." rows="2" style="width:100%; font-family:'Inter',sans-serif; font-size:14px; padding:9px 10px; border:1.5px solid var(--paper-line); border-radius:6px; resize:vertical; box-sizing:border-box;"></textarea>
    </div>
    <div style="margin-top:12px; display:flex; gap:24px; flex-wrap:wrap;">
      <div class="field" style="max-width: 220px; flex:1;">
        <label>Proveedor</label>
        <input type="text" id="f-provider" placeholder="Opcional">
      </div>
      <div class="field" style="max-width: 240px; flex:1;">
        <label>Bodega / espacio</label>
        <select id="f-warehouse">
          <option value="">Sin asignar</option>
          <option value="__new__">+ Nueva bodega o espacio…</option>
        </select>
        <input type="text" id="f-warehouse-new" placeholder="Nombre de la bodega o espacio" style="display:none; margin-top:8px;">
      </div>
      <div class="field">
        <label>Foto del producto</label>
        <div class="image-field">
          <div class="image-preview" id="image-preview">Sin foto</div>
          <div class="image-actions">
            <button type="button" class="btn btn-ghost btn-sm" id="btn-upload-image">Subir imagen</button>
            <button type="button" class="btn btn-ghost btn-sm" id="btn-remove-image" style="display:none;">Quitar</button>
          </div>
          <input type="file" id="f-image" accept="image/*">
        </div>
        <div class="hint">JPG o PNG, se ajusta automáticamente · también puedes pegarla con Ctrl+V</div>
      </div>
    </div>
    <div class="form-actions">
      <div class="live-margin" id="live-margin">Ganancia: <span class="mono">$ 0</span> · <span class="mono">0%</span></div>
      <div class="form-actions-right">
        <button class="btn btn-ghost" id="btn-cancel">Cancelar</button>
        <button class="btn btn-primary" id="btn-save">Guardar producto</button>
      </div>
    </div>
  </div>

  <div id="inv-body"></div>

  <div class="footer-note" id="footer-note" style="display:none;">
    Se considera <strong>stock bajo</strong> cuando quedan 3 unidades o menos, y <strong>agotado</strong> en 0.
  </div>

  <div class="modal-overlay" id="modal-overlay">
    <div class="modal-box">
      <div class="modal-title">Eliminar producto</div>
      <div class="modal-body" id="modal-body">¿Seguro que quieres eliminar este producto? Esta acción no se puede deshacer.</div>
      <div class="modal-actions">
        <button class="btn btn-ghost btn-sm" id="modal-cancel">Cancelar</button>
        <button class="btn btn-danger btn-sm" id="modal-confirm">Eliminar</button>
      </div>
    </div>
  </div>

  <div class="modal-overlay" id="history-overlay">
    <div class="modal-box history-box">
      <div class="history-head">
        <div>
          <div class="modal-title" style="margin-bottom:2px;">Historial de cambios</div>
          <div class="history-count" id="history-count"></div>
        </div>
        <div style="display:flex; gap:8px;">
          <input type="text" class="search" id="history-search" placeholder="Buscar producto…" style="width:180px;">
          <button class="btn btn-ghost btn-sm" id="history-close">Cerrar</button>
        </div>
      </div>
      <div class="history-list" id="history-list"></div>
    </div>
  </div>

  <div class="modal-overlay" id="categories-overlay">
    <div class="modal-box history-box" style="max-width:440px;">
      <div class="history-head">
        <div class="modal-title" style="margin-bottom:2px;">Categorías</div>
        <button class="btn btn-ghost btn-sm" id="categories-close">Cerrar</button>
      </div>
      <div style="display:flex; gap:8px; margin-bottom:14px;">
        <input type="text" class="search" id="new-category-input" placeholder="Nombre de la nueva categoría" style="flex:1;">
        <button class="btn btn-primary btn-sm" id="add-category-btn">Agregar</button>
      </div>
      <div class="history-list" id="categories-list"></div>
    </div>
  </div>

  <div class="quote-bar" id="quote-bar" style="display:none;">
    <span id="quote-bar-count">0 productos seleccionados</span>
    <div style="display:flex; gap:8px;">
      <button class="btn btn-ghost btn-sm" id="quote-bar-clear" style="color:var(--white); border-color:rgba(255,255,255,0.3);">Cancelar</button>
      <button class="btn btn-primary btn-sm" id="quote-bar-generate">Generar cotización</button>
    </div>
  </div>

  <div class="modal-overlay" id="quote-overlay">
    <div class="modal-box history-box">
      <div class="history-head">
        <div>
          <div class="modal-title" style="margin-bottom:2px;">Cotización</div>
          <div class="history-count" id="quote-item-count"></div>
        </div>
        <button class="btn btn-ghost btn-sm" id="quote-close">Cerrar</button>
      </div>
      <div class="history-list" id="quote-list"></div>
      <div class="quote-unpriced-note" id="quote-unpriced-note" style="display:none;">Algunos productos no tienen precio de venta configurado — no se incluyen en el total.</div>
      <div class="quote-total-row">
        <span>Total</span>
        <span id="quote-total-amount">$0</span>
      </div>
      <div class="quote-comercial-row">
        <label>Comercial que envía</label>
        <select id="quote-comercial">
          <option value="">— Selecciona —</option>
        </select>
      </div>
      <div class="modal-actions" style="margin-top:14px;">
        <button class="btn btn-primary" id="quote-download" style="width:100%;">Descargar cotización (PNG)</button>
      </div>
    </div>
  </div>

  <div class="toast" id="toast"></div>
  <div class="lightbox" id="lightbox"><img id="lightbox-img" src="" alt=""></div>
</div>

<script type="application/json" id="seed-xlsx-data">[]</script>

<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;700&family=Inter:wght@400;500;600&family=IBM+Plex+Mono:wght@400;500;600;700&display=swap" rel="stylesheet">

<script>
(function() {
  window.onerror = function(msg, url, line, col, err) {
    console.error('ERROR GLOBAL:', msg, 'en línea', line);
    const t = document.getElementById('toast');
    if (t) { t.textContent = 'Error: ' + msg; t.className = 'toast show'; setTimeout(() => t.className = 'toast', 5000); }
  };
  const SEED_DATA = [{"name": "REDMI NOTE 14 PRO NEGRO", "sku": "1251003", "cat": "Celulares", "provider": "", "cost": 990000.0, "sale": 1387190.0, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Pantalla 6.67\" AMOLED - Cámara 108 MP - 8 GB RAM | 256 GB - Batería 5500 mAh - MediaTek 8 núcleos - IP54 | Dual SIM | USB-C"}, {"name": "REDMI NOTE 14 PRO VERDE", "sku": "1251006", "cat": "Celulares", "provider": "", "cost": 990000.0, "sale": 1387190.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Pantalla 6.67\" AMOLED - Cámara 108 MP - 8 GB RAM | 256 GB - Batería 5500 mAh - MediaTek 8 núcleos - IP54 | Dual SIM | USB-C"}, {"name": "REDMI 15 NEGRO Pantalla IPS LCD de 6,9” FHD+", "sku": "1251009", "cat": "Celulares", "provider": "", "cost": 540000.0, "sale": 749900.0, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Procesador Qualcomm Snapdragon 685 (6 nm) - 8 GB de RAM para rendimiento fluido - 256 GB de almacenamiento ampliable con microSD - Batería de 7000 mAh con carga rápida 33W - Cámara principal 50 MP (f/1.8) + lente auxiliar - Cámara frontal 8 MP"}, {"name": "POCO X7 NEGRO Almacenamiento: 256 GB", "sku": "125030102", "cat": "Celulares", "provider": "", "cost": 1000000.0, "sale": 1401190.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Tamaño de la pantalla: 6.67 - Cámara posterior: 50 MP - Cámara frontal: 20 MP - Memoria RAM: 8GB"}, {"name": "MOTO G75 AZUL", "sku": "125101", "cat": "Celulares", "provider": "", "cost": 899900.0, "sale": 980000.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "ACER-AL15-41P-R7JP COMPUTADOR PORTATIL", "sku": "1111201", "cat": "Portatiles y computadores", "provider": "", "cost": 1459000.0, "sale": 1758999.0, "meli": 0.0, "redes": null, "stock": 7, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "procesador AMD Ryzen 7 5700U, pantalla de 15.6\" Full HD, 8 GB de RAM DDR4 (expandible) y almacenamiento SSD ultrarrápido de 512 GB NVMe"}, {"name": "ACER-AG14-31P-35FJ COMPUTADOR PORTATIL", "sku": "11112", "cat": "Portatiles y computadores", "provider": "", "cost": 1359000.0, "sale": 1599824.0, "meli": 0.0, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Procesador: Intel Core i3-N305 (hasta 3.8 GHz, 8 núcleos) - RAM: 8 GB  -  Almacenamiento: SSD 512 GB  -  Pantalla: 14” WUXGA IPS  -  Gráficos: Intel UHD - Sistema operativo: Linux - Conectividad: USB, USB-C, HDMI, Wi-Fi, Bluetooth - Peso: 1.49 kg"}, {"name": "IDEAPAD SLIM 3 15 IAN8 COMPUTADOR PORTATIL LENOVO", "sku": "11109", "cat": "Portatiles y computadores", "provider": "", "cost": 1339000.0, "sale": 1576294.0, "meli": null, "redes": null, "stock": 6, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Procesador: Intel Core i3-N305   -  Memoria RAM: 8  -  GB Almacenamiento: 512 GB.  -  Pantalla: 15,6  -  Full HD Gráficos: Gráficos Intel UHD integrados."}, {"name": "MONITOR CAIXUN C24X3F", "sku": "", "cat": "Portatiles y computadores", "provider": "", "cost": 256360.0, "sale": 360094.0, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Pantalla: 24 pulgadas con panel IPS plano.Resolución: Full HD (1920 × 1080 píxeles). - Tasa de refresco: Hasta 100Hz.Tiempo de respuesta: 14 ms (5 ms con Over Drive / OD).   -   Ángulo de visión: 178° / 178°.  -  Contraste: 1000:1.   -  Tecnologías visuales: Soporte HDR10, Anti-flicker (antiparpadeo) y Low Blue Light (filtro de luz azul) para fatiga visual.  - Conectividad: Puertos HDMI y VGA.  -  Audio: Incluye altavoces incorporados (2W x 2) y salida para audífonos.   -  Ergonomía: Compatible con soporte VESA (75 × 75 mm)."}, {"name": "TABLET LENOVO TAB K11 CON LAPIZ", "sku": "21709", "cat": "Tablets", "provider": "", "cost": 919035.0, "sale": 1082217.65, "meli": 0.0, "redes": 0.0, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Sistema operativo: Android  -  Procesador: MediaTek Helio  -  Características de la pantalla: Touch  - Cámara posterior: 13 MP  -  Almacenamiento: 128 GB -  Ram: 8 GB -  Incluye:  Forro protector + Teclado + Lápiz"}, {"name": "TABLET REDMI PAD PRO GRIS", "sku": "217051", "cat": "Tablets", "provider": "", "cost": 890986.0, "sale": 1049000.0, "meli": 0.0, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Pantalla 12.1\" 2.5K – 120 Hz  -  Snapdragon 7s Gen 2  -  6 GB RAM | 128 GB (expandible hasta 1.5 TB  -  Batería 10,000 mAh  -  Cámaras 8 MP (frontal y trasera)  - Diseño premium – 7.5 mm | 571 g  -  Dolby Vision – Gorilla Glass 3"}, {"name": "TABLET HOLDER SUPERFIX", "sku": "", "cat": "Tablets", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 10, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MAX ULTRA SMART WATCH GS-10 ROSADO", "sku": "327051", "cat": "SMART WATCH", "provider": "", "cost": 136130.0, "sale": 191772.0, "meli": 0.0, "redes": 0.0, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Atiende llamadas + sincroniza contactos  -  Registra pasos, distancia, calorías y actividad diaria - Monitoreo: presión, oxígeno y ritmo cardíaco - Pantalla OLED de alta resolución  -  Bluetooth 5.2 estable - Diseño cómodo y ligero"}, {"name": "ULTRA PRO SMART WATCH GS-ULTRA 2 NARANJA", "sku": "32702", "cat": "SMART WATCH", "provider": "", "cost": 122690.0, "sale": 172956.0, "meli": 0.0, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Cuerpo en aleación de zinc + correa de silicona líquida  -  Bluetooth 5.2  -  Compatible con Android 5.0 / iOS 10+ - Batería 3–5 días - Diseño elegante, cómodo y resistente"}, {"name": "TELEVISOR HISENSE 55\"", "sku": "46008", "cat": "TV- MONITORES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "resolución 4K Ultra HD, tecnología HDR (Dolby Vision), procesador con escalado IA, sistema operativo VIDAA (con control por voz y apps como Netflix/Prime Video), audio DTS Virtual:X y Game Mode Plus (60Hz)"}, {"name": "TELEVISOR SAMSUNG 85 \"", "sku": "46005", "cat": "TV- MONITORES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "panel gigante con resolución 4K UHD (3840 × 2160). Varía según la tecnología (Crystal UHD, QLED o Mini LED), procesador con IA para escalado 4K, sistema operativo Tizen, tres puertos HDMI, dos USB, Bluetooth 5.3, HDR y Motion Xcelerator"}, {"name": "IN EARS KZ-CASTOR PLATEADOS", "sku": "7100", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 60000.0, "meli": 130000.0, "redes": 115000.0, "stock": 8, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "IEM Hi-Fi afinación Harman neutral  - Doble driver dinámico 10 mm + 8 mm - Switches con hasta 16 perfiles de sonido - 20 Hz – 40 kHz | 31–35 Ω | 105 Db - Cable OFC desmontable 0.75 mm (sin micrófono)"}, {"name": "IN EARS KZ D-FI GRIS", "sku": "7174", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": 106000.0, "redes": 95000.0, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "IN EARS KZ VADER", "sku": "8699", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 145000.0, "meli": 230000.0, "redes": 205000.0, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Sonido potente y claro con doble driver dinámico - Graves profundos, voces definidas y agudos brillantes - Diseño ergonómico y ligero para uso prolongado - Cable desmontable (mayor durabilidad y fácil reemplazo) - Ideal para música, gaming, monitoreo y uso diario"}, {"name": "IN EARS KZ-ZS10 PRO 2", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 190000.0, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "IEM híbridos Hi-Fi (5 drivers por lado) - Driver dinámico 10 mm + armaduras balanceadas - Switches de afinación personalizable (4 niveles) -20 Hz – 40 kHz | 25–28 Ω | 108 dB  - Cable desmontable 0.75 mm con jack 3.5 mm"}, {"name": "IN EARS KZ-DQS", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 75000.0, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "IEM de entrada con gran relación calidad-precio -Driver dinámico 10 mm (sonido cálido y equilibrado - Graves profundos, medios naturales y agudos suaves - Diseño semiabierto con cubierta metálica - 20 Hz – 40 kHz | 14 Ω | 110 dB -Cable desmontable 2 pines"}, {"name": "IN EARS CCA FLA", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "IEM económicos con sonido personalizable (4 switches) - Doble driver dinámico 10 mm - 20 Hz – 40 kHz | ~30 Ω | 109–112 dB - Resina translúcida + placa metálica - Cable desmontable 0.78 mm (con/sin micrófono)"}, {"name": "IN EARS ZSN PRO X", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 90000.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "IEM híbridos con sonido en “V” (graves potentes) - Driver dinámico 10 mm + armadura balanceada - 7 Hz – 40 kHz | 25.9 Ω | 112 dB - Placa metálica + resina transparente- Cable desmontable 0.75 mm (opción con micrófono)"}, {"name": "IN EARS TRN TA2", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 310000.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "IEM híbridos (3 drivers por lado). Driver dinámico 8 mm + 2 armaduras balanceadas - 20 Hz – 20 kHz | 16 Ω | 107 dB - Resina + placa metálica - cable desmontable 2 pines 0.75 mm"}, {"name": "IN EARS TRN MT1", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "IN EARS TRN V30", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 150000.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "IEM híbridos (3 drivers por lado) - Driver dinámico 10 mm + 2 armaduras balanceadas - 20 Hz – 20 kHz | 20 Ω | 99 dB  -  Carcasa de resina translúcida  -  Cable desmontable 2 pines (opción con micrófono)"}, {"name": "IN EARS TRN ORCA", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "IEM con sonido en “V” y graves potentes - Driver dinámico 10 mm con diafragma LCP - Switches físicos con 6 modos de sonido 20 Hz – 20 kHz | 22–40 Ω | 108–112 dB Cable desmontable 0.75/0.78 mm (3.5 mm o USB-C)"}, {"name": "CABLE PARA IN EARS T1 QKZ AUDIO NEGRO", "sku": "21802011", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 50000.0, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE PARA IN EARS T1 QKZ AUDIO DORADO", "sku": "21802012", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 50000.0, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE PARA IN EARS T1 QKZ AUDIO AZUL", "sku": "21802013", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": 50000.0, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "LD SYSTEM U300 WIRELESS IN EARS", "sku": "507635", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "EXTRABASS HEADPHONES GEH-010 VERDE", "sku": "3252003", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "EXTRABASS HEADPHONES GEH-010 AZUL", "sku": "3252004", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "SHURE PSM PERSONAL MONITOR SYSTEM", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "POWER PLAY P2-BEHRINGER", "sku": "51401", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MIDAS DP48", "sku": "50608", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "POWER PLAY PM1 BEHRINGER", "sku": "51426", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "INTERFAZ DE AUDIO SCARLETT SOLO 4TH GEN", "sku": "500110", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "POWERPLAY P16 BEHRINGER", "sku": "", "cat": "AUDIFONOS Y IN EAR", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "SE V7 BLACK DYNAMIC VOCAL MICROPHONE", "sku": "507135", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 6, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Respuesta de Frecuencia:  40 Hz – 19 kHz  -  Patrón Polar: Supercardioide  -  Sensibilidad 2,0 mV / Pa (-54 dBV)  - Impedancia: 300 ohmios - Conector XLR macho de 3 patillas  - Tipo de Transductor: Dinamico  - Peso: 305 g (10,76 oz.)"}, {"name": "SE V7 X DYNAMIC INSTRUMENT MICROPHONE", "sku": "507131", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "SE V2 SWITCH DYNAMIC MULTI-PURPOSE MICROPHONE", "sku": "50717", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Respuesta de Frecuencia: 50 Hz a 16,000 Hz (16 kHz). -  Patrón Polar: Supercardioide  -  Sensibilidad  2.8 mV/Pa (-51 dBV).  - Impedancia eléctrica: 630 Ohmios.  -  Conector: XLR macho de 3 pines  - Tipo de Transductor: Dinámico  - Peso:  307 g (10.83 oz)."}, {"name": "SE V3", "sku": "507132", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "DYNAMIC VOCAL MICROPHONE  / Durante muchos años, hemos contado con ingenieros de sonido en directo que han utilizado nuestros micrófonos de estudio y filtros de reflexión en escenarios de todo el mundo con artistas como Linkin Park, Tom Petty & The Heartbreakers, Black Sabbath, entre muchos otros."}, {"name": "SE 7 MATCHED PAIR El sE7 es un micrófono de condensador de diafragma pequeño y back-electret de alta calidad pensado para una amplia gama de aplicaciones de estudio y sonido en directo, desde guitarras acústicas hasta pianos, baterías y mucho más.", "sku": "507137", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "Cápsula dinámica compatible con inalámbricos Shure", "sku": "507138", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Sonido profesional tipo V7  -  Respuesta 40 Hz – 19 kHz - Patrón cardioide  -  Construcción robusta  -  Incluye adaptador - SE V7 MC  DYNAMIC VOCAL MICROPHONE WIRELESS CAPSULE"}, {"name": "SE 7 SMALL DIAPHRAGM CONDENSER MICROPHONE", "sku": "507139", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "El sE7 es un micrófono de condensador de diafragma pequeño con electreto posterior de alta calidad, diseñado para una amplia gama de aplicaciones de estudio y sonido en directo, desde guitarras acústicas hasta pianos, baterías y mucho más."}, {"name": "VOCAL WIRELESS SYSTEM WMS40 MINI DUAL AKG HARMAN", "sku": "50756", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Respuesta de Frecuencia:  30 a 20000 Hz  - Patrón Polar: cardioide  - Sensibilidad 107 dB-A  - Impedancia: 1 - Atenuador: No  - Conector: Mini XLR-Plug  - Tipo de Transductor: Dinamico  -  Peso:1 Kg"}, {"name": "MICROFONO SHURE PGA48-LC", "sku": "50725", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MICROFONO SHURE PGA58-XLR", "sku": "50726", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MICROFONO SHURE PGA57-XLR", "sku": "5072603", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MICROFONO SHURE SM58-XLR", "sku": "507291", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MICROFONO SHURE SM57-LC", "sku": "507292", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Micrófono dinámico cardioide para instrumentos  -  Sonido limpio y preciso  -  Ideal para guitarra, bajo, batería y vientos  -  Respuesta 40 Hz – 15 kHz  - Sistema antigolpes neumático"}, {"name": "SL75C DYNAMIC CARDIOID MICROPHONE", "sku": "5075701", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "LD SYSTEMS U500 MALETIN", "sku": "507632", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MALETIN BC1200 BEHRINGER", "sku": "5075702", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "LD SYSTEM U300 DIVERSITY WIRELESS", "sku": "507634", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "BLX WIRELESS BODYPACK SYSTEM SHURE PEQUEÑO + CLV", "sku": "50730", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "BLX WIRELESS BODYPACK SYSTEM SHURE GRANDE + SM31", "sku": "50731", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "BLX WIRELESS RACK SYSTEM", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE ROXTONE PROFESSIONAL PS4M 4 CANALES HIGH PERFORMANCE", "sku": "5172906", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE ROXTONE PROFESSIONAL PS4F 4 CANALES HIGH PERFORMANCE", "sku": "5172907", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE ROXTONE SACC410L0060 6M HIGH PERFORMANCE", "sku": "5172908", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE ROXTONE SAYC130L0060 6M HIGH PERFORMANCE", "sku": "5172909", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE ROXTONE SGJJ110L0060 6M HIGH PERFORMANCE", "sku": "5172910", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE ROXTONE PACC170L0030 3M PREMIUN AUDIO CONNECTION", "sku": "5172912", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE ROXTONE SAMURAI RACC400L3-PB", "sku": "5172913", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 9, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CABLE ROXTONE SAMURAI RACC420L15-PB", "sku": "5172914", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RX3MDWP-BG", "sku": "5170404", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 7, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RJ3FD-2-B", "sku": "5170405", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 7, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RPAN240", "sku": "51706", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 20, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RJ3P-BG", "sku": "51724", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 12, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE", "sku": "51739", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 47, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "J2BG"}, {"name": "CONECTORES ROXTONE RPAN245", "sku": "51707", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 9, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RPAN220", "sku": "51705", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 6, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "RX3MD-NT"}, {"name": "CONECTORES ROXTONE RX3FDWP-BG", "sku": "5170403", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 8, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RJ45C5E-PH", "sku": "5170411", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 9, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RJ2PX-BG", "sku": "51723", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 9, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RA3J3MJF", "sku": "51726", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 36, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RMJ3PS-BG", "sku": "51725", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 15, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE RMJ3RPP-BG", "sku": "51704", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 14, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE LX3MH", "sku": "5061103", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 10, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CONECTORES ROXTONE MJ3BG", "sku": "517251", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "ATEM MINI PRO ISO", "sku": "50807", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "HDMI SPLITTER R0HS", "sku": "1120408", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "HDMI SPLITTER 1080P 3D", "sku": "1120404", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CAT SPLITTER BOX ROXTONE", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "CAJA DIRECTA KLARK TEKNIK DI22P PRO DI AV 2 DI22P", "sku": "2110103", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Caja directa estéreo -  Convertidor de señales no balanceadas a balanceadas -  Alta calidad de sonido  -  Construcción robusta para uso profesional"}, {"name": "Caja DI 10A KLARK TEKNIK directa activa", "sku": "5110102", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Caja directa activa  -  Conversión de señal de alta calidad  –  Electrónica avanzada para un sonido limpio  – Ideal para aplicaciones de sonido en vivo y estudio"}, {"name": "ULTRA-DI 400P BEHRINGER directa pasiva", "sku": "4590101", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "(1) Conector de 1/4 conector plug TS  -   (2) Conector de plug de 1/4 con opción flat/filtro (ideal para conectar el instrumento a su amplificador o backline del músico) - (3) Salida balanceada de conector XLR  -  (4) Switch que permite eliminar ruido de tierra en la entrada y salida  -  Construcción en metal  - Dimensiones: (6,6 x 12 x 3,5 cm) - Peso: 0,2 kg"}, {"name": "LARK M2 WIRELESS LAVALIER MICROPHONE", "sku": "5010301", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Sistema de Micrófono Inalámbrico 2.4 GHz -  Para periodismo móvil, creación de contenidos - 2 x transmisores con micrófonos omnidireccionales - Receptores de montaje en cámara y plug-ins - Distancia de transmisión de hasta 1000 pies  - Aplicación de control iOS/Android  - Garantía limitada de 1 año por Hollyland"}, {"name": "MICROFONO SE V7 WHITE", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": 495000.0, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Micrófono dinámico supercardioide para escenario  -  Sonido claro y natural, alta ganancia sin feedback  - Cápsula DMC7 con neodimio  - Construcción metálica robusta  -  Conector XLR   -  Respuesta: 40 Hz – 19 kHz"}, {"name": "MICROFONO SE V7 CHROME", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": 625900.0, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Micrófono dinámico vocal de mano supercardioide  -  Cápsula DMC7 con bobina de aluminio e imán de neodimio  -  Sonido natural, bajo ruido de manejo  -  Respuesta 40 Hz – 19 kHz / 300 Ω  -  Conector XLR  -  Cuerpo metálico con acabado cromado"}, {"name": "SHURE SV200", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 7, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Peso 250 g. -  Patrón polar cardiode -  Respuesta en frecuencia de 50Hz a 15kHz -  Conector XLR  -  Interruptor de apagado."}, {"name": "BLX WIRELESS COMBO SYSTEM", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Es el sistema de micrófono inalámbrico ideal para los que buscan la legendaria calidad de audio de Shure, una mayor duración de la batería y un rendimiento  confiable con una configuración sencilla. Ya sea en actuaciones en vivo como en discursos, el BLX ofrece a músicos y presentadores un sonido profesional con opciones de micrófono legendarias, incluyendo el SM58. Fabricado con precisión y disponible en diversas configuraciones como de mano, solapa, instrumento y de diadema, el BLX es la libertad inalámbrica simplificada."}, {"name": "MONITOR RW2090", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "es un sistema inalámbrico de monitoreo personal (In-Ear) de dos canales, ideal para músicos y bandas en vivo. Ofrece audio de alta definición sin latencia, alta estabilidad gracias a su señal UHF y un amplio rango de alcance en el escenario"}, {"name": "MINI SOUND METER UT353 UNI-T", "sku": "5160601", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 8, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Ruido (ponderación A) 30 ~ 130dB  -  Precisión ± 1,5 dB - Resolución 0,1 dB  -  Tasa de muestreo Rápido: 125 ms Lento: 1000 ms  -  Respuesta frecuente 31,5 Hz ~ 8 kHz  -  Indicación de sobrecarga OL  -  MÁXIMO MINIMO  -  Retención de datos  -  LCD luz de fondo  -  Apagado automático  -  Indicación de batería baja"}, {"name": "BOYA MINI WIRELESS MICROPHONE", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Sistema inalámbrico digital 2,4 GHz (2 transmisores + receptor USB-C) -  Patrón polar: Omnidireccional -  Respuesta en frecuencia: 20 Hz – 20 kHz -  Relación señal-ruido (SNR): ≥ 80 dB -  Máximo SPL: 120 dB  -  Alcance: hasta 100 m en línea de vista - Cancelación de ruido por IA de 3 niveles -   Modos de cambio de voz: 3 opciones -Autonomía transmisores: ~6 h por carga - Estuche cargador amplía duración total a ~30 h"}, {"name": "BOYA MAGIC TRANSFORMABLE WIRELESS MICROPHONE", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Sistema inalámbrico digital 2,4 GHz (kit 2 TX + 1 RX) con case multifunción  - 4-en-1: lavalier clip-on, handheld, desktop, on-camera -  Audio 48 kHz / 24-bit; limitador y safety track -  AI Noise Cancellation: Strong (-40 dB) / Light -  Respuesta en frecuencia 20 Hz–20 kHz; SNR ≥ 80 dB; SPL máx. ≈ 115 dB  -  Alcance inalámbrico ≈ 100 m en línea de vista -  Autonomía por TX ≈ 6 h; con estuche hasta ≈ 30 h -  Receptor USB-C (kits con Lightning/TRS según versión)"}, {"name": "HDTV EXTENDER 60M BY CAT", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "HDTV EXTENDER 60M 16062", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "es un dispositivo activo que transmite señales de audio y video en alta definición a través de un solo cable de red RJ45 (UTP Cat5e o Cat6). Permite superar la limitación de distancia de los cables HDMI convencionales sin perder calidad ni presentar latencia"}, {"name": "LX WIRELESS HANDHELD SYSTEM", "sku": "", "cat": "MICROFONOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MIXER UI24R", "sku": "50601", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Controle Ui24R desde navegadores iOS, Android, Windows, Mac OS y Linux sin instalar aplicaciones adicionales  -  Graba y mezcla con la calidez de 20 preamplificadores diseñados por Studer de calidad profesional.  - Compresión dbx y procesamiento de retardo y reverberación icónico de Lexicon  -  2 canales de modelado de amplificador de guitarra DigiTech  - Grabación multipista redundante y de doble ruta de las 24 entradas en una unidad USB y en un Mac/PC conectado - 24 entradas simultáneas  - Ecualizador paramétrico de 4 bandas, filtro de paso alto, compresor, de-esser y puerta de ruido en canales de entrada -  Analizador de frecuencia en tiempo real (RTA) en entradas y salidas - Compatible con la aplicación y el sistema Harman Connected PA para una configuración y control más sencillos"}, {"name": "MIXER DIGITAL MIDAS M32C", "sku": "50824", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "A través de red AES50 y snake digital se pueden conectar hasta 40 canales de entrada. -   25 buses de mezcla alineados en el tiempo y coherentes en fase. - A través de red AES50 y snake digital se pueden conectar hasta 96 salidas. -  Estructura de aluminio y acero de alto rendimiento. -  Procesamiento de señal digital de punto flotante de 40 bits. -  Montaje en rack de 1U para aplicaciones de sonido en vivo e instalaciones fijas."}, {"name": "MIXER DIGITAL SOUNDCRAFT UI 16", "sku": "5061201", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Tablet / PC / Smartphone Controlled Digital Mixer Wi-Fi integrado - Compatibilidad entre plataformas con dispositivos iOS, Android, Windows, Mac OS y Linux - Utilice hasta 10 dispositivos de control  - Preamplificadores de micrófono completamente remotos y controlados a distancia -Ecualizador paramétrico de 4 bandas,  -  Analizador de frecuencia en tiempo real (RTA) en entradas y salidas - 3 procesadores de efectos  - Mostrar / Recuerdo de instantánea con cajas fuertes de canales y bloqueo de seguridad - Reproducción y grabación de audio USB de 2 canales - Sistema de limitación de acceso protegido por contraseña - ID de sincronización ("}, {"name": "PRESONUS STUDIO NSB 16.8", "sku": "", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": 4772000.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "16 entradas XLR/TRS   - 8 salidas XLR  -  Preamps XMAX Clase A  -  Control remoto vía UC Surface  -  2 puertos AVB para expansión   -  Compatible con StudioLive Series III y EarMix"}, {"name": "MIDAS CONSOLA DIGITAL M32R", "sku": "50825", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": 11170000.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "40 canales  -  16 preamps MIDAS PRO  -  25 buses  -  Grabación multipista 32 canales  -  17 faders motorizados  -  48 kHz / Phantom 48V"}, {"name": "MIDAS CONSOLA DIGITAL M32", "sku": "50603", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": 15000000.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "32 entradas XLR MIDAS PRO  - 16 salidas XLR     -  6 AUX IN / 6 AUX OUT  -  6 matrices + 4 salidas de monitoreo  -  25 faders motorizados  -  25 buses de mezcla  -  Interfaz multitrack 32 ch  -  AES50 ×2 + ULTRANET + Ethernet para control"}, {"name": "MIDAS CONSOLA SD16", "sku": "50610", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": 2075000.0, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "Preamplificadores diseñados por Midas.   -   16 entradas híbridas (XLR/línea).  -  8 salidas XLR.  -  2 canales Hi-Z (alta impedancia).  -  4 salidas Ultranet para monitores P16-M.   -   Doble puerto AES50 para conexión en cascada. -  Conexión USB para actualizaciones.  -  Chasis metálico resistente a golpes."}, {"name": "MIDAS CONSOLA DL16/STAGE BOSE MEDUSA DL16", "sku": "50606", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": 3675000.0, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "16 entradas XLR / 8 salidas XLR  -Preamplificadores diseñados por MIDAS  -  Doble puerto AES50  -  2 salidas ópticas ADAT  - Salida Ultranet (P16-M)  -  USB para actualizaciones  -  Entrada/Salida MIDI  -  Salida audífonos ¼”  -  Chasis metálico para rack"}, {"name": "MIDAS CONSOLA S32/BEHRINGE S32 STAGE BOSE", "sku": "50605", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Preamplificadores diseñados por midas. - 32 entradas XLR (Canon). -  16 salidas XLR (Canon). - Botón para Mute general. - Conexión USB para actualizaciones. -  2 Salida Ópticas ADAT. - 2 Salidas AES/EBU. - Una salida Ultranet para sistema de monitores p16-m o Parlantes y Cabinas. - Puerto doble AES50 para múltiples unidades en cascada. - Salida y Entrada MIDI. - Indicador Led Phantom Power. -  Chasis metálico."}, {"name": "CONSOLA DIGITAL SOUNDCRAFT UI 16", "sku": "5061201", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Mezclador digital controlado desde tablet, PC o smartphone.  -  Wi-Fi integrado y conexión por Ethernet.  - Compatible con iOS, Android, Windows, macOS y Linux.  -  Control simultáneo de hasta 10 dispositivos. - Procesamiento profesional HARMAN (dbx®, DigiTech® y Lexicon®). -  16 canales con preamplificadores de micrófono de alta calidad. -  EQ paramétrico de 4 bandas, compresor, gate y de-esser por canal. - Ecualizador gráfico de 31 bandas y RTA en entradas y salidas. -  Efectos Lexicon® integrados: Reverb, Delay y Chorus. -  Grabación y reproducción de audio USB de 2 canales."}, {"name": "WING BEHRINGE 48 CANALES BK", "sku": "50805", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "40 entradas estereo, 8 auxilares estéreo, locales 8 XLR/TRS 8 AUX IN TRS.  - Preamplificadores Midas Pro.-  16 buses auxiliares estero, 8 matrices estéreo, 4 main estéreo. -  8 salidas locales XLR. -  3 puertos AES50  -   Wi Fi incorporado para conectarse a dispositivos de control. -  Interface de 48 X 48 48kHz -24 bit.  -  Pantalla táctil 10.1”. -  2 salidas de audífonos en TRS estéreo. -  100-240 VAC (50/60 Hz) - Peso 24 Kg."}, {"name": "PRESONUS EARMIX 16M", "sku": "5141101", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Mezclador personal por red AVB para las mixers digitales de Presonus StudioLive SSeries hace que sea fácil para cualquier intérprete mezclar de forma intuitiva una mezcla de monitor rápidamente. Solo lleva unos segundos seleccionar cualquiera de los 16 canales, optimizar su volumen y colocarlo en el campo estéreo. Una vez que haya creado su mezcla perfecta, puede modificar el sonido con EQ y limitación, disponible en cada canal, así como en el bus de mezcla estéreo. Lo mejor de todo es que puede guardar hasta 16 escenas de mezcla preestablecidas en el EarMix 16M para que estén listas para recuperación instantánea, lo que hace que los eventos que ocurren regularmente sean fáciles de configurar."}, {"name": "DF1000 KLARK TEKNIK", "sku": "", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "", "image": null, "descripcion": "FEEDBACK  /  Detección y supresión automática de feedback – 24 filtros DSP para máxima precisión – Control manual y automático – Pantalla LED para visualización de estado – Entradas y salidas balanceadas XLR – Construcción robusta para uso en giras"}, {"name": "BEHRINGER FLOW 8", "sku": "", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "2 entradas xlr -2 XLR/TRS – 4 entradas trs. -  2 salidas XLR para Master-  2 salidas TRS para auxiliares. - Interface usb de 8 canales - Bluetooth audio - 2 retornos de efecto. -  App para control, flowmix"}, {"name": "BEHRINGER XAIR XR18", "sku": "", "cat": "CONSOLAS - MIXER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 8, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "16 entradas xlr/trs – 2 entradas trs.  -  Preamplificadores hechos por Midas.  - 2 salidas XLR para Master.  - 6 salidas XLR para auxiliares.  - Ultranet para conectarse a monitoreo personal P16.   - Wi Fi incorporado para conectarse a dispositivos de control.  - Interface de 18 X 18 44.1/48kHz -24 bit.   -  4 retornos de efecto.   - Peso 3.9 Kg."}, {"name": "TRIPOD CAMARA ST-11", "sku": "50119", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "TRIPOD TABLET ST-12", "sku": "|", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "COMBO TECALDO + MOUSE LOGITECH", "sku": "212", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "UPS INTERACTIVA WATTANA ST-U-1200", "sku": "25405", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "REGULADOR ELECTRONICO DE WOLTAJE EV3000", "sku": "", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "REGULADOR AUTOMATICO DE VOLTAJE UNITEC", "sku": "22202", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "STARTEC REGULADOR AUTOMATICO", "sku": "22203", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "IMPRESORA TERMICA DE RECIBOS SAT Q22UB", "sku": "1120105", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "LECTOR CODIGO DE BARRAS 88S-50BTUB-U01", "sku": "21003", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "LECTOR DE CODIGO DE BARRAS SKU10499", "sku": "21004", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "LENTE DE CAMARA CANON EFS18-135MM", "sku": "501241", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "STARTEC HUB USB 2.0 4 PUERTOS", "sku": "", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MULTIHUB HU-02 IGOMA", "sku": "1120303", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "AUDIO ADAPTER TIPO C AD-01 IGOMA", "sku": "1251509", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "PROFESSIONAL WIRELESS MICROPHONE K-10 IGOMA", "sku": "50749", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "HDMI VGA CABLE ADAPTER ARGOM", "sku": "51730", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "MOVIL PHONE DESKTOP HOLDER MH-01 IGOMA", "sku": "130115", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "TRAVEL HOLDER TH03 IGOMA", "sku": "130112", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "SMARTPHONE HOLDER PA115 ROXTONE", "sku": "5030301", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "TABLET HOLDER SUPERFIX", "sku": "", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 10, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "Compatibilidad: Ajustable para dispositivos de 7 a 11 pulgadas, lo que incluye la mayoría de los modelos de iPad, iPad Mini, iPad Air, y Galaxy Tab.Montaje versátil: Equipado con una abrazadera universal diseñada para fijarse a tubos de hasta 35 mm de diámetro, ideal para parales de micrófono estándar y soportes de instrumentos."}, {"name": "SOPORTE PARA CELULAR 1 HORA", "sku": "5030303", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "WIFI ROUTER AC1200 TP-LINK", "sku": "25408", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "WIFI ROUTER AC1200 D-LINK", "sku": "25502", "cat": "ACCESORIOS", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "SUBWOOFER LD SYSTEM IC0A SUB 15A", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "1600 W Pico / 400 W RMS  -  131 dB SPL Máx.  - - Amplificador Clase D - Respuesta de frecuencia desde 36 Hz - 2 Entradas Combo XLR -  2 Salidas XLR - Protección inteligente (sobrecarga, sobrecalentamiento y sobretensión)"}, {"name": "CABINA ACTIVA BI-AMPLIFICADA ST-310 BT", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": 871000.0, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "Cabina activa - 300 W RMS - Altavoz 10” + driver 1.35” - Respuesta en frecuencia 55 Hz – 20 kHz - Dispersión 90° × 70° - Conexiones - XLR y RCA - Peso 11,5 kg (13,5 kg con empaque)"}, {"name": "CABINA ARREGLO YAMAKI LINEAL ARRAY AL-2118SW-E", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "18\" Autoamplificado  - 1200 W RMS    -133 dB SPL Máx.  - 35–120 Hz    -Uso profesional para exteriores   -  Gabinete de abedul de alta resistencia"}, {"name": "CABINA ARREGLO YAMAKI LINEAL ARRAY AL-2210-E", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 11, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "Rango completo con guía de onda  -  2×10” + 2×1.75” Neodimio   -   Potencia 1200 W RMS | 130 dB SPL máx.    -    Respuesta en frecuencia: 50 Hz – 20 kHz   -   Cobertura: 100° H × 10° V   -  Arreglos hasta 12 cajas (0°–10° en pasos de 1°)  -  Uso móvil y exteriores"}, {"name": "CABINA ARREGLO YAMAKI LINEAL AL-1028", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": ""}, {"name": "BOSE F1 CABINA MODEL 812 1000 WATTS", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "Sistema activo biamplificado   -  Arreglo flexible con 4 patrones de cobertura   -  1.000 W altavoz + 1.000 W subwoofer   -  Altavoz 12” + subwoofer 2×10”   -   SPL máx. 132 dB   -  Graves extendidos hasta 34 Hz  -  Soporte integrado ajustable   -   Ideal para eventos, DJs y sonido en vivo"}, {"name": "CABINA ACTIVA BETA THREE VX12a", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": 1600000.0, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "Cabina activa recargable de 3 vías  -  Woofer 8” + driver 1”   -  200 W RMS (400 W musical / 800 W pico)   -  Respuesta 60 Hz – 20 kHz  -  3 entradas XLR, 1 línea y salida RCA  -  Indicadores LED  -   Diseño ligero y compacto (8,8 kg)"}, {"name": "CABINA ACTIVA BETA THREE VX15a", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "Cabina activa 2 vías, woofer 15” + driver 1”  - 300 W RMS (1200 W pico), clase D  -  Respuesta 45 Hz – 16 kHz / SPL 124 dB  - Entrada XLR   -   Bluetooth / salida XLR  -  Gabinete ABS – Peso 24 kg"}, {"name": "CABINA ACTIVA BETA THREE N15 A I", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": 1955000.0, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "Cabina activa 2 vías (15” + driver 1.75”)  -  300 W RMS (clase H) / SPL hasta 126 dB  -  Respuesta 50 Hz – 18 kHz  -  XLR in/out, Mic/Línea conmutable  -   Controles de volumen, graves y agudos  -   Gabinete ABS / 110–220 V"}, {"name": "SUB BAJO ACTIVO SM-1500 YAMAKI", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "Cabina activa 2 vías (15” + driver 1.75”)  -  300 W RMS (clase H) / SPL hasta 126 dB  -  Respuesta 50 Hz – 18 kHz  -  XLR in/out, Mic/Línea conmutable  -   Controles de volumen, graves y agudos  -   Gabinete ABS / 110–220 V"}, {"name": "BASE RACK MAXLIN", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": ""}, {"name": "BOSE F1 SUBWOOFER 1000 WATTS", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": ""}, {"name": "MONITOR DE ESCENARIO PROEL WD10AV2", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": ""}, {"name": "CABINA ACTIVA YAMAKI SS-715", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 9, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": "Cabina activa bi-amplificada 700 W RMS / 1200 W musicales  -  Parlante 15″ + driver 1.35″ de titanio  -  Reproductor USB/SD y Bluetooth Incluye control remoto   -   2 entradas XLR (línea / línea-mic) y RCA   -   Salida XLR de señal  -  Ecualizador general de bajos y agudos"}, {"name": "LD SYSTEMS ANNY 10", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 3 (Garage)", "image": null, "descripcion": ""}, {"name": "CABINA PRODJ PSA-15A", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "CABINA ACTIVA YAMAKI ST-310 B", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "CABINA ACTIVA YAMAKI SS715", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "CABINA JBL EON ONE COMPAC", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "UPS INTERACTIVA WATTANA ST-U-850", "sku": "25402", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "N8A CABINA BETA THREE RECARGABLE PORTATIL", "sku": "50508", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "CABINA YAMAKI AL2210", "sku": "51415", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "F1 SUBWOOFER BOSE", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "QSC KLA181", "sku": "50532", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "CABINA PROEL PSA 15A", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "CABINA PRODJ P1 GO", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "PROEL FORCE", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "CABINA ELECTROVOICE ZLX G2 12\"", "sku": "50518", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "MONITORES LD SYSTEMS ICOA 12\"", "sku": "", "cat": "CABINAS - SUBWOFWER", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "PIANO MODX M6", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "sintetizador y workstation profesional de 61 teclas (acción semicontrapesada FSB con aftertouch), diseñado para directo y estudio. Pesa solo 6.6 kg y destaca por incorporar tres motores de sonido de la gama alta MONTAGE M: AWM2, FM-X y el motor analógico AN-X"}, {"name": "PIANO MODX M8", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "El Yamaha MODX M8 es un sintetizador y estación de trabajo profesional de 88 teclas contrapesadas con acción de martillo graduado y Initial Touch. Hereda el ADN del buque insignia MONTAGE M, incluyendo tres potentes motores de sonido (AWM2, FM-X y AN-X) y un diseño liviano ideal para escenarios."}, {"name": "CAJON PERUANO", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "PIANO YAMAHA PSR", "sku": "50421", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "E473  / El Yamaha PSR-E473 es un teclado portátil de 61 teclas sensibles al tacto. Equipado con un motor de audio mejorado, ofrece 820 voces de alta calidad, 290 estilos de acompañamiento y una polifonía de 128 voces."}, {"name": "PIANO YAMAHA 383", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": "es un teclado portátil de 61 teclas sensibles a la pulsación, ideal para principiantes y músicos en desarrollo. Ofrece 650 voces de alta calidad, 260 estilos de acompañamiento, y un sistema de aprendizaje interactivo. Además, su puerto USB transmite audio y MIDI."}, {"name": "BATERIA CARLSBRO PRO 45M", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "BATERIA MAPEX", "sku": "5131602", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "PLATILLOS ZILDJIAN KUZTOM DARK CYMBAL PACK", "sku": "5131510", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "BAQUETAS POR PAR AMERICAN CLASSIC", "sku": "50203", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "BAQUETAS POR PAR AMERICAN CLASSIC", "sku": "50202", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 5, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": "TERRA"}, {"name": "PASSIVE DI BOX PALMER PAN 01", "sku": "5110105", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 18, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "BASE PARA COLGAR CABINA LD SYSTEMS ICOA 12\"", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "BASE MICROFONO SUPER FIX SMS1101BP01", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "BASE MICROFONO SUPER FIX XMS402BP01", "sku": "5030901", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 12, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "BASE MICROFONO SUPER FIX SMS105BP01", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 6, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "BASE PIANO PROLINE", "sku": "5030407", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "BASES PARA CABINA PROPHONI SG-005", "sku": "5030703", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "BASE PARA CABINA SPEAKER STAND TYS-13Y PROPHONIC", "sku": "5030206", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 4, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "BASE CABINA PROPHONE TYS-502M", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 2 (Mesanini)", "image": null, "descripcion": ""}, {"name": "GGS 01 WMB GRAVITY NECK HUG", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 2, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "ADAPTADOR YAMAHA PA-300C", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "SUSTAIN PEDAL PP-F90", "sku": "504081", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 43, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "SUSTAIN PEDAL I2468", "sku": "504082", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 3, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "SUSTAIN PEDAL PROLINE", "sku": "504083", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}, {"name": "ADAPTADOR YAMAHA PA-3C", "sku": "", "cat": "INSTRUMENTOS Y BASES", "provider": "", "cost": null, "sale": null, "meli": null, "redes": null, "stock": 1, "warehouse": "Bodega 1 (3er piso)", "image": null, "descripcion": ""}];
  const STORAGE_KEY = 'inventario:productos_v3';
  const STORAGE_KEY_WAREHOUSES = 'inventario:bodegas';
  const STORAGE_KEY_CATEGORIES = 'inventario:categorias';
  const STORAGE_KEY_HISTORY = 'inventario:historial';
  const STORAGE_KEY_SEED_FLAG = 'inventario:seed_csv_v1';
  const STORAGE_KEY_SEED_XLSX_FLAG = 'inventario:seed_xlsx_v7';
  const uid = () => 'p_' + Math.random().toString(36).slice(2, 10);
  let products = SEED_DATA.map((item, i) => ({ id: 'sp_' + i, ...item }));
  let history = [];
  const USERS = {
    administrativo: { password: 'administrativo2026', label: 'Administrativo' },
    comercial: { password: 'Comercial2026', label: 'Comercial' }
  };
  const COMERCIALES = [
    { id: 'ezequiel', name: 'Ezequiel Camargo', phone: '313 292 5034', email: 'ezequiel.camargo@f1toppoint.com' },
    { id: 'esteban',  name: 'Esteban Díaz',     phone: '322 429 7239', email: 'esteban.diaz@f1toppoint.com' },
    { id: 'diana',    name: 'Diana Rincón',      phone: '315 402 8434', email: 'diana.rincon@f1toppoint.com' },
    { id: 'david',    name: 'David Pérez',       phone: '300 487 3651', email: 'david.perez@f1toppoint.com' }
  ];
  let currentUser = null;
  let dataLoaded = false;
  let selectedIds = new Set();
  let quoteQuantities = {};
  let lastListIds = [];
  let historySearch = '';
  let editingId = null;
  let pendingDeleteId = null;
  let sortKey = null;
  let sortDir = 1;
  let searchTerm = '';
  let catFilterVal = '';
  let whFilterVal = '';
  let currentImageData = null;
  let warehouses = [];
  let categories = [];

  const fmt = new Intl.NumberFormat('es-CO', { style: 'currency', currency: 'COP', maximumFractionDigits: 0 });
  const fmtNum = (n) => fmt.format(Math.round(n || 0));
  const hasPrice = (v) => v !== null && v !== undefined && v !== '';
  const fmtPrice = (v) => hasPrice(v) ? fmtNum(v) : 'Pendiente';

  document.getElementById('inv-datestamp').textContent = new Date().toLocaleDateString('es-CO', { day: 'numeric', month: 'long', year: 'numeric' });

  // ===== CONFIGURACIÓN SUPABASE (nube compartida entre equipos) =====
  const SUPABASE_URL = 'https://iwrwztcjryxjqkyawvwz.supabase.co';
  const SUPABASE_KEY = 'sb_publishable_hV_mhNSB9hJsdAWFyZErag_GIKov0ja';
  let sb = null;
  try {
    if (window.supabase && window.supabase.createClient) {
      sb = window.supabase.createClient(SUPABASE_URL, SUPABASE_KEY);
    }
  } catch (e) { console.error('No se pudo iniciar Supabase', e); }
  const hasSupabase = !!sb;

  const hasCloudStorage = typeof window.storage !== 'undefined' && !!window.storage;
  let storageMode = hasSupabase ? 'supabase' : 'memory';
  let memoryStore = {};

  // --- IndexedDB para imágenes (respaldo local / caché) ---
  let imgDB = null;
  function openImageDB() {
    return new Promise((resolve) => {
      if (imgDB) { resolve(imgDB); return; }
      if (typeof indexedDB === 'undefined') { resolve(null); return; }
      try {
        const req = indexedDB.open('inventario_imagenes', 1);
        req.onupgradeneeded = (e) => {
          const db = e.target.result;
          if (!db.objectStoreNames.contains('imagenes')) db.createObjectStore('imagenes');
        };
        req.onsuccess = (e) => { imgDB = e.target.result; resolve(imgDB); };
        req.onerror = () => resolve(null);
      } catch (e) { resolve(null); }
    });
  }

  // Convierte dataURL a Blob para subir a Supabase Storage
  function dataUrlToBlob(dataUrl) {
    const parts = dataUrl.split(',');
    const mime = (parts[0].match(/:(.*?);/) || [null, 'image/jpeg'])[1];
    const bin = atob(parts[1]);
    const arr = new Uint8Array(bin.length);
    for (let i = 0; i < bin.length; i++) arr[i] = bin.charCodeAt(i);
    return new Blob([arr], { type: mime });
  }

  async function imgDBSet(key, value) {
    // key = 'inventario:img:sp_5'  → nombre de archivo en el bucket
    const fileName = key.replace('inventario:img:', '') + '.jpg';
    // Guardar en Supabase Storage (compartido)
    if (hasSupabase) {
      try {
        const blob = dataUrlToBlob(value);
        const { error } = await sb.storage.from('imagenes').upload(fileName, blob, { upsert: true, contentType: 'image/jpeg' });
        if (error) console.warn('Supabase storage:', error.message);
      } catch (e) { console.warn('Error subiendo imagen', e); }
    }
    // Guardar también en IndexedDB como caché local (para velocidad y offline)
    const db = await openImageDB();
    if (db) {
      try {
        const tx = db.transaction('imagenes', 'readwrite');
        tx.objectStore('imagenes').put(value, key);
      } catch (e) { /* noop */ }
    }
    return true;
  }

  async function imgDBGet(key) {
    // Primero intentar caché local (rápido)
    const db = await openImageDB();
    if (db) {
      const cached = await new Promise((resolve) => {
        try {
          const tx = db.transaction('imagenes', 'readonly');
          const req = tx.objectStore('imagenes').get(key);
          req.onsuccess = () => resolve(req.result || null);
          req.onerror = () => resolve(null);
        } catch (e) { resolve(null); }
      });
      if (cached) return cached;
    }
    // Si no está en caché, traer de Supabase Storage
    if (hasSupabase) {
      try {
        const fileName = key.replace('inventario:img:', '') + '.jpg';
        const { data } = sb.storage.from('imagenes').getPublicUrl(fileName);
        if (data && data.publicUrl) {
          // Verificar que exista descargándola
          const resp = await fetch(data.publicUrl + '?t=' + Date.now());
          if (resp.ok) {
            const blob = await resp.blob();
            const dataUrl = await new Promise((res) => {
              const r = new FileReader();
              r.onload = () => res(r.result);
              r.onerror = () => res(null);
              r.readAsDataURL(blob);
            });
            // Guardar en caché local
            if (dataUrl && db) {
              try {
                const tx = db.transaction('imagenes', 'readwrite');
                tx.objectStore('imagenes').put(dataUrl, key);
              } catch (e) { /* noop */ }
            }
            return dataUrl;
          }
        }
      } catch (e) { /* imagen no encontrada */ }
    }
    return null;
  }

  async function imgDBDel(key) {
    const fileName = key.replace('inventario:img:', '') + '.jpg';
    if (hasSupabase) {
      try { await sb.storage.from('imagenes').remove([fileName]); } catch (e) { /* noop */ }
    }
    const db = await openImageDB();
    if (db) {
      try {
        const tx = db.transaction('imagenes', 'readwrite');
        tx.objectStore('imagenes').delete(key);
      } catch (e) { /* noop */ }
    }
  }

  async function storageGet(key) {
    if (hasSupabase) {
      try {
        const { data, error } = await sb.from('app_estado').select('valor').eq('clave', key).maybeSingle();
        if (!error && data && data.valor !== null && data.valor !== undefined) {
          return typeof data.valor === 'string' ? data.valor : JSON.stringify(data.valor);
        }
        return null;
      } catch (e) { return null; }
    }
    if (hasCloudStorage) {
      try {
        const r = await window.storage.get(key, false);
        return r ? r.value : null;
      } catch (e) { return null; }
    }
    try {
      if (typeof localStorage !== 'undefined') return localStorage.getItem(key);
    } catch (e) { /* localStorage bloqueado */ }
    return Object.prototype.hasOwnProperty.call(memoryStore, key) ? memoryStore[key] : null;
  }

  async function storageSet(key, value) {
    if (hasSupabase) {
      try {
        let parsed;
        try { parsed = JSON.parse(value); } catch (e) { parsed = value; }
        const { error } = await sb.from('app_estado').upsert({ clave: key, valor: parsed, updated_at: new Date().toISOString() });
        return !error;
      } catch (e) { return false; }
    }
    if (hasCloudStorage) {
      try { await window.storage.set(key, value, false); return true; }
      catch (e) { return false; }
    }
    try {
      if (typeof localStorage !== 'undefined') { localStorage.setItem(key, value); return true; }
    } catch (e) { /* bloqueado o lleno */ }
    memoryStore[key] = value;
    return true;
  }

  async function storageDel(key) {
    if (hasSupabase) {
      try { await sb.from('app_estado').delete().eq('clave', key); } catch (e) { /* noop */ }
      return;
    }
    if (hasCloudStorage) {
      try { await window.storage.delete(key, false); } catch (e) { /* noop */ }
      return;
    }
    try {
      if (typeof localStorage !== 'undefined') { localStorage.removeItem(key); return; }
    } catch (e) { /* noop */ }
    delete memoryStore[key];
  }

  function detectStorageMode() {
    if (hasSupabase) return 'supabase';
    if (hasCloudStorage) return 'cloud';
    try {
      if (typeof localStorage !== 'undefined') {
        const testKey = '__inv_test__';
        localStorage.setItem(testKey, '1');
        localStorage.removeItem(testKey);
        return 'local';
      }
    } catch (e) { /* no disponible */ }
    return 'memory';
  }

  function renderStorageBanner() {
    const el = document.getElementById('storage-banner');
    if (storageMode === 'supabase' || storageMode === 'cloud') {
      el.style.display = 'none';
      return;
    }
    el.style.display = 'block';
    if (storageMode === 'local') {
      el.className = 'storage-banner info';
      el.textContent = 'Los cambios se guardan en este navegador. Si abres el archivo desde otro computador o navegador, no los verás ahí.';
    } else {
      el.className = 'storage-banner warning';
      el.textContent = '⚠️ Tu navegador no permite guardar datos al abrir este archivo directamente (file://). Los cambios se perderán al cerrar o recargar la página. Para que se guarden, usa la herramienta desde el chat de Claude.';
    }
  }

  function escapeHtml(s) {
    return String(s == null ? '' : s).replace(/[&<>"']/g, c => ({ '&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;' }[c]));
  }

  async function load() {
    storageMode = detectStorageMode();
    renderStorageBanner();
    // Mostrar productos del seed INMEDIATAMENTE
    render();

    // Recuperar datos guardados PRIMERO (y esperar) para fijar el array de productos
    let hadStored = false;
    try {
      const res = await storageGet(STORAGE_KEY);
      if (res) {
        const parsed = JSON.parse(res);
        if (Array.isArray(parsed) && parsed.length > 0) {
          products = parsed;
          hadStored = true;
        }
      }
    } catch (e) {}
    try { const r = await storageGet(STORAGE_KEY_WAREHOUSES); if (r) warehouses = JSON.parse(r); } catch(e) {}
    try { const r = await storageGet(STORAGE_KEY_CATEGORIES); if (r) categories = JSON.parse(r); } catch(e) {}
    try { const r = await storageGet(STORAGE_KEY_HISTORY); if (r) history = JSON.parse(r); } catch(e) {}

    // Si la nube estaba vacía (primera vez), subir el seed inicial
    if (!hadStored && (hasSupabase || hasCloudStorage)) {
      await persist();
    }

    render(); // Renderizar con los datos definitivos ANTES de cargar imágenes

    // Ahora sí, cargar todas las imágenes sobre el array ya fijo
    await loadImagesInBackground();
  }

  async function loadImagesInBackground() {
    let loaded = 0;
    for (const p of products) {
      if (!p.image) {
        try {
          let img = await imgDBGet('inventario:img:' + p.id);
          if (!img) img = await storageGet('inventario:img:' + p.id);
          if (img) {
            p.image = img;
            loaded++;
            // Renderizar progresivamente cada 5 imágenes para que se vean apareciendo
            if (loaded % 5 === 0) render();
          }
        } catch(e) {}
      }
    }
    render(); // Render final garantizado
  }

  async function persistWarehouses() {
    try {
      await storageSet(STORAGE_KEY_WAREHOUSES, JSON.stringify(warehouses));
    } catch (e) {
      console.error('No se pudo guardar la lista de bodegas', e);
    }
  }

  async function persistHistory() {
    try {
      await storageSet(STORAGE_KEY_HISTORY, JSON.stringify(history));
    } catch (e) {
      console.error('No se pudo guardar el historial', e);
    }
  }

  const HIST_FIELDS = {
    name: 'Nombre', cat: 'Categoría', sku: 'SKU', provider: 'Proveedor',
    warehouse: 'Bodega', cost: 'Precio compra', sale: 'Precio venta',
    meli: 'Mercado Libre', redes: 'Redes / Shopify', stock: 'Stock',
    descripcion: 'Descripción', image: 'Foto'
  };
  const histVal = (v) => (v === null || v === undefined || v === '') ? '—' : String(v);

  function diffProduct(before, after) {
    const changes = [];
    Object.keys(HIST_FIELDS).forEach(key => {
      if (key === 'image') {
        const b = !!before.image, a = !!after.image;
        if (b !== a) changes.push({ field: HIST_FIELDS[key], before: b ? 'con foto' : 'sin foto', after: a ? 'con foto' : 'sin foto' });
        return;
      }
      const bRaw = before[key], aRaw = after[key];
      const b = histVal(key === 'descripcion' ? (bRaw||'').slice(0,60) : bRaw);
      const a = histVal(key === 'descripcion' ? (aRaw||'').slice(0,60) : aRaw);
      if (b !== a) changes.push({ field: HIST_FIELDS[key], before: b, after: a });
    });
    return changes;
  }

  function logHistory(action, name, changes) {
    history.unshift({ id: uid(), ts: new Date().toISOString(), action, name, user: currentUserLabel(), changes: changes || [] });
    if (history.length > 500) history = history.slice(0, 500);
    persistHistory();
  }

  function renderHistory() {
    const list = document.getElementById('history-list');
    const term = historySearch.trim().toLowerCase();
    const filtered = term ? history.filter(h => h.name.toLowerCase().includes(term)) : history;
    document.getElementById('history-count').textContent = `${filtered.length} de ${history.length} movimientos`;
    if (filtered.length === 0) {
      list.innerHTML = `<div class="hist-empty">${history.length === 0 ? 'Todavía no hay movimientos registrados.' : 'Nada coincide con tu búsqueda.'}</div>`;
      return;
    }
    const labels = { create: 'Creado', update: 'Actualizado', delete: 'Eliminado' };
    list.innerHTML = filtered.map(h => {
      const d = new Date(h.ts);
      const when = d.toLocaleDateString('es-CO', { day: '2-digit', month: 'short', year: 'numeric' }) + ' · ' + d.toLocaleTimeString('es-CO', { hour: '2-digit', minute: '2-digit' });
      const changesHtml = h.changes && h.changes.length
        ? `<ul class="hist-changes">${h.changes.map(c => `<li><b>${escapeHtml(c.field)}:</b> ${escapeHtml(c.before)} → ${escapeHtml(c.after)}</li>`).join('')}</ul>`
        : '';
      return `
        <div class="hist-entry">
          <div class="hist-top">
            <span class="hist-badge ${h.action}">${labels[h.action] || h.action}</span>
            <span class="hist-name">${escapeHtml(h.name)}</span>
            <span class="hist-time">${when}</span>
          </div>
          <div class="hist-user">${escapeHtml(h.user || '—')}</div>
          ${changesHtml}
        </div>`;
    }).join('');
  }

  document.getElementById('btn-history').addEventListener('click', () => {
    renderHistory();
    document.getElementById('history-overlay').classList.add('open');
  });
  document.getElementById('history-close').addEventListener('click', () => {
    document.getElementById('history-overlay').classList.remove('open');
  });
  document.getElementById('history-overlay').addEventListener('click', (e) => {
    if (e.target.id === 'history-overlay') document.getElementById('history-overlay').classList.remove('open');
  });
  document.getElementById('history-search').addEventListener('input', (e) => {
    historySearch = e.target.value;
    renderHistory();
  });

  // --- Gestor de categorías ---
  function renderCategoriesList() {
    const listEl = document.getElementById('categories-list');
    const cats = uniqueCategories();
    if (cats.length === 0) {
      listEl.innerHTML = `<div class="hist-empty">Aún no hay categorías. Agrega una arriba.</div>`;
      return;
    }
    listEl.innerHTML = cats.map(cat => {
      const count = products.filter(p => (p.cat || '').trim() === cat).length;
      const inList = categories.some(c => c.trim() === cat);
      return `
        <div class="cat-manage-row">
          <div>
            <span class="cat-manage-name">${escapeHtml(cat)}</span>
            <span class="cat-manage-count">${count} producto${count === 1 ? '' : 's'}</span>
          </div>
          ${count === 0 && inList
            ? `<button class="cat-manage-del" data-cat="${escapeHtml(cat)}" title="Eliminar categoría vacía">Eliminar</button>`
            : `<span class="cat-manage-lock" title="No se puede eliminar: tiene productos asignados">En uso</span>`}
        </div>`;
    }).join('');

    listEl.querySelectorAll('.cat-manage-del').forEach(btn => {
      btn.addEventListener('click', async () => {
        const cat = btn.getAttribute('data-cat');
        categories = categories.filter(c => c.trim() !== cat);
        await persistCategories();
        renderCategoriesList();
        refreshCategoryUI();
        showToast('Categoría eliminada');
      });
    });
  }

  async function addCategory() {
    const input = document.getElementById('new-category-input');
    const name = input.value.trim();
    if (!name) { showToast('Escribe un nombre de categoría'); return; }
    const exists = uniqueCategories().some(c => c.toLowerCase() === name.toLowerCase());
    if (exists) { showToast('Esa categoría ya existe'); input.value = ''; return; }
    categories.push(name);
    await persistCategories();
    input.value = '';
    renderCategoriesList();
    refreshCategoryUI();
    showToast('Categoría agregada');
  }

  document.getElementById('btn-categories').addEventListener('click', () => {
    renderCategoriesList();
    document.getElementById('categories-overlay').classList.add('open');
    setTimeout(() => document.getElementById('new-category-input').focus(), 50);
  });
  document.getElementById('categories-close').addEventListener('click', () => {
    document.getElementById('categories-overlay').classList.remove('open');
  });
  document.getElementById('categories-overlay').addEventListener('click', (e) => {
    if (e.target.id === 'categories-overlay') document.getElementById('categories-overlay').classList.remove('open');
  });
  document.getElementById('add-category-btn').addEventListener('click', addCategory);
  document.getElementById('new-category-input').addEventListener('keydown', (e) => {
    if (e.key === 'Enter') { e.preventDefault(); addCategory(); }
  });

  // --- Cotización ---
  function updateSelectAllCheckbox() {
    const cb = document.getElementById('select-all-checkbox');
    if (cb) cb.checked = lastListIds.length > 0 && lastListIds.every(id => selectedIds.has(id));
  }

  function updateQuoteBar() {
    const bar = document.getElementById('quote-bar');
    const n = selectedIds.size;
    if (n === 0) { bar.style.display = 'none'; return; }
    bar.style.display = 'flex';
    document.getElementById('quote-bar-count').textContent = n === 1 ? '1 producto seleccionado' : `${n} productos seleccionados`;
  }

  function quoteSelectedProducts() {
    return products.filter(p => selectedIds.has(p.id));
  }

  function quoteLineTotal(p) {
    const qty = Math.max(1, parseInt(quoteQuantities[p.id]) || 1);
    const unit = hasPrice(p.sale) ? Number(p.sale) : 0;
    return qty * unit;
  }

  function renderQuoteModal() {
    const list = document.getElementById('quote-list');
    const items = quoteSelectedProducts();
    document.getElementById('quote-item-count').textContent = items.length === 1 ? '1 producto' : `${items.length} productos`;

    const sel = document.getElementById('quote-comercial');
    const currentVal = sel.value;
    sel.innerHTML = '<option value="">— Selecciona —</option>' + COMERCIALES.map(c =>
      `<option value="${c.id}" ${c.id === currentVal ? 'selected' : ''}>${escapeHtml(c.name)}</option>`
    ).join('');

    if (items.length === 0) {
      list.innerHTML = `<div class="hist-empty">No has seleccionado productos. Cierra esta ventana y marca algunos con la casilla de la tabla.</div>`;
      document.getElementById('quote-total-amount').textContent = fmtNum(0);
      document.getElementById('quote-unpriced-note').style.display = 'none';
      return;
    }

    list.innerHTML = items.map(p => {
      const qty = Math.max(1, parseInt(quoteQuantities[p.id]) || 1);
      const unit = hasPrice(p.sale) ? Number(p.sale) : 0;
      const subtotal = qty * unit;
      return `
        <div class="quote-item" data-id="${p.id}">
          ${p.image
            ? `<img class="quote-item-thumb" src="${p.image}" alt="">`
            : `<span class="quote-item-thumb-placeholder">—</span>`}
          <div class="quote-item-info">
            <div class="quote-item-name">${escapeHtml(p.name)}</div>
            <div class="quote-item-sku">Ref: ${escapeHtml(p.sku || '—')}</div>
          </div>
          <div class="quote-item-qty">
            <label>Cant.</label>
            <input type="number" min="1" value="${qty}" class="quote-qty-input" data-id="${p.id}">
          </div>
          <div class="quote-item-price">${hasPrice(p.sale) ? fmtNum(unit) : 'Sin precio'}</div>
          <div class="quote-item-subtotal">${hasPrice(p.sale) ? fmtNum(subtotal) : '—'}</div>
          <button type="button" class="quote-item-remove" data-id="${p.id}" title="Quitar">×</button>
        </div>`;
    }).join('');

    const total = items.reduce((s, p) => s + quoteLineTotal(p), 0);
    document.getElementById('quote-total-amount').textContent = fmtNum(total);
    const anyUnpriced = items.some(p => !hasPrice(p.sale));
    document.getElementById('quote-unpriced-note').style.display = anyUnpriced ? 'block' : 'none';

    list.querySelectorAll('.quote-qty-input').forEach(inp => {
      inp.addEventListener('input', (e) => {
        const id = inp.getAttribute('data-id');
        const v = Math.max(1, parseInt(e.target.value) || 1);
        quoteQuantities[id] = v;
        const p = products.find(x => x.id === id);
        const row = inp.closest('.quote-item');
        row.querySelector('.quote-item-subtotal').textContent = hasPrice(p.sale) ? fmtNum(quoteLineTotal(p)) : '—';
        const newTotal = quoteSelectedProducts().reduce((s, pp) => s + quoteLineTotal(pp), 0);
        document.getElementById('quote-total-amount').textContent = fmtNum(newTotal);
      });
    });

    list.querySelectorAll('.quote-item-remove').forEach(btn => {
      btn.addEventListener('click', () => {
        const id = btn.getAttribute('data-id');
        selectedIds.delete(id);
        updateQuoteBar();
        renderQuoteModal();
        render();
      });
    });
  }

  document.getElementById('quote-bar-clear').addEventListener('click', () => {
    selectedIds.clear();
    updateQuoteBar();
    render();
  });

  document.getElementById('quote-bar-generate').addEventListener('click', () => {
    renderQuoteModal();
    document.getElementById('quote-overlay').classList.add('open');
  });

  document.getElementById('quote-close').addEventListener('click', () => {
    document.getElementById('quote-overlay').classList.remove('open');
  });
  document.getElementById('quote-overlay').addEventListener('click', (e) => {
    if (e.target.id === 'quote-overlay') document.getElementById('quote-overlay').classList.remove('open');
  });

  async function nextQuoteNumber() {
    let n = 0;
    try {
      const raw = await storageGet('inventario:cotizacion_contador');
      n = raw ? parseInt(raw) || 0 : 0;
    } catch (e) { n = 0; }
    n += 1;
    try { await storageSet('inventario:cotizacion_contador', String(n)); } catch (e) { /* noop */ }
    return n;
  }

  function loadImg(src) {
    return new Promise((resolve) => {
      const img = new Image();
      img.onload = () => resolve(img);
      img.onerror = () => resolve(null);
      img.src = src;
    });
  }

  document.getElementById('quote-download').addEventListener('click', async () => {
    const items = quoteSelectedProducts();
    if (items.length === 0) { showToast('Selecciona al menos un producto'); return; }
    const comId = document.getElementById('quote-comercial').value;
    const comercial = COMERCIALES.find(c => c.id === comId);
    if (!comercial) { showToast('Selecciona un comercial antes de descargar'); return; }

    showToast('Generando imagen…');

    if (!CanvasRenderingContext2D.prototype._hasRoundRect) {
      const orig = CanvasRenderingContext2D.prototype.roundRect;
      if (!orig) {
        CanvasRenderingContext2D.prototype.roundRect = function(x, y, w, h, r) {
          r = Math.min(r, w / 2, h / 2);
          this.moveTo(x + r, y); this.lineTo(x + w - r, y);
          this.quadraticCurveTo(x + w, y, x + w, y + r); this.lineTo(x + w, y + h - r);
          this.quadraticCurveTo(x + w, y + h, x + w - r, y + h); this.lineTo(x + r, y + h);
          this.quadraticCurveTo(x, y + h, x, y + h - r); this.lineTo(x, y + r);
          this.quadraticCurveTo(x, y, x + r, y); this.closePath();
          return this;
        };
      }
      CanvasRenderingContext2D.prototype._hasRoundRect = true;
    }

    const quoteNum = await nextQuoteNumber();
    const quoteCode = 'COT-' + String(quoteNum).padStart(4, '0');
    const dateStr = new Date().toLocaleDateString('es-CO', { day: 'numeric', month: 'long', year: 'numeric' });
    const total = items.reduce((s, p) => s + quoteLineTotal(p), 0);
    const anyUnpriced = items.some(p => !hasPrice(p.sale));

    const S = 2;
    const W = 620 * S;
    const padX = 36 * S, padTop = 36 * S;
    const cardGap = 14 * S;
    const imgSize = 70 * S;
    const cardPadX = 16 * S, cardPadY = 14 * S;
    const textGap = 14 * S;

    const canvas = document.createElement('canvas');
    canvas.width = W;
    const ctx = canvas.getContext('2d');

    const INK = '#0D3049', GREEN = '#1F8A4C', GREY = '#6E808E', LIGHT = '#8C9EAC', BORDER = '#DAE7F0', BG = '#F5F9FC';
    const fmtCOP = (n) => fmt.format(Math.round(n || 0));

    function truncText(text, maxW) {
      let t = String(text || '');
      if (ctx.measureText(t).width <= maxW) return t;
      while (t.length > 1 && ctx.measureText(t + '…').width > maxW) t = t.slice(0, -1);
      return t + '…';
    }

    function wrapText(text, maxW) {
      const words = String(text || '').split(' ');
      const lines = [];
      let line = '';
      for (const word of words) {
        const test = line ? line + ' ' + word : word;
        if (ctx.measureText(test).width > maxW && line) {
          lines.push(line);
          line = word;
        } else {
          line = test;
        }
      }
      if (line) lines.push(line);
      return lines.slice(0, 3);
    }

    // Pre-load images
    const images = {};
    for (const p of items) {
      if (p.image) images[p.id] = await loadImg(p.image);
    }
    // Load logo
    const logoEl = document.querySelector('.login-brand-logo') || document.querySelector('.header img[alt="FQS"]');
    const logoImg = logoEl ? await loadImg(logoEl.src) : null;

    // --- Measure pass ---
    let totalH = padTop;
    // Logo
    const logoH = 28 * S;
    totalH += logoH + 10 * S;
    // Header
    totalH += 30 * S; // title
    totalH += 16 * S; // subtitle
    totalH += 4 * S;  // separator line
    totalH += 20 * S; // gap

    const cardHeights = [];
    for (const p of items) {
      const desc = p.descripcion || '';
      ctx.font = `${11.5 * S}px Inter, sans-serif`;
      const descLines = desc ? wrapText(desc, W - padX * 2 - imgSize - textGap - cardPadX * 2 - 100 * S) : [];
      const contentH = (22 * S) + (descLines.length * 15 * S) + (18 * S) + 6 * S;
      const h = Math.max(imgSize + cardPadY * 2, contentH + cardPadY * 2);
      cardHeights.push({ h, descLines });
      totalH += h + cardGap;
    }

    // Total row
    totalH += 10 * S + 30 * S + 10 * S;
    if (anyUnpriced) totalH += 18 * S;
    // Commercial info
    totalH += 20 * S + 70 * S;
    // Footer
    totalH += 20 * S + 14 * S + 20 * S;
    totalH += padTop;

    canvas.height = totalH;

    // --- Draw pass ---
    ctx.fillStyle = '#FFFFFF';
    ctx.fillRect(0, 0, W, totalH);

    let y = padTop;

    // Logo
    if (logoImg) {
      const lRatio = logoH / logoImg.height;
      const lW = logoImg.width * lRatio;
      ctx.drawImage(logoImg, padX, y, lW, logoH);
    }
    y += logoH + 10 * S;

    // Title
    ctx.font = `bold ${24 * S}px Inter, sans-serif`;
    ctx.fillStyle = INK;
    ctx.fillText('Cotización', padX, y + 22 * S);
    y += 30 * S;

    // Subtitle
    ctx.font = `${12 * S}px Inter, sans-serif`;
    ctx.fillStyle = GREY;
    ctx.fillText(`${quoteCode}  ·  ${dateStr}`, padX, y + 10 * S);
    y += 16 * S;

    // Separator
    ctx.strokeStyle = INK;
    ctx.lineWidth = 2 * S;
    ctx.beginPath();
    ctx.moveTo(padX, y);
    ctx.lineTo(W - padX, y);
    ctx.stroke();
    y += 4 * S + 20 * S;

    // Cards
    for (let i = 0; i < items.length; i++) {
      const p = items[i];
      const { h, descLines } = cardHeights[i];
      const qty = Math.max(1, parseInt(quoteQuantities[p.id]) || 1);
      const unit = hasPrice(p.sale) ? Number(p.sale) : 0;
      const subtotal = qty * unit;
      const cardX = padX, cardW = W - padX * 2;

      ctx.strokeStyle = BORDER;
      ctx.lineWidth = 1.5 * S;
      ctx.beginPath();
      ctx.roundRect(cardX, y, cardW, h, 10 * S);
      ctx.stroke();

      const imgX = cardX + cardPadX, imgY = y + cardPadY;
      if (images[p.id]) {
        ctx.save();
        ctx.beginPath();
        ctx.roundRect(imgX, imgY, imgSize, imgSize, 8 * S);
        ctx.clip();
        const img = images[p.id];
        const ratio = Math.min(imgSize / img.width, imgSize / img.height);
        const dw = img.width * ratio, dh = img.height * ratio;
        ctx.drawImage(img, imgX + (imgSize - dw) / 2, imgY + (imgSize - dh) / 2, dw, dh);
        ctx.restore();
        ctx.strokeStyle = BORDER;
        ctx.lineWidth = 1 * S;
        ctx.beginPath();
        ctx.roundRect(imgX, imgY, imgSize, imgSize, 8 * S);
        ctx.stroke();
      } else {
        ctx.fillStyle = BG;
        ctx.beginPath();
        ctx.roundRect(imgX, imgY, imgSize, imgSize, 8 * S);
        ctx.fill();
        ctx.strokeStyle = BORDER;
        ctx.lineWidth = 1.5 * S;
        ctx.setLineDash([4 * S, 3 * S]);
        ctx.beginPath();
        ctx.roundRect(imgX, imgY, imgSize, imgSize, 8 * S);
        ctx.stroke();
        ctx.setLineDash([]);
        ctx.font = `${11 * S}px Inter, sans-serif`;
        ctx.fillStyle = '#A0AFBC';
        ctx.fillText('Sin foto', imgX + imgSize / 2 - ctx.measureText('Sin foto').width / 2, imgY + imgSize / 2 + 4 * S);
      }

      const tX = imgX + imgSize + textGap;
      const maxTextW = cardW - cardPadX - imgSize - textGap - cardPadX - 10 * S;
      let tY = y + cardPadY;

      ctx.font = `bold ${14 * S}px Inter, sans-serif`;
      ctx.fillStyle = INK;
      ctx.fillText(truncText(p.name, maxTextW), tX, tY + 12 * S);
      tY += 18 * S;

      ctx.font = `${11 * S}px monospace`;
      ctx.fillStyle = LIGHT;
      ctx.fillText(`Ref: ${p.sku || '—'}`, tX, tY + 9 * S);
      tY += 14 * S;

      if (descLines.length > 0) {
        ctx.font = `${11.5 * S}px Inter, sans-serif`;
        ctx.fillStyle = '#5A6C7A';
        descLines.forEach(line => {
          ctx.fillText(line, tX, tY + 10 * S);
          tY += 15 * S;
        });
      }

      const botY = y + h - cardPadY;
      ctx.font = `${12 * S}px Inter, sans-serif`;
      ctx.fillStyle = INK;
      ctx.fillText(`Cant.: ${qty}  ·  Precio unit.: ${hasPrice(p.sale) ? fmtCOP(unit) : 'Sin precio'}`, tX, botY);

      ctx.font = `bold ${15 * S}px Inter, sans-serif`;
      ctx.fillStyle = GREEN;
      const subText = hasPrice(p.sale) ? fmtCOP(subtotal) : '—';
      ctx.fillText(subText, cardX + cardW - cardPadX - ctx.measureText(subText).width, botY);

      y += h + cardGap;
    }

    // Total row
    ctx.strokeStyle = INK;
    ctx.lineWidth = 2.5 * S;
    ctx.beginPath();
    ctx.moveTo(padX, y);
    ctx.lineTo(W - padX, y);
    ctx.stroke();
    y += 10 * S;

    ctx.font = `bold ${17 * S}px Inter, sans-serif`;
    ctx.fillStyle = INK;
    ctx.fillText('Total', padX, y + 16 * S);
    ctx.fillStyle = GREEN;
    const totalText = fmtCOP(total);
    ctx.fillText(totalText, W - padX - ctx.measureText(totalText).width, y + 16 * S);
    y += 30 * S;

    if (anyUnpriced) {
      ctx.font = `${10.5 * S}px Inter, sans-serif`;
      ctx.fillStyle = '#96A5B2';
      ctx.fillText('* Algunos productos no tienen precio configurado y no se incluyen en el total.', padX, y + 8 * S);
      y += 18 * S;
    }

    // Commercial info block
    y += 20 * S;
    ctx.fillStyle = BG;
    ctx.beginPath();
    ctx.roundRect(padX, y, W - padX * 2, 60 * S, 10 * S);
    ctx.fill();
    ctx.strokeStyle = BORDER;
    ctx.lineWidth = 1.5 * S;
    ctx.beginPath();
    ctx.roundRect(padX, y, W - padX * 2, 60 * S, 10 * S);
    ctx.stroke();

    ctx.font = `${10 * S}px Inter, sans-serif`;
    ctx.fillStyle = '#96A5B2';
    ctx.fillText('ASESOR COMERCIAL', padX + 16 * S, y + 14 * S);

    ctx.font = `bold ${14 * S}px Inter, sans-serif`;
    ctx.fillStyle = INK;
    ctx.fillText(comercial.name, padX + 16 * S, y + 30 * S);

    ctx.font = `${11.5 * S}px Inter, sans-serif`;
    ctx.fillStyle = '#5A6C7A';
    ctx.fillText(`Tel: ${comercial.phone}   ·   ${comercial.email}`, padX + 16 * S, y + 46 * S);

    y += 70 * S;

    // Footer
    y += 10 * S;
    ctx.strokeStyle = BORDER;
    ctx.lineWidth = 1 * S;
    ctx.beginPath();
    ctx.moveTo(padX, y);
    ctx.lineTo(W - padX, y);
    ctx.stroke();
    y += 14 * S;
    ctx.font = `${10 * S}px Inter, sans-serif`;
    ctx.fillStyle = '#96A5B2';
    ctx.fillText('FQS · Fine Quality Sound', padX, y + 8 * S);
    ctx.fillText(quoteCode, W - padX - ctx.measureText(quoteCode).width, y + 8 * S);

    // Download
    try {
      canvas.toBlob(blob => {
        if (!blob) { showToast('Error al generar la imagen'); return; }
        const url = URL.createObjectURL(blob);
        const a = document.createElement('a');
        a.href = url;
        a.download = `${quoteCode}.png`;
        document.body.appendChild(a);
        a.click();
        document.body.removeChild(a);
        setTimeout(() => URL.revokeObjectURL(url), 3000);
        showToast('Cotización descargada');
      }, 'image/png');
    } catch (e) {
      console.error('Error descarga:', e);
      showToast('Error al descargar. Intenta clic derecho > Guardar imagen.');
      const dataUrl = canvas.toDataURL('image/png');
      openLightbox(dataUrl);
    }
  });

  // Importa una sola vez los productos del CSV que compartiste, respetando
  // los precios que sí venían en el archivo. Imágenes y bodega quedan vacías
  // para que las completes cuando quieras.
  async function importSeedIfNeeded() {
    // Legado — ya no se usa (el seed CSV está vacío).
  }

  // Solo importa los productos del seed si el almacenamiento está VACÍO.
  // Una vez que el usuario tiene datos guardados, NUNCA se sobrescriben
  // aunque se abra una versión nueva del archivo.
  async function importXlsxSeedIfNeeded() {
    // Legado — ya no se usa. Los productos se cargan desde SEED_DATA al inicio.
  }

  async function persist(changedId) {
    try {
      // Guardar productos SIN imágenes (datos livianos)
      const lite = products.map(p => {
        const { image, ...rest } = p;
        return rest;
      });
      await storageSet(STORAGE_KEY, JSON.stringify(lite));
    } catch (e) {
      console.error('No se pudo guardar', e);
      showToast('No se pudo guardar el cambio. Intenta de nuevo.');
      return;
    }
    // Guardar solo la imagen del producto que cambió (o todas si no se especifica)
    const toSave = changedId ? products.filter(p => p.id === changedId) : products;
    let failed = 0;
    for (const p of toSave) {
      const imgKey = 'inventario:img:' + p.id;
      if (p.image) {
        // Intentar primero IndexedDB (gran capacidad), luego el almacenamiento normal
        let ok = await imgDBSet(imgKey, p.image);
        if (!ok) ok = await storageSet(imgKey, p.image);
        if (!ok) failed++;
      } else {
        await imgDBDel(imgKey);
        await storageDel(imgKey);
      }
    }
    if (failed > 0) {
      showToast('El cambio se guardó, pero una imagen no se pudo almacenar. Prueba con una foto más pequeña.');
    }
  }

  function calcMargin(p) {
    if (!hasPrice(p.cost) || !hasPrice(p.sale)) return { gain: null, pct: null };
    const cost = Number(p.cost) || 0;
    const sale = Number(p.sale) || 0;
    const gain = sale - cost;
    const pct = cost > 0 ? (gain / cost) * 100 : (sale > 0 ? 100 : 0);
    return { gain, pct };
  }

  function stockStatus(stock) {
    const s = Number(stock) || 0;
    if (s <= 0) return { label: 'Agotado', cls: 'out' };
    if (s <= 3) return { label: 'Stock bajo', cls: 'low' };
    return { label: 'En stock', cls: 'ok' };
  }

  function showToast(msg) {
    const t = document.getElementById('toast');
    t.textContent = msg;
    t.classList.add('show');
    clearTimeout(t._timer);
    t._timer = setTimeout(() => t.classList.remove('show'), 2200);
  }

  function resizeImage(file, maxDim, quality) {
    return new Promise((resolve, reject) => {
      const reader = new FileReader();
      reader.onerror = () => reject(new Error('No se pudo leer el archivo'));
      reader.onload = () => {
        const img = new Image();
        img.onerror = () => reject(new Error('Archivo no es una imagen válida'));
        img.onload = () => {
          let { width, height } = img;
          if (width > height && width > maxDim) { height = Math.round(height * (maxDim / width)); width = maxDim; }
          else if (height > maxDim) { width = Math.round(width * (maxDim / height)); height = maxDim; }
          const canvas = document.createElement('canvas');
          canvas.width = width; canvas.height = height;
          const ctx = canvas.getContext('2d');
          ctx.fillStyle = '#FFFFFF';
          ctx.fillRect(0, 0, width, height);
          ctx.drawImage(img, 0, 0, width, height);
          // Compresión adaptativa: bajar calidad si pesa más de ~600KB
          let q = quality;
          let dataUrl = canvas.toDataURL('image/jpeg', q);
          const MAX_LEN = 800000; // ~600KB en base64
          while (dataUrl.length > MAX_LEN && q > 0.4) {
            q -= 0.1;
            dataUrl = canvas.toDataURL('image/jpeg', q);
          }
          resolve(dataUrl);
        };
        img.src = reader.result;
      };
      reader.readAsDataURL(file);
    });
  }

  function setImagePreview(dataUrl) {
    const preview = document.getElementById('image-preview');
    const removeBtn = document.getElementById('btn-remove-image');
    if (dataUrl) {
      preview.innerHTML = `<img src="${dataUrl}" alt="" style="cursor:zoom-in;" data-action="zoom">`;
      preview.style.cursor = 'zoom-in';
      removeBtn.style.display = 'inline-block';
    } else {
      preview.innerHTML = 'Sin foto';
      preview.style.cursor = 'default';
      removeBtn.style.display = 'none';
    }
  }

  document.getElementById('btn-upload-image').addEventListener('click', () => {
    document.getElementById('f-image').click();
  });
  document.getElementById('f-image').addEventListener('change', async (e) => {
    const file = e.target.files[0];
    if (!file) return;
    if (!file.type.startsWith('image/')) { showToast('Selecciona un archivo de imagen'); return; }
    try {
      const dataUrl = await resizeImage(file, 500, 0.75);
      currentImageData = dataUrl;
      setImagePreview(dataUrl);
    } catch (err) {
      showToast('No se pudo procesar la imagen');
    }
    e.target.value = '';
  });
  document.getElementById('btn-remove-image').addEventListener('click', () => {
    currentImageData = null;
    setImagePreview(null);
  });
  document.getElementById('image-preview').addEventListener('click', (e) => {
    if (e.target.tagName === 'IMG') openLightbox(e.target.src);
  });

  document.addEventListener('paste', async (e) => {
    const panel = document.getElementById('form-panel');
    if (!panel.classList.contains('open')) return;
    const items = e.clipboardData && e.clipboardData.items;
    if (!items) return;
    for (const item of items) {
      if (item.type && item.type.startsWith('image/')) {
        const file = item.getAsFile();
        if (!file) continue;
        e.preventDefault();
        try {
          const dataUrl = await resizeImage(file, 500, 0.75);
          currentImageData = dataUrl;
          setImagePreview(dataUrl);
          showToast('Imagen pegada');
        } catch (err) {
          showToast('No se pudo procesar la imagen pegada');
        }
        break;
      }
    }
  });

  document.getElementById('lightbox').addEventListener('click', () => {
    document.getElementById('lightbox').classList.remove('open');
  });
  function openLightbox(src) {
    document.getElementById('lightbox-img').src = src;
    document.getElementById('lightbox').classList.add('open');
  }

  function uniqueCategories() {
    const fromProducts = products.map(p => (p.cat || '').trim()).filter(Boolean);
    const fromList = categories.map(c => c.trim()).filter(Boolean);
    return [...new Set([...fromList, ...fromProducts])].sort((a,b) => a.localeCompare(b));
  }

  async function persistCategories() {
    try { await storageSet(STORAGE_KEY_CATEGORIES, JSON.stringify(categories)); }
    catch (e) { console.error('No se pudo guardar categorías', e); }
  }

  async function addCategoryIfNew(name) {
    const clean = (name || '').trim();
    if (!clean) return '';
    if (!categories.some(c => c.toLowerCase() === clean.toLowerCase()) &&
        !products.some(p => (p.cat || '').toLowerCase() === clean.toLowerCase())) {
      categories.push(clean);
      await persistCategories();
    }
    return clean;
  }

  function allWarehouses() {
    const fromList = warehouses.map(w => w.trim()).filter(Boolean);
    const fromProducts = products.map(p => (p.warehouse || '').trim()).filter(Boolean);
    return [...new Set([...fromList, ...fromProducts])].sort((a,b) => a.localeCompare(b));
  }

  async function addWarehouseIfNew(name) {
    const clean = (name || '').trim();
    if (!clean) return '';
    if (!warehouses.some(w => w.toLowerCase() === clean.toLowerCase())) {
      warehouses.push(clean);
      await persistWarehouses();
    }
    return clean;
  }

  function buildWarehouseOptionsHtml(selected) {
    const whs = allWarehouses();
    let html = `<option value=""${!selected ? ' selected' : ''}>Sin asignar</option>`;
    html += whs.map(w => `<option value="${escapeHtml(w)}"${w === selected ? ' selected' : ''}>${escapeHtml(w)}</option>`).join('');
    html += `<option value="__new__">+ Nueva bodega o espacio…</option>`;
    return html;
  }

  function refreshWarehouseFormUI() {
    const sel = document.getElementById('f-warehouse');
    const current = sel.value === '__new__' ? '__new__' : sel.value;
    sel.innerHTML = buildWarehouseOptionsHtml(current === '__new__' ? '' : current);
    if (current === '__new__') sel.value = '__new__';
  }

  document.getElementById('f-warehouse').addEventListener('change', (e) => {
    const newInput = document.getElementById('f-warehouse-new');
    if (e.target.value === '__new__') {
      newInput.style.display = 'block';
      newInput.focus();
    } else {
      newInput.style.display = 'none';
      newInput.value = '';
    }
  });

  function refreshWarehouseFilterUI() {
    const whs = allWarehouses();
    const filter = document.getElementById('wh-filter');
    const currentVal = filter.value;
    filter.innerHTML = '<option value="">Todas las bodegas</option>' +
      whs.map(w => `<option value="${escapeHtml(w)}">${escapeHtml(w)}</option>`).join('');
    filter.value = whs.includes(currentVal) ? currentVal : '';
    whFilterVal = filter.value;
  }

  function refreshCategoryUI() {
    const cats = uniqueCategories();
    const filter = document.getElementById('cat-filter');
    const currentVal = filter.value;
    filter.innerHTML = '<option value="">Todas las categorías</option>' +
      cats.map(c => `<option value="${escapeHtml(c)}">${escapeHtml(c)}</option>`).join('');
    filter.value = cats.includes(currentVal) ? currentVal : '';
    catFilterVal = filter.value;

    document.getElementById('cat-list').innerHTML = cats.map(c => `<option value="${escapeHtml(c)}">`).join('');
  }

  function render() {
    try { _render(); } catch(e) {
      console.error('Error en render:', e);
      const body = document.getElementById('inv-body');
      if (body) body.innerHTML = `<div style="padding:40px;color:red;font-size:14px;">Error al renderizar: ${e.message}<br><pre>${e.stack}</pre></div>`;
    }
  }
  function _render() {
    refreshCategoryUI();
    refreshWarehouseFormUI();
    refreshWarehouseFilterUI();
    const body = document.getElementById('inv-body');
    const footerNote = document.getElementById('footer-note');
    const term = searchTerm.trim().toLowerCase();

    let list = products.filter(p => {
      const matchesTerm = !term ||
        p.name.toLowerCase().includes(term) ||
        (p.cat || '').toLowerCase().includes(term) ||
        (p.sku || '').toLowerCase().includes(term) ||
        (p.provider || '').toLowerCase().includes(term) ||
        (p.descripcion || '').toLowerCase().includes(term) ||
        (p.warehouse || '').toLowerCase().includes(term);
      const matchesCat = !catFilterVal || (p.cat || '') === catFilterVal;
      const matchesWh = !whFilterVal || (p.warehouse || '') === whFilterVal;
      return matchesTerm && matchesCat && matchesWh;
    });

    if (sortKey) {
      list = [...list].sort((a, b) => {
        let av, bv;
        if (sortKey === 'margin') { av = calcMargin(a).pct; bv = calcMargin(b).pct; }
        else if (sortKey === 'name' || sortKey === 'cat' || sortKey === 'warehouse') { av = (a[sortKey]||'').toLowerCase(); bv = (b[sortKey]||'').toLowerCase(); }
        else { av = Number(a[sortKey]) || 0; bv = Number(b[sortKey]) || 0; }
        if (av < bv) return -1 * sortDir;
        if (av > bv) return 1 * sortDir;
        return 0;
      });
    }

    const count = products.length;
    const totalUnits = products.reduce((s, p) => s + (Number(p.stock)||0), 0);
    const pricedProducts = products.filter(p => hasPrice(p.cost) && hasPrice(p.sale));
    const totalCost = pricedProducts.reduce((s, p) => s + (Number(p.cost)||0) * (Number(p.stock)||0), 0);
    const totalSale = pricedProducts.reduce((s, p) => s + (Number(p.sale)||0) * (Number(p.stock)||0), 0);
    const avgMarginPct = pricedProducts.length > 0
      ? pricedProducts.reduce((s, p) => s + calcMargin(p).pct, 0) / pricedProducts.length
      : 0;
    const pendingCount = count - pricedProducts.length;

    document.getElementById('stat-count').textContent = count;
    document.getElementById('stat-units').textContent = totalUnits;
    document.getElementById('stat-cost').textContent = fmtNum(totalCost);
    document.getElementById('stat-sale').textContent = fmtNum(totalSale);
    document.getElementById('stat-margin').textContent = avgMarginPct.toFixed(1) + '%';
    const pendingEl = document.getElementById('stat-pending');
    if (pendingCount > 0) {
      pendingEl.style.display = 'block';
      pendingEl.textContent = `${pendingCount} sin precio`;
    } else {
      pendingEl.style.display = 'none';
    }

    if (products.length === 0) {
      footerNote.style.display = 'none';
      body.innerHTML = `
        <div class="empty">
          <div class="empty-title">Aún no hay productos</div>
          <div>Agrega el primero con el botón "Agregar producto".</div>
        </div>`;
      return;
    }
    footerNote.style.display = 'block';

    if (list.length === 0) {
      body.innerHTML = `<div class="empty"><div class="empty-title">Sin resultados</div><div>No hay productos que coincidan con tu búsqueda o filtro.</div></div>`;
      return;
    }

    const arrow = (key) => sortKey === key ? (sortDir === 1 ? ' ▲' : ' ▼') : '';

    const filteredUnits = list.reduce((s, p) => s + (Number(p.stock)||0), 0);
    const filteredPriced = list.filter(p => hasPrice(p.cost) && hasPrice(p.sale));
    const filteredCost = filteredPriced.reduce((s, p) => s + (Number(p.cost)||0) * (Number(p.stock)||0), 0);
    const filteredSale = filteredPriced.reduce((s, p) => s + (Number(p.sale)||0) * (Number(p.stock)||0), 0);
    lastListIds = list.map(p => p.id);

    let rows = list.map(p => {
      const { gain, pct } = calcMargin(p);
      const priced = gain !== null;
      const marginClass = !priced ? '' : (gain >= 0 ? 'margin-pos' : 'margin-neg');
      const stock = stockStatus(p.stock);
      return `
        <tr data-id="${p.id}">
          <td class="check-col"><input type="checkbox" class="row-check" data-id="${p.id}" ${selectedIds.has(p.id) ? 'checked' : ''}></td>
          <td class="name-cell">
            <div class="name-cell-inner">
              ${p.image
                ? `<img class="thumb" src="${p.image}" alt="" data-action="zoom" data-id="${p.id}">`
                : `<span class="thumb-placeholder">—</span>`}
              <span>
                ${escapeHtml(p.name)}
                ${p.sku ? `<span class="sku">${escapeHtml(p.sku)}</span>` : ''}
              </span>
            </div>
          </td>
          <td class="desc-cell" title="${escapeHtml(p.descripcion || '')}">${p.descripcion ? escapeHtml(p.descripcion) : '<span style="color:var(--ink-faint)">—</span>'}</td>
          <td>${p.cat ? `<span class="cat-badge">${escapeHtml(p.cat)}</span>` : '<span style="color:var(--ink-faint)">—</span>'}</td>
          <td>${escapeHtml(p.provider || '—')}</td>
          <td>
            <div class="wh-cell" data-id="${p.id}">
              <select class="wh-select" data-action="wh-select" data-id="${p.id}">
                ${buildWarehouseOptionsHtml(p.warehouse || '')}
              </select>
            </div>
          </td>
          <td class="num mono" style="${priced ? '' : 'color:var(--ink-faint)'}">${fmtPrice(p.cost)}</td>
          <td class="num mono" style="${hasPrice(p.sale) ? 'color:var(--green); font-weight:600;' : 'color:var(--ink-faint);'}">${fmtPrice(p.sale)}</td>
          <td class="num mono" style="${hasPrice(p.meli) ? 'color:var(--orange); font-weight:600;' : 'color:var(--ink-faint);'}">${hasPrice(p.meli) ? fmtNum(p.meli) : '—'}</td>
          <td class="num mono" style="${hasPrice(p.redes) ? 'color:var(--teal); font-weight:600;' : 'color:var(--ink-faint);'}">${hasPrice(p.redes) ? fmtNum(p.redes) : '—'}</td>
          <td class="num mono">
            ${p.stock}
            <span class="stock-badge ${stock.cls}">${stock.label}</span>
          </td>
          <td class="num mono ${marginClass}" style="${priced ? '' : 'color:var(--ink-faint)'}">${priced ? fmtNum(gain) : '—'}</td>
          <td class="num mono ${marginClass}" style="${priced ? '' : 'color:var(--ink-faint)'}">${priced ? pct.toFixed(1) + '%' : '—'}</td>
          <td class="num">
            <div class="row-actions">
              <button class="icon-btn" data-action="edit" data-id="${p.id}">Editar</button>
              <button class="icon-btn danger" data-action="delete" data-id="${p.id}">Eliminar</button>
            </div>
          </td>
        </tr>`;
    }).join('');

    body.innerHTML = `
      <div class="table-wrap">
        <table>
          <thead>
            <tr>
              <th class="check-col"><input type="checkbox" id="select-all-checkbox"></th>
              <th data-key="name">Producto${arrow('name')}</th>
              <th>Descripción</th>
              <th data-key="cat">Categoría${arrow('cat')}</th>
              <th>Proveedor</th>
              <th data-key="warehouse">Bodega / espacio${arrow('warehouse')}</th>
              <th class="num" data-key="cost">Precio compra${arrow('cost')}</th>
              <th class="num" data-key="sale">Precio venta${arrow('sale')}</th>
              <th class="num" data-key="meli">Mercado Libre${arrow('meli')}</th>
              <th class="num" data-key="redes">Redes / Shopify${arrow('redes')}</th>
              <th class="num" data-key="stock">Stock${arrow('stock')}</th>
              <th class="num" data-key="margin">Ganancia $${arrow('margin')}</th>
              <th class="num" data-key="margin">% sobre costo${arrow('margin')}</th>
              <th class="num"></th>
            </tr>
          </thead>
          <tbody>${rows}</tbody>
          <tfoot>
            <tr>
              <td colspan="6">Totales (${list.length} de ${count} productos)</td>
              <td class="num">${fmtNum(filteredCost)}</td>
              <td class="num">${fmtNum(filteredSale)}</td>
              <td class="num"></td>
              <td class="num"></td>
              <td class="num">${filteredUnits} u.</td>
              <td class="num" colspan="3">${fmtNum(filteredSale - filteredCost)}</td>
            </tr>
          </tfoot>
        </table>
      </div>`;

    body.querySelectorAll('thead th[data-key]').forEach(th => {
      th.addEventListener('click', () => {
        const key = th.getAttribute('data-key');
        if (sortKey === key) sortDir *= -1; else { sortKey = key; sortDir = 1; }
        render();
      });
    });

    body.querySelectorAll('.row-check').forEach(cb => {
      cb.addEventListener('change', (e) => {
        const id = cb.getAttribute('data-id');
        if (e.target.checked) {
          selectedIds.add(id);
          if (!quoteQuantities[id]) quoteQuantities[id] = 1;
        } else {
          selectedIds.delete(id);
        }
        updateSelectAllCheckbox();
        updateQuoteBar();
      });
    });

    const selectAllCb = document.getElementById('select-all-checkbox');
    if (selectAllCb) {
      selectAllCb.checked = lastListIds.length > 0 && lastListIds.every(id => selectedIds.has(id));
      selectAllCb.addEventListener('change', (e) => {
        if (e.target.checked) {
          lastListIds.forEach(id => { selectedIds.add(id); if (!quoteQuantities[id]) quoteQuantities[id] = 1; });
        } else {
          lastListIds.forEach(id => selectedIds.delete(id));
        }
        updateQuoteBar();
        render();
      });
    }

    body.querySelectorAll('[data-action="wh-select"]').forEach(sel => {
      sel.addEventListener('change', async (e) => {
        const id = sel.getAttribute('data-id');
        const p = products.find(x => x.id === id);
        if (!p) return;
        if (e.target.value === '__new__') {
          const cell = sel.closest('.wh-cell');
          cell.innerHTML = `
            <div class="wh-new-inline">
              <input type="text" placeholder="Nombre de la bodega" data-id="${id}">
              <button class="icon-btn" data-action="wh-confirm" data-id="${id}">OK</button>
            </div>`;
          const input = cell.querySelector('input');
          input.focus();
          const confirmNew = async () => {
            const name = await addWarehouseIfNew(input.value);
            const beforeWh = p.warehouse;
            p.warehouse = name;
            await persist();
            if ((beforeWh || '') !== (name || '')) {
              logHistory('update', p.name, [{ field: 'Bodega', before: histVal(beforeWh), after: histVal(name) }]);
            }
            render();
          };
          cell.querySelector('[data-action="wh-confirm"]').addEventListener('click', confirmNew);
          input.addEventListener('keydown', (ev) => {
            if (ev.key === 'Enter') { ev.preventDefault(); confirmNew(); }
            if (ev.key === 'Escape') { render(); }
          });
        } else {
          const beforeWh = p.warehouse;
          p.warehouse = e.target.value;
          await persist();
          if ((beforeWh || '') !== (e.target.value || '')) {
            logHistory('update', p.name, [{ field: 'Bodega', before: histVal(beforeWh), after: histVal(e.target.value) }]);
          }
          showToast('Bodega actualizada');
          render();
        }
      });
    });

    body.querySelectorAll('[data-action="zoom"]').forEach(img => {
      img.addEventListener('click', () => openLightbox(img.src));
    });

    body.querySelectorAll('[data-action="delete"]').forEach(btn => {
      btn.addEventListener('click', () => {
        const id = btn.getAttribute('data-id');
        const p = products.find(x => x.id === id);
        openDeleteModal(id, p ? p.name : '');
      });
    });

    body.querySelectorAll('[data-action="edit"]').forEach(btn => {
      btn.addEventListener('click', () => {
        try {
        const id = btn.getAttribute('data-id');
        const p = products.find(x => x.id === id);
        if (!p) { showToast('Producto no encontrado'); return; }
        editingId = id;
        document.getElementById('f-name').value = p.name;
        document.getElementById('f-cat').value = p.cat || '';
        document.getElementById('f-sku').value = p.sku || '';
        document.getElementById('f-cost').value = hasPrice(p.cost) ? p.cost : '';
        document.getElementById('f-sale').value = hasPrice(p.sale) ? p.sale : '';
        document.getElementById('f-meli').value = hasPrice(p.meli) ? p.meli : '';
        document.getElementById('f-redes').value = hasPrice(p.redes) ? p.redes : '';
        document.getElementById('f-stock').value = p.stock;
        document.getElementById('f-provider').value = p.provider || '';
        document.getElementById('f-descripcion').value = p.descripcion || '';
        refreshWarehouseFormUI();
        document.getElementById('f-warehouse').value = p.warehouse || '';
        document.getElementById('f-warehouse-new').style.display = 'none';
        document.getElementById('f-warehouse-new').value = '';
        currentImageData = p.image || null;
        setImagePreview(currentImageData);
        document.getElementById('form-title').textContent = 'Editar producto';
        document.getElementById('btn-save').textContent = 'Guardar cambios';
        updateLiveMargin();
        openForm();
        } catch(e) { console.error('Error al editar:', e); showToast('Error: ' + e.message); }
      });
    });
  }

  function openDeleteModal(id, name) {
    pendingDeleteId = id;
    document.getElementById('modal-body').textContent = `¿Seguro que quieres eliminar "${name}"? Esta acción no se puede deshacer.`;
    document.getElementById('modal-overlay').classList.add('open');
  }
  function closeDeleteModal() {
    pendingDeleteId = null;
    document.getElementById('modal-overlay').classList.remove('open');
  }
  document.getElementById('modal-cancel').addEventListener('click', closeDeleteModal);
  document.getElementById('modal-overlay').addEventListener('click', (e) => {
    if (e.target.id === 'modal-overlay') closeDeleteModal();
  });
  document.getElementById('modal-confirm').addEventListener('click', async () => {
    if (!pendingDeleteId) return;
    const p = products.find(x => x.id === pendingDeleteId);
    products = products.filter(x => x.id !== pendingDeleteId);
    if (p) {
      logHistory('delete', p.name, []);
      await imgDBDel('inventario:img:' + pendingDeleteId);
      await storageDel('inventario:img:' + pendingDeleteId);
    }
    await persist();
    closeDeleteModal();
    render();
    showToast('Producto eliminado');
  });

  function openForm() {
    document.getElementById('form-panel').classList.add('open');
    document.getElementById('f-name').focus();
  }
  function closeForm() {
    document.getElementById('form-panel').classList.remove('open');
    ['f-name','f-cat','f-sku','f-cost','f-sale','f-meli','f-redes','f-stock','f-provider','f-descripcion'].forEach(id => {
      document.getElementById(id).value = '';
      document.getElementById(id).classList.remove('err');
    });
    document.getElementById('f-warehouse').value = '';
    document.getElementById('f-warehouse-new').style.display = 'none';
    document.getElementById('f-warehouse-new').value = '';
    editingId = null;
    currentImageData = null;
    setImagePreview(null);
    document.getElementById('form-title').textContent = 'Nuevo producto';
    document.getElementById('btn-save').textContent = 'Guardar producto';
    updateLiveMargin();
  }

  function updateLiveMargin() {
    const costRaw = document.getElementById('f-cost').value;
    const saleRaw = document.getElementById('f-sale').value;
    const el = document.getElementById('live-margin');
    if (costRaw === '' || saleRaw === '') {
      el.innerHTML = `Ganancia: <span class="mono" style="color:var(--ink-faint)">Pendiente</span> · agrega ambos precios para calcularla`;
      return;
    }
    const cost = parseFloat(costRaw) || 0;
    const sale = parseFloat(saleRaw) || 0;
    const gain = sale - cost;
    const pct = cost > 0 ? (gain / cost) * 100 : (sale > 0 ? 100 : 0);
    const color = gain >= 0 ? 'var(--teal)' : 'var(--red)';
    el.innerHTML = `Ganancia: <span class="mono" style="color:${color}">${fmtNum(gain)}</span> · <span class="mono" style="color:${color}">${pct.toFixed(1)}%</span>`;
  }
  ['f-cost','f-sale'].forEach(id => document.getElementById(id).addEventListener('input', updateLiveMargin));

  document.getElementById('btn-toggle-form').addEventListener('click', () => {
    const panel = document.getElementById('form-panel');
    if (panel.classList.contains('open')) { closeForm(); } else { openForm(); }
  });
  document.getElementById('btn-cancel').addEventListener('click', closeForm);

  async function saveProduct() {
    const nameInput = document.getElementById('f-name');
    const costInput = document.getElementById('f-cost');
    const saleInput = document.getElementById('f-sale');
    [nameInput, costInput, saleInput].forEach(i => i.classList.remove('err'));

    const name = nameInput.value.trim();
    const cat = document.getElementById('f-cat').value.trim();
    const sku = document.getElementById('f-sku').value.trim();
    const costRaw = costInput.value.trim();
    const saleRaw = saleInput.value.trim();
    const cost = costRaw === '' ? null : parseFloat(costRaw);
    const sale = saleRaw === '' ? null : parseFloat(saleRaw);
    const meliRaw = document.getElementById('f-meli').value.trim();
    const redesRaw = document.getElementById('f-redes').value.trim();
    const meli = meliRaw === '' ? null : parseFloat(meliRaw);
    const redes = redesRaw === '' ? null : parseFloat(redesRaw);
    const stock = parseInt(document.getElementById('f-stock').value) || 0;
    const provider = document.getElementById('f-provider').value.trim();
    const descripcion = document.getElementById('f-descripcion').value.trim();
    const whSelectVal = document.getElementById('f-warehouse').value;
    let warehouse = whSelectVal;
    if (whSelectVal === '__new__') {
      warehouse = await addWarehouseIfNew(document.getElementById('f-warehouse-new').value);
    }

    let hasError = false;
    if (!name) { nameInput.classList.add('err'); hasError = true; }
    if (cost !== null && (isNaN(cost) || cost < 0)) { costInput.classList.add('err'); hasError = true; }
    if (sale !== null && (isNaN(sale) || sale < 0)) { saleInput.classList.add('err'); hasError = true; }
    if (hasError) { showToast('Revisa los campos marcados en rojo'); return; }

    let savedId = editingId;
    if (editingId) {
      const p = products.find(x => x.id === editingId);
      if (p) {
        const before = { ...p };
        p.name = name; p.cat = cat; p.sku = sku; p.cost = cost; p.sale = sale; p.meli = meli; p.redes = redes; p.stock = stock; p.provider = provider; p.descripcion = descripcion; p.image = currentImageData; p.warehouse = warehouse;
        const changes = diffProduct(before, p);
        if (changes.length) logHistory('update', name, changes);
      }
      showToast('Producto actualizado');
    } else {
      const newId = uid();
      products.push({ id: newId, name, cat, sku, cost, sale, meli, redes, stock, provider, descripcion, image: currentImageData, warehouse });
      logHistory('create', name, []);
      savedId = newId;
      showToast('Producto agregado');
    }
    await persist(savedId);
    closeForm();
    render();
  }

  document.getElementById('btn-save').addEventListener('click', saveProduct);
  document.getElementById('form-panel').addEventListener('keydown', (e) => {
    if (e.key === 'Enter' && e.target.tagName === 'INPUT') { e.preventDefault(); saveProduct(); }
    if (e.key === 'Escape') { closeForm(); }
  });

  document.getElementById('inv-search').addEventListener('input', (e) => {
    searchTerm = e.target.value;
    render();
  });
  document.getElementById('cat-filter').addEventListener('change', (e) => {
    catFilterVal = e.target.value;
    render();
  });
  document.getElementById('wh-filter').addEventListener('change', (e) => {
    whFilterVal = e.target.value;
    render();
  });

  document.getElementById('btn-export').addEventListener('click', () => {
    if (products.length === 0) { showToast('No hay productos para exportar'); return; }
    if (!window.XLSX) { showToast('El generador de Excel no cargó, intenta de nuevo'); return; }

    const headers = ['Nombre','Descripción','SKU','Categoría','Proveedor','Bodega/Espacio','Precio compra','Precio venta','Precio Mercado Libre','Precio redes/Shopify','Stock','Ganancia','% sobre costo'];
    const rows = products.map(p => {
      const { gain, pct } = calcMargin(p);
      return [
        p.name || '',
        p.descripcion || '',
        p.sku || '',
        p.cat || '',
        p.provider || '',
        p.warehouse || '',
        hasPrice(p.cost) ? Number(p.cost) : null,
        hasPrice(p.sale) ? Number(p.sale) : null,
        hasPrice(p.meli) ? Number(p.meli) : null,
        hasPrice(p.redes) ? Number(p.redes) : null,
        Number(p.stock) || 0,
        gain === null ? null : Math.round(gain),
        pct === null ? null : Math.round(pct * 10) / 1000
      ];
    });

    const ws = XLSX.utils.aoa_to_sheet([headers, ...rows]);
    ws['!cols'] = [
      { wch: 32 }, { wch: 40 }, { wch: 14 }, { wch: 16 }, { wch: 16 }, { wch: 18 },
      { wch: 13 }, { wch: 13 }, { wch: 15 }, { wch: 15 }, { wch: 8 }, { wch: 13 }, { wch: 11 }
    ];
    const moneyCols = [6, 7, 8, 9, 11];
    const range = XLSX.utils.decode_range(ws['!ref']);
    for (let r = 1; r <= range.e.r; r++) {
      moneyCols.forEach(c => {
        const cell = ws[XLSX.utils.encode_cell({ r, c })];
        if (cell && cell.t === 'n') cell.z = '#,##0';
      });
      const pctCell = ws[XLSX.utils.encode_cell({ r, c: 12 })];
      if (pctCell && pctCell.t === 'n') pctCell.z = '0.0%';
      const stockCell = ws[XLSX.utils.encode_cell({ r, c: 10 })];
      if (stockCell && stockCell.t === 'n') stockCell.z = '#,##0';
    }
    ws['!autofilter'] = { ref: ws['!ref'] };

    const wb = XLSX.utils.book_new();
    XLSX.utils.book_append_sheet(wb, ws, 'Inventario');
    XLSX.writeFile(wb, `inventario_${new Date().toISOString().slice(0,10)}.xlsx`);
    showToast('Excel exportado');
  });

  document.getElementById('btn-export-pdf').addEventListener('click', () => {
    if (products.length === 0) { showToast('No hay productos para exportar'); return; }
    if (!window.jspdf || !window.jspdf.jsPDF) { showToast('El generador de PDF no cargó, intenta de nuevo'); return; }

    const { jsPDF } = window.jspdf;
    const doc = new jsPDF({ orientation: 'landscape', unit: 'pt', format: 'a4' });
    const pageW = doc.internal.pageSize.getWidth();
    const pageH = doc.internal.pageSize.getHeight();
    const marginX = 30;
    const marginTop = 58;
    const marginBottom = 30;
    const INK = [13, 48, 73], WHITE = [255, 255, 255], GREEN = [31, 138, 76], ORANGE = [201, 106, 27];
    const LINE_COLOR = [206, 224, 236], ZEBRA_COLOR = [243, 248, 252], TOTALS_BG = [229, 242, 251];

    const cols = [
      { key: 'name',    label: 'Producto',      width: 110 },
      { key: 'desc',    label: 'Descripción',   width: 120 },
      { key: 'sku',     label: 'SKU',           width: 42 },
      { key: 'cat',     label: 'Categoría',     width: 55 },
      { key: 'provider',label: 'Proveedor',     width: 50 },
      { key: 'wh',      label: 'Bodega',        width: 60 },
      { key: 'cost',    label: 'Compra',        width: 48, align: 'right' },
      { key: 'sale',    label: 'Venta',         width: 48, align: 'right' },
      { key: 'meli',    label: 'M. Libre',      width: 48, align: 'right' },
      { key: 'redes',   label: 'Redes/Shopy',   width: 50, align: 'right' },
      { key: 'stock',   label: 'Stock',         width: 30, align: 'right' },
      { key: 'gain',    label: 'Ganancia',      width: 48, align: 'right' },
      { key: 'pct',     label: '% costo',       width: 40, align: 'right' }
    ];
    const tableWidth = cols.reduce((s, c) => s + c.width, 0);
    const colX = {}; { let cx = marginX; cols.forEach(c => { colX[c.key] = cx; cx += c.width; }); }

    const fontSize = 7.6;
    const rowH = 17;
    const headerH = 19;
    const cellPad = 4;

    function fit(text, maxWidth) {
      let t = String(text ?? '');
      if (t === '' || doc.getTextWidth(t) <= maxWidth) return t;
      while (t.length > 1 && doc.getTextWidth(t + '…') > maxWidth) t = t.slice(0, -1);
      return t.length <= 1 ? '…' : t + '…';
    }

    function drawGrid(y, h) {
      doc.setDrawColor(...LINE_COLOR);
      doc.setLineWidth(0.5);
      let x = marginX;
      cols.forEach(c => { doc.line(x, y, x, y + h); x += c.width; });
      doc.line(x, y, x, y + h);
      doc.line(marginX, y + h, marginX + tableWidth, y + h);
    }

    function drawTableHeader(y) {
      doc.setFillColor(...INK);
      doc.rect(marginX, y, tableWidth, headerH, 'F');
      doc.setFont(undefined, 'bold');
      doc.setFontSize(fontSize);
      doc.setTextColor(...WHITE);
      cols.forEach(c => {
        const label = fit(c.label, c.width - cellPad * 2);
        const tx = c.align === 'right' ? colX[c.key] + c.width - cellPad : colX[c.key] + cellPad;
        doc.text(label, tx, y + headerH - 6, { align: c.align === 'right' ? 'right' : 'left' });
      });
      doc.setDrawColor(...WHITE);
      doc.setLineWidth(0.5);
      let x = marginX;
      cols.forEach(c => { doc.line(x, y, x, y + headerH); x += c.width; });
      doc.line(x, y, x, y + headerH);
      doc.setTextColor(...INK);
      return y + headerH;
    }

    function drawRow(y, dataMap, opts) {
      opts = opts || {};
      if (opts.fill) { doc.setFillColor(...opts.fill); doc.rect(marginX, y, tableWidth, rowH, 'F'); }
      doc.setFont(undefined, opts.bold ? 'bold' : 'normal');
      doc.setFontSize(fontSize);
      cols.forEach(c => {
        const avail = c.width - cellPad * 2;
        const raw = dataMap[c.key];
        const text = fit(raw, avail);
        const tx = c.align === 'right' ? colX[c.key] + c.width - cellPad : colX[c.key] + cellPad;
        let color = INK;
        if (c.key === 'sale' && raw) color = GREEN;
        else if (c.key === 'meli' && raw) color = ORANGE;
        doc.setTextColor(...color);
        doc.text(text, tx, y + rowH - 5, { align: c.align === 'right' ? 'right' : 'left' });
      });
      drawGrid(y, rowH);
    }

    doc.setFont(undefined, 'bold');
    doc.setFontSize(14);
    doc.setTextColor(...INK);
    doc.text('Inventario FQS', marginX, 26);
    doc.setFont(undefined, 'normal');
    doc.setFontSize(9);
    doc.setTextColor(90, 110, 125);
    doc.text(`Generado el ${new Date().toLocaleDateString('es-CO', { day: 'numeric', month: 'long', year: 'numeric' })}  ·  ${products.length} productos`, marginX, 40);

    let y = marginTop;
    y = drawTableHeader(y);

    let rowIndex = 0;
    let totalCost = 0, totalSale = 0, totalStock = 0, totalGain = 0;

    products.forEach(p => {
      const { gain, pct } = calcMargin(p);
      const priced = gain !== null;
      if (priced) { totalCost += (Number(p.cost) || 0) * (Number(p.stock) || 0); totalSale += (Number(p.sale) || 0) * (Number(p.stock) || 0); totalGain += gain * (Number(p.stock) || 0); }
      totalStock += Number(p.stock) || 0;

      const rowData = {
        name: p.name || '', desc: p.descripcion || '', sku: p.sku || '', cat: p.cat || '',
        provider: p.provider || '', wh: p.warehouse || '',
        cost: hasPrice(p.cost) ? fmtNum(p.cost) : '', sale: hasPrice(p.sale) ? fmtNum(p.sale) : '',
        meli: hasPrice(p.meli) ? fmtNum(p.meli) : '', redes: hasPrice(p.redes) ? fmtNum(p.redes) : '',
        stock: String(p.stock), gain: gain === null ? '' : fmtNum(gain), pct: pct === null ? '' : pct.toFixed(1) + '%'
      };

      if (y + rowH > pageH - marginBottom) {
        doc.addPage();
        y = drawTableHeader(marginTop);
        rowIndex = 0;
      }
      drawRow(y, rowData, { fill: rowIndex % 2 === 1 ? ZEBRA_COLOR : null });
      y += rowH;
      rowIndex++;
    });

    if (y + rowH > pageH - marginBottom) { doc.addPage(); y = drawTableHeader(marginTop); }
    drawRow(y, {
      name: `TOTALES (${products.length} productos)`, desc: '', sku: '', cat: '', provider: '', wh: '',
      cost: fmtNum(totalCost), sale: fmtNum(totalSale), meli: '', redes: '',
      stock: `${totalStock} u.`, gain: fmtNum(totalGain), pct: ''
    }, { fill: TOTALS_BG, bold: true });

    const totalPages = doc.internal.getNumberOfPages();
    for (let i = 1; i <= totalPages; i++) {
      doc.setPage(i);
      doc.setFont(undefined, 'normal');
      doc.setFontSize(8);
      doc.setTextColor(150, 165, 178);
      doc.text(`Página ${i} de ${totalPages}`, pageW - marginX, pageH - 14, { align: 'right' });
    }

    doc.save(`inventario_${new Date().toISOString().slice(0,10)}.pdf`);
    showToast('PDF generado');
  });

  function currentUserLabel() {
    return currentUser && USERS[currentUser] ? USERS[currentUser].label : '—';
  }

  function tryLogin() {
    const u = document.getElementById('login-user').value;
    const p = document.getElementById('login-pass').value;
    const errEl = document.getElementById('login-error');
    if (!u || !USERS[u]) {
      errEl.textContent = 'Selecciona tu usuario.';
      errEl.style.display = 'block';
      return;
    }
    if (p !== USERS[u].password) {
      errEl.textContent = 'Contraseña incorrecta.';
      errEl.style.display = 'block';
      return;
    }
    currentUser = u;
    errEl.style.display = 'none';
    document.getElementById('login-overlay').style.display = 'none';
    document.getElementById('session-user-label').textContent = currentUserLabel();
    document.getElementById('session-info').style.display = 'block';
    if (!dataLoaded) {
      dataLoaded = true;
      document.getElementById('inv-datestamp').textContent = new Date().toLocaleDateString('es-CO', { day: 'numeric', month: 'long', year: 'numeric' });
      load();
    }
  }

  function logout() {
    currentUser = null;
    document.getElementById('login-user').value = '';
    document.getElementById('login-pass').value = '';
    document.getElementById('login-error').style.display = 'none';
    document.getElementById('session-info').style.display = 'none';
    document.getElementById('login-overlay').style.display = 'flex';
    closeForm();
  }

  document.getElementById('login-submit').addEventListener('click', tryLogin);
  document.getElementById('pw-toggle').addEventListener('click', () => {
    const input = document.getElementById('login-pass');
    const show = document.getElementById('pw-icon-show');
    const hide = document.getElementById('pw-icon-hide');
    const isPw = input.type === 'password';
    input.type = isPw ? 'text' : 'password';
    show.style.display = isPw ? 'none' : 'block';
    hide.style.display = isPw ? 'block' : 'none';
  });
  document.getElementById('login-pass').addEventListener('keydown', (e) => { if (e.key === 'Enter') tryLogin(); });
  document.getElementById('login-user').addEventListener('keydown', (e) => { if (e.key === 'Enter') document.getElementById('login-pass').focus(); });
  document.getElementById('btn-logout').addEventListener('click', logout);
})();
</script>
