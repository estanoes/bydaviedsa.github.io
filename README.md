<!DOCTYPE html>
<html lang="es">
<head>
<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-M6QXQMHP');</script>
<!-- End Google Tag Manager -->
<meta charset="UTF-8">
<title>bydavi roblox · Hub de fans</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
  :root{
    --bg1:#0b0d12; --bg2:#151827;
    --accent:#ff2d55; --accent2:#00b06b;
    --text:#f5f6fa; --sub:#9aa0ac; --card:#1a1d29;
  }
  *{box-sizing:border-box;}
  body{
    margin:0;min-height:100vh;
    background:
      radial-gradient(circle at 85% 0%, rgba(255,45,85,0.12), transparent 40%),
      radial-gradient(circle at 10% 90%, rgba(0,176,107,0.10), transparent 45%),
      linear-gradient(160deg, var(--bg1), var(--bg2));
    font-family:'Segoe UI', Roboto, Arial, sans-serif;
    color:var(--text);
    padding:28px 20px 80px;
  }
  a{color:#7fb8ff;}
  .wrap{max-width:1300px;margin:0 auto;}
  .layout{display:grid;grid-template-columns:1fr 300px;gap:24px;align-items:start;}
  .main-col{min-width:0;}
  .achievements{position:sticky;top:20px;background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:18px;padding:20px 22px;height:fit-content;}
  .achievements h3{margin:0 0 4px;font-size:15px;}
  .achievements .ach-desc{font-size:12px;color:var(--sub);margin-bottom:14px;}
  .ach-item{display:flex;align-items:center;gap:12px;padding:11px 0;border-bottom:1px solid rgba(255,255,255,0.06);}
  .ach-item:last-child{border-bottom:none;}
  .ach-icon{width:36px;height:36px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:17px;flex-shrink:0;background:rgba(255,255,255,0.06);}
  .ach-item.unlocked .ach-icon{background:linear-gradient(135deg,var(--accent),#ff5f7e);}
  .ach-item.locked{opacity:.5;}
  .ach-item.next{opacity:1;}
  .ach-name{font-weight:600;font-size:13.5px;}
  .ach-sub{font-size:11px;color:var(--sub);margin-top:2px;}
  .ach-bar{margin-top:6px;height:5px;border-radius:3px;background:rgba(255,255,255,0.08);overflow:hidden;}
  .ach-bar-fill{height:100%;background:linear-gradient(90deg,var(--accent),#ff5f7e);border-radius:3px;}
  @media (max-width: 860px){
    .layout{grid-template-columns:1fr;}
    .achievements{position:static;order:-1;}
  }

  header{
    display:flex;align-items:center;gap:18px;
    background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);
    border-radius:18px;padding:20px 24px;margin-bottom:26px;flex-wrap:wrap;
  }
  .avatar{
    position:relative;
    width:64px;height:64px;border-radius:50%;flex-shrink:0;
    background:linear-gradient(135deg,var(--accent),var(--accent2));
    display:flex;align-items:center;justify-content:center;font-weight:700;font-size:24px;color:#fff;
    overflow:hidden;
  }
  .avatar img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:none;z-index:1;}
  header h1{margin:0;font-size:22px;}
  header .handle{color:var(--sub);font-size:13px;}
  .headinfo{flex:1;min-width:180px;}
  .subs{margin-left:auto;text-align:right;}
  .subs .n{font-size:26px;font-weight:800;font-variant-numeric:tabular-nums;}
  .subs .l{font-size:11px;letter-spacing:1.5px;text-transform:uppercase;color:var(--sub);}
  .subbtn{
    margin-left:auto;background:var(--accent);color:#fff;text-decoration:none;
    padding:11px 20px;border-radius:999px;font-weight:700;font-size:13.5px;white-space:nowrap;
    box-shadow:0 6px 18px rgba(255,45,85,0.35);
  }
  .subbtn:hover{filter:brightness(1.08);}

  .live-banner{
    display:flex;align-items:center;gap:10px;background:rgba(255,45,85,0.1);
    border:1px solid rgba(255,45,85,0.35);border-radius:12px;padding:10px 16px;margin-bottom:16px;
    font-size:13.5px;font-weight:600;
  }
  .live-banner .reddot{width:9px;height:9px;border-radius:50%;background:var(--accent);animation:pulse 1.2s infinite;}
  .live-wrap{display:flex;gap:16px;flex-wrap:wrap;}
  .live-video{flex:2;min-width:320px;}
  .live-video iframe{width:100%;aspect-ratio:16/9;border:none;border-radius:12px;}
  .live-chat{flex:1;min-width:300px;}
  .live-chat iframe{width:100%;height:500px;border:none;border-radius:12px;background:#0e0e0e;}
  .live-chat .fallback{font-size:12px;color:var(--sub);margin-top:8px;text-align:center;}
  @keyframes pulse{0%,100%{opacity:1;}50%{opacity:.35;}}
  .notlive{text-align:center;padding:30px 10px;color:var(--sub);}
  .notlive .big{font-size:16px;color:var(--text);margin-bottom:6px;}

  .tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:22px;}
  .tab{
    padding:9px 15px;border-radius:999px;border:1px solid rgba(255,255,255,0.12);
    background:rgba(255,255,255,0.03);color:var(--sub);cursor:pointer;font-size:13px;font-weight:600;
  }
  .tab.active{background:linear-gradient(135deg,var(--accent),#ff5f7e);color:#fff;border-color:transparent;}

  .game{display:none;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.07);border-radius:18px;padding:26px;}
  .game.active{display:block;}
  .game h2{margin:0 0 4px;font-size:18px;}
  .game .desc{color:var(--sub);font-size:13px;margin-bottom:18px;}
  .scoreline{font-size:13px;color:var(--accent2);margin-bottom:16px;font-weight:600;}
  .scoreline b{font-size:19px;color:#fff;}

  .cards{display:flex;gap:14px;flex-wrap:wrap;}
  .vcard{
    flex:1;min-width:200px;background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.09);
    border-radius:14px;padding:10px;cursor:pointer;transition:transform .15s,border-color .15s;
  }
  .vcard:hover{transform:translateY(-3px);border-color:rgba(255,255,255,0.25);}
  .vcard img{width:100%;border-radius:8px;display:block;aspect-ratio:16/9;object-fit:cover;background:#222;}
  .vcard .t{font-size:12.5px;line-height:1.35;margin-top:8px;max-height:3.6em;overflow:hidden;}
  .vcard .v{font-size:12px;color:var(--sub);font-weight:600;margin-top:6px;}
  .vcard.correct{border-color:var(--accent2);box-shadow:0 0 0 2px rgba(0,176,107,0.35);}
  .vcard.wrong{border-color:var(--accent);box-shadow:0 0 0 2px rgba(255,45,85,0.35);}
  .vcard.disabled{pointer-events:none;opacity:.92;}
  .vs{display:flex;align-items:center;justify-content:center;font-size:12px;color:var(--sub);width:24px;flex-shrink:0;}

  .msg{margin-top:14px;font-size:13px;min-height:18px;}
  button.act{padding:10px 18px;border-radius:8px;border:none;cursor:pointer;font-weight:600;font-size:13.5px;background:linear-gradient(135deg,var(--accent),#ff5f7e);color:#fff;}
  button.act:disabled{opacity:.4;cursor:default;}

  .quiz-q{font-size:15px;margin-bottom:14px;}
  .quiz-opts{display:flex;flex-direction:column;gap:8px;max-width:460px;}
  .qopt{padding:11px 14px;border-radius:10px;border:1px solid rgba(255,255,255,0.12);background:rgba(255,255,255,0.03);cursor:pointer;font-size:13.5px;}
  .qopt:hover{border-color:rgba(255,255,255,0.3);}
  .qopt.correct{border-color:var(--accent2);background:rgba(0,176,107,0.12);}
  .qopt.wrong{border-color:var(--accent);background:rgba(255,45,85,0.12);}
  .qopt.disabled{pointer-events:none;}

  .memgrid{display:grid;grid-template-columns:repeat(auto-fill, minmax(90px,1fr));gap:10px;max-width:640px;}
  .mcard{aspect-ratio:1;border-radius:10px;background:#20232f;border:1px solid rgba(255,255,255,0.1);cursor:pointer;display:flex;align-items:center;justify-content:center;overflow:hidden;font-size:20px;color:var(--sub);}
  .mcard img{width:100%;height:100%;object-fit:cover;display:none;}
  .mcard.revealed img{display:block;}
  .mcard.revealed span{display:none;}
  .mcard.matched{border-color:var(--accent2);opacity:.55;pointer-events:none;}

  .blurcard{max-width:400px;}
  .blurcard img{width:100%;border-radius:12px;display:block;aspect-ratio:16/9;object-fit:cover;background:#222;transition:filter .5s ease;}
  .guessrow{display:flex;gap:8px;margin-top:14px;}
  .guessrow input[type=text]{flex:1;padding:10px 12px;border-radius:8px;border:1px solid rgba(255,255,255,0.15);background:#101320;color:var(--text);font-size:14px;}
  .attempts{font-size:12px;color:var(--sub);margin-top:8px;}

  .lb-box{margin-top:12px;max-width:360px;background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:12px;padding:10px 14px;}
  .lb-title{font-size:12px;font-weight:700;color:var(--sub);text-transform:uppercase;letter-spacing:.04em;margin-bottom:6px;}
  .lb-row{display:flex;align-items:center;gap:8px;font-size:13px;padding:3px 0;}
  .lb-row span:first-child{color:var(--sub);width:22px;flex-shrink:0;}
  .lb-row b{flex:1;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;}
  .lb-row.me{color:var(--accent2);}
  .lb-empty{font-size:12.5px;color:var(--sub);}

  .loading{color:var(--sub);font-size:13.5px;}
  .footer-note{margin-top:30px;font-size:11px;color:#5b606c;text-align:center;line-height:1.5;}
  .setup{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,0.6);backdrop-filter:blur(4px);z-index:50;}
  .card2{background:var(--card);border:1px solid rgba(255,255,255,0.08);border-radius:16px;padding:26px 28px;max-width:440px;}
  .card2 input{width:100%;margin:10px 0 14px;padding:10px 12px;border-radius:8px;border:1px solid rgba(255,255,255,0.15);background:#101320;color:var(--text);font-size:14px;}
  .card2 button{width:100%;}

  /* ===== Pantalla de inicio ===== */
  .intro{
    position:fixed;inset:0;z-index:100;display:flex;align-items:center;justify-content:center;
    padding:24px;
    background:
      radial-gradient(circle at 85% 0%, rgba(255,45,85,0.18), transparent 45%),
      radial-gradient(circle at 10% 90%, rgba(0,176,107,0.15), transparent 50%),
      linear-gradient(160deg, var(--bg1), var(--bg2));
  }
  .intro.hidden{display:none;}
  .intro-card{
    max-width:460px;width:100%;text-align:center;
    background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.09);
    border-radius:22px;padding:38px 30px 32px;
  }
  .intro-avatar{
    position:relative;overflow:hidden;
    width:76px;height:76px;border-radius:50%;margin:0 auto 16px;
    background:linear-gradient(135deg,var(--accent),var(--accent2));
    display:flex;align-items:center;justify-content:center;font-weight:700;font-size:30px;color:#fff;
  }
  .intro-avatar img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:none;z-index:1;}
  .intro-card h1{margin:0 0 6px;font-size:24px;}
  .intro-card p.sub{margin:0 0 26px;color:var(--sub);font-size:13.5px;}
  .intro-links{display:flex;flex-direction:column;gap:12px;margin-bottom:26px;}
  .intro-link{
    display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--text);
    padding:13px 16px;border-radius:12px;border:1px solid rgba(255,255,255,0.1);
    background:rgba(255,255,255,0.03);font-weight:600;font-size:14px;transition:transform .15s,border-color .15s;
  }
  .intro-link:hover{transform:translateY(-2px);border-color:rgba(255,255,255,0.3);}
  .intro-link .ic{
    width:34px;height:34px;border-radius:9px;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-size:17px;
  }
  .intro-link.discord .ic{background:#5865F2;color:#fff;}
  .intro-link.twitch .ic{background:#9146FF;color:#fff;}
  .intro-link.youtube .ic{background:#FF0000;color:#fff;}
  .intro-link .labels{display:flex;flex-direction:column;align-items:flex-start;gap:1px;}
  .intro-link .labels .l1{font-size:14px;}
  .intro-link .labels .l2{font-size:11.5px;color:var(--sub);font-weight:500;}
  .intro-enter{
    width:100%;border:none;cursor:pointer;padding:13px 18px;border-radius:999px;
    background:linear-gradient(135deg,var(--accent),#ff5f7e);color:#fff;font-weight:700;font-size:14.5px;
    box-shadow:0 8px 22px rgba(255,45,85,0.35);
  }
  .intro-enter:hover{filter:brightness(1.08);}
  .socialbar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:16px;}
  .socialbar a{
    display:flex;align-items:center;gap:7px;text-decoration:none;color:var(--text);
    padding:8px 13px;border-radius:999px;border:1px solid rgba(255,255,255,0.1);
    background:rgba(255,255,255,0.03);font-size:12.5px;font-weight:600;
  }
  .socialbar a:hover{border-color:rgba(255,255,255,0.3);}
  .socialbar .dot{width:8px;height:8px;border-radius:50%;flex-shrink:0;}
  .socialbar .discord .dot{background:#5865F2;}
  .socialbar .twitch .dot{background:#9146FF;}
  .socialbar .youtube .dot{background:#FF0000;}

  /* ===== Only davi ===== */
  .od-login{max-width:360px;margin:20px auto;text-align:center;}
  .od-login input{width:100%;margin:8px 0;padding:11px 14px;border-radius:10px;border:1px solid rgba(255,255,255,0.15);background:#101320;color:var(--text);font-size:14px;}
  .od-login button{width:100%;margin-top:6px;}
  .od-err{color:#ff6b6b;font-size:13px;margin-top:10px;min-height:18px;}

  .od-setup-row{display:flex;gap:10px;flex-wrap:wrap;margin:16px 0;}
  .od-setup-row input{flex:1;min-width:200px;padding:11px 14px;border-radius:10px;border:1px solid rgba(255,255,255,0.15);background:#101320;color:var(--text);font-size:14px;}
  button.act.secondary{background:rgba(255,255,255,0.08);}
  .od-status{background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:10px;padding:10px 14px;font-size:13.5px;margin-bottom:18px;}

  .od-columns{display:grid;grid-template-columns:1.2fr 1fr;gap:18px;}
  @media (max-width:720px){ .od-columns{grid-template-columns:1fr;} }
  .od-col h3{margin:0 0 10px;font-size:15px;display:flex;align-items:center;justify-content:space-between;gap:8px;}
  .od-feed-clear{background:none;border:1px solid rgba(255,255,255,0.2);color:var(--sub);font-size:11px;padding:4px 8px;border-radius:8px;cursor:pointer;}
  .od-feed-clear:hover{color:var(--text);border-color:rgba(255,255,255,0.4);}
  .od-feed{height:320px;overflow-y:auto;background:#0d0f16;border:1px solid rgba(255,255,255,0.08);border-radius:12px;padding:10px;display:flex;flex-direction:column-reverse;}
  .od-msg{padding:6px 4px;font-size:13px;border-bottom:1px solid rgba(255,255,255,0.05);}
  .od-msg.match{background:rgba(0,176,107,0.14);border-radius:6px;}
  .badge{display:inline-block;font-size:10.5px;font-weight:700;padding:2px 6px;border-radius:6px;margin-right:4px;vertical-align:middle;}
  .badge.yt{background:#FF0000;color:#fff;}
  .badge.tk{background:#010101;color:#fff;border:1px solid #444;}

  .od-participants{max-height:220px;overflow-y:auto;margin-bottom:14px;}
  .od-participant{padding:7px 4px;font-size:13.5px;border-bottom:1px solid rgba(255,255,255,0.05);}
  .od-empty{color:var(--sub);font-size:13px;padding:10px 0;}
  .winner-btn{width:100%;}
  .od-winner{margin-top:14px;text-align:center;min-height:20px;}
  .od-spin{font-size:18px;font-weight:700;opacity:0.7;}
  .od-winner-card{background:linear-gradient(135deg,rgba(255,45,85,0.18),rgba(0,176,107,0.15));border:1px solid rgba(255,255,255,0.15);border-radius:14px;padding:16px;font-size:16px;}
  .od-winner-msg{margin-top:6px;color:var(--sub);font-size:13px;font-style:italic;}

  .od-tiktok-add{margin-top:26px;padding-top:18px;border-top:1px solid rgba(255,255,255,0.08);}
  .od-tiktok-add h3{margin:0 0 6px;font-size:15px;}
  .desc.small{font-size:12px;}
  .od-tiktok-row{display:flex;gap:10px;flex-wrap:wrap;margin-top:10px;}
  .od-tiktok-row input{padding:10px 12px;border-radius:10px;border:1px solid rgba(255,255,255,0.15);background:#101320;color:var(--text);font-size:13.5px;}
  .od-tiktok-row input:first-child{flex:0 0 160px;}
  .od-tiktok-row input:nth-child(2){flex:1;min-width:150px;}

  .od-num-participants{max-height:200px;overflow-y:auto;margin-top:10px;}
  .od-num-participants .od-participant{display:flex;justify-content:space-between;align-items:center;}
  .od-num-results{margin-top:16px;}
  .od-num-ranking{margin-top:14px;display:flex;flex-direction:column;gap:8px;}
  .od-num-row{display:flex;align-items:center;gap:10px;flex-wrap:wrap;background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:10px;padding:8px 12px;font-size:13.5px;}
  .od-num-row span{color:var(--sub);}
  .od-num-tag{font-weight:700;color:var(--text);}
  .od-num-row.exact{background:linear-gradient(135deg,rgba(255,215,0,0.2),rgba(0,176,107,0.15));border-color:rgba(255,215,0,0.4);}
  .od-num-row.exact .od-num-tag{color:#ffd700;}
  .od-num-row.closest{border-color:rgba(0,176,107,0.4);}
  .od-num-row.farthest{opacity:0.7;}

  /* ===== Adaptación a móvil ===== */
  html{-webkit-text-size-adjust:100%;}
  body{overflow-x:hidden;}
  .setup{padding:16px;}
  .card2{width:100%;max-height:90vh;overflow-y:auto;}

  @media (hover:none){
    .vcard:hover, .intro-link:hover{transform:none;}
  }

  @media (max-width:860px){
    .achievements{order:2;position:static;margin-top:8px;}
  }

  @media (max-width:600px){
    body{padding:14px 12px 60px;}
    .socialbar{gap:6px;margin-bottom:12px;}
    .socialbar a{padding:7px 11px;font-size:12px;}

    header{padding:14px;gap:12px;margin-bottom:18px;border-radius:14px;}
    .avatar{width:52px;height:52px;font-size:20px;}
    header h1{font-size:18px;}
    .headinfo{min-width:0;flex:1 1 140px;}
    .subbtn{margin-left:0;padding:10px 16px;font-size:13px;flex:1 1 auto;text-align:center;}
    .subs{margin-left:0;text-align:right;flex:0 0 auto;}
    .subs .n{font-size:22px;}

    /* Pestañas: una sola fila deslizable con el dedo */
    .tabs{flex-wrap:nowrap;overflow-x:auto;-webkit-overflow-scrolling:touch;margin:0 -12px 16px;padding:2px 12px 8px;scrollbar-width:none;}
    .tabs::-webkit-scrollbar{display:none;}
    .tab{flex:0 0 auto;white-space:nowrap;padding:10px 14px;}

    .game{padding:16px 14px;border-radius:14px;}
    .game h2{font-size:16px;}
    .game .desc{font-size:12.5px;}

    /* Directo */
    .live-wrap{flex-direction:column;}
    .live-video, .live-chat{flex:1 1 auto;min-width:0;width:100%;}
    .live-chat iframe{height:380px;}
    .live-banner{font-size:12.5px;padding:9px 12px;}

    /* Duelos: los dos vídeos uno encima de otro */
    .cards{flex-direction:column;align-items:stretch;gap:8px;}
    .vcard{min-width:0;width:100%;}
    .vs{width:100%;height:20px;}
    .vcard .t{font-size:13px;}

    /* Quiz / título */
    .quiz-opts{max-width:100%;}
    .qopt{padding:13px 14px;}
    #titulo-area .vcard{max-width:100% !important;}

    /* Memoria: 3 columnas */
    .memgrid{grid-template-columns:repeat(3,1fr);gap:8px;max-width:100%;}

    /* Miniatura borrosa */
    .blurcard{max-width:100%;}
    .guessrow{flex-direction:column;}
    .guessrow input[type=text]{width:100%;}
    button.act{padding:12px 18px;}

    .lb-box{max-width:100%;}

    /* Only davi */
    .od-login{max-width:100%;}
    .od-setup-row{flex-direction:column;gap:8px;}
    .od-setup-row input, .od-setup-row button{width:100%;min-width:0;}
    .od-feed{height:260px;}
    .od-tiktok-row{flex-direction:column;}
    .od-tiktok-row input:first-child, .od-tiktok-row input:nth-child(2){flex:1 1 auto;width:100%;min-width:0;}

    /* Pantalla de inicio */
    .intro{padding:14px;overflow-y:auto;align-items:flex-start;}
    .intro-card{padding:28px 18px 24px;margin:auto 0;}
    .intro-card h1{font-size:22px;}

    .footer-note{font-size:10.5px;}
  }

  /* Evita el zoom automático de iOS al pulsar un campo de texto */
  @media (max-width:600px){
    input, textarea{font-size:16px !important;}
  }
</style>
</head>
<body>
<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-M6QXQMHP"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

<div class="intro" id="intro">
  <div class="intro-card">
    <div class="intro-avatar"><span id="introAvatarFallback">B</span><img id="introAvatarImg"></div>
    <h1>bydavi</h1>
    <p class="sub">Únete a la comunidad antes de entrar al hub</p>
    <div class="intro-links">
      <a class="intro-link discord" href="https://discord.gg/DgEzy3kdn" target="_blank" rel="noopener">
        <span class="ic">💬</span>
        <span class="labels"><span class="l1">Discord</span><span class="l2">Únete al servidor</span></span>
      </a>
      <a class="intro-link twitch" href="https://twitch.tv/bydavi64" target="_blank" rel="noopener">
        <span class="ic">🎮</span>
        <span class="labels"><span class="l1">Twitch</span><span class="l2">twitch.tv/bydavi64</span></span>
      </a>
      <a class="intro-link youtube" href="https://www.youtube.com/@bydavi_roblox" target="_blank" rel="noopener">
        <span class="ic">▶️</span>
        <span class="labels"><span class="l1">YouTube</span><span class="l2">@bydavi_roblox</span></span>
      </a>
    </div>
    <button class="intro-enter" onclick="document.getElementById('intro').classList.add('hidden')">Entrar a la web →</button>
  </div>
</div>

<div class="wrap">
  <div class="socialbar">
    <a class="discord" href="https://discord.gg/DgEzy3kdn" target="_blank" rel="noopener"><span class="dot"></span>Discord</a>
    <a class="twitch" href="https://twitch.tv/bydavi64" target="_blank" rel="noopener"><span class="dot"></span>Twitch</a>
    <a class="youtube" href="https://www.youtube.com/@bydavi_roblox" target="_blank" rel="noopener"><span class="dot"></span>YouTube</a>
  </div>

  <header>
    <div class="avatar" id="avatar"><span id="avatarFallback">B</span><img id="avatarImg"></div>
    <div class="headinfo">
      <h1 id="chname">bydavi roblox</h1>
      <div class="handle">@bydavi_roblox · <a href="https://www.youtube.com/@bydavi_roblox" target="_blank">Ver canal en YouTube ↗</a></div>
    </div>
    <a class="subbtn" href="https://www.youtube.com/channel/UCji4T495RXQCcQyaCz1Jfpw?sub_confirmation=1" target="_blank" rel="noopener">🔔 Suscribirse</a>
    <div class="subs">
      <div class="n" id="subCount">--</div>
      <div class="l">Suscriptores</div>
    </div>
  </header>

  <div class="layout">
  <div class="main-col">
  <div class="tabs">
    <div class="tab active" data-tab="directo">🔴 En directo</div>
    <div class="tab" data-tab="vistas">⚔️ Duelo de vistas</div>
    <div class="tab" data-tab="likes">👍 Duelo de likes</div>
    <div class="tab" data-tab="fecha">🗓️ ¿Cuál es más antiguo?</div>
    <div class="tab" data-tab="titulo">🧩 Completa el título</div>
    <div class="tab" data-tab="memoria">🖼️ Memoria de miniaturas</div>
    <div class="tab" data-tab="miniatura">🌫️ Miniatura borrosa</div>
    <div class="tab" data-tab="onlydavi">🔒 Only davi</div>
  </div>

  <section class="game active" id="game-directo">
    <h2>Directo del canal</h2>
    <div class="desc">Se comprueba automáticamente si bydavi está en directo entre las 18:00 y las 21:00 (hora de España).</div>
    <div id="directo-area" class="loading">Comprobando si está en directo…</div>
  </section>

  <section class="game" id="game-vistas">
    <h2>¿Cuál tiene más visitas?</h2>
    <div class="desc">Elige el vídeo que creas que tiene más reproducciones.</div>
    <div class="scoreline">Racha: <b id="vistas-streak">0</b> · Mejor: <b id="vistas-best">0</b></div>
    <div id="vistas-area" class="loading">Cargando vídeos…</div>
    <div class="msg" id="vistas-msg"></div>
    <div class="lb-box" id="lb-vistas"></div>
  </section>

  <section class="game" id="game-likes">
    <h2>¿Cuál tiene más likes?</h2>
    <div class="desc">Ahora no cuentan las visitas, cuentan los "me gusta" reales del vídeo.</div>
    <div class="scoreline">Racha: <b id="likes-streak">0</b> · Mejor: <b id="likes-best">0</b></div>
    <div id="likes-area" class="loading">Cargando vídeos…</div>
    <div class="msg" id="likes-msg"></div>
    <div class="lb-box" id="lb-likes"></div>
  </section>

  <section class="game" id="game-fecha">
    <h2>¿Cuál se subió antes?</h2>
    <div class="desc">Adivina cuál de los dos vídeos es más antiguo en el canal.</div>
    <div class="scoreline">Racha: <b id="fecha-streak">0</b> · Mejor: <b id="fecha-best">0</b></div>
    <div id="fecha-area" class="loading">Cargando vídeos…</div>
    <div class="msg" id="fecha-msg"></div>
    <div class="lb-box" id="lb-fecha"></div>
  </section>

  <section class="game" id="game-titulo">
    <h2>Completa el título real</h2>
    <div class="desc">Falta una palabra en el título de un vídeo de verdad del canal. Elige cuál es.</div>
    <div class="scoreline">Racha: <b id="titulo-streak">0</b> · Mejor: <b id="titulo-best">0</b></div>
    <div id="titulo-area" class="loading">Cargando títulos…</div>
    <div class="msg" id="titulo-msg"></div>
    <div class="lb-box" id="lb-titulo"></div>
  </section>

  <section class="game" id="game-memoria">
    <h2>Memoria de miniaturas</h2>
    <div class="desc">Encuentra las parejas de miniaturas reales del canal con el menor número de intentos.</div>
    <div class="scoreline">Intentos: <b id="mem-moves">0</b> · Parejas: <b id="mem-found">0</b>/<b id="mem-total">0</b></div>
    <div id="memoria-area" class="loading">Cargando miniaturas…</div>
    <div class="msg" id="memoria-msg"></div>
  </section>

  <section class="game" id="game-miniatura">
    <h2>Miniatura borrosa</h2>
    <div class="desc">Adivina el título del vídeo (vale con que sea aproximado) a partir de su miniatura. Cada fallo la desenfoca un poco menos.</div>
    <div class="scoreline">Racha: <b id="mini-streak">0</b> · Mejor: <b id="mini-best">0</b></div>
    <div id="miniatura-area" class="loading">Cargando miniaturas…</div>
    <div class="msg" id="mini-msg"></div>
    <div class="lb-box" id="lb-miniatura"></div>
  </section>

  <section class="game" id="game-onlydavi">
    <div id="odLogin" class="od-login">
      <h2>🔒 Only davi</h2>
      <div class="desc">Zona privada. Introduce tus credenciales para entrar.</div>
      <input id="odUser" type="text" placeholder="Usuario" autocomplete="off">
      <input id="odPass" type="password" placeholder="Contraseña" autocomplete="off">
      <button class="act" onclick="tryOnlyDaviLogin()">Entrar</button>
      <div class="od-err" id="odLoginErr"></div>
    </div>

    <div id="odPanel" style="display:none;">
      <h2>🎁 Detector de sorteos — chat en vivo</h2>
      <div class="desc">Detecta en tiempo real el chat de YouTube. Antes de arrancar cualquier sorteo, pulsa el botón de abajo para comprobar que estás en directo y conectar con el chat.</div>

      <div class="od-setup-row">
        <button class="act" id="odCheckLiveBtn" onclick="checkLiveManual()">🔴 Comprobar si estoy en directo</button>
      </div>
      <div class="od-status" id="odLiveCheckStatus">Todavía no se ha comprobado. Pulsa el botón antes de iniciar un sorteo.</div>

      <div class="od-setup-row">
        <input id="odKeyword" type="text" placeholder="Palabra clave del sorteo (ej: SORTEO)">
        <button class="act" onclick="startGiveaway()">▶️ Iniciar sorteo</button>
        <button class="act secondary" onclick="resetGiveaway()">🔄 Reiniciar</button>
      </div>
      <div class="od-status" id="odStatus">Sorteo detenido. Escribe una palabra clave y pulsa "Iniciar sorteo".</div>

      <div class="od-columns">
        <div class="od-col">
          <h3>Chat en directo (YouTube) <button class="od-feed-clear" id="odFeedClearBtn" onclick="clearFeedFilter()" style="display:none;">Ver chat completo</button></h3>
          <div class="od-feed" id="odFeed"></div>
        </div>
        <div class="od-col">
          <h3>Participantes válidos (<span id="odCount">0</span>)</h3>
          <div class="od-participants" id="odParticipants"><div class="od-empty">Nadie ha escrito la palabra clave todavía.</div></div>
          <button class="act winner-btn" onclick="pickWinner()">🎲 Elegir ganador</button>
          <div class="od-winner" id="odWinner"></div>
        </div>
      </div>

      <div class="od-tiktok-add">
        <h3>🔢 Sorteo "Adivina el número"</h3>
        <div class="desc small">Pon (opcional) un rango mínimo/máximo — por defecto 1 a 100 — y pulsa "Iniciar sorteo de número". Al empezar, la web elige un número al azar dentro del rango y lo guarda oculto: ni tú lo ves. Se conecta al chat en vivo de YouTube y el primero que escriba exactamente ese número gana; en ese momento se te revela el número y el ganador.</div>
        <div class="od-setup-row">
          <input id="odNumMin" type="number" step="1" placeholder="Número mínimo (ej: 1)">
          <input id="odNumMax" type="number" step="1" placeholder="Número máximo (ej: 100)">
          <button class="act" onclick="startNumberGame()">▶️ Iniciar sorteo de número</button>
          <button class="act secondary" onclick="resetNumberGame()">🔄 Reiniciar</button>
        </div>
        <div class="od-status" id="odNumStatus">Sorteo de número detenido. Pulsa "Iniciar sorteo de número".</div>
        <h3 style="margin-top:16px;">Intentos (<span id="odNumCount">0</span>)</h3>
        <div class="od-num-participants" id="odNumParticipants"><div class="od-empty">Todavía no hay intentos.</div></div>
        <div class="od-num-results" id="odNumResults"></div>
      </div>

      <div class="od-tiktok-add">
        <h3>🕵️ Sorteo "Riddle" (palabra oculta)</h3>
        <div class="desc small">Escribe una palabra secreta: no se muestra en la pantalla, se queda oculta. Se conecta solo al chat en directo de YouTube y en cuanto alguien la escriba exactamente, esa persona gana al instante. La palabra no se revela hasta que aparece el ganador.</div>
        <div class="od-setup-row">
          <input id="odRiddleWord" type="password" placeholder="Palabra secreta" autocomplete="off">
          <button class="act" onclick="startRiddle()">▶️ Iniciar riddle</button>
          <button class="act secondary" onclick="resetRiddle()">🔄 Reiniciar</button>
        </div>
        <div class="od-status" id="odRiddleStatus">Riddle detenido. Escribe la palabra secreta y pulsa "Iniciar riddle".</div>
        <div class="od-winner" id="odRiddleWinner"></div>
      </div>
    </div>
  </section>

  <div class="footer-note">
    Todos los datos (vistas, likes, fechas, títulos) vienen en directo de la API oficial de YouTube.<br>
    El número de suscriptores está redondeado a 3 cifras si el canal supera 1.000 — así lo limita YouTube en toda su plataforma, no solo aquí.
  </div>
  </div>

  <aside class="achievements" id="achievements">
    <h3>🏅 Logros de suscriptores</h3>
    <div class="ach-desc">Se desbloquean solos según los suscriptores reales del canal.</div>
    <div class="ach-list" id="achList"><div class="lb-empty">Cargando…</div></div>
  </aside>
  </div>
</div>

<div class="setup" id="nameModal">
  <div class="card2">
    <h3 style="margin-top:0;">🏆 ¡Nuevo récord!</h3>
    <p style="font-size:13.5px;color:var(--sub);">Escribe un nombre para guardarlo en la tabla de mejores puntuaciones. Solo te lo pedimos esta vez: la web lo recordará en este navegador.</p>
    <input id="nameInput" type="text" maxlength="20" placeholder="Tu nombre o apodo" autocomplete="off">
    <button class="act" onclick="submitName()">Guardar y ver mi puntuación</button>
  </div>
</div>

<div class="setup" id="setup">
  <div class="card2">
    <h2 style="margin-top:0;">No se pudo conectar con la API</h2>
    <p id="setupReason" style="color:var(--sub);font-size:13px;">Cargando motivo…</p>
    <textarea id="apiKeyInput" placeholder="Pega aquí tu API key (o varias, una por línea, hasta 4, para que la web cambie sola a la siguiente si una se queda sin cuota)" autocomplete="off" rows="4" style="width:100%;padding:10px 12px;border-radius:10px;border:1px solid rgba(255,255,255,0.15);background:#101320;color:var(--text);font-size:13.5px;font-family:inherit;resize:vertical;"></textarea>
    <button class="act" onclick="saveKey()">Guardar y reintentar</button>
  </div>
</div>

<script>
const CHANNEL_ID = "UCji4T495RXQCcQyaCz1Jfpw";

/* ===== Reparto de claves de API =====
   - MINIGAME_API_KEYS: solo para cargar los minijuegos (vistas, likes, fecha, título, memoria, miniatura).
   - GIVEAWAY_API_KEYS: solo para el directo (banner) y los sorteos (número, riddle, palabra clave / chat en vivo).
   Cada grupo rota internamente si una clave se queda sin cuota, pero nunca se mezclan entre sí. */
const MINIGAME_API_KEYS = [
  "AIzaSyBPWaqVMfc2MGu8xQ775lTHZBIMhaiqjQI"
];
const GIVEAWAY_API_KEYS = [
  "AIzaSyDaHjbL1nxdG0c0qFMclfIwqYo8m0t8fbE",
  "AIzaSyBhm9Tc6COe2UVpnHrxnor6vQHoCOooGvY",
  "AIzaSyAID5_Ow9S8Qq7VErjD3a8q41NYJEHnU9Q",
  "AIzaSyClAFBfFQXc99o2ho-HEk3gMdmo78AP0L8",
  "AIzaSyCR8Cp1nHqhKMfl6ILroKPvqih1R5vfOTQ",
  "AIzaSyAoil2feAnk-jtGCiXtr7LbCVjycIb2D0Y",
  "AIzaSyAQq3QRU9Gh3nTbI-ikXlghIWEHyn3zOIc",
  "AIzaSyCwz_dWtAMUIMZ4LOwvM_nqyeQN_kvOOu4"
];

let videos = [];        // {id,title,thumb,views,likes,publishedAt}
const MAX_VIDEO_PAGES = 4; // 4 páginas x 50 = hasta 200 vídeos del canal

/* ===== Variedad: cada juego reparte los vídeos como un mazo barajado =====
   No se repite ningún vídeo hasta que se han usado todos, y nunca sale el mismo dos veces seguidas. */
const decks = {};
function shuffleArr(arr){
  const a = arr.slice();
  for(let i=a.length-1; i>0; i--){ const j = Math.floor(Math.random()*(i+1)); [a[i],a[j]] = [a[j],a[i]]; }
  return a;
}
function drawFromDeck(key, pool){
  let d = decks[key];
  if(!d) d = decks[key] = {ids:[], last:null, size:0};
  const poolIds = new Set(pool.map(v=>v.id));
  d.ids = d.ids.filter(id => poolIds.has(id));
  if(!d.ids.length){
    d.ids = shuffleArr([...poolIds]);
    if(d.ids.length>1 && d.ids[d.ids.length-1]===d.last){
      const k = Math.floor(Math.random()*(d.ids.length-1));
      [d.ids[d.ids.length-1], d.ids[k]] = [d.ids[k], d.ids[d.ids.length-1]];
    }
  }
  const id = d.ids.pop();
  d.last = id;
  return pool.find(v=>v.id===id) || pool[0];
}
let channelMeta = null;

function loadPoolKeys(storageKey, defaults){
  try{
    const raw = localStorage.getItem(storageKey);
    if(raw){
      const arr = JSON.parse(raw).filter(Boolean);
      if(arr.length) return arr;
    }
  }catch(e){}
  return defaults.slice();
}
function makePool(storageKey, defaults){
  return { storageKey, keys: loadPoolKeys(storageKey, defaults), index: 0 };
}
function setPoolKeys(pool, arr){
  pool.keys = arr;
  pool.index = 0;
  try{ localStorage.setItem(pool.storageKey, JSON.stringify(arr)); }catch(e){}
}

const minigamePool = makePool('yt_minigame_keys', MINIGAME_API_KEYS);
const giveawayPool = makePool('yt_giveaway_keys', GIVEAWAY_API_KEYS);

function getKey(pool){ return pool.keys[pool.index % pool.keys.length]; }
function rotateKey(pool){
  if(pool.keys.length <= 1) return false;
  pool.index = (pool.index + 1) % pool.keys.length;
  return true;
}
function isQuotaError(data){
  if(!data || !data.error) return false;
  const reason = data.error.errors && data.error.errors[0] && data.error.errors[0].reason;
  if(reason === 'quotaExceeded' || reason === 'dailyLimitExceeded' || reason === 'rateLimitExceeded') return true;
  // Formato nuevo de error de cuota de Google (sin array "errors"): status RESOURCE_EXHAUSTED / código 429
  if(data.error.status === 'RESOURCE_EXHAUSTED' || data.error.code === 429) return true;
  if(typeof data.error.message === 'string' && /quota exceeded/i.test(data.error.message)) return true;
  return false;
}
async function ytFetch(pool, buildUrl){
  const maxAttempts = pool.keys.length;
  let attempts = 0;
  while(true){
    const key = getKey(pool);
    const res = await fetch(buildUrl(key));
    const data = await res.json();
    if(isQuotaError(data)){
      attempts++;
      if(attempts < maxAttempts && rotateKey(pool)){ continue; }
    }
    return data;
  }
}
function saveKey(){
  const v = document.getElementById('apiKeyInput').value.trim();
  if(!v) return;
  const arr = v.split(/[\n,]+/).map(s=>s.trim()).filter(Boolean).slice(0,4);
  if(!arr.length) return;
  // Este diálogo aparece cuando falla la carga de los minijuegos, así que guarda claves para ese grupo.
  setPoolKeys(minigamePool, arr);
  document.getElementById('setup').style.display='none';
  init();
}
function isoDurationToSeconds(iso){
  if(!iso) return Infinity;
  const m = iso.match(/PT(?:(\d+)H)?(?:(\d+)M)?(?:(\d+)S)?/);
  if(!m) return Infinity;
  const h = parseInt(m[1]||0,10), mi = parseInt(m[2]||0,10), se = parseInt(m[3]||0,10);
  return h*3600 + mi*60 + se;
}
function fmt(n){ return n.toLocaleString('es-ES'); }
function esc(s){ return String(s).replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c])); }
function fmtDate(iso){ return new Date(iso).toLocaleDateString('es-ES', {day:'numeric',month:'short',year:'numeric'}); }

document.querySelectorAll('.tab').forEach(t=>{
  t.addEventListener('click', ()=>{
    document.querySelectorAll('.tab').forEach(x=>x.classList.remove('active'));
    document.querySelectorAll('.game').forEach(x=>x.classList.remove('active'));
    t.classList.add('active');
    document.getElementById('game-'+t.dataset.tab).classList.add('active');
  });
});

function showSetup(reasonHtml){
  document.getElementById('setupReason').innerHTML = reasonHtml;
  document.getElementById('setup').style.display='flex';
}

async function init(){
  let chData;
  try{
    chData = await ytFetch(minigamePool, key => `https://www.googleapis.com/youtube/v3/channels?part=statistics,snippet,contentDetails&id=${CHANNEL_ID}&key=${encodeURIComponent(key)}`);
  }catch(networkErr){
    showSetup(`No se pudo ni contactar con Google. Lo más probable: <b>estás viendo este archivo dentro del chat de Claude</b>, y la vista previa bloquea llamadas a APIs externas por seguridad.<br><br>Solución: descarga el archivo y ábrelo con doble clic en tu navegador, no lo veas integrado en el chat.`);
    return;
  }

  try{
    if(chData.error){
      const reason = chData.error.errors && chData.error.errors[0] && chData.error.errors[0].reason;
      let extra = '';
      if(reason==='keyInvalid' || chData.error.code===400) extra = 'La clave no es válida o está mal copiada.';
      else if(reason==='forbidden' || chData.error.code===403) extra = 'Casi seguro es una <b>restricción de la clave</b>: en Google Cloud Console → Credenciales, revisa "Restricciones de la aplicación" (ponla en "Ninguna") y que la "YouTube Data API v3" esté activada en ese proyecto.';
      else if(reason==='quotaExceeded') extra = 'Se agotó la cuota diaria gratuita (10.000 unidades/día). Prueba mañana o crea otra clave.';
      showSetup(`Google dijo: <i>${esc(chData.error.message||'error desconocido')}</i>.<br><br>${extra}`);
      return;
    }
    const item = chData.items[0];
    document.getElementById('chname').textContent = item.snippet.title || 'bydavi roblox';
    const thumb = item.snippet.thumbnails && (item.snippet.thumbnails.high || item.snippet.thumbnails.medium || item.snippet.thumbnails.default);
    if(thumb){
      const img=document.getElementById('avatarImg');
      img.onload = ()=>{ document.getElementById('avatarFallback').style.display='none'; };
      img.src=thumb.url;
      img.style.display='block';

      const introImg=document.getElementById('introAvatarImg');
      introImg.onload = ()=>{ document.getElementById('introAvatarFallback').style.display='none'; };
      introImg.src=thumb.url;
      introImg.style.display='block';
    }
    document.getElementById('subCount').textContent = item.statistics.hiddenSubscriberCount ? "Oculto" : fmt(parseInt(item.statistics.subscriberCount,10));
    renderAchievements(item.statistics.hiddenSubscriberCount ? null : parseInt(item.statistics.subscriberCount||"0",10));

    channelMeta = {
      subs: parseInt(item.statistics.subscriberCount || "0", 10),
      videoCount: parseInt(item.statistics.videoCount || "0", 10),
      totalViews: parseInt(item.statistics.viewCount || "0", 10),
      joinYear: new Date(item.snippet.publishedAt).getFullYear()
    };

    const uploadsId = item.contentDetails.relatedPlaylists.uploads;
    let ids = [], pageToken = '';
    for(let page=0; page<MAX_VIDEO_PAGES; page++){
      const tok = pageToken;
      const plData = await ytFetch(minigamePool, key => `https://www.googleapis.com/youtube/v3/playlistItems?part=snippet&maxResults=50&playlistId=${uploadsId}` + (tok ? `&pageToken=${tok}` : '') + `&key=${encodeURIComponent(key)}`);
      if(plData.error){ if(page===0) throw new Error(plData.error.message); break; }
      ids = ids.concat(plData.items.map(it=>it.snippet && it.snippet.resourceId && it.snippet.resourceId.videoId).filter(Boolean));
      pageToken = plData.nextPageToken;
      if(!pageToken) break;
    }
    ids = [...new Set(ids)];

    const allAreas = ['vistas-area','likes-area','fecha-area','titulo-area','memoria-area'];
    if(ids.length < 2){
      allAreas.forEach(id=>{ document.getElementById(id).textContent = "Este canal aún no tiene suficientes vídeos públicos para jugar."; });
    } else {
      const chunks = [];
      for(let i=0; i<ids.length; i+=50) chunks.push(ids.slice(i, i+50));
      const results = await Promise.all(chunks.map(ch => ytFetch(minigamePool, key => `https://www.googleapis.com/youtube/v3/videos?part=snippet,statistics,contentDetails&id=${ch.join(',')}&key=${encodeURIComponent(key)}`)));
      const okItems = results.flatMap(r => r.items || []);
      if(!okItems.length){ const bad = results.find(r => r.error); throw new Error(bad ? bad.error.message : 'Sin datos de vídeos'); }
      videos = okItems.map(v=>({
        id:v.id,
        title:v.snippet.title,
        thumb:(v.snippet.thumbnails.maxres||v.snippet.thumbnails.standard||v.snippet.thumbnails.high||v.snippet.thumbnails.medium||v.snippet.thumbnails.default).url,
        views: parseInt(v.statistics.viewCount||"0",10),
        likes: v.statistics.likeCount!==undefined ? parseInt(v.statistics.likeCount,10) : null,
        publishedAt: v.snippet.publishedAt,
        isShort: isoDurationToSeconds(v.contentDetails && v.contentDetails.duration) <= 60
      }));
      newVistasDuel();
      newLikesDuel();
      newFechaDuel();
      newTitulo();
      newMemoria();
      newMiniatura();
    }
    refreshLiveStatus();

  }catch(e){
    showSetup(`Algo falló cargando los vídeos: <i>${esc(e.message||String(e))}</i>. Revisa que la clave tenga la "YouTube Data API v3" activada.`);
  }
}

/* ===== ¿Está en directo ahora? — comparte una única búsqueda para el banner y para los sorteos ===== */
let currentLiveVideoId = null;
let liveCheckTimer = null;

// Franja en la que el banner comprueba el directo (hora de España): de 18:00 a 20:59
const LIVE_WINDOW_START = 18, LIVE_WINDOW_END = 21;
function madridHour(){
  const h = new Intl.DateTimeFormat('es-ES', {timeZone:'Europe/Madrid', hour:'numeric', hourCycle:'h23'}).format(new Date());
  return parseInt(h, 10) % 24;
}
function inLiveWindow(){ const h = madridHour(); return h >= LIVE_WINDOW_START && h < LIVE_WINDOW_END; }

async function refreshLiveStatus(){
  const area = document.getElementById('directo-area');
  if(!inLiveWindow()){
    currentLiveVideoId = null;
    area.innerHTML = `
      <div class="notlive">
        <div class="big">Ahora mismo no se comprueba el directo</div>
        El directo se comprueba automáticamente entre las ${LIVE_WINDOW_START}:00 y las ${LIVE_WINDOW_END}:00 (hora de España).<br><br>
        <a href="https://www.youtube.com/@bydavi_roblox/streams" target="_blank">Ver el canal / directos ↗</a>
      </div>`;
    scheduleNextLiveCheck();
    return;
  }
  try{
    const data = await ytFetch(giveawayPool, key => `https://www.googleapis.com/youtube/v3/search?part=snippet&channelId=${CHANNEL_ID}&eventType=live&type=video&key=${encodeURIComponent(key)}`);
    if(data.error){
      const reason = data.error.errors && data.error.errors[0] && data.error.errors[0].reason;
      let extra = '';
      if(reason==='quotaExceeded') extra = 'Se agotó la cuota diaria gratuita de la API de YouTube. Prueba de nuevo mañana o con otra clave.';
      else if(reason==='forbidden' || data.error.code===403) extra = 'La clave de API no tiene permiso para esta consulta (revisa restricciones en Google Cloud Console).';
      area.innerHTML = `<div class="notlive"><div class="big">No se pudo comprobar el directo.</div>${esc(data.error.message||'')}<br>${extra}<br><br>Se volverá a comprobar automáticamente en unos minutos.</div>`;
      currentLiveVideoId = null;
      scheduleNextLiveCheck();
      return;
    }
    if(data.items && data.items.length){
      const live = data.items[0];
      const videoId = live.id.videoId;
      currentLiveVideoId = videoId;
      renderLiveBanner(live, videoId);
    } else {
      currentLiveVideoId = null;
      area.innerHTML = `
        <div class="notlive">
          <div class="big">bydavi no está en directo ahora mismo</div>
          Última comprobación: ${new Date().toLocaleTimeString('es-ES')}<br><br>
          <a href="https://www.youtube.com/@bydavi_roblox/streams" target="_blank">Ver directos anteriores ↗</a>
        </div>`;
    }
  }catch(e){
    area.innerHTML = `<div class="notlive"><div class="big">Sin conexión para comprobar el directo.</div>Se volverá a comprobar automáticamente en unos minutos.</div>`;
    currentLiveVideoId = null;
  }
  scheduleNextLiveCheck();
}

function renderLiveBanner(live, videoId){
  const area = document.getElementById('directo-area');
  const isLocalFile = location.protocol === 'file:';
  const domain = location.hostname || 'localhost';
  const chatBlock = isLocalFile
    ? `<div class="fallback" style="margin-top:0;">El chat en directo no puede incrustarse cuando la página se abre como archivo local.<br><a href="https://www.youtube.com/live_chat?v=${videoId}&is_popout=1" target="_blank">Abrir el chat en una pestaña aparte ↗</a></div>`
    : `<iframe src="https://www.youtube.com/live_chat?v=${videoId}&embed_domain=${domain}"></iframe>
       <div class="fallback">¿No carga el chat? <a href="https://www.youtube.com/live_chat?v=${videoId}&is_popout=1" target="_blank">Ábrelo aparte aquí ↗</a></div>`;
  area.innerHTML = `
    <div class="live-banner"><span class="reddot"></span> ¡bydavi está en directo ahora mismo! — ${esc(live.snippet.title)}</div>
    <div class="live-wrap">
      <div class="live-video">
        <iframe src="https://www.youtube.com/embed/${videoId}?autoplay=1&mute=1" allow="autoplay; encrypted-media" allowfullscreen></iframe>
        <div class="fallback">Empieza silenciado por los navegadores — usa el altavoz del propio vídeo para escucharlo.</div>
      </div>
      <div class="live-chat">
        ${chatBlock}
      </div>
    </div>`;
}

function scheduleNextLiveCheck(){
  if(liveCheckTimer) clearTimeout(liveCheckTimer);
  // Cada 10 min. Fuera de la franja horaria no se llama a la API (solo se vuelve a mirar la hora).
  liveCheckTimer = setTimeout(refreshLiveStatus, 10*60*1000);
}




/* ===== Logros de suscriptores (panel derecho) ===== */
const SUB_MILESTONES = [
  {value:100000,  label:'100 K suscriptores', icon:'🥉'},
  {value:150000,  label:'150 K suscriptores', icon:'🥈'},
  {value:200000,  label:'200 K suscriptores', icon:'🥇'},
  {value:300000,  label:'300 K suscriptores', icon:'💎'},
  {value:500000,  label:'500 K suscriptores', icon:'🏆'},
  {value:1000000, label:'1 M suscriptores',   icon:'👑'}
];
function renderAchievements(subs){
  const el = document.getElementById('achList');
  if(!el) return;
  if(subs===null || subs===undefined){
    el.innerHTML = '<div class="lb-empty">Este canal oculta su número de suscriptores, así que no se pueden calcular los logros.</div>';
    return;
  }
  let nextDone = false;
  el.innerHTML = SUB_MILESTONES.map((m,i)=>{
    const unlocked = subs >= m.value;
    let extra;
    if(unlocked){
      extra = `<div class="ach-sub">Conseguido ✅</div>`;
    } else if(!nextDone){
      nextDone = true;
      const prev = i>0 ? SUB_MILESTONES[i-1].value : 0;
      const pct = Math.max(0, Math.min(100, Math.round((subs-prev)/(m.value-prev)*100)));
      extra = `<div class="ach-bar"><div class="ach-bar-fill" style="width:${pct}%"></div></div><div class="ach-sub">${fmt(subs)} / ${fmt(m.value)}</div>`;
    } else {
      extra = `<div class="ach-sub">Objetivo: ${fmt(m.value)}</div>`;
    }
    return `<div class="ach-item ${unlocked?'unlocked':'locked'}"><div class="ach-icon">${unlocked?m.icon:'🔒'}</div><div style="flex:1;min-width:0;"><div class="ach-name">${m.label}</div>${extra}</div></div>`;
  }).join('');
}

/* ===== Leaderboard global (Firebase Realtime Database) ===== */
const LB_LABELS = { vistas:'Duelo de vistas', likes:'Duelo de likes', fecha:'¿Cuál es más antiguo?', titulo:'Completa el título', miniatura:'Miniatura borrosa' };
let pendingRecord = null; // {game, score}

function getPlayerName(){
  try{ return localStorage.getItem('yt_hub_name') || ''; }catch(e){ return ''; }
}
function setPlayerName(name){
  try{ localStorage.setItem('yt_hub_name', name); }catch(e){}
}
const FB_DB_URL = "https://bydavileaderboard-default-rtdb.europe-west1.firebasedatabase.app";

function lbKey(name){ return name.toLowerCase().replace(/[.$#\[\]\/\s]/g, '_'); }

async function lbFetch(game){
  const res = await fetch(`${FB_DB_URL}/leaderboard/${game}.json`);
  const data = await res.json();
  if(data && data.error) throw new Error(data.error);
  const arr = data ? Object.values(data) : [];
  arr.sort((a,b) => b.score - a.score);
  return arr.slice(0, 10);
}

async function renderLB(game){
  const el = document.getElementById('lb-'+game);
  if(!el) return;
  let arr;
  try{ arr = await lbFetch(game); }
  catch(e){ el.innerHTML = `<div class="lb-title">🏆 Mejores puntuaciones</div><div class="lb-empty">No se pudo cargar la tabla.</div>`; return; }
  const me = getPlayerName().toLowerCase();
  if(!arr.length){ el.innerHTML = `<div class="lb-title">🏆 Mejores puntuaciones</div><div class="lb-empty">Todavía no hay puntuaciones. ¡Sé el primero!</div>`; return; }
  el.innerHTML = `<div class="lb-title">🏆 Mejores puntuaciones</div>` + arr.map((e,i)=>
    `<div class="lb-row${e.name.toLowerCase()===me?' me':''}"><span>#${i+1}</span><b>${esc(e.name)}</b><span>${e.score}</span></div>`
  ).join('');
}
function renderAllLB(){ Object.keys(LB_LABELS).forEach(renderLB); }
renderAllLB();
setInterval(renderAllLB, 30000); // se actualiza sola cada 30 s

async function saveRecord(game, score){
  const name = getPlayerName();
  if(!name) return;
  try{
    await fetch(`${FB_DB_URL}/leaderboard/${game}/${lbKey(name)}.json`, {
      method: 'PUT',
      headers: {'Content-Type': 'application/json'},
      body: JSON.stringify({name, score})
    });
  }catch(e){}
  renderLB(game);
}

// Se llama cada vez que un minijuego bate su propia mejor marca (racha).
// Si todavía no sabemos el nombre del jugador, se le pide una única vez y luego se recuerda.
function recordIfBest(game, score){
  const name = getPlayerName();
  if(name){ saveRecord(game, score); return; }
  pendingRecord = { game, score };
  document.getElementById('nameInput').value = '';
  document.getElementById('nameModal').style.display = 'flex';
  setTimeout(()=>document.getElementById('nameInput').focus(), 50);
}
function submitName(){
  const v = document.getElementById('nameInput').value.trim().slice(0,20);
  if(!v) return;
  setPlayerName(v);
  document.getElementById('nameModal').style.display = 'none';
  if(pendingRecord){ saveRecord(pendingRecord.game, pendingRecord.score); pendingRecord = null; }
}
document.getElementById('nameInput').addEventListener('keydown', e=>{ if(e.key==='Enter') submitName(); });

/* ===== helper genérico para juegos de "duelo" (comparar 2 vídeos por un valor) ===== */
function genericDuel(pool, valueFn, valueLabel, formatFn, areaId, msgId, streakId, bestId, state, rerun, lbGame){
  const area = document.getElementById(areaId);
  if(pool.length < 2){ area.textContent = "No hay suficientes vídeos con este dato disponible."; return; }
  const va = drawFromDeck(areaId, pool);
  let vb = drawFromDeck(areaId, pool), t=0;
  while((vb.id===va.id || valueFn(va)===valueFn(vb)) && t<30){ vb = drawFromDeck(areaId, pool); t++; }
  const pair=[va,vb];
  document.getElementById(msgId).textContent='';
  area.innerHTML = `<div class="cards">
    <div class="vcard" data-i="0"><img src="${pair[0].thumb}"><div class="t">${esc(pair[0].title)}</div></div>
    <div class="vs">VS</div>
    <div class="vcard" data-i="1"><img src="${pair[1].thumb}"><div class="t">${esc(pair[1].title)}</div></div>
  </div>`;
  area.querySelectorAll('.vcard').forEach(c=>{
    c.addEventListener('click', ()=>{
      const i=parseInt(c.dataset.i,10);
      const cards=area.querySelectorAll('.vcard');
      cards.forEach(cc=>cc.classList.add('disabled'));
      const correct = valueFn(pair[0])>=valueFn(pair[1]) ? 0 : 1;
      cards[correct].classList.add('correct');
      cards[0].insertAdjacentHTML('beforeend', `<div class="v">${formatFn(valueFn(pair[0]))}</div>`);
      cards[1].insertAdjacentHTML('beforeend', `<div class="v">${formatFn(valueFn(pair[1]))}</div>`);
      const msg = document.getElementById(msgId);
      if(i===correct){
        state.streak++;
        if(state.streak>state.best){ state.best=state.streak; if(lbGame) recordIfBest(lbGame, state.best); }
        msg.textContent="¡Acertaste! 🔥"; msg.style.color="var(--accent2)";
      } else {
        cards[i].classList.add('wrong');
        msg.textContent="Fallaste, racha reiniciada."; msg.style.color="var(--accent)";
        state.streak=0;
      }
      document.getElementById(streakId).textContent=state.streak;
      document.getElementById(bestId).textContent=state.best;
      setTimeout(rerun, 1500);
    });
  });
}

/* ===== 1. Duelo de vistas ===== */
let vistasState={streak:0,best:0};
function newVistasDuel(){ genericDuel(videos, v=>v.views, 'vistas', n=>fmt(n)+' vistas', 'vistas-area','vistas-msg','vistas-streak','vistas-best',vistasState,newVistasDuel,'vistas'); }

/* ===== 2. Duelo de likes ===== */
let likesState={streak:0,best:0};
function newLikesDuel(){
  const pool = videos.filter(v=>v.likes!==null);
  genericDuel(pool, v=>v.likes, 'likes', n=>fmt(n)+' likes', 'likes-area','likes-msg','likes-streak','likes-best',likesState,newLikesDuel,'likes');
}

/* ===== 3. Duelo de fechas (¿cuál es más antiguo?) ===== */
let fechaState={streak:0,best:0};
function newFechaDuel(){
  // valor = -timestamp, así "el mayor valor" (helper genérico) coincide con "la fecha más antigua"
  genericDuel(
    videos,
    v => -new Date(v.publishedAt).getTime(),
    'fecha',
    negTs => fmtDate(new Date(-negTs)),
    'fecha-area','fecha-msg','fecha-streak','fecha-best',
    fechaState, newFechaDuel, 'fecha'
  );
}

/* ===== 4. Completa el título ===== */
let tituloState={streak:0,best:0};
const STOPWORDS = new Set(['para','como','pero','esto','esta','este','estos','estas','sobre','desde','entre','hasta','muy','todo','toda','todos','todas','cuando','donde','porque','tiene','tienen','vamos','hemos','vídeo','video','parte','nueva','nuevo']);
function wordBank(){
  const bank = new Set();
  videos.forEach(v=>{
    v.title.split(/[\s\-|_:!¡¿?.,()"'#]+/).forEach(w=>{
      const clean = w.trim();
      if(clean.length>=4 && !/^\d+$/.test(clean) && !STOPWORDS.has(clean.toLowerCase())){
        bank.add(clean);
      }
    });
  });
  return [...bank];
}
function newTitulo(){
  document.getElementById('titulo-msg').textContent='';
  const bank = wordBank();
  const area = document.getElementById('titulo-area');
  if(bank.length < 4){ area.textContent = "No hay suficientes títulos variados para este juego todavía."; return; }

  let tries=0, video, targetWord, regex;
  do{
    video = drawFromDeck('titulo', videos);
    const candidates = video.title.split(/[\s\-|_:!¡¿?.,()"'#]+/).filter(w=>w.trim().length>=4 && !/^\d+$/.test(w) && !STOPWORDS.has(w.toLowerCase()));
    targetWord = candidates.length ? candidates[Math.floor(Math.random()*candidates.length)] : null;
    tries++;
  }while(!targetWord && tries<20);

  if(!targetWord){ area.textContent = "No se encontró un título adecuado, prueba a recargar."; return; }

  regex = new RegExp(targetWord.replace(/[.*+?^${}()|[\]\\]/g,'\\$&'));
  const blanked = video.title.replace(regex, '_____');

  const distractors = new Set();
  while(distractors.size<3){
    const cand = bank[Math.floor(Math.random()*bank.length)];
    if(cand.toLowerCase()!==targetWord.toLowerCase()) distractors.add(cand);
  }
  const options = shuffleArr([targetWord, ...distractors]);

  area.innerHTML = `
    <div class="vcard" style="max-width:360px;cursor:default;">
      <img src="${video.thumb}">
      <div class="t">${esc(blanked)}</div>
    </div>
    <div class="quiz-opts" style="margin-top:14px;">
      ${options.map(o=>`<div class="qopt" data-v="${esc(o)}">${esc(o)}</div>`).join('')}
    </div>`;
  area.querySelectorAll('.qopt').forEach(o=>{
    o.addEventListener('click', ()=>{
      document.querySelectorAll('#titulo-area .qopt').forEach(x=>{
        x.classList.add('disabled');
        if(x.dataset.v===targetWord) x.classList.add('correct');
      });
      const msg = document.getElementById('titulo-msg');
      if(o.dataset.v===targetWord){
        tituloState.streak++;
        if(tituloState.streak>tituloState.best){ tituloState.best=tituloState.streak; recordIfBest('titulo', tituloState.best); }
        msg.textContent="¡Correcto! 🔥"; msg.style.color="var(--accent2)";
      } else {
        o.classList.add('wrong');
        tituloState.streak=0;
        msg.textContent="Fallaste — racha reiniciada."; msg.style.color="var(--accent)";
      }
      document.getElementById('titulo-streak').textContent=tituloState.streak;
      document.getElementById('titulo-best').textContent=tituloState.best;
      setTimeout(newTitulo, 1800);
    });
  });
}

/* ===== 5. Memoria de miniaturas ===== */
let memMoves=0, memFound=0, memLock=false, memFirst=null;
function newMemoria(){
  memMoves=0; memFound=0; memLock=false; memFirst=null;
  document.getElementById('mem-moves').textContent=0;
  document.getElementById('memoria-msg').textContent='';

  const n = Math.min(6, videos.length);
  document.getElementById('mem-total').textContent = n;
  document.getElementById('mem-found').textContent = 0;

  const chosen = [];
  const usedIds = new Set();
  let guard = 0;
  while(chosen.length < n && guard < 200){
    const v = drawFromDeck('memoria', videos);
    if(!usedIds.has(v.id)){ usedIds.add(v.id); chosen.push(v); }
    guard++;
  }
  let cards = [];
  chosen.forEach((v,idx)=>{ cards.push({pairId:idx, thumb:v.thumb}); cards.push({pairId:idx, thumb:v.thumb}); });
  cards = shuffleArr(cards);

  const area = document.getElementById('memoria-area');
  area.innerHTML = `<div class="memgrid">` + cards.map((c,i)=>
    `<div class="mcard" data-i="${i}" data-pair="${c.pairId}"><span>?</span><img src="${c.thumb}"></div>`
  ).join('') + `</div>`;

  area.querySelectorAll('.mcard').forEach(card=>{
    card.addEventListener('click', ()=>{
      if(memLock || card.classList.contains('revealed') || card.classList.contains('matched')) return;
      card.classList.add('revealed');
      if(memFirst===null){
        memFirst = card;
      } else {
        memMoves++;
        document.getElementById('mem-moves').textContent = memMoves;
        if(memFirst.dataset.pair === card.dataset.pair){
          memFirst.classList.add('matched');
          card.classList.add('matched');
          memFirst=null;
          memFound++;
          document.getElementById('mem-found').textContent = memFound;
          if(memFound===n){
            document.getElementById('memoria-msg').textContent = `¡Completado en ${memMoves} intentos! 🎉`;
            document.getElementById('memoria-msg').style.color = "var(--accent2)";
          }
        } else {
          memLock=true;
          const a=memFirst, b=card;
          setTimeout(()=>{
            a.classList.remove('revealed'); b.classList.remove('revealed');
            memFirst=null; memLock=false;
          }, 700);
        }
      }
    });
  });
}

/* ===== 6. Miniatura borrosa (adivina el título por la miniatura) ===== */
const BLUR_STEPS = [9, 6, 4, 2, 0]; // 5 intentos, cada fallo desenfoca bastante menos que antes
let miniState = {streak:0, best:0};
let miniVideo = null, miniAttempt = 0;

function normalizeText(s){
  return s.toLowerCase()
    .normalize('NFD').replace(/[\u0300-\u036f]/g,'')
    .replace(/[^a-z0-9\s]/g,' ')
    .replace(/\s+/g,' ').trim();
}
function approxMatch(guess, real){
  const g = normalizeText(guess), r = normalizeText(real);
  if(!g) return false;
  if(g.length>=5 && r.includes(g)) return true;
  const gw = g.split(' ').filter(w=>w.length>=3);
  const rw = new Set(r.split(' ').filter(w=>w.length>=3));
  if(!gw.length) return false;
  let common=0; gw.forEach(w=>{ if(rw.has(w)) common++; });
  return common>=2 || (common/gw.length)>=0.5;
}

function newMiniatura(){
  document.getElementById('mini-msg').textContent='';
  miniAttempt=0;
  const pool = videos.filter(v=>!v.isShort);
  const source = pool.length ? pool : videos; // si por lo que sea no hay vídeos normales, no se queda sin jugar
  miniVideo = drawFromDeck('miniatura', source);
  renderMiniatura();
}
function renderMiniatura(){
  const area = document.getElementById('miniatura-area');
  area.innerHTML = `
    <div class="blurcard">
      <img id="miniImg" src="${miniVideo.thumb}" style="filter:blur(${BLUR_STEPS[miniAttempt]}px);">
      <div class="guessrow">
        <input type="text" id="miniInput" placeholder="¿Cuál crees que es el título?" autocomplete="off">
        <button class="act" id="miniBtn">Adivinar</button>
      </div>
      <div class="attempts">Intento ${miniAttempt+1} de ${BLUR_STEPS.length}</div>
    </div>`;
  document.getElementById('miniBtn').addEventListener('click', submitMini);
  document.getElementById('miniInput').addEventListener('keydown', e=>{ if(e.key==='Enter') submitMini(); });
}
function submitMini(){
  const input = document.getElementById('miniInput');
  const val = input.value;
  const msg = document.getElementById('mini-msg');

  if(approxMatch(val, miniVideo.title)){
    document.getElementById('miniImg').style.filter = 'blur(0px)';
    document.getElementById('miniBtn').disabled = true;
    input.disabled = true;
    miniState.streak++;
    if(miniState.streak>miniState.best){ miniState.best=miniState.streak; recordIfBest('miniatura', miniState.best); }
    document.getElementById('mini-streak').textContent = miniState.streak;
    document.getElementById('mini-best').textContent = miniState.best;
    msg.textContent = `¡Acertaste! Era: "${miniVideo.title}"`; msg.style.color='var(--accent2)';
    setTimeout(newMiniatura, 2400);
    return;
  }

  miniAttempt++;
  if(miniAttempt >= BLUR_STEPS.length){
    document.getElementById('miniBtn').disabled = true;
    input.disabled = true;
    miniState.streak = 0;
    document.getElementById('mini-streak').textContent = miniState.streak;
    msg.textContent = `Se acabaron los intentos. Era: "${miniVideo.title}"`; msg.style.color='var(--accent)';
    setTimeout(newMiniatura, 2600);
  } else {
    document.getElementById('miniImg').style.filter = `blur(${BLUR_STEPS[miniAttempt]}px)`;
    document.querySelector('#miniatura-area .attempts').textContent = `Intento ${miniAttempt+1} de ${BLUR_STEPS.length}`;
    input.value = '';
    input.focus();
    msg.textContent = 'No es eso — un poco más nítida ahora, prueba otra vez.'; msg.style.color='var(--sub)';
  }
}

/* ===================== Only davi: acceso privado ===================== */
async function sha256Hex(str){
  const buf = await crypto.subtle.digest('SHA-256', new TextEncoder().encode(str));
  return Array.from(new Uint8Array(buf)).map(b=>b.toString(16).padStart(2,'0')).join('');
}
const OD_USER = 'Bydavi';
const OD_PASS_HASH = 'f41f565be0c6c389413d2cf2a4f1b3e98a37e7a4cd2d2aa7899e79df92c2f56c';

async function tryOnlyDaviLogin(){
  const u = document.getElementById('odUser').value.trim();
  const p = document.getElementById('odPass').value;
  const errEl = document.getElementById('odLoginErr');
  errEl.textContent = '';
  const hash = await sha256Hex(p);
  if(u.toLowerCase() === OD_USER.toLowerCase() && hash === OD_PASS_HASH){
    try{ sessionStorage.setItem('onlydavi_ok','1'); }catch(e){}
    unlockOnlyDavi();
  } else {
    errEl.textContent = '❌ Usuario o contraseña incorrectos.';
  }
}
function unlockOnlyDavi(){
  document.getElementById('odLogin').style.display='none';
  document.getElementById('odPanel').style.display='block';
}
try{ if(sessionStorage.getItem('onlydavi_ok')==='1') unlockOnlyDavi(); }catch(e){}
document.getElementById('odPass').addEventListener('keydown', e=>{ if(e.key==='Enter') tryOnlyDaviLogin(); });

/* ===================== Only davi: detector de sorteos ===================== */
let giveawayActive = false;
let giveawayKeyword = '';
let giveawayParticipants = new Map(); // 'plataforma:usuario' -> {username, platform, message}
let numberGameActive = false;
let numberParticipants = new Map(); // usuario(lower) -> {name, guess}
let numberSecret = null; // número secreto (solo en memoria, nunca se muestra hasta que alguien acierta)
let ytChatId = null;
let ytSeenIds = new Set();
let ytPollTimer = null;
let ytSearchTimer = null;
let chatConnectionActive = false;
let feedHistory = [];
let feedFilterKey = null;
let riddleActive = false;
let riddleWord = '';
let riddleFound = false;

function anySorteoActive(){ return giveawayActive || numberGameActive || riddleActive; }
function odSetStatus(html){ const el = document.getElementById('odStatus'); if(el) el.innerHTML = html; }
function odSetNumStatus(html){ const el = document.getElementById('odNumStatus'); if(el) el.innerHTML = html; }
function odSetRiddleStatus(html){ const el = document.getElementById('odRiddleStatus'); if(el) el.innerHTML = html; }
function broadcastChatStatus(html){
  if(giveawayActive) odSetStatus(html);
  if(numberGameActive) odSetNumStatus(html);
  if(riddleActive) odSetRiddleStatus(html);
}

function renderFeedEntry(platform, username, message, matched){
  feedHistory.push({platform, username, message, matched});
  if(feedHistory.length > 500) feedHistory.shift();
  const key = platform + ':' + username.toLowerCase();
  if(feedFilterKey && key !== feedFilterKey) return;
  const feed = document.getElementById('odFeed');
  if(!feed) return;
  feed.prepend(feedRowDiv({platform, username, message, matched}));
  while(feed.children.length > 80){ feed.removeChild(feed.lastChild); }
}

function feedRowDiv(e){
  const div = document.createElement('div');
  div.className = 'od-msg' + (e.matched ? ' match' : '');
  const badge = e.platform === 'yt' ? '<span class="badge yt">YT</span>' : '<span class="badge tk">TikTok</span>';
  div.innerHTML = `${badge}<b>${esc(e.username)}</b>: ${esc(e.message)}`;
  return div;
}

function rebuildFeed(){
  const feed = document.getElementById('odFeed');
  if(!feed) return;
  feed.innerHTML = '';
  const source = feedFilterKey ? feedHistory.filter(e => (e.platform+':'+e.username.toLowerCase()) === feedFilterKey) : feedHistory;
  source.slice(-80).forEach(e => feed.prepend(feedRowDiv(e)));
}

function setFeedFilterToWinner(platform, username){
  feedFilterKey = platform + ':' + username.toLowerCase();
  const btn = document.getElementById('odFeedClearBtn');
  if(btn) btn.style.display = 'inline-block';
  rebuildFeed();
}

function clearFeedFilter(){
  feedFilterKey = null;
  const btn = document.getElementById('odFeedClearBtn');
  if(btn) btn.style.display = 'none';
  rebuildFeed();
}

function renderParticipants(){
  const wrap = document.getElementById('odParticipants');
  if(!wrap) return;
  const arr = Array.from(giveawayParticipants.values());
  document.getElementById('odCount').textContent = arr.length;
  const last = arr.slice(-10).reverse();
  let html = last.map(p => `<div class="od-participant"><span class="badge ${p.platform==='yt'?'yt':'tk'}">${p.platform==='yt'?'YT':'TikTok'}</span><b>${esc(p.username)}</b></div>`).join('') || '<div class="od-empty">Nadie ha escrito la palabra clave todavía.</div>';
  if(arr.length > 10){ html = `<div class="od-empty">Mostrando los últimos 10 de ${arr.length} participantes (se guardan todos para el sorteo).</div>` + html; }
  wrap.innerHTML = html;
}

function renderNumberParticipants(){
  const wrap = document.getElementById('odNumParticipants');
  if(!wrap) return;
  const arr = Array.from(numberParticipants.values());
  document.getElementById('odNumCount').textContent = arr.length;
  const last = arr.slice(-10).reverse();
  let html = last.map(p => `<div class="od-participant"><b>${esc(p.name)}</b><span>${p.guess}</span></div>`).join('') || '<div class="od-empty">Todavía no hay intentos.</div>';
  if(arr.length > 10){ html = `<div class="od-empty">Mostrando los últimos 10 de ${arr.length} intentos.</div>` + html; }
  wrap.innerHTML = html;
}

function addEntry(platform, username, message){
  const clean = w => w.replace(/[^\p{L}\p{N}]/gu, '');
  const words = message.toLowerCase().split(/\s+/).map(clean);

  let matched = false;
  if(giveawayActive && giveawayKeyword){
    matched = words.includes(giveawayKeyword.toLowerCase());
  }
  let riddleMatched = false;
  if(riddleActive && !riddleFound && riddleWord){
    riddleMatched = words.includes(riddleWord.toLowerCase());
  }
  renderFeedEntry(platform, username, message, matched || riddleMatched);
  if(matched){
    const key = platform + ':' + username.toLowerCase();
    if(!giveawayParticipants.has(key)){
      giveawayParticipants.set(key, {username, platform, message});
      renderParticipants();
    }
  }
  if(riddleMatched){
    riddleFound = true;
    riddleActive = false;
    const secret = riddleWord;
    const winnerEl = document.getElementById('odRiddleWinner');
    if(winnerEl){
      winnerEl.innerHTML = `<div class="od-winner-card"><span class="badge ${platform==='yt'?'yt':'tk'}">${platform==='yt'?'YT':'TikTok'}</span> 🏆 <b>${esc(username)}</b> ha acertado la palabra secreta: <b>${esc(secret)}</b><div class="od-winner-msg">"${esc(message)}"</div></div>`;
    }
    odSetRiddleStatus(`🏆 ¡Riddle resuelto! La palabra era <b>${esc(secret)}</b> y la acertó <b>${esc(username)}</b>.`);
    setFeedFilterToWinner(platform, username);
  }
  if(numberGameActive && numberSecret !== null){
    const m = message.match(/-?\d+(?:[.,]\d+)?/);
    if(m){
      const guess = parseFloat(m[0].replace(',', '.'));
      if(!isNaN(guess)){
        const key = username.toLowerCase();
        numberParticipants.delete(key);
        numberParticipants.set(key, {name: username, guess});
        renderNumberParticipants();
        if(guess === numberSecret){
          const secret = numberSecret;
          numberGameActive = false;
          numberSecret = null;
          const resultsEl = document.getElementById('odNumResults');
          if(resultsEl){
            resultsEl.innerHTML = `<div class="od-winner-card"><span class="badge ${platform==='yt'?'yt':'tk'}">${platform==='yt'?'YT':'TikTok'}</span> 🏆 <b>${esc(username)}</b> ha acertado el número secreto: <b>${secret}</b><div class="od-winner-msg">"${esc(message)}"</div></div>`;
          }
          odSetNumStatus(`🏆 ¡Sorteo terminado! El número era <b>${secret}</b> y lo acertó <b>${esc(username)}</b>.`);
          setFeedFilterToWinner(platform, username);
        }
      }
    }
  }
}

/* ===================== Only davi: sorteo "adivina el número" ===================== */
function secureRandomInt(min, max){
  const range = max - min + 1;
  const buf = new Uint32Array(1);
  const limit = Math.floor(0x100000000 / range) * range; // evita sesgo
  do { crypto.getRandomValues(buf); } while(buf[0] >= limit);
  return min + (buf[0] % range);
}

function startNumberGame(){
  if(!requireLiveChat()) return;
  let min = parseInt(document.getElementById('odNumMin').value, 10);
  let max = parseInt(document.getElementById('odNumMax').value, 10);
  if(isNaN(min)) min = 1;
  if(isNaN(max)) max = 100;
  if(min > max){ const t = min; min = max; max = t; }
  if(min === max){ alert('El rango necesita al menos dos números distintos.'); return; }
  document.getElementById('odNumMin').value = min;
  document.getElementById('odNumMax').value = max;
  numberSecret = secureRandomInt(min, max);
  numberGameActive = true;
  numberParticipants.clear();
  renderNumberParticipants();
  document.getElementById('odNumResults').innerHTML = '';
  odSetNumStatus(`🟢 Sorteo activo — número secreto elegido entre ${min} y ${max}. El primero que lo escriba en el chat gana.`);
}

function resetNumberGame(){
  numberGameActive = false;
  numberSecret = null;
  numberParticipants.clear();
  document.getElementById('odNumMin').value = '';
  document.getElementById('odNumMax').value = '';
  document.getElementById('odNumResults').innerHTML = '';
  renderNumberParticipants();
  odSetNumStatus('Sorteo de número detenido. Pulsa "Iniciar sorteo de número".');
}

function startRiddle(){
  if(!requireLiveChat()) return;
  const w = document.getElementById('odRiddleWord').value.trim();
  if(!w){ alert('Escribe primero la palabra secreta.'); return; }
  riddleWord = w;
  riddleActive = true;
  riddleFound = false;
  document.getElementById('odRiddleWinner').innerHTML = '';
  document.getElementById('odRiddleWord').value = '';
  clearFeedFilter();
  odSetRiddleStatus('🟢 Riddle activo — esperando a que alguien escriba la palabra secreta en el chat…');
}

function resetRiddle(){
  riddleActive = false;
  riddleWord = '';
  riddleFound = false;
  document.getElementById('odRiddleWord').value = '';
  document.getElementById('odRiddleWinner').innerHTML = '';
  odSetRiddleStatus('Riddle detenido. Escribe la palabra secreta y pulsa "Iniciar riddle".');
  clearFeedFilter();
}

function startGiveaway(){
  if(!requireLiveChat()) return;
  const kw = document.getElementById('odKeyword').value.trim();
  if(!kw){ alert('Escribe primero la palabra clave del sorteo.'); return; }
  giveawayKeyword = kw;
  giveawayActive = true;
  giveawayParticipants.clear();
  renderParticipants();
  document.getElementById('odWinner').innerHTML = '';
  clearFeedFilter();
  odSetStatus(`🟢 Sorteo activo — buscando la palabra <b>${esc(kw)}</b>. Leyendo el chat de YouTube…`);
}

function resetGiveaway(){
  giveawayActive = false;
  giveawayKeyword = '';
  giveawayParticipants.clear();
  renderParticipants();
  document.getElementById('odWinner').innerHTML = '';
  clearFeedFilter();
  odSetStatus('Sorteo detenido. Escribe una palabra clave y pulsa "Iniciar sorteo".');
}

function maybeStopChat(){
  if(anySorteoActive()) return;
  ytChatId = null;
  ytSeenIds = new Set();
  if(ytPollTimer) clearTimeout(ytPollTimer);
  if(ytSearchTimer) clearTimeout(ytSearchTimer);
  chatConnectionActive = false;
  feedHistory = [];
  clearFeedFilter();
  document.getElementById('odFeed').innerHTML = '';
}

function setLiveCheckStatus(html){ const el = document.getElementById('odLiveCheckStatus'); if(el) el.innerHTML = html; }

// Solo el streamer (panel Only davi) puede pulsar esto. Busca el directo, y si lo hay, conecta con su chat.
let liveManualBusy = false;
async function checkLiveManual(){
  if(liveManualBusy) return;
  const btn = document.getElementById('odCheckLiveBtn');
  if(ytChatId){ setLiveCheckStatus('🟢 Ya estás conectado al chat en directo. Puedes iniciar sorteos.'); return; }
  liveManualBusy = true;
  if(btn) btn.disabled = true;
  setLiveCheckStatus('⏳ Comprobando si estás en directo…');
  try{
    const data = await ytFetch(giveawayPool, key => `https://www.googleapis.com/youtube/v3/search?part=snippet&channelId=${CHANNEL_ID}&eventType=live&type=video&key=${encodeURIComponent(key)}`);
    if(data.error){
      setLiveCheckStatus(`⚠️ Error de YouTube: ${esc(data.error.message||'')}`);
      return;
    }
    if(!data.items || !data.items.length){
      setLiveCheckStatus('🟡 No estás en directo ahora mismo. Cuando empieces el directo, pulsa de nuevo el botón.');
      return;
    }
    const videoId = data.items[0].id.videoId;
    currentLiveVideoId = videoId;
    const vdata = await ytFetch(giveawayPool, key => `https://www.googleapis.com/youtube/v3/videos?part=liveStreamingDetails&id=${videoId}&key=${encodeURIComponent(key)}`);
    const chatId = vdata.items && vdata.items[0] && vdata.items[0].liveStreamingDetails && vdata.items[0].liveStreamingDetails.activeLiveChatId;
    if(!chatId){
      setLiveCheckStatus('🟡 Estás en directo pero el chat en vivo está desactivado.');
      return;
    }
    ytChatId = chatId;
    ytSeenIds = new Set();
    setLiveCheckStatus('🟢 En directo y conectado al chat. Ya puedes iniciar sorteos.');
    pollYouTubeChat(null);
  }catch(e){
    setLiveCheckStatus('⚠️ Sin conexión para comprobar YouTube. Inténtalo de nuevo.');
  }finally{
    liveManualBusy = false;
    if(btn) btn.disabled = false;
  }
}

function requireLiveChat(){
  if(ytChatId) return true;
  alert('Primero pulsa "Comprobar si estoy en directo" y espera a que se conecte con el chat.');
  return false;
}

async function pollYouTubeChat(pageToken){
  if(!ytChatId) return;
  try{
    const data = await ytFetch(giveawayPool, key => `https://www.googleapis.com/youtube/v3/liveChat/messages?liveChatId=${ytChatId}&part=snippet,authorDetails&key=${encodeURIComponent(key)}` + (pageToken ? `&pageToken=${pageToken}` : ''));
    if(data.error){
      broadcastChatStatus('⚠️ Se perdió la conexión con el chat (¿ha terminado el directo?). Pulsa de nuevo "Comprobar si estoy en directo" para reconectar.');
      setLiveCheckStatus(`⚠️ Se perdió la conexión con el chat (${esc(data.error.message||'')}). Pulsa el botón para volver a comprobar.`);
      ytChatId = null;
      currentLiveVideoId = null;
      return;
    }
    (data.items||[]).forEach(item=>{
      if(ytSeenIds.has(item.id)) return;
      ytSeenIds.add(item.id);
      const author = item.authorDetails ? item.authorDetails.displayName : 'Anon';
      const msg = (item.snippet && item.snippet.displayMessage) || '';
      addEntry('yt', author, msg);
    });
    const interval = Math.max(data.pollingIntervalMillis || 8000, 5000);
    ytPollTimer = setTimeout(()=>pollYouTubeChat(data.nextPageToken), interval);
  }catch(e){
    ytPollTimer = setTimeout(()=>pollYouTubeChat(pageToken), 10000);
  }
}


function pickWinner(){
  const arr = Array.from(giveawayParticipants.values());
  if(!arr.length){ alert('Todavía no hay nadie con la palabra clave para sortear.'); return; }
  const winnerEl = document.getElementById('odWinner');
  let i = 0;
  const spins = 18;
  const timer = setInterval(()=>{
    const p = arr[Math.floor(Math.random()*arr.length)];
    winnerEl.innerHTML = `<div class="od-spin">${esc(p.username)}</div>`;
    i++;
    if(i>=spins){
      clearInterval(timer);
      const winner = arr[Math.floor(Math.random()*arr.length)];
      winnerEl.innerHTML = `<div class="od-winner-card"><span class="badge ${winner.platform==='yt'?'yt':'tk'}">${winner.platform==='yt'?'YT':'TikTok'}</span> 🏆 <b>${esc(winner.username)}</b><div class="od-winner-msg">"${esc(winner.message)}"</div></div>`;
      setFeedFilterToWinner(winner.platform, winner.username);
    }
  }, 90);
}

init();
</script>
</body>
</html>
