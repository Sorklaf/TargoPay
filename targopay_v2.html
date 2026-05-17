<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>TargoPay</title>
<link rel="icon" type="image/png" href="targobank-icon.jpeg">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">
<style>
/* ================================================================
   DESIGN-SYSTEM
   Primärfarben: Weiß (#FFFFFF) + Targobank-Blau (#2233b3)
   Minimalistisch, clean, modern
================================================================ */
:root {
  --blue:        #2233b3;
  --blue-dark:   #1a278a;
  --blue-light:  #e8ebf8;
  --blue-mid:    #3347cc;
  --white:       #ffffff;
  --bg:          #f4f6fb;
  --surface:     #ffffff;
  --border:      #e2e6f0;
  --text:        #111827;
  --text-muted:  #6b7280;
  --text-light:  #9ca3af;
  --green:       #287d13;
  --green-bg:    #edfce8;
  --red:         #bd1c1c;
  --red-bg:      #fef2f2;
  --orange:      #d97706;
  --card-color:  #2233b3;  /* Karten-Farbe, anpassbar */
  --nav-h:       72px;
}

* { margin:0; padding:0; box-sizing:border-box; -webkit-tap-highlight-color:transparent; }
body {
  font-family:'Inter',sans-serif;
  background:#d0d5e8;
  color:var(--text);
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  overflow:hidden;
}

/* ===== PHONE FRAME ===== */
.phone-frame {
  width:390px; height:844px;
  background:var(--bg);
  border-radius:44px;
  position:relative;
  overflow:hidden;
  box-shadow:
    0 0 0 1px rgba(0,0,0,0.15),
    0 40px 120px rgba(0,0,0,0.35),
    inset 0 1px 0 rgba(255,255,255,0.9);
}

/* ===== SCREENS ===== */
.screen {
  position:absolute; inset:0;
  display:flex; flex-direction:column;
  opacity:0; pointer-events:none;
  transition:opacity 0.3s ease, transform 0.3s ease;
  transform:translateX(24px);
  background:var(--bg);
}
.screen.active { opacity:1; pointer-events:all; transform:translateX(0); }
.screen.slide-out { opacity:0; transform:translateX(-24px); }

/* ===== STATUS BAR ===== */
.status-bar {
  display:flex; justify-content:space-between; align-items:center;
  padding:14px 28px 6px;
  font-size:12px; font-family:'Space Mono',monospace;
  color:var(--text-muted);
  flex-shrink:0;
  background:var(--bg);
}
.status-bar .time { font-weight:700; color:var(--text); font-size:15px; }

