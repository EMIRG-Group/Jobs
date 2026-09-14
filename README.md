<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Canada's labour market — September 2026</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wdth,wght@62..125,100..900&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --paper:#E7EAEA; --panel:#FCFDFD;
  --ink:#131F27; --ink2:#4C5C66; --ink3:#83919A;
  --rule:#C7CFD2; --hair:#DCE1E3;
  --grow:#146049; --growSoft:#A6CCBD;
  --fall:#9A3724; --fallSoft:#DCAC9D;
  --steel:#1D4C77; --steelSoft:#B9CDDD;
  --ochre:#8A6A14;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--ink);
  font-family:"IBM Plex Sans",-apple-system,BlinkMacSystemFont,sans-serif;
  font-size:14.5px;line-height:1.5;-webkit-font-smoothing:antialiased;font-variant-numeric:tabular-nums}
h1,h2,h3,h4{font-family:"Archivo",sans-serif;font-variation-settings:'wdth' 110;margin:0;line-height:1.05;letter-spacing:-.015em}
:focus-visible{outline:2px solid var(--steel);outline-offset:3px}

.shell{display:grid;grid-template-columns:184px 1fr;max-width:1160px;margin:0 auto}
.rail{position:sticky;top:0;align-self:start;height:100vh;padding:40px 20px 30px 26px;border-right:1px solid var(--rule)}
.mark{font-family:"Archivo";font-variation-settings:'wdth' 86;font-weight:700;font-size:12.5px;line-height:1.3;margin-bottom:28px}
.mark span{display:block;color:var(--ink3);font-weight:400}
.rail nav{display:flex;flex-direction:column}
.rail a{padding:5px 0 5px 12px;text-decoration:none;color:var(--ink2);font-size:13px;border-left:2px solid transparent;transition:.15s}
.rail a:hover{color:var(--ink)}
.rail a.on{color:var(--ink);border-left-color:var(--steel);font-weight:500}
.railfoot{position:absolute;bottom:30px;left:26px;right:20px;font-size:11px;color:var(--ink3);line-height:1.45}

main{padding:40px 52px 96px;min-width:0}
section{scroll-margin-top:24px;padding-top:66px}
section:first-of-type{padding-top:0}
.sh{display:flex;align-items:baseline;gap:16px;border-bottom:1px solid var(--ink);padding-bottom:7px;margin-bottom:24px}
.sh h2{font-size:21px;font-weight:700;font-variation-settings:'wdth' 106}
.sh p{margin:0 0 0 auto;font-size:12px;color:var(--ink3);text-align:right}

h1{font-size:clamp(32px,5vw,54px);font-weight:800;font-variation-settings:'wdth' 118;max-width:13ch}
.dek{margin:18px 0 0;font-size:16px;color:var(--ink2);max-width:52ch;line-height:1.5}
.stamp{font-size:11.5px;color:var(--ink3);margin-bottom:16px}
.strip{display:grid;grid-template-columns:repeat(6,1fr);border-top:1px solid var(--ink);border-bottom:1px solid var(--rule);margin-top:34px}
.strip div{padding:12px 12px 13px 0;border-right:1px solid var(--hair);display:flex;flex-direction:column}
.strip div:last-child{border-right:0}
.k{font-size:11px;color:var(--ink3);line-height:1.3}
.v{font-family:"Archivo";font-variation-settings:'wdth' 98;font-weight:700;font-size:21px;line-height:1;margin-top:auto;padding-top:14px}
.d{font-size:11px;margin-top:5px;color:var(--ink2)}
.up{color:var(--grow)}.down{color:var(--fall)}

/* ladder */
.toggle{display:inline-flex;border:1px solid var(--ink);margin-bottom:16px}
.toggle button{font:inherit;font-size:12.5px;background:none;border:0;padding:5px 14px;cursor:pointer;color:var(--ink2)}
.toggle button+button{border-left:1px solid var(--ink)}
.toggle button[aria-pressed="true"]{background:var(--ink);color:var(--panel);font-weight:500}
.ladder{border-top:1px solid var(--hair)}
.lrow{display:grid;grid-template-columns:168px 1fr 74px;align-items:stretch;width:100%;text-align:left;
  background:none;border:0;border-bottom:1px solid var(--hair);padding:0;font:inherit;color:inherit;cursor:pointer}
.lrow:hover .ln,.lrow[aria-current="true"] .ln{color:var(--ink);font-weight:500}
.lrow[aria-current="true"]{background:var(--panel)}
.ln{padding:0 14px 0 0;text-align:right;font-size:12.5px;color:var(--ink2);display:flex;align-items:center;justify-content:flex-end}
.lt{position:relative;height:28px;border-left:1px solid var(--hair);border-right:1px solid var(--hair)}
.ax{position:absolute;left:50%;top:0;bottom:0;width:1px;background:var(--ink3)}
.bar{position:absolute;top:7px;height:13px;width:0;transition:width .7s cubic-bezier(.2,.7,.3,1)}
.bar.pos{left:50%;background:var(--grow)}
.bar.neg{background:var(--fall)}
.lv{padding:0 0 0 12px;font-size:12.5px;font-weight:500;display:flex;align-items:center}
.detail{background:var(--panel);border:1px solid var(--rule);padding:16px 20px;margin-top:18px}
.detail h3{font-size:16px;font-weight:700}
.figs{display:flex;gap:26px;flex-wrap:wrap;margin:11px 0;padding-bottom:12px;border-bottom:1px solid var(--hair)}
.figs div{font-size:11px;color:var(--ink3)}
.figs b{display:block;font-family:"Archivo";font-weight:700;font-size:17px;color:var(--ink);margin-top:3px}
.detail p{margin:0;font-size:13.5px;color:var(--ink2);max-width:74ch}

/* plot */
.plotwrap{margin-top:36px;border-top:1px solid var(--hair);padding-top:16px}
.plothead{display:flex;align-items:baseline;gap:14px;margin-bottom:6px;flex-wrap:wrap}
.plothead h3{font-size:14px;font-weight:700;font-variation-settings:'wdth' 100}
.plothead p{margin:0;font-size:11.5px;color:var(--ink3)}
.plotbox{overflow-x:auto}
svg{display:block}
.gl{stroke:var(--hair);stroke-width:1}
.zl{stroke:var(--ink3);stroke-width:1;stroke-dasharray:3 3}
.tk{font-size:10px;fill:var(--ink3)}
.axname{font-size:10.5px;fill:var(--ink2)}
.zone{font-size:10px;fill:var(--ink3)}
.lead{stroke:var(--ink3);stroke-width:.7;opacity:.55}
.dl{font-size:10.5px;fill:var(--ink2)}

