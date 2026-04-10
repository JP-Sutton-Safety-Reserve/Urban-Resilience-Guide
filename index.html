<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
<title>Safety Reserve — Urban Resilience Guide v19</title>
<link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=DM+Serif+Display&display=swap" rel="stylesheet">
<style>
:root {
  --blue:#4A6FA5; --blue-light:#EAF0F9; --blue-dark:#2C4A6E;
  --green:#4A8570; --green-light:#D8EDE6;
  --teal:#3D7872; --teal-light:#D0E8E5;
  --purple:#7264A8; --purple-light:#EAE8F5;
  --amber:#9B7035; --amber-light:#F5E9D5;
  --red:#A84040; --red-light:#FDEAEA;
  --yellow-hl:#FFF9C2; --yellow-bdr:#C8AA00;
  --bg:#F2F4F8; --white:#FFFFFF;
  --text:#2C3347; --text-mid:#5A6270; --text-light:#8E95A3;
  --border:#DDE2EA; --shadow:0 4px 24px rgba(44,51,71,0.10);
}
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:'Sora',sans-serif;background:var(--bg);color:var(--text);min-height:100vh}
#app{min-height:100vh;display:flex;flex-direction:column;align-items:center;padding:0 14px 40px}

/* MASTER PROGRESS */
.master-progress{width:100%;max-width:580px;padding:14px 0 10px;position:sticky;top:0;background:var(--bg);z-index:100}
.phase-pills{display:flex;gap:7px}
.phase-pill{flex:1;display:flex;flex-direction:column;align-items:center;gap:4px}
.phase-pill-bar{width:100%;height:4px;background:var(--border);border-radius:2px;overflow:hidden}
.phase-pill-fill{height:100%;border-radius:2px;transition:width .45s ease}
.phase-pill-label{font-size:10px;font-weight:600;color:var(--text-light);text-align:center;letter-spacing:.04em}
.phase-pill.active .phase-pill-label{color:var(--blue)}
.phase-pill.done .phase-pill-label{color:var(--green)}

/* PRE-FLOW PROGRESS */
.preflow-bar{width:100%;max-width:580px;padding:14px 0 10px;position:sticky;top:0;background:var(--bg);z-index:100}
.preflow-steps{display:flex;align-items:center;width:100%}
.pf-step{display:flex;flex-direction:column;align-items:center;flex:1;gap:4px}
.pf-dot{width:28px;height:28px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700;transition:all .3s;border:2px solid var(--border);background:white;color:var(--text-light)}
.pf-dot.active{border-color:var(--blue);background:var(--blue);color:white;box-shadow:0 0 0 4px var(--blue-light)}
.pf-dot.done{border-color:var(--green);background:var(--green);color:white}
.pf-label{font-size:9px;font-weight:700;letter-spacing:.05em;text-transform:uppercase;color:var(--text-light);text-align:center}
.pf-label.active{color:var(--blue)} .pf-label.done{color:var(--green)}
.pf-line{flex:1;height:2px;background:var(--border);max-width:40px;margin-top:-18px;align-self:center;transition:background .3s}
.pf-line.done{background:var(--green)}

/* STOP BAR */
.stop-bar{width:100%;max-width:580px;display:flex;justify-content:flex-end;padding:6px 0 0;position:sticky;top:0;z-index:101;pointer-events:none}
.stop-bar-inner{pointer-events:all}
.btn-stop{background:#fff;border:1.5px solid var(--border);border-radius:8px;padding:5px 11px;font-size:11px;font-weight:700;font-family:'Sora',sans-serif;cursor:pointer;color:var(--text-mid);display:flex;align-items:center;gap:5px;transition:all .15s;box-shadow:0 1px 4px rgba(44,51,71,.08)}
.btn-stop:hover{border-color:var(--red);color:var(--red)}

/* CARD */
.card{background:var(--white);border-radius:18px;padding:28px;max-width:560px;width:100%;box-shadow:var(--shadow);margin-top:10px}
.card-title{font-family:'DM Serif Display',serif;font-size:25px;color:var(--blue-dark);margin-bottom:5px;line-height:1.2}
.card-subtitle{font-size:13px;color:var(--text-mid);margin-bottom:20px;line-height:1.6}
.step-lbl{font-size:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--text-light);margin-bottom:5px}
.step-prog{height:4px;background:var(--border);border-radius:2px;overflow:hidden;margin-bottom:20px}
.step-prog-fill{height:100%;background:linear-gradient(90deg,var(--blue),var(--teal));border-radius:2px;transition:width .4s ease}

/* FORM */
.flabel{display:block;font-size:11px;font-weight:700;letter-spacing:.06em;text-transform:uppercase;color:var(--text);margin-bottom:6px}
.finput,.fselect{width:100%;padding:11px 14px;border:1.5px solid var(--border);border-radius:9px;font-size:16px;font-family:'Sora',sans-serif;color:var(--text);background:var(--white);outline:none;transition:border-color .2s}
.finput:focus,.fselect:focus{border-color:var(--blue)}
.fgroup{margin-bottom:14px} .fgroup:last-child{margin-bottom:0}
.err{font-size:11px;color:var(--red);margin-top:4px}

/* BUTTONS */
.btn{display:inline-flex;align-items:center;justify-content:center;gap:7px;padding:11px 20px;border:none;border-radius:10px;font-size:13px;font-weight:700;font-family:'Sora',sans-serif;cursor:pointer;transition:all .15s;-webkit-tap-highlight-color:transparent;min-height:44px;text-decoration:none}
.btn-primary{background:var(--blue-dark);color:white}
.btn-primary:hover{opacity:.9}
.btn-primary:disabled{background:var(--text-light);cursor:not-allowed}
.btn-outline{background:white;color:var(--text);border:1.5px solid var(--border)}
.btn-outline:hover{border-color:var(--blue)}
.btn-sm{padding:7px 13px;font-size:12px;border-radius:8px;min-height:36px}
.btn-row{display:flex;gap:8px;margin-top:18px}
.btn-row .btn-primary{flex:1}
.btn-danger{background:var(--red);color:white}
.btn-danger:hover{opacity:.9}

/* OPTION BUTTONS */
.opt{display:block;width:100%;padding:13px 17px;min-height:48px;border:1.5px solid var(--border);border-radius:10px;background:white;font-size:13px;font-weight:600;font-family:'Sora',sans-serif;cursor:pointer;text-align:left;transition:all .15s;color:var(--text);margin-bottom:9px;line-height:1.4;-webkit-tap-highlight-color:transparent}
.opt:last-child{margin-bottom:0}
.opt:hover,.opt.sel{border-color:var(--blue);background:var(--blue-light);color:var(--blue-dark)}

