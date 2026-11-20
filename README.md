# BoiHisab
<!DOCTYPE html><html lang="bn"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>BoiHisab – বই বিক্রি ও ব্যবসার হিসাব</title>
<link rel="preconnect" href="https://fonts.googleapis.com"><link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#f2f5fa;--cd:#fff;--tx:#0e1c3d;--mu:#667699;--nv:#0b2a5b;--nv2:#163d82;--gr:#15934f;--rd:#d63030;--am:#b7791f;--bd:#e2e8f3;color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#09112a;--cd:#131e3b;--tx:#eaf0ff;--mu:#92a2c7;--nv:#0f2c63;--nv2:#4f86e8;--gr:#38c47c;--rd:#ff7070;--am:#f0b04a;--bd:#24325a;color-scheme:dark}}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--tx);font:16px/1.5 'Hind Siliguri',system-ui,-apple-system,'Noto Sans Bengali',sans-serif;padding-bottom:calc(84px + env(safe-area-inset-bottom,0px))}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--nv);z-index:30}
header{background:var(--nv);color:#fff;padding:14px 18px 16px;position:sticky;top:env(safe-area-inset-top,0px);z-index:20}
header b{font-size:22px;font-weight:700}header small{display:block;opacity:.75;font-size:13px}
main{max-width:760px;margin:0 auto;padding:14px}
h2{font-size:18px;margin:18px 2px 10px}h3{margin:0 0 12px;font-size:19px}
.g{display:grid;grid-template-columns:1fr 1fr;gap:10px}.card{background:var(--cd);border:1px solid var(--bd);border-radius:16px;padding:13px 14px;margin-bottom:10px}
.g .card{margin:0}.k{font-size:13px;color:var(--mu)}.v{font-size:21px;font-weight:700;margin-top:2px}.gr{color:var(--gr)}.rd{color:var(--rd)}.am{color:var(--am)}.mu{color:var(--mu);font-size:13px}
.big{background:linear-gradient(135deg,var(--nv),var(--nv2));color:#fff;border:0}.big .k{color:#cfe0ff}
.bar{height:14px;background:var(--bd);border-radius:9px;overflow:hidden;margin:8px 0}.bar i{display:block;height:100%;background:var(--gr);border-radius:9px}
button,select,input,textarea{font:inherit;color:var(--tx)}
.btn{border:0;border-radius:12px;background:var(--nv);color:#fff;padding:11px 14px;font-weight:600;cursor:pointer}.btn.o{background:transparent;border:1px solid var(--bd);color:var(--tx)}.btn.r{background:var(--rd)}.btn.s{padding:7px 11px;font-size:14px}
.row{display:flex;gap:8px;flex-wrap:wrap;align-items:center}.sp{justify-content:space-between}
.qa{display:grid;grid-template-columns:1fr 1fr;gap:8px}.qa .btn{background:var(--cd);color:var(--nv2);border:1px solid var(--bd)}.qa .btn:first-child{grid-column:1/3;background:var(--nv);color:#fff;font-size:17px;padding:14px}
label{display:block;font-size:14px;color:var(--mu);margin-bottom:10px}input,select,textarea{display:block;width:100%;margin-top:4px;padding:11px 12px;border:1px solid var(--bd);border-radius:11px;background:var(--bg);font-size:16px}
.tag{display:inline-block;padding:2px 9px;border-radius:20px;font-size:12.5px;font-weight:600;background:var(--bd)}.tag.g1{background:#dff5e8;color:#0d7a3e}.tag.r1{background:#fde4e4;color:#b42323}.tag.a1{background:#fdf0d3;color:#8a5a0b}
nav{position:fixed;bottom:0;left:0;right:0;background:var(--cd);border-top:1px solid var(--bd);display:flex;padding-bottom:env(safe-area-inset-bottom,0px);z-index:20}
nav button{flex:1;border:0;background:none;padding:9px 2px 8px;color:var(--mu);font-size:12.5px;font-weight:500}nav button span{display:block;font-size:21px;line-height:1.2}nav button.on{color:var(--nv2);font-weight:700}
.fab{position:fixed;right:16px;bottom:calc(78px + env(safe-area-inset-bottom,0px));z-index:19;border-radius:30px;padding:14px 20px;box-shadow:0 6px 18px rgba(11,42,91,.35);background:var(--gr)}
#ov{position:fixed;inset:0;background:rgba(5,12,30,.55);z-index:40;display:none;align-items:flex-end;justify-content:center}
#sh{background:var(--cd);width:100%;max-width:640px;max-height:92%;overflow:auto;border-radius:22px 22px 0 0;padding:18px 16px calc(20px + env(safe-area-inset-bottom,0px))}
.warn{background:#fdf0d3;color:#7a4d06;border-radius:14px;padding:11px 14px;margin-bottom:10px;font-size:14.5px}
.ch{display:flex;align-items:flex-end;gap:8px;height:120px;padding-top:6px}.ch div{flex:1;text-align:center;font-size:11px;color:var(--mu)}.ch i{display:block;background:var(--nv2);border-radius:6px 6px 0 0;min-height:3px}
table{width:100%;border-collapse:collapse;font-size:14px}td,th{padding:7px 4px;border-bottom:1px solid var(--bd);text-align:right}td:first-child,th:first-child{text-align:left}.tw{overflow-x:auto}
.seg{display:flex;background:var(--bd);border-radius:12px;padding:3px;margin-bottom:10px}.seg button{flex:1;border:0;background:none;padding:8px;border-radius:10px;font-weight:600;color:var(--mu)}.seg button.on{background:var(--cd);color:var(--nv2)}
</style></head><body>
<header><b>BoiHisab</b><small>বই বিক্রি ও ব্যবসার হিসাব</small></header>
<main id="main"></main>
<button class="btn fab" onclick="fOrder()">＋ নতুন অর্ডার</button>
<nav><button data-t="dash" onclick="go('dash')"><span>📊</span>ড্যাশবোর্ড</button><button data-t="orders" onclick="go('orders')"><span>🧾</span>অর্ডার</button><button data-t="stock" onclick="go('stock')"><span>📚</span>স্টক</button><button data-t="acc" onclick="go('acc')"><span>💰</span>হিসাব</button><button data-t="set" onclick="go('set')"><span>⚙️</span>সেটিংস</button></nav>
<div id="ov" onclick="if(event.target===this)closeS()"><div id="sh"></div></div>
<script>
const $=s=>document.querySelector(s);
const N=n=>(Math.round((n||0)*100)/100).toLocaleString('bn-BD'),M=n=>'৳'+N(Math.round(n||0));
const uid=()=>Date.now().toString(36)+Math.random().toString(36).slice(2,6);
const today=()=>{const d=new Date();return new Date(d-d.getTimezoneOffset()*6e4).toISOString().slice(0,10)};
const esc=s=>String(s??'').replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const mon=m=>new Date(m+'-01T00:00:00').toLocaleDateString('bn-BD',{month:'short',year:'numeric'});
const PM=['বিকাশ','নগদ','ক্যাশ','ব্যাংক','অন্যান্য'],CAT=['ছাপা ও প্রকাশনা','মার্কেটিং','কুরিয়ার/ডেলিভারি','প্যাকেজিং','অন্যান্য'];
let S,db,dbOk=true,tab='dash',sub='orders',f={q:'',del:'',pay:'',from:'',to:''};
const seed=()=>({batches:[{id:'b0',book:'বিশ্বাসের নকশা',date:today(),qty:15,cpc:215,extra:0}],customers:[],orders:[],payments:[],expenses:[],lastBackup:0,created:Date.now()});
/* ---- storage (IndexedDB) ---- */
const idb=()=>new Promise((ok,no)=>{const r=indexedDB.open('boihisab',1);r.onupgradeneeded=()=>r.result.createObjectStore('kv');r.onsuccess=()=>ok(r.result);r.onerror=()=>no(r.error)});
async function load(){try{db=await idb();return await new Promise(r=>{const q=db.transaction('kv').objectStore('kv').get('state');q.onsuccess=()=>r(q.result||null);q.onerror=()=>r(null)})}catch(e){dbOk=false;return null}}
function save(){try{db.transaction('kv','readwrite').objectStore('kv').put(JSON.parse(JSON.stringify(S)),'state')}catch(e){dbOk=false}}
function persist(){save();render()}
/* ---- calculations ---- */
const bt=b=>b.qty*b.cpc+(+b.extra||0),ba=b=>b.qty?bt(b)/b.qty:0;
function calc(){
 const bs=[...S.batches].sort((a,b)=>a.date.localeCompare(b.date)||a.id.localeCompare(b.id)),rem=bs.map(b=>({b,left:b.qty})),cost={};
 const act=[...S.orders].filter(o=>!o.cancelled).sort((a,b)=>a.date.localeCompare(b.date)||a.id.localeCompare(b.id));
 for(const o of act){let need=o.qty,c=0;for(const x of rem){if(need<=0)break;if(x.b.book!==o.book)continue;const t=Math.min(need,x.left);x.left-=t;need-=t;c+=t*ba(x.b)}cost[o.id]=c}
 const T={left:{},avail:{}};rem.forEach(x=>T.left[x.b.id]=x.left);
 S.batches.forEach(b=>T.avail[b.book]=(T.avail[b.book]||0)+b.qty);act.forEach(o=>T.avail[o.book]=(T.avail[o.book]||0)-o.qty);
 T.o=S.orders.map(o=>{const c=S.customers.find(x=>x.id===o.cid)||{name:'?'},paid=S.payments.filter(p=>p.oid===o.id).reduce((a,p)=>a+p.amount,0),total=o.qty*o.price;
  const cc=o.cancelled?0:cost[o.id]||0,due=o.cancelled?0:Math.max(0,total-paid);
  return{...o,c,paid,total,due,cost:cc,profit:o.cancelled?0:total-cc,ps:o.cancelled?'cx':paid<=0?'un':due>0?'pt':'pd'}}).sort((a,b)=>b.date.localeCompare(a.date)||b.id.localeCompare(a.id));
 const A=T.o.filter(o=>!o.cancelled),sum=(l,k)=>l.reduce((a,x)=>a+x[k],0);
 T.produced=sum(S.batches,'qty');T.ordered=sum(A,'qty');T.sold=sum(A.filter(o=>o.delivered),'qty');T.pending=T.ordered-T.sold;T.stock=T.produced-T.ordered;
 T.prod=S.batches.reduce((a,b)=>a+bt(b),0);T.exp=sum(S.expenses,'amount');T.inv=T.prod+T.exp;T.rev=sum(A,'total');T.cost=sum(A,'cost');
 T.recv=sum(S.payments,'amount');T.due=sum(A,'due');T.gross=T.rev-T.cost;T.net=T.gross-T.exp;T.remInv=Math.max(0,T.inv-T.recv);
 T.dd=A.filter(o=>o.delivered).length;T.dp=A.length-T.dd;
 const m={};const g=k=>m[k]||(m[k]={s:0,c:0,p:0,r:0});A.forEach(o=>{const x=g(o.date.slice(0,7));x.s+=o.total;x.c+=o.cost;x.p+=o.profit});S.payments.forEach(p=>g(p.date.slice(0,7)).r+=p.amount);
 T.m=Object.entries(m).sort();return T}
/* ---- views ---- */
const card=(k,v,c='')=>`<div class="card"><div class="k">${k}</div><div class="v ${c}">${v}</div></div>`;
function backupWarn(){if(!dbOk)return'<div class="warn">⚠️ এই ব্রাউজারে ডেটা সংরক্ষণ করা যাচ্ছে না (প্রাইভেট মোড হতে পারে)। এখনই ব্যাকআপ নিন।</div>';
 const d=S.lastBackup?Math.floor((Date.now()-S.lastBackup)/864e5):null;
 return d===null||d>=7?`<div class="warn">⚠️ ${d===null?'এখনো ব্যাকআপ নেওয়া হয়নি।':N(d)+' দিন ধরে ব্যাকআপ নেওয়া হয়নি।'} <a href="#" onclick="go('set');return false" style="color:inherit;font-weight:700">ব্যাকআপ নিন</a></div>`:''}
function vDash(T){const pct=T.inv?Math.min(100,T.recv/T.inv*100):0,ms=T.m.slice(-6),mx=Math.max(1,...ms.map(x=>x[1].s));
 return backupWarn()+`<div class="qa"><button class="btn" onclick="fOrder()">＋ নতুন অর্ডার</button><button class="btn" onclick="fBatch()">নতুন উৎপাদন ব্যাচ</button><button class="btn" onclick="fCust()">নতুন ক্রেতা</button><button class="btn" onclick="fExp()" style="grid-column:1/3">নতুন খরচ</button></div>
 <h2>ব্যবসার সারসংক্ষেপ</h2><div class="g">
 ${card('মোট বিক্রয়',M(T.rev))}${card('মোট লাভ',M(T.net),T.net>=0?'gr':'rd')}${card('মোট টাকা আদায়',M(T.recv),'gr')}${card('মোট বকেয়া',M(T.due),'rd')}
 ${card('মোট উৎপাদন খরচ',M(T.prod))}${card('মোট বই তৈরি',N(T.produced)+' টি')}${card('মোট বই বিক্রি',N(T.sold)+' টি')}${card('বর্তমানে স্টকে আছে',N(T.stock)+' টি')}
 ${card('ডেলিভারি সম্পন্ন',N(T.dd)+' অর্ডার','gr')}${card('ডেলিভারি বাকি',N(T.dp)+' অর্ডার','am')}</div>
 <h2>বিনিয়োগ ফেরত</h2><div class="card big"><div class="k">মোট বিনিয়োগ ${M(T.inv)}</div><div class="bar"><i style="width:${pct}%"></i></div><div class="row sp"><span>ফেরত পেয়েছি <b>${M(T.recv)}</b></span><span>বাকি <b>${M(T.remInv)}</b></span></div><div class="k" style="margin-top:4px">${N(Math.round(pct))}% উঠে এসেছে</div></div>
 <h2>মাসিক বিক্রয়</h2><div class="card">${ms.length?`<div class="ch">${ms.map(([k,x])=>`<div><i style="height:${Math.max(3,x.s/mx*100)}px"></i>${mon(k)}</div>`).join('')}</div>`:'<div class="mu">এখনো কোনো বিক্রয় নেই। প্রথম অর্ডার যোগ করুন।</div>'}</div>`}
const ps={pd:['পরিশোধিত','g1'],pt:['আংশিক পরিশোধ','a1'],un:['বকেয়া','r1'],cx:['বাতিল','']};
function listO(T){const q=f.q.trim().toLowerCase();
 const L=T.o.filter(o=>(!q||(o.c.name+o.c.phone+o.notes+o.book).toLowerCase().includes(q))&&(!f.del||(f.del==='y')===!!o.delivered)&&(!f.pay||o.ps===f.pay)&&(!f.from||o.date>=f.from)&&(!f.to||o.date<=f.to));
 return L.length?L.map(o=>`<div class="card"><div class="row sp"><b>${esc(o.c.name)}</b><span class="mu">${o.date}</span></div>
 <div class="mu">${esc(o.book)} · ${N(o.qty)} × ${M(o.price)} = <b style="color:var(--tx)">${M(o.total)}</b></div>
 <div class="row" style="margin:6px 0"><span class="tag ${ps[o.ps][1]}">${ps[o.ps][0]}</span>${o.cancelled?'':`<span class="tag ${o.delivered?'g1':'a1'}">${o.delivered?'✓ ডেলিভারি সম্পন্ন':'ডেলিভারি বাকি'}</span>`}</div>
 <div class="row sp"><span>পেয়েছি <b class="gr">${M(o.paid)}</b></span><span>বকেয়া <b class="rd">${M(o.due)}</b></span><span>লাভ <b class="${o.profit>=0?'gr':'rd'}">${M(o.profit)}</b></span></div>
 <div class="row" style="margin-top:10px">${o.cancelled?'':`<label style="margin:0;display:flex;gap:6px;align-items:center;color:var(--tx)"><input type="checkbox" style="width:22px;height:22px;margin:0" ${o.delivered?'checked':''} onchange="tglD('${o.id}',this.checked)">ডেলিভারি সম্পন্ন</label>`}<span style="flex:1"></span>
 ${o.cancelled?'':`<button class="btn s" onclick="fPay('${o.id}')">পেমেন্ট</button>`}<button class="btn s o" onclick="fOrder('${o.id}')">সম্পাদনা</button><button class="btn s o rd" onclick="delO('${o.id}')">মুছুন</button></div></div>`).join(''):'<div class="card mu">কোনো অর্ডার পাওয়া যায়নি।</div>'}
const redo=()=>{$('#lst').innerHTML=listO(calc())};
function vOrders(T){const seg=`<div class="seg"><button class="${sub==='orders'?'on':''}" onclick="sub='orders';render()">অর্ডার</button><button class="${sub==='cust'?'on':''}" onclick="sub='cust';render()">ক্রেতা</button></div>`;
 if(sub==='cust')return seg+`<div class="row sp"><h2 style="margin:0 2px 8px">ক্রেতার তালিকা</h2><button class="btn s" onclick="fCust()">＋ নতুন ক্রেতা</button></div><input placeholder="🔍 নাম/ফোন খুঁজুন" oninput="cq=this.value;$('#cl').innerHTML=listC(calc())" value="${esc(cq)}" style="margin-bottom:10px"><div id="cl">${listC(T)}</div>`;
 return seg+`<input placeholder="🔍 ক্রেতা, ফোন বা নোট খুঁজুন" value="${esc(f.q)}" oninput="f.q=this.value;redo()" style="margin-bottom:8px">
 <div class="g" style="margin-bottom:8px"><select onchange="f.del=this.value;redo()"><option value="">সব ডেলিভারি</option><option value="y" ${f.del==='y'?'selected':''}>ডেলিভারি সম্পন্ন</option><option value="n" ${f.del==='n'?'selected':''}>ডেলিভারি বাকি</option></select>
 <select onchange="f.pay=this.value;redo()"><option value="">সব পেমেন্ট</option>${['pd','pt','un','cx'].map(k=>`<option value="${k}" ${f.pay===k?'selected':''}>${ps[k][0]}</option>`).join('')}</select>
 <label style="margin:0">থেকে<input type="date" value="${f.from}" onchange="f.from=this.value;redo()"></label><label style="margin:0">পর্যন্ত<input type="date" value="${f.to}" onchange="f.to=this.value;redo()"></label></div><div id="lst">${listO(T)}</div>`}
let cq='';
function listC(T){const q=cq.trim().toLowerCase(),L=S.customers.filter(c=>!q||(c.name+c.phone).toLowerCase().includes(q));
 return L.length?L.map(c=>{const os=T.o.filter(o=>o.cid===c.id&&!o.cancelled);return`<div class="card" onclick="vCust('${c.id}')"><div class="row sp"><b>${esc(c.name)}</b><span class="mu">${esc(c.phone)}</span></div><div class="mu">${esc([c.area,c.district].filter(Boolean).join(', '))}</div><div class="row sp" style="margin-top:4px"><span>${N(os.length)} অর্ডার</span><span>বকেয়া <b class="rd">${M(os.reduce((a,o)=>a+o.due,0))}</b></span></div></div>`}).join(''):'<div class="card mu">কোনো ক্রেতা নেই। অর্ডার যোগ করলে ক্রেতা নিজে থেকেই তৈরি হবে।</div>'}
function vStock(T){return `<div class="g">${card('মোট তৈরি',N(T.produced)+' টি')}${card('মোট বিক্রি (ডেলিভারি)',N(T.sold)+' টি','gr')}${card('পেন্ডিং অর্ডার',N(T.pending)+' টি','am')}${card('স্টকে আছে',N(T.stock)+' টি',T.stock>0?'gr':'rd')}</div>
 <div class="row sp"><h2>উৎপাদন ব্যাচ</h2><button class="btn s" onclick="fBatch()">＋ নতুন ব্যাচ</button></div>
 ${[...S.batches].sort((a,b)=>b.date.localeCompare(a.date)).map(b=>`<div class="card"><div class="row sp"><b>${esc(b.book)}</b><span class="mu">${b.date}</span></div>
 <div class="mu">${N(b.qty)} কপি × ${M(b.cpc)}${b.extra?' + অতিরিক্ত '+M(b.extra):''}</div><div class="row sp" style="margin:4px 0"><span>মোট খরচ <b>${M(bt(b))}</b></span><span>প্রকৃত খরচ/কপি <b>${M(ba(b))}</b></span></div>
 <div class="mu">এই ব্যাচ থেকে স্টকে বাকি: <b>${N(T.left[b.id]||0)}</b> টি (FIFO)</div><div class="row" style="margin-top:8px"><button class="btn s o" onclick="fBatch('${b.id}')">সম্পাদনা</button><button class="btn s o rd" onclick="delB('${b.id}')">মুছুন</button></div></div>`).join('')}`}
function vAcc(T){return `<div class="g">${card('মোট বিক্রয়',M(T.rev))}${card('মোট উৎপাদন খরচ',M(T.prod))}${card('বিক্রিত বইয়ের খরচ',M(T.cost))}${card('গ্রস লাভ',M(T.gross),T.gross>=0?'gr':'rd')}${card('নিট লাভ',M(T.net),T.net>=0?'gr':'rd')}${card('প্রকৃত আদায়',M(T.recv),'gr')}${card('বকেয়া',M(T.due),'rd')}${card('ব্যবসায়িক খরচ',M(T.exp))}</div>
 <div class="card mu" style="margin-top:10px">লাভ = বিক্রয় − প্রতি অর্ডারে বরাদ্দ প্রকৃত উৎপাদন খরচ − অতিরিক্ত ব্যবসায়িক খরচ। উৎপাদন খরচ দুইবার গণনা হয় না।</div>
 <h2>মাসিক রিপোর্ট</h2><div class="card tw"><table><tr><th>মাস</th><th>বিক্রয়</th><th>আদায়</th><th>লাভ</th></tr>${T.m.length?T.m.map(([k,x])=>`<tr><td>${mon(k)}</td><td>${M(x.s)}</td><td>${M(x.r)}</td><td class="${x.p>=0?'gr':'rd'}">${M(x.p)}</td></tr>`).join(''):'<tr><td colspan=4 class="mu">কোনো তথ্য নেই</td></tr>'}</table></div>
 <div class="row sp"><h2>খরচের তালিকা</h2><button class="btn s" onclick="fExp()">＋ নতুন খরচ</button></div>
 ${S.expenses.length?[...S.expenses].sort((a,b)=>b.date.localeCompare(a.date)).map(e=>`<div class="card"><div class="row sp"><b>${esc(e.name)}</b><b class="rd">${M(e.amount)}</b></div><div class="mu">${e.date} · ${esc(e.cat)}${e.notes?' · '+esc(e.notes):''}</div><div class="row" style="margin-top:8px"><button class="btn s o" onclick="fExp('${e.id}')">সম্পাদনা</button><button class="btn s o rd" onclick="delE('${e.id}')">মুছুন</button></div></div>`).join(''):'<div class="card mu">এখনো কোনো খরচ যোগ করা হয়নি।</div>'}`}
function vSet(T){const d=S.lastBackup?new Date(S.lastBackup).toLocaleString('bn-BD'):'কখনো না';
 return backupWarn()+`<div class="card"><h3>ডেটা ব্যাকআপ</h3><div class="mu" style="margin-bottom:10px">শেষ ব্যাকআপ: ${d}</div><div class="row"><button class="btn" onclick="expJ()">JSON ব্যাকআপ</button><button class="btn o" onclick="expC()">CSV এক্সপোর্ট</button><button class="btn o" onclick="fRest()">রিস্টোর</button></div></div>
 <div class="card"><h3>ডেটা কোথায় থাকে?</h3><div class="mu">আপনার সব তথ্য শুধু এই ডিভাইসের এই ব্রাউজারে (IndexedDB) নিজে থেকেই সংরক্ষণ হয়। ব্রাউজার বন্ধ করলে বা রিফ্রেশ করলেও থাকে। তবে অন্য ফোন/কম্পিউটারের সাথে নিজে থেকে সিঙ্ক হয় না। ব্রাউজারের ডেটা মুছলে তথ্য হারাবে — তাই নিয়মিত JSON ব্যাকআপ নিন এবং নিজের ফাইল/ইমেইলে সংরক্ষণ করুন।</div></div>
 <div class="card"><h3>অ্যাপ সম্পর্কে</h3><div class="mu">BoiHisab · মোট ${N(S.orders.length)} অর্ডার, ${N(S.customers.length)} ক্রেতা, ${N(S.batches.length)} ব্যাচ</div></div>`}
function render(){const T=calc();$('#main').innerHTML=({dash:vDash,orders:vOrders,stock:vStock,acc:vAcc,set:vSet})[tab](T);document.querySelectorAll('nav button').forEach(b=>b.classList.toggle('on',b.dataset.t===tab));$('.fab').style.display=(tab==='dash'||tab==='set')?'none':''}
function go(t){tab=t;render();scrollTo(0,0)}
/* ---- sheet ---- */
const sheet=h=>{$('#sh').innerHTML=h;$('#ov').style.display='flex'},closeS=()=>{$('#ov').style.display='none'};
const I=(id,l,v='',t='text',x='')=>`<label>${l}<input id="${id}" type="${t}" value="${esc(v)}" ${t==='number'?'inputmode="decimal" step="any" min="0"':''} ${x}></label>`;
const g=k=>$('#'+k).value.trim();
const btns=(s,x='')=>`<div class="row" style="margin-top:6px"><button class="btn" style="flex:1" onclick="${s}">সংরক্ষণ করুন</button><button class="btn o" onclick="closeS()">বাতিল</button></div>${x}`;
/* orders */
function findC(n,p){return S.customers.find(c=>p&&c.phone===p)||S.customers.find(c=>c.name===n&&(!p||!c.phone))}
function fOrder(id){const o=id&&S.orders.find(x=>x.id===id),c=o?S.customers.find(x=>x.id===o.cid)||{}:{},books=[...new Set(S.batches.map(b=>b.book))];
 sheet(`<h3>${o?'অর্ডার সম্পাদনা':'নতুন অর্ডার'}</h3>${I('n','ক্রেতার নাম',c.name,'text','list="cl" oninput="pick()"')}<datalist id="cl">${S.customers.map(x=>`<option value="${esc(x.name)}">`).join('')}</datalist>
 ${I('ph','ফোন নম্বর',c.phone,'tel')}${I('ad','ডেলিভারি ঠিকানা',o?o.address:c.address)}${I('d','অর্ডারের তারিখ',o?o.date:today(),'date')}
 <label>বইয়ের নাম<select id="bk" onchange="upd()">${books.map(b=>`<option ${o&&o.book===b?'selected':''}>${esc(b)}</option>`).join('')}</select></label>
 <div class="g">${I('q','পরিমাণ',o?o.qty:1,'number','oninput="upd()"')}${I('p','প্রতি বইয়ের দাম (৳)',o?o.price:'','number','oninput="upd()"')}</div>
 ${o?'':`<div class="g">${I('r','এখন পেয়েছি (৳)','','number','oninput="upd()"')}<label>মাধ্যম<select id="pm">${PM.map(m=>`<option>${m}</option>`).join('')}</select></label></div>`}
 <div class="card" id="pv" style="background:var(--bg)"></div>
 <label style="display:flex;gap:8px;align-items:center;color:var(--tx)"><input id="dv" type="checkbox" style="width:22px;height:22px;margin:0" ${o&&o.delivered?'checked':''}>ডেলিভারি সম্পন্ন</label>
 ${o?`<label style="display:flex;gap:8px;align-items:center;color:var(--tx)"><input id="cx" type="checkbox" style="width:22px;height:22px;margin:0" ${o.cancelled?'checked':''}>অর্ডার বাতিল (স্টক ফেরত যাবে)</label>`:''}
 ${I('nt','নোট',o?o.notes:'')}${btns(`saveO('${id||''}')`)}`);window._eo=o;upd()}
function pick(){const c=S.customers.find(x=>x.name===g('n'));if(c){if(!g('ph'))$('#ph').value=c.phone||'';if(!g('ad'))$('#ad').value=c.address||''}}
function upd(){const q=+g('q')||0,p=+g('p')||0,r=$('#r')?+g('r')||0:null,T=calc(),o=window._eo,bk=g('bk'),av=(T.avail[bk]||0)+(o&&!o.cancelled&&o.book===bk?o.qty:0),t=q*p;
 $('#pv').innerHTML=`<div class="row sp"><span>মোট মূল্য</span><b>${M(t)}</b></div>${r===null?'':`<div class="row sp"><span>বকেয়া</span><b class="rd">${M(Math.max(0,t-r))}</b></div>`}<div class="row sp"><span>স্টকে আছে</span><b class="${q>av?'rd':''}">${N(av)} টি</b></div>`}
function saveO(id){const o=id&&S.orders.find(x=>x.id===id),q=+g('q'),p=g('p'),rc=$('#r')?+g('r')||0:0,bk=g('bk'),cx=!!(o&&$('#cx').checked);
 if(!g('n')||!(q>0)||p===''||+p<0)return alert('ক্রেতার নাম, পরিমাণ ও দাম দিন।');
 const T=calc(),av=(T.avail[bk]||0)+(o&&!o.cancelled&&o.book===bk?o.qty:0);
 if(!cx&&q>av)return alert('স্টকে মাত্র '+N(av)+' টি বই আছে। এর বেশি অর্ডার নেওয়া যাবে না।');
 if(rc>q*p)return alert('প্রাপ্ত টাকা মোট মূল্যের বেশি হতে পারে না।');
 let c=findC(g('n'),g('ph'));if(!c){c={id:uid(),name:g('n'),phone:g('ph'),address:g('ad'),district:'',area:'',notes:''};S.customers.push(c)}else{if(g('ph'))c.phone=g('ph');if(g('ad'))c.address=g('ad')}
 const d={cid:c.id,date:g('d')||today(),book:bk,qty:q,price:+p,delivered:$('#dv').checked,notes:g('nt'),cancelled:cx,address:g('ad')};
 if(o)Object.assign(o,d);else{const n={id:uid(),...d};S.orders.push(n);if(rc>0)S.payments.push({id:uid(),oid:n.id,date:d.date,amount:rc,method:$('#pm').value})}
 closeS();persist()}
function tglD(id,v){S.orders.find(o=>o.id===id).delivered=v;persist()}
function delO(id){if(!confirm('এই অর্ডার ও এর সব পেমেন্ট মুছে ফেলবেন?'))return;S.orders=S.orders.filter(o=>o.id!==id);S.payments=S.payments.filter(p=>p.oid!==id);persist()}
/* payments */
function fPay(id){const o=calc().o.find(x=>x.id===id),ps=S.payments.filter(p=>p.oid===id).sort((a,b)=>a.date.localeCompare(b.date));
 sheet(`<h3>পেমেন্ট — ${esc(o.c.name)}</h3><div class="card" style="background:var(--bg)"><div class="row sp"><span>মোট</span><b>${M(o.total)}</b></div><div class="row sp"><span>পেয়েছি</span><b class="gr">${M(o.paid)}</b></div><div class="row sp"><span>বকেয়া</span><b class="rd">${M(o.due)}</b></div></div>
 ${ps.map(p=>`<div class="row sp" style="padding:6px 0;border-bottom:1px solid var(--bd)"><span>${p.date} · ${p.method}</span><span><b>${M(p.amount)}</b> <button class="btn s o rd" onclick="delP('${p.id}','${id}')">✕</button></span></div>`).join('')||'<div class="mu">কোনো পেমেন্ট নেই</div>'}
 <h2>নতুন পেমেন্ট যোগ করুন</h2>${I('pa','টাকা (৳)',o.due||'','number')}${I('pd','তারিখ',today(),'date')}<label>মাধ্যম<select id="pm">${PM.map(m=>`<option>${m}</option>`).join('')}</select></label>${btns(`savP('${id}')`)}`)}
function savP(id){const a=+g('pa'),o=calc().o.find(x=>x.id===id);if(!(a>0))return alert('টাকার পরিমাণ দিন।');if(a>o.due+0.001&&!confirm('পরিমাণ বকেয়ার চেয়ে বেশি। তবুও যোগ করবেন?'))return;
 S.payments.push({id:uid(),oid:id,date:g('pd')||today(),amount:a,method:$('#pm').value});persist();fPay(id)}
function delP(p,id){if(!confirm('এই পেমেন্ট মুছবেন?'))return;S.payments=S.payments.filter(x=>x.id!==p);persist();fPay(id)}
/* batches */
function fBatch(id){const b=id&&S.batches.find(x=>x.id===id);
 sheet(`<h3>${b?'ব্যাচ সম্পাদনা':'নতুন উৎপাদন ব্যাচ'}</h3>${I('bn','বইয়ের নাম',b?b.book:S.batches[S.batches.length-1]?.book||'বিশ্বাসের নকশা')}${I('bd','উৎপাদনের তারিখ',b?b.date:today(),'date')}
 ${I('bq','কত কপি তৈরি',b?b.qty:'','number','oninput="ub()"')}${I('bc','প্রতি কপির খরচ (৳)',b?b.cpc:'','number','oninput="ub()"')}${I('be','অতিরিক্ত খরচ (৳)',b?b.extra:0,'number','oninput="ub()"')}
 <div class="card" id="bv" style="background:var(--bg)"></div>${btns(`saveB('${id||''}')`)}`);ub()}
function ub(){const q=+g('bq')||0,t=q*(+g('bc')||0)+(+g('be')||0);$('#bv').innerHTML=`<div class="row sp"><span>মোট উৎপাদন খরচ</span><b>${M(t)}</b></div><div class="row sp"><span>প্রকৃত খরচ/কপি</span><b>${M(q?t/q:0)}</b></div>`}
function saveB(id){const q=+g('bq'),c=+g('bc'),b=id&&S.batches.find(x=>x.id===id);if(!g('bn')||!(q>0)||g('bc')==='')return alert('বইয়ের নাম, কপি সংখ্যা ও খরচ দিন।');
 const d={book:g('bn'),date:g('bd')||today(),qty:q,cpc:c,extra:+g('be')||0};
 if(b){const keep=S.batches.slice();Object.assign(b,d);const T=calc();if(Object.values(T.avail).some(v=>v<0)){Object.assign(b,keep.find(x=>x.id===id));return alert('এত কম কপি করলে বিক্রিত অর্ডারের চেয়ে স্টক কম হয়ে যায়।')}}else S.batches.push({id:uid(),...d});closeS();persist()}
function delB(id){const b=S.batches.find(x=>x.id===id);S.batches=S.batches.filter(x=>x.id!==id);if(Object.values(calc().avail).some(v=>v<0)){S.batches.push(b);return alert('এই ব্যাচ মুছলে অর্ডারের জন্য পর্যাপ্ত স্টক থাকে না।')}S.batches.push(b);if(!confirm('এই ব্যাচ মুছে ফেলবেন?'))return;S.batches=S.batches.filter(x=>x.id!==id);persist()}
/* customers */
function fCust(id){const c=id&&S.customers.find(x=>x.id===id);
 sheet(`<h3>${c?'ক্রেতা সম্পাদনা':'নতুন ক্রেতা'}</h3>${I('cn','নাম',c?c.name:'')}${I('cp','ফোন নম্বর',c?c.phone:'','tel')}${I('ca','ঠিকানা',c?c.address:'')}<div class="g">${I('cd','জেলা',c?c.district:'')}${I('cr','এলাকা',c?c.area:'')}</div>${I('ct','নোট',c?c.notes:'')}${btns(`saveC('${id||''}')`)}`)}
function saveC(id){if(!g('cn'))return alert('নাম দিন।');const d={name:g('cn'),phone:g('cp'),address:g('ca'),district:g('cd'),area:g('cr'),notes:g('ct')},c=id&&S.customers.find(x=>x.id===id);
 if(c)Object.assign(c,d);else S.customers.push({id:uid(),...d});closeS();sub='cust';if(tab!=='orders'&&!c)tab='orders';persist()}
function vCust(id){const T=calc(),c=S.customers.find(x=>x.id===id),os=T.o.filter(o=>o.cid===id),pids=os.map(o=>o.id),ps=S.payments.filter(p=>pids.includes(p.oid)).sort((a,b)=>b.date.localeCompare(a.date));
 sheet(`<h3>${esc(c.name)}</h3><div class="mu">${esc(c.phone)} ${esc(c.address)}<br>${esc([c.area,c.district].filter(Boolean).join(', '))} ${esc(c.notes)}</div>
 <div class="row" style="margin:10px 0"><button class="btn s" onclick="fCust('${id}')">সম্পাদনা</button><button class="btn s o rd" onclick="delC('${id}')">মুছুন</button></div>
 <h2>অর্ডার ইতিহাস</h2>${os.map(o=>`<div class="row sp" style="padding:6px 0;border-bottom:1px solid var(--bd)"><span>${o.date} · ${N(o.qty)} টি · ${M(o.total)}</span><span class="tag ${ps2(o)}">${ps[o.ps]?'':''}${({pd:'পরিশোধিত',pt:'আংশিক',un:'বকেয়া',cx:'বাতিল'})[o.ps]}</span></div>`).join('')||'<div class="mu">কোনো অর্ডার নেই</div>'}
 <h2>পেমেন্ট ইতিহাস</h2>${ps.map(p=>`<div class="row sp" style="padding:6px 0;border-bottom:1px solid var(--bd)"><span>${p.date} · ${p.method}</span><b class="gr">${M(p.amount)}</b></div>`).join('')||'<div class="mu">কোনো পেমেন্ট নেই</div>'}<div class="row" style="margin-top:12px"><button class="btn o" onclick="closeS()">বন্ধ করুন</button></div>`)}
const ps2=o=>({pd:'g1',pt:'a1',un:'r1',cx:''})[o.ps];
function delC(id){if(S.orders.some(o=>o.cid===id))return alert('এই ক্রেতার অর্ডার আছে, তাই মোছা যাবে না।');if(!confirm('ক্রেতা মুছবেন?'))return;S.customers=S.customers.filter(c=>c.id!==id);closeS();persist()}
/* expenses */
function fExp(id){const e=id&&S.expenses.find(x=>x.id===id);
 sheet(`<h3>${e?'খরচ সম্পাদনা':'নতুন খরচ'}</h3>${I('en','খরচের নাম',e?e.name:'')}${I('ea','টাকা (৳)',e?e.amount:'','number')}${I('ed','তারিখ',e?e.date:today(),'date')}<label>ক্যাটাগরি<select id="ec">${CAT.map(c=>`<option ${e&&e.cat===c?'selected':''}>${c}</option>`).join('')}</select></label>${I('et','নোট',e?e.notes:'')}${btns(`saveE('${id||''}')`)}`)}
function saveE(id){const a=+g('ea');if(!g('en')||!(a>0))return alert('খরচের নাম ও টাকা দিন।');const d={name:g('en'),amount:a,date:g('ed')||today(),cat:$('#ec').value,notes:g('et')},e=id&&S.expenses.find(x=>x.id===id);
 if(e)Object.assign(e,d);else S.expenses.push({id:uid(),...d});closeS();persist()}
function delE(id){if(confirm('এই খরচ মুছবেন?')){S.expenses=S.expenses.filter(e=>e.id!==id);persist()}}
/* backup / restore / csv */
function outS(name,text,mime,title){const url=null;window._o={name,text,mime};
 sheet(`<h3>${title}</h3><div class="mu" style="margin-bottom:10px">নিচের যেকোনো একটি উপায়ে ফাইলটি নিজের কাছে সংরক্ষণ করুন (ফাইল অ্যাপ, ইমেইল, বা নোটস)।</div><div class="row"><button class="btn" onclick="shareO()">ফাইল সেভ / শেয়ার</button><button class="btn o" onclick="copyO()">টেক্সট কপি</button></div><textarea id="ot" readonly rows="6" style="margin-top:10px;font-size:12px">${esc(text)}</textarea><div class="row" style="margin-top:10px"><button class="btn o" onclick="closeS()">বন্ধ করুন</button></div>`)}
async function shareO(){const{name,text,mime}=window._o,file=new File([text],name,{type:mime});
 try{if(navigator.canShare&&navigator.canShare({files:[file]})){await navigator.share({files:[file],title:name});return done()}}catch(e){if(e.name==='AbortError')return}
 try{const a=document.createElement('a');a.href=URL.createObjectURL(new Blob([text],{type:mime}));a.download=name;document.body.appendChild(a);a.click();a.remove();done()}catch(e){copyO()}}
async function copyO(){try{await navigator.clipboard.writeText(window._o.text)}catch(e){const t=$('#ot');t.select();document.execCommand('copy')}done();alert('কপি হয়েছে। নোটস বা ইমেইলে পেস্ট করে রাখুন।')}
function done(){if(window._o.mime.includes('json')){S.lastBackup=Date.now();save()}}
function expJ(){outS('boihisab-backup-'+today()+'.json',JSON.stringify(S),'application/json','JSON ব্যাকআপ')}
function expC(){const T=calc(),q=v=>'"'+String(v??'').replace(/"/g,'""')+'"',r=[['তারিখ','ক্রেতা','ফোন','বই','পরিমাণ','দাম','মোট','পেয়েছি','বকেয়া','খরচ','লাভ','ডেলিভারি','অবস্থা']];
 T.o.forEach(o=>r.push([o.date,o.c.name,o.c.phone,o.book,o.qty,o.price,o.total,o.paid,o.due,Math.round(o.cost),Math.round(o.profit),o.delivered?'সম্পন্ন':'বাকি',({pd:'পরিশোধিত',pt:'আংশিক',un:'বকেয়া',cx:'বাতিল'})[o.ps]]));
 r.push([]);r.push(['খরচ','নাম','টাকা','তারিখ','ক্যাটাগরি']);S.expenses.forEach(e=>r.push(['',e.name,e.amount,e.date,e.cat]));
 outS('boihisab-orders-'+today()+'.csv','\ufeff'+r.map(x=>x.map(q).join(',')).join('\n'),'text/csv','CSV এক্সপোর্ট')}
function fRest(){sheet(`<h3>ব্যাকআপ রিস্টোর</h3><div class="warn">রিস্টোর করলে বর্তমান সব তথ্য ব্যাকআপের তথ্য দিয়ে বদলে যাবে।</div><label>ব্যাকআপ ফাইল বেছে নিন (.json)<input type="file" accept=".json,application/json" onchange="rf(this.files[0])"></label><label>অথবা কপি করা টেক্সট পেস্ট করুন<textarea id="rt" rows="5"></textarea></label>${btns('doRest(g(\'rt\'))')}`)}
function rf(f){if(!f)return;const r=new FileReader();r.onload=()=>doRest(r.result);r.readAsText(f)}
function doRest(t){try{const d=JSON.parse(t);if(!Array.isArray(d.batches)||!Array.isArray(d.orders)||!Array.isArray(d.payments))throw 0;
 if(!confirm('বর্তমান তথ্য মুছে ব্যাকআপ থেকে রিস্টোর করবেন?'))return;d.customers=d.customers||[];d.expenses=d.expenses||[];S=d;closeS();persist();alert('রিস্টোর সম্পন্ন হয়েছে।')}catch(e){alert('ফাইলটি সঠিক BoiHisab ব্যাকআপ নয়।')}}
/* start */
(async()=>{const s=await load();S=s||seed();if(!s)save();try{navigator.storage&&navigator.storage.persist&&navigator.storage.persist()}catch(e){}render()})();
</script></body></html>
