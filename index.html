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
var EJS_PUBLIC='cstVoAsfF9vn4uc6C',EJS_SERVICE='service_qz3nkkq',EJS_TPL='template_wmauhka',EJS_TPL_SIG='template_88jyjec',EJS_SERVICE_SIG='service_hp5456h';
var _PHTML_B64="PGRpdiBpZD0icHMyIiBzdHlsZT0iZGlzcGxheTpibG9jayI+CiAgPGRpdiBjbGFzcz0ic2VjdGlvbi1oZWFkZXIiPgogICAgPGgyPlF1ZXN0aW9ubmFpcmUgT2JqZWN0aWZzPC9oMj4KICAgIDxkaXYgc3R5bGU9ImRpc3BsYXk6ZmxleDtnYXA6OHB4Ij4KICAgICAgPGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1vdXRsaW5lIGJ0bi1zbSIgb25jbGljaz0icHJldlN0ZXAoJ2VudHJlZScpIj7ihpAgw4l0YXBlIHByw6ljLjwvYnV0dG9uPgogICAgICA8YnV0dG9uIGNsYXNzPSJidG4gYnRuLXByaW1hcnkgYnRuLXNtIiBvbmNsaWNrPSJuZXh0U3RlcCgncW9iamVjdGlmcycsJ3F1ZXN0aW9ubmFpcmUnKSI+w4l0YXBlIHN1aXZhbnRlIOKGkjwvYnV0dG9uPgogICAgPC9kaXY+CiAgPC9kaXY+CiAgPGRpdiBjbGFzcz0iaW5mby1ib3giPvCfjq8gw4l0YXBlIDIvNCBkdSBwYXJjb3VycyBjbGllbnQg4oCUIFJlY3VlaWwgZGVzIG9iamVjdGlmcyBkZSBwbGFjZW1lbnQuPC9kaXY+CgogIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXBzIiBpZD0icW8tcHJvZ3Jlc3MiPgogICAgPGRpdiBjbGFzcz0icHJvZ3Jlc3Mtc3RlcCBhY3RpdmUiPjxkaXYgY2xhc3M9InBzLWRvdCI+MTwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5JZGVudGl0w6k8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+MjwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5TaXR1YXRpb248L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+MzwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5GaW5hbmNlczwvZGl2PjwvZGl2PgogICAgPGRpdiBjbGFzcz0icHJvZ3Jlc3Mtc3RlcCI+PGRpdiBjbGFzcz0icHMtZG90Ij40PC9kaXY+PGRpdiBjbGFzcz0icHMtbGFiZWwiPlBhdHJpbW9pbmU8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+NTwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5Db25uYWlzc2FuY2U8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+NjwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5PYmplY3RpZnM8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+NzwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5FU0c8L2Rpdj48L2Rpdj4KICAgIDxkaXYgY2xhc3M9InByb2dyZXNzLXN0ZXAiPjxkaXYgY2xhc3M9InBzLWRvdCI+ODwvZGl2PjxkaXYgY2xhc3M9InBzLWxhYmVsIj5Qcm9maWw8L2Rpdj48L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpibG9jayIgaWQ9InFvLXMwIj4KICAgIDxkaXYgY2xhc3M9ImNhcmQiPgogICAgICA8ZGl2IGNsYXNzPSJxLXRpdGxlIj4xLiBJZGVudGl0w6kgZHUgc291c2NyaXB0ZXVyPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JpZCI+CiAgICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPkNpdmlsaXTDqTwvbGFiZWw+PHNlbGVjdCBpZD0icW8tY2l2Ij48b3B0aW9uPk1hZGFtZTwvb3B0aW9uPjxvcHRpb24+TW9uc2lldXI8L29wdGlvbj48L3NlbGVjdD48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+Tm9tIGRlIG5haXNzYW5jZTwvbGFiZWw+PGlucHV0IGlkPSJxby1ub20tbmFpc3MiIHBsYWNlaG9sZGVyPSJOb20gZGUgbmFpc3NhbmNlIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+Tm9tIGQndXNhZ2U8L2xhYmVsPjxpbnB1dCBpZD0icW8tbm9tLXVzYWdlIiBwbGFjZWhvbGRlcj0iTm9tIGQndXNhZ2UiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5QcsOpbm9tKHMpPC9sYWJlbD48aW5wdXQgaWQ9InFvLXByZW5vbSIgcGxhY2Vob2xkZXI9IlByw6lub20ocykiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5EYXRlIGRlIG5haXNzYW5jZTwvbGFiZWw+PGlucHV0IGlkPSJxby1kZG4iIHR5cGU9ImRhdGUiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5OYXRpb25hbGl0w6k8L2xhYmVsPjxpbnB1dCBpZD0icW8tbmF0aW9uYWxpdGUiIHZhbHVlPSJGcmFuw6dhaXNlIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIGZvcm0tZnVsbCI+PGxhYmVsPkFkcmVzc2UgcG9zdGFsZTwvbGFiZWw+PGlucHV0IGlkPSJxby1hZHJlc3NlIiBwbGFjZWhvbGRlcj0iQWRyZXNzZSBjb21wbMOodGUiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5FbWFpbDwvbGFiZWw+PGlucHV0IGlkPSJxby1lbWFpbCIgdHlwZT0iZW1haWwiIHBsYWNlaG9sZGVyPSJlbWFpbEBleGVtcGxlLmZyIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+VMOpbMOpcGhvbmU8L2xhYmVsPjxpbnB1dCBpZD0icW8tdGVsIiBwbGFjZWhvbGRlcj0iMDYuLi4iPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAgZm9ybS1mdWxsIj48bGFiZWw+VHJhbmNoZSBkJ8OiZ2U8L2xhYmVsPgogICAgICAgICAgPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2dhcDo4cHg7ZmxleC13cmFwOndyYXAiPgogICAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tYWdlIiB2YWx1ZT0iPDUwIj4gPGxhYmVsPk1vaW5zIGRlIDUwIGFuczwvbGFiZWw+PC9kaXY+CiAgICAgICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1hZ2UiIHZhbHVlPSI1MC02MCI+IDxsYWJlbD41MCDDoCA2MCBhbnM8L2xhYmVsPjwvZGl2PgogICAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tYWdlIiB2YWx1ZT0iNjEtNzAiPiA8bGFiZWw+NjEgw6AgNzAgYW5zPC9sYWJlbD48L2Rpdj4KICAgICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLWFnZSIgdmFsdWU9Ij43MCI+IDxsYWJlbD5QbHVzIGRlIDcwIGFuczwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8L2Rpdj4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPjxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0icW9OYXYoMSkiPlN1aXZhbnQg4oaSPC9idXR0b24+PC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpub25lIiBpZD0icW8tczEiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9InEtdGl0bGUiPjIuIFNpdHVhdGlvbiBmYW1pbGlhbGUgJiBwcm9mZXNzaW9ubmVsbGU8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncmlkIj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+U2l0dWF0aW9uIGZhbWlsaWFsZTwvbGFiZWw+CiAgICAgICAgICA8c2VsZWN0IGlkPSJxby1zaXQtZmFtIj48b3B0aW9uPkPDqWxpYmF0YWlyZTwvb3B0aW9uPjxvcHRpb24+TWFyacOpKGUpPC9vcHRpb24+PG9wdGlvbj5QYWNzw6koZSk8L29wdGlvbj48b3B0aW9uPkRpdm9yY8OpKGUpPC9vcHRpb24+PG9wdGlvbj5WZXVmKHZlKTwvb3B0aW9uPjwvc2VsZWN0PgogICAgICAgIDwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Sw6lnaW1lIG1hdHJpbW9uaWFsPC9sYWJlbD48aW5wdXQgaWQ9InFvLXJlZ2ltZSIgcGxhY2Vob2xkZXI9IkNvbW11bmF1dMOpIGzDqWdhbGUuLi4iPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Qcm9mZXNzaW9uPC9sYWJlbD48aW5wdXQgaWQ9InFvLXByb2Zlc3Npb24iIHBsYWNlaG9sZGVyPSJQcm9mZXNzaW9uLi4uIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+Q29uam9pbnQoZSk8L2xhYmVsPjxpbnB1dCBpZD0icW8tY29uam9pbnQiIHBsYWNlaG9sZGVyPSJOb20gJiBwcm9mZXNzaW9uIGR1IGNvbmpvaW50Ij48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+QW5uw6llIGTDqXBhcnQgcmV0cmFpdGUgcHLDqXZ1PC9sYWJlbD48aW5wdXQgaWQ9InFvLXJldHJhaXRlIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIyMDMwIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+UFBFPC9sYWJlbD4KICAgICAgICAgIDxzZWxlY3QgaWQ9InFvLXBwZSI+PG9wdGlvbiB2YWx1ZT0ibm9uIj5Ob248L29wdGlvbj48b3B0aW9uIHZhbHVlPSJvdWkiPk91aSDigJQgUGVyc29ubmUgUG9saXRpcXVlbWVudCBFeHBvc8OpZTwvb3B0aW9uPjwvc2VsZWN0PgogICAgICAgIDwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAgZm9ybS1mdWxsIj48bGFiZWw+RW5mYW50cyDDoCBjaGFyZ2U8L2xhYmVsPgogICAgICAgICAgPGRpdiBpZD0icW8tZW5mYW50cy1saXN0IiBzdHlsZT0ibWFyZ2luLWJvdHRvbTo4cHgiPjwvZGl2PgogICAgICAgICAgPGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1vdXRsaW5lIGJ0bi1zbSIgb25jbGljaz0iYWRkRW5mYW50Um93KCkiPisgQWpvdXRlciBlbmZhbnQ8L2J1dHRvbj4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPjxidXR0b24gY2xhc3M9ImJ0biBidG4tb3V0bGluZSIgb25jbGljaz0icW9OYXYoMCkiPuKGkCBQcsOpY8OpZGVudDwvYnV0dG9uPjxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0icW9OYXYoMikiPlN1aXZhbnQg4oaSPC9idXR0b24+PC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpub25lIiBpZD0icW8tczIiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9InEtdGl0bGUiPjMuIFNpdHVhdGlvbiBmaW5hbmNpw6hyZTwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyaWQiPgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5SZXZlbnVzIGFubnVlbHMgZHUgY2xpZW50ICjigqwpPC9sYWJlbD48aW5wdXQgaWQ9InFvLXJldi1jbGllbnQiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5SZXZlbnVzIGR1IGNvbmpvaW50ICjigqwpPC9sYWJlbD48aW5wdXQgaWQ9InFvLXJldi1jb25qb2ludCIgdHlwZT0ibnVtYmVyIiBwbGFjZWhvbGRlcj0iMCI+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPlJldmVudXMgZm9uY2llcnMgKOKCrCk8L2xhYmVsPjxpbnB1dCBpZD0icW8tcmV2LWZvbmNpZXIiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5SZXZlbnVzIGRlIGNhcGl0YXV4IG1vYmlsaWVycyAo4oKsKTwvbGFiZWw+PGlucHV0IGlkPSJxby1yZXYtcmNtIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+Q2hhcmdlcyBhbm51ZWxsZXMgZHUgZm95ZXIgKOKCrCk8L2xhYmVsPjxpbnB1dCBpZD0icW8tY2hhcmdlcyIgdHlwZT0ibnVtYmVyIiBwbGFjZWhvbGRlcj0iMCI+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPkNhcGFjaXTDqSBkJ8OpcGFyZ25lIGFubnVlbGxlICjigqwpPC9sYWJlbD48aW5wdXQgaWQ9InFvLWVwYXJnbmUiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiIG9uaW5wdXQ9ImNhbGNFcGFyZ25lKCkiPjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBpZD0icW8tZXBhcmduZS1yZXN1bHQiIHN0eWxlPSJiYWNrZ3JvdW5kOnZhcigtLW9mZik7Ym9yZGVyLXJhZGl1czo3cHg7cGFkZGluZzoxMHB4IDE0cHg7Zm9udC1zaXplOjEyLjVweDtjb2xvcjp2YXIoLS1tdXRlZCk7bWFyZ2luLXRvcDo4cHgiPjwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJxLW5hdi1idG5zIj48YnV0dG9uIGNsYXNzPSJidG4gYnRuLW91dGxpbmUiIG9uY2xpY2s9InFvTmF2KDEpIj7ihpAgUHLDqWPDqWRlbnQ8L2J1dHRvbj48YnV0dG9uIGNsYXNzPSJidG4gYnRuLWdvbGQiIG9uY2xpY2s9InFvTmF2KDMpIj5TdWl2YW50IOKGkjwvYnV0dG9uPjwvZGl2PgogICAgPC9kaXY+CiAgPC9kaXY+CgogIDxkaXYgY2xhc3M9InEtc2VjdGlvbiIgc3R5bGU9ImRpc3BsYXk6bm9uZSIgaWQ9InFvLXMzIj4KICAgIDxkaXYgY2xhc3M9ImNhcmQiPgogICAgICA8ZGl2IGNsYXNzPSJxLXRpdGxlIj40LiBQYXRyaW1vaW5lPC9kaXY+CiAgICAgIDxkaXYgaWQ9InFvLXBhdHJpbW9pbmUtdGFibGUiIHN0eWxlPSJtYXJnaW4tYm90dG9tOjE0cHgiPgogICAgICAgIDx0YWJsZSBjbGFzcz0iZGF0YS10YWJsZSIgc3R5bGU9ImZvbnQtc2l6ZToxMnB4Ij4KICAgICAgICAgIDx0aGVhZD48dHI+PHRoPk5hdHVyZSBkdSBwbGFjZW1lbnQ8L3RoPjx0aD5Nb250YW50IHPDqWN1cml0YWlyZSAo4oKsKTwvdGg+PHRoPk1vbnRhbnQgcmlzcXXDqSAvIFVDICjigqwpPC90aD48L3RyPjwvdGhlYWQ+CiAgICAgICAgICA8dGJvZHk+CiAgICAgICAgICAgIDx0cj48dGQ+TGl2cmV0cyByw6lnbGVtZW50w6lzIChBLCBMRETigKYpPC90ZD48dGQ+PGlucHV0IGNsYXNzPSJpbmxpbmUtaW5wdXQiIGlkPSJwdGYtbGl2cmV0cy1zIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD7igJQ8L3RkPjwvdHI+CiAgICAgICAgICAgIDx0cj48dGQ+w4lwYXJnbmUgbG9nZW1lbnQgKENFTC9QRUwpPC90ZD48dGQ+PGlucHV0IGNsYXNzPSJpbmxpbmUtaW5wdXQiIGlkPSJwdGYtY2VsIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD7igJQ8L3RkPjwvdHI+CiAgICAgICAgICAgIDx0cj48dGQ+UEVQPC90ZD48dGQ+PGlucHV0IGNsYXNzPSJpbmxpbmUtaW5wdXQiIGlkPSJwdGYtcGVwLXMiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiPjwvdGQ+PHRkPjxpbnB1dCBjbGFzcz0iaW5saW5lLWlucHV0IiBpZD0icHRmLXBlcC1yIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjwvdHI+CiAgICAgICAgICAgIDx0cj48dGQ+QXNzdXJhbmNlLXZpZSAvIFBFUlA8L3RkPjx0ZD48aW5wdXQgY2xhc3M9ImlubGluZS1pbnB1dCIgaWQ9InB0Zi1hdi1zIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD48aW5wdXQgY2xhc3M9ImlubGluZS1pbnB1dCIgaWQ9InB0Zi1hdi1yIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjwvdHI+CiAgICAgICAgICAgIDx0cj48dGQ+UEVBIC8gQ29tcHRlLXRpdHJlczwvdGQ+PHRkPuKAlDwvdGQ+PHRkPjxpbnB1dCBjbGFzcz0iaW5saW5lLWlucHV0IiBpZD0icHRmLXBlYSIgdHlwZT0ibnVtYmVyIiBwbGFjZWhvbGRlcj0iMCI+PC90ZD48L3RyPgogICAgICAgICAgICA8dHI+PHRkPsOJcGFyZ25lIHNhbGFyaWFsZTwvdGQ+PHRkPjxpbnB1dCBjbGFzcz0iaW5saW5lLWlucHV0IiBpZD0icHRmLXNhbC1zIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD48aW5wdXQgY2xhc3M9ImlubGluZS1pbnB1dCIgaWQ9InB0Zi1zYWwtciIgdHlwZT0ibnVtYmVyIiBwbGFjZWhvbGRlcj0iMCI+PC90ZD48L3RyPgogICAgICAgICAgICA8dHI+PHRkPkltbW9iaWxpZXI8L3RkPjx0ZD48aW5wdXQgY2xhc3M9ImlubGluZS1pbnB1dCIgaWQ9InB0Zi1pbW1vIiB0eXBlPSJudW1iZXIiIHBsYWNlaG9sZGVyPSIwIj48L3RkPjx0ZD7igJQ8L3RkPjwvdHI+CiAgICAgICAgICA8L3Rib2R5PgogICAgICAgIDwvdGFibGU+CiAgICAgICAgPHN0eWxlPi5pbmxpbmUtaW5wdXR7Ym9yZGVyOm5vbmU7Ym9yZGVyLWJvdHRvbToxLjVweCBzb2xpZCB2YXIoLS1saWdodCk7YmFja2dyb3VuZDp0cmFuc3BhcmVudDt3aWR0aDoxMDBweDtwYWRkaW5nOjNweCA2cHg7Zm9udC1zaXplOjEycHg7Y29sb3I6dmFyKC0tdGV4dCl9LmlubGluZS1pbnB1dDpmb2N1c3tvdXRsaW5lOm5vbmU7Ym9yZGVyLWJvdHRvbS1jb2xvcjp2YXIoLS1nb2xkKX08L3N0eWxlPgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncmlkIj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+UHJvcHJpw6l0YWlyZSBpbW1vYmlsaWVyID88L2xhYmVsPjxzZWxlY3QgaWQ9InFvLXByb3ByaW8iPjxvcHRpb24+Tm9uPC9vcHRpb24+PG9wdGlvbj5PdWkg4oCUIHLDqXNpZGVuY2UgcHJpbmNpcGFsZTwvb3B0aW9uPjxvcHRpb24+T3VpIOKAlCByw6lzaWRlbmNlIHNlY29uZGFpcmU8L29wdGlvbj48b3B0aW9uPk91aSDigJQgaW52ZXN0aXNzZW1lbnQgbG9jYXRpZjwvb3B0aW9uPjwvc2VsZWN0PjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5QYXJ0IHPDqWN1cml0YWlyZSBkdSBwYXRyaW1vaW5lPC9sYWJlbD48c2VsZWN0IGlkPSJxby1wYXJ0LXNlY3UiPjxvcHRpb24+Jmd0OyA2MCU8L29wdGlvbj48b3B0aW9uPjMwLTYwJTwvb3B0aW9uPjxvcHRpb24+Jmx0OyAzMCU8L29wdGlvbj48L3NlbGVjdD48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+UGFydCBkZSBjZSBwcm9qZXQgZGFucyBsZSBwYXRyaW1vaW5lPC9sYWJlbD48c2VsZWN0IGlkPSJxby1wYXJ0LXByb2pldCI+PG9wdGlvbj4mbHQ7IDIwJTwvb3B0aW9uPjxvcHRpb24+MjAtNTAlPC9vcHRpb24+PG9wdGlvbj4mZ3Q7IDUwJTwvb3B0aW9uPjwvc2VsZWN0PjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0icS1uYXYtYnRucyI+PGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1vdXRsaW5lIiBvbmNsaWNrPSJxb05hdigyKSI+4oaQIFByw6ljw6lkZW50PC9idXR0b24+PGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1nb2xkIiBvbmNsaWNrPSJxb05hdig0KSI+U3VpdmFudCDihpI8L2J1dHRvbj48L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJxLXNlY3Rpb24iIHN0eWxlPSJkaXNwbGF5Om5vbmUiIGlkPSJxby1zNCI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkIj4KICAgICAgPGRpdiBjbGFzcz0icS10aXRsZSI+NS4gQ29ubmFpc3NhbmNlICYgZXhww6lyaWVuY2UgZmluYW5jacOocmU8L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNHB4Ij4KICAgICAgICA8bGFiZWwgc3R5bGU9ImZvbnQtc2l6ZToxMnB4O2ZvbnQtd2VpZ2h0OjYwMDtjb2xvcjp2YXIoLS1uYXZ5KSI+Tml2ZWF1IGRlIGNvbm5haXNzYW5jZSBkZXMgbWFyY2jDqXMgOjwvbGFiZWw+CiAgICAgICAgPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2dhcDo4cHg7ZmxleC13cmFwOndyYXA7bWFyZ2luLXRvcDo4cHgiPgogICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLWNvbm5haXMiIHZhbHVlPSIwIj48bGFiZWw+SW5leGlzdGFudGU8L2xhYmVsPjwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLWNvbm5haXMiIHZhbHVlPSIxIj48bGFiZWw+TW9kw6lyw6llPC9sYWJlbD48L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1jb25uYWlzIiB2YWx1ZT0iMiI+PGxhYmVsPkNvcnJlY3RlPC9sYWJlbD48L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1jb25uYWlzIiB2YWx1ZT0iMyI+PGxhYmVsPkJvbm5lPC9sYWJlbD48L2Rpdj4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi1ib3R0b206MTRweCI+CiAgICAgICAgPGxhYmVsIHN0eWxlPSJmb250LXNpemU6MTJweDtmb250LXdlaWdodDo2MDA7Y29sb3I6dmFyKC0tbmF2eSkiPkVuIGNhcyBkZSBiYWlzc2UgZGUgMTUlIGRlIHZvcyBwbGFjZW1lbnRzLCB2b3VzIDo8L2xhYmVsPgogICAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi10b3A6OHB4Ij4KICAgICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1yZWFjdGlvbiIgdmFsdWU9IjAiPjxsYWJlbD5WZW5kZXogdG91dCBpbW3DqWRpYXRlbWVudDwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tcmVhY3Rpb24iIHZhbHVlPSIxIj48bGFiZWw+QXR0ZW5kZXogcXVlIGxlcyB2YWxldXJzIHJlbW9udGVudDwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tcmVhY3Rpb24iIHZhbHVlPSIyIj48bGFiZWw+VmVuZGV6IGxhIHBhcnRpZSBheWFudCBsZSBwbHVzIGJhaXNzw6k8L2xhYmVsPjwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXJlYWN0aW9uIiB2YWx1ZT0iMyI+PGxhYmVsPlByb2ZpdGV6IGRlIGxhIGJhaXNzZSBwb3VyIGludmVzdGlyIGRhdmFudGFnZTwvbGFiZWw+PC9kaXY+CiAgICAgICAgPC9kaXY+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyaWQiPgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5UcmFuc2FjdGlvbnMgc3VyIE9QQ1ZNIC8gZm9uZHMgPzwvbGFiZWw+PHNlbGVjdCBpZD0icW8tb3Bjdm0iPjxvcHRpb24+Tm9uPC9vcHRpb24+PG9wdGlvbj5PdWk8L29wdGlvbj48L3NlbGVjdD48L2Rpdj4KICAgICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWw+R2VzdGlvbiBzb3VzIG1hbmRhdCA/PC9sYWJlbD48c2VsZWN0IGlkPSJxby1tYW5kYXQiPjxvcHRpb24+Tm9uPC9vcHRpb24+PG9wdGlvbj5PdWk8L29wdGlvbj48L3NlbGVjdD48L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPjxidXR0b24gY2xhc3M9ImJ0biBidG4tb3V0bGluZSIgb25jbGljaz0icW9OYXYoMykiPuKGkCBQcsOpY8OpZGVudDwvYnV0dG9uPjxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0icW9OYXYoNSkiPlN1aXZhbnQg4oaSPC9idXR0b24+PC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpub25lIiBpZD0icW8tczUiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9InEtdGl0bGUiPjYuIE9iamVjdGlmcyBkZSBzb3VzY3JpcHRpb248L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNnB4Ij4KICAgICAgICA8bGFiZWwgc3R5bGU9ImZvbnQtc2l6ZToxMnB4O2ZvbnQtd2VpZ2h0OjYwMDtjb2xvcjp2YXIoLS1uYXZ5KSI+T2JqZWN0aWYocykgcHJpbmNpcGFsKGF1eCkgKHBsdXNpZXVycyBjaG9peCBwb3NzaWJsZXMpIDo8L2xhYmVsPgogICAgICAgIDxkaXYgc3R5bGU9ImRpc3BsYXk6Z3JpZDtncmlkLXRlbXBsYXRlLWNvbHVtbnM6MWZyIDFmcjtnYXA6OHB4O21hcmdpbi10b3A6OHB4Ij4KICAgICAgICAgIDxkaXYgY2xhc3M9ImNoZWNrLW9wdCI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW8tb2JqLXByZWNhdXRpb24iPjxsYWJlbCBmb3I9InFvLW9iai1wcmVjYXV0aW9uIj7DiXBhcmduZSBkZSBwcsOpY2F1dGlvbjwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJjaGVjay1vcHQiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9InFvLW9iai1wcm9ncmVzc2lmIj48bGFiZWwgZm9yPSJxby1vYmotcHJvZ3Jlc3NpZiI+Q29uc3RpdHVlciB1bmUgw6lwYXJnbmUgcHJvZ3Jlc3NpdmU8L2xhYmVsPjwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0iY2hlY2stb3B0Ij48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJxby1vYmotcHJvY2hlcyI+PGxhYmVsIGZvcj0icW8tb2JqLXByb2NoZXMiPkFpZGVyIHNlcyBwcm9jaGVzIC8gaMOpcml0aWVyczwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJjaGVjay1vcHQiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9InFvLW9iai1yZXZlbnVzIj48bGFiZWwgZm9yPSJxby1vYmotcmV2ZW51cyI+Q29tcGzDqXRlciBzZXMgcmV2ZW51czwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJjaGVjay1vcHQiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9InFvLW9iai12YWxvcmlzZXIiPjxsYWJlbCBmb3I9InFvLW9iai12YWxvcmlzZXIiPlZhbG9yaXNlciB1biBjYXBpdGFsIGV4aXN0YW50PC9sYWJlbD48L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9ImNoZWNrLW9wdCI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW8tb2JqLXJldHJhaXRlIj48bGFiZWwgZm9yPSJxby1vYmotcmV0cmFpdGUiPlByw6lwYXJlciBzYSByZXRyYWl0ZTwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJjaGVjay1vcHQiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9InFvLW9iai1maXNjYWxpdGUiPjxsYWJlbCBmb3I9InFvLW9iai1maXNjYWxpdGUiPk9wdGltaXNlciBzYSBmaXNjYWxpdMOpPC9sYWJlbD48L2Rpdj4KICAgICAgICAgIDxkaXYgY2xhc3M9ImNoZWNrLW9wdCI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW8tb2JqLXRyYW5zbWlzc2lvbiI+PGxhYmVsIGZvcj0icW8tb2JqLXRyYW5zbWlzc2lvbiI+T3B0aW1pc2VyIGxhIHRyYW5zbWlzc2lvbjwvbGFiZWw+PC9kaXY+CiAgICAgICAgPC9kaXY+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyaWQiPgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAiPjxsYWJlbD5Ib3Jpem9uIGRlIHBsYWNlbWVudDwvbGFiZWw+CiAgICAgICAgICA8c2VsZWN0IGlkPSJxby1ob3Jpem9uIj48b3B0aW9uPk1vaW5zIGRlIDMgYW5zPC9vcHRpb24+PG9wdGlvbj4zIMOgIDUgYW5zPC9vcHRpb24+PG9wdGlvbj41IMOgIDggYW5zPC9vcHRpb24+PG9wdGlvbiBzZWxlY3RlZD5QbHVzIGRlIDggYW5zPC9vcHRpb24+PC9zZWxlY3Q+CiAgICAgICAgPC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPk1vbnRhbnQgw6AgcGxhY2VyICjigqwpPC9sYWJlbD48aW5wdXQgaWQ9InFvLW1vbnRhbnQiIHR5cGU9Im51bWJlciIgcGxhY2Vob2xkZXI9IjAiPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImZvcm0tZ3JvdXAgZm9ybS1mdWxsIj48bGFiZWw+QXBwcm9jaGUgcGFyIHJhcHBvcnQgYXUgcmlzcXVlPC9sYWJlbD4KICAgICAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi10b3A6NnB4Ij4KICAgICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXJpc3F1ZSIgdmFsdWU9InNlY3VyaXRhaXJlIj48bGFiZWw+UGxhY2VtZW50IHPDqWN1cmlzw6ksIHBlcmZvcm1hbmNlIG1vaW5zIMOpbGV2w6llPC9sYWJlbD48L2Rpdj4KICAgICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXJpc3F1ZSIgdmFsdWU9InBydWRlbnQiPjxsYWJlbD5SaXNxdWUgZmFpYmxlIHBvdXIgdW4gcGV1IHBsdXMgZGUgcmVuZGVtZW50PC9sYWJlbD48L2Rpdj4KICAgICAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXJpc3F1ZSIgdmFsdWU9Im1vZGVyZSI+PGxhYmVsPlJpc3F1ZSBtZXN1csOpIHBvdXIgYW3DqWxpb3JlciBsZSByZW5kZW1lbnQ8L2xhYmVsPjwvZGl2PgogICAgICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tcmlzcXVlIiB2YWx1ZT0iZHluYW1pcXVlIj48bGFiZWw+QXZhbnQgdG91dCB1biByZW5kZW1lbnQgw6lsZXbDqSwgcXVpdHRlIMOgIHByZW5kcmUgZGVzIHJpc3F1ZXMgaW1wb3J0YW50czwvbGFiZWw+PC9kaXY+CiAgICAgICAgICA8L2Rpdj4KICAgICAgICA8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPjxidXR0b24gY2xhc3M9ImJ0biBidG4tb3V0bGluZSIgb25jbGljaz0icW9OYXYoNCkiPuKGkCBQcsOpY8OpZGVudDwvYnV0dG9uPjxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0icW9OYXYoNikiPlN1aXZhbnQg4oaSPC9idXR0b24+PC9kaXY+CiAgICA8L2Rpdj4KICA8L2Rpdj4KCiAgPGRpdiBjbGFzcz0icS1zZWN0aW9uIiBzdHlsZT0iZGlzcGxheTpub25lIiBpZD0icW8tczYiPgogICAgPGRpdiBjbGFzcz0iY2FyZCI+CiAgICAgIDxkaXYgY2xhc3M9InEtdGl0bGUiPjcuIFByw6lmw6lyZW5jZXMgRVNHIC8gRHVyYWJpbGl0w6kgKFNGRFIpPC9kaXY+CiAgICAgIDxkaXYgc3R5bGU9Im1hcmdpbi1ib3R0b206MTJweCI+CiAgICAgICAgPGRpdiBjbGFzcz0iY2hlY2stb3B0Ij48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJxby1lc2ctc2Vuc2libGUiPjxsYWJlbCBmb3I9InFvLWVzZy1zZW5zaWJsZSI+SmUgc3VpcyBzZW5zaWJsZSBhdXggY3JpdMOocmVzIEVTRyAoZW52aXJvbm5lbWVudCwgc29jaWFsLCBnb3V2ZXJuYW5jZSk8L2xhYmVsPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9ImNoZWNrLW9wdCI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0icW8tZXNnLWludGVncmVyIj48bGFiZWwgZm9yPSJxby1lc2ctaW50ZWdyZXIiPkplIHNvdWhhaXRlIGludMOpZ3JlciBkZXMgY3JpdMOocmVzIGRlIGR1cmFiaWxpdMOpIGRhbnMgbWVzIGludmVzdGlzc2VtZW50czwvbGFiZWw+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0iY2hlY2stb3B0Ij48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJxby1lc2ctbGFiZWwiPjxsYWJlbCBmb3I9InFvLWVzZy1sYWJlbCI+w4AgcHJvZHVpdCDDqXF1aXZhbGVudCwgamUgcHJpdmlsw6lnaWUgdW4gZm9uZHMgYXZlYyBsYWJlbCBFU0c8L2xhYmVsPjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPkF4ZSBkZSBwcsOpZsOpcmVuY2UgRVNHPC9sYWJlbD4KICAgICAgICA8c2VsZWN0IGlkPSJxby1lc2ctYXhlIj48b3B0aW9uPkF1Y3VuZSBwcsOpZsOpcmVuY2UgcGFydGljdWxpw6hyZTwvb3B0aW9uPjxvcHRpb24+RW52aXJvbm5lbWVudCAoRSk8L29wdGlvbj48b3B0aW9uPlNvY2lhbCAoUyk8L29wdGlvbj48b3B0aW9uPkdvdXZlcm5hbmNlIChHKTwvb3B0aW9uPjxvcHRpb24+Q29tYmluYWlzb24gRVNHPC9vcHRpb24+PC9zZWxlY3Q+CiAgICAgIDwvZGl2PgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIiBzdHlsZT0ibWFyZ2luLXRvcDoxMnB4Ij48bGFiZWw+UGFydCBkZSBsJ8OpcGFyZ25lIGTDqWRpw6llIMOgIGwnaW52ZXN0aXNzZW1lbnQgZHVyYWJsZTwvbGFiZWw+CiAgICAgICAgPHNlbGVjdCBpZD0icW8tZXNnLXBhcnQiPjxvcHRpb24+MCU8L29wdGlvbj48b3B0aW9uPk1vaW5zIGRlIDIwJTwvb3B0aW9uPjxvcHRpb24+MjAgw6AgNTAlPC9vcHRpb24+PG9wdGlvbj5QbHVzIGRlIDUwJTwvb3B0aW9uPjwvc2VsZWN0PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0icS1uYXYtYnRucyI+PGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1vdXRsaW5lIiBvbmNsaWNrPSJxb05hdig1KSI+4oaQIFByw6ljw6lkZW50PC9idXR0b24+PGJ1dHRvbiBjbGFzcz0iYnRuIGJ0bi1nb2xkIiBvbmNsaWNrPSJxb05hdig3KSI+U3VpdmFudCDihpI8L2J1dHRvbj48L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJxLXNlY3Rpb24iIHN0eWxlPSJkaXNwbGF5Om5vbmUiIGlkPSJxby1zNyI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkIj4KICAgICAgPGRpdiBjbGFzcz0icS10aXRsZSI+OC4gUHJvZmlsIGRlIHJpc3F1ZSAmIFZhbGlkYXRpb248L2Rpdj4KICAgICAgPGRpdiBpZD0icW8tc2NvcmUtcmVzdWx0IiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNnB4Ij48L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0iZGlzcGxheTpncmlkO2dyaWQtdGVtcGxhdGUtY29sdW1uczpyZXBlYXQoNCwxZnIpO2dhcDoxMHB4O21hcmdpbi1ib3R0b206MTZweCIgaWQ9InFvLXByb2ZpbC1ncmlkIj4KICAgICAgICA8ZGl2IGNsYXNzPSJyYWRpby1vcHQiIHN0eWxlPSJmbGV4LWRpcmVjdGlvbjpjb2x1bW47YWxpZ24taXRlbXM6Y2VudGVyO3RleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InFvLXByb2ZpbCIgdmFsdWU9IlPDqWN1cml0YWlyZSI+PGxhYmVsPjxiPlPDiUNVUklUQUlSRTwvYj48YnI+PHNtYWxsIHN0eWxlPSJjb2xvcjp2YXIoLS1tdXRlZCkiPlJpc3F1ZSBmYWlibGU8L3NtYWxsPjwvbGFiZWw+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0IiBzdHlsZT0iZmxleC1kaXJlY3Rpb246Y29sdW1uO2FsaWduLWl0ZW1zOmNlbnRlcjt0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1wcm9maWwiIHZhbHVlPSJNb2TDqXLDqSIgY2hlY2tlZD48bGFiZWw+PGI+TU9Ew4lSw4k8L2I+PGJyPjxzbWFsbCBzdHlsZT0iY29sb3I6dmFyKC0tbXV0ZWQpIj5SaXNxdWUgbW9kw6lyw6k8L3NtYWxsPjwvbGFiZWw+PC9kaXY+CiAgICAgICAgPGRpdiBjbGFzcz0icmFkaW8tb3B0IiBzdHlsZT0iZmxleC1kaXJlY3Rpb246Y29sdW1uO2FsaWduLWl0ZW1zOmNlbnRlcjt0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJxby1wcm9maWwiIHZhbHVlPSJEeW5hbWlxdWUiPjxsYWJlbD48Yj5EWU5BTUlRVUU8L2I+PGJyPjxzbWFsbCBzdHlsZT0iY29sb3I6dmFyKC0tbXV0ZWQpIj5SaXNxdWUgaW1wb3J0YW50PC9zbWFsbD48L2xhYmVsPjwvZGl2PgogICAgICAgIDxkaXYgY2xhc3M9InJhZGlvLW9wdCIgc3R5bGU9ImZsZXgtZGlyZWN0aW9uOmNvbHVtbjthbGlnbi1pdGVtczpjZW50ZXI7dGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icW8tcHJvZmlsIiB2YWx1ZT0iT2ZmZW5zaWYiPjxsYWJlbD48Yj5PRkZFTlNJRjwvYj48YnI+PHNtYWxsIHN0eWxlPSJjb2xvcjp2YXIoLS1tdXRlZCkiPlJpc3F1ZSDDqWxldsOpPC9zbWFsbD48L2xhYmVsPjwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsPkNvbW1lbnRhaXJlIGNvbnNlaWxsZXI8L2xhYmVsPjx0ZXh0YXJlYSBpZD0icW8tY29tbWVudGFpcmUiIHJvd3M9IjMiIHBsYWNlaG9sZGVyPSJPYnNlcnZhdGlvbnMgc3VyIGxlIHByb2ZpbCBjbGllbnQuLi4iPjwvdGV4dGFyZWE+PC9kaXY+CiAgICAgIDxkaXYgY2xhc3M9InEtbmF2LWJ0bnMiPgogICAgICAgIDxidXR0b24gY2xhc3M9ImJ0biBidG4tb3V0bGluZSIgb25jbGljaz0icW9OYXYoNikiPuKGkCBQcsOpY8OpZGVudDwvYnV0dG9uPgogICAgICAgIDxidXR0b24gY2xhc3M9ImJ0biBidG4tZ29sZCIgb25jbGljaz0ibWFya1N0ZXBEb25lKCdxb2JqZWN0aWZzJyk7bmV4dFN0ZXAoJ3FvYmplY3RpZnMnLCdxdWVzdGlvbm5haXJlJykiPuKckyBWYWxpZGVyICYgY29udGludWVyIOKGkjwvYnV0dG9uPgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2Pgo8L2Rpdj4KCg==";
var _CONNAISSANCE_B64="PGRpdj4KCjwhLS0gQkFSUkUgw4lUQVBFUyAtLT4KPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2JvcmRlci1yYWRpdXM6OHB4IDhweCAwIDA7b3ZlcmZsb3c6aGlkZGVuO21hcmdpbi1ib3R0b206MTZweCI+CiAgPGJ1dHRvbiBpZD0icGIzIiBvbmNsaWNrPSJnb0Nvbm5haXNzYW5jZSgzKSIgc3R5bGU9ImZsZXg6MTtwYWRkaW5nOjEwcHggNnB4O2JvcmRlcjpub25lO2JhY2tncm91bmQ6dmFyKC0tZ29sZCk7Y29sb3I6dmFyKC0tbmF2eSk7Zm9udC13ZWlnaHQ6NzAwO2ZvbnQtc2l6ZToxMS41cHg7Y3Vyc29yOnBvaW50ZXI7Zm9udC1mYW1pbHk6aW5oZXJpdCI+MSDCtyBDb25uYWlzc2FuY2UgJmFtcDsgQ29tcMOpdGVuY2U8L2J1dHRvbj4KICA8YnV0dG9uIGlkPSJwYjQiIG9uY2xpY2s9ImdvQ29ubmFpc3NhbmNlKDQpIiBzdHlsZT0iZmxleDoxO3BhZGRpbmc6MTBweCA2cHg7Ym9yZGVyOm5vbmU7YmFja2dyb3VuZDp2YXIoLS1jcmVhbTIpO2NvbG9yOnJnYmEoMTY4LDE4NywyMTIsMC44KTtmb250LXdlaWdodDo2MDA7Zm9udC1zaXplOjExLjVweDtjdXJzb3I6cG9pbnRlcjtmb250LWZhbWlseTppbmhlcml0Ij4yIMK3IMOJdmFsdWF0aW9uIGR1IHJpc3F1ZTwvYnV0dG9uPgo8L2Rpdj4KCjwhLS0g4pWQ4pWQ4pWQIFNFQ1RJT04gMyA6IENPTk5BSVNTQU5DRSAmIENPTVDDiVRFTkNFIOKVkOKVkOKVkCAtLT4KPGRpdiBpZD0icHMzIiBzdHlsZT0iZGlzcGxheTpibG9jayI+CiAgPGRpdiBjbGFzcz0ic2VjdGlvbi1oZWFkZXIiPjxoMj5Db25uYWlzc2FuY2UgJmFtcDsgQ29tcMOpdGVuY2U8L2gyPjwvZGl2PgogIDxkaXYgY2xhc3M9ImluZm8tYm94Ij5DZSBxdWVzdGlvbm5haXJlIGEgcG91ciBvYmplY3RpZiBkZSBub3VzIGFpZGVyIMOgIGTDqXRlcm1pbmVyIHZvdHJlIGF0dGl0dWRlIHBhciByYXBwb3J0IGF1IHJpc3F1ZSBldCB2b3RyZSBuaXZlYXUgZGUgY29ubmFpc3NhbmNlIGRlcyBwcm9kdWl0cyBmaW5hbmNpZXJzLiBJbCBkw6l0ZXJtaW5lIHZvdHJlIGNhdMOpZ29yaXNhdGlvbiA6IEludmVzdGlzc2V1ciBkZSBCYXNlIC8gQXZlcnRpIC8gQXZhbmPDqS48L2Rpdj4KCiAgPGRpdiBjbGFzcz0iY2FyZCIgc3R5bGU9Im1hcmdpbi1ib3R0b206MTJweCI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkLXRpdGxlIj5Qcm9kdWl0cyBmaW5hbmNpZXJzIOKAlCBFeHDDqXJpZW5jZSBldCBjb25uYWlzc2FuY2U8L2Rpdj4KICAgIDx0YWJsZSBjbGFzcz0idGJsIiBzdHlsZT0iZm9udC1zaXplOjExLjVweCI+CiAgICAgIDx0aGVhZD4KICAgICAgICA8dHIgc3R5bGU9ImJhY2tncm91bmQ6dmFyKC0tbmF2eSkiPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7d2lkdGg6NDAlO3BhZGRpbmc6N3B4IDEwcHgiPlByb2R1aXQ8L3RoPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7dGV4dC1hbGlnbjpjZW50ZXI7cGFkZGluZzo3cHggOHB4Ij5Ew6lqw6A8YnI+aW52ZXN0aTwvdGg+CiAgICAgICAgICA8dGggc3R5bGU9ImNvbG9yOnZhcigtLWdvbGQyKTt0ZXh0LWFsaWduOmNlbnRlcjtwYWRkaW5nOjdweCA4cHgiPlBhczxicj5kdSB0b3V0PC90aD4KICAgICAgICAgIDx0aCBzdHlsZT0iY29sb3I6dmFyKC0tZ29sZDIpO3RleHQtYWxpZ246Y2VudGVyO3BhZGRpbmc6N3B4IDhweCI+VW48YnI+cGV1PC90aD4KICAgICAgICAgIDx0aCBzdHlsZT0iY29sb3I6dmFyKC0tZ29sZDIpO3RleHQtYWxpZ246Y2VudGVyO3BhZGRpbmc6N3B4IDhweCI+QmllbjwvdGg+CiAgICAgICAgPC90cj4KICAgICAgPC90aGVhZD4KICAgICAgPHRib2R5PgogICAgICAgIDx0cj48dGQ+QWN0aW9ucyBvdSBPUENWTSDDoCBkb21pbmFudGUgYWN0aW9uczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tYWN0LWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMSIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMSIgbmFtZT0ia24tYWN0IiB2YWx1ZT0iMCI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIyIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIyIiBuYW1lPSJrbi1hY3QiIHZhbHVlPSIyIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjMiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjMiIG5hbWU9ImtuLWFjdCIgdmFsdWU9IjQiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+T2JsaWdhdGlvbnMgb3UgT1BDVk0gw6AgZG9taW5hbnRlIG9ibGlnYXRhaXJlczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tb2JsLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyNCIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNCIgbmFtZT0ia24tb2JsIiB2YWx1ZT0iMCI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI1IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI1IiBuYW1lPSJrbi1vYmwiIHZhbHVlPSIyIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjYiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjYiIG5hbWU9ImtuLW9ibCIgdmFsdWU9IjQiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+VGl0cmVzIGRlIHNvY2nDqXTDqXMgbm9uIGNvdMOpZXMgb3UgRklQLCBGQ1BJLCBGQ1BSPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1uY28taW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI3IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI3IiBuYW1lPSJrbi1uY28iIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjgiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjgiIG5hbWU9ImtuLW5jbyIgdmFsdWU9IjIiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyOSIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyOSIgbmFtZT0ia24tbmNvIiB2YWx1ZT0iNCI+PC9sYWJlbD48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5Qcm9kdWl0cyBtb27DqXRhaXJlcywgT1BDVk0gbW9uw6l0YWlyZSwgZm9uZHMgZXVyb3M8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImtuLW1vbi1pbnYiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjEwIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIxMCIgbmFtZT0ia24tbW9uIiB2YWx1ZT0iMCI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIxMSIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMTEiIG5hbWU9ImtuLW1vbiIgdmFsdWU9IjIiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMTIiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjEyIiBuYW1lPSJrbi1tb24iIHZhbHVlPSI0Ij48L2xhYmVsPjwvdGQ+PC90cj4KICAgICAgICA8dHI+PHRkPk9QQ1ZNIGRpdmVyc2lmacOpPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1kaXYtaW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIxMyIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMTMiIG5hbWU9ImtuLWRpdiIgdmFsdWU9IjAiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMTQiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjE0IiBuYW1lPSJrbi1kaXYiIHZhbHVlPSIyIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjE1IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIxNSIgbmFtZT0ia24tZGl2IiB2YWx1ZT0iNCI+PC9sYWJlbD48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5Qcm9kdWl0cyBzdHJ1Y3R1csOpczwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tc3RyLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMTYiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjE2IiBuYW1lPSJrbi1zdHIiIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjE3IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIxNyIgbmFtZT0ia24tc3RyIiB2YWx1ZT0iMiI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIxOCIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMTgiIG5hbWU9ImtuLXN0ciIgdmFsdWU9IjQiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+QXV0cmVzIChvcHRpb25zLCBnZXN0aW9uIGFsdGVybmF0aXZl4oCmKTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tYXV0LWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMTkiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjE5IiBuYW1lPSJrbi1hdXQiIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjIwIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIyMCIgbmFtZT0ia24tYXV0IiB2YWx1ZT0iMiI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIyMSIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMjEiIG5hbWU9ImtuLWF1dCIgdmFsdWU9IjQiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+UHJvZHVpdHMgYmFuY2FpcmVzIChsaXZyZXQsIFBFTOKApik8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxpbnB1dCB0eXBlPSJjaGVja2JveCIgaWQ9ImtuLWJhbi1pbnYiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjIyIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIyMiIgbmFtZT0ia24tYmFuIiB2YWx1ZT0iMCI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIyMyIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMjMiIG5hbWU9ImtuLWJhbiIgdmFsdWU9IjIiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMjQiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjI0IiBuYW1lPSJrbi1iYW4iIHZhbHVlPSI0Ij48L2xhYmVsPjwvdGQ+PC90cj4KICAgICAgICA8dHI+PHRkPkltbW9iaWxpZXIgKHLDqWVsLCBTQ1BJLCBEdWZsb3QsIExNTlAsIE9QQ0nigKYpPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1pbW0taW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIyNSIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMjUiIG5hbWU9ImtuLWltbSIgdmFsdWU9IjAiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMjYiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjI2IiBuYW1lPSJrbi1pbW0iIHZhbHVlPSIyIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjI3IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIyNyIgbmFtZT0ia24taW1tIiB2YWx1ZT0iNCI+PC9sYWJlbD48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5Bc3N1cmFuY2UtdmllLCBjb250cmF0IGRlIGNhcGl0YWxpc2F0aW9uPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1hdi1pbnYiPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjI4IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIyOCIgbmFtZT0ia24tYXYiIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjI5IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIyOSIgbmFtZT0ia24tYXYiIHZhbHVlPSIyIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjMwIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIzMCIgbmFtZT0ia24tYXYiIHZhbHVlPSI0Ij48L2xhYmVsPjwvdGQ+PC90cj4KICAgICAgICA8dHI+PHRkPk9ww6lyYXRpb24gZGUgZMOpZmlzY2FsaXNhdGlvbiBEb21Ub20gKEdpcmFyZGlu4oCmKTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tZG9tLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMzEiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjMxIiBuYW1lPSJrbi1kb20iIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjMyIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIzMiIgbmFtZT0ia24tZG9tIiB2YWx1ZT0iMiI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIzMyIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMzMiIG5hbWU9ImtuLWRvbSIgdmFsdWU9IjQiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+UEVFLCBQYXJ0aWNpcGF0aW9uLCBQZXJjb+KApjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGlucHV0IHR5cGU9ImNoZWNrYm94IiBpZD0ia24tcGVlLWludiI+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMzQiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjM0IiBuYW1lPSJrbi1wZWUiIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjM1IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIzNSIgbmFtZT0ia24tcGVlIiB2YWx1ZT0iMiI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIzNiIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMzYiIG5hbWU9ImtuLXBlZSIgdmFsdWU9IjQiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+U0NJPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48aW5wdXQgdHlwZT0iY2hlY2tib3giIGlkPSJrbi1zY2ktaW52Ij48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InIzNyIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyMzciIG5hbWU9ImtuLXNjaSIgdmFsdWU9IjAiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyMzgiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjM4IiBuYW1lPSJrbi1zY2kiIHZhbHVlPSIyIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjM5IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InIzOSIgbmFtZT0ia24tc2NpIiB2YWx1ZT0iNCI+PC9sYWJlbD48L3RkPjwvdHI+CiAgICAgIDwvdGJvZHk+CiAgICA8L3RhYmxlPgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJjYXJkIiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxMnB4Ij4KICAgIDxkaXYgY2xhc3M9ImNhcmQtdGl0bGUiPkRhbnMgbGUgcGFzc8OpLCBsYSBnZXN0aW9uIGRlIG1lcyBhdm9pcnPigKY8L2Rpdj4KICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9Imdlc3Rpb25fcGFzc2UiIHZhbHVlPSI1Ij4gQSDDqXTDqSBkw6lsw6lndcOpZSDDoCB1biBnZXN0aW9ubmFpcmUgKGdlc3Rpb24gc291cyBtYW5kYXQpPC9sYWJlbD4KICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9Imdlc3Rpb25fcGFzc2UiIHZhbHVlPSIyMCI+IEEgw6l0w6kgZ8OpcsOpZSBwYXIgbW9pLW3Dqm1lIHNhbnMgbCdhaWRlIGQndW4gY29uc2VpbGxlcjwvbGFiZWw+CiAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJnZXN0aW9uX3Bhc3NlIiB2YWx1ZT0iMTAiPiBBIMOpdMOpIGfDqXLDqWUgcGFyIG1vaS1tw6ptZSBhdmVjIGwnYWlkZSBkJ3VuIGNvbnNlaWxsZXI8L2xhYmVsPgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJjYXJkIiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxMnB4Ij4KICAgIDxkaXYgY2xhc3M9ImNhcmQtdGl0bGUiPlZvdHJlIGluZm9ybWF0aW9u4oCmPC9kaXY+CiAgICA8dGFibGUgY2xhc3M9InRibCIgc3R5bGU9ImZvbnQtc2l6ZToxMS41cHgiPgogICAgICA8dGhlYWQ+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOnZhcigtLW5hdnkpIj4KICAgICAgICAgIDx0aCBzdHlsZT0iY29sb3I6dmFyKC0tZ29sZDIpO3dpZHRoOjY1JTtwYWRkaW5nOjdweCAxMHB4Ij5KZSBtJ2luZm9ybWXigKY8L3RoPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7dGV4dC1hbGlnbjpjZW50ZXI7cGFkZGluZzo3cHggOHB4Ij5PdWk8L3RoPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7dGV4dC1hbGlnbjpjZW50ZXI7cGFkZGluZzo3cHggOHB4Ij5VbiBwZXU8YnI+bW9pbnMgc291dmVudDwvdGg+CiAgICAgICAgICA8dGggc3R5bGU9ImNvbG9yOnZhcigtLWdvbGQyKTt0ZXh0LWFsaWduOmNlbnRlcjtwYWRkaW5nOjdweCA4cHgiPkphbWFpczwvdGg+CiAgICAgICAgPC90cj4KICAgICAgPC90aGVhZD4KICAgICAgPHRib2R5PgogICAgICAgIDx0cj48dGQ+SmUgbGlzIGxhIHByZXNzZSBzcMOpY2lhbGlzw6llIGNvbmNlcm5hbnQgbWVzIHByb2R1aXRzIGQnw6lwYXJnbmU8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI0MCIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNDAiIG5hbWU9ImluZjEiIHZhbHVlPSIxNSI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI0MSIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNDEiIG5hbWU9ImluZjEiIHZhbHVlPSI4Ij48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjQyIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI0MiIgbmFtZT0iaW5mMSIgdmFsdWU9IjAiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+SmUgbSdpbmZvcm1lIGRlIGxhIHZhbGV1ciBkZSBtZXMgcGxhY2VtZW50cyBmaW5hbmNpZXJzIGF1IG1vaW5zIHRvdXMgbGVzIG1vaXM8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI0MyIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNDMiIG5hbWU9ImluZjIiIHZhbHVlPSIxNSI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI0NCIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNDQiIG5hbWU9ImluZjIiIHZhbHVlPSI4Ij48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjQ1IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI0NSIgbmFtZT0iaW5mMiIgdmFsdWU9IjAiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0cj48dGQ+SmUgbSdpbmZvcm1lIGRlIGxhIHZhbGV1ciBkZSBtZXMgcGxhY2VtZW50cyBpbW1vYmlsaWVycyBhdSBtb2lucyB0b3VzIGxlcyBhbnM8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI0NiIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNDYiIG5hbWU9ImluZjMiIHZhbHVlPSIxNSI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI0NyIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNDciIG5hbWU9ImluZjMiIHZhbHVlPSI4Ij48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjQ4IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI0OCIgbmFtZT0iaW5mMyIgdmFsdWU9IjAiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+SmUgcmVnYXJkZSBtb24gcmVsZXbDqSBiYW5jYWlyZSBhdSBtb2lucyB0b3VzIGxlcyBtb2lzPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyNDkiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjQ5IiBuYW1lPSJpbmY0IiB2YWx1ZT0iMTUiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyNTAiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjUwIiBuYW1lPSJpbmY0IiB2YWx1ZT0iOCI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI1MSIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNTEiIG5hbWU9ImluZjQiIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PC90cj4KICAgICAgPC90Ym9keT4KICAgIDwvdGFibGU+CiAgPC9kaXY+CgogIDxkaXYgY2xhc3M9ImNhcmQiIHN0eWxlPSJtYXJnaW4tYm90dG9tOjEycHgiPgogICAgPGRpdiBjbGFzcz0iY2FyZC10aXRsZSI+UXVlbHF1ZXMgYWZmaXJtYXRpb25z4oCmIChWcmFpID0gMSBwdCAvIEZhdXggPSAwIHB0KTwvZGl2PgogICAgPHRhYmxlIGNsYXNzPSJ0YmwiIHN0eWxlPSJmb250LXNpemU6MTEuNXB4Ij4KICAgICAgPHRoZWFkPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDp2YXIoLS1uYXZ5KSI+CiAgICAgICAgICA8dGggc3R5bGU9ImNvbG9yOnZhcigtLWdvbGQyKTt3aWR0aDo4MCU7cGFkZGluZzo3cHggMTBweCI+QWZmaXJtYXRpb248L3RoPgogICAgICAgICAgPHRoIHN0eWxlPSJjb2xvcjp2YXIoLS1nb2xkMik7dGV4dC1hbGlnbjpjZW50ZXI7cGFkZGluZzo3cHggOHB4Ij5WcmFpPGJyPigxcHQpPC90aD4KICAgICAgICAgIDx0aCBzdHlsZT0iY29sb3I6dmFyKC0tZ29sZDIpO3RleHQtYWxpZ246Y2VudGVyO3BhZGRpbmc6N3B4IDhweCI+RmF1eDxicj4oMHB0KTwvdGg+CiAgICAgICAgPC90cj4KICAgICAgPC90aGVhZD4KICAgICAgPHRib2R5PgogICAgICAgIDx0cj48dGQ+TGEgdmVudGUgZGFucyBsJ3VyZ2VuY2UgZGVzIMOpbMOpbWVudHMgZGUgbW9uIHBhdHJpbW9pbmUgcGV1dCBtJ2FtZW5lciDDoCBzdWJpciB1bmUgbW9pbnMtdmFsdWU8L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI1MiIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNTIiIG5hbWU9ImFmZjEiIHZhbHVlPSIxIj48L2xhYmVsPjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjUzIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI1MyIgbmFtZT0iYWZmMSIgdmFsdWU9IjAiPjwvbGFiZWw+PC90ZD48L3RyPgogICAgICAgIDx0ciBzdHlsZT0iYmFja2dyb3VuZDojZjlmOWZiIj48dGQ+UGx1cyB1biBwcm9kdWl0IGVzdCByaXNxdcOpLCBwbHVzIHNhIHZhbGV1ciBldCBzYSBwZXJmb3JtYW5jZSBwZXV2ZW50IHZhcmllciBmb3J0ZW1lbnQgw6AgbGEgaGF1c3NlIGNvbW1lIMOgIGxhIGJhaXNzZTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjU0IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI1NCIgbmFtZT0iYWZmMiIgdmFsdWU9IjEiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyNTUiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjU1IiBuYW1lPSJhZmYyIiB2YWx1ZT0iMCI+PC9sYWJlbD48L3RkPjwvdHI+CiAgICAgICAgPHRyPjx0ZD5Nb2lucyBtb24gcGF0cmltb2luZSBlc3QgZGl2ZXJzaWZpw6ksIHBsdXMgaWwgZXN0IGV4cG9zw6kgYXV4IHJpc3F1ZXMgZGUgdmFyaWF0aW9uIGQndW5lIHZhbGV1cjwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjU2IiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI1NiIgbmFtZT0iYWZmMyIgdmFsdWU9IjEiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyNTciIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjU3IiBuYW1lPSJhZmYzIiB2YWx1ZT0iMCI+PC9sYWJlbD48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5Ub3V0IHByb2R1aXQgZCfDqXBhcmduZSBwZXV0IHByw6lzZW50ZXIgdW4gb3UgcGx1c2lldXJzIHJpc3F1ZXMgYXV0cmVzIHF1J3VuZSB2YXJpYXRpb24gZGUgc2EgdmFsZXVyIChyZXF1YWxpZmljYXRpb24gZmlzY2FsZSwgbm9uLWxpcXVpZGl0w6nigKYpPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyNTgiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjU4IiBuYW1lPSJhZmY0IiB2YWx1ZT0iMSI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI1OSIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNTkiIG5hbWU9ImFmZjQiIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PC90cj4KICAgICAgICA8dHI+PHRkPlBvdXIgdW4gbcOqbWUgcGxhY2VtZW50LCBsZSByaXNxdWUgZXN0IGRpZmbDqXJlbnQgc2Vsb24gbCfDqWNow6lhbmNlICgxIGFuLCA1IGFucywgMTAgYW5zKTwvdGQ+PHRkIHN0eWxlPSJ0ZXh0LWFsaWduOmNlbnRlciI+PGxhYmVsIGZvcj0icjYwIiBzdHlsZT0iZGlzcGxheTpibG9jazt3aWR0aDoxMDAlO3RleHQtYWxpZ246Y2VudGVyO2N1cnNvcjpwb2ludGVyO3BhZGRpbmc6MTBweDttYXJnaW46LTEwcHgiPjxpbnB1dCB0eXBlPSJyYWRpbyIgaWQ9InI2MCIgbmFtZT0iYWZmNSIgdmFsdWU9IjEiPjwvbGFiZWw+PC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyNjEiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjYxIiBuYW1lPSJhZmY1IiB2YWx1ZT0iMCI+PC9sYWJlbD48L3RkPjwvdHI+CiAgICAgICAgPHRyIHN0eWxlPSJiYWNrZ3JvdW5kOiNmOWY5ZmIiPjx0ZD5MYSBzdHJ1Y3R1cmUgZGUgbW9uIHBhdHJpbW9pbmUsIGRhbnMgbGUgdGVtcHMgZXQgZW4gcHJlbmFudCBlbiBjb21wdGUgbGVzIHJpc3F1ZXMgbGnDqXMgw6AgY2hhcXVlIGFjdGlmLCBkb2l0IMOqdHJlIGNvaMOpcmVudGUgYXZlYyBtZXMgb2JqZWN0aWZzPC90ZD48dGQgc3R5bGU9InRleHQtYWxpZ246Y2VudGVyIj48bGFiZWwgZm9yPSJyNjIiIHN0eWxlPSJkaXNwbGF5OmJsb2NrO3dpZHRoOjEwMCU7dGV4dC1hbGlnbjpjZW50ZXI7Y3Vyc29yOnBvaW50ZXI7cGFkZGluZzoxMHB4O21hcmdpbjotMTBweCI+PGlucHV0IHR5cGU9InJhZGlvIiBpZD0icjYyIiBuYW1lPSJhZmY2IiB2YWx1ZT0iMSI+PC9sYWJlbD48L3RkPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXIiPjxsYWJlbCBmb3I9InI2MyIgc3R5bGU9ImRpc3BsYXk6YmxvY2s7d2lkdGg6MTAwJTt0ZXh0LWFsaWduOmNlbnRlcjtjdXJzb3I6cG9pbnRlcjtwYWRkaW5nOjEwcHg7bWFyZ2luOi0xMHB4Ij48aW5wdXQgdHlwZT0icmFkaW8iIGlkPSJyNjMiIG5hbWU9ImFmZjYiIHZhbHVlPSIwIj48L2xhYmVsPjwvdGQ+PC90cj4KICAgICAgPC90Ym9keT4KICAgIDwvdGFibGU+CiAgPC9kaXY+CgogIDwhLS0gU2NvcmUgY29ubmFpc3NhbmNlIC0tPgogIDxkaXYgY2xhc3M9ImNhcmQiIHN0eWxlPSJiYWNrZ3JvdW5kOnZhcigtLWNyZWFtMik7Ym9yZGVyOm5vbmU7bWFyZ2luLWJvdHRvbToxMnB4Ij4KICAgIDxkaXYgc3R5bGU9ImRpc3BsYXk6ZmxleDthbGlnbi1pdGVtczpjZW50ZXI7Z2FwOjE2cHg7ZmxleC13cmFwOndyYXAiPgogICAgICA8ZGl2IHN0eWxlPSJmbGV4OjEiPgogICAgICAgIDxkaXYgc3R5bGU9ImZvbnQtc2l6ZToxMXB4O2NvbG9yOnJnYmEoMTY4LDE4NywyMTIsMC44KTt0ZXh0LXRyYW5zZm9ybTp1cHBlcmNhc2U7bGV0dGVyLXNwYWNpbmc6LjRweDttYXJnaW4tYm90dG9tOjRweCI+U2NvcmUgY29ubmFpc3NhbmNlPC9kaXY+CiAgICAgICAgPGRpdiBpZD0icS1zY29yZS12YWwiIHN0eWxlPSJmb250LXNpemU6MjJweDtmb250LXdlaWdodDo3MDA7Y29sb3I6dmFyKC0tbmF2eSkiPuKAlDwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0iZmxleDoxIj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTFweDtjb2xvcjpyZ2JhKDE2OCwxODcsMjEyLDAuOCk7dGV4dC10cmFuc2Zvcm06dXBwZXJjYXNlO2xldHRlci1zcGFjaW5nOi40cHg7bWFyZ2luLWJvdHRvbTo0cHgiPkNhdMOpZ29yaWUgQU1GPC9kaXY+CiAgICAgICAgPGRpdiBpZD0icS1wcm9maWwtdmFsIiBzdHlsZT0iZm9udC1zaXplOjE2cHg7Zm9udC13ZWlnaHQ6NzAwO2NvbG9yOnZhcigtLW5hdnkpIj7igJQ8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXYgc3R5bGU9ImZsZXg6MSI+CiAgICAgICAgPGRpdiBzdHlsZT0iZm9udC1zaXplOjExcHg7Y29sb3I6cmdiYSgxNjgsMTg3LDIxMiwwLjgpO3RleHQtdHJhbnNmb3JtOnVwcGVyY2FzZTtsZXR0ZXItc3BhY2luZzouNHB4O21hcmdpbi1ib3R0b206NHB4Ij5CYXLDqG1lIDogODEtMTI1ID0gQmFzZSDCtyAxMjYtMTcxID0gQXZlcnRpIMK3IDE3Mi0yMTggPSBBdmFuY8OpPC9kaXY+CiAgICAgICAgPGJ1dHRvbiBjbGFzcz0iYnRuIGJwMiBic20iIG9uY2xpY2s9ImNhbGNTY29yZSgpIj5DYWxjdWxlciBsZSBzY29yZTwvYnV0dG9uPgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJxLW5hdi1idG5zIiBzdHlsZT0iZGlzcGxheTpmbGV4O2p1c3RpZnktY29udGVudDpmbGV4LWVuZDttYXJnaW4tdG9wOjE2cHgiPgogICAgPGJ1dHRvbiBjbGFzcz0iYnRuIGJwMiIgb25jbGljaz0iZ29Db25uYWlzc2FuY2UoNCkiPlN1aXZhbnQg4oaSIMOJdmFsdWF0aW9uIGR1IHJpc3F1ZTwvYnV0dG9uPgogIDwvZGl2Pgo8L2Rpdj4KCjwhLS0g4pWQ4pWQ4pWQIFNFQ1RJT04gNCA6IMOJVkFMVUFUSU9OIERVIFJJU1FVRSDilZDilZDilZAgLS0+CjxkaXYgaWQ9InBzNCIgc3R5bGU9ImRpc3BsYXk6bm9uZSI+CiAgPGRpdiBjbGFzcz0ic2VjdGlvbi1oZWFkZXIiPjxoMj5EIOKAlCDDiXZhbHVhdGlvbiBkdSByaXNxdWU8L2gyPjwvZGl2PgogIDxkaXYgY2xhc3M9ImluZm8tYm94Ij5KJ2FjY2VwdGUgdW5lIGZsdWN0dWF0aW9uIGRlIGxhIHZhbGV1ciBkZSBsJ0VOU0VNQkxFIGRlIG1vbiBwYXRyaW1vaW5lIMOgIGxhIGhhdXNzZSBjb21tZSDDoCBsYSBiYWlzc2UuPC9kaXY+CgogIDwhLS0gR1JBUEhJUVVFIFJFTkRFTUVOVC9SSVNRVUUgLS0+CiAgPGRpdiBjbGFzcz0iY2FyZCIgc3R5bGU9Im1hcmdpbi1ib3R0b206MTJweCI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkLXRpdGxlIj5HcmFwaGlxdWUgUmVuZGVtZW50IC8gUmlzcXVlIOKAlCBTw6lsZWN0aW9ubmV6IHZvdHJlIHByb2ZpbDwvZGl2PgogICAgPGRpdiBzdHlsZT0iZGlzcGxheTpncmlkO2dyaWQtdGVtcGxhdGUtY29sdW1uczoxZnIgMWZyO2dhcDoxNnB4O2FsaWduLWl0ZW1zOmNlbnRlciI+CiAgICAgIDxzdmcgdmlld0JveD0iMCAwIDM4MCAyNDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgc3R5bGU9IndpZHRoOjEwMCU7bWF4LXdpZHRoOjQyMHB4Ij4KICAgICAgICA8cmVjdCB3aWR0aD0iMzgwIiBoZWlnaHQ9IjI0MCIgZmlsbD0iI2Y5ZjlmYiIgcng9IjYiLz4KICAgICAgICA8bGluZSB4MT0iNDQiIHkxPSIyMDgiIHgyPSIzNjgiIHkyPSIyMDgiIHN0cm9rZT0iI2M4Y2RkNiIgc3Ryb2tlLXdpZHRoPSIxLjUiLz4KICAgICAgICA8bGluZSB4MT0iNDQiIHkxPSIyMDgiIHgyPSI0NCIgeTI9IjE2IiBzdHJva2U9IiNjOGNkZDYiIHN0cm9rZS13aWR0aD0iMS41Ii8+CiAgICAgICAgPHRleHQgeD0iMjA2IiB5PSIyMzAiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZpbGw9IiM1YTZhN2EiIGZvbnQtc2l6ZT0iMTAiPlJpc3F1ZSDihpI8L3RleHQ+CiAgICAgICAgPHRleHQgeD0iMTQiIHk9IjExMiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZmlsbD0iIzVhNmE3YSIgZm9udC1zaXplPSIxMCIgdHJhbnNmb3JtPSJyb3RhdGUoLTkwLDE0LDExMikiPlJlbmRlbWVudCDihpI8L3RleHQ+CiAgICAgICAgPHBhdGggZD0iTSA1NSAyMDAgUSAxMTAgMTcyIDE2OCAxMzYgUSAyMjggOTYgMjk4IDU2IFEgMzI4IDQyIDM1OCAzMiIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjQzlBODRDIiBzdHJva2Utd2lkdGg9IjIuNSIgc3Ryb2tlLWRhc2hhcnJheT0iNiwzIi8+CiAgICAgICAgPHBhdGggZD0iTSA1NSAyMDAgUSAxMTAgMTcyIDE2OCAxMzYgUSAyMjggOTYgMjk4IDU2IFEgMzI4IDQyIDM1OCAzMiBMIDM1OCAyMDggWiIgZmlsbD0icmdiYSgyMDEsMTY4LDc2LDAuMDcpIi8+CiAgICAgICAgPCEtLSBTUiAtLT4KICAgICAgICA8Y2lyY2xlIGN4PSI4MiIgY3k9IjE5NSIgcj0iMTMiIGZpbGw9IiMyN2FlNjAiIG9wYWNpdHk9IjAuOSIgc3R5bGU9ImN1cnNvcjpwb2ludGVyIiBvbmNsaWNrPSJzZWxlY3RQcm9maWxlRnJvbUNoYXJ0KCdzZWN1cml0ZScpIi8+CiAgICAgICAgPHRleHQgeD0iODIiIHk9IjE5OSIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZmlsbD0id2hpdGUiIGZvbnQtc2l6ZT0iOCIgZm9udC13ZWlnaHQ9ImJvbGQiPlNSPC90ZXh0PgogICAgICAgIDwhLS0gUCAtLT4KICAgICAgICA8Y2lyY2xlIGN4PSIxNTUiIGN5PSIxNTgiIHI9IjE0IiBmaWxsPSIjMjk1MWEzIiBvcGFjaXR5PSIwLjkiIHN0eWxlPSJjdXJzb3I6cG9pbnRlciIgb25jbGljaz0ic2VsZWN0UHJvZmlsZUZyb21DaGFydCgncHJ1ZGVudCcpIi8+CiAgICAgICAgPHRleHQgeD0iMTU1IiB5PSIxNjIiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZpbGw9IndoaXRlIiBmb250LXNpemU9IjkiIGZvbnQtd2VpZ2h0PSJib2xkIj5QPC90ZXh0PgogICAgICAgIDwhLS0gRSAtLT4KICAgICAgICA8Y2lyY2xlIGN4PSIyMzgiIGN5PSIxMTIiIHI9IjE0IiBmaWxsPSIjZTY3ZTIyIiBvcGFjaXR5PSIwLjkiIHN0eWxlPSJjdXJzb3I6cG9pbnRlciIgb25jbGljaz0ic2VsZWN0UHJvZmlsZUZyb21DaGFydCgnZXF1aWxpYnJlJykiLz4KICAgICAgICA8dGV4dCB4PSIyMzgiIHk9IjExNiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZmlsbD0id2hpdGUiIGZvbnQtc2l6ZT0iOSIgZm9udC13ZWlnaHQ9ImJvbGQiPkU8L3RleHQ+CiAgICAgICAgPCEtLSBEIC0tPgogICAgICAgIDxjaXJjbGUgY3g9IjMyMiIgY3k9IjYyIiByPSIxNCIgZmlsbD0iI2MwMzkyYiIgb3BhY2l0eT0iMC45IiBzdHlsZT0iY3Vyc29yOnBvaW50ZXIiIG9uY2xpY2s9InNlbGVjdFByb2ZpbGVGcm9tQ2hhcnQoJ2R5bmFtaXF1ZScpIi8+CiAgICAgICAgPHRleHQgeD0iMzIyIiB5PSI2NiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZmlsbD0id2hpdGUiIGZvbnQtc2l6ZT0iOSIgZm9udC13ZWlnaHQ9ImJvbGQiPkQ8L3RleHQ+CiAgICAgICAgPGNpcmNsZSBpZD0icmlzay1pbmRpY2F0b3IiIGN4PSItNTAiIGN5PSItNTAiIHI9IjIwIiBmaWxsPSJub25lIiBzdHJva2U9IiMwQTE2MjgiIHN0cm9rZS13aWR0aD0iMyIgc3Ryb2tlLWRhc2hhcnJheT0iNCwyIiBvcGFjaXR5PSIwLjgiLz4KICAgICAgPC9zdmc+CiAgICAgIDxkaXY+CiAgICAgICAgPGRpdiBzdHlsZT0iZGlzcGxheTpmbGV4O2ZsZXgtZGlyZWN0aW9uOmNvbHVtbjtnYXA6OHB4Ij4KICAgICAgICAgIDxkaXYgY2xhc3M9InJpc2stY2FyZCIgZGF0YS1wcm9maWxlPSJzZWN1cml0ZSIgb25jbGljaz0ic2VsZWN0Umlza1Byb2ZpbGUodGhpcykiIHN0eWxlPSJib3JkZXI6MXB4IHNvbGlkIHJnYmEoMjU1LDI1NSwyNTUsMC4xKTtib3JkZXItcmFkaXVzOjhweDtwYWRkaW5nOjEwcHggMTJweDtjdXJzb3I6cG9pbnRlcjtkaXNwbGF5OmZsZXg7YWxpZ24taXRlbXM6Y2VudGVyO2dhcDoxMHB4O2JhY2tncm91bmQ6cmdiYSgyNTUsMjU1LDI1NSwwLjAzKSI+CiAgICAgICAgICAgIDxkaXYgc3R5bGU9IndpZHRoOjEwcHg7aGVpZ2h0OjEwcHg7YmFja2dyb3VuZDojMjdhZTYwO2JvcmRlci1yYWRpdXM6NTAlO2ZsZXgtc2hyaW5rOjAiPjwvZGl2PgogICAgICAgICAgICA8ZGl2PjxkaXYgc3R5bGU9ImZvbnQtd2VpZ2h0OjcwMDtjb2xvcjojMjJjNTVlO2ZvbnQtc2l6ZToxMS41cHgiPlPDiUNVUklUw4kgKFNSKTwvZGl2PjxkaXYgc3R5bGU9ImZvbnQtc2l6ZToxMHB4O2NvbG9yOnJnYmEoMTY4LDE4NywyMTIsMC44KSI+Vm9sYXRpbGl0w6kgdHLDqHMgZmFpYmxlIMK3IFJpc3F1ZSAxLTIvNzwvZGl2PjwvZGl2PgogICAgICAgICAgPC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJyaXNrLWNhcmQiIGRhdGEtcHJvZmlsZT0icHJ1ZGVudCIgb25jbGljaz0ic2VsZWN0Umlza1Byb2ZpbGUodGhpcykiIHN0eWxlPSJib3JkZXI6MXB4IHNvbGlkIHJnYmEoMjU1LDI1NSwyNTUsMC4xKTtib3JkZXItcmFkaXVzOjhweDtwYWRkaW5nOjEwcHggMTJweDtjdXJzb3I6cG9pbnRlcjtkaXNwbGF5OmZsZXg7YWxpZ24taXRlbXM6Y2VudGVyO2dhcDoxMHB4O2JhY2tncm91bmQ6cmdiYSgyNTUsMjU1LDI1NSwwLjAzKSI+CiAgICAgICAgICAgIDxkaXYgc3R5bGU9IndpZHRoOjEwcHg7aGVpZ2h0OjEwcHg7YmFja2dyb3VuZDojMjk1MWEzO2JvcmRlci1yYWRpdXM6NTAlO2ZsZXgtc2hyaW5rOjAiPjwvZGl2PgogICAgICAgICAgICA8ZGl2PjxkaXYgc3R5bGU9ImZvbnQtd2VpZ2h0OjcwMDtjb2xvcjojNjBhNWZhO2ZvbnQtc2l6ZToxMS41cHgiPlBSVURFTlQgKFApPC9kaXY+PGRpdiBzdHlsZT0iZm9udC1zaXplOjEwcHg7Y29sb3I6cmdiYSgxNjgsMTg3LDIxMiwwLjgpIj5WYXJpYXRpb24gbW9kw6lyw6llIMK3IFJpc3F1ZSAzLTQvNzwvZGl2PjwvZGl2PgogICAgICAgICAgPC9kaXY+CiAgICAgICAgICA8ZGl2IGNsYXNzPSJyaXNrLWNhcmQiIGRhdGEtcHJvZmlsZT0iZXF1aWxpYnJlIiBvbmNsaWNrPSJzZWxlY3RSaXNrUHJvZmlsZSh0aGlzKSIgc3R5bGU9ImJvcmRlcjoxcHggc29saWQgcmdiYSgyNTUsMjU1LDI1NSwwLjEpO2JvcmRlci1yYWRpdXM6OHB4O3BhZGRpbmc6MTBweCAxMnB4O2N1cnNvcjpwb2ludGVyO2Rpc3BsYXk6ZmxleDthbGlnbi1pdGVtczpjZW50ZXI7Z2FwOjEwcHg7YmFja2dyb3VuZDpyZ2JhKDI1NSwyNTUsMjU1LDAuMDMpIj4KICAgICAgICAgICAgPGRpdiBzdHlsZT0id2lkdGg6MTBweDtoZWlnaHQ6MTBweDtiYWNrZ3JvdW5kOiNlNjdlMjI7Ym9yZGVyLXJhZGl1czo1MCU7ZmxleC1zaHJpbms6MCI+PC9kaXY+CiAgICAgICAgICAgIDxkaXY+PGRpdiBzdHlsZT0iZm9udC13ZWlnaHQ6NzAwO2NvbG9yOiNlNjdlMjI7Zm9udC1zaXplOjExLjVweCI+w4lRVUlMSUJSw4kgKEUpPC9kaXY+PGRpdiBzdHlsZT0iZm9udC1zaXplOjEwcHg7Y29sb3I6cmdiYSgxNjgsMTg3LDIxMiwwLjgpIj5Wb2xhdGlsaXTDqSBtb3llbm5lIMK3IFJpc3F1ZSA1Lzc8L2Rpdj48L2Rpdj4KICAgICAgICAgIDwvZGl2PgogICAgICAgICAgPGRpdiBjbGFzcz0icmlzay1jYXJkIiBkYXRhLXByb2ZpbGU9ImR5bmFtaXF1ZSIgb25jbGljaz0ic2VsZWN0Umlza1Byb2ZpbGUodGhpcykiIHN0eWxlPSJib3JkZXI6MXB4IHNvbGlkIHJnYmEoMjU1LDI1NSwyNTUsMC4xKTtib3JkZXItcmFkaXVzOjhweDtwYWRkaW5nOjEwcHggMTJweDtjdXJzb3I6cG9pbnRlcjtkaXNwbGF5OmZsZXg7YWxpZ24taXRlbXM6Y2VudGVyO2dhcDoxMHB4O2JhY2tncm91bmQ6cmdiYSgyNTUsMjU1LDI1NSwwLjAzKSI+CiAgICAgICAgICAgIDxkaXYgc3R5bGU9IndpZHRoOjEwcHg7aGVpZ2h0OjEwcHg7YmFja2dyb3VuZDojYzAzOTJiO2JvcmRlci1yYWRpdXM6NTAlO2ZsZXgtc2hyaW5rOjAiPjwvZGl2PgogICAgICAgICAgICA8ZGl2PjxkaXYgc3R5bGU9ImZvbnQtd2VpZ2h0OjcwMDtjb2xvcjojYzAzOTJiO2ZvbnQtc2l6ZToxMS41cHgiPkRZTkFNSVFVRSAoRCk8L2Rpdj48ZGl2IHN0eWxlPSJmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDE2OCwxODcsMjEyLDAuOCkiPkZvcnRlIHZvbGF0aWxpdMOpIMK3IFJpc3F1ZSA2LTcvNzwvZGl2PjwvZGl2PgogICAgICAgICAgPC9kaXY+CiAgICAgICAgPC9kaXY+CiAgICAgICAgPGRpdiBzdHlsZT0ibWFyZ2luLXRvcDoxMHB4O3BhZGRpbmc6OHB4IDEycHg7YmFja2dyb3VuZDp2YXIoLS1jcmVhbTIpO2JvcmRlci1yYWRpdXM6NnB4O2ZvbnQtc2l6ZToxMnB4Ij4KICAgICAgICAgIDxzdHJvbmc+UHJvZmlsIHPDqWxlY3Rpb25uw6kgOjwvc3Ryb25nPiA8c3BhbiBpZD0icmlzay1zZWxlY3RlZCIgc3R5bGU9ImZvbnQtd2VpZ2h0OjcwMDtjb2xvcjp2YXIoLS1uYXZ5KSI+4oCUIMOAIHPDqWxlY3Rpb25uZXI8L3NwYW4+CiAgICAgICAgPC9kaXY+CiAgICAgICAgPGlucHV0IHR5cGU9ImhpZGRlbiIgaWQ9InJpc2stcHJvZmlsZS12YWx1ZSIgdmFsdWU9IiI+CiAgICAgIDwvZGl2PgogICAgPC9kaXY+CiAgPC9kaXY+CgogIDwhLS0gUVVFU1RJT05TIENPTVBPUlRFTUVOVEFMRVMgLS0+CiAgPGRpdiBjbGFzcz0iY2FyZCIgc3R5bGU9Im1hcmdpbi1ib3R0b206MTJweCI+CiAgICA8ZGl2IGNsYXNzPSJjYXJkLXRpdGxlIj5RdWVzdGlvbnMgY29tcG9ydGVtZW50YWxlczwvZGl2PgoKICAgIDxkaXYgc3R5bGU9Im1hcmdpbi1ib3R0b206MTRweCI+CiAgICAgIDxwIHN0eWxlPSJmb250LXNpemU6MTJweDtmb250LXdlaWdodDo2MDA7Y29sb3I6dmFyKC0tbmF2eSk7bWFyZ2luLWJvdHRvbTo4cHgiPjEuIFNpIGRlbWFpbiwgbGEgdmFsZXVyIGRlIG1vbiBwbGFjZW1lbnQgdmVuYWl0IMOgIGNodXRlciBkZSAyMCXigKY8L3A+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3ExIiB2YWx1ZT0iNSI+IEplIHZlbmRzIGltbcOpZGlhdGVtZW50IFRPVVQgbW9uIHBsYWNlbWVudCBldCByYWNow6h0ZSBkZXMgYWN0aWZzIG1vaW5zIHJpc3F1w6lzPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTEiIHZhbHVlPSIxMCI+IEplIHZlbmRzIFVORSBQQVJUSUUgZGUgY2V0IGludmVzdGlzc2VtZW50IGV0IHJhY2jDqHRlIGRlcyBhY3RpZnMgbW9pbnMgcmlzcXXDqXM8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMSIgdmFsdWU9IjE1Ij4gSmUgY29uc2VydmUgbW9uIGludmVzdGlzc2VtZW50IGNhciBsYSB2YWxldXIgdmEgY2VydGFpbmVtZW50IHJlbW9udGVyPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTEiIHZhbHVlPSIyMCI+IEonZW4gcmFjaMOodGUgZW5jb3JlIHBsdXMgcG91ciBkaW1pbnVlciBtb24gY2/Du3QgZGUgcmV2aWVudDwvbGFiZWw+CiAgICA8L2Rpdj4KCiAgICA8ZGl2IHN0eWxlPSJtYXJnaW4tYm90dG9tOjE0cHgiPgogICAgICA8cCBzdHlsZT0iZm9udC1zaXplOjEycHg7Zm9udC13ZWlnaHQ6NjAwO2NvbG9yOnZhcigtLW5hdnkpO21hcmdpbi1ib3R0b206OHB4Ij4yLiBBdmV6LXZvdXMgZMOpasOgIHN1YmkgZGVzIHBlcnRlcyBkYW5zIGxlIHBhc3PDqSA/IFNpIG91aSwgY29tbWVudCBhdmV6LXZvdXMgcsOpYWdpID88L3A+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3EyIiB2YWx1ZT0iNSI+IEonYWkgdmVuZHU8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMiIgdmFsdWU9IjEwIj4gSidhaSB2ZW5kdSB1bmUgcGFydGllPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTIiIHZhbHVlPSIxNSI+IEonYWkgdG91dCBjb25zZXJ2w6k8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMiIgdmFsdWU9IjIwIj4gSidhaSByw6lpbnZlc3RpPC9sYWJlbD4KICAgIDwvZGl2PgoKICAgIDxkaXYgc3R5bGU9Im1hcmdpbi1ib3R0b206MTRweCI+CiAgICAgIDxwIHN0eWxlPSJmb250LXNpemU6MTJweDtmb250LXdlaWdodDo2MDA7Y29sb3I6dmFyKC0tbmF2eSk7bWFyZ2luLWJvdHRvbTo4cHgiPjMuIENvbW1lbnQgYXZlei12b3VzIHbDqWN1IGxlcyBkZXJuacOocmVzIHNlY291c3NlcyBmaW5hbmNpw6hyZXMgZGVzIG1hcmNow6lzID88L3A+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3EzIiB2YWx1ZT0iNSI+IEplIG4nZW4gZG9ybWFpcyBwYXMgbGEgbnVpdDwvbGFiZWw+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3EzIiB2YWx1ZT0iMTAiPiBUcsOocyBiaWVuLCBqZSBuJ8OpdGFpcyBwYXMgYXUgY291cmFudDwvbGFiZWw+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3EzIiB2YWx1ZT0iMTUiPiBKJ2FpIHN1aXZpIMOnYSBkZSBwcsOocyBtYWlzIHNhbnMgcGFuaXF1ZXI8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxMyIgdmFsdWU9IjIwIj4gVHLDqHMgYmllbi4gQ2VsYSByZW1vbnRlIHRvdWpvdXJzIGV0IG1lcyBwbGFjZW1lbnRzIHNvbnQgc29saWRlczwvbGFiZWw+CiAgICA8L2Rpdj4KCiAgICA8ZGl2IHN0eWxlPSJtYXJnaW4tYm90dG9tOjE0cHgiPgogICAgICA8cCBzdHlsZT0iZm9udC1zaXplOjEycHg7Zm9udC13ZWlnaHQ6NjAwO2NvbG9yOnZhcigtLW5hdnkpO21hcmdpbi1ib3R0b206OHB4Ij40LiBMZSBjcml0w6hyZSBkZSBsaXF1aWRpdMOpIGVzdCBpbXBvcnRhbnQgZGFucyBsZSBjYWRyZSBkZSBtb24gcGF0cmltb2luZeKApjwvcD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTQiIHZhbHVlPSI1Ij4gSmUgdmV1eCB0b3Vqb3VycyBhdm9pciB1bmUgcGFydCBpbXBvcnRhbnRlIGRlIG1vbiBwYXRyaW1vaW5lIGxpcXVpZGUsIGF1IGNhcyBvw7k8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNCIgdmFsdWU9IjEwIj4gSmUgc291aGFpdGUgY29uc2VydmVyIHVuIHBldGl0IG1hdGVsYXMgZGUgc8OpY3VyaXTDqTwvbGFiZWw+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3E0IiB2YWx1ZT0iMTUiPiBKZSBuZSBnYXJkZSBxdWUgY2UgZG9udCBqJ2FpIHZyYWltZW50IGJlc29pbiBjYXIgamUgc2FpcyBwb3V2b2lyIHZlbmRyZSBkZXMgYWN0aWZzIHJhcGlkZW1lbnQgc2FucyBwcm9ibMOobWU8L2xhYmVsPgogICAgPC9kaXY+CgogICAgPGRpdiBzdHlsZT0ibWFyZ2luLWJvdHRvbToxNHB4Ij4KICAgICAgPHAgc3R5bGU9ImZvbnQtc2l6ZToxMnB4O2ZvbnQtd2VpZ2h0OjYwMDtjb2xvcjp2YXIoLS1uYXZ5KTttYXJnaW4tYm90dG9tOjhweCI+NS4gRGFucyBsYSB2aWUsIGFpbWV6LXZvdXMgcHJlbmRyZSBkZXMgcmlzcXVlcyAoc3BvcnQsIGpldXgsIHBhcmnigKYpID88L3A+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3E1IiB2YWx1ZT0iNSI+IE5vbjwvbGFiZWw+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3E1IiB2YWx1ZT0iMTAiPiBQYXJmb2lzLCBzaSBsZXMgY29uc8OpcXVlbmNlcyBzb250IGZhaWJsZXM8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNSIgdmFsdWU9IjE1Ij4gQXNzZXogc291dmVudCwgc2kgamUgbWHDrnRyaXNlIGxlcyByaXNxdWVzIGV0IGxldXJzIGNvbnPDqXF1ZW5jZXM8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNSIgdmFsdWU9IjIwIj4gQXV0YW50IHF1ZSBqZSBwZXV4LiBKJ2FpbWUgbCdhZHLDqW5hbGluZSwgcXUnaW1wb3J0ZSBsZXMgY29uc8OpcXVlbmNlczwvbGFiZWw+CiAgICA8L2Rpdj4KCiAgICA8ZGl2IHN0eWxlPSJtYXJnaW4tYm90dG9tOjE0cHgiPgogICAgICA8cCBzdHlsZT0iZm9udC1zaXplOjEycHg7Zm9udC13ZWlnaHQ6NjAwO2NvbG9yOnZhcigtLW5hdnkpO21hcmdpbi1ib3R0b206OHB4Ij42LiBDb21tZSBpbmRpcXXDqSBwcsOpY8OpZGVtbWVudCwgdm90cmUgcHJpbmNpcGFsIG9iamVjdGlmIGEgdW5lIMOpY2jDqWFuY2UgZGXigKY8L3A+CiAgICAgIDxsYWJlbCBjbGFzcz0icmFkaW8tb3B0Ij48aW5wdXQgdHlwZT0icmFkaW8iIG5hbWU9InJpc3E2IiB2YWx1ZT0iNSI+IEVudHJlIDYgbW9pcyBldCAzIGFucyAoY291cnQgdGVybWUsIHByaXNlIGRlIHJpc3F1ZSBmYWlibGUpPC9sYWJlbD4KICAgICAgPGxhYmVsIGNsYXNzPSJyYWRpby1vcHQiPjxpbnB1dCB0eXBlPSJyYWRpbyIgbmFtZT0icmlzcTYiIHZhbHVlPSIxMCI+IEVudHJlIDQgZXQgMTAgYW5zIChtb3llbiB0ZXJtZSwgcHJpc2UgZGUgcmlzcXVlIMOpcXVpbGlicsOpZSk8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNiIgdmFsdWU9IjE1Ij4gRW50cmUgMTEgZXQgMTUgYW5zIChsb25nIHRlcm1lLCBwcmlzZSBkZSByaXNxdWUgZm9ydCk8L2xhYmVsPgogICAgICA8bGFiZWwgY2xhc3M9InJhZGlvLW9wdCI+PGlucHV0IHR5cGU9InJhZGlvIiBuYW1lPSJyaXNxNiIgdmFsdWU9IjIwIj4gU3Vww6lyaWV1ciDDoCAxNSBhbnMgKHRyw6hzIGxvbmcgdGVybWUsIHByaXNlIGRlIHJpc3F1ZSDDqWxldsOpZSk8L2xhYmVsPgogICAgPC9kaXY+CiAgPC9kaXY+CgogIDwhLS0gUsOJU1VMVEFUIFJJU1FVRSAtLT4KICA8ZGl2IGNsYXNzPSJjYXJkIiBzdHlsZT0iYmFja2dyb3VuZDp2YXIoLS1jcmVhbTIpO2JvcmRlcjpub25lO21hcmdpbi1ib3R0b206MTJweCI+CiAgICA8ZGl2IHN0eWxlPSJkaXNwbGF5OmZsZXg7YWxpZ24taXRlbXM6Y2VudGVyO2dhcDoxNnB4O2ZsZXgtd3JhcDp3cmFwIj4KICAgICAgPGRpdiBzdHlsZT0iZmxleDoxIj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTFweDtjb2xvcjpyZ2JhKDE2OCwxODcsMjEyLDAuOCk7dGV4dC10cmFuc2Zvcm06dXBwZXJjYXNlO2xldHRlci1zcGFjaW5nOi40cHg7bWFyZ2luLWJvdHRvbTo0cHgiPlNjb3JlIHJpc3F1ZTwvZGl2PgogICAgICAgIDxkaXYgaWQ9InJpc2stc2NvcmUtdmFsIiBzdHlsZT0iZm9udC1zaXplOjIycHg7Zm9udC13ZWlnaHQ6NzAwO2NvbG9yOnZhcigtLW5hdnkpIj7igJQ8L2Rpdj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDE2OCwxODcsMjEyLDAuOCkiPi8gMTIwIHB0czwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0iZmxleDoxIj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTFweDtjb2xvcjpyZ2JhKDE2OCwxODcsMjEyLDAuOCk7dGV4dC10cmFuc2Zvcm06dXBwZXJjYXNlO2xldHRlci1zcGFjaW5nOi40cHg7bWFyZ2luLWJvdHRvbTo0cHgiPlByb2ZpbCBjYWxjdWzDqTwvZGl2PgogICAgICAgIDxkaXYgaWQ9InJpc2stcHJvZmlsLWNhbGMiIHN0eWxlPSJmb250LXNpemU6MTZweDtmb250LXdlaWdodDo3MDA7Y29sb3I6dmFyKC0tbmF2eSkiPuKAlDwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdiBzdHlsZT0iZmxleDoxIj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDE2OCwxODcsMjEyLDAuOCk7bWFyZ2luLWJvdHRvbTo2cHgiPjMwLTUxIDogU8OpY3VyaXTDqSDCtyA1Mi03MiA6IFBydWRlbnQ8YnI+NzMtOTQgOiDDiXF1aWxpYnLDqSDCtyA5NS0xMTUgOiBEeW5hbWlxdWU8L2Rpdj4KICAgICAgICA8YnV0dG9uIGNsYXNzPSJidG4gYnAyIGJzbSIgb25jbGljaz0iY2FsY1Jpc2tTY29yZSgpIj5DYWxjdWxlciBsZSBzY29yZTwvYnV0dG9uPgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8IS0tIFLDiUNBUElUVUxBVElGIEZJTkFMIC0tPgogIDxkaXYgY2xhc3M9ImNhcmQiIHN0eWxlPSJiYWNrZ3JvdW5kOmxpbmVhci1ncmFkaWVudCgxMzVkZWcsdmFyKC0tbmF2eSksdmFyKC0tbmF2eTIpKTtib3JkZXI6bm9uZTttYXJnaW4tYm90dG9tOjEycHgiPgogICAgPGRpdiBzdHlsZT0iZm9udC1mYW1pbHk6J1BsYXlmYWlyIERpc3BsYXknLHNlcmlmO2ZvbnQtc2l6ZToxNXB4O2ZvbnQtd2VpZ2h0OjcwMDtjb2xvcjp2YXIoLS1nb2xkMik7bWFyZ2luLWJvdHRvbToxMnB4Ij5Sw6lzdWx0YXQg4oCUIFByb2ZpbCBkZSByaXNxdWUgY2xpZW50PC9kaXY+CiAgICA8ZGl2IHN0eWxlPSJkaXNwbGF5OmdyaWQ7Z3JpZC10ZW1wbGF0ZS1jb2x1bW5zOjFmciAxZnIgMWZyO2dhcDoxMnB4Ij4KICAgICAgPGRpdj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDI1NSwyNTUsMjU1LC41KTt0ZXh0LXRyYW5zZm9ybTp1cHBlcmNhc2U7bWFyZ2luLWJvdHRvbTo0cHgiPlNjb3JlIGNvbm5haXNzYW5jZTwvZGl2PgogICAgICAgIDxkaXYgaWQ9InJlc3VsdC1zY29yZS1rbiIgc3R5bGU9ImZvbnQtc2l6ZToxOHB4O2ZvbnQtd2VpZ2h0OjcwMDtjb2xvcjp3aGl0ZSI+4oCUPC9kaXY+CiAgICAgICAgPGRpdiBpZD0icmVzdWx0LWNhdC1rbiIgc3R5bGU9ImZvbnQtc2l6ZToxMXB4O2NvbG9yOnJnYmEoMjU1LDI1NSwyNTUsLjcpIj7igJQ8L2Rpdj4KICAgICAgPC9kaXY+CiAgICAgIDxkaXY+CiAgICAgICAgPGRpdiBzdHlsZT0iZm9udC1zaXplOjEwcHg7Y29sb3I6cmdiYSgyNTUsMjU1LDI1NSwuNSk7dGV4dC10cmFuc2Zvcm06dXBwZXJjYXNlO21hcmdpbi1ib3R0b206NHB4Ij5Qcm9maWwgZ3JhcGhpcXVlPC9kaXY+CiAgICAgICAgPGRpdiBpZD0icmVzdWx0LXByb2ZpbGUtZ3JhcGgiIHN0eWxlPSJmb250LXNpemU6MThweDtmb250LXdlaWdodDo3MDA7Y29sb3I6d2hpdGUiPuKAlDwvZGl2PgogICAgICA8L2Rpdj4KICAgICAgPGRpdj4KICAgICAgICA8ZGl2IHN0eWxlPSJmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDI1NSwyNTUsMjU1LC41KTt0ZXh0LXRyYW5zZm9ybTp1cHBlcmNhc2U7bWFyZ2luLWJvdHRvbTo0cHgiPlByb2ZpbCBjYWxjdWzDqTwvZGl2PgogICAgICAgIDxkaXYgaWQ9InJlc3VsdC1wcm9maWxlLWNhbGMiIHN0eWxlPSJmb250LXNpemU6MThweDtmb250LXdlaWdodDo3MDA7Y29sb3I6d2hpdGUiPuKAlDwvZGl2PgogICAgICA8L2Rpdj4KICAgIDwvZGl2PgogICAgPGRpdiBzdHlsZT0ibWFyZ2luLXRvcDoxMHB4O3BhZGRpbmctdG9wOjhweDtib3JkZXItdG9wOjFweCBzb2xpZCByZ2JhKDI1NSwyNTUsMjU1LC4xKTtmb250LXNpemU6MTBweDtjb2xvcjpyZ2JhKDI1NSwyNTUsMjU1LC40KSI+RW4gY2FzIGQnaW5jb2jDqXJlbmNlIGVudHJlIGxlIHByb2ZpbCBzw6lsZWN0aW9ubsOpIGV0IGxlIHByb2ZpbCBjYWxjdWzDqSwgbGUgY29uc2VpbGxlciBkb2l0IGRvY3VtZW50ZXIgZXQganVzdGlmaWVyIGxhIHJlY29tbWFuZGF0aW9uLjwvZGl2PgogIDwvZGl2PgoKICA8IS0tIFNJR05BVFVSRSAtLT4KICA8ZGl2IGNsYXNzPSJjYXJkIj4KICAgIDxkaXYgY2xhc3M9ImNhcmQtdGl0bGUiPkNlcnRpZmljYXRpb24gZXQgU2lnbmF0dXJlPC9kaXY+CiAgICA8ZGl2IGNsYXNzPSJpbmZvLWJveCI+SmUgY2VydGlmaWUgbCdleGFjdGl0dWRlIGRlcyBpbmZvcm1hdGlvbnMgZm91cm5pZXMgY2ktZGVzc3VzIGV0IHJlY29ubmFpcyBhdm9pciDDqXTDqSBpbmZvcm3DqShlKSBkZXMgcmlzcXVlcyBsacOpcyBhdXggcGxhY2VtZW50cyBmaW5hbmNpZXJzIGNvbmZvcm3DqW1lbnQgw6AgbGEgcsOpZ2xlbWVudGF0aW9uIE1JRjIuPC9kaXY+CiAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyaWQiPgogICAgICA8ZGl2IGNsYXNzPSJmb3JtLWdyb3VwIj48bGFiZWwgY2xhc3M9ImZsIj5GYWl0IMOgPC9sYWJlbD48aW5wdXQgaWQ9ImVyLWxpZXUiIGNsYXNzPSJmYyIgcGxhY2Vob2xkZXI9IlBhcmlzIj48L2Rpdj4KICAgICAgPGRpdiBjbGFzcz0iZm9ybS1ncm91cCI+PGxhYmVsIGNsYXNzPSJmbCI+TGU8L2xhYmVsPjxpbnB1dCBpZD0iZXItZGF0ZSIgY2xhc3M9ImZjIiB0eXBlPSJkYXRlIj48L2Rpdj4KICAgIDwvZGl2PgogICAgPGRpdiBzdHlsZT0ibWFyZ2luLXRvcDoxMnB4Ij4KICAgICAgPGxhYmVsIGNsYXNzPSJmbCI+U2lnbmF0dXJlIGNsaWVudDwvbGFiZWw+CiAgICAgIDxjYW52YXMgaWQ9ImVyLXNpZy1jYW52YXMiIHN0eWxlPSJib3JkZXI6MS41cHggZGFzaGVkIHZhcigtLWJkcik7Ym9yZGVyLXJhZGl1czo2cHg7aGVpZ2h0OjkwcHg7d2lkdGg6MTAwJTtkaXNwbGF5OmJsb2NrO21hcmdpbi10b3A6NnB4O2JhY2tncm91bmQ6I2ZhZmFmYSI+PC9jYW52YXM+CiAgICAgIDxidXR0b24gY2xhc3M9ImJ0biBiZ2ggYnNtIiBvbmNsaWNrPSJlckNsZWFyU2lnKCkiIHN0eWxlPSJtYXJnaW4tdG9wOjZweCI+RWZmYWNlciBsYSBzaWduYXR1cmU8L2J1dHRvbj4KICAgIDwvZGl2PgogIDwvZGl2PgoKICA8ZGl2IGNsYXNzPSJxLW5hdi1idG5zIiBzdHlsZT0iZGlzcGxheTpmbGV4O2p1c3RpZnktY29udGVudDpmbGV4LXN0YXJ0O21hcmdpbi10b3A6MTZweCI+CiAgICA8YnV0dG9uIGNsYXNzPSJidG4gYmdoIiBvbmNsaWNrPSJnb0Nvbm5haXNzYW5jZSgzKSI+4oaQIFJldG91ciBDb25uYWlzc2FuY2U8L2J1dHRvbj4KICA8L2Rpdj4KPC9kaXY+CjwvZGl2Pg==";

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
        CLIENT=Object.assign({email:email,prenom:a.prenom||'',nom:a.nom||'',docs:[],msgs:[],parcoursData:{},rapports:[],rapportsVus:[],notes:[]},a.clientData||{});
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
    CLIENT={email:match.email,prenom:match.prenom||'',nom:match.nom||'',docs:[],msgs:[],parcoursData:{},rapports:[],rapportsVus:[],notes:[]};
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
  if(name==='objectifs')renderObjectifs();
  if(name==='connaissance')renderConnaissance();
  if(name==='documents')renderDocs();
  if(name==='rapports'){renderRapports();renderNotes();}
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
  // Progression dossier
  var pd=CLIENT.parcoursData||{};
  var filled=Object.keys(pd).filter(function(k){return pd[k];}).length;
  var pct=Math.min(100,Math.round(filled/50*100));
  if(e('k-progress'))e('k-progress').textContent=pct+'%';
  // Actions
  var actions=[];
  var docs=(CLIENT.docs||[]).filter(function(d){return d.status!=='signed';});
  if(docs.length)actions.push('✍️ '+docs.length+' document(s) à signer');
  var vus=CLIENT.rapportsVus||[];
  var newRap=(CLIENT.rapports||[]).filter(function(r){return vus.indexOf(String(r.id))<0;}).length;
  if(newRap)actions.push('📚 '+newRap+' nouveau(x) rapport(s) disponible(s)');
  var unreadMsg=(CLIENT.msgs||[]).filter(function(m){return m.from!=='client'&&!m.read;}).length;
  if(unreadMsg)actions.push('💬 '+unreadMsg+' nouveau(x) message(s)');
  if(pct<50)actions.push('📋 Questionnaire objectifs à compléter');
  var ac=e('acc-actions');
  if(ac)ac.innerHTML=actions.length?actions.map(function(a){return'<div style="padding:6px 0;border-bottom:1px solid var(--bdr);color:var(--text2)">'+a+'</div>';}).join(''):'<div style="color:var(--text3)">Aucune action en attente ✓</div>';
  // Derniers messages
  var msgs=(CLIENT.msgs||[]).slice(-3).reverse();
  var am=e('acc-msgs');
  if(am)am.innerHTML=msgs.length?msgs.map(function(m){return'<div style="padding:6px 0;border-bottom:1px solid var(--bdr);font-size:12px"><span style="color:var(--text3)">'+m.date+'</span><br><span style="color:var(--text2)">'+escH(m.text.slice(0,60))+(m.text.length>60?'…':'')+'</span></div>';}).join(''):'<div style="color:var(--text3)">Aucun message récent.</div>';
}