/* LOC LIST */
.loc-wrap{border:1.5px solid var(--blue);border-radius:10px;overflow:hidden;margin-bottom:14px}
.loc-head{display:flex;align-items:center;gap:7px;font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.08em;color:white;background:var(--blue);padding:7px 11px}
.loc-body{padding:7px 7px 3px}
.loc-chip{display:flex;align-items:center;gap:8px;padding:8px 10px;border-radius:7px;background:#F9FAFB;border:1.5px solid var(--border);margin-bottom:5px}
.loc-chip.home{background:var(--blue-light);border-color:#BDD0E6}
.lc-icon{font-size:16px;flex-shrink:0}
.lc-main{flex:1;min-width:0}
.lc-name{font-size:12px;font-weight:700;color:var(--text);line-height:1.3;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.lc-sub{font-size:10px;color:var(--text-light);line-height:1.2}
.home-badge{display:inline-flex;align-items:center;font-size:9px;font-weight:700;background:var(--blue-light);color:var(--blue-dark);padding:1px 7px;border-radius:20px;letter-spacing:.04em;border:1px solid #BDD0E6;margin-left:5px}
.rm-btn{background:none;border:none;cursor:pointer;color:var(--text-light);font-size:18px;padding:3px;line-height:1;flex-shrink:0}
.rm-btn:hover{color:var(--red)}

/* INFO BOXES */
.warn-box{background:#FFFBEE;border:1.5px solid #E0C55A;border-radius:9px;padding:10px 13px;margin-top:6px;font-size:12px;color:#6A5100;line-height:1.5}
.info-box{background:var(--blue-light);border:1.5px solid #BDD0E6;border-radius:9px;padding:10px 13px;font-size:12px;color:var(--blue-dark);line-height:1.5;margin-bottom:14px}
.success-box{background:var(--green-light);border:1.5px solid #9EC8B4;border-radius:9px;padding:10px 13px;font-size:12px;color:#1A5240;line-height:1.5;margin-bottom:14px}
.alert-box{background:var(--red-light);border:1.5px solid #EAB0B0;border-radius:9px;padding:10px 13px;font-size:12px;color:var(--red);line-height:1.5;margin-bottom:14px}
.counter{background:var(--blue-light);border:1.5px solid #BDD0E6;border-radius:9px;padding:8px 12px;margin-bottom:12px;font-size:12px;color:var(--blue-dark);font-weight:600;display:flex;align-items:center;gap:7px}

/* LEGAL */
.legal-check-row{display:flex;align-items:flex-start;gap:12px;padding:14px;border:2px solid var(--border);border-radius:10px;cursor:pointer;transition:all .2s;margin-top:4px}
.legal-check-row:hover{border-color:var(--blue);background:var(--blue-light)}
.legal-check-row.accepted{border-color:var(--green);background:var(--green-light)}
.legal-checkbox{width:22px;height:22px;border-radius:5px;border:2px solid var(--border);display:flex;align-items:center;justify-content:center;flex-shrink:0;margin-top:1px;transition:all .2s;background:white;font-size:13px}
.legal-check-row.accepted .legal-checkbox{border-color:var(--green);background:var(--green);color:white}
.legal-check-text{font-size:13px;font-weight:600;color:var(--text);line-height:1.5}
.legal-bullet{display:flex;gap:10px;padding:10px 0;border-bottom:1px solid var(--border);font-size:13px;line-height:1.6;color:var(--text)}
.legal-bullet:last-child{border-bottom:none}
.legal-bullet-icon{font-size:16px;flex-shrink:0;margin-top:1px;margin-left:14px}

/* INDENT */
.indent{margin-top:12px;padding:14px;background:#F7F9FC;border-radius:10px;border:1.5px solid var(--border)}
.indent-dash{border-style:dashed;margin-bottom:12px}

/* QUESTIONNAIRE */
.q-header{font-size:10px;font-weight:700;color:var(--text-mid);text-transform:uppercase;letter-spacing:.08em;margin-bottom:14px;padding:7px 11px;background:#F4F5F8;border-radius:8px;display:flex;align-items:center;gap:6px}
.multi-block{border:1.5px solid var(--border);border-radius:10px;overflow:hidden;margin-bottom:14px}
.multi-block:last-of-type{margin-bottom:0}
.multi-head{padding:9px 13px;display:flex;align-items:center;gap:8px;border-bottom:1.5px solid var(--border)}
.multi-opts{display:flex;flex-direction:column;gap:9px;padding:11px 13px}
.mini-opt{display:block;width:100%;padding:11px 14px;min-height:44px;border:1.5px solid var(--border);border-radius:8px;background:white;font-size:13px;font-weight:600;font-family:'Sora',sans-serif;cursor:pointer;text-align:left;transition:all .15s;color:var(--text);-webkit-tap-highlight-color:transparent}
.mini-opt:hover,.mini-opt.sel{border-color:var(--blue);background:var(--blue-light);color:var(--blue-dark)}

/* OUTPUT */
.ref-wrap{background:var(--bg);min-height:100vh;padding:18px;width:100%}
.ref-card{max-width:960px;margin:0 auto;background:white;border-radius:13px;box-shadow:var(--shadow);overflow:hidden}
.out-grid{display:grid;grid-template-columns:repeat(2,1fr)}
@media(max-width:600px){.out-grid{grid-template-columns:1fr!important}}

/* COMM PLAN */
.comm-table{width:100%;border-collapse:collapse;margin-bottom:14px}
.comm-table td{padding:10px 12px;border:1px solid var(--border);font-size:13px;vertical-align:top}
.comm-input{width:100%;border:none;font-size:13px;font-family:'Sora',sans-serif;color:var(--text);background:transparent;outline:none;margin-bottom:4px;pointer-events:auto;cursor:text;-webkit-user-select:text;user-select:text}
.comm-phone{width:100%;border:none;font-size:13px;font-family:'Sora',sans-serif;color:var(--text-mid);background:transparent;outline:none;pointer-events:auto;cursor:text;-webkit-user-select:text;user-select:text}

/* ESSENTIALS */
.ess-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:7px;margin-bottom:14px}
@media(max-width:380px){.ess-grid{grid-template-columns:1fr}}
.ess-item{display:flex;align-items:center;gap:7px;padding:10px 12px;border:1.5px solid var(--border);border-radius:9px;cursor:pointer;transition:all .15s;font-size:12px;font-weight:600;color:var(--text);background:white;user-select:none;-webkit-tap-highlight-color:transparent}
.ess-item:hover{border-color:var(--blue)}
.ess-item.sel{background:var(--yellow-hl);border-color:var(--yellow-bdr);color:#5A4700}
.ess-check{font-size:13px;flex-shrink:0}

/* DIVIDER */
.divider{display:flex;align-items:center;gap:10px;margin:18px 0;color:var(--text-light);font-size:11px;font-weight:600;letter-spacing:.05em;text-transform:uppercase}
.divider::before,.divider::after{content:'';flex:1;height:1px;background:var(--border)}

/* FINAL */
.action-cards{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin:18px 0}
.action-card{background:var(--blue-light);border:1.5px solid #BDD0E6;border-radius:12px;padding:16px;text-align:center;cursor:pointer;transition:all .15s}
.action-card:hover{border-color:var(--blue);transform:translateY(-2px)}
.action-card .ac-icon{font-size:30px;margin-bottom:7px}
.action-card .ac-title{font-weight:700;font-size:13px;color:var(--blue-dark);margin-bottom:3px}
.action-card .ac-desc{font-size:11px;color:var(--text-mid);line-height:1.4}

/* PRINT STATUS OVERLAY */
.print-overlay{position:fixed;inset:0;background:rgba(44,51,71,.6);z-index:9999;display:flex;align-items:center;justify-content:center;backdrop-filter:blur(3px)}
.print-modal{background:white;border-radius:18px;padding:28px 32px;max-width:380px;width:90%;box-shadow:0 8px 40px rgba(44,51,71,.25)}
.print-modal-title{font-family:'DM Serif Display',serif;font-size:20px;color:var(--blue-dark);margin-bottom:5px}
.print-modal-sub{font-size:12px;color:var(--text-mid);margin-bottom:18px}
.print-doc-row{display:flex;align-items:center;gap:10px;padding:9px 12px;border-radius:8px;background:#F7F9FC;margin-bottom:8px;font-size:13px;font-weight:600;color:var(--text)}
.print-doc-row .pd-icon{font-size:18px}
.print-doc-row .pd-check{margin-left:auto;font-size:16px;color:var(--green)}

/* SHIELD */
.shield{width:50px;height:50px;background:linear-gradient(135deg,var(--blue-dark),var(--blue));border-radius:13px;display:flex;align-items:center;justify-content:center;font-size:22px;margin-bottom:13px;box-shadow:0 2px 10px rgba(44,74,110,.25)}

/* PAUSED */
.paused-screen{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:24px;text-align:center}
.paused-icon{font-size:56px;margin-bottom:18px}
.btn-resume{background:var(--blue-dark);border:none;border-radius:10px;padding:12px 28px;font-size:14px;font-weight:700;font-family:'Sora',sans-serif;cursor:pointer;color:white;transition:all .15s}
.btn-resume:hover{opacity:.9}

/* RESUME BANNER */
.resume-banner{background:linear-gradient(135deg,#1A3A5C,var(--blue-dark));border-radius:16px;padding:24px 28px;max-width:560px;width:100%;margin-top:10px;color:white}
.resume-banner h2{font-family:'DM Serif Display',serif;font-size:22px;margin-bottom:6px}
.resume-banner p{font-size:13px;opacity:.85;line-height:1.6;margin-bottom:18px}
.resume-tag{display:inline-flex;align-items:center;gap:6px;background:rgba(255,255,255,.15);border-radius:8px;padding:5px 11px;font-size:12px;font-weight:600;margin-bottom:18px}
.resume-actions{display:flex;gap:10px;flex-wrap:wrap}
.btn-resume-main{background:white;color:var(--blue-dark);border:none;border-radius:10px;padding:11px 22px;font-size:13px;font-weight:700;font-family:'Sora',sans-serif;cursor:pointer;transition:all .15s}
.btn-resume-main:hover{opacity:.9}
.btn-resume-fresh{background:rgba(255,255,255,.15);color:white;border:1.5px solid rgba(255,255,255,.3);border-radius:10px;padding:11px 22px;font-size:13px;font-weight:700;font-family:'Sora',sans-serif;cursor:pointer;transition:all .15s}
.btn-resume-fresh:hover{background:rgba(255,255,255,.25)}

/* ADMIN PANEL */
.admin-overlay{position:fixed;inset:0;background:rgba(20,25,40,.92);z-index:9998;display:flex;align-items:flex-start;justify-content:center;overflow-y:auto;backdrop-filter:blur(4px);padding:20px 14px 40px}
.admin-panel{background:#1C2233;border-radius:18px;max-width:680px;width:100%;margin:auto;border:1px solid rgba(255,255,255,.08);box-shadow:0 20px 60px rgba(0,0,0,.5)}
.admin-header{background:linear-gradient(135deg,#0F1929,#1C3A5C);border-radius:18px 18px 0 0;padding:22px 28px;display:flex;align-items:center;justify-content:space-between}
.admin-header h1{font-family:'DM Serif Display',serif;font-size:22px;color:white}
.admin-header p{font-size:11px;color:rgba(255,255,255,.5);margin-top:3px}
.admin-close{background:rgba(255,255,255,.1);border:none;border-radius:8px;color:white;cursor:pointer;font-size:18px;padding:6px 10px;font-family:'Sora',sans-serif;transition:all .15s}
.admin-close:hover{background:rgba(255,255,255,.2)}
.admin-tabs{display:flex;gap:0;border-bottom:1px solid rgba(255,255,255,.08);padding:0 28px;overflow-x:auto}
.admin-tab{padding:12px 16px;font-size:12px;font-weight:700;font-family:'Sora',sans-serif;cursor:pointer;color:rgba(255,255,255,.45);border:none;background:none;border-bottom:2px solid transparent;transition:all .2s;white-space:nowrap}
.admin-tab:hover{color:rgba(255,255,255,.8)}
.admin-tab.active{color:white;border-bottom-color:#4A9EE8}
.admin-body{padding:24px 28px}
.admin-section-title{font-size:11px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:rgba(255,255,255,.4);margin-bottom:10px}
.admin-textarea{width:100%;min-height:180px;padding:12px;border:1px solid rgba(255,255,255,.12);border-radius:10px;font-size:12px;font-family:'Sora',sans-serif;color:#D4E3F8;background:rgba(255,255,255,.05);resize:vertical;outline:none;line-height:1.7;transition:border-color .2s}
.admin-textarea:focus{border-color:#4A9EE8}
.admin-input{width:100%;padding:10px 14px;border:1px solid rgba(255,255,255,.12);border-radius:9px;font-size:14px;font-family:'Sora',sans-serif;color:#D4E3F8;background:rgba(255,255,255,.05);outline:none;transition:border-color .2s}
.admin-input:focus{border-color:#4A9EE8}
.admin-label{display:block;font-size:11px;font-weight:700;letter-spacing:.05em;text-transform:uppercase;color:rgba(255,255,255,.5);margin-bottom:6px}
.admin-fgroup{margin-bottom:18px}
.admin-btn{display:inline-flex;align-items:center;gap:7px;padding:10px 18px;border:none;border-radius:9px;font-size:12px;font-weight:700;font-family:'Sora',sans-serif;cursor:pointer;transition:all .15s}
.admin-btn-primary{background:#4A9EE8;color:white}
.admin-btn-primary:hover{background:#3A8ED8}
.admin-btn-outline{background:rgba(255,255,255,.08);color:rgba(255,255,255,.7);border:1px solid rgba(255,255,255,.15)}
.admin-btn-outline:hover{background:rgba(255,255,255,.14)}
.admin-btn-danger{background:rgba(168,64,64,.4);color:#FCA5A5;border:1px solid rgba(168,64,64,.5)}
.admin-btn-danger:hover{background:rgba(168,64,64,.6)}
.admin-btn-row{display:flex;gap:9px;margin-top:12px;flex-wrap:wrap}
.admin-info{background:rgba(74,158,232,.12);border:1px solid rgba(74,158,232,.25);border-radius:8px;padding:10px 13px;font-size:11px;color:rgba(74,158,232,.9);line-height:1.6;margin-bottom:14px}
.admin-warn{background:rgba(155,112,53,.2);border:1px solid rgba(155,112,53,.4);border-radius:8px;padding:10px 13px;font-size:11px;color:#F5C76A;line-height:1.6;margin-bottom:14px}
.admin-success-msg{font-size:12px;color:#6EE7B7;font-weight:600;display:flex;align-items:center;gap:5px}
.admin-record-row{border-bottom:1px solid rgba(255,255,255,.06);padding:10px 0;font-size:12px;color:rgba(255,255,255,.65);line-height:1.6}
.admin-record-row:last-child{border-bottom:none}
.admin-badge{display:inline-flex;align-items:center;font-size:10px;font-weight:700;padding:2px 8px;border-radius:20px}
.badge-green{background:rgba(74,133,112,.3);color:#6EE7B7;border:1px solid rgba(74,133,112,.4)}
.badge-blue{background:rgba(74,111,165,.3);color:#93C5FD;border:1px solid rgba(74,111,165,.4)}

/* LOGIN SCREEN */
.admin-login{display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:100vh;padding:20px}
.admin-login-card{background:#1C2233;border-radius:18px;padding:36px 32px;max-width:380px;width:100%;border:1px solid rgba(255,255,255,.08);box-shadow:0 20px 60px rgba(0,0,0,.5)}
.admin-login-card .shield-dark{width:50px;height:50px;background:linear-gradient(135deg,#0F1929,#1C3A5C);border-radius:13px;display:flex;align-items:center;justify-content:center;font-size:22px;margin-bottom:16px;box-shadow:0 2px 10px rgba(0,0,0,.4)}

/* ANIMATIONS */
@keyframes fadeIn{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:translateY(0)}}
.fade-in{animation:fadeIn .3s ease}

/* PRINT */
@media print{
  *{-webkit-print-color-adjust:exact!important;print-color-adjust:exact!important;color-adjust:exact!important}
  .no-print{display:none!important}
  .ref-wrap{background:white!important;padding:0!important}
  .ref-card{box-shadow:none!important;border-radius:0!important}
  .out-grid{grid-template-columns:repeat(2,1fr)!important}
}
@media(max-width:480px){
  #app{padding:0 10px 40px}
  .card{padding:20px;border-radius:14px}
  .card-title{font-size:21px}
  .action-cards{grid-template-columns:1fr}
}
</style>
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcode-generator/1.4.4/qrcode.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
</head>
<body>
<div id="app"></div>

<!-- TOS OVERLAY -->
<div id="tosOverlay" style="display:none;position:fixed;inset:0;background:rgba(44,51,71,.72);z-index:9990;align-items:center;justify-content:center;padding:20px;backdrop-filter:blur(3px)">
  <div style="background:white;border-radius:16px;width:100%;max-width:560px;max-height:84vh;display:flex;flex-direction:column;box-shadow:0 12px 48px rgba(44,51,71,.28);overflow:hidden">
    <div style="display:flex;align-items:center;justify-content:space-between;padding:16px 20px;border-bottom:1px solid #DDE2EA;flex-shrink:0;background:#F7F9FC">
      <div style="font-family:'DM Serif Display',serif;font-size:17px;color:#2C4A6E">Terms of Service</div>
      <button onclick="closeTosOverlay()" style="background:none;border:none;cursor:pointer;font-size:20px;color:#8E95A3;padding:4px 6px;line-height:1;border-radius:6px">✕</button>
    </div>
    <div id="tosBody" style="flex:1;overflow-y:auto;padding:20px 22px;font-family:'Sora',sans-serif;font-size:13px;color:#2C3347;line-height:1.75"></div>
    <div style="padding:13px 20px;border-top:1px solid #DDE2EA;display:flex;justify-content:flex-end;align-items:center;flex-shrink:0;background:#F7F9FC;gap:10px;flex-wrap:wrap">
      <button onclick="closeTosOverlay()" style="background:#2C4A6E;color:white;border:none;border-radius:8px;padding:8px 20px;font-size:12px;font-weight:700;font-family:'Sora',sans-serif;cursor:pointer">Close</button>
    </div>
  </div>
</div>

<script>
/* =============================================================
   CONFIGURABLE DEFAULTS — Edit these before deploying
   ============================================================= */
const ADMIN_PASSWORD_DEFAULT = 'SafetyRes@2024!Admin'; // Change via Admin Panel after first login

/* =============================================================
   TOS OVERLAY
   ============================================================= */
function openTosOverlay(e){
  if(e)e.preventDefault();
  const url=getTosUrl();
  const isValidUrl=url&&url.trim()&&!url.includes('YOUR-TERMS-URL-HERE')&&(url.startsWith('http://')||url.startsWith('https://'));
  const overlay=document.getElementById('tosOverlay');
  const body=document.getElementById('tosBody');
  if(body){
    if(isValidUrl){
      body.innerHTML='<div style="text-align:center;padding:20px 0">'+
        '<div style="font-size:36px;margin-bottom:14px">📋</div>'+
        '<div style="font-family:DM Serif Display,serif;font-size:18px;color:#2C4A6E;margin-bottom:8px">J.P. Sutton Terms of Service</div>'+
        '<div style="font-size:12px;color:#5A6270;line-height:1.7;margin-bottom:20px">Click the button below to read the full Terms of Service document.</div>'+
        '<a href="'+url+'" target="_blank" rel="noopener noreferrer" style="display:inline-flex;align-items:center;gap:7px;background:#2C4A6E;color:white;padding:11px 22px;border-radius:10px;font-size:13px;font-weight:700;text-decoration:none;font-family:Sora,sans-serif">Open Terms of Service ↗</a>'+
        '<div style="font-size:10px;color:#8E95A3;margin-top:14px">Opens in a new tab</div>'+
        '</div>';
    } else {
      body.innerHTML='<div style="padding:4px 0">'+
        '<div style="font-weight:700;font-size:14px;color:#2C4A6E;margin-bottom:10px">J.P. Sutton Safety Reserve — Terms of Service</div>'+
        '<p style="margin-bottom:10px">By activating and using the Safety Reserve and its digital materials, you agree to the following:</p>'+
        '<ol style="padding-left:18px;line-height:1.8;color:#2C3347">'+
        '<li style="margin-bottom:8px">This product is a <strong>preparedness supplement</strong>, not a safety guarantee or emergency service.</li>'+
        '<li style="margin-bottom:8px">All content — including Location Scenarios, AI Real Time Situational Analysis, and Disruption Insights — is <strong>general information only</strong>. It does not constitute instructions, advice, guidance, or recommendations of any kind.</li>'+
        '<li style="margin-bottom:8px">The AI Real Time Situational Analysis is generated by a third-party AI system. Outputs may be <strong>incomplete, inaccurate, or outdated</strong>. Always defer to official authorities and your own judgment.</li>'+
        '<li style="margin-bottom:8px">You are responsible for maintaining your kit, keeping batteries charged, and replacing expired contents.</li>'+
        '<li style="margin-bottom:8px">J.P. Sutton accepts no liability for decisions made in reliance on this product or its content.</li>'+
        '<li>Use of this product is subject to the full J.P. Sutton Terms of Service, available at <strong>jpsutton.com</strong>.</li>'+
        '</ol>'+
        '<div style="margin-top:16px;padding:10px 13px;background:#F7F9FC;border-radius:8px;border:1px solid #DDE2EA;font-size:11px;color:#8E95A3">To configure the full Terms of Service URL, go to Admin Panel → ToS URL tab.</div>'+
        '</div>';
    }
  }
  if(overlay)overlay.style.display='flex';
}
function closeTosOverlay(){
  const overlay=document.getElementById('tosOverlay');
  if(overlay)overlay.style.display='none';
}
// Close overlay on backdrop click
document.addEventListener('DOMContentLoaded',function(){
  const overlay=document.getElementById('tosOverlay');
  if(overlay)overlay.addEventListener('click',function(e){if(e.target===this)closeTosOverlay();});
});
/* ── INSERT YOUR TERMS OF SERVICE URL BELOW ─────────────────────────
   Replace the placeholder with your actual Terms of Service URL.
   You can also update this via Admin Panel (Ctrl+Shift+A or #admin
   in URL) → 'ToS URL' tab, without editing this file.
   ─────────────────────────────────────────────────────────────── */
const TERMS_URL_DEFAULT      = 'https://jpsutton.com/policies/terms-of-service';
/* ── INSERT YOUR PUBLIC URL BELOW ────────────────────────────────────
   This is the URL encoded into QR codes so iPhones can open them.
   Must be an https:// address — file:// URLs won't work on phones.
   Example: 'https://yoursite.com/emergency_prep.html'
   ─────────────────────────────────────────────────────────────── */
const BASE_URL_DEFAULT       = 'https://fantastic-entremet-7788e3.netlify.app/emergency_prep_v13.html';
const AI_QUERY_DATE_DEFAULT  = 'March 20';

const ACTIVATION_CARD_TEMPLATE_DEFAULT = `An app will guide you through a short setup — about 5 minutes — to build your personalized pages. The AI Real Time Situational Analysis can only be downloaded to your phone; all other content can be printed and/or downloaded. Printed materials can be inserted in the slots provided in this guide.

For help, contact support@jpsutton.com`;

/* Storage keys */
const SK = {
  session:       'jps_session_v3',
  mainState:     'jps_main_state_v3',
  registrations: 'jps_registrations_v3',
  legalRecords:  'jps_legal_records_v3',
  adminPass:     'jps_admin_pass',
  welcomeHtml:   'jps_welcome_html',
  aiQueryText:   'jps_ai_query_text',
  safetyText:    'jps_safety_text',
  tosUrl:        'jps_tos_url',
  aiQueryDate:   'jps_ai_query_date',
  codes:         'jps_codes_v1',
  codeImage:     'jps_code_image_v1',
  activationCardTemplate: 'jps_activation_card_tpl_v1',
  disruptionInsights: 'jps_disruption_v2',
  recoveryKey:   'jps_recovery_key_v1',
  baseUrl:       'jps_base_url',
  questionLogic: 'jps_question_logic_v1',
};

function store(key,val){try{localStorage.setItem(key,typeof val==='string'?val:JSON.stringify(val));}catch(e){}}
function load(key,def=''){try{const v=localStorage.getItem(key);return v!==null?v:def;}catch(e){return def;}}
function loadJson(key,def){try{const v=localStorage.getItem(key);return v?JSON.parse(v):def;}catch(e){return def;}}

/* Config accessors */
function getAdminPass(){return load(SK.adminPass,ADMIN_PASSWORD_DEFAULT);}
function getTosUrl(){return load(SK.tosUrl,TERMS_URL_DEFAULT);}
function getAIQueryDate(){return load(SK.aiQueryDate,AI_QUERY_DATE_DEFAULT);}
function getBaseUrl(){
  const saved=load(SK.baseUrl,'');
  if(saved)return saved;
  // If running from a real https/http server, use that URL
  if(window.location.protocol==='https:'||window.location.protocol==='http:')
    return window.location.href.split('?')[0];
  // Local file — return the configured default
  return BASE_URL_DEFAULT;
}
/* ============================================================
   CODE GENERATOR HELPERS
   ============================================================ */
function loadCodes(){return loadJson(SK.codes,[]);}
function saveCodes(arr){store(SK.codes,arr);}
function genCodeStr(){
  const c='ABCDEFGHJKLMNPQRSTUVWXYZ23456789';
  let s='';for(let i=0;i<8;i++)s+=c[Math.floor(Math.random()*c.length)];
  return s;
}
function getCodeRecord(code){return loadCodes().find(r=>r.code===code.trim().toUpperCase());}
function freshNewCode(){
  S.newCodeStr=genCodeStr();
  S.newOrderNumber='';
  S.newCodeAdminText=load(SK.activationCardTemplate,ACTIVATION_CARD_TEMPLATE_DEFAULT);
  // Load persisted center image (survives page refresh)
  const _storedImg=load(SK.codeImage,'');
  S.newCodeImageData=_storedImg||null;
  S.newCodeQrUrl=getBaseUrl()+'?code='+S.newCodeStr;
}

/* =============================================================
   AI QUERY DOCUMENT DEFAULT CONTENT
   ============================================================= */
const AI_QUERY_DEFAULT = `AI Real Time Situational Analysis

ROLE: Provide real-time situational awareness under uncertainty using public data. Primary objective: Rapidly determine what is most likely happening, how reliable that conclusion is, and how people are reacting. Strictly descriptive. No advice, guidance, or recommendations.

1. INPUT GATE (HARD STOP)
Require: Incident Type + Location
Else: ERROR — Missing required input. Please specify both.

2. LOCATION EXPANSION ENGINE
Expand into:
• Micro: exact site, entrances, intersections
• Local: adjacent blocks, facilities
• Regional: city + infrastructure nodes
Include slang/shorthand names, abbreviations, landmark-based references.

3. INCIDENT DETECTION MATRIX
• Violent: gunfire, explosion, armed response
• Infrastructure: outage, gas leak, water issue
• Environmental: smoke, odor, hazmat
• Weather: storm damage, flooding
• Transport: shutdowns, collisions
• Civil: protest, unrest
• Unknown: boom, shaking, flashes

4. PATTERN RECOGNITION LAYER
Archetypes: Transformer explosion · Gas explosion · Active shooter · Fire/structural fire · Military strike · Controlled demolition · Severe weather impact · Infrastructure failure
Output: Most Likely Scenario + Confidence Drivers

5. SIGNAL SCORING ENGINE
HIGH weight: Source Tier, # independent confirmations, location precision
MEDIUM weight: Time proximity, content specificity
Output: Confidence Score 0–100
• 80–100 → High Confidence
• 50–79  → Moderate Confidence
• 0–49   → Low Confidence

6. CORROBORATION LOGIC
Promote signals if ≥2 independent Tier B/C matches within 24h, OR 1 Tier A confirmation. Else discard.

7. OUTPUT FORMAT (MOBILE-FIRST, ≤180 words)
🛡️ SITUATIONAL SNAPSHOT — Location / Time / Input
🧠 MOST LIKELY SCENARIO [1 line]
📊 CONFIDENCE — Score [X/100] / Level [High/Moderate/Low]
🔴 WHAT IS HAPPENING — Max 3 bullets (active, unresolved)
🟠 WHAT PEOPLE ARE DOING — Max 5 bullets (movement, reactions, patterns)
🔵 SYSTEM IMPACT — Max 4 bullets (roads, transit, power, buildings)
⏱️ TIMING — First signal / Trend / Window
⚠️ CONTEXT — Max 2 lines (only if critical)

8. DUPLICATION FILTERS
Remove repeated nouns · Merge overlapping facts · Single-bullet compression · Eliminate non-essential adjectives

9. HARD FILTERS — Exclude
• Events outside 24h recency window (unless measurable ongoing effect)
• Irrelevant locations, syndicated filler, historical background
• Any incident confirmed fully resolved with no ongoing impact

10. SOCIAL SIGNAL INTELLIGENCE
Platforms: X (Twitter), Reddit, Nextdoor, Facebook public posts, Citizen App, Local news reply threads
Extract ONLY: Repeated observations (≥2 independent) · Physical descriptions · Behavioral observations · Geotagged posts
Reject: Opinions · Speculation · Single-user claims · Rumors outside 24h window
Boost confidence if ≥3 independent corroborated posts within 24h.`;

/* =============================================================
   CRITICAL SAFETY DEFAULT CONTENT
   ============================================================= */
const SAFETY_DEFAULT = `You now own a J.P. Sutton Safety Reserve Guide. The digital tools you're about to unlock are yours to keep — but please read this first.

BULLET|🤖|The AI Real Time Situational Analysis Is Not an Emergency Service.|It gives you general, AI-generated information. It does not provide real-time alerts, instructions, or emergency guidance. Always follow official authorities.

BULLET|⚡|AI Outputs Can Be Wrong.|The AI is a third-party system we don't control. Information may be incomplete, outdated, or inaccurate.

BULLET|🔋|Your Kit Needs Maintenance.|Inspect it periodically, charge the batteries, and replace anything expired. It only works if you keep it ready.

BULLET|📖|Content Is Information, Not Instructions.|Location Scenarios, Disruption Insights, and all other content are for general awareness only. In any real situation, rely on your own judgment and official guidance — not this material.`;

/* =============================================================
   WELCOME DEFAULT CONTENT
   ============================================================= */
const WELCOME_DEFAULT = `<div style="text-align:center;font-size:48px;margin-bottom:16px">🛡️</div>
<div style="font-family:'DM Serif Display',serif;font-size:26px;color:#2C4A6E;text-align:center;margin-bottom:14px;line-height:1.3">Welcome to your Safety Reserve</div>
<div style="font-size:14px;color:#5A6270;text-align:center;line-height:1.7">This app provides access to your Safety Reserve&#x2019;s digital materials, which can be customized, downloaded, and/or printed for use with your Urban Resilience Guide.</div>`;

/* =============================================================
   DISRUPTION INSIGHTS DEFAULT CONTENT
   ============================================================= */
const DISRUPTION_INSIGHTS_DEFAULT = `TITLE|Disruption Insights (Selected Examples)
INTRO|Understanding how past disruptions unfolded helps you think ahead. Examples below are illustrative and not comprehensive. Every situation is different.

CARD|⚡|Power outage|Electrical
BULLET|Fridge holds about 4 hours once the door stays closed. Freezer buys 24\u201348. The clock starts immediately.
BULLET|After dark, navigation, communication, and safety all run on one device. People who cut screen brightness early stayed connected through the night. People who didn\u2019t ran out of phone before they ran out of emergency.
BULLET|When networks congest, voice calls fail first. SMS pushes through when calls won\u2019t.
BULLET|Candle-related fires spike during blackouts. Battery-powered light is the practical choice in a dense urban space.
BULLET|People who had a named backup location \u2014 a friend\u2019s place, a hotel nearby \u2014 used it when outages stretched past a day. People who hadn\u2019t decided yet scrambled when it mattered.

CARD|\u25ce|Water supply interruption|Infrastructure
SUBHEAD|First 24 hours \u2014
BULLET|Tap water quality uncertain: the Grayl Geopress in your kit handles it. Press, filter, drink. That\u2019s what it\u2019s there for.
BULLET|Boil advisories follow supply disruptions quickly \u2014 sometimes within hours. Boiled water, once cooled, is safe for drinking and cooking.
SUBHEAD|If it\u2019s running longer \u2014
BULLET|One gallon per person per day covers drinking and basic hygiene. In summer heat, closer to two.
BULLET|Cities open distribution points. Your city\u2019s official social media \u2014 not a news outlet, not a neighbor\u2019s post \u2014 is the fastest way to find them.

CARD|\u2691|Civil unrest|Public safety
BULLET|People who stayed off the streets at peak \u2014 inside, or moving through quiet routes \u2014 consistently had fewer direct encounters than those near a focal point when things escalated.
BULLET|A crowd gathering around a visible tension point is a signal, not background noise. The people who got caught were almost always already nearby.
BULLET|When phones go down, people who had a specific backup address found each other. \u201cMeet near the coffee shop\u201d failed. A corner and a street name worked.
BULLET|During active disturbances, ambulances are heavily committed elsewhere. Getting yourself to care is faster than waiting for it to come to you.
CALLOUT|Consistently observed:|People in buildings or low-visibility positions reported far fewer direct encounters than those caught in crowded spaces at peak activity \u2014 across cities, across event types.

DIVIDER|Less predictable.

CARD|\u2248|Airborne hazards|Chemical / radiological
BULLET|Your heating and cooling system actively pulls outdoor air inside. It doesn\u2019t screen for what\u2019s in it. People who shut it off first and sealed windows contained their exposure fastest.
BULLET|Airborne hazards move with the wind. Moving sideways to the wind \u2014 not straight back from the source \u2014 exits the plume faster.
BULLET|Every wall, floor, and interior room between you and the outside reduces what reaches you. Further inside is always better.
BULLET|An N95 with a tight seal blocks roughly 95% of airborne particles. A loose fit or surgical mask delivers significantly less. How it fits matters more than the mask itself.

CARD|\u2622|Nuclear explosion scenarios|High-impact
BULLET|Distance from a detonation doesn\u2019t just help \u2014 it helps exponentially. Twice as far away is not twice as safe. It\u2019s dramatically, disproportionately safer.
BULLET|Concrete, brick, and below-ground spaces absorb radiation. A basement in a solid building is not just \u201cmore protected\u201d \u2014 it\u2019s a categorically different environment from being above ground or near glass.
BULLET|The first 24 hours carry the highest radiation intensity. People who stayed sheltered through that window had dramatically better outcomes than those who moved too soon.
BULLET|Every major network goes down. Battery-powered and hand-crank radios stayed on. That\u2019s what\u2019s in your kit.

FOOTER|All content reflects observed patterns from official planning documents, public safety materials, and documented events. Nothing here constitutes instructions, recommendations, emergency services, or professional advice of any kind. In any active situation, your local emergency management agency, public health announcements, and weather services are your primary real-time sources.`;

/* =============================================================
   DATA LAYER
   ============================================================= */
const VALID_STATES=new Set(["AL","AK","AZ","AR","CA","CO","CT","DE","FL","GA","HI","ID","IL","IN","IA","KS","KY","LA","ME","MD","MA","MI","MN","MS","MO","MT","NE","NV","NH","NJ","NM","NY","NC","ND","OH","OK","OR","PA","RI","SC","SD","TN","TX","UT","VT","VA","WA","WV","WI","WY","DC","PR","VI","GU","AS","MP"]);
const LOC_CFG={H:{label:"Home",icon:"🏠",color:"#4A6FA5",light:"#EAF0F9"},W:{label:"Work",icon:"🏢",color:"#7264A8",light:"#EAE8F5"},SC:{label:"School",icon:"🎓",color:"#7264A8",light:"#EAE8F5"},"FR-N":{label:"Nearby Friend",icon:"👫",color:"#4A8570",light:"#D8EDE6"},FR:{label:"Friend/Partner",icon:"👫",color:"#4A8570",light:"#D8EDE6"},FM:{label:"Family",icon:"🏡",color:"#3D7872",light:"#D0E8E5"},RP:{label:"Roommate's Parents",icon:"🏘️",color:"#3D7872",light:"#D0E8E5"},P:{label:"Public Building",icon:"🏛️",color:"#9B7035",light:"#F5E9D5"},PS:{label:"Public Shelter",icon:"⛺",color:"#9B7035",light:"#F5E9D5"}};
const CAT_ICONS={Resources:"📦",Safety:"🛡️",Support:"🤝","Time & Distance":"⏱️"};
let POS=[
  {id:"fw+",cat:"Resources",text:"May have food & water for 3+ days",na:["P","PS"],q:"food_water",trig:a=>["3-5 days","1 week+"].includes(a)},
  {id:"pwr+",cat:"Resources",text:"Possible alternative power supply",na:[],q:"backup_power",trig:a=>a==="Generator / solar"},
  {id:"es+",cat:"Resources",text:"Possible emergency supplies on hand",na:["P","PS"],q:"emergency_supplies",trig:a=>a==="Yes"},
  {id:"is+",cat:"Safety",text:"Possible interior shelter area",na:[],q:"interior_shelter",trig:a=>a==="Basement / interior room"},
  {id:"ep+",cat:"Safety",text:"Has emergency procedures or drills",na:["H","FR-N","FR","FM","RP"],q:"emergency_procedures",trig:a=>a==="Yes"},
  {id:"cm+",cat:"Support",text:"Could be comfortable",na:["W","SC","P","PS"],q:null,def:()=>true},
  {id:"st+",cat:"Support",text:"Staff likely present",na:["H","FR","FR-N","RP"],q:"building_staffed",trig:a=>a==="Yes",def:l=>["W","SC","PS"].includes(l.type)},
  {id:"ls+",cat:"Support",text:"Possible longer stay",na:["W","SC","P","PS"],q:"longer_stay",trig:a=>a==="Yes"},
  {id:"di+",cat:"Time & Distance",text:"Possible distance from localized event",na:[],q:null,def:l=>l.travelMinutes>=60},
];
let NEG=[
  {id:"lp-",cat:"Safety",text:"May have limited protective features",na:["SC","P","PS"],q:"interior_shelter",trig:a=>["No","Not sure"].includes(a)},
  {id:"fw-",cat:"Resources",text:"Unknown or limited food & water",na:["P","PS"],q:"food_water",trig:a=>["Less than 1 day","1-2 days","Unknown"].includes(a)},
  {id:"pu-",cat:"Resources",text:"Backup power availability unknown",na:["P","PS"],q:"backup_power",trig:a=>["None","Not sure"].includes(a)},
  {id:"po-",cat:"Resources",text:"Prolonged outages can be disruptive",na:["P","PS"],q:"backup_power",trig:a=>["None","Not sure"].includes(a)},
  {id:"ep-",cat:"Safety",text:"No confirmed emergency plan",na:["H","FR-N","FR","FM","RP"],q:"emergency_procedures",trig:a=>["No","Not sure"].includes(a)},
  {id:"ev-",cat:"Safety",text:"Possible evacuation zone",na:[],q:null,def:()=>true},
  {id:"bc-",cat:"Safety",text:"May be closed or inaccessible",na:["H","FR-N","FR","FM","RP"],q:null,def:l=>["W","SC","P","PS","RP"].includes(l.type)},
  {id:"bld-",cat:"Safety",text:"Structural resilience unknown",na:[],q:null,def:()=>true},
  {id:"dt-",cat:"Safety",text:"Potential for disease transmission",na:["H","FR-N","FR","FM","RP"],q:null,def:l=>["W","SC","P","PS"].includes(l.type)},
  {id:"cr-",cat:"Support",text:"Possible crowding",na:["H","W","FR-N","FR","FM","RP"],q:null,def:l=>["P","PS","SC"].includes(l.type)},
  {id:"cp-",cat:"Support",text:"Possible capacity limitations",na:["H","W","FR-N","FR","FM","RP"],q:null,def:l=>["SC","P","PS"].includes(l.type)},
  {id:"cv-",cat:"Support",text:"Confirm they know you may come",na:["H","W","SC","P","PS"],q:null,def:l=>["FR-N","FR","FM","RP"].includes(l.type)},
  {id:"ar-",cat:"Support",text:"Possible access restrictions",na:["H","FR-N","FR","P","PS"],q:null,def:l=>["W","SC","RP"].includes(l.type)},
  {id:"tt-",cat:"Time & Distance",text:"Travel time may be slow or unpredictable",na:["H","FR-N","P","PS"],q:null,def:l=>l.travelMinutes>=60},
  {id:"fu-",cat:"Time & Distance",text:"Check fuel or battery charge before traveling",na:["H","FR-N","P","PS"],q:"fuel",global:true,trig:(a,l)=>l.travelMinutes>=60&&["Less than half","Not sure"].includes(a)},
  {id:"tr-",cat:"Time & Distance",text:"Limited transportation options",na:["H"],q:"transportation",global:true,trig:a=>["Car sometimes available","No car — bike or transit only"].includes(a)},
];
let LOC_QS=[
  {key:"interior_shelter",label:"Does this location have an interior protected area?",hint:"e.g. basement or interior room",opts:["Basement / interior room","No","Not sure"],skip:[]},
  {key:"food_water",label:"How much food & water is likely available?",opts:["Less than 1 day","1-2 days","3-5 days","1 week+","Unknown"],skip:["P","PS"]},
  {key:"backup_power",label:"Is backup power available here?",hint:"Other than a personal power bank",opts:["Generator / solar","None","Not sure"],skip:[]},
  {key:"emergency_supplies",label:"Are emergency supplies likely here?",hint:"Radio, first aid kit, etc.",opts:["Yes","No","Not sure"],skip:["P","PS"]},
  {key:"emergency_procedures",label:"Does this location have emergency procedures or drills?",opts:["Yes","No","Not sure"],skip:["H","FR-N","FR","FM","RP"]},
  {key:"longer_stay",label:"If needed, could you stay there for a week or longer?",opts:["Yes","Maybe","No"],skip:["W","SC","P","PS"]},
  {key:"building_staffed",label:"Is this building normally staffed?",opts:["Yes","Not sure"],skip:["H","FR","FR-N","RP","FM","P","PS"]},
];

/* =============================================================
   QUESTION LOGIC — Spreadsheet-driven engine (v19)
   Upload your Attribute_mapping.xlsx via Admin → Question Logic
   to override the built-in POS / NEG / LOC_QS arrays at runtime.
   ============================================================= */

function buildAttrFromDescriptor(d) {
  const base = {id:d.id, cat:d.cat, text:d.text, na:d.na||[]};
  const t = d.trigger||{};
  switch(t.type){
    case 'answer':
      base.q = t.qKey;
      base.trig = a => (t.answers||[]).includes(a);
      break;
    case 'global_answer':
      base.q = t.qKey; base.global = true;
      base.trig = a => (t.answers||[]).some(ans => a && a.includes(ans));
      break;
    case 'global_fuel':
      base.q = 'fuel'; base.global = true;
      base.trig = (a,l) => l.travelMinutes>=60 && ['Less than half','Not sure'].includes(a);
      break;
    case 'default_types':
      base.q = null;
      base.def = l => (t.types||[]).includes(l.type);
      break;
    case 'default_all':
      base.q = null; base.def = () => true;
      break;
    case 'default_travel_min':
      base.q = null; base.def = l => l.travelMinutes >= (t.min||60);
      break;
    default:
      base.q = null; break;
  }
  return base;
}

function deriveQuestionKey(qText) {
  if(!qText||qText==='(See Location Choice)'||qText.trim()==='') return null;
  const q = qText.toLowerCase();
  if(q.includes('food')||q.includes('water')) return 'food_water';
  if(q.includes('backup power')) return 'backup_power';
  if(q.includes('emergency supplies')) return 'emergency_supplies';
  if(q.includes('interior')||q.includes('protected area')) return 'interior_shelter';
  if(q.includes('emergency procedures')||q.includes('drills')) return 'emergency_procedures';
  if(q.includes('stay')||q.includes('week or longer')) return 'longer_stay';
  if(q.includes('staffed')) return 'building_staffed';
  if(q.includes('transportan')||q.includes('transport')) return 'transportation';
  if(q.includes('fuel')||q.includes('battery charge')) return 'fuel';
  return null;
}

function parseOptions(str) {
  if(!str||str==='NaN') return [];
  return str.split('\n').map(s=>s.replace(/^[•□\t\s]+/,'').trim()).filter(Boolean);
}

function parseNATypes(str) {
  if(!str||str==='NaN') return [];
  return str.split(',').map(s=>s.trim()).filter(s=>s&&s!=='NaN');
}

function parseTriggerDescriptor(triggerStr, qKey) {
  const t = (triggerStr||'').trim();
  if(!t||t==='NaN') return {type:'none'};
  if(t.includes('Defaults to Yes for all')) return {type:'default_all'};
  if(t.includes('travel time greater than or equal to 1 hour')) return {type:'default_travel_min',min:60};
  if(t.startsWith('Depends on')) return {type:'global_fuel'};
  if(t.startsWith('Defaults to Yes for')){
    const typesStr=t.replace('Defaults to Yes for','').trim();
    const types=typesStr.split(',').map(s=>s.trim()).filter(s=>s&&s!=='NaN');
    return {type:'default_types',types};
  }
  const answers = t.split(',').map(s=>s.trim()).filter(s=>s&&s!=='NaN');
  if(qKey==='transportation') return {type:'global_answer',qKey,answers};
  return {type:'answer',qKey,answers};
}

function parseXlsxToLogic(workbook) {
  const sheetName = workbook.SheetNames[0];
  const sheet = workbook.Sheets[sheetName];
  const rows = XLSX.utils.sheet_to_json(sheet, {header:1, defval:''});
  const posData=[], negData=[];
  const questionsMap={};
  let idCounter=0;
  for(let ri=1; ri<rows.length; ri++){
    const row = rows[ri];
    const category = String(row[0]||'').trim();
    const attrName  = String(row[1]||'').trim();
    const cogCat    = String(row[2]||'').trim();
    const naStr     = String(row[3]||'').trim();
    const questionT = String(row[4]||'').trim();
    const responseS = String(row[5]||'').trim();
    const triggerS  = String(row[7]||'').trim();
    const cardText  = String(row[8]||'').trim();
    if(!cogCat||cogCat==='NaN'||!attrName||attrName==='NaN') continue;
    const na  = parseNATypes(naStr);
    const qKey= deriveQuestionKey(questionT);
    const trig= parseTriggerDescriptor(triggerS, qKey);
    const displayText = cardText&&cardText!=='NaN' ? cardText : attrName;
    if(qKey && !questionsMap[qKey] && questionT && questionT!=='(See Location Choice)'){
      const opts = parseOptions(responseS);
      if(opts.length>0) questionsMap[qKey]={key:qKey, label:questionT, hint:'', opts, skip:na};
    }
    const isPos = category.toLowerCase().includes('may have')||category.toLowerCase().includes('what you may');
    const id = (isPos?'pos_':'neg_')+idCounter++;
    const descriptor = {id, cat:cogCat, text:displayText, na,
      trigger:{...trig, qKey: trig.qKey||qKey}};
    if(isPos) posData.push(descriptor);
    else if(category.toLowerCase().includes('think about')) negData.push(descriptor);
  }
  return {pos:posData, neg:negData, questions:Object.values(questionsMap),
    uploadedAt:new Date().toISOString(), sheetName};
}

function applyStoredQuestionLogic(){
  try{
    const stored = loadJson(SK.questionLogic, null);
    if(!stored||!stored.pos||!stored.neg||!stored.questions) return;
    const newPOS = stored.pos.map(d=>buildAttrFromDescriptor(d));
    const newNEG = stored.neg.map(d=>buildAttrFromDescriptor(d));
    const newLocQs = stored.questions.filter(q=>q.key!=='transportation'&&q.key!=='fuel').map(q=>({
      key:q.key, label:q.label, hint:q.hint||'', opts:q.opts, skip:q.skip||[]
    }));
    if(newPOS.length&&newNEG.length){POS.length=0;POS.push(...newPOS);}
    if(newLocQs.length){LOC_QS.length=0;LOC_QS.push(...newLocQs);}
  }catch(e){console.warn('Question logic load failed:',e);}
}

const MAX_LOCS=6,MAX_PERSONAL=5;
const DEFAULT_ESSENTIALS=["Phone","Phone Charger","Wallet","Extra Cash","Identification/Passport","Water","Medications","Safety Reserve Backpack","Laptop","Laptop Charger","House Keys","Car Keys","Warm Clothes","Rain Poncho","Walking Shoes","Gloves","Hat","Sleeping Bag","Toothbrush","Toilet Paper","Additional Food"];

/* =============================================================
   HELPERS
   ============================================================= */
function fmtTime(m){if(!m||m===0)return null;if(m<60)return m+" min";const h=m/60;if(h===Math.floor(h))return h+" hr"+(h>1?"s":"");return h.toFixed(1)+" hrs";}
function isSusSmall(v){const n=parseInt(v);return!isNaN(n)&&n>=1&&n<=5;}
function validatePhone(v){if(!v||!v.trim())return null;const d=v.replace(/\D/g,'');if(d.length===10||(d.length===11&&d[0]==='1'))return null;return'Enter a valid 10-digit phone number';}
function esc(s){if(s===null||s===undefined)return'';return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');}
function computeAttrs(loc,la,ga){la=la||{};const chk=attr=>{if(attr.na.includes(loc.type))return false;if(attr.q){if(attr.global){const a=ga[attr.q];return a!=null?attr.trig(a,loc):false;}const a=la[attr.q];if(a!=null)return attr.trig(a);return attr.def?attr.def(loc):false;}return attr.def?attr.def(loc):false;};return{pos:POS.filter(chk),neg:NEG.filter(chk)};}
function groupByCat(attrs){const cats=["Resources","Safety","Support","Time & Distance"],out={};for(const c of cats){const it=attrs.filter(a=>a.cat===c);if(it.length)out[c]=it;}return out;}
function getOrderedLocs(locs){const pri=["H","W","SC"];const head=pri.map(t=>locs.find(l=>l.type===t)).filter(Boolean);const tail=locs.filter(l=>!pri.includes(l.type));return[...head,...tail].slice(0,6);}
function hasAttrEffect(qKey,lType){return[...POS,...NEG].some(a=>a.q===qKey&&!a.na.includes(lType)&&a.trig);}
function buildQList(locs){const qs=[];qs.push({type:"global",key:"transportation",label:"What transportation options do you usually have available?",opts:["My own car","Shared or borrowed car","Car sometimes available","No car — bike or transit only"]});for(const qd of LOC_QS){const ap=locs.filter(l=>!qd.skip.includes(l.type)&&hasAttrEffect(qd.key,l.type));if(!ap.length)continue;if(ap.length===1){const loc=ap[0];qs.push({type:"loc",locId:loc.id,locLabel:loc.displayLabel,locType:loc.type,...qd});}else qs.push({type:"collapsed",key:qd.key,label:qd.label,hint:qd.hint,opts:qd.opts,locs:ap});}if(locs.some(l=>l.travelMinutes>=60)){qs.push({type:"global",key:"fuel",label:"If you needed to drive a long distance, how much fuel or battery charge do you usually have?",opts:["Full or nearly full","Half","Less than half","Not sure"]});}return qs;}

/* =============================================================
   STORAGE
   ============================================================= */
function saveSession(){store(SK.session,{activationCode:S.activationCode,userFullName:S.userFullName,userEmail:S.userEmail,userName:S.userName,legalAccepted:S.legalAccepted,appFlow:S.appFlow,savedAt:new Date().toISOString()});}
function saveMainState(){
  const snap={phase:S.phase,srStep:S.srStep,userName:S.userName,wsChoice:S.wsChoice,workGoesIn:S.workGoesIn,workName:S.workName,workMins:S.workMins,workMinsConf:S.workMinsConf,schoolGoesIn:S.schoolGoesIn,schoolName:S.schoolName,schoolMins:S.schoolMins,schoolMinsConf:S.schoolMinsConf,locations:S.locations,friendRel:S.friendRel,friendName:S.friendName,friendMins:S.friendMins,friendMinsConf:S.friendMinsConf,friendCity:S.friendCity,friendState:S.friendState,pubType:S.pubType,buildingType:S.buildingType,pubMins:S.pubMins,pubMinsConf:S.pubMinsConf,qIndex:S.qIndex,locAns:S.locAns,globalAns:S.globalAns,commContacts:S.commContacts,commGroup:S.commGroup,selectedEssentials:[...S.selectedEssentials],customEssentials:S.customEssentials,fromFinal:S.fromFinal,savedAt:new Date().toISOString()};
  store(SK.mainState,snap);
}
function storeRegistration(){const records=loadJson(SK.registrations,[]);records.push({activationCode:S.activationCode,fullName:S.userFullName,email:S.userEmail,registeredAt:new Date().toISOString()});store(SK.registrations,records);}
async function storeLegalAcceptance(){
  let ip='Unavailable';
  try{const r=await fetch('https://api.ipify.org?format=json');const d=await r.json();ip=d.ip||'Unavailable';}catch(e){}
  S.userIP=ip;
  const records=loadJson(SK.legalRecords,[]);
  records.push({activationCode:S.activationCode,fullName:S.userFullName,email:S.userEmail,ip,acceptedAt:new Date().toISOString()});
  store(SK.legalRecords,records);
  const _codes=loadCodes();
  const _ci=_codes.findIndex(r=>r.code===S.activationCode.trim().toUpperCase());
  if(_ci>=0){_codes[_ci].activations=_codes[_ci].activations||[];_codes[_ci].activations.push({activatedAt:new Date().toISOString(),name:S.userFullName,email:S.userEmail,ip});saveCodes(_codes);}
}
function getSavedSession(){return loadJson(SK.session,null);}
function loadSavedMainState(){
  try{
    const d=loadJson(SK.mainState,null);
    if(!d)return;
    Object.assign(S,d);
    S.selectedEssentials=new Set(d.selectedEssentials||[]);
    S.errors={};S.collAns={};S.customInput='';
  }catch(e){}
}

/* =============================================================
   STATE
   ============================================================= */
const S={
  // Screen
  appFlow:'activation', // 'resume'|'activation'|'confirm'|'safety'|'welcomePage'|'main'
  appPaused:false,
  showAdmin:false, adminAuthed:false, adminTab:'welcome',
  adminLoginErr:'', adminSaveMsg:'', recoveryErr:'',
  // Pre-flow
  activationCode:'',activationErr:'',
  userFullName:'',userEmail:'',userIP:'',
  legalAccepted:false,legalErr:'',
  resumeCodeInput:'',resumeCodeErr:'',  // FIX 4: code required to resume
  // Main app
  phase:1,srStep:'welcome',userName:'',
  wsChoice:null,workGoesIn:null,workName:'',workMins:'',workMinsConf:false,
  schoolGoesIn:null,schoolName:'',schoolMins:'',schoolMinsConf:false,
  locations:[{id:'H',type:'H',displayLabel:'Home',travelMinutes:0}],
  friendRel:'friend',friendName:'',friendMins:'',friendMinsConf:false,
  friendCity:'',friendState:'',
  pubType:'building',buildingType:'Community center',pubMins:'',pubMinsConf:false,
  qIndex:0,locAns:{},globalAns:{},collAns:{},errors:{},
  commContacts:{primary:{name:'',phone:''},outOfTown:{name:'',phone:''},localFriend:{name:'',phone:''}},
  commGroup:'',commPhoneErrs:{},
  selectedEssentials:new Set(),customEssentials:[],customInput:'',
  fromFinal:false,
  finalStep:'ai',   // 'ai' | 'docs'
  aiDownloaded:false,
  newCodeStr:'',newOrderNumber:'',newCodeAdminText:'',newCodeImageData:null,newCodeQrUrl:'',codeListFilter:'all',adminCardTplMsg:'',
  showCompletion:false,
  showDisruptionView:false,
  showAIView:false,
  recordsSearch:'',
  docsActioned:false,docsActionType:'',  // 'print'|'download'|'both'
};

/* =============================================================
   HELPER UTILITIES — Password, CSV, Recovery Key
   ============================================================= */
function isStrongPassword(pw){
  if(pw.length<12)return'Password must be at least 12 characters.';
  if(!/[A-Z]/.test(pw))return'Must include an uppercase letter.';
  if(!/[a-z]/.test(pw))return'Must include a lowercase letter.';
  if(!/[0-9]/.test(pw))return'Must include a number.';
  if(!/[^A-Za-z0-9]/.test(pw))return'Must include a symbol (e.g. @, #, !).';
  return null;
}
function generateRecoveryKey(){
  const c='ABCDEFGHJKLMNPQRSTUVWXYZ23456789';
  const seg=()=>{let s='';for(let i=0;i<5;i++)s+=c[Math.floor(Math.random()*c.length)];return s;};
  return'SR-'+seg()+'-'+seg()+'-'+seg();
}
function getRecoveryKey(){
  let k=load(SK.recoveryKey,'');
  if(!k){k=generateRecoveryKey();store(SK.recoveryKey,k);}
  return k;
}
function downloadRecordsCSV(records,filename){
  if(!records||!records.length)return;
  const headers=Object.keys(records[0]);
  const rows=[headers.map(h=>JSON.stringify(h)).join(','),...records.map(r=>headers.map(h=>JSON.stringify(r[h]!=null?r[h]:'')).join(','))];
  const blob=new Blob([rows.join('\n')],{type:'text/csv'});
  const url=URL.createObjectURL(blob);
  const a=document.createElement('a');a.href=url;a.download=filename;a.click();
  setTimeout(()=>URL.revokeObjectURL(url),2000);
}
function getDisruptionHtml(){return load(SK.disruptionInsights,DISRUPTION_INSIGHTS_DEFAULT);}
function getDisruptionRawHTML(){
  /* If admin uploaded an HTML file, it's stored as '__HTML__:...' */
  const v=load(SK.disruptionInsights,'');
  return v.startsWith('__HTML__:')?v.slice(9):null;
}

/* =============================================================
   INIT — Check for saved session
   ============================================================= */
function initApp(){
  // Check for admin access via #admin hash (case-insensitive) OR ?admin=1 URL param
  const _iap=new URLSearchParams(window.location.search);
  if(window.location.hash.toLowerCase()==='#admin'||_iap.get('admin')==='1'){S.showAdmin=true;}
  try{const _p=new URLSearchParams(window.location.search),_c=_p.get('code');if(_c)S.activationCode=_c.trim().toUpperCase();}catch(e){}

  const saved=getSavedSession();
  if(saved&&saved.legalAccepted){
    // There is a resumable session
    S.activationCode=saved.activationCode||'';
    S.userFullName=saved.userFullName||'';
    S.userEmail=saved.userEmail||'';
    S.userName=saved.userName||'';
    S.legalAccepted=true;
    S.appFlow='resume'; // Show resume screen
  } else if(saved&&!saved.legalAccepted&&saved.appFlow){
    // Partially through pre-flow — restart activation
    S.appFlow='activation';
  }
  applyStoredQuestionLogic();
  render();
}

/* =============================================================
   PROGRESS
   ============================================================= */
function getProgress(){
  const srMap={welcome:0,work_school:15,friends:35,public_loc:55,review:70,questionnaire:80,sr_output:100};
  let p1=srMap[S.srStep]||0;
  if(S.srStep==='questionnaire'){const allQs=buildQList(getOrderedLocs(S.locations));p1=80+(allQs.length>0?(S.qIndex/allQs.length)*20:0);}
  const p2=S.phase<2?0:(S.phase===2?50:100);
  const p3=S.phase<3?0:(S.phase===3?50:100);
  return{p1:Math.round(p1),p2,p3};
}

/* =============================================================
   RENDER
   ============================================================= */
function render(){
  // FIX 1: Save focused element id & cursor position before DOM rebuild so typing isn't interrupted
  const _fid=document.activeElement?.id;
  const _fs=document.activeElement?.selectionStart;
  const _fe=document.activeElement?.selectionEnd;
  function restoreFocus(){if(_fid){const el=document.getElementById(_fid);if(el&&typeof el.focus==='function'){el.focus();try{el.setSelectionRange(_fs,_fe);}catch(e){}}}}

  const app=document.getElementById('app');

  // Admin overlay renders on top of everything
  if(S.showAdmin){
    app.innerHTML=(S.appFlow==='main'?renderMainShell():'')+'<div id="adminLayer">'+renderAdmin()+'</div>';
    attachHandlers();restoreFocus();
    return;
  }

  if(S.showDisruptionView){app.innerHTML=renderDisruptionView();attachHandlers();restoreFocus();return;}
  if(S.showAIView){app.innerHTML=renderAIView();attachHandlers();restoreFocus();return;}
  if(S.appPaused){app.innerHTML=renderPaused();attachHandlers();restoreFocus();return;}
  if(S.appFlow==='resume'){app.innerHTML=renderResumeScreen();attachHandlers();restoreFocus();return;}
  if(S.appFlow!=='main'){app.innerHTML=renderPreFlow();attachHandlers();restoreFocus();return;}

  if(S.phase===1&&S.srStep==='sr_output'){
    app.innerHTML=renderStopBar()+renderSROutput();
  } else {
    const prog=getProgress();
    let body='';
    if(S.phase===1)body=renderSR();
    else if(S.phase===2)body=renderCommPlan();
    else if(S.phase===3)body=renderEssentials();
    else body=renderFinal();
    app.innerHTML=renderStopBar()+renderMasterProgress(prog)+`<div class="fade-in">${body}</div>`;
  }
  saveMainState();
  attachHandlers();
  restoreFocus();
}

function renderMainShell(){
  return`<div id="mainBehind" style="opacity:.3;pointer-events:none;filter:blur(2px)">${renderStopBar()}<div style="height:200px"></div></div>`;
}

/* =============================================================
   DISRUPTION INSIGHTS INLINE VIEW
   ============================================================= */
function renderDisruptionView(){
  return`<div class="ref-wrap"><div style="max-width:720px;margin:0 auto;padding-bottom:30px">
    <div class="no-print" style="margin:14px 0 10px;display:flex;gap:8px;align-items:center;justify-content:flex-end">
      <button class="btn btn-outline btn-sm" id="btnDisruptionBack">Back to Summary →</button>
    </div>
    <div class="ref-card">
      ${brandBar('Disruption Insights')}
      <div style="padding:16px 20px">
        <div style="font-size:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:#8E95A3;margin-bottom:5px">Safety Reserve Urban Resilience Guide</div>
        <div style="font-family:'DM Serif Display',serif;font-size:20px;color:#2C3347;margin-bottom:4px">Disruption Insights (Selected Examples)</div>
        <div style="font-size:12px;color:#8E95A3;margin-bottom:14px">Representative examples of unusual events</div>
        <div>${buildDisruptionInsightsHTML()}</div>
      </div>
    </div>
  </div></div>`;
}

/* =============================================================
   AI QUERY INLINE VIEW
   ============================================================= */
function renderAIView(){
  const aiDate=getAIQueryDate();
  return`<div class="ref-wrap"><div style="max-width:720px;margin:0 auto;padding-bottom:30px">
    <div class="no-print" style="margin:14px 0 10px;display:flex;gap:8px;align-items:center">
      <button class="btn btn-outline btn-sm" id="btnAIViewBack">← Back to Summary</button>
    </div>
    <div class="ref-card">
      ${brandBar('AI Real Time Situational Analysis')}
      <div style="padding:16px 20px">
        <div style="font-size:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:#8E95A3;margin-bottom:5px">Safety Reserve Urban Resilience Guide</div>
        <div style="font-family:'DM Serif Display',serif;font-size:20px;color:#2C3347;margin-bottom:4px">AI Real Time Situational Analysis</div>
        <div style="font-size:11px;color:#8E95A3;margin-bottom:16px">Version: ${aiDate}</div>
        <div style="background:#FFF8ED;border:1.5px solid #E0C55A;border-radius:8px;padding:9px 13px;margin-bottom:16px;font-size:11px;color:#6A5100"><strong>⚠️ Note:</strong> This template is for informational use only. It is not an emergency service. Always follow official authorities.</div>
        <div style="line-height:1.7">${buildAIQueryHTML()}</div>
      </div>
    </div>
  </div></div>`;
}

/* =============================================================
   COMPLETION SCREEN
   ============================================================= */
function renderCompletion(){
  return`<div style="min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:32px 20px;text-align:center;background:linear-gradient(160deg,#f0f4ff 0%,#e8f5ee 100%)">
    <div style="font-size:64px;margin-bottom:16px;animation:fadeIn .5s ease">🛡️</div>
    <div style="font-family:'DM Serif Display',serif;font-size:32px;color:#2C4A6E;margin-bottom:10px;line-height:1.2">Safety Always.</div>
    <div style="font-size:15px;color:#5A6270;max-width:400px;line-height:1.7;margin-bottom:28px">Your documents are ready. Place them in your <strong>Urban Resilience Guide</strong> and keep them somewhere accessible.<br><br>You can return to this app anytime to update your plan.</div>
    <div style="background:white;border-radius:14px;padding:18px 24px;max-width:400px;width:100%;box-shadow:0 4px 20px rgba(44,51,71,.10);margin-bottom:22px;border:1.5px solid #D8EDE6">
      <div style="font-size:13px;font-weight:700;color:#1A5240;margin-bottom:8px">✓ What you've completed</div>
      <div style="font-size:12px;color:#5A6270;line-height:1.8;text-align:left">
        <div>📍 Location Scenarios — personalized to your inputs</div>
        <div>📋 Communication Plan — ready to fill or already filled</div>
        <div>🎒 Pre-Plan Essentials — your priority items selected</div>
        <div>🤖 AI Real Time Situational Analysis — included</div>
        <div>📊 Disruption Insights — included</div>
      </div>
    </div>
    <div style="display:flex;gap:10px;flex-wrap:wrap;justify-content:center">
      <button class="btn btn-primary" id="btnCompletionBack" style="background:#2C4A6E">← Back to Summary</button>
      <button class="btn btn-outline" id="btnCloseWindow" style="color:var(--text-mid)">✕ Close Window</button>
    </div>
    <div style="margin-top:20px;font-size:10px;color:#B0B8C8">Safety Reserve — Urban Resilience Guide · ${new Date().toLocaleDateString('en-US',{month:'long',year:'numeric'})}</div>
  </div>`;
}

/* =============================================================
   RESUME SCREEN
   ============================================================= */
function renderResumeScreen(){
  const saved=loadJson(SK.mainState,null);
  const savedAt=saved?.savedAt;
  let whenStr='';
  if(savedAt){
    const d=new Date(savedAt);
    whenStr=d.toLocaleDateString('en-US',{weekday:'short',month:'short',day:'numeric'})+' at '+d.toLocaleTimeString('en-US',{hour:'numeric',minute:'2-digit'});
  }
  const phaseLabel=['','Location Scenarios','Communication Plan','Pre-Plan Essentials','Final Summary'][saved?.phase||1]||'Location Scenarios';
  return`<div style="display:flex;flex-direction:column;align-items:center;min-height:100vh;padding:40px 14px;width:100%">
    <div class="resume-banner fade-in">
      <div class="resume-tag">💾 Session Found</div>
      <h2>Welcome back, ${esc(S.userFullName.split(' ')[0]||'there')}.</h2>
      <p>You have a saved session${whenStr?' — last saved '+whenStr:''}. You were in <strong>${phaseLabel}</strong>.</p>
      <div style="margin-bottom:16px">
        <label style="display:block;font-size:11px;font-weight:700;letter-spacing:.06em;text-transform:uppercase;color:rgba(255,255,255,.7);margin-bottom:7px">Enter your activation code to resume</label>
        <input class="finput" id="resumeCode" placeholder="e.g. XXXXXX" value="${esc(S.resumeCodeInput)}" autocomplete="off" autocapitalize="characters" style="font-size:17px;letter-spacing:.08em;font-weight:700;text-transform:uppercase;background:rgba(255,255,255,.12);border-color:rgba(255,255,255,.25);color:white">
        ${S.resumeCodeErr?`<div style="font-size:11px;color:#FCA5A5;margin-top:5px;font-weight:600">⚠ ${esc(S.resumeCodeErr)}</div>`:''}
      </div>
      <div class="resume-actions">
        <button class="btn-resume-main" id="btnResumeSession">▶ Resume Where I Left Off</button>
        <button class="btn-resume-fresh" id="btnStartFresh">Start Fresh</button>
      </div>
    </div>
    <div style="max-width:560px;width:100%;margin-top:18px">
      <div class="info-box fade-in" style="margin:0">
        <strong>📱 Tip:</strong> To resume this session anytime, simply open this app on the same device and browser. Your progress is stored locally and will be waiting for you.
      </div>
    </div>
  </div>`;
}

/* =============================================================
   PAUSED SCREEN
   ============================================================= */
function renderPaused(){
  return`<div class="paused-screen fade-in">
    <div class="paused-icon">⏸</div>
    <div class="card-title" style="text-align:center;margin-bottom:10px">App Paused</div>
    <div class="card-subtitle" style="text-align:center;max-width:340px">Your progress is saved automatically. You can close this browser and return anytime — your session will be waiting.<br><br><strong>To resume later:</strong> simply open this app again on this device.</div>
    <div style="margin-top:28px"><button class="btn-resume" id="btnResumeApp">▶ Resume Now</button></div>
    <div style="margin-top:16px;font-size:11px;color:var(--text-light);text-align:center">${esc(S.userName||S.userFullName||'')} · Kit: ${esc(S.activationCode)}</div>
  </div>`;
}

/* =============================================================
   PRE-FLOW
   ============================================================= */
function renderPreFlow(){
  const steps=[{key:'activation',label:'Activate'},{key:'confirm',label:'Details'},{key:'safety',label:'Safety &#38; Use'},{key:'welcomePage',label:'Welcome'}];
  const idx=steps.findIndex(s=>s.key===S.appFlow);
  let pills='';
  for(let i=0;i<steps.length;i++){
    const s=steps[i];
    const cls=i<idx?'done':i===idx?'active':'';
    const icon=i<idx?'✓':(i+1).toString();
    pills+=`<div class="pf-step"><div class="pf-dot ${cls}">${icon}</div><div class="pf-label ${cls}">${s.label}</div></div>`;
    if(i<steps.length-1)pills+=`<div class="pf-line ${i<idx?'done':''}"></div>`;
  }
  const bar=`<div class="preflow-bar"><div class="preflow-steps">${pills}</div></div>`;
  let body='';
  if(S.appFlow==='activation')body=renderActivation();
  else if(S.appFlow==='confirm')body=renderConfirmDetails();
  else if(S.appFlow==='safety')body=renderCriticalSafety();
  else if(S.appFlow==='welcomePage')body=renderWelcomePage();
  return bar+`<div class="fade-in">${body}</div>`;
}

function renderActivation(){
  return`<div class="card">
    <div class="shield">🛡️</div>
    <div class="card-title">Activate Your Digital Materials</div>
    <div class="card-subtitle">Enter the activation code found inside your Safety Reserve Guide to unlock your digital materials.</div>
    <div class="fgroup">
      <label class="flabel" for="activationCode">Activation Code</label>
      <input class="finput" id="activationCode" placeholder="e.g. XXXXXX" value="${esc(S.activationCode)}" autocomplete="off" autocapitalize="characters" style="font-size:20px;letter-spacing:.08em;font-weight:700;text-transform:uppercase">
      ${S.activationErr?`<div class="err">${esc(S.activationErr)}</div>`:''}
    </div>
    <div class="btn-row">
      <button class="btn btn-primary" id="btnActivateNext" ${!S.activationCode.trim()?'disabled':''}>Continue →</button>
    </div>
  </div>`;
}

function renderConfirmDetails(){
  return`<div class="card">
    <div style="font-size:30px;margin-bottom:13px">👤</div>
    <div class="card-title">Confirm Your Details</div>
    <div class="fgroup" style="margin-top:8px">
      <label class="flabel" for="regFullName">Full Name</label>
      <input class="finput" id="regFullName" placeholder="e.g. Jordan Smith" value="${esc(S.userFullName)}" autocomplete="name">
      ${S.errors&&S.errors.fullName?`<div class="err">${esc(S.errors.fullName)}</div>`:''}
    </div>
    <div class="fgroup">
      <label class="flabel" for="regEmail">Email Address</label>
      <input class="finput" id="regEmail" type="email" placeholder="e.g. jordan@example.com" value="${esc(S.userEmail)}" autocomplete="email">
      ${S.errors&&S.errors.email?`<div class="err">${esc(S.errors.email)}</div>`:''}
    </div>
    <div class="btn-row">
      <button class="btn btn-outline" id="btnConfirmBack">← Back</button>
      <button class="btn btn-primary" id="btnConfirmNext">Continue →</button>
    </div>
  </div>`;
}

function renderCriticalSafety(){
  const safetyRaw=load(SK.safetyText,SAFETY_DEFAULT);
  const lines=safetyRaw.split('\n');
  const intro=lines[0];
  const bullets=lines.filter(l=>l.startsWith('BULLET|'));
  const bulletsHtml=bullets.map(b=>{
    const parts=b.split('|');
    const icon=parts[1]||'•';
    const title=parts[2]||'';
    const body=(parts[3]||'');
    return`<div class="legal-bullet"><div class="legal-bullet-icon">${icon}</div><div style="padding:10px 14px 10px 0"><strong>${esc(title)}</strong> <span>${esc(body)}</span></div></div>`;
  }).join('');
  return`<div class="card">
    <div style="font-size:30px;margin-bottom:13px">⚠️</div>
    <div class="card-title">Critical Safety &amp; Use Summary</div>
    <div class="card-subtitle">${esc(intro)}</div>
    <div style="border:1.5px solid var(--border);border-radius:12px;overflow:hidden;margin-bottom:18px">${bulletsHtml}</div>
    <div style="background:#F7F9FC;border:1.5px solid var(--border);border-radius:10px;padding:14px 16px;margin-bottom:16px;font-size:12px;color:var(--text);line-height:1.75">
      By activating this product, I confirm I am an authorized user of this Safety Reserve Guide and agree that all content — including Location Scenarios and Disruption Insights — is general information only, not instructions, guidance, or advice. I will use my own judgment and defer to official authorities in any real situation. I agree to the J.P. Sutton <a href="#" onclick="openTosOverlay(event)" style="color:var(--blue-dark);font-weight:700;text-decoration:underline">Terms of Service</a>.
    </div>
    <label style="display:block;cursor:pointer">
      <div class="legal-check-row ${S.legalAccepted?'accepted':''}" id="legalCheckRow">
        <div class="legal-checkbox">${S.legalAccepted?'✓':''}</div>
        <div class="legal-check-text">I have read and agree to the above.</div>
      </div>
    </label>
    ${S.legalErr?`<div class="err" style="margin-top:8px">${esc(S.legalErr)}</div>`:''}
    <div class="btn-row">
      <button class="btn btn-outline" id="btnSafetyBack">← Back</button>
      <button class="btn btn-primary" id="btnSafetyNext" ${S.legalAccepted?'style="background:#1A5240"':''}>
        ${S.legalAccepted?'✓ Accepted — Continue →':'Accept &amp; Continue →'}
      </button>
    </div>
    <div style="font-size:10px;color:var(--text-light);margin-top:12px;text-align:center;line-height:1.5">Your acceptance is recorded with your name, IP address, and timestamp for our records.</div>
  </div>`;
}

function renderWelcomePage(){
  const html=load(SK.welcomeHtml,WELCOME_DEFAULT);
  return`<div class="card">
    <div class="fade-in">${html}</div>
    <div class="btn-row" style="margin-top:22px">
      <button class="btn btn-primary" id="btnWelcomeStart" style="background:#1A5240;font-size:14px;box-shadow:0 2px 8px rgba(26,82,64,.25)">Start →</button>
    </div>
    <div style="text-align:center;font-size:11px;color:var(--text-light);margin-top:10px">Takes approximately 5 minutes</div>
  </div>`;
}

/* =============================================================
   ADMIN PANEL
   ============================================================= */
function renderAdmin(){
  if(!S.adminAuthed){return renderAdminLogin();}
  return`<div class="admin-overlay" id="adminOverlay">
    <div class="admin-panel fade-in">
      <div class="admin-header">
        <div>
          <h1>🔐 Admin Panel</h1>
          <p>J.P. Sutton Safety Reserve — Content Manager</p>
        </div>
        <button class="admin-close" id="btnAdminClose">✕ Close</button>
      </div>
      <div class="admin-tabs">
        ${['welcome','safety','aiquery','disruption','tosurl','questionlogic','password','records','codes'].map(t=>{
          const labels={welcome:'Welcome Page',activationcard:'Activation Card',safety:'Safety Summary',aiquery:'AI Real-Time',disruption:'Disruption Insights',tosurl:'ToS URL',questionlogic:'Question Logic',password:'Password',records:'Records',codes:'Code Generator'};
          return`<button class="admin-tab ${S.adminTab===t?'active':''}" data-tab="${t}">${labels[t]}</button>`;
        }).join('')}
      </div>
      <div class="admin-body">${renderAdminTab()}</div>
    </div>
  </div>`;
}

function renderAdminLogin(){
  return`<div class="admin-overlay">
    <div class="admin-login-card fade-in">
      <div class="shield-dark">🔐</div>
      <div style="font-family:'DM Serif Display',serif;font-size:22px;color:white;margin-bottom:5px">Admin Access</div>
      <div style="font-size:12px;color:rgba(255,255,255,.5);margin-bottom:22px;line-height:1.5">This area is restricted to authorized administrators only.</div>
      <div class="admin-fgroup">
        <label class="admin-label" for="adminPwInput">Password</label>
        <input class="admin-input" type="password" id="adminPwInput" placeholder="Enter admin password" autocomplete="current-password">
        ${S.adminLoginErr?`<div style="font-size:11px;color:#FCA5A5;margin-top:6px">${esc(S.adminLoginErr)}</div>`:''}
      </div>
      <div class="admin-btn-row">
        <button class="admin-btn admin-btn-primary" id="btnAdminLogin" style="width:100%;justify-content:center">Unlock Admin Panel →</button>
      </div>
      <div style="margin-top:14px;text-align:center">
        <button class="admin-btn admin-btn-outline" id="btnAdminClose" style="font-size:11px">✕ Cancel</button>
      </div>
    </div>
  </div>`;
}

function renderAdminTab(){
  if(S.adminTab==='welcome')return renderAdminWelcome();
  if(S.adminTab==='activationcard')return renderAdminActivationCard();
  if(S.adminTab==='safety')return renderAdminSafety();
  if(S.adminTab==='aiquery')return renderAdminAIQuery();
  if(S.adminTab==='disruption')return renderAdminDisruption();
  if(S.adminTab==='tosurl')return renderAdminToS();
  if(S.adminTab==='password')return renderAdminPassword();
  if(S.adminTab==='records')return renderAdminRecords();
  if(S.adminTab==='questionlogic')return renderAdminQuestionLogic();
  if(S.adminTab==='codes')return renderAdminCodes();
  return'';
}

function renderAdminQuestionLogic(){
  const stored=loadJson(SK.questionLogic,null);
  const hasCustom=stored&&stored.pos&&stored.pos.length>0;
  const uploadedAt=stored?.uploadedAt?new Date(stored.uploadedAt).toLocaleString():'Never';
  const posCount=stored?.pos?.length||POS.length;
  const negCount=stored?.neg?.length||NEG.length;
  const qCount=stored?.questions?.length||LOC_QS.length;
  return`<div>
    <div class="admin-info">📊 <strong>Spreadsheet-Driven Question Logic</strong><br>Upload your <strong>Attribute_mapping.xlsx</strong> to update the questions asked during setup and the attributes shown on Location Scenario cards. Columns used: A=Category · B=Attribute · C=Cognitive Category · D=NA Types · E=Question · F=Responses · G=Defaults · H=Trigger · I=Adds to Card.</div>
    ${hasCustom
      ?`<div style="background:rgba(74,133,112,.2);border:1px solid rgba(74,133,112,.4);border-radius:8px;padding:10px 13px;font-size:11px;color:#6EE7B7;line-height:1.6;margin-bottom:14px">✓ <strong>Custom logic active</strong> — uploaded ${esc(uploadedAt)}<br>${posCount} positive attributes · ${negCount} caution attributes · ${qCount} questions</div>`
      :`<div class="admin-warn">⚠️ Using <strong>built-in defaults</strong>. Upload your spreadsheet below to activate custom logic.</div>`
    }
    <div style="background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.1);border-radius:10px;padding:16px;margin-bottom:16px">
      <div style="font-size:12px;font-weight:700;color:rgba(255,255,255,.8);margin-bottom:8px">📂 Upload Spreadsheet (.xlsx)</div>
      <div style="font-size:11px;color:rgba(255,255,255,.4);margin-bottom:12px;line-height:1.5">Select your attribute mapping spreadsheet. Columns must match: A=Category, B=Attribute, C=Cognitive Category, D=Not Applicable Types, E=Question, F=Responses, G=Defaults, H=Trigger, I=Adds to Card.</div>
      <input type="file" id="qlFileInput" accept=".xlsx,.xls" style="display:none">
      <button class="admin-btn admin-btn-primary" id="btnPickQLFile" style="background:#3A6EA8">📂 Choose Spreadsheet…</button>
      <span id="qlFileName" style="font-size:11px;color:rgba(255,255,255,.4);margin-left:10px"></span>
      <div id="qlParseStatus" style="margin-top:10px"></div>
    </div>
    ${hasCustom?`<div class="admin-btn-row"><button class="admin-btn admin-btn-danger" id="btnResetQL">🗑 Remove Custom Logic — Revert to Defaults</button></div>`:``}
    ${S.adminSaveMsg?`<div class="admin-success-msg" style="margin-top:10px">✓ ${esc(S.adminSaveMsg)}</div>`:''}
  </div>`;
}

function renderAdminDisruption(){
  const current=load(SK.disruptionInsights,DISRUPTION_INSIGHTS_DEFAULT);
  return`<div>
    <div class="admin-info">&#128202; <strong>Safety Reserve Urban Resilience Guide &#8212; Disruption Insights</strong><br>This page is included in every print/download. Use the structured plain-text format below:<br><code>TITLE|Page title</code> &middot; <code>INTRO|Intro paragraph</code> &middot; <code>CARD|emoji|Title|Category</code> &middot; <code>SUBHEAD|Sub-heading text</code> &middot; <code>BULLET|Bullet text</code> &middot; <code>CALLOUT|Bold label|Body text</code> &middot; <code>DIVIDER|Section label</code> &middot; <code>FOOTER|Footer text</code></div>
    <div class="admin-warn">&#9888;&#65039; Keep exact prefixes (CARD|, BULLET|, etc.) &#8212; edit only the text after the pipe (|). Each CARD must come before its BULLET/SUBHEAD/CALLOUT lines.</div>
    <div style="background:#1A2A1A;border:1px solid #2A4A2A;border-radius:10px;padding:14px 16px;margin-bottom:14px">
      <div style="font-size:12px;font-weight:700;color:#7EC87E;margin-bottom:8px">&#128206; Upload Disruption File</div>
      <div style="font-size:11px;color:rgba(255,255,255,.5);margin-bottom:10px;line-height:1.5">Attach an <strong style="color:rgba(255,255,255,.7)">.html</strong> file &#8212; its body will be used directly in every print job, bypassing the editor below. Or attach a <strong style="color:rgba(255,255,255,.7)">.txt</strong> pipe-format file to load it into the editor.</div>
      <input type="file" id="disruptionFileInput" accept=".html,.htm,.txt" style="display:none">
      <button class="admin-btn admin-btn-outline" id="btnPickDisruptionFile" style="border-color:#4A7A4A;color:#7EC87E">&#128194; Choose File&#8230;</button>
      <span id="disruptionFileName" style="font-size:11px;color:rgba(255,255,255,.4);margin-left:10px"></span>
    </div>
    <div class="admin-fgroup">
      <label class="admin-label">Disruption Insights Content (pipe-format)</label>
      <textarea class="admin-textarea" id="adminDisruptionArea" style="min-height:300px">${esc(current)}</textarea>
    </div>
    <div class="admin-btn-row">
      <button class="admin-btn admin-btn-primary" id="btnSaveDisruption">&#128190; Save Disruption Insights</button>
      <button class="admin-btn admin-btn-outline" id="btnResetDisruption">&#8617; Reset to Default</button>
    </div>
    ${S.adminSaveMsg?`<div class="admin-success-msg" style="margin-top:10px">&#10003; ${esc(S.adminSaveMsg)}</div>`:''}
  </div>`;
}
function renderAdminWelcome(){
  const current=load(SK.welcomeHtml,WELCOME_DEFAULT);
  return`<div>
    <div class="admin-info">This is the content shown on the Welcome page after the user accepts the legal terms. HTML is supported for rich formatting.</div>
    <div class="admin-fgroup">
      <label class="admin-label">Welcome Page HTML</label>
      <textarea class="admin-textarea" id="adminWelcomeArea" style="min-height:240px">${esc(current)}</textarea>
    </div>
    <div class="admin-btn-row">
      <button class="admin-btn admin-btn-primary" id="btnSaveWelcome">💾 Save Welcome Page</button>
      <button class="admin-btn admin-btn-outline" id="btnResetWelcome">↩ Reset to Default</button>
    </div>
    ${S.adminSaveMsg?`<div class="admin-success-msg" style="margin-top:10px">✓ ${esc(S.adminSaveMsg)}</div>`:''}
  </div>`;
}

function renderAdminSafety(){
  const current=load(SK.safetyText,SAFETY_DEFAULT);
  return`<div>
    <div class="admin-info">This controls the Critical Safety &amp; Use Summary page. Use the format below for bullet points — each bullet is on its own line starting with BULLET|icon|Title|Body text.</div>
    <div class="admin-warn">⚠️ Format: First line = intro paragraph. Each bullet = BULLET|emoji|Bold Title|Body text (Terms of Service is auto-linked)</div>
    <div class="admin-fgroup">
      <label class="admin-label">Safety Page Content</label>
      <textarea class="admin-textarea" id="adminSafetyArea" style="min-height:260px">${esc(current)}</textarea>
    </div>
    <div class="admin-btn-row">
      <button class="admin-btn admin-btn-primary" id="btnSaveSafety">💾 Save Safety Content</button>
      <button class="admin-btn admin-btn-outline" id="btnResetSafety">↩ Reset to Default</button>
    </div>
    ${S.adminSaveMsg?`<div class="admin-success-msg" style="margin-top:10px">✓ ${esc(S.adminSaveMsg)}</div>`:''}
  </div>`;
}

function renderAdminAIQuery(){
  const current=load(SK.aiQueryText,AI_QUERY_DEFAULT);
  const currentDate=getAIQueryDate();
  return`<div>
    <div class="admin-info">This is the AI Real Time Situational Analysis document included in every print/download. Update the content and version date whenever you release a new version.</div>
    <div class="admin-fgroup">
      <label class="admin-label">Document Version Date (e.g. March 20)</label>
      <input class="admin-input" id="adminAIDateInput" value="${esc(currentDate)}" placeholder="e.g. March 20">
    </div>
    <div class="admin-fgroup">
      <label class="admin-label">AI Real Time Situational Analysis Content</label>
      <textarea class="admin-textarea" id="adminAIQueryArea" style="min-height:280px">${esc(current)}</textarea>
    </div>
    <div class="admin-btn-row">
      <button class="admin-btn admin-btn-primary" id="btnSaveAIQuery">💾 Save AI Query Document</button>
      <button class="admin-btn admin-btn-outline" id="btnResetAIQuery">↩ Reset to Default</button>
    </div>
    ${S.adminSaveMsg?`<div class="admin-success-msg" style="margin-top:10px">✓ ${esc(S.adminSaveMsg)}</div>`:''}
  </div>`;
}

function renderAdminToS(){
  const current=getTosUrl();
  return`<div>
    <div class="admin-info">📋 <strong>Insert your Terms of Service URL here.</strong> This link is referenced in the Critical Safety &amp; Use Summary. You can also set it permanently by editing <code>TERMS_URL_DEFAULT</code> near the top of the HTML file's &lt;script&gt; section.</div>
    <div class="admin-fgroup">
      <label class="admin-label">Terms of Service URL</label>
      <input class="admin-input" id="adminTosInput" value="${esc(current)}" placeholder="https://yourdomain.com/terms">
    </div>
    <div class="admin-btn-row">
      <button class="admin-btn admin-btn-primary" id="btnSaveTos">💾 Save URL</button>
    </div>
    ${S.adminSaveMsg?`<div class="admin-success-msg" style="margin-top:10px">✓ ${esc(S.adminSaveMsg)}</div>`:''}
  </div>`;
}

function renderAdminPassword(){
  const recKey=getRecoveryKey();
  return`<div>
    <div class="admin-warn">⚠️ Password must be at least 12 characters and include uppercase, lowercase, a number, and a symbol (e.g. @, #, !).</div>
    <div class="admin-fgroup">
      <label class="admin-label">Current Password</label>
      <input class="admin-input" type="password" id="adminPwCurrent" placeholder="Current password">
    </div>
    <div class="admin-fgroup">
      <label class="admin-label">New Password (min 12 chars, uppercase, lowercase, number, symbol)</label>
      <input class="admin-input" type="password" id="adminPwNew" placeholder="e.g. Safety@Admin2025!">
    </div>
    <div class="admin-fgroup">
      <label class="admin-label">Confirm New Password</label>
      <input class="admin-input" type="password" id="adminPwConfirm" placeholder="Confirm new password">
    </div>
    ${S.adminLoginErr?`<div style="font-size:11px;color:#FCA5A5;margin-top:-8px;margin-bottom:8px">${esc(S.adminLoginErr)}</div>`:''}
    <div class="admin-btn-row">
      <button class="admin-btn admin-btn-primary" id="btnChangePassword">🔑 Change Password</button>
    </div>
    ${S.adminSaveMsg?`<div class="admin-success-msg" style="margin-top:10px">✓ ${esc(S.adminSaveMsg)}</div>`:''}
    <div style="margin-top:24px;padding-top:18px;border-top:1px solid rgba(255,255,255,.1)">
      <div class="admin-section-title" style="margin-bottom:10px">🔒 Recovery Mode</div>
      <div class="admin-info" style="margin-bottom:12px">If you forget your password, use this recovery key to reset it. <strong>Store this key somewhere safe outside this app.</strong></div>
      <div style="background:rgba(0,0,0,.35);border:1.5px solid rgba(255,255,255,.2);border-radius:9px;padding:11px 16px;font-size:15px;font-weight:800;letter-spacing:.12em;color:white;font-family:'Sora',sans-serif;margin-bottom:12px;text-align:center">${esc(recKey)}</div>
      <div class="admin-section-title" style="margin-bottom:8px">Use Recovery Key</div>
      <div class="admin-fgroup">
        <input class="admin-input" type="text" id="adminRecoveryInput" placeholder="Enter recovery key to reset password…" autocomplete="off">
      </div>
      <div class="admin-fgroup">
        <input class="admin-input" type="password" id="adminRecoveryNewPw" placeholder="New password (after recovery)">
      </div>
      <button class="admin-btn admin-btn-outline" id="btnRecoverPassword" style="color:#FCD34D;border-color:rgba(253,211,77,.4)">🔓 Reset via Recovery Key</button>
      ${S.recoveryErr?`<div style="font-size:11px;color:#FCA5A5;margin-top:8px">${esc(S.recoveryErr||'')}</div>`:''}
    </div>
  </div>`;
}

function renderAdminRecords(){
  const regs=loadJson(SK.registrations,[]);
  const legal=loadJson(SK.legalRecords,[]);
  const q=(S.recordsSearch||'').toLowerCase().trim();
  function matchRec(r){if(!q)return true;return(r.fullName||'').toLowerCase().includes(q)||(r.email||'').toLowerCase().includes(q)||(r.activationCode||'').toLowerCase().includes(q);}
  const filtRegs=regs.filter(matchRec);
  const filtLegal=legal.filter(matchRec);
  return`<div>
    <div class="admin-fgroup" style="margin-bottom:16px">
      <label class="admin-label">🔍 Search Records</label>
      <input class="admin-input" id="recordsSearchInput" value="${esc(S.recordsSearch||'')}" placeholder="Search by name or email…">
    </div>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:10px">
      <div class="admin-section-title" style="margin:0">Registrations (${filtRegs.length}${q?' of '+regs.length:''})</div>
      <button class="admin-btn admin-btn-outline" id="btnDownloadRegs" style="font-size:11px;padding:5px 10px">⬇ Download CSV</button>
    </div>
    ${filtRegs.length===0?`<div style="font-size:12px;color:rgba(255,255,255,.35);margin-bottom:24px">${q?'No matching registrations.':'No registrations yet.'}</div>`:filtRegs.slice().reverse().map(r=>`
      <div class="admin-record-row">
        <span class="admin-badge badge-blue" style="margin-right:7px">${esc(r.activationCode||'—')}</span>
        <strong style="color:rgba(255,255,255,.8)">${esc(r.fullName||'—')}</strong> · ${esc(r.email||'—')}<br>
        <span style="font-size:10px;color:rgba(255,255,255,.35)">${r.registeredAt?new Date(r.registeredAt).toLocaleString():''}</span>
      </div>`).join('')}
    <div style="display:flex;align-items:center;justify-content:space-between;margin:24px 0 10px">
      <div class="admin-section-title" style="margin:0">Legal Acceptances (${filtLegal.length}${q?' of '+legal.length:''})</div>
      <button class="admin-btn admin-btn-outline" id="btnDownloadLegal" style="font-size:11px;padding:5px 10px">⬇ Download CSV</button>
    </div>
    ${filtLegal.length===0?`<div style="font-size:12px;color:rgba(255,255,255,.35)">${q?'No matching acceptances.':'No acceptances yet.'}</div>`:filtLegal.slice().reverse().map(r=>`
      <div class="admin-record-row">
        <span class="admin-badge badge-green" style="margin-right:7px">Accepted</span>
        <strong style="color:rgba(255,255,255,.8)">${esc(r.fullName||'—')}</strong> · ${esc(r.email||'—')}<br>
        IP: <span style="color:rgba(255,255,255,.5)">${esc(r.ip||'—')}</span><br>
        <span style="font-size:10px;color:rgba(255,255,255,.35)">${r.acceptedAt?new Date(r.acceptedAt).toLocaleString():''}</span>
      </div>`).join('')}
    <div class="admin-btn-row" style="margin-top:20px">
      <button class="admin-btn admin-btn-danger" id="btnClearRecords">🗑 Clear All Records</button>
    </div>
  </div>`;
}

function renderAdminActivationCard(){
  const tpl=load(SK.activationCardTemplate,ACTIVATION_CARD_TEMPLATE_DEFAULT);
  return`<div>
    <div style="background:rgba(74,111,165,.12);border:1px solid rgba(74,111,165,.3);border-radius:12px;padding:18px;margin-bottom:20px">
      <div class="admin-section-title" style="margin-bottom:6px;color:rgba(74,158,232,.9)">📄 ACTIVATION CARD PAGE — DEFAULT TEMPLATE</div>
      <div class="admin-info" style="margin-bottom:14px">This page is inserted into the Safety Reserve Guide. Edit the "Get Started" text below and save it as the default. It will pre-fill into every new code you generate.</div>

      <div class="admin-fgroup">
        <label class="admin-label">Page Title (fixed)</label>
        <div style="padding:9px 13px;border:1px solid rgba(255,255,255,.1);border-radius:9px;font-size:13px;font-weight:700;color:rgba(255,255,255,.6);background:rgba(0,0,0,.2)">Your Urban Resilience Guide</div>
      </div>

      <div class="admin-fgroup">
        <label class="admin-label">Highlighted Sections (fixed — displayed with icons on card)</label>
        <div style="border:1px solid rgba(255,255,255,.08);border-radius:9px;overflow:hidden">
          ${[['🤖','AI Real Time Situational Analysis','Rapidly determine what is most likely happening, how reliable that conclusion is, and how people are reacting'],['📍','Location Scenarios','Possible options and associated considerations based on your inputs'],['📋','Your Communication Plan',''],['🎒','Pre-Plan Essentials','Items you plan to take if time and conditions allow'],['📊','Disruption Insights','Representative examples of unusual events, with observed patterns']].map(([ic,nm,sub])=>`<div style="display:flex;align-items:flex-start;gap:10px;padding:8px 13px;border-bottom:1px solid rgba(255,255,255,.06)"><span style="font-size:15px;flex-shrink:0;margin-top:1px">${ic}</span><div><div style="font-size:12px;font-weight:700;color:rgba(255,255,255,.75)">${nm}</div>${sub?`<div style="font-size:10px;color:rgba(255,255,255,.38);margin-top:1px">${sub}</div>`:''}</div></div>`).join('')}
        </div>
      </div>

      <div class="admin-fgroup">
        <label class="admin-label">"Get Started" Body Text <span style="color:rgba(255,255,255,.35);font-size:10px;font-weight:400;text-transform:none;letter-spacing:0">— appears below the QR / code on the printed card</span></label>
        <textarea class="admin-textarea" id="acTplTextarea" rows="6" style="min-height:110px">${esc(tpl)}</textarea>
      </div>

      <div class="admin-fgroup">
        <label class="admin-label">Support Email (fixed)</label>
        <div style="padding:9px 13px;border:1px solid rgba(255,255,255,.1);border-radius:9px;font-size:13px;color:rgba(255,255,255,.6);background:rgba(0,0,0,.2)">support@jpsutton.com</div>
      </div>

      <div class="admin-btn-row">
        <button class="admin-btn admin-btn-primary" id="btnSaveAcTemplate">💾 Save Default Template</button>
        ${S.adminCardTplMsg?`<span class="admin-success-msg">✓ ${esc(S.adminCardTplMsg)}</span>`:''}
      </div>
    </div>

    <div style="background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.08);border-radius:10px;padding:14px;font-size:11px;color:rgba(255,255,255,.4);line-height:1.7">
      <strong style="color:rgba(255,255,255,.6)">How the Activation Card works:</strong><br>
      Go to <strong style="color:rgba(74,158,232,.8)">Code Generator</strong> → enter a Shopify Order Number → click Save &amp; Print. The card will print with the fixed sections above, plus your template text, the QR code (or uploaded image), and the unique activation code.
    </div>
  </div>`;
}

function renderAdminCodes(){
  if(!S.newCodeStr)freshNewCode();
  const codes=loadCodes(),filt=S.codeListFilter||'all',now=new Date();
  const unused=codes.filter(c=>!c.cancelled&&new Date(c.expiresAt)>now&&(!c.activations||c.activations.length===0)).length;
  const activated=codes.filter(c=>!c.cancelled&&c.activations&&c.activations.length>=1).length;
  const multi=codes.filter(c=>!c.cancelled&&c.activations&&c.activations.length>1).length;
  const expired=codes.filter(c=>!c.cancelled&&new Date(c.expiresAt)<=now).length;
  const cancelled=codes.filter(c=>c.cancelled).length;
  let shown=codes;
  if(filt==='unused')shown=codes.filter(c=>!c.cancelled&&new Date(c.expiresAt)>now&&(!c.activations||c.activations.length===0));
  else if(filt==='activated')shown=codes.filter(c=>!c.cancelled&&c.activations&&c.activations.length>=1);
  else if(filt==='multi')shown=codes.filter(c=>!c.cancelled&&c.activations&&c.activations.length>1);
  else if(filt==='expired')shown=codes.filter(c=>!c.cancelled&&new Date(c.expiresAt)<=now);
  else if(filt==='cancelled')shown=codes.filter(c=>c.cancelled);
  return `<div>
    <div style="background:rgba(74,111,165,.12);border:1px solid rgba(74,111,165,.3);border-radius:12px;padding:18px;margin-bottom:20px">
      <div class="admin-section-title" style="margin-bottom:14px;color:rgba(74,158,232,.9)">⚡ GENERATE NEW ACTIVATION CODE</div>
      <div class="admin-fgroup">
        <label class="admin-label">📦 Shopify Order Number <span style="color:rgba(255,255,255,.35);font-size:10px;font-weight:400;text-transform:none;letter-spacing:0">(4-digit order from Shopify)</span></label>
        <input class="admin-input" id="newOrderNum" value="${esc(S.newOrderNumber)}" placeholder="e.g. 1042" maxlength="6" style="font-size:17px;font-weight:700;letter-spacing:.08em">
      </div>
      <div style="display:flex;align-items:center;gap:10px;margin-bottom:14px">
        <div style="flex:1">
          <label class="admin-label" style="margin-bottom:6px">Generated Activation Code</label>
          <div style="background:rgba(0,0,0,.3);border:1.5px solid rgba(255,255,255,.2);border-radius:9px;padding:11px 16px;font-size:22px;font-weight:800;letter-spacing:.2em;color:white;font-family:'Sora',sans-serif">${S.newCodeStr}</div>
        </div>
        <button class="admin-btn admin-btn-outline" id="btnGenNewCode" style="flex-shrink:0;margin-top:18px">↻ New Code</button>
      </div>
      <div class="admin-fgroup">
        <label class="admin-label">QR Code URL — scanning opens the app with the code pre-filled</label>
        <input class="admin-input" id="newCodeQrUrl" value="${esc(S.newCodeQrUrl)}" placeholder="https://yourapp.com?code=...">
      </div>
      <div class="admin-fgroup">
        <label class="admin-label">Center Image / Replace QR <span style="color:rgba(255,255,255,.35);font-size:10px;font-weight:400;text-transform:none;letter-spacing:0">— replaces the QR with your image; saved permanently across sessions</span></label>
        <div style="display:flex;align-items:center;gap:10px;flex-wrap:wrap;margin-top:6px">
          <label style="cursor:pointer"><span class="admin-btn admin-btn-outline" style="display:inline-flex;align-items:center;gap:5px;pointer-events:none">📷 Upload Image</span><input type="file" id="codeImageUpload" accept="image/*" style="display:none"></label>
          ${S.newCodeImageData?`<div style="width:54px;height:54px;border-radius:8px;overflow:hidden;border:2px solid rgba(74,158,232,.5);background:white;box-shadow:0 0 0 3px rgba(74,158,232,.15)"><img src="${S.newCodeImageData}" style="width:100%;height:100%;object-fit:contain"></div><button class="admin-btn admin-btn-danger" id="btnClearCodeImg" style="font-size:11px;padding:5px 9px">✕ Remove</button><span style="font-size:10px;color:rgba(74,158,232,.8)">✓ Saved — persists across sessions</span>`:`<span style="font-size:11px;color:rgba(255,255,255,.3)">No image — standard QR code will print</span>`}
        </div>
      </div>
      <div class="admin-fgroup">
        <label class="admin-label">Activation Card "Get Started" Text <span style="color:rgba(255,255,255,.35);font-size:10px;font-weight:400;text-transform:none;letter-spacing:0">— editable default template for all new cards</span></label>
        <textarea class="admin-textarea" id="newCodeAdminText" rows="5" style="min-height:100px">${esc(S.newCodeAdminText)}</textarea>
        <div style="display:flex;align-items:center;gap:8px;margin-top:7px;flex-wrap:wrap">
          <button class="admin-btn admin-btn-outline" id="btnSaveCardTemplate" style="font-size:11px">💾 Save as Default Template</button>
          ${S.adminCardTplMsg?`<span class="admin-success-msg">✓ ${esc(S.adminCardTplMsg)}</span>`:''}
        </div>
      </div>
      <div class="admin-btn-row">
        <button class="admin-btn admin-btn-primary" id="btnSaveAndPrintCode" style="font-size:13px;padding:12px 22px">🖨️ Save &amp; Print Activation Card</button>
      </div>
      ${S.adminSaveMsg?`<div class="admin-success-msg" style="margin-top:10px">✓ ${esc(S.adminSaveMsg)}</div>`:''}
    </div>
    <div style="display:grid;grid-template-columns:repeat(5,1fr);gap:7px;margin-bottom:16px">
      ${[['Total',codes.length,'rgba(255,255,255,.75)'],['Unused',unused,'#93C5FD'],['Activated',activated,'#6EE7B7'],['Multi-Use',multi,'#FDBA74'],['Cancelled',cancelled,'#FCA5A5']].map(([l,n,c])=>`<div style="background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.1);border-radius:9px;padding:11px 6px;text-align:center"><div style="font-size:22px;font-weight:800;color:${c}">${n}</div><div style="font-size:9px;color:rgba(255,255,255,.4);margin-top:2px;text-transform:uppercase;letter-spacing:.05em">${l}</div></div>`).join('')}
    </div>
    <div style="display:flex;gap:6px;margin-bottom:14px;flex-wrap:wrap">
      ${[['all','All'],['unused','Unused'],['activated','Activated'],['multi','Multi-Use'],['expired','Expired'],['cancelled','Cancelled']].map(([k,l])=>`<button class="admin-btn ${filt===k?'admin-btn-primary':'admin-btn-outline'}" data-cf="${k}" style="font-size:11px;padding:5px 11px">${l}</button>`).join('')}
    </div>
    <div>${shown.length===0?`<div style="font-size:12px;color:rgba(255,255,255,.3);padding:16px 0;text-align:center">No codes match this filter.</div>`:shown.slice().reverse().map(r=>{
      const acts=r.activations||[],isExp=new Date(r.expiresAt)<=now;
      const slbl=r.cancelled?'Cancelled':isExp?'Expired':acts.length===0?'Unused':acts.length===1?'Activated':'Multi-Use ('+acts.length+'\xd7)';
      const sc=r.cancelled?'#FCA5A5':isExp?'#FCD34D':acts.length===0?'#93C5FD':acts.length===1?'#6EE7B7':'#FDBA74';
      const expStr=new Date(r.expiresAt).toLocaleDateString('en-US',{month:'short',day:'numeric',year:'numeric'});
      const creStr=new Date(r.createdAt).toLocaleDateString('en-US',{month:'short',day:'numeric',year:'numeric'});
      return `<div style="border-bottom:1px solid rgba(255,255,255,.07);padding:12px 0">
        <div style="display:flex;align-items:center;gap:8px;flex-wrap:wrap">
          <code style="font-size:15px;font-weight:800;letter-spacing:.14em;color:white;font-family:'Sora',sans-serif">${r.code}</code>
          <span style="font-size:10px;font-weight:700;color:${sc}">${slbl}</span>
          ${r.orderNumber?`<span style="font-size:10px;color:rgba(255,255,255,.4);background:rgba(255,255,255,.07);padding:1px 8px;border-radius:4px">Order #${esc(r.orderNumber)}</span>`:''}
          <span style="font-size:10px;color:rgba(255,255,255,.28);margin-left:auto">Created ${creStr} · Exp ${expStr}</span>
          ${!r.cancelled?`<button class="admin-btn admin-btn-outline" data-printcode="${r.code}" style="font-size:10px;padding:4px 9px;min-height:0">🖨️ Card</button>`:''}
          ${!r.cancelled?`<button class="admin-btn admin-btn-danger" data-cancelcode="${r.code}" style="font-size:10px;padding:4px 9px;min-height:0">✕ Cancel</button>`:''}
        </div>
        ${acts.length>0?`<div style="margin-top:8px">${acts.map((a,i)=>`<div style="font-size:11px;color:rgba(255,255,255,.5);padding:3px 0 3px 10px;border-left:2px solid ${acts.length>1?'#FDBA74':'rgba(255,255,255,.15)'};margin-bottom:3px">${acts.length>1&&i===0?'<span style="font-size:9px;color:#FDBA74;font-weight:700;margin-right:6px;background:rgba(253,186,74,.12);padding:1px 6px;border-radius:4px">MULTI</span>':''}<strong style="color:rgba(255,255,255,.8)">${esc(a.name||'—')}</strong> · ${esc(a.email||'—')} · <span style="color:rgba(255,255,255,.32)">${esc(a.ip||'—')}</span> · ${new Date(a.activatedAt).toLocaleString()}</div>`).join('')}</div>`:`<div style="font-size:11px;color:rgba(255,255,255,.22);padding-top:5px;padding-left:10px">No activations yet</div>`}
      </div>`;
    }).join('')}</div>
    ${codes.length>0?`<div class="admin-btn-row" style="margin-top:18px">
      <button class="admin-btn admin-btn-outline" id="btnExportCodesCSV" style="background:rgba(74,158,232,.12);border-color:rgba(74,158,232,.3);color:rgba(74,158,232,.9)">⬇ Export CSV</button>
      <button class="admin-btn admin-btn-danger" id="btnClearAllCodes">🗑 Delete All Codes</button>
    </div>`:''}
  </div>`;
}

/* =============================================================
   MAIN APP RENDER HELPERS
   ============================================================= */
function renderStopBar(){
  return`<div class="stop-bar"><div class="stop-bar-inner">
    <button class="btn-stop" id="btnStopApp">■ Pause</button>
  </div></div>`;
}
function renderMasterProgress(prog){
  const phases=[{label:'1 · Location Scenarios',key:'p1',phase:1},{label:'2 · Contacts',key:'p2',phase:2},{label:'3 · Pre-Plan Essentials',key:'p3',phase:3}];
  return`<div class="master-progress"><div class="phase-pills">${phases.map(ph=>{
    const cls=S.phase===ph.phase?'active':(S.phase>ph.phase?'done':'');
    const fill=S.phase>ph.phase?100:(S.phase===ph.phase?prog[ph.key]:0);
    const col=cls==='done'?'var(--green)':cls==='active'?'var(--blue)':'var(--border)';
    return`<div class="phase-pill ${cls}"><div class="phase-pill-bar"><div class="phase-pill-fill" style="width:${fill}%;background:${col}"></div></div><div class="phase-pill-label">${ph.label}</div></div>`;
  }).join('')}</div></div>`;
}
function renderSR(){switch(S.srStep){case'welcome':return renderWelcome();case'work_school':return renderWorkSchool();case'friends':return renderFriends();case'public_loc':return renderPublicLoc();case'review':return renderReview();case'questionnaire':return renderQuestionnaire();}}
function renderWelcome(){
  // Skip welcome screen — go directly to work/school (must NOT call render() here; we're inside a render cycle)
  if(S.userName.trim()){S.srStep='work_school';return renderWorkSchool();}
  // Fallback: name missing (e.g. Start Fresh)
  return`<div class="card"><div class="shield">🛡️</div><div class="card-title">What's your first name?</div><div class="card-subtitle">This helps personalise your documents.</div><div class="fgroup"><label class="flabel" for="userName">First name</label><input class="finput" id="userName" placeholder="e.g. Jordan" value="${esc(S.userName)}" autocomplete="given-name" autofocus></div><div class="btn-row"><button class="btn btn-primary" id="btnWelNext" ${!S.userName.trim()?'disabled':''}>Continue →</button></div></div>`;
}
function renderWorkSchool(){const ol=getOrderedLocs(S.locations);return`<div class="card"><div class="step-lbl">Step 1 of 4 — Work &amp; School</div><div class="step-prog"><div class="step-prog-fill" style="width:25%"></div></div><div class="card-title" style="font-size:21px">Work or School?</div><div class="card-subtitle">Do you work or attend school in person?</div>${['work','school','both','na'].map(o=>`<button class="opt ${S.wsChoice===o?'sel':''}" data-ws="${o}">${{work:'💼 Work',school:'🎓 School',both:'💼🎓 Both',na:'Not applicable'}[o]}</button>`).join('')}${S.wsChoice&&['work','both'].includes(S.wsChoice)?renderWorkBlock():''}${S.wsChoice&&['school','both'].includes(S.wsChoice)?renderSchoolBlock():''}<div style="margin-top:18px">${renderLocList(ol,false)}</div><div class="btn-row"><button class="btn btn-outline" id="btnWsBack">← Back</button><button class="btn btn-primary" id="btnWsNext" ${!S.wsChoice?'disabled':''}>Next →</button></div></div>`;}
function renderWorkBlock(){return`<div class="indent"><div class="fgroup"><label class="flabel">Do you periodically go to an office?</label>${[true,false].map(v=>`<button class="opt ${S.workGoesIn===v?'sel':''}" data-wgi="${v}" style="margin-bottom:7px">${v?'Yes, I go to an office':'No, I work remotely'}</button>`).join('')}${S.errors.workGoesIn?`<div class="err">${esc(S.errors.workGoesIn)}</div>`:''}</div>${S.workGoesIn?`<div class="fgroup"><label class="flabel">Office name</label><input class="finput" id="workName" placeholder='e.g. "Midtown Office"' value="${esc(S.workName)}"></div><div class="fgroup"><label class="flabel">Travel time from home (minutes)</label><input class="finput" id="workMins" type="number" placeholder="e.g. 25" value="${esc(S.workMins)}">${isSusSmall(S.workMins)&&!S.workMinsConf?minsWarn('work',S.workMins):''}</div>${S.errors.work?`<div class="err">${esc(S.errors.work)}</div>`:''}`:''}`;  return`</div>`;}
function renderSchoolBlock(){return`<div class="indent" style="margin-top:10px"><div class="fgroup"><label class="flabel">Do you periodically go to a campus?</label>${[true,false].map(v=>`<button class="opt ${S.schoolGoesIn===v?'sel':''}" data-sgi="${v}" style="margin-bottom:7px">${v?'Yes, I attend campus':'No, I attend remotely'}</button>`).join('')}${S.errors.schoolGoesIn?`<div class="err">${esc(S.errors.schoolGoesIn)}</div>`:''}</div>${S.schoolGoesIn?`<div class="fgroup"><label class="flabel">Campus name</label><input class="finput" id="schoolName" placeholder='e.g. "Main Campus"' value="${esc(S.schoolName)}"></div><div class="fgroup"><label class="flabel">Travel time from home (minutes)</label><input class="finput" id="schoolMins" type="number" placeholder="e.g. 30" value="${esc(S.schoolMins)}">${isSusSmall(S.schoolMins)&&!S.schoolMinsConf?minsWarn('school',S.schoolMins):''}</div>${S.errors.school?`<div class="err">${esc(S.errors.school)}</div>`:''}`:''}`;  return`</div>`;}
function minsWarn(pfx,val){const h=parseInt(val);return`<div class="warn-box"><strong>⚠️ Is ${h} correct?</strong><br>Did you mean <strong>${h} minute${h===1?'':`s`}</strong> (very short trip), or <strong>${h} hour${h>1?'s':''} = ${h*60} minutes</strong>?<div style="display:flex;gap:7px;margin-top:8px;flex-wrap:wrap"><button class="btn btn-sm btn-outline" data-conf-mins="${pfx}">✓ Yes, ${h} min${h===1?'':`s`}</button><button class="btn btn-sm btn-primary" data-sw-hrs="${pfx}" data-hrs="${h*60}">Switch to ${h*60} min (${h} hr${h>1?'s':''})</button></div></div>`;}
function renderFriends(){const ol=getOrderedLocs(S.locations);const pCnt=S.locations.filter(l=>!["P","PS"].includes(l.type)).length;const canAdd=pCnt<MAX_PERSONAL;const m=parseInt(S.friendMins);const hasFormContent=!!(S.friendName.trim()||S.friendMins);const csNeed=S.friendRel==='roommates_parents'||((S.friendRel==='friend'||S.friendRel==='partner')&&m>60);return`<div class="card"><div class="step-lbl">Step 2 of 4 — Friends &amp; Family</div><div class="step-prog"><div class="step-prog-fill" style="width:50%"></div></div><div class="card-title" style="font-size:21px">Friends &amp; Family</div><div class="card-subtitle">Add people whose home you could go to. <strong>At least one must be 1+ hour away.</strong></div>${renderLocList(ol,true)}${canAdd?`<div class="indent indent-dash"><div class="fgroup"><label class="flabel">Add a Person or Place</label><select class="fselect" id="fRel"><option value="friend" ${S.friendRel==='friend'?'selected':''}>Friend</option><option value="partner" ${S.friendRel==='partner'?'selected':''}>Partner</option><option value="family" ${S.friendRel==='family'?'selected':''}>Family</option><option value="roommates_parents" ${S.friendRel==='roommates_parents'?'selected':''}>Roommate's Parents</option></select></div><div class="fgroup"><label class="flabel">Name or relationship</label><input class="finput" id="fName" placeholder="${S.friendRel==='family'?'e.g. Parents, Brother':'e.g. Alex'}" value="${esc(S.friendName)}">${S.errors.friendName?`<div class="err">${esc(S.errors.friendName)}</div>`:''}</div><div class="fgroup"><label class="flabel">Travel time from home (minutes)</label><input class="finput" id="fMins" type="number" placeholder="e.g. 120" value="${esc(S.friendMins)}">${S.errors.friendMins?`<div class="err">${esc(S.errors.friendMins)}</div>`:''} ${isSusSmall(S.friendMins)&&!S.friendMinsConf?minsWarn('friend',S.friendMins):''}</div>${csNeed?`<div style="display:flex;gap:9px"><div class="fgroup" style="flex:1"><label class="flabel">City</label><input class="finput" id="fCity" placeholder="City" value="${esc(S.friendCity)}">${S.errors.friendCity?`<div class="err">${esc(S.errors.friendCity)}</div>`:''}</div><div class="fgroup" style="width:76px"><label class="flabel">State</label><input class="finput" id="fState" placeholder="ST" maxlength="2" value="${esc(S.friendState)}">${S.errors.friendState?`<div class="err">${esc(S.errors.friendState)}</div>`:''}</div></div>`:''}${hasFormContent?`<button class="btn btn-sm btn-primary" id="btnAddFriend" style="width:100%;margin-top:4px;background:var(--blue-dark);box-shadow:0 2px 8px rgba(44,74,110,.3)">+ Add Person / Place</button>`:`<button class="btn btn-sm btn-outline" id="btnAddFriend" style="width:100%;margin-top:4px;border-color:var(--blue);color:var(--blue-dark)">+ Add Person / Place</button>`}</div>`:''}${pCnt>=MAX_PERSONAL?`<div class="success-box">✓ All 5 personal locations filled. Continue to add your public location.</div>`:''}<div class="btn-row"><button class="btn btn-outline" id="btnFrBack">← Back</button><button class="btn ${hasFormContent?'btn-outline':'btn-primary'}" id="btnFrNext" style="${hasFormContent?'color:var(--text-mid);':'background:#1A5240;box-shadow:0 2px 8px rgba(26,82,64,.25);'}">✓ Done — Next: Public Location →</button></div></div>`;}
function renderPublicLoc(){const ol=getOrderedLocs(S.locations);const personalCount=S.locations.filter(l=>!["P","PS"].includes(l.type)).length;const posNum=personalCount+1;const ordSuffix=['st','nd','rd'][posNum-1]||'th';return`<div class="card"><div class="step-lbl">Step 3 of 4 — Public Location</div><div class="step-prog"><div class="step-prog-fill" style="width:75%"></div></div><div class="card-title" style="font-size:21px">Public Location</div><div class="card-subtitle">A nearby public place as a useful fallback — your ${posNum}${ordSuffix} and final location.</div>${renderLocList(ol,true)}${['building','shelter'].map(o=>`<button class="opt ${S.pubType===o?'sel':''}" data-pt="${o}">${o==='building'?'🏛️ Public Building':'⛺ Public Shelter'}</button>`).join('')}${S.pubType==='building'?`<div class="fgroup" style="margin-top:4px"><label class="flabel">Building type</label><select class="fselect" id="bldType">${["Community center","Library","Large office building","Hotel lobby","Hospital waiting area","School building","Shopping mall","Large church","Other"].map(t=>`<option ${S.buildingType===t?'selected':''}>${t}</option>`).join('')}</select></div>`:''}<div class="fgroup" style="margin-top:14px"><label class="flabel">Approximate travel time from home (minutes)</label><input class="finput" id="pubMins" type="number" placeholder="e.g. 10" value="${esc(S.pubMins)}">${isSusSmall(S.pubMins)&&!S.pubMinsConf?minsWarn('pub',S.pubMins):''}</div>${S.errors.pub?`<div class="err">${esc(S.errors.pub)}</div>`:''}<div class="btn-row"><button class="btn btn-outline" id="btnPubBack">← Back</button><button class="btn btn-primary" id="btnPubNext">Next →</button></div></div>`;}

/* FIX: Back from Review goes to 'friends' so user can add a far-away contact */
function renderReview(){const ol=getOrderedLocs(S.locations);const hasDist=S.locations.some(l=>["FR","FM"].includes(l.type)&&l.travelMinutes>=60);return`<div class="card"><div class="step-lbl">Step 4 of 4 — Review</div><div class="step-prog"><div class="step-prog-fill" style="width:95%"></div></div><div class="card-title" style="font-size:21px">Review Your Locations</div><div class="card-subtitle">Up to ${MAX_LOCS} locations will appear on your reference card.</div>${renderLocList(ol,true)}${!hasDist?`<div class="alert-box">⚠️ You need at least one friend or family member <strong>more than 1 hour away.</strong><br><strong>Use the Back button to add one.</strong></div>`:''}<div class="btn-row"><button class="btn btn-outline" id="btnRevBack">← Back: Add Contacts</button><button class="btn btn-primary" id="btnRevNext" ${!hasDist?'disabled':''}>Start Quick Profile →</button></div></div>`;}

function renderQuestionnaire(){const ol=getOrderedLocs(S.locations);const allQs=buildQList(ol);if(!allQs.length){S.srStep='sr_output';render();return'';}const q=allQs[S.qIndex];const pct=Math.round((S.qIndex/allQs.length)*100);let qhead='',qbody='';if(q.type==='global'){qhead=`<div class="q-header"><span>🌐</span><span>General Question</span></div>`;const selA=S.globalAns[q.key];qbody=q.opts.map(o=>`<button class="opt ${selA===o?'sel':''}" data-qo="${encodeURIComponent(o)}">${o}</button>`).join('');}else if(q.type==='loc'){const cfg=LOC_CFG[q.locType]||{icon:'📍'};qhead=`<div class="q-header"><span>${cfg.icon}</span><span>${esc(q.locLabel)}</span></div>`;const selA=(S.locAns[q.locId]||{})[q.key];qbody=q.opts.map(o=>`<button class="opt ${selA===o?'sel':''}" data-qo="${encodeURIComponent(o)}">${o}</button>`).join('');}else{const answCnt=q.locs.filter(l=>S.collAns[l.id]).length;const allAns=answCnt===q.locs.length;qhead=`<div class="q-header"><span>📍</span><span>Answer for each location</span><span style="margin-left:auto;font-weight:700;color:${allAns?'var(--green)':'var(--amber)'}">${answCnt}/${q.locs.length} answered</span></div>`;qbody=`<div>${q.locs.map(loc=>{const cfg=LOC_CFG[loc.type];const sel=S.collAns[loc.id];return`<div class="multi-block"><div class="multi-head" style="background:${cfg.light}"><span style="font-size:15px">${cfg.icon}</span><div><div style="font-size:9px;font-weight:700;color:${cfg.color};text-transform:uppercase;letter-spacing:.06em">${cfg.label}</div><div style="font-size:12px;font-weight:700;color:var(--text)">${esc(loc.displayLabel)}</div></div>${sel?`<span style="margin-left:auto;font-size:11px;color:${cfg.color};font-weight:700">✓ ${sel}</span>`:''}</div><div class="multi-opts">${q.opts.map(o=>`<button class="mini-opt ${sel===o?'sel':''}" data-cl="${loc.id}" data-co="${encodeURIComponent(o)}">${o}</button>`).join('')}</div></div>`;}).join('')}<button class="btn btn-primary" id="btnCollNext" style="width:100%;margin-top:4px" ${!allAns?'disabled':''}>${allAns?'Next →':`Answer all ${q.locs.length} to continue`}</button></div>`;}return`<div class="card"><div style="margin-bottom:18px"><div style="font-size:11px;font-weight:600;color:var(--text-light);margin-bottom:5px">Question ${S.qIndex+1} of ${allQs.length} — ${pct}% complete</div><div class="step-prog"><div class="step-prog-fill" style="width:${pct}%"></div></div></div>${qhead}<div style="font-size:16px;font-weight:700;color:var(--blue-dark);margin-bottom:${q.hint?'5px':'18px'};line-height:1.4">${q.label}</div>${q.hint?`<div style="font-size:12px;color:var(--text-mid);margin-bottom:16px">${q.hint}</div>`:''}${qbody}${S.qIndex>0?`<button class="btn btn-outline" id="btnQBack" style="margin-top:12px;display:block">← Back</button>`:''}</div>`;}
function renderLocList(locs,canRm){return`<div class="loc-wrap"><div class="loc-head"><span>📍</span><span>Your locations so far (${locs.length} of max ${MAX_LOCS})</span></div><div class="loc-body">${locs.map(loc=>{const cfg=LOC_CFG[loc.type];const isH=loc.id==='H';const t=fmtTime(loc.travelMinutes);return`<div class="loc-chip ${isH?'home':''}"><span class="lc-icon">${cfg.icon}</span><div class="lc-main"><div style="display:flex;align-items:center;flex-wrap:wrap"><div class="lc-name">${esc(loc.displayLabel)}</div>${isH?'<span class="home-badge">✓ Auto-selected</span>':''}</div><div class="lc-sub">${cfg.label}${t?' · '+t:''}${isH?' · Your starting point':''}</div></div>${canRm&&!isH?`<button class="rm-btn" data-rm="${loc.id}">×</button>`:''}</div>`;}).join('')}</div></div>`;}

/* SR OUTPUT */
function renderSROutput(){const ol=getOrderedLocs(S.locations);const pad=[...ol];while(pad.length<6)pad.push(null);const today=new Date().toLocaleDateString("en-US",{month:"long",year:"numeric"});return`<div class="ref-wrap"><style>@media print{*{-webkit-print-color-adjust:exact!important;print-color-adjust:exact!important;color-adjust:exact!important}.no-print{display:none!important}.ref-wrap{background:white!important;padding:0!important}.ref-card{box-shadow:none!important;border-radius:0!important}.out-grid{grid-template-columns:repeat(2,1fr)!important}}</style><div class="no-print" style="max-width:960px;margin:0 auto 12px;display:flex;gap:8px;justify-content:space-between;align-items:center;flex-wrap:wrap;padding-top:14px"><button class="btn btn-outline btn-sm" id="btnSROBack">← Back</button><button class="btn btn-sm" id="btnSRContinue" style="background:#E05200;color:white;font-size:14px;padding:10px 24px;border-radius:10px;box-shadow:0 3px 12px rgba(224,82,0,.40);font-weight:800;border:2px solid rgba(255,255,255,.25);letter-spacing:.01em">${S.fromFinal?'← Back to Summary':'Continue: Communication Plan →'}</button></div><div id="ref-card-content" class="ref-card">${brandBar('Location Scenarios')}<div style="background:#FFF8ED;border-bottom:1px solid #EED97A;padding:8px 20px"><p style="font-size:11px;color:#7A5C00;line-height:1.5"><strong>Note:</strong> This page lists locations you identified during setup. Information shown is general. Conditions change rapidly during emergencies. Only you can decide what action is appropriate.</p></div><div style="padding:14px 20px 11px;border-bottom:2px solid #F0F1F4;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:7px"><div><div style="font-family:'DM Serif Display',serif;font-size:22px;color:#2C3347;line-height:1.2">Location Scenarios — Based on Your Inputs</div><div style="font-size:13px;color:#5A6270;margin-top:4px;font-weight:600">Possible options and associated considerations</div><div style="font-size:11px;color:#8E95A3;margin-top:3px">Prepared for: <strong style="color:#2C3347">${esc(S.userName)}</strong> · ${today}</div></div><div style="font-size:10px;color:#8E95A3;text-align:right;max-width:150px;line-height:1.4">Travel times are estimated from Home and may vary.</div></div><div style="padding:8px 20px;background:#F7F9FC;border-bottom:1px solid #E8EAF0"><p style="font-size:12px;color:#4B5563;line-height:1.7"><strong>When something unexpected happens:</strong> Take a moment to understand what's going on. Below are locations you previously entered. Conditions may differ during an event. Only you can decide what makes sense.</p></div><div class="out-grid">${pad.map(l=>renderLocBlock(l)).join('')}</div><div style="padding:10px 20px;background:#F8F9FC;border-top:1px solid #E8EAF0"><p style="font-size:10px;color:#5A6270;line-height:1.6">Your starting location and circumstances may affect which option makes sense. You decide what is appropriate. This page is for reference only.</p></div></div></div>`;}
function renderLocBlock(loc){if(!loc)return`<div style="border:1px solid #F0F1F4;background:#FAFAFA;min-height:100px;display:flex;align-items:center;justify-content:center"><span style="font-size:11px;color:#E0E3E8">---</span></div>`;const cfg=LOC_CFG[loc.type];const{pos,neg}=computeAttrs(loc,S.locAns[loc.id],S.globalAns||{});const pG=groupByCat(pos),nG=groupByCat(neg);const t=fmtTime(loc.travelMinutes);return`<div style="border:1px solid #E8EAF0;display:flex;flex-direction:column"><div style="background:${cfg.color};padding:10px 14px;color:white;-webkit-print-color-adjust:exact;print-color-adjust:exact"><div style="display:flex;align-items:center;gap:7px"><span style="font-size:18px">${cfg.icon}</span><div><div style="font-size:9px;font-weight:700;opacity:.8;text-transform:uppercase;letter-spacing:.08em">${cfg.label}</div><div style="font-size:13px;font-weight:700;line-height:1.2">${esc(loc.displayLabel)}</div></div>${t?`<div style="margin-left:auto;font-size:11px;opacity:.9;text-align:right"><div style="font-weight:600">${t}</div><div style="font-size:9px">from home</div></div>`:''}</div></div><div style="padding:12px 14px;flex:1;display:flex;gap:10px"><div style="flex:1;min-width:0">${pos.length?`<div style="font-size:9px;font-weight:700;text-transform:uppercase;letter-spacing:.07em;color:#2A6B4C;background:#D8EDE6;padding:2px 7px;border-radius:4px;margin-bottom:8px;display:inline-block">✓ May Be Available</div>${Object.entries(pG).map(([c,it])=>`<div style="margin-bottom:8px"><div style="font-weight:700;color:#5A6270;font-size:10px;display:flex;align-items:center;gap:3px;margin-bottom:2px"><span>${CAT_ICONS[c]}</span><span>${c}</span></div>${it.map(a=>`<div style="display:flex;gap:4px;padding-left:3px;color:#2A6B4C;margin-bottom:2px;font-size:11px;line-height:1.4"><span style="flex-shrink:0">·</span><span>${a.text}</span></div>`).join('')}</div>`).join('')}`:`''`}</div><div style="width:1px;background:#F0F1F4;flex-shrink:0"></div><div style="flex:1;min-width:0">${neg.length?`<div style="font-size:9px;font-weight:700;text-transform:uppercase;letter-spacing:.07em;color:#7A5C00;background:#F5E9D5;padding:2px 7px;border-radius:4px;margin-bottom:8px;display:inline-block">⚠ Think About</div>${Object.entries(nG).map(([c,it])=>`<div style="margin-bottom:8px"><div style="font-weight:700;color:#5A6270;font-size:10px;display:flex;align-items:center;gap:3px;margin-bottom:2px"><span>${CAT_ICONS[c]}</span><span>${c}</span></div>${it.map(a=>`<div style="display:flex;gap:4px;padding-left:3px;color:#7A5C00;margin-bottom:2px;font-size:11px;line-height:1.4"><span style="flex-shrink:0">·</span><span>${a.text}</span></div>`).join('')}</div>`).join('')}`:`<div style="font-size:11px;color:#C8CDD6;font-style:italic">No notable concerns</div>`}</div></div></div>`;}

/* COMM PLAN */
function renderCommPlan(){const cc=S.commContacts;
  const backToSummaryBanner=S.fromFinal?`<div style="display:flex;align-items:center;justify-content:space-between;background:var(--blue-light);border:1.5px solid #BDD0E6;border-radius:10px;padding:10px 14px;margin-bottom:16px"><span style="font-size:12px;font-weight:600;color:var(--blue-dark)">📋 Viewing from Summary</span><button class="btn btn-outline btn-sm" id="btnCommBackTopBanner" style="font-size:11px;padding:6px 12px">← Back to Summary</button></div>`:'';
  function crow(key,label,hint,lBg,lBdr,dBg){const c=cc[key],pe=S.commPhoneErrs[key];return`<tr><td style="padding:10px 12px;border:1px solid var(--border);font-size:11px;vertical-align:top;width:40%;background:${lBg};border-left:3px solid ${lBdr}"><div style="font-weight:700;font-size:12px;color:var(--text)">${label}</div>${hint?`<div style="font-size:10px;color:var(--text-mid);margin-top:2px;line-height:1.4">${hint}</div>`:''}</td><td style="padding:10px 12px;border:1px solid var(--border);background:${dBg}"><input class="comm-input" id="ci_${key}_name" placeholder="Name" value="${esc(c.name)}" data-ck="${key}" data-cf="name"><input class="comm-phone" id="ci_${key}_phone" placeholder="Phone number" value="${esc(c.phone)}" data-ck="${key}" data-cf="phone">${pe?`<div class="err" style="margin-top:2px">${pe}</div>`:''}</td></tr>`;}return`<div class="card">${backToSummaryBanner}<div style="font-size:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--text-light);margin-bottom:6px">Safety Reserve Urban Resilience Guide</div><div style="font-size:26px;margin-bottom:11px">📋</div><div class="card-title">Communication Plan</div><div class="card-subtitle">Who will you contact? Fill this in now, or print it and complete it by hand later.</div><div class="info-box"><strong>💡 Tip:</strong> When networks are jammed, texting usually gets through faster than a voice call.</div><table class="comm-table"><tbody><tr><td style="padding:10px 12px;border:1px solid var(--border);font-weight:700;font-size:12px;width:40%;background:#FDEAEA;border-left:3px solid #A84040;color:var(--text)">🚨 Emergency Services<div style="font-weight:400;font-size:10px;color:#A84040;margin-top:2px">if needed</div></td><td style="padding:10px 12px;border:1px solid var(--border);font-size:17px;font-weight:700;color:var(--text);background:#FFF5F5">911</td></tr>${crow('primary','📞 Your Primary Contact','','#EAF0F9','#4A6FA5','#F5F8FD')}${crow('outOfTown','🌐 Out-of-Town Hub Contact','Everyone checks in here. Outside the affected area, their line may stay clear when local networks are jammed — they relay news to everyone else.','#D8EDE6','#4A8570','#F4FAF7')}${crow('localFriend','🤝 Local Friend','','#EAE8F5','#7264A8','#F7F6FD')}</tbody></table><div class="fgroup"><label class="flabel">📱 Group Text</label><input class="finput" id="commGroup" placeholder="Group name or list of numbers" value="${esc(S.commGroup)}"><div style="font-size:10px;color:var(--text-light);margin-top:4px">Phone-based only — SMS or iMessage, not social media.</div></div><div class="btn-row"><button class="btn btn-outline" id="btnCommBack">${S.fromFinal?'← Back to Summary':'← Back'}</button><button class="btn btn-primary" id="btnCommNext" style="background:#1A5240;font-size:14px;box-shadow:0 2px 8px rgba(26,82,64,.25)">Next: Pre-Plan Essentials →</button></div></div>`;}

/* ESSENTIALS */
function renderEssentials(){const all=[...DEFAULT_ESSENTIALS,...S.customEssentials];
  const essBackBanner=S.fromFinal?`<div style="display:flex;align-items:center;justify-content:space-between;background:var(--blue-light);border:1.5px solid #BDD0E6;border-radius:10px;padding:10px 14px;margin-bottom:16px"><span style="font-size:12px;font-weight:600;color:var(--blue-dark)">🎒 Viewing from Summary</span><button class="btn btn-outline btn-sm" id="btnEssBackTopBanner" style="font-size:11px;padding:6px 12px">← Back to Summary</button></div>`:'';
  return`<div class="card">${essBackBanner}<div style="font-size:26px;margin-bottom:11px">🎒</div><div class="card-title">Pre-Plan Essentials</div><div class="card-subtitle">Tap items you plan to take if time and conditions allow. <strong>Prioritize personal safety above all.</strong></div><div class="ess-grid">${all.map(item=>{const sel=S.selectedEssentials.has(item);return`<div class="ess-item ${sel?'sel':''}" data-ess="${encodeURIComponent(item)}"><span class="ess-check">${sel?'⭐':'○'}</span><span>${esc(item)}</span></div>`;}).join('')}</div><div class="divider">Add your own items</div><div style="display:flex;gap:8px;margin-bottom:12px"><input class="finput" id="custInput" placeholder="Add a custom item…" value="${esc(S.customInput)}" style="flex:1"><button class="btn btn-outline btn-sm" id="btnAddCust" style="flex-shrink:0">+ Add</button></div><div style="font-size:11px;color:var(--text-light);margin-bottom:4px">${S.selectedEssentials.size} item${S.selectedEssentials.size!==1?'s':''} selected</div><div class="btn-row"><button class="btn btn-outline" id="btnEssBack">${S.fromFinal?'← Back to Summary':'← Back'}</button><button class="btn btn-primary" id="btnEssNext" style="background:#1A5240;font-size:14px;box-shadow:0 2px 8px rgba(26,82,64,.25)">Next: Print &amp; Save →</button></div></div>`;}

/* FINAL — Step 1: AI Download */
function renderFinal(){
  if(S.finalStep==='docs') return renderFinalDocs();
  const aiDate=getAIQueryDate();
  return`<div class="card">
    <div style="text-align:center;font-size:40px;margin-bottom:10px">🤖</div>
    <div style="text-align:center;font-size:10px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--text-light);margin-bottom:4px">Step 1 of 2</div>
    <div class="card-title" style="text-align:center;margin-bottom:6px">Save Your AI Query Prompt to Your Phone</div>
    <div style="font-size:13px;color:var(--text-mid);text-align:center;line-height:1.6;margin-bottom:20px">A preloaded query you save to your phone now and use later — when something unexpected happens.</div>

    <div style="background:var(--green-light);border:2px solid #9EC8B4;border-radius:12px;padding:14px 16px;margin-bottom:12px">
      <div style="font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.07em;color:#1A5240;margin-bottom:8px">⬇ Step 1 — Do This Now</div>
      <div style="font-size:13px;font-weight:700;color:#1A5240;margin-bottom:6px">Download and save the query to your phone.</div>
      <div style="font-size:12px;color:#1A5240;line-height:1.65">Tap the button below. When the file opens, save it somewhere easy to find — your Home Screen, a folder called <strong>Emergency</strong>, or iCloud / Google Drive. That's all you need to do right now.</div>
    </div>

    <div style="background:var(--blue-light);border:2px solid #4A6FA5;border-radius:12px;padding:14px 16px;margin-bottom:18px">
      <div style="font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.07em;color:#2C4A6E;margin-bottom:8px">📋 Step 2 — When Something Happens (Later)</div>
      <div style="font-size:13px;font-weight:700;color:#2C4A6E;margin-bottom:6px">Open the saved file and attach it to an AI system.</div>
      <div style="font-size:12px;color:#2C3347;line-height:1.65;margin-bottom:10px">Open the query you saved on your phone. In a third-party AI system (e.g., ChatGPT, Claude, Gemini), <strong>attach the file</strong>, then add:</div>
      <div style="display:flex;flex-direction:column;gap:4px;margin-bottom:10px;padding-left:4px">
        <div style="display:flex;gap:7px;font-size:12px;color:#2C3347;line-height:1.55"><span style="color:#4A6FA5;flex-shrink:0">•</span><span>The unusual event or situation (e.g., "smell of smoke," "police activity," "power outage")</span></div>
        <div style="display:flex;gap:7px;font-size:12px;color:#2C3347;line-height:1.55"><span style="color:#4A6FA5;flex-shrink:0">•</span><span>Your location</span></div>
      </div>
      <div style="font-size:12px;color:#2C3347;line-height:1.65;margin-bottom:10px">Submit to generate an informational response. Outputs may vary by platform.</div>
      <div style="border-top:1px solid #BDD0E6;padding-top:10px;display:flex;flex-direction:column;gap:3px">
        <div style="display:flex;gap:7px;font-size:11px;color:#4A6FA5;line-height:1.5"><span style="flex-shrink:0">•</span><span>Informational use only — no advice, guidance, or recommendations</span></div>
        <div style="display:flex;gap:7px;font-size:11px;color:#4A6FA5;line-height:1.5"><span style="flex-shrink:0">•</span><span>Results depend on the AI system and available public data</span></div>
      </div>
    </div>
    <button class="btn btn-primary" id="btnDownloadAI" style="width:100%;font-size:15px;padding:14px;border-radius:12px;background:#2C4A6E;box-shadow:0 3px 12px rgba(44,74,110,.3);margin-bottom:10px">
      📱 Download AI Query Prompt to Phone
    </button>
    ${S.aiDownloaded?`<div style="background:var(--green-light);border:1.5px solid #9EC8B4;border-radius:9px;padding:9px 13px;font-size:12px;color:#1A5240;font-weight:600;text-align:center;margin-bottom:14px">✓ Downloaded — save it somewhere easy to find</div>`:`<div style="font-size:11px;color:var(--text-light);text-align:center;margin-bottom:14px">When the PDF opens, tap the share icon and choose <strong>Save to Files</strong> or <strong>Add to Home Screen</strong></div>`}
    <div style="border-top:1px solid var(--border);padding-top:14px;display:flex;align-items:center;justify-content:space-between;gap:10px">
      <div style="font-size:11px;color:var(--text-light)">Version: ${aiDate}</div>
      <button class="btn btn-primary" id="btnFinalAINext" style="background:#1A5240;box-shadow:0 2px 8px rgba(26,82,64,.25)">Next: Your Other Documents →</button>
    </div>
  </div>`;
}

/* FINAL — Step 2: Other 4 Docs */
function renderFinalDocs(){
  const today=new Date().toLocaleDateString("en-US",{month:"long",day:"numeric",year:"numeric"});
  const ol=getOrderedLocs(S.locations);
  const selCnt=S.selectedEssentials.size;
  const hasComm=S.commContacts.primary.name||S.commContacts.outOfTown.name;
  const docs=[
    {icon:'📍',label:'Location Scenarios',sub:`${ol.length} location${ol.length!==1?'s':''} · Prepared for ${esc(S.userName)}`,id:'btnRevSR'},
    {icon:'📋',label:'Communication Plan',sub:hasComm?'Partially filled in':'Print &amp; fill by hand',id:'btnRevComm'},
    {icon:'🎒',label:'Pre-Plan Essentials',sub:`${selCnt} item${selCnt!==1?'s':''} selected`,id:'btnRevEss'},
    {icon:'📊',label:'Disruption Insights',sub:'Representative examples of unusual events',id:'btnRevDisruption'},
  ];
  return`<div class="card">
    <div style="text-align:center;font-size:10px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--text-light);margin-bottom:4px">Step 2 of 2</div>
    <div class="card-title" style="text-align:center;margin-bottom:6px">Your Other Documents</div>
    <div style="font-size:13px;color:var(--text-mid);text-align:center;line-height:1.6;margin-bottom:18px">These 4 documents go in your Urban Resilience Guide. Choose how you'd like to save them.</div>
    <div style="display:flex;flex-direction:column;gap:8px;margin-bottom:20px">
      ${docs.map(d=>`<div style="border:1.5px solid var(--border);border-radius:10px;padding:11px 13px;display:flex;align-items:center;justify-content:space-between;gap:9px">
        <div style="display:flex;align-items:center;gap:9px">
          <span style="font-size:20px">${d.icon}</span>
          <div><div style="font-weight:700;font-size:13px">${d.label}</div><div style="font-size:11px;color:var(--text-mid);margin-top:1px">${d.sub}</div></div>
        </div>
        <button class="btn btn-outline btn-sm" id="${d.id}">View</button>
      </div>`).join('')}
    </div>
    <div style="background:#F7F9FC;border:1.5px solid var(--border);border-radius:12px;padding:16px;margin-bottom:18px">
      <div style="font-size:12px;font-weight:700;color:var(--text);margin-bottom:12px;text-align:center">How would you like to save these documents?</div>
      <div style="display:flex;flex-direction:column;gap:9px">
        <button class="btn btn-outline" id="btnDoPrint" style="justify-content:flex-start;gap:12px;padding:13px 16px;border-radius:11px">
          <span style="font-size:22px">🖨️</span>
          <div style="text-align:left"><div style="font-weight:700;font-size:13px">Print</div><div style="font-size:11px;color:var(--text-mid)">Send to printer — place in your Urban Resilience Guide</div></div>
        </button>
        <button class="btn btn-outline" id="btnDoDownload" style="justify-content:flex-start;gap:12px;padding:13px 16px;border-radius:11px">
          <span style="font-size:22px">📲</span>
          <div style="text-align:left"><div style="font-weight:700;font-size:13px">Download</div><div style="font-size:11px;color:var(--text-mid)">Save as Word Document to your phone or computer</div></div>
        </button>
        <button class="btn btn-primary" id="btnDoPrintAndDownload" style="justify-content:flex-start;gap:12px;padding:13px 16px;border-radius:11px;background:#2C4A6E;box-shadow:0 2px 8px rgba(44,74,110,.25)">
          <span style="font-size:22px">🖨️📲</span>
          <div style="text-align:left"><div style="font-weight:700;font-size:13px">Print &amp; Download</div><div style="font-size:11px;opacity:.8">Print for the Guide and save a digital copy</div></div>
        </button>
      </div>
    </div>
    ${S.docsActioned?(()=>{
      const msg=S.docsActionType==='download'
        ?'Your documents have been saved. You can print them at any time and place them in your Urban Resilience Guide.'
        :S.docsActionType==='both'
        ?'Print for your Urban Resilience Guide and keep the downloaded copy somewhere easy to find.'
        :'Place these documents in your Urban Resilience Guide and keep them accessible.';
      return`<div style="background:var(--green-light);border:2px solid #4A8570;border-radius:12px;padding:16px 18px;margin-bottom:14px;display:flex;align-items:center;justify-content:space-between;gap:12px;flex-wrap:wrap">
      <div style="display:flex;align-items:center;gap:10px">
        <span style="font-size:24px">✅</span>
        <div><div style="font-weight:700;font-size:13px;color:#1A5240">Documents ready!</div><div style="font-size:11px;color:#2D7A5C;margin-top:2px;line-height:1.5">${msg}</div></div>
      </div>
      <button class="btn" id="btnCloseAfterAction" style="background:#1A5240;color:white;font-size:13px;padding:10px 22px;border-radius:10px;font-weight:700;white-space:nowrap;box-shadow:0 2px 8px rgba(26,82,64,.3)">✕ Close</button>
    </div>`;})()
    :''}
    <div style="display:flex;gap:9px;justify-content:space-between;align-items:center">
      <button class="btn btn-outline" id="btnFinalDocsBack">← Back</button>
      ${!S.docsActioned?`<button class="btn btn-outline" id="btnCloseWindow" style="font-size:13px;padding:11px 24px;border-radius:11px;color:var(--text-mid)">✕ Close Window</button>`:''}
    </div>
  </div>`;
}
/* PRINT */
function brandBar(title=''){
  return`<div style="background:#2C4A6E;color:white;padding:7px 18px;font-size:10px;font-weight:700;letter-spacing:.07em;display:flex;align-items:center;justify-content:space-between;-webkit-print-color-adjust:exact;print-color-adjust:exact">
    <span>🛡️&nbsp; Safety Reserve — Urban Resilience Guide</span>
    <span style="opacity:.7;font-weight:400">${title}</span>
  </div>`;}

function buildAIQueryHTML(){const text=load(SK.aiQueryText,AI_QUERY_DEFAULT);const lines=text.split('\n');let html='';for(const line of lines){const t=line.trim();if(!t){html+='<div style="margin:3px 0"></div>';continue;}if(/^\d+\.\s+[A-Z]/.test(t)&&t.length<80){html+=`<div style="font-size:13px;font-weight:700;color:#2C4A6E;margin:12px 0 5px;padding-bottom:3px;border-bottom:1px solid #E8EAF0">${esc(t)}</div>`;}else if(t.startsWith('•')||t.startsWith('-')){html+=`<div style="display:flex;gap:8px;font-size:12px;color:#2C3347;line-height:1.6;margin-bottom:3px"><span style="color:#4A6FA5;flex-shrink:0">•</span><span>${esc(t.replace(/^[•\-]\s*/,''))}</span></div>`;}else if(/^[🛡️🧠📊🔴🟠🔵⏱️⚠️]/.test(t)){html+=`<div style="font-size:12px;font-weight:700;color:#2C4A6E;margin:8px 0 3px;background:#EAF0F9;padding:5px 9px;border-radius:6px">${esc(t)}</div>`;}else{html+=`<div style="font-size:12px;color:#2C3347;line-height:1.6;margin-bottom:3px">${esc(t)}</div>`;}}return html;}

function buildDisruptionInsightsHTML(){
  let text=getDisruptionHtml()||DISRUPTION_INSIGHTS_DEFAULT;
  if(text.startsWith('__HTML__:'))text=text.slice(9);
  /* If the stored content is HTML (user pasted HTML, same as AI Query approach) use it directly */
  if(/<[a-zA-Z]/.test(text))return text;
  /* Otherwise parse pipe format */
  const lines=text.split('\n');
  let html='';
  let inCard=false;
  const closeCard=()=>{if(inCard){html+='</div></div>';inCard=false;}};
  for(const line of lines){
    const t=line.trim();
    if(!t)continue;
    if(t.startsWith('TITLE|')){/* handled by parent */}
    else if(t.startsWith('INTRO|')){html+=`<p style="font-size:12px;color:#5A6270;line-height:1.65;margin-bottom:14px">${esc(t.slice(6))}</p>`;}
    else if(t.startsWith('CARD|')){
      closeCard();
      const parts=t.split('|');
      const icon=parts[1]||'';const title=parts[2]||'';const category=parts[3]||'';
      html+=`<div style="border:1.5px solid #DDE2EA;border-radius:9px;overflow:hidden;margin-bottom:11px"><div style="display:flex;align-items:center;gap:9px;padding:9px 13px;border-bottom:1.5px solid #DDE2EA;background:#F4F5F8;-webkit-print-color-adjust:exact;print-color-adjust:exact"><span style="font-size:17px;flex-shrink:0">${icon}</span><span style="font-size:13px;font-weight:700;color:#2C3347;flex:1">${esc(title)}</span><span style="font-size:9px;font-weight:700;color:#8E95A3;text-transform:uppercase;letter-spacing:.05em;white-space:nowrap">${esc(category)}</span></div><div style="padding:9px 13px 5px">`;
      inCard=true;
    }
    else if(t.startsWith('SUBHEAD|')){html+=`<div style="font-size:11px;font-weight:700;color:#2C3347;margin:5px 0 2px">${esc(t.slice(8))}</div>`;}
    else if(t.startsWith('BULLET|')){html+=`<div style="display:flex;gap:7px;font-size:11.5px;color:#2C3347;line-height:1.55;margin-bottom:5px;padding-left:2px"><span style="color:#4A6FA5;flex-shrink:0;margin-top:1px">\u2013</span><span>${esc(t.slice(7))}</span></div>`;}
    else if(t.startsWith('CALLOUT|')){
      const cp=t.split('|');
      html+=`<div style="background:#EAF0F9;border-left:3px solid #4A6FA5;border-radius:0 6px 6px 0;padding:8px 11px;margin:6px 0 2px;-webkit-print-color-adjust:exact;print-color-adjust:exact"><span style="font-size:11px;font-weight:700;color:#2C4A6E">${esc(cp[1]||'')}</span><span style="font-size:11px;color:#2C4A6E;line-height:1.55"> ${esc(cp[2]||'')}</span></div>`;
    }
    else if(t.startsWith('DIVIDER|')){
      closeCard();
      html+=`<div style="margin:15px 0 10px;padding-bottom:5px;border-bottom:1.5px solid #E0E3EA"><span style="font-size:11px;font-weight:700;color:#8E95A3;text-transform:uppercase;letter-spacing:.07em">${esc(t.slice(8))}</span></div>`;
    }
    else if(t.startsWith('FOOTER|')){
      closeCard();
      html+=`<div style="background:#F7F9FC;border:1px solid #E8EAF0;border-radius:8px;padding:10px 13px;margin-top:12px;font-size:10px;color:#5A6270;line-height:1.65"><strong>About this guide</strong><br>${esc(t.slice(7))}</div>`;
    }
  }
  closeCard();
  return html;
}

function showPrintStatus(cb){
  const overlay=document.createElement('div');
  overlay.className='print-overlay';
  const docs=[
    {icon:'📍',label:'Location Scenarios — Based on Your Inputs'},
    {icon:'📋',label:'Communication Plan'},
    {icon:'🎒',label:'Pre-Plan Essentials'},
    {icon:'📊',label:'Disruption Insights (Selected Examples)'}
  ];
  overlay.innerHTML=`<div class="print-modal">
    <div class="print-modal-title">Preparing Your Documents</div>
    <div class="print-modal-sub">The following pages are included:</div>
    ${docs.map((d,i)=>`<div class="print-doc-row" id="pdrow${i}" style="opacity:0;transition:opacity .25s ease">
      <span class="pd-icon">${d.icon}</span>
      <span style="flex:1">${d.label}</span>
      <span class="pd-check" id="pdcheck${i}" style="opacity:0;transition:opacity .2s ease">✓</span>
    </div>`).join('')}
    <div style="margin-top:14px">
      <div style="height:5px;background:var(--border);border-radius:3px;overflow:hidden">
        <div id="pPBar" style="height:100%;width:0%;background:linear-gradient(90deg,var(--blue),var(--green));border-radius:3px;transition:width .4s ease"></div>
      </div>
      <div id="pPLbl" style="font-size:11px;color:var(--text-light);text-align:center;margin-top:7px">Starting…</div>
    </div>
    <div style="margin-top:10px;font-size:11px;color:var(--text-mid);text-align:center;font-style:italic;border-top:1px solid var(--border);padding-top:10px">📋 Place in your Urban Resilience Guide</div>
  </div>`;
  document.body.appendChild(overlay);
  const n=docs.length;
  docs.forEach((_,i)=>{
    setTimeout(()=>{
      const r=document.getElementById('pdrow'+i);if(r)r.style.opacity='1';
      setTimeout(()=>{
        const c=document.getElementById('pdcheck'+i);if(c)c.style.opacity='1';
        const b=document.getElementById('pPBar');if(b)b.style.width=Math.round(((i+1)/n)*85)+'%';
        const l=document.getElementById('pPLbl');
        if(l)l.textContent=i<n-1?`Preparing document ${i+2} of ${n}…`:'Almost ready…';
      },260);
    },i*340);
  });
  setTimeout(()=>{
    const b=document.getElementById('pPBar');if(b)b.style.width='100%';
    const l=document.getElementById('pPLbl');if(l)l.textContent='Opening…';
  },n*340+180);
  setTimeout(()=>{document.body.removeChild(overlay);cb();},n*340+650);
}

/* Build the 4-doc HTML block (no AI) */
function build4DocsHtml(){
  let _disruptionBody='';
  try{_disruptionBody=buildDisruptionInsightsHTML();}catch(e){_disruptionBody='';}
  if(!_disruptionBody||_disruptionBody.trim().length<50){
    try{
      const _raw=DISRUPTION_INSIGHTS_DEFAULT;
      _disruptionBody=_raw.split('\n').filter(l=>l.trim()&&!l.startsWith('TITLE|')).map(l=>`<p style="font-size:12px;color:#2C3347;line-height:1.65;margin-bottom:6px">${esc(l.replace(/^[A-Z]+\|/,''))}</p>`).join('');
    }catch(e){_disruptionBody='<p style="font-size:12px;color:#8E95A3">Content unavailable.</p>';}
  }
  const ol=getOrderedLocs(S.locations);const pad=[...ol];while(pad.length<6)pad.push(null);
  const today=new Date().toLocaleDateString("en-US",{month:"long",day:"numeric",year:"numeric"});
  const cc=S.commContacts;const allEss=[...DEFAULT_ESSENTIALS,...S.customEssentials];
  const _brand=(t)=>brandBar(t);
  const srHtml=`<div style="page-break-after:always;zoom:0.78"><style>@media print{@page{margin:0.15in}}</style>${_brand('Location Scenarios')}<div style="background:#FFF8ED;border-bottom:1px solid #EED97A;padding:8px 18px"><p style="font-size:11px;color:#7A5C00;line-height:1.5"><strong>Note:</strong> General reference only. Conditions change rapidly during emergencies.</p></div><div style="padding:13px 18px 10px;border-bottom:2px solid #F0F1F4;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:6px"><div><div style="font-family:'DM Serif Display',serif;font-size:19px;color:#2C3347;line-height:1.2">Location Scenarios — Based on Your Inputs</div><div style="font-size:12px;color:#5A6270;margin-top:3px;font-weight:600">Possible options and associated considerations</div><div style="font-size:11px;color:#8E95A3;margin-top:2px">Prepared for: <strong>${esc(S.userName)}</strong> · ${today}</div></div></div><div style="display:grid;grid-template-columns:repeat(2,1fr)">${pad.map(l=>renderLocBlock(l)).join('')}</div><div style="padding:10px 18px;background:#F8F9FC;border-top:1px solid #E8EAF0"><p style="font-size:10px;color:#5A6270">You decide what is appropriate. This page is for reference only.</p></div></div>`;
  const commHtml=`<div style="page-break-after:always;max-width:700px">${_brand('Communication Plan')}<div style="padding:16px 18px"><h1 style="font-family:'DM Serif Display',serif;font-size:22px;color:#2C3347;margin-bottom:4px">Communication Plan</h1><p style="font-size:11px;color:#8E95A3;margin-bottom:16px">Last updated: ${today}</p><div style="background:#FFFBEE;border:1.5px solid #E0C55A;border-radius:8px;padding:9px 13px;margin-bottom:16px;font-size:12px;color:#6A5100"><strong>💡 Tip:</strong> When networks are jammed, texting usually gets through faster than a voice call.</div><table style="width:100%;border-collapse:collapse"><tr><td style="padding:10px;border:1px solid #DDE2EA;background:#F7F9FC;font-weight:700;font-size:11px;width:38%">🚨 Emergency Services</td><td style="padding:10px;border:1px solid #DDE2EA;font-size:17px;font-weight:700">911</td></tr><tr><td style="padding:10px;border:1px solid #DDE2EA;background:#F7F9FC;font-weight:600;font-size:11px">📞 Primary Contact</td><td style="padding:10px;border:1px solid #DDE2EA;font-size:13px">${esc(cc.primary.name)||'___________________'} &nbsp;·&nbsp; ${esc(cc.primary.phone)||'___________________'}</td></tr><tr><td style="padding:10px;border:1px solid #DDE2EA;background:#F7F9FC;vertical-align:top"><div style="font-weight:600;font-size:11px">🌐 Out-of-Town Hub Contact</div><div style="font-size:10px;color:#8E95A3;margin-top:2px;line-height:1.4">Everyone checks in with this person outside the affected area.</div></td><td style="padding:10px;border:1px solid #DDE2EA;font-size:13px">${esc(cc.outOfTown.name)||'___________________'} &nbsp;·&nbsp; ${esc(cc.outOfTown.phone)||'___________________'}</td></tr><tr><td style="padding:10px;border:1px solid #DDE2EA;background:#F7F9FC;font-weight:600;font-size:11px">🤝 Local Friend</td><td style="padding:10px;border:1px solid #DDE2EA;font-size:13px">${esc(cc.localFriend.name)||'___________________'} &nbsp;·&nbsp; ${esc(cc.localFriend.phone)||'___________________'}</td></tr><tr><td style="padding:10px;border:1px solid #DDE2EA;background:#F7F9FC;font-weight:600;font-size:11px">📱 Group Text</td><td style="padding:10px;border:1px solid #DDE2EA;font-size:13px">${esc(S.commGroup)||'___________________'}</td></tr></table></div></div>`;
  const essHtml=`<div style="page-break-after:always;max-width:700px">${_brand('Pre-Plan Essentials')}<div style="padding:16px 18px"><h1 style="font-family:'DM Serif Display',serif;font-size:22px;color:#2C3347;margin-bottom:4px">Pre-Plan Your Essentials</h1><p style="font-size:11px;color:#8E95A3;margin-bottom:4px">Highlight items you may take if time and conditions allow.</p><p style="font-size:11px;color:#2C3347;margin-bottom:16px">${esc(S.userName)} · ${today}</p><div style="display:grid;grid-template-columns:repeat(2,1fr);gap:7px">${allEss.map(item=>{const sel=S.selectedEssentials.has(item);return`<div style="padding:9px 11px;border:1.5px solid ${sel?'#C8AA00':'#DDE2EA'};border-radius:8px;background:${sel?'#FFF9C2':'white'};font-size:12px;font-weight:600;color:${sel?'#5A4700':'#2C3347'};display:flex;align-items:center;gap:6px;-webkit-print-color-adjust:exact;print-color-adjust:exact"><span>${sel?'⭐':'○'}</span>${esc(item)}</div>`;}).join('')}</div></div></div>`;
  const disruptionHtml=`<div style="max-width:700px">${_brand('Disruption Insights')}<div style="padding:16px 18px"><h1 style="font-family:'DM Serif Display',serif;font-size:22px;color:#2C3347;margin-bottom:3px">Disruption Insights (Selected Examples)</h1><p style="font-size:12px;color:#8E95A3;margin-bottom:14px">Representative examples of unusual events</p>${_disruptionBody}</div></div>`;
  return{srHtml,commHtml,essHtml,disruptionHtml};
}

/* Download AI Analysis — saves as .doc (Word-compatible) so all AI engines accept it */
function doDownloadAI(){
  const aiDate=getAIQueryDate();
  // Build plain-text body from the AI query text for maximum compatibility
  const rawText=load(SK.aiQueryText,AI_QUERY_DEFAULT);
  const textBody=rawText.split('\n').map(line=>{
    const t=line.trim();
    if(!t)return'<w:p><w:pPr><w:spacing w:after="0"/></w:pPr></w:p>';
    const isHeading=/^\d+\.\s+[A-Z]/.test(t)&&t.length<80;
    const isBullet=t.startsWith('•')||t.startsWith('-');
    const text=t.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;');
    if(isHeading)return`<w:p><w:pPr><w:pStyle w:val="Heading2"/><w:spacing w:before="200" w:after="80"/></w:pPr><w:r><w:rPr><w:b/><w:color w:val="2C4A6E"/></w:rPr><w:t xml:space="preserve">${text}</w:t></w:r></w:p>`;
    if(isBullet)return`<w:p><w:pPr><w:ind w:left="360"/><w:spacing w:after="60"/></w:pPr><w:r><w:t xml:space="preserve">• ${text.replace(/^[•\-]\s*/,'')}</w:t></w:r></w:p>`;
    return`<w:p><w:pPr><w:spacing w:after="80"/></w:pPr><w:r><w:t xml:space="preserve">${text}</w:t></w:r></w:p>`;
  }).join('');
  const docxml=`<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<?mso-application progid="Word.Document"?>
<w:wordDocument xmlns:w="http://schemas.microsoft.com/office/word/2003/wordml"
  xmlns:wx="http://schemas.microsoft.com/office/word/2003/auxHint"
  xmlns:r="http://schemas.openxmlformats.org/officeDocument/2006/relationships">
<w:body>
<w:p><w:pPr><w:spacing w:after="40"/></w:pPr>
  <w:r><w:rPr><w:b/><w:sz w:val="32"/><w:color w:val="2C4A6E"/></w:rPr><w:t>AI Real Time Situational Analysis</w:t></w:r>
</w:p>
<w:p><w:pPr><w:spacing w:after="40"/></w:pPr>
  <w:r><w:rPr><w:sz w:val="20"/><w:color w:val="8E95A3"/></w:rPr><w:t>Version: ${aiDate} · Prepared for: ${esc(S.userName)}</w:t></w:r>
</w:p>
<w:p><w:pPr><w:spacing w:after="40"/></w:pPr>
  <w:r><w:rPr><w:sz w:val="20"/><w:color w:val="6A5100"/></w:rPr><w:t>IMPORTANT: This template is for informational use only. Not an emergency service. Always follow official authorities.</w:t></w:r>
</w:p>
<w:p><w:pPr><w:spacing w:after="120"/></w:pPr><w:r><w:t></w:t></w:r></w:p>
${textBody}
</w:body></w:wordDocument>`;
  const blob=new Blob([docxml],{type:'application/msword'});
  const url=URL.createObjectURL(blob);
  const a=document.createElement('a');
  a.href=url;
  a.download=`ai-query-prompt-${(S.userName||'safety').replace(/\s+/g,'-').toLowerCase()}.doc`;
  document.body.appendChild(a);a.click();document.body.removeChild(a);
  setTimeout(()=>URL.revokeObjectURL(url),3000);
  S.aiDownloaded=true;render();
}

/* Shared print CSS injected into every popup window */
const PRINT_CSS=`*{box-sizing:border-box;margin:0;padding:0;-webkit-print-color-adjust:exact!important;print-color-adjust:exact!important;color-adjust:exact!important}body{font-family:'Sora',sans-serif;background:white}@page{margin:0.5in;size:letter portrait}.page-section{page-break-after:always;page-break-inside:avoid}.page-section:last-child{page-break-after:auto}`;

/* Wrap each doc in a page-section div so print breaks work reliably */
function wrapSection(html){return`<div class="page-section">${html}</div>`;}

/* Print 4 docs — each section on its own page */
function doPrintAll(){
  const {srHtml,commHtml,essHtml,disruptionHtml}=build4DocsHtml();
  showPrintStatus(()=>{
    const w=window.open('','_blank','width=1000,height=800');
    if(!w){alert('Pop-up blocked. Please allow pop-ups for this site and try again.');return;}
    w.document.write(`<!DOCTYPE html><html><head><meta charset="UTF-8"><title>Safety Reserve — ${esc(S.userName)}</title><link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=DM+Serif+Display&display=swap" rel="stylesheet"><style>${PRINT_CSS}</style></head><body>${wrapSection(srHtml)}${wrapSection(commHtml)}${wrapSection(essHtml)}${wrapSection(disruptionHtml)}<script>window.onload=function(){window.print();}<\/script></body></html>`);
    w.document.close();
    S.docsActioned=true;S.docsActionType='print';render();
  });
}

/* Download 4 docs as .doc (Word-compatible) with proper page breaks */
function doDownloadDocs(){
  const {srHtml,commHtml,essHtml,disruptionHtml}=build4DocsHtml();
  showPrintStatus(()=>{
    // Use mso-page-break-before for Word page breaks + standard CSS for browsers
    const pageBreak='<div style="page-break-before:always;mso-page-break-before:always"></div>';
    const wordHtml=`<!DOCTYPE html><html xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:w="urn:schemas-microsoft-com:office:word" xmlns="http://www.w3.org/TR/REC-html40"><head><meta charset="UTF-8"><meta name="ProgId" content="Word.Document"><meta name="Generator" content="Safety Reserve"><title>Safety Reserve — ${esc(S.userName)}</title><link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=DM+Serif+Display&display=swap" rel="stylesheet"><!--[if gte mso 9]><xml><w:WordDocument><w:View>Print</w:View><w:Zoom>90</w:Zoom></w:WordDocument></xml><![endif]--><style>${PRINT_CSS} body{padding:0}</style></head><body>${srHtml}${pageBreak}${commHtml}${pageBreak}${essHtml}${pageBreak}${disruptionHtml}</body></html>`;
    const blob=new Blob(['\ufeff'+wordHtml],{type:'application/msword'});
    const url=URL.createObjectURL(blob);
    const a=document.createElement('a');
    a.href=url;
    a.download=`safety-reserve-${(S.userName||'kit').replace(/\s+/g,'-').toLowerCase()}.doc`;
    document.body.appendChild(a);a.click();document.body.removeChild(a);
    setTimeout(()=>URL.revokeObjectURL(url),3000);
    S.docsActioned=true;S.docsActionType='download';render();
  });
}

/* Print & Download — open print window AND trigger download */
function doPrintAndDownloadDocs(){
  const {srHtml,commHtml,essHtml,disruptionHtml}=build4DocsHtml();
  showPrintStatus(()=>{
    // Open print window
    const w=window.open('','_blank','width=1000,height=800');
    if(!w){alert('Pop-up blocked. Please allow pop-ups for this site and try again.');return;}
    w.document.write(`<!DOCTYPE html><html><head><meta charset="UTF-8"><title>Safety Reserve — ${esc(S.userName)}</title><link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=DM+Serif+Display&display=swap" rel="stylesheet"><style>${PRINT_CSS}</style></head><body>${wrapSection(srHtml)}${wrapSection(commHtml)}${wrapSection(essHtml)}${wrapSection(disruptionHtml)}<script>window.onload=function(){window.print();}<\/script></body></html>`);
    w.document.close();
    // Also trigger download
    const pageBreak='<div style="page-break-before:always;mso-page-break-before:always"></div>';
    const wordHtml=`<!DOCTYPE html><html xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:w="urn:schemas-microsoft-com:office:word" xmlns="http://www.w3.org/TR/REC-html40"><head><meta charset="UTF-8"><meta name="ProgId" content="Word.Document"><meta name="Generator" content="Safety Reserve"><title>Safety Reserve — ${esc(S.userName)}</title><!--[if gte mso 9]><xml><w:WordDocument><w:View>Print</w:View></w:WordDocument></xml><![endif]--><style>${PRINT_CSS} body{padding:0}</style></head><body>${srHtml}${pageBreak}${commHtml}${pageBreak}${essHtml}${pageBreak}${disruptionHtml}</body></html>`;
    const blob=new Blob(['\ufeff'+wordHtml],{type:'application/msword'});
    const url=URL.createObjectURL(blob);
    const a=document.createElement('a');
    a.href=url;
    a.download=`safety-reserve-${(S.userName||'kit').replace(/\s+/g,'-').toLowerCase()}.doc`;
    document.body.appendChild(a);a.click();document.body.removeChild(a);
    setTimeout(()=>URL.revokeObjectURL(url),3000);
    S.docsActioned=true;S.docsActionType='both';render();
  });
}

function showCloseFallback(){
  const msg=document.createElement('div');
  msg.style.cssText='position:fixed;inset:0;background:rgba(44,51,71,.7);z-index:9999;display:flex;align-items:center;justify-content:center;padding:24px;backdrop-filter:blur(4px)';
  msg.innerHTML='<div style="background:white;border-radius:16px;padding:32px 28px;max-width:380px;width:100%;text-align:center;box-shadow:0 8px 40px rgba(44,51,71,.25)">'
    +'<div style="font-size:52px;margin-bottom:14px">🛡️</div>'
    +'<div style="font-family:DM Serif Display,serif;font-size:24px;color:#2C4A6E;margin-bottom:8px">Safety Always.</div>'
    +'<div style="font-size:13px;color:#5A6270;line-height:1.7;margin-bottom:22px">Your documents are ready. Place them in your Urban Resilience Guide.<br><br>You can now close this tab.</div>'
    +'<div style="font-size:11px;color:#8E95A3;">You can reopen this app anytime on this device — your session is saved.</div>'
    +'</div>';
  document.body.appendChild(msg);
  msg.addEventListener('click',function(e){if(e.target===msg)document.body.removeChild(msg);});
}

/* =============================================================
   EVENT HANDLERS
   ============================================================= */
function bc(id,fn){const el=document.getElementById(id);if(el)el.addEventListener('click',fn);}
function bi(id,fn,ev='input'){const el=document.getElementById(id);if(el)el.addEventListener(ev,()=>fn(el.value));}

/* =============================================================
   DEBOUNCED RENDER — prevents full re-render on every keystroke
   ============================================================= */
let _renderTimer=null;
function debouncedRender(delay=280){clearTimeout(_renderTimer);_renderTimer=setTimeout(render,delay);}

function attachHandlers(){
  /* ADMIN */
  document.querySelectorAll('[data-tab]').forEach(el=>el.addEventListener('click',()=>{S.adminTab=el.dataset.tab;S.adminSaveMsg='';S.adminLoginErr='';render();}));
  bc('btnAdminClose',()=>{S.showAdmin=false;S.adminAuthed=false;if(window.location.hash==='#admin')history.replaceState(null,'',window.location.pathname);render();});
  bc('btnAdminLogin',()=>{const pw=document.getElementById('adminPwInput')?.value||'';if(pw===getAdminPass()){S.adminAuthed=true;S.adminLoginErr='';render();}else{S.adminLoginErr='Incorrect password. Please try again.';render();}});
  const apiInput=document.getElementById('adminPwInput');
  if(apiInput)apiInput.addEventListener('keydown',e=>{if(e.key==='Enter')document.getElementById('btnAdminLogin')?.click();});
  bc('btnSaveWelcome',()=>{const a=document.getElementById('adminWelcomeArea');if(a){store(SK.welcomeHtml,a.value);S.adminSaveMsg='Welcome page saved successfully.';render();}});
  bc('btnResetWelcome',()=>{store(SK.welcomeHtml,WELCOME_DEFAULT);S.adminSaveMsg='Welcome page reset to default.';render();});
  bc('btnSaveSafety',()=>{const a=document.getElementById('adminSafetyArea');if(a){store(SK.safetyText,a.value);S.adminSaveMsg='Safety content saved successfully.';render();}});
  bc('btnResetSafety',()=>{store(SK.safetyText,SAFETY_DEFAULT);S.adminSaveMsg='Safety content reset to default.';render();});
  bc('btnSaveAIQuery',()=>{const a=document.getElementById('adminAIQueryArea');const d=document.getElementById('adminAIDateInput');if(a){store(SK.aiQueryText,a.value);if(d)store(SK.aiQueryDate,d.value);S.adminSaveMsg='AI Real-Time document saved.';render();}});
  bc('btnResetAIQuery',()=>{store(SK.aiQueryText,AI_QUERY_DEFAULT);store(SK.aiQueryDate,AI_QUERY_DATE_DEFAULT);S.adminSaveMsg='AI Query reset to default.';render();});
  bc('btnSaveTos',()=>{const a=document.getElementById('adminTosInput');if(a){store(SK.tosUrl,a.value);S.adminSaveMsg='Terms of Service URL saved.';render();}});
  bc('btnChangePassword',()=>{
    const cur=document.getElementById('adminPwCurrent')?.value||'';
    const nw=document.getElementById('adminPwNew')?.value||'';
    const conf=document.getElementById('adminPwConfirm')?.value||'';
    if(cur!==getAdminPass()){S.adminLoginErr='Current password is incorrect.';render();return;}
    const pwErr=isStrongPassword(nw);
    if(pwErr){S.adminLoginErr=pwErr;render();return;}
    if(nw!==conf){S.adminLoginErr='New passwords do not match.';render();return;}
    store(SK.adminPass,nw);S.adminLoginErr='';S.adminSaveMsg='Password changed successfully.';render();
  });
  bc('btnClearRecords',()=>{if(confirm('Are you sure you want to delete ALL registration and legal records? This cannot be undone.')){store(SK.registrations,[]);store(SK.legalRecords,[]);S.adminSaveMsg='All records cleared.';render();}});

  /* RECORDS SEARCH + DOWNLOAD */
  bc('recordsSearchInput',undefined);
  const _rsi=document.getElementById('recordsSearchInput');
  if(_rsi)_rsi.addEventListener('input',()=>{S.recordsSearch=_rsi.value;render();});
  bc('btnDownloadRegs',()=>{const regs=loadJson(SK.registrations,[]);downloadRecordsCSV(regs,'registrations.csv');});
  bc('btnDownloadLegal',()=>{const legal=loadJson(SK.legalRecords,[]);downloadRecordsCSV(legal,'legal_acceptances.csv');});

  /* DISRUPTION INSIGHTS */
  bc('btnSaveDisruption',()=>{const a=document.getElementById('adminDisruptionArea');if(a){store(SK.disruptionInsights,a.value);S.adminSaveMsg='Disruption Insights saved.';render();}});
  bc('btnResetDisruption',()=>{store(SK.disruptionInsights,DISRUPTION_INSIGHTS_DEFAULT);S.adminSaveMsg='Disruption Insights reset to default.';render();});
  /* File upload for disruption */
  bc('btnPickDisruptionFile',()=>{const fi=document.getElementById('disruptionFileInput');if(fi)fi.click();});
  const _dfi=document.getElementById('disruptionFileInput');
  if(_dfi)_dfi.addEventListener('change',function(){
    const file=this.files[0];if(!file)return;
    const nameEl=document.getElementById('disruptionFileName');
    if(nameEl)nameEl.textContent=file.name;
    const reader=new FileReader();
    reader.onload=function(e){
      const raw=e.target.result;
      if(file.name.match(/\.html?$/i)){
        /* HTML file: extract body content and store as raw HTML for direct use */
        const tmp=document.createElement('div');
        tmp.innerHTML=raw;
        const body=tmp.querySelector('body');
        const htmlContent='__HTML__:'+(body?body.innerHTML:raw);
        store(SK.disruptionInsights,htmlContent);
        S.adminSaveMsg='HTML file loaded and saved: '+file.name;
      } else {
        /* Text pipe-format: put into textarea and save */
        const ta=document.getElementById('adminDisruptionArea');
        if(ta)ta.value=raw;
        store(SK.disruptionInsights,raw);
        S.adminSaveMsg='Text file loaded and saved: '+file.name;
      }
      render();
    };
    reader.readAsText(file);
  });

  /* RECOVERY KEY */
  bc('btnRecoverPassword',()=>{
    const rk=(document.getElementById('adminRecoveryInput')?.value||'').trim();
    const np=document.getElementById('adminRecoveryNewPw')?.value||'';
    if(rk!==getRecoveryKey()){S.recoveryErr='Recovery key incorrect.';render();return;}
    const err=isStrongPassword(np);
    if(err){S.recoveryErr=err;render();return;}
    store(SK.adminPass,np);S.recoveryErr='';S.adminSaveMsg='Password reset via recovery key.';render();
  });

  /* FINAL SCREEN */
  bc('btnCloseWindow',()=>{
    window.close();
    setTimeout(()=>{
      const btn=document.getElementById('btnCloseWindow');
      if(btn&&document.body){showCloseFallback();}
    },400);
  });
  bc('btnCloseAfterAction',()=>{
    window.close();
    setTimeout(()=>{
      const btn=document.getElementById('btnCloseAfterAction');
      if(btn&&document.body){showCloseFallback();}
    },400);
  });

  /* DISRUPTION INSIGHTS view button */
  bc('btnRevAI',()=>{S.showAIView=true;render();});
  bc('btnRevDisruption',()=>{S.showDisruptionView=true;render();});

  /* RESUME / PAUSED */
  bc('btnResumeApp',()=>{S.appPaused=false;render();});
  // FIX 4: Validate activation code before allowing resume
  bi('resumeCode',v=>{S.resumeCodeInput=v.toUpperCase();S.resumeCodeErr='';render();});
  const rcEl=document.getElementById('resumeCode');
  if(rcEl)rcEl.addEventListener('keydown',e=>{if(e.key==='Enter')document.getElementById('btnResumeSession')?.click();});
  bc('btnResumeSession',()=>{
    const entered=(S.resumeCodeInput||'').trim().toUpperCase();
    const saved=(S.activationCode||'').trim().toUpperCase();
    if(!entered){S.resumeCodeErr='Please enter your activation code.';render();return;}
    if(entered!==saved){S.resumeCodeErr='Incorrect code. Please check and try again.';render();return;}
    S.resumeCodeErr='';loadSavedMainState();S.appFlow='main';render();
  });
  bc('btnStartFresh',()=>{if(confirm('This will clear your saved progress and start over. Are you sure?')){localStorage.removeItem(SK.session);localStorage.removeItem(SK.mainState);Object.assign(S,{appFlow:'activation',activationCode:'',userFullName:'',userEmail:'',legalAccepted:false,phase:1,srStep:'welcome',userName:'',locations:[{id:'H',type:'H',displayLabel:'Home',travelMinutes:0}],selectedEssentials:new Set(),customEssentials:[],errors:{},collAns:{},resumeCodeInput:'',resumeCodeErr:''});render();}});
  bc('btnStopApp',()=>{S.appPaused=true;saveMainState();render();});

  /* PRE-FLOW */
  bi('activationCode',v=>{S.activationCode=v.toUpperCase();S.activationErr='';render();});
  const actEl=document.getElementById('activationCode');if(actEl)actEl.addEventListener('keydown',e=>{if(e.key==='Enter')handleActivateNext();});
  bc('btnActivateNext',handleActivateNext);
  bi('regFullName',v=>{S.userFullName=v;});
  bi('regEmail',v=>{S.userEmail=v;});
  bc('btnConfirmBack',()=>{S.appFlow='activation';render();});
  bc('btnConfirmNext',handleConfirmNext);
  bc('legalCheckRow',()=>{S.legalAccepted=!S.legalAccepted;S.legalErr='';render();});
  bc('btnSafetyBack',()=>{S.appFlow='confirm';render();});
  bc('btnSafetyNext',handleSafetyNext);
  bc('btnWelcomeStart',()=>{S.appFlow='main';saveSession();render();});

  /* MAIN APP */
  bi('userName',v=>{S.userName=v;const btn=document.getElementById('btnWelNext');if(btn)btn.disabled=!v.trim();});
  bc('btnWelNext',()=>{if(S.userName.trim()){S.srStep='work_school';render();}});
  document.querySelectorAll('[data-ws]').forEach(el=>el.addEventListener('click',()=>{S.wsChoice=el.dataset.ws;S.errors={};render();}));
  document.querySelectorAll('[data-wgi]').forEach(el=>el.addEventListener('click',()=>{S.workGoesIn=el.dataset.wgi==='true';render();}));
  document.querySelectorAll('[data-sgi]').forEach(el=>el.addEventListener('click',()=>{S.schoolGoesIn=el.dataset.sgi==='true';render();}));
  bi('workName',v=>{S.workName=v;});
  bi('workMins',v=>{S.workMins=v;S.workMinsConf=false;debouncedRender();});
  bi('schoolName',v=>{S.schoolName=v;});
  bi('schoolMins',v=>{S.schoolMins=v;S.schoolMinsConf=false;debouncedRender();});
  bc('btnWsBack',()=>{S.srStep='welcome';render();});
  bc('btnWsNext',handleWsNext);
  document.querySelectorAll('[data-conf-mins]').forEach(el=>el.addEventListener('click',()=>{const p=el.dataset.confMins;if(p==='work')S.workMinsConf=true;else if(p==='school')S.schoolMinsConf=true;else if(p==='friend')S.friendMinsConf=true;else if(p==='pub')S.pubMinsConf=true;render();}));
  document.querySelectorAll('[data-sw-hrs]').forEach(el=>el.addEventListener('click',()=>{const p=el.dataset.swHrs,h=el.dataset.hrs;if(p==='work'){S.workMins=h;S.workMinsConf=true;}else if(p==='school'){S.schoolMins=h;S.schoolMinsConf=true;}else if(p==='friend'){S.friendMins=h;S.friendMinsConf=true;}else if(p==='pub'){S.pubMins=h;S.pubMinsConf=true;}render();}));
  bi('fRel',v=>{S.friendRel=v;render();},'change');
  bi('fName',v=>{S.friendName=v;});bi('fMins',v=>{S.friendMins=v;S.friendMinsConf=false;debouncedRender();});bi('fCity',v=>{S.friendCity=v;});bi('fState',v=>{S.friendState=v.toUpperCase();});
  bc('btnAddFriend',handleAddFriend);
  bc('btnFrBack',()=>{S.srStep='work_school';render();});
  bc('btnFrNext',()=>{S.srStep='public_loc';render();});
  document.querySelectorAll('[data-rm]').forEach(el=>el.addEventListener('click',()=>{const id=el.dataset.rm;if(id==='H')return;S.locations=S.locations.filter(l=>l.id!==id);render();}));
  document.querySelectorAll('[data-pt]').forEach(el=>el.addEventListener('click',()=>{S.pubType=el.dataset.pt;render();}));
  bi('bldType',v=>{S.buildingType=v;},'change');
  bi('pubMins',v=>{S.pubMins=v;S.pubMinsConf=false;debouncedRender();});
  bc('btnPubBack',()=>{S.srStep='friends';render();});
  bc('btnPubNext',handlePublicNext);
  /* FIX: Review back goes to friends, not public_loc */
  bc('btnRevBack',()=>{S.srStep='friends';render();});
  bc('btnRevNext',()=>{const ok=S.locations.some(l=>["FR","FM"].includes(l.type)&&l.travelMinutes>=60);if(!ok){S.errors.dist="Need 1 friend/family 1+ hr away";render();return;}S.errors={};S.qIndex=0;S.collAns={};S.srStep='questionnaire';render();});
  document.querySelectorAll('[data-qo]').forEach(el=>el.addEventListener('click',()=>{const opt=decodeURIComponent(el.dataset.qo);const allQs=buildQList(getOrderedLocs(S.locations));const q=allQs[S.qIndex];if(q.type==='global'){S.globalAns={...S.globalAns,[q.key]:opt};advQ(S.globalAns);}else{S.locAns={...S.locAns,[q.locId]:{...(S.locAns[q.locId]||{}),[q.key]:opt}};advQ(S.globalAns);}}));
  document.querySelectorAll('[data-cl]').forEach(el=>el.addEventListener('click',()=>{S.collAns={...S.collAns,[el.dataset.cl]:decodeURIComponent(el.dataset.co)};render();}));
  bc('btnCollNext',()=>{const allQs=buildQList(getOrderedLocs(S.locations));const q=allQs[S.qIndex];for(const[id,ans]of Object.entries(S.collAns)){S.locAns={...S.locAns,[id]:{...(S.locAns[id]||{}),[q.key]:ans}};}S.collAns={};advQ(S.globalAns);});
  bc('btnQBack',()=>{if(S.qIndex>0){S.qIndex--;S.collAns={};render();}});
  bc('btnSROBack',()=>{S.srStep='review';render();});
  bc('btnDisruptionBack',()=>{S.showDisruptionView=false;S.phase=4;render();});
  bc('btnAIViewBack',()=>{S.showAIView=false;S.phase=4;render();});
  bc('btnSRContinue',()=>{if(S.fromFinal){S.fromFinal=false;S.phase=4;render();}else{S.phase=2;render();}});
  document.querySelectorAll('.comm-input,.comm-phone').forEach(el=>{['input','change'].forEach(ev=>el.addEventListener(ev,()=>{const k=el.dataset.ck,f=el.dataset.cf;S.commContacts[k][f]=el.value;if(f==='phone'){const err=validatePhone(el.value);S.commPhoneErrs={...S.commPhoneErrs,[k]:err};debouncedRender(600);}else{/* name: just save, no re-render */}}));});
  bi('commGroup',v=>{S.commGroup=v;});
  bc('btnCommBackTopBanner',()=>{S.fromFinal=false;S.phase=4;render();});
  bc('btnEssBackTopBanner',()=>{S.fromFinal=false;S.phase=4;render();});
  bc('btnCommBack',()=>{if(S.fromFinal){S.fromFinal=false;S.phase=4;render();}else{S.phase=1;S.srStep='sr_output';render();}});
  bc('btnCommNext',()=>{const errs={};for(const[k,c]of Object.entries(S.commContacts)){const e=validatePhone(c.phone);if(e)errs[k]=e;}S.commPhoneErrs=errs;if(Object.keys(errs).length){render();return;}S.phase=3;render();});
  document.querySelectorAll('[data-ess]').forEach(el=>el.addEventListener('click',()=>{const item=decodeURIComponent(el.dataset.ess);const sel=new Set(S.selectedEssentials);if(sel.has(item))sel.delete(item);else sel.add(item);S.selectedEssentials=sel;render();}));
  bi('custInput',v=>{S.customInput=v;});
  const addCust=()=>{const v=S.customInput.trim();if(v&&!DEFAULT_ESSENTIALS.includes(v)&&!S.customEssentials.includes(v)){S.customEssentials=[...S.customEssentials,v];S.selectedEssentials=new Set([...S.selectedEssentials,v]);S.customInput='';render();}};
  bc('btnAddCust',addCust);
  const ci=document.getElementById('custInput');if(ci)ci.addEventListener('keydown',e=>{if(e.key==='Enter')addCust();});
  bc('btnEssBack',()=>{if(S.fromFinal){S.fromFinal=false;S.phase=4;render();}else{S.phase=2;render();}});
  bc('btnEssNext',()=>{S.phase=4;S.finalStep='ai';S.aiDownloaded=false;render();});
  bc('btnPrintAll',doPrintAll);bc('btnSavePDF',doPrintAll);
  bc('btnDownloadAI',doDownloadAI);
  bc('btnFinalAINext',()=>{S.finalStep='docs';render();});
  bc('btnFinalDocsBack',()=>{S.finalStep='ai';S.docsActioned=false;render();});
  bc('btnDoPrint',doPrintAll);
  bc('btnDoDownload',doDownloadDocs);
  bc('btnDoPrintAndDownload',doPrintAndDownloadDocs);
  bc('btnRevSR',()=>{S.fromFinal=true;S.phase=1;S.srStep='sr_output';render();});
  bc('btnRevComm',()=>{S.fromFinal=true;S.phase=2;render();});  // FIX 3: set fromFinal so back button returns to summary
  bc('btnRevEss',()=>{S.fromFinal=true;S.phase=3;render();});   // FIX 3: set fromFinal so back button returns to summary


  /* QUESTION LOGIC TAB */
  bc('btnPickQLFile',()=>{const fi=document.getElementById('qlFileInput');if(fi)fi.click();});
  const _qlfi=document.getElementById('qlFileInput');
  if(_qlfi)_qlfi.addEventListener('change',function(){
    const file=this.files[0];if(!file)return;
    const nameEl=document.getElementById('qlFileName');
    if(nameEl)nameEl.textContent=file.name;
    const statusEl=document.getElementById('qlParseStatus');
    if(statusEl)statusEl.innerHTML=`<span style="font-size:11px;color:rgba(255,255,255,.5)">Parsing…</span>`;
    const reader=new FileReader();
    reader.onload=function(e){
      try{
        const data=new Uint8Array(e.target.result);
        const workbook=XLSX.read(data,{type:'array'});
        const logic=parseXlsxToLogic(workbook);
        if(!logic.pos.length&&!logic.neg.length){
          if(statusEl)statusEl.innerHTML=`<span style="font-size:11px;color:#FCA5A5">⚠ No data found. Check columns: A=Category, B=Attribute, C=Cognitive Cat, D=NA Types, E=Question, F=Responses, G=Defaults, H=Trigger, I=Adds to Card.</span>`;
          return;
        }
        store(SK.questionLogic,logic);
        applyStoredQuestionLogic();
        S.adminSaveMsg='Question logic updated: '+logic.pos.length+' positive, '+logic.neg.length+' caution attributes, '+logic.questions.length+' questions.';
        if(statusEl)statusEl.innerHTML='';
        render();
      }catch(err){
        if(statusEl)statusEl.innerHTML=`<span style="font-size:11px;color:#FCA5A5">⚠ Parse error: ${esc(String(err))}</span>`;
      }
    };
    reader.readAsArrayBuffer(file);
  });
  bc('btnResetQL',()=>{
    if(confirm('Remove custom question logic and revert to built-in defaults? The page will reload.')){
      localStorage.removeItem(SK.questionLogic);
      location.reload();
    }
  });

  /* CODE GENERATOR */
  bc('btnGenNewCode',()=>{
    // Generate fresh code but KEEP the persisted image & template
    S.newCodeStr=genCodeStr();
    S.newOrderNumber='';
    S.newCodeQrUrl=getBaseUrl()+'?code='+S.newCodeStr;
    S.newCodeAdminText=load(SK.activationCardTemplate,ACTIVATION_CARD_TEMPLATE_DEFAULT);
    const _img=load(SK.codeImage,'');S.newCodeImageData=_img||null;
    S.adminSaveMsg='';render();
  });
  const _ciiEl=document.getElementById('codeImageUpload');
  if(_ciiEl)_ciiEl.addEventListener('change',e=>{
    const f=e.target.files[0];if(!f)return;
    const fr=new FileReader();
    fr.onload=ev=>{
      const img=new Image();
      img.onload=()=>{
        const MAX=300;
        const scale=Math.min(1,MAX/Math.max(img.width,img.height));
        const cv=document.createElement('canvas');
        cv.width=Math.round(img.width*scale);
        cv.height=Math.round(img.height*scale);
        cv.getContext('2d').drawImage(img,0,0,cv.width,cv.height);
        const dataUrl=cv.toDataURL('image/png',0.92);
        S.newCodeImageData=dataUrl;
        // Persist image to localStorage so it survives page refresh
        store(SK.codeImage,dataUrl);
        render();
      };
      img.onerror=()=>{S.newCodeImageData=ev.target.result;store(SK.codeImage,ev.target.result);render();};
      img.src=ev.target.result;
    };
    fr.readAsDataURL(f);
  });
  bc('btnClearCodeImg',()=>{S.newCodeImageData=null;store(SK.codeImage,'');render();});
  const _nqEl=document.getElementById('newCodeQrUrl');
  if(_nqEl)_nqEl.addEventListener('input',()=>{S.newCodeQrUrl=_nqEl.value;});
  const _natEl=document.getElementById('newCodeAdminText');
  if(_natEl)_natEl.addEventListener('input',()=>{S.newCodeAdminText=_natEl.value;});
  const _onEl=document.getElementById('newOrderNum');
  if(_onEl)_onEl.addEventListener('input',()=>{S.newOrderNumber=_onEl.value;});
  bc('btnSaveCardTemplate',()=>{
    const txt=S.newCodeAdminText;
    store(SK.activationCardTemplate,txt);
    S.adminCardTplMsg='Template saved';
    render();
    setTimeout(()=>{S.adminCardTplMsg='';render();},2500);
  });
  bc('btnSaveAndPrintCode',async()=>{
    if(!S.newCodeStr)return;
    const _now=new Date(),_exp=new Date(_now);
    _exp.setFullYear(_exp.getFullYear()+1);
    const rec={code:S.newCodeStr,orderNumber:S.newOrderNumber.trim()||'',createdAt:_now.toISOString(),expiresAt:_exp.toISOString(),cancelled:false,adminText:S.newCodeAdminText||'',imageData:S.newCodeImageData||null,qrUrl:S.newCodeQrUrl||window.location.href.split('?')[0]+'?code='+S.newCodeStr,activations:[]};
    const _all=loadCodes();_all.push(rec);saveCodes(_all);
    S.adminSaveMsg='Code '+rec.code+(rec.orderNumber?' (Order #'+rec.orderNumber+')':'')+' saved.';
    const _saved=JSON.parse(JSON.stringify(rec));
    // Reset for next code, keeping persisted image & template
    S.newCodeStr=genCodeStr();S.newOrderNumber='';
    S.newCodeQrUrl=getBaseUrl()+'?code='+S.newCodeStr;
    S.newCodeAdminText=load(SK.activationCardTemplate,ACTIVATION_CARD_TEMPLATE_DEFAULT);
    render();
    await doPrintCode(_saved);
  });
  document.querySelectorAll('[data-cf]').forEach(el=>el.addEventListener('click',()=>{S.codeListFilter=el.dataset.cf;render();}));
  document.querySelectorAll('[data-cancelcode]').forEach(el=>el.addEventListener('click',()=>{
    const code=el.dataset.cancelcode;
    if(!confirm('Cancel code '+code+'?\n\nIt will immediately stop working. This cannot be undone.'))return;
    const _all=loadCodes(),_i=_all.findIndex(r=>r.code===code);
    if(_i>=0){_all[_i].cancelled=true;saveCodes(_all);}
    render();
  }));
  document.querySelectorAll('[data-printcode]').forEach(el=>el.addEventListener('click',async()=>{
    const rec=getCodeRecord(el.dataset.printcode);
    if(rec)await doPrintCode(rec);
  }));
  bc('btnClearAllCodes',()=>{if(confirm('Delete ALL generated codes and activation records?\n\nThis cannot be undone.')){saveCodes([]);S.codeListFilter='all';S.adminSaveMsg='';render();}});
  bc('btnExportCodesCSV',()=>{
    const codes=loadCodes();
    if(!codes.length)return;
    const rows=[['Code','Order Number','Status','Created','Expires','Activations','Activated By (name)','Activated By (email)','Activated At']];
    const now=new Date();
    codes.slice().reverse().forEach(r=>{
      const acts=r.activations||[];
      const isExp=new Date(r.expiresAt)<=now;
      const status=r.cancelled?'Cancelled':isExp?'Expired':acts.length===0?'Unused':acts.length===1?'Activated':'Multi-Use';
      if(acts.length===0){
        rows.push([r.code,r.orderNumber||'',status,r.createdAt,r.expiresAt,'0','','','']);
      } else {
        acts.forEach((a,i)=>{
          rows.push([r.code,i===0?(r.orderNumber||''):'',i===0?status:'',i===0?r.createdAt:'',i===0?r.expiresAt:'',i===0?acts.length:'',a.name||'',a.email||'',a.activatedAt||'']);
        });
      }
    });
    const csv=rows.map(r=>r.map(v=>'"'+String(v).replace(/"/g,'""')+'"').join(',')).join('\n');
    const blob=new Blob(['\ufeff'+csv],{type:'text/csv'});
    const url=URL.createObjectURL(blob);
    const a=document.createElement('a');a.href=url;
    a.download='safety-reserve-codes-'+new Date().toISOString().slice(0,10)+'.csv';
    document.body.appendChild(a);a.click();document.body.removeChild(a);
    setTimeout(()=>URL.revokeObjectURL(url),3000);
  });
  bc('btnSaveAcTemplate',()=>{
    const el=document.getElementById('acTplTextarea');
    if(!el)return;
    const txt=el.value;
    store(SK.activationCardTemplate,txt);
    S.adminCardTplMsg='Template saved';
    S.newCodeAdminText=txt;
    render();
    setTimeout(()=>{S.adminCardTplMsg='';render();},2500);
  });
}

/* =============================================================
   LOGIC HANDLERS
   ============================================================= */
function advQ(ga){const allQs=buildQList(getOrderedLocs(S.locations));let nx=S.qIndex+1;while(nx<allQs.length&&allQs[nx].key==='fuel'){if(ga?.transportation==='No car — bike or transit only')nx++;else break;}if(nx<allQs.length){S.qIndex=nx;S.collAns={};render();}else{S.srStep='sr_output';render();}}
function handleActivateNext(){
  const code=S.activationCode.trim();
  if(!code){S.activationErr='Please enter your activation code.';render();return;}
  const rec=getCodeRecord(code);
  if(rec){
    if(rec.cancelled){S.activationErr='This activation code has been cancelled. Please contact the Concierge at concierge@jpsutton.com';render();return;}
    if(new Date()>new Date(rec.expiresAt)){S.activationErr='Your activation code has expired. Please contact the Concierge at concierge@jpsutton.com';render();return;}
  }
  S.appFlow='confirm';S.errors={};saveSession();render();
}
function handleConfirmNext(){const errs={};if(!S.userFullName.trim())errs.fullName='Please enter your full name.';if(!S.userEmail.trim())errs.email='Please enter your email address.';else if(!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(S.userEmail.trim()))errs.email='Please enter a valid email address.';if(Object.keys(errs).length){S.errors=errs;render();return;}S.errors={};if(!S.userName)S.userName=S.userFullName.split(' ')[0];storeRegistration();saveSession();S.appFlow='safety';render();}
async function handleSafetyNext(){if(!S.legalAccepted){S.legalErr='You must accept the terms to proceed.';render();return;}S.legalErr='';await storeLegalAcceptance();saveSession();S.appFlow='welcomePage';render();}
function handleWsNext(){const errs={},locs=[...S.locations.filter(l=>!["W","SC"].includes(l.type))];if(['work','both'].includes(S.wsChoice)){if(S.workGoesIn===null){errs.workGoesIn="Please answer";S.errors=errs;render();return;}if(S.workGoesIn){if(!S.workName.trim()||!S.workMins){errs.work="Please fill in office details";S.errors=errs;render();return;}if(isSusSmall(S.workMins)&&!S.workMinsConf){errs.workMinsWarn=true;S.errors=errs;render();return;}locs.push({id:"W",type:"W",displayLabel:S.workName.trim(),travelMinutes:parseInt(S.workMins)});}}if(['school','both'].includes(S.wsChoice)){if(S.schoolGoesIn===null){errs.schoolGoesIn="Please answer";S.errors=errs;render();return;}if(S.schoolGoesIn){if(!S.schoolName.trim()||!S.schoolMins){errs.school="Please fill in campus details";S.errors=errs;render();return;}if(isSusSmall(S.schoolMins)&&!S.schoolMinsConf){errs.schoolMinsWarn=true;S.errors=errs;render();return;}locs.push({id:"SC",type:"SC",displayLabel:S.schoolName.trim(),travelMinutes:parseInt(S.schoolMins)});}}S.locations=locs;S.errors={};S.srStep='friends';render();}
function handleAddFriend(){const errs={};if(!S.friendName.trim())errs.friendName="Please enter a name";if(!S.friendMins||isNaN(parseInt(S.friendMins)))errs.friendMins="Please enter travel time";const m=parseInt(S.friendMins);if(!isNaN(m)&&isSusSmall(S.friendMins)&&!S.friendMinsConf){errs.friendMinsWarn=true;S.errors=errs;render();return;}if(S.friendRel==='roommates_parents'||((S.friendRel==='friend'||S.friendRel==='partner')&&m>60)){if(!S.friendCity.trim())errs.friendCity="City required";if(!S.friendState.trim())errs.friendState="State required";else if(!VALID_STATES.has(S.friendState.trim().toUpperCase()))errs.friendState="Valid 2-letter state (e.g. NY)";}if(Object.keys(errs).length){S.errors=errs;render();return;}let type;if(S.friendRel==='roommates_parents')type='RP';else if(S.friendRel==='family')type='FM';else type=m<=60?'FR-N':'FR';const id=`${type}_${Date.now()}`;S.locations=[...S.locations,{id,type,displayLabel:S.friendName.trim(),travelMinutes:m,city:S.friendCity.trim(),state:S.friendState.trim().toUpperCase()}];S.friendName='';S.friendMins='';S.friendCity='';S.friendState='';S.friendMinsConf=false;S.errors={};render();}
function handlePublicNext(){if(!S.pubType){S.errors.pub="Please select a type";render();return;}if(!S.pubMins||isNaN(parseInt(S.pubMins))||parseInt(S.pubMins)<=0){S.errors.pub="Please enter travel time from home";render();return;}const type=S.pubType==='shelter'?'PS':'P';const name=S.pubType==='shelter'?'Public Shelter':S.buildingType;const wo=S.locations.filter(l=>!["P","PS"].includes(l.type));S.locations=[...wo,{id:type,type,displayLabel:name,travelMinutes:parseInt(S.pubMins)||0}];S.errors={};S.srStep='review';render();}

/* =============================================================
   KEYBOARD SHORTCUT: Ctrl+Shift+A opens Admin Panel
   ============================================================= */
document.addEventListener('keydown',e=>{if(e.ctrlKey&&e.shiftKey&&e.key==='A'){e.preventDefault();S.showAdmin=true;render();}});
window.addEventListener('hashchange',()=>{if(window.location.hash.toLowerCase()==='#admin'){S.showAdmin=true;render();}});

/* =============================================================
   INIT
   ============================================================= */
initApp();
/* =============================================================
   QR CODE GENERATION
   ============================================================= */
async function generateQRDataURL(text,centerImgSrc,size){
  return new Promise(resolve=>{
    try{
      const qr=qrcode(0,'H');
      qr.addData(text);qr.make();
      const mc=qr.getModuleCount();
      const pad=Math.round(size*0.04),qrA=size-pad*2,cell=qrA/mc;
      const canvas=document.createElement('canvas');
      canvas.width=size;canvas.height=size;
      const ctx=canvas.getContext('2d');
      ctx.fillStyle='#FFFFFF';ctx.fillRect(0,0,size,size);
      ctx.fillStyle='#2C3347';
      for(let r=0;r<mc;r++)for(let c=0;c<mc;c++)if(qr.isDark(r,c))
        ctx.fillRect(Math.round(pad+c*cell),Math.round(pad+r*cell),Math.ceil(cell)+1,Math.ceil(cell)+1);
      if(!centerImgSrc){resolve(canvas.toDataURL('image/png'));return;}
      const img=new Image();
      img.onload=()=>{
        const iw=qrA*0.22,ix=pad+(qrA-iw)/2,iy=pad+(qrA-iw)/2;
        ctx.fillStyle='#FFFFFF';
        ctx.beginPath();ctx.arc(size/2,size/2,iw/2+10,0,Math.PI*2);ctx.fill();
        ctx.save();ctx.beginPath();ctx.arc(size/2,size/2,iw/2+2,0,Math.PI*2);ctx.clip();
        ctx.drawImage(img,ix,iy,iw,iw);ctx.restore();
        resolve(canvas.toDataURL('image/png'));
      };
      img.onerror=()=>resolve(canvas.toDataURL('image/png'));
      img.src=centerImgSrc;
    }catch(e){resolve('');}
  });
}

async function doPrintCode(rec){
  if(!rec)return;
  const qrUrl=rec.qrUrl||(getBaseUrl()+'?code='+rec.code);
  const expDate=new Date(rec.expiresAt).toLocaleDateString('en-US',{month:'long',day:'numeric',year:'numeric'});
  const createdDate=new Date(rec.createdAt).toLocaleDateString('en-US',{month:'long',day:'numeric',year:'numeric'});

  // Build the "Get Started" text paragraphs
  const gsParagraphs=(rec.adminText||'').split('\n').map(l=>l.trim()).filter(Boolean)
    .map(l=>`<p style="font-size:12.5px;color:#3A4560;line-height:1.7;margin:0 0 7px">${esc(l)}</p>`).join('');

  // Determine what to show in the visual panel (image or QR)
  let visualHtml='';
  if(rec.imageData){
    visualHtml=`<img src="${rec.imageData}" style="width:100%;height:100%;object-fit:contain;display:block" alt="Brand image">`;
  } else {
    // Generate QR code
    try{
      const qr=qrcode(0,'H');
      qr.addData(qrUrl);qr.make();
      const mc=qr.getModuleCount(),size=380;
      const pad=Math.round(size*0.04),qrA=size-pad*2,cell=qrA/mc;
      const cv=document.createElement('canvas');cv.width=size;cv.height=size;
      const ctx=cv.getContext('2d');
      ctx.fillStyle='#FFFFFF';ctx.fillRect(0,0,size,size);
      ctx.fillStyle='#2C3347';
      for(let r=0;r<mc;r++)for(let c=0;c<mc;c++)if(qr.isDark(r,c))
        ctx.fillRect(Math.round(pad+c*cell),Math.round(pad+r*cell),Math.ceil(cell)+1,Math.ceil(cell)+1);
      visualHtml=`<img src="${cv.toDataURL('image/png')}" style="width:100%;height:100%;object-fit:contain;display:block" alt="Scan to activate">`;
    }catch(e){
      visualHtml=`<span style="font-size:11px;color:#C0C8D8;padding:10px">QR unavailable</span>`;
    }
  }

  const orderLine=rec.orderNumber?`<span style="font-size:10px;color:#8E95A3">Order #${esc(rec.orderNumber)}</span>`:'';

  const w=window.open('','_blank','width=700,height=980');
  if(!w){alert('Pop-up blocked. Please allow pop-ups for this site and try again.');return;}

  w.document.write(`<!DOCTYPE html><html><head>
<meta charset="UTF-8">
<title>Safety Reserve — Urban Resilience Guide</title>
<link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=DM+Serif+Display&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0;-webkit-print-color-adjust:exact!important;print-color-adjust:exact!important;color-adjust:exact!important}
body{font-family:'Sora',sans-serif;background:#F2F4F8;min-height:100vh;display:flex;align-items:flex-start;justify-content:center;padding:22px 14px}
.page{background:white;max-width:560px;width:100%;border-radius:18px;box-shadow:0 6px 40px rgba(44,51,71,.13);overflow:hidden}

/* ── TOP BANNER ── */
.top-bar{background:linear-gradient(135deg,#1A2E4A,#2C4A6E);padding:14px 22px;display:flex;align-items:center;gap:12px}
.shield-icon{width:38px;height:38px;background:rgba(255,255,255,.15);border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0}
.top-bar-text{flex:1}
.top-bar-title{font-family:'DM Serif Display',serif;font-size:26px;color:white;line-height:1.15}

/* ── SECTION LISTING (top half) ── */
.sections-wrap{padding:14px 22px 10px}
.section-row{display:flex;align-items:center;gap:14px;padding:16px 18px;border-radius:11px;margin-bottom:8px;border:1px solid #E8EAF0;background:#FAFBFD}
.section-icon{font-size:22px;flex-shrink:0}
.section-text{}
.section-name{font-size:14px;font-weight:700;color:#2C3347;line-height:1.3}
.section-sub{font-size:11px;color:#7A8290;margin-top:3px;line-height:1.45}

/* ── DIVIDER ── */
.divider-bar{height:3px;background:linear-gradient(90deg,#2C4A6E,#4A8570,#7264A8);margin:0}

/* ── ACTIVATION PANEL (bottom half) ── */
.activate-wrap{padding:18px 22px 20px;background:linear-gradient(160deg,#F7F9FC 0%,#EAF0F9 100%)}
.get-started-label{display:inline-flex;align-items:center;gap:6px;background:#2C4A6E;color:white;font-size:10px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;padding:4px 12px;border-radius:20px;margin-bottom:14px}

/* Visual + code side by side */
.qr-code-row{display:flex;gap:18px;align-items:flex-start;margin-bottom:16px}
.visual-box{flex-shrink:0;width:150px;height:150px;border-radius:12px;overflow:hidden;border:2px solid #C8D4E8;background:white;display:flex;align-items:center;justify-content:center;box-shadow:0 3px 14px rgba(44,74,110,.12)}
.code-side{flex:1;display:flex;flex-direction:column;justify-content:center;gap:10px}
.code-eyebrow{font-size:9.5px;font-weight:700;letter-spacing:.12em;text-transform:uppercase;color:#8E95A3;margin-bottom:3px}
.code-box{background:white;border:2.5px solid #2C4A6E;border-radius:12px;padding:12px 16px;display:inline-block;box-shadow:0 2px 12px rgba(44,74,110,.14)}
.code-val{font-size:26px;font-weight:800;color:#2C4A6E;letter-spacing:.18em;font-family:'Sora',sans-serif}
.steps-list{display:flex;flex-direction:column;gap:5px}
.step-line{display:flex;align-items:center;gap:7px;font-size:11px;color:#3A4560;line-height:1.4}
.step-num{width:18px;height:18px;border-radius:50%;background:#2C4A6E;color:white;font-size:9px;font-weight:800;display:flex;align-items:center;justify-content:center;flex-shrink:0}

/* Get started text */
.gs-text{background:white;border:1.5px solid #D0DAE8;border-radius:10px;padding:12px 14px;margin-bottom:12px}

/* Validity + support row */
.footer-row{display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:6px;border-top:1px solid #DDE2EA;padding-top:10px}
.valid-pill{display:inline-flex;align-items:center;gap:5px;background:#D8EDE6;border:1.5px solid #9EC8B4;border-radius:20px;padding:3px 11px;font-size:10px;font-weight:700;color:#1A5240}
.support-link{font-size:10px;color:#8E95A3}
.support-link a{color:#4A6FA5;text-decoration:none;font-weight:600}

@page{margin:0;size:letter portrait}
@media print{
  body{background:white;padding:8px}
  .page{box-shadow:none;border-radius:0;max-width:100%}
  .no-print{display:none!important}
}
</style>
</head>
<body>
<div class="page">

  <!-- TOP BANNER -->
  <div class="top-bar">
    <div class="shield-icon">\ud83d\udee1\ufe0f</div>
    <div class="top-bar-text">
      <div class="top-bar-title">Your Urban Resilience Guide</div>
    </div>
  </div>

  <!-- SECTION LISTING -->
  <div class="sections-wrap">
    <div class="section-row" style="background:#EAF0F9;border-color:#BDD0E6">
      <div class="section-icon">🤖</div>
      <div class="section-text">
        <div class="section-name">AI Real Time Situational Analysis</div>
        <div class="section-sub">Rapidly determine what is most likely happening, how reliable that conclusion is, and how people are reacting</div>
      </div>
    </div>

    <div class="section-row" style="background:#D8EDE6;border-color:#9EC8B4">
      <div class="section-icon">📍</div>
      <div class="section-text">
        <div class="section-name">Location Scenarios</div>
        <div class="section-sub">Possible options and associated considerations based on your inputs</div>
      </div>
    </div>

    <div class="section-row" style="background:#EAE8F5;border-color:#C5BEE0">
      <div class="section-icon">📋</div>
      <div class="section-text">
        <div class="section-name">Your Communication Plan</div>
      </div>
    </div>

    <div class="section-row" style="background:#FFF9C2;border-color:#C8AA00">
      <div class="section-icon">🎒</div>
      <div class="section-text">
        <div class="section-name">Pre-Plan Essentials</div>
        <div class="section-sub" style="color:#8A6A00">Items you plan to take if time and conditions allow</div>
      </div>
    </div>

    <div class="section-row" style="background:#FDEAEA;border-color:#EAB0B0">
      <div class="section-icon">📊</div>
      <div class="section-text">
        <div class="section-name">Disruption Insights</div>
        <div class="section-sub" style="color:#A84040">Representative examples of unusual events, with observed patterns</div>
      </div>
    </div>
  </div>

  <div class="divider-bar"></div>

  <!-- ACTIVATION PANEL -->
  <div class="activate-wrap">
    <div class="get-started-label">&#9654; To Get Started</div>

    <div class="qr-code-row">
      <!-- Visual: QR or image -->
      <div class="visual-box">${visualHtml}</div>

      <!-- Code + steps -->
      <div class="code-side">
        <div>
          <div class="code-eyebrow">Your Activation Code</div>
          <div class="code-box">
            <div class="code-val">${rec.code}</div>
          </div>
        </div>
        <div class="steps-list">
          <div class="step-line"><div class="step-num">1</div><span>Open your phone's camera and scan the image to the left</span></div>
          <div class="step-line"><div class="step-num">2</div><span>Enter the code above when prompted</span></div>
          <div class="step-line"><div class="step-num">3</div><span>Follow the guided setup (~5 min)</span></div>
        </div>
      </div>
    </div>

    ${gsParagraphs?`<div class="gs-text">${gsParagraphs}</div>`:''}

    <div class="footer-row">
      <div class="valid-pill">\u2713&nbsp; Valid until ${expDate}</div>
      <div class="support-link">Need help? <a href="mailto:support@jpsutton.com">support@jpsutton.com</a></div>
    </div>
  </div>

</div>
<script>window.onload=function(){window.print();};<\/script>
</body></html>`);
  w.document.close();
}


</script>
</body>
</html>
