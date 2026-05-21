<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Nikitha 💕</title>
<style>
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box}
:root{
  --pink:#f472b6;--pink-light:#fce7f3;--pink-soft:#fbcfe8;--pink-deep:#db2777;--pink-pale:#fdf2f8;
  --lav:#c084fc;--lav-light:#ede9fe;--lav-soft:#ddd6fe;--lav-deep:#7c3aed;
  --blue:#60a5fa;--blue-light:#dbeafe;--blue-soft:#bfdbfe;--blue-deep:#2563eb;
  --deep:#06030e;--mid:#0f0820;--surface:#180f2e;
  --text:#f3ecff;--muted:#c4b2d8;
}
html{scroll-behavior:smooth}
body{background:var(--deep);color:var(--text);font-family:'Jost',sans-serif;overflow-x:hidden;min-height:100vh}
.orb{position:fixed;border-radius:50%;filter:blur(90px);opacity:.11;pointer-events:none;z-index:0}
.orb1{width:700px;height:700px;background:var(--pink);top:-150px;left:-200px;animation:om1 20s ease-in-out infinite alternate}
.orb2{width:600px;height:600px;background:var(--lav);bottom:-100px;right:-200px;animation:om2 24s ease-in-out infinite alternate}
.orb3{width:450px;height:450px;background:var(--blue);top:35%;left:45%;transform:translate(-50%,-50%);animation:om3 28s ease-in-out infinite alternate}
@keyframes om1{to{transform:translate(60px,80px)}}
@keyframes om2{to{transform:translate(-80px,-60px)}}
@keyframes om3{to{transform:translate(-45%,-45%)}}
#stars{position:fixed;top:0;left:0;width:100%;height:100%;z-index:0;pointer-events:none}
.petal{position:fixed;top:-90px;pointer-events:none;z-index:2;animation:pf linear infinite}
@keyframes pf{0%{transform:translateY(-90px) rotate(0deg) translateX(0);opacity:.85}50%{transform:translateY(50vh) rotate(300deg) translateX(50px);opacity:.6}100%{transform:translateY(115vh) rotate(600deg) translateX(-20px);opacity:0}}
.fheart{position:fixed;pointer-events:none;z-index:1;opacity:0;animation:fhu linear infinite}
@keyframes fhu{0%{transform:translateY(0) scale(1);opacity:.6}75%{opacity:.15}100%{transform:translateY(-95vh) scale(.25);opacity:0}}
section{position:relative;z-index:3}

/* ══ HERO ══ */
#hero{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:2rem 1.5rem;background:radial-gradient(ellipse at 50% 40%,rgba(192,132,252,.07) 0%,transparent 65%)}
.date-tag{font-weight:200;font-size:.74rem;letter-spacing:.48em;text-transform:uppercase;background:linear-gradient(90deg,var(--pink),var(--lav),var(--blue));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:2.2rem;opacity:0;animation:fu .9s ease forwards .3s}
.for-her{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:clamp(1rem,2.5vw,1.3rem);color:var(--pink-soft);letter-spacing:.1em;margin-bottom:.6rem;opacity:0;animation:fu .9s ease forwards .7s}

