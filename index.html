<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Heirlift Estate Services — Executive Dashboard</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
:root{--navy:#0F1F38;--blue:#185FA5;--blue-lt:#E8F1FB;--green:#166534;--green-lt:#DCFCE7;--amber:#92400e;--amber-lt:#FEF3C7;--red:#b91c1c;--g50:#F8FAFC;--g100:#F1F5F9;--g200:#E2E8F0;--g400:#94A3B8;--g600:#475569;--g800:#1E293B;--white:#fff;font-family:'Inter',-apple-system,sans-serif}
*{box-sizing:border-box;margin:0;padding:0}
body{background:var(--g50);color:var(--g800);font-size:13px;line-height:1.5}
.hdr{background:var(--navy);color:#fff;padding:14px 28px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:10px;position:sticky;top:0;z-index:100}
.hdr-l{display:flex;align-items:center;gap:12px}
.logo{width:34px;height:34px;background:var(--blue);border-radius:8px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.co{font-size:10px;color:rgba(255,255,255,.5);text-transform:uppercase;letter-spacing:.08em}
.rt{font-size:15px;font-weight:600}
.hdr-r{display:flex;align-items:center;gap:6px;flex-wrap:wrap}
.fbtn{font-size:11px;padding:6px 14px;border:1px solid rgba(255,255,255,.2);border-radius:6px;background:transparent;color:rgba(255,255,255,.7);cursor:pointer;font-family:inherit;font-weight:500;transition:all .15s}
.fbtn:hover{background:rgba(255,255,255,.1);color:#fff}
.fbtn.active{background:var(--blue);color:#fff;border-color:var(--blue)}
.crange{display:none;align-items:center;gap:6px;background:rgba(255,255,255,.08);padding:6px 10px;border-radius:8px}
.crange.show{display:flex}
.crange label{font-size:11px;color:rgba(255,255,255,.6);display:flex;align-items:center;gap:5px}
.crange input[type=date]{font-size:11px;padding:3px 6px;border:1px solid rgba(255,255,255,.2);border-radius:5px;background:rgba(255,255,255,.1);color:#fff;font-family:inherit;cursor:pointer;color-scheme:dark}
.apply-btn{font-size:11px;padding:5px 12px;border:none;border-radius:5px;background:var(--blue);color:#fff;cursor:pointer;font-family:inherit;font-weight:600}
.cancel-btn{font-size:11px;padding:5px 10px;border:1px solid rgba(255,255,255,.2);border-radius:5px;background:transparent;color:rgba(255,255,255,.6);cursor:pointer;font-family:inherit}
.live{display:inline-flex;align-items:center;gap:4px;font-size:10px;background:rgba(255,255,255,.1);color:rgba(255,255,255,.7);padding:3px 8px;border-radius:20px}
.ldot{width:6px;height:6px;border-radius:50%;background:#22c55e;animation:pulse 2s infinite}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.4}}
.banner{padding:8px 28px;font-size:12px;font-weight:500;border-bottom:1px solid #e5e7eb}
.banner.loading{background:#EFF6FF;color:var(--blue);display:block}
.banner.loaded{background:#F0FDF4;color:var(--green);display:block}
.banner.error{background:#FEF2F2;color:var(--red);display:block}
.main{padding:20px 28px;max-width:1200px;margin:0 auto}
.slbl{font-size:9px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--g400);margin:20px 0 8px;padding-bottom:5px;border-bottom:1px solid var(--g200)}
.slbl:first-child{margin-top:0}
.ptag{font-size:9px;font-weight:500;background:var(--blue-lt);color:var(--blue);padding:2px 7px;border-radius:4px;text-transform:none;letter-spacing:0;vertical-align:middle;margin-left:6px}
.kg{display:grid;gap:10px;margin-bottom:6px}
.g4{grid-template-columns:repeat(4,1fr)}
.kpi{background:var(--white);border:1px solid var(--g200);border-radius:10px;padding:12px 14px}
.kl{font-size:10px;color:var(--g400);margin-bottom:3px;line-height:1.3}
.kv{font-size:26px;font-weight:700;color:var(--g800);line-height:1;font-variant-numeric:tabular-nums}
.ks{font-size:10px;color:var(--g400);margin-top:3px}
.ks.g{color:var(--green);font-weight:500}
.ke{background:var(--white);border:1px solid var(--g200);border-radius:10px;overflow:hidden}
.keh{padding:12px 14px}
.eb{display:block;width:100%;text-align:left;font-size:10px;font-weight:600;color:var(--blue);padding:6px 14px 8px;background:none;border:none;border-top:1px solid var(--g100);cursor:pointer;font-family:inherit}
.eb:hover{background:var(--blue-lt)}
.eb.amb{color:var(--amber)}.eb.amb:hover{background:var(--amber-lt)}
.ep{display:none;border-top:1px solid var(--g200);padding:8px 12px 12px;max-height:280px;overflow-y:auto;background:var(--g50)}
.ep.open{display:block}
.lr{display:flex;align-items:flex-start;gap:7px;padding:5px 0;border-bottom:1px solid var(--g100)}
.lr:last-child{border-bottom:none}
.ld{width:6px;height:6px;border-radius:50%;flex-shrink:0;margin-top:5px}
.li{flex:1;min-width:0}
.ll{font-size:11px;font-weight:500;color:var(--blue);text-decoration:none;display:block;word-break:break-word;line-height:1.4}
.ll:hover{text-decoration:underline}
.ls{font-size:10px;color:var(--g400)}
.bdg{font-size:9px;padding:2px 6px;border-radius:4px;font-weight:600;white-space:nowrap;flex-shrink:0}
.dt{font-size:10px;color:var(--g400);flex-shrink:0}
.nd{font-size:11px;color:var(--g400);padding:10px 0;text-align:center}
.pipe{display:flex;border-radius:10px;overflow:hidden;border:1px solid var(--g200);margin-bottom:6px}
.stg{flex:1;padding:12px 6px;text-align:center;font-size:10px;font-weight:600;border-right:1px solid var(--g200)}
.stg:last-child{border-right:none}
.sc{font-size:24px;font-weight:700;display:block;margin-bottom:2px;font-variant-numeric:tabular-nums}
.s1{background:#EFF6FF;color:#1d4ed8}.s1 .sc{color:#1d4ed8}
.s2{background:#F0FDF4;color:var(--green)}.s2 .sc{color:var(--green)}
.s3{background:#FFFBEB;color:var(--amber)}.s3 .sc{color:var(--amber)}
.tc{display:grid;grid-template-columns:1.2fr .8fr;gap:12px;margin-bottom:6px}
.card{background:var(--white);border:1px solid var(--g200);border-radius:10px;padding:14px 16px}
table{width:100%;border-collapse:collapse;font-size:11px}
thead tr{border-bottom:1px solid var(--g200)}
th{font-size:9px;font-weight:600;text-transform:uppercase;letter-spacing:.05em;color:var(--g400);padding:5px 5px;text-align:right}
th:first-child{text-align:left}
td{padding:5px 5px;color:var(--g600);text-align:right;border-bottom:1px solid var(--g100);font-variant-numeric:tabular-nums}
td:first-child{text-align:left;font-weight:500;color:var(--g800)}
tr:last-child td{border-bottom:none}
tr.tot td{font-weight:700;background:var(--g50);color:var(--g800);border-top:1px solid var(--g200)}
.cw{position:relative;width:100%;height:150px;margin-top:6px}
.leg{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:6px}
.leg span{display:flex;align-items:center;gap:5px;font-size:10px;color:var(--g600)}
.leg-d{width:8px;height:8px;border-radius:2px}
.ir{display:flex;align-items:center;gap:8px;padding:4px 0}
.av{width:22px;height:22px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:9px;font-weight:700;flex-shrink:0}
.in{font-size:11px;font-weight:500;min-width:90px}
.it{flex:1;height:5px;background:var(--g100);border-radius:3px;overflow:hidden}
.if{height:100%;border-radius:3px}
.inum{font-size:11px;font-weight:600;min-width:36px;text-align:right}
.div{height:1px;background:var(--g200);margin:18px 0}
.note{background:#FFFBEB;border:1px solid #FCD34D;border-radius:8px;padding:10px 14px;font-size:11px;color:var(--amber);margin-top:10px;line-height:1.6}
.foot{background:var(--navy);color:rgba(255,255,255,.4);padding:12px 28px;font-size:10px;display:flex;justify-content:space-between;margin-top:28px;flex-wrap:wrap;gap:4px}
.spinner{display:inline-block;width:14px;height:14px;border:2px solid rgba(255,255,255,.3);border-top-color:#fff;border-radius:50%;animation:spin .7s linear infinite;margin-right:6px;vertical-align:middle}
@keyframes spin{to{transform:rotate(360deg)}}
::-webkit-scrollbar{width:4px}::-webkit-scrollbar-thumb{background:var(--g200);border-radius:2px}
@media(max-width:800px){.g4{grid-template-columns:repeat(2,1fr)}.tc{grid-template-columns:1fr}.pipe{flex-direction:column}.stg{border-right:none;border-bottom:1px solid var(--g200)}.main{padding:14px}.hdr{padding:12px 14px}}
</style>
</head>
<body>

<div class="hdr">
  <div class="hdr-l">
    <div class="logo"><svg viewBox="0 0 16 16" fill="white" width="17" height="17"><path d="M2 3h12v2H2zm0 4h8v2H2zm0 4h10v2H2z"/></svg></div>
    <div><div class="co">Heirlift Estate Services</div><div class="rt">Executive Sales Dashboard</div></div>
  </div>
  <div class="hdr-r">
    <span class="live"><span class="ldot"></span>Live · <span id="last-updated">Loading…</span></span>
    <button class="fbtn active" data-p="today">Today</button>
    <button class="fbtn" data-p="week">This Week</button>
    <button class="fbtn" data-p="month">This Month</button>
    <button class="fbtn" data-p="custom">Custom Range</button>
    <div class="crange" id="crange">
      <label>From <input type="date" id="d-from"></label>
      <label>To <input type="date" id="d-to"></label>
      <button class="apply-btn" id="apply-btn">Apply</button>
      <button class="cancel-btn" id="cancel-btn">Cancel</button>
    </div>
  </div>
</div>

<div id="banner" class="banner loading"><span class="spinner"></span>Connecting to Salesforce and loading live data…</div>

<div class="main" id="main-content" style="opacity:0.3;pointer-events:none">

  <div class="slbl">Activity — IC Performance <span class="ptag" id="act-tag">Today</span></div>
  <div class="card" style="margin-bottom:6px">
    <table>
      <thead><tr><th style="text-align:left">Name</th><th style="text-align:left">Role</th><th>Calls Made</th><th>Texts Sent</th><th>Emails Sent</th></tr></thead>
      <tbody id="ic-tbody"></tbody>
    </table>
  </div>

  <div class="slbl">Lead Disposition <span class="ptag" id="period-tag">Today</span></div>
  <div class="kg g4">
    <div class="ke"><div class="keh"><div class="kl">Total Leads</div><div class="kv" id="k-total">—</div></div><button class="eb" data-t="exp-total">▼ See all leads</button><div class="ep" id="exp-total"><div id="list-total"></div></div></div>
    <div class="ke"><div class="keh"><div class="kl">PI Processing Queue</div><div class="kv" id="k-pi">—</div></div><button class="eb" data-t="exp-pi">▼ See leads</button><div class="ep" id="exp-pi"><div id="list-pi"></div></div></div>
    <div class="ke"><div class="keh"><div class="kl">Sales Queue</div><div class="kv" id="k-sales">—</div></div><button class="eb" data-t="exp-sales">▼ See leads</button><div class="ep" id="exp-sales"><div id="list-sales"></div></div></div>
    <div class="ke"><div class="keh"><div class="kl">Offer Presented</div><div class="kv" id="k-offer">—</div><div class="ks g">Bonus eligible</div></div><button class="eb amb" data-t="exp-offer">▼ See leads</button><div class="ep" id="exp-offer"><div id="list-offer"></div></div></div>
  </div>

  <div class="slbl">Deals &amp; Activity</div>
  <div class="kg g4">
    <div class="ke"><div class="keh"><div class="kl">Moved to Signing</div><div class="kv" id="k-sign">—</div></div><button class="eb" data-t="exp-sign">▼ See leads</button><div class="ep" id="exp-sign"><div id="list-sign"></div></div></div>
    <div class="ke"><div class="keh"><div class="kl">Properties Driven</div><div class="kv" id="k-driven">—</div><div class="ks">Driver_Status__c</div></div><button class="eb" data-t="exp-driven">▼ See leads</button><div class="ep" id="exp-driven"><div id="list-driven"></div></div></div>
    <div class="ke"><div class="keh"><div class="kl">Letters Sent</div><div class="kv" id="k-letters">—</div><div class="ks">Letters_Action_Type__c</div></div><button class="eb" data-t="exp-letters">▼ See leads</button><div class="ep" id="exp-letters"><div id="list-letters"></div></div></div>
    <div class="kpi"><div class="kl">Leads Assigned (ICs)</div><div class="kv" id="k-isa">—</div></div>
  </div>

  <div class="div"></div>
  <div class="slbl">Pipeline Stages</div>
  <div class="pipe">
    <div class="stg s1"><span class="sc" id="p-sign">—</span>Signing</div>
    <div class="stg s2"><span class="sc" id="p-agree">—</span>Under Agreement</div>
    <div class="stg s3"><span class="sc" id="p-offer-stage">—</span>Present Offer/Options</div>
  </div>

  <div class="tc">
    <div class="card">
      <div class="slbl" style="margin-top:0;border-bottom:none;margin-bottom:8px">Lead Status Breakdown <span class="ptag" id="tbl-tag"></span></div>
      <div id="queue-tbl"><div class="nd">Loading…</div></div>
    </div>
    <div class="card">
      <div class="slbl" style="margin-top:0;border-bottom:none;margin-bottom:6px">Leads by IC <span class="ptag" id="chart-tag"></span></div>
      <div class="leg">
        <span><span class="leg-d" style="background:#378ADD"></span>Adam</span>
        <span><span class="leg-d" style="background:#BA7517"></span>Zack</span>
        <span><span class="leg-d" style="background:#D4537E"></span>May</span>
        <span><span class="leg-d" style="background:#1D9E75"></span>Trevor</span>
        <span><span class="leg-d" style="background:#7C3AED"></span>Ethan</span>
        <span><span class="leg-d" style="background:#F59E0B"></span>Paul</span>
      </div>
      <div class="cw"><canvas id="isaChart"></canvas></div>
    </div>
  </div>

  <div class="card" style="margin-top:10px">
    <div class="slbl" style="margin-top:0;border-bottom:none;margin-bottom:10px">Lead Count per IC <span class="ptag" id="bars-tag"></span></div>
    <div id="isa-bars"></div>
  </div>

  <div class="div"></div>
  <div class="slbl">Conversion Summary</div>
  <div class="kg g4">
    <div class="kpi"><div class="kl">Total Leads</div><div class="kv" id="a-total">—</div></div>
    <div class="kpi"><div class="kl">Offers Presented</div><div class="kv" style="color:var(--green)" id="a-offers">—</div></div>
    <div class="kpi"><div class="kl">In Signing</div><div class="kv" style="color:var(--blue)">0</div></div>
    <div class="kpi"><div class="kl">Offer Rate</div><div class="kv" style="color:var(--blue)" id="a-rate">—</div></div>
  </div>

  <div class="note"><strong>Fields not yet filled in Salesforce:</strong> Properties Driven and Letters Sent will show once ICs fill <strong>Driver_Status__c</strong> and <strong>Letters_Action_Type__c / Date_Mailed__c</strong> on each lead. Activity emails will populate when email tasks are logged in Salesforce.</div>
</div>

<div class="foot">
  <span>Heirlift Estate Services · Confidential</span>
  <span id="foot-time">Data source: simplysellnw.lightning.force.com · Loading…</span>
</div>

<script>
const SF = 'https://simplysellnw.lightning.force.com';
const API = '/api/data'; // Relative — works on any host

const IC_ROSTER = [
  {name:'Adam Taha',   role:'Senior IC', bg:'#DBEAFE',color:'#1e40af', chartColor:'#378ADD'},
  {name:'Zack Foster', role:'IC',        bg:'#FEF3C7',color:'#92400e', chartColor:'#BA7517'},
  {name:'May Taha',    role:'IC',        bg:'#FCE7F3',color:'#9d174d', chartColor:'#D4537E'},
  {name:'Trevor Awan', role:'IC',        bg:'#D1FAE5',color:'#065f46', chartColor:'#1D9E75'},
  {name:'Ethan Jones', role:'IC',        bg:'#EDE9FE',color:'#5b21b6', chartColor:'#7C3AED'},
  {name:'Paul',        role:'IC',        bg:'#FEF9C3',color:'#713f12', chartColor:'#F59E0B'},
];

let chart = null, currentPeriod = 'today';

function $(id){return document.getElementById(id);}
function set(id,v){const e=$(id);if(e)e.textContent=v;}

function sfLink(id,type='Lead'){return `${SF}/lightning/r/${type}__c/${id}/view`;}
function fmtDate(iso){if(!iso)return'';const d=new Date(iso);return(d.getMonth()+1)+'/'+(d.getDate());}
function fmtDur(s){if(s===null||s===undefined||s===0)return'No answer';if(s<60)return s+'s';return Math.floor(s/60)+'m '+(s%60)+'s';}

function ownerBadge(o){
  const ic=IC_ROSTER.find(r=>r.name===o);
  if(ic)return`<span class="bdg" style="background:${ic.bg};color:${ic.color}">${o.split(' ')[0]}</span>`;
  const s=o.replace(' Processing Queue','').replace(' Queue','');
  return`<span class="bdg" style="background:#F1F5F9;color:#475569">${s}</span>`;
}

function leadRow(r,dot){
  const url=`${SF}/lightning/r/${r.Id}/view`;
  return`<div class="lr"><div class="ld" style="background:${dot}"></div><div class="li"><a class="ll" href="${url}" target="_blank">${r.Name}</a><div class="ls">${r.Status||r.StageName||''}</div></div>${ownerBadge(r.Owner?.Name||r.OwnerName||'')}<span class="dt">${fmtDate(r.LastModifiedDate||r.CloseDate)}</span></div>`;
}

function fill(id,recs,dot){
  const el=$(id);if(!el)return;
  el.innerHTML=recs&&recs.length?recs.map(r=>leadRow(r,dot)).join(''):'<div class="nd">No records this period.</div>';
}

function renderIC(activity){
  const tbody=$('ic-tbody');if(!tbody)return;
  const calls=activity.calls||{}, texts=activity.texts||{};
  const callDetail=activity.callDetail||{}, textDetail=activity.textDetail||{};

  tbody.innerHTML=IC_ROSTER.map((ic,idx)=>{
    const c=calls[ic.name]||0, t=texts[ic.name]||0;
    const cd=callDetail[ic.name]||[], td=textDetail[ic.name]||[];
    const init=ic.name.split(' ').map(w=>w[0]).join('');
    const avatar=`<span style="width:22px;height:22px;border-radius:50%;background:${ic.bg};color:${ic.color};display:inline-flex;align-items:center;justify-content:center;font-size:9px;font-weight:700;flex-shrink:0">${init}</span>`;
    const roleBadge=`<span style="font-size:10px;padding:2px 7px;border-radius:4px;background:${ic.bg};color:${ic.color};font-weight:600">${ic.role}</span>`;

    const callBtn=c>0&&cd.length?`<span style="font-weight:700;color:#1e40af;cursor:pointer" onclick="toggleDet('cd-${idx}')">${c} ▼</span>`:`<span style="color:${c>0?'#1e40af':'#94A3B8'};font-weight:${c>0?700:400}">${c}</span>`;
    const textBtn=t>0&&td.length?`<span style="font-weight:700;color:#166534;cursor:pointer" onclick="toggleDet('td-${idx}')">${t} ▼</span>`:`<span style="color:${t>0?'#166534':'#94A3B8'};font-weight:${t>0?700:400}">${t}</span>`;

    const callDetailHTML=cd.length?cd.map(d=>{
      const lnk=d.leadId?`<a class="ll" href="${SF}/lightning/r/${d.leadId}/view" target="_blank">${d.lead}</a>`:`<span style="color:#94A3B8">${d.lead}</span>`;
      const dur=fmtDur(d.duration);const durC=(d.duration&&d.duration>0)?'#166534':'#94A3B8';
      return`<div style="display:flex;align-items:center;gap:8px;padding:5px 0;border-bottom:1px solid #f1f5f9"><div style="width:6px;height:6px;border-radius:50%;background:${ic.color};flex-shrink:0"></div><div style="flex:1;min-width:0;font-size:11px">${lnk}</div><span style="font-size:10px;color:${durC};font-weight:600">${dur}</span><span style="font-size:10px;color:#94A3B8">${d.time}</span></div>`;
    }).join(''):'<div class="nd">No calls logged.</div>';

    const textDetailHTML=td.length?td.map(d=>{
      const lnk=d.leadId?`<a class="ll" href="${SF}/lightning/r/${d.leadId}/view" target="_blank">${d.lead}</a>`:`<span style="color:#94A3B8">${d.lead}</span>`;
      return`<div style="display:flex;align-items:center;gap:8px;padding:5px 0;border-bottom:1px solid #f1f5f9"><div style="width:6px;height:6px;border-radius:50%;background:#1D9E75;flex-shrink:0"></div><div style="flex:1;min-width:0;font-size:11px">${lnk}</div><span style="font-size:10px;color:#94A3B8">${d.time}</span></div>`;
    }).join(''):'<div class="nd">No texts logged.</div>';

    return`<tr>
      <td><span style="display:inline-flex;align-items:center;gap:6px">${avatar}${ic.name}</span></td>
      <td style="text-align:left">${roleBadge}</td>
      <td>${callBtn}</td><td>${textBtn}</td><td style="color:#94A3B8">—</td>
    </tr>
    ${cd.length?`<tr id="cd-${idx}-row" style="display:none"><td colspan="5" style="padding:0 0 0 32px;background:#f8fafc"><div style="padding:8px 0 12px">${callDetailHTML}</div></td></tr>`:''}
    ${td.length?`<tr id="td-${idx}-row" style="display:none"><td colspan="5" style="padding:0 0 0 32px;background:#f8fafc"><div style="padding:8px 0 12px">${textDetailHTML}</div></td></tr>`:''}`;
  }).join('');
}

function toggleDet(id){
  const row=$(id+'-row');if(!row)return;
  const open=row.style.display==='none';
  row.style.display=open?'table-row':'none';
  document.querySelectorAll(`[onclick="toggleDet('${id}')"]`).forEach(el=>{
    el.textContent=el.textContent.replace(open?'▼':'▲',open?'▲':'▼');
  });
}

function renderDashboard(data){
  const {leads=[],opps=[],activity={},period}=data;
  const lbl={'today':'Today','week':'This Week','month':'This Month','custom':'Custom Range'}[period]||'Today';

  ['period-tag','tbl-tag','chart-tag','bars-tag','act-tag'].forEach(id=>set(id,lbl));

  const pi=leads.filter(l=>(l.Owner?.Name||'').includes('PI Processing'));
  const sales=leads.filter(l=>(l.Owner?.Name||'').includes('Sales Queue'));
  const isaL=leads.filter(l=>IC_ROSTER.some(ic=>ic.name===l.Owner?.Name));
  const driven=leads.filter(l=>l.Driver_Status__c);
  const lettr=leads.filter(l=>l.Letters_Action_Type__c||l.Date_Mailed__c);
  const offer=opps.filter(o=>/offer|present/i.test(o.StageName||''));
  const sign=opps.filter(o=>/sign/i.test(o.StageName||''));
  const agree=opps.filter(o=>/agreement|under/i.test(o.StageName||''));

  set('k-total',leads.length); set('k-pi',pi.length); set('k-sales',sales.length);
  set('k-offer',offer.length); set('k-sign',sign.length);
  set('k-driven',driven.length||'—'); set('k-letters',lettr.length||'—'); set('k-isa',isaL.length);
  set('p-sign',sign.length); set('p-agree',agree.length); set('p-offer-stage',offer.length);
  set('a-total',leads.length); set('a-offers',offer.length);
  set('a-rate',leads.length?(offer.length/leads.length*100).toFixed(1)+'%':'—');

  const now=new Date();
  set('last-updated',now.toLocaleTimeString('en-US',{hour:'numeric',minute:'2-digit'}));
  set('foot-time',`Data from Salesforce · ${now.toLocaleDateString('en-US',{weekday:'short',month:'short',day:'numeric',year:'numeric'})} · ${now.toLocaleTimeString('en-US',{hour:'numeric',minute:'2-digit'})}`);

  fill('list-total',leads,'#185FA5'); fill('list-pi',pi,'#1d4ed8'); fill('list-sales',sales,'#15803d');
  fill('list-offer',offer,'#92400e'); fill('list-sign',sign,'#185FA5');
  fill('list-driven',driven,'#1d4ed8'); fill('list-letters',lettr,'#166534');

  renderIC(activity);

  // ISA chart + bars
  const counts={};IC_ROSTER.forEach(ic=>counts[ic.name]=0);
  leads.forEach(l=>{const ic=IC_ROSTER.find(r=>r.name===l.Owner?.Name);if(ic)counts[ic.name]++;});
  if(chart){chart.data.datasets[0].data=IC_ROSTER.map(ic=>counts[ic.name]);chart.update();}
  const be=$('isa-bars');
  if(be){const mx=Math.max(...Object.values(counts),1);
    be.innerHTML=IC_ROSTER.map(ic=>{const c=counts[ic.name],p=Math.round(c/mx*100);
      return`<div class="ir"><div class="av" style="background:${ic.bg};color:${ic.color}">${ic.name.split(' ').map(w=>w[0]).join('')}</div><div class="in">${ic.name}</div><div class="it"><div class="if" style="width:${p}%;background:${ic.chartColor}"></div></div><div class="inum">${c}</div></div>`;
    }).join('');}

  // Queue table
  const te=$('queue-tbl');
  if(te){
    const statuses=[...new Set(leads.map(l=>l.Status).filter(Boolean))];
    const activeICs=IC_ROSTER.filter(ic=>counts[ic.name]>0);
    const other=leads.filter(l=>!IC_ROSTER.some(ic=>ic.name===l.Owner?.Name));
    const cols=[...activeICs.map(ic=>ic.name),other.length?'Other':null].filter(Boolean);
    if(!statuses.length){te.innerHTML='<div class="nd">No leads this period.</div>';}
    else{
      const rows=statuses.map(st=>{
        const sl=leads.filter(l=>l.Status===st);
        return`<tr><td>${st}</td><td>${sl.length}</td>${cols.map(col=>`<td>${sl.filter(l=>col==='Other'?!IC_ROSTER.some(ic=>ic.name===l.Owner?.Name):l.Owner?.Name===col).length}</td>`).join('')}</tr>`;
      });
      const tots=cols.map(col=>`<td>${col==='Other'?other.length:counts[col]||0}</td>`).join('');
      te.innerHTML=`<table><thead><tr><th>Status</th><th>Total</th>${cols.map(c=>`<th>${c==='Other'?'Other':c.split(' ')[0]}</th>`).join('')}</tr></thead><tbody>${rows.join('')}<tr class="tot"><td>Total</td><td>${leads.length}</td>${tots}</tr></tbody></table>`;
    }
  }

  $('main-content').style.opacity='1';
  $('main-content').style.pointerEvents='auto';
  document.querySelectorAll('.ep').forEach(p=>p.classList.remove('open'));
  document.querySelectorAll('.eb').forEach(b=>{b.textContent=b.textContent.replace('▲','▼');});
}

async function loadData(period,from,to){
  const banner=$('banner');
  if(banner){banner.className='banner loading';banner.innerHTML='<span class="spinner"></span>Fetching live Salesforce data…';}

  try{
    let url=`${API}?period=${period}`;
    if(period==='custom'&&from&&to) url+=`&from=${from}&to=${to}`;
    const res=await fetch(url);
    const data=await res.json();
    if(!data.ok) throw new Error(data.error||'Unknown error');
    renderDashboard(data);
    if(banner){banner.className='banner loaded';banner.textContent=`✓ Live Salesforce data · ${data.leads.length} leads · Updated ${new Date().toLocaleTimeString('en-US',{hour:'numeric',minute:'2-digit'})}`;}
  }catch(err){
    if(banner){banner.className='banner error';banner.textContent='Error loading data: '+err.message;}
    console.error(err);
  }
}

function setPeriod(p){
  currentPeriod=p;
  document.querySelectorAll('.fbtn[data-p]').forEach(b=>b.classList.toggle('active',b.dataset.p===p));
  const cr=$('crange');
  if(p==='custom'){cr.classList.add('show');return;}
  cr.classList.remove('show');
  loadData(p);
}

window.addEventListener('load',()=>{
  const ctx=$('isaChart').getContext('2d');
  chart=new Chart(ctx,{
    type:'bar',
    data:{labels:IC_ROSTER.map(ic=>ic.name.split(' ')[0]),datasets:[{data:IC_ROSTER.map(()=>0),backgroundColor:IC_ROSTER.map(ic=>ic.chartColor),borderWidth:0,borderRadius:5}]},
    options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false}},scales:{x:{grid:{display:false},ticks:{font:{size:10}}},y:{beginAtZero:true,ticks:{font:{size:10},stepSize:5}}}}
  });

  const today=new Date().toISOString().split('T')[0];
  const ago30=new Date(Date.now()-30*864e5).toISOString().split('T')[0];
  $('d-from').value=ago30; $('d-to').value=today;

  document.querySelectorAll('.fbtn[data-p]').forEach(b=>b.addEventListener('click',function(){setPeriod(this.dataset.p);}));
  $('apply-btn').addEventListener('click',()=>{
    const f=$('d-from').value,t=$('d-to').value;
    if(!f||!t){alert('Select both dates.');return;}
    if(f>t){alert('Start must be before end.');return;}
    $('crange').classList.remove('show');
    loadData('custom',f,t);
  });
  $('cancel-btn').addEventListener('click',()=>setPeriod('today'));
  document.querySelectorAll('.eb[data-t]').forEach(b=>b.addEventListener('click',function(){
    const p=$(this.dataset.t);if(!p)return;
    const open=p.classList.toggle('open');
    this.textContent=open?this.textContent.replace('▼','▲').replace('See all leads','Hide').replace('See leads','Hide'):this.textContent.replace('▲','▼').replace('Hide','See leads');
    if(!open&&this.dataset.t==='exp-total')this.textContent='▼ See all leads';
  }));

  loadData('today');
  // Auto-refresh every 5 minutes
  setInterval(()=>loadData(currentPeriod),5*60*1000);
});
</script>
</body>
</html>