/* three minis */
.trio{display:grid;grid-template-columns:repeat(3,1fr);border-top:1px solid var(--ink)}
.mini{padding:18px 26px 20px 0;border-right:1px solid var(--rule)}
.mini:last-child{border-right:0;padding-right:0}
.mini+.mini{padding-left:26px}
.mini h4{font-size:14px;font-weight:700;font-variation-settings:'wdth' 100;margin-bottom:3px}
.mcap{font-size:11.5px;color:var(--ink3);margin:0 0 16px;line-height:1.4}
.mrow{display:grid;grid-template-columns:74px 1fr 52px;align-items:center;gap:10px;margin-bottom:8px;font-size:11.5px}
.mrow .lab{color:var(--ink2);text-align:right;line-height:1.2}
.mtrack{height:15px;background:var(--hair);position:relative}
.mtrack i{position:absolute;top:0;bottom:0;width:0;transition:width .7s cubic-bezier(.2,.7,.3,1),left .7s}
.mtrack .ref{position:absolute;top:-4px;bottom:-4px;width:1px;background:var(--ochre)}
.mrow .num{font-weight:500;text-align:right}
.reflab{display:grid;grid-template-columns:74px 1fr 52px;gap:10px;font-size:10.5px;color:var(--ochre);margin-bottom:5px}
.reflab span:nth-child(2){position:relative}
.reflab em{position:absolute;font-style:normal;transform:translateX(-50%);white-space:nowrap}
.mfoot{font-size:11px;color:var(--ink3);margin-top:12px;line-height:1.5}

/* tracks */
.tracks{display:grid;grid-template-columns:1fr 1fr;border-top:1px solid var(--ink)}
.track:first-child{border-right:1px solid var(--rule)}
.th{padding:11px 22px 12px 0;font-family:"Archivo";font-weight:700;font-size:14px;font-variation-settings:'wdth' 100}
.th small{display:block;font-family:"IBM Plex Sans";font-weight:400;font-size:11.5px;color:var(--ink3);margin-top:3px}
.track:last-child .th,.track:last-child .it,.track:last-child .firm{padding-left:22px;padding-right:0}
.it{padding:10px 22px 11px 0;border-top:1px solid var(--hair)}
.it .t{font-weight:500;font-size:13.5px;line-height:1.3}
.it .w{font-size:12px;color:var(--ink2);margin-top:3px;line-height:1.45}
.ex{display:flex;align-items:center;gap:8px;margin-top:7px}
.exbar{height:3px;flex:0 0 96px;background:var(--hair);position:relative}
.exbar i{position:absolute;left:0;top:0;bottom:0;width:0;transition:width .6s}
.exlab{font-size:10.5px;color:var(--ink3);white-space:nowrap}

.firm{padding:10px 22px 11px 0;border-top:1px solid var(--hair);display:grid;grid-template-columns:1fr auto;gap:14px;align-items:start}
.firm .t{font-weight:500;font-size:13.5px;line-height:1.3}
.firm .w{font-size:12px;color:var(--ink2);line-height:1.45;margin-top:3px}
.tag{font-size:10.5px;color:var(--ink3);white-space:nowrap;border:1px solid var(--hair);padding:2px 7px;margin-top:1px}

/* forces */
.force{border-top:1px solid var(--hair)}
.force:last-child{border-bottom:1px solid var(--hair)}
.fb{width:100%;display:grid;grid-template-columns:1fr auto;gap:18px;align-items:start;background:none;border:0;
  padding:13px 0;font:inherit;text-align:left;color:inherit;cursor:pointer}
.fb:hover .ft{color:var(--steel)}
.ft{font-family:"Archivo";font-weight:700;font-size:15px;font-variation-settings:'wdth' 102;display:block}
.fs{font-size:12px;color:var(--ink2);margin-top:3px;display:block;max-width:64ch;line-height:1.45}
.fsg{font-size:10.5px;color:var(--ink3);white-space:nowrap;padding-top:3px}
.fbody{display:none;padding:0 0 18px}
.force.open .fbody{display:block}
.fbody ul{margin:0;padding-left:18px;font-size:13px;color:var(--ink2);max-width:70ch;line-height:1.5}
.fbody li{margin-bottom:5px}
.fbody .so{font-size:10.5px;color:var(--ink3);margin:10px 0 0}

/* capital */
.caps{display:grid;grid-template-columns:repeat(3,1fr);border-top:1px solid var(--ink)}
.cp{padding:15px 22px 17px 0;border-right:1px solid var(--rule);border-bottom:1px solid var(--hair)}
.cp:nth-child(3n){border-right:0;padding-right:0}
.cp:not(:nth-child(3n+1)){padding-left:22px}
.cp h4{font-size:13.5px;font-weight:700;font-variation-settings:'wdth' 100;line-height:1.2}
.cp .amt{font-family:"Archivo";font-weight:700;font-size:18px;color:var(--steel);margin:6px 0 5px;font-variation-settings:'wdth' 94}
.cp p{margin:0;font-size:11.5px;color:var(--ink2);line-height:1.5}
.cp .j{margin-top:9px;font-size:11px;color:var(--ink3);border-left:2px solid var(--growSoft);padding-left:9px;line-height:1.4}

/* provinces */
.prov{border-top:1px solid var(--ink)}
.pr{display:grid;grid-template-columns:158px 1fr 56px 90px;align-items:stretch;border-bottom:1px solid var(--hair);font-size:12.5px}
.pr.h{color:var(--ink3);border-bottom:1px solid var(--rule);font-size:11px}
.pr.h>div{padding-top:5px;padding-bottom:5px}
.pn{padding:0 14px 0 0;display:flex;align-items:center;justify-content:flex-end;text-align:right}
.pt{height:25px;position:relative;border-left:1px solid var(--hair)}
.pb{position:absolute;left:0;top:7px;height:11px;background:var(--steel);width:0;transition:width .7s cubic-bezier(.2,.7,.3,1)}
.pv{padding-left:12px;font-weight:500;display:flex;align-items:center}
.pe{padding-left:12px;color:var(--ink2);display:flex;align-items:center}
.pr.h .pn,.pr.h .pv,.pr.h .pe{display:block;text-align:right}
.pr.h .pv,.pr.h .pe{text-align:left}