/* BIG FIRST LETTER HERO */
.hero-name-wrap{position:relative;opacity:0;animation:fu 1.2s ease forwards 1s}
.big-n{font-family:'Great Vibes',cursive;font-size:clamp(9rem,28vw,22rem);line-height:.85;background:linear-gradient(135deg,var(--pink-soft) 0%,var(--lav) 40%,var(--blue-soft) 80%,var(--pink-soft) 100%);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;filter:drop-shadow(0 0 60px rgba(192,132,252,.6)) drop-shadow(0 0 120px rgba(244,114,182,.3));display:inline-block;animation:name-shimmer 6s ease infinite}
@keyframes name-shimmer{0%,100%{filter:drop-shadow(0 0 40px rgba(244,114,182,.5)) drop-shadow(0 0 80px rgba(192,132,252,.3))}50%{filter:drop-shadow(0 0 80px rgba(96,165,250,.6)) drop-shadow(0 0 140px rgba(192,132,252,.5))}}
.rest-name{font-family:'Great Vibes',cursive;font-size:clamp(2.8rem,8vw,5.5rem);background:linear-gradient(to right,var(--lav-soft),var(--blue-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;display:block;margin-top:-.5rem;letter-spacing:.05em}

.hero-birthday{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:clamp(1.1rem,3vw,1.6rem);color:var(--lav-soft);margin-top:1.2rem;opacity:0;animation:fu .9s ease forwards 1.6s}
.nicknames{display:flex;gap:1rem;justify-content:center;flex-wrap:wrap;margin-top:2.2rem;opacity:0;animation:fu .9s ease forwards 2s}
.nick{border-radius:999px;padding:.5rem 1.6rem;font-family:'Cormorant Garamond',serif;font-style:italic;font-size:1.05rem;letter-spacing:.06em;transition:all .35s;cursor:default}
.nick:nth-child(1){background:rgba(244,114,182,.1);border:1px solid rgba(244,114,182,.45);color:var(--pink-soft)}
.nick:nth-child(2){background:rgba(192,132,252,.1);border:1px solid rgba(192,132,252,.45);color:var(--lav-soft)}
.nick:nth-child(3){background:rgba(96,165,250,.1);border:1px solid rgba(96,165,250,.45);color:var(--blue-soft)}
.nick:hover{transform:translateY(-3px) scale(1.06);box-shadow:0 10px 30px rgba(192,132,252,.25)}
.hero-quote{margin-top:2.8rem;font-family:'Cormorant Garamond',serif;font-style:italic;font-size:clamp(.95rem,2.2vw,1.15rem);color:var(--muted);max-width:460px;line-height:1.9;opacity:0;animation:fu .9s ease forwards 2.5s}
.scroll-hint{margin-top:3.5rem;display:flex;flex-direction:column;align-items:center;gap:.6rem;opacity:0;animation:fu .9s ease forwards 3s}
.scroll-hint span{font-size:.68rem;letter-spacing:.35em;text-transform:uppercase;color:var(--muted)}
.sdot{width:5px;height:5px;border-radius:50%;background:var(--lav);animation:sdpulse 2.2s ease infinite}
@keyframes sdpulse{0%,100%{transform:translateY(0);opacity:.3}50%{transform:translateY(7px);opacity:1}}

/* ══ DIVIDERS ══ */
.dvd{display:flex;align-items:center;gap:1.2rem;padding:.5rem 2rem;margin:0 auto;max-width:700px;position:relative;z-index:3}
.dl{flex:1;height:1px}
.dl-p{background:linear-gradient(to right,transparent,rgba(244,114,182,.5),transparent)}
.dl-l{background:linear-gradient(to right,transparent,rgba(192,132,252,.5),transparent)}
.dl-b{background:linear-gradient(to right,transparent,rgba(96,165,250,.5),transparent)}
.di{font-size:.9rem;opacity:.65}

/* ══ SECTION LABEL ══ */
.slbl{text-align:center;font-size:.72rem;letter-spacing:.44em;text-transform:uppercase;background:linear-gradient(90deg,var(--pink),var(--lav),var(--blue));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:2.2rem}

/* ══ OPENING ══ */
#opening{padding:4.5rem 1.5rem}
.open-card{max-width:720px;margin:0 auto;text-align:center;background:linear-gradient(135deg,rgba(244,114,182,.05),rgba(192,132,252,.08),rgba(96,165,250,.04));border:1px solid rgba(192,132,252,.2);border-radius:28px;padding:3rem 2.5rem}
.open-text{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:clamp(1.1rem,2.8vw,1.3rem);line-height:2;color:var(--text)}
.open-text .pk{color:var(--pink)} .open-text .lv{color:var(--lav)} .open-text .bl{color:var(--blue-soft)}

/* ══ POEM ══ */
#poem{padding:5rem 1.5rem}
.poem-card{max-width:760px;margin:0 auto;background:linear-gradient(155deg,rgba(24,15,46,.97),rgba(15,8,32,.98));border:1px solid rgba(192,132,252,.2);border-radius:32px;padding:clamp(2.5rem,5vw,5rem) clamp(1.8rem,5vw,4.5rem);text-align:center;box-shadow:0 50px 120px rgba(0,0,0,.6),inset 0 1px 0 rgba(244,114,182,.1)}
.poem-title{font-family:'Great Vibes',cursive;font-size:clamp(2.8rem,8vw,4.5rem);background:linear-gradient(135deg,var(--pink-soft),var(--lav),var(--blue-soft),var(--lav),var(--pink-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:2.8rem;filter:drop-shadow(0 0 25px rgba(192,132,252,.4))}
.poem-body{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:clamp(1.02rem,2.6vw,1.22rem);line-height:2.2;color:var(--text);letter-spacing:.02em}
.st{margin-bottom:2.2rem}.st:last-child{margin-bottom:0}
.si{font-size:1.3rem;margin:1.8rem 0;display:block;animation:ipulse 4s ease infinite}
@keyframes ipulse{0%,100%{transform:scale(1)}50%{transform:scale(1.2)}}
.pk{color:var(--pink-soft)} .lv{color:var(--lav-soft)} .bl{color:var(--blue-soft)}

/* ══ MEMORIES ══ */
#memories{padding:5rem 1.5rem}
.mem-title{font-family:'Great Vibes',cursive;font-size:clamp(2.2rem,6vw,3.5rem);text-align:center;background:linear-gradient(to right,var(--pink),var(--lav));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:3.5rem;filter:drop-shadow(0 0 20px rgba(244,114,182,.3))}
.mem-grid{max-width:900px;margin:0 auto;display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:1.5rem}
.mc{background:linear-gradient(135deg,rgba(244,114,182,.06),rgba(192,132,252,.09));border-radius:24px;padding:2.2rem 2rem;border:1px solid rgba(192,132,252,.17);transition:all .4s;position:relative;overflow:hidden}
.mc::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,rgba(244,114,182,.04),transparent);border-radius:24px;opacity:0;transition:opacity .4s}
.mc:hover{transform:translateY(-6px);box-shadow:0 25px 60px rgba(192,132,252,.18)}.mc:hover::before{opacity:1}
.mi{font-size:2.2rem;margin-bottom:1.1rem;display:block;animation:ipulse 4s ease infinite}
.mc:nth-child(2) .mi{animation-delay:.7s}.mc:nth-child(3) .mi{animation-delay:1.4s}.mc:nth-child(4) .mi{animation-delay:2.1s}.mc:nth-child(5) .mi{animation-delay:2.8s}.mc:nth-child(6) .mi{animation-delay:.35s}
.mh{font-family:'Cormorant Garamond',serif;font-size:1.18rem;font-style:italic;margin-bottom:.7rem;color:var(--lav-soft)}
.mt{font-family:'Cormorant Garamond',serif;font-size:1rem;line-height:1.9;color:var(--muted)}

/* ══ LOVE LETTER ══ */
#letter{padding:5rem 1.5rem}
.letter-wrap{max-width:820px;margin:0 auto}
.letter-paper{background:linear-gradient(160deg,rgba(244,114,182,.03),rgba(24,15,46,.9),rgba(96,165,250,.025));border:1px solid rgba(192,132,252,.18);border-radius:6px 32px 32px 32px;padding:clamp(2.5rem,6vw,6rem) clamp(1.5rem,6vw,5rem);position:relative;box-shadow:0 40px 100px rgba(0,0,0,.5),inset 0 0 120px rgba(244,114,182,.015)}
.letter-paper::before{content:'';position:absolute;top:0;left:0;right:0;height:5px;background:linear-gradient(to right,var(--pink-deep),var(--lav),var(--blue),var(--lav),var(--pink-deep));border-radius:6px 32px 0 0;opacity:.9}

/* BIG DROP CAP N */
.drop-cap-wrap{display:block;margin-bottom:1.8rem}
.drop-n{font-family:'Great Vibes',cursive;font-size:clamp(6rem,18vw,11rem);line-height:.8;float:left;margin-right:1rem;margin-top:.2rem;background:linear-gradient(135deg,var(--pink-soft),var(--lav),var(--blue-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;filter:drop-shadow(0 0 30px rgba(192,132,252,.5));animation:name-shimmer 6s ease infinite}
.drop-rest{font-family:'Great Vibes',cursive;font-size:2.4rem;color:var(--lav-soft)}

.letter-body{font-family:'Cormorant Garamond',serif;font-size:clamp(1.08rem,2.6vw,1.24rem);line-height:2.1;color:var(--text);font-weight:300}
.letter-body p{margin-bottom:1.7rem}.letter-body p:last-child{margin-bottom:0}
.hl-p{color:var(--pink-soft);font-style:italic} .hl-l{color:var(--lav-soft);font-style:italic} .hl-b{color:var(--blue-soft);font-style:italic}
.letter-break{text-align:center;color:var(--lav);opacity:.45;margin:2.2rem 0;font-size:1.1rem;letter-spacing:1rem}
.letter-sign{margin-top:3.5rem;font-family:'Great Vibes',cursive;font-size:2.5rem;background:linear-gradient(to right,var(--lav-soft),var(--pink-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;text-align:right;line-height:1.4}
.letter-sign small{display:block;font-family:'Jost',sans-serif;font-size:.7rem;letter-spacing:.22em;color:var(--muted);text-transform:uppercase;font-style:normal;margin-top:.5rem;-webkit-text-fill-color:var(--muted)}

/* ══ THINGS I MISS ══ */
#miss{padding:5rem 1.5rem}
.miss-title{font-family:'Great Vibes',cursive;font-size:clamp(2rem,6vw,3.5rem);text-align:center;background:linear-gradient(to right,var(--lav),var(--pink));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:3.5rem}
.miss-list{max-width:700px;margin:0 auto;display:flex;flex-direction:column;gap:1.2rem}
.miss-item{display:flex;align-items:flex-start;gap:1.2rem;background:rgba(244,114,182,.05);border:1px solid rgba(244,114,182,.14);border-radius:18px;padding:1.4rem 1.8rem;transition:all .35s}
.miss-item:hover{background:rgba(244,114,182,.1);transform:translateX(5px);border-color:rgba(244,114,182,.3)}
.miss-dot{font-size:1.5rem;min-width:1.5rem;animation:ipulse 4s ease infinite}
.miss-item:nth-child(even) .miss-dot{animation-delay:1.2s}
.miss-text{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:1.1rem;line-height:1.85;color:var(--text);padding-top:.2rem}

/* ══ REASONS ══ */
#reasons{padding:5rem 1.5rem}
.reasons-title{font-family:'Great Vibes',cursive;font-size:clamp(2.2rem,6vw,3.5rem);text-align:center;background:linear-gradient(to right,var(--lav-soft),var(--blue-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:3.5rem;filter:drop-shadow(0 0 20px rgba(192,132,252,.3))}
.rlist{max-width:700px;margin:0 auto;display:flex;flex-direction:column;gap:1.1rem}
.ri{display:flex;align-items:flex-start;gap:1.1rem;background:rgba(192,132,252,.05);border:1px solid rgba(192,132,252,.12);border-radius:16px;padding:1.3rem 1.6rem;transition:all .35s}
.ri:hover{background:rgba(192,132,252,.1);transform:translateX(5px)}
.rn{font-family:'Great Vibes',cursive;font-size:2rem;min-width:1.8rem;line-height:1}
.ri:nth-child(3n+1) .rn{color:var(--pink)} .ri:nth-child(3n+2) .rn{color:var(--lav)} .ri:nth-child(3n) .rn{color:var(--blue)}
.rt{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:1.08rem;line-height:1.85;color:var(--text);padding-top:.3rem}

/* ══ WISH ══ */
#wish{padding:5rem 1.5rem;text-align:center}
.wish-title{font-family:'Great Vibes',cursive;font-size:clamp(3rem,9vw,5.5rem);background:linear-gradient(135deg,var(--pink-soft),var(--lav),var(--blue-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;filter:drop-shadow(0 0 35px rgba(192,132,252,.45));margin-bottom:.8rem}
.wish-sub{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:1.18rem;color:var(--lav-soft);margin-bottom:3.5rem}
.cake-wrap{display:flex;justify-content:center;margin-bottom:3rem}
.crows{display:flex;flex-direction:column;align-items:center;gap:0}
.crow{display:flex;gap:1.5rem;align-items:flex-end}
.candle{display:flex;flex-direction:column;align-items:center}
.flame{width:13px;height:24px;border-radius:50% 50% 30% 30%;animation:flicker 1.4s ease-in-out infinite}
.fp .flame{background:radial-gradient(ellipse at 50% 80%,#fff,#f9a8d4,#ec4899,transparent 70%)}
.fl .flame{background:radial-gradient(ellipse at 50% 80%,#fff,#e9d5ff,#a855f7,transparent 70%)}
.fb .flame{background:radial-gradient(ellipse at 50% 80%,#fff,#bfdbfe,#3b82f6,transparent 70%)}
@keyframes flicker{0%,100%{transform:scaleX(1) scaleY(1) rotate(-2deg)}25%{transform:scaleX(.78) scaleY(1.14) rotate(2deg)}50%{transform:scaleX(1.1) scaleY(.86) rotate(-1deg);opacity:.9}75%{transform:scaleX(.85) scaleY(1.1) rotate(3deg)}}
.candle:nth-child(2) .flame{animation-delay:.3s}.candle:nth-child(3) .flame{animation-delay:.7s}.candle:nth-child(4) .flame{animation-delay:1s}.candle:nth-child(5) .flame{animation-delay:.5s}.candle:nth-child(6) .flame{animation-delay:1.3s}.candle:nth-child(7) .flame{animation-delay:.2s}.candle:nth-child(8) .flame{animation-delay:.9s}.candle:nth-child(9) .flame{animation-delay:.4s}.candle:nth-child(10) .flame{animation-delay:1.1s}
.cbody{width:15px;height:70px;border-radius:3px 3px 2px 2px;position:relative;overflow:hidden}
.fp .cbody{background:linear-gradient(to right,#f9a8d4,#ec4899)}
.fl .cbody{background:linear-gradient(to right,#ddd6fe,#a855f7)}
.fb .cbody{background:linear-gradient(to right,#bfdbfe,#3b82f6)}
.drip{position:absolute;top:0;left:50%;transform:translateX(-50%);width:7px;height:13px;border-radius:0 0 50% 50%;opacity:.55}
.fp .drip{background:#fce7f3} .fl .drip{background:#ede9fe} .fb .drip{background:#dbeafe}
.ctier{display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden}
.ct1{width:320px;height:52px;background:linear-gradient(to bottom,#1e0f3c,#140a28);border:1px solid rgba(192,132,252,.25);border-radius:8px}
.ct2{width:240px;height:46px;background:linear-gradient(to bottom,#270d40,#1c0a30);border:1px solid rgba(244,114,182,.2);border-radius:6px}
.ct3{width:160px;height:38px;background:linear-gradient(to bottom,#2a0f44,#1f0c34);border:1px solid rgba(96,165,250,.2);border-radius:5px}
.ct1::before,.ct2::before,.ct3::before{content:'';position:absolute;inset:0;background:repeating-linear-gradient(90deg,transparent,transparent 18px,rgba(192,132,252,.06) 18px,rgba(192,132,252,.06) 20px)}
.ctext{font-family:'Great Vibes',cursive;position:relative;z-index:1}
.ct1 .ctext{font-size:1.35rem;background:linear-gradient(to right,var(--pink-soft),var(--lav-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.ct2 .ctext{font-size:1.15rem;color:var(--blue-soft)}
.ct3 .ctext{font-size:.95rem;color:var(--lav-soft)}
.wish-msg{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:1.18rem;color:var(--muted);max-width:540px;margin:0 auto;line-height:2.1}

/* ══ CLOSING LETTER ══ */
#closing-letter{padding:5rem 1.5rem}
.cl-card{max-width:760px;margin:0 auto;background:linear-gradient(135deg,rgba(244,114,182,.05),rgba(192,132,252,.08),rgba(96,165,250,.04));border:1px solid rgba(192,132,252,.2);border-radius:32px;padding:clamp(2.5rem,5vw,5rem) clamp(1.5rem,5vw,4rem);text-align:center}
.cl-icon{font-size:3.8rem;display:block;margin-bottom:1.8rem;animation:ipulse 2s ease infinite}
.cl-title{font-family:'Great Vibes',cursive;font-size:clamp(2.5rem,7vw,4rem);background:linear-gradient(to right,var(--pink-soft),var(--lav-soft),var(--blue-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:2rem}
.cl-body{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:clamp(1.05rem,2.6vw,1.22rem);line-height:2.2;color:var(--text);max-width:600px;margin:0 auto}
.cl-body p{margin-bottom:1.5rem}.cl-body p:last-child{margin-bottom:0}

/* ══ FINAL NAME ══ */
#final{padding:4rem 1.5rem 9rem;text-align:center}
.final-name{font-family:'Great Vibes',cursive;font-size:clamp(5rem,16vw,12rem);background:linear-gradient(135deg,var(--pink-soft),var(--lav),var(--blue-soft),var(--lav),var(--pink-soft));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;filter:drop-shadow(0 0 50px rgba(192,132,252,.5));animation:name-shimmer 5s ease infinite;line-height:1.1}
.final-date{margin-top:1.2rem;font-family:'Jost',sans-serif;font-weight:200;letter-spacing:.45em;font-size:.75rem;color:var(--muted);text-transform:uppercase}

/* ══ ANIMATIONS ══ */
@keyframes fu{from{opacity:0;transform:translateY(30px)}to{opacity:1;transform:translateY(0)}}
.reveal{opacity:0;transform:translateY(38px);transition:opacity 1s ease,transform 1s ease}
.reveal.visible{opacity:1;transform:translateY(0)}
.reveal-delay-1{transition-delay:.15s}.reveal-delay-2{transition-delay:.3s}.reveal-delay-3{transition-delay:.45s}

::-webkit-scrollbar{width:4px}
::-webkit-scrollbar-track{background:var(--deep)}
::-webkit-scrollbar-thumb{background:linear-gradient(to bottom,var(--pink-deep),var(--lav-deep));border-radius:2px}
</style>
</head>
<body>
<div class="orb orb1"></div><div class="orb orb2"></div><div class="orb orb3"></div>
<canvas id="stars"></canvas>

<!-- ══ HERO ══ -->
<section id="hero">
  <p class="date-tag">August 10 &nbsp;✦&nbsp; A day the universe made just for you</p>
  <p class="for-her">For the one who is my whole heart — always</p>
  <div class="hero-name-wrap">
    <span class="big-n">N</span>
    <span class="rest-name">ikitha</span>
  </div>
  <p class="hero-birthday">Happy Birthday, my love 🌸</p>
  <div class="nicknames">
    <span class="nick">Niku</span>
    <span class="nick">Jaan</span>
    <span class="nick">Cutie Pie</span>
  </div>
  <p class="hero-quote">"Some people arrive in your life and quietly rearrange everything —<br>the way you see the world, the way you feel in it.<br>You were that person for me."</p>
  <div class="scroll-hint">
    <span>made with every piece of love I have</span>
    <div class="sdot"></div>
  </div>
</section>

<!-- ══ OPENING ══ -->
<section id="opening">
  <div class="open-card reveal">
    <p class="open-text">
      Today, <span class="pk">August 10th</span>, is the day the world gets to celebrate you.<br><br>
      And I made this — every word, every line, every single thing on this page —<br>
      <span class="lv">because you deserve to feel loved not just when things are easy,<br>
      but always. Especially on the days when you feel most alone.</span><br><br>
      So take your time. <span class="bl">Let every word find you. Let yourself feel it.</span><br>
      This is yours. Every single word of it.
    </p>
  </div>
</section>

<div class="dvd reveal"><div class="dl dl-p"></div><span class="di">🌸</span><div class="dl dl-p"></div></div>

<!-- ══ POEM ══ -->
<section id="poem">
  <p class="slbl reveal">— a poem that has only ever been yours —</p>
  <div class="poem-card reveal">
    <h2 class="poem-title">Everything I Carry</h2>
    <div class="poem-body">

      <div class="st">
        <span class="pk">You are the kind of person who happens only once —</span><br>
        like the first rain after a summer that went on too long.<br>
        <span class="lv">I found you and without meaning to,</span><br>
        I handed you the quietest parts of me. I was never more wrong to be strong.
      </div>
      <span class="si">🌸</span>

      <div class="st">
        <span class="bl">I loved you the way the tide loves the shore —</span><br>
        not with noise, but with constancy. With return.<br>
        <span class="pk">Every single time I pulled away from the world,</span><br>
        <span class="lv">you were the one thing to which I always turned.</span>
      </div>
      <span class="si">💜</span>

      <div class="st">
        <span class="lv">Jaan — I used to close my eyes and just say your name</span><br>
        on the hard days when nothing else helped.<br>
        <span class="pk">Something about the sound of it settled everything in me —</span><br>
        <span class="bl">like the world could fall apart and still I'd be held.</span>
      </div>
      <span class="si">💙</span>

      <div class="st">
        <span class="pk">There were nights I lay awake needing one thing —</span><br>
        not answers, not distance, not the absence of pain.<br>
        <span class="lv">Just you. Your arms. Your quiet. Your warmth beside me.</span><br>
        <span class="bl">Just the world shrinking to the sound of your breathing again.</span>
      </div>
      <span class="si">🌷</span>

      <div class="st">
        <span class="bl">Cutie Pie — God, you were so soft in the best ways.</span><br>
        The ways that disarm you before you know what happened.<br>
        <span class="pk">You'd laugh and I'd forget every heavy thing I was carrying.</span><br>
        <span class="lv">You were the relief I didn't know how to ask for, but I was always glad I had it.</span>
      </div>
      <span class="si">✨</span>

      <div class="st">
        <span class="lv">You held me without ever making me feel like a burden.</span><br>
        <span class="pk">You cared without keeping score — that is so rare, Niku, so rare.</span><br>
        Most people love with conditions stitched into every seam.<br>
        <span class="bl">You loved simply. Fully. Like it was the most natural thing you could do.</span>
      </div>
      <span class="si">🌸</span>

      <div class="st">
        <span class="pk">And even now, across whatever distance or silence sits between us,</span><br>
        <span class="lv">I find myself smiling when I think of you — involuntarily, helplessly.</span><br>
        <span class="bl">Because you weren't just someone I loved.</span><br>
        You were someone who made me feel like love itself was possible.
      </div>
      <span class="si">💜</span>

      <div class="st">
        So on this August birthday — hear every word I mean:<br>
        <span class="pk">You deserve oceans and open skies and arms that hold you just right.</span><br>
        <span class="lv">You deserve to be someone's favourite thought every single morning.</span><br>
        <span class="bl">Happy Birthday, my beautiful Nikitha. I hope today holds you like I always wanted to.</span>
      </div>

    </div>
  </div>
</section>

<div class="dvd reveal"><div class="dl dl-l"></div><span class="di">💜</span><div class="dl dl-l"></div></div>

<!-- ══ MEMORIES ══ -->
<section id="memories">
  <p class="slbl reveal">— the things I hold closest —</p>
  <h2 class="mem-title reveal">Everything That Was You</h2>
  <div class="mem-grid reveal">
    <div class="mc">
      <span class="mi">🌙</span>
      <p class="mh">The late night conversations</p>
      <p class="mt">We'd start talking about nothing and somehow end up saying everything. Those were the hours I felt most alive — most like myself. I never wanted them to end, Niku. Not once.</p>
    </div>
    <div class="mc">
      <span class="mi">🤗</span>
      <p class="mh">The way you held me</p>
      <p class="mt">There is a specific kind of safety in being held by the right person. I found it in you. Your arms were the place the whole world went quiet. That is not something I will ever forget or replace.</p>
    </div>
    <div class="mc">
      <span class="mi">😂</span>
      <p class="mh">Your uncontrollable laugh</p>
      <p class="mt">The real one. The one you tried to hold in but couldn't. It would come out and instantly I'd start laughing too — before I even knew what was funny. Your joy was contagious in a way that felt like medicine.</p>
    </div>
    <div class="mc">
      <span class="mi">💆</span>
      <p class="mh">How you knew</p>
      <p class="mt">Before I said a word. Before I admitted it even to myself. You'd look at me and just know I wasn't okay. And then you'd do something so quietly perfect — just be there. That is a rare and beautiful gift.</p>
    </div>
    <div class="mc">
      <span class="mi">🌸</span>
      <p class="mh">Your softness</p>
      <p class="mt">Not weakness — softness. There is a difference and you lived in it. The way you were tender with people, with me. I have never met anyone who cared so gently. It changed how I understood love.</p>
    </div>
    <div class="mc">
      <span class="mi">💫</span>
      <p class="mh">Being chosen by you</p>
      <p class="mt">Every moment you chose to let me in — to call me, to lean on me, to share yourself with me — I was aware of it like a privilege. Being your person, even for a while, was one of the greatest things that ever happened to me.</p>
    </div>
    <div class="mc">
      <span class="mi">🌟</span>
      <p class="mh">Your voice</p>
      <p class="mt">On good days, it was sunshine. On hard days, it was the warmest blanket in the world. I would hear your voice and everything would recalibrate. You had that power, Niku. You always did.</p>
    </div>
    <div class="mc">
      <span class="mi">🫶</span>
      <p class="mh">How you made me feel</p>
      <p class="mt">Seen. Chosen. Enough. Not despite my flaws but alongside them. You looked at me like I was worth looking at, and that — that changed me in ways I am still discovering. Thank you for that, truly.</p>
    </div>
    <div class="mc">
      <span class="mi">🌺</span>
      <p class="mh">Every small ordinary moment</p>
      <p class="mt">The ordinary days with you were the extraordinary ones. Not the grand gestures — just you existing nearby, talking, laughing, being. Those simple moments are the ones I treasure most deeply.</p>
    </div>
  </div>
</section>

<div class="dvd reveal"><div class="dl dl-b"></div><span class="di">💙</span><div class="dl dl-b"></div></div>

<!-- ══ LOVE LETTER ══ -->
<section id="letter">
  <p class="slbl reveal">— a letter I have been writing in my heart for a long time —</p>
  <div class="letter-wrap reveal">
    <div class="letter-paper">
      <div class="drop-cap-wrap">
        <span class="drop-n">N</span>
        <span class="drop-rest">ikitha,</span>
      </div>
      <div class="letter-body">

        <p>My love. My Niku. My Jaan.<br>
        It is August 10th — your birthday — and I need you to know something before you read another word: <span class="hl-p">I am so endlessly, overwhelmingly glad that you exist.</span> Not for what you gave me. Not for what we were. Simply because a world with Nikitha in it is a better world, and I have always known that.</p>

        <p>I have been wanting to say this for a long time. Wanting to find words worthy of you. I'm not sure they exist — but I'll try, because you deserve more than silence and more than assumption. You deserve to know exactly how deeply you were loved.</p>

        <div class="letter-break">· · ·</div>

        <p><span class="hl-l">I need to tell you about the hugs.</span> I know that sounds simple but please hear me — there were so many moments when the weight of everything became too much, when I was holding myself together with the thinnest thread, and all I wanted — all I needed — was you. Your arms around me. The specific warmth of you. The way time stopped when you held me. <span class="hl-p">I needed that more than I ever told you, and I'm sorry I didn't say it louder while I had the chance.</span></p>

        <p>I needed your comfort the way you need air after being underwater too long. Not as weakness — as need. As the truest kind of human need. <span class="hl-b">You were the person in the whole world who could make hard things feel survivable just by being present.</span> I would hear your voice and something in me that had been braced for impact would finally, finally relax. That is not nothing, Niku. That is everything.</p>

        <p>There were nights I wanted to call you and say nothing except: <span class="hl-p">"I just need you near me."</span> Not to fix anything. Not to talk anything through. Just your presence — your quiet, warm, extraordinary presence — because it was the closest thing I have ever found to peace. You were my peace, Jaan. In all this loud and spinning world, you were where I came to be still.</p>

        <div class="letter-break">· · ·</div>

        <p><span class="hl-l">I loved you in the way that changes a person.</span> Not a temporary, surface-level kind of love. The kind that quietly restructures how you see everything. After loving you, I understood tenderness differently. I understood patience differently. I understood what it meant to be truly, completely seen by another person — because you saw me. All of me. And you didn't look away.</p>

        <p>I loved you when you were radiant and sure of yourself, standing in a room like you belonged in every room. And I loved you in the 3am versions of you — the ones you showed very few people — soft, uncertain, searching. <span class="hl-p">I loved every single version. Not in spite of the harder ones. Because of them.</span> Because you trusted me with them, and that trust was the most sacred thing anyone has ever given me.</p>

        <p>I loved the way you laughed before you could stop yourself. I loved the way you'd get excited about small things and your whole face would change. I loved how you cared for people — not performatively, but from somewhere deep and real inside you. <span class="hl-b">I loved that you were soft in a world that tells everyone to be hard. That took more courage than you ever gave yourself credit for.</span></p>

        <div class="letter-break">· · ·</div>

        <p>I want you to know — whatever happened between us — <span class="hl-l">I never stopped loving you. Not even close.</span> Things get complicated and people make mistakes and sometimes the most heartbreaking thing in the world is that love is not always enough to hold everything together. But the love was always there, Niku. It still is. It will be.</p>

        <p><span class="hl-p">You were never the problem. You were always the most beautiful thing in the equation.</span> And if I ever made you feel otherwise — if I ever let you question for even a single second how deeply you were cherished — then I am sorry. From the very depths of everything I am. You deserved better than my worst moments. You deserved my best ones, every day.</p>

        <p>I think about you and I feel this enormous, aching tenderness. This wanting-the-very-best-for-you that doesn't ask for anything in return. <span class="hl-b">I think: I hope she knows. I hope she feels it. I hope someone is holding her the way she deserves to be held.</span> And then I think: I hope it is someone who knows how rare she is. Someone who doesn't take a single second with her for granted.</p>

        <div class="letter-break">· · ·</div>

        <p>On your birthday, Cutie Pie, here is what I wish for you with every cell of my being:</p>

        <p><span class="hl-p">I wish you mornings that arrive gently</span> — the kind where you wake up and for a moment everything feels possible. I wish you friendships so deep and real that you forget what loneliness feels like. I wish you someone who looks at you across a room and still can't quite believe their luck, every single day, for the rest of your life.</p>

        <p><span class="hl-l">I wish you peace with yourself.</span> The kind that comes from finally knowing — truly knowing — that you are enough. That you were always enough. That every person who ever made you feel small was simply too limited to hold someone as large as you. You were never too much, Niku. You were exactly right.</p>

        <p><span class="hl-b">I wish you joy that surprises you.</span> The kind that shows up uninvited on a random Wednesday afternoon and makes you put your hand over your heart because it's almost too much. You deserve that kind of joy. The overwhelming, unexpected, this-is-what-life-is-for kind. Over and over, for the rest of your beautiful life.</p>

        <div class="letter-break">· · ·</div>

        <p>I made this for you because I never want you to feel alone on your birthday. Because I know what it is to wonder if anyone is thinking of you. <span class="hl-p">I want you to feel it as you read this: someone is thinking of you. Someone is hoping, with everything they have, that today is soft and warm and full of love for you.</span></p>

        <p>You gave me a home in a person. That is the most profound thing anyone has ever done for me. And no matter where life takes us, no matter what the seasons bring — <span class="hl-l">I will carry that with me always. You will always be the one who taught me what it felt like to be held, truly held, by another soul.</span></p>

        <p>So happy birthday, my beautiful, irreplaceable Nikitha. <span class="hl-p">Thank you for your laugh. Thank you for your warmth. Thank you for your hugs that made the world stop spinning.</span> Thank you for every night you stayed, every morning you showed up, every moment you chose to let me in.</p>

        <p><span class="hl-b">This world is immeasurably richer because you are in it.</span><br>
        I love you. I have always loved you. I always will.</p>

      </div>
      <p class="letter-sign">
        Always, completely, yours<br>
        <small>across every season — forever</small>
      </p>
    </div>
  </div>
</section>

<div class="dvd reveal"><div class="dl dl-p"></div><span class="di">🌸</span><div class="dl dl-p"></div></div>

<!-- ══ THINGS I MISS ══ -->
<section id="miss">
  <p class="slbl reveal">— things I hold quietly in my heart —</p>
  <h2 class="miss-title reveal">What I Miss Most About You, Niku</h2>
  <div class="miss-list reveal">
    <div class="miss-item"><span class="miss-dot">🌸</span><span class="miss-text">The way I felt when you said my name — like I was the most important person in the room. Like I mattered. I have never found that anywhere else.</span></div>
    <div class="miss-item"><span class="miss-dot">💜</span><span class="miss-text">Your hugs. God, your hugs. The way everything — every worry, every weight — would just evaporate the second your arms were around me.</span></div>
    <div class="miss-item"><span class="miss-dot">💙</span><span class="miss-text">Hearing your voice when I was having a hard day. There was no medicine as effective as you simply existing on the other end of a call.</span></div>
    <div class="miss-item"><span class="miss-dot">🌸</span><span class="miss-text">The version of me I was when I was with you. Lighter. Softer. More willing to be open. You brought out the best of me, Jaan. You really did.</span></div>
    <div class="miss-item"><span class="miss-dot">💜</span><span class="miss-text">Having someone to share the small things with — a song, a funny thought, a moment that would have meant nothing to anyone else but everything to us.</span></div>
    <div class="miss-item"><span class="miss-dot">💙</span><span class="miss-text">The quiet. The specific, perfect quiet of being with you and not needing to fill it. That kind of comfort with another person is extraordinarily rare.</span></div>
    <div class="miss-item"><span class="miss-dot">🌸</span><span class="miss-text">Simply, plainly: you. Every part of you. The whole Nikitha — Niku, Jaan, Cutie Pie — all of it, all of her, all the time.</span></div>
  </div>
</section>

<div class="dvd reveal"><div class="dl dl-l"></div><span class="di">💜</span><div class="dl dl-l"></div></div>

<!-- ══ REASONS ══ -->
<section id="reasons">
  <p class="slbl reveal">— because you should always know —</p>
  <h2 class="reasons-title reveal">Why You Are The Most Special Person</h2>
  <div class="rlist reveal">
    <div class="ri"><span class="rn">✦</span><span class="rt">The way you love — wholly, genuinely, without holding back. In a world of people who love with conditions and exits already planned, you loved with your whole self. That is extraordinary.</span></div>
    <div class="ri"><span class="rn">✦</span><span class="rt">Your laugh — the real one, uncontrollable and unguarded. It is one of the most beautiful sounds I have ever heard and I would do ridiculous things just to hear it again.</span></div>
    <div class="ri"><span class="rn">✦</span><span class="rt">How you notice the people around you. The sadness behind someone's smile, the need behind someone's silence. You see people — really see them — and that is a gift most people never receive.</span></div>
    <div class="ri"><span class="rn">✦</span><span class="rt">Your strength, which you wear quietly and often mistake for something less. You have carried things that would have broken other people. You are so much stronger than you know, Niku.</span></div>
    <div class="ri"><span class="rn">✦</span><span class="rt">The warmth of you — physical and otherwise. Being near you feels like being near something good and safe. People feel it. I felt it every single time.</span></div>
    <div class="ri"><span class="rn">✦</span><span class="rt">Your softness in a world that rewards hardness. You stayed tender. You kept choosing kindness. That took more courage than anyone gives you credit for.</span></div>
    <div class="ri"><span class="rn">✦</span><span class="rt">The comfort you give. There is no one alive who could comfort me the way you could. Whatever that is — magic, chemistry, simply you — it belongs entirely to you and it is irreplaceable.</span></div>
    <div class="ri"><span class="rn">✦</span><span class="rt">How you made ordinary moments feel significant. A regular evening, a random conversation — everything felt more alive when you were in it. You have that effect on the world.</span></div>
    <div class="ri"><span class="rn">✦</span><span class="rt">And simply, most importantly: you are one of a kind. There is no one else like you. There will never be. The world is a different place because you are in it — better, warmer, more worth being alive in.</span></div>
  </div>
</section>

<div class="dvd reveal"><div class="dl dl-b"></div><span class="di">💙</span><div class="dl dl-b"></div></div>

<!-- ══ WISH ══ -->
<section id="wish">
  <h2 class="wish-title reveal">Make a Wish, My Niku 🕯️</h2>
  <p class="wish-sub reveal">Close your beautiful eyes. Breathe. Wish for everything your heart quietly holds.</p>
  <div class="cake-wrap reveal">
    <div class="crows">
      <div class="crow">
        <div class="candle fp"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fl"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fb"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fp"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fl"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fb"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fp"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fl"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fb"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
        <div class="candle fp"><div class="flame"></div><div class="cbody"><div class="drip"></div></div></div>
      </div>
      <div class="ctier ct3"><span class="ctext">for the most beloved</span></div>
      <div class="ctier ct2"><span class="ctext">our Niku, our Jaan</span></div>
      <div class="ctier ct1"><span class="ctext">Happy Birthday Nikitha ✨</span></div>
    </div>
  </div>
  <p class="wish-msg reveal">
    Every single candle on this cake is a wish for you.<br>
    For the love that finds you and stays.<br>
    For the peace that settles in your bones.<br>
    For every good thing — all of it, all at once, endlessly —<br>
    because that is exactly what you deserve, Niku. Every bit of it.
  </p>
</section>

<!-- ══ CLOSING LETTER ══ -->
<section id="closing-letter">
  <div class="cl-card reveal">
    <span class="cl-icon">💌</span>
    <h2 class="cl-title">One Last Thing, Jaan</h2>
    <div class="cl-body">
      <p>If you are crying right now, I want you to know — those are the good tears. The kind that remind you that you are loved. That you were loved. That you will always, always be loved.</p>
      <p>Somewhere out there, right now, someone is thinking of you with the most tender, aching, full-hearted warmth. Someone remembers the sound of your laugh and smiles without meaning to. Someone hopes — more than they can say — that you are okay. That you are happy. That life is giving you everything you deserve.</p>
      <p><span class="hl-p">That someone is me, Niku. That has never changed and it never will.</span></p>
      <p>So on this birthday — please know: you are not forgotten. You are not ordinary. You are not just someone who passed through. <span class="hl-l">You are the kind of person who rewrites the people who love you. You rewrote me.</span></p>
      <p><span class="hl-b">Please come find me. Hug me the way only you can. Let me hold you back. Let me remind you in person what every word on this page has been trying to say.</span></p>
      <p>Happy Birthday, my beautiful, irreplaceable Nikitha.<br>
      <em>I love you. I love you. I love you.</em></p>
    </div>
  </div>
</section>

<!-- ══ FINAL ══ -->
<section id="final">
  <p class="final-name reveal">Nikitha</p>
  <p class="final-date reveal">August 10 &nbsp;·&nbsp; Always Loved &nbsp;·&nbsp; Forever Remembered &nbsp;·&nbsp; Endlessly Cherished</p>
</section>

<script>
// STARS
const cv=document.getElementById('stars'),cx=cv.getContext('2d');
let W,H,stars=[];
function resize(){W=cv.width=window.innerWidth;H=cv.height=window.innerHeight;}
function initStars(){stars=Array.from({length:280},()=>({x:Math.random()*W,y:Math.random()*H,r:Math.random()*1.6+.2,a:Math.random(),da:Math.random()*.007+.002,speed:Math.random()*.1+.03,hue:Math.random()<.33?'255,180,220':Math.random()<.5?'200,160,255':'170,210,255'}));}
function drawStars(){cx.clearRect(0,0,W,H);stars.forEach(s=>{s.a+=s.da;if(s.a>1||s.a<0)s.da*=-1;cx.beginPath();cx.arc(s.x,s.y,s.r,0,Math.PI*2);const g=cx.createRadialGradient(s.x,s.y,0,s.x,s.y,s.r*3);g.addColorStop(0,`rgba(${s.hue},${s.a})`);g.addColorStop(1,'transparent');cx.fillStyle=g;cx.fill();s.y-=s.speed;if(s.y<-2){s.y=H+2;s.x=Math.random()*W;}});requestAnimationFrame(drawStars);}
resize();initStars();drawStars();
window.addEventListener('resize',()=>{resize();initStars();});

// PETALS
const petals=['🌸','🌺','🌷','💮','❀','✿'];
function spawnPetal(){const p=document.createElement('div');p.className='petal';p.textContent=petals[Math.floor(Math.random()*petals.length)];p.style.left=Math.random()*100+'vw';p.style.fontSize=(.6+Math.random()*.9)+'rem';const d=8+Math.random()*11;p.style.animationDuration=d+'s';p.style.animationDelay=(Math.random()*5)+'s';document.body.appendChild(p);setTimeout(()=>p.remove(),(d+6)*1000);}
for(let i=0;i<24;i++)setTimeout(spawnPetal,i*400);
setInterval(spawnPetal,1400);

// HEARTS
const hearts=['💕','💜','💙','🩷','💗','🤍','💖','💝'];
function spawnHeart(){const h=document.createElement('div');h.className='fheart';h.textContent=hearts[Math.floor(Math.random()*hearts.length)];h.style.left=Math.random()*100+'vw';h.style.bottom='0';h.style.fontSize=(.45+Math.random()*.7)+'rem';const d=6+Math.random()*9;h.style.animationDuration=d+'s';h.style.animationDelay=Math.random()*4+'s';document.body.appendChild(h);setTimeout(()=>h.remove(),(d+5)*1000);}
for(let i=0;i<14;i++)setTimeout(spawnHeart,i*800);
setInterval(spawnHeart,1800);

// REVEAL
const revs=document.querySelectorAll('.reveal');
const obs=new IntersectionObserver(entries=>{entries.forEach((e,i)=>{if(e.isIntersecting){setTimeout(()=>e.target.classList.add('visible'),i*60);obs.unobserve(e.target);}});},{threshold:.08});
revs.forEach(r=>obs.observe(r));
</script>
</body>
</html>      