/* ===== BOTTOM NAV ===== */
.bottom-nav {
  position:absolute; bottom:0; left:0; right:0;
  height:var(--nav-h);
  background:var(--blue);
  display:flex; align-items:center; justify-content:space-around;
  padding:0 8px 10px;
  z-index:100;
  border-radius:0 0 44px 44px;
}
.nav-item {
  display:flex; flex-direction:column; align-items:center; gap:4px;
  cursor:pointer; padding:8px 16px; border-radius:14px;
  transition:background 0.2s;
  min-width:60px;
}
.nav-item:active { background:rgba(255,255,255,0.15); }
.nav-item svg { width:22px; height:22px; stroke:rgba(255,255,255,0.6); fill:none; stroke-width:1.8; transition:stroke 0.2s; }
.nav-item.active svg { stroke:#ffffff; }
.nav-item .nav-label { font-size:10px; font-weight:500; color:rgba(255,255,255,0.6); transition:color 0.2s; }
.nav-item.active .nav-label { color:#ffffff; }
/* Aktiver Indikator-Punkt */
.nav-item.active::before {
  content:''; position:absolute; top:0;
  width:32px; height:3px;
  background:#ffffff; border-radius:0 0 3px 3px;
}
.nav-item { position:relative; }

/* ===== CONTENT AREA (mit Platz für Nav) ===== */
.content-area {
  flex:1; overflow-y:auto; padding-bottom:calc(var(--nav-h) + 8px);
  scrollbar-width:none;
}
.content-area::-webkit-scrollbar { display:none; }

/* ===== PAGE HEADER ===== */
.page-header {
  padding:8px 20px 16px;
  flex-shrink:0;
}
.page-title { font-size:22px; font-weight:700; color:var(--text); letter-spacing:-0.4px; }
.page-subtitle { font-size:13px; color:var(--text-muted); margin-top:2px; }

/* ===== CARDS ===== */
.card-base {
  background:var(--surface);
  border-radius:16px;
  border:1px solid var(--border);
  overflow:hidden;
}

/* ===== BUTTONS ===== */
.btn-primary {
  width:100%; padding:16px;
  background:var(--blue);
  border:none; border-radius:14px;
  color:#fff; font-size:15px; font-weight:600;
  font-family:'Inter',sans-serif;
  cursor:pointer;
  transition:background 0.15s, transform 0.1s;
  box-shadow:0 4px 16px rgba(34,51,179,0.3);
}
.btn-primary:active { background:var(--blue-dark); transform:scale(0.98); }
.btn-primary:disabled { opacity:0.5; cursor:not-allowed; transform:none; }

.btn-secondary {
  width:100%; padding:13px;
  background:var(--blue-light);
  border:1px solid var(--blue);
  border-radius:14px;
  color:var(--blue); font-size:14px; font-weight:600;
  font-family:'Inter',sans-serif;
  cursor:pointer;
  transition:background 0.15s;
  margin-top:8px;
}
.btn-secondary:active { background:#d0d7f5; }

.btn-ghost {
  width:100%; padding:13px;
  background:transparent;
  border:1px solid var(--border);
  border-radius:14px;
  color:var(--text-muted); font-size:14px; font-weight:500;
  font-family:'Inter',sans-serif;
  cursor:pointer;
  transition:background 0.15s;
  margin-top:8px;
}
.btn-ghost:active { background:var(--border); }

/* ===== FORM ===== */
.form-group { margin-bottom:14px; }
.form-label {
  font-size:11px; font-weight:600;
  color:var(--text-muted);
  text-transform:uppercase; letter-spacing:0.07em;
  margin-bottom:6px; display:block;
}
.form-input {
  width:100%;
  background:var(--bg);
  border:1.5px solid var(--border);
  border-radius:12px;
  padding:12px 14px;
  color:var(--text);
  font-family:'Inter',sans-serif; font-size:14px;
  outline:none;
  transition:border-color 0.2s, box-shadow 0.2s;
}
.form-input:focus {
  border-color:var(--blue);
  box-shadow:0 0 0 3px rgba(34,51,179,0.1);
}
.form-input::placeholder { color:var(--text-light); }

/* ===== NOTICE BOXES ===== */
.notice-green {
  background:var(--green-bg); border:1px solid #a7f3d0;
  border-radius:12px; padding:12px 14px;
  font-size:12px; color:var(--green); line-height:1.5;
  margin-bottom:12px;
}
.notice-blue {
  background:var(--blue-light); border:1px solid rgba(34,51,179,0.2);
  border-radius:12px; padding:12px 14px;
  font-size:12px; color:var(--blue); line-height:1.5;
  margin-bottom:12px;
}
.notice-red {
  background:var(--red-bg); border:1px solid #fecaca;
  border-radius:12px; padding:12px 14px;
  font-size:12px; color:var(--red); line-height:1.5;
  margin-bottom:12px;
}
.notice-orange {
  background:#fffbeb; border:1px solid #fde68a;
  border-radius:12px; padding:12px 14px;
  font-size:12px; color:var(--orange); line-height:1.5;
  margin-bottom:12px;
}

/* ===== BACK BUTTON ===== */
.back-btn {
  width:38px; height:38px;
  background:var(--surface); border:1px solid var(--border);
  border-radius:12px;
  display:flex; align-items:center; justify-content:center;
  cursor:pointer; flex-shrink:0;
  transition:background 0.15s;
}
.back-btn:active { background:var(--border); }
.back-btn svg { width:18px; height:18px; stroke:var(--text); fill:none; stroke-width:2.2; }

.screen-header {
  display:flex; align-items:center; gap:12px;
  padding:8px 20px 16px; flex-shrink:0;
}
.screen-title { font-size:20px; font-weight:700; }

/* ================================================================
   HOME SCREEN
================================================================ */
#home { background:var(--bg); }

.home-top {
  background:var(--blue);
  padding:0 20px 24px;
  border-radius:0 0 28px 28px;
  flex-shrink:0;
}
.home-top .status-bar { background:transparent; }
.home-top .time { color:rgba(255,255,255,0.9); }
.home-top .status-bar { color:rgba(255,255,255,0.6); }

.home-greeting { font-size:13px; color:rgba(255,255,255,0.7); font-weight:500; margin-bottom:2px; }
.home-name { font-size:24px; font-weight:700; color:#fff; letter-spacing:-0.4px; }
.live-badge {
  display:inline-flex; align-items:center; gap:5px;
  background:rgba(255,255,255,0.15);
  border:1px solid rgba(255,255,255,0.25);
  border-radius:100px; padding:3px 10px;
  font-size:11px; color:rgba(255,255,255,0.9);
  margin-top:6px;
}
.live-dot { width:6px; height:6px; background:#4ade80; border-radius:50%; animation:blink-dot 1.5s infinite; }
@keyframes blink-dot { 0%,100%{opacity:0.4} 50%{opacity:1} }

/* ===== VIRTUELLE KARTE ===== */
.card-wrapper { padding:20px 20px 0; flex-shrink:0; }
.virtual-card {
  background:var(--card-color);
  border-radius:20px;
  padding:22px;
  position:relative;
  overflow:hidden;
  aspect-ratio:1.586;
  display:flex; flex-direction:column; justify-content:space-between;
  box-shadow:0 12px 40px rgba(34,51,179,0.35);
  cursor:pointer;
  transition:transform 0.2s;
  border:2px solid rgba(0,0,0,0.15);
}
.virtual-card:active { transform:scale(0.98); }
/* Glanz-Overlay */
.card-gloss {
  position:absolute; inset:0;
  background:linear-gradient(135deg,rgba(255,255,255,0.18) 0%,transparent 60%);
  pointer-events:none;
}
.card-top { display:flex; justify-content:space-between; align-items:flex-start; position:relative; }
.card-chip {
  width:34px; height:26px;
  background:linear-gradient(135deg,#e8c97e,#c8a84b);
  border-radius:5px; position:relative; overflow:hidden;
}
.card-chip::before { content:''; position:absolute; top:50%; left:0; right:0; height:1px; background:rgba(0,0,0,0.2); transform:translateY(-50%); }
.card-chip::after  { content:''; position:absolute; left:50%; top:0; bottom:0; width:1px; background:rgba(0,0,0,0.2); transform:translateX(-50%); }

/* Targobank Logo auf der Karte */
.card-bank-logo {
  display:flex; align-items:center; gap:6px;
}
.card-bank-logo img {
  height:22px; filter:brightness(0) invert(1);
  opacity:0.92;
}

.card-iban-short {
  font-family:'Space Mono',monospace;
  font-size:14px; letter-spacing:0.2em;
  color:rgba(255,255,255,0.85);
  position:relative;
}
.card-bottom { display:flex; justify-content:space-between; align-items:flex-end; position:relative; }
.card-holder { font-size:11px; font-weight:600; text-transform:uppercase; letter-spacing:0.1em; color:rgba(255,255,255,0.75); }
.card-currency { font-family:'Space Mono',monospace; font-size:11px; color:rgba(255,255,255,0.6); }
.card-mc { display:flex; }
.card-mc-c { width:26px; height:26px; border-radius:50%; }
.card-mc-c:first-child { background:#eb001b; margin-right:-9px; }
.card-mc-c:last-child  { background:#f79e1b; opacity:0.9; }

/* ===== BALANCE ===== */
.balance-section { padding:16px 20px 12px; flex-shrink:0; }
.balance-label { font-size:11px; font-weight:600; color:var(--text-muted); text-transform:uppercase; letter-spacing:0.07em; margin-bottom:4px; }
.balance-amount { font-size:38px; font-weight:700; letter-spacing:-1.5px; color:var(--text); }
.balance-amount.positive { color:#287d13; }
.balance-amount.negative { color:#bd1c1c; }
.balance-amount .cur { font-size:20px; font-weight:400; color:var(--text-muted); margin-right:3px; }
.balance-iban { font-size:11px; color:var(--text-light); font-family:'Space Mono',monospace; margin-top:3px; }

/* ===== QUICK ACTIONS ===== */
.quick-actions { display:grid; grid-template-columns:repeat(3,1fr); gap:10px; padding:0 20px 16px; flex-shrink:0; }
.qa-btn { display:flex; flex-direction:column; align-items:center; gap:6px; cursor:pointer; transition:transform 0.15s; }
.qa-btn:active { transform:scale(0.92); }
.qa-icon {
  width:54px; height:54px;
  background:var(--surface); border-radius:16px;
  display:flex; align-items:center; justify-content:center;
  border:1px solid var(--border);
  box-shadow:0 2px 8px rgba(0,0,0,0.06);
}
.qa-btn.primary .qa-icon { background:var(--blue); border-color:transparent; box-shadow:0 4px 16px rgba(34,51,179,0.3); }
.qa-btn.primary .qa-icon svg { stroke:#fff; }
.qa-icon svg { width:20px; height:20px; stroke:var(--blue); fill:none; stroke-width:1.8; }
.qa-label { font-size:10px; font-weight:500; color:var(--text-muted); text-align:center; }

/* ===== TRANSAKTIONEN ===== */
.section-header { display:flex; justify-content:space-between; align-items:center; padding:0 20px 10px; flex-shrink:0; }
.section-title { font-size:16px; font-weight:600; color:var(--text); }
.section-link { font-size:12px; color:var(--blue); font-weight:500; cursor:pointer; }

.tx-item { display:flex; align-items:center; gap:12px; padding:12px 20px; border-bottom:1px solid var(--border); background:var(--surface); }
.tx-item:first-child { border-radius:16px 16px 0 0; }
.tx-item:last-child  { border-radius:0 0 16px 16px; border-bottom:none; }
.tx-icon { width:40px; height:40px; background:var(--blue-light); border-radius:12px; display:flex; align-items:center; justify-content:center; font-size:16px; flex-shrink:0; }
.tx-info { flex:1; min-width:0; }
.tx-name { font-size:14px; font-weight:500; color:var(--text); margin-bottom:2px; white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
.tx-date { font-size:11px; color:var(--text-muted); }
.tx-amount { font-size:13px; font-weight:600; font-family:'Space Mono',monospace; flex-shrink:0; }
.tx-amount.debit  { color:var(--text); }
.tx-amount.credit { color:#287d13; }

/* Monats-Trennzeile */
.tx-month-header {
  font-size:11px; font-weight:700; color:var(--text-muted);
  text-transform:uppercase; letter-spacing:0.08em;
  padding:14px 20px 6px;
}
.tx-month-header:first-child { padding-top:4px; }

/* Refresh-Button beim Kontostand */
.balance-refresh-btn {
  background:none; border:none; cursor:pointer;
  padding:4px; margin-left:6px; vertical-align:middle;
  display:inline-flex; align-items:center;
  opacity:0.55; transition:opacity 0.15s, transform 0.4s;
}
.balance-refresh-btn:hover { opacity:1; }
.balance-refresh-btn.spinning svg { animation:spin-once 0.7s linear; }
@keyframes spin-once { from{transform:rotate(0deg)} to{transform:rotate(360deg)} }
.balance-refresh-btn svg { width:15px; height:15px; stroke:var(--text); fill:none; stroke-width:2; }
.loading-tx { text-align:center; padding:32px 20px; color:var(--text-muted); font-size:13px; background:var(--surface); border-radius:16px; }

/* ================================================================
   KONTOSTAND / ÜBERSICHT SCREEN
================================================================ */
#overview { background:var(--bg); }
.overview-balance-card {
  margin:0 20px 16px;
  background:var(--blue);
  border-radius:20px;
  padding:24px;
  color:#fff;
}
.ovb-label { font-size:12px; color:rgba(255,255,255,0.7); font-weight:500; margin-bottom:6px; }
.ovb-amount { font-size:42px; font-weight:700; letter-spacing:-2px; }
.ovb-amount .cur { font-size:22px; font-weight:400; opacity:0.7; margin-right:4px; }
.ovb-iban { font-size:11px; font-family:'Space Mono',monospace; color:rgba(255,255,255,0.6); margin-top:6px; }
.ovb-meta { display:flex; gap:16px; margin-top:14px; }
.ovb-meta-item { flex:1; background:rgba(255,255,255,0.1); border-radius:12px; padding:10px 12px; }
.ovb-meta-label { font-size:10px; color:rgba(255,255,255,0.6); font-weight:500; margin-bottom:3px; }
.ovb-meta-value { font-size:14px; font-weight:600; color:#fff; }

.tx-filter { display:flex; gap:8px; padding:0 20px 12px; overflow-x:auto; scrollbar-width:none; flex-shrink:0; }
.tx-filter::-webkit-scrollbar { display:none; }
.filter-chip {
  padding:7px 14px; border-radius:100px;
  background:var(--surface); border:1.5px solid var(--border);
  font-size:12px; font-weight:500; color:var(--text-muted);
  cursor:pointer; white-space:nowrap; flex-shrink:0;
  transition:all 0.15s;
}
.filter-chip.active { background:var(--blue); border-color:var(--blue); color:#fff; }

/* ================================================================
   ÜBERWEISUNG SCREEN
================================================================ */
#transfer { background:var(--bg); }
.transfer-body { flex:1; overflow-y:auto; padding:0 20px; scrollbar-width:none; }
.transfer-body::-webkit-scrollbar { display:none; }
.transfer-cta { padding:12px 20px 20px; flex-shrink:0; }

/* Girocode-Scanner Button */
.scan-btn {
  display:flex; align-items:center; gap:10px;
  width:100%; padding:14px 16px;
  background:var(--blue-light); border:1.5px dashed var(--blue);
  border-radius:14px; cursor:pointer;
  font-size:14px; font-weight:600; color:var(--blue);
  font-family:'Inter',sans-serif;
  transition:background 0.15s;
  margin-bottom:16px;
}
.scan-btn:active { background:#d0d7f5; }
.scan-btn svg { width:20px; height:20px; stroke:var(--blue); fill:none; stroke-width:1.8; flex-shrink:0; }

/* QR-Scanner Modal */
.qr-modal {
  position:absolute; inset:0; z-index:200;
  background:#000;
  display:flex; flex-direction:column;
  opacity:0; pointer-events:none;
  transition:opacity 0.25s;
}
.qr-modal.open { opacity:1; pointer-events:all; }
.qr-video-wrap { flex:1; position:relative; overflow:hidden; }
#qr-video { width:100%; height:100%; object-fit:cover; }
.qr-overlay {
  position:absolute; inset:0;
  display:flex; align-items:center; justify-content:center;
}
.qr-frame {
  width:220px; height:220px;
  border:2px solid rgba(255,255,255,0.8);
  border-radius:20px;
  box-shadow:0 0 0 9999px rgba(0,0,0,0.55);
  position:relative;
}
.qr-corner {
  position:absolute; width:24px; height:24px;
  border-color:var(--blue); border-style:solid;
}
.qr-corner.tl { top:-2px; left:-2px; border-width:3px 0 0 3px; border-radius:4px 0 0 0; }
.qr-corner.tr { top:-2px; right:-2px; border-width:3px 3px 0 0; border-radius:0 4px 0 0; }
.qr-corner.bl { bottom:-2px; left:-2px; border-width:0 0 3px 3px; border-radius:0 0 0 4px; }
.qr-corner.br { bottom:-2px; right:-2px; border-width:0 3px 3px 0; border-radius:0 0 4px 0; }
.qr-scan-line {
  position:absolute; left:0; right:0; height:2px;
  background:linear-gradient(90deg,transparent,var(--blue),transparent);
  animation:scan-anim 2s linear infinite;
}
@keyframes scan-anim { 0%{top:0} 100%{top:100%} }
.qr-hint { color:rgba(255,255,255,0.8); font-size:13px; text-align:center; margin-top:16px; }
.qr-close-bar {
  padding:16px 20px 24px;
  background:#111;
  display:flex; flex-direction:column; gap:8px;
}
.qr-status { font-size:13px; color:rgba(255,255,255,0.7); text-align:center; min-height:18px; }

/* ================================================================
   EINSTELLUNGEN SCREEN
================================================================ */
#settings { background:var(--bg); }
.settings-body { flex:1; overflow-y:auto; padding:0 20px; scrollbar-width:none; }
.settings-body::-webkit-scrollbar { display:none; }

.settings-section { margin-bottom:20px; }
.settings-section-title {
  font-size:11px; font-weight:600; color:var(--text-muted);
  text-transform:uppercase; letter-spacing:0.07em;
  padding:0 4px; margin-bottom:8px;
}
.settings-group {
  background:var(--surface); border-radius:16px;
  border:1px solid var(--border); overflow:hidden;
}
.settings-row {
  display:flex; align-items:center; gap:12px;
  padding:14px 16px; border-bottom:1px solid var(--border);
  cursor:pointer; transition:background 0.15s;
}
.settings-row:last-child { border-bottom:none; }
.settings-row:active { background:var(--bg); }
.settings-row-icon {
  width:36px; height:36px;
  background:var(--blue-light); border-radius:10px;
  display:flex; align-items:center; justify-content:center;
  flex-shrink:0;
}
.settings-row-icon svg { width:18px; height:18px; stroke:var(--blue); fill:none; stroke-width:1.8; }
.settings-row-content { flex:1; min-width:0; }
.settings-row-label { font-size:14px; font-weight:500; color:var(--text); }
.settings-row-value { font-size:12px; color:var(--text-muted); margin-top:1px; white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
.settings-row-arrow { color:var(--text-light); font-size:16px; }

/* Token-Status in Einstellungen */
.token-badge {
  display:inline-flex; align-items:center; gap:5px;
  padding:3px 8px; border-radius:100px;
  font-size:11px; font-weight:500;
}
.token-badge.ok     { background:var(--green-bg); color:var(--green); }
.token-badge.warn   { background:#fffbeb; color:var(--orange); }
.token-badge.err    { background:var(--red-bg); color:var(--red); }
.token-badge-dot    { width:6px; height:6px; border-radius:50%; }
.token-badge.ok   .token-badge-dot { background:var(--green); }
.token-badge.warn .token-badge-dot { background:var(--orange); }
.token-badge.err  .token-badge-dot { background:var(--red); }

/* Farb-Picker für Karte */
.color-picker-row {
  display:flex; gap:10px; flex-wrap:wrap;
  padding:14px 16px;
}
.color-swatch {
  width:36px; height:36px; border-radius:10px;
  cursor:pointer; border:2px solid transparent;
  transition:transform 0.15s, border-color 0.15s;
  flex-shrink:0;
}
.color-swatch:active { transform:scale(0.9); }
.color-swatch.selected { border-color:var(--text); transform:scale(1.1); }
.color-swatch-custom {
  width:36px; height:36px; border-radius:10px;
  border:2px dashed var(--border);
  display:flex; align-items:center; justify-content:center;
  cursor:pointer; font-size:18px; color:var(--text-muted);
  flex-shrink:0;
  transition:background 0.15s;
}
.color-swatch-custom:active { background:var(--bg); }
input[type="color"] { display:none; }

/* ================================================================
   KONTO-HINTERLEGEN SCREEN (im Setup / Einstellungen)
================================================================ */
#setup-screen { background:var(--bg); }
.setup-body { flex:1; overflow-y:auto; padding:0 20px; scrollbar-width:none; }
.setup-body::-webkit-scrollbar { display:none; }
.setup-step-card {
  background:var(--surface); border:1px solid var(--border);
  border-radius:16px; padding:16px; margin-bottom:12px;
}
.setup-step-header { display:flex; align-items:center; gap:10px; margin-bottom:14px; }
.step-badge {
  width:28px; height:28px; background:var(--blue);
  border-radius:8px; display:flex; align-items:center; justify-content:center;
  font-size:12px; font-weight:700; color:#fff; flex-shrink:0;
}
.step-title { font-size:14px; font-weight:600; color:var(--text); }

/* Token-Status in Setup */
.token-status-box { margin-bottom:12px; }
.token-status-row {
  display:flex; align-items:flex-start; gap:8px;
  padding:10px 12px; border-radius:12px;
  font-size:12px; line-height:1.5;
}
.token-status-row.ok   { background:var(--green-bg); border:1px solid #a7f3d0; color:var(--green); }
.token-status-row.warn { background:#fffbeb; border:1px solid #fde68a; color:var(--orange); }
.token-status-row.err  { background:var(--red-bg); border:1px solid #fecaca; color:var(--red); }
.ts-dot { width:7px; height:7px; border-radius:50%; flex-shrink:0; margin-top:3px; }
.token-status-row.ok   .ts-dot { background:var(--green); }
.token-status-row.warn .ts-dot { background:var(--orange); }
.token-status-row.err  .ts-dot { background:var(--red); }

/* ================================================================
   AMOUNT + PAY + SUCCESS (minimalistisch)
================================================================ */
#amount { background:var(--bg); }
.amount-display {
  display:flex; flex-direction:column; align-items:center;
  justify-content:center; flex:1; gap:10px;
}
.amount-hint { font-size:13px; color:var(--text-muted); }
.amount-number {
  font-size:60px; font-weight:700; letter-spacing:-3px;
  color:var(--text); display:flex; align-items:center;
}
.amount-cursor {
  width:3px; height:52px; background:var(--blue);
  border-radius:2px; animation:blink 1s step-end infinite; margin-left:4px;
}
@keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }
.numpad { display:grid; grid-template-columns:repeat(3,1fr); gap:10px; padding:0 20px 20px; flex-shrink:0; }
.num-key {
  padding:18px; background:var(--surface); border-radius:14px;
  border:1px solid var(--border); font-size:22px; font-weight:500;
  text-align:center; cursor:pointer; transition:background 0.1s;
  user-select:none; color:var(--text);
}
.num-key:active { background:var(--border); }
.num-key.del { background:var(--red-bg); border-color:#fecaca; color:var(--red); }
.num-key.confirm { background:var(--blue); border-color:transparent; font-size:16px; color:#fff; font-weight:700; box-shadow:0 4px 16px rgba(34,51,179,0.3); }

#pay { background:var(--bg); }
.nfc-area { flex:1; display:flex; flex-direction:column; align-items:center; justify-content:center; padding:0 32px; gap:20px; }
.nfc-ring { position:relative; width:180px; height:180px; display:flex; align-items:center; justify-content:center; }
.nfc-ring-outer { position:absolute; width:180px; height:180px; border:2px solid rgba(34,51,179,0.12); border-radius:50%; animation:pulse-ring 2.5s ease-in-out infinite; }
.nfc-ring-mid   { position:absolute; width:140px; height:140px; border:2px solid rgba(34,51,179,0.2);  border-radius:50%; animation:pulse-ring 2.5s ease-in-out infinite 0.4s; }
.nfc-ring-inner { position:absolute; width:100px; height:100px; border:2px solid rgba(34,51,179,0.35); border-radius:50%; animation:pulse-ring 2.5s ease-in-out infinite 0.8s; }
.nfc-center { width:68px; height:68px; background:var(--blue); border-radius:50%; display:flex; align-items:center; justify-content:center; box-shadow:0 0 40px rgba(34,51,179,0.4); z-index:1; }
.nfc-center svg { width:30px; height:30px; fill:#fff; }
@keyframes pulse-ring { 0%{transform:scale(0.95);opacity:0.4} 50%{transform:scale(1.05);opacity:1} 100%{transform:scale(0.95);opacity:0.4} }
.pay-amount-display { text-align:center; }
.pay-amount-label { font-size:12px; color:var(--text-muted); text-transform:uppercase; letter-spacing:0.07em; margin-bottom:6px; }
.pay-amount-value { font-size:46px; font-weight:700; letter-spacing:-2px; color:var(--text); }
.pay-amount-value sup { font-size:20px; font-weight:400; vertical-align:super; color:var(--text-muted); }
.pay-instruction { text-align:center; font-size:13px; color:var(--text-muted); line-height:1.5; }
.pay-instruction strong { color:var(--text); display:block; font-size:15px; font-weight:600; margin-bottom:4px; }
.scan-status { display:flex; align-items:center; gap:8px; padding:9px 16px; background:var(--surface); border-radius:100px; border:1px solid var(--border); font-size:12px; color:var(--text-muted); }
.scan-dot { width:8px; height:8px; background:var(--blue); border-radius:50%; animation:blink-dot 1.2s ease-in-out infinite; }
.pay-method-selector { display:flex; gap:8px; padding:0 20px; flex-shrink:0; }
.method-chip { flex:1; padding:10px 6px; background:var(--surface); border-radius:12px; border:1.5px solid var(--border); text-align:center; cursor:pointer; font-size:11px; font-weight:500; transition:all 0.2s; color:var(--text-muted); }
.method-chip.selected { border-color:var(--blue); background:var(--blue-light); color:var(--blue); }
.method-chip .mc-icon { font-size:14px; display:block; margin-bottom:3px; }
.security-badge { display:flex; align-items:center; gap:8px; padding:9px 16px; background:var(--green-bg); border:1px solid #a7f3d0; border-radius:12px; margin:10px 20px 0; font-size:11px; color:var(--green); flex-shrink:0; }
.security-badge svg { width:14px; height:14px; fill:var(--green); flex-shrink:0; }
.pay-cta { padding:12px 20px 20px; flex-shrink:0; }

#success { background:var(--bg); align-items:center; justify-content:center; gap:16px; }
.success-icon { width:84px; height:84px; background:var(--green); border-radius:50%; display:flex; align-items:center; justify-content:center; box-shadow:0 0 50px rgba(5,150,105,0.35); animation:pop-in 0.5s cubic-bezier(0.34,1.56,0.64,1) forwards; }
@keyframes pop-in { from{transform:scale(0);opacity:0} to{transform:scale(1);opacity:1} }
.success-icon svg { width:40px; height:40px; stroke:#fff; fill:none; stroke-width:3; }
.success-text { text-align:center; }
.success-text h2 { font-size:24px; font-weight:700; margin-bottom:4px; }
.success-text p  { font-size:13px; color:var(--text-muted); }
.success-amount { font-size:42px; font-weight:700; letter-spacing:-2px; color:var(--green); }
.success-meta { background:var(--surface); border-radius:18px; padding:16px; width:calc(100% - 40px); border:1px solid var(--border); }
.meta-row { display:flex; justify-content:space-between; align-items:center; padding:7px 0; }
.meta-row:not(:last-child) { border-bottom:1px solid var(--border); }
.meta-label { font-size:12px; color:var(--text-muted); }
.meta-value { font-size:12px; font-weight:600; font-family:'Space Mono',monospace; color:var(--text); }
.success-cta { padding:0 20px; width:100%; }
.notice-banner { background:var(--blue-light); border-top:1px solid rgba(34,51,179,0.15); padding:10px 20px; font-size:11px; color:var(--blue); line-height:1.5; text-align:center; flex-shrink:0; }

/* ================================================================
   CONNECTING SCREEN
================================================================ */
#connecting { background:var(--bg); align-items:center; justify-content:center; gap:20px; }
.connecting-spinner { width:64px; height:64px; border:3px solid var(--blue-light); border-top-color:var(--blue); border-radius:50%; animation:spin 0.8s linear infinite; }
@keyframes spin { to{transform:rotate(360deg)} }
.connecting-title { font-size:20px; font-weight:700; color:var(--text); }
.connecting-sub { font-size:13px; color:var(--text-muted); text-align:center; padding:0 40px; line-height:1.5; }
.connecting-steps { display:flex; flex-direction:column; gap:8px; width:calc(100% - 40px); }
.c-step { display:flex; align-items:center; gap:10px; padding:12px 14px; background:var(--surface); border-radius:12px; border:1px solid var(--border); font-size:13px; color:var(--text-muted); transition:all 0.3s; }
.c-step.done   { border-color:#a7f3d0; color:var(--green); background:var(--green-bg); }
.c-step.active { border-color:rgba(34,51,179,0.3); color:var(--text); background:var(--blue-light); }
.c-step-dot { width:8px; height:8px; border-radius:50%; background:var(--border); flex-shrink:0; transition:background 0.3s; }
.c-step.done   .c-step-dot { background:var(--green); }
.c-step.active .c-step-dot { background:var(--blue); animation:blink-dot 0.8s infinite; }

@media (max-width:420px) { .phone-frame { width:100vw; height:100vh; border-radius:0; } }

/* ================================================================
   TRANSAKTIONS-DETAIL MODAL
================================================================ */
.tx-detail-overlay {
  position:absolute; inset:0; z-index:300;
  background:rgba(0,0,0,0.45);
  display:flex; align-items:flex-end;
  opacity:0; pointer-events:none;
  transition:opacity 0.22s ease;
  backdrop-filter:blur(2px);
}
.tx-detail-overlay.open { opacity:1; pointer-events:all; }
.tx-detail-sheet {
  width:100%; background:#fff;
  border-radius:24px 24px 0 0;
  padding:0 0 32px;
  transform:translateY(100%);
  transition:transform 0.28s cubic-bezier(0.34,1.2,0.64,1);
  max-height:82%;
  display:flex; flex-direction:column;
}
.tx-detail-overlay.open .tx-detail-sheet { transform:translateY(0); }
.tx-detail-handle {
  width:36px; height:4px; background:#e2e8f0;
  border-radius:2px; margin:12px auto 0;
  flex-shrink:0;
}
.tx-detail-header {
  display:flex; align-items:center; gap:14px;
  padding:16px 20px 14px;
  border-bottom:1px solid var(--border);
  flex-shrink:0;
}
.tx-detail-icon {
  width:48px; height:48px; border-radius:14px;
  background:var(--blue-light);
  display:flex; align-items:center; justify-content:center;
  font-size:22px; flex-shrink:0;
}
.tx-detail-title { flex:1; min-width:0; }
.tx-detail-name {
  font-size:15px; font-weight:600; color:var(--text);
  white-space:nowrap; overflow:hidden; text-overflow:ellipsis;
}
.tx-detail-status {
  font-size:11px; color:var(--text-muted); margin-top:2px;
}
.tx-detail-close {
  width:32px; height:32px; border-radius:50%;
  background:var(--bg); border:none; cursor:pointer;
  display:flex; align-items:center; justify-content:center;
  flex-shrink:0;
}
.tx-detail-close svg { width:16px; height:16px; stroke:var(--text-muted); fill:none; stroke-width:2; }
.tx-detail-amount {
  text-align:center; padding:20px 20px 16px;
  font-size:36px; font-weight:700; letter-spacing:-1.5px;
  font-family:'Space Mono',monospace;
  flex-shrink:0;
}
.tx-detail-amount.credit { color:var(--green); }
.tx-detail-amount.debit  { color:var(--text); }
.tx-detail-rows {
  flex:1; overflow-y:auto; padding:0 20px;
  scrollbar-width:none;
}
.tx-detail-rows::-webkit-scrollbar { display:none; }
.tx-detail-row {
  display:flex; justify-content:space-between; align-items:flex-start;
  padding:11px 0;
  border-bottom:1px solid var(--border);
  gap:12px;
}
.tx-detail-row:last-child { border-bottom:none; }
.tx-detail-row-label {
  font-size:12px; color:var(--text-muted); font-weight:500;
  flex-shrink:0; padding-top:1px;
}
.tx-detail-row-value {
  font-size:13px; color:var(--text); font-weight:500;
  text-align:right; word-break:break-all;
}
.tx-detail-row-value.mono { font-family:'Space Mono',monospace; font-size:12px; }
.tx-detail-action-row {
  padding:16px 20px 0;
  display:flex; gap:10px;
  flex-shrink:0;
}
.tx-detail-action-btn {
  flex:1; padding:13px 0;
  border-radius:14px; border:none; cursor:pointer;
  font-size:13px; font-weight:600; font-family:'Inter',sans-serif;
  transition:opacity 0.15s;
}
.tx-detail-action-btn:active { opacity:0.75; }
.tx-detail-action-btn.primary { background:var(--blue); color:#fff; }
.tx-detail-action-btn.secondary { background:var(--blue-light); color:var(--blue); }
.tx-item { cursor:pointer; transition:background 0.12s; }
.tx-item:active { background:#f1f5f9; }
</style>
</head>
<body>
<div class="phone-frame">

<!-- ================================================================
     HOME SCREEN
================================================================ -->
<div class="screen active" id="home">
  <div class="home-top">
    <div class="status-bar"><span class="time">09:41</span><span>●●●</span></div>
    <div class="home-greeting" id="greeting-text">Guten Morgen</div>
    <div class="home-name" id="display-name">Targobank</div>
    <div class="live-badge"><div class="live-dot"></div>Live · GoCardless PSD2</div>
  </div>

  <div class="content-area">
    <!-- Virtuelle Karte -->
    <div class="card-wrapper">
      <div class="virtual-card" id="virtual-card">
        <div class="card-gloss"></div>
        <div class="card-top">
          <div class="card-bank-logo">
            <img id="card-logo-img" src="targobank-logo.png" alt="TARGOBANK">
          </div>
        </div>
        <div class="card-iban-short" id="display-iban-short">•••• •••• •••• ••••</div>
        <div class="card-bottom">
          <div>
            <div class="card-holder" id="display-owner">–</div>
            <div class="card-currency" id="display-currency">EUR</div>
          </div>
        </div>
      </div>
    </div>

    <!-- Kontostand -->
    <div class="balance-section">
      <div class="balance-label">Verfügbares Guthaben</div>
      <div class="balance-amount" id="display-balance-wrap">
        <span class="cur">€</span><span id="display-balance">–</span>
        <button class="balance-refresh-btn" id="balance-refresh-btn" onclick="refreshBalanceBtn()" title="Aktualisieren">
          <svg viewBox="0 0 24 24"><polyline points="23 4 23 10 17 10"/><polyline points="1 20 1 14 7 14"/><path d="M3.51 9a9 9 0 0 1 14.85-3.36L23 10M1 14l4.64 4.36A9 9 0 0 0 20.49 15"/></svg>
        </button>
      </div>
      <div class="balance-iban" id="display-iban">IBAN wird geladen…</div>
    </div>

    <!-- Quick Actions -->
    <div class="quick-actions" style="grid-template-columns:repeat(2,1fr);">
      <div class="qa-btn primary" onclick="navTo('transfer')">
        <div class="qa-icon">
          <svg viewBox="0 0 24 24"><line x1="5" y1="9" x2="19" y2="9"/><polyline points="15 4 20 9 15 14"/><line x1="19" y1="15" x2="5" y2="15"/><polyline points="9 10 4 15 9 20"/></svg>
        </div>
        <div class="qa-label">Überweisen</div>
      </div>
      <div class="qa-btn" onclick="refreshData()">
        <div class="qa-icon">
          <svg viewBox="0 0 24 24"><polyline points="23 4 23 10 17 10"/><polyline points="1 20 1 14 7 14"/><path d="M3.51 9a9 9 0 0 1 14.85-3.36L23 10M1 14l4.64 4.36A9 9 0 0 0 20.49 15"/></svg>
        </div>
        <div class="qa-label">Aktualisieren</div>
      </div>
    </div>

    <!-- Transaktionen -->
    <div class="section-header">
      <div class="section-title">Letzte Buchungen</div>
      <div class="section-link" onclick="refreshData()">Alle ansehen</div>
    </div>
    <div style="padding:0 20px 8px;" id="tx-list">
      <div class="loading-tx">⏳ Lade Transaktionen…</div>
    </div>
  </div>

  <!-- Bottom Nav -->
  <div class="bottom-nav">
    <div class="nav-item active" id="nav-home" onclick="navTo('home')">
      <svg viewBox="0 0 24 24"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
      <span class="nav-label">Start</span>
    </div>
    <div class="nav-item" id="nav-overview" onclick="navTo('overview')">
      <svg viewBox="0 0 24 24"><line x1="12" y1="1" x2="12" y2="23"/><path d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/></svg>
      <span class="nav-label">Kontostand</span>
    </div>
    <div class="nav-item" id="nav-transfer" onclick="navTo('transfer')">
      <svg viewBox="0 0 24 24"><line x1="5" y1="9" x2="19" y2="9"/><polyline points="15 4 20 9 15 14"/><line x1="19" y1="15" x2="5" y2="15"/><polyline points="9 10 4 15 9 20"/></svg>
      <span class="nav-label">Überweisung</span>
    </div>
    <div class="nav-item" id="nav-settings" onclick="navTo('settings')">
      <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06-.06a2 2 0 0 1-2.83-2.83l.06-.06A1.65 1.65 0 0 0 4.68 15a1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06A1.65 1.65 0 0 0 9 4.68a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06A1.65 1.65 0 0 0 19.4 9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
      <span class="nav-label">Einstellungen</span>
    </div>
  </div>
</div>

<!-- ================================================================
     KONTOSTAND / ÜBERSICHT SCREEN
================================================================ -->
<div class="screen" id="overview">
  <div class="status-bar"><span class="time">09:41</span></div>
  <div class="page-header">
    <div class="page-title">Kontoübersicht</div>
    <div class="page-subtitle" id="ov-last-update">Zuletzt aktualisiert: –</div>
  </div>

  <div class="content-area">
    <div class="overview-balance-card">
      <div style="display:flex;align-items:center;justify-content:space-between;">
        <div class="ovb-label">Verfügbares Guthaben</div>
        <button onclick="refreshBalanceBtn()" id="ov-refresh-btn" style="background:none;border:none;cursor:pointer;padding:2px;opacity:0.7;" title="Aktualisieren">
          <svg viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" width="16" height="16"><polyline points="23 4 23 10 17 10"/><polyline points="1 20 1 14 7 14"/><path d="M3.51 9a9 9 0 0 1 14.85-3.36L23 10M1 14l4.64 4.36A9 9 0 0 0 20.49 15"/></svg>
        </button>
      </div>
      <div class="ovb-amount"><span class="cur">€</span><span id="ov-balance">–</span></div>
      <div class="ovb-iban" id="ov-iban">IBAN wird geladen…</div>
      <div class="ovb-meta">
        <div class="ovb-meta-item">
          <div class="ovb-meta-label">Kontoinhaber</div>
          <div class="ovb-meta-value" id="ov-owner">–</div>
        </div>
        <div class="ovb-meta-item">
          <div class="ovb-meta-label">Währung</div>
          <div class="ovb-meta-value" id="ov-currency">EUR</div>
        </div>
      </div>
    </div>

    <div class="tx-filter">
      <div class="filter-chip active" onclick="filterTx('all', this)">Alle</div>
      <div class="filter-chip" onclick="filterTx('credit', this)">Eingang</div>
      <div class="filter-chip" onclick="filterTx('debit', this)">Ausgang</div>
      <div class="filter-chip" onclick="filterTx('pending', this)">Ausstehend</div>
    </div>

    <div style="padding:0 20px 8px;" id="ov-tx-list">
      <div class="loading-tx">⏳ Lade Transaktionen…</div>
    </div>
  </div>

  <div class="bottom-nav">
    <div class="nav-item" id="nav-home2" onclick="navTo('home')">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
      <span class="nav-label">Start</span>
    </div>
    <div class="nav-item active" id="nav-overview2">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><line x1="12" y1="1" x2="12" y2="23"/><path d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/></svg>
      <span class="nav-label">Kontostand</span>
    </div>
    <div class="nav-item" id="nav-transfer2" onclick="navTo('transfer')">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><line x1="5" y1="9" x2="19" y2="9"/><polyline points="15 4 20 9 15 14"/><line x1="19" y1="15" x2="5" y2="15"/><polyline points="9 10 4 15 9 20"/></svg>
      <span class="nav-label">Überweisung</span>
    </div>
    <div class="nav-item" id="nav-settings2" onclick="navTo('settings')">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06-.06a2 2 0 0 1-2.83-2.83l.06-.06A1.65 1.65 0 0 0 4.68 15a1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06A1.65 1.65 0 0 0 9 4.68a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06A1.65 1.65 0 0 0 19.4 9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
      <span class="nav-label">Einstellungen</span>
    </div>
  </div>
</div>

<!-- ================================================================
     ÜBERWEISUNG SCREEN
================================================================ -->
<div class="screen" id="transfer">
  <div class="status-bar"><span class="time">09:41</span></div>
  <div class="screen-header">
    <div class="back-btn" onclick="navTo('home')"><svg viewBox="0 0 24 24"><polyline points="15 18 9 12 15 6"/></svg></div>
    <div class="screen-title">SEPA-Überweisung</div>
  </div>

  <div class="transfer-body">
    <!-- Girocode-Scanner -->
    <button class="scan-btn" onclick="openQrScanner()">
      <svg viewBox="0 0 29 29" fill="none" xmlns="http://www.w3.org/2000/svg" style="width:24px;height:24px;flex-shrink:0;">
        <!-- Finder oben links -->
        <rect x="1" y="1" width="11" height="11" rx="2" fill="#111827"/>
        <rect x="3" y="3" width="7" height="7" rx="1" fill="white"/>
        <rect x="5" y="5" width="3" height="3" fill="#111827"/>
        <!-- Finder oben rechts -->
        <rect x="17" y="1" width="11" height="11" rx="2" fill="#111827"/>
        <rect x="19" y="3" width="7" height="7" rx="1" fill="white"/>
        <rect x="21" y="5" width="3" height="3" fill="#111827"/>
        <!-- Finder unten links -->
        <rect x="1" y="17" width="11" height="11" rx="2" fill="#111827"/>
        <rect x="3" y="19" width="7" height="7" rx="1" fill="white"/>
        <rect x="5" y="21" width="3" height="3" fill="#111827"/>
        <!-- Datenmodule unten rechts -->
        <rect x="17" y="17" width="4" height="4" rx="0.5" fill="#111827"/>
        <rect x="23" y="17" width="4" height="4" rx="0.5" fill="#111827"/>
        <rect x="17" y="23" width="4" height="4" rx="0.5" fill="#111827"/>
        <rect x="23" y="23" width="4" height="4" rx="0.5" fill="#111827"/>
        <rect x="20" y="20" width="2" height="2" rx="0.3" fill="#111827"/>
      </svg>
      Girocode scannen – Felder automatisch ausfüllen
    </button>

    <div class="notice-blue">💡 Überweisungen werden per GoCardless PIS initiiert. Für die Bestätigung wirst du zur Targobank-Authentifizierung weitergeleitet (SCA).</div>

    <div class="form-group"><label class="form-label">Empfänger Name</label><input class="form-input" id="t-name" type="text" placeholder="Max Mustermann"></div>
    <div class="form-group"><label class="form-label">IBAN des Empfängers</label><input class="form-input" id="t-iban" type="text" placeholder="DE89 3704 0044 0532 0130 00"></div>
    <div class="form-group"><label class="form-label">BIC (optional)</label><input class="form-input" id="t-bic" type="text" placeholder="COBADEFFXXX"></div>
    <div class="form-group"><label class="form-label">Betrag (€)</label><input class="form-input" id="t-amount" type="number" placeholder="0.00" step="0.01" min="0.01"></div>
    <div class="form-group"><label class="form-label">Verwendungszweck</label><input class="form-input" id="t-ref" type="text" placeholder="Rechnung Nr. 2024-001"></div>
    <div class="notice-orange">⚠️ GoCardless PIS benötigt eine PIS-Berechtigung in deinem GoCardless-Account.</div>
  </div>
  <div class="transfer-cta">
    <button class="btn-primary" onclick="initiateTransfer()">Überweisung initiieren →</button>
  </div>

  <!-- QR-Scanner Modal (innerhalb des Transfer-Screens) -->
  <div class="qr-modal" id="qr-modal">
    <div class="qr-video-wrap">
      <video id="qr-video" autoplay playsinline muted></video>
      <div class="qr-overlay">
        <div>
          <div class="qr-frame">
            <div class="qr-corner tl"></div>
            <div class="qr-corner tr"></div>
            <div class="qr-corner bl"></div>
            <div class="qr-corner br"></div>
            <div class="qr-scan-line"></div>
          </div>
          <div class="qr-hint">Girocode in den Rahmen halten</div>
        </div>
      </div>
    </div>
    <div class="qr-close-bar">
      <div class="qr-status" id="qr-status">Kamera wird gestartet…</div>
      <button class="btn-ghost" style="color:#fff;border-color:rgba(255,255,255,0.2);" onclick="closeQrScanner()">Abbrechen</button>
    </div>
  </div>
</div>

<!-- ================================================================
     EINSTELLUNGEN SCREEN
================================================================ -->
<div class="screen" id="settings">
  <div class="status-bar"><span class="time">09:41</span></div>
  <div class="page-header">
    <div class="page-title">Einstellungen</div>
  </div>

  <div class="content-area">
    <div class="settings-body">

      <!-- TOKEN STATUS -->
      <div class="settings-section">
        <div class="settings-section-title">API-Status</div>
        <div class="settings-group">
          <div class="settings-row" style="cursor:default;">
            <div class="settings-row-icon"><svg viewBox="0 0 24 24"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label">GoCardless Token</div>
              <div id="settings-token-status" class="settings-row-value">Wird geprüft…</div>
            </div>
          </div>
        </div>
      </div>

      <!-- KONTO HINTERLEGEN -->
      <div class="settings-section">
        <div class="settings-section-title">Konto</div>
        <div class="settings-group">
          <div class="settings-row" onclick="showScreen('setup-screen')">
            <div class="settings-row-icon"><svg viewBox="0 0 24 24"><rect x="1" y="4" width="22" height="16" rx="2"/><line x1="1" y1="10" x2="23" y2="10"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label">Konto hinterlegen</div>
              <div class="settings-row-value" id="settings-account-val">Kein Konto verbunden</div>
            </div>
            <div class="settings-row-arrow">›</div>
          </div>
          <div class="settings-row" onclick="refreshData()">
            <div class="settings-row-icon"><svg viewBox="0 0 24 24"><polyline points="23 4 23 10 17 10"/><polyline points="1 20 1 14 7 14"/><path d="M3.51 9a9 9 0 0 1 14.85-3.36L23 10M1 14l4.64 4.36A9 9 0 0 0 20.49 15"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label">Daten aktualisieren</div>
              <div class="settings-row-value">Kontostand &amp; Transaktionen neu laden</div>
            </div>
            <div class="settings-row-arrow">›</div>
          </div>
        </div>
      </div>

      <!-- KARTEN-DESIGN -->
      <div class="settings-section">
        <div class="settings-section-title">Karten-Design</div>
        <div class="settings-group">
          <div class="settings-row" style="cursor:default; flex-direction:column; align-items:flex-start; gap:10px;">
            <div style="display:flex;align-items:center;gap:12px;width:100%;">
              <div class="settings-row-icon"><svg viewBox="0 0 24 24"><rect x="1" y="4" width="22" height="16" rx="2"/><line x1="1" y1="10" x2="23" y2="10"/></svg></div>
              <div class="settings-row-content">
                <div class="settings-row-label">Kartenfarbe</div>
                <div class="settings-row-value">Wähle eine Farbe für deine virtuelle Karte</div>
              </div>
            </div>
            <div class="color-picker-row">
              <div class="color-swatch selected" style="background:#2233b3;" data-color="#2233b3" onclick="setCardColor('#2233b3', this)"></div>
              <div class="color-swatch" style="background:#111827;" data-color="#111827" onclick="setCardColor('#111827', this)"></div>
              <div class="color-swatch" style="background:#059669;" data-color="#059669" onclick="setCardColor('#059669', this)"></div>
              <div class="color-swatch" style="background:#dc2626;" data-color="#dc2626" onclick="setCardColor('#dc2626', this)"></div>
              <div class="color-swatch" style="background:#7c3aed;" data-color="#7c3aed" onclick="setCardColor('#7c3aed', this)"></div>
              <div class="color-swatch" style="background:#d97706;" data-color="#d97706" onclick="setCardColor('#d97706', this)"></div>
              <div class="color-swatch" style="background:#0891b2;" data-color="#0891b2" onclick="setCardColor('#0891b2', this)"></div>
              <div class="color-swatch-custom" onclick="document.getElementById('custom-color-input').click()" title="Eigene Farbe">+</div>
              <input type="color" id="custom-color-input" value="#2233b3" onchange="setCardColor(this.value, null)">
            </div>
          </div>
        </div>
      </div>

      <!-- SICHERHEIT & DATENSCHUTZ -->
      <div class="settings-section">
        <div class="settings-section-title">Sicherheit &amp; Datenschutz</div>
        <div class="settings-group">
          <div class="settings-row" style="cursor:default;">
            <div class="settings-row-icon"><svg viewBox="0 0 24 24"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label">Datenspeicherung</div>
              <div class="settings-row-value">Ausschließlich lokal (localStorage) – keine Übertragung</div>
            </div>
          </div>
          <div class="settings-row" onclick="clearAllData()">
            <div class="settings-row-icon" style="background:#fef2f2;"><svg viewBox="0 0 24 24" style="stroke:#dc2626;"><polyline points="3 6 5 6 21 6"/><path d="M19 6l-1 14a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2L5 6"/><path d="M10 11v6"/><path d="M14 11v6"/><path d="M9 6V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label" style="color:#dc2626;">Alle Daten löschen</div>
              <div class="settings-row-value">Zugangsdaten und Token zurücksetzen</div>
            </div>
            <div class="settings-row-arrow">›</div>
          </div>
        </div>
      </div>

      <!-- BENACHRICHTIGUNGEN -->
      <div class="settings-section">
        <div class="settings-section-title">Anzeige</div>
        <div class="settings-group">
          <div class="settings-row" style="cursor:default;">
            <div class="settings-row-icon"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="12"/><line x1="12" y1="16" x2="12.01" y2="16"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label">Transaktionen anzeigen</div>
              <div class="settings-row-value">Max. 25 Buchungen auf der Startseite</div>
            </div>
          </div>
          <div class="settings-row" style="cursor:default;">
            <div class="settings-row-icon"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 8v4l3 3"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label">Zugriffsdauer</div>
              <div class="settings-row-value">GoCardless: 90 Tage Kontodatenzugriff</div>
            </div>
          </div>
        </div>
      </div>

      <!-- APP-INFO -->
      <div class="settings-section">
        <div class="settings-section-title">App-Info</div>
        <div class="settings-group">
          <div class="settings-row" style="cursor:default;">
            <div class="settings-row-icon"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><line x1="12" y1="16" x2="12" y2="12"/><line x1="12" y1="8" x2="12.01" y2="8"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label">TargoPay</div>
              <div class="settings-row-value">Version 2.0 · GoCardless PSD2 · Open Banking</div>
            </div>
          </div>
          <div class="settings-row" style="cursor:default;">
            <div class="settings-row-icon"><svg viewBox="0 0 24 24"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg></div>
            <div class="settings-row-content">
              <div class="settings-row-label">Regulierung</div>
              <div class="settings-row-value">PSD2 · AISP-Nutzung · Privatperson · BaFin-lizenzfrei</div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>

  <div class="bottom-nav">
    <div class="nav-item" onclick="navTo('home')">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
      <span class="nav-label">Start</span>
    </div>
    <div class="nav-item" onclick="navTo('overview')">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><line x1="12" y1="1" x2="12" y2="23"/><path d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/></svg>
      <span class="nav-label">Kontostand</span>
    </div>
    <div class="nav-item" onclick="navTo('transfer')">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><line x1="5" y1="9" x2="19" y2="9"/><polyline points="15 4 20 9 15 14"/><line x1="19" y1="15" x2="5" y2="15"/><polyline points="9 10 4 15 9 20"/></svg>
      <span class="nav-label">Überweisung</span>
    </div>
    <div class="nav-item active">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06-.06a2 2 0 0 1-2.83-2.83l.06-.06A1.65 1.65 0 0 0 4.68 15a1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06A1.65 1.65 0 0 0 9 4.68a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06A1.65 1.65 0 0 0 19.4 9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
      <span class="nav-label">Einstellungen</span>
    </div>
  </div>
</div>

<!-- ================================================================
     KONTO HINTERLEGEN / SETUP SCREEN
================================================================ -->
<div class="screen" id="setup-screen">
  <div class="status-bar"><span class="time">09:41</span></div>
  <div class="screen-header">
    <div class="back-btn" onclick="showScreen('settings')"><svg viewBox="0 0 24 24"><polyline points="15 18 9 12 15 6"/></svg></div>
    <div class="screen-title">Konto hinterlegen</div>
  </div>

  <div class="setup-body">
    <div class="notice-green">✅ Als Privatperson mit Zugriff nur auf eigene Konten benötigst du keine BaFin-Lizenz. Daten laufen ausschließlich zwischen dir und GoCardless.</div>

    <div id="token-status-box" style="display:none;" class="token-status-box"></div>

    <div class="setup-step-card">
      <div class="setup-step-header"><div class="step-badge">1</div><div class="step-title">GoCardless API-Zugangsdaten</div></div>
      <div class="form-group"><label class="form-label">Secret ID</label><input class="form-input" id="cfg-secret-id" type="text" placeholder="xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx" autocomplete="off" spellcheck="false"></div>
      <div class="form-group"><label class="form-label">Secret Key</label><input class="form-input" id="cfg-secret-key" type="password" placeholder="Dein GoCardless Secret Key" autocomplete="new-password"></div>
      <div style="font-size:11px;color:var(--text-muted);line-height:1.5;">Kostenlos erstellen auf <a href="https://bankaccountdata.gocardless.com/user-secrets/" target="_blank" style="color:var(--blue);">bankaccountdata.gocardless.com</a> → Developers → User secrets</div>
    </div>

    <div class="setup-step-card">
      <div class="setup-step-header"><div class="step-badge">2</div><div class="step-title">Targobank-Konto verknüpfen</div></div>
      <div class="form-group"><label class="form-label">Requisition ID (nach Bank-Login)</label><input class="form-input" id="cfg-req-id" type="text" placeholder="xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx" autocomplete="off" spellcheck="false"></div>
      <div style="font-size:11px;color:var(--text-muted);line-height:1.5;margin-bottom:10px;">Wird nach dem ersten Bank-Login automatisch erzeugt:</div>
      <button class="btn-secondary" onclick="startRequisition()">🔗 Targobank neu verknüpfen</button>
    </div>

    <div class="setup-step-card">
      <div class="setup-step-header"><div class="step-badge">3</div><div class="step-title">Konto-ID auswählen</div></div>
      <div class="form-group"><label class="form-label">Account ID</label><input class="form-input" id="cfg-account-id" type="text" placeholder="xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx" autocomplete="off" spellcheck="false"></div>
      <div style="font-size:11px;color:var(--text-muted);line-height:1.5;margin-bottom:10px;">Nach der Verknüpfung automatisch abrufbar:</div>
      <button class="btn-secondary" onclick="fetchAccounts()">📋 Konten abrufen &amp; auswählen</button>
    </div>

    <div class="notice-orange">⚠️ Zugangsdaten werden ausschließlich lokal im Browser (localStorage) gespeichert und nie weitergegeben.</div>
  </div>

  <div style="padding:12px 20px 20px; flex-shrink:0;">
    <button class="btn-primary" id="connect-btn" onclick="saveAndConnect()">Verbindung herstellen →</button>
  </div>
</div>

<!-- ================================================================
     CONNECTING SCREEN
================================================================ -->
<div class="screen" id="connecting">
  <div class="connecting-spinner"></div>
  <div class="connecting-title">Verbinde…</div>
  <div class="connecting-sub" id="connecting-sub-text">Authentifizierung über GoCardless PSD2</div>
  <div class="connecting-steps">
    <div class="c-step" id="cs1"><div class="c-step-dot"></div>Token prüfen / generieren</div>
    <div class="c-step" id="cs2"><div class="c-step-dot"></div>Kontodaten abrufen</div>
    <div class="c-step" id="cs3"><div class="c-step-dot"></div>Kontostand laden</div>
    <div class="c-step" id="cs4"><div class="c-step-dot"></div>Transaktionen laden</div>
  </div>
</div>

<!-- amount / pay / success screens entfernt (nur Simulation, nicht funktional) -->

<!-- Transaktions-Detail Modal -->
<div class="tx-detail-overlay" id="tx-detail-overlay" onclick="closeTxDetail(event)">
  <div class="tx-detail-sheet" id="tx-detail-sheet">
    <div class="tx-detail-handle"></div>
    <div class="tx-detail-header">
      <div class="tx-detail-icon" id="txd-icon">💳</div>
      <div class="tx-detail-title">
        <div class="tx-detail-name" id="txd-name">–</div>
        <div class="tx-detail-status" id="txd-status">–</div>
      </div>
      <button class="tx-detail-close" onclick="closeTxDetail()">
        <svg viewBox="0 0 24 24"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>
      </button>
    </div>
    <div class="tx-detail-amount" id="txd-amount">–</div>
    <div class="tx-detail-rows" id="txd-rows"></div>
    <div class="tx-detail-action-row">
      <button class="tx-detail-action-btn secondary" onclick="copyTxDetail()">Kopieren</button>
      <button class="tx-detail-action-btn primary" onclick="prefillTransfer()">Zurücküberweisen</button>
    </div>
  </div>
</div>

</div><!-- phone-frame -->

<!-- jsQR für Girocode-Scanning -->
<script src="https://cdn.jsdelivr.net/npm/jsqr@1.4.0/dist/jsQR.js"></script>

<script>
// ================================================================
//  GoCardless Bank Account Data API – TargoPay v2
//  Docs: https://developer.gocardless.com/bank-account-data/overview
// ================================================================
const GC_BASE = 'https://bankaccountdata.gocardless.com/api/v2';
const TARGO_INSTITUTION_ID = 'TARGOBANK_DETAR';

let cfg = {
  secretId:'', secretKey:'',
  requisitionId:'', accountId:'',
  accessToken:'', accessExpiry:0,
  refreshToken:'', refreshExpiry:0,
  _ibanShort:'', cardColor:'#2233b3'
};

// Alle geladenen Transaktionen (für Filter)
let allTxData = [];

// ================================================================
// CONFIG
// ================================================================
function loadConfig() {
  try { const s = localStorage.getItem('targoPayCfg'); if (s) cfg = {...cfg, ...JSON.parse(s)}; } catch(e) {}
  document.getElementById('cfg-secret-id').value   = cfg.secretId      || '';
  document.getElementById('cfg-secret-key').value  = cfg.secretKey     || '';
  document.getElementById('cfg-req-id').value      = cfg.requisitionId || '';
  document.getElementById('cfg-account-id').value  = cfg.accountId     || '';
  applyCardColor(cfg.cardColor || '#2233b3', false);
  renderTokenStatus();
  updateSettingsValues();
}
function saveConfig() {
  cfg.secretId      = document.getElementById('cfg-secret-id').value.trim();
  cfg.secretKey     = document.getElementById('cfg-secret-key').value.trim();
  cfg.requisitionId = document.getElementById('cfg-req-id').value.trim();
  cfg.accountId     = document.getElementById('cfg-account-id').value.trim();
  persistConfig();
}
function persistConfig() {
  try { localStorage.setItem('targoPayCfg', JSON.stringify(cfg)); } catch(e) {}
}
function updateSettingsValues() {
  const el = document.getElementById('settings-account-val');
  if (el) el.textContent = cfg.accountId ? cfg.accountId.slice(0,8) + '…' : 'Kein Konto verbunden';
}

// ================================================================
// KARTEN-FARBE
// ================================================================
function setCardColor(color, swatchEl) {
  applyCardColor(color, true);
  cfg.cardColor = color;
  persistConfig();
  // Swatch-Auswahl aktualisieren
  document.querySelectorAll('.color-swatch').forEach(s => s.classList.remove('selected'));
  if (swatchEl) swatchEl.classList.add('selected');
}
function applyCardColor(color, animate) {
  document.documentElement.style.setProperty('--card-color', color);
  const card = document.getElementById('virtual-card');
  if (card && animate) {
    card.style.transition = 'background 0.4s ease';
    card.style.background = color;
    setTimeout(() => { card.style.background = ''; }, 500);
  }
  // Swatch-Selektion synchronisieren
  document.querySelectorAll('.color-swatch').forEach(s => {
    s.classList.toggle('selected', s.dataset.color === color);
  });
}

// ================================================================
// TOKEN-STATUS
// ================================================================
function renderTokenStatus() {
  const box = document.getElementById('token-status-box');
  const settingsEl = document.getElementById('settings-token-status');
  if (!cfg.accessToken) {
    if (box) box.style.display = 'none';
    if (settingsEl) settingsEl.textContent = 'Nicht verbunden';
    return;
  }
  const now = Date.now();
  const accessLeft  = cfg.accessExpiry  - now;
  const refreshLeft = cfg.refreshExpiry - now;
  let cls, msg, shortMsg;
  if (refreshLeft <= 0) {
    cls = 'err'; msg = '⛔ Refresh Token abgelaufen – bitte neu verbinden.';
    shortMsg = 'Abgelaufen – neu verbinden';
  } else if (accessLeft <= 0) {
    cls = 'warn'; const days = Math.floor(refreshLeft / 86400000);
    msg = `⏳ Access Token abgelaufen – wird automatisch erneuert. Refresh Token noch ${days} Tag(e) gültig.`;
    shortMsg = `Wird erneuert · Refresh ${days}d`;
  } else {
    cls = 'ok'; const h = Math.floor(accessLeft/3600000), m = Math.floor((accessLeft%3600000)/60000);
    msg = `✅ Token gültig – noch ${h}h ${m}min.`;
    shortMsg = `Gültig · noch ${h}h ${m}min`;
  }
  if (box) {
    box.style.display = 'block';
    box.innerHTML = `<div class="token-status-row ${cls}"><div class="ts-dot"></div><span>${msg}</span></div>`;
  }
  if (settingsEl) {
    settingsEl.innerHTML = `<span class="token-badge ${cls}"><span class="token-badge-dot"></span>${shortMsg}</span>`;
  }
}

// ================================================================
// TOKEN-MANAGEMENT
// ================================================================
async function getToken() {
  const now = Date.now(), BUF = 60_000;
  if (cfg.accessToken && (cfg.accessExpiry - now) > BUF) return cfg.accessToken;
  if (cfg.refreshToken && (cfg.refreshExpiry - now) > BUF) return await refreshAccessToken();
  return await fetchNewTokenPair();
}
async function fetchNewTokenPair() {
  if (!cfg.secretId || !cfg.secretKey) throw new Error('Secret ID und Secret Key fehlen.');
  const res = await gcPost('/token/new/', { secret_id: cfg.secretId, secret_key: cfg.secretKey }, false);
  cfg.accessToken  = res.access;
  cfg.accessExpiry = Date.now() + (res.access_expires  - 60) * 1000;
  cfg.refreshToken = res.refresh;
  cfg.refreshExpiry= Date.now() + (res.refresh_expires - 60) * 1000;
  persistConfig(); renderTokenStatus(); return cfg.accessToken;
}
async function refreshAccessToken() {
  const res = await gcPost('/token/refresh/', { refresh: cfg.refreshToken }, false);
  cfg.accessToken  = res.access;
  cfg.accessExpiry = Date.now() + (res.access_expires - 60) * 1000;
  persistConfig(); renderTokenStatus(); return cfg.accessToken;
}

// ================================================================
// HTTP-HELPER
// ================================================================
async function gcGet(path) {
  const token = await getToken();
  const res = await fetch(`${GC_BASE}${path}`, { headers:{'Authorization':`Bearer ${token}`,'Accept':'application/json'} });
  return handleResponse(res, `GET ${path}`);
}
async function gcPost(path, body, withAuth=true) {
  const headers = {'Content-Type':'application/json','Accept':'application/json'};
  if (withAuth) { const token = await getToken(); headers['Authorization'] = `Bearer ${token}`; }
  const res = await fetch(`${GC_BASE}${path}`, { method:'POST', headers, body:JSON.stringify(body) });
  return handleResponse(res, `POST ${path}`);
}
async function handleResponse(res, label) {
  if (res.ok) return res.json();
  let e; try { e = await res.json(); } catch(_) { e = {}; }
  if (res.status === 429) {
    const s = e.detail?.match(/try again in (\d+) seconds/)?.[1];
    throw new RateLimitError(s ? `Rate Limit. Bitte ${s}s warten.` : 'Rate Limit. Kurz warten.', parseInt(s||'60',10));
  }
  if (res.status === 401) { cfg.accessToken=''; cfg.accessExpiry=0; persistConfig(); throw new Error('Nicht autorisiert (401). Bitte neu verbinden.'); }
  throw new Error(`${label} [${res.status}]: ${e.detail||e.summary||JSON.stringify(e)}`);
}
class RateLimitError extends Error {
  constructor(msg, s) { super(msg); this.name='RateLimitError'; this.retryAfter=s; }
}

// ================================================================
// REQUISITION
// ================================================================
async function startRequisition() {
  saveConfig();
  if (!cfg.secretId || !cfg.secretKey) { alert('Bitte Secret ID und Secret Key eingeben.'); return; }
  try {
    await getToken();
    const d = await gcPost('/requisitions/', {
      redirect: window.location.href.split('?')[0],
      institution_id: TARGO_INSTITUTION_ID,
      reference: 'targo-' + Date.now(),
      user_language: 'DE'
    });
    cfg.requisitionId = d.id;
    document.getElementById('cfg-req-id').value = d.id;
    persistConfig();
    window.location.href = d.link;
  } catch(e) { handleError('Requisition starten', e); }
}
async function fetchAccounts() {
  saveConfig();
  if (!cfg.requisitionId) { alert('Bitte zuerst Targobank verknüpfen.'); return; }
  try {
    const d = await gcGet(`/requisitions/${cfg.requisitionId}/`);
    const statusHints = { CR:'Bank-Login noch nicht abgeschlossen.', GC:'Zustimmung läuft.', UA:'Authentifizierung läuft.', RJ:'Abgelehnt – neu verknüpfen.', SA:'Kontoauswahl läuft.', GA:'Zugriff wird gewährt.', EX:'Abgelaufen – neu verknüpfen.' };
    if (d.status && d.status !== 'LN') { alert(`Noch nicht bereit.\n${statusHints[d.status]||'Status: '+d.status}`); return; }
    if (!d.accounts?.length) { alert('Keine Konten gefunden. Bitte neu verknüpfen.'); return; }
    const chosen = d.accounts.length === 1 ? d.accounts[0] : prompt(`${d.accounts.length} Konten:\n\n${d.accounts.join('\n')}\n\nWelche ID?`, d.accounts[0]);
    if (chosen) { cfg.accountId = chosen.trim(); document.getElementById('cfg-account-id').value = cfg.accountId; persistConfig(); alert('✅ Konto gespeichert.'); updateSettingsValues(); }
  } catch(e) { handleError('Konten abrufen', e); }
}
async function handlePostRedirect() {
  const params = new URLSearchParams(window.location.search);
  if (params.has('ref') || params.has('requisition_id') || params.has('error')) history.replaceState({}, document.title, window.location.pathname);
  if (params.has('error')) { alert(`Bank-Login fehlgeschlagen: ${params.get('error')}`); return; }
  if (!cfg.requisitionId) return;
  try {
    const d = await gcGet(`/requisitions/${cfg.requisitionId}/`);
    if (d.status === 'LN' && d.accounts?.length) { cfg.accountId = d.accounts[0]; document.getElementById('cfg-account-id').value = cfg.accountId; persistConfig(); await saveAndConnect(); }
  } catch(e) { console.warn('[TargoPay] Auto-Connect:', e.message); }
}

// ================================================================
// VERBINDUNG HERSTELLEN
// ================================================================
async function saveAndConnect() {
  saveConfig();
  if (!cfg.secretId || !cfg.secretKey) { alert('Bitte Secret ID und Secret Key eingeben.'); return; }
  if (!cfg.accountId) { alert('Bitte Konto-ID eingeben (Schritt 3).'); return; }
  const btn = document.getElementById('connect-btn');
  if (btn) { btn.disabled=true; btn.textContent='⏳ Verbinde…'; }
  showScreen('connecting');
  const steps = ['cs1','cs2','cs3','cs4'];
  const fns = [()=>getToken(), ()=>fetchDetails(), ()=>fetchBalance(), ()=>fetchTxs()];
  for (let i=0; i<fns.length; i++) {
    document.getElementById(steps[i]).className = 'c-step active';
    try { await fns[i](); document.getElementById(steps[i]).className = 'c-step done'; }
    catch(e) { document.getElementById(steps[i]).className='c-step'; if(btn){btn.disabled=false;btn.textContent='Verbindung herstellen →';} handleError(`Schritt ${i+1}`,e); showScreen('setup-screen'); return; }
    await delay(350);
  }
  if (btn) { btn.disabled=false; btn.textContent='Verbindung herstellen →'; }
  await delay(200);
  updateGreeting();
  updateSettingsValues();
  navTo('home');
}

// ================================================================
// DATEN ABRUFEN
// ================================================================
async function fetchDetails() {
  const d = await gcGet(`/accounts/${cfg.accountId}/details/`);
  const a = d.account;
  const iban  = a.iban || '–';
  const last4 = iban.replace(/\s/g,'').slice(-4);
  const owner = a.ownerName || a.displayName || a.name || 'Kontoinhaber';
  document.getElementById('display-name').textContent      = owner.split(' ')[0];
  document.getElementById('display-owner').textContent     = owner.toUpperCase();
  document.getElementById('display-currency').textContent  = a.currency || 'EUR';
  document.getElementById('display-iban').textContent      = iban;
  document.getElementById('display-iban-short').textContent= `•••• •••• •••• ${last4}`;
  // Übersicht-Screen
  const ovOwner = document.getElementById('ov-owner'); if(ovOwner) ovOwner.textContent = owner;
  const ovIban  = document.getElementById('ov-iban');  if(ovIban)  ovIban.textContent  = iban;
  const ovCur   = document.getElementById('ov-currency'); if(ovCur) ovCur.textContent  = a.currency||'EUR';
  cfg._ibanShort = last4; persistConfig();
}
async function fetchBalance() {
  const d = await gcGet(`/accounts/${cfg.accountId}/balances/`);
  const bals = d.balances || [];
  const b = bals.find(x=>x.balanceType==='interimAvailable') || bals.find(x=>x.balanceType==='closingBooked') || bals.find(x=>x.balanceType==='openingBooked') || bals[0];
  if (b) {
    const amt = parseFloat(b.balanceAmount.amount);
    const isPos = amt >= 0;
    const sign = isPos ? '+' : '';
    const fmt = sign + amt.toLocaleString('de-DE',{minimumFractionDigits:2,maximumFractionDigits:2});
    // Home screen
    const balEl = document.getElementById('display-balance');
    balEl.textContent = fmt;
    const wrap = document.getElementById('display-balance-wrap');
    if (wrap) {
      wrap.classList.toggle('positive', isPos);
      wrap.classList.toggle('negative', !isPos);
    }
    // Übersicht screen
    const ovBal = document.getElementById('ov-balance');
    if (ovBal) {
      ovBal.textContent = fmt;
      ovBal.style.color = isPos ? '#287d13' : '#bd1c1c';
    }
  }
  const lu = document.getElementById('ov-last-update');
  if(lu) lu.textContent = 'Zuletzt: ' + new Date().toLocaleTimeString('de-DE',{hour:'2-digit',minute:'2-digit'});
}
async function fetchTxs() {
  const d = await gcGet(`/accounts/${cfg.accountId}/transactions/`);
  allTxData = [...(d.transactions?.booked||[]), ...(d.transactions?.pending||[])];
  renderTxList(allTxData.slice(0,25), 'tx-list');
  renderTxList(allTxData.slice(0,50), 'ov-tx-list');
}
function renderTxList(txs, containerId) {
  const container = document.getElementById(containerId);
  if (!container) return;
  if (!txs.length) { container.innerHTML='<div class="loading-tx">Keine Transaktionen gefunden.</div>'; return; }

  // Transaktionen nach Monat gruppieren
  const groups = {}; // key: 'YYYY-MM' -> { label, txs[] }
  txs.forEach(tx => {
    const dateStr = tx.bookingDate || tx.valueDate || '';
    let key, label;
    if (dateStr) {
      const d = new Date(dateStr);
      key = d.getFullYear() + '-' + String(d.getMonth()+1).padStart(2,'0');
      label = d.toLocaleDateString('de-DE', {month:'long', year:'numeric'});
    } else {
      key = 'unbekannt'; label = 'Datum unbekannt';
    }
    if (!groups[key]) groups[key] = { label, txs: [] };
    groups[key].txs.push(tx);
  });

  let html = '';
  Object.keys(groups).sort((a,b) => b.localeCompare(a)).forEach(key => {
    const g = groups[key];
    html += `<div class="tx-month-header">${esc(g.label)}</div>`;
    html += g.txs.map(tx => {
      const amt = parseFloat(tx.transactionAmount?.amount||0);
      const isCredit = amt > 0;
      const fmtAmt = (isCredit?'+':'') + amt.toLocaleString('de-DE',{minimumFractionDigits:2,maximumFractionDigits:2}) + ' €';
      const name = tx.creditorName||tx.debtorName||tx.remittanceInformationUnstructured||'Transaktion';
      const raw  = tx.remittanceInformationUnstructured||'';
      const dateStr = tx.bookingDate||tx.valueDate||'';
      const dateFmt = dateStr ? new Date(dateStr).toLocaleDateString('de-DE',{day:'2-digit',month:'short'}) : '';
      const sub = (raw&&raw!==name) ? ' · '+esc(raw.slice(0,26)) : '';
      const isPending = !tx.bookingDate && tx.valueDate;
      const pendingTag = isPending ? ' <span style="font-size:10px;color:var(--orange);">(ausstehend)</span>' : '';
      const txIdx = allTxData.indexOf(tx);
      return `<div class="tx-item" onclick="openTxDetail(${txIdx})">
        <div class="tx-icon">${txEmoji(name,amt)}</div>
        <div class="tx-info"><div class="tx-name">${esc(name)}${pendingTag}</div><div class="tx-date">${dateFmt}${sub}</div></div>
        <div class="tx-amount ${isCredit?'credit':'debit'}">${fmtAmt}</div>
      </div>`;
    }).join('');
  });
  container.innerHTML = html;
}
function filterTx(type, chipEl) {
  document.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));
  if(chipEl) chipEl.classList.add('active');
  let filtered;
  if (type==='all')     filtered = allTxData;
  else if (type==='credit')  filtered = allTxData.filter(tx=>parseFloat(tx.transactionAmount?.amount||0)>0);
  else if (type==='debit')   filtered = allTxData.filter(tx=>parseFloat(tx.transactionAmount?.amount||0)<0);
  else if (type==='pending') filtered = allTxData.filter(tx=>!tx.bookingDate&&tx.valueDate);
  renderTxList((filtered||allTxData).slice(0,50), 'ov-tx-list');
}
async function refreshData() {
  const link = document.querySelector('.section-link');
  if(link) link.textContent='⏳ Lädt…';
  try { await fetchBalance(); await fetchTxs(); } catch(e) { handleError('Aktualisieren',e); }
  finally { if(link) link.textContent='Alle ansehen'; }
}

// ================================================================
// SEPA-ÜBERWEISUNG
// ================================================================
async function initiateTransfer() {
  const name = document.getElementById('t-name').value.trim();
  const iban = document.getElementById('t-iban').value.replace(/\s/g,'');
  const amt  = parseFloat(document.getElementById('t-amount').value);
  const ref  = document.getElementById('t-ref').value.trim() || 'Überweisung';
  if (!name||!iban||!amt||isNaN(amt)||amt<=0) { alert('Bitte alle Pflichtfelder korrekt ausfüllen.'); return; }
  const ibanClean = iban.toUpperCase().replace(/\s/g,'');
  if (!/^[A-Z]{2}[0-9]{2}[A-Z0-9]{11,30}$/.test(ibanClean)) { alert('Ungültige IBAN.'); return; }
  const ok = confirm(`Überweisung bestätigen?\n\nEmpfänger: ${name}\nIBAN: ${ibanClean}\nBetrag: €${amt.toFixed(2)}\nVerwendungszweck: ${ref}\n\nWeiterleitung zur Targobank-SCA.`);
  if (!ok) return;
  try {
    const token = await getToken();
    const body = { creditor_account:{iban:ibanClean}, creditor_name:name, instructed_amount:{currency:'EUR',amount:amt.toFixed(2)}, remittance_information_unstructured:ref, end_to_end_identification:('TARGO'+Date.now()).slice(0,35) };
    const res = await fetch(`${GC_BASE}/payments/`, { method:'POST', headers:{'Authorization':`Bearer ${token}`,'Content-Type':'application/json','Accept':'application/json'}, body:JSON.stringify(body) });
    const d = await handleResponse(res, 'POST /payments/');
    if (d.link) window.location.href = d.link;
    else { alert(`Initiiert. Status: ${d.status||'?'}`); navTo('home'); }
  } catch(e) { handleError('Überweisung',e); }
}

// ================================================================
// GIROCODE / EPC-QR SCANNER
//
// EPC-QR Format (11 Zeilen, newline-getrennt):
//   Zeile 1:  BCD          (Service Tag)
//   Zeile 2:  001 oder 002 (Version)
//   Zeile 3:  1            (Encoding: UTF-8)
//   Zeile 4:  SCT          (Identification: SEPA Credit Transfer)
//   Zeile 5:  BIC          (Empfänger-BIC, optional ab Version 002)
//   Zeile 6:  Name         (Empfänger-Name, max. 70 Zeichen)
//   Zeile 7:  IBAN         (Empfänger-IBAN)
//   Zeile 8:  EUR12.34     (Betrag, Format: EUR + Dezimalzahl)
//   Zeile 9:  (leer)       (Purpose Code, optional)
//   Zeile 10: (leer)       (Structured Reference, optional)
//   Zeile 11: Verwendungszweck (Unstructured Reference, optional)
// ================================================================
let qrStream = null;
let qrAnimFrame = null;

function openQrScanner() {
  const modal = document.getElementById('qr-modal');
  modal.classList.add('open');
  document.getElementById('qr-status').textContent = 'Kamera wird gestartet…';
  startQrCamera();
}
function closeQrScanner() {
  const modal = document.getElementById('qr-modal');
  modal.classList.remove('open');
  stopQrCamera();
}
async function startQrCamera() {
  try {
    qrStream = await navigator.mediaDevices.getUserMedia({ video:{ facingMode:'environment', width:{ideal:1280}, height:{ideal:720} } });
    const video = document.getElementById('qr-video');
    video.srcObject = qrStream;
    video.play();
    video.addEventListener('loadeddata', () => {
      document.getElementById('qr-status').textContent = 'Girocode in den Rahmen halten…';
      scanQrFrame(video);
    }, { once:true });
  } catch(e) {
    document.getElementById('qr-status').textContent = 'Kamera nicht verfügbar: ' + e.message;
  }
}
function stopQrCamera() {
  if (qrAnimFrame) { cancelAnimationFrame(qrAnimFrame); qrAnimFrame = null; }
  if (qrStream) { qrStream.getTracks().forEach(t=>t.stop()); qrStream = null; }
  const video = document.getElementById('qr-video');
  if (video) { video.srcObject = null; }
}
function scanQrFrame(video) {
  if (!qrStream) return;
  const canvas = document.createElement('canvas');
  canvas.width  = video.videoWidth;
  canvas.height = video.videoHeight;
  const ctx = canvas.getContext('2d');
  ctx.drawImage(video, 0, 0, canvas.width, canvas.height);
  const imageData = ctx.getImageData(0, 0, canvas.width, canvas.height);
  const code = jsQR(imageData.data, imageData.width, imageData.height, { inversionAttempts:'dontInvert' });
  if (code) {
    const parsed = parseGirocode(code.data);
    if (parsed) {
      document.getElementById('qr-status').textContent = '✅ Girocode erkannt!';
      stopQrCamera();
      setTimeout(() => {
        closeQrScanner();
        fillTransferForm(parsed);
      }, 600);
      return;
    } else {
      document.getElementById('qr-status').textContent = '⚠️ QR-Code erkannt, aber kein gültiger Girocode.';
    }
  }
  qrAnimFrame = requestAnimationFrame(() => scanQrFrame(video));
}

// EPC-QR / Girocode parsen
function parseGirocode(raw) {
  const lines = raw.split(/\r?\n/);
  // Mindestlänge und Service-Tag prüfen
  if (lines.length < 7) return null;
  if (lines[0].trim() !== 'BCD') return null;
  if (lines[3].trim() !== 'SCT') return null;

  const bic    = (lines[4]||'').trim();
  const name   = (lines[5]||'').trim();
  const iban   = (lines[6]||'').trim().replace(/\s/g,'');
  const amtRaw = (lines[7]||'').trim();  // z.B. "EUR12.50"
  const ref    = (lines[10]||lines[9]||'').trim();

  if (!name || !iban) return null;

  // Betrag extrahieren: "EUR12.50" → "12.50"
  const amtMatch = amtRaw.match(/[A-Z]{3}([\d.]+)/);
  const amount = amtMatch ? amtMatch[1] : '';

  return { name, iban, bic, amount, ref };
}

// Transfer-Formular mit gescannten Daten befüllen
function fillTransferForm(data) {
  if (data.name)   document.getElementById('t-name').value   = data.name;
  if (data.iban)   document.getElementById('t-iban').value   = data.iban;
  if (data.bic)    document.getElementById('t-bic').value    = data.bic;
  if (data.amount) document.getElementById('t-amount').value = data.amount;
  if (data.ref)    document.getElementById('t-ref').value    = data.ref;
  // Visuelles Feedback
  ['t-name','t-iban','t-bic','t-amount','t-ref'].forEach(id => {
    const el = document.getElementById(id);
    if (el && el.value) {
      el.style.borderColor = 'var(--green)';
      el.style.background  = 'var(--green-bg)';
      setTimeout(() => { el.style.borderColor=''; el.style.background=''; }, 2000);
    }
  });
}

// ================================================================
// DATEN LÖSCHEN
// ================================================================
function clearAllData() {
  const ok = confirm('Alle gespeicherten Daten (Zugangsdaten, Token, Konto-ID) wirklich löschen?\n\nDie App muss danach neu eingerichtet werden.');
  if (!ok) return;
  localStorage.removeItem('targoPayCfg');
  cfg = { secretId:'', secretKey:'', requisitionId:'', accountId:'', accessToken:'', accessExpiry:0, refreshToken:'', refreshExpiry:0, _ibanShort:'', cardColor:'#2233b3' };
  loadConfig();
  alert('✅ Alle Daten gelöscht.');
  navTo('home');
}

// ================================================================
// FEHLERBEHANDLUNG
// ================================================================
function handleError(ctx, err) {
  if (err instanceof RateLimitError) alert(`⏱ Rate Limit – ${ctx}\n\n${err.message}\n\nBitte ${err.retryAfter}s warten.`);
  else alert(`Fehler – ${ctx}:\n\n${err.message}`);
  console.error('[TargoPay]', ctx, err);
}

// ================================================================
// NAVIGATION
// ================================================================
const NAV_SCREENS = ['home','overview','transfer','settings'];
function navTo(screenId) {
  showScreen(screenId);
  // Bottom-Nav-Highlighting für alle Screens
  ['home','overview','transfer','settings'].forEach(id => {
    document.querySelectorAll(`[id^="nav-${id}"]`).forEach(el => {
      el.classList.toggle('active', id === screenId);
    });
  });
  // Übersicht-Screen: Daten synchronisieren
  if (screenId === 'overview') {
    const ovBal = document.getElementById('ov-balance');
    const homeBal = document.getElementById('display-balance');
    if (ovBal && homeBal && homeBal.textContent !== '–') ovBal.textContent = homeBal.textContent;
    renderTxList(allTxData.slice(0,50), 'ov-tx-list');
  }
  if (screenId === 'settings') { renderTokenStatus(); updateSettingsValues(); }
}
function showScreen(id) {
  document.querySelectorAll('.screen').forEach(s => {
    if (s.classList.contains('active')) { s.classList.add('slide-out'); setTimeout(()=>s.classList.remove('active','slide-out'),300); }
  });
  const next = document.getElementById(id);
  setTimeout(() => { next.style.transform='translateX(24px)'; next.classList.add('active'); setTimeout(()=>{next.style.transform='';},10); }, 70);
}

// ================================================================
// BALANCE REFRESH BUTTON
// ================================================================
async function refreshBalanceBtn() {
  const btn  = document.getElementById('balance-refresh-btn');
  const btn2 = document.getElementById('ov-refresh-btn');
  [btn, btn2].forEach(b => { if (b) { b.classList.add('spinning'); b.disabled = true; } });
  try {
    await fetchBalance();
    await fetchTxs();
  } catch(e) {
    handleError('Aktualisieren', e);
  } finally {
    setTimeout(() => {
      [btn, btn2].forEach(b => { if (b) { b.classList.remove('spinning'); b.disabled = false; } });
    }, 700);
  }
}

// ================================================================
// HELPERS
// ================================================================
function txEmoji(name, amt) {
  if (amt>0) return '💰';
  const n=name.toLowerCase();
  if (/rewe|edeka|aldi|lidl|penny|netto|kaufland/.test(n)) return '🛒';
  if (/tankstelle|aral|shell|esso|bp |total/.test(n))      return '⛽';
  if (/starbucks|coffee|café|kaffee/.test(n))              return '☕';
  if (/bahn|db |bahncard|vgn|mvv|hvv|bvg/.test(n))        return '🚂';
  if (/amazon|zalando|otto /.test(n))                      return '📦';
  if (/netflix|spotify|prime|disney|apple/.test(n))        return '📺';
  if (/miete|wohnung|hausgeld|nebenkost/.test(n))          return '🏠';
  if (/arzt|apotheke|krankenhaus|praxis/.test(n))          return '💊';
  if (/pizza|lieferando|uber eat|döner|restaurant/.test(n))return '🍕';
  if (/paypal/.test(n))                                    return '🅿️';
  return '💳';
}
function esc(s) { return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;'); }
function delay(ms) { return new Promise(r=>setTimeout(r,ms)); }
function updateGreeting() {
  const h=new Date().getHours();
  const g=h<12?'Guten Morgen':h<18?'Guten Tag':'Guten Abend';
  const el=document.getElementById('greeting-text'); if(el) el.textContent=g;
}
function updateTime() {
  const n=new Date(), t=String(n.getHours()).padStart(2,'0')+':'+String(n.getMinutes()).padStart(2,'0');
  document.querySelectorAll('.time').forEach(el=>el.textContent=t);
}

// ================================================================
// TRANSAKTIONS-DETAIL MODAL
// ================================================================
let currentTxDetail = null;

function openTxDetail(idx) {
  const tx = allTxData[idx];
  if (!tx) return;
  currentTxDetail = tx;

  const amt = parseFloat(tx.transactionAmount?.amount || 0);
  const isCredit = amt > 0;
  const currency = tx.transactionAmount?.currency || 'EUR';
  const fmtAmt = (isCredit ? '+' : '') +
    amt.toLocaleString('de-DE', { minimumFractionDigits: 2, maximumFractionDigits: 2 }) + ' ' + currency;
  const name = tx.creditorName || tx.debtorName || tx.remittanceInformationUnstructured || 'Transaktion';
  const isPending = !tx.bookingDate && tx.valueDate;

  // Header
  document.getElementById('txd-icon').textContent = txEmoji(name, amt);
  document.getElementById('txd-name').textContent = name;
  document.getElementById('txd-status').textContent = isPending ? '⏳ Ausstehend' : '✓ Gebucht';

  // Betrag
  const amtEl = document.getElementById('txd-amount');
  amtEl.textContent = fmtAmt;
  amtEl.className = 'tx-detail-amount ' + (isCredit ? 'credit' : 'debit');

  // Detail-Zeilen aufbauen
  const rows = [];
  const addRow = (label, value, mono) => {
    if (value && value !== '–') rows.push({ label, value, mono });
  };

  const bookingDate = tx.bookingDate
    ? new Date(tx.bookingDate).toLocaleDateString('de-DE', { day: '2-digit', month: 'long', year: 'numeric' })
    : null;
  const valueDate = tx.valueDate
    ? new Date(tx.valueDate).toLocaleDateString('de-DE', { day: '2-digit', month: 'long', year: 'numeric' })
    : null;

  addRow('Buchungsdatum',  bookingDate  || '–');
  addRow('Wertstellungsdatum', valueDate !== bookingDate ? valueDate : null);
  addRow(isCredit ? 'Auftraggeber' : 'Empfänger', name);
  addRow('IBAN ' + (isCredit ? 'Auftraggeber' : 'Empfänger'),
    tx.creditorAccount?.iban || tx.debtorAccount?.iban || null, true);
  addRow('BIC', tx.creditorAgent?.bic || tx.debtorAgent?.bic || null, true);
  addRow('Verwendungszweck', tx.remittanceInformationUnstructured || tx.remittanceInformationStructured || null);
  addRow('Transaktions-ID', tx.transactionId || tx.internalTransactionId || null, true);
  addRow('Mandatsreferenz', tx.mandateId || null, true);
  addRow('Gläubiger-ID', tx.creditorId || null, true);
  addRow('Kategorie', tx.proprietaryBankTransactionCode || tx.bankTransactionCode || null);
  addRow('Saldo nach Buchung',
    tx.balanceAfterTransaction?.balanceAmount?.amount
      ? tx.balanceAfterTransaction.balanceAmount.amount + ' ' + (tx.balanceAfterTransaction.balanceAmount.currency || 'EUR')
      : null);

  document.getElementById('txd-rows').innerHTML = rows.map(r =>
    `<div class="tx-detail-row">
      <div class="tx-detail-row-label">${esc(r.label)}</div>
      <div class="tx-detail-row-value${r.mono ? ' mono' : ''}">${esc(r.value)}</div>
    </div>`
  ).join('');

  // "Zurücküberweisen" nur bei Ausgang sinnvoll
  const backBtn = document.querySelector('.tx-detail-action-btn.primary');
  if (backBtn) backBtn.style.display = isCredit ? 'none' : '';

  document.getElementById('tx-detail-overlay').classList.add('open');
  document.body.style.overflow = 'hidden';
}

function closeTxDetail(event) {
  if (event && event.target !== document.getElementById('tx-detail-overlay')) return;
  document.getElementById('tx-detail-overlay').classList.remove('open');
  currentTxDetail = null;
}

function copyTxDetail() {
  if (!currentTxDetail) return;
  const tx = currentTxDetail;
  const amt = parseFloat(tx.transactionAmount?.amount || 0);
  const currency = tx.transactionAmount?.currency || 'EUR';
  const name = tx.creditorName || tx.debtorName || tx.remittanceInformationUnstructured || 'Transaktion';
  const lines = [
    'Buchung: ' + name,
    'Betrag: ' + amt.toLocaleString('de-DE', { minimumFractionDigits: 2, maximumFractionDigits: 2 }) + ' ' + currency,
    'Buchungsdatum: ' + (tx.bookingDate || tx.valueDate || '–'),
    'Verwendungszweck: ' + (tx.remittanceInformationUnstructured || '–'),
    'IBAN: ' + (tx.creditorAccount?.iban || tx.debtorAccount?.iban || '–'),
    'Transaktions-ID: ' + (tx.transactionId || tx.internalTransactionId || '–'),
  ];
  navigator.clipboard.writeText(lines.join('\n')).then(() => {
    const btn = document.querySelector('.tx-detail-action-btn.secondary');
    if (btn) { btn.textContent = '✓ Kopiert'; setTimeout(() => btn.textContent = 'Kopieren', 2000); }
  }).catch(() => alert('Kopieren nicht möglich.'));
}

function prefillTransfer() {
  if (!currentTxDetail) return;
  const tx = currentTxDetail;
  const name = tx.creditorName || tx.debtorName || '';
  const iban = tx.creditorAccount?.iban || tx.debtorAccount?.iban || '';
  const bic  = tx.creditorAgent?.bic  || tx.debtorAgent?.bic  || '';
  const ref  = tx.remittanceInformationUnstructured || '';
  closeTxDetail();
  navTo('transfer');
  setTimeout(() => {
    if (name) document.getElementById('t-name').value = name;
    if (iban) document.getElementById('t-iban').value = iban;
    if (bic)  document.getElementById('t-bic').value  = bic;
    if (ref)  document.getElementById('t-ref').value  = ref;
  }, 320);
}

// ================================================================
// INIT
// ================================================================
loadConfig();
updateGreeting();
updateTime();
setInterval(updateTime, 30_000);
handlePostRedirect().catch(e=>console.warn('[TargoPay]',e));
if (cfg.secretId && cfg.accountId) setTimeout(()=>saveAndConnect(), 400);
</script>
</body>
</html>