/* limits */
.lim{display:grid;grid-template-columns:1fr 1fr;gap:0 36px}
.cav{border-left:2px solid var(--ochre);padding-left:14px;margin-bottom:20px}
.cav h4{font-size:13.5px;font-weight:700;font-variation-settings:'wdth' 100;margin-bottom:3px}
.cav p{margin:0;font-size:12.5px;color:var(--ink2);line-height:1.5}
.src{font-size:11px;color:var(--ink3);line-height:1.65;max-width:80ch;margin-top:16px;border-top:1px solid var(--hair);padding-top:14px}
.src b{color:var(--ink2);font-weight:500}

@media(max-width:920px){
  .shell{grid-template-columns:1fr}
  .rail{position:static;height:auto;border-right:0;border-bottom:1px solid var(--rule);padding:22px 20px}
  .rail nav{flex-direction:row;flex-wrap:wrap;gap:0 14px}
  .rail a{border-left:0;border-bottom:2px solid transparent;padding:4px 0}
  .rail a.on{border-left:0;border-bottom-color:var(--steel)}
  .railfoot{position:static;margin-top:14px}
  main{padding:26px 20px 70px}
  .strip{grid-template-columns:repeat(2,1fr)}
  .strip div{border-bottom:1px solid var(--hair)}
  .trio,.tracks,.caps,.lim{grid-template-columns:1fr}
  .mini,.cp{border-right:0;padding-left:0!important;padding-right:0;border-bottom:1px solid var(--hair)}
  .track:first-child{border-right:0;border-bottom:1px solid var(--ink)}
  .track:last-child .th,.track:last-child .it,.track:last-child .firm{padding-left:0}
  .it,.firm,.th{padding-right:0}
  .lrow{grid-template-columns:104px 1fr 66px}
  .ln{font-size:11.5px}
  .pr{grid-template-columns:102px 1fr 54px}.pe{display:none}
  .plotbox{margin:0 -20px;padding:0 20px}
}
@media(prefers-reduced-motion:reduce){*{transition:none!important;scroll-behavior:auto!important}}
</style>
</head>
<body>
<div class="shell">

<aside class="rail">
  <div class="mark">Canada's labour market<span>September 2026</span></div>
  <nav id="nav">
    <a href="#pulse" class="on">Pulse</a><a href="#sectors">Sectors</a><a href="#signals">Signals</a>
    <a href="#roles">Roles</a><a href="#firms">Firms</a><a href="#forces">Forces</a>
    <a href="#capital">Capital</a><a href="#regions">Regions</a><a href="#limits">Limits</a>
  </nav>
  <div class="railfoot">Statistics Canada Labour Force Survey, August 2026. Seasonally adjusted unless noted.</div>
</aside>

<main>

<section id="pulse">
  <div class="stamp">Reference week 9–15 August 2026</div>
  <h1>Where Canada's jobs are going</h1>
  <p class="dek">The unemployment rate has barely moved in two years. Underneath it, the composition of Canadian work is being rewritten.</p>
  <div class="strip">
    <div><span class="k">Employed</span><span class="v">21.17M</span><span class="d down">&minus;42,000 in August</span></div>
    <div><span class="k">Unemployment</span><span class="v">6.4%</span><span class="d">unchanged</span></div>
    <div><span class="k">Hourly wage</span><span class="v">$37.02</span><span class="d">+2.0% y/y</span></div>
    <div><span class="k">Jobless 27+ weeks</span><span class="v">24.0%</span><span class="d down">was 17.1%</span></div>
    <div><span class="k">Vacancies</span><span class="v">507K</span><span class="d up">first rise since 2022</span></div>
    <div><span class="k">Policy rate</span><span class="v">2.25%</span><span class="d">held 2 Sept</span></div>
  </div>
</section>

<section id="sectors">
  <div class="sh"><h2>Sector ladder</h2><p>All 16 industry groups. Select a row.</p></div>
  <div class="toggle" role="group" aria-label="Period">
    <button id="bY" aria-pressed="true">12 months</button><button id="bM" aria-pressed="false">August</button>
  </div>
  <div class="ladder" id="ladder"></div>
  <div class="detail" id="detail" aria-live="polite"></div>

  <div class="plotwrap">
    <div class="plothead">
      <h3>Size against growth</h3>
      <p>Bubble area is employment. Horizontal position is 12-month change.</p>
    </div>
    <div class="plotbox"><div id="plot"></div></div>
  </div>
</section>

<section id="signals">
  <div class="sh"><h2>Three numbers</h2><p>The rest of the page follows from these.</p></div>
  <div class="trio">

    <div class="mini">
      <h4>Wages stopped keeping up</h4>
      <p class="mcap">12-month wage growth by earnings quartile</p>
      <div class="reflab"><span></span><span><em style="left:92%">inflation 2.3%</em></span><span></span></div>
      <div id="wage"></div>
      <p class="mfoot">Hourly levels: $18.66, $26.61, $37.99, $65.15. Every quartile sits below inflation, but the bottom half loses most.</p>
    </div>

    <div class="mini">
      <h4>Labour supply cut on purpose</h4>
      <p class="mcap">New temporary resident arrivals, target</p>
      <div id="immig"></div>
      <p class="mfoot">A 43% cut in one year; study permits roughly halve. This is why employment fell 42,000 in August while the jobless rate held.</p>
    </div>

    <div class="mini">
      <h4>Canada builds AI, barely uses it</h4>
      <p class="mcap">Share of businesses using AI</p>
      <div id="adopt"></div>
      <p class="mfoot">The displacement has not arrived here yet. Neither has the productivity gain. That is runway, and it is finite.</p>
    </div>

  </div>
</section>

<section id="roles">
  <div class="sh"><h2>Roles</h2><p>Bars show task exposure to current AI, not predicted job loss.</p></div>
  <div class="tracks">
    <div class="track"><div class="th">Opening up<small>Retirements, care demand, committed capital</small></div><div id="rise"></div></div>
    <div class="track"><div class="th">Closing in<small>Fewer postings long before any layoffs</small></div><div id="fall"></div></div>
  </div>