// ═══ MESSAGES ═══
function syncMessages(){
  jbGet(MSG_BIN).then(function(data){
    var k=eKey(CLIENT.email);

    // ── Sync des notes globales publiées par le conseiller (champ "reportings",
    //    diffusées à TOUS les clients — indépendant de l'entrée par client)
    if(data.reportings&&data.reportings.length){
      var remoteNotes=data.reportings;
      var noteIds=new Set((CLIENT.notes||[]).map(function(n){return String(n.id||((n.titre||n.nom||'')+'|'+(n.dateAffichee||n.date||'')));}));
      remoteNotes.forEach(function(n){
        var nid=String(n.id||((n.titre||n.nom||'')+'|'+(n.dateAffichee||n.date||'')));
        if(!noteIds.has(nid)){
          if(!CLIENT.notes)CLIENT.notes=[];
          CLIENT.notes.push(n);
          noteIds.add(nid);
        }
      });
    }

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

    saveLocal();
    renderMsgs();
    renderKPIs();
    renderDocs();
    renderRapports();
    renderNotes();

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
// Notes globales publiées par le conseiller depuis le CRM (champ "reportings"
// dans MSG_BIN) — diffusées à tous les clients, distinctes des rapports
// personnalisés. Lecture défensive des noms de champs (le CRM peut évoluer).
function renderNotes(){
  var el=document.getElementById('notes-list');if(!el)return;
  var notes=(CLIENT&&CLIENT.notes)||[];
  if(!notes.length){el.innerHTML='';return;}

  function toTime(n){
    var d=n.datePublication||n.dateAffichee||n.date||'';
    var p=String(d).split('/');
    if(p.length===3)return new Date(p[2],p[1]-1,p[0]).getTime();
    return 0;
  }
  var sorted=notes.slice().sort(function(a,b){return toTime(b)-toTime(a);});

  el.innerHTML='<div class="rap-cat-h">📰 Notes de votre conseiller</div>'
    +sorted.map(function(n){
      var titre=n.titre||n.nom||n.title||'Note';
      var dateAff=n.dateAffichee||n.date||'';
      var contenu=n.contenu||n.texte||n.content||'';
      var pdfUrl=n.pdfUrl||n.url||n.lien||n.pdf||'';
      return '<div class="card" style="margin-bottom:12px">'
        +'<div style="display:flex;justify-content:space-between;align-items:flex-start;gap:12px">'
          +'<div style="font-size:14px;font-weight:600;color:var(--text)">'+escH(titre)+'</div>'
          +(dateAff?'<div style="font-size:11px;color:var(--text3);white-space:nowrap">'+escH(dateAff)+'</div>':'')
        +'</div>'
        +(contenu?'<div style="font-size:12.5px;color:var(--text2);margin-top:8px;line-height:1.6;white-space:pre-wrap">'+escH(contenu)+'</div>':'')
        +(pdfUrl?'<div style="margin-top:10px"><button class="btn btn-primary btn-sm" onclick="window.open(\''+escH(pdfUrl)+'\',\'_blank\')">⬇ Consulter le PDF</button></div>':'')
        +'</div>';
    }).join('');
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
      <div class="sb-section">Mon profil investisseur</div>
      <div class="nav-item" id="nav-objectifs" onclick="goPage('objectifs',this)"><span class="nav-icon">🎯</span>Objectifs & situation</div>
      <div class="nav-item" id="nav-connaissance" onclick="goPage('connaissance',this)"><span class="nav-icon">📊</span>Connaissance & expérience</div>
      <div class="sb-section">Documents & échanges</div>
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
          <div class="kpi"><div class="kpi-label">Dossier complété</div><div class="kpi-value" id="k-progress">—</div><div class="kpi-sub">questionnaires remplis</div></div>
        </div>
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
      </div>
