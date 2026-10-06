
<html lang="zh-Hant">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<title>尾牙賓果</title>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;500;700&family=Noto+Serif+TC:wght@700&display=swap">
<style>
:root{
  color-scheme:light;
  --bg:#fbf4ee; --surface:#ffffff; --line:#e6d6c8; --fg:#2a1a14; --muted:#7d6355;
  --accent:#b01e28; --gold:#c08a2e; --good:#1f7a4d;
  --shadow:0 1px 2px rgba(60,30,20,.08),0 8px 24px rgba(60,30,20,.06);
  --font-display:"Noto Serif TC",Georgia,serif;
  --font-body:"Noto Sans TC",system-ui,-apple-system,"PingFang TC","Microsoft JhengHei",sans-serif;
  padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){
  color-scheme:dark;
  --bg:#17100e; --surface:#231816; --line:#3b2a25; --fg:#f4e9e2; --muted:#b09a8f;
  --accent:#e4616a; --gold:#e0ac4c; --good:#4bbd85;
  --shadow:0 1px 2px rgba(0,0,0,.4),0 8px 24px rgba(0,0,0,.35);
}}
:root[data-theme="dark"]{
  color-scheme:dark;
  --bg:#17100e; --surface:#231816; --line:#3b2a25; --fg:#f4e9e2; --muted:#b09a8f;
  --accent:#e4616a; --gold:#e0ac4c; --good:#4bbd85;
  --shadow:0 1px 2px rgba(0,0,0,.4),0 8px 24px rgba(0,0,0,.35);
}
*{box-sizing:border-box}
html,body{margin:0}
body{background:var(--bg);color:var(--fg);font-family:var(--font-body);font-size:14px}
img{max-width:100%}
[hidden]{display:none!important}
.wrap{max-width:760px;margin:0 auto;padding-inline:16px;padding-block:20px 56px}
h1{font-family:var(--font-display);font-size:26px;margin:0;letter-spacing:.02em}
h2{font-family:var(--font-display);font-size:18px;margin:0 0 10px}
.sub{color:var(--muted);font-size:13px;margin:4px 0 0}
header.top{display:flex;align-items:baseline;gap:12px;flex-wrap:wrap;border-bottom:2px solid var(--accent);padding-bottom:12px;margin-bottom:16px}
.tabs{display:flex;gap:8px;margin-bottom:18px}
.tabs button{flex:1;min-width:0;padding:10px 8px;border:1px solid var(--line);background:var(--surface);color:var(--muted);border-radius:8px;font:inherit;font-size:14px;cursor:pointer}
.tabs button[aria-selected="true"]{background:var(--accent);border-color:var(--accent);color:#fff;font-weight:700}
.panel{background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:18px;box-shadow:var(--shadow);margin-bottom:16px}
label{display:block;font-size:12px;letter-spacing:.06em;color:var(--muted);margin-bottom:6px}
input[type=text],input[type=number]{width:100%;padding:10px 12px;border:1px solid var(--line);border-radius:8px;background:var(--bg);color:var(--fg);font:inherit}
.row{display:flex;gap:10px;flex-wrap:wrap;align-items:flex-end}
.row>*{min-width:0}
.btn{padding:10px 16px;border-radius:8px;border:1px solid var(--accent);background:var(--accent);color:#fff;font:inherit;font-weight:700;cursor:pointer}
.btn.ghost{background:transparent;color:var(--accent)}
.btn:disabled{opacity:.45;cursor:not-allowed}
.grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin:14px 0}
.cell{aspect-ratio:1;display:flex;align-items:center;justify-content:center;border:1px solid var(--line);border-radius:10px;background:var(--bg);font-size:clamp(18px,6vw,26px);font-weight:700;font-variant-numeric:tabular-nums;font-family:var(--font-display)}
.cell.hit{background:var(--accent);border-color:var(--accent);color:#fff}
.cell.pick{cursor:pointer}
.cell.sel{outline:2px solid var(--gold);outline-offset:1px}
.chips{display:flex;flex-wrap:wrap;gap:6px}
.chip{min-width:36px;text-align:center;padding:6px 8px;border-radius:999px;border:1px solid var(--line);font:inherit;font-size:13px;font-variant-numeric:tabular-nums;background:var(--bg);color:var(--fg)}
button.chip{cursor:pointer}
.chip.on{background:var(--gold);border-color:var(--gold);color:#241603;font-weight:700}
.chip.latest{background:var(--accent);border-color:var(--accent);color:#fff}
.note{font-size:13px;color:var(--muted);line-height:1.6}
.big{font-family:var(--font-display);font-size:64px;line-height:1;color:var(--accent);font-variant-numeric:tabular-nums}
table{width:100%;border-collapse:collapse;font-size:14px}
th,td{text-align:left;padding:8px 6px;border-bottom:1px solid var(--line)}
th{font-size:11px;letter-spacing:.06em;color:var(--muted)}
td.n{text-align:right;font-variant-numeric:tabular-nums}
.tablewrap{overflow-x:auto}
.pill{display:inline-block;padding:2px 8px;border-radius:999px;font-size:12px;font-weight:700;background:var(--good);color:#fff}
.stats{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:12px}
.stat{flex:1 1 90px;border:1px solid var(--line);border-radius:10px;padding:10px;text-align:center;background:var(--bg)}
.stat b{display:block;font-size:22px;font-variant-numeric:tabular-nums}
.stat span{font-size:12px;color:var(--muted)}
.hr{height:1px;background:var(--line);margin:16px 0}
.err{color:var(--accent);font-size:13px;margin-top:8px}
:focus-visible{outline:2px solid var(--gold);outline-offset:2px}
</style>
</head>
<body>
<div class="wrap">
  <header class="top">
    <h1>尾牙賓果</h1>
    <p class="sub">4×4 ・ 號碼 1–50 ・ 連線即中獎</p>
  </header>

  <div class="tabs" role="tablist">
    <button id="tabPlay" role="tab" aria-selected="true">我的賓果卡</button>
    <button id="tabHost" role="tab" aria-selected="false">主持後台</button>
  </div>

  <section id="viewPlay">
    <div class="panel" id="boot"><p class="note">連線中…</p></div>

    <div class="panel" id="makeCard" hidden>
      <h2>製作你的賓果卡</h2>
      <p class="note">填上姓名，然後隨機產生或自己選號。送出後就不能再修改。</p>
      <div class="hr"></div>
      <label for="pname">姓名 / 部門</label>
      <input type="text" id="pname" maxlength="20" placeholder="例：杜小傑/心衛科">
      <div class="row" style="margin-top:12px">
        <button class="btn" id="btnRandom">隨機產生</button>
        <button class="btn ghost" id="btnManual">自己選號</button>
      </div>
      <p class="note" id="pickHint" hidden style="margin-top:14px">先點卡片上的格子，再點下方號碼填入。再點一次已填的格子可清除。已填 <b id="pickCount">0</b> / 16</p>
      <div class="grid" id="previewGrid"></div>
      <div id="pickArea" hidden><div class="chips" id="pool"></div></div>
      <button class="btn" id="btnSave" disabled>確認送出（不可更改）</button>
      <p class="err" id="saveErr" hidden></p>
    </div>

    <div class="panel" id="myCard" hidden>
      <h2 id="myName">我的賓果卡</h2>
      <p class="note">卡片已鎖定。對中的號碼會自動變色。</p>
      <div class="grid" id="myGrid"></div>
      <p class="note">目前 <span class="pill" id="myLines">0 條線</span>　已開出 <b id="myDrawn">0</b> 個號碼</p>
    </div>

    <div class="panel">
      <h2>已開出的號碼</h2>
      <div class="chips" id="playBoard"></div>
    </div>
  </section>

  <section id="viewHost" hidden>
    <div class="panel" id="lock">
      <h2>主持人登入</h2>
      <label for="pass">通關密碼</label>
      <div class="row">
        <input type="text" id="pass" style="flex:1 1 160px" placeholder="請輸入密碼">
        <button class="btn" id="btnPass">進入</button>
      </div>
      <p class="err" id="passErr" hidden>密碼錯誤</p>
    </div>

    <div id="hostBody" hidden>
      <div class="panel">
        <h2>抽號</h2>
        <div class="row" style="align-items:center;gap:20px">
          <div>
            <div class="big" id="lastNum">—</div>
            <span class="note">最新號碼</span>
          </div>
          <div style="flex:1 1 200px">
            <button class="btn" id="btnDraw" style="width:100%">隨機抽一個號碼</button>
            <div class="row" style="margin-top:10px">
              <input type="number" id="manualNum" min="1" max="50" placeholder="長官指定號碼 1–50" style="flex:1 1 120px">
              <button class="btn ghost" id="btnManualDraw">指定開出</button>
            </div>
            <p class="err" id="drawErr" hidden></p>
          </div>
        </div>
        <div class="hr"></div>
        <div class="chips" id="hostBoard"></div>
        <div class="hr"></div>
        <div class="row">
          <button class="btn ghost" id="btnUndo">收回上一個號碼</button>
          <button class="btn ghost" id="btnReset">清空重新開始</button>
        </div>
      </div>

      <div class="panel">
        <h2>中獎名單</h2>
        <div class="stats" id="stats"></div>
        <div class="tablewrap">
          <table>
            <thead><tr><th>姓名</th><th class="n">連線</th><th class="n">差一格</th></tr></thead>
            <tbody id="winners"></tbody>
          </table>
        </div>
        <p class="note" id="joinCount" style="margin-top:10px"></p>
      </div>
    </div>
  </section>
</div>

<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2.45.4/dist/umd/supabase.js"></script>
<script>
(function(){
  "use strict";

  /* ========= 只要改這三行 ========= */
  const SUPABASE_URL  = "https://opvnnnmrbqwduratnbbq.supabase.co/rest/v1/";
  const SUPABASE_ANON = "sb_publishable_iyC2JMQ_QgTDyy3hKPITHA_UqXKg5Fs";
  const HOST_PASS     = "u10111103@116";


  /* =============================== */

  const MAXN=50, SIZE=16, LS_KEY="bingo_player_id";
  const LINES=(function(){const L=[];
    for(let r=0;r<4;r++)L.push([0,1,2,3].map(c=>r*4+c));
    for(let c=0;c<4;c++)L.push([0,1,2,3].map(r=>r*4+c));
    L.push([0,5,10,15]);L.push([3,6,9,12]);return L;})();
  function linesFor(nums,drawn){
    const set=new Set(drawn);let full=0,near=0;
    for(const L of LINES){let hit=0;for(const i of L)if(set.has(nums[i]))hit++;
      if(hit===4)full++;else if(hit===3)near++;}
    return{full,near};
  }
  (function(){const r=linesFor([1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16],[1,2,3,4,5,6,7,8]);
    if(r.full!==2)console.warn("line check failed",r);})();

  const $=id=>document.getElementById(id);
  const ls={get(k){try{return localStorage.getItem(k)}catch(e){return null}},
            set(k,v){try{localStorage.setItem(k,v)}catch(e){}}};

  let sb=null, drawn=[], myNums=null, myNameVal="", allCards=[];
  let pick=new Array(SIZE).fill(null), manualMode=false, selSlot=0;

  function tab(w){
    $("tabPlay").setAttribute("aria-selected",w==="play");
    $("tabHost").setAttribute("aria-selected",w==="host");
    $("viewPlay").hidden=w!=="play"; $("viewHost").hidden=w!=="host";
  }
  $("tabPlay").onclick=()=>tab("play");
  $("tabHost").onclick=()=>tab("host");

  function renderBoard(el){
    el.replaceChildren();
    const set=new Set(drawn), last=drawn[drawn.length-1];
    for(let n=1;n<=MAXN;n++){
      const d=document.createElement("span");
      d.className="chip"+(set.has(n)?" on":"")+(n===last?" latest":"");
      d.textContent=n; el.appendChild(d);
    }
  }
  function renderMyCard(){
    if(!myNums)return;
    $("myCard").hidden=false; $("makeCard").hidden=true;
    $("myName").textContent=myNameVal?myNameVal+" 的賓果卡":"我的賓果卡";
    const set=new Set(drawn), g=$("myGrid"); g.replaceChildren();
    myNums.forEach(n=>{const d=document.createElement("div");
      d.className="cell"+(set.has(n)?" hit":"");d.textContent=n;g.appendChild(d);});
    $("myLines").textContent=linesFor(myNums,drawn).full+" 條線";
    $("myDrawn").textContent=drawn.length;
  }

  function randomNums(){
    const p=[];for(let i=1;i<=MAXN;i++)p.push(i);
    for(let i=p.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[p[i],p[j]]=[p[j],p[i]];}
    return p.slice(0,SIZE);
  }
  const filled=()=>pick.filter(v=>v!=null).length;
  function nextEmpty(from){for(let k=0;k<SIZE;k++){const i=(from+k)%SIZE;if(pick[i]==null)return i;}return -1;}
  function renderPreview(){
    const g=$("previewGrid");g.replaceChildren();
    for(let i=0;i<SIZE;i++){
      const d=document.createElement("div");
      d.className="cell"+(manualMode?" pick":"")+(manualMode&&i===selSlot?" sel":"");
      d.textContent=pick[i]!=null?pick[i]:"·";
      if(manualMode){
        d.setAttribute("role","button");d.tabIndex=0;
        const act=()=>{ if(pick[i]!=null&&i===selSlot)pick[i]=null; else selSlot=i;
          renderPool();renderPreview(); };
        d.onclick=act;
        d.onkeydown=e=>{if(e.key==="Enter"||e.key===" "){e.preventDefault();act();}};
      }
      g.appendChild(d);
    }
    $("pickCount").textContent=filled();
    $("btnSave").disabled=filled()!==SIZE;
  }
  function renderPool(){
    const p=$("pool");p.replaceChildren();
    const used=new Set(pick.filter(v=>v!=null));
    for(let n=1;n<=MAXN;n++){
      const b=document.createElement("button");
      b.type="button";b.className="chip"+(used.has(n)?" on":"");b.textContent=n;
      b.onclick=()=>{
        const at=pick.indexOf(n);
        if(at>=0){pick[at]=null;selSlot=at;}
        else{pick[selSlot]=n;const nx=nextEmpty(selSlot+1);if(nx>=0)selSlot=nx;}
        renderPool();renderPreview();
      };
      p.appendChild(b);
    }
  }
  $("btnRandom").onclick=()=>{manualMode=false;pick=randomNums();
    $("pickArea").hidden=true;$("pickHint").hidden=true;renderPreview();};
  $("btnManual").onclick=()=>{manualMode=true;pick=new Array(SIZE).fill(null);selSlot=0;
    $("pickArea").hidden=false;$("pickHint").hidden=false;renderPool();renderPreview();};

  $("btnSave").onclick=async()=>{
    const name=$("pname").value.trim();
    const err=$("saveErr");
    if(!name){err.hidden=false;err.textContent="請先填寫姓名。";return;}
    const nums=pick.slice();
    if(nums.some(v=>v==null)||new Set(nums).size!==SIZE){
      err.hidden=false;err.textContent="16 格都要填滿且號碼不重複。";return;}
    $("btnSave").disabled=true;err.hidden=true;
    const {data,error}=await sb.from("players").insert({name,nums}).select("id").single();
    if(error){err.hidden=false;err.textContent="送出失敗："+error.message;$("btnSave").disabled=false;return;}
    ls.set(LS_KEY,data.id);
    myNums=nums;myNameVal=name;renderMyCard();
  };

  let unlocked=ls.get("bingo_host")==="1";
  function showHost(){unlocked=true;$("lock").hidden=true;$("hostBody").hidden=false;ls.set("bingo_host","1");}
  if(unlocked)showHost();
  $("btnPass").onclick=()=>{if($("pass").value.trim()===HOST_PASS)showHost();else $("passErr").hidden=false;};
  $("pass").onkeydown=e=>{if(e.key==="Enter")$("btnPass").click();};

  async function saveDrawn(next){
    const {error}=await sb.from("game").update({drawn:next,updated_at:new Date().toISOString()}).eq("id",1);
    if(error){$("drawErr").hidden=false;$("drawErr").textContent="寫入失敗："+error.message;return;}
    drawn=next;renderAll();
  }
  $("btnDraw").onclick=()=>{
    $("drawErr").hidden=true;
    const set=new Set(drawn),left=[];
    for(let n=1;n<=MAXN;n++)if(!set.has(n))left.push(n);
    if(!left.length){$("drawErr").hidden=false;$("drawErr").textContent="50 個號碼都開完了。";return;}
    saveDrawn(drawn.concat(left[Math.floor(Math.random()*left.length)]));
  };
  $("btnManualDraw").onclick=()=>{
    $("drawErr").hidden=true;
    const n=parseInt($("manualNum").value,10);
    if(!(n>=1&&n<=MAXN)){$("drawErr").hidden=false;$("drawErr").textContent="請輸入 1 到 50 的號碼。";return;}
    if(drawn.includes(n)){$("drawErr").hidden=false;$("drawErr").textContent=n+" 已經開過了。";return;}
    $("manualNum").value="";saveDrawn(drawn.concat(n));
  };
  $("btnUndo").onclick=()=>{if(drawn.length)saveDrawn(drawn.slice(0,-1));};
  let armed=false;
  $("btnReset").onclick=()=>{
    if(!armed){armed=true;$("btnReset").textContent="再按一次確認清空";
      setTimeout(()=>{armed=false;$("btnReset").textContent="清空重新開始";},4000);return;}
    armed=false;$("btnReset").textContent="清空重新開始";saveDrawn([]);
  };

  function renderHost(){
    if(!unlocked)return;
    $("lastNum").textContent=drawn.length?drawn[drawn.length-1]:"—";
    renderBoard($("hostBoard"));
    const rows=allCards.map(c=>{const r=linesFor(c.nums||[],drawn);
      return{name:c.name||"（未具名）",full:r.full,near:r.near};})
      .sort((a,b)=>b.full-a.full||b.near-a.near||a.name.localeCompare(b.name,"zh-Hant"));
    const tb=$("winners");tb.replaceChildren();
    rows.filter(r=>r.full>0||r.near>0).slice(0,150).forEach(r=>{
      const tr=document.createElement("tr");
      const t1=document.createElement("td");t1.textContent=r.name;
      const t2=document.createElement("td");t2.className="n";
      if(r.full>0){const s=document.createElement("span");s.className="pill";s.textContent=r.full+" 線";t2.appendChild(s);}
      else t2.textContent="—";
      const t3=document.createElement("td");t3.className="n";t3.textContent=r.near;
      tr.append(t1,t2,t3);tb.appendChild(tr);
    });
    const st=$("stats");st.replaceChildren();
    [["一線以上",1],["兩線以上",2],["三線以上",3]].forEach(([lab,k])=>{
      const d=document.createElement("div");d.className="stat";
      const b=document.createElement("b");b.textContent=rows.filter(r=>r.full>=k).length;
      const s=document.createElement("span");s.textContent=lab;
      d.append(b,s);st.appendChild(d);
    });
    $("joinCount").textContent="目前已建卡人數："+allCards.length;
  }
  function renderAll(){renderBoard($("playBoard"));renderMyCard();renderHost();}

  function bootFail(msg){
    $("boot").hidden=false;$("boot").replaceChildren();
    const p=document.createElement("p");p.className="note";p.textContent=msg;
    $("boot").appendChild(p);
  }

  (async function(){
    try{
      if(!window.supabase){bootFail("無法載入連線程式，請確認網路後重新整理。");return;}
      if(SUPABASE_URL.indexOf("你的")>=0){bootFail("尚未填入 Supabase 連線資訊，請打開檔案修改最上方三行設定。");return;}
      sb=window.supabase.createClient(SUPABASE_URL,SUPABASE_ANON);

      const g=await sb.from("game").select("drawn").eq("id",1).single();
      if(g.error){bootFail("連線失敗："+g.error.message);return;}
      drawn=g.data.drawn||[];

      const p=await sb.from("players").select("id,name,nums");
      if(p.error){bootFail("讀取名單失敗："+p.error.message);return;}
      allCards=p.data||[];

      const myId=ls.get(LS_KEY);
      if(myId){
        const mine=allCards.find(c=>c.id===myId);
        if(mine){myNums=mine.nums;myNameVal=mine.name;}
      }
      $("boot").hidden=true;
      if(!myNums)$("makeCard").hidden=false;

      sb.channel("bingo")
        .on("postgres_changes",{event:"UPDATE",schema:"public",table:"game"},
          pay=>{drawn=(pay.new&&pay.new.drawn)||[];renderAll();})
        .on("postgres_changes",{event:"INSERT",schema:"public",table:"players"},
          pay=>{if(pay.new){allCards.push(pay.new);renderHost();}})
        .subscribe();

      // 保險：每 20 秒對一次，避免推播漏掉
      setInterval(async()=>{
        const r=await sb.from("game").select("drawn").eq("id",1).single();
        if(!r.error&&r.data){
          const nd=r.data.drawn||[];
          if(nd.length!==drawn.length){drawn=nd;renderAll();}
        }
        if(unlocked){
          const q=await sb.from("players").select("id,name,nums");
          if(!q.error&&q.data&&q.data.length!==allCards.length){allCards=q.data;renderHost();}
        }
      },20000);

      renderPreview();renderAll();
    }catch(e){
      console.error(e);bootFail("載入時發生問題，請重新整理頁面。");
    }
  })();
})();
</script>
</body>
</html>