</section>

<section id="firms">
  <div class="sh"><h2>Firms</h2><p>Funding and headcount have decoupled.</p></div>
  <div class="tracks">
    <div class="track"><div class="th">Rising<small>Recent rounds, Canadian footprint</small></div><div id="ch"></div></div>
    <div class="track"><div class="th">Established<small>Position secure, headcount plans less so</small></div><div id="in"></div></div>
  </div>
</section>

<section id="forces">
  <div class="sh"><h2>Forces</h2><p>Select to expand.</p></div>
  <div id="forcelist"></div>
</section>

<section id="capital">
  <div class="sh"><h2>Capital</h2><p>Job figures are government targets, not forecasts.</p></div>
  <div class="caps" id="caps"></div>
</section>

<section id="regions">
  <div class="sh"><h2>Regions</h2><p>Unemployment rate, August 2026.</p></div>
  <div class="prov">
    <div class="pr h"><div class="pn">Province</div><div></div><div class="pv">Rate</div><div class="pe">Employed</div></div>
    <div id="provs"></div>
  </div>
</section>

<section id="limits">
  <div class="sh"><h2>Limits</h2><p>Read before acting on any of the above.</p></div>
  <div class="lim">
    <div class="cav"><h4>Monthly moves are mostly noise</h4><p>The survey samples 65,000 households. A 42,000 swing sits barely outside the standard error. Six-month trends are the signal.</p></div>
    <div class="cav"><h4>Exposure is not job loss</h4><p>Exposure scores measure what AI could do to a job's tasks, not what employers have done. Roughly 90% of AI-adopting Canadian firms report no staffing change.</p></div>
    <div class="cav"><h4>Tariffs move weekly</h4><p>Canada's retaliation on 700+ US products took effect 8 September. Employment effects will not surface in survey data for months.</p></div>
    <div class="cav"><h4>Targets are political documents</h4><p>250,000 AI jobs, 125,000 defence careers, $500B investment: announced objectives with no independent verification. Direction, not quantity.</p></div>
  </div>
  <div class="src"><b>Statistics Canada</b> Labour Force Survey Aug 2026; Job Vacancy and Wage Survey Q1 2026; AI occupational exposure research 2024–26. <b>Bank of Canada</b> rate decision 2 Sept 2026; Monetary Policy Report Apr 2026; early signs of AI-driven labour adjustment, Aug 2026. <b>Government of Canada</b> AI for All strategy; Defence Industrial Strategy; critical minerals programs; 2026–2028 Immigration Levels Plan. <b>BuildForce Canada</b> 2025–2034 outlook. <b>Conference Board of Canada.</b> Company figures from public announcements.</div>
</section>

</main>
</div>

<script>
const sectors=[
{n:"Health care and social assistance",s:"Health care",lvl:3015.9,yoy:129.0,yoyp:4.5,mom:6.0,b:"Nearly 60% of all net job creation over the year. Demand is demographic, so it ignores the cycle. The constraint is training seats and credential recognition, not demand. Lowest AI exposure of any large sector."},
{n:"Information, culture and recreation",s:"Info & culture",lvl:890.1,yoy:49.3,yoyp:5.9,mom:12.0,b:"Fastest percentage growth in the economy. Gains concentrate in data and digital infrastructure; legacy media keeps shrinking inside the aggregate."},
{n:"Transportation and warehousing",s:"Transport",lvl:1120.4,yoy:47.4,yoyp:4.4,mom:-2.6,b:"E-commerce volume plus freight rerouting away from US corridors. Trucking HR Canada projects vacancies above 40,000 by 2030. Autonomy is the long-run risk, not the near-term one."},
{n:"Other services",s:"Other services",lvl:797.0,yoy:26.2,yoyp:3.4,mom:0.3,b:"Repair, personal care, civic organisations. A large share of this growth is self-employment, up 80,000 over the year — part entrepreneurship, part inability to find an employer."},
{n:"Professional, scientific and technical",s:"Professional",lvl:2026.8,yoy:26.0,yoyp:1.3,mom:-4.2,b:"Growing in aggregate, restructuring inside. Senior and licensed roles expand while junior analyst and entry-level coding hiring slows hardest."},
{n:"Manufacturing",s:"Manufacturing",lvl:1847.0,yoy:21.9,yoyp:1.2,mom:22.1,b:"The only significant August gain, almost entirely Ontario. Split sector: export-facing steel, aluminum and lumber contract under 50% tariffs while defence and domestic production hold up."},
{n:"Accommodation and food services",s:"Accommodation",lvl:1193.9,yoy:15.5,yoyp:1.3,mom:-5.7,b:"Modest growth, but a heavy user of temporary foreign workers and international students. The 43% cut to new arrivals removes much of its hiring pool."},
{n:"Construction",s:"Construction",lvl:1647.5,yoy:13.7,yoyp:0.8,mom:1.5,b:"Flat headline hiding a succession gap. One in five workers is over 55. BuildForce projects 270,000 retirements against a 380,000 hiring requirement by 2034."},
{n:"Business and building support",s:"Business support",lvl:687.3,yoy:11.6,yoyp:1.7,mom:-19.9,b:"Largest single-month drop in August, down 20,000. Call centres, admin support, security. The most directly exposed large services category."},
{n:"Natural resources",s:"Natural resources",lvl:331.4,yoy:-0.3,yoyp:-0.1,mom:-7.7,b:"Lumber in multi-year decline, roughly 20% below 2024 exports. Against that, $3.6B in new critical minerals programs — but those projects hire late this decade, not now."},
{n:"Agriculture",s:"Agriculture",lvl:215.2,yoy:-5.1,yoyp:-2.3,mom:-0.6,b:"Exposed on both sides: heaviest user of the Temporary Foreign Worker Program, which takes the sharpest cut, and material direct losses under the 50% tariff scenario."},
{n:"Utilities",s:"Utilities",lvl:156.6,yoy:-7.6,yoyp:-4.6,mom:-5.6,b:"Largest percentage decline, though a small and volatile sector. Watch the other direction: grid expansion for data centres and the Darlington SMR need substantial electrical capacity."},
{n:"Public administration",s:"Public admin",lvl:1231.9,yoy:-13.5,yoyp:-1.1,mom:-8.8,b:"Third consecutive monthly decline. Public sector employment is down 78,000 since May. Government has absorbed graduate hiring for two decades; that absorber is switched off."},
{n:"Finance, insurance and real estate",s:"Finance",lvl:1482.5,yoy:-15.1,yoyp:-1.0,mom:-9.6,b:"Shrinking while the banks are profitable. CIBC has ~50,000 staff on an internal AI assistant; RBC drafts pitch decks with it. The work is not disappearing — the junior seats are."},
{n:"Educational services",s:"Education",lvl:1575.1,yoy:-27.8,yoyp:-1.7,mom:-8.7,b:"Direct casualty of the study permit cap: arrivals cut from 305,000 to 155,000. Institutions built cost structures on international tuition and are restructuring."},
{n:"Wholesale and retail trade",s:"Retail & wholesale",lvl:2954.3,yoy:-55.0,yoyp:-1.8,mom:-10.5,b:"Largest absolute decline in the economy. Slower population growth removes the customer arrivals that propped up expansion, while automation cuts floor staff."}];

