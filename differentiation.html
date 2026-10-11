<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sopaan · Differentiation</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Source+Sans+3:wght@400;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap">
<style>
  html,body{margin:0;} img{max-width:100%;} [hidden]{display:none !important;}
  :root{
    --navy:#16264A; --navy-2:#1F3B6B; --gold:#C79A3E; --gold-soft:#F3E7C9;
    --paper:#FBF9F4; --paper-2:#F1EAD8; --card:#FFFFFF;
    --ink:#211E1A; --ink-soft:#655D4C; --rule:#E4DCC8;
    --success:#2E8B57; --success-soft:#E1F2E7;
    --danger:#BF4B45; --danger-soft:#FAE3E1;
    --locked:#C7BEA9;
    --focus:#1F3B6B;
    --accent-text:#1F3B6B; --retry-text:#8A661F;
    color-scheme:light;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
      --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
      --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
      --success:#7BC79A; --success-soft:#1B2E22;
      --danger:#E38884; --danger-soft:#331D1B;
      --locked:#4A4436;
      --focus:#E0B75B;
      --accent-text:#E0B75B; --retry-text:#E0B75B;
      color-scheme:dark;
    }
  }
  :root[data-theme="dark"]{
    --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
    --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
    --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
    --success:#7BC79A; --success-soft:#1B2E22;
    --danger:#E38884; --danger-soft:#331D1B;
    --locked:#4A4436;
    --focus:#E0B75B;
    --accent-text:#E0B75B; --retry-text:#E0B75B;
    color-scheme:dark;
  }

  *{box-sizing:border-box;}
  body{background:var(--paper); color:var(--ink); font-family:'Source Sans 3',-apple-system,'Segoe UI',sans-serif; padding-inline:0; padding-block:0;}
  h1,h2,h3{font-family:'Fraunces',Georgia,serif; text-wrap:balance; margin:0;}
  .num{font-family:'IBM Plex Mono',ui-monospace,monospace; font-variant-numeric:tabular-nums;}

  header.brand{
    background:linear-gradient(155deg,var(--navy) 0%, var(--navy-2) 100%);
    color:#F4EFDF; padding-block:calc(20px + env(safe-area-inset-top,0px)) 18px; padding-inline:20px;
  }
  .brand-row{display:flex; align-items:center; gap:12px; max-width:900px; margin:0 auto;}
  .crest{
    width:42px; height:42px; border-radius:10px; background:var(--gold); color:var(--navy);
    display:flex; align-items:center; justify-content:center; font-family:'Fraunces',serif; font-weight:700; font-size:18px; flex-shrink:0;
  }
  .brand-name{font-size:12px; letter-spacing:.08em; text-transform:uppercase; color:var(--gold); font-weight:700;}
  .series-name{font-size:19px; font-weight:700; font-family:'Fraunces',serif;}
  .chapter-eyebrow{max-width:900px; margin:14px auto 0; font-size:12px; letter-spacing:.06em; text-transform:uppercase; color:#AEB9D6;}
  .chapter-title{font-size:28px; max-width:900px; margin:2px auto 0;}
  .chapter-sub{font-size:14.5px; color:var(--gold); font-weight:700; max-width:900px; margin:3px auto 0;}

  .chapter-progress{max-width:900px; margin:14px auto 0; display:flex; align-items:center; gap:10px;}
  .cp-track{flex:1; height:6px; border-radius:99px; background:rgba(255,255,255,.18); overflow:hidden;}
  .cp-fill{height:100%; background:var(--gold); border-radius:99px; transition:width .3s ease;}
  .cp-label{font-size:11.5px; color:#CFD7EA; white-space:nowrap;}

  .tabbar{position:sticky; top:env(safe-area-inset-top,0px); z-index:15; background:var(--paper); border-bottom:1px solid var(--rule); overflow-x:auto; white-space:nowrap;}
  .tabbar-inner{max-width:900px; margin:0 auto; display:flex; padding-inline:16px;}
  .tab-btn{font-family:inherit; font-size:14px; font-weight:600; color:var(--ink-soft); background:none; border:none; padding:13px 16px; cursor:pointer; position:relative; flex-shrink:0;}
  .tab-btn.active{color:var(--accent-text);}
  .tab-btn.active::after{content:''; position:absolute; left:12px; right:12px; bottom:0; height:3px; background:var(--gold); border-radius:3px 3px 0 0;}
  .tab-count{font-size:11px; color:var(--ink-soft); margin-left:5px;}

  .slide-progress{max-width:900px; margin:0 auto; padding:10px 16px 0; display:flex; align-items:center; gap:10px;}
  .sp-track{flex:1; height:5px; border-radius:99px; background:var(--rule); overflow:hidden;}
  .sp-fill{height:100%; background:var(--accent-text); border-radius:99px; transition:width .3s ease;}
  .sp-label{font-size:12px; color:var(--ink-soft); white-space:nowrap; font-weight:600;}

  .wrap{max-width:900px; margin:0 auto; padding:16px 16px calc(110px + env(safe-area-inset-bottom,0px));}

  .qcard{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px;}
  .qhead{display:flex; align-items:flex-start; gap:10px; margin-bottom:10px;}
  .qnum{width:32px; height:32px; border-radius:8px; background:var(--gold-soft); color:var(--accent-text); display:flex; align-items:center; justify-content:center; font-weight:700; font-family:'Fraunces',serif; flex-shrink:0; font-size:14px;}
  .qtext{font-size:16px; line-height:1.55; flex:1;}
  .qtag{font-size:10.5px; color:var(--gold); background:var(--gold-soft); padding:2px 7px; border-radius:99px; font-weight:700; margin-left:6px; white-space:nowrap;}
  .marks-pill{font-size:11px; font-weight:700; color:var(--ink-soft); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; margin-left:auto; flex-shrink:0; white-space:nowrap;}
  .step-badge{font-size:11px; font-weight:700; color:var(--accent-text); background:var(--paper-2); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; display:inline-block; margin-bottom:12px;}

  .options{display:flex; flex-direction:column; gap:8px; margin-top:10px;}
  .opt{display:flex; align-items:center; gap:10px; padding:11px 12px; border:1.5px solid var(--rule); border-radius:10px; cursor:pointer; font-size:15px; background:var(--paper);}
  .opt input{accent-color:var(--navy-2);}
  .opt.is-correct{border-color:var(--success); background:var(--success-soft);}
  .opt.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .opt.locked{cursor:not-allowed;}

  .subpart-label{font-weight:700; font-size:12.5px; color:var(--accent-text); text-transform:uppercase; letter-spacing:.03em; margin:14px 0 6px;}
  .or-divider{text-align:center; font-size:11px; font-weight:700; letter-spacing:.08em; color:var(--ink-soft); margin:8px 0;}

  .steps{display:flex; flex-direction:column; gap:10px;}
  .step-line{font-size:14.5px; line-height:1.9; background:var(--paper); border:1px dashed var(--rule); border-radius:10px; padding:9px 12px;}
  .step-line.resolved{opacity:.9;}
  .blank-input{font-family:'IBM Plex Mono',monospace; font-size:14px; border:1.5px solid var(--rule); border-radius:6px; padding:3px 8px; width:120px; background:var(--card); color:var(--ink); margin:0 2px;}
  .blank-input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .blank-input.is-correct{border-color:var(--success); background:var(--success-soft);}
  .blank-input.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .blank-input[disabled]{opacity:.85;}
  .reveal-note{font-size:12px; color:var(--danger); padding-left:2px; margin-top:-2px;}

  .feedback{font-size:13.5px; padding:10px 12px; border-radius:9px; margin-top:14px; display:none;}
  .feedback.show{display:block;}
  .feedback.ok{background:var(--success-soft); color:var(--success);}
  .feedback.retry{background:var(--gold-soft); color:var(--retry-text);}
  .feedback.reveal{background:var(--danger-soft); color:var(--danger);}
  .feedback.err{background:var(--danger-soft); color:var(--danger);}
  .attempts-dots{display:inline-flex; gap:4px; margin-left:2px;}
  .attempts-dots span{width:6px; height:6px; border-radius:50%; background:var(--ink-soft); opacity:.3; display:inline-block;}
  .attempts-dots span.used{opacity:1; background:var(--danger);}

  .ar-box{background:var(--paper-2); border-radius:10px; padding:10px 12px; margin-bottom:12px; font-size:13px; color:var(--ink-soft);}

  .navbar{
    position:fixed; left:0; right:0; bottom:0; z-index:30; background:var(--paper);
    border-top:1px solid var(--rule); padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));
  }
  .navbar-inner{max-width:900px; margin:0 auto; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
  .btn{font-family:inherit; font-size:13.5px; font-weight:700; padding:10px 14px; border-radius:9px; border:1.5px solid var(--rule); background:var(--card); color:var(--ink); cursor:pointer;}
  .btn:hover{border-color:var(--navy-2);}
  .btn:disabled{opacity:.4; cursor:not-allowed;}
  .btn-primary{background:var(--navy-2); color:#fff; border-color:var(--navy-2);}
  .navbar .spacer{flex:1;}

  .fab{position:fixed; right:16px; bottom:calc(74px + env(safe-area-inset-bottom,0px)); background:var(--gold); color:var(--navy); border:none; border-radius:999px; padding:11px 16px; font-family:inherit; font-weight:700; font-size:13px; display:flex; align-items:center; gap:7px; cursor:pointer; box-shadow:0 6px 16px rgba(0,0,0,.18); z-index:35;}
  .fab-badge{background:rgba(255,255,255,.55); border-radius:99px; padding:1px 7px; font-size:11px;}

  .overlay{position:fixed; inset:0; background:rgba(20,18,14,.45); z-index:50; display:none; align-items:flex-end; justify-content:center;}
  .overlay.show{display:flex;}
  .palette{background:var(--card); width:min(480px,100%); max-height:78vh; overflow-y:auto; border-radius:18px 18px 0 0; padding:18px 18px calc(18px + env(safe-area-inset-bottom,0px)); border:1px solid var(--rule); border-bottom:none;}
  @media (min-width:640px){ .overlay{align-items:center;} .palette{border-radius:18px; border-bottom:1px solid var(--rule); max-height:74vh;} }
  .palette-head{display:flex; align-items:center; justify-content:space-between; margin-bottom:6px;}
  .palette-head h2{font-size:16px;}
  .palette-close{background:none; border:none; font-size:20px; color:var(--ink-soft); cursor:pointer; padding:4px;}
  .palette-legend{display:flex; gap:12px; flex-wrap:wrap; font-size:11px; color:var(--ink-soft); margin:10px 0 14px;}
  .palette-legend span{display:inline-flex; align-items:center; gap:5px;}
  .dot{width:9px; height:9px; border-radius:50%; display:inline-block;}
  .dot.correct{background:var(--success);} .dot.revealed{background:var(--danger);}
  .dot.skipped{background:var(--gold);} .dot.locked{background:var(--locked);}
  .dot.current{background:var(--navy-2);}
  .chip-grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(48px,1fr)); gap:8px;}
  .chip{border:1.5px solid var(--rule); border-radius:9px; padding:8px 4px; text-align:center; font-family:'IBM Plex Mono',monospace; font-size:12.5px; font-weight:600; cursor:pointer; background:var(--paper); color:var(--ink);}
  .chip[data-status="correct"]{border-color:var(--success); background:var(--success-soft); color:var(--success);}
  .chip[data-status="revealed"]{border-color:var(--danger); background:var(--danger-soft); color:var(--danger);}
  .chip[data-status="skipped"]{border-color:var(--gold); background:var(--gold-soft); color:var(--retry-text);}
  .chip[data-status="locked"]{border-color:var(--rule); color:var(--locked); cursor:not-allowed; background:var(--paper-2);}
  .chip[data-status="current"]{outline:2px solid var(--navy-2); outline-offset:1px;}

  .toast{position:fixed; left:50%; bottom:calc(140px + env(safe-area-inset-bottom,0px)); transform:translateX(-50%); background:var(--ink); color:var(--paper); padding:9px 16px; border-radius:99px; font-size:13px; opacity:0; pointer-events:none; transition:opacity .25s ease; z-index:60;}
  .toast.show{opacity:1;}

  .done-card{text-align:center; padding:36px 20px;}
  .done-card .big{font-size:38px; margin-bottom:6px;}
  .score-pills{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0;}
  .score-pill{padding:8px 16px; border-radius:99px; font-size:13px; font-weight:700;}

  footer.brandfoot{max-width:900px; margin:14px auto 0; padding:0 16px calc(110px + env(safe-area-inset-bottom,0px)); text-align:center; font-size:12px; color:var(--ink-soft);}

  .mode-pill{font-family:inherit; font-size:12.5px; font-weight:700; color:var(--navy); background:var(--gold); border:none; border-radius:99px; padding:6px 14px; cursor:pointer; margin-top:12px; display:inline-flex; align-items:center; gap:6px;}
  .mode-pick{display:flex; flex-direction:column; gap:14px; padding:8px 0 24px;}
  .mode-card{background:var(--card); border:1.5px solid var(--rule); border-radius:16px; padding:22px; cursor:pointer; text-align:left;}
  .mode-card:hover{border-color:var(--navy-2);}
  .mode-card .mode-icon{font-size:26px; margin-bottom:8px;}
  .mode-card h3{font-size:18px; margin-bottom:6px;}
  .mode-card p{font-size:13.5px; color:var(--ink-soft); line-height:1.5; margin:0;}
  .quiz-hint{font-size:12.5px; color:var(--ink-soft); background:var(--paper-2); border-radius:9px; padding:8px 12px; margin-bottom:14px;}
  .review-row{border:1px solid var(--rule); border-radius:10px; padding:11px 13px; margin-bottom:10px;}
  .review-tag{font-size:11.5px; font-weight:700; margin-bottom:4px; display:block;}
  .review-tag.ok{color:var(--success);} .review-tag.bad{color:var(--danger);} .review-tag.na{color:var(--ink-soft);}
  .review-q{font-size:13.5px; margin-bottom:6px; color:var(--ink-soft);}
  .review-ans{font-size:13px; margin-bottom:2px;}

  .who-row{max-width:900px; margin:12px auto 0; display:flex; flex-wrap:wrap; gap:8px; align-items:center;}
  .who-row .mode-pill{margin-top:0;}
  .who{display:inline-flex; flex-wrap:wrap; align-items:center; gap:6px; font-size:12.5px; color:#CFD7EA;}
  .who b{color:#F4EFDF;}
  .who button{font-family:inherit; font-size:12px; font-weight:700; color:#F4EFDF; background:rgba(255,255,255,.12); border:1px solid rgba(255,255,255,.22); border-radius:99px; padding:5px 11px; cursor:pointer;}
  .who button:hover{background:rgba(255,255,255,.2);}
  .login-card{max-width:460px; margin:8px auto 0; background:var(--card); border:1px solid var(--rule); border-radius:16px; padding:22px;}
  .login-card h2{font-size:21px; margin-bottom:4px;}
  .login-card p.lead{font-size:13.5px; color:var(--ink-soft); margin:0 0 16px; line-height:1.5;}
  .fld{display:flex; flex-direction:column; gap:5px; margin-bottom:12px;}
  .fld label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .fld input{font-family:inherit; font-size:15px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:9px; background:var(--paper); color:var(--ink);}
  .fld input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .fld-row{display:grid; grid-template-columns:1fr 1fr; gap:10px;}
  .login-err{font-size:13px; color:var(--danger); background:var(--danger-soft); border-radius:8px; padding:8px 10px; margin-bottom:12px;}
  .login-note{font-size:12px; color:var(--ink-soft); margin-top:12px; line-height:1.5;}
  .known{margin:0 0 16px; display:flex; flex-direction:column; gap:6px;}
  .known-label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .known-btn{display:flex; justify-content:space-between; align-items:center; gap:10px; text-align:left; font-family:inherit; font-size:14.5px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:10px; background:var(--paper); color:var(--ink); cursor:pointer;}
  .known-btn:hover{border-color:var(--navy-2);}
  .known-btn small{font-size:12px; color:var(--ink-soft);}
  .rec-card{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px; margin-bottom:14px;}
  .rec-card h2{font-size:19px; margin-bottom:10px;}
  .rec-card h3{font-size:15px; margin:4px 0 8px;}
  .rec-table-wrap{overflow-x:auto;}
  .rec-table{width:100%; border-collapse:collapse; font-size:13.5px; font-variant-numeric:tabular-nums;}
  .rec-table th{text-align:left; font-size:11.5px; text-transform:uppercase; letter-spacing:.04em; color:var(--ink-soft); padding:6px 8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-table td{padding:8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-bar{display:inline-block; width:70px; height:6px; border-radius:99px; background:var(--rule); overflow:hidden; vertical-align:middle; margin-right:6px;}
  .rec-bar i{display:block; height:100%; background:var(--success);}
  .rec-empty{font-size:13.5px; color:var(--ink-soft);}
  .sec-sub{max-width:900px; margin:0 auto; padding:10px 16px 0; font-size:12.5px; font-weight:700; color:var(--accent-text); letter-spacing:.02em;}
  .opt{flex-wrap:wrap;}
  .opt-l{font-family:'IBM Plex Mono',monospace; font-size:13px; font-weight:600; color:var(--ink-soft);}
  .opt-t{flex:1; min-width:0;}
  .opt.is-chosen:not(.is-correct):not(.is-wrong){border-color:var(--navy-2); background:var(--gold-soft);}
  .opt-tag{font-size:11px; font-weight:700; padding:2px 8px; border-radius:99px; background:var(--card); border:1px solid currentColor; white-space:nowrap;}
  .opt.is-correct .opt-tag{color:var(--success);} .opt.is-wrong .opt-tag{color:var(--danger);} .opt.is-chosen:not(.is-correct):not(.is-wrong) .opt-tag{color:var(--accent-text);}
  .chosen{font-size:13.5px; margin-top:10px; padding:8px 12px; border-radius:9px;}
  .chosen.ok{background:var(--success-soft); color:var(--success);} .chosen.bad{background:var(--danger-soft); color:var(--danger);}
  .chosen + .chosen{margin-top:6px;}
  .solution{margin-top:14px; border:1px solid var(--rule); border-left:4px solid var(--gold); background:var(--paper-2); border-radius:10px; padding:12px 14px;}
  .sol-h{font-family:'Fraunces',Georgia,serif; font-weight:700; font-size:14px; color:var(--accent-text); margin-bottom:6px;}
  .sol-line{font-size:14.5px; line-height:1.7;}
  .rev-sol summary{cursor:pointer; font-size:12.5px; font-weight:700; color:var(--accent-text); margin-top:6px;}
  .rev-sol .solution{margin-top:8px;}
  .chapter-credit{max-width:900px; margin:4px auto 0; font-size:12px; color:#CFD7EA;}
  footer.brandfoot a{color:inherit;}
  .blank-input.wide{width:260px; max-width:100%; font-family:'Source Sans 3',sans-serif;}
  .blank-input.expr{width:170px; max-width:100%;}
  /*fix-layout*/ .cp-fill,.sp-fill{width:0;} .fld{min-width:0;} .fld input{width:100%; min-width:0; box-sizing:border-box;}
  .fig{margin:6px 0 10px; display:flex; justify-content:center;}
  .figsvg{width:100%; max-width:340px; height:auto; overflow:visible;}
  .figsvg .ln,.figsvg .arm{stroke:var(--ink); stroke-width:1.6; fill:none;}
  .figsvg .arm{stroke:var(--accent-text); stroke-width:2;}
  .figsvg .pt{fill:var(--ink);}
  .figsvg .lb{fill:var(--ink); font:600 13px 'Source Sans 3',sans-serif;}
  .figsvg .al{fill:var(--accent-text); font:700 12px 'Source Sans 3',sans-serif;}
  .figsvg .wg{fill:var(--gold-soft); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .wg2{fill:rgba(199,154,62,.35); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .ra{fill:none; stroke:var(--ink); stroke-width:1.2;}
  .figsvg .ahd{fill:var(--ink);}
  .figsvg .pr{fill:var(--paper-2); stroke:var(--ink-soft); stroke-width:1.2;}
  .figsvg .tk{stroke:var(--ink-soft); stroke-width:.8;}
  .figsvg .po{fill:var(--ink); font:600 8.5px 'IBM Plex Mono',monospace;}
  .figsvg .pi{fill:var(--danger); font:600 7.5px 'IBM Plex Mono',monospace;}
  .figsvg .sh{fill:var(--gold-soft); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh2{fill:rgba(199,154,62,.38); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh3{fill:rgba(199,154,62,.22); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .none{fill:none;}
  .figsvg .hid{stroke-dasharray:5 4; fill:none;}
  .figsvg .tick{stroke:var(--ink); stroke-width:1.4; fill:none;}
  .figsvg .shd{fill:var(--accent-text); fill-opacity:.55;}
  .figsvg .cell{fill:var(--card); stroke:var(--ink); stroke-width:1.1;}
  .figsvg .dr{fill:var(--danger);} .figsvg .dw{fill:var(--card); stroke:var(--ink); stroke-width:1.2;}
  .figsvg .dotfill{fill:var(--danger);}
  .tt{border-collapse:collapse; font-size:13.5px; margin:4px auto; font-variant-numeric:tabular-nums;} .tt th,.tt td{border:1px solid var(--rule); padding:4px 9px; text-align:left;} .tt th{background:var(--paper-2); font-weight:700;} .ttw{overflow-x:auto; max-width:100%;}
  .fq{display:inline-flex; flex-direction:column; vertical-align:middle; text-align:center; font-size:.82em; line-height:1.12; margin:0 2px;}
  .fq>span:first-child{border-bottom:1.5px solid currentColor; padding:0 2px;}
  .fq>span:last-child{padding:0 2px;}
  .mx{white-space:nowrap;}
  .blank-input.fr{width:110px;}
  @media (prefers-reduced-motion:reduce){ *{transition:none !important;} }
.datline{display:block;margin-top:8px;padding:8px 10px;border-radius:8px;background:var(--paper-2);font:500 14px/1.7 'IBM Plex Mono',monospace;word-spacing:2px;overflow-wrap:anywhere;}

  .theory{display:flex;flex-direction:column;gap:16px;padding-bottom:40px;}
  .hub{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .hub{grid-template-columns:repeat(3,1fr);} }
  .hub-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:16px;display:flex;flex-direction:column;gap:8px;}
  .hub-card h3{font-family:'Fraunces',serif;font-size:18px;margin:0;color:var(--accent-text);}
  .hub-card p{margin:0;font-size:14px;color:var(--ink-soft);line-height:1.5;}
  .hub-btns{display:flex;flex-wrap:wrap;gap:8px;margin-top:auto;}
  .hub-btn{min-height:40px;border:1.5px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:10px;padding:8px 12px;font:600 14px 'Source Sans 3',sans-serif;cursor:pointer;text-align:left;}
  .hub-btn:hover{border-color:var(--gold);}
  .hub-btn.primary{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .note{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:18px;scroll-margin-top:120px;}
  .note h2{font-family:'Fraunces',serif;font-size:22px;margin:0 0 4px;color:var(--ink);}
  .note .lt{font-size:13.5px;color:var(--ink-soft);margin:0 0 12px;}
  .note .lt b{color:var(--accent-text);}
  .note h4{font:700 15px 'Source Sans 3',sans-serif;margin:16px 0 6px;color:var(--accent-text);}
  .note p,.note li{font-size:15.5px;line-height:1.6;}
  .note ul{padding-left:20px;margin:6px 0;}
  .keybox{background:var(--gold-soft);border-left:4px solid var(--gold);border-radius:8px;padding:10px 12px;margin:10px 0;font-size:15px;line-height:1.6;}
  .keybox b{color:var(--ink);}
  .ex{background:var(--paper-2);border-radius:10px;padding:12px;margin:10px 0;}
  .ex .exh{font-family:'Fraunces',serif;font-weight:700;color:var(--accent-text);margin-bottom:4px;}
  .ex .exl{font-size:15px;line-height:1.7;}
  .ttab{width:100%;border-collapse:collapse;font-size:14.5px;margin:8px 0;}
  .ttab th,.ttab td{border:1px solid var(--rule);padding:7px 8px;text-align:left;vertical-align:top;}
  .ttab th{background:var(--paper-2);}
  .tscroll{overflow-x:auto;}
  .mono{font-family:'IBM Plex Mono',monospace;font-size:.92em;}
  @media (max-width:480px){ .ttab{font-size:13.5px;} .ttab th,.ttab td{padding:6px;} }
  .note .figsvg{max-width:100%;height:auto;display:block;margin:8px auto;}


  .rep-top{display:flex;flex-wrap:wrap;gap:18px;align-items:center;justify-content:center;margin-top:8px;}
  .rep-legend{flex:1;min-width:220px;display:flex;flex-direction:column;gap:8px;}
  .rep-cap{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);text-transform:uppercase;letter-spacing:.05em;}
  .rep-li{display:flex;align-items:center;gap:6px;font-size:15px;}
  .rep-n{margin-left:auto;white-space:nowrap;padding-left:8px;font-family:'IBM Plex Mono',monospace;font-weight:600;}
  .sw{display:inline-block;width:12px;height:12px;border-radius:3px;flex:none;}
  .rep-grid{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .rep-grid{grid-template-columns:1fr 1fr;} }
  .rep-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:14px;display:flex;flex-direction:column;gap:10px;}
  .rep-h{display:flex;align-items:center;gap:8px;font:700 16px 'Source Sans 3',sans-serif;}
  .crit{display:inline-grid;place-items:center;width:28px;height:28px;border-radius:50%;color:var(--card);font:700 15px Fraunces,serif;flex:none;}
  .rep-row{display:flex;gap:14px;align-items:center;}
  .rep-stats{display:flex;flex-direction:column;gap:5px;font-size:14.5px;}
  .rep-stats div{display:flex;align-items:center;gap:6px;}
  .rep-lvl{margin-top:4px;color:var(--accent-text);} .rep-lvl span{color:var(--ink-soft);font-size:13px;}
  .rep-note{font-size:13px;color:var(--ink-soft);}


  .skip-chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin:12px 0;}
  .skip-chips .chip{min-width:48px;min-height:40px;cursor:pointer;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--retry-text);border-radius:10px;font:600 14px 'IBM Plex Mono',monospace;}
  .skip-btns{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-top:12px;}


  .kb-toggle{border:none;background:transparent;font-size:15px;cursor:pointer;padding:0 2px;vertical-align:middle;opacity:.7;}
  .vkb{position:fixed;left:0;right:0;bottom:0;z-index:80;background:var(--paper-2);border-top:1px solid var(--rule);box-shadow:0 -6px 20px rgba(0,0,0,.12);padding:6px 6px 8px;display:none;}
  .vkb.show{display:block;}
  .vkb-top{display:flex;justify-content:space-between;align-items:center;max-width:640px;margin:0 auto 4px;font:600 12px 'Source Sans 3',sans-serif;color:var(--ink-soft);}
  .vkb-link{border:none;background:none;color:var(--accent-text);font:600 12px 'Source Sans 3',sans-serif;cursor:pointer;text-decoration:underline;}
  .vkb-row{display:flex;gap:5px;max-width:640px;margin:0 auto 5px;}
  .vkb-k{flex:1;min-height:42px;border:1px solid var(--rule);border-radius:8px;background:var(--card);color:var(--ink);font:600 17px 'IBM Plex Mono',monospace;cursor:pointer;padding:0;}
  .vkb-k.fn{font:600 13px 'Source Sans 3',sans-serif;background:var(--gold-soft);}
  .vkb-k.done{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .vkb-k:active{transform:scale(.96);}
  body.kb-open .wrap{padding-bottom:360px;}
  body.kb-open .fab{display:none;}
  .tool-bar{display:flex;gap:8px;flex-wrap:wrap;margin:-4px 0 10px;}
  .tool-btn{min-height:36px;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--ink);border-radius:18px;padding:4px 12px;font:600 13.5px 'Source Sans 3',sans-serif;cursor:pointer;}
  .tool-panel{position:fixed;z-index:85;background:var(--card);border:1px solid var(--rule);border-radius:14px;box-shadow:0 10px 30px rgba(0,0,0,.25);display:none;}
  .tool-panel.show{display:block;}
  .tp-head{display:flex;align-items:center;gap:8px;padding:8px 10px;border-bottom:1px solid var(--rule);font:600 14px 'Source Sans 3',sans-serif;}
  .tp-note{font-size:12px;color:var(--ink-soft);font-weight:500;}
  .tp-x{margin-left:auto;border:1px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:8px;min-height:32px;padding:2px 10px;cursor:pointer;font:600 13px 'Source Sans 3',sans-serif;}
  .tp-x + .tp-x{margin-left:0;}
  .calc{right:12px;bottom:84px;width:min(330px,calc(100vw - 24px));}
  body.calc-open .wrap{padding-bottom:440px;}
  body.calc-open .fab{display:none;}
  @media (max-width:640px){ .calc{left:6px;right:6px;width:auto;} .calc-keys button{min-height:36px;} }
  .calc-disp{padding:8px 12px;text-align:right;background:var(--paper-2);}
  .calc-expr{font:500 13px 'IBM Plex Mono',monospace;color:var(--ink-soft);min-height:18px;word-break:break-all;}
  .calc-res{font:600 24px 'IBM Plex Mono',monospace;color:var(--ink);word-break:break-all;}
  .calc-keys{display:grid;grid-template-columns:repeat(6,1fr);gap:5px;padding:8px;}
  .calc-keys button{min-height:40px;border:1px solid var(--rule);border-radius:8px;background:var(--card);color:var(--ink);font:600 14px 'IBM Plex Mono',monospace;cursor:pointer;padding:0;}
  .calc-keys button.fn{background:var(--gold-soft);font-family:'Source Sans 3',sans-serif;font-size:13px;}
  .calc-keys button.eq{grid-column:span 2;background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .desmos{left:50%;top:50%;transform:translate(-50%,-50%);width:min(760px,calc(100vw - 16px));height:min(560px,calc(100vh - 90px));flex-direction:column;}
  .desmos.show{display:flex;}
  #desmosBox{flex:1;min-height:0;border-radius:0 0 14px 14px;overflow:hidden;}
  .desmos-msg{padding:24px;text-align:center;color:var(--ink-soft);}
  .chip[data-status="skipped"]{cursor:pointer;}
  .chip[data-status="answered"]{border-color:var(--accent-text);color:var(--accent-text);}


  button.crest-home{border:none;padding:0;position:relative;cursor:pointer;transition:transform .15s ease;}
  button.crest-home:hover,button.crest-home:focus-visible{transform:scale(1.06);outline:2px solid var(--gold);outline-offset:2px;}
  .crest-h{position:absolute;right:-7px;bottom:-7px;width:18px;height:18px;border-radius:50%;background:#F4EFDF;color:var(--navy);font:700 12px/18px 'Source Sans 3',sans-serif;text-align:center;box-shadow:0 1px 3px rgba(0,0,0,.3);}
  .brand .brand-row{position:relative;}
  .bmasw{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);display:flex;flex-shrink:0;white-space:nowrap;align-items:center;gap:6px;background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.25);border-radius:99px;padding:5px 14px;color:#F4EFDF;}
  .bmasw-ic{font-size:16px;} .bmasw-t{font:600 20px 'IBM Plex Mono',monospace;letter-spacing:.02em;min-width:62px;text-align:center;}
  .bmasw-b{border:none;background:rgba(255,255,255,.18);color:#F4EFDF;border-radius:50%;width:30px;height:30px;cursor:pointer;font-size:13px;}
  .bmasw.off{display:none;}
  @media (max-width:560px){ .bmasw{position:static;transform:none;margin-left:auto;padding:4px 5px 4px 8px;gap:4px;} .bmasw-ic{display:none;} .bmasw-t{font-size:16px;min-width:48px;} .bmasw-b{width:26px;height:26px;} .brand .series-name{font-size:15px;} .brand .brand-name{font-size:10.5px;} .brand .brand-row>div:not(.bmasw){min-width:0;} }
  .bmasw-done{font:600 15px 'IBM Plex Mono',monospace;color:var(--accent-text);margin:4px 0 8px;}
  .sp-fab{position:fixed;left:14px;bottom:84px;z-index:60;border:1.5px solid var(--navy-2);background:var(--card);color:var(--ink);border-radius:99px;padding:9px 14px;font:700 14px 'Source Sans 3',sans-serif;box-shadow:0 4px 14px rgba(0,0,0,.15);cursor:pointer;}
  .sp-fab.on{background:var(--navy);color:#F4EFDF;}
  body.kb-open .sp-fab{display:none;}
  .sp-canvas{position:absolute;z-index:55;display:none;touch-action:none;cursor:crosshair;}
  .sp-canvas.passive{pointer-events:none;cursor:default;}
  .sp-bar{position:fixed;top:8px;left:8px;right:8px;margin:0 auto;width:max-content;z-index:90;display:none;align-items:center;gap:6px;background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:6px 8px;box-shadow:0 6px 20px rgba(0,0,0,.2);max-width:calc(100vw - 16px);flex-wrap:wrap;justify-content:center;}
  .sp-lbl{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);margin-right:2px;}
  .sp-pen,.sp-tool{width:38px;height:38px;border-radius:10px;border:1.5px solid var(--rule);background:var(--paper);cursor:pointer;display:inline-flex;align-items:center;justify-content:center;font-size:17px;padding:0;color:var(--ink);}
  .sp-pen i{width:20px;height:20px;border-radius:50%;display:block;}
  .sp-pen.on,.sp-tool.on{border-color:var(--navy-2);box-shadow:0 0 0 3px var(--gold-soft);}
  @media (max-width:560px){ .sp-lbl{display:none;} .sp-pen,.sp-tool{width:34px;height:34px;} .sp-fab span{display:none;} }

  /* larger reading sizes */
  .chapter-eyebrow{font-size:13.5px;}
  .chapter-title{font-size:36px;line-height:1.15;}
  .chapter-sub{font-size:16.5px;}
  .tab-btn{font-size:15.5px;}
  .sec-sub{font-size:15px;}
  .qtext{font-size:19px;line-height:1.55;}
  .qnum{width:36px;height:36px;font-size:16px;}
  .opt{font-size:17.5px;padding:12px 14px;}
  .step-line{font-size:17.5px;line-height:2;}
  .blank-input{font-size:16px;}
  .sol-line{font-size:16.5px;}
  .feedback{font-size:15px;}
  .note h2{font-size:28px;}
  .note h4{font-size:19px;}
  .note p,.note li{font-size:17.5px;line-height:1.65;}
  .note .lt{font-size:15.5px;}
  .ex .exh{font-size:18px;} .ex .exl{font-size:16.5px;}
  .keybox{font-size:16.5px;}
  .ttab{font-size:15.5px;}
  .hub-card h3{font-size:21px;} .hub-card p{font-size:15.5px;} .hub-btn{font-size:15px;}
  @media (max-width:480px){ .chapter-title{font-size:30px;} .qtext{font-size:18px;} .opt,.step-line{font-size:16.5px;} .note h2{font-size:24px;} .note p,.note li{font-size:16.5px;} }

  /* v4 celebration */
  .v4conf{position:fixed;inset:0;width:100vw;height:100vh;pointer-events:none;z-index:9999;}
  .v4ban{background:linear-gradient(135deg,var(--gold-soft),var(--card));border:2px solid var(--gold);border-radius:18px;padding:18px 14px 16px;margin:-4px 0 18px;text-align:center;animation:v4pop .55s cubic-bezier(.2,1.6,.4,1);}
  @keyframes v4pop{0%{transform:scale(.6);opacity:0}100%{transform:scale(1);opacity:1}}
  .v4trophy{font-size:54px;line-height:1;animation:v4bob 1.4s ease-in-out infinite;}
  @keyframes v4bob{0%,100%{transform:translateY(0) rotate(-6deg)}50%{transform:translateY(-6px) rotate(6deg)}}
  .v4h{font-size:28px;font-weight:800;color:var(--accent-text);margin-top:6px;}
  .v4m{font-size:19px;color:var(--ink);margin-top:4px;}
  .v4pills{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:12px;}
  .v4p{font-size:16px;font-weight:700;border-radius:999px;padding:6px 12px;}
  .v4p.g{background:var(--success-soft);color:var(--success);} .v4p.o{background:var(--gold-soft);color:var(--retry-text);}
  .v4p.r{background:var(--danger-soft);color:var(--danger);} .v4p.s{background:var(--rule);color:var(--ink);}
  .v4next{margin-top:14px;} .v4go{font-size:18px !important;padding:13px 20px !important;}
  .v4rec td.v4g{color:var(--success);font-weight:700;} .v4rec td.v4o{color:var(--retry-text);font-weight:700;} .v4rec td.v4r{color:var(--danger);font-weight:700;}
  .v4rec tr.v4tot td{font-weight:800;border-top:2px solid var(--rule);}
  .v4rec th{font-size:12.5px;padding:6px 3px !important;white-space:nowrap;} .v4rec td{font-size:15px;padding:7px 3px !important;text-align:center;}
  .v4rec td:first-child,.v4rec th:first-child{text-align:left;white-space:normal;min-width:92px;max-width:150px;font-size:14.5px;}
  @media(max-width:460px){ .v4left{display:none;} }
  .v4leg{font-size:14.5px;color:var(--ink-soft);margin:2px 0 8px;line-height:1.5;}
  body.v4done .fab-q,body.v4done #qFab{display:none;}
  .v4sum{font-size:16px;margin-top:10px;}
  /* v4 larger reading sizes */
  body{font-size:18px;}
  .chapter-title{font-size:38px !important;line-height:1.15;}
  .chapter-sub{font-size:17px !important;}
  .tab-btn{font-size:16.5px !important;}
  .sec-sub{font-size:16.5px !important;}
  .qtext{font-size:21px !important;line-height:1.6 !important;}
  .qnum{width:38px !important;height:38px !important;font-size:17px !important;}
  .opt{font-size:19.5px !important;padding:13px 15px !important;}
  .step-line{font-size:19.5px !important;line-height:2.1 !important;}
  .blank-input{font-size:18px !important;min-height:40px;}
  .sol-line{font-size:18px !important;line-height:1.6;}
  .feedback{font-size:16.5px !important;}
  .note h2{font-size:29px !important;}
  .note h3{font-size:22px !important;}
  .note h4{font-size:20px !important;}
  .note p,.note li,.note td,.note th{font-size:18.5px !important;line-height:1.7 !important;}
  .ex .exh{font-size:19px !important;} .ex .exl{font-size:18px !important;}
  .keybox{font-size:18px !important;}
  .hub-card p{font-size:17.5px !important;} .hub-btn{font-size:16.5px !important;}
  .review-q,.review-ans{font-size:17.5px !important;}
  .rec-table td{font-size:16px;}
  .vkb-k{font-size:19px !important;}
  .fq{font-size:0.95em;}

  header.brand{background:linear-gradient(180deg,rgba(20,20,20,.55),rgba(20,20,20,.78)),url('data:image/jpeg;base64,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') center/cover no-repeat, #2b2b2b !important;}
  .crest,button.crest-home{width:58px !important;height:54px !important;background:transparent !important;border-radius:12px !important;}
  .crest img{width:58px;height:53px;display:block;filter:drop-shadow(0 1px 2px rgba(0,0,0,.5));}
  button.crest-home .crest-h{right:-4px;bottom:-4px;}
  .brand-name{color:#F4EFDF !important;font-family:'Fraunces',Georgia,serif;font-size:13px !important;letter-spacing:.06em;}
  .series-name{color:#E8D9A8;}
  .chapter-eyebrow{color:#D9D4C7 !important;}
  .chapter-sub{color:#F1D58A !important;}
</style>
</head>
<body>
<header class="brand">
  <div class="brand-row">
    <div class="crest"><img src="data:image/png;base64,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" alt="Brain and Mind"></div>
    <div>
      <div class="brand-name">Brain &amp; Mind Academy</div>
      <div class="series-name">Sopaan <span style="font-weight:400;font-size:14px;color:#CFD7EA;">Practice Series</span></div>
    </div>
  </div>
  <div class="chapter-eyebrow">AP Calculus AB / BC · Topic sheet</div>
  <div class="chapter-title">Differentiation</div>
  <div class="chapter-sub">Theory Notes · Step-by-step Practice · Test</div><div class="chapter-credit">Theory · Step-by-step practice · Learning assessment</div>
  <div class="chapter-progress">
    <div class="cp-track"><div class="cp-fill" id="cpFill"></div></div>
    <div class="cp-label" id="cpLabel">0% complete</div>
  </div>
  <div class="who-row"><button class="mode-pill" id="modePill" hidden>Choose a mode</button><span class="who" id="whoBar" hidden></span></div>
</header>

<nav class="tabbar"><div class="tabbar-inner" id="tabbar"></div></nav>
<div class="sec-sub" id="secSub"></div><div class="slide-progress"><div class="sp-track"><div class="sp-fill" id="spFill"></div></div><div class="sp-label" id="spLabel">Question 1 of 49</div></div>
<div class="wrap" id="wrap"></div>
<footer class="brandfoot">Brain &amp; Mind Academy · Sopaan Practice Series<br>Theory notes, practice questions and worked solutions by Brain &amp; Mind Academy. Sheets 6 and 9 include the Chain Rule practice problems from Paul Dawkins, <a href="https://tutorial.math.lamar.edu/problems/calci/chainrule.aspx">Paul’s Online Math Notes</a> (Lamar University).</footer>

<div class="navbar"><div class="navbar-inner" id="navbarInner"></div></div>
<button class="fab" id="paletteFab"><span>Questions</span><span class="fab-badge" id="fabBadge">0/49</span></button>

<div class="overlay" id="overlay">
  <div class="palette" role="dialog" aria-label="Question palette">
    <div class="palette-head"><h2 id="paletteTitle">Question palette</h2><button class="palette-close" id="paletteClose">&times;</button></div>
    <div class="palette-legend">
      <span><i class="dot current"></i>Current</span><span><i class="dot correct"></i>Correct</span>
      <span><i class="dot revealed"></i>Revealed</span><span><i class="dot skipped"></i>Skipped</span>
      <span><i class="dot locked"></i>Locked</span>
    </div>
    <div class="chip-grid" id="paletteBody"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ================= audio ================= */
var audioCtx=null;
function ensureAudio(){ if(!audioCtx){ try{ audioCtx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return audioCtx; }
function playTone(freqs,dur,type){
  var ctx=ensureAudio(); if(!ctx) return;
  try{
    var t0=ctx.currentTime;
    freqs.forEach(function(f,i){
      var o=ctx.createOscillator(), g=ctx.createGain();
      o.type=type||'sine'; o.frequency.value=f;
      var start=t0+i*dur;
      g.gain.setValueAtTime(0.0001,start);
      g.gain.exponentialRampToValueAtTime(0.16,start+0.02);
      g.gain.exponentialRampToValueAtTime(0.0001,start+dur);
      o.connect(g); g.connect(ctx.destination);
      o.start(start); o.stop(start+dur+0.02);
    });
  }catch(e){}
}
function playSuccess(){ playTone([523.25,659.25,783.99],0.11,'sine'); }
function playWrong(){ playTone([220,185],0.14,'square'); }
function playReveal(){ playTone([300,220],0.16,'triangle'); }

/* ================= helpers ================= */
function norm(s){
  return String(s===undefined||s===null?'':s).trim().toLowerCase().replace(/\s+/g,'')
    .replace(/[×∗*·]/g,'x').replace(/÷/g,'/').replace(/–|—|−/g,'-')
    .replace(/[²]/g,'^2').replace(/[³]/g,'^3').replace(/[⁴]/g,'^4').replace(/[⁵]/g,'^5')
    .replace(/[⁶]/g,'^6').replace(/[⁷]/g,'^7').replace(/[⁸]/g,'^8').replace(/[⁹]/g,'^9')
    .replace(/\^/g,'');
}
function parseNum(s){
  if(s===undefined||s===null) return null;
  var t=String(s).trim().replace(/,/g,'').replace(/[−–—]/g,'-').replace(/\s+/g,''); if(t==='') return null;
  var neg=false; if(t[0]==='-'){neg=true;t=t.slice(1);}
  var m=t.match(/^(\d+)\/(\d+)$/);
  if(m){ var v=parseInt(m[1],10)/parseInt(m[2],10); return neg?-v:v; }
  if(/^\d+(\.\d+)?$/.test(t)){ var v2=parseFloat(t); return neg?-v2:v2; }
  return null;
}
/* ---- expression checker: compares answers like (P-2w)/2 and P/2-w at random values ---- */
function exprPrep(s){
  return String(s).toLowerCase().replace(/\s+/g,'').replace(/^[a-z]\(x\)=/i,'').replace(/^[a-z]=/i,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/⁴/g,'^4').replace(/⁵/g,'^5').replace(/⁶/g,'^6').replace(/⁷/g,'^7').replace(/⁸/g,'^8').replace(/⁹/g,'^9').replace(/π/g,'#').replace(/pi/gi,'#').replace(/½/g,'(1/2)');
}
function exprCompile(src){
  var s=exprPrep(src), i=0, toks=[], absDepth=0;
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length && /[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(/[a-zA-Z#]/.test(ch)){ toks.push({k:'v',v:ch}); i++; continue; }
    if(ch==='|'){ var pv=toks[toks.length-1]; var opn=(absDepth===0)||!pv||('+-*/^(['.indexOf(pv.k)>=0); if(opn){ absDepth++; toks.push({k:'['}); } else { absDepth--; toks.push({k:']'}); } i++; continue; }
    if('+-*/^()'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  var out=[];
  for(var t=0;t<toks.length;t++){
    var a=toks[t], b=out[out.length-1];
    if(b && (b.k==='n'||b.k==='v'||b.k===')'||b.k===']') && (a.k==='n'||a.k==='v'||a.k==='('||a.k==='[')) out.push({k:'&'});
    out.push(a);
  }
  var p=0;
  function peek(){ return out[p]; }
  function parseE(){ var n=parseT(); while(peek() && (peek().k==='+'||peek().k==='-')){ var o=out[p++].k, r=parseT(); n=(function(l,r,o){return function(e){ return o==='+'?l(e)+r(e):l(e)-r(e); };})(n,r,o); } return n; }
  function parseI(){ var n=parseU(); while(peek() && peek().k==='&'){ p++; var r=parseP(); n=(function(l,r){return function(e){ return l(e)*r(e); };})(n,r); } return n; }
  function parseT(){ var n=parseI(); while(peek() && (peek().k==='*'||peek().k==='/')){ var o=out[p++].k, r=parseI(); n=(function(l,r,o){return function(e){ return o==='*'?l(e)*r(e):l(e)/r(e); };})(n,r,o); } return n; }
  function parseU(){ if(peek() && peek().k==='-'){ p++; var u=parseU(); return function(e){ return -u(e); }; } if(peek() && peek().k==='+'){ p++; return parseU(); } return parseP(); }
  function parseP(){ var b=parseA(); if(peek() && peek().k==='^'){ p++; var x=parseU(); return function(e){ return Math.pow(b(e),x(e)); }; } return b; }
  function parseA(){
    var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){ return t.v; };
    if(t.k==='v') return t.v==='#' ? function(){ return Math.PI; } : function(e){ return e[t.v]; };
    if(t.k==='('){ var n=parseE(); if(!peek()||peek().k!==')') throw 0; p++; return n; }
    if(t.k==='['){ var m=parseE(); if(!peek()||peek().k!==']') throw 0; p++; return function(e){ return Math.abs(m(e)); }; }
    throw 0;
  }
  try{ var f=parseE(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function exprEqual(input,answer){
  var f=exprCompile(input), g=exprCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<8;trial++){
    var env={}; 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=1.3+Math.random()*4.1; });
    var x=f(env), y=g(env);
    if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-7*Math.max(1,Math.abs(x),Math.abs(y))) return false;
    hits++;
  }
  return hits>=3;
}
function wordsNorm(s){ return String(s||'').toLowerCase().replace(/\band\b/g,' ').replace(/[^a-z]/g,''); }
function listNorm(s){ return (String(s||'').replace(/[−–—]/g,'-').replace(/(\d) (?=\d{3}\b)/g,'$1').match(/-?\d+(\.\d+)?/g)||[]).join(','); }
function powNorm(s){ return String(s||'').toLowerCase().replace(/\s+/g,'').replace(/[×∗*·.]/g,'x').replace(/[⁰¹²³⁴⁵⁶⁷⁸⁹]+/g,function(m){ return '^'+m.split('').map(function(c){ return '⁰¹²³⁴⁵⁶⁷⁸⁹'.indexOf(c); }).join(''); }).replace(/\^1(?!\d)/g,''); }
function fr(s){ return String(s).replace(/\{(\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>').replace(/\{(\d+)\/(\d+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); }
function gcdI(a,b){ a=Math.abs(a); b=Math.abs(b); while(b){ var t=a%b; a=b; b=t; } return a; }
function fracParse(s){ s=String(s===undefined||s===null?'':s).trim().replace(/[\u2044\u2215\u00f7]/g,'/').replace(/\s+/g,' ').replace(/\s*\/\s*/g,'/'); var m;
  if((m=s.match(/^(-?\d+)$/))) return {v:+m[1],form:'int',n:+m[1],d:1};
  if((m=s.match(/^(-?\d+)\/(\d+)$/))){ if(+m[2]===0) return null; return {v:m[1]/m[2],form:'frac',n:+m[1],d:+m[2]}; }
  if((m=s.match(/^(-?)(\d+)(?: |\+)(\d+)\/(\d+)$/))){ if(+m[4]===0) return null; var sg=m[1]?-1:1; return {v:sg*(+m[2]+m[3]/m[4]),form:'mixed',w:sg*m[2],n:+m[3],d:+m[4]}; }
  if((m=s.match(/^-?\d*\.\d+$/))) return {v:parseFloat(s),form:'dec'};
  return null; }
function fracOK(mode,input,answer){
  if(mode==='flist'){ var A=String(input).split(/[,;]/).map(function(x){return x.trim();}).filter(Boolean), K=String(answer).split(/[,;]/).map(function(x){return x.trim();});
    if(A.length!==K.length) return false; return A.every(function(x,i){ var a=fracParse(x), k=fracParse(K[i]); return a&&k&&Math.abs(a.v-k.v)<1e-9; }); }
  var a=fracParse(input), k=fracParse(answer); if(!a||!k) return false;
  var same=Math.abs(a.v-k.v)<1e-9; if(!same) return false;
  if(mode==='fv') return true;
  if(mode==='dec') return a.form==='dec'||a.form==='int';
  if(mode==='fe') return (a.form==='frac'&&k.form==='frac'&&a.n===k.n&&a.d===k.d)||(a.form==='int'&&k.form==='int');
  if(mode==='fi') return a.form==='frac'||(a.form==='int'&&k.form==='int');
  if(mode==='fl') return a.form==='int'||(a.form==='frac'&&gcdI(a.n,a.d)===1)||(a.form==='mixed'&&a.n<a.d&&gcdI(a.n,a.d)===1);
  if(mode==='fm') return a.form==='int'||(a.form==='mixed'&&a.n>0&&a.n<a.d&&gcdI(a.n,a.d)===1);
  return false; }
function answerMatches(input,answer,accept,expr){
  if(expr==='dec'||expr==='fv'||expr==='fe'||expr==='fl'||expr==='fm'||expr==='fi'||expr==='flist'){ if(input===undefined||input===null||String(input).trim()==='') return false; return fracOK(expr,input,answer); }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  if(expr==='words'){ return [answer].concat(accept||[]).some(function(a){ if(/\d/.test(a)) return norm(a)===norm(input); var w=wordsNorm(a); return w!=='' && w===wordsNorm(input); }); }
  if(expr==='list'){ return [answer].concat(accept||[]).some(function(a){ return listNorm(a)===listNorm(input); }); }
  if(expr==='pow'){ return [answer].concat(accept||[]).some(function(a){ return powNorm(a)===powNorm(input); }); }
  if(expr==='time'){ var tn=function(x){ var t=String(x).toLowerCase().replace(/[\s.]/g,'').replace(/[:h]/g,''); if(/^\d{3}(am|pm)?$/.test(t)) t='0'+t; return t; }; return [answer].concat(accept||[]).some(function(a){ return tn(a)===tn(input); }); }
  if(expr==='glist'){ var gn=function(x){ return String(x).toUpperCase().split(/[\s,;]+/).filter(Boolean).sort().join(','); }; return [answer].concat(accept||[]).some(function(a){ return gn(a)===gn(input); }); }
  if(expr==='coord'){ var cn=function(x){ return String(x).replace(/[\u2212\u2013\u2014]/g,'-').replace(/[\s()\[\]]/g,''); }; return [answer].concat(accept||[]).some(function(a){ return cn(a)===cn(input); }); }
  if(expr==='dlist'){ var dn=function(x){ return (String(x).replace(/[−–—]/g,'-').match(/-?\d*\.?\d+/g)||[]).map(Number).join(','); }; return [answer].concat(accept||[]).some(function(a){ return dn(a)===dn(input); }); }
  if(expr==='set'){ var sn=function(x){ return (String(x).match(/-?\d+/g)||[]).map(Number).sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return sn(a)===sn(input); }); }
  if(expr==='primes'){ var pn=function(x){ var t=powNorm(x).replace(/[^0-9x^]/g,''); var out=[]; t.split('x').forEach(function(tok){ if(!tok) return; var m=tok.split('^'); var b=+m[0], e=m[1]?+m[1]:1; for(var i=0;i<e;i++) out.push(b); }); return out.sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return pn(a)===pn(input); }); }
  if(expr==='angle'){ var an=function(x){ return String(x).toUpperCase().replace(/[^A-Z]/g,''); }; var k=an(answer), v=an(input); return v===k || v===k.split('').reverse().join(''); }
  if(expr==='trans'){ var tv=function(x){ var s=String(x).toLowerCase().replace(/[−–—]/g,'-').replace(/\b(units?|squares?|and|then|steps?|to|the|a)\b/g,' ').replace(/[,;.]/g,' '); var re=/(\d+)\s*(right|left|up|down|r|l|u|d)\b/g, m, dx=0, dy=0, n=0; while((m=re.exec(s))){ var v=+m[1], d=m[2][0]; if(d==='r')dx+=v; else if(d==='l')dx-=v; else if(d==='u')dy+=v; else dy-=v; n++; } if(!n||s.replace(re,'').replace(/\s+/g,'')!=='') return null; return dx+','+dy; }; var ti=tv(input); return ti!==null && [answer].concat(accept||[]).some(function(a){ return tv(a)===ti; }); }
  if(expr==='rot'){ var rv=function(x){ var s=String(x).toLowerCase().replace(/quarter[\s-]*turn/g,'90').replace(/half[\s-]*turn/g,'180').replace(/three[\s-]*quarter[\s-]*turn/g,'270'); var m=s.match(/\b(90|180|270)\b/); if(!m) return null; var a=+m[1]; if(a===180) return '180'; var dir=/anti|counter|acw|ccw/.test(s)?-1:(/clockwise|\bcw\b/.test(s)?1:0); if(!dir) return null; return String(((a*dir)%360+360)%360); }; var ri=rv(input); return ri!==null && ri===rv(answer); }
  if(expr==='expanded'){ var f=function(x){ return String(x).replace(/\s+/g,'').replace(/,/g,''); }; return [answer].concat(accept||[]).some(function(a){ return f(a)===f(input); }); }
  if(expr===true && input!==undefined && input!==null && String(input).trim()!==''){
    if(exprEqual(input,answer)) return true;
    var alt=String(input).replace(/\/\s*(\d+(?:\.\d+)?)\s*([a-zA-Z(])/g,'/$1*$2'); if(alt!==String(input) && exprEqual(alt,answer)) return true;
    return (accept||[]).some(function(a){ return exprEqual(input,a); });
  }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  var n1=parseNum(input), n2=parseNum(answer);
  if(n1!==null && n2!==null){ if(Math.abs(n1-n2)<1e-3) return true; return (accept||[]).some(function(a){ var n3=parseNum(a); return n3!==null && Math.abs(n1-n3)<1e-3; }); }
  var cands=[answer].concat(accept||[]); var ni=norm(input);
  for(var i=0;i<cands.length;i++){ if(norm(cands[i])===ni) return true; }
  return false;
}
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;'); }

/* ================= DATA ================= */
var AR_OPTIONS = ["Both A and R are true, and R is the correct explanation of A","Both A and R are true, but R is NOT the correct explanation of A","A is true but R is false","A is false but R is true"];
var THEORY = "<div class=\"hub\"><div class=\"hub-card\"><h3>📖 Theory notes</h3><p>Notes for every part of differentiation: definitions, rule tables, common mistakes and worked examples with every line shown.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-jump=\"n1\">1 · Definition of the derivative</button><button class=\"hub-btn\" data-jump=\"n2\">2 · Power, constant and sum rules</button><button class=\"hub-btn\" data-jump=\"n3\">3 · Product and quotient rules</button><button class=\"hub-btn\" data-jump=\"n4\">4 · Trig, exponential and log derivatives</button><button class=\"hub-btn\" data-jump=\"n5\">5 · Chain rule</button><button class=\"hub-btn\" data-jump=\"n6\">6 · Chain rule: Paul’s problems</button><button class=\"hub-btn\" data-jump=\"n7\">7 · Implicit and higher derivatives</button><button class=\"hub-btn\" data-jump=\"n8\">8 · Inverses, tables and graphs</button><button class=\"hub-btn\" data-jump=\"n9\">9 · Using derivatives</button></div></div><div class=\"hub-card\"><h3>🎯 Step-by-step practice</h3><p>Nine practice sheets, from the limit definition to the chain rule and its uses. Multiple-choice questions alternate with fill-ins that walk you through one step at a time. Tap a blank for the calculus keyboard (eˣ, √, ln, trig).</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s1\">1 · Definition of the derivative</button><button class=\"hub-btn\" data-go=\"s2\">2 · Power, constant and sum rules</button><button class=\"hub-btn\" data-go=\"s3\">3 · Product and quotient rules</button><button class=\"hub-btn\" data-go=\"s4\">4 · Trig, exponential and log derivatives</button><button class=\"hub-btn\" data-go=\"s5\">5 · Chain rule</button><button class=\"hub-btn\" data-go=\"s6\">6 · Chain rule: Paul’s problems</button><button class=\"hub-btn\" data-go=\"s7\">7 · Implicit and higher derivatives</button><button class=\"hub-btn\" data-go=\"s8\">8 · Inverses, tables and graphs</button><button class=\"hub-btn\" data-go=\"s9\">9 · Using derivatives</button></div></div><div class=\"hub-card\"><h3>📝 Test</h3><p>Four assessments mixing the whole topic, one per skill area. Take them in Quiz mode, then open the report to see your results.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s10\">A · Knowing and understanding</button><button class=\"hub-btn\" data-go=\"s11\">B · Investigating patterns</button><button class=\"hub-btn\" data-go=\"s12\">C · Communicating</button><button class=\"hub-btn\" data-go=\"s13\">D · Applying mathematics in real-life contexts</button><button class=\"hub-btn primary\" data-go=\"report\">📊 View my report</button></div></div></div><section class=\"note\" id=\"nintro\"><h2>What is a derivative?</h2><p>The <b>derivative</b> f′(x) measures how fast f(x) changes as x changes: it is the slope of the tangent line to the graph of f at x, and the instantaneous rate of change of f.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Notation</th><th>Read as</th></tr><tr><td>f′(x)</td><td>“f prime of x”</td></tr><tr><td>dy/dx</td><td>“dee y by dee x”</td></tr><tr><td>d/dx [f(x)]</td><td>“the derivative of f(x) with respect to x”</td></tr><tr><td>f″(x), d²y/dx²</td><td>second derivative</td></tr></table></div><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Assessment</th><th>Skill area</th></tr><tr><td>A</td><td>Knowing and understanding the rules</td></tr><tr><td>B</td><td>Investigating patterns</td></tr><tr><td>C</td><td>Communicating: notation, explaining, spotting errors</td></tr><tr><td>D</td><td>Applying derivatives in real-life contexts</td></tr></table></div><p><b>Typing answers:</b> use ^ for powers, sqrt( ) or √ for roots, e^( ) for exponentials, ln( ), sin( ), cos( ), tan( ). Put brackets round fractions that multiply: type (2/3)x, not 2/3x. Any correct equivalent form is accepted.</p><p style=\"font-size:15px;color:var(--ink-soft)\">Practice sheet 6 and the Paul problems in sheet 9 are the Chain Rule practice problems from Paul Dawkins, <i>Paul’s Online Math Notes</i> (tutorial.math.lamar.edu), with worked solutions written by Brain &amp; Mind Academy.</p></section><section class=\"note\" id=\"n1\"><h2>1 · Definition of the derivative</h2><p class=\"lt\"><b>Learning target:</b> I can find f′(x) from the limit definition, tell average from instantaneous rate of change, read tangent slopes from a graph and decide where a function is differentiable.</p><div class=\"keybox\"><b>Definition.</b> The derivative of f at x is<br><span style=\"font-size:17px\">f′(x) = lim<sub>h→0</sub> <span class=\"fq\"><span>f(x + h) − f(x)</span><span>h</span></span></span><br>provided the limit exists. At a single point x = a: f′(a) = lim<sub>h→0</sub> <span class=\"fq\"><span>f(a + h) − f(a)</span><span>h</span></span> = lim<sub>x→a</sub> <span class=\"fq\"><span>f(x) − f(a)</span><span>x − a</span></span>.</div><p>The fraction (f(x + h) − f(x))/h is the slope of a <b>secant line</b> through two points of the graph, a distance h apart. As h → 0 the second point slides onto the first and the secant turns into the <b>tangent line</b>. So f′(a) is the slope of the tangent at x = a.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Idea</th><th>Formula</th><th>Picture</th></tr><tr><td>Average rate of change on [a, b]</td><td>(f(b) − f(a))/(b − a)</td><td>slope of the secant line</td></tr><tr><td>Instantaneous rate of change at a</td><td>f′(a)</td><td>slope of the tangent line</td></tr><tr><td>Velocity from position s(t)</td><td>v(t) = s′(t)</td><td>average velocity → instantaneous velocity</td></tr></table></div><h4>Four steps for the limit definition</h4><div class=\"keybox\">1. Write f(x + h) and expand it.<br>2. Subtract f(x): every term without h cancels.<br>3. Divide by h (cancel the common factor h).<br>4. Let h → 0.</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · f(x) = x² + 4x</div><div class=\"exl\">f(x + h) = (x + h)² + 4(x + h) = x² + 2xh + h² + 4x + 4h<br>f(x + h) − f(x) = 2xh + h² + 4h<br>(f(x + h) − f(x))/h = 2x + h + 4<br>Let h → 0:  f′(x) = <b>2x + 4</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · f(x) = √x (multiply by the conjugate)</div><div class=\"exl\">(√(x + h) − √x)/h × (√(x + h) + √x)/(√(x + h) + √x) = h/(h(√(x + h) + √x))<br>= 1/(√(x + h) + √x)<br>Let h → 0:  f′(x) = <b>1/(2√x)</b></div></div><h4>Differentiable or not?</h4><p>If f is differentiable at a, then f is continuous at a. The converse is false: a continuous graph can still fail to have a tangent slope.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>f is not differentiable at a when…</th><th>Example</th></tr><tr><td>there is a corner (different slopes on each side)</td><td>|x| at x = 0</td></tr><tr><td>there is a cusp</td><td>x<sup>2/3</sup> at x = 0</td></tr><tr><td>the tangent is vertical</td><td>∛x at x = 0</td></tr><tr><td>f is not continuous</td><td>a jump or a hole</td></tr></table></div><p><b>Piecewise check at the join x = a:</b> (1) the two pieces give the same value at a (continuity); (2) the two pieces give the same slope at a. Both must hold.</p><div class=\"ex\"><div class=\"exh\">Worked example 3 · f(x) = x² for x ≤ 2, f(x) = 4x − 4 for x > 2</div><div class=\"exl\">Values: 2² = 4 and 4(2) − 4 = 4, so f is continuous at 2.<br>Slopes: (x²)′ = 2x gives 4 at x = 2; (4x − 4)′ = 4. Equal, so f is <b>differentiable</b> at x = 2.</div></div><p><b>Slopes from a graph:</b> draw (or use) the tangent line, pick two grid points on it and work out rise ÷ run. On a straight segment, f′ is just the slope of that segment; at a sharp corner f′ does not exist.</p><div class=\"keybox\"><b>Common mistakes.</b> Forgetting to subtract f(x) (the h-free terms must cancel). Dividing only one term by h. Putting h = 0 <i>before</i> cancelling, which gives 0/0. Confusing the average rate on an interval with the slope at a point.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s1\">Practise 1 →</button></div></section><section class=\"note\" id=\"n2\"><h2>2 · Power, constant and sum rules</h2><p class=\"lt\"><b>Learning target:</b> I can differentiate sums of powers (including negative and fractional powers), rewrite roots and quotients first, and use f′ for tangent lines, horizontal tangents and rates.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Rule</th><th>In symbols</th><th>Example</th></tr><tr><td>Constant</td><td>d/dx [c] = 0</td><td>d/dx [7] = 0</td></tr><tr><td>Power</td><td>d/dx [x<sup>n</sup>] = nx<sup>n−1</sup> (any real n)</td><td>d/dx [x<sup>5</sup>] = 5x<sup>4</sup></td></tr><tr><td>Constant multiple</td><td>d/dx [c·f] = c·f′</td><td>d/dx [3x<sup>4</sup>] = 12x<sup>3</sup></td></tr><tr><td>Sum and difference</td><td>(f ± g)′ = f′ ± g′</td><td>d/dx [x<sup>3</sup> − x] = 3x<sup>2</sup> − 1</td></tr></table></div><h4>Rewrite first, then differentiate</h4><p>The Power Rule needs the form c·x<sup>n</sup>. Turn roots into fractional powers and move powers of x out of a denominator as negative powers.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Original</th><th>Rewrite</th><th>Differentiate</th><th>Simplify</th></tr><tr><td>y = 4/x<sup>2</sup></td><td>y = 4x<sup>−2</sup></td><td>y′ = −8x<sup>−3</sup></td><td>y′ = −8/x<sup>3</sup></td></tr><tr><td>y = 6√x</td><td>y = 6x<sup>1/2</sup></td><td>y′ = 3x<sup>−1/2</sup></td><td>y′ = 3/√x</td></tr><tr><td>y = 1/(3∛x)</td><td>y = {1/3}x<sup>−1/3</sup></td><td>y′ = −{1/9}x<sup>−4/3</sup></td><td>y′ = −1/(9x∛x)</td></tr><tr><td>y = (x<sup>2</sup> + 5)/x</td><td>y = x + 5x<sup>−1</sup></td><td>y′ = 1 − 5x<sup>−2</sup></td><td>y′ = 1 − 5/x<sup>2</sup></td></tr></table></div><h4>Tangent lines, horizontal tangents and rates</h4><div class=\"keybox\">Tangent line at x = a: <b>y − f(a) = f′(a)(x − a)</b>.<br>Horizontal tangent: solve <b>f′(x) = 0</b>, then find the y-values from f.<br>Rate of change of y with respect to x: dy/dx, in (units of y) per (unit of x).</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Tangent to f(x) = x³ − 5x at x = 1</div><div class=\"exl\">f(1) = 1 − 5 = −4;  f′(x) = 3x² − 5, so f′(1) = −2.<br>y − (−4) = −2(x − 1)  ⇒  <b>y = −2x − 2</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Horizontal tangents of y = x³ − 12x</div><div class=\"exl\">y′ = 3x² − 12 = 3(x − 2)(x + 2) = 0  ⇒  x = −2 or x = 2<br>Points: <b>(−2, 16)</b> and <b>(2, −16)</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · A square of side s has area A = s²</div><div class=\"exl\">dA/ds = 2s.  At s = 5 cm: dA/ds = <b>10 cm² per cm</b>.<br>Meaning: when s = 5, the area grows about 10 cm² for each extra 1 cm of side.</div></div><div class=\"keybox\"><b>Common mistakes.</b> The derivative of a constant is 0, not the constant. For x<sup>−3</sup> the new power is −4 (one less), not −2. Do not differentiate the top and bottom of a fraction separately: rewrite it first. Remember to find the y-value as well when a question asks for a point.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s2\">Practise 2 →</button></div></section><section class=\"note\" id=\"n3\"><h2>3 · Product and quotient rules</h2><p class=\"lt\"><b>Learning target:</b> I can use the Product and Quotient Rules, evaluate f′(c), and recognise when rewriting is quicker than the Quotient Rule.</p><div class=\"keybox\"><b>Product Rule:</b> (fg)′ = f′g + fg′. &nbsp;“derivative of the first × second + first × derivative of the second”.<br><b>Quotient Rule:</b> (<span class=\"fq\"><span>f</span><span>g</span></span>)′ = <span class=\"fq\"><span>g f′ − f g′</span><span>g²</span></span>. &nbsp;“low d-high minus high d-low, over low squared”.</div><p>The derivative of a product is <b>not</b> the product of the derivatives: (x · x)′ = (x²)′ = 2x, but 1 · 1 = 1. In the Quotient Rule the order of the top matters, because of the minus sign.</p><div class=\"ex\"><div class=\"exh\">Worked example 1 · y = (x² + 1)(3x − 4)</div><div class=\"exl\">u = x² + 1, u′ = 2x;  v = 3x − 4, v′ = 3<br>y′ = 2x(3x − 4) + 3(x² + 1) = 6x² − 8x + 3x² + 3 = <b>9x² − 8x + 3</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · y = (2x + 1)/(x − 3)</div><div class=\"exl\">low = x − 3, d-low = 1;  high = 2x + 1, d-high = 2<br>y′ = ((x − 3)(2) − (2x + 1)(1))/(x − 3)² = <b>−7/(x − 3)²</b></div></div><h4>Rewrite instead of using the Quotient Rule</h4><p>When the denominator is a single term c·x<sup>n</sup>, divide it into each term of the top and use the Power Rule.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Original</th><th>Rewrite</th><th>Differentiate</th><th>Simplify</th></tr><tr><td>y = (x<sup>3</sup> + 2)/x</td><td>y = x<sup>2</sup> + 2x<sup>−1</sup></td><td>y′ = 2x − 2x<sup>−2</sup></td><td>y′ = 2x − 2/x<sup>2</sup></td></tr><tr><td>y = 7/(3x<sup>2</sup>)</td><td>y = {7/3}x<sup>−2</sup></td><td>y′ = −{14/3}x<sup>−3</sup></td><td>y′ = −14/(3x<sup>3</sup>)</td></tr><tr><td>y = (x − 4)/√x</td><td>y = x<sup>1/2</sup> − 4x<sup>−1/2</sup></td><td>y′ = {1/2}x<sup>−1/2</sup> + 2x<sup>−3/2</sup></td><td>y′ = (x + 4)/(2x√x)</td></tr></table></div><h4>Values of f′(c)</h4><p>Differentiate first, then substitute. With given values: (fg)′(c) = f′(c)g(c) + f(c)g′(c) and (f/g)′(c) = (g(c)f′(c) − f(c)g′(c))/g(c)².</p><div class=\"ex\"><div class=\"exh\">Worked example 3 · f(1) = 2, f′(1) = 3, g(1) = −1, g′(1) = 4</div><div class=\"exl\">(fg)′(1) = 3(−1) + 2(4) = <b>5</b><br>(f/g)′(1) = ((−1)(3) − 2(4))/(−1)² = <b>−11</b></div></div><div class=\"keybox\"><b>Common mistakes.</b> Writing (fg)′ = f′g′ or (f/g)′ = f′/g′. Swapping the order in the Quotient Rule (it flips the sign). Forgetting to square the denominator. Using the Quotient Rule when a constant is on the bottom: y = (x² + x)/5 is just {1/5}(x² + x).</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s3\">Practise 3 →</button></div></section><section class=\"note\" id=\"n4\"><h2>4 · Trig, exponential and log derivatives</h2><p class=\"lt\"><b>Learning target:</b> I can differentiate the six trig functions, eˣ, aˣ, ln x and logₐx, using log laws to simplify first.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Function</th><th>Derivative</th><th>Function</th><th>Derivative</th></tr><tr><td>sin x</td><td>cos x</td><td>csc x</td><td>−csc x cot x</td></tr><tr><td>cos x</td><td>−sin x</td><td>sec x</td><td>sec x tan x</td></tr><tr><td>tan x</td><td>sec<sup>2</sup> x</td><td>cot x</td><td>−csc<sup>2</sup> x</td></tr><tr><td>e<sup>x</sup></td><td>e<sup>x</sup></td><td>a<sup>x</sup></td><td>a<sup>x</sup> ln a</td></tr><tr><td>ln x</td><td>1/x</td><td>log<sub>a</sub> x</td><td>1/(x ln a)</td></tr></table></div><p><b>Memory aids.</b> Every “co-” function (cos, cot, csc) has a minus sign in its derivative. The pairs tan ↔ sec² and cot ↔ −csc² go together, and so do sec ↔ sec tan and csc ↔ −csc cot. Angles are in <b>radians</b>.</p><p><b>Why a<sup>x</sup> ln a?</b> a<sup>x</sup> = e<sup>x ln a</sup>, and ln a is just a constant. In the same way log<sub>a</sub> x = ln x / ln a.</p><h4>Use log laws before differentiating</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Law</th><th>Example</th></tr><tr><td>ln(AB) = ln A + ln B</td><td>ln(5x) = ln 5 + ln x</td></tr><tr><td>ln(A/B) = ln A − ln B</td><td>ln(x/e) = ln x − 1</td></tr><tr><td>ln(A<sup>k</sup>) = k ln A</td><td>ln(x<sup>6</sup>) = 6 ln x</td></tr><tr><td>ln(e<sup>k</sup>) = k</td><td>ln(e<sup>4x</sup>) = 4x</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 1 · y = ln(x³e<sup>2x</sup>)</div><div class=\"exl\">Simplify: y = ln(x³) + ln(e<sup>2x</sup>) = 3 ln x + 2x<br>y′ = <b>3/x + 2</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · y = x³ cos x (Product Rule)</div><div class=\"exl\">y′ = 3x² cos x + x³(−sin x) = <b>3x² cos x − x³ sin x</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · y = e<sup>x</sup>/x (Quotient Rule)</div><div class=\"exl\">y′ = (x · e<sup>x</sup> − e<sup>x</sup> · 1)/x² = <b>e<sup>x</sup>(x − 1)/x²</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 4 · y = 4<sup>x</sup> − log<sub>5</sub> x</div><div class=\"exl\">y′ = <b>4<sup>x</sup> ln 4 − 1/(x ln 5)</b></div></div><div class=\"keybox\"><b>Common mistakes.</b> d/dx [e<sup>x</sup>] is e<sup>x</sup>, not xe<sup>x−1</sup> (the Power Rule is for x<sup>n</sup>, not n<sup>x</sup>). d/dx [ln 7] = 0, because ln 7 is a number. ln(x + 3) is <b>not</b> ln x + ln 3. Forgetting the minus signs on the co-functions.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s4\">Practise 4 →</button></div></section><section class=\"note\" id=\"n5\"><h2>5 · Chain rule</h2><p class=\"lt\"><b>Learning target:</b> I can differentiate compositions (powers, trig, exponentials and logs of a function, and nested functions) and combine the Chain Rule with the Product and Quotient Rules.</p><div class=\"keybox\"><b>Chain Rule.</b> If y = f(u) and u = g(x), then <span style=\"font-size:17px\">dy/dx = dy/du · du/dx</span>, that is<br><span style=\"font-size:17px\">[f(g(x))]′ = f′(g(x)) · g′(x)</span><br>“derivative of the outside (inside left alone) × derivative of the inside”.</div><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Outer function</th><th>General rule (u = inner function)</th><th>Example</th></tr><tr><td>power u<sup>n</sup></td><td>n u<sup>n−1</sup> · u′</td><td>[(x² + 1)<sup>3</sup>]′ = 3(x² + 1)² · 2x</td></tr><tr><td>sin u, cos u</td><td>cos u · u′,  −sin u · u′</td><td>[sin 4x]′ = 4 cos 4x</td></tr><tr><td>tan u</td><td>sec<sup>2</sup> u · u′</td><td>[tan x³]′ = 3x² sec<sup>2</sup>(x³)</td></tr><tr><td>e<sup>u</sup></td><td>e<sup>u</sup> · u′</td><td>[e<sup>5x</sup>]′ = 5e<sup>5x</sup></td></tr><tr><td>a<sup>u</sup></td><td>a<sup>u</sup> ln a · u′</td><td>[3<sup>2x</sup>]′ = 2 · 3<sup>2x</sup> ln 3</td></tr><tr><td>ln u</td><td>u′/u</td><td>[ln(x² + 7)]′ = 2x/(x² + 7)</td></tr><tr><td>√u</td><td>u′/(2√u)</td><td>[√(1 + x²)]′ = x/√(1 + x²)</td></tr></table></div><h4>How to set it up</h4><div class=\"keybox\">1. Find the <b>outer</b> function (the last thing you would do on a calculator) and the <b>inner</b> function u.<br>2. Differentiate the outer function, keeping u inside unchanged.<br>3. Multiply by u′. If u itself is a composition, repeat (one factor per layer).</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · y = (5x − x³)<sup>4</sup></div><div class=\"exl\">outer: u<sup>4</sup> → 4u<sup>3</sup>;  inner: u = 5x − x³, u′ = 5 − 3x²<br>y′ = <b>4(5x − x³)<sup>3</sup>(5 − 3x²)</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Three layers: y = cos<sup>2</sup>(3x) = [cos(3x)]<sup>2</sup></div><div class=\"exl\">square: 2 cos(3x);  cosine: −sin(3x);  inside: 3<br>y′ = 2 cos(3x) · (−sin(3x)) · 3 = <b>−6 sin(3x) cos(3x)</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · With the Product Rule: y = x e<sup>−2x</sup></div><div class=\"exl\">y′ = 1 · e<sup>−2x</sup> + x · (−2e<sup>−2x</sup>) = <b>e<sup>−2x</sup>(1 − 2x)</b></div></div><div class=\"ex\"><div class=\"exh\">Worked example 4 · With given values: h(x) = f(g(x)), g(2) = 5, g′(2) = −3, f′(5) = 4</div><div class=\"exl\">h′(2) = f′(g(2)) · g′(2) = f′(5) · (−3) = <b>−12</b></div></div><div class=\"keybox\"><b>Common mistakes.</b> Forgetting the inner derivative: [sin 3x]′ is 3 cos 3x, not cos 3x. Changing the inside: [(x² + 1)<sup>5</sup>]′ keeps (x² + 1)<sup>4</sup>, not (2x)<sup>4</sup>. sin<sup>2</sup>x means (sin x)<sup>2</sup>, whose outer function is the square. In f′(g(x)), evaluate f′ at g(x), not at x.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s5\">Practise 5 →</button></div></section><section class=\"note\" id=\"n6\"><h2>6 · Chain rule: Paul’s problems</h2><p class=\"lt\"><b>Learning target:</b> I can differentiate any composite function by naming the inner and outer functions, including all 27 chain rule problems from Paul’s Online Math Notes.</p><div class=\"keybox\"><b>The chain rule.</b> If y = f(g(x)), then <b>dy/dx = f′(g(x)) · g′(x)</b>.<br>With u = g(x): <b>dy/dx = (dy/du) · (du/dx)</b>.<br>In words: <i>differentiate the outer function, keep the inside the same, then multiply by the derivative of the inside.</i></div><h4>Four steps</h4><ol><li>Name the <b>inner</b> function u (what is inside the brackets, the root, the exponent or the trig function).</li><li>Differentiate the <b>outer</b> function with respect to u.</li><li>Multiply by <b>du/dx</b>.</li><li>Put u back in terms of x and tidy up.</li></ol><h4>Outer functions you must know (u is the inner function)</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Function</th><th>Derivative</th></tr><tr><td>uⁿ</td><td>n uⁿ⁻¹ · u′</td></tr><tr><td>√u</td><td>u′ / (2√u)</td></tr><tr><td>sin u</td><td>cos u · u′</td></tr><tr><td>cos u</td><td>−sin u · u′</td></tr><tr><td>tan u</td><td>sec²u · u′</td></tr><tr><td>sec u</td><td>sec u tan u · u′</td></tr><tr><td>csc u</td><td>−csc u cot u · u′</td></tr><tr><td>cot u</td><td>−csc²u · u′</td></tr><tr><td>e<sup>u</sup></td><td>e<sup>u</sup> · u′</td></tr><tr><td>a<sup>u</sup></td><td>a<sup>u</sup> ln a · u′</td></tr><tr><td>ln u</td><td>u′ / u</td></tr><tr><td>tan⁻¹u</td><td>u′ / (1 + u²)</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 1 · A power of a function: y = (5x³ − 2x)⁷</div><div class=\"exl\">Inner u = 5x³ − 2x, so du/dx = 15x² − 2. Outer u⁷, so dy/du = 7u⁶.<br>dy/dx = 7u⁶ · (15x² − 2) = <b>7(5x³ − 2x)⁶(15x² − 2)</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Three layers: y = sin³(2x + 1)</div><div class=\"exl\">Read it as [sin(2x + 1)]³: power outside, then sine, then the linear function 2x + 1.<br>Power: 3 sin²(2x + 1). Sine: × cos(2x + 1). Linear: × 2.<br>dy/dx = <b>6 sin²(2x + 1) cos(2x + 1)</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Chain rule inside the product rule: y = x²e<sup>−3x</sup></div><div class=\"exl\">Product rule with (x²)′ = 2x and (e<sup>−3x</sup>)′ = −3e<sup>−3x</sup> (chain rule).<br>dy/dx = 2x e<sup>−3x</sup> − 3x² e<sup>−3x</sup> = <b>x e<sup>−3x</sup>(2 − 3x)</b>.</div></div><h4>sin²x or sin(x²)?</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Expression</th><th>Layers</th><th>Derivative</th></tr><tr><td>sin²x = (sin x)²</td><td>power outside, sine inside</td><td>2 sin x cos x</td></tr><tr><td>sin(x²)</td><td>sine outside, x² inside</td><td>2x cos(x²)</td></tr></table></div><div class=\"keybox\"><b>Common mistakes.</b> (1) Forgetting the inner derivative: d/dx sin(5x) is 5 cos(5x), not cos(5x). (2) Changing the inside: the derivative of cos(x²) is −sin(x²) · 2x; the inside stays x². (3) Multiplying by the inner function instead of its derivative. (4) Differentiating the inside but not the outside: d/dx (x² + 1)³ is 3(x² + 1)² · 2x, not (2x)³.</div><p style=\"font-size:15px;color:var(--ink-soft)\">Practice sheet 6 is problems 1–27 of the Chain Rule practice problems in Paul Dawkins, <i>Paul’s Online Math Notes</i>, Lamar University. The tag <b>Paul · Problem k</b> gives the problem number. The worked solutions here are our own.</p><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s6\">Practise 6 →</button></div></section><section class=\"note\" id=\"n7\"><h2>7 · Implicit and higher derivatives</h2><p class=\"lt\"><b>Learning target:</b> I can find dy/dx and d²y/dx² implicitly, find slopes and tangent lines on implicit curves, and spot patterns in nth derivatives.</p><p>Some curves, such as x² + y² = 25, are not written as y = f(x). We can still find dy/dx: differentiate <b>both sides</b> with respect to x, treating y as a function of x. Each time you differentiate an expression in y, the chain rule gives an extra factor <b>dy/dx</b>.</p><h4>Steps</h4><ol><li>Differentiate every term with respect to x. Terms in y get a factor dy/dx; products like xy need the product rule.</li><li>Move every dy/dx term to one side and everything else to the other side.</li><li>Factor out dy/dx and divide.</li><li>For a slope at a point, substitute x and y <b>after</b> differentiating.</li></ol><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Term</th><th>d/dx of the term</th></tr><tr><td>y²</td><td>2y · dy/dx</td></tr><tr><td>y³</td><td>3y² · dy/dx</td></tr><tr><td>xy</td><td>y + x · dy/dx</td></tr><tr><td>x²y</td><td>2xy + x² · dy/dx</td></tr><tr><td>sin y</td><td>cos y · dy/dx</td></tr><tr><td>e<sup>y</sup></td><td>e<sup>y</sup> · dy/dx</td></tr><tr><td>ln y</td><td>(1/y) · dy/dx</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Slope and tangent line on x² + 3xy + y² = 11 at (1, 2)</div><div class=\"exl\">Check the point: 1 + 6 + 4 = 11 ✓.<br>Differentiate: 2x + 3y + 3x · dy/dx + 2y · dy/dx = 0.<br>Collect: dy/dx (3x + 2y) = −(2x + 3y), so dy/dx = −(2x + 3y)/(3x + 2y).<br>At (1, 2): dy/dx = −(2 + 6)/(3 + 4) = <b>−8/7</b>. Tangent line: y − 2 = −(8/7)(x − 1).</div></div><h4>Second derivative implicitly</h4><p>Differentiate the expression for dy/dx again (quotient rule), then <b>substitute dy/dx</b> and simplify, using the equation of the curve if it helps.</p><div class=\"ex\"><div class=\"exh\">Worked example 2 · d²y/dx² on x² − y² = 1</div><div class=\"exl\">2x − 2y · y′ = 0, so y′ = x/y.<br>y″ = (y · 1 − x · y′)/y² = (y − x · x/y)/y² = (y² − x²)/y³.<br>On the curve x² − y² = 1, so y² − x² = −1 and <b>y″ = −1/y³</b>.</div></div><h4>Higher-order derivatives</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Prime notation</th><th>Leibniz notation</th><th>Derivative</th></tr><tr><td>f′(x)</td><td>dy/dx</td><td>first</td></tr><tr><td>f″(x)</td><td>d²y/dx²</td><td>second</td></tr><tr><td>f‴(x)</td><td>d³y/dx³</td><td>third</td></tr><tr><td>f⁽⁴⁾(x)</td><td>d⁴y/dx⁴</td><td>fourth</td></tr><tr><td>f⁽ⁿ⁾(x)</td><td>dⁿy/dxⁿ</td><td>nth</td></tr></table></div><h4>Patterns in nth derivatives</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>f(x)</th><th>f⁽ⁿ⁾(x)</th></tr><tr><td>e<sup>kx</sup></td><td>kⁿ e<sup>kx</sup></td></tr><tr><td>sin x</td><td>cycles every 4: cos x, −sin x, −cos x, sin x</td></tr><tr><td>cos x</td><td>cycles every 4: −sin x, −cos x, sin x, cos x</td></tr><tr><td>1/x</td><td>(−1)ⁿ n! / xⁿ⁺¹</td></tr><tr><td>ln x</td><td>(−1)ⁿ⁻¹ (n − 1)! / xⁿ</td></tr><tr><td>polynomial of degree m</td><td>the (m + 1)th derivative is 0</td></tr></table></div><div class=\"keybox\"><b>Common mistakes.</b> (1) Writing d/dx (y²) = 2y with no dy/dx. (2) Differentiating xy as x · dy/dx only; it is a product: y + x · dy/dx. (3) Substituting the point before differentiating: the numbers then have no derivative. (4) For f⁽⁹⁹⁾ of sin x, divide 99 by 4 and use the remainder (3 → −cos x).</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s7\">Practise 7 →</button></div></section><section class=\"note\" id=\"n8\"><h2>8 · Inverses, tables and graphs</h2><p class=\"lt\"><b>Learning target:</b> I can use (f⁻¹)′(a) = 1/f′(f⁻¹(a)), differentiate inverse trig functions, and find derivatives of sums, products, quotients and compositions from tables and graphs.</p><div class=\"keybox\"><b>Derivative of an inverse function.</b> If g = f⁻¹ and f(b) = a, then<br><b>g′(a) = 1 / f′(b) = 1 / f′(f⁻¹(a))</b>.</div><p><b>Why.</b> f(g(x)) = x for every x. Differentiate with the chain rule: f′(g(x)) · g′(x) = 1, so g′(x) = 1/f′(g(x)). On a graph, reflecting in the line y = x swaps rise and run, so the slopes at matching points are reciprocals.</p><h4>Steps</h4><ol><li>Find b with f(b) = a (solve, guess a small integer, or read it from a table).</li><li>Work out f′(b).</li><li>Take the reciprocal.</li></ol><div class=\"ex\"><div class=\"exh\">Worked example 1 · f(x) = x³ + x + 1, g = f⁻¹: find g′(3)</div><div class=\"exl\">f(1) = 1 + 1 + 1 = 3, so f⁻¹(3) = 1.<br>f′(x) = 3x² + 1, so f′(1) = 4.<br>g′(3) = 1/f′(1) = <b>1/4</b>.</div></div><h4>Inverse trigonometric functions</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Function</th><th>Derivative</th><th>With the chain rule (u = inner)</th></tr><tr><td>sin⁻¹x (arcsin x)</td><td>1 / √(1 − x²)</td><td>u′ / √(1 − u²)</td></tr><tr><td>cos⁻¹x (arccos x)</td><td>−1 / √(1 − x²)</td><td>−u′ / √(1 − u²)</td></tr><tr><td>tan⁻¹x (arctan x)</td><td>1 / (1 + x²)</td><td>u′ / (1 + u²)</td></tr></table></div><p>For example, y = tan⁻¹x means tan y = x. Differentiate: sec²y · y′ = 1, so y′ = 1/sec²y = 1/(1 + tan²y) = 1/(1 + x²). Note sin⁻¹x is the inverse function, not 1/sin x.</p><h4>Derivatives from tables and graphs</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Function</th><th>Value at x = a</th></tr><tr><td>h = f + g</td><td>h′(a) = f′(a) + g′(a)</td></tr><tr><td>h = f g</td><td>h′(a) = f′(a) g(a) + f(a) g′(a)</td></tr><tr><td>h = f / g</td><td>h′(a) = [f′(a) g(a) − f(a) g′(a)] / g(a)²</td></tr><tr><td>h = f(g(x))</td><td>h′(a) = f′(g(a)) · g′(a)</td></tr></table></div><p>For a composition, first find g(a) in the table, then look up f′ <b>at that value</b>. On a graph made of line segments, f′ is the slope of the segment (rise ÷ run); at a corner f′ does not exist.</p><div class=\"ex\"><div class=\"exh\">Worked example 2 · Composition from a table</div><div class=\"exl\">Given g(1) = 4, g′(1) = −2 and f′(4) = 3. For h(x) = f(g(x)):<br>h′(1) = f′(g(1)) · g′(1) = f′(4) · (−2) = 3 · (−2) = <b>−6</b>.</div></div><div class=\"keybox\"><b>Common mistakes.</b> (1) Using 1/f′(a) instead of 1/f′(f⁻¹(a)). (2) Reading f⁻¹ as 1/f. (3) For f(g(x)), using f′(a) instead of f′(g(a)). (4) Forgetting the chain factor in tan⁻¹(5x): its derivative is 5/(1 + 25x²).</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s8\">Practise 8 →</button></div></section><section class=\"note\" id=\"n9\"><h2>9 · Using derivatives</h2><p class=\"lt\"><b>Learning target:</b> I can write tangent lines, find where a function increases or decreases with a sign chart, and describe motion using velocity and acceleration.</p><h4>Tangent lines</h4><div class=\"keybox\">The tangent line to y = f(x) at x = a passes through (a, f(a)) with slope f′(a):<br><b>y = f(a) + f′(a)(x − a)</b>.</div><h4>Increasing and decreasing</h4><p>If f′(x) &gt; 0 on an interval, f is <b>increasing</b> there; if f′(x) &lt; 0, f is <b>decreasing</b>. Critical points (f′ = 0 or f′ undefined) split the line into intervals where the sign of f′ cannot change.</p><ol><li>Find f′ and factor it.</li><li>Solve f′(x) = 0 (and find where f′ is undefined).</li><li>Make a sign chart: pick a test value in each interval.</li><li>State the intervals.</li></ol><div class=\"ex\"><div class=\"exh\">Worked example 1 · f(x) = x³ − 12x</div><div class=\"exl\">f′(x) = 3x² − 12 = 3(x − 2)(x + 2), so the critical points are x = −2 and x = 2.<br>Test values: f′(−3) = 15 &gt; 0, f′(0) = −12 &lt; 0, f′(3) = 15 &gt; 0.<br>f is <b>increasing on (−∞, −2) and (2, ∞)</b> and <b>decreasing on (−2, 2)</b>.</div></div><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Interval</th><th>Test value</th><th>Sign of f′</th><th>f is</th></tr><tr><td>x &lt; −2</td><td>−3</td><td>+</td><td>increasing</td></tr><tr><td>−2 &lt; x &lt; 2</td><td>0</td><td>−</td><td>decreasing</td></tr><tr><td>x &gt; 2</td><td>3</td><td>+</td><td>increasing</td></tr></table></div><p>A critical point where f′ does <b>not</b> change sign (for example at a squared factor such as (x − 4)²) does not switch the function from increasing to decreasing.</p><h4>Motion on a line</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Quantity</th><th>Meaning</th></tr><tr><td>s(t)</td><td>position</td></tr><tr><td>v(t) = s′(t)</td><td>velocity: v &gt; 0 moving right (up), v &lt; 0 moving left (down), v = 0 at rest</td></tr><tr><td>a(t) = v′(t) = s″(t)</td><td>acceleration</td></tr><tr><td>|v(t)|</td><td>speed</td></tr><tr><td>v and a same sign</td><td>speeding up (opposite signs: slowing down)</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · s(t) = t³ − 6t² + 9t (metres, t ≥ 0)</div><div class=\"exl\">v(t) = 3t² − 12t + 9 = 3(t − 1)(t − 3): at rest at t = 1 and t = 3.<br>Moving right for 0 ≤ t &lt; 1 and t &gt; 3; moving left for 1 &lt; t &lt; 3.<br>a(t) = 6t − 12. At t = 2: v = −3 and a = 0; at t = 4: v = 9 and a = 12 (speeding up).</div></div><div class=\"keybox\"><b>Common mistakes.</b> (1) Writing the tangent as y = f′(a)(x − a) without f(a). (2) Testing the sign of f instead of f′. (3) Forgetting critical points where f′ is undefined, or the ends of a given interval. (4) Calculators in degree mode: calculus with trig always uses radians.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s9\">Practise 9 →</button></div></section><section class=\"note\" id=\"nsum\"><h2>Topic checklist</h2><ul><li>I can find f′(x) from the limit definition, tell average from instantaneous rate of change, read tangent slopes from a graph and decide where a function is differentiable.</li><li>I can differentiate sums of powers (including negative and fractional powers), rewrite roots and quotients first, and use f′ for tangent lines, horizontal tangents and rates.</li><li>I can use the Product and Quotient Rules, evaluate f′(c), and recognise when rewriting is quicker than the Quotient Rule.</li><li>I can differentiate the six trig functions, eˣ, aˣ, ln x and logₐx, using log laws to simplify first.</li><li>I can differentiate compositions (powers, trig, exponentials and logs of a function, and nested functions) and combine the Chain Rule with the Product and Quotient Rules.</li><li>I can differentiate any composite function by naming the inner and outer functions, including all 27 chain rule problems from Paul’s Online Math Notes.</li><li>I can find dy/dx and d²y/dx² implicitly, find slopes and tangent lines on implicit curves, and spot patterns in nth derivatives.</li><li>I can use (f⁻¹)′(a) = 1/f′(f⁻¹(a)), differentiate inverse trig functions, and find derivatives of sums, products, quotients and compositions from tables and graphs.</li><li>I can write tangent lines, find where a function increases or decreases with a sign chart, and describe motion using velocity and acceleration.</li></ul><div class=\"hub-btns\" style=\"margin-top:10px\"><button class=\"hub-btn\" data-go=\"s10\">Assessment A</button><button class=\"hub-btn\" data-go=\"s11\">Assessment B</button><button class=\"hub-btn\" data-go=\"s12\">Assessment C</button><button class=\"hub-btn\" data-go=\"s13\">Assessment D</button><button class=\"hub-btn primary\" data-go=\"report\">📊 Report</button></div></section>";
var REPORT = [["s10", "A", "Knowing and understanding"], ["s11", "B", "Investigating patterns"], ["s12", "C", "Communicating"], ["s13", "D", "Applying mathematics in real-life contexts"]];
var SECTIONS = [{"id": "s1", "label": "1 · Definition of the derivative", "sub": "Limit definition · tangent slopes · average vs instantaneous rate · differentiability", "slides": [{"kind": "mcq", "text": "Which limit is the <b>definition</b> of the derivative f′(x)?", "opts": ["lim<sub>h→0</sub> (f(x) + h − f(x))/h", "lim<sub>h→0</sub> (f(x + h) − f(x))", "lim<sub>h→0</sub> (f(x + h) − f(x))/h", "lim<sub>h→∞</sub> (f(x + h) − f(x))/h"], "correct": 2, "tag": "", "sol": "f′(x) is the limit of the secant slope (f(x + h) − f(x))/h as h → 0. Without “/h” there is no slope; f(x) + h is not f evaluated at x + h; and h must shrink to 0, not grow."}, {"kind": "blank", "p": "Use the limit definition to find f′(x) for f(x) = 3x<sup>2</sup> − 5x. Expand fully at each step.", "tag": "", "marks": "", "flat": [{"t": "f(x + h) = 3(x + h)<sup>2</sup> − 5(x + h) = __B1__", "a": {"B1": "3x^2+6xh+3h^2-5x-5h"}, "expr": "calc"}, {"t": "f(x + h) − f(x) = __B1__", "a": {"B1": "6xh+3h^2-5h"}, "expr": "calc"}, {"t": "Divide by h: (f(x + h) − f(x))/h = __B1__", "a": {"B1": "6x+3h-5"}, "expr": "calc"}, {"t": "Let h → 0: f′(x) = __B1__", "a": {"B1": "6x-5"}, "expr": "calc"}], "sol": "3(x² + 2xh + h²) − 5x − 5h = 3x² + 6xh + 3h² − 5x − 5h.\nThe terms 3x² and −5x cancel: 6xh + 3h² − 5h.\nEvery term has a factor h: (6xh + 3h² − 5h)/h = 6x + 3h − 5.\nAs h → 0 the 3h term vanishes: f′(x) = 6x − 5."}, {"kind": "mcq", "text": "What is the slope of the tangent line to f(x) = x<sup>3</sup> − 4x + 2 at x = 2?", "opts": ["8", "−4", "12", "2"], "correct": 0, "tag": "", "sol": "f′(x) = 3x² − 4, so f′(2) = 12 − 4 = 8. (2 is the y-value f(2); 12 forgets the −4; −4 is f′(0).)"}, {"kind": "blank", "p": "Use the limit definition to find f′(x) for f(x) = 2/x.", "tag": "", "marks": "", "flat": [{"t": "f(x + h) − f(x) = 2/(x + h) − 2/x. As one fraction: __B1__", "a": {"B1": "-2h/(x(x+h))"}, "expr": "calc"}, {"t": "Divide by h: __B1__", "a": {"B1": "-2/(x(x+h))"}, "expr": "calc"}, {"t": "Let h → 0: f′(x) = __B1__", "a": {"B1": "-2/x^2"}, "expr": "calc"}], "sol": "Common denominator x(x + h): (2x − 2(x + h))/(x(x + h)) = −2h/(x(x + h)).\nDividing by h cancels it: −2/(x(x + h)).\nPut h = 0: −2/(x · x) = −2/x²."}, {"kind": "mcq", "text": "Find the <b>average</b> rate of change of f(x) = x<sup>2</sup> + 1 on the interval [1, 4].", "opts": ["2", "15", "8", "5"], "correct": 3, "tag": "", "sol": "(f(4) − f(1))/(4 − 1) = (17 − 2)/3 = 5. (15 forgets to divide by 3; 8 = f′(4) and 2 = f′(1) are instantaneous rates at the ends.)"}, {"kind": "blank", "p": "A particle moves along a line with position s(t) = t<sup>3</sup> + t metres after t seconds.", "tag": "", "marks": "", "flat": [{"t": "s(3) = __B1__ m and s(1) = __B2__ m", "a": {"B1": "30", "B2": "2"}}, {"t": "Average velocity on [1, 3]: (s(3) − s(1))/(3 − 1) = __B1__ m/s", "a": {"B1": "14"}}, {"t": "Velocity: v(t) = s′(t) = __B1__", "a": {"B1": "3t^2+1"}, "expr": "calc"}, {"t": "Instantaneous velocity at t = 2: s′(2) = __B1__ m/s", "a": {"B1": "13"}}], "sol": "s(3) = 27 + 3 = 30 and s(1) = 1 + 1 = 2.\n(30 − 2)/2 = 14 m/s: the slope of the secant from t = 1 to t = 3.\ns′(t) = 3t² + 1.\ns′(2) = 12 + 1 = 13 m/s: the slope of the tangent at t = 2, close to (but not equal to) the average 14 m/s."}, {"kind": "mcq", "text": "Which statement about f(x) = |x − 2| at x = 2 is true?", "opts": ["Not continuous, so it is not differentiable", "Differentiable, but not continuous at x = 2", "Continuous, but not differentiable: there is a corner", "Continuous and differentiable, with f′(2) = 0"], "correct": 2, "tag": "", "sol": "The graph is a V with its tip at (2, 0): no break, so f is continuous. The slope is −1 just left of 2 and +1 just right of 2, so there is no single tangent slope: f′(2) does not exist. (Differentiable functions are always continuous, so “differentiable, but not continuous” is impossible.)"}, {"kind": "blank", "p": "Is f differentiable at x = 1?  f(x) = x<sup>2</sup> + 1 for x ≤ 1,  f(x) = 2x for x > 1.", "tag": "", "marks": "", "flat": [{"t": "Values at the join: f(1) = __B1__ and 2(1) = __B2__", "a": {"B1": "2", "B2": "2"}}, {"t": "Slope from the left: d/dx (x<sup>2</sup> + 1) = 2x, which is __B1__ at x = 1", "a": {"B1": "2"}}, {"t": "Slope from the right: d/dx (2x) at x = 1 is __B1__", "a": {"B1": "2"}}, {"t": "Is f differentiable at x = 1? (yes / no) __B1__", "a": {"B1": "yes"}, "expr": "words"}], "sol": "Both pieces give 2, so f is continuous at x = 1.\n2(1) = 2.\nThe line 2x has slope 2 everywhere.\nYes: f is continuous and the one-sided slopes agree (both 2)."}, {"kind": "mcq", "text": "g(x) = x<sup>2</sup> for x ≤ 2 and g(x) = 4x − 3 for x > 2. Which is true at x = 2?", "opts": ["g is differentiable, since both slopes equal 4", "g is not continuous, so g is not differentiable", "g is continuous but has a corner at x = 2", "g is continuous and differentiable at x = 2"], "correct": 1, "tag": "", "sol": "Values: 2² = 4 but 4(2) − 3 = 5, so the graph jumps from 4 to 5 and g is not continuous at 2. A function that is not continuous cannot be differentiable, even though both pieces have slope 4 there."}, {"kind": "blank", "p": "Find a and b so that f is differentiable at x = 3:  f(x) = x<sup>2</sup> for x ≤ 3,  f(x) = ax + b for x > 3.", "tag": "", "marks": "", "flat": [{"t": "The slopes must match at x = 3: a = __B1__", "a": {"B1": "6"}}, {"t": "The values must match at x = 3: 3a + b = __B1__", "a": {"B1": "9"}}, {"t": "So b = __B1__", "a": {"B1": "-9"}}], "sol": "(x²)′ = 2x = 6 at x = 3, and the line has slope a, so a = 6.\nx² gives 9 at x = 3, so 3a + b = 9.\n18 + b = 9, so b = −9. (f(x) = 6x − 9 for x > 3 is the tangent line to y = x² at x = 3.)"}, {"kind": "mcq", "text": "The dashed line is tangent to the graph of f at the point (2, 3). Use the grid to find f′(2).", "opts": ["3", "−1", "2", "{1/2}"], "correct": 2, "tag": "", "sol": "The tangent passes through (0, −1) and (2, 3): slope = rise ÷ run = (3 − (−1))/(2 − 0) = 4/2 = 2. (3 is f(2), the height; −1 is the y-intercept; {1/2} is run ÷ rise.)", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 186 304\" role=\"img\" style=\"max-width:340px\"><line x1=\"14\" y1=\"14\" x2=\"14\" y2=\"284\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"44\" y1=\"14\" x2=\"44\" y2=\"284\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"74\" y1=\"14\" x2=\"74\" y2=\"284\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"104\" y1=\"14\" x2=\"104\" y2=\"284\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"134\" y1=\"14\" x2=\"134\" y2=\"284\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"164\" y1=\"14\" x2=\"164\" y2=\"284\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"284\" x2=\"164\" y2=\"284\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"254\" x2=\"164\" y2=\"254\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"224\" x2=\"164\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"194\" x2=\"164\" y2=\"194\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"164\" x2=\"164\" y2=\"164\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"134\" x2=\"164\" y2=\"134\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"104\" x2=\"164\" y2=\"104\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"74\" x2=\"164\" y2=\"74\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"44\" x2=\"164\" y2=\"44\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"14\" x2=\"164\" y2=\"14\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"224\" x2=\"170\" y2=\"224\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"44\" y1=\"284\" x2=\"44\" y2=\"8\" style=\"stroke:var(--ink);stroke-width:1.6\"/><path d=\"M170,224 l-7,-4 v8 z\" style=\"fill:var(--ink)\"/><path d=\"M44,8 l-4,7 h8 z\" style=\"fill:var(--ink)\"/><text x=\"168\" y=\"238\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;\">x</text><text x=\"33\" y=\"16\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;\">y</text><text x=\"36\" y=\"236\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;font-style:normal\">0</text><text x=\"74\" y=\"236\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;font-style:normal\">1</text><text x=\"35\" y=\"194\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;font-style:normal\">1</text><path d=\"M14.0,179.0 L17.3,182.2 L20.7,184.9 L24.0,187.4 L27.4,189.4 L30.7,191.1 L34.1,192.4 L37.4,193.3 L40.8,193.8 L44.1,194.0 L47.5,193.8 L50.8,193.2 L54.2,192.3 L57.5,191.0 L60.9,189.3 L64.2,187.2 L67.6,184.7 L70.9,181.9 L74.3,178.7 L77.6,175.2 L81.0,171.2 L84.3,166.9 L87.7,162.2 L91.0,157.2 L94.4,151.7 L97.7,145.9 L101.0,139.8 L104.4,133.2 L107.7,126.3 L111.1,119.0 L114.4,111.3 L117.8,103.2 L121.1,94.8 L124.5,86.0 L127.8,76.9 L131.2,67.3 L134.5,57.4 L137.9,47.1 L141.2,36.4 L144.6,25.4 L147.9,14.0\" style=\"fill:none;stroke:var(--accent-text);stroke-width:2.4;stroke-linejoin:round\"/><text x=\"125.0\" y=\"35.00000000000001\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;fill:var(--accent-text);font-size:16px\">f</text><path d=\"M29.0,284.0 L164.0,14.0\" style=\"fill:none;stroke:var(--danger);stroke-width:2.4;stroke-linejoin:round;stroke-dasharray:7 4\"/><circle cx=\"104\" cy=\"134\" r=\"4\" style=\"fill:var(--ink)\"/></svg>"}, {"kind": "blank", "p": "The graph of f is made of straight segments (corners at x = 2 and x = 5). Find:", "tag": "", "marks": "", "flat": [{"t": "f′(1) = __B1__", "a": {"B1": "2"}}, {"t": "f′(3) = __B1__", "a": {"B1": "-1"}}, {"t": "f′(5.5) = __B1__", "a": {"B1": "0"}}, {"t": "Every x in (0, 6) where f is not differentiable (in increasing order): __B1__", "a": {"B1": "2, 5"}, "expr": "dlist"}], "sol": "From (0, 1) to (2, 5): slope 4/2 = 2.\nFrom (2, 5) to (5, 2): slope −3/3 = −1.\nFrom (5, 2) to (6, 2) the graph is flat: slope 0.\nAt the corners x = 2 (slope 2 changes to −1) and x = 5 (−1 changes to 0) there is no single tangent slope.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 276 244\" role=\"img\" style=\"max-width:340px\"><line x1=\"14\" y1=\"14\" x2=\"14\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"44\" y1=\"14\" x2=\"44\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"74\" y1=\"14\" x2=\"74\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"104\" y1=\"14\" x2=\"104\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"134\" y1=\"14\" x2=\"134\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"164\" y1=\"14\" x2=\"164\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"194\" y1=\"14\" x2=\"194\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"224\" y1=\"14\" x2=\"224\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"254\" y1=\"14\" x2=\"254\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"224\" x2=\"254\" y2=\"224\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"194\" x2=\"254\" y2=\"194\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"164\" x2=\"254\" y2=\"164\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"134\" x2=\"254\" y2=\"134\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"104\" x2=\"254\" y2=\"104\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"74\" x2=\"254\" y2=\"74\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"44\" x2=\"254\" y2=\"44\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"14\" x2=\"254\" y2=\"14\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"14\" y1=\"194\" x2=\"260\" y2=\"194\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"44\" y1=\"224\" x2=\"44\" y2=\"8\" style=\"stroke:var(--ink);stroke-width:1.6\"/><path d=\"M260,194 l-7,-4 v8 z\" style=\"fill:var(--ink)\"/><path d=\"M44,8 l-4,7 h8 z\" style=\"fill:var(--ink)\"/><text x=\"258\" y=\"208\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;\">x</text><text x=\"33\" y=\"16\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;\">y</text><text x=\"36\" y=\"206\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;font-style:normal\">0</text><text x=\"74\" y=\"206\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;font-style:normal\">1</text><text x=\"35\" y=\"164\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;font-style:normal\">1</text><path d=\"M44.0,164.0 L104.0,44.0 L194.0,134.0 L224.0,134.0\" style=\"fill:none;stroke:var(--accent-text);stroke-width:2.4;stroke-linejoin:round\"/><text x=\"83.0\" y=\"37.99999999999999\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:italic 600 14px serif;fill:var(--accent-text);font-size:16px\">f</text><circle cx=\"44\" cy=\"164\" r=\"4\" style=\"fill:var(--ink)\"/><circle cx=\"104\" cy=\"44\" r=\"4\" style=\"fill:var(--ink)\"/><circle cx=\"194\" cy=\"134\" r=\"4\" style=\"fill:var(--ink)\"/><circle cx=\"224\" cy=\"134\" r=\"4\" style=\"fill:var(--ink)\"/></svg>"}, {"kind": "mcq", "text": "The limit lim<sub>h→0</sub> ((3 + h)<sup>2</sup> − 9)/h is f′(a) for some f and a. Which is correct?", "opts": ["f(x) = x<sup>2</sup> at a = 3; the limit is 6", "f(x) = x<sup>2</sup> at a = 3; the limit is 9", "f(x) = x<sup>2</sup> − 9 at a = 0; the limit is 0", "f(x) = x<sup>2</sup> at a = 9; the limit is 18"], "correct": 0, "tag": "", "sol": "It has the form (f(a + h) − f(a))/h with f(x) = x², a = 3 and f(3) = 9. Since f′(x) = 2x, the limit is f′(3) = 6. (Check: ((3 + h)² − 9)/h = (6h + h²)/h = 6 + h → 6.)"}, {"kind": "blank", "p": "Use the limit definition at a point to find the tangent line to f(x) = x<sup>2</sup> − 3x at x = 4.", "tag": "", "marks": "", "flat": [{"t": "f(4) = __B1__", "a": {"B1": "4"}}, {"t": "f(4 + h) − f(4) = __B1__ (simplify, in terms of h)", "a": {"B1": "h^2+5h"}, "expr": "calc"}, {"t": "f′(4) = lim<sub>h→0</sub> [f(4 + h) − f(4)]/h = __B1__", "a": {"B1": "5"}}, {"t": "Tangent line: y = __B1__", "a": {"B1": "5x-16"}, "expr": "calc"}], "sol": "16 − 12 = 4.\n(4 + h)² − 3(4 + h) − 4 = 16 + 8h + h² − 12 − 3h − 4 = h² + 5h.\n(h² + 5h)/h = h + 5 → 5.\ny − 4 = 5(x − 4), so y = 5x − 16."}, {"kind": "mcq", "text": "Which statement is <b>always</b> true?", "opts": ["If f is differentiable at a, then f is continuous at a", "If f is continuous at a, then f is differentiable at a", "A vertical tangent at x = a means f′(a) = 0", "|x| is differentiable at 0 because it is continuous there"], "correct": 0, "tag": "", "sol": "Differentiable ⇒ continuous. The converse fails: |x| is continuous at 0 but has a corner. A vertical tangent has undefined slope, so f′(a) does not exist (a horizontal tangent has f′(a) = 0)."}]}, {"id": "s2", "label": "2 · Power, constant and sum rules", "sub": "Negative and fractional powers · rewriting · tangent lines · horizontal tangents · rates", "slides": [{"kind": "mcq", "text": "Differentiate y = 7x<sup>5</sup> − 3x<sup>2</sup> + 4.", "opts": ["5x<sup>4</sup> − 2x", "35x<sup>6</sup> − 6x<sup>3</sup> + 4x", "35x<sup>4</sup> − 6x", "35x<sup>4</sup> − 6x + 4"], "correct": 2, "tag": "", "sol": "Power Rule term by term: 7 · 5x⁴ − 3 · 2x + 0 = 35x⁴ − 6x. The constant 4 has derivative 0; the coefficients 7 and 3 stay; the powers go down by one, not up."}, {"kind": "blank", "p": "Differentiate each function.", "tag": "", "marks": "", "flat": [{"t": "a) y = 9  →  dy/dx = __B1__", "a": {"B1": "0"}, "expr": "calc"}, {"t": "b) f(x) = 4x<sup>6</sup>  →  f′(x) = __B1__", "a": {"B1": "24x^5"}, "expr": "calc"}, {"t": "c) y = x<sup>5</sup> − 3x + 8  →  dy/dx = __B1__", "a": {"B1": "5x^4-3"}, "expr": "calc"}, {"t": "d) g(t) = 2t<sup>3</sup> − t<sup>2</sup> + 6t  →  g′(t) = __B1__", "a": {"B1": "6t^2-2t+6"}, "expr": "calc"}], "sol": "A constant does not change, so its derivative is 0.\n4 · 6x⁵ = 24x⁵.\n5x⁴ − 3 + 0 = 5x⁴ − 3.\n6t² − 2t + 6 (the variable is t, so differentiate with respect to t)."}, {"kind": "mcq", "text": "Differentiate y = 6/x<sup>3</sup>.", "opts": ["−18/x<sup>2</sup>", "2/x<sup>2</sup>", "−18/x<sup>4</sup>", "18/x<sup>4</sup>"], "correct": 2, "tag": "", "sol": "Rewrite: y = 6x⁻³. Then y′ = 6 · (−3)x⁻⁴ = −18x⁻⁴ = −18/x⁴. (−18/x² moves the power the wrong way; 2/x² = 6/(3x²) differentiates the denominator.)"}, {"kind": "blank", "p": "Rewrite each function as a power of x, then differentiate.", "tag": "", "marks": "", "flat": [{"t": "y = 5∛x. Write it as y = 5x<sup>k</sup>: k = __B1__", "a": {"B1": "1/3"}, "expr": "calc"}, {"t": "dy/dx = __B1__ (put a fraction coefficient in brackets, like (1/4)x<sup>…</sup>)", "a": {"B1": "(5/3)x^(-2/3)"}, "expr": "calc"}, {"t": "y = 4/√x. Write it as y = 4x<sup>k</sup>: k = __B1__", "a": {"B1": "-1/2"}, "expr": "calc"}, {"t": "dy/dx = __B1__", "a": {"B1": "-2x^(-3/2)"}, "expr": "calc"}], "sol": "The cube root is the power {1/3}: y = 5x<sup>1/3</sup>.\n5 · {1/3} x<sup>1/3 − 1</sup> = {5/3}x<sup>−2/3</sup> = 5/(3∛(x²)).\n1/√x = x<sup>−1/2</sup>, so y = 4x<sup>−1/2</sup>.\n4 · (−{1/2})x<sup>−3/2</sup> = −2x<sup>−3/2</sup> = −2/(x√x)."}, {"kind": "mcq", "text": "Differentiate y = (x<sup>3</sup> − 4x + 2)/x.", "opts": ["2x + 2/x<sup>2</sup>", "2x − 4 − 2/x<sup>2</sup>", "2x − 2/x<sup>2</sup>", "3x<sup>2</sup> − 4"], "correct": 2, "tag": "", "sol": "Divide first: y = x² − 4 + 2x⁻¹. Then y′ = 2x − 2x⁻² = 2x − 2/x². (3x² − 4 differentiates only the top; the constant −4 must disappear.)"}, {"kind": "blank", "p": "Rewrite, then differentiate. Use fractional powers for the roots.", "tag": "", "marks": "", "flat": [{"t": "y = √x (x − 3). Multiply out: y = __B1__", "a": {"B1": "x^(3/2)-3x^(1/2)"}, "expr": "calc"}, {"t": "dy/dx = __B1__ (bracket fraction coefficients)", "a": {"B1": "(3/2)x^(1/2)-(3/2)x^(-1/2)"}, "expr": "calc"}, {"t": "y = (2x + 1)<sup>2</sup>. Expand: y = __B1__", "a": {"B1": "4x^2+4x+1"}, "expr": "calc"}, {"t": "dy/dx = __B1__", "a": {"B1": "8x+4"}, "expr": "calc"}], "sol": "x<sup>1/2</sup> · x = x<sup>3/2</sup> and x<sup>1/2</sup> · 3 = 3x<sup>1/2</sup>: y = x<sup>3/2</sup> − 3x<sup>1/2</sup>.\n{3/2}x<sup>1/2</sup> − {3/2}x<sup>−1/2</sup> = {3/2}(√x − 1/√x).\n(2x + 1)(2x + 1) = 4x² + 4x + 1.\n8x + 4."}, {"kind": "mcq", "text": "Find the tangent line to y = x<sup>3</sup> − 2x<sup>2</sup> + 1 at x = 2.", "opts": ["y = 4x − 8", "y = 12x − 23", "y = 4x − 7", "y = 4x + 1"], "correct": 2, "tag": "", "sol": "Point: y(2) = 8 − 8 + 1 = 1. Slope: y′ = 3x² − 4x, so y′(2) = 12 − 8 = 4. Line: y − 1 = 4(x − 2), so y = 4x − 7. (4x − 8 forgets the + 1; 4x + 1 uses 1 as the intercept; slope 12 drops the −4x term.)"}, {"kind": "blank", "p": "Find the tangent line to f(x) = 2√x + x at x = 4.", "tag": "", "marks": "", "flat": [{"t": "f(4) = __B1__", "a": {"B1": "8"}}, {"t": "f′(x) = __B1__", "a": {"B1": "1/sqrt(x)+1"}, "expr": "calc"}, {"t": "f′(4) = __B1__", "a": {"B1": "3/2"}, "expr": "calc"}, {"t": "Tangent line: y = __B1__", "a": {"B1": "(3/2)x+2"}, "expr": "calc", "accept": ["3/2x+2"]}], "sol": "2 · 2 + 4 = 8.\n2 · {1/2}x<sup>−1/2</sup> + 1 = 1/√x + 1.\n1/2 + 1 = {3/2}.\ny − 8 = {3/2}(x − 4), so y = {3/2}x + 2."}, {"kind": "mcq", "text": "At which points does y = x<sup>3</sup> − 3x<sup>2</sup> − 9x + 5 have a <b>horizontal</b> tangent?", "opts": ["(−1, 0) and (3, 0)", "(−1, 10) and (3, −22)", "(1, −6) and (−3, −22)", "(1, −6) and (3, −22)"], "correct": 1, "tag": "", "sol": "y′ = 3x² − 6x − 9 = 3(x − 3)(x + 1) = 0 at x = −1 and x = 3. Then y(−1) = −1 − 3 + 9 + 5 = 10 and y(3) = 27 − 27 − 27 + 5 = −22. (The y-values are not 0: put the x-values back into y.)", "tools": ["desmos"], "desmos": ["y=x^3-3x^2-9x+5"]}, {"kind": "blank", "p": "Find where f(x) = x<sup>4</sup> − 8x<sup>2</sup> has horizontal tangents.", "tag": "", "marks": "", "flat": [{"t": "f′(x) = __B1__", "a": {"B1": "4x^3-16x"}, "expr": "calc"}, {"t": "Solve f′(x) = 0. The x-values (in increasing order): __B1__", "a": {"B1": "-2, 0, 2"}, "expr": "dlist"}, {"t": "The matching y-values (same order): __B1__", "a": {"B1": "-16, 0, -16"}, "expr": "dlist"}], "sol": "4x³ − 16x.\n4x(x² − 4) = 4x(x − 2)(x + 2) = 0, so x = −2, 0, 2.\nf(−2) = 16 − 32 = −16, f(0) = 0, f(2) = −16: points (−2, −16), (0, 0), (2, −16)."}, {"kind": "mcq", "text": "The volume of a cube with edge s cm is V = s<sup>3</sup>. How fast is V changing with respect to s when s = 5 cm?", "opts": ["15 cm³ per cm", "25 cm³ per cm", "75 cm³ per cm", "125 cm³ per cm"], "correct": 2, "tag": "", "sol": "dV/ds = 3s², and 3 · 5² = 75 cm³ per cm. (125 is the volume itself; 25 = s²; 15 = 3s.)"}, {"kind": "blank", "p": "A spherical balloon has volume V = {4/3}πr<sup>3</sup> (r in cm).", "tag": "", "marks": "", "flat": [{"t": "dV/dr = __B1__", "a": {"B1": "4pi*r^2"}, "expr": "calc"}, {"t": "At r = 3 cm, dV/dr = kπ cm³ per cm, where k = __B1__", "a": {"B1": "36"}}, {"t": "Estimate the increase in volume when r grows from 3 to 3.1 cm: ΔV ≈ (dV/dr) × 0.1 ≈ __B1__ cm³ (1 d.p.)", "a": {"B1": "11.3"}, "expr": "approx"}], "sol": "{4/3}π · 3r² = 4πr² (the surface area of the sphere!).\n4π · 9 = 36π cm³ per cm.\n36π × 0.1 = 3.6π ≈ 11.3 cm³."}, {"kind": "mcq", "text": "Which function has derivative 6x<sup>2</sup> − 4?", "opts": ["2x<sup>3</sup> − 4", "6x<sup>3</sup> − 4x", "3x<sup>2</sup> − 4x", "2x<sup>3</sup> − 4x + 9"], "correct": 3, "tag": "", "sol": "Differentiate each: (2x³ − 4x + 9)′ = 6x² − 4 ✓. (6x³ − 4x)′ = 18x² − 4; (2x³ − 4)′ = 6x²; (3x² − 4x)′ = 6x − 4."}, {"kind": "blank", "p": "Differentiate with respect to the variable shown. All other letters are constants.", "tag": "", "marks": "", "flat": [{"t": "y = 4ax<sup>3</sup> − bx<sup>2</sup> + c  →  dy/dx = __B1__", "a": {"B1": "12a*x^2-2b*x"}, "expr": "calc"}, {"t": "f(t) = πt<sup>2</sup> + e<sup>2</sup>t  →  f′(t) = __B1__", "a": {"B1": "2pi*t+e^2"}, "expr": "calc"}], "sol": "a and b are constant multiples and c is a constant: 12ax² − 2bx + 0.\nπ and e² are just numbers: f′(t) = 2πt + e²."}, {"kind": "mcq", "text": "<b>Error analysis.</b> Sam writes d/dx [1/x<sup>2</sup>] = 1/(2x). Which comment is correct?", "opts": ["Wrong: the derivative is −1/(2x), keeping the minus sign", "Wrong: x<sup>−2</sup> differentiates to 2x<sup>−1</sup>", "Right: differentiate the denominator x<sup>2</sup> to get 2x", "Wrong: 1/x<sup>2</sup> = x<sup>−2</sup>, so the derivative is −2x<sup>−3</sup>"], "correct": 3, "tag": "", "sol": "Rewrite first: 1/x² = x⁻². Power Rule: −2x⁻³ = −2/x³. You cannot differentiate the denominator on its own, and the power drops from −2 to −3."}]}, {"id": "s3", "label": "3 · Product and quotient rules", "sub": "Product Rule · Quotient Rule · f′(c) · rewrite instead of the Quotient Rule", "slides": [{"kind": "mcq", "text": "Which is the Product Rule?", "opts": ["(fg)′ = f′g − fg′", "(fg)′ = f′g′", "(fg)′ = f′g + fg′", "(fg)′ = f′g′ + fg"], "correct": 2, "tag": "", "sol": "Derivative of the first × the second + the first × derivative of the second. Test with f = g = x: (x²)′ = 2x = 1·x + x·1, while f′g′ = 1."}, {"kind": "blank", "p": "Differentiate y = (x<sup>2</sup> + 3)(4x − 1) with the Product Rule.", "tag": "", "marks": "", "flat": [{"t": "u = x<sup>2</sup> + 3, so u′ = __B1__", "a": {"B1": "2x"}, "expr": "calc"}, {"t": "v = 4x − 1, so v′ = __B1__", "a": {"B1": "4"}, "expr": "calc"}, {"t": "y′ = u′v + uv′ = __B1__ (simplify)", "a": {"B1": "12x^2-2x+12"}, "expr": "calc"}], "sol": "(x² + 3)′ = 2x.\n(4x − 1)′ = 4.\n2x(4x − 1) + 4(x² + 3) = 8x² − 2x + 4x² + 12 = 12x² − 2x + 12."}, {"kind": "mcq", "text": "Differentiate y = (2x + 1)(x<sup>2</sup> − 5).", "opts": ["4x<sup>2</sup> + 2x − 10", "6x<sup>2</sup> + 2x − 10", "6x<sup>2</sup> + 2x + 10", "4x"], "correct": 1, "tag": "", "sol": "y′ = 2(x² − 5) + (2x + 1)(2x) = 2x² − 10 + 4x² + 2x = 6x² + 2x − 10. (4x is the product of the derivatives, 2 · 2x.)"}, {"kind": "blank", "p": "Differentiate y = (3x − 2)/(x + 4) with the Quotient Rule.", "tag": "", "marks": "", "flat": [{"t": "Numerator (low · d-high − high · d-low): (x + 4)(3) − (3x − 2)(1) = __B1__", "a": {"B1": "14"}, "expr": "calc"}, {"t": "y′ = __B1__", "a": {"B1": "14/(x+4)^2"}, "expr": "calc"}], "sol": "3x + 12 − 3x + 2 = 14.\ny′ = 14/(x + 4)²."}, {"kind": "mcq", "text": "Which is the Quotient Rule?", "opts": ["(f/g)′ = (fg′ − gf′)/g<sup>2</sup>", "(f/g)′ = (gf′ + fg′)/g<sup>2</sup>", "(f/g)′ = (gf′ − fg′)/g<sup>2</sup>", "(f/g)′ = f′/g′"], "correct": 2, "tag": "", "sol": "“Low d-high minus high d-low, over low squared”: (g f′ − f g′)/g². Swapping the two terms changes the sign of the answer."}, {"kind": "blank", "p": "Differentiate y = x<sup>2</sup>/(2x + 3).", "tag": "", "marks": "", "flat": [{"t": "Numerator: (2x + 3)(2x) − x<sup>2</sup>(2) = __B1__", "a": {"B1": "2x^2+6x"}, "expr": "calc"}, {"t": "y′ = __B1__", "a": {"B1": "(2x^2+6x)/(2x+3)^2"}, "expr": "calc"}], "sol": "4x² + 6x − 2x² = 2x² + 6x.\ny′ = (2x² + 6x)/(2x + 3)² = 2x(x + 3)/(2x + 3)²."}, {"kind": "mcq", "text": "h(x) = (x<sup>2</sup> + 1)(x<sup>3</sup> − 2). Find h′(1).", "opts": ["−2", "4", "8", "6"], "correct": 1, "tag": "", "sol": "h′(x) = 2x(x³ − 2) + (x² + 1)(3x²). At x = 1: 2(−1) + 2(3) = −2 + 6 = 4. (6 is f′(1)g′(1) = 2 · 3; −2 is only the first term.)"}, {"kind": "blank", "p": "g(x) = (x + 5)/(x<sup>2</sup> + 1).", "tag": "", "marks": "", "flat": [{"t": "g(2) = __B1__", "a": {"B1": "7/5"}, "expr": "calc"}, {"t": "g′(x) = __B1__", "a": {"B1": "(1-10x-x^2)/(x^2+1)^2"}, "expr": "calc"}, {"t": "g′(2) = __B1__", "a": {"B1": "-23/25"}, "expr": "calc"}], "sol": "(2 + 5)/(4 + 1) = {7/5}.\n((x² + 1)(1) − (x + 5)(2x))/(x² + 1)² = (1 − 10x − x²)/(x² + 1)².\n(1 − 20 − 4)/25 = −{23/25}."}, {"kind": "mcq", "text": "For which function is it simplest to <b>rewrite with powers of x</b> instead of using the Quotient Rule?", "opts": ["y = (x + 1)/(x − 1)", "y = x/(x<sup>2</sup> + 1)", "y = 2x/(3 − x)", "y = (x<sup>2</sup> + 3x)/√x"], "correct": 3, "tag": "", "sol": "Its denominator is a single power, x<sup>1/2</sup>, so y = x<sup>3/2</sup> + 3x<sup>1/2</sup> and y′ = {3/2}x<sup>1/2</sup> + {3/2}x<sup>−1/2</sup>. The others have a sum on the bottom and need the Quotient Rule."}, {"kind": "blank", "p": "Rewrite, then differentiate (no Quotient Rule needed).  Original → Rewrite → Differentiate. Put fraction coefficients in brackets, like (1/4)x<sup>…</sup>.", "tag": "", "marks": "", "flat": [{"t": "y = 5/(2x<sup>3</sup>)  →  Rewrite: y = __B1__", "a": {"B1": "(5/2)x^(-3)"}, "expr": "calc"}, {"t": "Differentiate: y′ = __B1__", "a": {"B1": "-(15/2)x^(-4)"}, "expr": "calc"}, {"t": "y = (x<sup>2</sup> + 4)/(3x)  →  Rewrite: y = __B1__", "a": {"B1": "(1/3)x+(4/3)x^(-1)"}, "expr": "calc", "accept": ["1/3x+4/3x^(-1)"]}, {"t": "Differentiate: y′ = __B1__", "a": {"B1": "1/3-(4/3)x^(-2)"}, "expr": "calc", "accept": ["1/3-4/3x^(-2)"]}], "sol": "5/(2x³) = {5/2}x⁻³.\n{5/2} · (−3)x⁻⁴ = −{15/2}x⁻⁴ = −15/(2x⁴).\nx²/(3x) + 4/(3x) = {1/3}x + {4/3}x⁻¹.\n{1/3} − {4/3}x⁻² = {1/3} − 4/(3x²)."}, {"kind": "mcq", "text": "Differentiate y = √x (x<sup>2</sup> − 4).", "opts": ["(3x<sup>2</sup> − 4)/(2√x)", "(x<sup>2</sup> − 4)/(2√x)", "(5x<sup>2</sup> + 4)/(2√x)", "(5x<sup>2</sup> − 4)/(2√x)"], "correct": 3, "tag": "", "sol": "y′ = (1/(2√x))(x² − 4) + √x · 2x. Over the common denominator 2√x: (x² − 4 + 4x²)/(2√x) = (5x² − 4)/(2√x). ((x² − 4)/(2√x) is only the first term of the Product Rule.)"}, {"kind": "blank", "p": "f(2) = 5, f′(2) = −2, g(2) = 4 and g′(2) = 3. Find:", "tag": "", "marks": "", "flat": [{"t": "(fg)′(2) = __B1__", "a": {"B1": "7"}, "expr": "calc"}, {"t": "(f/g)′(2) = __B1__", "a": {"B1": "-23/16"}, "expr": "calc"}, {"t": "k′(2), where k(x) = x<sup>2</sup> f(x): __B1__", "a": {"B1": "12"}, "expr": "calc"}], "sol": "f′(2)g(2) + f(2)g′(2) = (−2)(4) + 5(3) = 7.\n(g(2)f′(2) − f(2)g′(2))/g(2)² = (4(−2) − 5(3))/16 = −{23/16}.\nk′(x) = 2x f(x) + x² f′(x), so k′(2) = 4(5) + 4(−2) = 12."}, {"kind": "mcq", "text": "<b>Error analysis.</b> Lena writes d/dx [x<sup>2</sup>/(x + 1)] = 2x/1 = 2x. Which comment is correct?", "opts": ["Wrong: the answer is (x<sup>2</sup> + 2x)/(x + 1)<sup>2</sup>", "Right: differentiate the top and the bottom separately", "Wrong: the answer is (3x<sup>2</sup> + 2x)/(x + 1)<sup>2</sup>", "Wrong: the answer is −(x<sup>2</sup> + 2x)/(x + 1)<sup>2</sup>"], "correct": 0, "tag": "", "sol": "Quotient Rule: ((x + 1)(2x) − x²(1))/(x + 1)² = (x² + 2x)/(x + 1)². Lena used f′/g′. The minus version swaps the order; 3x² + 2x adds the terms instead of subtracting."}, {"kind": "blank", "p": "Find the tangent line to y = 2x/(x + 1) at x = 1.", "tag": "", "marks": "", "flat": [{"t": "y′ = __B1__", "a": {"B1": "2/(x+1)^2"}, "expr": "calc"}, {"t": "Slope at x = 1: __B1__", "a": {"B1": "1/2"}, "expr": "calc"}, {"t": "Tangent line: y = __B1__", "a": {"B1": "(1/2)x+1/2"}, "expr": "calc", "accept": ["1/2x+1/2"]}], "sol": "((x + 1)(2) − 2x(1))/(x + 1)² = 2/(x + 1)².\n2/4 = {1/2}.\ny(1) = 1, so y − 1 = {1/2}(x − 1): y = {1/2}x + {1/2}."}, {"kind": "mcq", "text": "Where does y = x/(x<sup>2</sup> + 9) have horizontal tangents?", "opts": ["x = −3 and x = 3", "x = 3 only", "x = −9 and x = 9", "x = 0 only"], "correct": 0, "tag": "", "sol": "y′ = ((x² + 9) − x · 2x)/(x² + 9)² = (9 − x²)/(x² + 9)². A fraction is 0 when its top is 0: 9 − x² = 0, so x = ±3.", "tools": ["desmos"], "desmos": ["y=x/(x^2+9)"]}]}, {"id": "s4", "label": "4 · Trig, exponential and log derivatives", "sub": "sin, cos, tan, sec, csc, cot · eˣ, aˣ · ln x, logₐx · log laws first", "slides": [{"kind": "mcq", "text": "Differentiate y = sec x.", "opts": ["−csc x cot x", "sec x tan x", "sec<sup>2</sup> x", "tan<sup>2</sup> x"], "correct": 1, "tag": "", "sol": "d/dx [sec x] = sec x tan x. (sec² x is the derivative of tan x; −csc x cot x is the derivative of csc x.)"}, {"kind": "blank", "p": "Complete the table of trigonometric derivatives (x in radians).", "tag": "", "marks": "", "flat": [{"t": "d/dx [sin x] = __B1__", "a": {"B1": "cos(x)"}, "expr": "calc"}, {"t": "d/dx [tan x] = __B1__", "a": {"B1": "sec(x)^2"}, "expr": "calc"}, {"t": "d/dx [csc x] = __B1__", "a": {"B1": "-csc(x)cot(x)"}, "expr": "calc"}, {"t": "d/dx [cot x] = __B1__", "a": {"B1": "-csc(x)^2"}, "expr": "calc"}], "sol": "cos x.\nsec² x (type sec(x)²).\n−csc x cot x: a co-function, so a minus sign.\n−csc² x: a co-function, so a minus sign."}, {"kind": "mcq", "text": "Differentiate y = 3 sin x − 2 cos x.", "opts": ["−3 cos x − 2 sin x", "−3 cos x + 2 sin x", "3 cos x + 2 sin x", "3 cos x − 2 sin x"], "correct": 2, "tag": "", "sol": "(sin x)′ = cos x and (cos x)′ = −sin x, so y′ = 3 cos x − 2(−sin x) = 3 cos x + 2 sin x."}, {"kind": "blank", "p": "Use the Product and Quotient Rules with trig functions.", "tag": "", "marks": "", "flat": [{"t": "f(x) = x<sup>2</sup> sin x  →  f′(x) = __B1__", "a": {"B1": "2x*sin(x)+x^2*cos(x)"}, "expr": "calc"}, {"t": "f′(π/2) = __B1__", "a": {"B1": "pi"}, "expr": "calc"}, {"t": "g(x) = (tan x)/x  →  g′(x) = __B1__", "a": {"B1": "(x*sec(x)^2-tan(x))/x^2"}, "expr": "calc"}], "sol": "2x sin x + x² cos x.\n2(π/2)(1) + (π/2)²(0) = π.\n(x sec² x − tan x · 1)/x²."}, {"kind": "mcq", "text": "Differentiate y = 5e<sup>x</sup> + x<sup>e</sup>. (e ≈ 2.718 is a constant.)", "opts": ["5e<sup>x</sup> + x<sup>e</sup> ln x", "5e<sup>x</sup> + e·x<sup>e−1</sup>", "5e<sup>x</sup> + x<sup>e</sup>", "5xe<sup>x−1</sup> + e·x<sup>e−1</sup>"], "correct": 1, "tag": "", "sol": "e<sup>x</sup> is its own derivative. x<sup>e</sup> is a power of x with a constant exponent, so the Power Rule gives e·x<sup>e−1</sup>. (The Power Rule does not apply to e<sup>x</sup>, whose exponent is the variable.)"}, {"kind": "blank", "p": "Differentiate each exponential function.", "tag": "", "marks": "", "flat": [{"t": "y = 3<sup>x</sup>  →  y′ = __B1__", "a": {"B1": "3^x*ln(3)"}, "expr": "calc"}, {"t": "y = 5 · 2<sup>x</sup>  →  y′ = __B1__", "a": {"B1": "5*2^x*ln(2)"}, "expr": "calc"}, {"t": "y = 10<sup>x</sup> + x<sup>10</sup>  →  y′ = __B1__", "a": {"B1": "10^x*ln(10)+10x^9"}, "expr": "calc"}], "sol": "(a<sup>x</sup>)′ = a<sup>x</sup> ln a: 3<sup>x</sup> ln 3.\n5 · 2<sup>x</sup> ln 2.\n10<sup>x</sup> ln 10 (exponential) + 10x⁹ (power): two different rules."}, {"kind": "mcq", "text": "Differentiate y = ln x + log<sub>10</sub> x.", "opts": ["1/x + 1/(10x)", "1/x + (ln 10)/x", "1/x + 1/(x ln 10)", "1/x + 1/x"], "correct": 2, "tag": "", "sol": "(ln x)′ = 1/x and (log<sub>a</sub> x)′ = 1/(x ln a), so y′ = 1/x + 1/(x ln 10). (log<sub>10</sub> x = ln x / ln 10.)"}, {"kind": "blank", "p": "Differentiate the logarithmic functions.", "tag": "", "marks": "", "flat": [{"t": "y = log<sub>2</sub> x  →  y′ = __B1__", "a": {"B1": "1/(x*ln(2))"}, "expr": "calc"}, {"t": "y = ln(x<sup>7</sup>). Use a log law first: y = __B1__", "a": {"B1": "7ln(x)"}, "expr": "calc"}, {"t": "so y′ = __B1__", "a": {"B1": "7/x"}, "expr": "calc"}, {"t": "y = ln(5x)  →  y′ = __B1__", "a": {"B1": "1/x"}, "expr": "calc"}], "sol": "1/(x ln 2).\nln(x⁷) = 7 ln x.\n7 · (1/x) = 7/x.\nln(5x) = ln 5 + ln x, and ln 5 is a constant: y′ = 1/x."}, {"kind": "mcq", "text": "Differentiate y = ln(x<sup>2</sup>e<sup>4x</sup>). (Simplify with log laws first.)", "opts": ["2/x + 4x", "2/x + 4", "8/x", "1/(x<sup>2</sup>e<sup>4x</sup>)"], "correct": 1, "tag": "", "sol": "ln(x<sup>2</sup>e<sup>4x</sup>) = 2 ln x + ln(e<sup>4x</sup>) = 2 ln x + 4x. So y′ = 2/x + 4. (1/(x<sup>2</sup>e<sup>4x</sup>) forgets that the derivative of ln u is u′/u, not 1/u; 2/x + 4x forgets to differentiate 4x; 8/x multiplies the two derivatives 2/x and 4.)"}, {"kind": "blank", "p": "Simplify with log laws, then differentiate.", "tag": "", "marks": "", "flat": [{"t": "y = ln(x<sup>4</sup>√x). Simplify to y = k ln x: k = __B1__", "a": {"B1": "9/2"}, "expr": "calc"}, {"t": "y′ = __B1__", "a": {"B1": "9/(2x)"}, "expr": "calc"}, {"t": "y = ln(e<sup>3x</sup>/x<sup>2</sup>). Simplify: y = __B1__", "a": {"B1": "3x-2ln(x)"}, "expr": "calc"}, {"t": "y′ = __B1__", "a": {"B1": "3-2/x"}, "expr": "calc"}], "sol": "x⁴ · x<sup>1/2</sup> = x<sup>9/2</sup>, so y = {9/2} ln x.\n{9/2} · 1/x = 9/(2x).\nln(e<sup>3x</sup>) − ln(x²) = 3x − 2 ln x.\n3 − 2/x."}, {"kind": "mcq", "text": "Differentiate y = e<sup>x</sup>(sin x + cos x).", "opts": ["2e<sup>x</sup>(sin x + cos x)", "e<sup>x</sup>(cos x − sin x)", "2e<sup>x</sup> cos x", "2e<sup>x</sup> sin x"], "correct": 2, "tag": "", "sol": "Product Rule: e<sup>x</sup>(sin x + cos x) + e<sup>x</sup>(cos x − sin x) = 2e<sup>x</sup> cos x. (e<sup>x</sup>(cos x − sin x) multiplies the two derivatives; 2e<sup>x</sup>(sin x + cos x) uses (cos x)′ = +sin x; 2e<sup>x</sup> sin x comes from writing (sin x + cos x)′ as sin x − cos x.)"}, {"kind": "blank", "p": "Differentiate y = (ln x)/x.", "tag": "", "marks": "", "flat": [{"t": "Quotient Rule numerator: x · (1/x) − (ln x) · 1 = __B1__", "a": {"B1": "1-ln(x)"}, "expr": "calc"}, {"t": "y′ = __B1__", "a": {"B1": "(1-ln(x))/x^2"}, "expr": "calc"}, {"t": "The value of y′ at x = e: __B1__", "a": {"B1": "0"}, "expr": "calc"}], "sol": "1 − ln x.\n(1 − ln x)/x².\nln e = 1, so the top is 0: the graph has a horizontal tangent at x = e."}, {"kind": "mcq", "text": "Find the tangent line to y = x + ln x at x = 1.", "opts": ["y = 2x", "y = x", "y = 2x − 1", "y = 2x + 1"], "correct": 2, "tag": "", "sol": "y(1) = 1 + 0 = 1. y′ = 1 + 1/x, so y′(1) = 2. Line: y − 1 = 2(x − 1), so y = 2x − 1.", "tools": ["desmos"], "desmos": ["y=x+ln(x)"]}, {"kind": "blank", "p": "f(x) = sec x + tan x. Give exact values.", "tag": "", "marks": "", "flat": [{"t": "f(π/4) = __B1__", "a": {"B1": "sqrt(2)+1"}, "expr": "calc"}, {"t": "f′(x) = __B1__", "a": {"B1": "sec(x)tan(x)+sec(x)^2"}, "expr": "calc"}, {"t": "f′(π/4) = __B1__", "a": {"B1": "2+sqrt(2)"}, "expr": "calc"}], "sol": "sec(π/4) = √2 and tan(π/4) = 1: √2 + 1.\nsec x tan x + sec² x.\n√2 · 1 + (√2)² = √2 + 2."}, {"kind": "mcq", "text": "<b>Error analysis.</b> Priya says d/dx [ln(2x)] = 1/(2x). Which comment is correct?", "opts": ["Wrong: the derivative is 2/x, by the factor 2", "Right: the derivative of ln u is always 1/u", "Wrong: ln(2x) = ln 2 + ln x, so the derivative is 1/x", "Wrong: the derivative is {1/2}, because ln 2x = 2 ln x"], "correct": 2, "tag": "", "sol": "ln(2x) = ln 2 + ln x and ln 2 is a constant, so the derivative is 1/x. (With the Chain Rule: (1/(2x)) · 2 = 1/x, the same.) ln(2x) is not 2 ln x."}]}, {"id": "s5", "label": "5 · Chain rule", "sub": "Powers, trig, exp and log of a function · nested · with Product and Quotient Rules", "slides": [{"kind": "mcq", "text": "Differentiate y = (3x<sup>2</sup> + 1)<sup>5</sup>.", "opts": ["30x(3x<sup>2</sup> + 1)<sup>4</sup>", "30x(3x<sup>2</sup> + 1)<sup>5</sup>", "5(6x)<sup>4</sup>", "5(3x<sup>2</sup> + 1)<sup>4</sup>"], "correct": 0, "tag": "", "sol": "Outer: u⁵ → 5u⁴; inner: u = 3x² + 1, u′ = 6x. y′ = 5(3x² + 1)⁴ · 6x = 30x(3x² + 1)⁴. (5(3x² + 1)⁴ forgets the inner derivative; 5(6x)⁴ changes the inside.)"}, {"kind": "blank", "p": "Differentiate y = (x<sup>3</sup> − 4x)<sup>6</sup> one step at a time.", "tag": "", "marks": "", "flat": [{"t": "Inner function: u = __B1__", "a": {"B1": "x^3-4x"}, "expr": "calc"}, {"t": "Outer function y = u<sup>6</sup>, so dy/du = __B1__ (in terms of u)", "a": {"B1": "6u^5"}, "expr": "calc"}, {"t": "du/dx = __B1__", "a": {"B1": "3x^2-4"}, "expr": "calc"}, {"t": "dy/dx = (dy/du)(du/dx) = __B1__", "a": {"B1": "6(x^3-4x)^5(3x^2-4)"}, "expr": "calc"}], "sol": "The inside of the bracket: u = x³ − 4x.\n6u⁵.\n3x² − 4.\n6(x³ − 4x)⁵(3x² − 4): put u = x³ − 4x back."}, {"kind": "mcq", "text": "Differentiate y = √(4x + 1).", "opts": ["1/(2√(4x + 1))", "2/√(4x + 1)", "4/√(4x + 1)", "2√(4x + 1)"], "correct": 1, "tag": "", "sol": "y = (4x + 1)<sup>1/2</sup>, so y′ = {1/2}(4x + 1)<sup>−1/2</sup> · 4 = 2/√(4x + 1). (1/(2√(4x + 1)) forgets the inner derivative 4; 4/√(4x + 1) forgets the {1/2}.)"}, {"kind": "blank", "p": "Trig of a function: differentiate each.", "tag": "", "marks": "", "flat": [{"t": "y = sin(5x<sup>2</sup>)  →  y′ = __B1__", "a": {"B1": "10x*cos(5x^2)"}, "expr": "calc"}, {"t": "y = cos<sup>3</sup>x = (cos x)<sup>3</sup>  →  y′ = __B1__", "a": {"B1": "-3cos(x)^2*sin(x)"}, "expr": "calc"}, {"t": "y = tan(√x)  →  y′ = __B1__", "a": {"B1": "sec(sqrt(x))^2/(2sqrt(x))"}, "expr": "calc"}], "sol": "cos(5x²) · 10x = 10x cos(5x²).\n3(cos x)² · (−sin x) = −3 cos² x sin x.\nsec²(√x) · 1/(2√x) = sec²(√x)/(2√x)."}, {"kind": "mcq", "text": "Differentiate y = e<sup>x²+3x</sup>.", "opts": ["(2x + 3)e<sup>2x+3</sup>", "(2x + 3)e<sup>x²+3x</sup>", "(x<sup>2</sup> + 3x)e<sup>x²+3x−1</sup>", "e<sup>x²+3x</sup>"], "correct": 1, "tag": "", "sol": "(e<sup>u</sup>)′ = e<sup>u</sup> · u′ with u = x² + 3x, so y′ = (2x + 3)e<sup>x²+3x</sup>. The exponent stays the same; e<sup>u</sup> is not a power of u."}, {"kind": "blank", "p": "Exponential and logarithm of a function: differentiate each.", "tag": "", "marks": "", "flat": [{"t": "y = ln(x<sup>2</sup> + 4)  →  y′ = __B1__", "a": {"B1": "2x/(x^2+4)"}, "expr": "calc"}, {"t": "y = e<sup>−3x</sup>  →  y′ = __B1__", "a": {"B1": "-3e^(-3x)"}, "expr": "calc"}, {"t": "y = 2<sup>x²</sup>  →  y′ = __B1__", "a": {"B1": "2x*2^(x^2)*ln(2)"}, "expr": "calc"}, {"t": "y = log<sub>3</sub>(2x + 5)  →  y′ = __B1__", "a": {"B1": "2/((2x+5)ln(3))"}, "expr": "calc"}], "sol": "u′/u = 2x/(x² + 4).\ne<sup>−3x</sup> · (−3) = −3e<sup>−3x</sup>.\n2<sup>x²</sup> ln 2 · 2x.\n(1/((2x + 5) ln 3)) · 2 = 2/((2x + 5) ln 3)."}, {"kind": "mcq", "text": "Differentiate y = sin<sup>3</sup>(4x).", "opts": ["3 sin<sup>2</sup>(4x) cos(4x)", "−12 sin<sup>2</sup>(4x) cos(4x)", "12 cos<sup>2</sup>(4x)", "12 sin<sup>2</sup>(4x) cos(4x)"], "correct": 3, "tag": "", "sol": "Three layers: cube, sine, 4x. y′ = 3 sin²(4x) · cos(4x) · 4 = 12 sin²(4x) cos(4x). (3 sin²(4x) cos(4x) misses the innermost factor 4.)"}, {"kind": "blank", "p": "Differentiate y = e<sup>cos(2x)</sup>, working from the inside out.", "tag": "", "marks": "", "flat": [{"t": "Innermost: d/dx [2x] = __B1__", "a": {"B1": "2"}, "expr": "calc"}, {"t": "Middle: d/dx [cos(2x)] = __B1__", "a": {"B1": "-2sin(2x)"}, "expr": "calc"}, {"t": "dy/dx = __B1__", "a": {"B1": "-2sin(2x)e^(cos(2x))"}, "expr": "calc"}], "sol": "2.\n−sin(2x) · 2 = −2 sin(2x).\ne<sup>cos(2x)</sup> · (−2 sin(2x)) = −2 sin(2x) e<sup>cos(2x)</sup>."}, {"kind": "mcq", "text": "Differentiate y = ln(√(x<sup>2</sup> + 1)).", "opts": ["x/√(x<sup>2</sup> + 1)", "2x/(x<sup>2</sup> + 1)", "1/√(x<sup>2</sup> + 1)", "x/(x<sup>2</sup> + 1)"], "correct": 3, "tag": "", "sol": "Simplify first: y = {1/2} ln(x² + 1). Then y′ = {1/2} · 2x/(x² + 1) = x/(x² + 1). (2x/(x² + 1) forgets the {1/2}.)"}, {"kind": "blank", "p": "Nested functions: differentiate each.", "tag": "", "marks": "", "flat": [{"t": "y = (1 + sin 3x)<sup>4</sup>. Derivative of the inside: d/dx [1 + sin 3x] = __B1__", "a": {"B1": "3cos(3x)"}, "expr": "calc"}, {"t": "dy/dx = __B1__", "a": {"B1": "12cos(3x)(1+sin(3x))^3"}, "expr": "calc"}, {"t": "y = cos<sup>2</sup>(e<sup>x</sup>)  →  dy/dx = __B1__", "a": {"B1": "-2e^x*cos(e^x)*sin(e^x)"}, "expr": "calc"}], "sol": "3 cos 3x.\n4(1 + sin 3x)³ · 3 cos 3x = 12 cos 3x (1 + sin 3x)³.\n2 cos(e<sup>x</sup>) · (−sin(e<sup>x</sup>)) · e<sup>x</sup> = −2e<sup>x</sup> sin(e<sup>x</sup>) cos(e<sup>x</sup>)."}, {"kind": "mcq", "text": "Differentiate y = x<sup>2</sup>(2x − 1)<sup>3</sup>.", "opts": ["2x(2x − 1)<sup>3</sup> + 3x<sup>2</sup>(2x − 1)<sup>2</sup>", "2x(2x − 1)<sup>3</sup> + 6x<sup>2</sup>(2x − 1)<sup>2</sup>", "6x<sup>2</sup>(2x − 1)<sup>2</sup>", "12x(2x − 1)<sup>2</sup>"], "correct": 1, "tag": "", "sol": "Product Rule, with the Chain Rule on the second factor: 2x(2x − 1)³ + x² · 3(2x − 1)² · 2 = 2x(2x − 1)³ + 6x²(2x − 1)². (The 3x² version forgets the inner 2; 12x(2x − 1)² multiplies the two derivatives.)"}, {"kind": "blank", "p": "The Chain Rule with the Quotient Rule.", "tag": "", "marks": "", "flat": [{"t": "d/dx [√(x<sup>2</sup> + 1)] = __B1__", "a": {"B1": "x/sqrt(x^2+1)"}, "expr": "calc"}, {"t": "y = x/√(x<sup>2</sup> + 1)  →  y′ = __B1__ (simplify)", "a": {"B1": "1/(x^2+1)^(3/2)"}, "expr": "calc"}, {"t": "y = e<sup>2x</sup>/(x + 1)  →  y′ = __B1__", "a": {"B1": "e^(2x)(2x+1)/(x+1)^2"}, "expr": "calc"}], "sol": "2x/(2√(x² + 1)) = x/√(x² + 1).\n(√(x² + 1) · 1 − x · x/√(x² + 1))/(x² + 1). Multiply top and bottom by √(x² + 1): (x² + 1 − x²)/(x² + 1)<sup>3/2</sup> = 1/(x² + 1)<sup>3/2</sup>.\n((x + 1) · 2e<sup>2x</sup> − e<sup>2x</sup> · 1)/(x + 1)² = e<sup>2x</sup>(2x + 1)/(x + 1)²."}, {"kind": "mcq", "text": "h(x) = f(g(x)), with g(1) = 3, g′(1) = 2, f′(1) = 4 and f′(3) = 5. Find h′(1).", "opts": ["15", "5", "10", "8"], "correct": 2, "tag": "", "sol": "h′(1) = f′(g(1)) · g′(1) = f′(3) · 2 = 5 · 2 = 10. (8 uses f′(1), evaluating f′ at x instead of at g(x); 15 multiplies by g(1) instead of g′(1).)"}, {"kind": "blank", "p": "A cup of coffee cools so that its temperature after t minutes is T = 20 + 60e<sup>−0.1t</sup> °C.", "tag": "", "marks": "", "flat": [{"t": "dT/dt = __B1__", "a": {"B1": "-6e^(-0.1t)"}, "expr": "calc"}, {"t": "At t = 10, dT/dt = __B1__ °C per minute (2 d.p.)", "a": {"B1": "-2.21"}, "expr": "approx"}, {"t": "At t = 10 the coffee is __B1__ (cooling / warming)", "a": {"B1": "cooling"}, "expr": "words"}], "sol": "60 · e<sup>−0.1t</sup> · (−0.1) = −6e<sup>−0.1t</sup>.\n−6e<sup>−1</sup> = −6/e ≈ −2.21 °C per minute.\ndT/dt is negative, so the temperature is falling: the coffee is cooling."}, {"kind": "mcq", "text": "Find the tangent line to y = (x<sup>2</sup> − 3)<sup>4</sup> at x = 2.", "opts": ["y = 16x + 1", "y = 16x − 31", "y = 4x − 7", "y = 16x − 32"], "correct": 1, "tag": "", "sol": "y(2) = 1⁴ = 1. y′ = 4(x² − 3)³ · 2x = 8x(x² − 3)³, so y′(2) = 16. Line: y − 1 = 16(x − 2), so y = 16x − 31. (Slope 4 forgets the inner derivative 2x.)"}]}, {"id": "s6", "label": "6 · Chain rule (Paul)", "sub": "Paul’s Online Math Notes · Chain Rule problems 1–27", "slides": [{"kind": "blank", "p": "<b>Paul · Problem 1</b> · Differentiate f(x) = (6x² + 7x)⁴.", "tag": "", "marks": "", "flat": [{"t": "Inner function: u = __B1__", "a": {"B1": "6x^2+7x"}, "expr": "calc"}, {"t": "du/dx = __B1__", "a": {"B1": "12x+7"}, "expr": "calc"}, {"t": "Outer function u⁴: d/du (u⁴) = __B1__ (in terms of u)", "a": {"B1": "4u^3"}, "expr": "calc"}, {"t": "f′(x) = __B1__", "a": {"B1": "4(6x^2+7x)^3(12x+7)"}, "expr": "calc"}], "sol": "The power 4 is the outer layer; inside it is u = 6x² + 7x.\ndu/dx = 12x + 7.\nd/du (u⁴) = 4u³.\nf′(x) = 4u³ · du/dx = 4(6x² + 7x)³(12x + 7)."}, {"kind": "mcq", "text": "<b>Paul · Problem 2</b> · Differentiate g(t) = (4t² − 3t + 2)<sup>−2</sup>.", "opts": ["−2(8t − 3)(4t² − 3t + 2)<sup>−1</sup>", "−2(4t² − 3t + 2)<sup>−3</sup>", "−2(8t − 3)(4t² − 3t + 2)<sup>−3</sup>", "−2(8t − 3)<sup>−3</sup>"], "correct": 2, "tag": "", "sol": "Outer: u<sup>−2</sup> → −2u<sup>−3</sup> (the power goes down by 1: −2 − 1 = −3). Inner: u = 4t² − 3t + 2, u′ = 8t − 3. So g′(t) = −2(8t − 3)(4t² − 3t + 2)<sup>−3</sup>. Leaving out (8t − 3) forgets the inner derivative; the power −1 comes from adding 1 instead of subtracting; (8t − 3)<sup>−3</sup> differentiates the inside instead of keeping it."}, {"kind": "mcq", "text": "<b>Paul · Problem 3</b> · Differentiate y = ∛(1 − 8z).", "opts": ["−(8/3)(1 − 8z)<sup>2/3</sup>", "−8(1 − 8z)<sup>−2/3</sup>", "−(8/3)(1 − 8z)<sup>−2/3</sup>", "(1/3)(1 − 8z)<sup>−2/3</sup>"], "correct": 2, "tag": "", "sol": "Rewrite y = (1 − 8z)<sup>1/3</sup>. Outer: u<sup>1/3</sup> → (1/3)u<sup>−2/3</sup>. Inner: u = 1 − 8z, u′ = −8. So y′ = (1/3)(1 − 8z)<sup>−2/3</sup> · (−8) = −(8/3)(1 − 8z)<sup>−2/3</sup> = −8 / (3∛((1 − 8z)²)). (1/3)(1 − 8z)<sup>−2/3</sup> forgets the −8; −8(…) drops the 1/3; the power 2/3 comes from adding 1 to the exponent instead of subtracting."}, {"kind": "blank", "p": "<b>Paul · Problem 4</b> · Differentiate R(w) = csc(7w).", "tag": "", "marks": "", "flat": [{"t": "Inner function: u = __B1__", "a": {"B1": "7w"}, "expr": "calc"}, {"t": "Outer function csc u: d/du (csc u) = __B1__ (in terms of u)", "a": {"B1": "-csc(u)cot(u)"}, "expr": "calc"}, {"t": "R′(w) = __B1__", "a": {"B1": "-7csc(7w)cot(7w)"}, "expr": "calc"}], "sol": "The cosecant is the outer layer; inside it is u = 7w, with du/dw = 7.\nd/du (csc u) = −csc u cot u.\nR′(w) = −csc(7w) cot(7w) · 7 = −7 csc(7w) cot(7w)."}, {"kind": "blank", "p": "<b>Paul · Problem 5</b> · Differentiate G(x) = 2 sin(3x + tan x).", "tag": "", "marks": "", "flat": [{"t": "Inner function: u = __B1__", "a": {"B1": "3x+tan(x)"}, "expr": "calc"}, {"t": "du/dx = __B1__", "a": {"B1": "3+sec^2(x)"}, "expr": "calc"}, {"t": "G′(x) = __B1__", "a": {"B1": "2(3+sec^2(x))cos(3x+tan(x))"}, "expr": "calc"}], "sol": "Inside the sine is u = 3x + tan x.\ndu/dx = 3 + sec²x.\nThe 2 stays; sin u → cos u. G′(x) = 2(3 + sec²x) cos(3x + tan x)."}, {"kind": "mcq", "text": "<b>Paul · Problem 6</b> · Differentiate h(u) = tan(4 + 10u).", "opts": ["10 sec(4 + 10u) tan(4 + 10u)", "10 sec²(4 + 10u)", "(4 + 10u) sec²(4 + 10u)", "sec²(4 + 10u)"], "correct": 1, "tag": "", "sol": "Outer: tan → sec². Inner: 4 + 10u, whose derivative is 10. So h′(u) = 10 sec²(4 + 10u). sec²(4 + 10u) forgets the inner derivative; sec · tan is the derivative of sec, not tan; (4 + 10u) multiplies by the inner function instead of its derivative."}, {"kind": "blank", "p": "<b>Paul · Problem 7</b> · Differentiate f(t) = 5 + e<sup>4t + t⁷</sup>.", "tag": "", "marks": "", "flat": [{"t": "Inner function (the exponent): u = __B1__", "a": {"B1": "4t+t^7"}, "expr": "calc"}, {"t": "du/dt = __B1__", "a": {"B1": "4+7t^6"}, "expr": "calc"}, {"t": "f′(t) = __B1__", "a": {"B1": "(4+7t^6)e^(4t+t^7)"}, "expr": "calc"}], "sol": "The exponent is the inner function: u = 4t + t⁷.\ndu/dt = 4 + 7t⁶.\nThe constant 5 has derivative 0, and d/du (e<sup>u</sup>) = e<sup>u</sup>, so f′(t) = (4 + 7t⁶) e<sup>4t + t⁷</sup>."}, {"kind": "mcq", "text": "<b>Paul · Problem 8</b> · Differentiate g(x) = e<sup>1 − cos x</sup>.", "opts": ["e<sup>1 − cos x</sup>", "−sin x · e<sup>1 − cos x</sup>", "(1 − cos x) e<sup>−cos x</sup>", "sin x · e<sup>1 − cos x</sup>"], "correct": 3, "tag": "", "sol": "Outer: e<sup>u</sup> → e<sup>u</sup>. Inner: u = 1 − cos x, so u′ = 0 − (−sin x) = sin x. g′(x) = sin x · e<sup>1 − cos x</sup>. e<sup>1 − cos x</sup> alone forgets u′; −sin x is a sign slip with −cos x; (1 − cos x)e<sup>−cos x</sup> wrongly uses the power rule on e<sup>u</sup>."}, {"kind": "blank", "p": "<b>Paul · Problem 9</b> · Differentiate H(z) = 2<sup>1 − 6z</sup>.", "tag": "", "marks": "", "flat": [{"t": "Inner function: u = __B1__", "a": {"B1": "1-6z"}, "expr": "calc"}, {"t": "Outer function 2<sup>u</sup>: d/du (2<sup>u</sup>) = __B1__ (in terms of u; type ln(2))", "a": {"B1": "2^u*ln(2)"}, "expr": "calc"}, {"t": "H′(z) = __B1__", "a": {"B1": "-6ln(2)*2^(1-6z)"}, "expr": "calc"}], "sol": "The exponent u = 1 − 6z is the inner function; du/dz = −6.\nd/du (aᵘ) = aᵘ ln a, so d/du (2ᵘ) = 2ᵘ ln 2.\nH′(z) = 2<sup>1 − 6z</sup> ln 2 · (−6) = −6 ln 2 · 2<sup>1 − 6z</sup>."}, {"kind": "mcq", "text": "<b>Paul · Problem 10</b> · Differentiate u(t) = tan⁻¹(3t − 1).", "opts": ["3 / (1 + (3t − 1)²)", "1 / (1 + (3t − 1)²)", "3 sec²(3t − 1)", "−3 csc²(3t − 1)"], "correct": 0, "tag": "", "sol": "d/dx tan⁻¹x = 1/(1 + x²). With the inner function 3t − 1 (derivative 3): u′(t) = 3/(1 + (3t − 1)²). Without the 3 the inner derivative is missing; 3 sec²(3t − 1) is the derivative of tan, not tan⁻¹; −3 csc² treats tan⁻¹ as 1/tan, which it is not."}, {"kind": "blank", "p": "<b>Paul · Problem 11</b> · Differentiate F(y) = ln(1 − 5y² + y³).", "tag": "", "marks": "", "flat": [{"t": "Inner function: u = __B1__", "a": {"B1": "1-5y^2+y^3"}, "expr": "calc"}, {"t": "du/dy = __B1__", "a": {"B1": "3y^2-10y"}, "expr": "calc"}, {"t": "F′(y) = __B1__", "a": {"B1": "(3y^2-10y)/(1-5y^2+y^3)"}, "expr": "calc"}], "sol": "Inside the logarithm is u = 1 − 5y² + y³.\ndu/dy = −10y + 3y².\nd/du (ln u) = 1/u, so F′(y) = (3y² − 10y)/(1 − 5y² + y³)."}, {"kind": "mcq", "text": "<b>Paul · Problem 12</b> · Differentiate V(x) = ln(sin x − cot x).", "opts": ["(cos x + csc²x) / (sin x − cot x)", "1 / (sin x − cot x)", "(cos x − csc²x) / (sin x − cot x)", "(cos x + csc²x) / (sin x − cot x)²"], "correct": 0, "tag": "", "sol": "ln u → u′/u with u = sin x − cot x. Since (cot x)′ = −csc²x, u′ = cos x − (−csc²x) = cos x + csc²x. So V′(x) = (cos x + csc²x)/(sin x − cot x). 1/(sin x − cot x) forgets u′; cos x − csc²x loses the double minus; squaring the bottom mixes the rule up with the quotient rule."}, {"kind": "blank", "p": "<b>Paul · Problem 13</b> · Differentiate h(z) = sin(z⁶) + sin⁶(z).", "tag": "", "marks": "", "flat": [{"t": "d/dz sin(z⁶) = __B1__", "a": {"B1": "6z^5cos(z^6)"}, "expr": "calc"}, {"t": "d/dz sin⁶(z) = d/dz [sin z]⁶ = __B1__", "a": {"B1": "6sin^5(z)cos(z)"}, "expr": "calc"}, {"t": "h′(z) = __B1__", "a": {"B1": "6z^5cos(z^6)+6sin^5(z)cos(z)"}, "expr": "calc"}], "sol": "In sin(z⁶) the sine is outside and z⁶ inside: cos(z⁶) · 6z⁵.\nIn sin⁶(z) = [sin z]⁶ the power is outside and sin z inside: 6 sin⁵z · cos z.\nh′(z) = 6z⁵ cos(z⁶) + 6 sin⁵(z) cos(z). The two terms look alike but have their layers the other way round."}, {"kind": "mcq", "text": "<b>Paul · Problem 14</b> · Differentiate S(w) = √(7w) + e<sup>−w</sup>.", "opts": ["(7/2)√(7w) − e<sup>−w</sup>", "1 / (2√(7w)) − e<sup>−w</sup>", "7 / (2√(7w)) − e<sup>−w</sup>", "7 / (2√(7w)) + e<sup>−w</sup>"], "correct": 2, "tag": "", "sol": "√(7w) = (7w)<sup>1/2</sup> → (1/2)(7w)<sup>−1/2</sup> · 7 = 7/(2√(7w)). e<sup>−w</sup> → e<sup>−w</sup> · (−1) = −e<sup>−w</sup>. So S′(w) = 7/(2√(7w)) − e<sup>−w</sup>. 1/(2√(7w)) forgets the inner 7; + e<sup>−w</sup> forgets the −1 from the exponent; (7/2)√(7w) keeps the power 1/2 instead of lowering it."}, {"kind": "blank", "p": "<b>Paul · Problem 15</b> · Differentiate g(z) = 3z⁷ − sin(z² + 6).", "tag": "", "marks": "", "flat": [{"t": "d/dz (3z⁷) = __B1__", "a": {"B1": "21z^6"}, "expr": "calc"}, {"t": "Inner function of the sine: u = z² + 6, du/dz = __B1__", "a": {"B1": "2z"}, "expr": "calc"}, {"t": "g′(z) = __B1__", "a": {"B1": "21z^6-2zcos(z^2+6)"}, "expr": "calc"}], "sol": "Power rule: 3 · 7z⁶ = 21z⁶.\ndu/dz = 2z.\nsin u → cos u · u′, and the minus sign stays: g′(z) = 21z⁶ − 2z cos(z² + 6)."}, {"kind": "mcq", "text": "<b>Paul · Problem 16</b> · Differentiate f(x) = ln(sin x) − (x⁴ − 3x)¹⁰.", "opts": ["cot x − 10(4x³ − 3)(x⁴ − 3x)⁹", "1/sin x − 10(x⁴ − 3x)⁹", "cot x − 10(x⁴ − 3x)⁹", "tan x − 10(4x³ − 3)(x⁴ − 3x)⁹"], "correct": 0, "tag": "", "sol": "ln(sin x) → (cos x)/(sin x) = cot x. (x⁴ − 3x)¹⁰ → 10(x⁴ − 3x)⁹ · (4x³ − 3). So f′(x) = cot x − 10(4x³ − 3)(x⁴ − 3x)⁹. 1/sin x and the missing (4x³ − 3) forget the inner derivatives; tan x turns the fraction cos/sin upside down."}, {"kind": "blank", "p": "<b>Paul · Problem 17</b> · Differentiate h(t) = t⁶ √(5t² − t). (Product rule, with the chain rule inside.)", "tag": "", "marks": "", "flat": [{"t": "d/dt (t⁶) = __B1__", "a": {"B1": "6t^5"}, "expr": "calc"}, {"t": "d/dt √(5t² − t) = __B1__", "a": {"B1": "(10t-1)/(2sqrt(5t^2-t))"}, "expr": "calc", "accept": ["1/2(5t^2-t)^(-1/2)(10t-1)", "1/2(5t^2-t)^(-1/2)*(10t-1)"]}, {"t": "h′(t) = __B1__", "a": {"B1": "6t^5sqrt(5t^2-t)+t^6(10t-1)/(2sqrt(5t^2-t))"}, "expr": "calc"}], "sol": "6t⁵.\n√u → u′/(2√u) with u = 5t² − t and u′ = 10t − 1: (10t − 1)/(2√(5t² − t)).\nProduct rule (first)′ · second + first · (second)′: h′(t) = 6t⁵√(5t² − t) + t⁶(10t − 1)/(2√(5t² − t))."}, {"kind": "mcq", "text": "<b>Paul · Problem 18</b> · Differentiate q(t) = t² ln(t⁵).", "opts": ["2t ln(t⁵) + t<sup>−3</sup>", "2t ln(t⁵) + 5t⁶", "2t ln(t⁵) + 5t", "(2t)(5/t) = 10"], "correct": 2, "tag": "", "sol": "Product rule: q′ = 2t · ln(t⁵) + t² · d/dt ln(t⁵). By the chain rule d/dt ln(t⁵) = 5t⁴/t⁵ = 5/t, so the second term is t² · 5/t = 5t. q′(t) = 2t ln(t⁵) + 5t. (You can also write ln(t⁵) = 5 ln t first.) t<sup>−3</sup> forgets the 5t⁴; 5t⁶ forgets to divide by t⁵; 10 multiplies the two derivatives."}, {"kind": "blank", "p": "<b>Paul · Problem 19</b> · Differentiate g(w) = cos(3w) sec(1 − w).", "tag": "", "marks": "", "flat": [{"t": "d/dw cos(3w) = __B1__", "a": {"B1": "-3sin(3w)"}, "expr": "calc"}, {"t": "d/dw sec(1 − w) = __B1__", "a": {"B1": "-sec(1-w)tan(1-w)"}, "expr": "calc"}, {"t": "g′(w) = __B1__", "a": {"B1": "-3sin(3w)sec(1-w)-cos(3w)sec(1-w)tan(1-w)"}, "expr": "calc"}], "sol": "cos u → −sin u · u′ with u′ = 3: −3 sin(3w).\nsec u → sec u tan u · u′ with u = 1 − w, u′ = −1: −sec(1 − w) tan(1 − w).\nProduct rule: g′(w) = −3 sin(3w) sec(1 − w) − cos(3w) sec(1 − w) tan(1 − w)."}, {"kind": "mcq", "text": "<b>Paul · Problem 20</b> · Differentiate y = sin(3t) / (1 + t²).", "opts": ["[cos(3t)(1 + t²) − 2t sin(3t)] / (1 + t²)²", "[2t sin(3t) − 3cos(3t)(1 + t²)] / (1 + t²)²", "3cos(3t) / (2t)", "[3cos(3t)(1 + t²) − 2t sin(3t)] / (1 + t²)²"], "correct": 3, "tag": "", "sol": "Quotient rule with top sin(3t), (top)′ = 3cos(3t) (chain rule), bottom 1 + t², (bottom)′ = 2t: y′ = [3cos(3t)(1 + t²) − 2t sin(3t)]/(1 + t²)². [2t sin(3t) − 3cos(3t)(1 + t²)]/(1 + t²)² swaps the order in the numerator (wrong sign); cos(3t)(1 + t²) without the 3 forgets the chain rule; 3cos(3t)/(2t) divides the derivatives."}, {"kind": "blank", "p": "<b>Paul · Problem 21</b> · Differentiate K(x) = (1 + e<sup>−2x</sup>) / (x + tan(12x)).", "tag": "", "marks": "", "flat": [{"t": "Derivative of the numerator: __B1__", "a": {"B1": "-2e^(-2x)"}, "expr": "calc"}, {"t": "Derivative of the denominator: __B1__", "a": {"B1": "1+12sec^2(12x)"}, "expr": "calc"}, {"t": "K′(x) = __B1__", "a": {"B1": "(-2e^(-2x)(x+tan(12x))-(1+e^(-2x))(1+12sec^2(12x)))/(x+tan(12x))^2"}, "expr": "calc"}], "sol": "(e<sup>−2x</sup>)′ = −2e<sup>−2x</sup> (chain rule).\n(tan(12x))′ = 12 sec²(12x), so the denominator has derivative 1 + 12 sec²(12x).\nQuotient rule: K′(x) = [−2e<sup>−2x</sup>(x + tan(12x)) − (1 + e<sup>−2x</sup>)(1 + 12 sec²(12x))] / (x + tan(12x))²."}, {"kind": "mcq", "text": "<b>Paul · Problem 22</b> · Differentiate f(x) = cos(x² eˣ).", "opts": ["−(2x eˣ + x² eˣ) sin(x² eˣ)", "−sin(x² eˣ)", "(2x eˣ + x² eˣ) sin(x² eˣ)", "−2x eˣ sin(x² eˣ)"], "correct": 0, "tag": "", "sol": "Outer: cos u → −sin u. Inner: u = x²eˣ needs the product rule: u′ = 2x eˣ + x² eˣ. f′(x) = −(2x eˣ + x² eˣ) sin(x² eˣ) = −x eˣ(x + 2) sin(x² eˣ). −sin(x² eˣ) alone forgets u′; −2x eˣ sin(x² eˣ) differentiates only the x² in the product; the version without the minus sign loses the minus of (cos u)′."}, {"kind": "blank", "p": "<b>Paul · Problem 23</b> · Differentiate z = √(5x + tan(4x)).", "tag": "", "marks": "", "flat": [{"t": "Inner function: u = __B1__", "a": {"B1": "5x+tan(4x)"}, "expr": "calc"}, {"t": "Outer function √u: d/du (√u) = __B1__ (in terms of u)", "a": {"B1": "1/(2sqrt(u))"}, "expr": "calc"}, {"t": "du/dx = __B1__", "a": {"B1": "5+4sec^2(4x)"}, "expr": "calc"}, {"t": "dz/dx = __B1__", "a": {"B1": "(5+4sec^2(4x))/(2sqrt(5x+tan(4x)))"}, "expr": "calc"}], "sol": "Under the root is u = 5x + tan(4x).\n√u = u<sup>1/2</sup> → (1/2)u<sup>−1/2</sup> = 1/(2√u).\ndu/dx = 5 + 4 sec²(4x) (chain rule on tan(4x)).\ndz/dx = (5 + 4 sec²(4x)) / (2√(5x + tan(4x)))."}, {"kind": "mcq", "text": "<b>Paul · Problem 24</b> · Differentiate f(t) = (e<sup>−6t</sup> + sin(2 − t))³.", "opts": ["3(e<sup>−6t</sup> + sin(2 − t))² (−6e<sup>−6t</sup> + cos(2 − t))", "3(−6e<sup>−6t</sup> − cos(2 − t))²", "3(e<sup>−6t</sup> + sin(2 − t))²", "3(e<sup>−6t</sup> + sin(2 − t))² (−6e<sup>−6t</sup> − cos(2 − t))"], "correct": 3, "tag": "", "sol": "Outer: u³ → 3u². Inner: u = e<sup>−6t</sup> + sin(2 − t), u′ = −6e<sup>−6t</sup> + cos(2 − t) · (−1) = −6e<sup>−6t</sup> − cos(2 − t). So f′(t) = 3(e<sup>−6t</sup> + sin(2 − t))²(−6e<sup>−6t</sup> − cos(2 − t)). The version with + cos(2 − t) forgets the −1 from (2 − t); 3(e<sup>−6t</sup> + sin(2 − t))² alone forgets u′; 3(−6e<sup>−6t</sup> − cos(2 − t))² squares the inner derivative instead of keeping the inside."}, {"kind": "mcq", "text": "<b>Paul · Problem 25</b> · Differentiate g(x) = (ln(x² + 1) − tan⁻¹(6x))¹⁰.", "opts": ["10(ln(x² + 1) − tan⁻¹(6x))⁹ (1/(x² + 1) − 1/(1 + 36x²))", "10(ln(x² + 1) − tan⁻¹(6x))⁹ (2x/(x² + 1) − 6/(1 + 6x²))", "10(ln(x² + 1) − tan⁻¹(6x))⁹", "10(ln(x² + 1) − tan⁻¹(6x))⁹ (2x/(x² + 1) − 6/(1 + 36x²))"], "correct": 3, "tag": "", "sol": "Outer: u¹⁰ → 10u⁹. Inner: u = ln(x² + 1) − tan⁻¹(6x). Each piece needs the chain rule again: (ln(x² + 1))′ = 2x/(x² + 1) and (tan⁻¹(6x))′ = 6/(1 + (6x)²) = 6/(1 + 36x²). So g′(x) = 10(ln(x² + 1) − tan⁻¹(6x))⁹(2x/(x² + 1) − 6/(1 + 36x²)). 6/(1 + 6x²) does not square the 6 in (6x)²; 1/(x² + 1) − 1/(1 + 36x²) forgets both inner derivatives 2x and 6; 10(…)⁹ alone forgets u′."}, {"kind": "blank", "p": "<b>Paul · Problem 26</b> · Differentiate h(z) = tan⁴(z² + 1). (Three layers: a power, a tangent, then z² + 1.)", "tag": "", "marks": "", "flat": [{"t": "Innermost function: __B1__", "a": {"B1": "z^2+1"}, "expr": "calc"}, {"t": "d/dz tan(z² + 1) = __B1__", "a": {"B1": "2zsec^2(z^2+1)"}, "expr": "calc"}, {"t": "h(z) = [tan(z² + 1)]⁴, so h′(z) = __B1__", "a": {"B1": "8ztan^3(z^2+1)sec^2(z^2+1)"}, "expr": "calc"}], "sol": "From the inside out: z² + 1, then tan, then the 4th power.\ntan u → sec²u · u′ with u′ = 2z: 2z sec²(z² + 1).\nPower layer: 4 tan³(z² + 1) times the derivative of tan(z² + 1): h′(z) = 4 tan³(z² + 1) · 2z sec²(z² + 1) = 8z tan³(z² + 1) sec²(z² + 1)."}, {"kind": "blank", "p": "<b>Paul · Problem 27</b> · Differentiate f(x) = (∛(12x) + sin²(3x))<sup>−1</sup>.", "tag": "", "marks": "", "flat": [{"t": "d/dx ∛(12x) = d/dx (12x)<sup>1/3</sup> = __B1__", "a": {"B1": "4(12x)^(-2/3)"}, "expr": "calc", "accept": ["1/3(12x)^(-2/3)(12)"]}, {"t": "d/dx sin²(3x) = __B1__", "a": {"B1": "6sin(3x)cos(3x)"}, "expr": "calc"}, {"t": "f′(x) = __B1__", "a": {"B1": "-(4(12x)^(-2/3)+6sin(3x)cos(3x))/((12x)^(1/3)+sin^2(3x))^2"}, "expr": "calc"}], "sol": "(1/3)(12x)<sup>−2/3</sup> · 12 = 4(12x)<sup>−2/3</sup>.\nPower outside, sin(3x) inside, 3x innermost: 2 sin(3x) · cos(3x) · 3 = 6 sin(3x) cos(3x) (= 3 sin(6x)).\nu<sup>−1</sup> → −u<sup>−2</sup> · u′: f′(x) = −(4(12x)<sup>−2/3</sup> + 6 sin(3x) cos(3x)) / (∛(12x) + sin²(3x))²."}]}, {"id": "s7", "label": "7 · Implicit & higher", "sub": "dy/dx implicitly, tangent lines, f″, f‴ and nth-derivative patterns", "slides": [{"kind": "mcq", "text": "For the circle x² + y² = 36, find dy/dx.", "opts": ["x/y", "−x/y", "−2x", "−y/x"], "correct": 1, "tag": "", "sol": "Differentiate both sides: 2x + 2y · dy/dx = 0, so dy/dx = −2x/(2y) = −x/y. (x/y loses the minus sign; −y/x is upside down; −2x forgets the y-term.)"}, {"kind": "blank", "p": "Find dy/dx for the curve x² + xy + y² = 19.", "tag": "", "marks": "", "flat": [{"t": "d/dx (x²) = __B1__", "a": {"B1": "2x"}, "expr": "calc"}, {"t": "d/dx (xy) = __B1__ + x · dy/dx   (product rule)", "a": {"B1": "y"}, "expr": "calc"}, {"t": "d/dx (y²) = __B1__ · dy/dx", "a": {"B1": "2y"}, "expr": "calc"}, {"t": "Collect the dy/dx terms and solve: dy/dx = __B1__", "a": {"B1": "-(2x+y)/(x+2y)"}, "expr": "calc"}], "sol": "2x.\nProduct rule: (x)′ · y + x · (y)′ = y + x · dy/dx.\nChain rule: 2y · dy/dx.\n2x + y + (x + 2y) · dy/dx = 0, so dy/dx (x + 2y) = −(2x + y) and dy/dx = −(2x + y)/(x + 2y)."}, {"kind": "mcq", "text": "On the curve x² + xy + y² = 19, what is the slope of the tangent line at the point (2, 3)?", "opts": ["7/8", "−8/7", "−4/3", "−7/8"], "correct": 3, "tag": "", "sol": "From dy/dx = −(2x + y)/(x + 2y): at (2, 3), dy/dx = −(4 + 3)/(2 + 6) = −7/8. (−8/7 is the fraction upside down; −4/3 uses only the x² and y² terms, −2x/(2y).)"}, {"kind": "blank", "p": "Find the tangent line to the curve x²y + y³ = 10 at the point (3, 1).", "tag": "", "marks": "", "flat": [{"t": "Implicitly: 2xy + x² · dy/dx + 3y² · dy/dx = 0, so dy/dx = __B1__", "a": {"B1": "-2xy/(x^2+3y^2)"}, "expr": "calc"}, {"t": "Slope at (3, 1): __B1__", "a": {"B1": "-1/2"}, "expr": "calc"}, {"t": "Tangent line: y = __B1__", "a": {"B1": "-x/2+5/2"}, "expr": "calc", "accept": ["-1/2x+5/2"]}], "sol": "x²y is a product: 2xy + x² y′. y³ gives 3y² y′. So y′(x² + 3y²) = −2xy and y′ = −2xy/(x² + 3y²).\nAt (3, 1): −2(3)(1)/(9 + 3) = −6/12 = −1/2.\ny − 1 = −(1/2)(x − 3), so y = −x/2 + 5/2."}, {"kind": "mcq", "text": "If sin y = x, find dy/dx.", "opts": ["1/cos y", "1/sin y", "−1/cos y", "cos y"], "correct": 0, "tag": "", "sol": "Differentiate both sides with respect to x: cos y · dy/dx = 1, so dy/dx = 1/cos y = sec y. (cos y forgets to divide; 1/sin y uses the wrong derivative of sin y.)"}, {"kind": "blank", "p": "Find d²y/dx² for the circle x² + y² = 49.", "tag": "", "marks": "", "flat": [{"t": "First derivative: dy/dx = __B1__", "a": {"B1": "-x/y"}, "expr": "calc"}, {"t": "Quotient rule: d²y/dx² = −(y · 1 − x · dy/dx)/y². Substitute your dy/dx: this is −(y + __B1__)/y²", "a": {"B1": "x^2/y"}, "expr": "calc"}, {"t": "Multiply top and bottom by y and use x² + y² = 49: d²y/dx² = __B1__", "a": {"B1": "-49/y^3"}, "expr": "calc", "accept": ["-(x^2+y^2)/y^3"]}], "sol": "2x + 2y y′ = 0, so y′ = −x/y.\ny − x(−x/y) = y + x²/y.\n−(y + x²/y)/y² = −(y² + x²)/y³ = −49/y³."}, {"kind": "mcq", "text": "If f(x) = x⁵ − 3x³ + x, find f″(x).", "opts": ["20x³ − 9x", "20x³ − 18x", "20x⁴ − 18x²", "5x⁴ − 9x² + 1"], "correct": 1, "tag": "", "sol": "f′(x) = 5x⁴ − 9x² + 1, then f″(x) = 20x³ − 18x. (5x⁴ − 9x² + 1 is only the first derivative; 20x³ − 9x forgets to differentiate −9x² fully; 20x⁴ − 18x² does not lower the powers.)"}, {"kind": "blank", "p": "Find the derivatives of f(x) = x⁴ − 2x³ + 7x − 5, one after another.", "tag": "", "marks": "", "flat": [{"t": "f′(x) = __B1__", "a": {"B1": "4x^3-6x^2+7"}, "expr": "calc"}, {"t": "f″(x) = __B1__", "a": {"B1": "12x^2-12x"}, "expr": "calc"}, {"t": "f‴(x) = __B1__", "a": {"B1": "24x-12"}, "expr": "calc"}, {"t": "f⁽⁴⁾(x) = __B1__", "a": {"B1": "24"}, "expr": "calc"}, {"t": "f⁽⁵⁾(x) = __B1__", "a": {"B1": "0"}, "expr": "calc"}], "sol": "4x³ − 6x² + 7 (the constant −5 disappears).\n12x² − 12x.\n24x − 12.\n24.\n0: a polynomial of degree 4 has fifth derivative 0."}, {"kind": "mcq", "text": "Which formula gives the nth derivative of f(x) = e<sup>3x</sup>?", "opts": ["e<sup>3x</sup>", "3ⁿ e<sup>3nx</sup>", "3n e<sup>3x</sup>", "3ⁿ e<sup>3x</sup>"], "correct": 3, "tag": "", "sol": "Each derivative multiplies by 3 (chain rule): f′ = 3e<sup>3x</sup>, f″ = 9e<sup>3x</sup>, f‴ = 27e<sup>3x</sup>, …, so f⁽ⁿ⁾(x) = 3ⁿ e<sup>3x</sup>. (3n would give 9 for n = 3, not 27; the exponent 3x never changes.)"}, {"kind": "blank", "p": "Look for the pattern in the derivatives of y = sin(2x).", "tag": "", "marks": "", "flat": [{"t": "y′ = __B1__", "a": {"B1": "2cos(2x)"}, "expr": "calc"}, {"t": "y″ = __B1__", "a": {"B1": "-4sin(2x)"}, "expr": "calc"}, {"t": "y‴ = __B1__", "a": {"B1": "-8cos(2x)"}, "expr": "calc"}, {"t": "y⁽⁴⁾ = __B1__", "a": {"B1": "16sin(2x)"}, "expr": "calc"}, {"t": "So y⁽⁴⁾ = k · y with k = __B1__", "a": {"B1": "16"}, "expr": "calc"}], "sol": "Chain rule: 2cos(2x).\n−4 sin(2x).\n−8 cos(2x).\n16 sin(2x).\ny⁽⁴⁾ = 16 sin(2x) = 16y: four derivatives bring back sin(2x), multiplied by 2⁴ = 16."}, {"kind": "mcq", "text": "If f(x) = 1/x, what is f⁽⁵⁾(x)?", "opts": ["−120/x⁶", "120/x⁶", "−5/x⁶", "−120/x⁵"], "correct": 0, "tag": "", "sol": "f = x<sup>−1</sup>, f′ = −x<sup>−2</sup>, f″ = 2x<sup>−3</sup>, f‴ = −6x<sup>−4</sup>, f⁽⁴⁾ = 24x<sup>−5</sup>, f⁽⁵⁾ = −120x<sup>−6</sup>. The pattern is (−1)ⁿ n!/xⁿ⁺¹: odd n gives a minus sign and 5! = 120."}, {"kind": "blank", "p": "Find the pattern in the derivatives of f(x) = ln x.", "tag": "", "marks": "", "flat": [{"t": "f′(x) = __B1__", "a": {"B1": "1/x"}, "expr": "calc"}, {"t": "f″(x) = __B1__", "a": {"B1": "-1/x^2"}, "expr": "calc"}, {"t": "f‴(x) = __B1__", "a": {"B1": "2/x^3"}, "expr": "calc"}, {"t": "f⁽⁴⁾(x) = __B1__", "a": {"B1": "-6/x^4"}, "expr": "calc"}, {"t": "Using the pattern (−1)ⁿ⁻¹(n − 1)!/xⁿ: f⁽¹⁰⁾(x) = __B1__", "a": {"B1": "-362880/x^10"}, "expr": "calc"}], "sol": "1/x.\n−1/x².\n2/x³.\n−6/x⁴.\nn = 10: (−1)⁹ · 9!/x¹⁰ = −362880/x¹⁰."}, {"kind": "mcq", "text": "Find dy/dx if xy² − x³ = 4.", "opts": ["(y² − 3x²)/(2xy)", "(3x² − y²)/(2y)", "(3x² − y²)/(2xy)", "3x²/(2xy)"], "correct": 2, "tag": "", "sol": "Product rule on xy²: y² + x · 2y · dy/dx. So y² + 2xy · dy/dx − 3x² = 0 and dy/dx = (3x² − y²)/(2xy). ((3x² − y²)/(2y) drops the x of the product; 3x²/(2xy) forgets the y² term; (y² − 3x²)/(2xy) has the sign reversed.)"}, {"kind": "blank", "p": "Find dy/dx and d²y/dx² for y² = 4x + 1 (take y &gt; 0).", "tag": "", "marks": "", "flat": [{"t": "Differentiate: 2y · dy/dx = __B1__", "a": {"B1": "4"}, "expr": "calc"}, {"t": "dy/dx = __B1__ (in terms of y)", "a": {"B1": "2/y"}, "expr": "calc"}, {"t": "d²y/dx² = −2 · (dy/dx)/y². Substitute dy/dx: d²y/dx² = __B1__ (in terms of y)", "a": {"B1": "-4/y^3"}, "expr": "calc"}], "sol": "The right side 4x + 1 has derivative 4.\ndy/dx = 4/(2y) = 2/y.\nd/dx (2/y) = −2y⁻² · dy/dx = −2(2/y)/y² = −4/y³."}, {"kind": "mcq", "text": "At which points does the curve x² − xy + y² = 3 have a horizontal tangent line?", "opts": ["(0, √3) and (0, −√3)", "(1, 1) and (−1, −1)", "(2, 1) and (−2, −1)", "(1, 2) and (−1, −2)"], "correct": 3, "tag": "", "sol": "Implicitly: 2x − y − x y′ + 2y y′ = 0, so y′ = (y − 2x)/(2y − x). Horizontal means y′ = 0: y = 2x. Substitute: x² − 2x² + 4x² = 3, so 3x² = 3 and x = ±1, giving (1, 2) and (−1, −2). (2, 1) and (−2, −1) are where the tangent is vertical (2y − x = 0); (1, 1) and (−1, −1) are not on the curve (1 − 1 + 1 = 1 ≠ 3); at (0, ±√3) the slope is 1/2."}]}, {"id": "s8", "label": "8 · Inverses & tables", "sub": "Inverse functions, inverse trig, and derivatives from tables and graphs", "slides": [{"kind": "mcq", "text": "Let f(x) = x³ + 2x − 1 and g = f⁻¹. Find g′(2).", "opts": ["14", "1/5", "1/14", "5"], "correct": 1, "tag": "", "sol": "First find f⁻¹(2): f(1) = 1 + 2 − 1 = 2, so f⁻¹(2) = 1. f′(x) = 3x² + 2, so f′(1) = 5. Then g′(2) = 1/f′(1) = 1/5. (1/14 = 1/f′(2) uses the wrong point; 5 and 14 forget the reciprocal.)"}, {"kind": "blank", "p": "Let f(x) = 2x + eˣ, which is one-to-one. Find (f⁻¹)′(1).", "tag": "", "marks": "", "flat": [{"t": "Solve f(x) = 1 by inspection: f⁻¹(1) = __B1__", "a": {"B1": "0"}, "expr": "calc"}, {"t": "f′(x) = __B1__", "a": {"B1": "2+e^x"}, "expr": "calc"}, {"t": "f′(f⁻¹(1)) = __B1__", "a": {"B1": "3"}, "expr": "calc"}, {"t": "(f⁻¹)′(1) = __B1__", "a": {"B1": "1/3"}, "expr": "calc"}], "sol": "f(0) = 0 + e⁰ = 1, so f⁻¹(1) = 0.\nf′(x) = 2 + eˣ.\nf′(0) = 2 + 1 = 3.\n(f⁻¹)′(1) = 1/f′(0) = 1/3."}, {"kind": "mcq", "text": "Find d/dx [sin⁻¹(x/3)] for −3 &lt; x &lt; 3.", "opts": ["1 / (9 + x²)", "1 / √(9 − x²)", "1 / (3√(9 − x²))", "1 / √(1 − x²/9)"], "correct": 1, "tag": "", "sol": "sin⁻¹u → u′/√(1 − u²) with u = x/3, u′ = 1/3: (1/3)/√(1 − x²/9) = (1/3)/(√(9 − x²)/3) = 1/√(9 − x²). 1/√(1 − x²/9) forgets the 1/3 (it equals 3/√(9 − x²)); 1/(3√(9 − x²)) divides by 3 twice; 1/(9 + x²) mixes up the sin⁻¹ and tan⁻¹ formulas."}, {"kind": "blank", "p": "Differentiate y = tan⁻¹(e<sup>2x</sup>).", "tag": "", "marks": "", "flat": [{"t": "Inner function: u = __B1__", "a": {"B1": "e^(2x)"}, "expr": "calc"}, {"t": "du/dx = __B1__", "a": {"B1": "2e^(2x)"}, "expr": "calc"}, {"t": "dy/dx = __B1__", "a": {"B1": "2e^(2x)/(1+e^(4x))"}, "expr": "calc"}], "sol": "Inside the inverse tangent is u = e<sup>2x</sup>.\ndu/dx = 2e<sup>2x</sup>.\ntan⁻¹u → u′/(1 + u²): dy/dx = 2e<sup>2x</sup>/(1 + (e<sup>2x</sup>)²) = 2e<sup>2x</sup>/(1 + e<sup>4x</sup>)."}, {"kind": "mcq", "text": "Find d/dx [tan⁻¹(1/x)] for x &gt; 0.", "opts": ["1/(1 + 1/x²)", "−1/(x²(1 + x²))", "1/(1 + x²)", "−1/(1 + x²)"], "correct": 3, "tag": "", "sol": "u = 1/x, u′ = −1/x². So d/dx = (−1/x²)/(1 + 1/x²). Multiply top and bottom by x²: −1/(x² + 1). 1/(1 + 1/x²) forgets u′; −1/(x²(1 + x²)) multiplies by 1/x² instead of cancelling it; 1/(1 + x²) loses the sign."}, {"kind": "blank", "p": "The table gives values of the differentiable functions f and g and their derivatives. Find the derivatives.", "tag": "", "marks": "", "flat": [{"t": "h(x) = f(x) + 3g(x): h′(2) = __B1__", "a": {"B1": "1"}, "expr": "calc"}, {"t": "p(x) = f(x) g(x): p′(2) = __B1__", "a": {"B1": "11"}, "expr": "calc"}, {"t": "r(x) = 2f(x) − [g(x)]²: r′(3) = __B1__", "a": {"B1": "-2"}, "expr": "calc"}], "sol": "h′(2) = f′(2) + 3g′(2) = 4 + 3(−1) = 1.\np′(2) = f′(2) g(2) + f(2) g′(2) = 4 · 3 + 1 · (−1) = 11.\nr′(x) = 2f′(x) − 2g(x) g′(x), so r′(3) = 2 · 6 − 2 · 1 · 7 = −2.", "fig": "<div class=\"tscroll\"><table class=\"ttab\"><tr><th>x</th><th>f(x)</th><th>f′(x)</th><th>g(x)</th><th>g′(x)</th></tr><tr><td>1</td><td>3</td><td>−2</td><td>2</td><td>5</td></tr><tr><td>2</td><td>1</td><td>4</td><td>3</td><td>−1</td></tr><tr><td>3</td><td>2</td><td>6</td><td>1</td><td>7</td></tr></table></div>"}, {"kind": "mcq", "text": "The table gives values of the differentiable functions f and g and their derivatives. Let h(x) = f(g(x)). Find h′(2).", "opts": ["6", "−6", "18", "−4"], "correct": 1, "tag": "", "sol": "h′(2) = f′(g(2)) · g′(2) = f′(3) · (−1) = 6 · (−1) = −6. (−4 = f′(2) · g′(2) uses f′ at the wrong point; 6 forgets g′(2); 18 = f′(3) · g(2) multiplies by g instead of g′.)", "fig": "<div class=\"tscroll\"><table class=\"ttab\"><tr><th>x</th><th>f(x)</th><th>f′(x)</th><th>g(x)</th><th>g′(x)</th></tr><tr><td>1</td><td>3</td><td>−2</td><td>2</td><td>5</td></tr><tr><td>2</td><td>1</td><td>4</td><td>3</td><td>−1</td></tr><tr><td>3</td><td>2</td><td>6</td><td>1</td><td>7</td></tr></table></div>"}, {"kind": "blank", "p": "The table gives values of the differentiable functions f and g and their derivatives. Let q(x) = f(x)/g(x). Find q′(1).", "tag": "", "marks": "", "flat": [{"t": "f′(1) g(1) = __B1__", "a": {"B1": "-4"}, "expr": "calc"}, {"t": "f(1) g′(1) = __B1__", "a": {"B1": "15"}, "expr": "calc"}, {"t": "[g(1)]² = __B1__", "a": {"B1": "4"}, "expr": "calc"}, {"t": "q′(1) = __B1__", "a": {"B1": "-19/4"}, "expr": "calc"}], "sol": "f′(1) g(1) = (−2)(2) = −4.\nf(1) g′(1) = 3 · 5 = 15.\ng(1)² = 4.\nq′(1) = [f′(1) g(1) − f(1) g′(1)]/g(1)² = (−4 − 15)/4 = −19/4.", "fig": "<div class=\"tscroll\"><table class=\"ttab\"><tr><th>x</th><th>f(x)</th><th>f′(x)</th><th>g(x)</th><th>g′(x)</th></tr><tr><td>1</td><td>3</td><td>−2</td><td>2</td><td>5</td></tr><tr><td>2</td><td>1</td><td>4</td><td>3</td><td>−1</td></tr><tr><td>3</td><td>2</td><td>6</td><td>1</td><td>7</td></tr></table></div>"}, {"kind": "mcq", "text": "The table gives values of the differentiable functions f and g and their derivatives. Let k(x) = g(f(x)). Find k′(1).", "opts": ["−10", "−14", "7", "14"], "correct": 1, "tag": "", "sol": "k′(1) = g′(f(1)) · f′(1) = g′(3) · (−2) = 7 · (−2) = −14. (−10 = g′(1) · f′(1) evaluates g′ at 1 instead of at f(1) = 3; 7 forgets f′(1).)", "fig": "<div class=\"tscroll\"><table class=\"ttab\"><tr><th>x</th><th>f(x)</th><th>f′(x)</th><th>g(x)</th><th>g′(x)</th></tr><tr><td>1</td><td>3</td><td>−2</td><td>2</td><td>5</td></tr><tr><td>2</td><td>1</td><td>4</td><td>3</td><td>−1</td></tr><tr><td>3</td><td>2</td><td>6</td><td>1</td><td>7</td></tr></table></div>"}, {"kind": "blank", "p": "The table gives values of the differentiable functions f and g and their derivatives. Assume f and g are invertible near each x in the table (their derivatives there are not 0). Use (f⁻¹)′(a) = 1/f′(f⁻¹(a)).", "tag": "", "marks": "", "flat": [{"t": "f⁻¹(1) = __B1__", "a": {"B1": "2"}, "expr": "calc"}, {"t": "f′(f⁻¹(1)) = __B1__", "a": {"B1": "4"}, "expr": "calc"}, {"t": "(f⁻¹)′(1) = __B1__", "a": {"B1": "1/4"}, "expr": "calc"}, {"t": "(g⁻¹)′(3) = __B1__", "a": {"B1": "-1"}, "expr": "calc"}], "sol": "f(2) = 1, so f⁻¹(1) = 2.\nf′(2) = 4.\n(f⁻¹)′(1) = 1/4.\ng(2) = 3, so (g⁻¹)′(3) = 1/g′(2) = 1/(−1) = −1.", "fig": "<div class=\"tscroll\"><table class=\"ttab\"><tr><th>x</th><th>f(x)</th><th>f′(x)</th><th>g(x)</th><th>g′(x)</th></tr><tr><td>1</td><td>3</td><td>−2</td><td>2</td><td>5</td></tr><tr><td>2</td><td>1</td><td>4</td><td>3</td><td>−1</td></tr><tr><td>3</td><td>2</td><td>6</td><td>1</td><td>7</td></tr></table></div>"}, {"kind": "mcq", "text": "The graph of f is made of straight line segments joining (0, 1), (2, 5), (5, 2) and (7, 2). Let h(x) = x · f(x). Find h′(1).", "opts": ["5", "3", "2", "6"], "correct": 0, "tag": "", "sol": "Product rule: h′(1) = 1 · f(1) + 1 · f′(1). From the graph f(1) = 3 (halfway from 1 to 5) and f′(1) = slope of the first segment = (5 − 1)/2 = 2. So h′(1) = 3 + 2 = 5. (2 is only x · f′(x); 3 is only f(1); 6 = f(1) · f′(1).)", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 284 248\" role=\"img\" aria-label=\"graph of f made of line segments\" style=\"max-width:340px;width:100%\"><line x1=\"18\" y1=\"18\" x2=\"18\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"52\" y1=\"18\" x2=\"52\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"86\" y1=\"18\" x2=\"86\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"120\" y1=\"18\" x2=\"120\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"154\" y1=\"18\" x2=\"154\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"188\" y1=\"18\" x2=\"188\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"222\" y1=\"18\" x2=\"222\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"256\" y1=\"18\" x2=\"256\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"222\" x2=\"256\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"188\" x2=\"256\" y2=\"188\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"154\" x2=\"256\" y2=\"154\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"120\" x2=\"256\" y2=\"120\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"86\" x2=\"256\" y2=\"86\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"52\" x2=\"256\" y2=\"52\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"18\" x2=\"256\" y2=\"18\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"222\" x2=\"264\" y2=\"222\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"18\" y1=\"222\" x2=\"18\" y2=\"10\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"52\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">1</text><text x=\"86\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">2</text><text x=\"120\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">3</text><text x=\"154\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">4</text><text x=\"188\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">5</text><text x=\"222\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">6</text><text x=\"256\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">7</text><text x=\"9\" y=\"188\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">1</text><text x=\"9\" y=\"154\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">2</text><text x=\"9\" y=\"120\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">3</text><text x=\"9\" y=\"86\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">4</text><text x=\"9\" y=\"52\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">5</text><text x=\"9\" y=\"18\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">6</text><text x=\"9\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">0</text><text x=\"260\" y=\"212\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;font-style:italic;font-weight:600\">x</text><text x=\"30\" y=\"14\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;font-style:italic;font-weight:600\">y</text><path d=\"M18.0,188.0 L86.0,52.0 L188.0,154.0 L256.0,154.0\" style=\"fill:none;stroke:var(--accent-text);stroke-width:2.6;stroke-linejoin:round\"/><circle cx=\"18.0\" cy=\"188.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"86.0\" cy=\"52.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"188.0\" cy=\"154.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"256.0\" cy=\"154.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><text x=\"218.60000000000002\" y=\"140\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;fill:var(--accent-text);font-style:italic;font-weight:600;font-size:15px\">y = f(x)</text></svg>"}, {"kind": "blank", "p": "The graph of f is made of straight line segments joining (0, 1), (2, 5), (5, 2) and (7, 2). Use the graph to find these derivatives.", "tag": "", "marks": "", "flat": [{"t": "f(3) = __B1__", "a": {"B1": "4"}, "expr": "calc"}, {"t": "f′(3) = __B1__", "a": {"B1": "-1"}, "expr": "calc"}, {"t": "m(x) = f(x)/x: m′(3) = __B1__", "a": {"B1": "-7/9"}, "expr": "calc"}, {"t": "k(x) = f(x²): k′(2) = __B1__", "a": {"B1": "-4"}, "expr": "calc"}], "sol": "On the segment from (2, 5) to (5, 2) the graph drops 1 for each step right: f(3) = 4.\nThat segment has slope (2 − 5)/(5 − 2) = −1.\nQuotient rule: m′(3) = [3 f′(3) − f(3) · 1]/3² = (−3 − 4)/9 = −7/9.\nChain rule: k′(x) = f′(x²) · 2x, so k′(2) = f′(4) · 4 = (−1)(4) = −4.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 284 248\" role=\"img\" aria-label=\"graph of f made of line segments\" style=\"max-width:340px;width:100%\"><line x1=\"18\" y1=\"18\" x2=\"18\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"52\" y1=\"18\" x2=\"52\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"86\" y1=\"18\" x2=\"86\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"120\" y1=\"18\" x2=\"120\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"154\" y1=\"18\" x2=\"154\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"188\" y1=\"18\" x2=\"188\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"222\" y1=\"18\" x2=\"222\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"256\" y1=\"18\" x2=\"256\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"222\" x2=\"256\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"188\" x2=\"256\" y2=\"188\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"154\" x2=\"256\" y2=\"154\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"120\" x2=\"256\" y2=\"120\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"86\" x2=\"256\" y2=\"86\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"52\" x2=\"256\" y2=\"52\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"18\" x2=\"256\" y2=\"18\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"222\" x2=\"264\" y2=\"222\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"18\" y1=\"222\" x2=\"18\" y2=\"10\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"52\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">1</text><text x=\"86\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">2</text><text x=\"120\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">3</text><text x=\"154\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">4</text><text x=\"188\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">5</text><text x=\"222\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">6</text><text x=\"256\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">7</text><text x=\"9\" y=\"188\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">1</text><text x=\"9\" y=\"154\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">2</text><text x=\"9\" y=\"120\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">3</text><text x=\"9\" y=\"86\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">4</text><text x=\"9\" y=\"52\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">5</text><text x=\"9\" y=\"18\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">6</text><text x=\"9\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">0</text><text x=\"260\" y=\"212\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;font-style:italic;font-weight:600\">x</text><text x=\"30\" y=\"14\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;font-style:italic;font-weight:600\">y</text><path d=\"M18.0,188.0 L86.0,52.0 L188.0,154.0 L256.0,154.0\" style=\"fill:none;stroke:var(--accent-text);stroke-width:2.6;stroke-linejoin:round\"/><circle cx=\"18.0\" cy=\"188.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"86.0\" cy=\"52.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"188.0\" cy=\"154.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"256.0\" cy=\"154.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><text x=\"218.60000000000002\" y=\"140\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;fill:var(--accent-text);font-style:italic;font-weight:600;font-size:15px\">y = f(x)</text></svg>"}, {"kind": "mcq", "text": "The graph of f is made of straight line segments joining (0, 1), (2, 5), (5, 2) and (7, 2). For 0 &lt; x &lt; 7, where is f not differentiable?", "opts": ["x = 2 and x = 5", "x = 2 only", "x = 5 only", "nowhere, because f is continuous"], "correct": 0, "tag": "", "sol": "At x = 2 the slope jumps from 2 to −1 and at x = 5 from −1 to 0: both are corners, so f′ does not exist there. A continuous function can still fail to be differentiable at a corner.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 284 248\" role=\"img\" aria-label=\"graph of f made of line segments\" style=\"max-width:340px;width:100%\"><line x1=\"18\" y1=\"18\" x2=\"18\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"52\" y1=\"18\" x2=\"52\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"86\" y1=\"18\" x2=\"86\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"120\" y1=\"18\" x2=\"120\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"154\" y1=\"18\" x2=\"154\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"188\" y1=\"18\" x2=\"188\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"222\" y1=\"18\" x2=\"222\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"256\" y1=\"18\" x2=\"256\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"222\" x2=\"256\" y2=\"222\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"188\" x2=\"256\" y2=\"188\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"154\" x2=\"256\" y2=\"154\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"120\" x2=\"256\" y2=\"120\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"86\" x2=\"256\" y2=\"86\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"52\" x2=\"256\" y2=\"52\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"18\" x2=\"256\" y2=\"18\" style=\"stroke:var(--rule);stroke-width:1\"/><line x1=\"18\" y1=\"222\" x2=\"264\" y2=\"222\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"18\" y1=\"222\" x2=\"18\" y2=\"10\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"52\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">1</text><text x=\"86\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">2</text><text x=\"120\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">3</text><text x=\"154\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">4</text><text x=\"188\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">5</text><text x=\"222\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">6</text><text x=\"256\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">7</text><text x=\"9\" y=\"188\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">1</text><text x=\"9\" y=\"154\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">2</text><text x=\"9\" y=\"120\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">3</text><text x=\"9\" y=\"86\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">4</text><text x=\"9\" y=\"52\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">5</text><text x=\"9\" y=\"18\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">6</text><text x=\"9\" y=\"234\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;\">0</text><text x=\"260\" y=\"212\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;font-style:italic;font-weight:600\">x</text><text x=\"30\" y=\"14\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;font-style:italic;font-weight:600\">y</text><path d=\"M18.0,188.0 L86.0,52.0 L188.0,154.0 L256.0,154.0\" style=\"fill:none;stroke:var(--accent-text);stroke-width:2.6;stroke-linejoin:round\"/><circle cx=\"18.0\" cy=\"188.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"86.0\" cy=\"52.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"188.0\" cy=\"154.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><circle cx=\"256.0\" cy=\"154.0\" r=\"3.6\" style=\"fill:var(--accent-text)\"/><text x=\"218.60000000000002\" y=\"140\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:13px sans-serif;fill:var(--accent-text);font-style:italic;font-weight:600;font-size:15px\">y = f(x)</text></svg>"}, {"kind": "blank", "p": "Let f(x) = tan⁻¹x + tan⁻¹(1/x) for x &gt; 0.", "tag": "", "marks": "", "flat": [{"t": "d/dx tan⁻¹x = __B1__", "a": {"B1": "1/(1+x^2)"}, "expr": "calc"}, {"t": "d/dx tan⁻¹(1/x) = __B1__", "a": {"B1": "-1/(1+x^2)"}, "expr": "calc"}, {"t": "f′(x) = __B1__", "a": {"B1": "0"}, "expr": "calc"}], "sol": "1/(1 + x²).\n(−1/x²)/(1 + 1/x²) = −1/(x² + 1).\nThe two terms cancel: f′(x) = 0, so f is constant for x &gt; 0. (At x = 1 it is π/4 + π/4 = π/2.)"}, {"kind": "mcq", "text": "f is differentiable and increasing, f(3) = 7, and the tangent line to the graph of f at x = 3 is y = 2x + 1. If g = f⁻¹, find g′(7).", "opts": ["1/3", "2", "1/7", "1/2"], "correct": 3, "tag": "", "sol": "The tangent line has slope 2, so f′(3) = 2. Since f(3) = 7, g(7) = 3 and g′(7) = 1/f′(3) = 1/2. (2 forgets the reciprocal; 1/7 and 1/3 use a function value instead of a slope.)"}]}, {"id": "s9", "label": "9 · Using derivatives", "sub": "Paul problems 28–32 · tangent lines, sign charts, motion", "slides": [{"kind": "blank", "p": "<b>Paul · Problem 28</b> · Find the tangent line to f(x) = 4√(2x) − 6e<sup>2 − x</sup> at x = 2.", "tag": "", "marks": "", "flat": [{"t": "f(2) = __B1__", "a": {"B1": "2"}, "expr": "calc"}, {"t": "f′(x) = __B1__", "a": {"B1": "4/sqrt(2x)+6e^(2-x)"}, "expr": "calc"}, {"t": "f′(2) = __B1__", "a": {"B1": "8"}, "expr": "calc"}, {"t": "Tangent line: y = __B1__", "a": {"B1": "8x-14"}, "expr": "calc"}], "sol": "f(2) = 4√4 − 6e⁰ = 8 − 6 = 2.\n4 · (1/(2√(2x))) · 2 = 4/√(2x), and −6e<sup>2 − x</sup> · (−1) = +6e<sup>2 − x</sup>: f′(x) = 4/√(2x) + 6e<sup>2 − x</sup>.\nf′(2) = 4/2 + 6 = 8.\ny = 2 + 8(x − 2) = 8x − 14."}, {"kind": "mcq", "text": "Find the equation of the tangent line to y = x e<sup>x − 1</sup> at x = 1.", "opts": ["y = 2x + 1", "y = x", "y = 2x − 1", "y = 2x"], "correct": 2, "tag": "", "sol": "At x = 1: y = 1 · e⁰ = 1. Product rule: y′ = e<sup>x − 1</sup> + x e<sup>x − 1</sup> = e<sup>x − 1</sup>(1 + x), so the slope is 2. Tangent: y = 1 + 2(x − 1) = 2x − 1. (y = x uses slope 1 by forgetting the product rule; the others do not pass through (1, 1).)", "tools": ["desmos"], "desmos": ["y=xe^{x-1}"]}, {"kind": "blank", "p": "<b>Paul · Problem 29</b> · For V(z) = z⁴(2z − 8)³, find the critical points.", "tag": "", "marks": "", "flat": [{"t": "d/dz (2z − 8)³ = __B1__", "a": {"B1": "6(2z-8)^2"}, "expr": "calc"}, {"t": "Product rule: V′(z) = 4z³(2z − 8)³ + __B1__", "a": {"B1": "6z^4(2z-8)^2"}, "expr": "calc"}, {"t": "Factor out 2z³(2z − 8)²: V′(z) = 2z³(2z − 8)²(__B1__)", "a": {"B1": "7z-16"}, "expr": "calc"}, {"t": "V′(z) = 0 at z = 0, z = 4 and z = __B1__ (as a fraction)", "a": {"B1": "16/7"}, "expr": "calc"}, {"t": "Test values: V′(1) = __B1__", "a": {"B1": "-648"}, "expr": "calc"}, {"t": "V′(3) = __B1__", "a": {"B1": "1080"}, "expr": "calc"}], "sol": "Chain rule: 3(2z − 8)² · 2 = 6(2z − 8)².\nz⁴ · 6(2z − 8)² = 6z⁴(2z − 8)².\n2z³(2z − 8)²[2(2z − 8) + 3z] = 2z³(2z − 8)²(7z − 16).\nSet each factor to 0: z = 0, z = 4, z = 16/7.\nV′(1) = 2 · 1 · 36 · (−9) = −648.\nV′(3) = 2 · 27 · 4 · 5 = 1080."}, {"kind": "mcq", "text": "<b>Paul · Problem 29</b> · V(z) = z⁴(2z − 8)³ has V′(z) = 2z³(2z − 8)²(7z − 16). Where is V increasing and where is it decreasing?", "opts": ["increasing on (−∞, 0) and (16/7, 4); decreasing on (0, 16/7) and (4, ∞)", "increasing on (−∞, 0) and (4, ∞); decreasing on (0, 16/7) and (16/7, 4)", "increasing on (−∞, 0), (16/7, 4) and (4, ∞); decreasing on (0, 16/7)", "increasing on (0, 16/7); decreasing on (−∞, 0), (16/7, 4) and (4, ∞)"], "correct": 2, "tag": "", "sol": "Sign chart with test values −1, 1, 3, 5: V′ is +, −, +, +. The squared factor (2z − 8)² is never negative, so V′ does not change sign at z = 4. V is increasing on (−∞, 0), (16/7, 4) and (4, ∞), and decreasing on (0, 16/7). (Graph it: the curve flattens at z = 4 but keeps rising.)", "tools": ["desmos"], "desmos": ["y=x^4(2x-8)^3"]}, {"kind": "blank", "p": "<b>Paul · Problem 30</b> · A particle has position s(t) = sin(3t) − 2t + 4 on 0 ≤ t ≤ 3 (radians). Find when its velocity is zero.", "tag": "", "marks": "", "flat": [{"t": "s′(t) = __B1__", "a": {"B1": "3cos(3t)-2"}, "expr": "calc"}, {"t": "s′(t) = 0 when cos(3t) = __B1__", "a": {"B1": "2/3"}, "expr": "calc"}, {"t": "Times in [0, 3] when s′(t) = 0, to 4 decimal places, in increasing order: __B1__", "a": {"B1": "0.2804, 1.8140, 2.3748"}, "expr": "dlist", "accept": ["0.280, 1.814, 2.375", "0.28, 1.81, 2.37", "0.28, 1.814, 2.375"]}, {"t": "s′(0) = __B1__", "a": {"B1": "1"}, "expr": "calc"}], "sol": "s′(t) = 3cos(3t) − 2.\n3cos(3t) = 2 gives cos(3t) = 2/3.\n3t = cos⁻¹(2/3) ≈ 0.8411, 2π − 0.8411 ≈ 5.4421 or 2π + 0.8411 ≈ 7.1243 (the next one, 4π − 0.8411, is more than 9). Dividing by 3: t ≈ 0.2804, 1.8140, 2.3748.\ns′(0) = 3 − 2 = 1 &gt; 0, so the particle starts by moving right."}, {"kind": "mcq", "text": "<b>Paul · Problem 30</b> · s(t) = sin(3t) − 2t + 4 with s′(t) = 3cos(3t) − 2, and s′(t) = 0 at t ≈ 0.2804, 1.8140 and 2.3748. When is the particle moving to the right on [0, 3]?", "opts": ["on (0.2804, 2.3748) only", "on [0, 0.2804) and (1.8140, 2.3748)", "on [0, 1.8140) only", "on (0.2804, 1.8140) and (2.3748, 3]"], "correct": 1, "tag": "", "sol": "Moving right means s′(t) &gt; 0. Test values: s′(0.1) ≈ 0.87 &gt; 0, s′(1) ≈ −4.97 &lt; 0, s′(2) ≈ 0.88 &gt; 0, s′(2.8) ≈ −3.56 &lt; 0. So it moves right on [0, 0.2804) and (1.8140, 2.3748), and left on (0.2804, 1.8140) and (2.3748, 3]."}, {"kind": "blank", "p": "<b>Paul · Problem 31</b> · For A(t) = t² e<sup>5 − t</sup>, find A′(t) and the critical points.", "tag": "", "marks": "", "flat": [{"t": "A′(t) = __B1__ (factor it)", "a": {"B1": "t(2-t)e^(5-t)"}, "expr": "calc"}, {"t": "Critical points, in increasing order: __B1__", "a": {"B1": "0, 2"}, "expr": "dlist"}, {"t": "Test values: A′(1) = __B1__ (exact)", "a": {"B1": "e^4"}, "expr": "calc"}, {"t": "A′(3) = __B1__ (exact)", "a": {"B1": "-3e^2"}, "expr": "calc"}], "sol": "A′(t) = 2t e<sup>5 − t</sup> − t² e<sup>5 − t</sup> = t(2 − t)e<sup>5 − t</sup>.\ne<sup>5 − t</sup> is never 0, so t = 0 or t = 2.\nA′(1) = 1 · 1 · e⁴ = e⁴ &gt; 0.\nA′(3) = 3 · (−1) · e² = −3e² &lt; 0."}, {"kind": "mcq", "text": "<b>Paul · Problem 31</b> · A(t) = t² e<sup>5 − t</sup> has A′(t) = t(2 − t)e<sup>5 − t</sup>. Where is A increasing and where is it decreasing?", "opts": ["increasing on (0, ∞); decreasing on (−∞, 0)", "increasing on (0, 2); decreasing on (−∞, 0) and (2, ∞)", "increasing on (−∞, 0) and (2, ∞); decreasing on (0, 2)", "increasing on (−∞, 2); decreasing on (2, ∞)"], "correct": 1, "tag": "", "sol": "Sign chart with test values −1, 1, 3: A′ is −, +, −. So A is increasing on (0, 2) and decreasing on (−∞, 0) and (2, ∞).", "tools": ["desmos"], "desmos": ["y=x^2e^{5-x}"]}, {"kind": "blank", "p": "<b>Paul · Problem 32</b> · For f(x) = ln(x⁴ + 20x³ + 100) on [−1, 20], find f′ and the critical points.", "tag": "", "marks": "", "flat": [{"t": "f′(x) = __B1__", "a": {"B1": "(4x^3+60x^2)/(x^4+20x^3+100)"}, "expr": "calc"}, {"t": "Factor the numerator of f′. It is 0 at x = 0 and at x = __B1__", "a": {"B1": "-15"}, "expr": "calc"}, {"t": "The only critical point in [−1, 20] is x = __B1__", "a": {"B1": "0"}, "expr": "calc"}, {"t": "The denominator at x = −1 is __B1__", "a": {"B1": "81"}, "expr": "calc"}], "sol": "ln u → u′/u: f′(x) = (4x³ + 60x²)/(x⁴ + 20x³ + 100).\n4x³ + 60x² = 4x²(x + 15), which is 0 at x = 0 and x = −15.\nThe numerator is 0 at x = 0 and x = −15, and −15 is outside [−1, 20]. The denominator is positive on [−1, 20], so f′ is never undefined there.\n1 − 20 + 100 = 81."}, {"kind": "mcq", "text": "<b>Paul · Problem 32</b> · f(x) = ln(x⁴ + 20x³ + 100) has f′(x) = 4x²(x + 15)/(x⁴ + 20x³ + 100). On [−1, 20], where is f increasing and where is it decreasing?", "opts": ["decreasing on (−1, 0); increasing on (0, 20)", "increasing on (−1, 0) and (0, 20); never decreasing", "increasing on (−1, 0); decreasing on (0, 20)", "decreasing on (−1, 0) and (0, 20); never increasing"], "correct": 1, "tag": "", "sol": "On [−1, 20]: 4x² ≥ 0, x + 15 &gt; 0 and the denominator is positive, so f′(x) ≥ 0 with f′ = 0 only at x = 0. f is increasing on (−1, 0) and (0, 20) and never decreasing; at x = 0 the graph just levels off for a moment."}, {"kind": "blank", "p": "For f(x) = x³ − 6x² + 9x + 1, make a sign chart for f′.", "tag": "", "marks": "", "flat": [{"t": "f′(x) = __B1__", "a": {"B1": "3x^2-12x+9"}, "expr": "calc"}, {"t": "Critical points, in increasing order: __B1__", "a": {"B1": "1, 3"}, "expr": "dlist"}, {"t": "Test values: f′(0) = __B1__", "a": {"B1": "9"}, "expr": "calc"}, {"t": "f′(2) = __B1__", "a": {"B1": "-3"}, "expr": "calc"}, {"t": "f′(4) = __B1__", "a": {"B1": "9"}, "expr": "calc"}], "sol": "f′(x) = 3x² − 12x + 9 = 3(x − 1)(x − 3).\nx = 1 and x = 3.\nf′(0) = 9 &gt; 0.\nf′(2) = 12 − 24 + 9 = −3 &lt; 0.\nf′(4) = 48 − 48 + 9 = 9 &gt; 0."}, {"kind": "mcq", "text": "f(x) = x³ − 6x² + 9x + 1 has f′(x) = 3(x − 1)(x − 3). On which interval(s) is f decreasing?", "opts": ["(3, ∞) only", "(1, 3) only", "(−∞, 1) and (3, ∞)", "(−∞, 3)"], "correct": 1, "tag": "", "sol": "f′(2) = −3 &lt; 0 and f′ is positive outside [1, 3], so f is decreasing only on (1, 3). (−∞, 1) and (3, ∞) is where f is increasing.", "tools": ["desmos"], "desmos": ["y=x^3-6x^2+9x+1"]}, {"kind": "blank", "p": "A particle moves along a line with position s(t) = t³ − 9t² + 24t metres, t ≥ 0 seconds.", "tag": "", "marks": "", "flat": [{"t": "Velocity v(t) = __B1__", "a": {"B1": "3t^2-18t+24"}, "expr": "calc"}, {"t": "Acceleration a(t) = __B1__", "a": {"B1": "6t-18"}, "expr": "calc"}, {"t": "The particle is at rest at t = __B1__ (in increasing order)", "a": {"B1": "2, 4"}, "expr": "dlist"}, {"t": "v(1) = __B1__ m/s", "a": {"B1": "9"}, "expr": "calc"}, {"t": "a(1) = __B1__ m/s²", "a": {"B1": "-12"}, "expr": "calc"}], "sol": "v = s′ = 3t² − 18t + 24.\na = v′ = 6t − 18.\nv = 3(t − 2)(t − 4) = 0 at t = 2 and t = 4.\nv(1) = 3 − 18 + 24 = 9.\na(1) = 6 − 18 = −12."}, {"kind": "mcq", "text": "For s(t) = t³ − 9t² + 24t (t ≥ 0) we have v(t) = 3(t − 2)(t − 4) and a(t) = 6t − 18. When is the particle speeding up?", "opts": ["3 &lt; t &lt; 4 only", "2 &lt; t &lt; 3 and t &gt; 4", "t &gt; 3 only", "0 ≤ t &lt; 2 and t &gt; 4"], "correct": 1, "tag": "", "sol": "Speeding up means v and a have the same sign. v &gt; 0 for t &lt; 2 and t &gt; 4, v &lt; 0 for 2 &lt; t &lt; 4; a &lt; 0 for t &lt; 3 and a &gt; 0 for t &gt; 3. Both negative on (2, 3), both positive for t &gt; 4. (t &gt; 3 only checks a; 0 ≤ t &lt; 2 and t &gt; 4 is where the particle moves right.)"}, {"kind": "blank", "p": "A particle has position s(t) = t e<sup>−t/2</sup> for t ≥ 0.", "tag": "", "marks": "", "flat": [{"t": "v(t) = __B1__", "a": {"B1": "e^(-t/2)(1-t/2)"}, "expr": "calc", "accept": ["e^(-1/2t)(1-1/2t)"]}, {"t": "a(t) = __B1__", "a": {"B1": "e^(-t/2)(t/4-1)"}, "expr": "calc", "accept": ["e^(-1/2t)(1/4t-1)"]}, {"t": "The particle changes direction at t = __B1__", "a": {"B1": "2"}, "expr": "calc"}, {"t": "a(2) = __B1__ (exact)", "a": {"B1": "-1/(2e)"}, "expr": "calc"}], "sol": "Product rule: v = e<sup>−t/2</sup> + t · (−½)e<sup>−t/2</sup> = e<sup>−t/2</sup>(1 − t/2).\na = (−½)e<sup>−t/2</sup>(1 − t/2) + e<sup>−t/2</sup>(−½) = e<sup>−t/2</sup>(t/4 − 1).\ne<sup>−t/2</sup> &gt; 0, so v = 0 only at t = 2, and v changes from + to − there.\na(2) = e<sup>−1</sup>(½ − 1) = −1/(2e)."}, {"kind": "mcq", "text": "At which points does y = x³ − 3x have a horizontal tangent line?", "opts": ["(0, 0) only", "(√3, 0) and (−√3, 0)", "(1, 2) and (−1, −2)", "(1, −2) and (−1, 2)"], "correct": 3, "tag": "", "sol": "y′ = 3x² − 3 = 0 gives x = ±1. y(1) = 1 − 3 = −2 and y(−1) = −1 + 3 = 2. (The points (±√3, 0) are where the graph crosses the x-axis, not where it is flat.)", "tools": ["desmos"], "desmos": ["y=x^3-3x"]}]}, {"id": "s10", "label": "Assessment A", "sub": "Knowing and understanding", "slides": [{"kind": "blank", "p": "Use the limit definition f′(x) = lim<sub>h→0</sub> [f(x + h) − f(x)]/h to differentiate f(x) = 2x² − 7x.", "tag": "", "marks": "", "flat": [{"t": "f(x + h) − f(x) = __B1__ (expand and simplify)", "a": {"B1": "4xh+2h^2-7h"}, "expr": "calc"}, {"t": "Divide by h: [f(x + h) − f(x)]/h = __B1__", "a": {"B1": "4x+2h-7"}, "expr": "calc"}, {"t": "Let h → 0: f′(x) = __B1__", "a": {"B1": "4x-7"}, "expr": "calc"}], "sol": "2(x + h)² − 7(x + h) − 2x² + 7x = 2x² + 4xh + 2h² − 7x − 7h − 2x² + 7x = 4xh + 2h² − 7h.\nEach term has a factor h: 4x + 2h − 7.\nAs h → 0 the 2h disappears: f′(x) = 4x − 7."}, {"kind": "mcq", "text": "Differentiate y = 4x⁵ − 3/x² + 6√x.", "opts": ["20x⁴ + 3/(2x) + 3/√x", "20x⁴ + 6/x³ + 3/√x", "20x⁴ + 6/x³ + 6/√x", "20x⁴ − 6/x³ + 3/√x"], "correct": 1, "tag": "", "sol": "Rewrite: y = 4x⁵ − 3x<sup>−2</sup> + 6x<sup>1/2</sup>. Then y′ = 20x⁴ + 6x<sup>−3</sup> + 3x<sup>−1/2</sup> = 20x⁴ + 6/x³ + 3/√x. (−3 · (−2) = +6, so −6/x³ is a sign slip; 6/√x forgets the ½; 3/(2x) differentiates the denominator only.)"}, {"kind": "blank", "p": "Let f(x) = (x² + 1)eˣ.", "tag": "", "marks": "", "flat": [{"t": "Product rule: f′(x) = __B1__", "a": {"B1": "e^x(x+1)^2"}, "expr": "calc"}, {"t": "f′(0) = __B1__", "a": {"B1": "1"}, "expr": "calc"}, {"t": "f′(1) = __B1__ (exact)", "a": {"B1": "4e"}, "expr": "calc"}], "sol": "f′(x) = 2x eˣ + (x² + 1)eˣ = eˣ(x² + 2x + 1) = eˣ(x + 1)².\nf′(0) = e⁰ · 1 = 1.\nf′(1) = e · 4 = 4e."}, {"kind": "mcq", "text": "Differentiate y = (2x + 1)/(x² + 3).", "opts": ["(2x² + 2x − 6)/(x² + 3)²", "1/x", "(−2x² − 2x + 6)/(x² + 3)", "(−2x² − 2x + 6)/(x² + 3)²"], "correct": 3, "tag": "", "sol": "Quotient rule: [2(x² + 3) − (2x + 1)(2x)]/(x² + 3)² = (2x² + 6 − 4x² − 2x)/(x² + 3)² = (−2x² − 2x + 6)/(x² + 3)². (Swapping the numerator terms gives the opposite sign; 1/x = 2/(2x) divides the derivatives; the version over (x² + 3) forgets to square the denominator.)"}, {"kind": "blank", "p": "Differentiate y = sec x + ln(cos x).", "tag": "", "marks": "", "flat": [{"t": "d/dx (sec x) = __B1__", "a": {"B1": "sec(x)tan(x)"}, "expr": "calc"}, {"t": "d/dx ln(cos x) = __B1__", "a": {"B1": "-tan(x)"}, "expr": "calc"}, {"t": "y′ = __B1__", "a": {"B1": "sec(x)tan(x)-tan(x)"}, "expr": "calc"}], "sol": "sec x tan x.\nChain rule: (−sin x)/(cos x) = −tan x.\ny′ = sec x tan x − tan x = tan x (sec x − 1)."}, {"kind": "mcq", "text": "Differentiate y = e<sup>sin(2x)</sup>.", "opts": ["2cos(2x) e<sup>2cos(2x)</sup>", "2cos(2x) e<sup>sin(2x)</sup>", "cos(2x) e<sup>sin(2x)</sup>", "e<sup>sin(2x)</sup>"], "correct": 1, "tag": "", "sol": "e<sup>u</sup> → e<sup>u</sup> · u′ with u = sin(2x) and u′ = 2cos(2x) (chain rule again). The exponent stays sin(2x). (cos(2x) e<sup>sin(2x)</sup> forgets the 2 from 2x; e<sup>sin(2x)</sup> alone forgets u′; e<sup>2cos(2x)</sup> changes the exponent.)"}, {"kind": "blank", "p": "The curve e<sup>y</sup> + xy = e passes through (0, 1).", "tag": "", "marks": "", "flat": [{"t": "Implicitly: e<sup>y</sup> · dy/dx + y + x · dy/dx = 0, so dy/dx = __B1__", "a": {"B1": "-y/(e^y+x)"}, "expr": "calc"}, {"t": "Slope at (0, 1): __B1__ (exact)", "a": {"B1": "-1/e"}, "expr": "calc"}], "sol": "dy/dx (e<sup>y</sup> + x) = −y, so dy/dx = −y/(e<sup>y</sup> + x).\nAt (0, 1): −1/(e + 0) = −1/e."}, {"kind": "mcq", "text": "Differentiate y = tan⁻¹(5x).", "opts": ["5/(1 + 5x²)", "5/(1 + 25x²)", "5 sec²(5x)", "1/(1 + 25x²)"], "correct": 1, "tag": "", "sol": "tan⁻¹u → u′/(1 + u²) with u = 5x: 5/(1 + (5x)²) = 5/(1 + 25x²). (5x must be squared as a whole; sec² is the derivative of tan, not tan⁻¹.)"}, {"kind": "blank", "p": "Find the tangent line to y = ln x at x = e.", "tag": "", "marks": "", "flat": [{"t": "y(e) = __B1__", "a": {"B1": "1"}, "expr": "calc"}, {"t": "Slope y′(e) = __B1__ (exact)", "a": {"B1": "1/e"}, "expr": "calc"}, {"t": "Tangent line: y = __B1__", "a": {"B1": "x/e"}, "expr": "calc", "accept": ["1/ex"]}], "sol": "ln e = 1, so the point is (e, 1).\ny′ = 1/x, so the slope is 1/e.\ny = 1 + (1/e)(x − e) = x/e. (This tangent passes through the origin.)"}, {"kind": "mcq", "text": "Differentiate y = cos⁴(3x).", "opts": ["−12 cos³(3x) sin(3x)", "−4 cos³(3x) sin(3x)", "12 cos³(3x) sin(3x)", "−12 sin³(3x)"], "correct": 0, "tag": "", "sol": "Three layers: power, cosine, 3x. 4cos³(3x) · (−sin(3x)) · 3 = −12 cos³(3x) sin(3x). (−4… forgets the 3; +12… forgets the minus from cos′; −12 sin³(3x) differentiates inside the power instead of multiplying.)"}]}, {"id": "s11", "label": "Assessment B", "sub": "Investigating patterns", "slides": [{"kind": "mcq", "text": "What is the 99th derivative of f(x) = sin x?", "opts": ["−sin x", "sin x", "−cos x", "cos x"], "correct": 2, "tag": "", "sol": "The derivatives of sin x repeat every 4: cos x, −sin x, −cos x, sin x. 99 = 4 · 24 + 3, so f⁽⁹⁹⁾ = f‴ = −cos x."}, {"kind": "blank", "p": "Investigate the derivatives of f(x) = x eˣ.", "tag": "", "marks": "", "flat": [{"t": "f′(x) = __B1__", "a": {"B1": "(x+1)e^x"}, "expr": "calc"}, {"t": "f″(x) = __B1__", "a": {"B1": "(x+2)e^x"}, "expr": "calc"}, {"t": "f‴(x) = __B1__", "a": {"B1": "(x+3)e^x"}, "expr": "calc"}, {"t": "Continue the pattern: f⁽¹⁰⁾(x) = __B1__", "a": {"B1": "(x+10)e^x"}, "expr": "calc"}], "sol": "eˣ + x eˣ = (x + 1)eˣ.\neˣ + (x + 1)eˣ = (x + 2)eˣ.\n(x + 3)eˣ.\nEach derivative adds 1 to the bracket: f⁽ⁿ⁾(x) = (x + n)eˣ, so f⁽¹⁰⁾(x) = (x + 10)eˣ."}, {"kind": "mcq", "text": "For any constant n, what is d/dx [(x² + 1)ⁿ]?", "opts": ["2nx(x² + 1)ⁿ⁻¹", "n(x² + 1)ⁿ⁻¹", "n(2x)ⁿ⁻¹", "2nx(x² + 1)ⁿ⁺¹"], "correct": 0, "tag": "", "sol": "Chain rule: n(x² + 1)ⁿ⁻¹ · 2x = 2nx(x² + 1)ⁿ⁻¹. (n(x² + 1)ⁿ⁻¹ forgets the inner derivative 2x; the power goes down by 1, not up; n(2x)ⁿ⁻¹ differentiates the inside before applying the power.)"}, {"kind": "blank", "p": "Investigate the slope of f(x) = x² at x = 3 using the average rate of change on [3, 3 + h].", "tag": "", "marks": "", "flat": [{"t": "h = 0.1: [f(3.1) − f(3)]/0.1 = __B1__", "a": {"B1": "6.1"}, "expr": "calc"}, {"t": "h = 0.01: [f(3.01) − f(3)]/0.01 = __B1__", "a": {"B1": "6.01"}, "expr": "calc"}, {"t": "h = 0.001: __B1__", "a": {"B1": "6.001"}, "expr": "calc"}, {"t": "In general [f(3 + h) − f(3)]/h = (6h + h²)/h = 6 + __B1__", "a": {"B1": "h"}, "expr": "calc"}, {"t": "So f′(3) = __B1__", "a": {"B1": "6"}, "expr": "calc"}], "sol": "(9.61 − 9)/0.1 = 6.1.\n(9.0601 − 9)/0.01 = 6.01.\n(9.006001 − 9)/0.001 = 6.001.\n(3 + h)² − 9 = 6h + h², and dividing by h gives 6 + h.\nAs h → 0, 6 + h → 6 = f′(3) (and 2x = 6 at x = 3)."}, {"kind": "mcq", "text": "Which formula gives the nth derivative of f(x) = e<sup>−2x</sup>?", "opts": ["2ⁿ e<sup>−2x</sup>", "(−2)ⁿ e<sup>−2x</sup>", "−2n e<sup>−2x</sup>", "−2ⁿ e<sup>−2x</sup>"], "correct": 1, "tag": "", "sol": "Each derivative multiplies by −2: f′ = −2e<sup>−2x</sup>, f″ = 4e<sup>−2x</sup>, f‴ = −8e<sup>−2x</sup>. So f⁽ⁿ⁾ = (−2)ⁿ e<sup>−2x</sup>; the sign alternates. (−2ⁿ is always negative, 2ⁿ always positive, and −2n gives −4 instead of 4 for n = 2.)"}, {"kind": "blank", "p": "Investigate the derivatives of g(x) = 1/(1 − x) = (1 − x)<sup>−1</sup>.", "tag": "", "marks": "", "flat": [{"t": "g′(x) = __B1__", "a": {"B1": "1/(1-x)^2"}, "expr": "calc"}, {"t": "g″(x) = __B1__", "a": {"B1": "2/(1-x)^3"}, "expr": "calc"}, {"t": "g‴(x) = __B1__", "a": {"B1": "6/(1-x)^4"}, "expr": "calc"}, {"t": "Pattern g⁽ⁿ⁾(x) = n!/(1 − x)ⁿ⁺¹: g⁽⁵⁾(x) = __B1__", "a": {"B1": "120/(1-x)^6"}, "expr": "calc"}], "sol": "−1 · (1 − x)<sup>−2</sup> · (−1) = 1/(1 − x)².\n−2(1 − x)<sup>−3</sup> · (−1) = 2/(1 − x)³.\n6/(1 − x)⁴.\nThe chain factor −1 cancels the minus sign each time: g⁽⁵⁾ = 5!/(1 − x)⁶ = 120/(1 − x)⁶."}, {"kind": "mcq", "text": "Extend the product rule: which formula is correct for the second derivative (fg)″?", "opts": ["f″g″", "f″g + 2f′g′ + fg″", "f″g + f′g′ + fg″", "f″g + fg″"], "correct": 1, "tag": "", "sol": "(fg)′ = f′g + fg′. Differentiate again: (f″g + f′g′) + (f′g′ + fg″) = f″g + 2f′g′ + fg″, like the binomial (a + b)². Check with f = sin x, g = eˣ: the formula gives (−sin x + 2cos x + sin x)eˣ = 2eˣ cos x, which is the second derivative of eˣ sin x."}, {"kind": "blank", "p": "Investigate repeated derivatives of sin(3x).", "tag": "", "marks": "", "flat": [{"t": "d/dx sin(3x) = __B1__", "a": {"B1": "3cos(3x)"}, "expr": "calc"}, {"t": "d²/dx² sin(3x) = __B1__", "a": {"B1": "-9sin(3x)"}, "expr": "calc"}, {"t": "d⁴/dx⁴ sin(3x) = __B1__", "a": {"B1": "81sin(3x)"}, "expr": "calc"}, {"t": "Every two derivatives multiply by −9, so d⁶/dx⁶ sin(3x) = k sin(3x) with k = __B1__", "a": {"B1": "-729"}, "expr": "calc"}], "sol": "3cos(3x).\n−9 sin(3x).\n(−9)² sin(3x) = 81 sin(3x).\n(−9)³ = −729."}, {"kind": "mcq", "text": "The tangent line to y = x² at x = a is y = 2ax − a². What is its y-intercept?", "opts": ["−2a", "a²", "−a²", "2a"], "correct": 2, "tag": "", "sol": "Point (a, a²), slope 2a: y = a² + 2a(x − a) = 2ax − a². At x = 0, y = −a². For example a = 3 gives y = 6x − 9, intercept −9. Every tangent to this parabola crosses the y-axis below the origin."}]}, {"id": "s12", "label": "Assessment C", "sub": "Communicating", "slides": [{"kind": "mcq", "text": "Which of these is <b>not</b> a way of writing the derivative of y = f(x)?", "opts": ["Δy/Δx on [x, x + 1]", "dy/dx", "d/dx [f(x)]", "f′(x)"], "correct": 0, "tag": "", "sol": "dy/dx, f′(x) and d/dx [f(x)] all mean the derivative. Δy/Δx on [x, x + 1] is an average rate of change over an interval of width 1; it only becomes the derivative in the limit as the width shrinks to 0."}, {"kind": "blank", "p": "<b>Spot the error.</b> A student writes d/dx (3x² + 1)⁵ = 5(3x² + 1)⁴.", "tag": "", "marks": "", "flat": [{"t": "The student forgot to multiply by the derivative of the inside, which is __B1__", "a": {"B1": "6x"}, "expr": "calc"}, {"t": "The correct derivative is __B1__", "a": {"B1": "30x(3x^2+1)^4"}, "expr": "calc"}], "sol": "The inner function 3x² + 1 has derivative 6x.\n5(3x² + 1)⁴ · 6x = 30x(3x² + 1)⁴."}, {"kind": "mcq", "text": "Why is f(x) = |x − 2| not differentiable at x = 2?", "opts": ["f(2) = 0, and a derivative cannot be found where f is 0", "f is not continuous at x = 2, so it has no derivative there", "The slope is −1 just left of 2 and +1 just right of 2, so there is a corner", "The tangent at x = 2 is horizontal, so the slope is undefined"], "correct": 2, "tag": "", "sol": "f is continuous at 2, but the left slope (−1) and the right slope (+1) are different, so lim [f(2 + h) − f(2)]/h does not exist. f(2) = 0 has nothing to do with it, and a horizontal tangent would have slope 0, not an undefined slope."}, {"kind": "blank", "p": "<b>Spot the error.</b> A student writes d/dx [x² sin x] = 2x cos x.", "tag": "", "marks": "", "flat": [{"t": "Correct product rule: d/dx [x² sin x] = 2x sin x + __B1__", "a": {"B1": "x^2cos(x)"}, "expr": "calc"}, {"t": "So the derivative is __B1__", "a": {"B1": "2xsin(x)+x^2cos(x)"}, "expr": "calc"}], "sol": "The student multiplied the two derivatives. The product rule is (first)′ · second + first · (second)′; the missing term is x² cos x.\nd/dx [x² sin x] = 2x sin x + x² cos x."}, {"kind": "mcq", "text": "What does d²y/dx² mean?", "opts": ["the derivative of y² with respect to x", "dy/dx divided by x²", "(dy/dx)², the first derivative squared", "the derivative of dy/dx with respect to x"], "correct": 3, "tag": "", "sol": "d²y/dx² = d/dx (dy/dx): differentiate twice. The “2”s are part of the notation, not powers: (dy/dx)² is a different thing. For y = x³, d²y/dx² = 6x but (dy/dx)² = 9x⁴."}, {"kind": "blank", "p": "<b>Spot the error.</b> A student writes d/dx [x/(x + 1)] = [x · 1 − (x + 1) · 1]/(x + 1)² = −1/(x + 1)².", "tag": "", "marks": "", "flat": [{"t": "The numerator must be (bottom)(top)′ − (top)(bottom)′ = (x + 1) · 1 − x · 1 = __B1__", "a": {"B1": "1"}, "expr": "calc"}, {"t": "So the derivative is __B1__", "a": {"B1": "1/(x+1)^2"}, "expr": "calc"}], "sol": "The student swapped the order of the two terms, which flips the sign.\nd/dx [x/(x + 1)] = 1/(x + 1)². (Check: x/(x + 1) = 1 − 1/(x + 1) is increasing, so the derivative must be positive.)"}, {"kind": "mcq", "text": "<b>Spot the error.</b> For x² + y² = 4 a student writes “2x + 2y = 0, so dy/dx = −1.” Which comment is right?", "opts": ["d/dx (y²) is 2y · dy/dx, so dy/dx = −x/y", "x² should become x, so x + 2y · dy/dx = 0", "The working is correct: dy/dx = −1 everywhere on the circle", "The right side should become 4, so 2x + 2y = 4"], "correct": 0, "tag": "", "sol": "y is a function of x, so the chain rule gives d/dx (y²) = 2y · dy/dx. Then 2x + 2y · dy/dx = 0 and dy/dx = −x/y. The derivative of the constant 4 is 0. A slope of −1 everywhere would make the circle a straight line."}, {"kind": "blank", "p": "Use Leibniz notation: y = u³ with u = 2x − 5.", "tag": "", "marks": "", "flat": [{"t": "dy/du = __B1__ (in terms of u)", "a": {"B1": "3u^2"}, "expr": "calc"}, {"t": "du/dx = __B1__", "a": {"B1": "2"}, "expr": "calc"}, {"t": "dy/dx = (dy/du)(du/dx) = __B1__ (in terms of x)", "a": {"B1": "6(2x-5)^2"}, "expr": "calc"}], "sol": "dy/du = 3u².\ndu/dx = 2.\ndy/dx = 3u² · 2 = 6u² = 6(2x − 5)². The du “cancels” in the notation, which is a good way to remember the chain rule."}, {"kind": "mcq", "text": "<b>Spot the error.</b> f(x) = x³ and g = f⁻¹. A student says g′(8) = 1/f′(8) = 1/192. What is the correct value, and why?", "opts": ["1/12, because g(8) = 2 and f′(2) = 12", "12, because f′(2) = 12", "−1/12, because inverse functions reverse the slope", "1/192, because f′(8) = 3 · 8² = 192"], "correct": 0, "tag": "", "sol": "The formula is g′(a) = 1/f′(g(a)). Here g(8) = ∛8 = 2 and f′(2) = 3 · 2² = 12, so g′(8) = 1/12. (Check: g(x) = x<sup>1/3</sup>, g′(x) = (1/3)x<sup>−2/3</sup>, and g′(8) = (1/3)(1/4) = 1/12.) The student used f′ at the wrong point."}, {"kind": "blank", "p": "Use log properties first, then differentiate y = ln(x³√(x + 1)).", "tag": "", "marks": "", "flat": [{"t": "ln(x³√(x + 1)) = 3 ln x + k · ln(x + 1) with k = __B1__", "a": {"B1": "1/2"}, "expr": "calc"}, {"t": "y′ = __B1__", "a": {"B1": "3/x+1/(2(x+1))"}, "expr": "calc"}], "sol": "ln(ab) = ln a + ln b, ln(x³) = 3 ln x and ln √(x + 1) = ½ ln(x + 1). So k = ½.\ny′ = 3/x + 1/(2(x + 1)). This is much shorter than the chain rule on the whole logarithm."}]}, {"id": "s13", "label": "Assessment D", "sub": "Applying mathematics in real-life contexts", "slides": [{"kind": "mcq", "text": "The volume of a cube with edge s cm is V = s³. How fast is the volume changing with respect to s when s = 4 cm?", "opts": ["16 cm³ per cm", "64 cm³ per cm", "12 cm³ per cm", "48 cm³ per cm"], "correct": 3, "tag": "", "sol": "dV/ds = 3s², so at s = 4 it is 3 · 16 = 48 cm³ per cm. (64 is the volume itself; 12 = 3s; 16 = s².)"}, {"kind": "blank", "p": "A ball is thrown upward. Its height is h(t) = 30 + 25t − 4.9t² metres after t seconds.", "tag": "", "marks": "", "flat": [{"t": "Velocity v(t) = __B1__", "a": {"B1": "25-9.8t"}, "expr": "calc"}, {"t": "v(2) = __B1__ m/s", "a": {"B1": "5.4"}, "expr": "calc"}, {"t": "The ball is highest when v(t) = 0, at t ≈ __B1__ s (2 decimal places)", "a": {"B1": "2.55"}, "expr": "approx"}, {"t": "Acceleration h″(t) = __B1__ m/s²", "a": {"B1": "-9.8"}, "expr": "calc"}], "sol": "v(t) = h′(t) = 25 − 9.8t.\nv(2) = 25 − 19.6 = 5.4 m/s (still rising).\n25 − 9.8t = 0 gives t = 25/9.8 ≈ 2.55 s.\nh″(t) = −9.8 m/s²: gravity."}, {"kind": "mcq", "text": "A town’s population is P(t) = 500e<sup>0.04t</sup> people, t years from now. How fast is it growing when t = 10?", "opts": ["about 1.5 people per year", "about 745.9 people per year", "about 29.8 people per year", "exactly 20 people per year"], "correct": 2, "tag": "", "sol": "P′(t) = 500 · 0.04 e<sup>0.04t</sup> = 20e<sup>0.04t</sup>, so P′(10) = 20e<sup>0.4</sup> ≈ 29.8 people per year. (745.9 is P(10), the population itself; 20 forgets the e<sup>0.4</sup>; 1.5 is just e<sup>0.4</sup>.)"}, {"kind": "blank", "p": "The cost of making x items is C(x) = 2000 + 15x − 0.01x² dollars.", "tag": "", "marks": "", "flat": [{"t": "Marginal cost C′(x) = __B1__", "a": {"B1": "15-0.02x"}, "expr": "calc"}, {"t": "C′(100) = __B1__ dollars per item", "a": {"B1": "13"}, "expr": "calc"}, {"t": "The actual cost of the 101st item, C(101) − C(100) = __B1__ dollars", "a": {"B1": "12.99"}, "expr": "calc"}], "sol": "C′(x) = 15 − 0.02x.\nC′(100) = 15 − 2 = 13.\nC(101) = 3412.99 and C(100) = 3400, so the 101st item costs $12.99: the derivative is a very good estimate."}, {"kind": "mcq", "text": "A 10 m ladder leans against a wall. Its foot slides away from the wall at 0.5 m/s. How fast is the top sliding down when the foot is 6 m from the wall? (x² + y² = 100)", "opts": ["dy/dt = −0.667 m/s", "dy/dt = −3 m/s", "dy/dt = −0.375 m/s", "dy/dt = 0.375 m/s"], "correct": 2, "tag": "", "sol": "When x = 6, y = √(100 − 36) = 8. Differentiate x² + y² = 100 with respect to t: 2x dx/dt + 2y dy/dt = 0, so dy/dt = −(x/y) dx/dt = −(6/8)(0.5) = −0.375 m/s: the top moves down at 0.375 m/s. (−0.667 uses y/x; −3 forgets to divide by y.)"}, {"kind": "blank", "p": "The concentration of a medicine in the blood is C(t) = 5t e<sup>−0.5t</sup> mg/L, t hours after a dose.", "tag": "", "marks": "", "flat": [{"t": "C′(t) = __B1__ (factor it)", "a": {"B1": "5e^(-0.5t)(1-0.5t)"}, "expr": "calc"}, {"t": "C′(1) ≈ __B1__ mg/L per hour (2 decimal places)", "a": {"B1": "1.52"}, "expr": "approx"}, {"t": "The concentration is greatest when C′(t) = 0, at t = __B1__ hours", "a": {"B1": "2"}, "expr": "calc"}], "sol": "Product rule: 5e<sup>−0.5t</sup> + 5t(−0.5)e<sup>−0.5t</sup> = 5e<sup>−0.5t</sup>(1 − 0.5t).\nC′(1) = 2.5e<sup>−0.5</sup> ≈ 1.52: still rising one hour after the dose.\n1 − 0.5t = 0 at t = 2; C′ is positive before and negative after, so this is the maximum."}, {"kind": "mcq", "text": "A cup of coffee cools so that its temperature is T(t) = 20 + 70e<sup>−0.1t</sup> °C after t minutes. What is T′(5)?", "opts": ["about 62.5 °C per minute", "about 4.25 °C per minute", "about −7 °C per minute", "about −4.25 °C per minute"], "correct": 3, "tag": "", "sol": "T′(t) = 70 · (−0.1)e<sup>−0.1t</sup> = −7e<sup>−0.1t</sup>, so T′(5) = −7e<sup>−0.5</sup> ≈ −4.25 °C per minute. The negative sign means the coffee is cooling. (62.5 °C is the temperature T(5); −7 is T′(0).)"}, {"kind": "blank", "p": "A spherical balloon has volume V = (4/3)πr³ cm³ when its radius is r cm.", "tag": "", "marks": "", "flat": [{"t": "dV/dr = __B1__ (type pi for π)", "a": {"B1": "4pi*r^2"}, "expr": "calc"}, {"t": "At r = 3: dV/dr = __B1__ (exact, in terms of π)", "a": {"B1": "36pi"}, "expr": "calc"}, {"t": "dV/dr ≈ __B1__ cm³ per cm (1 decimal place)", "a": {"B1": "113.1"}, "expr": "approx"}], "sol": "dV/dr = 4πr², which is the surface area of the sphere.\n4π · 9 = 36π.\n36π ≈ 113.1 cm³ per cm."}, {"kind": "mcq", "text": "<b>Is this reasonable?</b> A student models a runner’s distance as s(t) = 0.3t² metres after t seconds and states “v(60) = 36 m/s.” Which comment is best?", "opts": ["It is wrong: v(60) = 0.6 m/s, because the derivative of 0.3t² is 0.6", "It is wrong: v(60) = 0.3 · 60² = 1080 m/s", "It is reasonable: v(t) = 0.6t is the correct derivative, so the answer must be realistic", "The calculus is right, but 36 m/s ≈ 130 km/h is far too fast for a runner, so the model fails for large t"], "correct": 3, "tag": "", "sol": "v(t) = s′(t) = 0.6t, so v(60) = 36 m/s: the arithmetic is fine. But 36 m/s = 129.6 km/h, about three times faster than the fastest sprinters. A model with constant acceleration can only describe the first few seconds of a run. 1080 is s(60), a distance, and 0.6 forgets the t."}]}];
/* ================= build slide lists ================= */
var SLIDES = {}; SECTIONS.forEach(function(sec){ SLIDES[sec.id]=sec.slides; });
var TAB_DEFS = SECTIONS.map(function(sec){ return {id:sec.id, label:sec.label, sub:sec.sub}; });

/* ================= state ================= */
function blankItem(slide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    return {status:'unanswered', attempts:0, choice:undefined};
  }
  return {status:'unanswered', curStep:0, stepStates: slide.flat.map(function(){ return {status:'unanswered', attempts:0, inputs:{}}; })};
}
function defaultState(){
  var s={tabs:{}};
  TAB_DEFS.forEach(function(td){
    s.tabs[td.id] = { idx:0, maxReached:0, items: SLIDES[td.id].map(function(sl){ return blankItem(sl); }) };
  });
  return s;
}
var appState = {mode:null, learning:null, quiz:null};
var state = null;      // alias for appState[appState.mode]
var MODE = null;
var activeTab=TAB_DEFS[0].id;

function setMode(m){
  appState.mode = m;
  if(!appState[m]) appState[m] = defaultState();
  state = appState[m];
  MODE = m;
}
/* ================= student accounts (saved on this device) ================= */
var SHEET_KEY='sopaan-diff';
var ACC_KEY='sopaan-students-v1';
var storageOK=true;
var MEM={};
function lsGet(k){ var r=null; try{ r=localStorage.getItem(k); }catch(e){ storageOK=false; }
  if(r===null||r===undefined) r=MEM[k]||null; try{ return r?JSON.parse(r):null; }catch(e){ return null; } }
function lsSet(k,v){ var j=JSON.stringify(v); MEM[k]=j; try{ localStorage.setItem(k,j); return true; }catch(e){ storageOK=false; return false; } }
try{ localStorage.setItem('sopaan-probe','1'); localStorage.removeItem('sopaan-probe'); }catch(e){ storageOK=false; }
function hashPin(pin,salt){ var h=2166136261, str=salt+'|'+pin; for(var i=0;i<str.length;i++){ h^=str.charCodeAt(i); h=Math.imul(h,16777619)>>>0; } return h.toString(36); }
function accKey(name,roll){ return (name.trim().toLowerCase().replace(/\s+/g,' ')+'#'+roll.trim().toLowerCase()); }
function accounts(){ return lsGet(ACC_KEY)||{students:{}}; }
var student=null; // {key,name,roll}
var records=[];   // finished-tab history for this student on this sheet
function progKey(){ return SHEET_KEY+'::'+student.key; }

function loadState(){
  appState = {mode:null, learning:null, quiz:null}; records=[]; activeTab=TAB_DEFS[0].id;
  var saved=lsGet(progKey());
  if(!saved) return;
  try{
    ['learning','quiz'].forEach(function(m){
      if(saved[m] && saved[m].tabs){
        var fresh = defaultState();
        TAB_DEFS.forEach(function(td){
          if(saved[m].tabs[td.id] && saved[m].tabs[td.id].items && saved[m].tabs[td.id].items.length===SLIDES[td.id].length){
            fresh.tabs[td.id] = saved[m].tabs[td.id];
          }
        });
        appState[m] = fresh;
      }
    });
    if(saved.mode==='learning' || saved.mode==='quiz') appState.mode = saved.mode;
    if(saved.activeTab && TAB_DEFS.some(function(t){ return t.id===saved.activeTab; })) activeTab = saved.activeTab;
    if(Array.isArray(saved.records)) records = saved.records;
  }catch(e){}
}
function saveState(){
  if(!student) return;
  lsSet(progKey(), {mode:appState.mode, learning:appState.learning, quiz:appState.quiz, activeTab:activeTab, records:records, updated:Date.now()});
  var acc=accounts(); if(acc.students[student.key]){ acc.students[student.key].last=Date.now(); lsSet(ACC_KEY,acc); }
}
function addRecord(mode, tabId, correct, revealed, skipped, total){
  records.unshift({at:Date.now(), mode:mode, tab:tabId, correct:correct, revealed:revealed, skipped:skipped, total:total});
  if(records.length>60) records.length=60;
  saveState();
}
function fmtDate(ms){ try{ return new Date(ms).toLocaleString(undefined,{day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'}); }catch(e){ return ''; } }

function renderWho(){
  var el=document.getElementById('whoBar');
  if(!student){ el.hidden=true; el.innerHTML=''; return; }
  el.hidden=false;
  el.innerHTML='Signed in as <b>'+esc(student.name)+'</b> · Roll '+esc(student.roll)+
    ' <button id="btnRecord">My record</button> <button id="btnSignOut">Sign out</button>';
  document.getElementById('btnRecord').addEventListener('click', renderRecord);
  document.getElementById('btnSignOut').addEventListener('click', signOut);
}
function signOut(){
  saveState(); student=null; state=null; MODE=null;
  var acc=accounts(); delete acc.current; lsSet(ACC_KEY,acc);
  document.getElementById('modePill').hidden=true;
  renderWho(); renderLogin();
}
function signIn(key){
  var acc=accounts(); var st=acc.students[key]; if(!st) return;
  student={key:key, name:st.name, roll:st.roll};
  acc.current=key; st.last=Date.now(); lsSet(ACC_KEY,acc);
  loadState(); renderWho();
  if(appState.mode==='learning' || appState.mode==='quiz'){
    setMode(appState.mode); document.getElementById('modePill').hidden=false; updateModePill();
    showChrome(true); buildTabbar(); renderSlide();
    showToast('Welcome back, '+st.name.split(' ')[0]+'. Picking up where you left off.');
  } else {
    renderModePicker();
  }
}
function renderLogin(msg){
  showChrome(false);
  var acc=accounts(); var keys=Object.keys(acc.students).sort(function(a,b){ return (acc.students[b].last||0)-(acc.students[a].last||0); });
  var h='<div class="login-card"><h2>Student sign-in</h2>'+
    '<p class="lead">Sign in to save your answers, see your record and continue where you left off next time.</p>';
  if(!storageOK) h+='<div class="login-err">This browser is blocking saved data (for example, a private window). You can still practise, but progress will not be kept after you close the page.</div>';
  if(msg) h+='<div class="login-err">'+esc(msg)+'</div>';
  if(keys.length){
    h+='<div class="known"><span class="known-label">Continue as</span>';
    keys.slice(0,6).forEach(function(k){ var st=acc.students[k];
      h+='<button class="known-btn" data-k="'+esc(k)+'"><span>'+esc(st.name)+' <small>· Roll '+esc(st.roll)+'</small></span><small>'+(st.last?'Last active '+fmtDate(st.last):'')+'</small></button>'; });
    h+='</div>';
  }
  h+='<form id="loginForm" novalidate>'+
    '<div class="fld"><label for="lgName">Full name</label><input id="lgName" autocomplete="name" required></div>'+
    '<div class="fld-row"><div class="fld"><label for="lgRoll">Roll no.</label><input id="lgRoll" required></div>'+
    '<div class="fld"><label for="lgPin">4-digit PIN</label><input id="lgPin" type="password" inputmode="numeric" maxlength="4" autocomplete="off" required></div></div>'+
    '<button class="btn btn-primary" type="submit" style="width:100%;">Sign in</button>'+
    '<p class="login-note">New here? Enter your name, roll no. and a PIN you will remember, and your profile is created. Progress is saved on this device, so use the same device and browser to continue.</p>'+
    '</form></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  wrap.querySelectorAll('.known-btn').forEach(function(b){
    b.addEventListener('click', function(){
      var st=accounts().students[b.dataset.k];
      document.getElementById('lgName').value=st.name; document.getElementById('lgRoll').value=st.roll;
      document.getElementById('lgPin').focus();
    });
  });
  document.getElementById('loginForm').addEventListener('submit', function(e){
    e.preventDefault();
    var name=document.getElementById('lgName').value.trim(), roll=document.getElementById('lgRoll').value.trim(), pin=document.getElementById('lgPin').value.trim();
    if(!name||!roll){ renderLoginErr('Enter your name and roll no.'); return; }
    if(!/^\d{4}$/.test(pin)){ renderLoginErr('Your PIN must be exactly 4 digits.'); return; }
    var k=accKey(name,roll); var acc=accounts();
    if(acc.students[k]){
      if(acc.students[k].pin!==hashPin(pin,k)){ renderLoginErr('That PIN does not match this name and roll no. Try again.'); return; }
    } else {
      acc.students[k]={name:name.replace(/\s+/g,' '), roll:roll, pin:hashPin(pin,k), created:Date.now()};
      lsSet(ACC_KEY,acc);
    }
    signIn(k);
  });
}
function renderLoginErr(m){
  var n=document.getElementById('lgName').value, r=document.getElementById('lgRoll').value;
  renderLogin(m); document.getElementById('lgName').value=n; document.getElementById('lgRoll').value=r; document.getElementById('lgPin').focus();
}
function tabSummary(m){
  var st=appState[m]; if(!st) return null;
  return TAB_DEFS.map(function(td){
    var items=st.tabs[td.id].items, n=items.length;
    var c=items.filter(function(i){return i.status==='correct';}).length;
    var done=items.filter(function(i){return i.status!=='unanswered';}).length;
    return {label:td.label, n:n, done:done, correct:c};
  });
}
function renderRecord(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+' · Differentiation</p>';
  ['learning','quiz'].forEach(function(m){
    var sum=tabSummary(m);
    h+='<h3>'+(m==='learning'?'📘 Learning Sheet':'📝 Quiz Mode')+'</h3>';
    if(!sum){ h+='<p class="rec-empty">Not started yet.</p>'; return; }
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>Section</th><th>Progress</th><th>Correct first time</th></tr></thead><tbody>';
    sum.forEach(function(r){ var pct=Math.round(r.done/r.n*100);
      h+='<tr><td>'+r.label+'</td><td><span class="rec-bar"><i style="width:'+pct+'%"></i></span>'+r.done+' / '+r.n+'</td><td>'+(m==='quiz'?'—':r.correct+' / '+r.n)+'</td></tr>'; });
    h+='</tbody></table></div>';
  });
  h+='</div><div class="rec-card"><h3>Finished sections</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sections finished yet. Each time you finish a tab, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>When</th><th>Mode</th><th>Section</th><th>Score</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+(r.mode==='learning'?' <span class="rec-empty">('+r.revealed+' revealed, '+r.skipped+' skipped)</span>':'')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){
    if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker();
  });
  window.scrollTo({top:0});
}

/* ================= tab bar ================= */
function buildTabbar(){
  var el=document.getElementById('tabbar');
  el.innerHTML = '<button class="tab-btn'+(activeTab==='theory'?' active':'')+'" data-tab="theory">Theory<span class="tab-count">notes</span></button>' + TAB_DEFS.map(function(t){
    return '<button class="tab-btn'+(t.id===activeTab?' active':'')+'" data-tab="'+t.id+'">'+t.label+'<span class="tab-count">'+SLIDES[t.id].length+'</span></button>';
  }).join('') + '<button class="tab-btn'+(activeTab==='report'?' active':'')+'" data-tab="report">📊 Report<span class="tab-count">pie</span></button>';
  el.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click', function(){ activeTab=btn.dataset.tab; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  });
}

/* ================= rendering ================= */
function canProceed(item){ return item.status==='correct'||item.status==='revealed'||item.status==='skipped'; }

function renderSlide(){
  if(!state.tabs[activeTab]){ activeTab=TAB_DEFS[0].id; }
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  if(ts.idx>=slides.length||ts.idx<0) ts.idx=0;
  var idx = ts.idx;
  var slide = slides[idx];
  var item = ts.items[idx];

  var tdef=TAB_DEFS.find(function(t){return t.id===activeTab;});
  document.getElementById('spLabel').textContent = tdef.label+' · Question '+(idx+1)+' of '+slides.length;
  document.getElementById('secSub').textContent = tdef.label+' — '+tdef.sub;
  document.getElementById('spFill').style.width = Math.round(((idx)/(Math.max(slides.length-1,1)))*100)+'%';

  var h='<div class="qcard">';
  if(slide.kind==='mcq' || slide.kind==='ar'){
    h += renderChoiceBody(slide, item, idx);
  } else {
    h += renderBlankBody(slide, item, idx);
  }
  h += '<div class="feedback" id="feedbackBox"></div>';
  if(MODE==='learning' && (item.status==='correct'||item.status==='revealed')) h += solutionHTML(slide);
  h += '</div>';

  document.getElementById('wrap').innerHTML = h;
  wireSlideEvents(slide, item, idx);
  restoreFeedback(item);
  renderNavbar(item);
  updateFab();
  saveState();
}

function solutionHTML(slide){
  if(!slide.sol) return '';
  return '<div class="solution"><div class="sol-h">Solution</div>'+slide.sol.split('\n').map(function(l){ return '<div class="sol-line">'+fr(esc(l))+'</div>'; }).join('')+'</div>';
}
var LETTERS=['a','b','c','d','e','f'];
function chosenHTML(slide,item){
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(item.choice===undefined) return '';
  var ok=item.choice===slide.correct;
  var h='<div class="chosen '+(ok?'ok':'bad')+'"><b>Your answer:</b> ('+LETTERS[item.choice]+') '+fr(esc(opts[item.choice]))+(ok?' ✓':' ✗')+'</div>';
  if(!ok) h+='<div class="chosen ok"><b>Correct answer:</b> ('+LETTERS[slide.correct]+') '+fr(esc(opts[slide.correct]))+'</div>';
  return h;
}
function renderChoiceBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div>';
  if(slide.kind==='mcq'){
    h += '<div class="qtext">'+fr(esc(slide.text))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  } else {
    h += '<div class="qtext"><span class="qtag" style="margin-left:0;margin-right:6px;">A / R</span>Assertion (A): '+fr(esc(slide.a))+'<br>Reason (R): '+fr(esc(slide.r))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  }
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(MODE==='quiz') h += '<div class="quiz-hint">Quiz mode — pick an option. The correct answer is revealed once you finish this tab.</div>';
  var locked = MODE==='learning' && (item.status==='correct' || item.status==='revealed');
  h += '<div class="options">';
  opts.forEach(function(opt,i){
    var cls='opt';
    if(locked){
      if(i===slide.correct) cls+=' is-correct';
      else if(item.choice===i) cls+=' is-wrong';
      cls+=' locked';
    }
    if(item.choice===i) cls+=' is-chosen';
    h += '<label class="'+cls+'"><input type="radio" name="choice" value="'+i+'" '+(item.choice===i?'checked':'')+' '+(locked?'disabled':'')+'> <span class="opt-l">('+LETTERS[i]+')</span> <span class="opt-t">'+fr(esc(opt))+'</span>'+(item.choice===i?'<span class="opt-tag">'+(locked?(i===slide.correct?'Your answer ✓':'Your answer ✗'):'Selected')+'</span>':'')+'</label>';
  });
  h += '</div>';
  if(locked) h += chosenHTML(slide,item);
  return h;
}

function renderBlankBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div><div class="qtext">';
  if(slide.kind==='case'){ h += '<b>'+esc(slide.title)+'.</b> '+esc(slide.body); }
  else { var pp=fr(esc(slide.p)).split('\n'); h += pp[0]+pp.slice(1).map(function(x){return '<span class="datline">'+x+'</span>';}).join(''); }
  h += (slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  if(slide.marks) h += '<div class="marks-pill">'+slide.marks+'</div>';
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';

  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  var blankCount=0; slide.flat.forEach(function(s){ blankCount+=Object.keys(s.a).length; });

  if(MODE==='quiz'){
    h += '<div class="step-badge">'+blankCount+' blank'+(blankCount===1?'':'s')+' in this question</div>';
    h += '<div class="quiz-hint">Quiz mode — fill in what you can. Correct answers are revealed once you finish this tab.</div>';
    if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
    if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
    h += '<div class="steps">';
    for(var qi=0; qi<total; qi++){
      var qstep = slide.flat[qi];
      var qss = item.stepStates[qi];
      if(qstep.partLabel) h += '<div class="subpart-label">'+esc(qstep.partLabel)+'</div>';
      if(qstep.orDivider) h += '<div class="or-divider">OR</div>';
      var qline = fr(qstep.t);
      Object.keys(qstep.a).forEach(function(bkey){
        var val = qss.inputs[bkey]||'';
        var inp='<input class="blank-input'+(['fv','fe','fl','fm','fi','dec'].indexOf(qstep.expr)>=0?' fr':(qstep.expr==='flist'||qstep.expr==='dlist'||qstep.expr==='glist')?' wide':qstep.expr===true?' expr':(qstep.expr==='words'||qstep.expr==='list'||qstep.expr==='expanded'||qstep.expr==='set'||qstep.expr==='primes'||qstep.expr==='trans'||qstep.expr==='rot'?' wide':''))+'" data-step="'+qi+'" data-bkey="'+bkey+'" value="'+esc(val)+'">';
        qline = qline.replace('__'+bkey+'__', inp);
      });
      if(qstep.fig) h += '<div class="fig">'+qstep.fig+'</div>';
      h += '<div class="step-line">'+qline+'</div>';
    }
    h += '</div>';
    return h;
  }

  if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
  if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
  var locked = item.status==='correct' || item.status==='revealed';
  var upto = locked ? total-1 : item.curStep;
  h += '<div class="step-badge">Step '+(Math.min(item.curStep,total-1)+1)+' of '+total+'</div>';
  h += '<div class="steps">';
  for(var i=0;i<=upto;i++){
    var step = slide.flat[i];
    var ss = item.stepStates[i];
    if(step.partLabel) h += '<div class="subpart-label">'+esc(step.partLabel)+'</div>';
    if(step.orDivider) h += '<div class="or-divider">OR</div>';
    var resolved = ss.status==='correct' || ss.status==='revealed';
    var line = fr(step.t);
    Object.keys(step.a).forEach(function(bkey){
      var fs = ss.inputs['fs_'+bkey];
      var cls = fs==='correct'?'is-correct':(fs==='wrong'?'is-wrong':'');
      var val = ss.inputs[bkey]||'';
      var dis = resolved ? 'disabled':'';
      var inp='<input class="blank-input '+cls+(['fv','fe','fl','fm','fi','dec'].indexOf(step.expr)>=0?' fr':(step.expr==='flist'||step.expr==='dlist'||step.expr==='glist')?' wide':step.expr===true?' expr':(step.expr==='words'||step.expr==='list'||step.expr==='expanded'||step.expr==='set'||step.expr==='primes'||step.expr==='trans'||step.expr==='rot'?' wide':''))+'" data-step="'+i+'" data-bkey="'+bkey+'" value="'+esc(val)+'" '+dis+'>';
      line = line.replace('__'+bkey+'__', inp);
    });
    if(step.fig) h += '<div class="fig">'+step.fig+'</div>';
    h += '<div class="step-line'+(resolved?' resolved':'')+'">'+line+'</div>';
    if(ss.status==='revealed'){
      var reveals=[];
      Object.keys(step.a).forEach(function(bkey){ reveals.push(bkey+' = '+esc(step.a[bkey])); });
      h += '<div class="reveal-note">correct: '+reveals.join(', ')+'</div>';
    }
  }
  h += '</div>';
  return h;
}

var __flash=null;
function restoreFeedback(item){
  var fb=document.getElementById('feedbackBox'); if(!fb) return;
  if(__flash){ fb.className='feedback show '+__flash.c; fb.innerHTML=__flash.h; __flash=null; return; }
  if(MODE==='quiz'){ fb.className='feedback'; fb.innerHTML=''; return; }
  if(item.status==='correct'){ fb.className='feedback show ok'; fb.innerHTML='<b>All done — correct!</b>'; }
  else if(item.status==='revealed'){ fb.className='feedback show reveal'; fb.innerHTML='<b>Answer revealed above.</b> Move on whenever you’re ready.'; }
  else if(item.status==='skipped'){ fb.className='feedback show retry'; fb.innerHTML='Skipped — you can answer it now and press <b>Check</b>, or come back later from the Question Palette.'; }
  else { fb.className='feedback'; fb.innerHTML=''; }
}

function slideIsAnswered(slide,item){
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return item.stepStates.some(function(ss){ return Object.keys(ss.inputs).some(function(k){ return k.indexOf('fs_')!==0 && ss.inputs[k] && String(ss.inputs[k]).trim()!==''; }); });
}
function renderNavbar(item){
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  var slide = slides[ts.idx];
  var isLast = ts.idx === slides.length-1;
  var h='';
  h += '<button class="btn" id="btnPrev" '+(ts.idx===0?'disabled':'')+'>&larr; Previous</button>';

  if(MODE==='quiz'){
    h += '<button class="btn" id="btnSkip">Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnNext">'+(isLast?'Finish':'Next →')+'</button>';
  } else {
    h += '<button class="btn" id="btnSkip" '+(item.status!=='unanswered'?'disabled':'')+'>Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnCheck" '+((item.status!=='unanswered'&&item.status!=='skipped')?'disabled':'')+'>Check</button>';
    h += '<button class="btn btn-primary" id="btnNext" '+(canProceed(item)?'':'disabled')+'>'+(isLast?'Finish':'Next →')+'</button>';
  }
  document.getElementById('navbarInner').innerHTML = h;

  document.getElementById('btnPrev').addEventListener('click', function(){ if(ts.idx>0){ ts.idx--; renderSlide(); } });

  if(MODE==='quiz'){
    document.getElementById('btnSkip').addEventListener('click', function(){
      item.status='skipped';
      advanceQuiz(ts, slides);
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      item.status = slideIsAnswered(slide,item) ? 'answered' : 'unanswered';
      advanceQuiz(ts, slides);
    });
  } else {
    document.getElementById('btnSkip').addEventListener('click', function(){
      if(item.status==='unanswered'){ item.status='skipped'; renderSlide(); }
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      if(!canProceed(item)) return;
      if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
      else { renderFinished(); }
    });
    document.getElementById('btnCheck').addEventListener('click', function(){ handleCheck(); });
  }
}
function advanceQuiz(ts, slides){
  if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
  else { renderFinished(); }
}

function wireSlideEvents(slide, item, idx){
  document.querySelectorAll('input[type="radio"][name="choice"]').forEach(function(r){
    r.addEventListener('change', function(){ item.choice=parseInt(r.value,10); saveState();
      document.querySelectorAll('.opt').forEach(function(l){ l.classList.remove('is-chosen'); var t=l.querySelector('.opt-tag'); if(t) t.remove(); });
      var lab=r.closest('.opt'); lab.classList.add('is-chosen'); var tg=document.createElement('span'); tg.className='opt-tag'; tg.textContent='Selected'; lab.appendChild(tg); });
  });
  document.querySelectorAll('.blank-input').forEach(function(inp){
    inp.addEventListener('input', function(){
      var si=parseInt(inp.dataset.step,10), bk=inp.dataset.bkey;
      item.stepStates[si].inputs[bk]=inp.value;
      saveState();
    });
  });
}

function handleCheck(){
  var ts = state.tabs[activeTab];
  var slide = SLIDES[activeTab][ts.idx];
  var item = ts.items[ts.idx];
  if(item.status==='skipped') item.status='unanswered';
  var fb = document.getElementById('feedbackBox');

  if(slide.kind==='mcq' || slide.kind==='ar'){
    if(item.choice===undefined){ fb.className='feedback show err'; fb.innerHTML='Please choose an option first.'; return; }
    var ok = item.choice===slide.correct;
    if(ok){
      item.status='correct'; playSuccess();
      fb.className='feedback show ok'; fb.innerHTML='<b>Correct!</b>';
    } else {
      item.attempts=(item.attempts||0)+1;
      if(item.attempts>=2){ item.status='revealed'; playReveal(); }
      else { playWrong(); fb.className='feedback show retry'; fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'}; }
    }
    renderSlide();
    return;
  }

  // blank / case
  var step = slide.flat[item.curStep];
  var ss = item.stepStates[item.curStep];
  var blanks = Object.keys(step.a);
  var missing = blanks.some(function(k){ return !ss.inputs[k] || String(ss.inputs[k]).trim()===''; });
  if(missing){ fb.className='feedback show err'; fb.innerHTML='Fill in every blank in this step before checking.'; return; }

  var allGood=true;
  blanks.forEach(function(k){
    var good=answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr);
    ss.inputs['fs_'+k]=good?'correct':'wrong';
    if(!good) allGood=false;
  });

  if(allGood){
    ss.status='correct'; playSuccess();
    advanceStepOrFinish(item, slide);
  } else {
    ss.attempts=(ss.attempts||0)+1;
    if(ss.attempts>=2){
      ss.status='revealed'; playReveal();
      advanceStepOrFinish(item, slide);
    } else {
      playWrong();
      fb.className='feedback show retry';
      fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'};
      renderSlide();
      return;
    }
  }
  renderSlide();
}

function advanceStepOrFinish(item, slide){
  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  if(item.curStep < total-1){
    item.curStep++;
  } else {
    var anyRevealed = item.stepStates.some(function(ss){ return ss.status==='revealed'; });
    item.status = anyRevealed ? 'revealed' : 'correct';
  }
}

/* ================= palette ================= */
var overlay=document.getElementById('overlay');
function statusOf(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  return ts.items[i].status==='unanswered' ? 'locked' : ts.items[i].status;
}
function buildPalette(){
  var slides=SLIDES[activeTab];
  document.getElementById('paletteTitle').textContent = TAB_DEFS.find(function(t){return t.id===activeTab;}).label+' · Question palette';
  var body=document.getElementById('paletteBody');
  var html='';
  for(var i=0;i<slides.length;i++){
    html += '<div class="chip" data-status="'+statusOf(activeTab,i)+'" data-idx="'+i+'">'+(i+1)+'</div>';
  }
  body.innerHTML = html;
  body.querySelectorAll('.chip').forEach(function(chip){
    chip.addEventListener('click', function(){
      var i=parseInt(chip.dataset.idx,10);
      var ts=state.tabs[activeTab];
      if(i>ts.maxReached){ showToast('Finish the earlier questions to unlock this one.'); return; }
      ts.idx=i; closePalette(); renderSlide();
    });
  });
}
function openPalette(){ buildPalette(); overlay.classList.add('show'); }
function closePalette(){ overlay.classList.remove('show'); }
var toastTimer;
function showToast(msg){
  var t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer); toastTimer=setTimeout(function(){ t.classList.remove('show'); },2200);
}
document.getElementById('paletteFab').addEventListener('click', openPalette);
document.getElementById('paletteClose').addEventListener('click', closePalette);
overlay.addEventListener('click', function(e){ if(e.target===overlay) closePalette(); });

function updateFab(){
  var slides=SLIDES[activeTab];
  var done=state.tabs[activeTab].items.filter(function(it){ return it.status==='correct'||it.status==='revealed'||it.status==='skipped'; }).length;
  document.getElementById('fabBadge').textContent = done+'/'+slides.length;
}

/* ================= overall progress + finish ================= */
function updateChapterProgress(){
  var total=0, done=0;
  TAB_DEFS.forEach(function(td){
    state.tabs[td.id].items.forEach(function(it){
      total++;
      if(it.status==='correct'||it.status==='revealed'||it.status==='skipped') done++;
    });
  });
  var pct = total>0 ? Math.round((done/total)*100) : 0;
  document.getElementById('cpFill').style.width=pct+'%';
  document.getElementById('cpLabel').textContent=pct+'% complete';
}
function isSlideCorrect(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice===slide.correct;
  return slide.flat.every(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).every(function(k){ return answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr); });
  });
}
function isSlideAttempted(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return slide.flat.some(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).some(function(k){ return ss.inputs[k] && String(ss.inputs[k]).trim()!==''; });
  });
}
function slideLabel(slide){
  var t = slide.kind==='case' ? slide.title : (slide.kind==='ar' ? slide.a : (slide.p||slide.text||''));
  t = String(t);
  return t.length>90 ? t.slice(0,90)+'…' : t;
}
function slideAnswerText(slide, item, correctSide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
    if(correctSide) return '('+LETTERS[slide.correct]+') '+opts[slide.correct];
    return item.choice!==undefined ? '('+LETTERS[item.choice]+') '+opts[item.choice] : '— not attempted —';
  }
  return slide.flat.map(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).map(function(k){
      return correctSide ? step.a[k] : (ss.inputs[k] || '—');
    }).join(', ');
  }).join('  |  ');
}

function renderFinished(){
  if(MODE==='quiz'){ renderQuizResults(); return; }
  var ts=state.tabs[activeTab];
  var correct=ts.items.filter(function(i){return i.status==='correct';}).length;
  var revealed=ts.items.filter(function(i){return i.status==='revealed';}).length;
  var skipped=ts.items.filter(function(i){return i.status==='skipped';}).length;
  var h='<div class="qcard done-card"><div class="big">✨</div><h2>Tab complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">You worked through all '+ts.items.length+' questions in this tab.</p>';
  if(!ts.recorded){ ts.recorded=true; addRecord('learning', activeTab, correct, revealed, skipped, ts.items.length); }
  h+='<div class="score-pills">'+
     '<span class="score-pill" style="background:var(--success-soft);color:var(--success);">'+correct+' correct</span>'+
     '<span class="score-pill" style="background:var(--danger-soft);color:var(--danger);">'+revealed+' revealed</span>'+
     '<span class="score-pill" style="background:var(--gold-soft);color:var(--retry-text);">'+skipped+' skipped</span></div>'+
     '<button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; ts.recorded=false; renderSlide(); });
  updateChapterProgress(); saveState();
}

function renderQuizResults(){
  var ts=state.tabs[activeTab];
  var slides=SLIDES[activeTab];
  var correctCount=0, attemptedCount=0;
  var rowsHtml = slides.map(function(slide,i){
    var item=ts.items[i];
    var ok=isSlideCorrect(activeTab,i);
    var att=isSlideAttempted(activeTab,i);
    if(ok) correctCount++;
    if(att) attemptedCount++;
    var tagCls = ok?'ok':(att?'bad':'na');
    var tagText = ok?'Correct':(att?'Incorrect':'Not attempted');
    var row='<div class="review-row">';
    row+='<span class="review-tag '+tagCls+'">Q'+(i+1)+' · '+tagText+'</span>';
    row+='<div class="review-q">'+fr(esc(slideLabel(slide)))+'</div>';
    row+='<div class="review-ans"><b>Your answer:</b> '+fr(esc(slideAnswerText(slide,item,false)))+'</div>';
    if(!ok) row+='<div class="review-ans" style="color:var(--success);"><b>Correct answer:</b> '+fr(esc(slideAnswerText(slide,item,true)))+'</div>';
    if(slide.sol) row+='<details class="rev-sol"><summary>Show solution</summary>'+solutionHTML(slide)+'</details>';
    row+='</div>';
    return row;
  }).join('');

  addRecord('quiz', activeTab, correctCount, 0, 0, slides.length);
  var h='<div class="qcard done-card" style="text-align:left;">';
  h+='<div style="text-align:center;"><div class="big">🏁</div><h2>Quiz complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">'+correctCount+' / '+slides.length+' correct · '+attemptedCount+' attempted</p></div>';
  h+='<div style="margin-top:16px;">'+rowsHtml+'</div>';
  h+='<div style="text-align:center;margin-top:6px;"><button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  h+='</div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; renderSlide(); });
  playSuccess();
  updateChapterProgress(); saveState();
}

/* ================= mode picker ================= */
function updateModePill(){
  var btn=document.getElementById('modePill');
  if(!btn) return;
  btn.textContent = MODE==='quiz' ? '📝 Quiz Mode · switch' : '📘 Learning Sheet · switch';
}
function showChrome(show){
  document.querySelector('.tabbar').style.display = show?'':'none';
  document.querySelector('.slide-progress').style.display = show?'':'none';
  document.querySelector('.navbar').style.display = show?'':'none';
  document.getElementById('paletteFab').style.display = show?'':'none';
}
function renderModePicker(){
  showChrome(false);
  var wrap=document.getElementById('wrap');
  wrap.innerHTML =
    '<div class="mode-pick">'+
      '<div class="mode-card" data-pick="learning"><div class="mode-icon">📘</div><h3>Learning Sheet</h3>'+
      '<p>Work through each question step by step with instant feedback — two tries, then the correct value is revealed right there so you can keep moving.</p></div>'+
      '<div class="mode-card" data-pick="quiz"><div class="mode-icon">📝</div><h3>Quiz Mode</h3>'+
      '<p>Attempt every question with no hints along the way. Your score and the full answer key are shown together once you finish the tab — just like the real exam.</p></div>'+
    '</div>';
  wrap.querySelectorAll('[data-pick]').forEach(function(card){
    card.addEventListener('click', function(){
      setMode(card.dataset.pick); activeTab='theory';
      document.getElementById('modePill').hidden=false;
      updateModePill();
      showChrome(true);
      buildTabbar();
      renderSlide();
    });
  });
}
document.getElementById('modePill').addEventListener('click', function(){
  if(!appState.mode){ return; }
  setMode(appState.mode==='quiz' ? 'learning' : 'quiz');
  updateModePill();
  showChrome(true);
  buildTabbar();
  renderSlide();
});

/* ================= boot ================= */
var _origRenderSlide = renderSlide;
renderSlide = function(){ _origRenderSlide(); updateChapterProgress(); updateModePill(); };


/* ================= theory tab ================= */
function renderTheory(){
  var wrap=document.getElementById('wrap');
  wrap.innerHTML='<div class="theory">'+fr(THEORY)+'</div>';
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Theory — notes, key ideas and worked examples';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
  wrap.querySelectorAll('[data-jump]').forEach(function(b){ b.addEventListener('click',function(){ var t=document.getElementById(b.dataset.jump); if(t) t.scrollIntoView({behavior:'smooth',block:'start'}); }); });
}
var _rsTheory = renderSlide;
renderSlide = function(){
  if(activeTab==='theory'){ renderTheory(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  document.querySelector('.slide-progress').style.display='';
  document.querySelector('.navbar').style.display='';
  document.getElementById('paletteFab').style.display='';
  _rsTheory();
};


/* ================= MYP criterion report ================= */
var CRIT_COL={A:'var(--accent-text)',B:'var(--gold)',C:'#8A6FC4',D:'#2F9AA0'};
function critStats(){
  return REPORT.map(function(r){
    var tabId=r[0], slides=SLIDES[tabId], ts=state&&state.tabs[tabId];
    var c=0,w=0,n=0;
    slides.forEach(function(sl,i){
      if(!ts||!ts.items[i]){ n++; return; }
      var it=ts.items[i];
      if(MODE==='learning'){
        if(it.status==='correct') c++; else if(it.status==='revealed') w++; else n++;
      } else {
        if(isSlideCorrect(tabId,i)) c++; else if(isSlideAttempted(tabId,i)) w++; else n++;
      }
    });
    var tot=slides.length, pct=tot?Math.round(c/tot*100):0;
    var lvl=Math.round(c/Math.max(tot,1)*8);
    return {tab:tabId,letter:r[1],name:r[2],c:c,w:w,n:n,tot:tot,pct:pct,lvl:lvl};
  });
}
function arcPath(cx,cy,r,a0,a1){
  if(a1-a0>=Math.PI*2-1e-6){ return 'M'+(cx-r)+','+cy+' a'+r+','+r+' 0 1,0 '+(2*r)+',0 a'+r+','+r+' 0 1,0 '+(-2*r)+',0 Z'; }
  var x0=cx+r*Math.sin(a0), y0=cy-r*Math.cos(a0), x1=cx+r*Math.sin(a1), y1=cy-r*Math.cos(a1);
  return 'M'+cx+','+cy+' L'+x0.toFixed(2)+','+y0.toFixed(2)+' A'+r+','+r+' 0 '+((a1-a0)>Math.PI?1:0)+',1 '+x1.toFixed(2)+','+y1.toFixed(2)+' Z';
}
function pieSVG(parts,size,hole,center,sub){
  var tot=parts.reduce(function(s,p){return s+p.v;},0), cx=size/2, cy=size/2, r=size/2-4, a=0, h='';
  if(!tot){ h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+r+'" style="fill:var(--paper-2);stroke:var(--rule)"/>'; }
  parts.forEach(function(p){ if(!p.v) return; var b=a+p.v/tot*Math.PI*2; h+='<path d="'+arcPath(cx,cy,r,a,b)+'" style="fill:'+p.col+';stroke:var(--card);stroke-width:2"><title>'+esc(p.label)+': '+p.v+'</title></path>'; a=b; });
  if(hole) h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+(r*hole)+'" style="fill:var(--card)"/>';
  if(center) h+='<text x="'+cx+'" y="'+(cy-(sub?4:0))+'" text-anchor="middle" dominant-baseline="middle" style="fill:var(--ink);font:700 '+(size>150?22:15)+'px Fraunces,serif">'+center+'</text>';
  if(sub) h+='<text x="'+cx+'" y="'+(cy+16)+'" text-anchor="middle" style="fill:var(--ink-soft);font:600 11px \'Source Sans 3\',sans-serif">'+sub+'</text>';
  return '<svg viewBox="0 0 '+size+' '+size+'" width="'+size+'" height="'+size+'" role="img">'+h+'</svg>';
}
function band(l){ return l===0?'0':(l<=2?'1–2':(l<=4?'3–4':(l<=6?'5–6':'7–8'))); }
function renderReport(){
  var st=critStats(), totC=0, totQ=0;
  st.forEach(function(s){ totC+=s.c; totQ+=s.tot; });
  var h='<div class="theory">';
  h+='<section class="note"><h2>Chapter test report</h2><p class="lt">'+(MODE==='quiz'?'<b>Quiz mode</b> results: answers are marked when you finish each test tab.':'<b>Learning mode</b> results: a question counts as correct only if you got it without the answer being revealed. Switch to Quiz mode for an exam-style score.')+'</p>';
  h+='<div class="rep-top"><div class="rep-pie">'+pieSVG(st.map(function(s){return {v:s.c,col:CRIT_COL[s.letter],label:'Criterion '+s.letter};}),200,0.55,totC+'/'+totQ,'correct')+'</div>';
  h+='<div class="rep-legend"><div class="rep-cap">Marks earned, by criterion</div>'+st.map(function(s){ return '<div class="rep-li"><span class="sw" style="background:'+CRIT_COL[s.letter]+'"></span><b>'+s.letter+'</b>&nbsp;'+esc(s.name)+'<span class="rep-n">'+s.c+' / '+s.tot+'</span></div>'; }).join('')+'</div></div></section>';
  h+='<div class="rep-grid">'+st.map(function(s){
    return '<div class="rep-card"><div class="rep-h"><span class="crit" style="background:'+CRIT_COL[s.letter]+'">'+s.letter+'</span>'+esc(s.name)+'</div>'+
      '<div class="rep-row">'+pieSVG([{v:s.c,col:'var(--success)',label:'Correct'},{v:s.w,col:'var(--danger)',label:'Incorrect'},{v:s.n,col:'var(--locked)',label:'Not attempted'}],120,0.5,s.pct+'%')+
      '<div class="rep-stats"><div><span class="sw" style="background:var(--success)"></span>Correct <b>'+s.c+'</b></div><div><span class="sw" style="background:var(--danger)"></span>Incorrect <b>'+s.w+'</b></div><div><span class="sw" style="background:var(--locked)"></span>Not attempted <b>'+s.n+'</b></div>'+
      '<div class="rep-lvl">Indicative level <b>'+s.lvl+'</b> / 8 <span>(band '+band(s.lvl)+')</span></div></div></div>'+
      '<button class="hub-btn" data-go="'+s.tab+'">Open Test '+s.letter+' →</button></div>';
  }).join('')+'</div>';
  h+='<p class="rep-note">Indicative level = fraction of questions correct × 8, rounded. It is a practice guide only; your teacher awards the real MYP criterion levels.</p></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Report — chapter test results by MYP criterion';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
}
var _rsReport = renderSlide;
renderSlide = function(){
  if(activeTab==='report'){ renderReport(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  _rsReport();
};


/* ================= skipped-question return ================= */
function firstSkippedIdx(ts){
  for(var i=0;i<ts.items.length;i++){
    var it=ts.items[i];
    if(MODE==='quiz'){ if(!isSlideAttempted(activeTab,i)) return i; }
    else if(it.status==='skipped'||it.status==='unanswered') return i;
  }
  return -1;
}
function skippedList(ts){
  var out=[]; for(var i=0;i<ts.items.length;i++){ var it=ts.items[i];
    if(MODE==='quiz' ? !isSlideAttempted(activeTab,i) : (it.status==='skipped'||it.status==='unanswered')) out.push(i); }
  return out;
}
function renderSkipGate(ts){
  var list=skippedList(ts);
  var h='<div class="qcard done-card"><div class="big">⏭️</div><h2>You skipped '+list.length+' question'+(list.length>1?'s':'')+'</h2>'+
    '<p style="color:var(--ink-soft);font-size:14px;">Answer them now, or submit the tab as it is. Answers are marked only when you submit.</p>'+
    '<div class="skip-chips">'+list.map(function(i){ return '<button class="chip skip-go" data-i="'+i+'">Q'+(i+1)+'</button>'; }).join('')+'</div>'+
    '<div class="skip-btns"><button class="btn btn-primary" id="btnGoSkipped">Answer skipped questions</button><button class="btn" id="btnSubmitAnyway">Submit anyway</button></div></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  var go=function(i){ ts.idx=i; ts.maxReached=Math.max(ts.maxReached,i); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); };
  document.getElementById('btnGoSkipped').addEventListener('click',function(){ go(list[0]); });
  document.querySelectorAll('.skip-go').forEach(function(b){ b.addEventListener('click',function(){ go(parseInt(b.dataset.i,10)); }); });
  document.getElementById('btnSubmitAnyway').addEventListener('click',function(){ ts.submitOK=true; renderFinished(); ts.submitOK=false; });
  saveState();
}
var _rfSkip = renderFinished;
renderFinished = function(){
  var ts=state.tabs[activeTab];
  if(MODE==='quiz' && !ts.submitOK && skippedList(ts).length){ renderSkipGate(ts); return; }
  _rfSkip();
  if(MODE==='learning'){
    var list=skippedList(ts);
    if(list.length){
      var card=document.querySelector('.done-card');
      if(card){ var d=document.createElement('div'); d.className='skip-btns';
        d.innerHTML='<button class="btn btn-primary" id="btnGoSkipped">Attempt skipped questions ('+list.length+')</button>';
        card.appendChild(d);
        document.getElementById('btnGoSkipped').addEventListener('click',function(){ ts.idx=list[0]; ts.recorded=false; renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); }
    }
  }
};


/* ================= approx answers (physics: within 1%) ================= */
var _amTools = answerMatches;
answerMatches = function(input,answer,accept,expr){
  if(expr==='approx'){
    var n1=parseNum(input); if(n1===null) return false;
    return [answer].concat(accept||[]).some(function(a){ var n2=parseNum(a); if(n2===null) return false; return Math.abs(n1-n2) <= Math.max(0.011*Math.abs(n2), 1e-9); });
  }
  return _amTools(input,answer,accept,expr);
};

/* ================= palette: every question already reached can be opened ================= */
statusOf = function(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  var s=ts.items[i].status;
  if(s==='unanswered') return 'skipped';
  return s;
};

/* ================= on-screen keyboard ================= */
var KB={on:true, page:'num', target:null};
try{ var kbp=localStorage.getItem('sopaan-kb-pref'); if(kbp==='off') KB.on=false; }catch(e){}
function kbSave(){ try{ localStorage.setItem('sopaan-kb-pref', KB.on?'on':'off'); }catch(e){} }
var KEYS_NUM=[['7','8','9','(',')'],['4','5','6','−','/'],['1','2','3','.',','],['0',':','%','°','⌫'],['abc','←','→','Clear','Done']];
var KEYS_FRAC=[['7','8','9','/'],['4','5','6','−'],['1','2','3','space'],['0',',','⌫','Clear'],['abc','←','→','Done']];
var KEYS_ALG=[['7','8','9','x','y','n'],['4','5','6','+','−','a'],['1','2','3','×','÷','b'],['0','.','(',')','^','²'],['/','π','|','t','⌫','Clear'],['abc','←','→','Done']];
function kbLayoutFor(inp){ try{ var ts=state.tabs[activeTab], sl=SLIDES[activeTab][ts.idx], stp=sl.flat[parseInt(inp.dataset.step,10)]; var m=stp.expr, key=String(stp.a[inp.dataset.bkey]||'');
  if(m==='words'||m==='glist'||m==='angle') return 'abc'; if(m===true||m==='pow'||m==='primes') return 'alg';
  if(['fv','fe','fl','fm','fi','flist'].indexOf(m)>=0) return 'frac'; if(m==='dec'||m==='approx'||m==='dlist'||m==='set'||m==='coord'||m==='list'||m==='time') return 'num';
  if(/^[\-−]?\d+ \d+\/\d+$/.test(key)||/^[\-−]?\d+\/\d+$/.test(key)) return 'frac'; if(/[a-df-z]/i.test(key.replace(/pi/gi,''))) return /\d/.test(key)?'alg':'abc'; return 'num'; }catch(e){ return 'num'; } }
var KEYS_CALC=[['7','8','9','x','(',')'],['4','5','6','+','−','^'],['1','2','3','×','/','²'],['0','.','e','eˣ','√','ln'],['sin','cos','tan','t','⌫','Clear'],['abc','←','→','Done']];
var KEYS_ABC=[['q','w','e','r','t','y','u','i','o','p'],['a','s','d','f','g','h','j','k','l','-'],['z','x','c','v','b','n','m',',',':','/'],['123','space','←','→','⌫','Done']];
function kbBuild(){
  var el=document.getElementById('vkb'); if(!el){ el=document.createElement('div'); el.id='vkb'; el.className='vkb'; document.body.appendChild(el);
    el.addEventListener('pointerdown',function(e){ var b=e.target.closest('button[data-k]'); e.preventDefault(); if(b) kbPress(b.dataset.k); });
    el.addEventListener('mousedown',function(e){ e.preventDefault(); }); }
  var rows={num:KEYS_NUM,frac:KEYS_FRAC,alg:KEYS_ALG,abc:KEYS_ABC,calc:KEYS_CALC}[KB.page]||KEYS_NUM;
  el.innerHTML='<div class="vkb-top"><span>⌨️ Keyboard</span><button data-k="device" class="vkb-link">Use device keyboard</button></div>'+
    rows.map(function(r){ return '<div class="vkb-row">'+r.map(function(k){
      var cls='vkb-k'+(/^(abc|123|Done|Clear|⌫|←|→|space)$/.test(k)?' fn':'')+(k==='Done'?' done':'');
      return '<button type="button" class="'+cls+'" data-k="'+k+'">'+(k==='space'?'space':k)+'</button>'; }).join('')+'</div>'; }).join('');
  return el;
}
function kbShow(inp){ KB.target=inp; KB.home=kbLayoutFor(inp); KB.page=KB.home; if(!KB.on) return; var cp=document.getElementById('calcPanel'); if(cp&&cp.classList.contains('show')) return; var el=kbBuild(); var nb=document.querySelector('.navbar'); el.style.bottom=(nb?nb.getBoundingClientRect().height:0)+'px'; el.classList.add('show'); document.body.classList.add('kb-open'); setTimeout(function(){ var r=inp.getBoundingClientRect(), top=el.getBoundingClientRect().top; if(r.bottom>top-12) window.scrollBy({top:r.bottom-top+60,behavior:'smooth'}); else if(r.top<60) window.scrollBy({top:r.top-80,behavior:'smooth'}); },30); }
function kbHide(){ var el=document.getElementById('vkb'); if(el) el.classList.remove('show'); document.body.classList.remove('kb-open'); }
function kbInsert(s){
  var t=KB.target; if(!t||t.disabled) return;
  var a=t.selectionStart==null?t.value.length:t.selectionStart, b=t.selectionEnd==null?a:t.selectionEnd;
  t.value=t.value.slice(0,a)+s+t.value.slice(b); var p=a+s.length; try{ t.setSelectionRange(p,p); }catch(e){}
  t.dispatchEvent(new Event('input',{bubbles:true}));
}
function kbPress(k){
  var t=KB.target; if(k==='device'){ KB.on=false; kbSave(); kbHide(); document.querySelectorAll('.blank-input').forEach(function(i){ i.removeAttribute('inputmode'); }); if(t){ t.blur(); setTimeout(function(){ t.focus(); },50); } showToast('Device keyboard on. Tap ⌨️ on any blank to bring the on-screen keyboard back.'); return; }
  if(k==='Done'){ kbHide(); if(t) t.blur(); return; }
  if(k==='abc'||k==='123'){ KB.page=(k==='abc')?'abc':(KB.home&&KB.home!=='abc'?KB.home:'num'); kbBuild(); return; }
  if(!t) return;
  if(k==='⌫'){ var a=t.selectionStart, b=t.selectionEnd; if(a===b&&a>0){ t.value=t.value.slice(0,a-1)+t.value.slice(b); try{t.setSelectionRange(a-1,a-1);}catch(e){} } else { t.value=t.value.slice(0,a)+t.value.slice(b); try{t.setSelectionRange(a,a);}catch(e){} } t.dispatchEvent(new Event('input',{bubbles:true})); return; }
  if(k==='Clear'){ t.value=''; t.dispatchEvent(new Event('input',{bubbles:true})); return; }
  if(k==='←'||k==='→'){ var p=(t.selectionStart||0)+(k==='←'?-1:1); p=Math.max(0,Math.min(t.value.length,p)); try{t.setSelectionRange(p,p);}catch(e){} return; }
  var map={'−':'-','space':' '}; kbInsert(map[k]!==undefined?map[k]:k);
}
function kbWire(){
  document.querySelectorAll('.blank-input').forEach(function(inp){
    if(inp.dataset.kb) return; inp.dataset.kb='1';
    if(KB.on) inp.setAttribute('inputmode','none');
    inp.addEventListener('focus',function(){ kbShow(inp); });
    var btn=document.createElement('button'); btn.type='button'; btn.className='kb-toggle'; btn.title='On-screen keyboard'; btn.textContent='⌨️'; btn.tabIndex=-1;
    btn.addEventListener('mousedown',function(e){ e.preventDefault(); });
    btn.addEventListener('click',function(){ KB.on=true; kbSave(); document.querySelectorAll('.blank-input').forEach(function(i){ i.setAttribute('inputmode','none'); }); inp.focus(); kbShow(inp); });
    if(!inp.disabled) inp.insertAdjacentElement('afterend',btn);
  });
}
document.addEventListener('focusout',function(e){ setTimeout(function(){ var a=document.activeElement; if(!a||!a.classList||!a.classList.contains('blank-input')){ if(!document.querySelector('#vkb:hover')) kbHide(); } },120); });

/* ================= calculator ================= */
var CALC={expr:'', ans:0};
function calcEval(src){
  var s=String(src).replace(/×/g,'*').replace(/÷/g,'/').replace(/−/g,'-').replace(/π/g,'(PI)').replace(/Ans/g,'('+CALC.ans+')').replace(/\^/g,'**').replace(/√\(/g,'sqrt(').replace(/²/g,'**2').replace(/E/g,'*10**');
  s=s.replace(/(^|[(*\/+\-,])-/g,'$1(-1)*');
  if(/[^0-9+\-*/().,a-z A-Z]/.test(s)) throw 0;
  var ok=s.replace(/sin|cos|tan|asin|acos|atan|sqrt|log|ln|PI|abs/g,''); if(/[a-zA-Z]/.test(ok)) throw 0;
  var f=new Function('sin','cos','tan','asin','acos','atan','sqrt','log','ln','PI','abs','return ('+s+');');
  var d=Math.PI/180;
  var v=f(function(x){return Math.sin(x*d);},function(x){return Math.cos(x*d);},function(x){return Math.tan(x*d);},
    function(x){return Math.asin(x)/d;},function(x){return Math.acos(x)/d;},function(x){return Math.atan(x)/d;},Math.sqrt,Math.log10,Math.log,Math.PI,Math.abs);
  if(typeof v!=='number'||!isFinite(v)) throw 0; return v;
}
function fmtNum(v){ if(Math.abs(v)>=1e10||(Math.abs(v)<1e-6&&v!==0)) return v.toExponential(6).replace(/\.?0+e/,'e'); return String(parseFloat(v.toPrecision(10))); }
var CKEYS=[['sin(','cos(','tan(','√(','^','²'],['asin(','acos(','atan(','(',')','π'],['7','8','9','÷','⌫','AC'],['4','5','6','×','E','Ans'],['1','2','3','−','(−)','Insert'],['0','.','=','+']];
function openCalc(){
  var p=document.getElementById('calcPanel');
  if(!p){ p=document.createElement('div'); p.id='calcPanel'; p.className='tool-panel calc';
    p.innerHTML='<div class="tp-head"><b>🧮 Calculator</b><span class="tp-note">degrees · tap a blank, then Insert</span><button class="tp-x" data-c="close">✕</button></div>'+
      '<div class="calc-disp"><div class="calc-expr" id="calcExpr"></div><div class="calc-res" id="calcRes">0</div></div>'+
      '<div class="calc-keys">'+CKEYS.map(function(r){ return r.map(function(k){ return '<button type="button" data-c="'+k+'" class="'+(k==='='?'eq':(/^(AC|⌫|Insert)$/.test(k)?'fn':''))+'">'+({'sin(':'sin','cos(':'cos','tan(':'tan','asin(':'sin⁻¹','acos(':'cos⁻¹','atan(':'tan⁻¹','√(':'√'}[k]||k)+'</button>'; }).join(''); }).join('')+'</div>';
    document.body.appendChild(p);
    p.addEventListener('mousedown',function(e){ if(e.target.closest('button')) e.preventDefault(); });
    p.addEventListener('click',function(e){ var b=e.target.closest('button[data-c]'); if(!b) return; calcKey(b.dataset.c); });
  }
  kbHide(); var nb=document.querySelector('.navbar'); p.style.bottom=((nb?nb.getBoundingClientRect().height:0)+8)+'px'; p.classList.add('show'); document.body.classList.add('calc-open'); calcShow();
}
function calcShow(res){ document.getElementById('calcExpr').textContent=CALC.expr||' '; if(res!==undefined) document.getElementById('calcRes').textContent=res; }
function calcKey(k){
  if(k==='close'){ document.getElementById('calcPanel').classList.remove('show'); document.body.classList.remove('calc-open'); return; }
  if(k==='AC'){ CALC.expr=''; calcShow('0'); return; }
  if(k==='⌫'){ CALC.expr=CALC.expr.replace(/(asin\(|acos\(|atan\(|sin\(|cos\(|tan\(|√\(|Ans|.)$/,''); calcShow(); return; }
  if(k==='='){ try{ var v=calcEval(CALC.expr); CALC.ans=v; calcShow(fmtNum(v)); }catch(e){ calcShow('Error'); } return; }
  if(k==='(−)'){ CALC.expr+='−'; calcShow(); return; }
  if(k==='Insert'){ var r=document.getElementById('calcRes').textContent; if(KB.target && !KB.target.disabled && r!=='Error'){ KB.target.value=r; KB.target.dispatchEvent(new Event('input',{bubbles:true})); showToast('Inserted '+r+' into the blank.'); } else showToast('Tap a blank first, then press Insert.'); return; }
  CALC.expr+=k; calcShow();
}

/* ================= Desmos ================= */
var DESMOS_KEY='dcb31709b452b1cf9dc26972add0fda6', desmosCalc=null, desmosLoading=false;
function openDesmos(exprs){
  var p=document.getElementById('desmosPanel');
  if(!p){ p=document.createElement('div'); p.id='desmosPanel'; p.className='tool-panel desmos';
    p.innerHTML='<div class="tp-head"><b>📈 Desmos graphing calculator</b><button class="tp-x" id="desmosReset">Reset graph</button><button class="tp-x" id="desmosClose">✕</button></div><div id="desmosBox"><div class="desmos-msg">Loading Desmos…</div></div>';
    document.body.appendChild(p);
    document.getElementById('desmosClose').addEventListener('click',function(){ p.classList.remove('show'); });
    document.getElementById('desmosReset').addEventListener('click',function(){ if(desmosCalc) desmosSet(p._exprs||[]); });
  }
  p._exprs=exprs||[]; p.classList.add('show');
  if(window.Desmos){ desmosInit(); desmosSet(p._exprs); return; }
  if(desmosLoading) return; desmosLoading=true;
  var sc=document.createElement('script'); sc.src='https://www.desmos.com/api/v1.9/calculator.js?apiKey='+DESMOS_KEY;
  sc.onload=function(){ desmosInit(); desmosSet(p._exprs); };
  sc.onerror=function(){ desmosLoading=false; document.getElementById('desmosBox').innerHTML='<div class="desmos-msg">Desmos needs an internet connection. <a href="https://www.desmos.com/calculator" target="_blank" rel="noopener">Open Desmos in a new tab</a>.</div>'; };
  document.head.appendChild(sc);
}
function desmosInit(){ if(desmosCalc) return; var box=document.getElementById('desmosBox'); box.innerHTML=''; desmosCalc=Desmos.GraphingCalculator(box,{expressionsCollapsed:false,settingsMenu:false,border:false,degreeMode:true}); }
function desmosSet(exprs){ if(!desmosCalc) return; desmosCalc.setBlank(); (exprs||[]).forEach(function(e,i){ if(typeof e==='string') desmosCalc.setExpression({id:'e'+i,latex:e}); else desmosCalc.setExpression(Object.assign({id:'e'+i},e)); }); }

/* ================= toolbar on each question ================= */
var _rsTools = renderSlide;
renderSlide = function(){
  _rsTools();
  kbHide();
  if(activeTab==='theory'||activeTab==='report') return;
  var ts=state.tabs[activeTab]; if(!ts) return;
  var slide=SLIDES[activeTab][ts.idx], card=document.querySelector('#wrap .qcard');
  if(card && slide && slide.tools && slide.tools.length && !card.querySelector('.tool-bar')){
    var bar=document.createElement('div'); bar.className='tool-bar';
    bar.innerHTML=(slide.tools.indexOf('calc')>=0?'<button type="button" class="tool-btn" data-t="calc">🧮 Calculator</button>':'')+
                  (slide.tools.indexOf('desmos')>=0?'<button type="button" class="tool-btn" data-t="desmos">📈 Desmos graph</button>':'');
    card.insertBefore(bar, card.firstChild);
    bar.addEventListener('click',function(e){ var b=e.target.closest('[data-t]'); if(!b) return; if(b.dataset.t==='calc') openCalc(); else openDesmos(slide.desmos||[]); });
  }
  kbWire();
};



/* ================= signed fractions in text: {−3/4}, {3/−4}, {−2 1/3}, {p/q} ================= */
fr = function(s){ return String(s).replace(/&lt;(\/?)(b|sup|sub|i)>/g,'<$1$2>')
  .replace(/\{([−-]?\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>')
  .replace(/\{([−-]?[A-Za-z0-9]+)\/([−-]?[A-Za-z0-9]+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); };
/* ================= BMA badge → main page of this sheet (theory hub) ================= */
(function(){
  var c=document.querySelector('.brand .crest'); if(!c) return;
  var a=document.createElement('button'); a.type='button'; a.className='crest crest-home'; a.title='Back to the main page (theory notes)'; a.setAttribute('aria-label','Main page');
  a.innerHTML='<img src="data:image/png;base64,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" alt="Brain and Mind"><span class="crest-h">⌂</span>'; c.parentNode.replaceChild(a,c);
  a.addEventListener('click',function(){
    if(!student||!MODE){ window.scrollTo({top:0,behavior:'smooth'}); return; }
    if(typeof kbHide==='function') kbHide(); if(typeof SP!=='undefined'&&SP.on) spToggle(false);
    var cp=document.getElementById('calcPanel'); if(cp) cp.classList.remove('show'); document.body.classList.remove('calc-open');
    activeTab = (typeof THEORY!=='undefined') ? 'theory' : TAB_DEFS[0].id;
    buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'});
  });
})();

/* ================= session clock: starts at sign-in and keeps running ================= */
var CLK={t0:null};
(function(){
  var row=document.querySelector('.brand .brand-row'); if(!row) return;
  var d=document.createElement('div'); d.className='bmasw off'; d.id='swBox'; d.title='Time since you signed in';
  d.innerHTML='<span class="bmasw-ic">⏱</span><span class="bmasw-t" id="swT">00:00</span>';
  row.appendChild(d); setInterval(swTick,1000);
})();
function swFmt(s){ s=Math.floor(s||0); var h=Math.floor(s/3600), m=Math.floor(s%3600/60), x=s%60; return (h?h+':'+String(m).padStart(2,'0'):String(m).padStart(2,'0'))+':'+String(x).padStart(2,'0'); }
function swTick(){
  var box=document.getElementById('swBox'); if(!box) return;
  if(student && !CLK.t0) CLK.t0=Date.now();
  if(!student) CLK.t0=null;
  box.classList.toggle('off',!CLK.t0);
  document.getElementById('swT').textContent = CLK.t0 ? swFmt((Date.now()-CLK.t0)/1000) : '00:00';
}
function swTab(){ try{ if(!state||!state.tabs||activeTab==='theory'||activeTab==='report') return null; return state.tabs[activeTab]||null; }catch(e){ return null; } }
var _rsSW = renderSlide;
renderSlide = function(){ _rsSW(); swTick(); };
var _rfSW = renderFinished;
renderFinished = function(){ _rfSW(); var done=document.querySelector('#wrap .done-card'); if(CLK.t0 && done && !done.querySelector('.bmasw-done')){ var p=document.createElement('p'); p.className='bmasw-done'; p.textContent='⏱ Time since sign-in: '+swFmt((Date.now()-CLK.t0)/1000); var h2=done.querySelector('h2'); if(h2) h2.insertAdjacentElement('afterend',p); else done.appendChild(p); } };

/* ================= scratchpad (Khan-style, 4 pens) ================= */
var SP={on:false, draw:true, color:'ink', size:3, erase:false, store:{}, key:null, cv:null, ctx:null, down:false, last:null};
var SP_COL={ink:null, blue:'#2563EB', red:'#DC2626', green:'#16A34A'};
function spInk(){ return getComputedStyle(document.documentElement).getPropertyValue('--ink').trim()||'#211E1A'; }
function spKey(){ var ts=swTab(); return ts ? (MODE+'|'+activeTab+'|'+ts.idx) : null; }
function spBuild(){
  if(SP.cv) return;
  var cv=document.createElement('canvas'); cv.id='spCanvas'; cv.className='sp-canvas'; document.body.appendChild(cv);
  var bar=document.createElement('div'); bar.id='spBar'; bar.className='sp-bar';
  bar.innerHTML='<span class="sp-lbl">✏️ Scratchpad</span>'+
    ['ink','blue','red','green'].map(function(c){ return '<button type="button" class="sp-pen" data-c="'+c+'" title="'+(c==='ink'?'black':c)+' pen"><i style="background:'+(c==='ink'?'var(--ink)':SP_COL[c])+'"></i></button>'; }).join('')+
    '<button type="button" class="sp-tool" data-t="erase" title="Eraser">🧽</button><button type="button" class="sp-tool" data-t="size" title="Pen size">●</button><button type="button" class="sp-tool" data-t="scroll" title="Pause drawing to scroll or answer">✋</button>'+
    '<button type="button" class="sp-tool" data-t="clear" title="Clear page">🗑</button><button type="button" class="sp-tool" data-t="close" title="Close scratchpad">✕</button>';
  document.body.appendChild(bar);
  bar.addEventListener('click',function(e){ var b=e.target.closest('button'); if(!b) return;
    if(b.dataset.c){ SP.color=b.dataset.c; SP.erase=false; SP.draw=true; }
    else if(b.dataset.t==='erase'){ SP.erase=true; SP.draw=true; }
    else if(b.dataset.t==='size'){ SP.size = SP.size===3?6:(SP.size===6?1.5:3); b.textContent = SP.size===6?'⬤':(SP.size===1.5?'·':'●'); }
    else if(b.dataset.t==='scroll'){ SP.draw=!SP.draw; }
    else if(b.dataset.t==='clear'){ spClear(); }
    else if(b.dataset.t==='close'){ spToggle(false); return; }
    spUI(); });
  SP.cv=cv; SP.ctx=cv.getContext('2d');
  cv.addEventListener('pointerdown',function(e){ if(!SP.draw) return; e.preventDefault(); cv.setPointerCapture(e.pointerId); SP.down=true; SP.last=spPt(e); spDot(SP.last); });
  cv.addEventListener('pointermove',function(e){ if(!SP.down) return; e.preventDefault(); var p=spPt(e); spLine(SP.last,p); SP.last=p; });
  var up=function(){ if(SP.down){ SP.down=false; spSave(); } };
  cv.addEventListener('pointerup',up); cv.addEventListener('pointercancel',up); cv.addEventListener('pointerleave',up);
  window.addEventListener('resize',function(){ if(SP.on) spFit(true); });
}
function spPt(e){ var r=SP.cv.getBoundingClientRect(); return {x:e.clientX-r.left, y:e.clientY-r.top}; }
function spStyle(){ var c=SP.ctx; c.lineCap='round'; c.lineJoin='round'; c.globalCompositeOperation=SP.erase?'destination-out':'source-over'; c.strokeStyle=c.fillStyle=(SP.color==='ink'?spInk():SP_COL[SP.color]); c.lineWidth=SP.erase?22:SP.size; }
function spDot(p){ spStyle(); var c=SP.ctx; c.beginPath(); c.arc(p.x,p.y,(SP.erase?11:SP.size/2),0,Math.PI*2); c.fill(); }
function spLine(a,b){ spStyle(); var c=SP.ctx; c.beginPath(); c.moveTo(a.x,a.y); c.lineTo(b.x,b.y); c.stroke(); }
function spSave(){ if(SP.key&&SP.cv){ try{ SP.store[SP.key]=SP.cv.toDataURL(); }catch(e){} } }
function spClear(){ if(!SP.ctx) return; SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.clearRect(0,0,SP.cv.width,SP.cv.height); SP.ctx.restore(); if(SP.key) delete SP.store[SP.key]; }
function spFit(keep){
  var wrap=document.getElementById('wrap'); if(!wrap||!SP.cv) return;
  var r=wrap.getBoundingClientRect(), top=r.top+window.scrollY, h=Math.max(wrap.scrollHeight, window.innerHeight-r.top)+40, w=document.documentElement.clientWidth;
  var old=keep&&SP.key?SP.store[SP.key]:null, dpr=window.devicePixelRatio||1;
  SP.cv.style.top=top+'px'; SP.cv.style.left='0px'; SP.cv.style.width=w+'px'; SP.cv.style.height=h+'px';
  SP.cv.width=Math.round(w*dpr); SP.cv.height=Math.round(h*dpr); SP.ctx.setTransform(dpr,0,0,dpr,0,0);
  if(old){ var im=new Image(); im.onload=function(){ SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.drawImage(im,0,0); SP.ctx.restore(); }; im.src=old; }
}
function spLoad(){ spSave(); SP.key=spKey(); spFit(false); var d=SP.key&&SP.store[SP.key]; if(d){ var im=new Image(); im.onload=function(){ SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.drawImage(im,0,0); SP.ctx.restore(); }; im.src=d; } }
function spUI(){
  var bar=document.getElementById('spBar'); if(!bar) return;
  bar.querySelectorAll('.sp-pen').forEach(function(b){ b.classList.toggle('on', !SP.erase && SP.draw && b.dataset.c===SP.color); });
  bar.querySelector('[data-t=erase]').classList.toggle('on', SP.erase && SP.draw);
  bar.querySelector('[data-t=scroll]').classList.toggle('on', !SP.draw);
  SP.cv.classList.toggle('passive', !SP.draw);
  var fb=document.getElementById('spFab'); if(fb) fb.classList.toggle('on',SP.on);
}
function spToggle(on){
  spBuild(); SP.on=(on===undefined)?!SP.on:on;
  document.body.classList.toggle('sp-open',SP.on); SP.cv.style.display=SP.on?'block':'none'; document.getElementById('spBar').style.display=SP.on?'flex':'none';
  if(SP.on){ SP.draw=true; SP.erase=false; spLoad(); if(typeof kbHide==='function') kbHide(); } else { spSave(); }
  spUI();
}
(function(){ var f=document.createElement('button'); f.type='button'; f.id='spFab'; f.className='sp-fab'; f.innerHTML='✏️ <span>Scratchpad</span>'; f.title='Open a scratchpad to write your working'; f.addEventListener('click',function(){ spToggle(); }); document.body.appendChild(f); })();
var _rsSP = renderSlide;
renderSlide = function(){ _rsSP(); var fab=document.getElementById('spFab'); var q=!!swTab(); if(fab) fab.style.display=q?'':'none'; if(!q && SP.on) spToggle(false); if(SP.on) setTimeout(spLoad,30); };


/* ================= v4: attempt classification ================= */
function v4Class(item){
  if(!item) return 'un';
  if(item.status==='skipped') return 'sk';
  if(item.status==='unanswered') return 'un';
  if(item.stepStates){ // step question
    if(item.status!=='correct' && item.status!=='revealed') return 'un';
    if(item.status==='revealed' || item.stepStates.some(function(s){return s.status==='revealed';})) return 'w';
    return item.stepStates.some(function(s){return (s.attempts||0)>0;}) ? 'c2' : 'c1';
  }
  if(item.status==='revealed') return 'w';
  if(item.status==='correct') return (item.attempts||0)>0 ? 'c2' : 'c1';
  if(item.status==='wrong'||item.status==='incorrect') return 'w';
  return 'un';
}
function v4Counts(items){ var c={n:items.length,c1:0,c2:0,w:0,sk:0,un:0}; items.forEach(function(it){ c[v4Class(it)]++; }); return c; }

/* ================= v4: My record with attempt columns ================= */
renderRecord = function(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var title=(document.querySelector('.chapter-title')||{}).textContent||'';
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+(title?' · '+esc(title):'')+'</p>';
  var st=appState.learning;
  h+='<h3>📘 Learning Sheet — attempts</h3><p class="v4leg"><b>1st ✓</b> correct on the first attempt · <b>2nd ✓</b> correct on the second attempt · <b>Wrong</b> still wrong after two attempts (answer revealed) · <b>Skip</b> skipped<span class="v4left"> · <b>Left</b> not done yet</span></p>';
  if(!st){ h+='<p class="rec-empty">Not started yet.</p>'; }
  else {
    var T={n:0,c1:0,c2:0,w:0,sk:0,un:0};
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>Sheet</th><th>Qs</th><th>1st ✓</th><th>2nd ✓</th><th>Wrong</th><th>Skip</th><th class="v4left">Left</th></tr></thead><tbody>';
    TAB_DEFS.forEach(function(td){ var tt=st.tabs[td.id]; if(!tt||!tt.items||!tt.items.length) return; var c=v4Counts(tt.items);
      ['n','c1','c2','w','sk','un'].forEach(function(k){ T[k]+=c[k]; });
      h+='<tr><td>'+td.label+'</td><td>'+c.n+'</td><td class="v4g">'+c.c1+'</td><td class="v4o">'+c.c2+'</td><td class="v4r">'+c.w+'</td><td>'+c.sk+'</td><td class="v4left">'+c.un+'</td></tr>'; });
    h+='<tr class="v4tot"><td>Total</td><td>'+T.n+'</td><td class="v4g">'+T.c1+'</td><td class="v4o">'+T.c2+'</td><td class="v4r">'+T.w+'</td><td>'+T.sk+'</td><td class="v4left">'+T.un+'</td></tr>';
    h+='</tbody></table></div>';
    var doneN=T.c1+T.c2+T.w; if(doneN){ h+='<p class="v4sum">Of '+doneN+' questions answered: <b>'+Math.round(T.c1/doneN*100)+'%</b> right first time, <b>'+Math.round(T.c2/doneN*100)+'%</b> right on the second try, <b>'+Math.round(T.w/doneN*100)+'%</b> still wrong after two tries.</p>'; }
  }
  var q=appState.quiz;
  h+='<h3>📝 Quiz Mode</h3>';
  if(!q){ h+='<p class="rec-empty">Not started yet.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>Sheet</th><th>Qs</th><th>Status</th><th>Correct</th><th>Wrong</th></tr></thead><tbody>';
    TAB_DEFS.forEach(function(td){ var tt=q.tabs[td.id]; if(!tt||!tt.items||!tt.items.length) return; var n=tt.items.length, cor=0, att=0;
      tt.items.forEach(function(it){ if(it.status!=='unanswered'||it.choice!==undefined) att++; });
      var rec=records.filter(function(r){ return r.mode==='quiz'&&r.tab===td.id; })[0];
      if(rec){ cor=rec.correct; att=Math.max(att,rec.total); }
      h+='<tr><td>'+td.label+'</td><td>'+n+'</td><td>'+(rec?'Finished':att+' / '+n)+'</td><td class="v4g">'+(rec?cor:'—')+'</td><td class="v4r">'+(rec?(rec.total-cor):'—')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><div class="rec-card"><h3>Finished sheets (latest first)</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sheets finished yet. Each time you finish a sheet, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>When</th><th>Mode</th><th>Sheet</th><th>Score</th><th>1st ✓</th><th>2nd ✓</th><th>Wrong</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+'</td><td>'+(r.c1!=null?r.c1:'—')+'</td><td>'+(r.c2!=null?r.c2:'—')+'</td><td>'+(r.w!=null?r.w:(r.mode==='quiz'?r.total-r.correct:'—'))+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){ if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker(); });
  window.scrollTo({top:0});
};
var _v4add = addRecord;
addRecord = function(mode, tabId, correct, revealed, skipped, total){
  _v4add(mode, tabId, correct, revealed, skipped, total);
  try{ if(mode==='learning'&&records[0]){ var c=v4Counts(state.tabs[tabId].items); records[0].c1=c.c1; records[0].c2=c.c2; records[0].w=c.w; saveState(); } }catch(e){}
};

/* ================= v4: celebration ================= */
function v4Cracker(){
  var ctx=ensureAudio(); if(!ctx) return; try{ if(ctx.state==='suspended') ctx.resume(); }catch(e){}
  var now=ctx.currentTime;
  function pop(t, vol, dur, hp){
    var len=Math.floor(ctx.sampleRate*dur), buf=ctx.createBuffer(1,len,ctx.sampleRate), d=buf.getChannelData(0);
    for(var i=0;i<len;i++){ d[i]=(Math.random()*2-1)*Math.pow(1-i/len,3); }
    var src=ctx.createBufferSource(); src.buffer=buf;
    var f=ctx.createBiquadFilter(); f.type='highpass'; f.frequency.value=hp;
    var g=ctx.createGain(); g.gain.setValueAtTime(vol,t); g.gain.exponentialRampToValueAtTime(0.001,t+dur);
    src.connect(f); f.connect(g); g.connect(ctx.destination); src.start(t); src.stop(t+dur+0.02);
  }
  pop(now,0.9,0.35,300);                                   // big bang
  for(var k=0;k<14;k++){ pop(now+0.35+Math.random()*1.3, 0.25+Math.random()*0.35, 0.05+Math.random()*0.08, 1500+Math.random()*2500); } // crackles
  [523.25,659.25,783.99,1046.5].forEach(function(fq,i){ var o=ctx.createOscillator(), g=ctx.createGain(); o.type='triangle'; o.frequency.value=fq;
    var t=now+0.15+i*0.12; g.gain.setValueAtTime(0.0001,t); g.gain.exponentialRampToValueAtTime(0.18,t+0.03); g.gain.exponentialRampToValueAtTime(0.001,t+0.5);
    o.connect(g); g.connect(ctx.destination); o.start(t); o.stop(t+0.55); });
}
function v4Confetti(){
  var cv=document.createElement('canvas'); cv.className='v4conf'; document.body.appendChild(cv);
  var W=cv.width=window.innerWidth*(window.devicePixelRatio||1), H=cv.height=window.innerHeight*(window.devicePixelRatio||1), s=(window.devicePixelRatio||1);
  var ctx=cv.getContext('2d'), cols=['#e8b13a','#d9534f','#2e86de','#27ae60','#9b59b6','#f39c12','#1abc9c','#ff6b9a'], P=[];
  function burst(x,y,n){ for(var i=0;i<n;i++){ var a=Math.random()*Math.PI*2, v=(4+Math.random()*9)*s;
    P.push({x:x,y:y,vx:Math.cos(a)*v,vy:Math.sin(a)*v-6*s,w:(6+Math.random()*7)*s,h:(4+Math.random()*5)*s,r:Math.random()*6,vr:(Math.random()-.5)*.4,c:cols[i%cols.length],life:0,flyer:Math.random()<.25}); } }
  burst(W*0.2,H*0.35,90); burst(W*0.8,H*0.35,90); setTimeout(function(){ burst(W*0.5,H*0.25,120); },380); setTimeout(function(){ burst(W*0.35,H*0.3,70); burst(W*0.65,H*0.3,70); },800);
  var t0=performance.now();
  (function frame(t){
    ctx.clearRect(0,0,W,H);
    P.forEach(function(p){ p.vy+=0.22*s; p.vx*=0.985; p.vy*=0.985; p.x+=p.vx; p.y+=p.vy; p.r+=p.vr; p.life++;
      ctx.save(); ctx.translate(p.x,p.y); ctx.rotate(p.r); ctx.fillStyle=p.c;
      if(p.flyer){ ctx.fillRect(-p.w*1.4,-1.5*s,p.w*2.8,3*s); } else { ctx.fillRect(-p.w/2,-p.h/2,p.w,p.h*Math.abs(Math.cos(p.life/6))); }
      ctx.restore(); });
    if(t-t0<4200) requestAnimationFrame(frame); else cv.remove();
  })(t0);
}
function v4NextTab(){
  var i=TAB_DEFS.findIndex(function(t){return t.id===activeTab;});
  for(var j=i+1;j<TAB_DEFS.length;j++){ var id=TAB_DEFS[j].id; if(id!=='theory' && SLIDES[id] && SLIDES[id].length) return TAB_DEFS[j]; }
  return null;
}
function v4Celebrate(){
  var done=document.querySelector('#wrap .done-card'); if(!done || done.dataset.v4) return; done.dataset.v4='1';
  var ts=state.tabs[activeTab], c=v4Counts(ts.items), n=ts.items.length;
  var first=(student&&student.name)?String(student.name).split(' ')[0]:'';
  var pct=MODE==='quiz'?null:Math.round((c.c1+c.c2)/Math.max(n,1)*100);
  var msg = pct===null ? 'You finished this sheet!' : (pct>=90?'Outstanding work!':pct>=75?'Excellent effort!':pct>=50?'Well done — keep going!':'Great persistence — every try makes you stronger!');
  var banner=document.createElement('div'); banner.className='v4ban';
  banner.innerHTML='<div class="v4trophy">🏆</div><div class="v4h">Congratulations'+(first?', '+esc(first):'')+'!</div><div class="v4m">'+msg+'</div>'+
    (MODE==='quiz'?'':'<div class="v4pills"><span class="v4p g">✅ '+c.c1+' first attempt</span><span class="v4p o">🔁 '+c.c2+' second attempt</span><span class="v4p r">❌ '+c.w+' finally wrong</span>'+(c.sk?'<span class="v4p s">⏭ '+c.sk+' skipped</span>':'')+'</div>');
  done.insertBefore(banner, done.firstChild);
  var nx=v4NextTab(), wrapB=document.createElement('div'); wrapB.className='v4next';
  if(nx){ wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">Next sheet: '+nx.label+' →</button>'; }
  else if(SLIDES.report!==undefined || TAB_DEFS.some(function(t){return t.id==='report';})){ wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">📊 View my report →</button>'; }
  else { wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">⌂ Back to the home page</button>'; }
  banner.appendChild(wrapB);
  document.getElementById('v4Next').addEventListener('click',function(){
    var t=nx?nx.id:(TAB_DEFS.some(function(x){return x.id==='report';})?'report':(TAB_DEFS[0]&&TAB_DEFS[0].id));
    activeTab=t; showChrome(true); buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  setTimeout(function(){ var r=banner.getBoundingClientRect(); window.scrollBy({top:r.top-110,behavior:'smooth'}); },60);
  v4Confetti(); v4Cracker();
}
var _v4rf = renderFinished;
renderFinished = function(){ _v4rf.apply(this,arguments); try{ v4Celebrate(); }catch(e){ console.log('v4',e); } };


/* ================= calculus answer mode ================= */
function calcCompile(src){
  var s=String(src).replace(/\s+/g,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/π/g,'#').replace(/eˣ/g,'e^x');
  if(s.indexOf('=')>=0) s=s.slice(s.lastIndexOf('=')+1);
  var FN=['sqrt','cbrt','abs','ln','log','exp','sin','cos','tan','sec','csc','cot','pi'];
  var i=0,toks=[];
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length&&/[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(ch==='√'){ toks.push({k:'f',v:'sqrt'}); i++; continue; }
    if(ch==='∛'){ toks.push({k:'f',v:'cbrt'}); i++; continue; }
    if(/[a-zA-Z#]/.test(ch)){
      var hit=null; for(var q=0;q<FN.length;q++){ if(s.substr(i,FN[q].length).toLowerCase()===FN[q]){ hit=FN[q]; break; } }
      if(hit==='pi'){ toks.push({k:'v',v:'#'}); i+=2; continue; }
      if(hit){ toks.push({k:'f',v:hit}); i+=hit.length; continue; }
      toks.push({k:'v',v:ch}); i++; continue; }
    if('+-*/^()|'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  // absolute value bars -> abs( )
  var t2=[],open=false; for(var a=0;a<toks.length;a++){ var tk=toks[a]; if(tk.k==='|'){ if(!open){ t2.push({k:'f',v:'abs'}); t2.push({k:'('}); open=true; } else { t2.push({k:')'}); open=false; } } else t2.push(tk); }
  toks=t2;
  var out=[];
  for(var t=0;t<toks.length;t++){ var A=toks[t], B=out[out.length-1];
    if(B&&(B.k==='n'||B.k==='v'||B.k===')')&&(A.k==='n'||A.k==='v'||A.k==='('||A.k==='f')) out.push({k:'&'});
    out.push(A); }
  var p=0; function pk(){ return out[p]; }
  var F={sqrt:Math.sqrt,cbrt:Math.cbrt,ln:Math.log,log:function(x){return Math.log(x)/Math.LN10;},exp:Math.exp,sin:Math.sin,cos:Math.cos,tan:Math.tan,
    sec:function(x){return 1/Math.cos(x);},csc:function(x){return 1/Math.sin(x);},cot:function(x){return 1/Math.tan(x);},abs:Math.abs};
  function E(){ var n=T(); while(pk()&&(pk().k==='+'||pk().k==='-')){ var o=out[p++].k,r=T(); n=(function(l,r,o){return function(e){return o==='+'?l(e)+r(e):l(e)-r(e);};})(n,r,o);} return n; }
  function T(){ var n=I(); while(pk()&&(pk().k==='*'||pk().k==='/')){ var o=out[p++].k,r=I(); n=(function(l,r,o){return function(e){return o==='*'?l(e)*r(e):l(e)/r(e);};})(n,r,o);} return n; }
  function I(){ var n=U(); while(pk()&&pk().k==='&'){ p++; var r=P(); n=(function(l,r){return function(e){return l(e)*r(e);};})(n,r);} return n; }
  function U(){ if(pk()&&pk().k==='-'){ p++; var u=U(); return function(e){return -u(e);}; } if(pk()&&pk().k==='+'){ p++; return U(); } return P(); }
  function P(){ var b=Aa(); if(pk()&&pk().k==='^'){ p++; var x=U(); return function(e){return Math.pow(b(e),x(e));}; } return b; }
  function Aa(){ var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){return t.v;};
    if(t.k==='v'){ if(t.v==='#') return function(){return Math.PI;}; if(t.v==='e') return function(){return Math.E;}; return function(e){return e[t.v];}; }
    if(t.k==='('){ var n=E(); if(!pk()||pk().k!==')') throw 0; p++; return n; }
    if(t.k==='f'){ var fn=F[t.v]; var ex=null;
      if(pk()&&pk().k==='^'){ p++; ex=Aa(); if(pk()&&pk().k==='&') p++; }            // sin^2(x)
      var arg; if(pk()&&pk().k==='('){ p++; arg=E(); if(!pk()||pk().k!==')') throw 0; p++; } else { arg=P(); while(pk()&&pk().k==='&'&&out[p+1]&&(out[p+1].k==='n'||(out[p+1].k==='v'&&out[p+1].v!=='e'))){ p++; var nx=P(); arg=(function(l,r){return function(e){return l(e)*r(e);};})(arg,nx); } }
      return ex? function(e){ return Math.pow(fn(arg(e)),ex(e)); } : function(e){ return fn(arg(e)); }; }
    throw 0; }
  try{ var f=E(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function calcEqual(input,answer){
  var f=calcCompile(input), g=calcCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<14;trial++){
    var env={}; 'abcdfghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=0.35+Math.random()*2.3; });
    var x=f(env), y=g(env); if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-6*Math.max(1,Math.abs(x),Math.abs(y))) return false; hits++;
  }
  return hits>=4;
}
(function(){
  var _am=answerMatches;
  answerMatches=function(input,answer,accept,expr){
    if(expr==='calc'){ if(input===undefined||input===null||String(input).trim()==='') return false;
      if(calcEqual(input,answer)) return true; return (accept||[]).some(function(a){ return calcEqual(input,a); }); }
    return _am.apply(this,arguments); };
  var _kl=kbLayoutFor;
  kbLayoutFor=function(inp){ try{ var ts=state.tabs[activeTab], sl=SLIDES[activeTab][ts.idx], stp=sl.flat[parseInt(inp.dataset.step,10)]; if(stp.expr==='calc') return 'calc'; }catch(e){} return _kl(inp); };
  var _kp=kbPress;
  kbPress=function(k){ var m={'eˣ':'e^(','√':'√(','ln':'ln(','sin':'sin(','cos':'cos(','tan':'tan('}; if(KB.page==='calc'&&m[k]){ kbInsert(m[k]); return; } return _kp(k); };
})();

renderLogin();
})();
</script>
</body>
</html>
