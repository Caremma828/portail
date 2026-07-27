<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1">
<meta name="theme-color" content="#0c1a2e">
<title>Caremma Finance — Espace Client</title>
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=DM+Serif+Display&display=swap" rel="stylesheet">
<style>
/* ═══ RESET ═══ */
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html,body{height:100%;font-family:'Inter',-apple-system,sans-serif;background:#0c1a2e;color:#e2eaf6;-webkit-font-smoothing:antialiased}

/* ═══ VARIABLES ═══ */
:root{
  --navy:#0c1a2e;--navy2:#102038;--navy3:#162a48;--navy4:#1e3558;
  --gold:#c9a84c;--gold2:#e8c96a;--gold3:#f5e4b0;
  --text:#e2eaf6;--text2:#8faabf;--text3:#5a7a96;
  --green:#22c55e;--red:#ef4444;--orange:#f59e0b;
  --bdr:rgba(255,255,255,0.06);--bdr-gold:rgba(201,168,76,0.2);
  --r:12px;--r2:8px;--r3:6px;
  --shadow:0 4px 24px rgba(0,0,0,0.35);
  --shadow-lg:0 16px 48px rgba(0,0,0,0.5);
  /* Variables pour le contenu B64 injecté */
  --cream:#1e3558;--cream2:#162a48;--cream3:#102038;--off:#0c1a2e;
  --muted:#8faabf;--bdr2:rgba(201,168,76,0.2);
}
::-webkit-scrollbar{width:3px;height:3px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:rgba(201,168,76,0.4);border-radius:2px}

/* ═══ LOGIN ═══ */
#login-screen{
  position:fixed;inset:0;display:flex;align-items:center;justify-content:center;z-index:100;
  background:radial-gradient(ellipse at 25% 35%,#1e3558 0%,#0c1a2e 55%),linear-gradient(180deg,#0c1a2e,#081422);
}
.login-bg-glow{
  position:absolute;inset:0;pointer-events:none;
  background:radial-gradient(circle at 75% 65%,rgba(201,168,76,0.06) 0%,transparent 50%);
}
.login-card{
  position:relative;width:440px;max-width:calc(100vw - 32px);
  background:rgba(16,32,56,0.92);border:1px solid rgba(201,168,76,0.18);
  border-radius:20px;padding:48px 40px;
  backdrop-filter:blur(20px);box-shadow:0 32px 80px rgba(0,0,0,0.55);
}
.login-brand{text-align:center;margin-bottom:36px}
.login-mark{
  width:54px;height:54px;border-radius:14px;margin:0 auto 14px;
  background:linear-gradient(135deg,var(--gold),var(--gold2));
  display:flex;align-items:center;justify-content:center;
  font-size:19px;font-weight:700;color:#0c1a2e;letter-spacing:0.5px;
}
.login-name{font-family:'DM Serif Display',serif;font-size:20px;color:var(--gold2);letter-spacing:0.5px}
.login-orias{font-size:11px;color:var(--text3);letter-spacing:1.2px;text-transform:uppercase;margin-top:4px}
.login-h{font-family:'DM Serif Display',serif;font-size:24px;font-weight:400;color:var(--text);margin-bottom:8px}
.login-sub{font-size:13px;color:var(--text2);line-height:1.6;margin-bottom:28px}
.lbl{display:block;font-size:11px;font-weight:600;letter-spacing:1px;text-transform:uppercase;color:var(--gold);margin-bottom:7px}
.linput{
  width:100%;background:rgba(255,255,255,0.05);border:1px solid var(--bdr);
  border-radius:var(--r2);padding:13px 16px;font-size:14px;color:var(--text);
  outline:none;transition:all 0.2s;margin-bottom:18px;font-family:inherit;
}
.linput:focus{border-color:var(--gold);background:rgba(255,255,255,0.07)}
.linput::placeholder{color:var(--text3)}
.login-btn{
  width:100%;padding:14px;
  background:linear-gradient(135deg,var(--gold),var(--gold2));
  border:none;border-radius:var(--r2);font-size:14px;font-weight:600;
  color:#0c1a2e;cursor:pointer;transition:all 0.2s;font-family:inherit;letter-spacing:0.3px;
}
.login-btn:hover{opacity:0.92;transform:translateY(-1px);box-shadow:0 8px 24px rgba(201,168,76,0.3)}
.login-err{
  background:rgba(239,68,68,0.1);border:1px solid rgba(239,68,68,0.3);
  border-radius:var(--r3);padding:11px 14px;font-size:12px;color:#fca5a5;
  margin-bottom:16px;display:none;
}
.login-foot{text-align:center;margin-top:20px;font-size:12px;color:var(--text3)}

/* ═══ APP ═══ */
#app{display:none;height:100vh;flex-direction:column}

/* ═══ TOPBAR ═══ */
.topbar{
  height:58px;background:rgba(12,26,46,0.98);border-bottom:1px solid var(--bdr);
  display:flex;align-items:center;justify-content:space-between;
  padding:0 24px;flex-shrink:0;backdrop-filter:blur(12px);position:relative;z-index:10;
}
.tb-left{display:flex;align-items:center;gap:10px}
.tb-mark{width:28px;height:28px;border-radius:7px;background:linear-gradient(135deg,var(--gold),var(--gold2));display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:#0c1a2e}
.tb-name{font-family:'DM Serif Display',serif;font-size:15px;color:var(--gold2)}
.tb-right{display:flex;align-items:center;gap:12px}
.tb-greeting{font-size:13px;color:var(--text2)}
.tb-avatar{width:32px;height:32px;border-radius:50%;background:var(--navy3);border:1px solid var(--bdr-gold);display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:600;color:var(--gold2)}
.tb-save{font-size:11px;color:var(--green);opacity:0;transition:opacity 0.3s}
.tb-save.visible{opacity:1}
.tb-logout{font-size:12px;color:var(--text3);background:none;border:1px solid var(--bdr);border-radius:5px;padding:5px 11px;cursor:pointer;transition:all 0.2s;font-family:inherit}
.tb-logout:hover{color:var(--text);border-color:var(--bdr-gold)}

/* ═══ LAYOUT ═══ */
.layout{display:flex;flex:1;overflow:hidden}

/* ═══ SIDEBAR ═══ */
.sidebar{width:224px;background:var(--navy2);border-right:1px solid var(--bdr);display:flex;flex-direction:column;flex-shrink:0;overflow-y:auto;padding:8px 6px}
.sb-section{padding:14px 10px 5px;font-size:10px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--text3)}
.nav-item{
  display:flex;align-items:center;gap:9px;padding:10px 11px;
  cursor:pointer;border-radius:var(--r2);margin:1px 0;
  font-size:13px;color:var(--text2);transition:all 0.15s;border:1px solid transparent;
}
.nav-item:hover{background:rgba(255,255,255,0.05);color:var(--text)}
.nav-item.active{background:rgba(201,168,76,0.1);color:var(--gold2);border-color:rgba(201,168,76,0.2)}
.nav-icon{font-size:15px;width:18px;text-align:center;flex-shrink:0}
.nav-badge{margin-left:auto;background:var(--gold);color:#0c1a2e;border-radius:10px;font-size:10px;font-weight:700;padding:1px 7px;min-width:18px;text-align:center}

/* ═══ MAIN ═══ */
.main{flex:1;overflow-y:auto;background:#0e1e33}
.page{display:none;padding:28px;min-height:100%;animation:fadein 0.2s ease}
.page.active{display:block}
@keyframes fadein{from{opacity:0;transform:translateY(5px)}to{opacity:1;transform:translateY(0)}}
.ph{margin-bottom:24px}
.pt{font-family:'DM Serif Display',serif;font-size:24px;font-weight:400;color:var(--text);margin-bottom:5px}
.ps{font-size:13px;color:var(--text3)}

/* ═══ CARDS ═══ */
.card{background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r);padding:22px;margin-bottom:16px}
.card-title{font-size:11px;font-weight:600;letter-spacing:1.2px;text-transform:uppercase;color:var(--gold);margin-bottom:16px;display:flex;align-items:center;gap:7px}
.card-row{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-bottom:16px}

/* ═══ KPIs ═══ */
.kpi-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:14px;margin-bottom:22px}
.kpi{background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r);padding:20px;position:relative;overflow:hidden;transition:border-color 0.2s;cursor:default}
.kpi:hover{border-color:var(--bdr-gold)}
.kpi::after{content:'';position:absolute;bottom:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--gold),transparent)}
.kpi-label{font-size:11px;font-weight:500;letter-spacing:0.8px;text-transform:uppercase;color:var(--text3);margin-bottom:9px}
.kpi-value{font-size:24px;font-weight:300;color:var(--text);font-family:'DM Serif Display',serif;line-height:1.1}
.kpi-sub{font-size:11px;color:var(--text3);margin-top:5px}
.up{color:var(--green)}.dn{color:var(--red)}

/* ═══ BUTTONS ═══ */
.btn{padding:9px 18px;border-radius:var(--r2);font-size:13px;font-weight:500;cursor:pointer;transition:all 0.2s;font-family:inherit;border:none;display:inline-flex;align-items:center;gap:6px}
.btn-primary{background:linear-gradient(135deg,var(--gold),var(--gold2));color:#0c1a2e;font-weight:600}
.btn-primary:hover{opacity:0.9;transform:translateY(-1px);box-shadow:0 6px 18px rgba(201,168,76,0.25)}
.btn-ghost{background:transparent;border:1px solid var(--bdr);color:var(--text2)}
.btn-ghost:hover{border-color:var(--bdr-gold);color:var(--text)}
.btn-danger{background:rgba(239,68,68,0.1);border:1px solid rgba(239,68,68,0.3);color:#fca5a5}
.btn-sm{padding:6px 13px;font-size:12px}

/* ═══ FORMS ═══ */
.fg{margin-bottom:15px}
.fl{display:block;font-size:11px;font-weight:600;letter-spacing:0.8px;text-transform:uppercase;color:var(--gold);margin-bottom:6px}
.fc,.form-input{width:100%;background:rgba(255,255,255,0.04);border:1px solid var(--bdr);border-radius:var(--r2);padding:10px 14px;font-size:13px;color:var(--text);outline:none;transition:border-color 0.2s;font-family:inherit}
.fc:focus,.form-input:focus{border-color:var(--gold)}
.fc::placeholder,.form-input::placeholder{color:var(--text3)}
.fg2{display:grid;grid-template-columns:1fr 1fr;gap:14px}
@media(max-width:600px){.fg2{grid-template-columns:1fr}}

/* ═══ MESSAGES ═══ */
.msg-list{display:flex;flex-direction:column;gap:10px;margin-bottom:16px;min-height:220px;max-height:420px;overflow-y:auto;padding:2px 0}
.msg{max-width:74%;padding:11px 15px;border-radius:14px;font-size:13px;line-height:1.55}
.msg.client{align-self:flex-end;background:rgba(201,168,76,0.12);border:1px solid rgba(201,168,76,0.18);color:var(--text);border-bottom-right-radius:4px}
.msg.conseiller{align-self:flex-start;background:var(--navy3);border:1px solid var(--bdr);color:var(--text2);border-bottom-left-radius:4px}
.msg-meta{font-size:10px;color:var(--text3);margin-top:4px;font-weight:500}
.msg-bar{display:flex;gap:10px;align-items:flex-end;padding-top:14px;border-top:1px solid var(--bdr)}
.msg-ta{flex:1;background:rgba(255,255,255,0.04);border:1px solid var(--bdr);border-radius:var(--r2);padding:10px 14px;font-size:13px;color:var(--text);resize:none;min-height:42px;outline:none;font-family:inherit;transition:border-color 0.2s}
.msg-ta:focus{border-color:var(--gold)}
.msg-empty{text-align:center;color:var(--text3);font-size:13px;padding:40px 20px;line-height:1.6}

/* ═══ DOCUMENTS ═══ */
.doc-item{display:flex;align-items:center;gap:13px;padding:14px 16px;background:rgba(255,255,255,0.02);border:1px solid var(--bdr);border-radius:var(--r2);margin-bottom:8px;transition:all 0.2s}
.doc-item:hover{background:rgba(255,255,255,0.04);border-color:var(--bdr-gold)}
.doc-icon{font-size:22px;flex-shrink:0}
.doc-info{flex:1;min-width:0}
.doc-name{font-size:13px;font-weight:500;color:var(--text);white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.doc-meta{font-size:11px;color:var(--text3);margin-top:2px}
.doc-acts{display:flex;align-items:center;gap:7px;flex-shrink:0}
.badge{font-size:10px;font-weight:600;padding:3px 9px;border-radius:12px;white-space:nowrap}
.badge-ok{background:rgba(34,197,94,0.12);color:var(--green);border:1px solid rgba(34,197,94,0.25)}
.badge-pending{background:rgba(201,168,76,0.12);color:var(--gold);border:1px solid rgba(201,168,76,0.25)}
.rap-pill{font-size:11.5px;font-weight:600;padding:6px 13px;border-radius:20px;cursor:pointer;border:1px solid var(--bdr);color:var(--text2);background:transparent;transition:all 0.15s;white-space:nowrap}
.rap-pill:hover{border-color:var(--bdr-gold);color:var(--text)}
.rap-pill.active{background:rgba(201,168,76,0.12);color:var(--gold2);border-color:rgba(201,168,76,0.3)}
.rap-cat-h{font-size:11px;font-weight:600;letter-spacing:1px;text-transform:uppercase;color:var(--text3);margin:18px 0 10px}
.rap-row{display:flex;align-items:center;gap:14px;padding:14px 16px;background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r2);margin-bottom:9px;transition:border-color 0.15s}
.rap-row:hover{border-color:var(--bdr-gold)}
.rap-icon{width:38px;height:38px;border-radius:9px;background:rgba(201,168,76,0.1);display:flex;align-items:center;justify-content:center;font-size:17px;flex-shrink:0}
.rap-new{background:var(--gold);color:var(--navy);font-size:9px;font-weight:700;padding:2px 7px;border-radius:8px;margin-left:8px;vertical-align:middle}

/* ═══ Stories (bandeau dashboard) ═══ */
.stories-row{display:flex;gap:12px;overflow-x:auto;padding:4px 2px 14px;margin-bottom:6px;scrollbar-width:thin}
.stories-row::-webkit-scrollbar{height:6px}
.stories-row::-webkit-scrollbar-thumb{background:var(--bdr-gold);border-radius:4px}
.story-card{flex:0 0 148px;background:linear-gradient(160deg,var(--navy2),var(--navy3,var(--navy2)));border:1px solid var(--bdr);border-radius:var(--r2);padding:14px 14px 12px;cursor:pointer;transition:transform 0.15s,border-color 0.15s}
.story-card:hover{transform:translateY(-3px);border-color:var(--bdr-gold)}
.story-ico{font-size:22px;margin-bottom:8px}
.story-label{font-size:9.5px;font-weight:700;letter-spacing:0.6px;text-transform:uppercase;color:var(--gold2);margin-bottom:4px}
.story-title{font-size:12.5px;font-weight:600;color:var(--text);line-height:1.35;overflow:hidden;display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical}

/* ═══ Jalon / progression patrimoniale ═══ */
.milestone-card{background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r2);padding:18px 20px;margin-bottom:16px}
.milestone-bar-track{height:10px;border-radius:6px;background:rgba(255,255,255,0.06);overflow:hidden;margin:12px 0 8px}
.milestone-bar-fill{height:100%;border-radius:6px;background:linear-gradient(90deg,var(--gold2),var(--gold));transition:width 1.1s cubic-bezier(.22,1,.36,1)}

/* ═══ Confetti (célébration de jalon) ═══ */
.confetti-piece{position:fixed;top:-12px;width:8px;height:14px;opacity:0.9;z-index:9999;pointer-events:none;animation:confetti-fall linear forwards}
@keyframes confetti-fall{to{transform:translateY(105vh) rotate(540deg);opacity:0.3}}

/* ═══ Donut allocation d'actifs ═══ */
.donut-wrap{display:flex;gap:28px;align-items:center;flex-wrap:wrap}
.donut-svg{flex:0 0 auto}
.donut-legend{display:flex;flex-direction:column;gap:9px;flex:1;min-width:180px}
.donut-legend-row{display:flex;align-items:center;gap:9px;font-size:12.5px;color:var(--text2);cursor:default;transition:opacity 0.15s}
.donut-legend-row:hover{opacity:0.75}
.donut-dot{width:10px;height:10px;border-radius:3px;flex-shrink:0}
.donut-legend-val{margin-left:auto;font-weight:600;color:var(--text)}

/* ═══ Simulateur "Et si..." ═══ */
.sim-card{background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r2);padding:22px 24px}
.sim-row{display:flex;justify-content:space-between;align-items:center;margin-bottom:6px;font-size:12.5px;color:var(--text2)}
.sim-slider{width:100%;-webkit-appearance:none;height:5px;border-radius:4px;background:rgba(255,255,255,0.1);margin-bottom:18px;accent-color:var(--gold)}
.sim-pills{display:flex;gap:8px;margin-bottom:20px}
.sim-result{text-align:center;padding:20px 10px;background:rgba(201,168,76,0.07);border:1px solid rgba(201,168,76,0.2);border-radius:var(--r2);margin-top:6px}
.sim-result-value{font-size:30px;font-weight:700;color:var(--gold2);letter-spacing:-0.5px}
.sim-breakdown{display:flex;gap:3px;height:8px;border-radius:5px;overflow:hidden;margin:14px 0 10px}
.sim-breakdown div{height:100%}
.sim-legend{display:flex;gap:16px;flex-wrap:wrap;font-size:11px;color:var(--text3)}

/* ═══ Mon patrimoine (actifs déclarés par le client) ═══ */
.patr-total-row{display:flex;gap:14px;flex-wrap:wrap;margin-bottom:18px}
.patr-total-card{flex:1;min-width:180px;background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r2);padding:16px 18px}
.patr-total-label{font-size:10.5px;font-weight:700;letter-spacing:0.6px;text-transform:uppercase;color:var(--text3);margin-bottom:6px}
.patr-total-value{font-size:22px;font-weight:700;color:var(--text)}
.patr-form-grid{display:grid;grid-template-columns:1.1fr 2fr 1fr auto;gap:10px;align-items:end}
.patr-form-grid label{font-size:10.5px;font-weight:600;letter-spacing:0.4px;text-transform:uppercase;color:var(--text3);display:block;margin-bottom:6px}
.patr-form-grid select,.patr-form-grid input{width:100%;padding:10px 12px;border-radius:9px;border:1px solid var(--bdr);background:var(--navy2);color:var(--text);font-size:13px;font-family:inherit}
.patr-row{display:flex;align-items:center;gap:14px;padding:13px 16px;background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r2);margin-bottom:8px}
.patr-row:hover{border-color:var(--bdr-gold)}
.patr-ico{width:36px;height:36px;border-radius:9px;background:rgba(201,168,76,0.1);display:flex;align-items:center;justify-content:center;font-size:16px;flex-shrink:0}
.patr-row-actions{display:flex;gap:6px}
.patr-icon-btn{width:28px;height:28px;border-radius:7px;border:1px solid var(--bdr);background:transparent;color:var(--text3);cursor:pointer;font-size:12px;display:flex;align-items:center;justify-content:center;transition:all 0.15s}
.patr-icon-btn:hover{border-color:var(--bdr-gold);color:var(--gold2)}

/* ═══ Objectif personnel ═══ */
.goal-card{background:linear-gradient(160deg,var(--navy2),rgba(201,168,76,0.05));border:1px solid var(--bdr);border-radius:var(--r2);padding:20px 22px}
.goal-empty-form{display:grid;grid-template-columns:1.4fr 1fr 1fr auto;gap:10px;align-items:end}
.goal-empty-form label{font-size:10.5px;font-weight:600;letter-spacing:0.4px;text-transform:uppercase;color:var(--text3);display:block;margin-bottom:6px}
.goal-empty-form input{width:100%;padding:10px 12px;border-radius:9px;border:1px solid var(--bdr);background:var(--navy2);color:var(--text);font-size:13px;font-family:inherit}

/* ═══ Suggestion de versement ═══ */
.nudge-card{display:flex;align-items:center;gap:16px;background:rgba(201,168,76,0.06);border:1px solid rgba(201,168,76,0.22);border-radius:var(--r2);padding:16px 20px;margin-bottom:16px;flex-wrap:wrap}
.nudge-ico{font-size:26px}
.nudge-text{flex:1;min-width:200px;font-size:12.5px;color:var(--text2);line-height:1.5}
.nudge-text b{color:var(--gold2)}

/* ═══ Streak de régularité ═══ */
.streak-card{background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r2);padding:18px 20px}
.streak-flame{font-size:26px}
.streak-count{font-size:20px;font-weight:700;color:var(--gold2)}
.streak-grid{display:flex;gap:6px;margin-top:14px;flex-wrap:wrap}
.streak-month{width:34px;height:34px;border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:600;color:var(--text3);background:rgba(255,255,255,0.04);border:1px solid var(--bdr)}
.streak-month.done{background:rgba(201,168,76,0.18);border-color:rgba(201,168,76,0.4);color:var(--gold2)}
.streak-checkin-btn{margin-top:14px}

/* ═══ Guides & Simulateurs ═══ */
.guide-disclaimer{background:rgba(138,155,176,0.08);border:1px solid var(--bdr);border-radius:var(--r2);padding:12px 16px;font-size:11.5px;color:var(--text3);line-height:1.6;margin-bottom:18px}
.fiche{background:var(--navy2);border:1px solid var(--bdr);border-radius:var(--r2);margin-bottom:10px;overflow:hidden}
.fiche-head{display:flex;align-items:center;gap:12px;padding:15px 18px;cursor:pointer;user-select:none}
.fiche-head:hover{background:rgba(255,255,255,0.02)}
.fiche-ico{font-size:19px}
.fiche-title{flex:1;font-size:13.5px;font-weight:600;color:var(--text)}
.fiche-chevron{font-size:12px;color:var(--text3);transition:transform 0.2s}
.fiche.open .fiche-chevron{transform:rotate(180deg)}
.fiche-body{max-height:0;overflow:hidden;transition:max-height 0.25s ease}
.fiche.open .fiche-body{max-height:900px}
.fiche-body-inner{padding:0 18px 18px 18px;font-size:12.5px;color:var(--text2);line-height:1.7}
.fiche-body-inner ul{margin:6px 0 6px 18px}
.fiche-body-inner li{margin-bottom:4px}
.fiche-body-inner .fiche-note{margin-top:10px;padding:9px 12px;background:rgba(201,168,76,0.06);border-left:2px solid var(--bdr-gold);font-size:11.5px;color:var(--text3)}

.sim2-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:16px}
.sim2-field label{font-size:10.5px;font-weight:600;letter-spacing:0.4px;text-transform:uppercase;color:var(--text3);display:block;margin-bottom:6px}
.sim2-field input,.sim2-field select{width:100%;padding:10px 12px;border-radius:9px;border:1px solid var(--bdr);background:var(--navy2);color:var(--text);font-size:13px;font-family:inherit}
.sim2-pills{display:flex;gap:8px;margin-bottom:16px;flex-wrap:wrap}

/* ═══ UPLOAD ═══ */
.upload-zone{border:2px dashed rgba(201,168,76,0.2);border-radius:var(--r);padding:32px;text-align:center;cursor:pointer;transition:all 0.2s;background:rgba(201,168,76,0.02)}
.upload-zone:hover,.upload-zone.over{border-color:var(--gold);background:rgba(201,168,76,0.06)}
.upload-icon{font-size:30px;margin-bottom:10px;opacity:0.7}
.upload-title{font-size:14px;font-weight:500;color:var(--text);margin-bottom:4px}
.upload-sub{font-size:12px;color:var(--text3)}

/* ═══ SIGNATURE ═══ */
.sig-card{background:var(--navy2);border:1px solid var(--bdr-gold);border-radius:var(--r);padding:24px;margin-top:16px}
.sig-steps{display:flex;gap:6px;margin-bottom:22px}
.sig-step{flex:1;padding:9px 6px;text-align:center;font-size:11px;font-weight:500;border-radius:6px;background:rgba(255,255,255,0.03);border:1px solid var(--bdr);color:var(--text3);transition:all 0.2s;letter-spacing:0.3px}
.sig-step.active{background:rgba(201,168,76,0.1);border-color:var(--bdr-gold);color:var(--gold2)}
.sig-step.done{background:rgba(34,197,94,0.08);border-color:rgba(34,197,94,0.2);color:var(--green)}
#sig-canvas{display:block;width:100%;height:150px;cursor:crosshair;touch-action:none;border-radius:var(--r2)}

/* ═══ CHART ═══ */
.chart-wrap{height:200px;position:relative;margin:8px 0}

/* ═══ PROGRESS BAR ═══ */
.progress-bar{height:4px;background:rgba(255,255,255,0.06);border-radius:2px;margin-bottom:6px;overflow:hidden}
.progress-fill{height:100%;background:linear-gradient(90deg,var(--gold),var(--gold2));border-radius:2px;transition:width 0.5s ease}
.progress-label{font-size:11px;color:var(--text3);margin-bottom:14px}

/* ═══ SESSION TIMER ═══ */
#session-warning{position:fixed;bottom:70px;right:24px;background:var(--navy2);border:1px solid var(--bdr-gold);border-radius:var(--r2);padding:14px 18px;font-size:13px;color:var(--text);box-shadow:var(--shadow);z-index:999;display:none}

/* ═══ TOAST ═══ */
#toast-wrap{position:fixed;bottom:24px;right:24px;z-index:9999;display:flex;flex-direction:column;gap:8px;pointer-events:none}
.toast{padding:12px 18px;border-radius:10px;font-size:13px;font-weight:500;animation:toast-in 0.25s ease;min-width:250px;background:var(--navy2);border:1px solid var(--bdr);color:var(--text);box-shadow:var(--shadow)}
.toast.success{border-color:rgba(34,197,94,0.4);background:rgba(34,197,94,0.1);color:#86efac}
.toast.error{border-color:rgba(239,68,68,0.4);background:rgba(239,68,68,0.1);color:#fca5a5}
.toast.warn{border-color:rgba(245,158,11,0.4);background:rgba(245,158,11,0.1);color:#fcd34d}
@keyframes toast-in{from{opacity:0;transform:translateX(14px)}to{opacity:1;transform:translateX(0)}}

/* ═══ QUESTIONNAIRE OVERRIDES ═══ */
#pg-objectifs *,#pg-connaissance *{color:inherit}
#pg-objectifs,#pg-connaissance{color:var(--text)}
#pg-objectifs h2,#pg-objectifs h3,#pg-connaissance h2,#pg-connaissance h3{font-family:'DM Serif Display',serif;font-weight:400;color:var(--text);font-size:17px;margin:18px 0 12px}
#pg-objectifs p,#pg-connaissance p{color:var(--text2);font-size:13px;line-height:1.6}
/* Sections */
#pg-objectifs .card,#pg-connaissance .card{background:var(--navy2)!important;border:1px solid var(--bdr)!important;border-radius:var(--r)!important}
#pg-objectifs .sh,#pg-connaissance .sh{background:rgba(201,168,76,0.06)!important;border-bottom:1px solid var(--bdr-gold)!important;padding:12px 16px!important;border-radius:var(--r) var(--r) 0 0!important}
#pg-objectifs .st,#pg-connaissance .st{color:var(--gold)!important;font-size:11px!important;font-weight:600!important;letter-spacing:1.2px!important;text-transform:uppercase!important}
/* Tableaux */
#pg-objectifs table,#pg-connaissance table{width:100%!important;border-collapse:collapse!important;background:transparent!important}
#pg-objectifs thead,#pg-connaissance thead{background:rgba(201,168,76,0.05)!important}
#pg-objectifs th,#pg-connaissance th{background:transparent!important;color:var(--gold)!important;font-size:11px!important;font-weight:600!important;letter-spacing:0.8px!important;text-transform:uppercase!important;padding:11px 14px!important;border-bottom:1px solid var(--bdr-gold)!important;text-align:center!important}
#pg-objectifs td,#pg-connaissance td{background:transparent!important;color:var(--text2)!important;padding:10px 14px!important;border-bottom:1px solid rgba(255,255,255,0.04)!important;vertical-align:middle!important}
#pg-objectifs td:first-child,#pg-connaissance td:first-child{color:var(--text)!important;font-weight:500!important}
#pg-objectifs tr,#pg-connaissance tr{background:transparent!important}
#pg-objectifs tr:nth-child(even) td,#pg-connaissance tr:nth-child(even) td{background:rgba(255,255,255,0.02)!important}
#pg-objectifs tr:hover td,#pg-connaissance tr:hover td{background:rgba(201,168,76,0.04)!important}
/* Inputs dans questionnaires */
#pg-objectifs input[type=text],#pg-objectifs input[type=number],#pg-objectifs input[type=email],
#pg-objectifs input[type=date],#pg-objectifs select,#pg-objectifs textarea,
#pg-connaissance input[type=text],#pg-connaissance input[type=number],#pg-connaissance select,#pg-connaissance textarea,
.inline-input,.fc,.form-control{background:rgba(255,255,255,0.05)!important;border:1px solid rgba(255,255,255,0.1)!important;border-radius:var(--r2)!important;color:var(--text)!important;padding:8px 12px!important;font-family:inherit!important;width:100%!important;outline:none!important;transition:border-color 0.2s!important;font-size:13px!important}
#pg-objectifs input:focus,#pg-objectifs select:focus,#pg-objectifs textarea:focus,
#pg-connaissance input:focus,#pg-connaissance select:focus,.inline-input:focus{border-color:var(--gold)!important}
#pg-objectifs input::placeholder,#pg-connaissance input::placeholder,.inline-input::placeholder{color:rgba(143,170,191,0.5)!important}
/* Labels */
#pg-objectifs label,#pg-connaissance label{color:var(--text2)!important;font-size:13px!important}
#pg-objectifs .fl,#pg-connaissance .fl{color:var(--gold)!important;font-size:11px!important;font-weight:600!important;letter-spacing:0.8px!important;text-transform:uppercase!important}
/* Radios et checkboxes */
#pg-objectifs input[type=radio],#pg-connaissance input[type=radio]{width:17px!important;height:17px!important;accent-color:var(--gold)!important;cursor:pointer!important}
#pg-objectifs input[type=checkbox],#pg-connaissance input[type=checkbox]{width:16px!important;height:16px!important;accent-color:var(--gold)!important;cursor:pointer!important}
#pg-objectifs td label,#pg-connaissance td label{display:block!important;width:100%!important;text-align:center!important;cursor:pointer!important;padding:8px!important;margin:-8px!important;color:var(--text2)!important}
/* Radio-opt pills */
#pg-objectifs .radio-opt,#pg-connaissance .radio-opt{background:rgba(255,255,255,0.04)!important;border:1px solid rgba(255,255,255,0.09)!important;border-radius:20px!important;color:var(--text2)!important;padding:7px 15px!important;cursor:pointer!important;transition:all 0.15s!important;display:inline-flex!important;align-items:center!important;gap:7px!important;margin:3px!important;font-size:12px!important}
#pg-objectifs .radio-opt.selected,#pg-objectifs .radio-opt.on,
#pg-connaissance .radio-opt.selected,#pg-connaissance .radio-opt.on{background:rgba(201,168,76,0.14)!important;border-color:rgba(201,168,76,0.35)!important;color:var(--gold2)!important;font-weight:600!important}
#pg-objectifs .radio-opt input,#pg-connaissance .radio-opt input{display:none!important}
/* Boutons dans questionnaires */
#pg-objectifs .btn.bp2,#pg-connaissance .btn.bp2,
#pg-objectifs button.bp2,#pg-connaissance button.bp2{background:linear-gradient(135deg,var(--gold),var(--gold2))!important;color:#0c1a2e!important;border:none!important;border-radius:var(--r2)!important;padding:10px 20px!important;font-size:13px!important;font-weight:600!important;cursor:pointer!important;font-family:inherit!important}
/* Score box */
.q-score-box{background:rgba(201,168,76,0.07)!important;border:1px solid var(--bdr-gold)!important;border-radius:var(--r)!important;padding:24px!important;text-align:center!important;margin-top:20px!important}
#score-val,#q-score-val,#result-score-kn{font-size:52px!important;font-weight:300!important;color:var(--gold2)!important;font-family:'DM Serif Display',serif!important;display:block!important}
#q-profil-val,#result-cat-kn{font-size:15px!important;color:var(--text)!important;margin-top:8px!important;display:block!important}
/* Patrimoine table */
.data-table{width:100%!important;border-collapse:collapse!important}
.data-table th{background:rgba(201,168,76,0.06)!important;color:var(--gold)!important;font-size:11px!important;font-weight:600!important;letter-spacing:0.8px!important;text-transform:uppercase!important;padding:10px 14px!important;border-bottom:1px solid var(--bdr-gold)!important}
.data-table td{background:transparent!important;color:var(--text)!important;padding:9px 14px!important;border-bottom:1px solid rgba(255,255,255,0.04)!important}
/* q-title */
.q-title{font-size:15px!important;font-weight:600!important;color:var(--gold2)!important;margin-bottom:14px!important;padding-bottom:10px!important;border-bottom:1px solid var(--bdr-gold)!important}
/* nav-btns supprimés via JS */
.q-nav-btns{display:none!important}

/* ═══ RESPONSIVE ═══ */
@media(max-width:768px){
  .sidebar{display:none}
  .page{padding:16px}
  .kpi-grid{grid-template-columns:1fr 1fr}
  .topbar{padding:0 16px}
  .card-row{grid-template-columns:1fr}
  .login-card{padding:36px 24px}
}

/* ══ QUESTIONNAIRES — CONTENU B64 COMPLET ══ */

/* Wrappers injectés */
#obj-content, #conn-content {
  color: var(--text) !important;
}

/* Section header */
#obj-content .section-header, #conn-content .section-header {
  padding: 16px 0 10px !important;
  border-bottom: 1px solid var(--bdr-gold) !important;
  margin-bottom: 18px !important;
}
#obj-content .section-header h2, #conn-content .section-header h2 {
  font-family: 'DM Serif Display', serif !important;
  font-size: 18px !important;
  font-weight: 400 !important;
  color: var(--text) !important;
}

/* q-section */
#obj-content .q-section, #conn-content .q-section {
  margin-bottom: 24px !important;
}

/* q-title */
#obj-content .q-title, #conn-content .q-title {
  font-size: 14px !important;
  font-weight: 600 !important;
  color: var(--gold2) !important;
  margin-bottom: 14px !important;
  padding-bottom: 10px !important;
  border-bottom: 1px solid rgba(201,168,76,0.15) !important;
}

/* info-box */
#obj-content .info-box, #conn-content .info-box {
  background: rgba(201,168,76,0.07) !important;
  border-left: 3px solid var(--gold) !important;
  border-radius: 0 var(--r2) var(--r2) 0 !important;
  padding: 12px 16px !important;
  font-size: 13px !important;
  color: var(--text2) !important;
  margin-bottom: 18px !important;
  line-height: 1.6 !important;
}

/* Cards */
#obj-content .card, #conn-content .card {
  background: rgba(22,42,72,0.6) !important;
  border: 1px solid var(--bdr) !important;
  border-radius: var(--r) !important;
  padding: 20px !important;
  margin-bottom: 16px !important;
}

/* form-grid */
#obj-content .form-grid, #conn-content .form-grid {
  display: grid !important;
  grid-template-columns: 1fr 1fr !important;
  gap: 14px !important;
}
#obj-content .form-full, #conn-content .form-full {
  grid-column: 1 / -1 !important;
}
@media(max-width:600px){
  #obj-content .form-grid, #conn-content .form-grid { grid-template-columns: 1fr !important; }
}

/* form-group */
#obj-content .form-group, #conn-content .form-group {
  margin-bottom: 14px !important;
}
#obj-content .form-group label, #conn-content .form-group label {
  display: block !important;
  font-size: 11px !important;
  font-weight: 600 !important;
  letter-spacing: 0.8px !important;
  text-transform: uppercase !important;
  color: var(--gold) !important;
  margin-bottom: 6px !important;
}

/* Inputs */
#obj-content input[type=text], #obj-content input[type=number],
#obj-content input[type=email], #obj-content input[type=date],
#obj-content select, #obj-content textarea,
#conn-content input[type=text], #conn-content input[type=number],
#conn-content select, #conn-content textarea,
#obj-content .inline-input, #conn-content .inline-input {
  width: 100% !important;
  background: rgba(255,255,255,0.05) !important;
  border: 1px solid rgba(255,255,255,0.1) !important;
  border-radius: var(--r2) !important;
  color: var(--text) !important;
  padding: 9px 13px !important;
  font-size: 13px !important;
  font-family: inherit !important;
  outline: none !important;
  transition: border-color 0.2s !important;
}
#obj-content input:focus, #obj-content select:focus, #obj-content textarea:focus,
#conn-content input:focus, #conn-content select:focus { border-color: var(--gold) !important; }
#obj-content input::placeholder, #conn-content input::placeholder,
#obj-content .inline-input::placeholder { color: rgba(143,170,191,0.45) !important; }
#obj-content select option, #conn-content select option { background: var(--navy2) !important; color: var(--text) !important; }

/* Tableaux */
#obj-content table, #conn-content table {
  width: 100% !important; border-collapse: collapse !important; background: transparent !important;
}
#obj-content th, #conn-content th {
  background: rgba(201,168,76,0.06) !important;
  color: var(--gold) !important;
  font-size: 11px !important; font-weight: 600 !important;
  letter-spacing: 0.8px !important; text-transform: uppercase !important;
  padding: 10px 14px !important; border-bottom: 1px solid var(--bdr-gold) !important;
}
#obj-content td, #conn-content td {
  background: transparent !important; color: var(--text2) !important;
  padding: 10px 14px !important; border-bottom: 1px solid rgba(255,255,255,0.04) !important;
  vertical-align: middle !important;
}
#obj-content td:first-child, #conn-content td:first-child { color: var(--text) !important; font-weight: 500 !important; }
#obj-content tr:nth-child(even) td, #conn-content tr:nth-child(even) td { background: rgba(255,255,255,0.02) !important; }
#obj-content tr:hover td, #conn-content tr:hover td { background: rgba(201,168,76,0.04) !important; }

/* Radios & checkboxes */
#obj-content input[type=radio], #conn-content input[type=radio] { width:17px!important;height:17px!important;accent-color:var(--gold)!important;cursor:pointer!important; }
#obj-content input[type=checkbox], #conn-content input[type=checkbox] { width:16px!important;height:16px!important;accent-color:var(--gold)!important;cursor:pointer!important; }
#obj-content td label, #conn-content td label { display:block!important;width:100%!important;text-align:center!important;cursor:pointer!important;padding:8px!important;margin:-8px!important;color:var(--text2)!important; }

/* Radio-opt */
#obj-content .radio-opt, #conn-content .radio-opt {
  display: inline-flex !important; align-items: center !important; gap: 7px !important;
  padding: 8px 15px !important; margin: 3px !important;
  background: rgba(255,255,255,0.04) !important; border: 1px solid rgba(255,255,255,0.09) !important;
  border-radius: 20px !important; color: var(--text2) !important;
  cursor: pointer !important; transition: all 0.15s !important; font-size: 12px !important;
}
#obj-content .radio-opt.selected, #obj-content .radio-opt.on,
#conn-content .radio-opt.selected, #conn-content .radio-opt.on {
  background: rgba(201,168,76,0.14) !important; border-color: rgba(201,168,76,0.35) !important;
  color: var(--gold2) !important; font-weight: 600 !important;
}
#obj-content .radio-opt input, #conn-content .radio-opt input { display: none !important; }

/* check-opt */
#obj-content .check-opt, #conn-content .check-opt {
  display: flex !important; align-items: center !important; gap: 10px !important;
  padding: 10px 14px !important; margin-bottom: 6px !important;
  background: rgba(255,255,255,0.03) !important; border: 1px solid var(--bdr) !important;
  border-radius: var(--r2) !important; cursor: pointer !important; transition: all 0.15s !important;
  color: var(--text2) !important; font-size: 13px !important;
}
#obj-content .check-opt:hover, #conn-content .check-opt:hover { border-color: var(--bdr-gold) !important; background: rgba(201,168,76,0.05) !important; }
#obj-content .check-opt input, #conn-content .check-opt input { accent-color: var(--gold) !important; width: 16px !important; height: 16px !important; flex-shrink: 0 !important; }

/* Boutons */
#obj-content .btn-primary, #obj-content .btn-gold, #obj-content .btn.bp2,
#conn-content .btn-primary, #conn-content .btn-gold, #conn-content .btn.bp2 {
  background: linear-gradient(135deg,var(--gold),var(--gold2)) !important;
  color: #0c1a2e !important; border: none !important; border-radius: var(--r2) !important;
  padding: 10px 20px !important; font-size: 13px !important; font-weight: 600 !important;
  cursor: pointer !important; font-family: inherit !important; transition: all 0.2s !important;
}
#obj-content .btn-outline, #conn-content .btn-outline {
  background: transparent !important; border: 1px solid var(--bdr) !important;
  color: var(--text2) !important; border-radius: var(--r2) !important;
  padding: 10px 20px !important; font-size: 13px !important;
  cursor: pointer !important; font-family: inherit !important; transition: all 0.2s !important;
}

/* Score */
#obj-content #score-val, #conn-content #score-val,
#obj-content #q-score-val, #conn-content #q-score-val,
#obj-content #result-score-kn, #conn-content #result-score-kn {
  font-size: 52px !important; font-weight: 300 !important;
  color: var(--gold2) !important; font-family: 'DM Serif Display', serif !important; display: block !important;
}
#obj-content #q-profil-val, #conn-content #q-profil-val,
#obj-content #result-cat-kn, #conn-content #result-cat-kn {
  font-size: 15px !important; color: var(--text) !important; margin-top: 8px !important; display: block !important;
}
.q-score-box {
  background: rgba(201,168,76,0.07) !important; border: 1px solid var(--bdr-gold) !important;
  border-radius: var(--r) !important; padding: 28px !important; text-align: center !important; margin-top: 20px !important;
}

/* card-title dans les questionnaires */
#obj-content .card-title, #conn-content .card-title {
  font-size: 11px !important; font-weight: 600 !important; letter-spacing: 1.2px !important;
  text-transform: uppercase !important; color: var(--gold) !important; margin-bottom: 16px !important;
}

/* Masquer progress-steps (navigation entre étapes) */
#obj-content .progress-steps, #conn-content .progress-steps,
#obj-content .q-nav-btns, #conn-content .q-nav-btns { display: none !important; }

/* ══ FORCE UNIVERSELLE — TOUT LE CONTENU INJECTÉ ══ */

/* Bannière étape en haut */
#obj-content [style*="background:#"],
#obj-content [style*="background: #"],
#conn-content [style*="background:#"],
#conn-content [style*="background: #"] {
  background: rgba(201,168,76,0.08) !important;
  color: var(--text2) !important;
  border-color: var(--bdr-gold) !important;
}

/* TOUS les textes dans les questionnaires */
#obj-content, #obj-content *:not(button):not(input):not(select):not(textarea),
#conn-content, #conn-content *:not(button):not(input):not(select):not(textarea) {
  color: var(--text2) !important;
}

/* Titres h2/h3/h4 */
#obj-content h1,#obj-content h2,#obj-content h3,#obj-content h4,
#conn-content h1,#conn-content h2,#conn-content h3,#conn-content h4 {
  color: var(--text) !important;
  font-family: 'DM Serif Display', serif !important;
  font-weight: 400 !important;
}

/* q-title et section-header */
#obj-content .q-title, #conn-content .q-title {
  color: var(--gold2) !important;
  font-size: 15px !important;
  font-weight: 600 !important;
}

/* TOUS les inputs — forcer fond navy et texte blanc */
#obj-content input[type=text],
#obj-content input[type=number],
#obj-content input[type=email],
#obj-content input[type=date],
#obj-content input[type=tel],
#obj-content input[type=password],
#obj-content select,
#obj-content textarea,
#conn-content input[type=text],
#conn-content input[type=number],
#conn-content input[type=email],
#conn-content input[type=date],
#conn-content input[type=tel],
#conn-content select,
#conn-content textarea,
#obj-content .inline-input,
#conn-content .inline-input,
#obj-content .fc,
#conn-content .fc {
  background: rgba(255,255,255,0.06) !important;
  border: 1px solid rgba(255,255,255,0.12) !important;
  border-radius: 8px !important;
  color: #e2eaf6 !important;
  padding: 10px 14px !important;
  font-family: 'Inter', sans-serif !important;
  font-size: 13px !important;
  width: 100% !important;
  box-sizing: border-box !important;
  outline: none !important;
  -webkit-appearance: none !important;
  appearance: none !important;
}
#obj-content input:focus, #obj-content select:focus, #obj-content textarea:focus,
#conn-content input:focus, #conn-content select:focus, #conn-content textarea:focus {
  border-color: var(--gold) !important;
  background: rgba(255,255,255,0.08) !important;
}
#obj-content input::placeholder, #conn-content input::placeholder,
#obj-content textarea::placeholder, #conn-content textarea::placeholder {
  color: rgba(143,170,191,0.4) !important;
}
#obj-content select option, #conn-content select option {
  background: #102038 !important;
  color: #e2eaf6 !important;
}

/* radio-opt — forcer couleur texte visible */
#obj-content .radio-opt, #conn-content .radio-opt {
  background: rgba(255,255,255,0.05) !important;
  border: 1px solid rgba(255,255,255,0.12) !important;
  border-radius: 24px !important;
  color: #c8d8e8 !important;
  padding: 9px 18px !important;
  margin: 4px !important;
  cursor: pointer !important;
  font-size: 13px !important;
  font-weight: 400 !important;
  display: inline-flex !important;
  align-items: center !important;
  gap: 8px !important;
  transition: all 0.15s !important;
  line-height: 1.4 !important;
}
#obj-content .radio-opt:hover, #conn-content .radio-opt:hover {
  background: rgba(201,168,76,0.1) !important;
  border-color: rgba(201,168,76,0.3) !important;
  color: #e8c96a !important;
}
#obj-content .radio-opt.selected, #obj-content .radio-opt.on,
#conn-content .radio-opt.selected, #conn-content .radio-opt.on {
  background: rgba(201,168,76,0.15) !important;
  border-color: rgba(201,168,76,0.5) !important;
  color: #e8c96a !important;
  font-weight: 600 !important;
}
#obj-content .radio-opt input, #conn-content .radio-opt input {
  display: none !important;
}

/* Numéros de questions */
#obj-content p > strong, #conn-content p > strong,
#obj-content li > strong, #conn-content li > strong {
  color: var(--text) !important;
}

/* Questions (paragraphes) */
#obj-content p, #conn-content p {
  color: var(--text2) !important;
  font-size: 13px !important;
  line-height: 1.65 !important;
  margin-bottom: 10px !important;
}

/* check-opt */
#obj-content .check-opt, #conn-content .check-opt {
  background: rgba(255,255,255,0.04) !important;
  border: 1px solid rgba(255,255,255,0.09) !important;
  border-radius: 8px !important;
  color: #c8d8e8 !important;
  padding: 11px 15px !important;
  margin-bottom: 6px !important;
  cursor: pointer !important;
  font-size: 13px !important;
  display: flex !important;
  align-items: center !important;
  gap: 10px !important;
  transition: all 0.15s !important;
}
#obj-content .check-opt:hover, #conn-content .check-opt:hover {
  background: rgba(201,168,76,0.07) !important;
  border-color: rgba(201,168,76,0.25) !important;
}

/* data-table (patrimoine) */
#obj-content .data-table th, #conn-content .data-table th {
  background: rgba(201,168,76,0.07) !important;
  color: var(--gold) !important;
  font-size: 11px !important;
  font-weight: 600 !important;
  letter-spacing: 0.8px !important;
  text-transform: uppercase !important;
  padding: 11px 14px !important;
  border-bottom: 1px solid var(--bdr-gold) !important;
}
#obj-content .data-table td, #conn-content .data-table td {
  background: transparent !important;
  color: #c8d8e8 !important;
  padding: 9px 14px !important;
  border-bottom: 1px solid rgba(255,255,255,0.04) !important;
}
#obj-content .data-table tr:nth-child(even) td,
#conn-content .data-table tr:nth-child(even) td {
  background: rgba(255,255,255,0.02) !important;
}

/* info-box */
#obj-content .info-box, #conn-content .info-box {
  background: rgba(201,168,76,0.06) !important;
  border-left: 3px solid var(--gold) !important;
  border-radius: 0 8px 8px 0 !important;
  padding: 12px 16px !important;
  color: var(--text2) !important;
  font-size: 13px !important;
  line-height: 1.6 !important;
  margin: 14px 0 !important;
}

/* Masquer la bannière "Étape X/Y" */
#obj-content .progress-steps,
#obj-content [style*="Étape"],
#conn-content .progress-steps {
  display: none !important;
}

/* ══ INPUTS SANS TYPE EXPLICITE (défaut = text) ══ */
#obj-content input:not([type]),
#obj-content input[type=text],
#obj-content input[type=number],
#obj-content input[type=email],
#obj-content input[type=date],
#obj-content input[type=tel],
#obj-content select,
#obj-content textarea,
#conn-content input:not([type]),
#conn-content input[type=text],
#conn-content input[type=number],
#conn-content input[type=email],
#conn-content select,
#conn-content textarea {
  background-color: rgba(255,255,255,0.07) !important;
  background: rgba(255,255,255,0.07) !important;
  border: 1px solid rgba(255,255,255,0.14) !important;
  border-radius: 8px !important;
  color: #e2eaf6 !important;
  padding: 10px 14px !important;
  font-family: 'Inter', -apple-system, sans-serif !important;
  font-size: 13px !important;
  width: 100% !important;
  box-sizing: border-box !important;
  outline: none !important;
  -webkit-appearance: none !important;
  appearance: none !important;
  box-shadow: none !important;
}
#obj-content input:not([type]):focus,
#obj-content input[type=text]:focus,
#obj-content input[type=date]:focus,
#obj-content select:focus,
#conn-content input:not([type]):focus,
#conn-content select:focus {
  border-color: #c9a84c !important;
  background: rgba(255,255,255,0.09) !important;
  box-shadow: 0 0 0 3px rgba(201,168,76,0.12) !important;
}
#obj-content input::placeholder,
#conn-content input::placeholder {
  color: rgba(143,170,191,0.5) !important;
}

/* Sections qo-s cachées — forcer visible */
#obj-content [id^="qo-s"],
#obj-content .q-section {
  display: block !important;
  visibility: visible !important;
  opacity: 1 !important;
}

/* Forcer texte lisible partout dans obj-content */
#obj-content label,
#obj-content .form-group label,
#obj-content p,
#obj-content span,
#obj-content div:not(.card):not(.radio-opt):not(.check-opt) {
  color: #a8bbd4 !important;
}
#obj-content h1,#obj-content h2,#obj-content h3,#obj-content h4,
#obj-content .q-title,#obj-content strong {
  color: #e2eaf6 !important;
}
#obj-content .form-group label {
  color: #c9a84c !important;
  font-size: 11px !important;
  font-weight: 600 !important;
  letter-spacing: 0.8px !important;
  text-transform: uppercase !important;
  margin-bottom: 6px !important;
  display: block !important;
}

/* radio-opt état sélectionné forcé */
#conn-content label.radio-opt.selected,
#conn-content label.radio-opt.on,
#obj-content label.radio-opt.selected,
#obj-content label.radio-opt.on {
  background: rgba(201,168,76,0.18) !important;
  border-color: rgba(201,168,76,0.55) !important;
  color: #f0d878 !important;
  font-weight: 600 !important;
  box-shadow: 0 0 0 2px rgba(201,168,76,0.15) !important;
}
/* Profil graphique SVG - cercles cliquables */
#conn-content svg circle, #conn-content svg text {
  cursor: pointer !important;
}

/* risk-cards profil graphique */
.risk-card {
  border: 1px solid rgba(255,255,255,0.1) !important;
  border-radius: 8px !important;
  padding: 10px 12px !important;
  cursor: pointer !important;
  display: flex !important;
  align-items: center !important;
  gap: 10px !important;
  background: rgba(255,255,255,0.03) !important;
  transition: all 0.15s !important;
  margin-bottom: 6px !important;
}
.risk-card:hover {
  border-color: rgba(201,168,76,0.3) !important;
  background: rgba(201,168,76,0.06) !important;
}
.risk-card.selected {
  border-color: #c9a84c !important;
  background: rgba(201,168,76,0.12) !important;
}
.risk-card * { color: inherit !important; }
.risk-card div[style*="font-weight:700"] { color: #e2eaf6 !important; font-weight: 600 !important; }
.risk-card div[style*="font-size:10px"] { color: rgba(168,187,212,0.7) !important; }

</style>












<script>
















// ═══ CONFIG ═══
var MSG_BIN='69efcf8736566621a8fb341e',CLIENTS_BIN='69efcc82856a6821897cc233',JBKEY='$2a$10$H/fTo.AwPWr.044IVk/qoOQeZHgnUicO63Oobmk2KqcOUB7LFSGym';

// Fichier publié par le CRM (module "Publications") via l'API GitHub Contents.
// Format confirmé : { updated, items:[{id,ts,titre,date,contenu,url,type}] }
var PUBLICATIONS_URL='https://caremma828.github.io/caremma-data/publications.json';
function fetchPublications(){
  return fetch(PUBLICATIONS_URL+'?t='+Date.now(),{cache:'no-store'})
    .then(function(r){if(!r.ok)throw new Error('pub '+r.status);return r.json();})
    .then(function(j){return (j&&j.items)||[];})
    .catch(function(){return [];});
}
var EJS_PUBLIC='cstVoAsfF9vn4uc6C',EJS_SERVICE='service_qz3nkkq',EJS_TPL='template_wmauhka',EJS_TPL_SIG='template_88jyjec',EJS_SERVICE_SIG='service_hp5456h';
var _PHTML_B64="PGRpdiBpZD0icHMyIiBzdHlsZT0iZGlzcGxheTpibG9jayI+CiAgPGRpdiBjbGFzcz0ic2VjdGlvbi1oZWFkZXIiPgogICAgPGgyPlF1ZXN0aW9ubmFpcmUgT2JqZWN0aWZzPC9oMj4KICAgIDxkaXYgc3R5bGU9ImRpc3BsYXk6ZmxleDtnYXA6OHB4Ij4KICAgICAgPGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1vdXRsaW5lIGJ0bi1zbSIgb25jbGljaz0icHJldlN0ZXAoJ2VudHJlZScpIj7ihpAgw4l0YXBlIHByw6ljLjwvYnV0dG9uPgogICAgICA8YnV0dG9uIGNsYXNzPSJidG4gYnRuLXByaW1hcnkgYnRuLXNtIiBvbmNsaWNrPSJuZXh0U3RlcCgncW9iamVjdGlmcycsJ3F1ZXN0aW9ubmFpcmUnKSI+w4l0YXBlIHN1aXZhbnRlIOKGkjwvYnV0dG9uPgogICAgPC9kaXY+CiAgPC9kaXY+CiAgPGRpdiBjbGFzcz0iaW5mby1ib3giPvCfjq8gw4l0YXBlIDIvNCBkdSBwYXJjb3VycyBjbGllbnQg4oCUIFJlY3VlaWwgZGVzIG9iamVjdGlmcyBkZSBwbGFjZW1lbnQuPC9kaXY+CgogIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXBzIiBpZD0icW8tcHJvZ3Jlc3MiPgogICAgPGRpdiBjbGFzcz0icHJvZ3Jlc3Mtc3RlcCBhY3RpdmUiPjxkaXYgY2xhc3M9InBzLWRvdCI+MTwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5JZGVudGl0w6k8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+MjwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5TaXR1YXRpb248L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+MzwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5GaW5hbmNlczwvZGl2PjwvZGl2PgogICAgPGRpdiBjbGFzcz0icHJvZ3Jlc3Mtc3RlcCI+PGRpdiBjbGFzcz0icHMtZG90Ij40PC9kaXY+PGRpdiBjbGFzcz0icHMtbGFiZWwiPlBhdHJpbW9pbmU8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+NTwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5Db25uYWlzc2FuY2U8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+NjwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5PYmplY3RpZnM8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+NzwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5FU0c8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+ODwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5Qcm9maWw8L2Rpdj48L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpibG9jayIgaWQ9InFvLXMwIj4KICAgIDxkaXYgY2xhc3M9ImNhcmQiPgogICAgICA8ZGl2IGNsYXNzPSJxLXRpdGxlIj4xLiBJZGVudGl0w6kgZHUgc291c2NyaXB0ZXVyPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JpZCI+CiAgICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPkNpdmlsaXTDqTwvbGFiZWw+PHNlbGVjdCBpZD0icW8tY2l2Ij48b3B0aW9uPk1hZGFtZTwvb3B0aW9uPjxvcHRpb24+TW9uc2lldXI8L29wdGlvbj48L3NlbGVjdD48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+Tm9tIGRlIG5haXNzYW5jZTwvbGFiZWw+PGlucHV0IGlkPSJxby1ub20tbmFpc3MiIHBsYWNlaG9sZGVyPSJOb20gZGUgbmFpc3NhbmNlIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+Tm9tIGQndXNhZ2U8L2xhYmVsPjxpbnB1dCBpZD0icW8tbm9tLXVzYWdlIiBwbGFjZWhvbGRlcj0iTm9tIGQndXNhZ2UiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5QcsOpbm9tKHMpPC9sYWJlbD48aW5wdXQgaWQ9InFvLXByZW5vbSIgcGxhY2Vob2xkZXI9IlByw6lub20ocykiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5EYXRlIGRlIG5haXNzYW5jZTwvbGFiZWw+PGlucHV0IGlkPSJxby1kZG4iIHR5cGU9ImRhdGUiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5OYXRpb25hbGl0w6k8L2xhYmVsPjxpbnB1dCBpZD0icW8tbmF0aW9uYWxpdGUiIHZhbHVlPSJGcmFuw6dhaXNlIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIGZvcm0tZnVsbCI+PGxhYmVsPkFkcmVzc2UgcG9zdGFsZTwvbGFiZWw+PGlucHV0IGlkPSJxby1hZHJlc3NlIiBwbGFjZWhvbGRlcj0iQWRyZXNzZSBjb21wbMOodGUiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5FbWFpbDwvbGFiZWw+PGlucHV0IGlkPSJxby1lbWFpbCIgdHlwZT0iZW1haWwiIHBsYWNlaG9sZGVyPSJlbWFpbEBleGVtcGxlLmZyIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+VMOpbMOpcGhvbmU8L2xhYmVsPjxpbnB1dCBpZD0icW8tdGVsIiBwbGFjZWhvbGRlcj0iMDYuLi4iPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAgZm9ybS1mdWxsIj48bGFiZWw+VHJhbmNoZSBkJ8OiZ2U8L2xhYmVsPgogICAgICAgICAgPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2dhcDo4cHg7ZmxleC13cmFwOndyYXAiPgogICAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tYWdlIiB2YWx1ZT0iPDUwIj4gPGxhYmVsPk1vaW5zIGRlIDUwIGFuczwvbGFiZWw+PC9kaXY+CiAgICAgICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1hZ2UiIHZhbHVlPSI1MC02MCI+IDxsYWJlbD41MCDDoCA2MCBhbnM8L2xhYmVsPjwvZGl2PgogICAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tYWdlIiB2YWx1ZT0iNjEtNzAiPiA8bGFiZWw+NjEgw6AgNzAgYW5zPC9sYWJlbD48L2Rpdj4KICAgICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLWFnZSIgdmFsdWU9Ij43MCI+IDxsYWJlbD5QbHVzIGRlIDcwIGFuczwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8L2Rpdj4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPjxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0icW9OYXYoMSkiPlN1aXZhbnQg4oaSPC9idXR0b24+PC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpub25lIiBpZD0icW8tczEiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9InEtdGl0bGUiPjIuIFNpdHVhdGlvbiBmYW1pbGlhbGUgJiBwcm9mZXNzaW9ubmVsbGU8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncmlkIj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+U2l0dWF0aW9uIGZhbWlsaWFsZTwvbGFiZWw+CiAgICAgICAgICA8c2VsZWN0IGlkPSJxby1zaXQtZmFtIj48b3B0aW9uPkPDqWxpYmF0YWlyZTwvb3B0aW9uPjxvcHRpb24+TWFyacOpKGUpPC9vcHRpb24+PG9wdGlvbj5QYWNzw6koZSk8L29wdGlvbj48b3B0aW9uPkRpdm9yY8OpKGUpPC9vcHRpb24+PG9wdGlvbj5WZXVmKHZlKTwvb3B0aW9uPjwvc2VsZWN0PgogICAgICAgIDwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Sw6lnaW1lIG1hdHJpbW9uaWFsPC9sYWJlbD48aW5wdXQgaWQ9InFvLXJlZ2ltZSIgcGxhY2Vob2xkZXI9IkNvbW11bmF1dMOpIGzDqWdhbGUuLi4iPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Qcm9mZXNzaW9uPC9sYWJlbD48aW5wdXQgaWQ9InFvLXByb2Zlc3Npb24iIHBsYWNlaG9sZGVyPSJQcm9mZXNzaW9uLi4uIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+Q29uam9pbnQoZSk8L2xhYmVsPjxpbnB1dCBpZD0icW8tY29uam9pbnQiIHBsYWNlaG9sZGVyPSJOb20gJiBwcm9mZXNzaW9uIGR1IGNvbmpvaW50Ij48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+QW5uw6llIGTDqXBhcnQgcmV0cmFpdGUgcHLDqXZ1PC9sYWJlbD48aW5wdXQgaWQ9InFvLXJldHJhaXRlIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIyMDMwIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+UFBFPC9sYWJlbD4KICAgICAgICAgIDxzZWxlY3QgaWQ9InFvLXBwZSI+PG9wdGlvbiB2YWx1ZT0ibm9uIj5Ob248L29wdGlvbj48b3B0aW9uIHZhbHVlPSJvdWkiPk91aSDigJQgUGVyc29ubmUgUG9saXRpcXVlbWVudCBFeHBvc8OpZTwvb3B0aW9uPjwvc2VsZWN0PgogICAgICAgIDwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAgZm9ybS1mdWxsIj48bGFiZWw+RW5mYW50cyDDoCBjaGFyZ2U8L2xhYmVsPgogICAgICAgICAgPGRpdiBpZD0icW8tZW5mYW50cy1saXN0IiBzdHlsZT0ibWFyZ2luLWJvdHRvbTo4cHgiPjwvZGl2PgogICAgICAgICAgPGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1vdXRsaW5lIGJ0bi1zbSIgb25jbGljaz0iYWRkRW5mYW50Um93KCkiPisgQWpvdXRlciBlbmZhbnQ8L2J1dHRvbj4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPjxidXR0b24gY2xhc3M9ImJ0biBidG4tb3V0bGluZSIgb25jbGljaz0icW9OYXYoMCkiPuKGkCBQcsOpY8OpZGVudDwvYnV0dG9uPjxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0icW9OYXYoMikiPlN1aXZhbnQg4oaSPC9idXR0b24+PC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpub25lIiBpZD0icW8tczIiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9InEtdGl0bGUiPjMuIFNpdHVhdGlvbiBmaW5hbmNpw6hyZTwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyaWQiPgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5SZXZlbnVzIGFubnVlbHMgZHUgY2xpZW50ICjigqwpPC9sYWJlbD48aW5wdXQgaWQ9InFvLXJldi1jbGllbnQiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5SZXZlbnVzIGR1IGNvbmpvaW50ICjigqwpPC9sYWJlbD48aW5wdXQgaWQ9InFvLXJldi1jb25qb2ludCIgdHlwZT0ibnVtYmVyIiBwbGFjZWhvbGRlcj0iMCI+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPlJldmVudXMgZm9uY2llcnMgKOKCrCk8L2xhYmVsPjxpbnB1dCBpZD0icW8tcmV2LWZvbmNpZXIiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5SZXZlbnVzIGRlIGNhcGl0YXV4IG1vYmlsaWVycyAo4oKsKTwvbGFiZWw+PGlucHV0IGlkPSJxby1yZXYtcmNtIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+Q2hhcmdlcyBhbm51ZWxsZXMgZHUgZm95ZXIgKOKCrCk8L2xhYmVsPjxpbnB1dCBpZD0icW8tY2hhcmdlcyIgdHlwZT0ibnVtYmVyIiBwbGFjZWhvbGRlcj0iMCI+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPkNhcGFjaXTDqSBkJ8OpcGFyZ25lIGFubnVlbGxlICjigqwpPC9sYWJlbD48aW5wdXQgaWQ9InFvLWVwYXJnbmUiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiIG9uaW5wdXQ9ImNhbGNFcGFyZ25lKCkiPjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBpZD0icW8tZXBhcmduZS1yZXN1bHQiIHN0eWxlPSJiYWNrZ3JvdW5kOnZhcigtLW9mZik7Ym9yZGVyLXJhZGl1czo3cHg7cGFkZGluZzoxMHB4IDE0cHg7Zm9udC1zaXplOjEyLjVweDtjb2xvcjp2YXIoLS1tdXRlZCk7bWFyZ2luLXRvcDo4cHgiPjwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJxLW5hdi1idG5zIj48YnV0dG9uIGNsYXNzPSJidG4gYnRuLW91dGxpbmUiIG9uY2xpY2s9InFvTmF2KDEpIj7ihpAgUHLDqWPDqWRlbnQ8L2J1dHRvbj48YnV0dG9uIGNsYXNzPSJidG4gYnRuLWdvbGQiIG9uY2xpY2s9InFvTmF2KDMpIj5TdWl2YW50IOKGkjwvYnV0dG9uPjwvZGl2PgogICAgPC9kaXY+CiAgPC9kaXY+CgogIDxkaXYgY2xhc3M9InEtc2VjdGlvbiIgc3R5bGU9ImRpc3BsYXk6bm9uZSIgaWQ9InFvLXMzIj4KICAgIDxkaXYgY2xhc3M9ImNhcmQiPgogICAgICA8ZGl2IGNsYXNzPSJxLXRpdGxlIj40LiBQYXRyaW1vaW5lPC9kaXY+CiAgICAgIDxkaXYgaWQ9InFvLXBhdHJpbW9pbmUtdGFibGUiIHN0eWxlPSJtYXJnaW4tYm90dG9tOjE0cHgiPgogICAgICAgIDx0YWJsZSBjbGFzcz0iZGF0YS10YWJsZSIgc3R5bGU9ImZvbnQtc2l6ZToxMnB4Ij4KICAgICAgICAgIDx0aGVhZD48dHI+PHRoPk5hdHVyZSBkdSBwbGFjZW1lbnQ8L3RoPjx0aD5Nb250YW50IHPDqWN1cml0YWlyZSAo4oKsKTwvdGg+PHRoPk1vbnRhbnQgcmlzcXXDqSAvIFVDICjigqwpPC90aD48L3RyPjwvdGhlYWQ+CiAgICAgICAgICA8dGJvZHk+CiAgICAgICAgICAgIDx0cj48dGQ+TGl2cmV0cyByw6lnbGVtZW50w6lzIChBLCBMRETigKYpPC90ZD48dGQ+PGlucHV0IGNsYXNzPSJpbmxpbmUtaW5wdXQiIGlkPSJwdGYtbGl2cmV0cy1zIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD7igJQ8L3RkPjwvdHI+CiAgICAgICAgICAgIDx0cj48dGQ+w4lwYXJnbmUgbG9nZW1lbnQgKENFTC9QRUwpPC90ZD48dGQ+PGlucHV0IGNsYXNzPSJpbmxpbmUtaW5wdXQiIGlkPSJwdGYtY2VsIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD7igJQ8L3RkPjwvdHI+CiAgICAgICAgICAgIDx0cj48dGQ+UEVQPC90ZD48dGQ+PGlucHV0IGNsYXNzPSJpbmxpbmUtaW5wdXQiIGlkPSJwdGYtcGVwLXMiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiPjwvdGQ+PHRkPjxpbnB1dCBjbGFzcz0iaW5saW5lLWlucHV0IiBpZD0icHRmLXBlcC1yIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjwvdHI+CiAgICAgICAgICAgIDx0cj48dGQ+QXNzdXJhbmNlLXZpZSAvIFBFUlA8L3RkPjx0ZD48aW5wdXQgY2xhc3M9ImlubGluZS1pbnB1dCIgaWQ9InB0Zi1hdi1zIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD48aW5wdXQgY2xhc3M9ImlubGluZS1pbnB1dCIgaWQ9InB0Zi1hdi1yIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjwvdHI+CiAgICAgICAgICAgIDx0cj48dGQ+UEVBIC8gQ29tcHRlLXRpdHJlczwvdGQ+PHRkPuKAlDwvdGQ+PHRkPjxpbnB1dCBjbGFzcz0iaW5saW5lLWlucHV0IiBpZD0icHRmLXBlYSIgdHlwZT0ibnVtYmVyIiBwbGFjZWhvbGRlcj0iMCI+PC90ZD48L3RyPgogICAgICAgICAgICA8dHI+PHRkPsOJcGFyZ25lIHNhbGFyaWFsZTwvdGQ+PHRkPjxpbnB1dCBjbGFzcz0iaW5saW5lLWlucHV0IiBpZD0icHRmLXNhbC1zIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD48aW5wdXQgY2xhc3M9ImlubGluZS1pbnB1dCIgaWQ9InB0Zi1zYWwtciIgdHlwZT0ibnVtYmVyIiBwbGFjZWhvbGRlcj0iMCI+PC90ZD48L3RyPgogICAgICAgICAgICA8dHI+PHRkPkltbW9iaWxpZXI8L3RkPjx0ZD48aW5wdXQgY2xhc3M9ImlubGluZS1pbnB1dCIgaWQ9InB0Zi1pbW1vIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD7igJQ8L3RkPjwvdHI+CiAgICAgICAgICA8L3Rib2R5PgogICAgICAgIDwvdGFibGU+CiAgICAgICAgPHN0eWxlPi5pbmxpbmUtaW5wdXR7Ym9yZGVyOm5vbmU7Ym9yZGVyLWJvdHRvbToxLjVweCBzb2xpZCB2YXIoLS1saWdodCk7YmFja2dyb3VuZDp0cmFuc3BhcmVudDt3aWR0aDoxMDBweDtwYWRkaW5nOjNweCA2cHg7Zm9udC1zaXplOjEycHg7Y29sb3I6dmFyKC0tdGV4dCl9LmlubGluZS1pbnB1dDpmb2N1c3tvdXRsaW5lOm5vbmU7Ym9yZGVyLWJvdHRvbS1jb2xvcjp2YXIoLS1nb2xkKX08L3N0eWxlPgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncmlkIj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+UHJvcHJpw6l0YWlyZSBpbW1vYmlsaWVyID88L2xhYmVsPjxzZWxlY3QgaWQ9InFvLXByb3ByaW8iPjxvcHRpb24+Tm9uPC9vcHRpb24+PG9wdGlvbj5PdWkg4oCUIHLDqXNpZGVuY2UgcHJpbmNpcGFsZTwvb3B0aW9uPjxvcHRpb24+T3VpIOKAlCByw6lzaWRlbmNlIHNlY29uZGFpcmU8L29wdGlvbj48b3B0aW9uPk91aSDigJQgaW52ZXN0aXNzZW1lbnQgbG9jYXRpZjwvb3B0aW9uPjwvc2VsZWN0PjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5QYXJ0IHPDqWN1cml0YWlyZSBkdSBwYXRyaW1vaW5lPC9sYWJlbD48c2VsZWN0IGlkPSJxby1wYXJ0LXNlY3UiPjxvcHRpb24+Jmd0OyA2MCU8L29wdGlvbj48b3B0aW9uPjMwLTYwJTwvb3B0aW9uPjxvcHRpb24+Jmx0OyAzMCU8L29wdGlvbj48L3NlbGVjdD48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+UGFydCBkZSBjZSBwcm9qZXQgZGFucyBsZSBwYXRyaW1vaW5lPC9sYWJlbD48c2VsZWN0IGlkPSJxby1wYXJ0LXByb2pldCI+PG9wdGlvbj4mbHQ7IDIwJTwvb3B0aW9uPjxvcHRpb24+MjAtNTAlPC9vcHRpb24+PG9wdGlvbj4mZ3Q7IDUwJTwvb3B0aW9uPjwvc2VsZWN0PjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0icS1uYXYtYnRucyI+PGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1vdXRsaW5lIiBvbmNsaWNrPSJxb05hdigyKSI+4oaQIFByw6ljw6lkZW50PC9idXR0b24+PGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1nb2xkIiBvbmNsaWNrPSJxb05hdig0KSI+U3VpdmFudCDihpI8L2J1dHRvbj48L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJxLXNlY3Rpb24iIHN0eWxlPSJkaXNwbGF5Om5vbmUiIGlkPSJxby1zNCI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkIj4KICAgICAgPGRpdiBjbGFzcz0icS10aXRsZSI+NS4gQ29ubmFpc3NhbmNlICYgZXhww6lyaWVuY2UgZmluYW5jacOocmU8L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNHB4Ij4KICAgICAgICA8bGFiZWwgc3R5bGU9ImZvbnQtc2l6ZToxMnB4O2ZvbnQtd2VpZ2h0OjYwMDtjb2xvcjp2YXIoLS1uYXZ5KSI+Tml2ZWF1IGRlIGNvbm5haXNzYW5jZSBkZXMgbWFyY2jDqXMgOjwvbGFiZWw+CiAgICAgICAgPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2dhcDo4cHg7ZmxleC13cmFwOndyYXA7bWFyZ2luLXRvcDo4cHgiPgogICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLWNvbm5haXMiIHZhbHVlPSIwIj48bGFiZWw+SW5leGlzdGFudGU8L2xhYmVsPjwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLWNvbm5haXMiIHZhbHVlPSIxIj48bGFiZWw+TW9kw6lyw6llPC9sYWJlbD48L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1jb25uYWlzIiB2YWx1ZT0iMiI+PGxhYmVsPkNvcnJlY3RlPC9sYWJlbD48L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1jb25uYWlzIiB2YWx1ZT0iMyI+PGxhYmVsPkJvbm5lPC9sYWJlbD48L2Rpdj4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi1ib3R0b206MTRweCI+CiAgICAgICAgPGxhYmVsIHN0eWxlPSJmb250LXNpemU6MTJweDtmb250LXdlaWdodDo2MDA7Y29sb3I6dmFyKC0tbmF2eSkiPkVuIGNhcyBkZSBiYWlzc2UgZGUgMTUlIGRlIHZvcyBwbGFjZW1lbnRzLCB2b3VzIDo8L2xhYmVsPgogICAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi10b3A6OHB4Ij4KICAgICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1yZWFjdGlvbiIgdmFsdWU9IjAiPjxsYWJlbD5WZW5kZXogdG91dCBpbW3DqWRpYXRlbWVudDwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tcmVhY3Rpb24iIHZhbHVlPSIxIj48bGFiZWw+QXR0ZW5kZXogcXVlIGxlcyB2YWxldXJzIHJlbW9udGVudDwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tcmVhY3Rpb24iIHZhbHVlPSIyIj48bGFiZWw+VmVuZGV6IGxhIHBhcnRpZSBheWFudCBsZSBwbHVzIGJhaXNzw6k8L2xhYmVsPjwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXJlYWN0aW9uIiB2YWx1ZT0iMyI+PGxhYmVsPlByb2ZpdGV6IGRlIGxhIGJhaXNzZSBwb3VyIGludmVzdGlyIGRhdmFudGFnZTwvbGFiZWw+PC9kaXY+CiAgICAgICAgPC9kaXY+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyaWQiPgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5UcmFuc2FjdGlvbnMgc3VyIE9QQ1ZNIC8gZm9uZHMgPzwvbGFiZWw+PHNlbGVjdCBpZD0icW8tb3Bjdm0iPjxvcHRpb24+Tm9uPC9vcHRpb24+PG9wdGlvbj5PdWk8L29wdGlvbj48L3NlbGVjdD48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+R2VzdGlvbiBzb3VzIG1hbmRhdCA/PC9sYWJlbD48c2VsZWN0IGlkPSJxby1tYW5kYXQiPjxvcHRpb24+Tm9uPC9vcHRpb24+PG9wdGlvbj5PdWk8L29wdGlvbj48L3NlbGVjdD48L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPjxidXR0b24gY2xhc3M9ImJ0biBidG4tb3V0bGluZSIgb25jbGljaz0icW9OYXYoMykiPuKGkCBQcsOpY8OpZGVudDwvYnV0dG9uPjxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0icW9OYXYoNSkiPlN1aXZhbnQg4oaSPC9idXR0b24+PC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpub25lIiBpZD0icW8tczUiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9InEtdGl0bGUiPjYuIE9iamVjdGlmcyBkZSBzb3VzY3JpcHRpb248L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNnB4Ij4KICAgICAgICA8bGFiZWwgc3R5bGU9ImZvbnQtc2l6ZToxMnB4O2ZvbnQtd2VpZ2h0OjYwMDtjb2xvcjp2YXIoLS1uYXZ5KSI+T2JqZWN0aWYocykgcHJpbmNpcGFsKGF1eCkgKHBsdXNpZXVycyBjaG9peCBwb3NzaWJsZXMpIDo8L2xhYmVsPgogICAgICAgIDxkaXYgc3R5bGU9ImRpc3BsYXk6Z3JpZDtncmlkLXRlbXBsYXRlLWNvbHVtbnM6MWZyIDFmcjtnYXA6OHB4O21hcmdpbi10b3A6OHB4Ij4KICAgICAgICAgIDxkaXYgY2xhc3M9ImNoZWNrLW9wdCI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW8tb2JqLXByZWNhdXRpb24iPjxsYWJlbCBmb3I9InFvLW9iai1wcmVjYXV0aW9uIj7DiXBhcmduZSBkZSBwcsOpY2F1dGlvbjwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJjaGVjay1vcHQiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9InFvLW9iai1wcm9ncmVzc2lmIj48bGFiZWwgZm9yPSJxby1vYmotcHJvZ3Jlc3NpZiI+Q29uc3RpdHVlciB1bmUgw6lwYXJnbmUgcHJvZ3Jlc3NpdmU8L2xhYmVsPjwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0iY2hlY2stb3B0Ij48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJxby1vYmotcHJvY2hlcyI+PGxhYmVsIGZvcj0icW8tb2JqLXByb2NoZXMiPkFpZGVyIHNlcyBwcm9jaGVzIC8gaMOpcml0aWVyczwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJjaGVjay1vcHQiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9InFvLW9iai1yZXZlbnVzIj48bGFiZWwgZm9yPSJxby1vYmotcmV2ZW51cyI+Q29tcGzDqXRlciBzZXMgcmV2ZW51czwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJjaGVjay1vcHQiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9InFvLW9iai12YWxvcmlzZXIiPjxsYWJlbCBmb3I9InFvLW9iai12YWxvcmlzZXIiPlZhbG9yaXNlciB1biBjYXBpdGFsIGV4aXN0YW50PC9sYWJlbD48L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9ImNoZWNrLW9wdCI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW8tb2JqLXJldHJhaXRlIj48bGFiZWwgZm9yPSJxby1vYmotcmV0cmFpdGUiPlByw6lwYXJlciBzYSByZXRyYWl0ZTwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJjaGVjay1vcHQiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9InFvLW9iai1maXNjYWxpdGUiPjxsYWJlbCBmb3I9InFvLW9iai1maXNjYWxpdGUiPk9wdGltaXNlciBzYSBmaXNjYWxpdMOpPC9sYWJlbD48L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9ImNoZWNrLW9wdCI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW8tb2JqLXRyYW5zbWlzc2lvbiI+PGxhYmVsIGZvcj0icW8tb2JqLXRyYW5zbWlzc2lvbiI+T3B0aW1pc2VyIGxhIHRyYW5zbWlzc2lvbjwvbGFiZWw+PC9kaXY+CiAgICAgICAgPC9kaXY+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyaWQiPgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Ib3Jpem9uIGRlIHBsYWNlbWVudDwvbGFiZWw+CiAgICAgICAgICA8c2VsZWN0IGlkPSJxby1ob3Jpem9uIj48b3B0aW9uPk1vaW5zIGRlIDMgYW5zPC9vcHRpb24+PG9wdGlvbj4zIMOgIDUgYW5zPC9vcHRpb24+PG9wdGlvbj41IMOgIDggYW5zPC9vcHRpb24+PG9wdGlvbiBzZWxlY3RlZD5QbHVzIGRlIDggYW5zPC9vcHRpb24+PC9zZWxlY3Q+CiAgICAgICAgPC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPk1vbnRhbnQgw6AgcGxhY2VyICjigqwpPC9sYWJlbD48aW5wdXQgaWQ9InFvLW1vbnRhbnQiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAgZm9ybS1mdWxsIj48bGFiZWw+QXBwcm9jaGUgcGFyIHJhcHBvcnQgYXUgcmlzcXVlPC9sYWJlbD4KICAgICAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi10b3A6NnB4Ij4KICAgICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXJpc3F1ZSIgdmFsdWU9InNlY3VyaXRhaXJlIj48bGFiZWw+UGxhY2VtZW50IHPDqWN1cmlzw6ksIHBlcmZvcm1hbmNlIG1vaW5zIMOpbGV2w6llPC9sYWJlbD48L2Rpdj4KICAgICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXJpc3F1ZSIgdmFsdWU9InBydWRlbnQiPjxsYWJlbD5SaXNxdWUgZmFpYmxlIHBvdXIgdW4gcGV1IHBsdXMgZGUgcmVuZGVtZW50PC9sYWJlbD48L2Rpdj4KICAgICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXJpc3F1ZSIgdmFsdWU9Im1vZGVyZSI+PGxhYmVsPlJpc3F1ZSBtZXN1csOpIHBvdXIgYW3DqWxpb3JlciBsZSByZW5kZW1lbnQ8L2xhYmVsPjwvZGl2PgogICAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tcmlzcXVlIiB2YWx1ZT0iZHluYW1pcXVlIj48bGFiZWw+QXZhbnQgdG91dCB1biByZW5kZW1lbnQgw6lsZXbDqSwgcXVpdHRlIMOgIHByZW5kcmUgZGVzIHJpc3F1ZXMgaW1wb3J0YW50czwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8L2Rpdj4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPjxidXR0b24gY2xhc3M9ImJ0biBidG4tb3V0bGluZSIgb25jbGljaz0icW9OYXYoNCkiPuKGkCBQcsOpY8OpZGVudDwvYnV0dG9uPjxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0icW9OYXYoNikiPlN1aXZhbnQg4oaSPC9idXR0b24+PC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpub25lIiBpZD0icW8tczYiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9InEtdGl0bGUiPjcuIFByw6lmw6lyZW5jZXMgRVNHIC8gRHVyYWJpbGl0w6kgKFNGRFIpPC9kaXY+CiAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi1ib3R0b206MTJweCI+CiAgICAgICAgPGRpdiBjbGFzcz0iY2hlY2stb3B0Ij48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJxby1lc2ctc2Vuc2libGUiPjxsYWJlbCBmb3I9InFvLWVzZy1zZW5zaWJsZSI+SmUgc3VpcyBzZW5zaWJsZSBhdXggY3JpdMOocmVzIEVTRyAoZW52aXJvbm5lbWVudCwgc29jaWFsLCBnb3V2ZXJuYW5jZSk8L2xhYmVsPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImNoZWNrLW9wdCI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW8tZXNnLWludGVncmVyIj48bGFiZWwgZm9yPSJxby1lc2ctaW50ZWdyZXIiPkplIHNvdWhhaXRlIGludMOpZ3JlciBkZXMgY3JpdMOocmVzIGRlIGR1cmFiaWxpdMOpIGRhbnMgbWVzIGludmVzdGlzc2VtZW50czwvbGFiZWw+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0iY2hlY2stb3B0Ij48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJxby1lc2ctbGFiZWwiPjxsYWJlbCBmb3I9InFvLWVzZy1sYWJlbCI+w4AgcHJvZHVpdCDDqXF1aXZhbGVudCwgamUgcHJpdmlsw6lnaWUgdW4gZm9uZHMgYXZlYyBsYWJlbCBFU0c8L2xhYmVsPjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPkF4ZSBkZSBwcsOpZsOpcmVuY2UgRVNHPC9sYWJlbD4KICAgICAgICA8c2VsZWN0IGlkPSJxby1lc2ctYXhlIj48b3B0aW9uPkF1Y3VuZSBwcsOpZsOpcmVuY2UgcGFydGljdWxpw6hyZTwvb3B0aW9uPjxvcHRpb24+RW52aXJvbm5lbWVudCAoRSk8L29wdGlvbj48b3B0aW9uPlNvY2lhbCAoUyk8L29wdGlvbj48b3B0aW9uPkdvdXZlcm5hbmNlIChHKTwvb3B0aW9uPjxvcHRpb24+Q29tYmluYWlzb24gRVNHPC9vcHRpb24+PC9zZWxlY3Q+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIiBzdHlsZT0ibWFyZ2luLXRvcDoxMnB4Ij48bGFiZWw+UGFydCBkZSBsJ8OpcGFyZ25lIGTDqWRpw6llIMOgIGwnaW52ZXN0aXNzZW1lbnQgZHVyYWJsZTwvbGFiZWw+CiAgICAgICAgPHNlbGVjdCBpZD0icW8tZXNnLXBhcnQiPjxvcHRpb24+MCU8L29wdGlvbj48b3B0aW9uPk1vaW5zIGRlIDIwJTwvb3B0aW9uPjxvcHRpb24+MjAgw6AgNTAlPC9vcHRpb24+PG9wdGlvbj5QbHVzIGRlIDUwJTwvb3B0aW9uPjwvc2VsZWN0PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0icS1uYXYtYnRucyI+PGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1vdXRsaW5lIiBvbmNsaWNrPSJxb05hdig1KSI+4oaQIFByw6ljw6lkZW50PC9idXR0b24+PGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1nb2xkIiBvbmNsaWNrPSJxb05hdig3KSI+U3VpdmFudCDihpI8L2J1dHRvbj48L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJxLXNlY3Rpb24iIHN0eWxlPSJkaXNwbGF5Om5vbmUiIGlkPSJxby1zNyI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkIj4KICAgICAgPGRpdiBjbGFzcz0icS10aXRsZSI+OC4gUHJvZmlsIGRlIHJpc3F1ZSAmIFZhbGlkYXRpb248L2Rpdj4KICAgICAgPGRpdiBpZD0icW8tc2NvcmUtcmVzdWx0IiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNnB4Ij48L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0iZGlzcGxheTpncmlkO2dyaWQtdGVtcGxhdGUtY29sdW1uczpyZXBlYXQoNCwxZnIpO2dhcDoxMHB4O21hcmdpbi1ib3R0b206MTZweCIgaWQ9InFvLXByb2ZpbC1ncmlkIj4KICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiIHN0eWxlPSJmbGV4LWRpcmVjdGlvbjpjb2x1bW47YWxpZ24taXRlbXM6Y2VudGVyO3RleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXByb2ZpbCIgdmFsdWU9IlPDqWN1cml0YWlyZSI+PGxhYmVsPjxiPlPDiUNVUklUQUlSRTwvYj48YnI+PHNtYWxsIHN0eWxlPSJjb2xvcjp2YXIoLS1tdXRlZCkiPlJpc3F1ZSBmYWlibGU8L3NtYWxsPjwvbGFiZWw+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0IiBzdHlsZT0iZmxleC1kaXJlY3Rpb246Y29sdW1uO2FsaWduLWl0ZW1zOmNlbnRlcjt0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1wcm9maWwiIHZhbHVlPSJNb2TDqXLDqSIgY2hlY2tlZD48bGFiZWw+PGI+TU9Ew4lSw4k8L2I+PGJyPjxzbWFsbCBzdHlsZT0iY29sb3I6dmFyKC0tbXV0ZWQpIj5SaXNxdWUgbW9kw6lyw6k8L3NtYWxsPjwvbGFiZWw+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0IiBzdHlsZT0iZmxleC1kaXJlY3Rpb246Y29sdW1uO2FsaWduLWl0ZW1zOmNlbnRlcjt0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1wcm9maWwiIHZhbHVlPSJEeW5hbWlxdWUiPjxsYWJlbD48Yj5EWU5BTUlRVUU8L2I+PGJyPjxzbWFsbCBzdHlsZT0iY29sb3I6dmFyKC0tbXV0ZWQpIj5SaXNxdWUgaW1wb3J0YW50PC9zbWFsbD48L2xhYmVsPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCIgc3R5bGU9ImZsZXgtZGlyZWN0aW9uOmNvbHVtbjthbGlnbi1pdGVtczpjZW50ZXI7dGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tcHJvZmlsIiB2YWx1ZT0iT2ZmZW5zaWYiPjxsYWJlbD48Yj5PRkZFTlNJRjwvYj48YnI+PHNtYWxsIHN0eWxlPSJjb2xvcjp2YXIoLS1tdXRlZCkiPlJpc3F1ZSDDqWxldsOpPC9zbWFsbD48L2xhYmVsPjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPkNvbW1lbnRhaXJlIGNvbnNlaWxsZXI8L2xhYmVsPjx0ZXh0YXJlYSBpZD0icW8tY29tbWVudGFpcmUiIHJvd3M9IjMiIHBsYWNlaG9sZGVyPSJPYnNlcnZhdGlvbnMgc3VyIGxlIHByb2ZpbCBjbGllbnQuLi4iPjwvdGV4dGFyZWE+PC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPgogICAgICAgIDxidXR0b24gY2xhc3M9ImJ0biBidG4tb3V0bGluZSIgb25jbGljaz0icW9OYXYoNikiPuKGkCBQcsOpY8OpZGVudDwvYnV0dG9uPgogICAgICAgIDxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0ibWFya1N0ZXBEb25lKCdxb2JqZWN0aWZzJyk7bmV4dFN0ZXAoJ3FvYmplY3RpZnMnLCdxdWVzdGlvbm5haXJlJykiPuKckyBWYWxpZGVyICYgY29udGludWVyIOKGkjwvYnV0dG9uPgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2Pgo8L2Rpdj4KCg==";
var _PARCOURS_TOOL_B64="PCFET0NUWVBFIGh0bWw+CjxodG1sIGxhbmc9ImZyIj4KPGhlYWQ+CjxtZXRhIGNoYXJzZXQ9IlVURi04Ij4KPHRpdGxlPlBhcmNvdXJzIENsaWVudCBDb21wbGV0IOKAlCBDYXJlbW1hIEZpbmFuY2U8L3RpdGxlPgo8c3R5bGU+CiAgOnJvb3R7CiAgICAtLW5hdnk6IzBmMWUzNTsgLS1uYXZ5MjojMTYyODNmOyAtLWdvbGQ6I2M5YTg0YzsgLS1nb2xkMjojYjg5NDRhOwogICAgLS1jcmVhbTojZjdmNWVmOyAtLXRleHQ6IzFhMWEyZTsgLS1tdXRlZDojNWE2YTdhOyAtLWxpbmU6I2RkZDljZTsgLS1ncmVlbjojMWE3YTNhOwogIH0KICAqe2JveC1zaXppbmc6Ym9yZGVyLWJveH0KICBib2R5e2ZvbnQtZmFtaWx5Okdlb3JnaWEsJ1RpbWVzIE5ldyBSb21hbicsc2VyaWY7Y29sb3I6dmFyKC0tdGV4dCk7YmFja2dyb3VuZDojZWNlZmYyO21hcmdpbjowO3BhZGRpbmc6MCAwIDYwcHh9CiAgLnNoZWV0e21heC13aWR0aDo5MDBweDttYXJnaW46MCBhdXRvO2JhY2tncm91bmQ6I2ZmZjtib3gtc2hhZG93OjAgNHB4IDI0cHggcmdiYSgwLDAsMCwuMDgpfQogIC5oZXJve2JhY2tncm91bmQ6dmFyKC0tbmF2eSk7Y29sb3I6I2ZmZjtwYWRkaW5nOjI0cHggNDBweCAxOHB4fQogIC5oZXJvIC5icmFuZHtjb2xvcjp2YXIoLS1nb2xkKTtmb250LXdlaWdodDpib2xkO2ZvbnQtc2l6ZToyMHB4O2xldHRlci1zcGFjaW5nOi4zcHh9CiAgLmhlcm8gLnN1Yntjb2xvcjojYjljMmNlO2ZvbnQtc2l6ZToxMXB4O21hcmdpbi10b3A6MnB4fQogIC5oZXJvIGgxe2ZvbnQtc2l6ZToyNHB4O21hcmdpbjoxMnB4IDAgMnB4fQogIC5oZXJvIC50YWdsaW5le2NvbG9yOnZhcigtLWdvbGQpO2ZvbnQtc3R5bGU6aXRhbGljO2ZvbnQtc2l6ZToxMnB4fQogIC5nb2xkYmFye2hlaWdodDo0cHg7YmFja2dyb3VuZDpsaW5lYXItZ3JhZGllbnQoOTBkZWcsdmFyKC0tZ29sZCksI2U4ZDlhOCx2YXIoLS1nb2xkKSl9CiAgLmNvbnRlbnR7cGFkZGluZzoyMnB4IDQwcHggMTBweH0KICAuaW50cm97Zm9udC1zaXplOjEzcHg7Y29sb3I6dmFyKC0tbXV0ZWQpO2xpbmUtaGVpZ2h0OjEuNjttYXJnaW4tYm90dG9tOjEycHh9CiAgLnNlYy1iYXJ7YmFja2dyb3VuZDp2YXIoLS1uYXZ5KTtjb2xvcjp2YXIoLS1nb2xkKTtmb250LXdlaWdodDpib2xkO2ZvbnQtc2l6ZToxMi41cHg7bGV0dGVyLXNwYWNpbmc6LjVweDtwYWRkaW5nOjlweCAxNnB4O21hcmdpbjoyMnB4IDAgMTJweDt0ZXh0LXRyYW5zZm9ybTp1cHBlcmNhc2V9CiAgaDMuc3Vie2ZvbnQtc2l6ZToxNHB4O2NvbG9yOnZhcigtLW5hdnkpO21hcmdpbjoxNnB4IDAgN3B4fQogIC5jYXJke2JhY2tncm91bmQ6dmFyKC0tY3JlYW0pO2JvcmRlcjoxcHggc29saWQgdmFyKC0tbGluZSk7Ym9yZGVyLXJhZGl1czo4cHg7cGFkZGluZzoxM3B4IDE3cHg7bWFyZ2luLWJvdHRvbToxMnB4fQogIGxhYmVsLmZpZWxke2Rpc3BsYXk6YmxvY2s7Zm9udC1zaXplOjEwLjVweDtjb2xvcjp2YXIoLS1tdXRlZCk7Zm9udC1zdHlsZTppdGFsaWM7bWFyZ2luLWJvdHRvbTozcHh9CiAgLmdyaWQye2Rpc3BsYXk6Z3JpZDtncmlkLXRlbXBsYXRlLWNvbHVtbnM6MWZyIDFmcjtnYXA6OXB4IDE4cHh9CiAgaW5wdXRbdHlwZT10ZXh0XSxpbnB1dFt0eXBlPW51bWJlcl0saW5wdXRbdHlwZT1kYXRlXSx0ZXh0YXJlYSxzZWxlY3R7CiAgICB3aWR0aDoxMDAlO3BhZGRpbmc6NnB4IDlweDtib3JkZXI6MXB4IHNvbGlkIHZhcigtLWxpbmUpO2JvcmRlci1yYWRpdXM6NXB4O2ZvbnQtZmFtaWx5OmluaGVyaXQ7Zm9udC1zaXplOjEyLjVweDtiYWNrZ3JvdW5kOiNmZmY7CiAgfQogIHRleHRhcmVhe3Jlc2l6ZTp2ZXJ0aWNhbH0KICB0YWJsZXt3aWR0aDoxMDAlO2JvcmRlci1jb2xsYXBzZTpjb2xsYXBzZTtmb250LXNpemU6MTJweDttYXJnaW4tYm90dG9tOjlweH0KICB0aHtiYWNrZ3JvdW5kOnZhcigtLW5hdnkpO2NvbG9yOnZhcigtLWdvbGQpO3BhZGRpbmc6NnB4IDhweDt0ZXh0LWFsaWduOmNlbnRlcjtmb250LXNpemU6MTAuNXB4fQogIHRoLmxlZnR7dGV4dC1hbGlnbjpsZWZ0fQogIHRke3BhZGRpbmc6NXB4IDhweDtib3JkZXItYm90dG9tOjFweCBzb2xpZCB2YXIoLS1saW5lKTt0ZXh0LWFsaWduOmNlbnRlcn0KICB0ZC5sZWZ0e3RleHQtYWxpZ246bGVmdH0KICB0cjpudGgtY2hpbGQoZXZlbikgdGR7YmFja2dyb3VuZDojZmJmYWY3fQogIC5vcHQtcm93e2Rpc3BsYXk6ZmxleDthbGlnbi1pdGVtczpjZW50ZXI7Z2FwOjhweDtwYWRkaW5nOjNweCAwO2ZvbnQtc2l6ZToxMi41cHh9CiAgLm9wdC1yb3cgaW5wdXR7YWNjZW50LWNvbG9yOnZhcigtLWdvbGQyKX0KICAuaW5saW5lLXlue2Rpc3BsYXk6ZmxleDtnYXA6MTZweDthbGlnbi1pdGVtczpjZW50ZXI7Zm9udC1zaXplOjEyLjVweDttYXJnaW46NXB4IDAgOXB4O2ZsZXgtd3JhcDp3cmFwfQogIC5yZXN1bHQtYm94e2JhY2tncm91bmQ6bGluZWFyLWdyYWRpZW50KDEzNWRlZyx2YXIoLS1uYXZ5KSx2YXIoLS1uYXZ5MikpO2NvbG9yOiNmZmY7Ym9yZGVyLXJhZGl1czo4cHg7cGFkZGluZzoxNnB4IDIwcHg7bWFyZ2luOjE0cHggMH0KICAucmVzdWx0LWJveCAubGFiZWx7Y29sb3I6I2I5YzJjZTtmb250LXNpemU6MTBweDt0ZXh0LXRyYW5zZm9ybTp1cHBlcmNhc2U7bGV0dGVyLXNwYWNpbmc6LjRweH0KICAucmVzdWx0LWJveCAudmFsdWV7Zm9udC1zaXplOjIycHg7Zm9udC13ZWlnaHQ6Ym9sZDtjb2xvcjp2YXIoLS1nb2xkKTttYXJnaW4tdG9wOjJweH0KICAucmVzdWx0LXJvd3tkaXNwbGF5OmZsZXg7Z2FwOjMycHg7ZmxleC13cmFwOndyYXB9CiAgLmJhcmVtZXtmb250LXNpemU6MTAuNXB4O2NvbG9yOiNiOWMyY2U7bWFyZ2luLXRvcDo5cHh9CiAgLm5vdGV7Zm9udC1zaXplOjEwcHg7Y29sb3I6dmFyKC0tbXV0ZWQpO2ZvbnQtc3R5bGU6aXRhbGljO21hcmdpbi10b3A6N3B4O2xpbmUtaGVpZ2h0OjEuNX0KICAuc2lnLWJveHtib3JkZXI6MXB4IHNvbGlkIHZhcigtLWxpbmUpO2JvcmRlci1yYWRpdXM6NnB4O2hlaWdodDo2NXB4O21hcmdpbi10b3A6NXB4O2JhY2tncm91bmQ6I2ZmZn0KICAudHdvLWNvbHtkaXNwbGF5OmdyaWQ7Z3JpZC10ZW1wbGF0ZS1jb2x1bW5zOjFmciAxZnI7Z2FwOjIycHh9CgogIC8qIOKUgOKUgCBCYXJyZSBkJ291dGlscyBldCBvbmdsZXRzIChtYXNxdcOpcyDDoCBsJ2ltcHJlc3Npb24pIOKUgOKUgCAqLwogIC50b29sYmFye3Bvc2l0aW9uOnN0aWNreTt0b3A6MDtiYWNrZ3JvdW5kOiNmZmY7Ym9yZGVyLWJvdHRvbToxcHggc29saWQgdmFyKC0tbGluZSk7cGFkZGluZzo5cHggNDBweDtkaXNwbGF5OmZsZXg7anVzdGlmeS1jb250ZW50OnNwYWNlLWJldHdlZW47YWxpZ24taXRlbXM6Y2VudGVyO3otaW5kZXg6MjA7ZmxleC13cmFwOndyYXA7Z2FwOjhweH0KICAuYnRue2JhY2tncm91bmQ6dmFyKC0tZ29sZCk7Y29sb3I6dmFyKC0tbmF2eSk7Ym9yZGVyOm5vbmU7cGFkZGluZzo4cHggMTZweDtib3JkZXItcmFkaXVzOjZweDtmb250LXdlaWdodDpib2xkO2ZvbnQtc2l6ZToxMi41cHg7Y3Vyc29yOnBvaW50ZXI7Zm9udC1mYW1pbHk6aW5oZXJpdH0KICAuYnRuOmhvdmVye2JhY2tncm91bmQ6dmFyKC0tZ29sZDIpfQogIC5idG4uZ2hvc3R7YmFja2dyb3VuZDojZmZmO2JvcmRlcjoxcHggc29saWQgdmFyKC0tbGluZSk7Y29sb3I6dmFyKC0tbXV0ZWQpfQogIC5idG4uc2VuZHtiYWNrZ3JvdW5kOnZhcigtLW5hdnkpO2NvbG9yOnZhcigtLWdvbGQpfQogIC50YWJiYXJ7ZGlzcGxheTpmbGV4O2dhcDowO2JhY2tncm91bmQ6dmFyKC0tbmF2eTIpO3Bvc2l0aW9uOnN0aWNreTt0b3A6NDVweDt6LWluZGV4OjE5fQogIC50YWJ7ZmxleDoxO3RleHQtYWxpZ246Y2VudGVyO3BhZGRpbmc6MTFweCA2cHg7Y29sb3I6I2I5YzJjZTtmb250LXNpemU6MTJweDtmb250LXdlaWdodDpib2xkO2N1cnNvcjpwb2ludGVyO2JvcmRlci1ib3R0b206M3B4IHNvbGlkIHRyYW5zcGFyZW50fQogIC50YWIuYWN0aXZle2NvbG9yOnZhcigtLWdvbGQpO2JvcmRlci1ib3R0b20tY29sb3I6dmFyKC0tZ29sZCk7YmFja2dyb3VuZDpyZ2JhKDI1NSwyNTUsMjU1LC4wMyl9CiAgLnRhYnBhZ2V7ZGlzcGxheTpub25lfQogIC50YWJwYWdlLmFjdGl2ZXtkaXNwbGF5OmJsb2NrfQogIC5mb290ZXItYmFye3BhZGRpbmc6MTRweCA0MHB4O2ZvbnQtc2l6ZToxMC41cHg7Y29sb3I6dmFyKC0tbXV0ZWQpO2JvcmRlci10b3A6MXB4IHNvbGlkIHZhcigtLWxpbmUpfQogIC5tc2d7Zm9udC1zaXplOjExLjVweDtjb2xvcjp2YXIoLS1tdXRlZCl9CgogIEBtZWRpYSBwcmludHsKICAgICp7LXdlYmtpdC1wcmludC1jb2xvci1hZGp1c3Q6ZXhhY3QgIWltcG9ydGFudDtwcmludC1jb2xvci1hZGp1c3Q6ZXhhY3QgIWltcG9ydGFudDtjb2xvci1hZGp1c3Q6ZXhhY3QgIWltcG9ydGFudH0KICAgIC50b29sYmFyLCAudGFiYmFye2Rpc3BsYXk6bm9uZSAhaW1wb3J0YW50fQogICAgYm9keXtiYWNrZ3JvdW5kOiNmZmZ9CiAgICAuc2hlZXR7Ym94LXNoYWRvdzpub25lO21heC13aWR0aDpub25lfQogICAgLnRhYnBhZ2V7ZGlzcGxheTpibG9jayAhaW1wb3J0YW50fQogICAgLnRhYnBhZ2UgKyAudGFicGFnZXtwYWdlLWJyZWFrLWJlZm9yZTphbHdheXN9CiAgICAuaGVybywgLnNlYy1iYXIsIC5yZXN1bHQtYm94e2JyZWFrLWluc2lkZTphdm9pZH0KICAgIHRhYmxle2JyZWFrLWluc2lkZTphdXRvfQogICAgdHJ7YnJlYWstaW5zaWRlOmF2b2lkfQogICAgLmNhcmQsIC5yZXN1bHQtYm94e2JyZWFrLWluc2lkZTphdm9pZH0KICB9Cjwvc3R5bGU+CjwvaGVhZD4KPGJvZHk+Cgo8ZGl2IGNsYXNzPSJ0b29sYmFyIG5vLXByaW50Ij4KICA8ZGl2PjxiPlBhcmNvdXJzIENsaWVudCBDb21wbGV0PC9iPiDigJQgPHNwYW4gaWQ9ImNsaWVudC1uYW1lLWRpc3BsYXkiPm5vdXZlYXUgY2xpZW50PC9zcGFuPjwvZGl2PgogIDxkaXYgc3R5bGU9ImRpc3BsYXk6ZmxleDtnYXA6MTBweDthbGlnbi1pdGVtczpjZW50ZXI7ZmxleC13cmFwOndyYXAiPgogICAgPHNwYW4gY2xhc3M9Im1zZyIgaWQ9ImF1dG9zYXZlLW1zZyI+PC9zcGFuPgogICAgPGJ1dHRvbiBjbGFzcz0iYnRuIGdob3N0IiBvbmNsaWNrPSJyZXNldEZvcm0oKSI+UsOpaW5pdGlhbGlzZXI8L2J1dHRvbj4KICAgIDxidXR0b24gY2xhc3M9ImJ0biBnaG9zdCIgb25jbGljaz0iZXhwb3J0RGF0YUpTT04oKSI+4qyH77iPIEV4cG9ydGVyIGxlcyBkb25uw6llczwvYnV0dG9uPgogICAgPGJ1dHRvbiBjbGFzcz0iYnRuIiBvbmNsaWNrPSJkb3dubG9hZFBERigpIj7wn5K+IFTDqWzDqWNoYXJnZXIgbGUgUERGPC9idXR0b24+CiAgICA8YnV0dG9uIGNsYXNzPSJidG4gc2VuZCIgb25jbGljaz0iZW52b3llclBhckVtYWlsKCkiPvCfk6cgRW52b3llciBwYXIgZW1haWw8L2J1dHRvbj4KICA8L2Rpdj4KPC9kaXY+CjxkaXYgY2xhc3M9Im5vLXByaW50IiBzdHlsZT0iYmFja2dyb3VuZDojZmZmOGU2O2JvcmRlci1ib3R0b206MXB4IHNvbGlkICNlOGQ5YTg7cGFkZGluZzo2cHggNDBweDtmb250LXNpemU6MTFweDtjb2xvcjojN2E2NDIwIj7ihLnvuI8gIkVudm95ZXIgcGFyIGVtYWlsIiB0w6lsw6ljaGFyZ2UgbGUgUERGIHB1aXMgb3V2cmUgdm90cmUgbWVzc2FnZXJpZSBwcsOpLXJlbXBsaWUg4oCUIGlsIHZvdXMgc3VmZml0IGRlIGpvaW5kcmUgbGUgZmljaGllciB0w6lsw6ljaGFyZ8OpIChhdWN1biBvdXRpbCB3ZWIgbmUgcGV1dCBqb2luZHJlIHVuIGZpY2hpZXIgYXV0b21hdGlxdWVtZW50IMOgIHVuIGVtYWlsKS48L2Rpdj4KCjxkaXYgY2xhc3M9InRhYmJhciBuby1wcmludCI+CiAgPGRpdiBjbGFzcz0idGFiIGFjdGl2ZSIgZGF0YS10YWI9ImVudHJlZSIgb25jbGljaz0ic2hvd1RhYignZW50cmVlJykiPjEgwrcgRW50csOpZSBlbiByZWxhdGlvbjwvZGl2PgogIDxkaXYgY2xhc3M9InRhYiIgZGF0YS10YWI9Im9iamVjdGlmcyIgb25jbGljaz0ic2hvd1RhYignb2JqZWN0aWZzJykiPjIgwrcgT2JqZWN0aWZzPC9kaXY+CiAgPGRpdiBjbGFzcz0idGFiIiBkYXRhLXRhYj0iY29ubmFpc3NhbmNlIiBvbmNsaWNrPSJzaG93VGFiKCdjb25uYWlzc2FuY2UnKSI+MyDCtyBDb25uYWlzc2FuY2UgJiByaXNxdWU8L2Rpdj4KICA8ZGl2IGNsYXNzPSJ0YWIiIGRhdGEtdGFiPSJhZGVxdWF0aW9uIiBvbmNsaWNrPSJzaG93VGFiKCdhZGVxdWF0aW9uJykiPjQgwrcgQWTDqXF1YXRpb248L2Rpdj4KPC9kaXY+Cgo8ZGl2IGNsYXNzPSJzaGVldCI+CiAgPGRpdiBjbGFzcz0iaGVybyI+CiAgICA8ZGl2IGNsYXNzPSJicmFuZCI+Q0FSRU1NQSBGSU5BTkNFPC9kaXY+CiAgICA8ZGl2IGNsYXNzPSJzdWIiPkNvbnNlaWwgZW4gSW52ZXN0aXNzZW1lbnRzIEZpbmFuY2llcnMgwrcgQ291cnRpZXIgZW4gYXNzdXJhbmNlIMK3IE9SSUFTIG7CsDI0MDA3NzY3PC9kaXY+CiAgICA8aDE+UGFyY291cnMgQ2xpZW50IENvbXBsZXQ8L2gxPgogICAgPGRpdiBjbGFzcz0idGFnbGluZSI+RW50csOpZSBlbiByZWxhdGlvbiDCtyBPYmplY3RpZnMgwrcgQ29ubmFpc3NhbmNlICYgY29tcMOpdGVuY2Ugwrcgw4l2YWx1YXRpb24gZHUgcmlzcXVlIMK3IEFkw6lxdWF0aW9uPC9kaXY+CiAgPC9kaXY+CiAgPGRpdiBjbGFzcz0iZ29sZGJhciI+PC9kaXY+CgogIDxkaXYgY2xhc3M9ImNvbnRlbnQiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9ImdyaWQyIj4KICAgICAgICA8ZGl2PjxsYWJlbCBjbGFzcz0iZmllbGQiPlByw6lub20gZHUgY2xpZW50PC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImNsaWVudF9wcmVub20iIG9uaW5wdXQ9InVwZGF0ZUNsaWVudE5hbWUoKSI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Ob20gZHUgY2xpZW50PC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImNsaWVudF9ub20iIG9uaW5wdXQ9InVwZGF0ZUNsaWVudE5hbWUoKSI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5FbWFpbCBkdSBjbGllbnQgKHBvdXIgbCdlbnZvaSBlbiBzaWduYXR1cmUpPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImNsaWVudF9lbWFpbCI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5EYXRlPC9sYWJlbD48aW5wdXQgdHlwZT0iZGF0ZSIgaWQ9ImRvY19kYXRlIj48L2Rpdj4KICAgICAgPC9kaXY+CiAgICA8L2Rpdj4KCiAgICA8IS0tIOKVkOKVkOKVkOKVkOKVkOKVkOKVkOKVkOKVkOKVkOKVkCBUQUIgMSA6IEVOVFJFRSBFTiBSRUxBVElPTiDilZDilZDilZDilZDilZDilZDilZDilZDilZDilZDilZAgLS0+CiAgICA8ZGl2IGNsYXNzPSJ0YWJwYWdlIGFjdGl2ZSIgaWQ9InRhYnBhZ2UtZW50cmVlIj4KICAgICAgPGRpdiBjbGFzcz0ic2VjLWJhciI+RG9jdW1lbnQgZCdlbnRyw6llIGVuIHJlbGF0aW9uPC9kaXY+CiAgICAgIDxoMyBjbGFzcz0ic3ViIj5BLiBJbmZvcm1hdGlvbnMgcHLDqWFsYWJsZXMgc3VyIGwnaW50ZXJtw6lkaWFpcmU8L2gzPgogICAgICA8cCBjbGFzcz0iaW50cm8iPkNBUkVNTUEgRklOQU5DRSBlc3QgaW1tYXRyaWN1bMOpZSBhdSByZWdpc3RyZSB1bmlxdWUgZGVzIGludGVybcOpZGlhaXJlcyBlbiBhc3N1cmFuY2UsIGJhbnF1ZSBldCBmaW5hbmNlIChPUklBUyBuwrAyNDAwNzc2Nywgd3d3Lm9yaWFzLmZyKSBlbiBxdWFsaXTDqSBkZSBjb3VydGllciBkJ2Fzc3VyYW5jZS4gU0FTIGF1IGNhcGl0YWwgZGUgNTAwIOKCrCwgUkNTIGRlIFBvbnRvaXNlIG7CsDkzMyA1MzcgNDMzLCBzacOoZ2Ugc29jaWFsIDExMiBSdWUgUm91Z2V0IGRlIExpc2xlLCA5NTg3MCBCZXpvbnMuIEFzc3Vyw6llIGVuIHJlc3BvbnNhYmlsaXTDqSBjaXZpbGUgcHJvZmVzc2lvbm5lbGxlIGV0IGdhcmFudGllIGZpbmFuY2nDqHJlIGF1cHLDqHMgZCdBSUcgKGNvbnRyYXQgbsKwUkQwMTk4MTA5MVMpLiBDb250csO0bMOpZSBwYXIgbCdBQ1BSLiBBZGjDqXJlbnRlIMOgIGxhIENOQ0VGIEFzc3VyYW5jZS48L3A+CiAgICAgIDxkaXYgY2xhc3M9Im9wdC1yb3ciPjxsYWJlbD48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJlcl9wYXNfcmVsYXRpb25fY2FwaXRhbGlzdGlxdWUiPiBDQVJFTU1BIEZJTkFOQ0UgbidlbnRyZXRpZW50IHBhcyBkZSByZWxhdGlvbiBzaWduaWZpY2F0aXZlIGRlIG5hdHVyZSBjYXBpdGFsaXN0aXF1ZSBvdSBjb21tZXJjaWFsZSBhdmVjIHVuZSBlbnRyZXByaXNlIGQnYXNzdXJhbmNlIChwYXJ0aWNpcGF0aW9uICZndDsgMTAgJSBkZXMgZHJvaXRzIGRlIHZvdGUgb3UgZHUgY2FwaXRhbCk8L2xhYmVsPjwvZGl2PgoKICAgICAgPGgzIGNsYXNzPSJzdWIiPkIuIEluZm9ybWF0aW9ucyBwcsOpYWxhYmxlcyByZWxhdGl2ZXMgw6AgbGEgZm91cm5pdHVyZSBkdSBjb250cmF0PC9oMz4KICAgICAgPHAgY2xhc3M9ImludHJvIj5DQVJFTU1BIEZJTkFOQ0Ugbidlc3QgcGFzIHNvdW1pc2Ugw6AgdW5lIG9ibGlnYXRpb24gZCdleGNsdXNpdml0w6kgZXQgZm9uZGUgc29uIGFuYWx5c2Ugc3VyIHVuIG5vbWJyZSByZXN0cmVpbnQgZGUgY29udHJhdHMuIEFzc3VyZXVycyBwYXJ0ZW5haXJlcyA6PC9wPgogICAgICA8ZGl2IGNsYXNzPSJncmlkMiI+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Bc3N1cmV1ciAxPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImVyX2Fzc3VyZXVyMSI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Bc3N1cmV1ciAyPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImVyX2Fzc3VyZXVyMiI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Bc3N1cmV1ciAzPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImVyX2Fzc3VyZXVyMyI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Bc3N1cmV1ciA0PC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImVyX2Fzc3VyZXVyNCI+PC9kaXY+CiAgICAgIDwvZGl2PgogICAgICA8cCBjbGFzcz0ibm90ZSI+U2VydmljZSBkZSByZWNvbW1hbmRhdGlvbiBwZXJzb25uYWxpc8OpZSBldCBzZXJ2aWNlIGQnw6l2YWx1YXRpb24gcMOpcmlvZGlxdWUgOiBvcHRpb25uZWxzLCBzdXNjZXB0aWJsZXMgZCfDqnRyZSBwYXlhbnRzLjwvcD4KCiAgICAgIDxoMyBjbGFzcz0ic3ViIj5Sw6ltdW7DqXJhdGlvbjwvaDM+CiAgICAgIDxwIGNsYXNzPSJpbnRybyI+UG91ciBjZSBjb250cmF0LCBDQVJFTU1BIEZJTkFOQ0Ugc2VyYSByw6ltdW7DqXLDqWUgc3VyIGxhIGJhc2UgOjwvcD4KICAgICAgPGRpdiBjbGFzcz0ib3B0LXJvdyI+PGxhYmVsPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImVyX3JlbV9ob25vcmFpcmUiPiBEJ3VuIGhvbm9yYWlyZSBkZSBjb25zZWlsPC9sYWJlbD4gPGlucHV0IHR5cGU9InRleHQiIHBsYWNlaG9sZGVyPSJtb250YW50IC8gbW9kZSBkZSBjYWxjdWwiIGlkPSJlcl9yZW1faG9ub3JhaXJlX2RldGFpbCIgc3R5bGU9IndpZHRoOjIyMHB4Ij48L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0ib3B0LXJvdyI+PGxhYmVsPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImVyX3JlbV9jb21taXNzaW9uIj4gRCd1bmUgY29tbWlzc2lvbiBpbmNsdXNlIGRhbnMgbGEgcHJpbWU8L2xhYmVsPiA8aW5wdXQgdHlwZT0idGV4dCIgcGxhY2Vob2xkZXI9IiUiIGlkPSJlcl9yZW1fY29tbWlzc2lvbl9kZXRhaWwiIHN0eWxlPSJ3aWR0aDo4MHB4Ij48L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0ib3B0LXJvdyI+PGxhYmVsPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImVyX3JlbV9mcmFpc19nZXN0aW9uIj4gRCd1biAlIGRlcyBmcmFpcyBkZSBnZXN0aW9uIHJldmVyc8OpczwvbGFiZWw+IDxpbnB1dCB0eXBlPSJ0ZXh0IiBwbGFjZWhvbGRlcj0iJSIgaWQ9ImVyX3JlbV9mcmFpc19nZXN0aW9uX2RldGFpbCIgc3R5bGU9IndpZHRoOjgwcHgiPjwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJvcHQtcm93Ij48bGFiZWw+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0iZXJfcmVtX2NvbWJpbmFpc29uIj4gRCd1bmUgY29tYmluYWlzb24gZGVzIHR5cGVzIGNpLWRlc3N1czwvbGFiZWw+PC9kaXY+CgogICAgICA8aDMgY2xhc3M9InN1YiI+UsOpY2xhbWF0aW9uICYgbcOpZGlhdGlvbjwvaDM+CiAgICAgIDxwIGNsYXNzPSJpbnRybyI+U2VydmljZSBpbnRlcm5lIDogbWFyYy5yZXZlcnNlYXVAY2FyZW1tYWZpbmFuY2UuY29tIOKAlCAxMTIgUnVlIFJvdWdldCBkZSBMaXNsZSwgOTU4NzAgQmV6b25zLiBNw6lkaWF0ZXVyIGRlIGxhIGNvbnNvbW1hdGlvbiA6IENOUCBNw6lkaWF0aW9uLUNvbnNvbW1hdGlvbiwgMjcgQXZlbnVlIGRlIGxhIExpYsOpcmF0aW9uLCA0MjQwMCBTYWludC1DaGFtb25kLjwvcD4KCiAgICAgIDxkaXYgY2xhc3M9InR3by1jb2wiIHN0eWxlPSJtYXJnaW4tdG9wOjIwcHgiPgogICAgICAgIDxkaXY+PGgzIGNsYXNzPSJzdWIiPkZhaXQgw6A8L2gzPjxpbnB1dCB0eXBlPSJ0ZXh0IiBpZD0iZXJfbGlldSI+PC9kaXY+CiAgICAgICAgPGRpdj48aDMgY2xhc3M9InN1YiI+U2lnbmF0dXJlIGNsaWVudDwvaDM+PGRpdiBjbGFzcz0ic2lnLWJveCI+PC9kaXY+PC9kaXY+CiAgICAgIDwvZGl2PgogICAgPC9kaXY+CgogICAgPCEtLSDilZDilZDilZDilZDilZDilZDilZDilZDilZDilZDilZAgVEFCIDIgOiBPQkpFQ1RJRlMg4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQIC0tPgogICAgPGRpdiBjbGFzcz0idGFicGFnZSIgaWQ9InRhYnBhZ2Utb2JqZWN0aWZzIj4KICAgICAgPGRpdiBjbGFzcz0ic2VjLWJhciI+U2l0dWF0aW9uIGZpbmFuY2nDqHJlIGR1IHNvdXNjcmlwdGV1cjwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJncmlkMiI+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Ob20gZGUgbmFpc3NhbmNlPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9InFvX25vbV9uYWlzcyI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Ob20gZCd1c2FnZTwvbGFiZWw+PGlucHV0IHR5cGU9InRleHQiIGlkPSJxb19ub21fdXNhZ2UiPjwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+UHLDqW5vbShzKTwvbGFiZWw+PGlucHV0IHR5cGU9InRleHQiIGlkPSJxb19wcmVub20iPjwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+RGF0ZSBkZSBuYWlzc2FuY2U8L2xhYmVsPjxpbnB1dCB0eXBlPSJkYXRlIiBpZD0icW9fZGRuIj48L2Rpdj4KICAgICAgICA8ZGl2PjxsYWJlbCBjbGFzcz0iZmllbGQiPk5hdGlvbmFsaXTDqTwvbGFiZWw+PGlucHV0IHR5cGU9InRleHQiIGlkPSJxb19uYXRpb25hbGl0ZSIgdmFsdWU9IkZyYW7Dp2Fpc2UiPjwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+QWRyZXNzZSBwb3N0YWxlPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9InFvX2FkcmVzc2UiPjwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+VMOpbMOpcGhvbmU8L2xhYmVsPjxpbnB1dCB0eXBlPSJ0ZXh0IiBpZD0icW9fdGVsIj48L2Rpdj4KICAgICAgICA8ZGl2PjxsYWJlbCBjbGFzcz0iZmllbGQiPkFkcmVzc2UgZmlzY2FsZSAoc2kgZGlmZsOpcmVudGUgLyBGQVRDQSk8L2xhYmVsPjxpbnB1dCB0eXBlPSJ0ZXh0IiBpZD0icW9fYWRyZXNzZV9maXNjYWxlIj48L2Rpdj4KICAgICAgPC9kaXY+CgogICAgICA8aDMgY2xhc3M9InN1YiI+U3RhdHV0IGZhbWlsaWFsIGV0IHByb2Zlc3Npb25uZWw8L2gzPgogICAgICA8ZGl2IGNsYXNzPSJvcHQtcm93Ij4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxb19zaXR1YXRpb25fZmFtaWxsZSIgdmFsdWU9IkNlbGliYXRhaXJlIj4gQ8OpbGliYXRhaXJlPC9sYWJlbD4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxb19zaXR1YXRpb25fZmFtaWxsZSIgdmFsdWU9Ik1hcmllIj4gTWFyacOpKGUpPC9sYWJlbD4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxb19zaXR1YXRpb25fZmFtaWxsZSIgdmFsdWU9IlBhY3NlIj4gUGFjc8OpKGUpPC9sYWJlbD4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxb19zaXR1YXRpb25fZmFtaWxsZSIgdmFsdWU9IkRpdm9yY2UiPiBEaXZvcmPDqShlKTwvbGFiZWw+CiAgICAgICAgPGxhYmVsPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW9fc2l0dWF0aW9uX2ZhbWlsbGUiIHZhbHVlPSJWZXVmIj4gVmV1Zih2ZSk8L2xhYmVsPgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZ3JpZDIiPgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+UHJvZmVzc2lvbiAob3UgZGVybmnDqHJlIHByb2Zlc3Npb24pPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9InFvX3Byb2Zlc3Npb24iPjwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+QW5uw6llIHByw6l2aXNpb25uZWxsZSBkZSBkw6lwYXJ0IMOgIGxhIHJldHJhaXRlPC9sYWJlbD48aW5wdXQgdHlwZT0ibnVtYmVyIiBpZD0icW9fcmV0cmFpdGUiPjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iaW5saW5lLXluIj48c3Bhbj5QZXJzb25uZSBQb2xpdGlxdWVtZW50IEV4cG9zw6llIChQUEUpID88L3NwYW4+CiAgICAgICAgPGxhYmVsPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW9fcHBlIiB2YWx1ZT0ib3VpIj4gT3VpPC9sYWJlbD4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxb19wcGUiIHZhbHVlPSJub24iPiBOb248L2xhYmVsPgogICAgICA8L2Rpdj4KCiAgICAgIDxoMyBjbGFzcz0ic3ViIj5SZXZlbnVzIGV0IGNoYXJnZXM8L2gzPgogICAgICA8ZGl2IGNsYXNzPSJncmlkMiI+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5SZXZlbnVzIGFubnVlbHMgZHUgY2xpZW50ICjigqwpPC9sYWJlbD48aW5wdXQgdHlwZT0ibnVtYmVyIiBpZD0icW9fcmV2X2NsaWVudCI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5SZXZlbnVzIGFubnVlbHMgZHUgY29uam9pbnQgKOKCrCk8L2xhYmVsPjxpbnB1dCB0eXBlPSJudW1iZXIiIGlkPSJxb19yZXZfY29uam9pbnQiPjwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+Q2hhcmdlcyBhbm51ZWxsZXMgZHUgZm95ZXIgKOKCrCk8L2xhYmVsPjxpbnB1dCB0eXBlPSJudW1iZXIiIGlkPSJxb19jaGFyZ2VzIj48L2Rpdj4KICAgICAgICA8ZGl2PjxsYWJlbCBjbGFzcz0iZmllbGQiPkNhcGFjaXTDqSBkJ8OpcGFyZ25lIGFubnVlbGxlICjigqwpPC9sYWJlbD48aW5wdXQgdHlwZT0ibnVtYmVyIiBpZD0icW9fZXBhcmduZSI+PC9kaXY+CiAgICAgIDwvZGl2PgoKICAgICAgPGgzIGNsYXNzPSJzdWIiPkNvbXBvc2l0aW9uIGR1IHBhdHJpbW9pbmU8L2gzPgogICAgICA8ZGl2IGNsYXNzPSJncmlkMiI+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5QYXJ0IHPDqWN1cml0YWlyZSBkdSBwYXRyaW1vaW5lPC9sYWJlbD4KICAgICAgICAgIDxzZWxlY3QgaWQ9InFvX3BhcnRfc2VjdSI+PG9wdGlvbj4mZ3Q7IDYwJTwvb3B0aW9uPjxvcHRpb24+MzAtNjAlPC9vcHRpb24+PG9wdGlvbj4mbHQ7IDMwJTwvb3B0aW9uPjwvc2VsZWN0PgogICAgICAgIDwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+UGFydCBkZSBjZSBwcm9qZXQgZGFucyBsZSBwYXRyaW1vaW5lPC9sYWJlbD4KICAgICAgICAgIDxzZWxlY3QgaWQ9InFvX3BhcnRfcHJvamV0Ij48b3B0aW9uPiZsdDsgMjAlPC9vcHRpb24+PG9wdGlvbj4yMC01MCU8L29wdGlvbj48b3B0aW9uPiZndDsgNTAlPC9vcHRpb24+PC9zZWxlY3Q+CiAgICAgICAgPC9kaXY+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJpbmxpbmUteW4iPjxzcGFuPlByb3ByacOpdGFpcmUgZCd1biBiaWVuIGltbW9iaWxpZXIgPzwvc3Bhbj4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxb19wcm9wcmlvIiB2YWx1ZT0ib3VpIj4gT3VpPC9sYWJlbD4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxb19wcm9wcmlvIiB2YWx1ZT0ibm9uIj4gTm9uPC9sYWJlbD4KICAgICAgPC9kaXY+CgogICAgICA8aDMgY2xhc3M9InN1YiI+T2JqZWN0aWZzIGRlIHNvdXNjcmlwdGlvbjwvaDM+CiAgICAgIDxkaXYgaWQ9InFvLW9iamVjdGlmcy1saXN0Ij48L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZ3JpZDIiIHN0eWxlPSJtYXJnaW4tdG9wOjEwcHgiPgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+SG9yaXpvbiBkZSBwbGFjZW1lbnQ8L2xhYmVsPgogICAgICAgICAgPHNlbGVjdCBpZD0icW9faG9yaXpvbiI+PG9wdGlvbj5Nb2lucyBkZSAzIGFuczwvb3B0aW9uPjxvcHRpb24+MyDDoCA1IGFuczwvb3B0aW9uPjxvcHRpb24+NSDDoCA4IGFuczwvb3B0aW9uPjxvcHRpb24gc2VsZWN0ZWQ+UGx1cyBkZSA4IGFuczwvb3B0aW9uPjwvc2VsZWN0PgogICAgICAgIDwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+TW9udGFudCDDoCBwbGFjZXIgKOKCrCk8L2xhYmVsPjxpbnB1dCB0eXBlPSJudW1iZXIiIGlkPSJxb19tb250YW50Ij48L2Rpdj4KICAgICAgPC9kaXY+CgogICAgICA8aDMgY2xhc3M9InN1YiI+UHLDqWbDqXJlbmNlcyBlbiBtYXRpw6hyZSBkZSBkdXJhYmlsaXTDqSAoRVNHKTwvaDM+CiAgICAgIDxkaXYgY2xhc3M9Im9wdC1yb3ciPjxsYWJlbD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvX2VzZyIgdmFsdWU9Im91aV90b3V0X2FfZmFpdCI+IFNlbnNpYmxlIGF1eCBjcml0w6hyZXMgRVNHLCB0b3V0IMOgIGZhaXQ8L2xhYmVsPjwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJvcHQtcm93Ij48bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxb19lc2ciIHZhbHVlPSJwYXNfcHJpb3JpdGUiPiBTZW5zaWJsZSwgbWFpcyBjZSBuJ2VzdCBwYXMgZW5jb3JlIG1hIHByaW9yaXTDqTwvbGFiZWw+PC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9Im9wdC1yb3ciPjxsYWJlbD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvX2VzZyIgdmFsdWU9Im5vbiI+IE5vbiwgcGFzIGR1IHRvdXQ8L2xhYmVsPjwvZGl2PgogICAgPC9kaXY+CgogICAgPCEtLSDilZDilZDilZDilZDilZDilZDilZDilZDilZDilZDilZAgVEFCIDMgOiBDT05OQUlTU0FOQ0UgJiBSSVNRVUUg4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQIC0tPgogICAgPGRpdiBjbGFzcz0idGFicGFnZSIgaWQ9InRhYnBhZ2UtY29ubmFpc3NhbmNlIj4KICAgICAgPGRpdiBjbGFzcz0ic2VjLWJhciI+Ri4gQ29ubmFpc3NhbmNlICYgY29tcMOpdGVuY2U8L2Rpdj4KICAgICAgPHAgY2xhc3M9ImludHJvIj5Ew6l0ZXJtaW5lIGxhIGNhdMOpZ29yaXNhdGlvbiBkdSBjbGllbnQgOiBJbnZlc3Rpc3NldXIgZGUgQmFzZSAvIEF2ZXJ0aSAvIEF2YW5jw6kuIExlIHNjb3JlIHNlIGNhbGN1bGUgYXV0b21hdGlxdWVtZW50LjwvcD4KICAgICAgPHRhYmxlIGlkPSJwcm9kdWl0cy10YWJsZSI+PHRyPjx0aCBjbGFzcz0ibGVmdCI+UHJvZHVpdDwvdGg+PHRoPkTDqWrDoCBpbnZlc3RpPC90aD48dGg+UGFzIGR1IHRvdXQ8L3RoPjx0aD5VbiBwZXU8L3RoPjx0aD5CaWVuPC90aD48L3RyPjwvdGFibGU+CgogICAgICA8aDMgY2xhc3M9InN1YiI+Rm9ybWF0aW9uIGV0IGV4cMOpcmllbmNlIHByb2Zlc3Npb25uZWxsZTwvaDM+CiAgICAgIDxkaXYgY2xhc3M9ImlubGluZS15biI+PHNwYW4+Rm9ybWF0aW9uIG91IGRpcGzDtG1lIGVuIGZpbmFuY2UgPzwvc3Bhbj4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJmb3JtYXRpb25fZmluIiB2YWx1ZT0iNSI+IE91aTwvbGFiZWw+CiAgICAgICAgPGxhYmVsPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iZm9ybWF0aW9uX2ZpbiIgdmFsdWU9IjAiPiBOb248L2xhYmVsPgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iaW5saW5lLXluIj48c3Bhbj5Qcm9mZXNzaW9uIGRhbnMgbGUgc2VjdGV1ciBmaW5hbmNpZXIgPzwvc3Bhbj4KICAgICAgICA8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJleHBfcHJvX2ZpbiIgdmFsdWU9IjUiPiBPdWk8L2xhYmVsPgogICAgICAgIDxsYWJlbD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImV4cF9wcm9fZmluIiB2YWx1ZT0iMCI+IE5vbjwvbGFiZWw+CiAgICAgIDwvZGl2PgogICAgICA8aDMgY2xhc3M9InN1YiI+RGVwdWlzIGNvbWJpZW4gZGUgdGVtcHMgaW52ZXN0aXNzZXotdm91cyA/PC9oMz4KICAgICAgPGRpdiBpZD0iYW5jaWVubmV0ZS1vcHRzIj48L2Rpdj4KCiAgICAgIDxoMyBjbGFzcz0ic3ViIj5EYW5zIGxlIHBhc3PDqSwgbGEgZ2VzdGlvbiBkZSBtZXMgYXZvaXJz4oCmPC9oMz4KICAgICAgPGRpdiBjbGFzcz0ib3B0LXJvdyI+PGxhYmVsPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iZ2VzdGlvbl9wYXNzZSIgdmFsdWU9IjUiPiBBIMOpdMOpIGTDqWzDqWd1w6llIMOgIHVuIGdlc3Rpb25uYWlyZTwvbGFiZWw+PC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9Im9wdC1yb3ciPjxsYWJlbD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9Imdlc3Rpb25fcGFzc2UiIHZhbHVlPSIyMCI+IEEgw6l0w6kgZ8OpcsOpZSBwYXIgbW9pLW3Dqm1lIHNhbnMgY29uc2VpbGxlcjwvbGFiZWw+PC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9Im9wdC1yb3ciPjxsYWJlbD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9Imdlc3Rpb25fcGFzc2UiIHZhbHVlPSIxMCI+IEEgw6l0w6kgZ8OpcsOpZSBwYXIgbW9pLW3Dqm1lIGF2ZWMgY29uc2VpbGxlcjwvbGFiZWw+PC9kaXY+CgogICAgICA8aDMgY2xhc3M9InN1YiI+RnLDqXF1ZW5jZSBldCB2b2x1bWUgZGUgdm9zIG9ww6lyYXRpb25zPC9oMz4KICAgICAgPGRpdiBjbGFzcz0iZ3JpZDIiPgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+Tm9tYnJlIGRlIHRyYW5zYWN0aW9ucyAoMTIgbW9pcyk8L2xhYmVsPjxkaXYgaWQ9ImZyZXEtb3B0cyI+PC9kaXY+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Nb250YW50IG1veWVuIHBhciBvcMOpcmF0aW9uPC9sYWJlbD48ZGl2IGlkPSJtb250YW50LW9wdHMiPjwvZGl2PjwvZGl2PgogICAgICA8L2Rpdj4KCiAgICAgIDxoMyBjbGFzcz0ic3ViIj5Wb3RyZSBpbmZvcm1hdGlvbuKApjwvaDM+CiAgICAgIDx0YWJsZSBpZD0iaW5mby10YWJsZSI+PHRyPjx0aCBjbGFzcz0ibGVmdCI+SmUgbSdpbmZvcm1l4oCmPC90aD48dGg+T3VpPC90aD48dGg+VW4gcGV1IG1vaW5zIHNvdXZlbnQ8L3RoPjx0aD5KYW1haXM8L3RoPjwvdHI+PC90YWJsZT4KCiAgICAgIDxoMyBjbGFzcz0ic3ViIj5RdWVscXVlcyBhZmZpcm1hdGlvbnPigKYgKFZyYWkgPSAxIHB0IC8gRmF1eCA9IDAgcHQpPC9oMz4KICAgICAgPHRhYmxlIGlkPSJhZmYtdGFibGUiPjx0cj48dGggY2xhc3M9ImxlZnQiPkFmZmlybWF0aW9uPC90aD48dGg+VnJhaTwvdGg+PHRoPkZhdXg8L3RoPjwvdHI+PC90YWJsZT4KCiAgICAgIDxkaXYgY2xhc3M9InJlc3VsdC1ib3giPgogICAgICAgIDxkaXYgY2xhc3M9InJlc3VsdC1yb3ciPgogICAgICAgICAgPGRpdj48ZGl2IGNsYXNzPSJsYWJlbCI+U2NvcmUgY29ubmFpc3NhbmNlPC9kaXY+PGRpdiBjbGFzcz0idmFsdWUiIGlkPSJzY29yZS1jb25uYWlzc2FuY2UiPjAgLyAyMTg8L2Rpdj48L2Rpdj4KICAgICAgICAgIDxkaXY+PGRpdiBjbGFzcz0ibGFiZWwiPkNhdMOpZ29yaWU8L2Rpdj48ZGl2IGNsYXNzPSJ2YWx1ZSIgaWQ9ImNhdGVnb3JpZS1jb25uYWlzc2FuY2UiPuKAlDwvZGl2PjwvZGl2PgogICAgICAgIDwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImJhcmVtZSI+QmFyw6htZSA6IDgxLTEyNSA9IEJhc2UgJm5ic3A7wrcmbmJzcDsgMTI2LTE3MSA9IEF2ZXJ0aSAmbmJzcDvCtyZuYnNwOyAxNzItMjE4ID0gQXZhbmPDqTwvZGl2PgogICAgICA8L2Rpdj4KCiAgICAgIDxkaXYgY2xhc3M9InNlYy1iYXIiPkcuIMOJdmFsdWF0aW9uIGR1IHJpc3F1ZTwvZGl2PgogICAgICA8ZGl2IGlkPSJyaXNrLXF1ZXN0aW9ucyI+PC9kaXY+CiAgICAgIDxoMyBjbGFzcz0ic3ViIj5SaXNxdWUgc3VyIGxlIHBhdHJpbW9pbmUgZGFucyBzYSBnbG9iYWxpdMOpPC9oMz4KICAgICAgPGRpdiBjbGFzcz0ib3B0LXJvdyI+PGxhYmVsPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlza19wcm9maWxfZ2xvYmFsIiB2YWx1ZT0ic2VjdXJpdGUiPiBTw6ljdXJpdMOpIDogdm9sYXRpbGl0w6kgdHLDqHMgZmFpYmxlPC9sYWJlbD48L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0ib3B0LXJvdyI+PGxhYmVsPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlza19wcm9maWxfZ2xvYmFsIiB2YWx1ZT0icHJ1ZGVudCI+IFBydWRlbnQgOiB2b2xhdGlsaXTDqSBmYWlibGU8L2xhYmVsPjwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJvcHQtcm93Ij48bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNrX3Byb2ZpbF9nbG9iYWwiIHZhbHVlPSJlcXVpbGlicmUiPiDDiXF1aWxpYnLDqSA6IHZvbGF0aWxpdMOpIG1veWVubmU8L2xhYmVsPjwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJvcHQtcm93Ij48bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNrX3Byb2ZpbF9nbG9iYWwiIHZhbHVlPSJkeW5hbWlxdWUiPiBEeW5hbWlxdWUgOiBmb3J0ZSB2b2xhdGlsaXTDqTwvbGFiZWw+PC9kaXY+CgogICAgICA8ZGl2IGNsYXNzPSJyZXN1bHQtYm94Ij4KICAgICAgICA8ZGl2IGNsYXNzPSJyZXN1bHQtcm93Ij4KICAgICAgICAgIDxkaXY+PGRpdiBjbGFzcz0ibGFiZWwiPlNjb3JlIHJpc3F1ZTwvZGl2PjxkaXYgY2xhc3M9InZhbHVlIiBpZD0ic2NvcmUtcmlzcXVlIj4wIC8gMTE1PC9kaXY+PC9kaXY+CiAgICAgICAgICA8ZGl2PjxkaXYgY2xhc3M9ImxhYmVsIj5Qcm9maWwgY2FsY3Vsw6k8L2Rpdj48ZGl2IGNsYXNzPSJ2YWx1ZSIgaWQ9InByb2ZpbC1yaXNxdWUiPuKAlDwvZGl2PjwvZGl2PgogICAgICAgICAgPGRpdj48ZGl2IGNsYXNzPSJsYWJlbCI+UHJvZmlsIHPDqWxlY3Rpb25uw6k8L2Rpdj48ZGl2IGNsYXNzPSJ2YWx1ZSIgaWQ9InByb2ZpbC1zZWxlY3Rpb25uZSIgc3R5bGU9ImZvbnQtc2l6ZToxNXB4Ij7igJQ8L2Rpdj48L2Rpdj4KICAgICAgICA8L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJiYXJlbWUiPjMwLTUxID0gU8OpY3VyaXRhaXJlIMK3IDUyLTcyID0gUHJ1ZGVudCDCtyA3My05MyA9IMOJcXVpbGlicsOpIMK3IDk0LTExNSA9IER5bmFtaXF1ZTwvZGl2PgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgoKICAgIDwhLS0g4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWQIFRBQiA0IDogQURFUVVBVElPTiDilZDilZDilZDilZDilZDilZDilZDilZDilZDilZDilZAgLS0+CiAgICA8ZGl2IGNsYXNzPSJ0YWJwYWdlIiBpZD0idGFicGFnZS1hZGVxdWF0aW9uIj4KICAgICAgPGRpdiBjbGFzcz0ic2VjLWJhciI+RMOpY2xhcmF0aW9uIGQnYWTDqXF1YXRpb248L2Rpdj4KICAgICAgPGgzIGNsYXNzPSJzdWIiPjEuIFJhcHBlbCBkZXMgZXhpZ2VuY2VzIGV0IGJlc29pbnMgZXhwcmltw6lzPC9oMz4KICAgICAgPGRpdiBjbGFzcz0iZ3JpZDIiPgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+UmFwcGVsIGRlIGxhIGRlbWFuZGU8L2xhYmVsPjxpbnB1dCB0eXBlPSJ0ZXh0IiBpZD0iYWRlcV9kZW1hbmRlIj48L2Rpdj4KICAgICAgICA8ZGl2PjxsYWJlbCBjbGFzcz0iZmllbGQiPlJhcHBlbCBkZXMgb2JqZWN0aWZzPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImFkZXFfb2JqZWN0aWZzIj48L2Rpdj4KICAgICAgPC9kaXY+CgogICAgICA8aDMgY2xhc3M9InN1YiI+Mi4gU29sdXRpb25zIGVudmlzYWfDqWVzPC9oMz4KICAgICAgPGRpdiBjbGFzcz0iZ3JpZDIiPgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+U29sdXRpb24gcmV0ZW51ZTwvbGFiZWw+PGlucHV0IHR5cGU9InRleHQiIGlkPSJhZGVxX3NvbHV0aW9uMSI+PC9kaXY+CiAgICAgICAgPGRpdj48bGFiZWwgY2xhc3M9ImZpZWxkIj5Tb2x1dGlvbiBhbHRlcm5hdGl2ZTwvbGFiZWw+PGlucHV0IHR5cGU9InRleHQiIGlkPSJhZGVxX3NvbHV0aW9uMiI+PC9kaXY+CiAgICAgIDwvZGl2PgoKICAgICAgPGgzIGNsYXNzPSJzdWIiPjMuIFLDqWNhcGl0dWxhdGlmPC9oMz4KICAgICAgPGRpdiBpZD0iYWRlcS1yZWNhcCI+PC9kaXY+CgogICAgICA8aDMgY2xhc3M9InN1YiI+Q2/Du3RzIGV0IGZyYWlzPC9oMz4KICAgICAgPGRpdiBjbGFzcz0iZ3JpZDIiPgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+RnJhaXMgZGUgY291cnRhZ2UgKCUpPC9sYWJlbD48aW5wdXQgdHlwZT0idGV4dCIgaWQ9ImFkZXFfZnJhaXNfY291cnRhZ2UiPjwvZGl2PgogICAgICAgIDxkaXY+PGxhYmVsIGNsYXNzPSJmaWVsZCI+RnJhaXMgZGUgZ2VzdGlvbiBmaW5hbmNpw6hyZSAoJSk8L2xhYmVsPjxpbnB1dCB0eXBlPSJ0ZXh0IiBpZD0iYWRlcV9mcmFpc19nZXN0aW9uIj48L2Rpdj4KICAgICAgPC9kaXY+CgogICAgICA8cCBjbGFzcz0ibm90ZSI+TGUgQ2xpZW50IHJlY29ubmHDrnQgcXVlIGxlcyBpbmZvcm1hdGlvbnMgZm91cm5pZXMgc29udCBzaW5jw6hyZXMgZXQgZXhhY3RlcywgZXQgcydlbmdhZ2Ugw6AgaW5mb3JtZXIgbCdpbnRlcm3DqWRpYWlyZSBkZSB0b3V0IGNoYW5nZW1lbnQgZGUgc2l0dWF0aW9uIG91IGQnb2JqZWN0aWZzLjwvcD4KCiAgICAgIDxkaXYgY2xhc3M9InR3by1jb2wiIHN0eWxlPSJtYXJnaW4tdG9wOjIwcHgiPgogICAgICAgIDxkaXY+PGgzIGNsYXNzPSJzdWIiPlNpZ25hdHVyZSBjbGllbnQ8L2gzPjxkaXYgY2xhc3M9InNpZy1ib3giPjwvZGl2PjwvZGl2PgogICAgICAgIDxkaXY+PGgzIGNsYXNzPSJzdWIiPlNpZ25hdHVyZSBkZSBsJ2ludGVybcOpZGlhaXJlPC9oMz48ZGl2IGNsYXNzPSJzaWctYm94Ij48L2Rpdj48L2Rpdj4KICAgICAgPC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0iZm9vdGVyLWJhciI+U0FTIENBUkVNTUEgRklOQU5DRSDCtyBSQ1MgUG9udG9pc2UgOTMzIDUzNyA0MzMgwrcgMTEyIFJ1ZSBSb3VnZXQgZGUgTGlzbGUsIDk1ODcwIEJlem9ucyDCtyBPUklBUyBuwrAyNDAwNzc2NzwvZGl2Pgo8L2Rpdj4KCjxzY3JpcHQ+Ci8vIOKVkOKVkOKVkCBOYXZpZ2F0aW9uIHBhciBvbmdsZXRzIChtYXNxdcOpZSDDoCBsJ2ltcHJlc3Npb24gOiB0b3V0ZXMgbGVzIHNlY3Rpb25zIHMnaW1wcmltZW50KSDilZDilZDilZAKZnVuY3Rpb24gc2hvd1RhYihuYW1lKXsKICBkb2N1bWVudC5xdWVyeVNlbGVjdG9yQWxsKCcudGFicGFnZScpLmZvckVhY2goZnVuY3Rpb24ocCl7cC5jbGFzc0xpc3QucmVtb3ZlKCdhY3RpdmUnKTt9KTsKICBkb2N1bWVudC5xdWVyeVNlbGVjdG9yQWxsKCcudGFiJykuZm9yRWFjaChmdW5jdGlvbih0KXt0LmNsYXNzTGlzdC5yZW1vdmUoJ2FjdGl2ZScpO30pOwogIGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCd0YWJwYWdlLScrbmFtZSkuY2xhc3NMaXN0LmFkZCgnYWN0aXZlJyk7CiAgZG9jdW1lbnQucXVlcnlTZWxlY3RvcignLnRhYltkYXRhLXRhYj0iJytuYW1lKyciXScpLmNsYXNzTGlzdC5hZGQoJ2FjdGl2ZScpOwp9CmZ1bmN0aW9uIHVwZGF0ZUNsaWVudE5hbWUoKXsKICB2YXIgcD1kb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnY2xpZW50X3ByZW5vbScpLnZhbHVlLCBuPWRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCdjbGllbnRfbm9tJykudmFsdWU7CiAgZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ2NsaWVudC1uYW1lLWRpc3BsYXknKS50ZXh0Q29udGVudCA9IChwfHxuKSA/IChwKycgJytuKS50cmltKCkgOiAnbm91dmVhdSBjbGllbnQnOwogIHNhdmVTdGF0ZSgpOwp9CgovLyDilZDilZDilZAgRG9ubsOpZXMgZGVzIHNlY3Rpb25zIG5vdMOpZXMgKGlkZW50aXF1ZXMgw6AgbGEgRmljaGUgQ29ubmFpc3NhbmNlIENsaWVudCkg4pWQ4pWQ4pWQCnZhciBQUk9EVUlUUyA9IFsKICBbJ2FjdCcsJ0FjdGlvbnMgb3UgT1BDVk0gw6AgZG9taW5hbnRlIGFjdGlvbnMnXSxbJ29ibCcsJ09ibGlnYXRpb25zIG91IE9QQ1ZNIMOgIGRvbWluYW50ZSBvYmxpZ2F0YWlyZSddLAogIFsnbmNvJywnVGl0cmVzIG5vbiBjb3TDqXMsIEZJUCwgRkNQSSwgRkNQUiddLFsnbW9uJywnUHJvZHVpdHMgbW9uw6l0YWlyZXMsIGZvbmRzIGV1cm9zJ10sCiAgWydkaXYnLCdPUENWTSBkaXZlcnNpZmnDqSddLFsnc3RyJywnUHJvZHVpdHMgc3RydWN0dXLDqXMnXSxbJ2V0ZicsJ0VURiAvIHRyYWNrZXJzJ10sCiAgWydkZXInLCdQcm9kdWl0cyBkw6lyaXbDqXMgKG9wdGlvbnMsIGZ1dHVyZXMpJ10sWydjcnknLCdDcnlwdG9hY3RpZnMnXSxbJ2xldicsJ1Byb2R1aXRzIMOgIGVmZmV0IGRlIGxldmllciAvIFNSRCddLAogIFsnYXV0JywnQXV0cmVzIChnZXN0aW9uIGFsdGVybmF0aXZl4oCmKSddLFsnYmFuJywnUHJvZHVpdHMgYmFuY2FpcmVzIChsaXZyZXQsIFBFTOKApiknXSwKICBbJ2ltbScsJ0ltbW9iaWxpZXIgKHLDqWVsLCBTQ1BJLCBMTU5QLCBPUENJ4oCmKSddLFsnYXYnLCdBc3N1cmFuY2UtdmllLCBjb250cmF0IGRlIGNhcGl0YWxpc2F0aW9uJ10sCiAgWydkb20nLCdEw6lmaXNjYWxpc2F0aW9uIERvbVRvbSAoR2lyYXJkaW7igKYpJ10sWydwZWUnLCdQRUUsIFBhcnRpY2lwYXRpb24sIFBlcmNvJ10sWydzY2knLCdTQ0knXSwKXTsKdmFyIHByb2R1aXRzVGJsID0gZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ3Byb2R1aXRzLXRhYmxlJyk7ClBST0RVSVRTLmZvckVhY2goZnVuY3Rpb24ocCl7CiAgdmFyIHRyID0gZG9jdW1lbnQuY3JlYXRlRWxlbWVudCgndHInKTsKICB0ci5pbm5lckhUTUwgPSAnPHRkIGNsYXNzPSJsZWZ0Ij4nK3BbMV0rJzwvdGQ+JwogICAgKyAnPHRkPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImtuXycrcFswXSsnX2ludiI+PC90ZD4nCiAgICArICc8dGQ+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbl8nK3BbMF0rJyIgdmFsdWU9IjAiPjwvdGQ+JwogICAgKyAnPHRkPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia25fJytwWzBdKyciIHZhbHVlPSIyIj48L3RkPicKICAgICsgJzx0ZD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuXycrcFswXSsnIiB2YWx1ZT0iNCI+PC90ZD4nOwogIHByb2R1aXRzVGJsLmFwcGVuZENoaWxkKHRyKTsKfSk7CltbJ2FuY2llbm5ldGUtb3B0cycsJ2FuY2llbm5ldGVfaW52ZXN0JyxbWycwJywnSmFtYWlzIGludmVzdGknXSxbJzUnLCdNb2lucyBkZSAyIGFucyddLFsnMTAnLCcyIMOgIDUgYW5zJ10sWycxNScsJzUgw6AgMTAgYW5zJ10sWycyMCcsJ1BsdXMgZGUgMTAgYW5zJ11dXSwKIFsnZnJlcS1vcHRzJywnZnJlcV90cmFucycsW1snMCcsJ0F1Y3VuZSddLFsnNScsJzEgw6AgNSddLFsnMTAnLCc2IMOgIDIwJ10sWycxNScsJ1BsdXMgZGUgMjAnXV1dLAogWydtb250YW50LW9wdHMnLCdtb250YW50X21veScsW1snMCcsJ01vaW5zIGRlIDUgMDAwIOKCrCddLFsnNCcsJzUgMDAwIMOgIDIwIDAwMCDigqwnXSxbJzgnLCcyMCAwMDAgw6AgNTAgMDAwIOKCrCddLFsnMTMnLCdQbHVzIGRlIDUwIDAwMCDigqwnXV1dCl0uZm9yRWFjaChmdW5jdGlvbihjZmcpewogIHZhciBkaXYgPSBkb2N1bWVudC5nZXRFbGVtZW50QnlJZChjZmdbMF0pOwogIGNmZ1syXS5mb3JFYWNoKGZ1bmN0aW9uKG8pewogICAgdmFyIGQgPSBkb2N1bWVudC5jcmVhdGVFbGVtZW50KCdkaXYnKTsgZC5jbGFzc05hbWU9J29wdC1yb3cnOwogICAgZC5pbm5lckhUTUwgPSAnPGxhYmVsPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iJytjZmdbMV0rJyIgdmFsdWU9Iicrb1swXSsnIj4gJytvWzFdKyc8L2xhYmVsPic7CiAgICBkaXYuYXBwZW5kQ2hpbGQoZCk7CiAgfSk7Cn0pOwp2YXIgSU5GT19ST1dTID0gW1snaW5mMScsIkplIGxpcyBsYSBwcmVzc2Ugc3DDqWNpYWxpc8OpZSBjb25jZXJuYW50IG1lcyBwcm9kdWl0cyBkJ8OpcGFyZ25lIl0sCiAgWydpbmYyJywiSmUgbSdpbmZvcm1lIGRlIGxhIHZhbGV1ciBkZSBtZXMgcGxhY2VtZW50cyBmaW5hbmNpZXJzIGF1IG1vaW5zIHRvdXMgbGVzIG1vaXMiXSwKICBbJ2luZjMnLCJKZSBtJ2luZm9ybWUgZGUgbGEgdmFsZXVyIGRlIG1lcyBwbGFjZW1lbnRzIGltbW9iaWxpZXJzIGF1IG1vaW5zIHRvdXMgbGVzIGFucyJdLAogIFsnaW5mNCcsJ0plIHJlZ2FyZGUgbW9uIHJlbGV2w6kgYmFuY2FpcmUgYXUgbW9pbnMgdG91cyBsZXMgbW9pcyddXTsKdmFyIGluZm9UYmwgPSBkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnaW5mby10YWJsZScpOwpJTkZPX1JPV1MuZm9yRWFjaChmdW5jdGlvbihyKXsKICB2YXIgdHIgPSBkb2N1bWVudC5jcmVhdGVFbGVtZW50KCd0cicpOwogIHRyLmlubmVySFRNTCA9ICc8dGQgY2xhc3M9ImxlZnQiPicrclsxXSsnPC90ZD48dGQ+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSInK3JbMF0rJyIgdmFsdWU9IjE1Ij48L3RkPjx0ZD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9IicrclswXSsnIiB2YWx1ZT0iOCI+PC90ZD48dGQ+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSInK3JbMF0rJyIgdmFsdWU9IjAiPjwvdGQ+JzsKICBpbmZvVGJsLmFwcGVuZENoaWxkKHRyKTsKfSk7CnZhciBBRkZJUk1BVElPTlMgPSBbIkxhIHZlbnRlIGRhbnMgbCd1cmdlbmNlIGRlcyDDqWzDqW1lbnRzIGRlIG1vbiBwYXRyaW1vaW5lIHBldXQgbSdhbWVuZXIgw6Agc3ViaXIgdW5lIG1vaW5zLXZhbHVlIiwKICAiUGx1cyB1biBwcm9kdWl0IGVzdCByaXNxdcOpLCBwbHVzIHNhIHZhbGV1ciBwZXV0IHZhcmllciBmb3J0ZW1lbnQgw6AgbGEgaGF1c3NlIGNvbW1lIMOgIGxhIGJhaXNzZSIsCiAgIk1vaW5zIG1vbiBwYXRyaW1vaW5lIGVzdCBkaXZlcnNpZmnDqSwgcGx1cyBpbCBlc3QgZXhwb3PDqSBhdXggcmlzcXVlcyBkZSB2YXJpYXRpb24gZCd1bmUgdmFsZXVyIiwKICAiVG91dCBwcm9kdWl0IGQnw6lwYXJnbmUgcGV1dCBwcsOpc2VudGVyIGQnYXV0cmVzIHJpc3F1ZXMgcXUndW5lIHZhcmlhdGlvbiBkZSBzYSB2YWxldXIiLAogICJQb3VyIHVuIG3Dqm1lIHBsYWNlbWVudCwgbGUgcmlzcXVlIGVzdCBkaWZmw6lyZW50IHNlbG9uIGwnw6ljaMOpYW5jZSIsCiAgIkxhIHN0cnVjdHVyZSBkZSBtb24gcGF0cmltb2luZSBkb2l0IMOqdHJlIGNvaMOpcmVudGUgYXZlYyBtZXMgb2JqZWN0aWZzIiwKICAiTGVzIHByb2R1aXRzIGTDqXJpdsOpcyBwZXV2ZW50IGVudHJhw65uZXIgZGVzIHBlcnRlcyBzdXDDqXJpZXVyZXMgYXUgY2FwaXRhbCBpbnZlc3RpIiwKICAiVW4gaW52ZXN0aXNzZW1lbnQgZW4gZGV2aXNlIMOpdHJhbmfDqHJlIG0nZXhwb3NlIMOgIHVuIHJpc3F1ZSBkZSBjaGFuZ2UiLAogICJVbiBwcm9kdWl0IHBldSBsaXF1aWRlIHBldXQgw6p0cmUgZGlmZmljaWxlIMOgIHJldmVuZHJlIHJhcGlkZW1lbnQsIG91IGF2ZWMgdW5lIGTDqWNvdGUiLAogICJFbiBjYXMgZGUgZMOpZmFpbGxhbmNlIGRlIGwnw6ltZXR0ZXVyLCBqZSBwZXV4IHBlcmRyZSB0b3V0IG91IHBhcnRpZSBkZSBtb24gY2FwaXRhbCIsCiAgIkwnZWZmZXQgZGUgbGV2aWVyIGFtcGxpZmllIGxlcyBnYWlucyBFVCBsZXMgcGVydGVzIHBvdGVudGllbGxlcyIsCiAgIkxlcyBjcnlwdG9hY3RpZnMgcHLDqXNlbnRlbnQgZGVzIHJpc3F1ZXMgc2lnbmlmaWNhdGl2ZW1lbnQgc3Vww6lyaWV1cnMgw6AgY2V1eCBkZXMgYWN0aW9ucyJdOwp2YXIgYWZmVGJsID0gZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ2FmZi10YWJsZScpOwpBRkZJUk1BVElPTlMuZm9yRWFjaChmdW5jdGlvbihhLGkpewogIHZhciBuPSdhZmYnKyhpKzEpOyB2YXIgdHI9ZG9jdW1lbnQuY3JlYXRlRWxlbWVudCgndHInKTsKICB0ci5pbm5lckhUTUwgPSAnPHRkIGNsYXNzPSJsZWZ0Ij4nK2ErJzwvdGQ+PHRkPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iJytuKyciIHZhbHVlPSIxIj48L3RkPjx0ZD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9IicrbisnIiB2YWx1ZT0iMCI+PC90ZD4nOwogIGFmZlRibC5hcHBlbmRDaGlsZCh0cik7Cn0pOwp2YXIgT0JKRUNUSUZTX1NPVVNDUklQVElPTiA9IFsiU2UgY29uc3RpdHVlciB1bmUgw6lwYXJnbmUgZGUgcHLDqWNhdXRpb24iLCJWYWxvcmlzZXIgdW4gY2FwaXRhbCBleGlzdGFudCIsIlByw6lwYXJlciBzYSByZXRyYWl0ZSIsIk9wdGltaXNlciBzYSBmaXNjYWxpdMOpIiwiT3B0aW1pc2VyIGxhIHRyYW5zbWlzc2lvbiIsIkFpZGVyIHNlcyBwcm9jaGVzIiwiQ29tcGzDqXRlciBzZXMgcmV2ZW51cyJdOwp2YXIgb2JqTGlzdCA9IGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCdxby1vYmplY3RpZnMtbGlzdCcpOwpPQkpFQ1RJRlNfU09VU0NSSVBUSU9OLmZvckVhY2goZnVuY3Rpb24obyxpKXsKICB2YXIgZD1kb2N1bWVudC5jcmVhdGVFbGVtZW50KCdkaXYnKTsgZC5jbGFzc05hbWU9J29wdC1yb3cnOwogIGQuaW5uZXJIVE1MPSc8bGFiZWw+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW9fb2JqXycraSsnIj4gJytvKyc8L2xhYmVsPic7CiAgb2JqTGlzdC5hcHBlbmRDaGlsZChkKTsKfSk7CnZhciBSRUNBUF9RID0gWyJMYSByZWNvbW1hbmRhdGlvbiBlc3QtZWxsZSBhZGFwdMOpZSBhdSBjbGllbnQgPyIsIkVzdC1lbGxlIGNvbmZvcm1lIGF1eCBvYmplY3RpZnMgPyIsIkxhIGR1csOpZSBkJ2ludmVzdGlzc2VtZW50IGVzdC1lbGxlIGNvbmZvcm1lID8iLCJFc3QtZWxsZSBhZGFwdMOpZSBhdXggY29ubmFpc3NhbmNlcyBldCDDoCBsJ2V4cMOpcmllbmNlID8iLCJFc3QtZWxsZSBhZGFwdMOpZSBhdSBwcm9maWwgZGUgcmlzcXVlID8iLCJJbnTDqGdyZS10LWVsbGUgbGVzIHByw6lmw6lyZW5jZXMgZGUgZHVyYWJpbGl0w6kgPyJdOwp2YXIgcmVjYXBEaXYgPSBkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnYWRlcS1yZWNhcCcpOwpSRUNBUF9RLmZvckVhY2goZnVuY3Rpb24ocSxpKXsKICB2YXIgZD1kb2N1bWVudC5jcmVhdGVFbGVtZW50KCdkaXYnKTsKICBkLmlubmVySFRNTD0nPGRpdiBzdHlsZT0iZm9udC1zaXplOjEyLjVweDttYXJnaW4tdG9wOjhweCI+JytxKyc8L2Rpdj48ZGl2IGNsYXNzPSJpbmxpbmUteW4iPjxsYWJlbD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFkZXFfcmVjYXBfJytpKyciIHZhbHVlPSJvdWkiPiBPdWk8L2xhYmVsPjxsYWJlbD48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFkZXFfcmVjYXBfJytpKyciIHZhbHVlPSJub24iPiBOb248L2xhYmVsPjwvZGl2Pic7CiAgcmVjYXBEaXYuYXBwZW5kQ2hpbGQoZCk7Cn0pOwp2YXIgUklTS19RVUVTVElPTlMgPSBbCiAge25hbWU6J3Jpc2tfcTEnLCBxOicxLiBTaSBkZW1haW4gbGEgdmFsZXVyIGRlIG1vbiBwbGFjZW1lbnQgdmVuYWl0IMOgIGNodXRlciBkZSAyMCAlJywgb3B0czpbWyc1JywnSmUgdmVuZHMgVE9VVCBldCByYWNow6h0ZSBkZXMgYWN0aWZzIG1vaW5zIHJpc3F1w6lzJ10sWycxMCcsJ0plIHZlbmRzIFVORSBQQVJUSUUgZXQgcmFjaMOodGUgZGVzIGFjdGlmcyBtb2lucyByaXNxdcOpcyddLFsnMTUnLCdKZSBjb25zZXJ2ZSwgbGEgdmFsZXVyIHZhIHJlbW9udGVyJ10sWycyMCcsIkonZW4gcmFjaMOodGUgZW5jb3JlIHBsdXMiXV19LAogIHtuYW1lOidyaXNrX3EyJywgcTonMi4gQXZlei12b3VzIGTDqWrDoCBzdWJpIGRlcyBwZXJ0ZXMgPyBDb21tZW50IGF2ZXotdm91cyByw6lhZ2kgPycsIG9wdHM6W1snNScsIkonYWkgdmVuZHUiXSxbJzEwJywiSidhaSB2ZW5kdSB1bmUgcGFydGllIl0sWycxNScsIkonYWkgdG91dCBjb25zZXJ2w6kiXSxbJzIwJywiSidhaSByw6lpbnZlc3RpIl1dfSwKICB7bmFtZToncmlza19xMycsIHE6JzMuIENvbW1lbnQgYXZlei12b3VzIHbDqWN1IGxlcyBkZXJuacOocmVzIHNlY291c3NlcyBkZXMgbWFyY2jDqXMgPycsIG9wdHM6W1snNScsIkplIG4nZW4gZG9ybWFpcyBwYXMgbGEgbnVpdCJdLFsnMTAnLCJKZSBuJ8OpdGFpcyBwYXMgYXUgY291cmFudCJdLFsnMTUnLCJTdWl2aSBkZSBwcsOocyBzYW5zIHBhbmlxdWVyIl0sWycyMCcsJ1NlcmVpbmVtZW50J11dfSwKICB7bmFtZToncmlza19xNCcsIHE6JzQuIExlIGNyaXTDqHJlIGRlIGxpcXVpZGl0w6kgZXN0IGltcG9ydGFudCBwb3VyIG1vbiBwYXRyaW1vaW5lJywgb3B0czpbWyc1JywnVG91am91cnMgdW5lIHBhcnQgaW1wb3J0YW50ZSBsaXF1aWRlJ10sWycxMCcsJ1VuIHBldGl0IG1hdGVsYXMgZGUgc8OpY3VyaXTDqSddLFsnMTUnLCJKZSBuZSBnYXJkZSBxdWUgY2UgZG9udCBqJ2FpIGJlc29pbiJdXX0sCiAge25hbWU6J3Jpc2tfcTUnLCBxOic1LiBBaW1lei12b3VzIHByZW5kcmUgZGVzIHJpc3F1ZXMgZGFucyBsYSB2aWUgPycsIG9wdHM6W1snNScsJ05vbiddLFsnMTAnLCdQYXJmb2lzJ10sWycxNScsJ0Fzc2V6IHNvdXZlbnQnXSxbJzIwJywiQXV0YW50IHF1ZSBqZSBwZXV4Il1dfSwKICB7bmFtZToncmlza19xNicsIHE6JzYuIFZvdHJlIHByaW5jaXBhbCBvYmplY3RpZiBhIHVuZSDDqWNow6lhbmNlIGRlJywgb3B0czpbWyc1JywnNiBtb2lzIMOgIDMgYW5zJ10sWycxMCcsJzQgw6AgMTAgYW5zJ10sWycxNScsJzExIMOgIDE1IGFucyddLFsnMjAnLCdQbHVzIGRlIDE1IGFucyddXX0sCl07CnZhciByaXNrRGl2ID0gZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ3Jpc2stcXVlc3Rpb25zJyk7ClJJU0tfUVVFU1RJT05TLmZvckVhY2goZnVuY3Rpb24ocnEpewogIHZhciBoPWRvY3VtZW50LmNyZWF0ZUVsZW1lbnQoJ2gzJyk7IGguY2xhc3NOYW1lPSdzdWInOyBoLnRleHRDb250ZW50PXJxLnE7IHJpc2tEaXYuYXBwZW5kQ2hpbGQoaCk7CiAgcnEub3B0cy5mb3JFYWNoKGZ1bmN0aW9uKG8pewogICAgdmFyIGQ9ZG9jdW1lbnQuY3JlYXRlRWxlbWVudCgnZGl2Jyk7IGQuY2xhc3NOYW1lPSdvcHQtcm93JzsKICAgIGQuaW5uZXJIVE1MPSc8bGFiZWw+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSInK3JxLm5hbWUrJyIgdmFsdWU9Iicrb1swXSsnIj4gJytvWzFdKyc8L2xhYmVsPic7CiAgICByaXNrRGl2LmFwcGVuZENoaWxkKGQpOwogIH0pOwp9KTsKCi8vIOKVkOKVkOKVkCBDYWxjdWwgZW4gZGlyZWN0IOKVkOKVkOKVkAp2YXIgU0NPUkVfRklFTERTID0gWydnZXN0aW9uX3Bhc3NlJywnZm9ybWF0aW9uX2ZpbicsJ2V4cF9wcm9fZmluJywnYW5jaWVubmV0ZV9pbnZlc3QnLCdmcmVxX3RyYW5zJywnbW9udGFudF9tb3knLCdpbmYxJywnaW5mMicsJ2luZjMnLCdpbmY0J10KICAuY29uY2F0KFBST0RVSVRTLm1hcChmdW5jdGlvbihwKXtyZXR1cm4gJ2tuXycrcFswXTt9KSkuY29uY2F0KEFGRklSTUFUSU9OUy5tYXAoZnVuY3Rpb24oYSxpKXtyZXR1cm4gJ2FmZicrKGkrMSk7fSkpOwp2YXIgUklTS19GSUVMRFMgPSBSSVNLX1FVRVNUSU9OUy5tYXAoZnVuY3Rpb24ocil7cmV0dXJuIHIubmFtZTt9KTsKZnVuY3Rpb24gcmFkaW9WYWx1ZShuYW1lKXt2YXIgZWxzPWRvY3VtZW50LmdldEVsZW1lbnRzQnlOYW1lKG5hbWUpO2Zvcih2YXIgaT0wO2k8ZWxzLmxlbmd0aDtpKyspaWYoZWxzW2ldLmNoZWNrZWQpcmV0dXJuIHBhcnNlRmxvYXQoZWxzW2ldLnZhbHVlKTtyZXR1cm4gbnVsbDt9CmZ1bmN0aW9uIHJhZGlvVmFsdWVUZXh0KG5hbWUpe3ZhciBlbHM9ZG9jdW1lbnQuZ2V0RWxlbWVudHNCeU5hbWUobmFtZSk7Zm9yKHZhciBpPTA7aTxlbHMubGVuZ3RoO2krKylpZihlbHNbaV0uY2hlY2tlZClyZXR1cm4gZWxzW2ldLnBhcmVudEVsZW1lbnQudGV4dENvbnRlbnQudHJpbSgpO3JldHVybiBudWxsO30KZnVuY3Rpb24gY29tcHV0ZUFsbCgpewogIHZhciB0b3RhbD0wOyBTQ09SRV9GSUVMRFMuZm9yRWFjaChmdW5jdGlvbihmKXt2YXIgdj1yYWRpb1ZhbHVlKGYpOyBpZih2IT09bnVsbCkgdG90YWwrPXY7fSk7CiAgZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ3Njb3JlLWNvbm5haXNzYW5jZScpLnRleHRDb250ZW50ID0gdG90YWwrJyAvIDIxOCc7CiAgdmFyIGNhdD0n4oCUJzsgaWYodG90YWw+MCl7IGlmKHRvdGFsPD04MCljYXQ9J1Njb3JlIGluc3VmZmlzYW50JztlbHNlIGlmKHRvdGFsPD0xMjUpY2F0PSdJbnZlc3Rpc3NldXIgZGUgQmFzZSc7ZWxzZSBpZih0b3RhbDw9MTcxKWNhdD0nSW52ZXN0aXNzZXVyIEF2ZXJ0aSc7ZWxzZSBjYXQ9J0ludmVzdGlzc2V1ciBBdmFuY8OpJzsgfQogIGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCdjYXRlZ29yaWUtY29ubmFpc3NhbmNlJykudGV4dENvbnRlbnQgPSBjYXQ7CgogIHZhciByaXNrVG90YWw9MDsgUklTS19GSUVMRFMuZm9yRWFjaChmdW5jdGlvbihmKXt2YXIgdj1yYWRpb1ZhbHVlKGYpOyBpZih2IT09bnVsbCkgcmlza1RvdGFsKz12O30pOwogIGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCdzY29yZS1yaXNxdWUnKS50ZXh0Q29udGVudCA9IHJpc2tUb3RhbCsnIC8gMTE1JzsKICB2YXIgcHJvZj0n4oCUJzsgaWYocmlza1RvdGFsPjApeyBpZihyaXNrVG90YWw8PTUxKXByb2Y9J1PDqWN1cml0YWlyZSc7ZWxzZSBpZihyaXNrVG90YWw8PTcyKXByb2Y9J1BydWRlbnQnO2Vsc2UgaWYocmlza1RvdGFsPD05Mylwcm9mPSfDiXF1aWxpYnLDqSc7ZWxzZSBwcm9mPSdEeW5hbWlxdWUnOyB9CiAgZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ3Byb2ZpbC1yaXNxdWUnKS50ZXh0Q29udGVudCA9IHByb2Y7CiAgZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ3Byb2ZpbC1zZWxlY3Rpb25uZScpLnRleHRDb250ZW50ID0gcmFkaW9WYWx1ZVRleHQoJ3Jpc2tfcHJvZmlsX2dsb2JhbCcpIHx8ICfigJQnOwogIHNhdmVTdGF0ZSgpOwp9CmRvY3VtZW50LmFkZEV2ZW50TGlzdGVuZXIoJ2NoYW5nZScsIGNvbXB1dGVBbGwpOwpkb2N1bWVudC5hZGRFdmVudExpc3RlbmVyKCdpbnB1dCcsIGZ1bmN0aW9uKGUpeyBpZihlLnRhcmdldC50YWdOYW1lPT09J0lOUFVUJykgc2F2ZVN0YXRlKCk7IH0pOwoKLy8g4pWQ4pWQ4pWQIFNhdXZlZ2FyZGUgbG9jYWxlIOKVkOKVkOKVkApmdW5jdGlvbiBjb2xsZWN0Rm9ybURhdGEoKXsKICB2YXIgZGF0YT17fTsKICBkb2N1bWVudC5xdWVyeVNlbGVjdG9yQWxsKCdpbnB1dCwgc2VsZWN0JykuZm9yRWFjaChmdW5jdGlvbihlbCl7CiAgICB2YXIga2V5PWVsLmlkfHxlbC5uYW1lOyBpZigha2V5KSByZXR1cm47CiAgICBpZihlbC50eXBlPT09J2NoZWNrYm94JykgZGF0YVtrZXldPWVsLmNoZWNrZWQ7CiAgICBlbHNlIGlmKGVsLnR5cGU9PT0ncmFkaW8nKXsgaWYoZWwuY2hlY2tlZCkgZGF0YVtlbC5uYW1lXT1lbC52YWx1ZTsgfQogICAgZWxzZSBkYXRhW2tleV09ZWwudmFsdWU7CiAgfSk7CiAgcmV0dXJuIGRhdGE7Cn0KZnVuY3Rpb24gc2F2ZVN0YXRlKCl7CiAgdHJ5ewogICAgbG9jYWxTdG9yYWdlLnNldEl0ZW0oJ2NhcmVtbWFfcGFyY291cnNfY29tcGxldCcsIEpTT04uc3RyaW5naWZ5KGNvbGxlY3RGb3JtRGF0YSgpKSk7CiAgICB2YXIgbT1kb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnYXV0b3NhdmUtbXNnJyk7IGlmKG0peyBtLnRleHRDb250ZW50PSfinJMgU2F1dmVnYXJkw6knOyBzZXRUaW1lb3V0KGZ1bmN0aW9uKCl7bS50ZXh0Q29udGVudD0nJzt9LDE1MDApOyB9CiAgfWNhdGNoKGUpe30KfQpmdW5jdGlvbiBsb2FkU3RhdGUoKXsKICB0cnl7CiAgICB2YXIgcmF3PWxvY2FsU3RvcmFnZS5nZXRJdGVtKCdjYXJlbW1hX3BhcmNvdXJzX2NvbXBsZXQnKTsgaWYoIXJhdykgcmV0dXJuOwogICAgdmFyIGRhdGE9SlNPTi5wYXJzZShyYXcpOwogICAgT2JqZWN0LmtleXMoZGF0YSkuZm9yRWFjaChmdW5jdGlvbihrZXkpewogICAgICB2YXIgZWxzPWRvY3VtZW50LmdldEVsZW1lbnRzQnlOYW1lKGtleSk7CiAgICAgIGlmKGVscy5sZW5ndGggJiYgZWxzWzBdLnR5cGU9PT0ncmFkaW8nKXsgZWxzLmZvckVhY2goZnVuY3Rpb24oZWwpe2VsLmNoZWNrZWQ9KGVsLnZhbHVlPT09ZGF0YVtrZXldKTt9KTsgfQogICAgICBlbHNlIHsgdmFyIGVsPWRvY3VtZW50LmdldEVsZW1lbnRCeUlkKGtleSk7IGlmKCFlbCkgcmV0dXJuOyBpZihlbC50eXBlPT09J2NoZWNrYm94JykgZWwuY2hlY2tlZD1kYXRhW2tleV07IGVsc2UgZWwudmFsdWU9ZGF0YVtrZXldOyB9CiAgICB9KTsKICB9Y2F0Y2goZSl7fQp9CmZ1bmN0aW9uIHJlc2V0Rm9ybSgpewogIGlmKCFjb25maXJtKCdFZmZhY2VyIHRvdXRlcyBsZXMgcsOpcG9uc2VzIHNhaXNpZXMgPycpKSByZXR1cm47CiAgbG9jYWxTdG9yYWdlLnJlbW92ZUl0ZW0oJ2NhcmVtbWFfcGFyY291cnNfY29tcGxldCcpOwogIGRvY3VtZW50LnF1ZXJ5U2VsZWN0b3JBbGwoJ2lucHV0JykuZm9yRWFjaChmdW5jdGlvbihlbCl7IGlmKGVsLnR5cGU9PT0nY2hlY2tib3gnfHxlbC50eXBlPT09J3JhZGlvJykgZWwuY2hlY2tlZD1mYWxzZTsgZWxzZSBlbC52YWx1ZT0nJzsgfSk7CiAgY29tcHV0ZUFsbCgpOyB1cGRhdGVDbGllbnROYW1lKCk7Cn0KCi8vIOKVkOKVkOKVkCBUw6lsw6ljaGFyZ2VtZW50IFBERiAoaW1wcmVzc2lvbiBuYXZpZ2F0ZXVyLCBjb3VsZXVycyBDYXJlbW1hIGZvcmPDqWVzIHZpYSBDU1MgcHJpbnQpIOKVkOKVkOKVkApmdW5jdGlvbiBkb3dubG9hZFBERigpewogIHRvYXN0X3BjMignT3V2ZXJ0dXJlIGRlIGxcJ2FwZXLDp3UgZFwnaW1wcmVzc2lvbuKApiBjaG9pc2lzc2V6ICJFbnJlZ2lzdHJlciBlbiBQREYiIGNvbW1lIGltcHJpbWFudGUuJyk7CiAgc2V0VGltZW91dChmdW5jdGlvbigpeyB3aW5kb3cucHJpbnQoKTsgfSwgMzAwKTsKfQoKLy8g4pWQ4pWQ4pWQIEVudm9pIHBhciBlbWFpbCAobWFpbHRvIOKAlCBsZSBQREYgZG9pdCDDqnRyZSBqb2ludCBtYW51ZWxsZW1lbnQsIGF1Y3VuIG91dGlsIHdlYiBuZSBwZXV0Ci8vICAgICBqb2luZHJlIHVuIGZpY2hpZXIgYXV0b21hdGlxdWVtZW50IMOgIHVuIGVtYWlsIHNhbnMgcGFzc2VyIHBhciB1biBzZXJ2ZXVyIGQnZW52b2kpIOKVkOKVkOKVkApmdW5jdGlvbiBlbnZveWVyUGFyRW1haWwoKXsKICB2YXIgZW1haWwgPSAoZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ2NsaWVudF9lbWFpbCcpLnZhbHVlfHwnJykudHJpbSgpOwogIHZhciBwcmVub20gPSAoZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ2NsaWVudF9wcmVub20nKS52YWx1ZXx8JycpLnRyaW0oKTsKICB2YXIgbm9tID0gKGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCdjbGllbnRfbm9tJykudmFsdWV8fCcnKS50cmltKCk7CiAgaWYoIWVtYWlsKXsgYWxlcnQoIk1lcmNpIGRlIHJlbnNlaWduZXIgbCdlbWFpbCBkdSBjbGllbnQgYXZhbnQgbCdlbnZvaS4iKTsgcmV0dXJuOyB9CiAgdmFyIHN1YmplY3QgPSAnVm90cmUgcGFyY291cnMgY2xpZW50IENhcmVtbWEgRmluYW5jZSc7CiAgdmFyIGJvZHkgPSAnQm9uam91ciAnKyhwcmVub218fCcnKSsnLFxuXG4nCiAgICArICdWb3VzIHRyb3V2ZXJleiBjaS1qb2ludCB2b3RyZSBkb3NzaWVyIGRlIHBhcmNvdXJzIGNsaWVudCAoZW50csOpZSBlbiByZWxhdGlvbiwgb2JqZWN0aWZzLCBjb25uYWlzc2FuY2UgJiByaXNxdWUsIGFkw6lxdWF0aW9uKS5cblxuJwogICAgKyAnTWVyY2kgZGUgbGUgY29uc3VsdGVyLCBsZSBzaWduZXIsIHB1aXMgZGUgbWUgbGUgcmV0b3VybmVyIHBhciByZXRvdXIgZGUgbWFpbC5cblxuJwogICAgKyAnQmllbiBjb3JkaWFsZW1lbnQsXG5NYXJjIFJldmVyc2VhdVxuQ2FyZW1tYSBGaW5hbmNlJzsKICB2YXIgbWFpbHRvID0gJ21haWx0bzonK2VuY29kZVVSSUNvbXBvbmVudChlbWFpbCkrJz9zdWJqZWN0PScrZW5jb2RlVVJJQ29tcG9uZW50KHN1YmplY3QpKycmYm9keT0nK2VuY29kZVVSSUNvbXBvbmVudChib2R5KTsKICBkb3dubG9hZFBERigpOwogIHNldFRpbWVvdXQoZnVuY3Rpb24oKXsgd2luZG93LmxvY2F0aW9uLmhyZWYgPSBtYWlsdG87IH0sIDgwMCk7Cn0KCi8vIOKVkOKVkOKVkCBFeHBvcnQgZGVzIGRvbm7DqWVzIChKU09OKSDigJQgw6AgaW1wb3J0ZXIgZW5zdWl0ZSBkYW5zIGxlIENSTSBwb3VyIHJldHJvdXZlciBsZSBjbGllbnQgYXV0b21hdGlxdWVtZW50IOKVkOKVkOKVkApmdW5jdGlvbiBleHBvcnREYXRhSlNPTigpewogIHZhciBwcmVub209KGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCdjbGllbnRfcHJlbm9tJykudmFsdWV8fCcnKS50cmltKCk7CiAgdmFyIG5vbT0oZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ2NsaWVudF9ub20nKS52YWx1ZXx8JycpLnRyaW0oKTsKICB2YXIgcGF5bG9hZCA9IHsKICAgIF9tZXRhOiB7CiAgICAgIHByZW5vbTogcHJlbm9tLCBub206IG5vbSwKICAgICAgZW1haWw6IChkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnY2xpZW50X2VtYWlsJykudmFsdWV8fCcnKS50cmltKCksCiAgICAgIGRhdGU6IChkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnZG9jX2RhdGUnKS52YWx1ZXx8JycpLAogICAgICBzY29yZUNvbm5haXNzYW5jZTogZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ3Njb3JlLWNvbm5haXNzYW5jZScpLnRleHRDb250ZW50LAogICAgICBjYXRlZ29yaWVDb25uYWlzc2FuY2U6IGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCdjYXRlZ29yaWUtY29ubmFpc3NhbmNlJykudGV4dENvbnRlbnQsCiAgICAgIHNjb3JlUmlzcXVlOiBkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnc2NvcmUtcmlzcXVlJykudGV4dENvbnRlbnQsCiAgICAgIHByb2ZpbFJpc3F1ZTogZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ3Byb2ZpbC1yaXNxdWUnKS50ZXh0Q29udGVudCwKICAgICAgZXhwb3J0ZUxlOiBuZXcgRGF0ZSgpLnRvTG9jYWxlU3RyaW5nKCdmci1GUicpLAogICAgfSwKICAgIGRhdGE6IGNvbGxlY3RGb3JtRGF0YSgpLAogIH07CiAgdmFyIGJsb2IgPSBuZXcgQmxvYihbSlNPTi5zdHJpbmdpZnkocGF5bG9hZCwgbnVsbCwgMildLCB7dHlwZTonYXBwbGljYXRpb24vanNvbid9KTsKICB2YXIgdXJsID0gVVJMLmNyZWF0ZU9iamVjdFVSTChibG9iKTsKICB2YXIgYSA9IGRvY3VtZW50LmNyZWF0ZUVsZW1lbnQoJ2EnKTsKICB2YXIgc2FmZU5hbWUgPSAoKHByZW5vbSsnXycrbm9tKS50cmltKCkucmVwbGFjZSgvW15hLXpBLVowLTlfLV0rL2csJ18nKSkgfHwgJ2NsaWVudCc7CiAgYS5ocmVmID0gdXJsOyBhLmRvd25sb2FkID0gJ3BhcmNvdXJzXycrc2FmZU5hbWUrJy5qc29uJzsKICBkb2N1bWVudC5ib2R5LmFwcGVuZENoaWxkKGEpOyBhLmNsaWNrKCk7IGRvY3VtZW50LmJvZHkucmVtb3ZlQ2hpbGQoYSk7CiAgVVJMLnJldm9rZU9iamVjdFVSTCh1cmwpOwogIHRvYXN0X3BjMignRmljaGllciBkZSBkb25uw6llcyBleHBvcnTDqSDinJMg4oCUIMOgIGltcG9ydGVyIGRhbnMgbGUgQ1JNJyk7Cn0KZnVuY3Rpb24gdG9hc3RfcGMyKG1zZyl7CiAgdmFyIGVsID0gZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ2F1dG9zYXZlLW1zZycpOwogIGlmKGVsKXsgZWwudGV4dENvbnRlbnQgPSBtc2c7IHNldFRpbWVvdXQoZnVuY3Rpb24oKXsgZWwudGV4dENvbnRlbnQ9Jyc7IH0sIDMwMDApOyB9Cn0KCmxvYWRTdGF0ZSgpOwpjb21wdXRlQWxsKCk7CnVwZGF0ZUNsaWVudE5hbWUoKTsKPC9zY3JpcHQ+CjwvYm9keT4KPC9odG1sPgo=";
var _CONNAISSANCE_B64="PGRpdj4KCjwhLS0gQkFSUkUgw4lUQVBFUyAtLT4KPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2JvcmRlci1yYWRpdXM6OHB4IDhweCAwIDA7b3ZlcmZsb3c6aGlkZGVuO21hcmdpbi1ib3R0b206MTZweCI+CiAgPGJ1dHRvbiBpZD0icGIzIiBvbmNsaWNrPSJnb0Nvbm5haXNzYW5jZSgzKSIgc3R5bGU9ImZsZXg6MTtwYWRkaW5nOjEwcHggNnB4O2JvcmRlcjpub25lO2JhY2tncm91bmQ6dmFyKC0tZ29sZCk7Y29sb3I6dmFyKC0tbmF2eSk7Zm9udC13ZWlnaHQ6NzAwO2ZvbnQtc2l6ZToxMS41cHg7Y3Vyc29yOnBvaW50ZXI7Zm9udC1mYW1pbHk6aW5oZXJpdCI+MSDCtyBDb25uYWlzc2FuY2UgJmFtcDsgQ29tcMOpdGVuY2U8L2J1dHRvbj4KICA8YnV0dG9uIGlkPSJwYjQiIG9uY2xpY2s9ImdvQ29ubmFpc3NhbmNlKDQpIiBzdHlsZT0iZmxleDoxO3BhZGRpbmc6MTBweCA2cHg7Ym9yZGVyOm5vbmU7YmFja2dyb3VuZDp2YXIoLS1jcmVhbTIpO2NvbG9yOnZhcigtLW11dGVkKTtmb250LXdlaWdodDo2MDA7Zm9udC1zaXplOjExLjVweDtjdXJzb3I6cG9pbnRlcjtmb250LWZhbWlseTppbmhlcml0Ij4yIMK3IMOJdmFsdWF0aW9uIGR1IHJpc3F1ZTwvYnV0dG9uPgo8L2Rpdj4KCjwhLS0g4pWQ4pWQ4pWQIFNFQ1RJT04gMyA6IENPTk5BSVNTQU5DRSAmIENPTVDDiVRFTkNFIOKVkOKVkOKVkCAtLT4KPGRpdiBpZD0icHMzIiBzdHlsZT0iZGlzcGxheTpibG9jayI+CiAgPGRpdiBjbGFzcz0ic2VjdGlvbi1oZWFkZXIiPjxoMj5Db25uYWlzc2FuY2UgJmFtcDsgQ29tcMOpdGVuY2U8L2gyPjwvZGl2PgogIDxkaXYgY2xhc3M9ImluZm8tYm94Ij5DZSBxdWVzdGlvbm5haXJlIGEgcG91ciBvYmplY3RpZiBkZSBub3VzIGFpZGVyIMOgIGTDqXRlcm1pbmVyIHZvdHJlIGF0dGl0dWRlIHBhciByYXBwb3J0IGF1IHJpc3F1ZSBldCB2b3RyZSBuaXZlYXUgZGUgY29ubmFpc3NhbmNlIGRlcyBwcm9kdWl0cyBmaW5hbmNpZXJzLiBJbCBkw6l0ZXJtaW5lIHZvdHJlIGNhdMOpZ29yaXNhdGlvbiA6IEludmVzdGlzc2V1ciBkZSBCYXNlIC8gQXZlcnRpIC8gQXZhbmPDqS48L2Rpdj4KCiAgPGRpdiBjbGFzcz0iY2FyZCIgc3R5bGU9Im1hcmdpbi1ib3R0b206MTJweCI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkLXRpdGxlIj5Qcm9kdWl0cyBmaW5hbmNpZXJzIOKAlCBFeHDDqXJpZW5jZSBldCBjb25uYWlzc2FuY2U8L2Rpdj4KICAgIDx0YWJsZSBjbGFzcz0idGJsIiBzdHlsZT0iZm9udC1zaXplOjExLjVweCI+CiAgICAgIDx0aGVhZD4KICAgICAgICA8dHIgc3R5bGU9ImJhY2tncm91bmQ6dmFyKC0tbmF2eSkiPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7d2lkdGg6NDAlO3BhZGRpbmc6N3B4IDEwcHgiPlByb2R1aXQ8L3RoPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7dGV4dC1hbGlnbjpjZW50ZXI7cGFkZGluZzo3cHggOHB4Ij5Ew6lqw6A8YnI+aW52ZXN0aTwvdGg+CiAgICAgICAgICA8dGggc3R5bGU9ImNvbG9yOnZhcigtLWdvbGQyKTt0ZXh0LWFsaWduOmNlbnRlcjtwYWRkaW5nOjdweCA4cHgiPlBhczxicj5kdSB0b3V0PC90aD4KICAgICAgICAgIDx0aCBzdHlsZT0iY29sb3I6dmFyKC0tZ29sZDIpO3RleHQtYWxpZ246Y2VudGVyO3BhZGRpbmc6N3B4IDhweCI+VW48YnI+cGV1PC90aD4KICAgICAgICAgIDx0aCBzdHlsZT0iY29sb3I6dmFyKC0tZ29sZDIpO3RleHQtYWxpZ246Y2VudGVyO3BhZGRpbmc6N3B4IDhweCI+QmllbjwvdGg+CiAgICAgICAgPC90cj4KICAgICAgPC90aGVhZD4KICAgICAgPHRib2R5PgogICAgICAgIDx0cj48dGQ+QWN0aW9ucyBvdSBPUENWTSDDoCBkb21pbmFudGUgYWN0aW9uczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tYWN0LWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWFjdCIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1hY3QiIHZhbHVlPSIyIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tYWN0IiB2YWx1ZT0iNCI+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+T2JsaWdhdGlvbnMgb3UgT1BDVk0gw6AgZG9taW5hbnRlIG9ibGlnYXRhaXJlczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tb2JsLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLW9ibCIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1vYmwiIHZhbHVlPSIyIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tb2JsIiB2YWx1ZT0iNCI+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+VGl0cmVzIGRlIHNvY2nDqXTDqXMgbm9uIGNvdMOpZXMgb3UgRklQLCBGQ1BJLCBGQ1BSPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1uY28taW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tbmNvIiB2YWx1ZT0iMCI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLW5jbyIgdmFsdWU9IjIiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1uY28iIHZhbHVlPSI0Ij48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5Qcm9kdWl0cyBtb27DqXRhaXJlcywgT1BDVk0gbW9uw6l0YWlyZSwgZm9uZHMgZXVyb3M8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImtuLW1vbi1pbnYiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1tb24iIHZhbHVlPSIwIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tbW9uIiB2YWx1ZT0iMiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLW1vbiIgdmFsdWU9IjQiPjwvdGQ+PC90cj4KICAgICAgICA8dHI+PHRkPk9QQ1ZNIGRpdmVyc2lmacOpPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1kaXYtaW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tZGl2IiB2YWx1ZT0iMCI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWRpdiIgdmFsdWU9IjIiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1kaXYiIHZhbHVlPSI0Ij48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5Qcm9kdWl0cyBzdHJ1Y3R1csOpczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tc3RyLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLXN0ciIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1zdHIiIHZhbHVlPSIyIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tc3RyIiB2YWx1ZT0iNCI+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+QXV0cmVzIChvcHRpb25zLCBnZXN0aW9uIGFsdGVybmF0aXZl4oCmKTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tYXV0LWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWF1dCIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1hdXQiIHZhbHVlPSIyIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tYXV0IiB2YWx1ZT0iNCI+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+UHJvZHVpdHMgYmFuY2FpcmVzIChsaXZyZXQsIFBFTOKApik8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImtuLWJhbi1pbnYiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1iYW4iIHZhbHVlPSIwIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tYmFuIiB2YWx1ZT0iMiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWJhbiIgdmFsdWU9IjQiPjwvdGQ+PC90cj4KICAgICAgICA8dHI+PHRkPkltbW9iaWxpZXIgKHLDqWVsLCBTQ1BJLCBEdWZsb3QsIExNTlAsIE9QQ0nigKYpPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1pbW0taW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24taW1tIiB2YWx1ZT0iMCI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWltbSIgdmFsdWU9IjIiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1pbW0iIHZhbHVlPSI0Ij48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5Bc3N1cmFuY2UtdmllLCBjb250cmF0IGRlIGNhcGl0YWxpc2F0aW9uPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1hdi1pbnYiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1hdiIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1hdiIgdmFsdWU9IjIiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1hdiIgdmFsdWU9IjQiPjwvdGQ+PC90cj4KICAgICAgICA8dHI+PHRkPk9ww6lyYXRpb24gZGUgZMOpZmlzY2FsaXNhdGlvbiBEb21Ub20gKEdpcmFyZGlu4oCmKTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tZG9tLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWRvbSIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1kb20iIHZhbHVlPSIyIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tZG9tIiB2YWx1ZT0iNCI+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+UEVFLCBQYXJ0aWNpcGF0aW9uLCBQZXJjb+KApjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tcGVlLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLXBlZSIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1wZWUiIHZhbHVlPSIyIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tcGVlIiB2YWx1ZT0iNCI+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+U0NJPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1zY2ktaW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tc2NpIiB2YWx1ZT0iMCI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLXNjaSIgdmFsdWU9IjIiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1zY2kiIHZhbHVlPSI0Ij48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5FVEYgLyB0cmFja2VyczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tZXRmLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWV0ZiIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1ldGYiIHZhbHVlPSIyIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tZXRmIiB2YWx1ZT0iNCI+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+UHJvZHVpdHMgZMOpcml2w6lzIChvcHRpb25zLCBmdXR1cmVzLCB3YXJyYW50cyk8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImtuLWRlci1pbnYiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1kZXIiIHZhbHVlPSIwIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tZGVyIiB2YWx1ZT0iMiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWRlciIgdmFsdWU9IjQiPjwvdGQ+PC90cj4KICAgICAgICA8dHIgc3R5bGU9ImJhY2tncm91bmQ6I2Y5ZjlmYiI+PHRkPkNyeXB0b2FjdGlmczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tY3J5LWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWNyeSIgdmFsdWU9IjAiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1jcnkiIHZhbHVlPSIyIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tY3J5IiB2YWx1ZT0iNCI+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+UHJvZHVpdHMgw6AgZWZmZXQgZGUgbGV2aWVyIC8gU1JEPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1sZXYtaW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ia24tbGV2IiB2YWx1ZT0iMCI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImtuLWxldiIgdmFsdWU9IjIiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJrbi1sZXYiIHZhbHVlPSI0Ij48L3RkPjwvdHI+CiAgICAgIDwvdGJvZHk+CiAgICA8L3RhYmxlPgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJjYXJkIiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxMnB4Ij4KICAgIDxkaXYgY2xhc3M9ImNhcmQtdGl0bGUiPkZvcm1hdGlvbiBldCBleHDDqXJpZW5jZSBwcm9mZXNzaW9ubmVsbGU8L2Rpdj4KICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JpZCI+CiAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Gb3JtYXRpb24gb3UgZGlwbMO0bWUgZW4gZmluYW5jZSAvIMOpY29ub21pZSAvIGdlc3Rpb24gPzwvbGFiZWw+CiAgICAgICAgPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2dhcDoxNHB4O21hcmdpbi10b3A6NnB4Ij4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0IiBzdHlsZT0iZGlzcGxheTppbmxpbmUtZmxleDt3aWR0aDphdXRvIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImZvcm1hdGlvbl9maW4iIHZhbHVlPSI1Ij4gT3VpPC9sYWJlbD4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0IiBzdHlsZT0iZGlzcGxheTppbmxpbmUtZmxleDt3aWR0aDphdXRvIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImZvcm1hdGlvbl9maW4iIHZhbHVlPSIwIj4gTm9uPC9sYWJlbD4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Qcm9mZXNzaW9uIGFjdHVlbGxlIG91IHBhc3PDqWUgZGFucyBsZSBzZWN0ZXVyIGZpbmFuY2llciA/PC9sYWJlbD4KICAgICAgICA8ZGl2IHN0eWxlPSJkaXNwbGF5OmZsZXg7Z2FwOjE0cHg7bWFyZ2luLXRvcDo2cHgiPgogICAgICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiIHN0eWxlPSJkaXNwbGF5OmlubGluZS1mbGV4O3dpZHRoOmF1dG8iPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iZXhwX3Byb19maW4iIHZhbHVlPSI1Ij4gT3VpPC9sYWJlbD4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0IiBzdHlsZT0iZGlzcGxheTppbmxpbmUtZmxleDt3aWR0aDphdXRvIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImV4cF9wcm9fZmluIiB2YWx1ZT0iMCI+IE5vbjwvbGFiZWw+CiAgICAgICAgPC9kaXY+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIGZvcm0tZnVsbCI+PGxhYmVsPkRlcHVpcyBjb21iaWVuIGRlIHRlbXBzIGludmVzdGlzc2V6LXZvdXMgc3VyIGxlcyBtYXJjaMOpcyBmaW5hbmNpZXJzID88L2xhYmVsPgogICAgICAgIDxkaXYgc3R5bGU9ImRpc3BsYXk6ZmxleDtnYXA6OHB4O2ZsZXgtd3JhcDp3cmFwO21hcmdpbi10b3A6NnB4Ij4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFuY2llbm5ldGVfaW52ZXN0IiB2YWx1ZT0iMCI+IEphbWFpcyBpbnZlc3RpPC9sYWJlbD4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFuY2llbm5ldGVfaW52ZXN0IiB2YWx1ZT0iNSI+IE1vaW5zIGRlIDIgYW5zPC9sYWJlbD4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFuY2llbm5ldGVfaW52ZXN0IiB2YWx1ZT0iMTAiPiAyIMOgIDUgYW5zPC9sYWJlbD4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFuY2llbm5ldGVfaW52ZXN0IiB2YWx1ZT0iMTUiPiA1IMOgIDEwIGFuczwvbGFiZWw+CiAgICAgICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhbmNpZW5uZXRlX2ludmVzdCIgdmFsdWU9IjIwIj4gUGx1cyBkZSAxMCBhbnM8L2xhYmVsPgogICAgICAgIDwvZGl2PgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJjYXJkIiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxMnB4Ij4KICAgIDxkaXYgY2xhc3M9ImNhcmQtdGl0bGUiPkRhbnMgbGUgcGFzc8OpLCBsYSBnZXN0aW9uIGRlIG1lcyBhdm9pcnPigKY8L2Rpdj4KICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9Imdlc3Rpb25fcGFzc2UiIHZhbHVlPSI1Ij4gQSDDqXTDqSBkw6lsw6lndcOpZSDDoCB1biBnZXN0aW9ubmFpcmUgKGdlc3Rpb24gc291cyBtYW5kYXQpPC9sYWJlbD4KICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9Imdlc3Rpb25fcGFzc2UiIHZhbHVlPSIyMCI+IEEgw6l0w6kgZ8OpcsOpZSBwYXIgbW9pLW3Dqm1lIHNhbnMgbCdhaWRlIGQndW4gY29uc2VpbGxlcjwvbGFiZWw+CiAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJnZXN0aW9uX3Bhc3NlIiB2YWx1ZT0iMTAiPiBBIMOpdMOpIGfDqXLDqWUgcGFyIG1vaS1tw6ptZSBhdmVjIGwnYWlkZSBkJ3VuIGNvbnNlaWxsZXI8L2xhYmVsPgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJjYXJkIiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxMnB4Ij4KICAgIDxkaXYgY2xhc3M9ImNhcmQtdGl0bGUiPkZyw6lxdWVuY2UgZXQgdm9sdW1lIGRlIHZvcyBvcMOpcmF0aW9ucyAoMTIgZGVybmllcnMgbW9pcyk8L2Rpdj4KICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JpZCI+CiAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Ob21icmUgZGUgdHJhbnNhY3Rpb25zIHN1ciBwcm9kdWl0cyBmaW5hbmNpZXJzIHJpc3F1w6lzPC9sYWJlbD4KICAgICAgICA8ZGl2IHN0eWxlPSJtYXJnaW4tdG9wOjZweCI+CiAgICAgICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJmcmVxX3RyYW5zIiB2YWx1ZT0iMCI+IEF1Y3VuZTwvbGFiZWw+CiAgICAgICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJmcmVxX3RyYW5zIiB2YWx1ZT0iNSI+IDEgw6AgNTwvbGFiZWw+CiAgICAgICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJmcmVxX3RyYW5zIiB2YWx1ZT0iMTAiPiA2IMOgIDIwPC9sYWJlbD4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImZyZXFfdHJhbnMiIHZhbHVlPSIxNSI+IFBsdXMgZGUgMjA8L2xhYmVsPgogICAgICAgIDwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPk1vbnRhbnQgbW95ZW4gaW52ZXN0aSBwYXIgb3DDqXJhdGlvbjwvbGFiZWw+CiAgICAgICAgPGRpdiBzdHlsZT0ibWFyZ2luLXRvcDo2cHgiPgogICAgICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ibW9udGFudF9tb3kiIHZhbHVlPSIwIj4gTW9pbnMgZGUgNSAwMDAg4oKsPC9sYWJlbD4KICAgICAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9Im1vbnRhbnRfbW95IiB2YWx1ZT0iNCI+IDUgMDAwIMOgIDIwIDAwMCDigqw8L2xhYmVsPgogICAgICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ibW9udGFudF9tb3kiIHZhbHVlPSI4Ij4gMjAgMDAwIMOgIDUwIDAwMCDigqw8L2xhYmVsPgogICAgICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0ibW9udGFudF9tb3kiIHZhbHVlPSIxMyI+IFBsdXMgZGUgNTAgMDAwIOKCrDwvbGFiZWw+CiAgICAgICAgPC9kaXY+CiAgICAgIDwvZGl2PgogICAgPC9kaXY+CiAgPC9kaXY+CgogIDxkaXYgY2xhc3M9ImNhcmQiIHN0eWxlPSJtYXJnaW4tYm90dG9tOjEycHgiPgogICAgPGRpdiBjbGFzcz0iY2FyZC10aXRsZSI+Vm90cmUgaW5mb3JtYXRpb27igKY8L2Rpdj4KICAgIDx0YWJsZSBjbGFzcz0idGJsIiBzdHlsZT0iZm9udC1zaXplOjExLjVweCI+CiAgICAgIDx0aGVhZD4KICAgICAgICA8dHIgc3R5bGU9ImJhY2tncm91bmQ6dmFyKC0tbmF2eSkiPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7d2lkdGg6NjUlO3BhZGRpbmc6N3B4IDEwcHgiPkplIG0naW5mb3JtZeKApjwvdGg+CiAgICAgICAgICA8dGggc3R5bGU9ImNvbG9yOnZhcigtLWdvbGQyKTt0ZXh0LWFsaWduOmNlbnRlcjtwYWRkaW5nOjdweCA4cHgiPk91aTwvdGg+CiAgICAgICAgICA8dGggc3R5bGU9ImNvbG9yOnZhcigtLWdvbGQyKTt0ZXh0LWFsaWduOmNlbnRlcjtwYWRkaW5nOjdweCA4cHgiPlVuIHBldTxicj5tb2lucyBzb3V2ZW50PC90aD4KICAgICAgICAgIDx0aCBzdHlsZT0iY29sb3I6dmFyKC0tZ29sZDIpO3RleHQtYWxpZ246Y2VudGVyO3BhZGRpbmc6N3B4IDhweCI+SmFtYWlzPC90aD4KICAgICAgICA8L3RyPgogICAgICA8L3RoZWFkPgogICAgICA8dGJvZHk+CiAgICAgICAgPHRyPjx0ZD5KZSBsaXMgbGEgcHJlc3NlIHNww6ljaWFsaXPDqWUgY29uY2VybmFudCBtZXMgcHJvZHVpdHMgZCfDqXBhcmduZTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJpbmYxIiB2YWx1ZT0iMTUiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJpbmYxIiB2YWx1ZT0iOCI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImluZjEiIHZhbHVlPSIwIj48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5KZSBtJ2luZm9ybWUgZGUgbGEgdmFsZXVyIGRlIG1lcyBwbGFjZW1lbnRzIGZpbmFuY2llcnMgYXUgbW9pbnMgdG91cyBsZXMgbW9pczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJpbmYyIiB2YWx1ZT0iMTUiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJpbmYyIiB2YWx1ZT0iOCI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImluZjIiIHZhbHVlPSIwIj48L3RkPjwvdHI+CiAgICAgICAgPHRyPjx0ZD5KZSBtJ2luZm9ybWUgZGUgbGEgdmFsZXVyIGRlIG1lcyBwbGFjZW1lbnRzIGltbW9iaWxpZXJzIGF1IG1vaW5zIHRvdXMgbGVzIGFuczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJpbmYzIiB2YWx1ZT0iMTUiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJpbmYzIiB2YWx1ZT0iOCI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImluZjMiIHZhbHVlPSIwIj48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5KZSByZWdhcmRlIG1vbiByZWxldsOpIGJhbmNhaXJlIGF1IG1vaW5zIHRvdXMgbGVzIG1vaXM8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iaW5mNCIgdmFsdWU9IjE1Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iaW5mNCIgdmFsdWU9IjgiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJpbmY0IiB2YWx1ZT0iMCI+PC90ZD48L3RyPgogICAgICA8L3Rib2R5PgogICAgPC90YWJsZT4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0iY2FyZCIgc3R5bGU9Im1hcmdpbi1ib3R0b206MTJweCI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkLXRpdGxlIj5RdWVscXVlcyBhZmZpcm1hdGlvbnPigKYgKFZyYWkgPSAxIHB0IC8gRmF1eCA9IDAgcHQpPC9kaXY+CiAgICA8dGFibGUgY2xhc3M9InRibCIgc3R5bGU9ImZvbnQtc2l6ZToxMS41cHgiPgogICAgICA8dGhlYWQ+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOnZhcigtLW5hdnkpIj4KICAgICAgICAgIDx0aCBzdHlsZT0iY29sb3I6dmFyKC0tZ29sZDIpO3dpZHRoOjgwJTtwYWRkaW5nOjdweCAxMHB4Ij5BZmZpcm1hdGlvbjwvdGg+CiAgICAgICAgICA8dGggc3R5bGU9ImNvbG9yOnZhcigtLWdvbGQyKTt0ZXh0LWFsaWduOmNlbnRlcjtwYWRkaW5nOjdweCA4cHgiPlZyYWk8YnI+KDFwdCk8L3RoPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7dGV4dC1hbGlnbjpjZW50ZXI7cGFkZGluZzo3cHggOHB4Ij5GYXV4PGJyPigwcHQpPC90aD4KICAgICAgICA8L3RyPgogICAgICA8L3RoZWFkPgogICAgICA8dGJvZHk+CiAgICAgICAgPHRyPjx0ZD5MYSB2ZW50ZSBkYW5zIGwndXJnZW5jZSBkZXMgw6lsw6ltZW50cyBkZSBtb24gcGF0cmltb2luZSBwZXV0IG0nYW1lbmVyIMOgIHN1YmlyIHVuZSBtb2lucy12YWx1ZTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhZmYxIiB2YWx1ZT0iMSI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFmZjEiIHZhbHVlPSIwIj48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5QbHVzIHVuIHByb2R1aXQgZXN0IHJpc3F1w6ksIHBsdXMgc2EgdmFsZXVyIGV0IHNhIHBlcmZvcm1hbmNlIHBldXZlbnQgdmFyaWVyIGZvcnRlbWVudCDDoCBsYSBoYXVzc2UgY29tbWUgw6AgbGEgYmFpc3NlPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFmZjIiIHZhbHVlPSIxIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmMiIgdmFsdWU9IjAiPjwvdGQ+PC90cj4KICAgICAgICA8dHI+PHRkPk1vaW5zIG1vbiBwYXRyaW1vaW5lIGVzdCBkaXZlcnNpZmnDqSwgcGx1cyBpbCBlc3QgZXhwb3PDqSBhdXggcmlzcXVlcyBkZSB2YXJpYXRpb24gZCd1bmUgdmFsZXVyPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFmZjMiIHZhbHVlPSIxIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmMyIgdmFsdWU9IjAiPjwvdGQ+PC90cj4KICAgICAgICA8dHIgc3R5bGU9ImJhY2tncm91bmQ6I2Y5ZjlmYiI+PHRkPlRvdXQgcHJvZHVpdCBkJ8OpcGFyZ25lIHBldXQgcHLDqXNlbnRlciB1biBvdSBwbHVzaWV1cnMgcmlzcXVlcyBhdXRyZXMgcXUndW5lIHZhcmlhdGlvbiBkZSBzYSB2YWxldXIgKHJlcXVhbGlmaWNhdGlvbiBmaXNjYWxlLCBub24tbGlxdWlkaXTDqeKApik8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmNCIgdmFsdWU9IjEiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhZmY0IiB2YWx1ZT0iMCI+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+UG91ciB1biBtw6ptZSBwbGFjZW1lbnQsIGxlIHJpc3F1ZSBlc3QgZGlmZsOpcmVudCBzZWxvbiBsJ8OpY2jDqWFuY2UgKDEgYW4sIDUgYW5zLCAxMCBhbnMpPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFmZjUiIHZhbHVlPSIxIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmNSIgdmFsdWU9IjAiPjwvdGQ+PC90cj4KICAgICAgICA8dHIgc3R5bGU9ImJhY2tncm91bmQ6I2Y5ZjlmYiI+PHRkPkxhIHN0cnVjdHVyZSBkZSBtb24gcGF0cmltb2luZSwgZGFucyBsZSB0ZW1wcyBldCBlbiBwcmVuYW50IGVuIGNvbXB0ZSBsZXMgcmlzcXVlcyBsacOpcyDDoCBjaGFxdWUgYWN0aWYsIGRvaXQgw6p0cmUgY29ow6lyZW50ZSBhdmVjIG1lcyBvYmplY3RpZnM8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmNiIgdmFsdWU9IjEiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhZmY2IiB2YWx1ZT0iMCI+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+TGVzIHByb2R1aXRzIGTDqXJpdsOpcyAob3B0aW9ucywgZnV0dXJlcykgcGV1dmVudCBlbnRyYcOubmVyIGRlcyBwZXJ0ZXMgc3Vww6lyaWV1cmVzIGF1IGNhcGl0YWwgaW52ZXN0aTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhZmY3IiB2YWx1ZT0iMSI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFmZjciIHZhbHVlPSIwIj48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5VbiBpbnZlc3Rpc3NlbWVudCBsaWJlbGzDqSBlbiBkZXZpc2Ugw6l0cmFuZ8OocmUgbSdleHBvc2Ugw6AgdW4gcmlzcXVlIGRlIGNoYW5nZSBpbmTDqXBlbmRhbnQgZGUgbGEgcGVyZm9ybWFuY2UgZHUgcHJvZHVpdCBsdWktbcOqbWU8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmOCIgdmFsdWU9IjEiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhZmY4IiB2YWx1ZT0iMCI+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+VW4gcHJvZHVpdCBwZXUgbGlxdWlkZSBwZXV0IMOqdHJlIGRpZmZpY2lsZSDDoCByZXZlbmRyZSByYXBpZGVtZW50LCBvdSBzZXVsZW1lbnQgYXZlYyB1bmUgZMOpY290ZTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhZmY5IiB2YWx1ZT0iMSI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9ImFmZjkiIHZhbHVlPSIwIj48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5FbiBjYXMgZGUgZMOpZmFpbGxhbmNlIGRlIGwnw6ltZXR0ZXVyIGQndW4gcHJvZHVpdCBzdHJ1Y3R1csOpLCBqZSBwZXV4IHBlcmRyZSB0b3V0IG91IHBhcnRpZSBkZSBtb24gY2FwaXRhbCAocmlzcXVlIGRlIGNvbnRyZXBhcnRpZSk8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmMTAiIHZhbHVlPSIxIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmMTAiIHZhbHVlPSIwIj48L3RkPjwvdHI+CiAgICAgICAgPHRyPjx0ZD5MJ2VmZmV0IGRlIGxldmllciBhbXBsaWZpZSBhdXNzaSBiaWVuIGxlcyBnYWlucyBwb3RlbnRpZWxzIHF1ZSBsZXMgcGVydGVzIHBvdGVudGllbGxlczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhZmYxMSIgdmFsdWU9IjEiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJhZmYxMSIgdmFsdWU9IjAiPjwvdGQ+PC90cj4KICAgICAgICA8dHIgc3R5bGU9ImJhY2tncm91bmQ6I2Y5ZjlmYiI+PHRkPkxlcyBjcnlwdG9hY3RpZnMgcHLDqXNlbnRlbnQgdW5lIHZvbGF0aWxpdMOpIGV0IGRlcyByaXNxdWVzIHNpZ25pZmljYXRpdmVtZW50IHN1cMOpcmlldXJzIMOgIGNldXggZGVzIGFjdGlvbnM8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmMTIiIHZhbHVlPSIxIj48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0iYWZmMTIiIHZhbHVlPSIwIj48L3RkPjwvdHI+CiAgICAgIDwvdGJvZHk+CiAgICA8L3RhYmxlPgogIDwvZGl2PgoKICA8IS0tIFNjb3JlIGNvbm5haXNzYW5jZSAtLT4KICA8ZGl2IGNsYXNzPSJjYXJkIiBzdHlsZT0iYmFja2dyb3VuZDp2YXIoLS1jcmVhbTIpO2JvcmRlcjpub25lO21hcmdpbi1ib3R0b206MTJweCI+CiAgICA8ZGl2IHN0eWxlPSJkaXNwbGF5OmZsZXg7YWxpZ24taXRlbXM6Y2VudGVyO2dhcDoxNnB4O2ZsZXgtd3JhcDp3cmFwIj4KICAgICAgPGRpdiBzdHlsZT0iZmxleDoxIj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTFweDtjb2xvcjp2YXIoLS1tdXRlZCk7dGV4dC10cmFuc2Zvcm06dXBwZXJjYXNlO2xldHRlci1zcGFjaW5nOi40cHg7bWFyZ2luLWJvdHRvbTo0cHgiPlNjb3JlIGNvbm5haXNzYW5jZTwvZGl2PgogICAgICAgIDxkaXYgaWQ9InEtc2NvcmUtdmFsIiBzdHlsZT0iZm9udC1zaXplOjIycHg7Zm9udC13ZWlnaHQ6NzAwO2NvbG9yOnZhcigtLW5hdnkpIj7igJQ8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgc3R5bGU9ImZsZXg6MSI+CiAgICAgICAgPGRpdiBzdHlsZT0iZm9udC1zaXplOjExcHg7Y29sb3I6dmFyKC0tbXV0ZWQpO3RleHQtdHJhbnNmb3JtOnVwcGVyY2FzZTtsZXR0ZXItc3BhY2luZzouNHB4O21hcmdpbi1ib3R0b206NHB4Ij5DYXTDqWdvcmllIEFNRjwvZGl2PgogICAgICAgIDxkaXYgaWQ9InEtcHJvZmlsLXZhbCIgc3R5bGU9ImZvbnQtc2l6ZToxNnB4O2ZvbnQtd2VpZ2h0OjcwMDtjb2xvcjp2YXIoLS1uYXZ5KSI+4oCUPC9kaXY+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IHN0eWxlPSJmbGV4OjEiPgogICAgICAgIDxkaXYgc3R5bGU9ImZvbnQtc2l6ZToxMXB4O2NvbG9yOnZhcigtLW11dGVkKTt0ZXh0LXRyYW5zZm9ybTp1cHBlcmNhc2U7bGV0dGVyLXNwYWNpbmc6LjRweDttYXJnaW4tYm90dG9tOjRweCI+QmFyw6htZSA6IDgxLTEyNSA9IEJhc2UgwrcgMTI2LTE3MSA9IEF2ZXJ0aSDCtyAxNzItMjE4ID0gQXZhbmPDqTwvZGl2PgogICAgICAgIDxidXR0b24gY2xhc3M9ImJ0biBicDIgYnNtIiBvbmNsaWNrPSJjYWxjU2NvcmUoKSI+Q2FsY3VsZXIgbGUgc2NvcmU8L2J1dHRvbj4KICAgICAgPC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1uYXYtYnRucyIgc3R5bGU9ImRpc3BsYXk6ZmxleDtqdXN0aWZ5LWNvbnRlbnQ6ZmxleC1lbmQ7bWFyZ2luLXRvcDoxNnB4Ij4KICAgIDxidXR0b24gY2xhc3M9ImJ0biBicDIiIG9uY2xpY2s9ImdvQ29ubmFpc3NhbmNlKDQpIj5TdWl2YW50IOKGkiDDiXZhbHVhdGlvbiBkdSByaXNxdWU8L2J1dHRvbj4KICA8L2Rpdj4KPC9kaXY+Cgo8IS0tIOKVkOKVkOKVkCBTRUNUSU9OIDQgOiDDiVZBTFVBVElPTiBEVSBSSVNRVUUg4pWQ4pWQ4pWQIC0tPgo8ZGl2IGlkPSJwczQiIHN0eWxlPSJkaXNwbGF5Om5vbmUiPgogIDxkaXYgY2xhc3M9InNlY3Rpb24taGVhZGVyIj48aDI+RCDigJQgw4l2YWx1YXRpb24gZHUgcmlzcXVlPC9oMj48L2Rpdj4KICA8ZGl2IGNsYXNzPSJpbmZvLWJveCI+SidhY2NlcHRlIHVuZSBmbHVjdHVhdGlvbiBkZSBsYSB2YWxldXIgZGUgbCdFTlNFTUJMRSBkZSBtb24gcGF0cmltb2luZSDDoCBsYSBoYXVzc2UgY29tbWUgw6AgbGEgYmFpc3NlLjwvZGl2PgoKICA8IS0tIEdSQVBISVFVRSBSRU5ERU1FTlQvUklTUVVFIC0tPgogIDxkaXYgY2xhc3M9ImNhcmQiIHN0eWxlPSJtYXJnaW4tYm90dG9tOjEycHgiPgogICAgPGRpdiBjbGFzcz0iY2FyZC10aXRsZSI+R3JhcGhpcXVlIFJlbmRlbWVudCAvIFJpc3F1ZSDigJQgU8OpbGVjdGlvbm5leiB2b3RyZSBwcm9maWw8L2Rpdj4KICAgIDxkaXYgc3R5bGU9ImRpc3BsYXk6Z3JpZDtncmlkLXRlbXBsYXRlLWNvbHVtbnM6MWZyIDFmcjtnYXA6MTZweDthbGlnbi1pdGVtczpjZW50ZXIiPgogICAgICA8c3ZnIHZpZXdCb3g9IjAgMCAzODAgMjQwIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJ3aWR0aDoxMDAlO21heC13aWR0aDo0MjBweCI+CiAgICAgICAgPHJlY3Qgd2lkdGg9IjM4MCIgaGVpZ2h0PSIyNDAiIGZpbGw9IiNmOWY5ZmIiIHJ4PSI2Ii8+CiAgICAgICAgPGxpbmUgeDE9IjQ0IiB5MT0iMjA4IiB4Mj0iMzY4IiB5Mj0iMjA4IiBzdHJva2U9IiNjOGNkZDYiIHN0cm9rZS13aWR0aD0iMS41Ii8+CiAgICAgICAgPGxpbmUgeDE9IjQ0IiB5MT0iMjA4IiB4Mj0iNDQiIHkyPSIxNiIgc3Ryb2tlPSIjYzhjZGQ2IiBzdHJva2Utd2lkdGg9IjEuNSIvPgogICAgICAgIDx0ZXh0IHg9IjIwNiIgeT0iMjMwIiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmaWxsPSIjNWE2YTdhIiBmb250LXNpemU9IjEwIj5SaXNxdWUg4oaSPC90ZXh0PgogICAgICAgIDx0ZXh0IHg9IjE0IiB5PSIxMTIiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZpbGw9IiM1YTZhN2EiIGZvbnQtc2l6ZT0iMTAiIHRyYW5zZm9ybT0icm90YXRlKC05MCwxNCwxMTIpIj5SZW5kZW1lbnQg4oaSPC90ZXh0PgogICAgICAgIDxwYXRoIGQ9Ik0gNTUgMjAwIFEgMTEwIDE3MiAxNjggMTM2IFEgMjI4IDk2IDI5OCA1NiBRIDMyOCA0MiAzNTggMzIiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI0M5QTg0QyIgc3Ryb2tlLXdpZHRoPSIyLjUiIHN0cm9rZS1kYXNoYXJyYXk9IjYsMyIvPgogICAgICAgIDxwYXRoIGQ9Ik0gNTUgMjAwIFEgMTEwIDE3MiAxNjggMTM2IFEgMjI4IDk2IDI5OCA1NiBRIDMyOCA0MiAzNTggMzIgTCAzNTggMjA4IFoiIGZpbGw9InJnYmEoMjAxLDE2OCw3NiwwLjA3KSIvPgogICAgICAgIDwhLS0gU1IgLS0+CiAgICAgICAgPGNpcmNsZSBjeD0iODIiIGN5PSIxOTUiIHI9IjEzIiBmaWxsPSIjMjdhZTYwIiBvcGFjaXR5PSIwLjkiIHN0eWxlPSJjdXJzb3I6cG9pbnRlciIgb25jbGljaz0ic2VsZWN0UHJvZmlsZUZyb21DaGFydCgnc2VjdXJpdGUnKSIvPgogICAgICAgIDx0ZXh0IHg9IjgyIiB5PSIxOTkiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZpbGw9IndoaXRlIiBmb250LXNpemU9IjgiIGZvbnQtd2VpZ2h0PSJib2xkIj5TUjwvdGV4dD4KICAgICAgICA8IS0tIFAgLS0+CiAgICAgICAgPGNpcmNsZSBjeD0iMTU1IiBjeT0iMTU4IiByPSIxNCIgZmlsbD0iIzI5NTFhMyIgb3BhY2l0eT0iMC45IiBzdHlsZT0iY3Vyc29yOnBvaW50ZXIiIG9uY2xpY2s9InNlbGVjdFByb2ZpbGVGcm9tQ2hhcnQoJ3BydWRlbnQnKSIvPgogICAgICAgIDx0ZXh0IHg9IjE1NSIgeT0iMTYyIiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmaWxsPSJ3aGl0ZSIgZm9udC1zaXplPSI5IiBmb250LXdlaWdodD0iYm9sZCI+UDwvdGV4dD4KICAgICAgICA8IS0tIEUgLS0+CiAgICAgICAgPGNpcmNsZSBjeD0iMjM4IiBjeT0iMTEyIiByPSIxNCIgZmlsbD0iI2U2N2UyMiIgb3BhY2l0eT0iMC45IiBzdHlsZT0iY3Vyc29yOnBvaW50ZXIiIG9uY2xpY2s9InNlbGVjdFByb2ZpbGVGcm9tQ2hhcnQoJ2VxdWlsaWJyZScpIi8+CiAgICAgICAgPHRleHQgeD0iMjM4IiB5PSIxMTYiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZpbGw9IndoaXRlIiBmb250LXNpemU9IjkiIGZvbnQtd2VpZ2h0PSJib2xkIj5FPC90ZXh0PgogICAgICAgIDwhLS0gRCAtLT4KICAgICAgICA8Y2lyY2xlIGN4PSIzMjIiIGN5PSI2MiIgcj0iMTQiIGZpbGw9IiNjMDM5MmIiIG9wYWNpdHk9IjAuOSIgc3R5bGU9ImN1cnNvcjpwb2ludGVyIiBvbmNsaWNrPSJzZWxlY3RQcm9maWxlRnJvbUNoYXJ0KCdkeW5hbWlxdWUnKSIvPgogICAgICAgIDx0ZXh0IHg9IjMyMiIgeT0iNjYiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZpbGw9IndoaXRlIiBmb250LXNpemU9IjkiIGZvbnQtd2VpZ2h0PSJib2xkIj5EPC90ZXh0PgogICAgICAgIDxjaXJjbGUgaWQ9InJpc2staW5kaWNhdG9yIiBjeD0iLTUwIiBjeT0iLTUwIiByPSIyMCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMEExNjI4IiBzdHJva2Utd2lkdGg9IjMiIHN0cm9rZS1kYXNoYXJyYXk9IjQsMiIgb3BhY2l0eT0iMC44Ii8+CiAgICAgIDwvc3ZnPgogICAgICA8ZGl2PgogICAgICAgIDxkaXYgc3R5bGU9ImRpc3BsYXk6ZmxleDtmbGV4LWRpcmVjdGlvbjpjb2x1bW47Z2FwOjhweCI+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJyaXNrLWNhcmQiIGRhdGEtcHJvZmlsZT0ic2VjdXJpdGUiIG9uY2xpY2s9InNlbGVjdFJpc2tQcm9maWxlKHRoaXMpIiBzdHlsZT0iYm9yZGVyOjJweCBzb2xpZCAjZTRlN2VmO2JvcmRlci1yYWRpdXM6OHB4O3BhZGRpbmc6MTBweCAxMnB4O2N1cnNvcjpwb2ludGVyO2Rpc3BsYXk6ZmxleDthbGlnbi1pdGVtczpjZW50ZXI7Z2FwOjEwcHgiPgogICAgICAgICAgICA8ZGl2IHN0eWxlPSJ3aWR0aDoxMHB4O2hlaWdodDoxMHB4O2JhY2tncm91bmQ6IzI3YWU2MDtib3JkZXItcmFkaXVzOjUwJTtmbGV4LXNocmluazowIj48L2Rpdj4KICAgICAgICAgICAgPGRpdj48ZGl2IHN0eWxlPSJmb250LXdlaWdodDo3MDA7Y29sb3I6IzI3YWU2MDtmb250LXNpemU6MTEuNXB4Ij5Tw4lDVVJJVMOJIChTUik8L2Rpdj48ZGl2IHN0eWxlPSJmb250LXNpemU6MTBweDtjb2xvcjp2YXIoLS1tdXRlZCkiPlZvbGF0aWxpdMOpIHRyw6hzIGZhaWJsZSDCtyBSaXNxdWUgMS0yLzc8L2Rpdj48L2Rpdj4KICAgICAgICAgIDwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0icmlzay1jYXJkIiBkYXRhLXByb2ZpbGU9InBydWRlbnQiIG9uY2xpY2s9InNlbGVjdFJpc2tQcm9maWxlKHRoaXMpIiBzdHlsZT0iYm9yZGVyOjJweCBzb2xpZCAjZTRlN2VmO2JvcmRlci1yYWRpdXM6OHB4O3BhZGRpbmc6MTBweCAxMnB4O2N1cnNvcjpwb2ludGVyO2Rpc3BsYXk6ZmxleDthbGlnbi1pdGVtczpjZW50ZXI7Z2FwOjEwcHgiPgogICAgICAgICAgICA8ZGl2IHN0eWxlPSJ3aWR0aDoxMHB4O2hlaWdodDoxMHB4O2JhY2tncm91bmQ6IzI5NTFhMztib3JkZXItcmFkaXVzOjUwJTtmbGV4LXNocmluazowIj48L2Rpdj4KICAgICAgICAgICAgPGRpdj48ZGl2IHN0eWxlPSJmb250LXdlaWdodDo3MDA7Y29sb3I6IzI5NTFhMztmb250LXNpemU6MTEuNXB4Ij5QUlVERU5UIChQKTwvZGl2PjxkaXYgc3R5bGU9ImZvbnQtc2l6ZToxMHB4O2NvbG9yOnZhcigtLW11dGVkKSI+VmFyaWF0aW9uIG1vZMOpcsOpZSDCtyBSaXNxdWUgMy00Lzc8L2Rpdj48L2Rpdj4KICAgICAgICAgIDwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0icmlzay1jYXJkIiBkYXRhLXByb2ZpbGU9ImVxdWlsaWJyZSIgb25jbGljaz0ic2VsZWN0Umlza1Byb2ZpbGUodGhpcykiIHN0eWxlPSJib3JkZXI6MnB4IHNvbGlkICNlNGU3ZWY7Ym9yZGVyLXJhZGl1czo4cHg7cGFkZGluZzoxMHB4IDEycHg7Y3Vyc29yOnBvaW50ZXI7ZGlzcGxheTpmbGV4O2FsaWduLWl0ZW1zOmNlbnRlcjtnYXA6MTBweCI+CiAgICAgICAgICAgIDxkaXYgc3R5bGU9IndpZHRoOjEwcHg7aGVpZ2h0OjEwcHg7YmFja2dyb3VuZDojZTY3ZTIyO2JvcmRlci1yYWRpdXM6NTAlO2ZsZXgtc2hyaW5rOjAiPjwvZGl2PgogICAgICAgICAgICA8ZGl2PjxkaXYgc3R5bGU9ImZvbnQtd2VpZ2h0OjcwMDtjb2xvcjojZTY3ZTIyO2ZvbnQtc2l6ZToxMS41cHgiPsOJUVVJTElCUsOJIChFKTwvZGl2PjxkaXYgc3R5bGU9ImZvbnQtc2l6ZToxMHB4O2NvbG9yOnZhcigtLW11dGVkKSI+Vm9sYXRpbGl0w6kgbW95ZW5uZSDCtyBSaXNxdWUgNS83PC9kaXY+PC9kaXY+CiAgICAgICAgICA8L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9InJpc2stY2FyZCIgZGF0YS1wcm9maWxlPSJkeW5hbWlxdWUiIG9uY2xpY2s9InNlbGVjdFJpc2tQcm9maWxlKHRoaXMpIiBzdHlsZT0iYm9yZGVyOjJweCBzb2xpZCAjZTRlN2VmO2JvcmRlci1yYWRpdXM6OHB4O3BhZGRpbmc6MTBweCAxMnB4O2N1cnNvcjpwb2ludGVyO2Rpc3BsYXk6ZmxleDthbGlnbi1pdGVtczpjZW50ZXI7Z2FwOjEwcHgiPgogICAgICAgICAgICA8ZGl2IHN0eWxlPSJ3aWR0aDoxMHB4O2hlaWdodDoxMHB4O2JhY2tncm91bmQ6I2MwMzkyYjtib3JkZXItcmFkaXVzOjUwJTtmbGV4LXNocmluazowIj48L2Rpdj4KICAgICAgICAgICAgPGRpdj48ZGl2IHN0eWxlPSJmb250LXdlaWdodDo3MDA7Y29sb3I6I2MwMzkyYjtmb250LXNpemU6MTEuNXB4Ij5EWU5BTUlRVUUgKEQpPC9kaXY+PGRpdiBzdHlsZT0iZm9udC1zaXplOjEwcHg7Y29sb3I6dmFyKC0tbXV0ZWQpIj5Gb3J0ZSB2b2xhdGlsaXTDqSDCtyBSaXNxdWUgNi03Lzc8L2Rpdj48L2Rpdj4KICAgICAgICAgIDwvZGl2PgogICAgICAgIDwvZGl2PgogICAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi10b3A6MTBweDtwYWRkaW5nOjhweCAxMnB4O2JhY2tncm91bmQ6dmFyKC0tY3JlYW0yKTtib3JkZXItcmFkaXVzOjZweDtmb250LXNpemU6MTJweCI+CiAgICAgICAgICA8c3Ryb25nPlByb2ZpbCBzw6lsZWN0aW9ubsOpIDo8L3N0cm9uZz4gPHNwYW4gaWQ9InJpc2stc2VsZWN0ZWQiIHN0eWxlPSJmb250LXdlaWdodDo3MDA7Y29sb3I6dmFyKC0tbmF2eSkiPuKAlCDDgCBzw6lsZWN0aW9ubmVyPC9zcGFuPgogICAgICAgIDwvZGl2PgogICAgICAgIDxpbnB1dCB0eXBlPSJoaWRkZW4iIGlkPSJyaXNrLXByb2ZpbGUtdmFsdWUiIHZhbHVlPSIiPgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8IS0tIFFVRVNUSU9OUyBDT01QT1JURU1FTlRBTEVTIC0tPgogIDxkaXYgY2xhc3M9ImNhcmQiIHN0eWxlPSJtYXJnaW4tYm90dG9tOjEycHgiPgogICAgPGRpdiBjbGFzcz0iY2FyZC10aXRsZSI+UXVlc3Rpb25zIGNvbXBvcnRlbWVudGFsZXM8L2Rpdj4KCiAgICA8ZGl2IHN0eWxlPSJtYXJnaW4tYm90dG9tOjE0cHgiPgogICAgICA8cCBzdHlsZT0iZm9udC1zaXplOjEycHg7Zm9udC13ZWlnaHQ6NjAwO2NvbG9yOnZhcigtLW5hdnkpO21hcmdpbi1ib3R0b206OHB4Ij4xLiBTaSBkZW1haW4sIGxhIHZhbGV1ciBkZSBtb24gcGxhY2VtZW50IHZlbmFpdCDDoCBjaHV0ZXIgZGUgMjAl4oCmPC9wPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMSIgdmFsdWU9IjUiPiBKZSB2ZW5kcyBpbW3DqWRpYXRlbWVudCBUT1VUIG1vbiBwbGFjZW1lbnQgZXQgcmFjaMOodGUgZGVzIGFjdGlmcyBtb2lucyByaXNxdcOpczwvbGFiZWw+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3ExIiB2YWx1ZT0iMTAiPiBKZSB2ZW5kcyBVTkUgUEFSVElFIGRlIGNldCBpbnZlc3Rpc3NlbWVudCBldCByYWNow6h0ZSBkZXMgYWN0aWZzIG1vaW5zIHJpc3F1w6lzPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTEiIHZhbHVlPSIxNSI+IEplIGNvbnNlcnZlIG1vbiBpbnZlc3Rpc3NlbWVudCBjYXIgbGEgdmFsZXVyIHZhIGNlcnRhaW5lbWVudCByZW1vbnRlcjwvbGFiZWw+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3ExIiB2YWx1ZT0iMjAiPiBKJ2VuIHJhY2jDqHRlIGVuY29yZSBwbHVzIHBvdXIgZGltaW51ZXIgbW9uIGNvw7t0IGRlIHJldmllbnQ8L2xhYmVsPgogICAgPC9kaXY+CgogICAgPGRpdiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNHB4Ij4KICAgICAgPHAgc3R5bGU9ImZvbnQtc2l6ZToxMnB4O2ZvbnQtd2VpZ2h0OjYwMDtjb2xvcjp2YXIoLS1uYXZ5KTttYXJnaW4tYm90dG9tOjhweCI+Mi4gQXZlei12b3VzIGTDqWrDoCBzdWJpIGRlcyBwZXJ0ZXMgZGFucyBsZSBwYXNzw6kgPyBTaSBvdWksIGNvbW1lbnQgYXZlei12b3VzIHLDqWFnaSA/PC9wPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMiIgdmFsdWU9IjUiPiBKJ2FpIHZlbmR1PC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTIiIHZhbHVlPSIxMCI+IEonYWkgdmVuZHUgdW5lIHBhcnRpZTwvbGFiZWw+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3EyIiB2YWx1ZT0iMTUiPiBKJ2FpIHRvdXQgY29uc2VydsOpPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTIiIHZhbHVlPSIyMCI+IEonYWkgcsOpaW52ZXN0aTwvbGFiZWw+CiAgICA8L2Rpdj4KCiAgICA8ZGl2IHN0eWxlPSJtYXJnaW4tYm90dG9tOjE0cHgiPgogICAgICA8cCBzdHlsZT0iZm9udC1zaXplOjEycHg7Zm9udC13ZWlnaHQ6NjAwO2NvbG9yOnZhcigtLW5hdnkpO21hcmdpbi1ib3R0b206OHB4Ij4zLiBDb21tZW50IGF2ZXotdm91cyB2w6ljdSBsZXMgZGVybmnDqHJlcyBzZWNvdXNzZXMgZmluYW5jacOocmVzIGRlcyBtYXJjaMOpcyA/PC9wPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMyIgdmFsdWU9IjUiPiBKZSBuJ2VuIGRvcm1haXMgcGFzIGxhIG51aXQ8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMyIgdmFsdWU9IjEwIj4gVHLDqHMgYmllbiwgamUgbifDqXRhaXMgcGFzIGF1IGNvdXJhbnQ8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMyIgdmFsdWU9IjE1Ij4gSidhaSBzdWl2aSDDp2EgZGUgcHLDqHMgbWFpcyBzYW5zIHBhbmlxdWVyPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTMiIHZhbHVlPSIyMCI+IFRyw6hzIGJpZW4uIENlbGEgcmVtb250ZSB0b3Vqb3VycyBldCBtZXMgcGxhY2VtZW50cyBzb250IHNvbGlkZXM8L2xhYmVsPgogICAgPC9kaXY+CgogICAgPGRpdiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNHB4Ij4KICAgICAgPHAgc3R5bGU9ImZvbnQtc2l6ZToxMnB4O2ZvbnQtd2VpZ2h0OjYwMDtjb2xvcjp2YXIoLS1uYXZ5KTttYXJnaW4tYm90dG9tOjhweCI+NC4gTGUgY3JpdMOocmUgZGUgbGlxdWlkaXTDqSBlc3QgaW1wb3J0YW50IGRhbnMgbGUgY2FkcmUgZGUgbW9uIHBhdHJpbW9pbmXigKY8L3A+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3E0IiB2YWx1ZT0iNSI+IEplIHZldXggdG91am91cnMgYXZvaXIgdW5lIHBhcnQgaW1wb3J0YW50ZSBkZSBtb24gcGF0cmltb2luZSBsaXF1aWRlLCBhdSBjYXMgb8O5PC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTQiIHZhbHVlPSIxMCI+IEplIHNvdWhhaXRlIGNvbnNlcnZlciB1biBwZXRpdCBtYXRlbGFzIGRlIHPDqWN1cml0w6k8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNCIgdmFsdWU9IjE1Ij4gSmUgbmUgZ2FyZGUgcXVlIGNlIGRvbnQgaidhaSB2cmFpbWVudCBiZXNvaW4gY2FyIGplIHNhaXMgcG91dm9pciB2ZW5kcmUgZGVzIGFjdGlmcyByYXBpZGVtZW50IHNhbnMgcHJvYmzDqG1lPC9sYWJlbD4KICAgIDwvZGl2PgoKICAgIDxkaXYgc3R5bGU9Im1hcmdpbi1ib3R0b206MTRweCI+CiAgICAgIDxwIHN0eWxlPSJmb250LXNpemU6MTJweDtmb250LXdlaWdodDo2MDA7Y29sb3I6dmFyKC0tbmF2eSk7bWFyZ2luLWJvdHRvbTo4cHgiPjUuIERhbnMgbGEgdmllLCBhaW1lei12b3VzIHByZW5kcmUgZGVzIHJpc3F1ZXMgKHNwb3J0LCBqZXV4LCBwYXJp4oCmKSA/PC9wPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNSIgdmFsdWU9IjUiPiBOb248L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNSIgdmFsdWU9IjEwIj4gUGFyZm9pcywgc2kgbGVzIGNvbnPDqXF1ZW5jZXMgc29udCBmYWlibGVzPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTUiIHZhbHVlPSIxNSI+IEFzc2V6IHNvdXZlbnQsIHNpIGplIG1hw650cmlzZSBsZXMgcmlzcXVlcyBldCBsZXVycyBjb25zw6lxdWVuY2VzPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTUiIHZhbHVlPSIyMCI+IEF1dGFudCBxdWUgamUgcGV1eC4gSidhaW1lIGwnYWRyw6luYWxpbmUsIHF1J2ltcG9ydGUgbGVzIGNvbnPDqXF1ZW5jZXM8L2xhYmVsPgogICAgPC9kaXY+CgogICAgPGRpdiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNHB4Ij4KICAgICAgPHAgc3R5bGU9ImZvbnQtc2l6ZToxMnB4O2ZvbnQtd2VpZ2h0OjYwMDtjb2xvcjp2YXIoLS1uYXZ5KTttYXJnaW4tYm90dG9tOjhweCI+Ni4gQ29tbWUgaW5kaXF1w6kgcHLDqWPDqWRlbW1lbnQsIHZvdHJlIHByaW5jaXBhbCBvYmplY3RpZiBhIHVuZSDDqWNow6lhbmNlIGRl4oCmPC9wPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNiIgdmFsdWU9IjUiPiBFbnRyZSA2IG1vaXMgZXQgMyBhbnMgKGNvdXJ0IHRlcm1lLCBwcmlzZSBkZSByaXNxdWUgZmFpYmxlKTwvbGFiZWw+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3E2IiB2YWx1ZT0iMTAiPiBFbnRyZSA0IGV0IDEwIGFucyAobW95ZW4gdGVybWUsIHByaXNlIGRlIHJpc3F1ZSDDqXF1aWxpYnLDqWUpPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTYiIHZhbHVlPSIxNSI+IEVudHJlIDExIGV0IDE1IGFucyAobG9uZyB0ZXJtZSwgcHJpc2UgZGUgcmlzcXVlIGZvcnQpPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTYiIHZhbHVlPSIyMCI+IFN1cMOpcmlldXIgw6AgMTUgYW5zICh0csOocyBsb25nIHRlcm1lLCBwcmlzZSBkZSByaXNxdWUgw6lsZXbDqWUpPC9sYWJlbD4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8IS0tIFLDiVNVTFRBVCBSSVNRVUUgLS0+CiAgPGRpdiBjbGFzcz0iY2FyZCIgc3R5bGU9ImJhY2tncm91bmQ6dmFyKC0tY3JlYW0yKTtib3JkZXI6bm9uZTttYXJnaW4tYm90dG9tOjEycHgiPgogICAgPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2FsaWduLWl0ZW1zOmNlbnRlcjtnYXA6MTZweDtmbGV4LXdyYXA6d3JhcCI+CiAgICAgIDxkaXYgc3R5bGU9ImZsZXg6MSI+CiAgICAgICAgPGRpdiBzdHlsZT0iZm9udC1zaXplOjExcHg7Y29sb3I6dmFyKC0tbXV0ZWQpO3RleHQtdHJhbnNmb3JtOnVwcGVyY2FzZTtsZXR0ZXItc3BhY2luZzouNHB4O21hcmdpbi1ib3R0b206NHB4Ij5TY29yZSByaXNxdWU8L2Rpdj4KICAgICAgICA8ZGl2IGlkPSJyaXNrLXNjb3JlLXZhbCIgc3R5bGU9ImZvbnQtc2l6ZToyMnB4O2ZvbnQtd2VpZ2h0OjcwMDtjb2xvcjp2YXIoLS1uYXZ5KSI+4oCUPC9kaXY+CiAgICAgICAgPGRpdiBzdHlsZT0iZm9udC1zaXplOjEwcHg7Y29sb3I6dmFyKC0tbXV0ZWQpIj4vIDEyMCBwdHM8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgc3R5bGU9ImZsZXg6MSI+CiAgICAgICAgPGRpdiBzdHlsZT0iZm9udC1zaXplOjExcHg7Y29sb3I6dmFyKC0tbXV0ZWQpO3RleHQtdHJhbnNmb3JtOnVwcGVyY2FzZTtsZXR0ZXItc3BhY2luZzouNHB4O21hcmdpbi1ib3R0b206NHB4Ij5Qcm9maWwgY2FsY3Vsw6k8L2Rpdj4KICAgICAgICA8ZGl2IGlkPSJyaXNrLXByb2ZpbC1jYWxjIiBzdHlsZT0iZm9udC1zaXplOjE2cHg7Zm9udC13ZWlnaHQ6NzAwO2NvbG9yOnZhcigtLW5hdnkpIj7igJQ8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgc3R5bGU9ImZsZXg6MSI+CiAgICAgICAgPGRpdiBzdHlsZT0iZm9udC1zaXplOjEwcHg7Y29sb3I6dmFyKC0tbXV0ZWQpO21hcmdpbi1ib3R0b206NnB4Ij40MC02NyA6IFPDqWN1cml0w6kgwrcgNjgtOTUgOiBQcnVkZW50PGJyPjk2LTEyMyA6IMOJcXVpbGlicsOpIMK3IDEyNCsgOiBEeW5hbWlxdWU8L2Rpdj4KICAgICAgICA8YnV0dG9uIGNsYXNzPSJidG4gYnAyIGJzbSIgb25jbGljaz0iY2FsY1Jpc2tTY29yZSgpIj5DYWxjdWxlciBsZSBzY29yZTwvYnV0dG9uPgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8IS0tIFLDiUNBUElUVUxBVElGIEZJTkFMIC0tPgogIDxkaXYgY2xhc3M9ImNhcmQiIHN0eWxlPSJiYWNrZ3JvdW5kOmxpbmVhci1ncmFkaWVudCgxMzVkZWcsdmFyKC0tbmF2eSksdmFyKC0tbmF2eTIpKTtib3JkZXI6bm9uZTttYXJnaW4tYm90dG9tOjEycHgiPgogICAgPGRpdiBzdHlsZT0iZm9udC1mYW1pbHk6J1BsYXlmYWlyIERpc3BsYXknLHNlcmlmO2ZvbnQtc2l6ZToxNXB4O2ZvbnQtd2VpZ2h0OjcwMDtjb2xvcjp2YXIoLS1nb2xkMik7bWFyZ2luLWJvdHRvbToxMnB4Ij5Sw6lzdWx0YXQg4oCUIFByb2ZpbCBkZSByaXNxdWUgY2xpZW50PC9kaXY+CiAgICA8ZGl2IHN0eWxlPSJkaXNwbGF5OmdyaWQ7Z3JpZC10ZW1wbGF0ZS1jb2x1bW5zOjFmciAxZnIgMWZyO2dhcDoxMnB4Ij4KICAgICAgPGRpdj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDI1NSwyNTUsMjU1LC41KTt0ZXh0LXRyYW5zZm9ybTp1cHBlcmNhc2U7bWFyZ2luLWJvdHRvbTo0cHgiPlNjb3JlIGNvbm5haXNzYW5jZTwvZGl2PgogICAgICAgIDxkaXYgaWQ9InJlc3VsdC1zY29yZS1rbiIgc3R5bGU9ImZvbnQtc2l6ZToxOHB4O2ZvbnQtd2VpZ2h0OjcwMDtjb2xvcjp3aGl0ZSI+4oCUPC9kaXY+CiAgICAgICAgPGRpdiBpZD0icmVzdWx0LWNhdC1rbiIgc3R5bGU9ImZvbnQtc2l6ZToxMXB4O2NvbG9yOnJnYmEoMjU1LDI1NSwyNTUsLjcpIj7igJQ8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXY+CiAgICAgICAgPGRpdiBzdHlsZT0iZm9udC1zaXplOjEwcHg7Y29sb3I6cmdiYSgyNTUsMjU1LDI1NSwuNSk7dGV4dC10cmFuc2Zvcm06dXBwZXJjYXNlO21hcmdpbi1ib3R0b206NHB4Ij5Qcm9maWwgZ3JhcGhpcXVlPC9kaXY+CiAgICAgICAgPGRpdiBpZD0icmVzdWx0LXByb2ZpbGUtZ3JhcGgiIHN0eWxlPSJmb250LXNpemU6MThweDtmb250LXdlaWdodDo3MDA7Y29sb3I6d2hpdGUiPuKAlDwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDI1NSwyNTUsMjU1LC41KTt0ZXh0LXRyYW5zZm9ybTp1cHBlcmNhc2U7bWFyZ2luLWJvdHRvbTo0cHgiPlByb2ZpbCBjYWxjdWzDqTwvZGl2PgogICAgICAgIDxkaXYgaWQ9InJlc3VsdC1wcm9maWxlLWNhbGMiIHN0eWxlPSJmb250LXNpemU6MThweDtmb250LXdlaWdodDo3MDA7Y29sb3I6d2hpdGUiPuKAlDwvZGl2PgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogICAgPGRpdiBzdHlsZT0ibWFyZ2luLXRvcDoxMHB4O3BhZGRpbmctdG9wOjhweDtib3JkZXItdG9wOjFweCBzb2xpZCByZ2JhKDI1NSwyNTUsMjU1LC4xKTtmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDI1NSwyNTUsMjU1LC40KSI+RW4gY2FzIGQnaW5jb2jDqXJlbmNlIGVudHJlIGxlIHByb2ZpbCBzw6lsZWN0aW9ubsOpIGV0IGxlIHByb2ZpbCBjYWxjdWzDqSwgbGUgY29uc2VpbGxlciBkb2l0IGRvY3VtZW50ZXIgZXQganVzdGlmaWVyIGxhIHJlY29tbWFuZGF0aW9uLjwvZGl2PgogIDwvZGl2PgoKICA8IS0tIFNJR05BVFVSRSAtLT4KICA8ZGl2IGNsYXNzPSJjYXJkIj4KICAgIDxkaXYgY2xhc3M9ImNhcmQtdGl0bGUiPkNlcnRpZmljYXRpb24gZXQgU2lnbmF0dXJlPC9kaXY+CiAgICA8ZGl2IGNsYXNzPSJpbmZvLWJveCI+SmUgY2VydGlmaWUgbCdleGFjdGl0dWRlIGRlcyBpbmZvcm1hdGlvbnMgZm91cm5pZXMgY2ktZGVzc3VzIGV0IHJlY29ubmFpcyBhdm9pciDDqXTDqSBpbmZvcm3DqShlKSBkZXMgcmlzcXVlcyBsacOpcyBhdXggcGxhY2VtZW50cyBmaW5hbmNpZXJzIGNvbmZvcm3DqW1lbnQgw6AgbGEgcsOpZ2xlbWVudGF0aW9uIE1JRjIuPC9kaXY+CiAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyaWQiPgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWwgY2xhc3M9ImZsIj5GYWl0IMOgPC9sYWJlbD48aW5wdXQgaWQ9ImVyLWxpZXUiIGNsYXNzPSJmYyIgcGxhY2Vob2xkZXI9IlBhcmlzIj48L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsIGNsYXNzPSJmbCI+TGU8L2xhYmVsPjxpbnB1dCBpZD0iZXItZGF0ZSIgY2xhc3M9ImZjIiB0eXBlPSJkYXRlIj48L2Rpdj4KICAgIDwvZGl2PgogICAgPGRpdiBzdHlsZT0ibWFyZ2luLXRvcDoxMnB4Ij4KICAgICAgPGxhYmVsIGNsYXNzPSJmbCI+U2lnbmF0dXJlIGNsaWVudDwvbGFiZWw+CiAgICAgIDxjYW52YXMgaWQ9ImVyLXNpZy1jYW52YXMiIHN0eWxlPSJib3JkZXI6MS41cHggZGFzaGVkIHZhcigtLWJkcik7Ym9yZGVyLXJhZGl1czo2cHg7aGVpZ2h0OjkwcHg7d2lkdGg6MTAwJTtkaXNwbGF5OmJsb2NrO21hcmdpbi10b3A6NnB4O2JhY2tncm91bmQ6I2ZhZmFmYSI+PC9jYW52YXM+CiAgICAgIDxidXR0b24gY2xhc3M9ImJ0biBiZ2ggYnNtIiBvbmNsaWNrPSJlckNsZWFyU2lnKCkiIHN0eWxlPSJtYXJnaW4tdG9wOjZweCI+RWZmYWNlciBsYSBzaWduYXR1cmU8L2J1dHRvbj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJxLW5hdi1idG5zIiBzdHlsZT0iZGlzcGxheTpmbGV4O2p1c3RpZnktY29udGVudDpmbGV4LXN0YXJ0O21hcmdpbi10b3A6MTZweCI+CiAgICA8YnV0dG9uIGNsYXNzPSJidG4gYmdoIiBvbmNsaWNrPSJnb0Nvbm5haXNzYW5jZSgzKSI+4oaQIFJldG91ciBDb25uYWlzc2FuY2U8L2J1dHRvbj4KICA8L2Rpdj4KPC9kaXY+CjwvZGl2Pg==";

// ═══ STATE ═══
var CLIENT=null;
var _sigDoc=null,_sigCode=null,_sigCtx=null,_sigDrawing=false;
var _sessionTimer=null,_sessionRemain=1800; // 30 min
var _saveTimeout=null;

// ═══ UTILS ═══
function eKey(e){return(e||'').toLowerCase().replace(/[^a-z0-9]/g,'_');}
function fmt(n){return n?(+n).toLocaleString('fr-FR',{style:'currency',currency:'EUR',maximumFractionDigits:0}):'—';}
function escH(s){return(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;');}
function today(){return new Date().toLocaleDateString('fr-FR');}

function toast(msg,type){
  var w=document.getElementById('toast-wrap');if(!w)return;
  var t=document.createElement('div');t.className='toast'+(type?' '+type:'');t.textContent=msg;
  w.appendChild(t);
  setTimeout(function(){t.style.opacity='0';t.style.transition='opacity 0.3s';setTimeout(function(){t.remove();},300);},3200);
}

function showSave(){
  var s=document.getElementById('tb-save');if(!s)return;
  s.classList.add('visible');
  clearTimeout(_saveTimeout);
  _saveTimeout=setTimeout(function(){s.classList.remove('visible');},2000);
}

function saveLocal(){
  if(!CLIENT)return;
  try{
    var slim=JSON.parse(JSON.stringify(CLIENT));
    // Exclure seulement les données binaires (signatures, fichiers uploadés)
    if(slim.parcoursData){
      Object.keys(slim.parcoursData).forEach(function(k){
        if(k.indexOf('signature')>=0) delete slim.parcoursData[k];
      });
    }
    if(slim.docs) slim.docs=slim.docs.map(function(d){
      var dd=Object.assign({},d); delete dd.data; delete dd.signature; return dd;
    });
    // Garder patrimoine et ptfHistory (pas trop volumineux)
    slim.patrimoine = CLIENT.patrimoine||{};
    slim.ptfHistory = CLIENT.ptfHistory||[];
    localStorage.setItem('caremma_c_'+eKey(CLIENT.email),JSON.stringify(slim));
    showSave();
  }catch(e){
    if(e.name==='QuotaExceededError'){
      try{
        // Nettoyer et sauvegarder le minimum
        for(var i=localStorage.length-1;i>=0;i--){
          var k=localStorage.key(i);
          if(k&&k.indexOf('caremma_c_')===0) localStorage.removeItem(k);
        }
        localStorage.setItem('caremma_c_'+eKey(CLIENT.email),JSON.stringify({
          email:CLIENT.email,prenom:CLIENT.prenom,nom:CLIENT.nom,
          parcoursData:CLIENT.parcoursData||{},patrimoine:CLIENT.patrimoine||{}
        }));
        toast('Espace disque libéré ✓','warn');
      }catch(e2){console.warn('saveLocal:',e2);}
    }
  }
}

// ═══ JSONBin ═══
function _jbSleep(ms){return new Promise(function(res){setTimeout(res,ms);});}
// Lecture JSONBin avec tolérance au rate-limiting (403/429 sur lectures rapprochées).
// 6 tentatives, attente croissante : 900ms, 1.8s, 3.6s, 7.2s, 14.4s.
function jbGet(id,_try){
  _try=_try||0;
  return fetch('https://api.jsonbin.io/v3/b/'+id+'/latest',{
    headers:{'X-Master-Key':JBKEY,'X-Bin-Meta':'false'}
  }).then(function(r){
    if(!r.ok){
      var limited=(r.status===403||r.status===429);
      if(limited&&_try<5){
        return _jbSleep(900*Math.pow(2,_try)).then(function(){return jbGet(id,_try+1);});
      }
      throw new Error('JB '+r.status);
    }
    return r.json();
  }).catch(function(e){
    // erreur réseau transitoire : on retente aussi
    if(_try<5&&/Failed to fetch|NetworkError|Load failed/i.test(e.message||'')){
      return _jbSleep(900*Math.pow(2,_try)).then(function(){return jbGet(id,_try+1);});
    }
    throw e;
  });
}
function jbPut(id,data){
  return fetch('https://api.jsonbin.io/v3/b/'+id,{
    method:'PUT',
    headers:{'Content-Type':'application/json','X-Master-Key':JBKEY},
    body:JSON.stringify(data)
  }).then(function(r){if(!r.ok)throw new Error('JB PUT '+r.status);return r.json();});
}

// ═══ SESSION ═══
function startSession(){
  _sessionRemain=1800;
  clearInterval(_sessionTimer);
  _sessionTimer=setInterval(function(){
    _sessionRemain--;
    if(_sessionRemain<=300){
      var sw=document.getElementById('session-warning');
      var m=Math.floor(_sessionRemain/60),s=_sessionRemain%60;
      if(sw){sw.style.display='block';document.getElementById('sw-time').textContent=m+':'+(s<10?'0':'')+s;}
    }
    if(_sessionRemain<=0){clearInterval(_sessionTimer);logout();toast('Session expirée — reconnectez-vous.','warn');}
  },1000);
  document.addEventListener('click',resetSession,{passive:true});
  document.addEventListener('keydown',resetSession,{passive:true});
}
function resetSession(){
  _sessionRemain=1800;
  var sw=document.getElementById('session-warning');
  if(sw)sw.style.display='none';
}

// ═══ AUTH ═══
function doLogin(){
  // (accès dev supprimé — tout accès passe désormais par mot de passe ou code serveur)
  var email=(document.getElementById('li-email').value||'').trim().toLowerCase();
  var code=(document.getElementById('li-code').value||'').trim();
  var errEl=document.getElementById('login-err');
  var btn=document.getElementById('login-btn');
  errEl.style.display='none';
  if(!email||!code){errEl.style.display='block';errEl.textContent='Veuillez remplir tous les champs.';return;}
  btn.textContent='Vérification...';btn.disabled=true;

  // 1. Mot de passe local
  var stored=localStorage.getItem('caremma_auth_'+eKey(email));
  if(stored){
    try{
      var a=JSON.parse(stored);
      if(a.password===code){
        CLIENT=Object.assign({email:email,prenom:a.prenom||'',nom:a.nom||'',docs:[],msgs:[],parcoursData:{},rapports:[],rapportsVus:[],notes:[],patrimoineDeclare:[],objectifPerso:null,streakMonths:[]},a.clientData||{});
        var saved=localStorage.getItem('caremma_c_'+eKey(email));
        if(saved)try{CLIENT=Object.assign(CLIENT,JSON.parse(saved));}catch(e){}
        btn.textContent='Accéder à mon espace →';btn.disabled=false;
        startApp();return;
      }
    }catch(e){}
  }

  // 2. Code JSONBin
  jbGet(CLIENTS_BIN).then(function(data){
    var clients=data.clients||[];
    var match=clients.find(function(c){return c.email.toLowerCase()===email&&c.code===code;});
    if(!match){
      errEl.style.display='block';errEl.textContent='Email ou code incorrect.';
      btn.textContent='Accéder à mon espace →';btn.disabled=false;return;
    }
    CLIENT={email:match.email,prenom:match.prenom||'',nom:match.nom||'',docs:[],msgs:[],parcoursData:{},rapports:[],rapportsVus:[],notes:[],patrimoineDeclare:[],objectifPerso:null,streakMonths:[]};
    var saved=localStorage.getItem('caremma_c_'+eKey(email));
    if(saved)try{CLIENT=Object.assign(CLIENT,JSON.parse(saved));}catch(e){}
    btn.textContent='Accéder à mon espace →';btn.disabled=false;
    startApp();
  }).catch(function(){
    errEl.style.display='block';errEl.textContent='Erreur de connexion. Réessayez.';
    btn.textContent='Accéder à mon espace →';btn.disabled=false;
  });
}

function setPassword(){
  var p1=document.getElementById('sp-p1').value;
  var p2=document.getElementById('sp-p2').value;
  var err=document.getElementById('sp-err');
  if(!p1||p1.length<6||p1!==p2){err.style.display='block';err.textContent='Mots de passe incorrects ou trop courts.';return;}
  err.style.display='none';
  localStorage.setItem('caremma_auth_'+eKey(CLIENT.email),JSON.stringify({password:p1,prenom:CLIENT.prenom,nom:CLIENT.nom,clientData:CLIENT}));
  document.getElementById('setpwd-screen').style.display='none';
  startApp();toast('Mot de passe créé ✓','success');
}

function logout(){
  clearInterval(_sessionTimer);CLIENT=null;
  document.getElementById('app').style.display='none';
  document.getElementById('login-screen').style.display='flex';
  document.getElementById('li-code').value='';
}

function startApp(){
  document.getElementById('login-screen').style.display='none';
  document.getElementById('setpwd-screen').style.display='none';
  var app=document.getElementById('app');app.style.display='flex';
  document.getElementById('tb-greeting').textContent='Bonjour, '+CLIENT.prenom;
  var av=document.getElementById('tb-avatar');
  if(av)av.textContent=(CLIENT.prenom[0]||'').toUpperCase()+(CLIENT.nom[0]||'').toUpperCase();
  document.getElementById('acc-title').textContent='Bonjour '+CLIENT.prenom+' 👋';
  if(typeof emailjs!=='undefined')emailjs.init(EJS_PUBLIC);
  startSession();
  renderKPIs();
  loadReporting();
  syncMessages();
}


function goPage(name,navEl){
  document.querySelectorAll('.page').forEach(function(p){p.classList.remove('active');});
  document.querySelectorAll('.nav-item').forEach(function(n){n.classList.remove('active');});
  var pg=document.getElementById('pg-'+name);if(pg)pg.classList.add('active');
  if(navEl)navEl.classList.add('active');
  else{var n=document.getElementById('nav-'+name);if(n)n.classList.add('active');}
  if(name==='accueil')renderKPIs();
  if(name==='objectifs')renderObjectifs();
  if(name==='connaissance')renderConnaissance();
  if(name==='monprofil'){
    var pframe=document.getElementById('profil-tool-frame');
    if(pframe && !pframe.dataset.loaded){ pframe.src='data:text/html;base64,'+_PARCOURS_TOOL_B64; pframe.dataset.loaded='1'; }
  }
  if(name==='documents')renderDocs();
  if(name==='rapports'){renderRapports();renderNotes();}
  if(name==='patrimoine'){renderGoalCard();renderPatrimoineDeclare();}
  if(name==='guides'){renderFiches();initSimAV();initSimPER();}
  if(name==='messages'){
    syncMessages();renderMsgs();
    // Auto-refresh toutes les 20s sur la page messages
    if(window._msgRefresh) clearInterval(window._msgRefresh);
    window._msgRefresh = setInterval(function(){
      var pg=document.getElementById('pg-messages');
      if(pg&&pg.classList.contains('active')){ syncMessages(); }
      else{ clearInterval(window._msgRefresh); }
    },20000);
  } else {
    if(window._msgRefresh){ clearInterval(window._msgRefresh); window._msgRefresh=null; }
  }
  if(name==='reporting'){
    // D'abord rendre visible, PUIS charger et dessiner
    setTimeout(function(){
      loadReporting();
      renderAllocationDonut();
      initSimulateur();
      // Dessiner avec les données déjà en mémoire
      var h=window._pendingHistory||(CLIENT&&CLIENT.ptfHistory)||[];
      if(h.length>=2){
        setTimeout(function(){ drawChart(h); },100);
      }
    },50);
    // Auto-refresh 30s
    if(window._repRefresh) clearInterval(window._repRefresh);
    window._repRefresh=setInterval(function(){
      var pg=document.getElementById('pg-reporting');
      if(pg&&pg.classList.contains('active')){
        loadReporting();
      } else {
        clearInterval(window._repRefresh);window._repRefresh=null;
      }
    },30000);
  } else {
    if(window._repRefresh){clearInterval(window._repRefresh);window._repRefresh=null;}
  }
}

// ═══ KPIs ═══
function renderKPIs(){
  var p=CLIENT.patrimoine||{};
  var e=function(id){return document.getElementById(id);};
  if(e('k-val'))e('k-val').textContent=p.valeur?fmt(p.valeur):'—';
  if(e('k-date'))e('k-date').textContent=p.dateMAJ?'Au '+p.dateMAJ:'';
  if(e('k-perf')&&p.perfYTD!=null){
    e('k-perf').textContent=(p.perfYTD>=0?'+':'')+p.perfYTD+'%';
    e('k-perf').className='kpi-value '+(p.perfYTD>=0?'up':'dn');
  }
  if(e('k-profil'))e('k-profil').textContent=CLIENT.profil||'—';
  // Progression vers le prochain jalon patrimonial
  var mv=nextMilestoneInfo(currentPortfolioValue());
  if(e('k-progress'))e('k-progress').textContent=mv.pct+'%';
  if(e('k-progress-sub'))e('k-progress-sub').textContent='vers '+fmt(mv.next);
  // Actions
  var actions=[];
  var docs=(CLIENT.docs||[]).filter(function(d){return d.status!=='signed';});
  if(docs.length)actions.push('✍️ '+docs.length+' document(s) à signer');
  var vus=CLIENT.rapportsVus||[];
  var newRap=(CLIENT.rapports||[]).filter(function(r){return vus.indexOf(String(r.id))<0;}).length;
  if(newRap)actions.push('📚 '+newRap+' nouveau(x) rapport(s) disponible(s)');
  var unreadMsg=(CLIENT.msgs||[]).filter(function(m){return m.from!=='client'&&!m.read;}).length;
  if(unreadMsg)actions.push('💬 '+unreadMsg+' nouveau(x) message(s)');
  var ac=e('acc-actions');
  if(ac)ac.innerHTML=actions.length?actions.map(function(a){return'<div style="padding:6px 0;border-bottom:1px solid var(--bdr);color:var(--text2)">'+a+'</div>';}).join(''):'<div style="color:var(--text3)">Aucune action en attente ✓</div>';
  // Derniers messages
  var msgs=(CLIENT.msgs||[]).slice(-3).reverse();
  var am=e('acc-msgs');
  if(am)am.innerHTML=msgs.length?msgs.map(function(m){return'<div style="padding:6px 0;border-bottom:1px solid var(--bdr);font-size:12px"><span style="color:var(--text3)">'+m.date+'</span><br><span style="color:var(--text2)">'+escH(m.text.slice(0,60))+(m.text.length>60?'…':'')+'</span></div>';}).join(''):'<div style="color:var(--text3)">Aucun message récent.</div>';
  renderStories();
  renderMilestoneCard();
  renderNudgeCard();
  renderStreakCard();
}

// ═══ JALONS PATRIMONIAUX ═══
var MILESTONES=[25000,50000,100000,250000,500000,750000,1000000,1500000,2000000,3000000,5000000,7500000,10000000];
function currentPortfolioValue(){
  var p=CLIENT.patrimoine||{};
  if(p.valeur)return p.valeur;
  var h=CLIENT.ptfHistory||[];
  if(h.length)return h[h.length-1].valeur||0;
  return 0;
}
function nextMilestoneInfo(value){
  var prev=0,next=MILESTONES[0];
  for(var i=0;i<MILESTONES.length;i++){
    if(value<MILESTONES[i]){next=MILESTONES[i];prev=i>0?MILESTONES[i-1]:0;break;}
    prev=MILESTONES[i];next=MILESTONES[i];
  }
  var pct=next>prev?Math.max(0,Math.min(100,Math.round((value-prev)/(next-prev)*100))):100;
  return {prev:prev,next:next,pct:pct,value:value};
}
function renderMilestoneCard(){
  var el=document.getElementById('milestone-card');if(!el)return;
  var v=currentPortfolioValue();
  if(!v){el.innerHTML='';return;}
  var mv=nextMilestoneInfo(v);
  el.innerHTML='<div class="milestone-card">'
    +'<div style="display:flex;justify-content:space-between;align-items:baseline;font-size:12.5px;color:var(--text2)">'
      +'<span>🏆 Progression patrimoniale</span><span style="color:var(--text3)">'+fmt(v)+' / '+fmt(mv.next)+'</span>'
    +'</div>'
    +'<div class="milestone-bar-track"><div class="milestone-bar-fill" style="width:'+mv.pct+'%"></div></div>'
    +'<div style="font-size:11px;color:var(--text3)">Encore '+fmt(mv.next-v)+' avant le cap des '+fmt(mv.next)+'</div>'
    +'</div>';
  checkMilestoneCelebration(mv);
}
function checkMilestoneCelebration(mv){
  try{
    var key='caremma_milestone_'+eKey(CLIENT.email);
    var last=Number(localStorage.getItem(key)||0);
    if(mv.value>=mv.prev&&mv.prev>last&&mv.prev>0){
      localStorage.setItem(key,String(mv.prev));
      launchConfetti();
      toast('🏆 Cap des '+fmt(mv.prev)+' franchi !','warn');
    } else if(!localStorage.getItem(key)&&mv.prev>0){
      localStorage.setItem(key,String(mv.prev));
    }
  }catch(e){}
}
function launchConfetti(){
  var colors=['#c9a84c','#e8d9a8','#8a9bb0','#ffffff'];
  for(var i=0;i<36;i++){
    (function(){
      var d=document.createElement('div');
      d.className='confetti-piece';
      d.style.left=(Math.random()*100)+'vw';
      d.style.background=colors[Math.floor(Math.random()*colors.length)];
      d.style.animationDuration=(2.2+Math.random()*1.6)+'s';
      d.style.animationDelay=(Math.random()*0.4)+'s';
      document.body.appendChild(d);
      setTimeout(function(){d.remove();},4200);
    })();
  }
}

// ═══ STORIES (bandeau dashboard) ═══
function renderStories(){
  var el=document.getElementById('stories-row');if(!el)return;
  var cards=[];
  var notes=(CLIENT.notes||[]).slice().sort(function(a,b){return(b.ts||0)-(a.ts||0);});
  if(notes.length)cards.push({ico:'📰',label:'Note conseiller',title:notes[0].titre||'Note',page:'rapports'});
  var raps=(CLIENT.rapports||[]).slice().sort(function(a,b){
    function t(r){var p=(r.date||'').split('/');return p.length===3?new Date(p[2],p[1]-1,p[0]).getTime():0;}
    return t(b)-t(a);
  });
  if(raps.length)cards.push({ico:'📚',label:'Rapport dispo',title:raps[0].nom||'Rapport',page:'rapports'});
  var unreadMsg=(CLIENT.msgs||[]).filter(function(m){return m.from!=='client'&&!m.read;}).length;
  if(unreadMsg)cards.push({ico:'💬',label:'Messagerie',title:unreadMsg+' nouveau(x) message(s)',page:'messages'});
  var h=CLIENT.ptfHistory||[];
  if(h.length>=2){
    var delta=h[h.length-1].valeur-h[h.length-2].valeur;
    var pctD=h[h.length-2].valeur?Math.round(delta/h[h.length-2].valeur*1000)/10:0;
    cards.push({ico:pctD>=0?'📈':'📉',label:'Performance',title:(pctD>=0?'+':'')+pctD+'% dernière période',page:'reporting'});
  }
  var docs=(CLIENT.docs||[]).filter(function(d){return d.status!=='signed';});
  if(docs.length)cards.push({ico:'✍️',label:'À signer',title:docs.length+' document(s)',page:'documents'});

  if(!cards.length){el.innerHTML='';return;}
  el.innerHTML=cards.map(function(c){
    return '<div class="story-card" onclick="goPage(\''+c.page+'\',document.getElementById(\'nav-'+c.page+'\'))">'
      +'<div class="story-ico">'+c.ico+'</div>'
      +'<div class="story-label">'+escH(c.label)+'</div>'
      +'<div class="story-title">'+escH(c.title)+'</div>'
      +'</div>';
  }).join('');
}

// ═══ MESSAGES ═══
function syncMessages(){
  var k=eKey(CLIENT.email);
  // Filet de sécurité : normalise tout document déjà chargé (localStorage) avec l'ancien statut
  if(CLIENT.docs){ CLIENT.docs.forEach(function(d){ if(d.status==='to_sign') d.status='pending'; }); }
  Promise.all([jbGet(MSG_BIN).catch(function(){return null;}),fetchPublications()]).then(function(res){
    var data=res[0]||{};
    var pubs=res[1]||[];

    // ── Sync des publications globales du CRM (note/PDF diffusés à tous les clients)
    var pubIds=new Set((CLIENT.notes||[]).map(function(n){return String(n.id);}));
    pubs.forEach(function(p){
      if(!pubIds.has(String(p.id))){
        if(!CLIENT.notes)CLIENT.notes=[];
        CLIENT.notes.push(p);
        pubIds.add(String(p.id));
      }
    });

    var entry=data.messages&&data.messages[k];
    if(!entry){saveLocal();renderNotes();return;}

    // ── Sync messages (déduplication robuste par id ou texte+date)
    if(entry.msgs){
      var remote=entry.msgs;
      var ids=new Set((CLIENT.msgs||[]).filter(function(m){return m.id;}).map(function(m){return String(m.id);}));
      var textKeys=new Set((CLIENT.msgs||[]).map(function(m){return (m.text||'')+'|'+(m.date||'');}));
      remote.forEach(function(m){
        var uid=m.id?String(m.id):null;
        var tkey=(m.text||'')+'|'+(m.date||'');
        if(uid){
          if(!ids.has(uid)){if(!CLIENT.msgs)CLIENT.msgs=[];CLIENT.msgs.push(m);ids.add(uid);}
        } else {
          if(!textKeys.has(tkey)){if(!CLIENT.msgs)CLIENT.msgs=[];CLIENT.msgs.push(m);textKeys.add(tkey);}
        }
      });
    }

    // ── Sync documents envoyés par le conseiller
    if(entry.docs){
      var remoteDocs=entry.docs;
      var docIds=new Set((CLIENT.docs||[]).map(function(d){return String(d.id);}));
      remoteDocs.forEach(function(d){
        if(!docIds.has(String(d.id))){
          if(!CLIENT.docs)CLIENT.docs=[];
          // Le CRM écrit le statut "to_sign" pour un document en attente de signature ;
          // le portail attend "pending" pour afficher le bouton Signer. On normalise ici
          // une bonne fois, pour que tous les documents (nouveaux et existants) s'ouvrent.
          if(d.status==='to_sign') d.status='pending';
          CLIENT.docs.push(d);
          docIds.add(String(d.id));
        }
      });
    }

    // ── Sync rapports/documents consultables envoyés par le conseiller
    if(entry.rapports){
      var remoteRap=entry.rapports;
      var rapIds=new Set((CLIENT.rapports||[]).map(function(r){return String(r.id);}));
      remoteRap.forEach(function(r){
        if(!rapIds.has(String(r.id))){
          if(!CLIENT.rapports)CLIENT.rapports=[];
          CLIENT.rapports.push(r);
          rapIds.add(String(r.id));
        }
      });
    }

    // ── Sync patrimoine (pour les KPIs de performance)
    if(entry.patrimoine){
      CLIENT.patrimoine=entry.patrimoine;
      if(entry.patrimoine.historique)CLIENT.ptfHistory=entry.patrimoine.historique;
      else if(entry.ptfHistory)CLIENT.ptfHistory=entry.ptfHistory;
    }
    if(entry.profil)CLIENT.profil=entry.profil;
    if(entry.patrimoineDeclare&&(!CLIENT.patrimoineDeclare||!CLIENT.patrimoineDeclare.length)){
      CLIENT.patrimoineDeclare=entry.patrimoineDeclare;
    }
    if(entry.objectifPerso&&!CLIENT.objectifPerso){
      CLIENT.objectifPerso=entry.objectifPerso;
    }
    if(entry.streakMonths&&(!CLIENT.streakMonths||!CLIENT.streakMonths.length)){
      CLIENT.streakMonths=entry.streakMonths;
    }

    saveLocal();
    renderMsgs();
    renderKPIs();
    renderDocs();
    renderRapports();
    renderNotes();
    renderPatrimoineDeclare();
    renderGoalCard();

    var unread=(CLIENT.msgs||[]).filter(function(m){return m.from!=='client'&&!m.read;}).length;
    var b=document.getElementById('msg-badge');
    if(b){b.textContent=unread;b.style.display=unread?'inline':'none';}
    var db=document.getElementById('doc-badge');
    var pendingDocs=(CLIENT.docs||[]).filter(function(d){return d.status==='pending';}).length;
    if(db){db.textContent=pendingDocs;db.style.display=pendingDocs?'inline':'none';}
    var rb=document.getElementById('rap-badge');
    var vus=CLIENT.rapportsVus||[];
    var newRap=(CLIENT.rapports||[]).filter(function(r){return vus.indexOf(String(r.id))<0;}).length;
    if(rb){rb.textContent=newRap;rb.style.display=newRap?'inline':'none';}
  }).catch(function(){});
}

// ═══ DOCUMENTS ═══
function renderDocs(){
  var el=document.getElementById('docs-list');if(!el)return;
  var docs=CLIENT.docs||[];
  if(!docs.length){
    el.innerHTML='<div style="text-align:center;padding:40px 20px;color:var(--text3)">'
      +'<div style="font-size:36px;margin-bottom:12px">📂</div>'
      +'<div style="font-size:14px;font-weight:600;color:var(--text2);margin-bottom:6px">Aucun document pour le moment</div>'
      +'<div style="font-size:12px;line-height:1.6">Votre conseiller vous enverra des documents à signer depuis le CRM.</div>'
      +'</div>';
    return;
  }
  var statusLabel={pending:'⏳ En attente de signature',signed:'✅ Signé','':'📄 Document'};
  var statusColor={pending:'var(--orange)',signed:'var(--green)','':'var(--text2)'};
  el.innerHTML=docs.map(function(d){
    var signed=d.status==='signed';
    return '<div style="display:flex;align-items:center;gap:14px;padding:14px 16px;background:var(--surface);'
      +'border:1.5px solid '+(d.status==='pending'?'var(--gold)':signed?'rgba(34,197,94,.3)':'var(--bdr-gold)')+';'
      +'border-radius:10px;margin-bottom:10px">'
      +'<div style="font-size:26px;flex-shrink:0">'+(signed?'✅':d.status==='pending'?'📋':'📄')+'</div>'
      +'<div style="flex:1;min-width:0">'
        +'<div style="font-size:13px;font-weight:600;color:var(--text1);margin-bottom:2px">'+escH(d.nom)+'</div>'
        +'<div style="font-size:11px;color:var(--text3)">'+escH(d.date||'')+(d.cat?' · '+escH(d.cat):'')+'</div>'
      +'</div>'
      +'<div style="flex-shrink:0;text-align:right">'
        +'<div style="font-size:11px;font-weight:600;color:'+(statusColor[d.status]||statusColor[''])+';margin-bottom:6px">'+(statusLabel[d.status]||'')+'</div>'
        +(d.status==='pending'?'<button onclick="openDocSig(\''+escH(d.id)+'\')" class="btn btn-gold btn-sm" style="font-size:11px;padding:5px 12px">✍️ Signer</button>':'')
        +(signed&&d.signatureDate?'<div style="font-size:10px;color:var(--text3);margin-top:3px">le '+escH(d.signatureDate)+'</div>':'')
      +'</div>'
      +'</div>';
  }).join('');
}

function openDocSig(docId){
  var doc=(CLIENT.docs||[]).find(function(d){return String(d.id)===String(docId);});
  if(!doc){toast('Document introuvable','error');return;}
  _sigDoc=doc;
  var z=document.getElementById('sig-zone');
  if(!z){toast('Zone de signature introuvable','error');return;}
  z.style.display='block';

  // Bouton "Voir le document" si c'est un doc questionnaire
  var previewBtn='';
  if(doc.docType){
    var docKeyMap={objectifs:'objectifs',connaissance:'connaissance',entree:'objectifs',adequation:'connaissance'};
    var previewKey=docKeyMap[doc.docType]||doc.docType;
    previewBtn='<button onclick="openRecapAndMail(null,null,\''+previewKey+'\')" class="btn btn-outline btn-sm" style="font-size:11px">👁 Voir le document</button>';
  }

  z.innerHTML='<div style="background:var(--surface);border:1.5px solid var(--bdr-gold);border-radius:12px;padding:20px;margin-top:12px">'
    +'<div style="display:flex;align-items:center;gap:10px;margin-bottom:12px">'
      +'<div style="font-size:22px">📋</div>'
      +'<div><div style="font-size:14px;font-weight:600;color:var(--gold2)">Signature requise</div>'
        +'<div style="font-size:11px;color:var(--text3);margin-top:1px">'+escH(doc.nom)+'</div>'
      +'</div>'
      +(previewBtn?'<div style="margin-left:auto">'+previewBtn+'</div>':'')
    +'</div>'
    +'<div style="font-size:11px;color:var(--text3);margin-bottom:10px;padding:8px 10px;background:rgba(201,168,76,.06);border-radius:6px;border-left:2px solid var(--gold)">Tracez votre signature dans la zone ci-dessous, puis cliquez "Valider". Le document signé vous sera téléchargeable et sera automatiquement envoyé à votre conseiller.</div>'
    +'<canvas id="sig-canvas" width="600" height="140" style="width:100%;height:140px;cursor:crosshair;background:white;border-radius:6px;border:1.5px solid var(--bdr-gold);display:block"></canvas>'
    +'<div style="display:flex;gap:8px;margin-top:10px;flex-wrap:wrap">'
      +'<button onclick="clearSig()" class="btn btn-outline btn-sm">🗑 Effacer</button>'
      +'<button onclick="confirmSig()" class="btn btn-gold" style="padding:7px 16px;font-size:12px">✅ Valider ma signature</button>'
      +'<button onclick="closeSig()" class="btn btn-outline btn-sm" style="margin-left:auto">Annuler</button>'
    +'</div>'
    +'</div>';
  // Init canvas
  var canvas=document.getElementById('sig-canvas');
  _sigCtx=canvas.getContext('2d');_sigDrawing=false;
  _sigCtx.lineWidth=2;_sigCtx.strokeStyle='#0A1628';_sigCtx.lineCap='round';_sigCtx.lineJoin='round';
  function getXY(e,c){var r=c.getBoundingClientRect();return[(e.clientX-r.left)*(c.width/r.width),(e.clientY-r.top)*(c.height/r.height)];}
  canvas.addEventListener('mousedown',function(e){_sigDrawing=true;var p=getXY(e,canvas);_sigCtx.beginPath();_sigCtx.moveTo(p[0],p[1]);});
  canvas.addEventListener('mousemove',function(e){if(!_sigDrawing)return;var p=getXY(e,canvas);_sigCtx.lineTo(p[0],p[1]);_sigCtx.stroke();});
  canvas.addEventListener('mouseup',function(){_sigDrawing=false;});
  canvas.addEventListener('mouseleave',function(){_sigDrawing=false;});
  canvas.addEventListener('touchstart',function(e){e.preventDefault();_sigDrawing=true;var t=e.touches[0];var p=getXY(t,canvas);_sigCtx.beginPath();_sigCtx.moveTo(p[0],p[1]);},{passive:false});
  canvas.addEventListener('touchmove',function(e){e.preventDefault();if(!_sigDrawing)return;var t=e.touches[0];var p=getXY(t,canvas);_sigCtx.lineTo(p[0],p[1]);_sigCtx.stroke();},{passive:false});
  canvas.addEventListener('touchend',function(){_sigDrawing=false;});
  canvas.scrollIntoView({behavior:'smooth',block:'center'});
}

// ═══ RAPPORTS & DOCUMENTS (consultation) ═══
var _rapFilter='tous';
var _rapCatMeta={
  'reporting':{label:'Reporting trimestriel',icon:'📈'},
  'reglementaire':{label:'Documents réglementaires',icon:'📋'},
  'convention':{label:'Conventions',icon:'📝'},
  'autre':{label:'Autres',icon:'📄'}
};
function rapCatKey(cat){
  var c=(cat||'').toLowerCase();
  if(c.indexOf('report')>=0)return'reporting';
  if(c.indexOf('regl')>=0||c.indexOf('règl')>=0||c.indexOf('der')>=0||c.indexOf('adequ')>=0)return'reglementaire';
  if(c.indexOf('conv')>=0)return'convention';
  return'autre';
}
function rapIcon(type){
  if((type||'').toLowerCase()==='pptx')return'📊';
  if((type||'').toLowerCase()==='pdf')return'📄';
  return'📁';
}
function setRapFilter(key){_rapFilter=key;renderRapports();}

// ═══ Documents volumineux : reconstitution depuis bins fragmentés ═══
// Le CRM découpe les fichiers > 100 Ko en plusieurs bins JSONBin.
// On les relit un par un, espacés de 900 ms pour ne pas déclencher le rate-limiting.
function _repMime(r){
  var t=(r.type||r.mime||'').toLowerCase();
  if(t.indexOf('/')>0)return t;
  if(t==='pdf')return'application/pdf';
  if(t==='pptx')return'application/vnd.openxmlformats-officedocument.presentationml.presentation';
  if(t==='xlsx')return'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet';
  if(t==='docx')return'application/vnd.openxmlformats-officedocument.wordprocessingml.document';
  var n=(r.nom||'').toLowerCase();
  if(/\.pdf$/.test(n))return'application/pdf';
  return'application/octet-stream';
}
function _repDeliver(r,b64){
  try{
    var pure=String(b64).indexOf('base64,')>=0?String(b64).split('base64,')[1]:String(b64);
    var bin=atob(pure.replace(/\s/g,''));
    var arr=new Uint8Array(bin.length);
    for(var i=0;i<bin.length;i++)arr[i]=bin.charCodeAt(i);
    var blob=new Blob([arr],{type:_repMime(r)});
    var url=URL.createObjectURL(blob);
    var a=document.createElement('a');
    a.href=url;a.download=r.nom||'document';
    document.body.appendChild(a);a.click();document.body.removeChild(a);
    setTimeout(function(){URL.revokeObjectURL(url);},4000);
    toast('Document téléchargé ✓','success');
    // cache local : évite de recharger les bins au prochain clic
    try{localStorage.setItem('caremma_rep_'+eKey(CLIENT.email)+'_'+r.id,pure);}catch(e){}
  }catch(e){
    toast('Document illisible. Contactez votre conseiller.','error');
  }
}
function dlRepDocChunks(r){
  // 1) cache local si déjà téléchargé une fois
  try{
    var c=localStorage.getItem('caremma_rep_'+eKey(CLIENT.email)+'_'+r.id);
    if(c){_repDeliver(r,c);return;}
  }catch(e){}
  toast('Préparation du document… (0/'+r.chunks.length+')','info');
  var parts=[];
  var seq=Promise.resolve();
  r.chunks.forEach(function(binId,idx){
    seq=seq.then(function(){
      return jbGet(binId).then(function(d){
        parts[idx]=(d&&(d.chunk||d.data||d.part))||'';
        toast('Préparation du document… ('+(idx+1)+'/'+r.chunks.length+')','info');
        return _jbSleep(900);
      });
    });
  });
  seq.then(function(){
    var full=parts.join('');
    if(!full){toast('Document vide ou indisponible.','error');return;}
    _repDeliver(r,full);
  }).catch(function(e){
    toast('Téléchargement interrompu ('+(e.message||'erreur')+'). Réessayez dans 30 s.','error');
  });
}
function openRapport(id){
  var r=(CLIENT.rapports||[]).find(function(x){return String(x.id)===String(id);});
  if(!r){toast('Document introuvable','error');return;}
  if(!CLIENT.rapportsVus)CLIENT.rapportsVus=[];
  if(CLIENT.rapportsVus.indexOf(String(id))<0){CLIENT.rapportsVus.push(String(id));saveLocal();}
  if(r.url)window.open(r.url,'_blank');
  else if(r.chunks&&r.chunks.length)dlRepDocChunks(r);
  else if(r.data)_repDeliver(r,r.data);
  else toast('Aucun lien associé à ce document pour le moment.','warn');
  renderRapports();
  var rb=document.getElementById('rap-badge');
  if(rb){
    var vus=CLIENT.rapportsVus||[];
    var n=(CLIENT.rapports||[]).filter(function(x){return vus.indexOf(String(x.id))<0;}).length;
    rb.textContent=n;rb.style.display=n?'inline':'none';
  }
}
// Publications globales du CRM (fichier publications.json sur GitHub Pages) —
// diffusées à tous les clients, affichées en tête de "Rapports de gestion".
function renderNotes(){
  var el=document.getElementById('notes-list');if(!el)return;
  var notes=(CLIENT&&CLIENT.notes)||[];
  if(!notes.length){el.innerHTML='';return;}
  var sorted=notes.slice().sort(function(a,b){return(b.ts||0)-(a.ts||0);});
  el.innerHTML='<div class="rap-cat-h">📰 Notes de votre conseiller</div>'
    +sorted.map(function(n){
      return '<div class="card" style="margin-bottom:12px">'
        +'<div style="display:flex;justify-content:space-between;align-items:flex-start;gap:12px">'
          +'<div style="font-size:14px;font-weight:600;color:var(--text)">'+escH(n.titre||'Note')+'</div>'
          +(n.date?'<div style="font-size:11px;color:var(--text3);white-space:nowrap">'+escH(n.date)+'</div>':'')
        +'</div>'
        +(n.contenu?'<div style="font-size:12.5px;color:var(--text2);margin-top:8px;line-height:1.6;white-space:pre-wrap">'+escH(n.contenu)+'</div>':'')
        +(n.url?'<div style="margin-top:10px"><button class="btn btn-primary btn-sm" onclick="window.open(\''+escH(n.url)+'\',\'_blank\')">⬇ Consulter le PDF</button></div>':'')
        +'</div>';
    }).join('');
}

// ═══ MON PATRIMOINE (actifs déclarés par le client) ═══
var PATR_CAT_META={
  immobilier:{label:'Immobilier',icon:'🏠'},
  comptes:{label:'Comptes bancaires',icon:'🏦'},
  assurancevie:{label:'Assurance-vie (externe)',icon:'📄'},
  epargnesal:{label:'Épargne salariale',icon:'💼'},
  autresplacements:{label:'Autres placements',icon:'📊'},
  autres:{label:'Autres',icon:'📦'}
};
function addAsset(){
  var cat=(document.getElementById('patr-cat')||{}).value;
  var libelle=((document.getElementById('patr-libelle')||{}).value||'').trim();
  var valeur=Number((document.getElementById('patr-valeur')||{}).value||0);
  if(!libelle){toast('Merci d\'indiquer un libellé','warn');return;}
  if(!valeur||valeur<=0){toast('Merci d\'indiquer une valeur estimée','warn');return;}
  if(!CLIENT.patrimoineDeclare)CLIENT.patrimoineDeclare=[];
  CLIENT.patrimoineDeclare.push({
    id:'a_'+Date.now(),cat:cat,libelle:libelle,valeur:valeur,
    dateMaj:new Date().toLocaleDateString('fr-FR')
  });
  document.getElementById('patr-libelle').value='';
  document.getElementById('patr-valeur').value='';
  saveLocal();
  renderPatrimoineDeclare();
  pushPatrimoineDeclare();
  toast('Actif ajouté ✓');
}
function deleteAsset(id){
  CLIENT.patrimoineDeclare=(CLIENT.patrimoineDeclare||[]).filter(function(a){return a.id!==id;});
  saveLocal();
  renderPatrimoineDeclare();
  pushPatrimoineDeclare();
}
function editAsset(id){
  var a=(CLIENT.patrimoineDeclare||[]).find(function(x){return x.id===id;});
  if(!a)return;
  var nl=prompt('Libellé :',a.libelle);
  if(nl===null)return;
  var nv=prompt('Valeur estimée (€) :',a.valeur);
  if(nv===null)return;
  nv=Number(nv);
  if(!nl.trim()||!nv||nv<=0){toast('Valeurs invalides','warn');return;}
  a.libelle=nl.trim();a.valeur=nv;a.dateMaj=new Date().toLocaleDateString('fr-FR');
  saveLocal();
  renderPatrimoineDeclare();
  pushPatrimoineDeclare();
}
function pushPatrimoineDeclare(){
  var k=eKey(CLIENT.email);
  jbGet(MSG_BIN).then(function(data){
    if(!data.messages)data.messages={};
    if(!data.messages[k])data.messages[k]={email:CLIENT.email,prenom:CLIENT.prenom,nom:CLIENT.nom};
    data.messages[k].patrimoineDeclare=CLIENT.patrimoineDeclare||[];
    return jbPut(MSG_BIN,data);
  }).catch(function(){/* échec silencieux : les données restent sauvegardées localement */});
}
// ═══ OBJECTIF PERSONNEL ═══
function renderGoalCard(){
  var el=document.getElementById('goal-card');if(!el)return;
  var g=CLIENT.objectifPerso;
  if(!g){
    el.innerHTML='<div class="goal-card">'
      +'<div class="card-title" style="margin-bottom:12px">🎯 Définir un objectif personnel</div>'
      +'<div class="goal-empty-form">'
        +'<div><label>Nom de l\'objectif</label><input type="text" id="goal-nom" placeholder="Ex : Apport résidence secondaire"></div>'
        +'<div><label>Montant cible (€)</label><input type="number" id="goal-montant" placeholder="100000" min="0" step="1000"></div>'
        +'<div><label>Échéance (optionnel)</label><input type="text" id="goal-date" placeholder="Ex : Fin 2028"></div>'
        +'<div><button class="btn btn-primary" onclick="setGoal()">Définir</button></div>'
      +'</div></div>';
    return;
  }
  var totalActuel=currentPortfolioValue()+((CLIENT.patrimoineDeclare||[]).reduce(function(s,a){return s+(a.valeur||0);},0));
  var pct=g.montant?Math.max(0,Math.min(100,Math.round(totalActuel/g.montant*100))):0;
  var reste=Math.max(0,g.montant-totalActuel);
  el.innerHTML='<div class="goal-card">'
    +'<div style="display:flex;justify-content:space-between;align-items:flex-start;gap:12px;flex-wrap:wrap">'
      +'<div><div class="card-title" style="margin-bottom:2px">🎯 '+escH(g.nom)+'</div>'
      +(g.date?'<div style="font-size:11px;color:var(--text3)">Échéance : '+escH(g.date)+'</div>':'')+'</div>'
      +'<div style="text-align:right"><div style="font-size:20px;font-weight:700;color:var(--gold2)">'+pct+'%</div>'
      +'<button class="patr-icon-btn" onclick="deleteGoal()" title="Supprimer l\'objectif" style="margin-top:4px">🗑</button></div>'
    +'</div>'
    +'<div class="milestone-bar-track" style="margin-top:14px"><div class="milestone-bar-fill" style="width:'+pct+'%"></div></div>'
    +'<div style="font-size:11.5px;color:var(--text3);margin-top:6px">'
      +(reste>0?('Encore <b style="color:var(--gold2)">'+fmt(reste)+'</b> pour atteindre '+fmt(g.montant)):'🎉 Objectif atteint, félicitations !')
    +'</div></div>';
}
function setGoal(){
  var nom=((document.getElementById('goal-nom')||{}).value||'').trim();
  var montant=Number((document.getElementById('goal-montant')||{}).value||0);
  var date=((document.getElementById('goal-date')||{}).value||'').trim();
  if(!nom||!montant||montant<=0){toast('Merci d\'indiquer un nom et un montant cible','warn');return;}
  CLIENT.objectifPerso={nom:nom,montant:montant,date:date};
  saveLocal();renderGoalCard();renderKPIs();
  pushClientField('objectifPerso',CLIENT.objectifPerso);
  toast('Objectif défini 🎯');
}
function deleteGoal(){
  CLIENT.objectifPerso=null;
  saveLocal();renderGoalCard();renderKPIs();
  pushClientField('objectifPerso',null);
}
// Pousse un champ isolé de CLIENT vers l'entrée serveur (même pattern que pushPatrimoineDeclare)
function pushClientField(field,value){
  var k=eKey(CLIENT.email);
  jbGet(MSG_BIN).then(function(data){
    if(!data.messages)data.messages={};
    if(!data.messages[k])data.messages[k]={email:CLIENT.email,prenom:CLIENT.prenom,nom:CLIENT.nom};
    data.messages[k][field]=value;
    return jbPut(MSG_BIN,data);
  }).catch(function(){});
}

// ═══ SUGGESTION DE VERSEMENT (nudge doux, jamais automatique) ═══
function renderNudgeCard(){
  var el=document.getElementById('nudge-card');if(!el)return;
  var g=CLIENT.objectifPerso;
  var v=currentPortfolioValue()+((CLIENT.patrimoineDeclare||[]).reduce(function(s,a){return s+(a.valeur||0);},0));
  var text=null,cible=null;
  if(g&&g.montant>v){
    cible=g.montant-v;
    text='Il vous reste <b>'+fmt(cible)+'</b> pour atteindre votre objectif « '+escH(g.nom)+' ». Un versement complémentaire peut vous en rapprocher.';
  } else {
    var mv=nextMilestoneInfo(currentPortfolioValue());
    if(mv.value>0&&mv.next>mv.value){
      cible=mv.next-mv.value;
      text='Encore <b>'+fmt(cible)+'</b> pour passer le cap des '+fmt(mv.next)+'. Parlons-en si un versement complémentaire vous intéresse.';
    }
  }
  if(!text){el.innerHTML='';return;}
  el.innerHTML='<div class="nudge-card">'
    +'<div class="nudge-ico">💡</div>'
    +'<div class="nudge-text">'+text+'</div>'
    +'<button class="btn btn-primary btn-sm" onclick="nudgeContact()">💬 En discuter</button>'
    +'</div>';
}
function nudgeContact(){
  goPage('messages',document.getElementById('nav-messages'));
  setTimeout(function(){
    var ta=document.getElementById('msg-input');
    if(ta&&!ta.value)ta.value='Bonjour, je souhaiterais échanger sur un versement complémentaire. Pouvez-vous me rappeler les modalités ?';
    if(ta)ta.focus();
  },300);
}

// ═══ STREAK DE RÉGULARITÉ (auto-déclaratif, aucune pression) ═══
function monthKey(d){return d.getFullYear()+'-'+String(d.getMonth()+1).padStart(2,'0');}
function last6MonthKeys(){
  var arr=[];var d=new Date();
  for(var i=5;i>=0;i--){var m=new Date(d.getFullYear(),d.getMonth()-i,1);arr.push(monthKey(m));}
  return arr;
}
function renderStreakCard(){
  var el=document.getElementById('streak-card');if(!el)return;
  var months=last6MonthKeys();
  var done=CLIENT.streakMonths||[];
  var curKey=monthKey(new Date());
  var checkedThisMonth=done.indexOf(curKey)>=0;
  // Calcule le streak consécutif en remontant depuis le mois en cours
  var streak=0;
  for(var i=months.length-1;i>=0;i--){
    if(done.indexOf(months[i])>=0)streak++;else break;
  }
  var grid=months.map(function(mk){
    var d=new Date(mk+'-01T00:00:00');
    var label=d.toLocaleDateString('fr-FR',{month:'short'}).replace('.','');
    var isDone=done.indexOf(mk)>=0;
    return '<div class="streak-month'+(isDone?' done':'')+'" title="'+mk+'">'+label+'</div>';
  }).join('');
  el.innerHTML='<div class="streak-card">'
    +'<div style="display:flex;align-items:center;gap:10px">'
      +'<span class="streak-flame">'+(streak>0?'🔥':'💤')+'</span>'
      +'<span class="streak-count">'+streak+' mois'+(streak>1?'s':'')+' d\'affilée</span>'
    +'</div>'
    +'<div style="font-size:11.5px;color:var(--text3);margin-top:6px">Marquez les mois où vous avez mis de l\'argent de côté — pour rester régulier, façon petit défi.</div>'
    +'<div class="streak-grid">'+grid+'</div>'
    +(checkedThisMonth
      ?'<div style="font-size:12px;color:var(--gold2);margin-top:12px">✓ Mois en cours déjà marqué</div>'
      :'<button class="btn btn-ghost btn-sm streak-checkin-btn" onclick="checkinStreak()">✓ J\'ai mis de l\'argent de côté ce mois-ci</button>')
    +'</div>';
}
function checkinStreak(){
  var curKey=monthKey(new Date());
  if(!CLIENT.streakMonths)CLIENT.streakMonths=[];
  if(CLIENT.streakMonths.indexOf(curKey)<0)CLIENT.streakMonths.push(curKey);
  saveLocal();renderStreakCard();
  pushClientField('streakMonths',CLIENT.streakMonths);
  toast('Bien joué ! 🔥');
}

// ═══ GUIDES & SIMULATEURS ═══
// Contenu factuel, régime fiscal 2026. Information générale — pas un conseil personnalisé.
var FICHES=[
  {id:'av',icon:'💰',titre:'Assurance-vie — fiscalité du rachat',body:
    '<ul>'
    +'<li>Avant <b>8 ans</b> : les gains sont soumis au Prélèvement Forfaitaire Unique de <b>30%</b> (12,8% d\'impôt + 17,2% de prélèvements sociaux), avec possibilité d\'opter pour le barème progressif de l\'impôt sur le revenu.</li>'
    +'<li>Après <b>8 ans</b> : abattement annuel sur les gains de <b>4 600€</b> (personne seule) ou <b>9 200€</b> (couple soumis à imposition commune), puis taux réduit de <b>7,5%</b> (dans la limite de 150 000€ de versements cumulés tous contrats, 12,8% au-delà).</li>'
    +'<li>Les prélèvements sociaux de <b>17,2%</b> s\'appliquent dans tous les cas, sur la totalité des gains (l\'abattement ne joue que sur l\'impôt sur le revenu).</li>'
    +'<li>En cas de décès : abattement de <b>152 500€</b> par bénéficiaire sur les primes versées avant 70 ans ; <b>30 500€</b> au global sur les primes versées après 70 ans.</li>'
    +'</ul><div class="fiche-note">Versements antérieurs au 27/09/2017 : régime spécifique (PFL dégressif 35% / 15% / 7,5%).</div>'},
  {id:'per',icon:'🏦',titre:'PER — déduction fiscale et plafonds 2026',body:
    '<ul>'
    +'<li>Les versements volontaires sont déductibles du revenu imposable, dans la limite d\'un plafond annuel indiqué sur votre avis d\'imposition ("Plafond Épargne Retraite").</li>'
    +'<li>Pour un salarié en 2026 : plafond = 10% des revenus professionnels N-1, entre un plancher de <b>4 710€</b> et un maximum de <b>37 680€</b> (8× PASS 2025).</li>'
    +'<li>Les plafonds non utilisés sont reportables sur <b>5 ans</b> (contre 3 ans auparavant) et mutualisables entre conjoints.</li>'
    +'<li>Nouveauté 2026 : la déductibilité des versements prend fin à <b>70 ans</b> (rétroactif au 1er janvier 2026).</li>'
    +'<li>À la sortie (rente ou capital), les prélèvements sociaux sont passés de 17,2% à <b>18,6%</b> depuis 2026.</li>'
    +'</ul><div class="fiche-note">Le gain fiscal à l\'entrée est d\'autant plus important que votre tranche marginale d\'imposition (TMI) est élevée.</div>'},
  {id:'pea',icon:'📈',titre:'PEA — plafonds et fiscalité',body:
    '<ul>'
    +'<li>Plafond de versement : <b>150 000€</b> pour le PEA classique (225 000€ cumulé avec un PEA-PME).</li>'
    +'<li>Après <b>5 ans</b> de détention, les gains sont exonérés d\'impôt sur le revenu (seuls les 17,2% de prélèvements sociaux restent dus).</li>'
    +'<li>Un retrait avant 5 ans entraîne en principe la clôture du plan et une taxation au PFU de 30%.</li>'
    +'</ul>'},
  {id:'pvm',icon:'📊',titre:'Plus-values mobilières (hors PEA)',body:
    '<ul>'
    +'<li>Les plus-values de cession de valeurs mobilières (actions, obligations, comptes-titres) sont soumises au PFU de <b>30%</b> (12,8% + 17,2%).</li>'
    +'<li>Option possible pour le barème progressif de l\'impôt sur le revenu, avec abattements pour durée de détention sur les titres acquis avant 2018.</li>'
    +'</ul>'},
  {id:'succ',icon:'🏛️',titre:'Succession & donation — abattements',body:
    '<ul>'
    +'<li>Abattement en ligne directe (parent-enfant) : <b>100 000€</b> par bénéficiaire, renouvelable tous les <b>15 ans</b>.</li>'
    +'<li>Entre époux ou partenaires de PACS : exonération totale de droits de succession.</li>'
    +'<li>Don familial de sommes d\'argent : <b>31 865€</b> supplémentaires par enfant/petit-enfant majeur, si le donateur a moins de 80 ans.</li>'
    +'<li>Barème progressif en ligne directe : de 5% (jusqu\'à 8 072€) à 45% (au-delà de 1 805 677€).</li>'
    +'<li>Nouveauté 2026 : abattement pour les enfants du conjoint (beaux-enfants) relevé à <b>15 932€</b> (contre 1 594€ auparavant).</li>'
    +'</ul><div class="fiche-note">Les abattements et barèmes sont gelés depuis plusieurs années — l\'inflation augmente donc mécaniquement la charge fiscale réelle au fil du temps.</div>'},
  {id:'ifi',icon:'🏠',titre:'IFI — impôt sur la fortune immobilière',body:
    '<ul>'
    +'<li>Concerne le patrimoine immobilier net taxable supérieur à <b>1,3 million d\'euros</b> au 1er janvier.</li>'
    +'<li>La résidence principale bénéficie d\'un abattement de <b>30%</b> sur sa valeur.</li>'
    +'<li>Sont exclus de l\'assiette : l\'immobilier professionnel, l\'assurance-vie, le PEA, les comptes-titres, les liquidités.</li>'
    +'<li>Barème progressif à partir d\'environ 800 000€ de patrimoine taxable, avec une décote entre 1,3 et 1,4 M€.</li>'
    +'</ul>'}
];
function renderFiches(){
  var el=document.getElementById('fiches-list');if(!el)return;
  el.innerHTML=FICHES.map(function(f){
    return '<div class="fiche" id="fiche-'+f.id+'">'
      +'<div class="fiche-head" onclick="toggleFiche(\''+f.id+'\')">'
        +'<span class="fiche-ico">'+f.icon+'</span>'
        +'<span class="fiche-title">'+escH(f.titre)+'</span>'
        +'<span class="fiche-chevron">▾</span>'
      +'</div>'
      +'<div class="fiche-body"><div class="fiche-body-inner">'+f.body+'</div></div>'
      +'</div>';
  }).join('');
}
function toggleFiche(id){
  var el=document.getElementById('fiche-'+id);if(!el)return;
  el.classList.toggle('open');
}

// ── Simulateur fiscalité rachat assurance-vie ──
function initSimAV(){
  var el=document.getElementById('sim-av');if(!el)return;
  if(el.dataset.init){computeSimAV();return;}
  el.dataset.init='1';
  el.innerHTML=
    '<div class="sim2-grid">'
      +'<div class="sim2-field"><label>Montant du rachat (€)</label><input type="number" id="av-montant" value="20000" min="0" step="500" oninput="computeSimAV()"></div>'
      +'<div class="sim2-field"><label>Part de plus-value dans le rachat (%)</label><input type="number" id="av-pctpv" value="30" min="0" max="100" step="1" oninput="computeSimAV()"></div>'
      +'<div class="sim2-field"><label>Total de vos versements, tous contrats (€)</label><input type="number" id="av-totalvers" value="80000" min="0" step="1000" oninput="computeSimAV()"></div>'
      +'<div class="sim2-field"><label>&nbsp;</label><div style="font-size:11px;color:var(--text3);padding-top:8px">Détermine le taux applicable au-delà de 150 000€</div></div>'
    +'</div>'
    +'<div class="sim2-pills">'
      +'<button type="button" class="rap-pill active" data-anc="1" onclick="setSimAVPill(this,\'anc\')">Contrat ≥ 8 ans</button>'
      +'<button type="button" class="rap-pill" data-anc="0" onclick="setSimAVPill(this,\'anc\')">Contrat &lt; 8 ans</button>'
    +'</div>'
    +'<div class="sim2-pills">'
      +'<button type="button" class="rap-pill active" data-couple="0" onclick="setSimAVPill(this,\'couple\')">Personne seule</button>'
      +'<button type="button" class="rap-pill" data-couple="1" onclick="setSimAVPill(this,\'couple\')">Couple (imposition commune)</button>'
    +'</div>'
    +'<div class="sim-result"><div style="font-size:11px;color:var(--text3);margin-bottom:4px">Montant net perçu (estimation)</div><div class="sim-result-value" id="av-net">—</div></div>'
    +'<div class="sim-legend" id="av-detail" style="margin-top:12px"></div>'
    +'<div style="font-size:10.5px;color:var(--text3);margin-top:12px;line-height:1.5">Estimation indicative hors option barème progressif de l\'impôt sur le revenu, qui peut être plus favorable selon votre situation. Ne remplace pas une analyse personnalisée.</div>';
  computeSimAV();
}
function setSimAVPill(btn,group){
  var siblings=btn.parentElement.querySelectorAll('.rap-pill');
  for(var i=0;i<siblings.length;i++)siblings[i].classList.remove('active');
  btn.classList.add('active');
  computeSimAV();
}
function computeSimAV(){
  var montant=Number((document.getElementById('av-montant')||{}).value||0);
  var pctPv=Number((document.getElementById('av-pctpv')||{}).value||0)/100;
  var totalVers=Number((document.getElementById('av-totalvers')||{}).value||0);
  var anc8=document.querySelector('[data-anc].active');
  var isAnc8=anc8?anc8.dataset.anc==='1':true;
  var coupleBtn=document.querySelector('[data-couple].active');
  var isCouple=coupleBtn?coupleBtn.dataset.couple==='1':false;

  var gains=montant*pctPv;
  var abattement=0,baseImposable=gains,tauxIR=0.128;
  if(isAnc8){
    abattement=Math.min(gains,isCouple?9200:4600);
    baseImposable=Math.max(0,gains-abattement);
    tauxIR=totalVers<=150000?0.075:0.128;
  }
  var impotIR=baseImposable*tauxIR;
  var ps=gains*0.172;
  var totalPrelevements=impotIR+ps;
  var net=montant-totalPrelevements;

  var netEl=document.getElementById('av-net');if(netEl)netEl.textContent=fmt(Math.round(net));
  var detailEl=document.getElementById('av-detail');
  if(detailEl)detailEl.innerHTML=
    '<span>Gains dans le rachat : '+fmt(Math.round(gains))+'</span>'
    +(abattement>0?'<span>Abattement appliqué : -'+fmt(Math.round(abattement))+'</span>':'')
    +'<span>Impôt sur le revenu ('+(tauxIR*100).toFixed(1)+'%) : '+fmt(Math.round(impotIR))+'</span>'
    +'<span>Prélèvements sociaux (17,2%) : '+fmt(Math.round(ps))+'</span>'
    +'<span style="color:var(--gold2)">Total prélèvements : '+fmt(Math.round(totalPrelevements))+'</span>';
}

// ── Simulateur économie d'impôt PER ──
function initSimPER(){
  var el=document.getElementById('sim-per');if(!el)return;
  if(el.dataset.init){computeSimPER();return;}
  el.dataset.init='1';
  el.innerHTML=
    '<div class="sim2-grid">'
      +'<div class="sim2-field"><label>Versement PER envisagé (€)</label><input type="number" id="per-versement" value="3000" min="0" step="100" oninput="computeSimPER()"></div>'
      +'<div class="sim2-field"><label>Votre tranche marginale d\'imposition (TMI)</label>'
        +'<select id="per-tmi" onchange="computeSimPER()">'
          +'<option value="0">0%</option><option value="0.11">11%</option><option value="0.30" selected>30%</option><option value="0.41">41%</option><option value="0.45">45%</option>'
        +'</select></div>'
    +'</div>'
    +'<div class="sim-result"><div style="font-size:11px;color:var(--text3);margin-bottom:4px">Économie d\'impôt estimée</div><div class="sim-result-value" id="per-economie">—</div></div>'
    +'<div class="sim-legend" id="per-detail" style="margin-top:12px"></div>'
    +'<div style="font-size:10.5px;color:var(--text3);margin-top:12px;line-height:1.5">Simulation indicative — le plafond de déduction réel dépend de vos revenus et figure sur votre avis d\'imposition (plancher 4 710€, jusqu\'à 37 680€ pour un salarié en 2026). Déductibilité supprimée à partir de 70 ans.</div>';
  computeSimPER();
}
function computeSimPER(){
  var versement=Number((document.getElementById('per-versement')||{}).value||0);
  var tmi=Number((document.getElementById('per-tmi')||{}).value||0);
  var economie=versement*tmi;
  var coutReel=versement-economie;
  var ecoEl=document.getElementById('per-economie');if(ecoEl)ecoEl.textContent=fmt(Math.round(economie));
  var detEl=document.getElementById('per-detail');
  if(detEl)detEl.innerHTML=
    '<span>Versement brut : '+fmt(versement)+'</span>'
    +'<span>Économie d\'impôt (TMI '+(tmi*100)+'%) : '+fmt(Math.round(economie))+'</span>'
    +'<span style="color:var(--gold2)">Coût réel après économie d\'impôt : '+fmt(Math.round(coutReel))+'</span>';
}

function renderPatrimoineDeclare(){
  var totalGere=currentPortfolioValue();
  var assets=CLIENT.patrimoineDeclare||[];
  var totalDeclare=assets.reduce(function(s,a){return s+(a.valeur||0);},0);
  var eG=document.getElementById('patr-gere');if(eG)eG.textContent=totalGere?fmt(totalGere):'—';
  var eD=document.getElementById('patr-declare');if(eD)eD.textContent=fmt(totalDeclare);
  var eT=document.getElementById('patr-total');if(eT)eT.textContent=fmt(totalGere+totalDeclare);

  // Mini donut par catégorie
  var donutEl=document.getElementById('patrimoine-donut');
  if(donutEl){
    if(!assets.length){donutEl.innerHTML='';}
    else{
      var byCat={};
      assets.forEach(function(a){byCat[a.cat]=(byCat[a.cat]||0)+(a.valeur||0);});
      var offset=0;
      var stops=Object.keys(byCat).map(function(k,i){
        var pct=byCat[k]/totalDeclare*100;
        var col=DONUT_PALETTE[i%DONUT_PALETTE.length];
        var seg=col+' '+offset+'% '+(offset+pct)+'%';
        offset+=pct;
        return seg;
      }).join(',');
      var legend=Object.keys(byCat).map(function(k,i){
        var pct=Math.round(byCat[k]/totalDeclare*1000)/10;
        var col=DONUT_PALETTE[i%DONUT_PALETTE.length];
        var meta=PATR_CAT_META[k]||{label:k};
        return '<div class="donut-legend-row"><span class="donut-dot" style="background:'+col+'"></span>'+meta.icon+' '+escH(meta.label)+'<span class="donut-legend-val">'+pct+'%</span></div>';
      }).join('');
      donutEl.innerHTML='<div class="card"><div class="card-title">Répartition de vos actifs déclarés</div>'
        +'<div class="donut-wrap">'
          +'<div class="donut-svg" style="width:120px;height:120px;border-radius:50%;background:conic-gradient('+stops+')">'
            +'<div style="width:64px;height:64px;border-radius:50%;background:var(--navy2);margin:28px;"></div>'
          +'</div>'
          +'<div class="donut-legend">'+legend+'</div>'
        +'</div></div>';
    }
  }

  // Liste des actifs groupés par catégorie
  var listEl=document.getElementById('patrimoine-list');if(!listEl)return;
  if(!assets.length){
    listEl.innerHTML='<div class="card" style="text-align:center;padding:36px 20px;color:var(--text3)">'
      +'<div style="font-size:34px;margin-bottom:10px">🏛️</div>'
      +'<div style="font-size:13.5px;font-weight:600;color:var(--text2);margin-bottom:6px">Aucun actif déclaré pour le moment</div>'
      +'<div style="font-size:12px;line-height:1.6">Ajoutez vos biens (immobilier, comptes, assurance-vie...) pour une vue complète de votre patrimoine.</div>'
      +'</div>';
    return;
  }
  var groups={};
  assets.forEach(function(a){if(!groups[a.cat])groups[a.cat]=[];groups[a.cat].push(a);});
  var html='';
  Object.keys(PATR_CAT_META).forEach(function(k){
    if(!groups[k]||!groups[k].length)return;
    var meta=PATR_CAT_META[k];
    html+='<div class="rap-cat-h">'+meta.icon+' '+meta.label+'</div>';
    html+=groups[k].map(function(a){
      return '<div class="patr-row">'
        +'<div class="patr-ico">'+meta.icon+'</div>'
        +'<div style="flex:1;min-width:0">'
          +'<div style="font-size:13px;font-weight:600;color:var(--text)">'+escH(a.libelle)+'</div>'
          +'<div style="font-size:11px;color:var(--text3);margin-top:2px">Mis à jour le '+escH(a.dateMaj||'')+'</div>'
        +'</div>'
        +'<div style="font-size:14px;font-weight:600;color:var(--text)">'+fmt(a.valeur)+'</div>'
        +'<div class="patr-row-actions">'
          +'<button class="patr-icon-btn" onclick="editAsset(\''+a.id+'\')" title="Modifier">✎</button>'
          +'<button class="patr-icon-btn" onclick="deleteAsset(\''+a.id+'\')" title="Supprimer">🗑</button>'
        +'</div>'
        +'</div>';
    }).join('');
  });
  listEl.innerHTML=html;
}

function renderRapports(){
  var list=document.getElementById('rapports-list');if(!list)return;
  var all=(CLIENT&&CLIENT.rapports)||[];
  var vus=(CLIENT&&CLIENT.rapportsVus)||[];

  // Pills de filtre (générées à partir des catégories réellement présentes)
  var filtersEl=document.getElementById('rap-filters');
  if(filtersEl){
    var catsPresent={};
    all.forEach(function(r){catsPresent[rapCatKey(r.cat)]=true;});
    var pills='<button class="rap-pill'+(_rapFilter==='tous'?' active':'')+'" onclick="setRapFilter(\'tous\')">Tous ('+all.length+')</button>';
    Object.keys(_rapCatMeta).forEach(function(k){
      if(!catsPresent[k])return;
      var n=all.filter(function(r){return rapCatKey(r.cat)===k;}).length;
      pills+='<button class="rap-pill'+(_rapFilter===k?' active':'')+'" onclick="setRapFilter(\''+k+'\')">'+_rapCatMeta[k].icon+' '+_rapCatMeta[k].label+' ('+n+')</button>';
    });
    filtersEl.innerHTML=pills;
  }

  var q=((document.getElementById('rap-search')||{}).value||'').trim().toLowerCase();
  var filtered=all.filter(function(r){
    if(_rapFilter!=='tous'&&rapCatKey(r.cat)!==_rapFilter)return false;
    if(q&&(r.nom||'').toLowerCase().indexOf(q)<0)return false;
    return true;
  });

  if(!all.length){
    list.innerHTML='<div class="card" style="text-align:center;padding:40px 20px;color:var(--text3)">'
      +'<div style="font-size:36px;margin-bottom:12px">📚</div>'
      +'<div style="font-size:14px;font-weight:600;color:var(--text2);margin-bottom:6px">Aucun rapport pour le moment</div>'
      +'<div style="font-size:12px;line-height:1.6">Votre conseiller mettra à votre disposition vos rapports de gestion et documents ici.</div>'
      +'</div>';
    return;
  }
  if(!filtered.length){
    list.innerHTML='<div class="card" style="text-align:center;padding:30px 20px;color:var(--text3);font-size:13px">Aucun document ne correspond à votre recherche.</div>';
    return;
  }

  // Regroupement par catégorie, tri du plus récent au plus ancien
  function toTime(d){var p=(d||'').split('/');return p.length===3?new Date(p[2],p[1]-1,p[0]).getTime():0;}
  var groups={};
  filtered.forEach(function(r){var k=rapCatKey(r.cat);if(!groups[k])groups[k]=[];groups[k].push(r);});
  var html='';
  Object.keys(_rapCatMeta).forEach(function(k){
    if(!groups[k]||!groups[k].length)return;
    var items=groups[k].slice().sort(function(a,b){return toTime(b.date)-toTime(a.date);});
    html+='<div class="rap-cat-h">'+_rapCatMeta[k].icon+' '+_rapCatMeta[k].label+'</div>';
    html+=items.map(function(r){
      var isNew=vus.indexOf(String(r.id))<0;
      return '<div class="rap-row">'
        +'<div class="rap-icon">'+rapIcon(r.type)+'</div>'
        +'<div style="flex:1;min-width:0">'
          +'<div style="font-size:13px;font-weight:600;color:var(--text)">'+escH(r.nom)+(isNew?'<span class="rap-new">Nouveau</span>':'')+'</div>'
          +'<div style="font-size:11px;color:var(--text3);margin-top:2px">'+escH(r.date||'')+(r.taille?' · '+escH(r.taille):'')+(r.type?' · '+escH(r.type.toUpperCase()):'')+'</div>'
        +'</div>'
        +'<button class="btn btn-primary btn-sm" onclick="openRapport(\''+escH(String(r.id))+'\')">⬇ Télécharger</button>'
        +'</div>';
    }).join('');
  });
  list.innerHTML=html;
}

function renderMsgs(){
  var list=document.getElementById('msg-list');if(!list)return;
  var msgs=CLIENT.msgs||[];
  if(!msgs.length){
    list.innerHTML='<div class="msg-empty">Aucun message pour l\'instant.<br>Posez vos questions directement à votre conseiller.</div>';
    return;
  }
  list.innerHTML=msgs.map(function(m){
    var cls=m.from==='client'?'client':'conseiller';
    var who=m.from==='client'?CLIENT.prenom:'Marc Reverseau';
    return'<div class="msg '+cls+'"><div>'+escH(m.text)+'</div><div class="msg-meta">'+who+' · '+m.date+'</div></div>';
  }).join('');
  list.scrollTop=list.scrollHeight;
  // Marquer comme lus
  (CLIENT.msgs||[]).forEach(function(m){if(m.from!=='client')m.read=true;});
  saveLocal();
}

function sendMsg(){
  var inp=document.getElementById('msg-input');
  var text=(inp&&inp.value||'').trim();if(!text)return;
  inp.value='';
  var msg={id:Date.now(),from:'client',text:text,
    date:new Date().toLocaleString('fr-FR',{hour:'2-digit',minute:'2-digit',day:'2-digit',month:'2-digit'}),read:false};
  if(!CLIENT.msgs)CLIENT.msgs=[];
  CLIENT.msgs.push(msg);saveLocal();renderMsgs();
  jbGet(MSG_BIN).then(function(data){
    var k=eKey(CLIENT.email);
    if(!data.messages)data.messages={};
    if(!data.messages[k])data.messages[k]={prenom:CLIENT.prenom,nom:CLIENT.nom,email:CLIENT.email,msgs:[],docs:[]};
    if(!data.messages[k].msgs)data.messages[k].msgs=[];
    data.messages[k].msgs.push(msg);return jbPut(MSG_BIN,data);
  }).then(function(){toast('Message envoyé ✓','success');})
  .catch(function(){toast('Sauvegardé localement ✓','success');});
}

// ═══ QUESTIONNAIRES ═══
function decodeB64(b64){
  return decodeURIComponent(Array.from(atob(b64)).map(function(c){return'%'+c.charCodeAt(0).toString(16).padStart(2,'0');}).join(''));
}

function renderObjectifs(){
  var el=document.getElementById('obj-content');if(!el||el._loaded)return;
  var decoded=decodeB64(_PHTML_B64);
  var tmp=document.createElement('div');tmp.innerHTML=decoded;
  var ps2=tmp.querySelector('#ps2');
  if(ps2){
    ps2.style.display='block';
    // Supprimer navigation par étapes - tout afficher d'un coup
    ps2.querySelectorAll('.q-nav-btns,.progress-steps,.q-progress').forEach(function(b){b.remove();});
    // Forcer toutes les sections visibles
    ps2.querySelectorAll('.q-section,[id^="qo-s"]').forEach(function(s){
      s.style.display='block';
      s.style.visibility='visible';
      s.style.opacity='1';
      s.removeAttribute('hidden');
    });
    // Remplacer le bouton "Étape suivante" final par "Envoyer à mon conseiller"
    ps2.querySelectorAll('button').forEach(function(btn){
      var txt = btn.textContent||'';
      if(txt.indexOf('suivante')>=0||txt.indexOf('Étape')>=0||txt.indexOf('précédente')>=0||txt.indexOf('préc.')>=0){
        btn.remove();
      }
    });
  }
  el.innerHTML=ps2?ps2.outerHTML:'';el._loaded=true;
  restoreFormData(el,'objectifs');
  attachAutoSave(el,'objectifs');
  updateProgress(el,'prog-obj','prog-obj-lbl');
  // Message de transition
  var nav=document.createElement('div');
  nav.style.cssText='margin-top:20px;padding:14px 18px;background:rgba(201,168,76,0.06);border:1px solid rgba(201,168,76,0.2);border-radius:10px;font-size:13px;color:var(--text2);line-height:1.6';
  nav.innerHTML='<strong style="color:var(--gold2)">✓ Questionnaire objectifs complété</strong><br>Rendez-vous dans <strong>Connaissance &amp; Compétence</strong> pour finaliser votre dossier et le signer.';
  el.appendChild(nav);
  // Init sélection visuelle des radio-opts
  setTimeout(function(){ initRadioOpts(el); }, 100);
}

function renderConnaissance(){
  var el=document.getElementById('conn-content');if(!el||el._loaded)return;
  var decoded=decodeB64(_CONNAISSANCE_B64);
  var tmp=document.createElement('div');tmp.innerHTML=decoded;
  // Afficher ps3 ET ps4
  var ps3=tmp.querySelector('#ps3');
  var ps4=tmp.querySelector('#ps4');
  var html='';
  if(ps3){ps3.style.display='block';ps3.querySelectorAll('.q-nav-btns').forEach(function(b){b.remove();});html+=ps3.outerHTML;}
  if(ps4){ps4.style.display='block';ps4.querySelectorAll('.q-nav-btns').forEach(function(b){b.remove();});html+=ps4.outerHTML;}
  el.innerHTML=html;el._loaded=true;
  restoreFormData(el,'connaissance');
  attachAutoSave(el,'connaissance');
  // Init radio-opts cliquables
  setTimeout(function(){ initRadioOpts(el); }, 50);
  updateProgress(el,'prog-conn','prog-conn-lbl');
  appendSendBtn(el,'connaissance');
}

function restoreFormData(el,key){
  var pd=(CLIENT.parcoursData&&CLIENT.parcoursData[key])||{};
  Object.keys(pd).forEach(function(id){
    var e=el.querySelector('#'+id);if(!e)return;
    if(e.type==='checkbox'||e.type==='radio')e.checked=pd[id];else e.value=pd[id];
  });
}

function attachAutoSave(el,key){
  el.querySelectorAll('input,select,textarea').forEach(function(inp){
    inp.addEventListener('change',function(){
      if(!CLIENT.parcoursData)CLIENT.parcoursData={};
      if(!CLIENT.parcoursData[key])CLIENT.parcoursData[key]={};
      if(this.id)CLIENT.parcoursData[key][this.id]=(this.type==='checkbox'||this.type==='radio')?this.checked:this.value;
      saveLocal();updateProgress(el,'prog-'+(key==='objectifs'?'obj':'conn'),'prog-'+(key==='objectifs'?'obj':'conn')+'-lbl');
    });
  });
}

function updateProgress(el,barId,lblId){
  var inputs=el.querySelectorAll('input:not([type=submit]),select,textarea');
  var total=inputs.length,filled=0;
  inputs.forEach(function(inp){
    if(inp.type==='radio'){if(el.querySelectorAll('input[name="'+inp.name+'"]:checked').length)filled++;}
    else if(inp.type==='checkbox'){if(inp.checked)filled++;}
    else if(inp.value)filled++;
  });
  // Dédupliquer les radios
  var radioNames={};inputs.forEach(function(inp){if(inp.type==='radio')radioNames[inp.name]=true;});
  var radioCount=Object.keys(radioNames).length;
  var nonRadioTotal=total-el.querySelectorAll('input[type=radio]').length;
  var radioFilled=0;Object.keys(radioNames).forEach(function(n){if(el.querySelector('input[name="'+n+'"]:checked'))radioFilled++;});
  var nonRadioFilled=0;inputs.forEach(function(inp){if(inp.type!=='radio'&&inp.value)nonRadioFilled++;});
  var pct=total?Math.min(100,Math.round((radioFilled+nonRadioFilled)/(radioCount+nonRadioTotal)*100)):0;
  var bar=document.getElementById(barId);if(bar)bar.style.width=pct+'%';
  var lbl=document.getElementById(lblId);if(lbl)lbl.textContent='Complétion : '+pct+'%';
}

function appendSignAndSendBtn(el){
  var nav=document.createElement('div');
  nav.style.cssText='margin-top:28px;padding:20px;border:1px solid var(--bdr-gold);border-radius:12px;background:rgba(201,168,76,0.04)';

  var title=document.createElement('div');
  title.style.cssText='font-size:13px;font-weight:600;color:var(--gold2);margin-bottom:6px';
  title.textContent='✅ Questionnaires complétés';
  nav.appendChild(title);

  var sub=document.createElement('div');
  sub.style.cssText='font-size:12px;color:var(--text3);margin-bottom:16px;line-height:1.5';
  sub.textContent='Signez électroniquement pour valider et envoyer l\'intégralité de votre dossier (objectifs + connaissance & compétence) à votre conseiller.';
  nav.appendChild(sub);

  var btn=document.createElement('button');
  btn.className='btn btn-primary';
  btn.innerHTML='✍️ Signer et envoyer mon dossier complet';
  btn.onclick=function(){
    // Collecter données objectifs ET connaissance
    var dataObj={};
    var elObj=document.getElementById('obj-content');
    if(elObj) elObj.querySelectorAll('input,select,textarea').forEach(function(inp){
      if(inp.id) dataObj[inp.id]=(inp.type==='checkbox'||inp.type==='radio')?inp.checked:inp.value;
    });
    var dataConn={};
    el.querySelectorAll('input,select,textarea').forEach(function(inp){
      if(inp.id) dataConn[inp.id]=(inp.type==='checkbox'||inp.type==='radio')?inp.checked:inp.value;
    });
    if(!CLIENT.parcoursData) CLIENT.parcoursData={};
    CLIENT.parcoursData.objectifs=Object.assign(CLIENT.parcoursData.objectifs||{},dataObj);
    CLIENT.parcoursData.connaissance=Object.assign(CLIENT.parcoursData.connaissance||{},dataConn);
    saveLocal();
    // Ouvrir le flux signature
    openSignAndSend('connaissance',{objectifs:dataObj,connaissance:dataConn},el);
  };
  nav.appendChild(btn);
  el.appendChild(nav);

  var sigZone=document.createElement('div');
  sigZone.id='sig-inline-connaissance';
  sigZone.style.display='none';
  el.appendChild(sigZone);
}


function appendSendBtn(el,key){
  var nav=document.createElement('div');
  nav.style.cssText='margin-top:28px;padding:20px;border:1px solid var(--bdr-gold);border-radius:12px;background:rgba(201,168,76,0.04)';
  var title=document.createElement('div');
  title.style.cssText='font-size:13px;font-weight:600;color:var(--gold2);margin-bottom:6px';
  title.textContent='✅ Questionnaire complété';
  nav.appendChild(title);
  var sub=document.createElement('div');
  sub.style.cssText='font-size:12px;color:var(--text3);margin-bottom:16px;line-height:1.5';
  sub.textContent="Avant d'envoyer vos réponses à votre conseiller, veuillez valider votre identité par signature électronique.";
  nav.appendChild(sub);
  var btn=document.createElement('button');
  btn.className='btn btn-primary';
  btn.innerHTML='✍️ Signer et envoyer à mon conseiller';
  btn.onclick=function(){
    var data={};
    el.querySelectorAll('input,select,textarea').forEach(function(inp){
      if(inp.id) data[inp.id]=(inp.type==='checkbox'||inp.type==='radio')?inp.checked:inp.value;
    });
    if(!CLIENT.parcoursData) CLIENT.parcoursData={};
    CLIENT.parcoursData[key]=Object.assign(CLIENT.parcoursData[key]||{},data);
    saveLocal();
    openSignAndSend(key,data,el);
  };
  nav.appendChild(btn);
  el.appendChild(nav);
  var sigZone=document.createElement('div');
  sigZone.id='sig-inline-'+key;
  sigZone.style.display='none';
  el.appendChild(sigZone);
}

var _sendKey=null,_sendData=null,_sendEl=null,_sendSigCode=null;

function openSignAndSend(key,data,el){
  _sendKey=key;_sendData=data;_sendEl=el;_sendSigCode=null;
  var zone=document.getElementById('sig-inline-'+key);
  if(!zone)return;
  zone.style.display='block';
  zone.scrollIntoView({behavior:'smooth',block:'center'});
  renderSignStep(1);
}

function renderSignStep(n){
  var zone=document.getElementById('sig-inline-'+(_sendKey||''));
  if(!zone)return;
  var stepBar=function(active){
    var steps=['① Email','② Code','③ Signature'];
    return '<div style="display:flex;gap:6px;margin-bottom:18px">'+steps.map(function(s,i){
      var done=i+1<active,cur=i+1===active;
      var bg=done?'rgba(34,197,94,0.1)':cur?'rgba(201,168,76,0.12)':'rgba(255,255,255,0.03)';
      var bc=done?'rgba(34,197,94,0.3)':cur?'var(--bdr-gold)':'var(--bdr)';
      var col=done?'var(--green)':cur?'var(--gold2)':'var(--text3)';
      var lbl=done?'✓ '+s.slice(2):s;
      return '<div style="flex:1;text-align:center;padding:8px;border-radius:6px;font-size:11px;font-weight:600;background:'+bg+';border:1px solid '+bc+';color:'+col+'">'+lbl+'</div>';
    }).join('')+'</div>';
  };
  var wrap='<div style="background:var(--navy2);border:1px solid var(--bdr-gold);border-radius:12px;padding:20px;margin-top:12px">';
  if(n===1){
    zone.innerHTML=wrap+stepBar(1)
      +'<p style="font-size:13px;color:var(--text2);margin-bottom:16px;line-height:1.6">Un code de vérification va être envoyé à<br><strong style="color:var(--gold2)">'+CLIENT.email+'</strong></p>'
      +'<div style="display:flex;gap:8px;flex-wrap:wrap">'
      +'<button class="btn btn-primary" onclick="sendSignAndSendCode()">📧 Envoyer le code</button>'
      +'<button class="btn btn-ghost btn-sm" onclick="cancelSignAndSend()">Annuler</button>'
      +'</div></div>';
  } else if(n===2){
    zone.innerHTML=wrap+stepBar(2)
      +'<p style="font-size:13px;color:var(--text2);margin-bottom:14px">Saisissez le code reçu par email :</p>'
      +'<div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap;margin-bottom:10px">'
      +'<input id="sas-code-input" class="fc" type="text" inputmode="numeric" maxlength="6" placeholder="000000" style="max-width:150px;font-size:20px;letter-spacing:6px;text-align:center">'
      +'<button class="btn btn-primary" onclick="verifySignAndSendCode()">Vérifier →</button>'
      +'</div>'
      +'<div id="sas-code-err" style="color:var(--red);font-size:12px;display:none;margin-bottom:10px">❌ Code incorrect.</div>'
      +'<div style="display:flex;gap:8px;flex-wrap:wrap">'
      +'<button class="btn btn-ghost btn-sm" onclick="sendSignAndSendCode()">↻ Renvoyer</button>'
      +'<button class="btn btn-ghost btn-sm" onclick="cancelSignAndSend()">Annuler</button>'
      +'</div></div>';
  } else if(n===3){
    zone.innerHTML=wrap+stepBar(3)
      +'<p style="font-size:13px;color:var(--green);font-weight:600;margin-bottom:12px">✓ Identité vérifiée — Tracez votre signature</p>'
      +'<canvas id="sas-canvas" style="border:1px solid var(--bdr-gold);border-radius:8px;background:white;width:100%;height:130px;display:block;cursor:crosshair;touch-action:none;margin-bottom:14px"></canvas>'
      +'<div style="display:flex;gap:8px;flex-wrap:wrap">'
      +'<button class="btn btn-ghost btn-sm" onclick="clearSasCanvas()">🗑 Effacer</button>'
      +'<button class="btn btn-primary" onclick="confirmSignAndSend()">✅ Valider et envoyer</button>'
      +'<button class="btn btn-ghost btn-sm" onclick="cancelSignAndSend()">Annuler</button>'
      +'</div></div>';
    setTimeout(function(){
      var canvas=document.getElementById('sas-canvas');
      if(!canvas)return;
      var rect=canvas.getBoundingClientRect();
      canvas.width=Math.round(rect.width)||700;canvas.height=130;
      var ctx=canvas.getContext('2d');
      ctx.strokeStyle='#0c1a2e';ctx.lineWidth=2.5;ctx.lineCap='round';ctx.lineJoin='round';
      canvas._ctx=ctx;canvas._drawing=false;
      canvas.onmousedown=function(e){this._drawing=true;ctx.beginPath();ctx.moveTo(e.offsetX,e.offsetY);};
      canvas.onmousemove=function(e){if(!this._drawing)return;ctx.lineTo(e.offsetX,e.offsetY);ctx.stroke();};
      canvas.onmouseup=canvas.onmouseleave=function(){this._drawing=false;};
      canvas.ontouchstart=function(e){e.preventDefault();this._drawing=true;var t=e.touches[0];var r=canvas.getBoundingClientRect();ctx.beginPath();ctx.moveTo((t.clientX-r.left)*(canvas.width/r.width),(t.clientY-r.top)*(canvas.height/r.height));};
      canvas.ontouchmove=function(e){e.preventDefault();if(!this._drawing)return;var t=e.touches[0];var r=canvas.getBoundingClientRect();ctx.lineTo((t.clientX-r.left)*(canvas.width/r.width),(t.clientY-r.top)*(canvas.height/r.height));ctx.stroke();};
      canvas.ontouchend=function(){this._drawing=false;};
    },100);
  }
}

async function sendSignAndSendCode(){
  _sendSigCode=Math.floor(100000+Math.random()*900000).toString();
  renderSignStep(2);
  try{
    await sendEmailJS(EJS_SERVICE_SIG,EJS_TPL_SIG,{
      to_email:CLIENT.email,to_name:CLIENT.prenom+' '+CLIENT.nom,
      from_name:'Caremma Finance',reply_to:'marc.reverseau@caremmafinance.com',
      client_prenom:CLIENT.prenom,access_code:_sendSigCode,
      subject:'Code de signature — Caremma Finance',
      message:"Votre code pour valider l'envoi de votre questionnaire : "+_sendSigCode
    });
    toast('Code envoyé à '+CLIENT.email+' ✓','success');
  }catch(e){toast('Erreur envoi : '+(e.text||e.message),'error');renderSignStep(1);}
}

function verifySignAndSendCode(){
  var entered=(document.getElementById('sas-code-input').value||'').trim();
  if(entered===_sendSigCode){
    document.getElementById('sas-code-err').style.display='none';
    renderSignStep(3);
  } else {
    document.getElementById('sas-code-err').style.display='block';
    document.getElementById('sas-code-input').value='';
  }
}

function clearSasCanvas(){
  var c=document.getElementById('sas-canvas');
  if(c&&c._ctx)c._ctx.clearRect(0,0,c.width,c.height);
}

async function confirmSignAndSend(){
  var canvas=document.getElementById('sas-canvas');
  if(!canvas){toast('Erreur canvas','error');return;}
  var px=canvas._ctx.getImageData(0,0,canvas.width,canvas.height).data;
  var ok=false;for(var i=3;i<px.length;i+=4)if(px[i]>0){ok=true;break;}
  if(!ok){toast('Veuillez tracer votre signature','error');return;}
  var sigData=canvas.toDataURL('image/png');
  var sigDate=new Date().toLocaleString('fr-FR');
  if(!CLIENT.parcoursData)CLIENT.parcoursData={};
  CLIENT.parcoursData['signature_'+_sendKey]=sigData;
  CLIENT.parcoursData['signature_'+_sendKey+'_date']=sigDate;
  saveLocal();

  var zone=document.getElementById('sig-inline-'+_sendKey);
  if(zone)zone.innerHTML='<div style="background:var(--navy2);border:1px solid var(--bdr-gold);border-radius:12px;padding:24px;text-align:center"><div style="font-size:24px;margin-bottom:10px">⏳</div><div style="font-size:14px;font-weight:600;color:var(--gold2)">Génération du récapitulatif...</div></div>';

  // Sauvegarder dans JSONBin en arrière-plan (non bloquant)
  jbGet(MSG_BIN).then(function(d){
    var k=eKey(CLIENT.email);
    if(!d.messages)d.messages={};
    if(!d.messages[k])d.messages[k]={prenom:CLIENT.prenom,nom:CLIENT.nom,email:CLIENT.email,msgs:[],docs:[]};
    d.messages[k][_sendKey]=_sendData;
    d.messages[k][_sendKey+'Envoye']=today();
    d.messages[k][_sendKey+'Signature']=sigDate;
    return jbPut(MSG_BIN,d);
  }).catch(function(){});

  // Générer et ouvrir le PDF + mailto
  setTimeout(function(){
    openRecapAndMail(sigData, sigDate, _sendKey);
    if(zone)zone.innerHTML='<div style="background:rgba(34,197,94,0.08);border:1px solid rgba(34,197,94,0.3);border-radius:12px;padding:24px;text-align:center">'
      +'<div style="font-size:32px;margin-bottom:10px">✅</div>'
      +'<div style="font-size:15px;font-weight:600;color:var(--green);margin-bottom:6px">Questionnaire signé</div>'
      +'<div style="font-size:12px;color:var(--text3);margin-bottom:12px">Signé le '+sigDate+'</div>'
      +'<button class="btn btn-primary" onclick="openRecapAndMail(CLIENT.parcoursData[\'signature_'+_sendKey+'\'],CLIENT.parcoursData[\'signature_'+_sendKey+'_date\'],\''+_sendKey+'\')">📧 Envoyer à mon conseiller</button>'
      +'</div>';
    toast('Signature validée ✓','success');
  }, 300);
}

function cancelSignAndSend(){
  var zone=document.getElementById('sig-inline-'+(_sendKey||'objectifs'));
  if(zone)zone.style.display='none';
  _sendKey=null;_sendData=null;_sendEl=null;_sendSigCode=null;
}


function openRecapAndMail(sigData, sigDate, key){
  var today2 = new Date().toLocaleDateString('fr-FR',{year:'numeric',month:'long',day:'numeric'});
  var pd = CLIENT.parcoursData||{};
  var obj = pd.objectifs||{};
  var conn = pd.connaissance||{};

  var sc = document.getElementById('q-score-val')||document.getElementById('result-score-kn');
  var cc = document.getElementById('q-profil-val')||document.getElementById('result-cat-kn');
  var sr = document.getElementById('risk-score-val');
  var cr = document.getElementById('risk-profil-calc');

  function v(id){ return obj[id]||conn[id]||pd[id]||''; }
  function vOrDash(id){ return v(id)||'—'; }

  // Lire un radio depuis le DOM
  function domRadio(name){
    var el = document.querySelector('input[name="'+name+'"]:checked');
    if(el){
      var lbl = el.closest('label');
      if(lbl) return lbl.textContent.trim();
      return el.value;
    }
    return '—';
  }

  // Lire valeur radio depuis parcoursData (booléen checked)
  function savedRadio(name, opts){
    // opts = [{val:'5',lbl:'texte'}]
    for(var i=0;i<opts.length;i++){
      var k = name+'_'+opts[i].val;
      if(v(k)||obj[k]||conn[k]) return opts[i].lbl;
    }
    // Essayer directement
    var direct = v(name);
    if(direct && direct !== 'false' && direct !== false) return direct;
    return domRadio(name);
  }

  function checkboxVal(id){ return (v(id)===true||v(id)==='true')?'✓':'☐'; }

  // Produits financiers - niveau de connaissance
  var kn_labels = {
    'kn-act':'Actions/OPCVM actions','kn-obl':'Obligations/OPCVM oblig.',
    'kn-nco':'Titres non cotés/FIP/FCPI','kn-mon':'Monétaire/fonds euros',
    'kn-div':'OPCVM diversifié','kn-str':'Produits structurés',
    'kn-aut':'Autres (options, alt.)','kn-ban':'Produits bancaires',
    'kn-imm':'Immobilier/SCPI/OPCI','kn-av':'Assurance-vie/capitalisation',
    'kn-dom':'DomTom/Girardin','kn-pee':'PEE/Participation/Perco','kn-sci':'SCI'
  };
  var kn_vals = {'0':'Aucune','2':'Bonne','4':'Très bonne'};
  function kn(id){
    var el = document.querySelector('input[name="'+id+'"]:checked');
    if(el) return kn_vals[el.value]||el.value;
    return '—';
  }

  // Questions inf
  var inf_labels = [
    'Je m\'informe sur mes placements',
    'Je m\'informe de la valeur de mes placements financiers au moins tous les mois',
    'Je m\'informe de la valeur de mes placements immobiliers au moins tous les ans',
    'Je regarde mon relevé bancaire au moins tous les mois'
  ];
  var inf_vals = {'15':'Souvent','8':'Moins souvent','0':'Jamais'};
  function inf(i){
    var el = document.querySelector('input[name="inf'+i+'"]:checked');
    if(el) return inf_vals[el.value]||el.value;
    return '—';
  }

  // Affirmations
  var aff_labels = [
    '','// n\'existe pas',
    'Plus un produit est risqué, plus sa valeur peut varier',
    'Moins le patrimoine est diversifié, plus il est exposé',
    'Tout produit peut présenter d\'autres risques (fiscal, liquidité…)',
    'Pour un même placement, le risque diffère selon l\'échéance',
    'La structure du patrimoine doit être cohérente avec les objectifs'
  ];
  var aff_vals = {'1':'Vrai','0':'Faux'};
  function aff(j){
    var el = document.querySelector('input[name="aff'+j+'"]:checked');
    if(el) return aff_vals[el.value]||el.value;
    return '—';
  }

  // Risque - options complètes
  var risq_opts = {
    1:[{v:'5',l:'Vend immédiatement tout'},{v:'10',l:'Vend une partie'},{v:'15',l:'Conserve (va remonter)'},{v:'20',l:'En rachète davantage'}],
    2:[{v:'5',l:'A vendu'},{v:'10',l:'A vendu une partie'},{v:'15',l:'A tout conservé'},{v:'20',l:'A réinvesti'}],
    3:[{v:'5',l:'N\'en dormais pas la nuit'},{v:'10',l:'N\'était pas au courant'},{v:'15',l:'A suivi sans paniquer'},{v:'20',l:'Très bien, placements solides'}],
    4:[{v:'5',l:'Part liquide importante'},{v:'10',l:'Petit matelas de sécurité'},{v:'15',l:'Vend rapidement si besoin'}],
    5:[{v:'5',l:'Non'},{v:'10',l:'Parfois (conséquences faibles)'},{v:'15',l:'Assez souvent (risques maîtrisés)'},{v:'20',l:'Autant que possible'}],
    6:[{v:'5',l:'6 mois - 3 ans (court terme)'},{v:'10',l:'4 - 10 ans (moyen terme)'},{v:'15',l:'11 - 15 ans (long terme)'},{v:'20',l:'> 15 ans (très long terme)'}]
  };
  function risq(i){
    var el = document.querySelector('input[name="risq'+i+'"]:checked');
    if(el){
      var lbl=el.closest('label'); if(lbl) return lbl.textContent.trim().replace(/\s+/g,' ');
      var opts=risq_opts[i]||[];
      for(var k=0;k<opts.length;k++) if(opts[k].v===el.value) return opts[k].l;
      return el.value;
    }
    return '—';
  }

  var H = '<!DOCTYPE html><html><head><meta charset="UTF-8"><title>Récapitulatif — '+CLIENT.prenom+' '+CLIENT.nom+'</title><style>'
    +'@media print{@page{margin:1.5cm;size:A4}body{-webkit-print-color-adjust:exact;print-color-adjust:exact}.no-print{display:none}}'
    +'*{box-sizing:border-box;margin:0;padding:0}'
    +'body{font-family:Georgia,serif;color:#1a1a2e;font-size:9.5pt;background:white;line-height:1.4}'
    +'.hdr{background:#0f1e35;padding:18px 26px;display:flex;justify-content:space-between;align-items:center}'
    +'.brand{font-size:15pt;font-weight:bold;color:#c9a84c;letter-spacing:.5px}'
    +'.brand-sub{font-size:8pt;color:rgba(255,255,255,.5);margin-top:2px}'
    +'.doc-title{font-size:11pt;font-weight:bold;color:#c9a84c;text-align:right}'
    +'.doc-info{font-size:8pt;color:rgba(255,255,255,.5);text-align:right;margin-top:2px}'
    +'.gold-bar{height:3px;background:linear-gradient(90deg,#c9a84c,#e8c96a,#c9a84c)}'
    +'.body{padding:16px 26px}'
    +'.sec{margin-bottom:14px;break-inside:avoid;page-break-inside:avoid}'
    +'.sec-title{font-size:9pt;font-weight:bold;color:white;background:#0f1e35;padding:5px 10px;border-left:3px solid #c9a84c;margin-bottom:6px;text-transform:uppercase;letter-spacing:.5px}'
    +'.grid{display:grid;grid-template-columns:1fr 1fr;border:1px solid #e0e0e0;border-bottom:none}'
    +'.grid-1{display:grid;grid-template-columns:1fr;border:1px solid #e0e0e0;border-bottom:none}'
    +'.row{display:flex;padding:4px 8px;border-bottom:1px solid #e8e8e8;background:white}'
    +'.row:nth-child(even){background:#fafafa}'
    +'.lbl{color:#4a5a6a;font-size:8.5pt;min-width:160px;flex-shrink:0;font-style:italic}'
    +'.val{color:#1a1a2e;font-size:8.5pt;font-weight:bold}'
    +'.kn-table{width:100%;border-collapse:collapse;font-size:8.5pt}'
    +'.kn-table th{background:#1a2f4e;color:#c9a84c;padding:5px 8px;text-align:center;font-size:8pt;font-weight:normal}'
    +'.kn-table th:first-child{text-align:left}'
    +'.kn-table td{padding:4px 8px;border-bottom:1px solid #ebebeb;text-align:center}'
    +'.kn-table td:first-child{text-align:left;color:#2a3a4a}'
    +'.kn-table tr:nth-child(even){background:#fafafa}'
    +'.kn-badge{display:inline-block;padding:1px 7px;border-radius:10px;font-size:8pt}'
    +'.kn-none{background:#f0f0f0;color:#888}'
    +'.kn-good{background:#e8f5e9;color:#2e7d32}'
    +'.kn-great{background:#e3f2fd;color:#1565c0}'
    +'.inv-badge{font-size:8pt;display:inline-block;padding:1px 6px;border-radius:3px;background:#e8e0d0;color:#8a6a3a}'
    +'.score-wrap{display:flex;gap:10px;margin-top:4px}'
    +'.sbox{flex:1;background:#0f1e35;border-radius:5px;padding:10px 12px;color:white}'
    +'.slbl{font-size:7.5pt;color:rgba(255,255,255,.5);text-transform:uppercase;letter-spacing:.8px;margin-bottom:4px}'
    +'.snum{font-size:18pt;font-weight:300;color:#c9a84c;line-height:1}'
    +'.scat{font-size:9pt;font-weight:bold;margin-top:3px}'
    +'.sig-box{border:1.5px solid #c9a84c;border-radius:5px;padding:12px 16px;background:#fffdf7}'
    +'.sig-canvas-box{border:1px solid #ddd;border-radius:4px;background:white;height:70px;margin:8px 0;display:flex;align-items:center;justify-content:center;font-style:italic;color:#aaa;font-size:8.5pt}'
    +'.ftr{background:#0f1e35;padding:8px 26px;display:flex;justify-content:space-between;align-items:center;margin-top:0}'
    +'.ftr-t{font-size:7.5pt;color:rgba(255,255,255,.4)}'
    +'.ftr-brand{font-size:8.5pt;font-weight:bold;color:#c9a84c}'
    +'.print-btn{position:fixed;bottom:16px;right:16px;background:#c9a84c;color:#0f1e35;border:none;border-radius:6px;padding:10px 18px;font-size:13px;font-weight:bold;cursor:pointer;box-shadow:0 2px 8px rgba(0,0,0,.2)}'
    +'</style></head><body>'

    // EN-TÊTE
    +'<div class="hdr">'
    +'<div><div class="brand">CAREMMA FINANCE</div><div class="brand-sub">Conseil en Investissement Financier · ORIAS N°24007767 · Bezons, Île-de-France</div></div>'
    +'<div><div class="doc-title">Récapitulatif Client</div><div class="doc-info">Établi le '+today2+'<br>'+CLIENT.prenom+' '+CLIENT.nom+'</div></div>'
    +'</div><div class="gold-bar"></div><div class="body">'

    // ══ QUESTIONNAIRE OBJECTIFS ══
    +'<div class="sec"><div class="sec-title">Questionnaire Objectifs de Placement</div></div>'

    // S1 Identité
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">1 · Identité du souscripteur</div>'
    +'<div class="grid">'
    +'<div class="row"><span class="lbl">Civilité</span><span class="val">'+vOrDash('qo-civ')+'</span></div>'
    +'<div class="row"><span class="lbl">Nom de naissance</span><span class="val">'+vOrDash('qo-nom-naiss')+'</span></div>'
    +'<div class="row"><span class="lbl">Nom d\'usage</span><span class="val">'+vOrDash('qo-nom-usage')+'</span></div>'
    +'<div class="row"><span class="lbl">Prénom(s)</span><span class="val">'+vOrDash('qo-prenom')+'</span></div>'
    +'<div class="row"><span class="lbl">Date de naissance</span><span class="val">'+vOrDash('qo-ddn')+'</span></div>'
    +'<div class="row"><span class="lbl">Nationalité</span><span class="val">'+vOrDash('qo-nationalite')+'</span></div>'
    +'<div class="row"><span class="lbl">Téléphone</span><span class="val">'+vOrDash('qo-tel')+'</span></div>'
    +'<div class="row"><span class="lbl">Tranche d\'âge</span><span class="val">'+domRadio('qo-age')+'</span></div>'
    +'</div>'
    +'<div class="grid-1"><div class="row"><span class="lbl">Adresse postale</span><span class="val">'+vOrDash('qo-adresse')+'</span></div></div>'
    +'</div>'

    // S2 Famille & Pro
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">2 · Situation familiale & professionnelle</div>'
    +'<div class="grid">'
    +'<div class="row"><span class="lbl">Situation familiale</span><span class="val">'+vOrDash('qo-sit-fam')+'</span></div>'
    +'<div class="row"><span class="lbl">Régime matrimonial</span><span class="val">'+vOrDash('qo-regime')+'</span></div>'
    +'<div class="row"><span class="lbl">Profession</span><span class="val">'+vOrDash('qo-profession')+'</span></div>'
    +'<div class="row"><span class="lbl">Conjoint(e)</span><span class="val">'+vOrDash('qo-conjoint')+'</span></div>'
    +'<div class="row"><span class="lbl">Départ retraite prévu</span><span class="val">'+vOrDash('qo-retraite')+'</span></div>'
    +'<div class="row"><span class="lbl">PPE (Personne Politiquement Exposée)</span><span class="val">'+vOrDash('qo-ppe')+'</span></div>'
    +'</div></div>'

    // S3 Finances
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">3 · Situation financière</div>'
    +'<div class="grid">'
    +'<div class="row"><span class="lbl">Revenus annuels client</span><span class="val">'+vOrDash('qo-rev-client')+' €</span></div>'
    +'<div class="row"><span class="lbl">Revenus annuels conjoint</span><span class="val">'+vOrDash('qo-rev-conjoint')+' €</span></div>'
    +'<div class="row"><span class="lbl">Revenus fonciers</span><span class="val">'+vOrDash('qo-rev-foncier')+' €</span></div>'
    +'<div class="row"><span class="lbl">Revenus cap. mobiliers</span><span class="val">'+vOrDash('qo-rev-rcm')+' €</span></div>'
    +'<div class="row"><span class="lbl">Charges annuelles foyer</span><span class="val">'+vOrDash('qo-charges')+' €</span></div>'
    +'<div class="row"><span class="lbl">Capacité d\'épargne annuelle</span><span class="val">'+vOrDash('qo-epargne')+' €</span></div>'
    +'</div></div>'

    // S4 Patrimoine
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">4 · Patrimoine</div>'
    +'<div class="grid">'
    +'<div class="row"><span class="lbl">Propriétaire résidence principale</span><span class="val">'+vOrDash('qo-proprio')+'</span></div>'
    +'<div class="row"><span class="lbl">Part sécuritaire du patrimoine</span><span class="val">'+vOrDash('qo-part-secu')+' %</span></div>'
    +'<div class="row"><span class="lbl">Part de ce projet / patrimoine total</span><span class="val">'+vOrDash('qo-part-projet')+' %</span></div>'
    +'</div></div>'

    // S5 Objectifs
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">5 · Objectifs de placement</div>'
    +'<div class="grid-1">'
    +'<div class="row"><span class="lbl">Épargne de précaution</span><span class="val">'+checkboxVal('qo-obj-precaution')+'</span></div>'
    +'<div class="row"><span class="lbl">Constituer une épargne progressive</span><span class="val">'+checkboxVal('qo-obj-progressif')+'</span></div>'
    +'<div class="row"><span class="lbl">Aider ses proches / héritiers</span><span class="val">'+checkboxVal('qo-obj-proches')+'</span></div>'
    +'<div class="row"><span class="lbl">Compléter ses revenus</span><span class="val">'+checkboxVal('qo-obj-revenus')+'</span></div>'
    +'<div class="row"><span class="lbl">Valoriser un capital existant</span><span class="val">'+checkboxVal('qo-obj-valoriser')+'</span></div>'
    +'<div class="row"><span class="lbl">Préparer sa retraite</span><span class="val">'+checkboxVal('qo-obj-retraite')+'</span></div>'
    +'<div class="row"><span class="lbl">Optimiser sa fiscalité</span><span class="val">'+checkboxVal('qo-obj-fiscalite')+'</span></div>'
    +'<div class="row"><span class="lbl">Transmission de patrimoine</span><span class="val">'+checkboxVal('qo-obj-transmission')+'</span></div>'
    +'</div>'
    +'<div class="grid">'
    +'<div class="row"><span class="lbl">Horizon de placement</span><span class="val">'+vOrDash('qo-horizon')+'</span></div>'
    +'<div class="row"><span class="lbl">Montant à placer</span><span class="val">'+vOrDash('qo-montant')+' €</span></div>'
    +'<div class="row"><span class="lbl">Tolérance au risque</span><span class="val">'+domRadio('qo-risque')+'</span></div>'
    +'<div class="row"><span class="lbl">Profil déclaré</span><span class="val">'+domRadio('qo-profil')+'</span></div>'
    +'</div></div>'

    // S6 ESG
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">6 · Préférences ESG / Durabilité (SFDR)</div>'
    +'<div class="grid">'
    +'<div class="row"><span class="lbl">Sensible aux critères ESG</span><span class="val">'+vOrDash('qo-esg-sensible')+'</span></div>'
    +'<div class="row"><span class="lbl">Intégrer critères durabilité</span><span class="val">'+vOrDash('qo-esg-integrer')+'</span></div>'
    +'<div class="row"><span class="lbl">Axe de préférence ESG</span><span class="val">'+vOrDash('qo-esg-axe')+'</span></div>'
    +'<div class="row"><span class="lbl">Part dédiée investissement durable</span><span class="val">'+vOrDash('qo-esg-part')+' %</span></div>'
    +'</div></div>'

    // ══ QUESTIONNAIRE CONNAISSANCE ══
    +'<div class="sec" style="margin-top:10px"><div class="sec-title">Questionnaire Connaissance & Compétence</div></div>'

    // Tableau produits financiers
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">7 · Connaissance des produits financiers</div>'
    +'<table class="kn-table">'
    +'<tr><th>Produit</th><th>Déjà investi ?</th><th>Niveau de connaissance</th></tr>'
    +Object.keys(kn_labels).map(function(id){
      var inv = document.querySelector('input#'+id+'-inv');
      var invText = inv ? (inv.checked?'Oui':'Non') : '—';
      var knLevel = kn(id);
      var badgeCls = knLevel==='Très bonne'?'kn-great':knLevel==='Bonne'?'kn-good':'kn-none';
      return '<tr><td>'+kn_labels[id]+'</td>'
        +'<td><span class="inv-badge">'+invText+'</span></td>'
        +'<td><span class="kn-badge '+badgeCls+'">'+knLevel+'</span></td></tr>';
    }).join('')
    +'</table></div>'

    // Gestion passée
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">8 · Gestion passée des avoirs</div>'
    +'<div class="grid-1"><div class="row"><span class="lbl">Dans le passé, la gestion de mes avoirs…</span><span class="val">'+domRadio('gestion_passe')+'</span></div></div></div>'

    // Questions information
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">9 · Fréquence de suivi des placements</div>'
    +'<div class="grid-1">'
    +'<div class="row"><span class="lbl">Je m\'informe de la valeur de mes placements financiers au moins tous les mois</span><span class="val">'+inf(2)+'</span></div>'
    +'<div class="row"><span class="lbl">Je m\'informe de la valeur de mes placements immobiliers au moins tous les ans</span><span class="val">'+inf(3)+'</span></div>'
    +'<div class="row"><span class="lbl">Je regarde mon relevé bancaire au moins tous les mois</span><span class="val">'+inf(4)+'</span></div>'
    +'</div></div>'

    // Affirmations
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">10 · Affirmations (Vrai / Faux)</div>'
    +'<div class="grid-1">'
    +'<div class="row"><span class="lbl">Plus un produit est risqué, plus sa valeur peut varier fortement</span><span class="val">'+aff(2)+'</span></div>'
    +'<div class="row"><span class="lbl">Moins le patrimoine est diversifié, plus il est exposé aux risques</span><span class="val">'+aff(3)+'</span></div>'
    +'<div class="row"><span class="lbl">Tout produit peut présenter d\'autres risques (fiscal, liquidité…)</span><span class="val">'+aff(4)+'</span></div>'
    +'<div class="row"><span class="lbl">Pour un même placement, le risque diffère selon l\'échéance</span><span class="val">'+aff(5)+'</span></div>'
    +'<div class="row"><span class="lbl">La structure du patrimoine doit être cohérente avec les objectifs</span><span class="val">'+aff(6)+'</span></div>'
    +'</div></div>'

    // ══ ÉVALUATION DU RISQUE ══
    +'<div class="sec"><div class="sec-title">Évaluation Comportementale du Risque</div></div>'
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">11 · Questions comportementales</div>'
    +'<div class="grid-1">'
    +'<div class="row"><span class="lbl">1. Si mon placement chute de 20%…</span><span class="val">'+risq(1)+'</span></div>'
    +'<div class="row"><span class="lbl">2. Pertes passées, comment ai-je réagi ?</span><span class="val">'+risq(2)+'</span></div>'
    +'<div class="row"><span class="lbl">3. Comment ai-je vécu les secousses des marchés ?</span><span class="val">'+risq(3)+'</span></div>'
    +'<div class="row"><span class="lbl">4. Critère de liquidité dans mon patrimoine</span><span class="val">'+risq(4)+'</span></div>'
    +'<div class="row"><span class="lbl">5. Dans la vie, aimez-vous prendre des risques ?</span><span class="val">'+risq(5)+'</span></div>'
    +'<div class="row"><span class="lbl">6. Échéance de mon principal objectif</span><span class="val">'+risq(6)+'</span></div>'
    +'</div></div>'

    // Scores
    +'<div class="sec"><div class="sec-title" style="background:#1a3050">12 · Résultats & Profil AMF</div>'
    +'<div class="score-wrap">'
    +'<div class="sbox"><div class="slbl">Score connaissance</div><div class="snum">'+(sc?sc.textContent:'—')+'</div><div class="scat">'+(cc?cc.textContent:'—')+'</div></div>'
    +'<div class="sbox"><div class="slbl">Score risque · /115 pts</div><div class="snum">'+(sr?sr.textContent:'—')+'</div><div class="scat">'+(cr?cr.textContent:'—')+'</div></div>'
    +'<div class="sbox"><div class="slbl">Profil graphique</div><div class="snum" style="font-size:12pt;margin-top:4px">'+(document.getElementById('result-profile-graph')?document.getElementById('result-profile-graph').textContent:'—')+'</div></div>'
    +'</div></div>'

    // ══ SIGNATURE ══
    +'<div class="sec" style="margin-top:8px"><div class="sec-title">Signature Électronique</div>'
    +'<div class="sig-box">'
    +'<div style="font-size:8.5pt;color:#5a6a7a;margin-bottom:10px;line-height:1.5">Je soussigné(e) <strong>'+CLIENT.prenom+' '+CLIENT.nom+'</strong> certifie l\'exactitude et l\'exhaustivité des informations fournies dans ce questionnaire, et consens au traitement de ces données par Caremma Finance dans le cadre de la relation de conseil en investissement.</div>'
    +(sigData
        ? '<div class="sig-canvas-box" style="height:auto;padding:8px;font-style:normal;color:inherit"><img src="'+sigData+'" style="height:70px;max-width:300px;object-fit:contain;display:block;margin:0 auto;border-radius:2px"></div>'
        : '<div class="sig-canvas-box">Signature non disponible</div>')
    +'<div style="display:flex;justify-content:space-between;margin-top:6px">'
    +'<div><div style="font-size:9pt;font-weight:bold;color:#0f1e35">'+CLIENT.prenom+' '+CLIENT.nom+'</div>'
    +'<div style="font-size:8pt;color:#8a9ab5">'+CLIENT.email+'</div></div>'
    +'<div style="text-align:right"><div style="font-size:8pt;color:#5a6a7a">Signé électroniquement le</div>'
    +'<div style="font-size:9pt;font-weight:bold;color:#0f1e35">'+(sigDate||today2)+'</div>'
    +'<div style="font-size:7.5pt;color:#8a9ab5;font-style:italic">Validé par code envoyé à '+CLIENT.email+'</div></div>'
    +'</div></div></div>'

    +'</div>'
    +'<div class="ftr">'
    +'<span class="ftr-t">Document confidentiel · Usage exclusif Caremma Finance · Ne pas diffuser</span>'
    +'<span class="ftr-brand">CAREMMA FINANCE</span>'
    +'<span class="ftr-t">ORIAS 24007767 · Bezons · '+today2+'</span>'
    +'</div>'
    +'<button class="print-btn no-print" onclick="window.print()">🖨️ Sauvegarder en PDF</button>'
    +'</body></html>';

  var win = window.open('','_blank','width=870,height=1080');
  if(win){
    win.document.write(H);
    win.document.close();
    win.focus();
    // Déclencher le mail UNIQUEMENT si sigData fourni (= doc vraiment signé)
    if(sigData){
      setTimeout(function(){
        var subject = encodeURIComponent('Document signé — '+CLIENT.prenom+' '+CLIENT.nom+' — '+today2);
        var bodyParts = [
          'Bonjour Marc,',
          '',
          CLIENT.prenom+' '+CLIENT.nom+' a signé son questionnaire Caremma Finance.',
          '',
          '• Client : '+CLIENT.prenom+' '+CLIENT.nom,
          '• Email : '+CLIENT.email,
          '• Signé le : '+(sigDate||today2),
          '• Score connaissance : '+(sc?sc.textContent:'—'),
          '• Profil de risque : '+(cr?cr.textContent:'—'),
          '',
          '──────────────────────────────────',
          'INSTRUCTIONS POUR JOINDRE LE PDF :',
          '1. Dans la fenêtre ouverte, cliquez le bouton "🖨️ Sauvegarder en PDF" en bas à droite',
          '2. Choisissez "Enregistrer au format PDF" comme imprimante',
          '3. Joignez ce PDF à cet email avant de l\'envoyer',
          '──────────────────────────────────',
          '',
          'Cordialement,',
          CLIENT.prenom+' '+CLIENT.nom
        ];
        var body = encodeURIComponent(bodyParts.join('\n'));
        window.location.href = 'mailto:marc.reverseau@caremmafinance.com?subject='+subject+'&body='+body;
      }, 1500);
    }
  }
}




async function sendSigCode(){
  if(!_sigDoc){toast('Aucun document','error');return;}
  _sigCode=Math.floor(100000+Math.random()*900000).toString();
  setSigStep(2);
  document.getElementById('sig-code').value='';
  document.getElementById('sig-err').style.display='none';
  try{
    await sendEmailJS(EJS_SERVICE_SIG,EJS_TPL_SIG,{
      to_email:CLIENT.email,to_name:CLIENT.prenom+' '+CLIENT.nom,
      from_name:'Caremma Finance',reply_to:'marc.reverseau@caremmafinance.com',
      client_prenom:CLIENT.prenom,access_code:_sigCode,
      subject:'Code de signature — Caremma Finance',
      message:'Code pour signer "'+_sigDoc.nom+'" : '+_sigCode+' (10 min)'
    });
    toast('Code envoyé à '+CLIENT.email+' ✓','success');
  }catch(e){toast('Erreur envoi : '+(e.text||e.message),'error');setSigStep(1);}
}

function verifySigCode(){
  var entered=(document.getElementById('sig-code').value||'').trim();
  var errEl=document.getElementById('sig-err');
  if(entered===_sigCode){
    errEl.style.display='none';setSigStep(3);
    var canvas=document.getElementById('sig-canvas');
    var rect=canvas.getBoundingClientRect();
    canvas.width=Math.round(rect.width)||700;canvas.height=150;
    _sigCtx=canvas.getContext('2d');
    _sigCtx.strokeStyle='#0c1a2e';_sigCtx.lineWidth=2.5;_sigCtx.lineCap='round';_sigCtx.lineJoin='round';
    _sigCtx.clearRect(0,0,canvas.width,canvas.height);
    canvas.onmousedown=function(e){_sigDrawing=true;_sigCtx.beginPath();_sigCtx.moveTo(e.offsetX,e.offsetY);};
    canvas.onmousemove=function(e){if(!_sigDrawing)return;_sigCtx.lineTo(e.offsetX,e.offsetY);_sigCtx.stroke();};
    canvas.onmouseup=canvas.onmouseleave=function(){_sigDrawing=false;};
    canvas.ontouchstart=function(e){e.preventDefault();_sigDrawing=true;var t=e.touches[0];var r=canvas.getBoundingClientRect();_sigCtx.beginPath();_sigCtx.moveTo((t.clientX-r.left)*(canvas.width/r.width),(t.clientY-r.top)*(canvas.height/r.height));};
    canvas.ontouchmove=function(e){e.preventDefault();if(!_sigDrawing)return;var t=e.touches[0];var r=canvas.getBoundingClientRect();_sigCtx.lineTo((t.clientX-r.left)*(canvas.width/r.width),(t.clientY-r.top)*(canvas.height/r.height));_sigCtx.stroke();};
    canvas.ontouchend=function(){_sigDrawing=false;};
  }else{
    errEl.style.display='block';document.getElementById('sig-code').value='';
  }
}

function clearSig(){var c=document.getElementById('sig-canvas');if(_sigCtx&&c)_sigCtx.clearRect(0,0,c.width,c.height);}
function closeSig(){var z=document.getElementById('sig-zone');if(z)z.style.display='none';_sigDoc=null;_sigCode=null;}

function confirmSig(){
  var canvas=document.getElementById('sig-canvas');
  if(!canvas||!_sigDoc){toast('Erreur','error');return;}
  var data=_sigCtx.getImageData(0,0,canvas.width,canvas.height).data;
  var ok=false;for(var i=3;i<data.length;i+=4)if(data[i]>0){ok=true;break;}
  if(!ok){toast('Veuillez tracer votre signature','error');return;}
  var sigData=canvas.toDataURL('image/png');
  var sigDate=new Date().toLocaleString('fr-FR');
  var signedDoc=_sigDoc; // keep reference before closeSig clears _sigDoc
  _sigDoc.signature=sigData;_sigDoc.signatureDate=sigDate;_sigDoc.status='signed';
  saveLocal();renderDocs();closeSig();
  toast('✅ Document signé — ouverture du récapitulatif...','success');

  // ── Sync signature dans JSONBin (le conseiller verra la signature)
  jbGet(MSG_BIN).then(function(d){
    var k=eKey(CLIENT.email);
    if(!d.messages)d.messages={};
    if(!d.messages[k])d.messages[k]={prenom:CLIENT.prenom,nom:CLIENT.nom,email:CLIENT.email,msgs:[],docs:[]};
    var docs=d.messages[k].docs||[];
    var idx=docs.findIndex(function(x){return String(x.id)===String(signedDoc.id);});
    var entry={id:signedDoc.id,nom:signedDoc.nom,docType:signedDoc.docType||'',
      signature:sigData,signatureDate:sigDate,status:'signed'};
    if(idx>=0)docs[idx]=Object.assign(docs[idx],entry);else docs.push(entry);
    d.messages[k].docs=docs;
    // Message de notification au conseiller
    if(!d.messages[k].msgs)d.messages[k].msgs=[];
    d.messages[k].msgs.push({id:Date.now(),from:'client',
      text:'✅ J\'ai signé le document "'+signedDoc.nom+'" le '+sigDate+'. Le PDF signé a été généré.',
      date:new Date().toLocaleDateString('fr-FR'),read:false});
    return jbPut(MSG_BIN,d);
  }).catch(function(){});

  // ── Générer le PDF récapitulatif avec la signature et ouvrir l'email
  var docKeyMap={objectifs:'objectifs',connaissance:'connaissance',entree:'objectifs',adequation:'connaissance'};
  var recapKey=signedDoc.docType?docKeyMap[signedDoc.docType]||signedDoc.docType:null;
  setTimeout(function(){
    if(recapKey){
      // Ouvrir le récap avec la signature incluse
      openRecapAndMail(sigData, sigDate, recapKey);
    } else {
      // Pas de questionnaire lié : juste email de notification
      var today2=new Date().toLocaleDateString('fr-FR',{year:'numeric',month:'long',day:'numeric'});
      var subject=encodeURIComponent('Document signé — '+signedDoc.nom+' — '+CLIENT.prenom+' '+CLIENT.nom);
      var bodyTxt=['Bonjour Marc,','',''+CLIENT.prenom+' '+CLIENT.nom+' a signé le document "'+signedDoc.nom+'".',
        'Date de signature : '+sigDate,'Email client : '+CLIENT.email,'','Cordialement,',CLIENT.prenom+' '+CLIENT.nom];
      window.location.href='mailto:marc.reverseau@caremmafinance.com?subject='+subject+'&body='+encodeURIComponent(bodyTxt.join('\n'));
    }
  },400);
}

// ═══ REPORTING ═══
// ═══ ALLOCATION D'ACTIFS (donut) ═══
// Format attendu (facultatif) : CLIENT.patrimoine.allocation = [{label,valeur,couleur}]
// Si absent, message d'attente affiché — pas de fausse donnée générée.
var DONUT_PALETTE=['#c9a84c','#8a9bb0','#5f7a94','#e8d9a8','#4a5d70','#b08a3e'];
function renderAllocationDonut(){
  var el=document.getElementById('allocation-donut');if(!el)return;
  var alloc=(CLIENT.patrimoine&&CLIENT.patrimoine.allocation)||[];
  if(!alloc.length){
    el.innerHTML='<div style="text-align:center;padding:26px 10px;color:var(--text3);font-size:12.5px">'
      +'Allocation d\'actifs non renseignée pour le moment.<br>Votre conseiller la mettra à jour depuis le CRM.</div>';
    return;
  }
  var total=alloc.reduce(function(s,a){return s+(a.valeur||0);},0)||1;
  var offset=0;
  var stops=alloc.map(function(a,i){
    var pct=(a.valeur||0)/total*100;
    var col=a.couleur||DONUT_PALETTE[i%DONUT_PALETTE.length];
    var seg=col+' '+offset+'% '+(offset+pct)+'%';
    offset+=pct;
    return seg;
  }).join(',');
  var legend=alloc.map(function(a,i){
    var pct=Math.round((a.valeur||0)/total*1000)/10;
    var col=a.couleur||DONUT_PALETTE[i%DONUT_PALETTE.length];
    return '<div class="donut-legend-row"><span class="donut-dot" style="background:'+col+'"></span>'+escH(a.label||'')+'<span class="donut-legend-val">'+pct+'%</span></div>';
  }).join('');
  el.innerHTML='<div class="donut-wrap">'
    +'<div class="donut-svg" style="width:140px;height:140px;border-radius:50%;background:conic-gradient('+stops+')">'
      +'<div style="width:76px;height:76px;border-radius:50%;background:var(--navy2);margin:32px;"></div>'
    +'</div>'
    +'<div class="donut-legend">'+legend+'</div>'
    +'</div>';
}

// ═══ SIMULATEUR "ET SI..." ═══
function initSimulateur(){
  var el=document.getElementById('simulateur');if(!el)return;
  if(el.dataset.init){computeSimulateur();return;}
  el.dataset.init='1';
  el.innerHTML=
    '<div class="sim-row"><span>Versement mensuel</span><span id="sim-mensuel-val" style="color:var(--gold2);font-weight:600">300 €</span></div>'
    +'<input type="range" id="sim-mensuel" class="sim-slider" min="0" max="3000" step="50" value="300" oninput="computeSimulateur()">'
    +'<div class="sim-row"><span>Horizon</span><span id="sim-annees-val" style="color:var(--gold2);font-weight:600">10 ans</span></div>'
    +'<input type="range" id="sim-annees" class="sim-slider" min="1" max="30" step="1" value="10" oninput="computeSimulateur()">'
    +'<div class="sim-pills" id="sim-profil-pills">'
      +'<button type="button" class="rap-pill" data-rate="0.03" onclick="setSimProfil(this)">Prudent 3%</button>'
      +'<button type="button" class="rap-pill active" data-rate="0.05" onclick="setSimProfil(this)">Équilibré 5%</button>'
      +'<button type="button" class="rap-pill" data-rate="0.07" onclick="setSimProfil(this)">Dynamique 7%</button>'
    +'</div>'
    +'<div class="sim-result">'
      +'<div style="font-size:11px;color:var(--text3);margin-bottom:4px">Capital estimé</div>'
      +'<div class="sim-result-value" id="sim-total">—</div>'
    +'</div>'
    +'<div class="sim-breakdown" id="sim-breakdown"></div>'
    +'<div class="sim-legend" id="sim-legend"></div>'
    +'<div style="font-size:10.5px;color:var(--text3);margin-top:12px;line-height:1.5">Simulation indicative basée sur une hypothèse de rendement annuel constant. Elle ne constitue pas une garantie de performance future — les marchés peuvent évoluer différemment.</div>';
  computeSimulateur();
}
function setSimProfil(btn){
  var pills=btn.parentElement.querySelectorAll('.rap-pill');
  for(var i=0;i<pills.length;i++)pills[i].classList.remove('active');
  btn.classList.add('active');
  computeSimulateur();
}
function computeSimulateur(){
  var mensuel=Number((document.getElementById('sim-mensuel')||{}).value||0);
  var annees=Number((document.getElementById('sim-annees')||{}).value||0);
  var activePill=document.querySelector('#sim-profil-pills .rap-pill.active');
  var rate=Number((activePill&&activePill.dataset.rate)||0.05);
  var mv=document.getElementById('sim-mensuel-val');if(mv)mv.textContent=fmt(mensuel);
  var av=document.getElementById('sim-annees-val');if(av)av.textContent=annees+' an'+(annees>1?'s':'');

  var capitalInitial=currentPortfolioValue();
  var months=annees*12;
  var mRate=rate/12;
  var valeur=capitalInitial;
  for(var i=0;i<months;i++){valeur=valeur*(1+mRate)+mensuel;}
  var versementsCumules=mensuel*months;
  var interets=Math.max(0,valeur-capitalInitial-versementsCumules);

  var totalEl=document.getElementById('sim-total');
  if(totalEl)totalEl.textContent=fmt(Math.round(valeur));

  var totalParts=capitalInitial+versementsCumules+interets||1;
  var bd=document.getElementById('sim-breakdown');
  if(bd)bd.innerHTML=
    '<div style="width:'+(capitalInitial/totalParts*100)+'%;background:#5f7a94"></div>'
    +'<div style="width:'+(versementsCumules/totalParts*100)+'%;background:#8a9bb0"></div>'
    +'<div style="width:'+(interets/totalParts*100)+'%;background:var(--gold)"></div>';
  var lg=document.getElementById('sim-legend');
  if(lg)lg.innerHTML=
    '<span>■ Capital initial : '+fmt(Math.round(capitalInitial))+'</span>'
    +'<span>■ Versements cumulés : '+fmt(Math.round(versementsCumules))+'</span>'
    +'<span>■ Intérêts générés : '+fmt(Math.round(interets))+'</span>';
}

function loadReporting(){
  if(!CLIENT)return;
  var local=CLIENT.patrimoine||{};
  renderReporting(local,CLIENT.ptfHistory||[]);
  jbGet(MSG_BIN).then(function(data){
    var k=eKey(CLIENT.email);
    var entry=data.messages&&data.messages[k];
    if(entry&&entry.patrimoine){
      CLIENT.patrimoine=entry.patrimoine;
      // Prendre l'historique le plus complet
      CLIENT.ptfHistory = entry.patrimoine.historique
        || entry.ptfHistory
        || CLIENT.ptfHistory || [];
      if(entry.profil) CLIENT.profil=entry.profil;
      saveLocal();
      // Attendre que le DOM soit visible avant de dessiner
      setTimeout(function(){ renderReporting(CLIENT.patrimoine,CLIENT.ptfHistory); renderKPIs(); },100);
    } else {
      // Pas de données patrimoine dans JSONBin — afficher message invitation
      var wrap2=document.querySelector('.chart-wrap');
      if(wrap2) wrap2.innerHTML='<div style="display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%;gap:12px;color:var(--text3);text-align:center">'
        +'<div style="font-size:30px">📊</div>'
        +'<div style="font-size:14px;font-weight:500;color:var(--text2)">Aucune donnée de portefeuille</div>'
        +'<div style="font-size:12px;max-width:300px;line-height:1.6">Votre conseiller mettra à jour vos performances depuis le CRM.</div>'
        +'</div>';
      // Mettre à jour les KPIs même sans patrimoine (affiche — pour perf)
      renderKPIs();
    }
  }).catch(function(e){
    console.warn('Reporting:',e);
    renderReporting(CLIENT.patrimoine||{},CLIENT.ptfHistory||[]);
  });
}

function renderReporting(p,history){
  var e=function(id){return document.getElementById(id);};
  if(e('r-val'))e('r-val').textContent=p.valeur?fmt(p.valeur):'—';
  if(e('r-date'))e('r-date').textContent=p.dateMAJ?'Au '+p.dateMAJ:'';
  if(e('r-perf')&&p.perfYTD!=null){e('r-perf').textContent=(p.perfYTD>=0?'+':'')+p.perfYTD+'%';e('r-perf').className='kpi-value '+(p.perfYTD>=0?'up':'dn');}
  if(e('r-profil'))e('r-profil').textContent=p.profil||CLIENT.profil||'—';
  drawChart(history);
  // Message si pas de données
  var wrap = document.querySelector('.chart-wrap');
  if(wrap && (!history||history.length<2)){
    wrap.innerHTML = '<div style="display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%;gap:12px;color:var(--text3)">'
      +'<div style="font-size:32px">📊</div>'
      +'<div style="font-size:14px;font-weight:500;color:var(--text2)">Aucune donnée de portefeuille</div>'
      +'<div style="font-size:12px;text-align:center;max-width:320px;line-height:1.6">Votre conseiller mettra à jour vos données de performance depuis le CRM.</div>'
      +'</div>';
  }
}

function drawChart(history){
  if(history&&history.length) window._pendingHistory=history;
  var h = window._pendingHistory||[];
  var canvas = document.getElementById('ptf-chart');
  var emptyEl = document.getElementById('ptf-empty');
  if(!canvas) return;

  if(!h||h.length<2){
    if(emptyEl){emptyEl.style.display='flex';}
    canvas.style.display='none';
    return;
  }
  canvas.style.display='block';
  if(emptyEl) emptyEl.style.display='none';

  // Reset dimensions
  canvas.removeAttribute('width');
  canvas.removeAttribute('height');

  var base = h[0].valeur||1;
  var perfs = h.map(function(x){ return parseFloat(((x.valeur-base)/base*100).toFixed(2)); });

  if(window._ptfChart){try{window._ptfChart.destroy();}catch(e){} window._ptfChart=null;}

  window._ptfChart = new Chart(canvas.getContext('2d'),{
    type:'line',
    data:{
      labels: h.map(function(x){return x.date||x.dateRaw||'';}),
      datasets:[
        {
          label:'Valeur (€)',
          data: h.map(function(x){return x.valeur;}),
          borderColor:'#c9a84c',
          backgroundColor:'rgba(201,168,76,0.1)',
          borderWidth:2.5,
          pointBackgroundColor:'#e8c96a',
          pointRadius:4,
          pointHoverRadius:6,
          fill:true,
          tension:0.3,
          yAxisID:'yVal'
        },
        {
          label:'Perf. (%)',
          data: perfs,
          borderColor:'rgba(34,197,94,0.9)',
          backgroundColor:'transparent',
          borderWidth:2,
          borderDash:[5,4],
          pointRadius:3,
          pointBackgroundColor:'#22c55e',
          fill:false,
          tension:0.3,
          yAxisID:'yPerf'
        }
      ]
    },
    options:{
      responsive:true,
      maintainAspectRatio:false,
      interaction:{mode:'index',intersect:false},
      plugins:{
        legend:{display:true,position:'top',labels:{color:'rgba(200,216,232,0.8)',font:{size:11},usePointStyle:true}},
        tooltip:{callbacks:{label:function(c){
          if(c.dataset.yAxisID==='yVal') return ' '+fmt(c.parsed.y);
          return ' '+(c.parsed.y>=0?'+':'')+c.parsed.y.toFixed(2)+'%';
        }}}
      },
      scales:{
        x:{
          grid:{color:'rgba(255,255,255,0.04)'},
          ticks:{color:'rgba(143,170,191,0.7)',font:{size:10},maxTicksLimit:12,maxRotation:45},
          title:{display:true,text:'Mois',color:'rgba(143,170,191,0.4)',font:{size:10}}
        },
        yVal:{
          position:'left',
          grid:{color:'rgba(255,255,255,0.04)'},
          ticks:{color:'rgba(201,168,76,0.8)',font:{size:10},callback:function(v){
            return v>=1e6?(v/1e6).toFixed(1)+'M€':v>=1000?(v/1000).toFixed(0)+'K€':v+'€';
          }},
          title:{display:true,text:'Valeur (€)',color:'rgba(201,168,76,0.5)',font:{size:10}}
        },
        yPerf:{
          position:'right',
          grid:{drawOnChartArea:false},
          ticks:{color:'rgba(34,197,94,0.7)',font:{size:10},callback:function(v){return (v>=0?'+':'')+v.toFixed(1)+'%';}},
          title:{display:true,text:'Perf. (%)',color:'rgba(34,197,94,0.5)',font:{size:10}}
        }
      }
    }
  });
}

// Filtre période
function setPeriod(period,btn){
  if(btn){
    document.querySelectorAll('#period-btns button').forEach(function(b){
      b.style.background='transparent';b.style.color='var(--text3)';b.style.border='1px solid var(--bdr)';
    });
    btn.style.background='var(--gold)';btn.style.color='#0c1a2e';btn.style.border='none';
  }
  var all=window._pendingHistory||CLIENT.ptfHistory||[];
  if(!all.length){drawChart([]);return;}
  var now=new Date();
  var filtered=all.filter(function(h){
    if(period==='tout') return true;
    var d=new Date((h.dateRaw||'2000-01')+'-01');
    var months={'6m':6,'1a':12,'3a':36}[period]||999;
    return (now-d)/(1000*60*60*24*30)<=months;
  });
  drawChart(filtered.length>=2?filtered:all);
}


// Filtre période
function setPeriod(period, btn){
  if(btn){
    document.querySelectorAll('#period-btns button').forEach(function(b){
      b.className='btn btn-ghost btn-sm';b.style.padding='4px 10px';b.style.fontSize='11px';
    });
    btn.className='btn btn-primary btn-sm';btn.style.padding='4px 10px';btn.style.fontSize='11px';
  }
  var all=window._pendingHistory||CLIENT.ptfHistory||[];
  if(!all.length){drawChart([]);return;}
  var now=new Date();
  var filtered=all.filter(function(h){
    if(period==='tout') return true;
    var d=new Date((h.dateRaw||'2000-01')+'-01');
    var months={'6m':6,'1a':12,'3a':36}[period]||6;
    return (now-d)/(1000*60*60*24*30)<=months;
  });
  drawChart(filtered.length>=2?filtered:all);
}


function initRadioOpts(container){
  if(!container) return;

  // 1. label.radio-opt (questionnaire connaissance - ps3/ps4)
  container.querySelectorAll('label.radio-opt').forEach(function(label){
    label.style.cursor='pointer';
    var inp=label.querySelector('input[type=radio]');
    if(inp&&inp.checked) label.classList.add('selected');
    label.addEventListener('click',function(){
      var name=this.querySelector('input[type=radio]');
      if(!name) return;
      var grp=name.name;
      container.querySelectorAll('label.radio-opt input[name="'+grp+'"]').forEach(function(r){
        r.closest('label').classList.remove('selected','on');
      });
      this.classList.add('selected');
      var r=this.querySelector('input[type=radio]');
      if(r){r.checked=true;}
      if(typeof calcScore==='function') calcScore();
      if(typeof calcRiskScore==='function') calcRiskScore();
      saveLocal();
    });
  });

  // 2. div.radio-opt (questionnaire objectifs)
  container.querySelectorAll('div.radio-opt').forEach(function(div){
    div.style.cursor='pointer';
    var inp=div.querySelector('input[type=radio],input[type=checkbox]');
    if(inp&&inp.checked) div.classList.add('selected');
    div.addEventListener('click',function(){
      var inp2=this.querySelector('input[type=radio]');
      if(inp2){
        // Désélectionner le groupe
        var grp=inp2.name;
        if(grp){
          container.querySelectorAll('div.radio-opt input[name="'+grp+'"]').forEach(function(r){
            r.closest('div.radio-opt').classList.remove('selected','on');
          });
        }
        inp2.checked=true;
        this.classList.add('selected');
        saveLocal();
      } else {
        // Checkbox
        var chk=this.querySelector('input[type=checkbox]');
        if(chk){
          chk.checked=!chk.checked;
          this.classList.toggle('selected',chk.checked);
          saveLocal();
        }
      }
    });
  });
}

function downloadPDF(url, filename){
  var a = document.createElement('a');
  a.href = url; a.download = filename||'recap.html';
  a.target = '_blank'; a.click();
}


// ═══ SCORE QUESTIONNAIRE CONNAISSANCE ═══
window.calcScore = function(){
  var scope = document.getElementById('ps3')
    || document.querySelector('#conn-content #ps3')
    || document.getElementById('conn-content')
    || document;
  var total = 0;
  ['act','obl','nco','mon','div','str','aut','ban','imm','av','dom','pee','sci'].forEach(function(p){
    var r = scope.querySelector('input[name="kn-'+p+'"]:checked')
         || document.querySelector('input[name="kn-'+p+'"]:checked');
    if(r) total += parseInt(r.value)||0;
  });
  var gp = scope.querySelector('input[name="gestion_passe"]:checked')
        || document.querySelector('input[name="gestion_passe"]:checked');
  if(gp) total += parseInt(gp.value)||0;
  for(var i=1;i<=4;i++){
    var r = scope.querySelector('input[name="inf'+i+'"]:checked')
          || document.querySelector('input[name="inf'+i+'"]:checked');
    if(r) total += parseInt(r.value)||0;
  }
  for(var j=1;j<=6;j++){
    var r2 = scope.querySelector('input[name="aff'+j+'"]:checked')
           || document.querySelector('input[name="aff'+j+'"]:checked');
    if(r2) total += parseInt(r2.value)||0;
  }
  var cat = total<=125 ? 'Investisseur de Base'
    : total<=171 ? 'Investisseur Averti' : 'Investisseur Avancé';
  ['q-score-val','score-val','result-score-kn'].forEach(function(id){
    var e=document.getElementById(id); if(e) e.textContent=total;
  });
  ['q-profil-val','result-cat-kn'].forEach(function(id){
    var e=document.getElementById(id); if(e) e.textContent=cat;
  });
  console.log('Score connaissance: '+total+' → '+cat);
};

window.calcRiskScore = function(){
  var scope = document.getElementById('ps3')
    || document.querySelector('#conn-content #ps3')
    || document.getElementById('conn-content')
    || document;
  var total = 0;
  for(var i=1;i<=6;i++){
    var r = scope.querySelector('input[name="risq'+i+'"]:checked')
          || document.querySelector('input[name="risq'+i+'"]:checked');
    if(r) total += parseInt(r.value)||0;
  }
  // Barème calibré 30-115 pts
  var cat = total<=51 ? 'Sécurité' : total<=72 ? 'Prudent'
    : total<=94 ? 'Équilibré' : 'Dynamique';
  var rv = scope.querySelector('#risk-score-val')||document.getElementById('risk-score-val');
  if(rv) rv.textContent = total;
  var rc = scope.querySelector('#risk-profil-calc')||document.getElementById('risk-profil-calc');
  if(rc) rc.textContent = cat;
  var rpc = document.getElementById('result-profile-calc');
  if(rpc) rpc.textContent = cat;
  console.log('Score risque: '+total+' → '+cat);
};


// Envoi email via API EmailJS directement (sans SDK)
async function sendEmailJS(serviceId, templateId, params){
  var response = await fetch('https://api.emailjs.com/api/v1.0/email/send', {
    method: 'POST',
    headers: {'Content-Type': 'application/json'},
    body: JSON.stringify({
      service_id: serviceId,
      template_id: templateId,
      user_id: EJS_PUBLIC,
      template_params: params
    })
  });
  if(!response.ok){
    var err = await response.text();
    throw new Error('EmailJS: '+err);
  }
  return response;
}













</script>
<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
</head>
<body>
<div id="toast-wrap"></div>
<div id="session-warning">⚠️ Session expirée dans <span id="sw-time">5:00</span> — <button class="btn btn-primary btn-sm" onclick="resetSession()">Rester connecté</button></div>

<!-- ═══ LOGIN ═══ -->
<div id="login-screen">
  <div class="login-bg-glow"></div>
  <div class="login-card">
    <div class="login-brand">
      <div class="login-mark">CF</div>
      <div class="login-name">Caremma Finance</div>
      <div class="login-orias">Conseil en Investissement · ORIAS 24007767</div>
    </div>
    <div class="login-h">Votre espace client</div>
    <div class="login-sub">Connectez-vous avec votre adresse email et le code reçu par email, ou votre mot de passe.</div>
    <div class="login-err" id="login-err"></div>
    <label class="lbl">Adresse email</label>
    <input class="linput" id="li-email" type="email" placeholder="prenom.nom@email.fr" autocomplete="email">
    <label class="lbl">Code ou mot de passe</label>
    <input class="linput" id="li-code" type="password" placeholder="••••••" autocomplete="current-password"
      onkeydown="if(event.key==='Enter')doLogin()">
    <button class="login-btn" id="login-btn" onclick="doLogin()">Accéder à mon espace →</button>
    <div class="login-foot">Pas encore de compte ? Contactez votre conseiller.</div>
  </div>
  </div>
</div>

<!-- ═══ SET PASSWORD ═══ -->
<div id="setpwd-screen" style="position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:radial-gradient(ellipse at 25% 35%,#1e3558,#0c1a2e);z-index:100">
  <div class="login-card">
    <div class="login-brand">
      <div class="login-mark">CF</div>
      <div class="login-name">Caremma Finance</div>
    </div>
    <div class="login-h">Première connexion</div>
    <div class="login-sub">Créez votre mot de passe personnel (minimum 6 caractères).</div>
    <div class="login-err" id="sp-err"></div>
    <label class="lbl">Nouveau mot de passe</label>
    <input class="linput" id="sp-p1" type="password" placeholder="••••••">
    <label class="lbl">Confirmer</label>
    <input class="linput" id="sp-p2" type="password" placeholder="••••••" onkeydown="if(event.key==='Enter')setPassword()">
    <button class="login-btn" onclick="setPassword()">Confirmer →</button>
  </div>
</div>

<!-- ═══ APP ═══ -->
<div id="app">
  <div class="topbar">
    <div class="tb-left">
      <div class="tb-mark">CF</div>
      <span class="tb-name">Caremma Finance</span>
    </div>
    <div class="tb-right">
      <span class="tb-save" id="tb-save">✓ Sauvegardé</span>
      <span class="tb-greeting" id="tb-greeting"></span>
      <div class="tb-avatar" id="tb-avatar"></div>
      <button class="tb-logout" onclick="logout()">Déconnexion</button>
    </div>
  </div>

  <div class="layout">
    <div class="sidebar" id="sidebar">
      <div class="sb-section">Vue d'ensemble</div>
      <div class="nav-item active" id="nav-accueil" onclick="goPage('accueil',this)"><span class="nav-icon">🏠</span>Tableau de bord</div>
      <div class="sb-section">Mon portefeuille</div>
      <div class="nav-item" id="nav-reporting" onclick="goPage('reporting',this)"><span class="nav-icon">📈</span>Performance & valorisation</div>
      <div class="nav-item" id="nav-rapports" onclick="goPage('rapports',this)"><span class="nav-icon">📚</span>Rapports de gestion <span id="rap-badge" style="display:none;background:var(--gold);color:var(--navy);font-size:9px;font-weight:700;padding:1px 5px;border-radius:8px;margin-left:4px"></span></div>
      <div class="nav-item" id="nav-patrimoine" onclick="goPage('patrimoine',this)"><span class="nav-icon">🏛️</span>Mon patrimoine</div>
      <div class="nav-item" id="nav-guides" onclick="goPage('guides',this)"><span class="nav-icon">📖</span>Guides & simulateurs</div>
      <div class="sb-section">Documents & échanges</div>
      <div class="nav-item" id="nav-monprofil" onclick="goPage('monprofil',this)"><span class="nav-icon">📝</span>Mon profil</div>
      <div class="nav-item" id="nav-documents" onclick="goPage('documents',this)"><span class="nav-icon">✍️</span>Documents à signer <span id="doc-badge" style="display:none;background:var(--gold);color:var(--navy);font-size:9px;font-weight:700;padding:1px 5px;border-radius:8px;margin-left:4px"></span></div>
      <div class="nav-item" id="nav-messages" onclick="goPage('messages',this)"><span class="nav-icon">💬</span>Messagerie<span class="nav-badge" id="msg-badge" style="display:none">0</span></div>
    </div>

    <div class="main" id="main">

      <!-- ACCUEIL -->
      <div class="page active" id="pg-accueil">
        <div class="ph"><div class="pt" id="acc-title">Bonjour</div><div class="ps">Bienvenue sur votre espace client Caremma Finance</div></div>
        <div class="kpi-grid">
          <div class="kpi"><div class="kpi-label">Valeur du portefeuille</div><div class="kpi-value" id="k-val">—</div><div class="kpi-sub" id="k-date"></div></div>
          <div class="kpi"><div class="kpi-label">Performance YTD</div><div class="kpi-value" id="k-perf">—</div><div class="kpi-sub">depuis le 1er janvier</div></div>
          <div class="kpi"><div class="kpi-label">Profil investisseur</div><div class="kpi-value" id="k-profil" style="font-size:16px;margin-top:4px">—</div></div>
          <div class="kpi"><div class="kpi-label">Prochain jalon</div><div class="kpi-value" id="k-progress">—</div><div class="kpi-sub" id="k-progress-sub">progression patrimoniale</div></div>
        </div>

        <div id="stories-row" class="stories-row"></div>
        <div id="milestone-card"></div>
        <div id="nudge-card"></div>
        <div id="streak-card" style="margin-bottom:16px"></div>

        <div class="card-row">
          <div class="card">
            <div class="card-title">Actions requises</div>
            <div id="acc-actions" style="font-size:13px;color:var(--text3);line-height:1.8">Aucune action en attente.</div>
          </div>
          <div class="card">
            <div class="card-title">Derniers messages</div>
            <div id="acc-msgs" style="font-size:13px;color:var(--text3)">Aucun message récent.</div>
          </div>
        </div>
      </div>

      <!-- MESSAGES -->
      <div class="page" id="pg-messages">
        <div class="ph"><div class="pt">Messagerie</div><div class="ps">Échangez directement avec Marc Reverseau · Caremma Finance</div></div>
        <div class="card" style="display:flex;flex-direction:column;min-height:480px">
          <div class="msg-list" id="msg-list"></div>
          <div class="msg-bar">
            <textarea class="msg-ta" id="msg-input" placeholder="Votre message..." rows="2"
              onkeydown="if(event.key==='Enter'&&!event.shiftKey){event.preventDefault();sendMsg()}"></textarea>
            <button class="btn btn-primary" onclick="sendMsg()">Envoyer</button>
          </div>
        </div>
      </div>

      <!-- OBJECTIFS -->
      <div class="page" id="pg-objectifs">
        <div class="ph">
          <div class="pt">Objectifs & situation</div>
          <div class="ps">Vos objectifs patrimoniaux · Situation financière · Fiscalité</div>
        </div>
        <div class="progress-bar"><div class="progress-fill" id="prog-obj" style="width:0%"></div></div>
        <div class="progress-label" id="prog-obj-lbl">Complétion : 0%</div>
        <div id="obj-content"></div>
      </div>

      <!-- CONNAISSANCE -->
      <div class="page" id="pg-connaissance">
        <div class="ph">
          <div class="pt">Connaissance & expérience</div>
          <div class="ps">Évaluation de vos connaissances financières · Profil AMF</div>
        </div>
        <div class="progress-bar"><div class="progress-fill" id="prog-conn" style="width:0%"></div></div>
        <div class="progress-label" id="prog-conn-lbl">Complétion : 0%</div>
        <div id="conn-content"></div>
      </div>

      <!-- MON PROFIL -->
      <div class="page" id="pg-monprofil">
        <div class="ph"><div class="pt">Mon profil</div><div class="ps">Complétez ou mettez à jour vos informations (objectifs, connaissance & risque, adéquation)</div></div>
        <div class="card" style="padding:0;overflow:hidden">
          <div style="padding:12px 16px;border-bottom:1px solid var(--bdr-gold);display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:8px">
            <div style="font-size:12.5px;color:var(--text3)">📝 Vos informations sont pré-remplies si votre conseiller les a déjà saisies. Vous pouvez les compléter ou les mettre à jour à tout moment.</div>
          </div>
          <iframe id="profil-tool-frame" style="width:100%;height:78vh;border:none;display:block;background:#eceff2"></iframe>
        </div>
      </div>

      <!-- DOCUMENTS -->
      <div class="page" id="pg-documents">
        <div class="ph"><div class="pt">Documents à signer</div><div class="ps">Déposez, consultez et signez vos documents contractuels</div></div>
        <div class="card">
          <div class="card-title">Déposer un document</div>
          <div class="upload-zone" id="upload-zone"
            onclick="document.getElementById('file-inp').click()"
            ondragover="event.preventDefault();this.classList.add('over')"
            ondragleave="this.classList.remove('over')"
            ondrop="event.preventDefault();this.classList.remove('over');handleUpload(event.dataTransfer.files[0])">
            <div class="upload-icon">📎</div>
            <div class="upload-title">Glisser un fichier ici ou cliquer</div>
            <div class="upload-sub">PDF · JPG · PNG · max 5 Mo</div>
          </div>
          <input type="file" id="file-inp" style="display:none" accept=".pdf,.jpg,.jpeg,.png"
            onchange="handleUpload(this.files[0]);this.value=''">
        </div>
        <div id="docs-list"></div>
        <!-- SIGNATURE -->
        <div id="sig-zone" style="display:none">
          <div class="sig-card">
            <div class="card-title">✍️ Signature — <span id="sig-doc-name" style="text-transform:none;font-weight:400;color:var(--text)"></span></div>
            <div class="sig-steps">
              <div class="sig-step active" id="sig-st1">① Email</div>
              <div class="sig-step" id="sig-st2">② Code</div>
              <div class="sig-step" id="sig-st3">③ Signature</div>
            </div>
            <div id="sig-s1">
              <p style="font-size:13px;color:var(--text2);margin-bottom:16px;line-height:1.6">Choisissez votre mode de signature :</p>
              <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:16px">
                <button class="btn btn-primary" onclick="sendSigCode()">✍️ Signature manuscrite (code email)</button>
                <button class="btn btn-ghost" onclick="openDocuSign()" style="border-color:var(--bdr-gold);color:var(--gold2)">
                  <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" style="flex-shrink:0"><path d="M12 20h9M16.5 3.5a2.121 2.121 0 013 3L7 19l-4 1 1-4L16.5 3.5z"/></svg>
                  DocuSign
                </button>
              </div>
              <button class="btn btn-ghost btn-sm" onclick="closeSig()">Annuler</button>
            </div>
            <div id="sig-s2" style="display:none">
              <p style="font-size:13px;color:var(--text2);margin-bottom:14px">Saisissez le code reçu par email :</p>
              <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap;margin-bottom:10px">
                <input id="sig-code" class="fc" type="text" inputmode="numeric" maxlength="6" placeholder="000000"
                  style="max-width:150px;font-size:20px;letter-spacing:6px;text-align:center">
                <button class="btn btn-primary" onclick="verifySigCode()">Vérifier →</button>
              </div>
              <div id="sig-err" style="color:var(--red);font-size:12px;display:none;margin-bottom:10px">❌ Code incorrect.</div>
              <button class="btn btn-ghost btn-sm" onclick="sendSigCode()">↻ Renvoyer</button>
              <button class="btn btn-ghost btn-sm" style="margin-left:8px" onclick="closeSig()">Annuler</button>
            </div>
            <div id="sig-s3" style="display:none">
              <p style="font-size:13px;color:var(--green);font-weight:600;margin-bottom:12px">✓ Identité vérifiée — Tracez votre signature</p>
              <canvas id="sig-canvas" style="border:1px solid var(--bdr-gold);border-radius:var(--r2);background:white;margin-bottom:14px"></canvas>
              <div style="display:flex;gap:8px;flex-wrap:wrap">
                <button class="btn btn-ghost btn-sm" onclick="clearSig()">🗑 Effacer</button>
                <button class="btn btn-primary" onclick="confirmSig()">✅ Valider</button>
                <button class="btn btn-ghost btn-sm" onclick="closeSig()">Annuler</button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- RAPPORTS -->
      <div class="page" id="pg-rapports">
        <div class="ph"><div class="pt">Rapports de gestion</div><div class="ps">Consultez et téléchargez vos rapports de gestion, relevés et documents contractuels</div></div>
        <div id="notes-list"></div>
        <div class="card" style="padding:16px 22px">
          <div style="display:flex;gap:10px;flex-wrap:wrap;align-items:center">
            <input id="rap-search" class="linput" placeholder="🔎 Rechercher un document..." style="max-width:280px;margin-bottom:0" oninput="renderRapports()">
            <div id="rap-filters" style="display:flex;gap:6px;flex-wrap:wrap"></div>
          </div>
        </div>
        <div id="rapports-list"></div>
      </div>

      <!-- PATRIMOINE (déclaratif client) -->
      <div class="page" id="pg-patrimoine">
        <div class="ph"><div class="pt">Mon patrimoine</div><div class="ps">Ajoutez vos actifs (immobilier, comptes, assurance-vie...) pour une vue complète de votre patrimoine</div></div>

        <div id="goal-card" style="margin-bottom:18px"></div>

        <div class="patr-total-row">
          <div class="patr-total-card"><div class="patr-total-label">Géré par Caremma Finance</div><div class="patr-total-value" id="patr-gere">—</div></div>
          <div class="patr-total-card"><div class="patr-total-label">Déclaré par vous</div><div class="patr-total-value" id="patr-declare">—</div></div>
          <div class="patr-total-card" style="border-color:rgba(201,168,76,0.3)"><div class="patr-total-label" style="color:var(--gold2)">Patrimoine total</div><div class="patr-total-value" id="patr-total" style="color:var(--gold2)">—</div></div>
        </div>

        <div class="card" style="margin-bottom:18px">
          <div class="card-title">Ajouter un actif</div>
          <div class="patr-form-grid">
            <div>
              <label>Catégorie</label>
              <select id="patr-cat">
                <option value="immobilier">🏠 Immobilier</option>
                <option value="comptes">🏦 Comptes bancaires</option>
                <option value="assurancevie">📄 Assurance-vie (externe)</option>
                <option value="epargnesal">💼 Épargne salariale</option>
                <option value="autresplacements">📊 Autres placements</option>
                <option value="autres">📦 Autres</option>
              </select>
            </div>
            <div>
              <label>Libellé</label>
              <input type="text" id="patr-libelle" placeholder="Ex : Résidence principale, Livret A...">
            </div>
            <div>
              <label>Valeur estimée (€)</label>
              <input type="number" id="patr-valeur" placeholder="0" min="0" step="100">
            </div>
            <div>
              <button class="btn btn-primary" onclick="addAsset()">+ Ajouter</button>
            </div>
          </div>
        </div>

        <div id="patrimoine-donut" style="margin-bottom:8px"></div>
        <div id="patrimoine-list"></div>
      </div>

      <!-- GUIDES & SIMULATEURS -->
      <div class="page" id="pg-guides">
        <div class="ph"><div class="pt">Guides & simulateurs</div><div class="ps">Fiches pratiques et simulateurs sur la fiscalité de votre épargne</div></div>

        <div class="guide-disclaimer">ℹ️ Ces fiches et simulateurs sont fournis à titre d'information générale (régime fiscal 2026) et ne constituent pas un conseil personnalisé. Votre situation peut comporter des spécificités — parlez-en avec votre conseiller avant toute décision.</div>

        <div class="card-title" style="margin-bottom:10px">📚 Fiches pratiques</div>
        <div id="fiches-list"></div>

        <div class="card-title" style="margin:24px 0 10px">🧮 Simulateur — Fiscalité d'un rachat d'assurance-vie</div>
        <div class="card"><div id="sim-av"></div></div>

        <div class="card-title" style="margin:24px 0 10px">🧮 Simulateur — Économie d'impôt PER</div>
        <div class="card"><div id="sim-per"></div></div>
      </div>

      <!-- REPORTING -->
      <div class="page" id="pg-reporting">
        <div class="ph" style="display:flex;align-items:flex-start;justify-content:space-between;flex-wrap:wrap;gap:12px">
          <div><div class="pt">Performance & valorisation</div><div class="ps">Évolution de la valeur de vos actifs</div></div>
          <button class="btn btn-ghost btn-sm" onclick="loadReporting()" style="color:var(--gold);border-color:var(--bdr-gold)">↻ Actualiser</button>
        </div>

        <div class="kpi-grid" style="grid-template-columns:repeat(3,1fr);margin-bottom:20px">
          <div class="kpi"><div class="kpi-label">Valeur actuelle</div><div class="kpi-value" id="r-val">—</div><div class="kpi-sub" id="r-date"></div></div>
          <div class="kpi"><div class="kpi-label">Performance YTD</div><div class="kpi-value" id="r-perf">—</div></div>
          <div class="kpi"><div class="kpi-label">Profil</div><div class="kpi-value" id="r-profil" style="font-size:16px;margin-top:4px">—</div></div>
        </div>

        <div class="card">
          <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:14px">
            <div class="card-title" style="margin-bottom:0">Courbe de performance</div>
            <div style="display:flex;gap:6px" id="period-btns">
              <button onclick="setPeriod('6m',this)" class="btn btn-sm btn-primary btn-sm" style="padding:4px 10px;font-size:11px">6M</button>
              <button onclick="setPeriod('1a',this)" class="btn btn-ghost btn-sm" style="padding:4px 10px;font-size:11px">1A</button>
              <button onclick="setPeriod('tout',this)" class="btn btn-ghost btn-sm" style="padding:4px 10px;font-size:11px">Tout</button>
            </div>
          </div>
          <div style="position:relative;height:220px">
            <canvas id="ptf-chart"></canvas>
            <div id="ptf-empty" style="display:none;position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px;color:var(--text3)">
              <div style="font-size:30px">📊</div>
              <div style="font-size:13px;font-weight:500;color:var(--text2)">Aucune donnée de portefeuille</div>
              <div style="font-size:11px;text-align:center;max-width:280px;line-height:1.6">Votre conseiller mettra à jour vos performances depuis le CRM.</div>
            </div>
          </div>
        </div>

        <div id="rep-detail"></div>

        <div class="card" style="margin-top:16px">
          <div class="card-title">Allocation d'actifs</div>
          <div id="allocation-donut"></div>
        </div>

        <div class="card" style="margin-top:16px">
          <div class="card-title">Simulateur — Et si je versais chaque mois...</div>
          <div id="simulateur"></div>
        </div>
      </div>