const rise=[
{t:"Nurses, LPNs, personal support workers",w:"Health care added 129,000 jobs. Licensing is the bottleneck, not demand.",e:12},
{t:"Electricians, pipefitters, welders, HVAC",w:"Most acute structural shortage in the country. 8,000–9,000 apprenticeship hours means supply cannot respond fast.",e:15},
{t:"Data centre and grid trades",w:"Sovereign compute buildout targets 100+ MW. Every megawatt needs electrical and cooling capacity.",e:14},
{t:"Defence manufacturing and machinists",w:"Strategy targets 125,000 careers against ~$180B direct investment, with Canadian-supplier preference.",e:22},
{t:"Mining engineers and metallurgists",w:"$3.6B in new federal programs, five projects referred to the Major Projects Office.",e:25},
{t:"Machine learning and data engineers",w:"~2,900 open AI engineering roles. 42% of Canadian tech teams report a skills gap.",e:52},
{t:"Cybersecurity and AI assurance",w:"Shortage-risk occupation through 2033. Model evaluation and red-teaming are new job families.",e:38},
{t:"Truck drivers and logistics supervisors",w:"Sector grew 4.4%. Projected vacancies above 40,000 by 2030.",e:33},
{t:"Early childhood educators and care workers",w:"Childcare expansion plus aging population. Wages remain the binding constraint.",e:16}];

const fall=[
{t:"Office clerks and data entry",w:"Statistics Canada identifies clerical work as carrying the highest generative-AI risk of any occupation group.",e:88},
{t:"Customer service and call centre",w:"Support services shed 20,000 in August alone. Routine queries route to internal assistants at scale.",e:82},
{t:"Administrative assistants",w:"Scheduling, drafting and data processing are exactly the task bundle current tools handle well.",e:79},
{t:"Bookkeeping and routine audit",w:"Compliance work grows; transaction processing shrinks. Vacancies down year over year.",e:71},
{t:"Retail cashiers and floor staff",w:"Retail lost 55,000 jobs — the largest absolute decline. Automation compounds a demand shortfall.",e:68},
{t:"Junior analysts and entry-level developers",w:"In coding jobs, under-30 employment was flat while the 30–49 cohort rose nearly 30%. The bottom rung broke.",e:64},
{t:"Articling students and paralegal support",w:"Document review and first drafts were the training tasks that made junior legal roles viable.",e:61},
{t:"Government administrative staff",w:"Public administration down 13,500 over the year. Attrition rather than layoffs.",e:45},
{t:"Export steel, aluminum and lumber production",w:"Steel exports to the US roughly halved. Layoff rate in US-dependent industries: 0.9% vs 0.7% elsewhere.",e:18},
{t:"Post-secondary staff",w:"Educational services lost 27,800 as study permits were cut roughly in half.",e:34}];

const ch=[
{t:"Waabi",w:"Autonomous trucking. US$750M Series C plus ~$250M from Uber — largest raise in Canadian tech history.",g:"Toronto"},
{t:"Cohere",w:"Enterprise LLMs. $500M Series E led by PSP Investments. The domestic option for regulated buyers.",g:"Toronto"},
{t:"Dominion Dynamics",w:"$100M Series A in July — Canada's largest defence-tech Series A to date, per lead investor Georgian.",g:"Defence"},
{t:"Taalas",w:"AI silicon. Bakes models directly into chips. Among the top-scored Canadian AI startups of 2026.",g:"Toronto"},
{t:"Tenstorrent",w:"AI processors. One of few non-US firms with standing in accelerator design.",g:"Toronto"},
{t:"Trulioo",w:"Identity verification. $150M Series D led by Goldman Sachs AM, covering 195+ countries.",g:"Vancouver"},
{t:"Miovision",w:"$120M to scale AI intersection management into US and European smart-city contracts.",g:"Waterloo"},
{t:"Sanctuary AI",w:"Humanoid robotics. Canada's clearest bet on physical rather than knowledge-work automation.",g:"Vancouver"}];

const inc=[
{t:"RBC, CIBC, TD",w:"Profitable, expanding AI internally. CIBC has ~50,000 staff on an internal assistant.",g:"Sector \u221215.1K"},
{t:"Shopify",w:"Headcount down from ~11,600 at peak to ~8,100. Teams must justify why AI cannot do the work first.",g:"Shrinking"},
{t:"Celestica, Hypertec, Ranovus",w:"Compute hardware, cooling, optical interconnect. Named in the national strategy's supply chain.",g:"Hiring"},
{t:"eStruxture, Denvr, ThinkOn",w:"Data centres and sovereign cloud. Residency rules give domestic providers a procurement edge.",g:"Buildout"},
{t:"Bombardier, CAE, Irving, Davie",w:"Defence and aerospace primes positioned against a generational procurement wave.",g:"Hiring"},
{t:"Wealthsimple, Clio, 1Password",w:"Mature scale-ups at $10B, ~$5B and unicorn valuations. Past rapid headcount expansion.",g:"Selective"},
{t:"Telus, Bell, Rogers",w:"Central to the connectivity pillar, and simultaneously running cost reduction.",g:"Flat to down"},
{t:"Mila, Vector, Amii",w:"Not employers at scale but the talent source. Mila alone has 1,400+ researchers.",g:"Pipeline"}];

const forces=[
{t:"Labour supply is being cut deliberately",s:"New temporary resident arrivals fall 43% in one year.",g:"Supply",
b:`<ul><li>Study permit arrivals drop from 305,000 to 155,000. The Temporary Foreign Worker stream takes the sharpest proportional cut.</li>
<li>Permanent resident admissions hold steady at 380,000 through 2028.</li>
<li>Non-permanent residents have fallen from a 7.6% population peak to 6.5%, targeting under 5% by end-2027.</li>
<li>It removes workers from agriculture, construction, hospitality and elder care — and removes consumers from retail, rental housing and education.</li>
<li>It also flatters the jobless rate: a shrinking labour force shrinks the denominator.</li></ul>
<p class="so">IRCC 2026–2028 Immigration Levels Plan</p>`},
{t:"AI is compressing entry, not eliminating jobs",s:"About 60% of jobs are highly exposed. Roughly 90% of adopting firms report no staffing change.",g:"Structural",
b:`<ul><li>Roughly half of exposed roles are complementary rather than substitutable. Complementary roles grew 2.9% over 2023–24 against 1.6% for competing roles.</li>
<li>The Bank of Canada puts the job-finding gap between full-exposure and no-exposure occupations at about &minus;14 points by 2025, from &minus;2 before 2020.</li>
<li>In coding-intensive work, employment for ages 15–29 was flat while ages 30–49 rose nearly 30%.</li>
<li>Long-term unemployment sits at 24.0%, against a 17.1% pre-pandemic average.</li>
<li>The tasks given to juniors — first drafts, data cleaning, document review — were the tasks that taught them the job.</li></ul>
<p class="so">Bank of Canada Aug 2026; Statistics Canada Jan 2026; Conference Board of Canada</p>`},
{t:"A retirement wave training cannot match",s:"Roughly 700,000 tradespeople retire by 2030. One in five construction workers is already over 55.",g:"Demographic",
b:`<ul><li>Apprenticeship registrations hit a record 101,541 in 2024 and the country still falls behind — licensed trades take 8,000–9,000 hours.</li>
<li>BuildForce projects ~270,000 construction retirements against a 380,000 hiring requirement, a potential shortfall near 108,000 by 2034.</li>
<li>Ontario alone needs ~126,100 new construction workers by 2035 as ~92,000 retire.</li>
<li>Non-residential grows 7% to ~700,000 workers by 2035; residential dips through 2028 as population growth slows.</li></ul>
<p class="so">BuildForce Canada 2025–2034 outlook</p>`},
{t:"The tariff wall is narrow but deep",s:"Sectoral tariffs cover ~1% of employment and ~15% of exports.",g:"Trade",
b:`<ul><li>Steel exports to the US have roughly halved under a 50% tariff; production fell less, supported by Buy Canadian procurement and import quotas.</li>
<li>Aluminum exports dropped ~50% before partial redirection to Europe at lower margins. Canada still supplied 60% of US unwrought aluminum imports in H1 2026.</li>
<li>Lumber sits ~20% below 2024 levels, continuing a decline that predates this dispute.</li>
<li>Because intermediate goods cross the border repeatedly in autos and construction materials, compounding cost exceeds the headline rate.</li>
<li>Economist Trevor Tombe puts up to 90,000 jobs at risk in the full 50% scenario.</li></ul>
<p class="so">Bank of Canada tariff analysis; Department of Finance Aug 2026</p>`},
{t:"Wage growth has stalled, and unevenly",s:"Up 2.0% year over year — slowest since 2017. The bottom quartile got 1.1%.",g:"Distribution",
b:`<ul><li>Growth averaged 4.9% across 2023–24, decelerated to 3.4% in 2025, now 2.0%.</li>
<li>With core inflation near 2.3%, the bottom half of the distribution is losing real income while the top half roughly holds.</li>
<li>The labour shortage narrative and the wage data have stopped agreeing — which usually means shortages are concentrated in specific licensed occupations rather than general.</li></ul>
<p class="so">Statistics Canada Aug 2026, not seasonally adjusted</p>`},
{t:"Government has stopped absorbing graduates",s:"Public sector employment down 78,000 since May. Three consecutive monthly declines.",g:"Policy",
b:`<ul><li>Public administration is down 13,500 over the year; public sector employees down 0.4%.</li>
<li>Private sector employees are up 156,000 and self-employment up 80,000 over the same period.</li>
<li>For two decades the public service was a reliable first employer for humanities and social science graduates. That route has narrowed at the same moment entry-level private roles are thinning.</li></ul>
<p class="so">Statistics Canada Aug 2026</p>`}];

const caps=[
{h:"AI for All",a:"~$2B federal",p:"Sovereign compute, a public supercomputer for researchers and SMEs, Canadian data residency, AI literacy for a million students.",j:"Targets 250,000 jobs and 90,000 youth placements by 2031"},
{h:"Defence Industrial Strategy",a:"~$180B investment",p:"Canadian-supplier preference in procurement, domestic defence innovation funding, streamlined acquisition.",j:"Targets 125,000 careers across the supply chain"},
{h:"Critical minerals",a:"$3.6B in programs",p:"$1.5B First and Last Mile Fund for mine infrastructure, $165.2M across 22 projects in eight provinces.",j:"Mining and processing roles, remote and northern"},
{h:"Sovereign compute",a:"Up to $700M public",p:"Public supercomputer, a secure NRC facility, and Canadian AI data capacity scaling to at least 100 MW.",j:"Electrical and cooling trades before any software role"},
{h:"Darlington SMR",a:"First in the G7",p:"First of four units at Bowmanville, Ontario, powering around 300,000 homes.",j:"1,600 construction jobs, 200 long-term"},
{h:"Private investment target",a:"$500B over 5 years",p:"Anchored by a September 2026 Investment Summit on energy, minerals, AI, defence and infrastructure.",j:"A target, not a commitment"}];

const provs=[
{n:"Newfoundland and Labrador",r:8.6,e:"245,000"},{n:"Prince Edward Island",r:7.9,e:"96,000"},
{n:"New Brunswick",r:7.3,e:"409,000"},{n:"Ontario",r:6.9,e:"8,307,000"},
{n:"Alberta",r:6.8,e:"2,661,000"},{n:"British Columbia",r:6.5,e:"2,949,000"},
{n:"Nova Scotia",r:6.1,e:"541,000"},{n:"Saskatchewan",r:6.0,e:"622,000"},
{n:"Quebec",r:5.6,e:"4,589,000"},{n:"Manitoba",r:5.0,e:"756,000"}];

/* ── ladder ─────────────────────────────── */
let mode="yoy",current=sectors[0].n;
const L=document.getElementById('ladder'),D=document.getElementById('detail');
const f=v=>(v>0?"+":v<0?"\u2212":"")+Math.abs(v).toFixed(1)+"K";

function draw(){
  const rows=[...sectors].sort((a,b)=>b[mode]-a[mode]),max=Math.max(...rows.map(r=>Math.abs(r[mode])));
  L.innerHTML="";
  rows.forEach((s,i)=>{
    const v=s[mode],p=(Math.abs(v)/max)*47;
    const b=document.createElement('button');
    b.className='lrow';b.setAttribute('aria-current',s.n===current);
    b.innerHTML=`<span class="ln">${s.s}</span><span class="lt"><span class="ax"></span><span class="bar ${v>=0?'pos':'neg'}"></span></span><span class="lv ${v>=0?'up':'down'}">${f(v)}</span>`;
    b.onclick=()=>sel(s.n);L.appendChild(b);
    const bar=b.querySelector('.bar');
    if(v<0)bar.style.left=(50-p)+'%';
    requestAnimationFrame(()=>setTimeout(()=>bar.style.width=p+'%',i*20));
  });
}
function sel(n){
  current=n;const s=sectors.find(x=>x.n===n);
  D.innerHTML=`<h3>${s.n}</h3><div class="figs">
    <div>Employed<b>${s.lvl.toFixed(1)}K</b></div>
    <div>12-month<b class="${s.yoy>=0?'up':'down'}">${f(s.yoy)}</b></div>
    <div>Percent<b class="${s.yoyp>=0?'up':'down'}">${s.yoyp>0?'+':'\u2212'}${Math.abs(s.yoyp)}%</b></div>
    <div>August<b class="${s.mom>=0?'up':'down'}">${f(s.mom)}</b></div></div><p>${s.b}</p>`;
  [...L.children].forEach(r=>r.setAttribute('aria-current',r.querySelector('.ln').textContent===s.s));
}
document.getElementById('bY').onclick=()=>{mode="yoy";tog();draw()};
document.getElementById('bM').onclick=()=>{mode="mom";tog();draw()};
function tog(){document.getElementById('bY').setAttribute('aria-pressed',mode==="yoy");
  document.getElementById('bM').setAttribute('aria-pressed',mode==="mom")}

/* ── bubble chart ───────────────────────── */
(function(){
  const W=880,H=420,ml=58,mr=136,mt=30,mb=52;
  const xmin=-6,xmax=7,ymax=3400;
  const X=v=>ml+((v-xmin)/(xmax-xmin))*(W-ml-mr);
  const Y=v=>H-mb-(v/ymax)*(H-mt-mb);
  const R=v=>Math.sqrt(v/Math.PI)*0.72;          // area-proportional
  const esc=s=>s.replace(/&/g,'&amp;').replace(/</g,'&lt;');
  let g='';

  // horizontal gridlines + y ticks
  [0,1000,2000,3000].forEach(t=>{
    g+=`<line class="gl" x1="${ml}" y1="${Y(t).toFixed(1)}" x2="${W-mr}" y2="${Y(t).toFixed(1)}"/>`;
    g+=`<text class="tk" x="${ml-10}" y="${(Y(t)+3.5).toFixed(1)}" text-anchor="end">${t?t/1000+'M':'0'}</text>`;
  });
  g+=`<text class="axname" x="${ml-10}" y="${mt-10}" text-anchor="end">Employed</text>`;

  // x ticks + baseline
  g+=`<line class="gl" x1="${ml}" y1="${H-mb}" x2="${W-mr}" y2="${H-mb}"/>`;
  [-6,-4,-2,0,2,4,6].forEach(t=>{
    g+=`<line class="gl" x1="${X(t).toFixed(1)}" y1="${H-mb}" x2="${X(t).toFixed(1)}" y2="${H-mb+5}"/>`;
    g+=`<text class="tk" x="${X(t).toFixed(1)}" y="${H-mb+18}" text-anchor="middle">${t>0?'+':t<0?'\u2212':''}${Math.abs(t)}%</text>`;
  });
  g+=`<text class="axname" x="${((ml+W-mr)/2).toFixed(1)}" y="${H-mb+36}" text-anchor="middle">12-month change in employment</text>`;

  // zero line + zone labels
  g+=`<line class="zl" x1="${X(0).toFixed(1)}" y1="${mt}" x2="${X(0).toFixed(1)}" y2="${H-mb}"/>`;
  g+=`<text class="zone" x="${(X(0)-8).toFixed(1)}" y="${mt+2}" text-anchor="end">shrinking</text>`;
  g+=`<text class="zone" x="${(X(0)+8).toFixed(1)}" y="${mt+2}">growing</text>`;

  // points
  const pts=sectors.map(d=>({d,x:X(d.yoyp),y:Y(d.lvl),r:R(d.lvl)}));
  pts.sort((a,b)=>b.r-a.r);   // big bubbles behind
  pts.forEach(p=>{
    const c=p.d.yoyp>=0?'var(--grow)':'var(--fall)';
    g+=`<circle cx="${p.x.toFixed(1)}" cy="${p.y.toFixed(1)}" r="${p.r.toFixed(1)}" fill="${c}" fill-opacity=".15" stroke="${c}" stroke-width="1.3"><title>${esc(p.d.n)} — ${p.d.lvl.toFixed(0)}K, ${p.d.yoyp>0?'+':''}${p.d.yoyp}%</title></circle>`;
    g+=`<circle cx="${p.x.toFixed(1)}" cy="${p.y.toFixed(1)}" r="1.6" fill="${c}"/>`;
  });

  // labels, placed right of each bubble then de-collided in 2D
  const CH=5.45, FH=13;
  const labs=pts.map(p=>({p,txt:p.d.s,w:p.d.s.length*CH,x:p.x+p.r+8,y:p.y,ax:p.x+p.r+3,ay:p.y}));
  for(let it=0;it<140;it++){
    let moved=false;
    for(let i=0;i<labs.length;i++)for(let j=i+1;j<labs.length;j++){
      const a=labs[i],b=labs[j];
      const dy=Math.abs(a.y-b.y), ox=!(a.x+a.w<b.x-2||b.x+b.w<a.x-2);
      if(ox&&dy<FH){
        const push=(FH-dy)/2+.4;
        if(a.y<=b.y){a.y-=push;b.y+=push}else{a.y+=push;b.y-=push}
        moved=true;
      }
    }
    labs.forEach(l=>{l.y=Math.max(mt+6,Math.min(H-mb-4,l.y))});
    if(!moved)break;
  }
  labs.forEach(l=>{
    if(Math.abs(l.y-l.ay)>3)
      g+=`<line class="lead" x1="${l.ax.toFixed(1)}" y1="${l.ay.toFixed(1)}" x2="${(l.x-3).toFixed(1)}" y2="${l.y.toFixed(1)}"/>`;
    g+=`<text class="dl" x="${l.x.toFixed(1)}" y="${(l.y+3.5).toFixed(1)}">${esc(l.txt)}</text>`;
  });

  document.getElementById('plot').innerHTML=
    `<svg viewBox="0 0 ${W} ${H}" width="${W}" height="${H}" style="max-width:100%;height:auto;min-width:660px" role="img" aria-label="Bubble chart: sector employment against 12-month growth rate">${g}</svg>`;
})();

/* ── mini charts ────────────────────────── */
const mrow=(lab,w,num,col,left)=>`<div class="mrow"><span class="lab">${lab}</span>
<span class="mtrack"><i data-w="${w}"${left!==undefined?` data-l="${left}"`:''} style="background:${col}${left!==undefined?`;left:${left}%`:';left:0'}"></i>${arguments.callee?'':''}</span>
<span class="num">${num}</span></div>`;

function bar(lab,w,num,col,left,ref){
  return `<div class="mrow"><span class="lab">${lab}</span><span class="mtrack">`+
    `<i data-w="${w}" style="background:${col};left:${left||0}%"></i>`+
    (ref?`<span class="ref" style="left:${ref}%"></span>`:'')+
    `</span><span class="num">${num}</span></div>`;
}
// wage growth, scale 0–2.5%, inflation reference at 2.3% = 92%
document.getElementById('wage').innerHTML=
  bar("Bottom 25%",44,"+1.1%","var(--fall)",0,92)+
  bar("Second 25%",52,"+1.3%","var(--fallSoft)",0,92)+
  bar("Third 25%",84,"+2.1%","var(--steelSoft)",0,92)+
  bar("Top 25%",84,"+2.1%","var(--steel)",0,92);

// temporary resident arrivals, scale 0–674K
document.getElementById('immig').innerHTML=
  bar("2025 actual",100,"674K","var(--ink)")+
  bar("2026 target",57,"385K","var(--fall)")+
  bar("2027 target",55,"370K","var(--fall)");

// AI adoption, scale 0–60%
document.getElementById('adopt').innerHTML=
  bar("Canada",20,"12%","var(--fall)")+
  bar("Nordics",22,"29\u201342%","var(--grow)",48)+
  bar("2034 goal",100,"60%","var(--steelSoft)");

/* ── lists ──────────────────────────────── */
const role=(r,c)=>`<div class="it"><div class="t">${r.t}</div><div class="w">${r.w}</div>
<div class="ex"><span class="exbar"><i data-w="${r.e}" style="background:${c}"></i></span><span class="exlab">${r.e}% exposure</span></div></div>`;
document.getElementById('rise').innerHTML=rise.map(r=>role(r,'var(--growSoft)')).join('');
document.getElementById('fall').innerHTML=fall.map(r=>role(r,'var(--fall)')).join('');

const firm=x=>`<div class="firm"><div><div class="t">${x.t}</div><div class="w">${x.w}</div></div><span class="tag">${x.g}</span></div>`;
document.getElementById('ch').innerHTML=ch.map(firm).join('');
document.getElementById('in').innerHTML=inc.map(firm).join('');

const FL=document.getElementById('forcelist');
forces.forEach((x,i)=>{
  const d=document.createElement('div');d.className='force';
  d.innerHTML=`<button class="fb" aria-expanded="false" aria-controls="f${i}"><span><span class="ft">${x.t}</span><span class="fs">${x.s}</span></span><span class="fsg">${x.g}</span></button><div class="fbody" id="f${i}">${x.b}</div>`;
  const b=d.querySelector('button');
  b.onclick=()=>b.setAttribute('aria-expanded',d.classList.toggle('open'));
  FL.appendChild(d);
});

document.getElementById('caps').innerHTML=caps.map(c=>
  `<div class="cp"><h4>${c.h}</h4><div class="amt">${c.a}</div><p>${c.p}</p><div class="j">${c.j}</div></div>`).join('');

const P=document.getElementById('provs'),pmax=Math.max(...provs.map(p=>p.r));
provs.forEach((p,i)=>{
  const r=document.createElement('div');r.className='pr';
  r.innerHTML=`<div class="pn">${p.n}</div><div class="pt"><div class="pb"></div></div><div class="pv">${p.r}%</div><div class="pe">${p.e}</div>`;
  P.appendChild(r);
  const b=r.querySelector('.pb');
  requestAnimationFrame(()=>setTimeout(()=>b.style.width=(p.r/pmax*100)+'%',260+i*26));
});

/* ── animate bars on scroll ─────────────── */
const bo=new IntersectionObserver(es=>es.forEach(e=>{
  if(e.isIntersecting){
    e.target.style.width=Math.min(parseFloat(e.target.dataset.w),100)+'%';
    bo.unobserve(e.target);
  }
}),{threshold:.15});
document.querySelectorAll('[data-w]').forEach(el=>bo.observe(el));

/* ── scrollspy ──────────────────────────── */
const links=[...document.querySelectorAll('#nav a')];
const secs=links.map(a=>document.querySelector(a.getAttribute('href')));
const spy=new IntersectionObserver(es=>es.forEach(e=>{
  if(e.isIntersecting){
    const i=secs.indexOf(e.target);
    if(i>-1){links.forEach(l=>l.classList.remove('on'));links[i].classList.add('on')}
  }
}),{rootMargin:'-8% 0px -78% 0px'});
secs.forEach(s=>s&&spy.observe(s));

draw();sel(sectors[0].n);tog();
</script>
</body>
</html>
