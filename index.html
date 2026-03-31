<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shopmart — AI Product Research</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Mono:wght@400;500&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,400&display=swap" rel="stylesheet">
<style>
:root {
  --bg: #08080e;
  --s1: #10101a;
  --s2: #16161f;
  --s3: #1e1e2a;
  --border: rgba(255,255,255,0.06);
  --border2: rgba(255,255,255,0.11);
  --accent: #00d68f;
  --accent-dim: rgba(0,214,143,0.12);
  --amber: #f59e0b;
  --amber-dim: rgba(245,158,11,0.12);
  --purple: #8b5cf6;
  --purple-dim: rgba(139,92,246,0.12);
  --blue: #3b82f6;
  --blue-dim: rgba(59,130,246,0.12);
  --red: #ef4444;
  --text: #eeeef5;
  --text2: #7777a0;
  --text3: #44445a;
  --usa: #3b82f6;
  --uk: #8b5cf6;
  --au: #10b981;
  --gulf: #f59e0b;
}
* { margin:0; padding:0; box-sizing:border-box; }
body {
  font-family: 'DM Sans', sans-serif;
  background: var(--bg);
  color: var(--text);
  min-height: 100vh;
}
body::before {
  content:'';
  position:fixed;
  inset:0;
  background-image:
    linear-gradient(rgba(255,255,255,0.018) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.018) 1px, transparent 1px);
  background-size: 48px 48px;
  pointer-events:none;
  z-index:0;
}
.wrap { max-width: 980px; margin: 0 auto; padding: 2rem 1.5rem 5rem; position:relative; z-index:1; }

/* HEADER */
.header { margin-bottom: 2.5rem; }
.logo-row { display:flex; align-items:center; gap:10px; margin-bottom:0.6rem; }
.pulse { width:9px; height:9px; border-radius:50%; background:var(--accent); box-shadow: 0 0 0 0 rgba(0,214,143,0.4); animation: pulse 2s infinite; }
@keyframes pulse { 0%{box-shadow:0 0 0 0 rgba(0,214,143,0.4)} 70%{box-shadow:0 0 0 8px rgba(0,214,143,0)} 100%{box-shadow:0 0 0 0 rgba(0,214,143,0)} }
.brand { font-family:'Syne',sans-serif; font-size:13px; font-weight:600; letter-spacing:0.12em; color:var(--accent); text-transform:uppercase; }
h1 { font-family:'Syne',sans-serif; font-size:clamp(1.6rem,4vw,2.4rem); font-weight:800; color:var(--text); line-height:1.1; }
h1 span { color:var(--accent); }
.sub { font-size:14px; color:var(--text2); margin-top:0.5rem; }

/* ZONES */
.zones-bar { display:flex; gap:8px; flex-wrap:wrap; margin-bottom:1.5rem; }
.zone-pill { display:flex; align-items:center; gap:6px; padding:5px 12px; border-radius:99px; border:1px solid; font-size:12px; font-weight:500; font-family:'DM Mono',monospace; }
.z-usa { border-color:rgba(59,130,246,0.4); background:rgba(59,130,246,0.08); color:#93c5fd; }
.z-uk  { border-color:rgba(139,92,246,0.4); background:rgba(139,92,246,0.08); color:#c4b5fd; }
.z-au  { border-color:rgba(16,185,129,0.4); background:rgba(16,185,129,0.08); color:#6ee7b7; }
.z-gulf{ border-color:rgba(245,158,11,0.4); background:rgba(245,158,11,0.08); color:#fcd34d; }
.zone-dot { width:6px; height:6px; border-radius:50%; flex-shrink:0; }

/* CONTROLS */
.controls { background:var(--s1); border:1px solid var(--border); border-radius:16px; padding:1.5rem; margin-bottom:1.5rem; }
.controls-grid { display:grid; grid-template-columns:1fr 1fr; gap:1rem; margin-bottom:1rem; }
@media(max-width:560px){.controls-grid{grid-template-columns:1fr;}}
.field label { font-size:11px; font-weight:500; color:var(--text2); letter-spacing:0.08em; text-transform:uppercase; display:block; margin-bottom:6px; }
select, input[type=text] {
  width:100%; background:var(--s2); border:1px solid var(--border2); border-radius:8px;
  color:var(--text); font-family:'DM Sans',sans-serif; font-size:13px; padding:9px 12px;
  appearance:none; outline:none; transition:border-color 0.2s;
}
select:focus, input[type=text]:focus { border-color:rgba(0,214,143,0.4); }
.zone-checks { display:flex; gap:8px; flex-wrap:wrap; }
.zone-check { display:flex; align-items:center; gap:5px; cursor:pointer; }
.zone-check input { display:none; }
.zone-check-label {
  padding:5px 11px; border-radius:99px; border:1px solid var(--border2);
  font-size:12px; font-weight:500; color:var(--text2); cursor:pointer;
  transition:all 0.15s; user-select:none;
}
.zone-check input:checked + .zone-check-label.usa { border-color:rgba(59,130,246,0.5); background:rgba(59,130,246,0.12); color:#93c5fd; }
.zone-check input:checked + .zone-check-label.uk  { border-color:rgba(139,92,246,0.5); background:rgba(139,92,246,0.12); color:#c4b5fd; }
.zone-check input:checked + .zone-check-label.au  { border-color:rgba(16,185,129,0.5); background:rgba(16,185,129,0.12); color:#6ee7b7; }
.zone-check input:checked + .zone-check-label.gulf{ border-color:rgba(245,158,11,0.5); background:rgba(245,158,11,0.12); color:#fcd34d; }
.run-btn {
  width:100%; padding:13px; border-radius:10px; border:none; cursor:pointer;
  background:var(--accent); color:#000; font-family:'Syne',sans-serif;
  font-size:14px; font-weight:700; letter-spacing:0.05em; transition:all 0.2s;
  display:flex; align-items:center; justify-content:center; gap:8px;
}
.run-btn:hover { background:#00f5a0; transform:translateY(-1px); }
.run-btn:disabled { background:var(--s3); color:var(--text3); cursor:not-allowed; transform:none; }
.run-btn .spinner { width:16px; height:16px; border:2px solid rgba(0,0,0,0.2); border-top-color:#000; border-radius:50%; animation:spin 0.7s linear infinite; display:none; }
.run-btn.loading .spinner { display:block; }
.run-btn.loading .btn-text { opacity:0.6; }
@keyframes spin{to{transform:rotate(360deg)}}

/* STATUS */
.status-bar { background:var(--s2); border:1px solid var(--border); border-radius:10px; padding:10px 14px; margin-bottom:1.5rem; display:none; font-size:13px; color:var(--text2); font-family:'DM Mono',monospace; }
.status-bar.visible { display:flex; align-items:center; gap:8px; }
.status-dot { width:6px; height:6px; border-radius:50%; background:var(--accent); animation:pulse 1.2s infinite; flex-shrink:0; }

/* RESULTS */
.results-header { display:flex; align-items:center; justify-content:space-between; margin-bottom:1rem; }
.results-title { font-family:'Syne',sans-serif; font-size:15px; font-weight:700; }
.results-meta { font-size:12px; color:var(--text2); font-family:'DM Mono',monospace; }
.products-grid { display:grid; grid-template-columns:repeat(auto-fill,minmax(280px,1fr)); gap:14px; }

/* PRODUCT CARD */
.product-card {
  background:var(--s1); border:1px solid var(--border); border-radius:14px;
  padding:1.1rem; cursor:pointer; transition:all 0.2s; position:relative; overflow:hidden;
}
.product-card::before {
  content:''; position:absolute; top:0; left:0; right:0; height:2px;
  background:linear-gradient(90deg, transparent, var(--accent-color,var(--accent)), transparent);
  opacity:0; transition:opacity 0.2s;
}
.product-card:hover { border-color:var(--border2); transform:translateY(-2px); }
.product-card:hover::before { opacity:1; }

.card-top { display:flex; align-items:flex-start; justify-content:space-between; gap:8px; margin-bottom:10px; }
.card-rank { font-family:'DM Mono',monospace; font-size:11px; color:var(--text3); }
.score-badge { padding:3px 8px; border-radius:99px; font-size:11px; font-weight:600; font-family:'DM Mono',monospace; }
.score-hot { background:rgba(239,68,68,0.15); color:#fca5a5; border:1px solid rgba(239,68,68,0.2); }
.score-high { background:rgba(0,214,143,0.12); color:#6ee7b7; border:1px solid rgba(0,214,143,0.2); }
.score-med { background:rgba(245,158,11,0.12); color:#fcd34d; border:1px solid rgba(245,158,11,0.2); }

.product-name { font-family:'Syne',sans-serif; font-size:14px; font-weight:700; color:var(--text); margin-bottom:4px; line-height:1.3; }
.product-desc { font-size:12px; color:var(--text2); line-height:1.5; margin-bottom:10px; }

.metrics { display:grid; grid-template-columns:1fr 1fr; gap:6px; margin-bottom:10px; }
.metric { background:var(--s2); border-radius:7px; padding:7px 9px; }
.metric-label { font-size:10px; color:var(--text3); text-transform:uppercase; letter-spacing:0.06em; margin-bottom:2px; }
.metric-value { font-family:'DM Mono',monospace; font-size:13px; font-weight:500; color:var(--text); }
.metric-value.green { color:var(--accent); }
.metric-value.amber { color:var(--amber); }

.zone-tags { display:flex; gap:4px; flex-wrap:wrap; margin-bottom:10px; }
.zone-tag { padding:2px 7px; border-radius:4px; font-size:10px; font-weight:600; font-family:'DM Mono',monospace; }
.zt-usa { background:rgba(59,130,246,0.12); color:#93c5fd; }
.zt-uk  { background:rgba(139,92,246,0.12); color:#c4b5fd; }
.zt-au  { background:rgba(16,185,129,0.12); color:#6ee7b7; }
.zt-gulf{ background:rgba(245,158,11,0.12); color:#fcd34d; }

.tiktok-angle { background:var(--s2); border-radius:7px; padding:8px 10px; margin-bottom:10px; }
.tiktok-angle-label { font-size:10px; color:var(--text3); text-transform:uppercase; letter-spacing:0.06em; margin-bottom:3px; }
.tiktok-angle-text { font-size:12px; color:var(--text2); line-height:1.4; font-style:italic; }

.card-actions { display:flex; gap:6px; }
.copy-btn {
  flex:1; padding:7px 10px; border-radius:7px; border:1px solid var(--border2);
  background:transparent; color:var(--text2); font-size:11px; font-family:'DM Mono',monospace;
  cursor:pointer; transition:all 0.15s; text-align:center;
}
.copy-btn:hover { background:var(--s3); color:var(--text); border-color:var(--border2); }
.copy-btn.copied { border-color:rgba(0,214,143,0.4); color:var(--accent); background:var(--accent-dim); }
.import-btn {
  flex:1; padding:7px 10px; border-radius:7px; border:none;
  background:var(--accent-dim); color:var(--accent); font-size:11px; font-family:'DM Mono',monospace;
  cursor:pointer; transition:all 0.15s; font-weight:500;
}
.import-btn:hover { background:rgba(0,214,143,0.2); }

/* EMPTY / ERROR */
.empty { text-align:center; padding:4rem 2rem; color:var(--text2); }
.empty-icon { width:48px; height:48px; border:1px solid var(--border2); border-radius:12px; display:flex; align-items:center; justify-content:center; margin:0 auto 1rem; }
.error-box { background:rgba(239,68,68,0.08); border:1px solid rgba(239,68,68,0.2); border-radius:10px; padding:1rem 1.2rem; margin-bottom:1rem; font-size:13px; color:#fca5a5; display:none; }
.error-box.visible { display:block; }

/* FOOTER */
.footer-note { text-align:center; margin-top:2rem; font-size:11px; color:var(--text3); font-family:'DM Mono',monospace; }
</style>
</head>
<body>
<div class="wrap">

  <div class="header">
    <div class="logo-row">
      <div class="pulse"></div>
      <span class="brand">Shopmart · AI Research</span>
    </div>
    <h1>Find <span>trending products</span><br>for your markets</h1>
    <p class="sub">Powered by Claude AI · Scored for TikTok virality + regional demand</p>
  </div>

  <div class="zones-bar">
    <div class="zone-pill z-usa"><div class="zone-dot" style="background:#3b82f6"></div>USA</div>
    <div class="zone-pill z-uk"><div class="zone-dot" style="background:#8b5cf6"></div>UK</div>
    <div class="zone-pill z-au"><div class="zone-dot" style="background:#10b981"></div>Australia</div>
    <div class="zone-pill z-gulf"><div class="zone-dot" style="background:#f59e0b"></div>Saudi Arabia</div>
    <div class="zone-pill z-gulf"><div class="zone-dot" style="background:#f59e0b"></div>UAE</div>
    <div class="zone-pill z-gulf"><div class="zone-dot" style="background:#f59e0b"></div>Kuwait</div>
    <div class="zone-pill z-gulf"><div class="zone-dot" style="background:#f59e0b"></div>Qatar</div>
  </div>

  <div class="controls">
    <div class="controls-grid">
      <div class="field">
        <label>Product category</label>
        <select id="category">
          <option value="any">Any — let AI decide</option>
          <option value="home gadgets">Home & kitchen gadgets</option>
          <option value="beauty skincare">Beauty & skincare</option>
          <option value="fitness health">Fitness & health</option>
          <option value="pet products">Pet products</option>
          <option value="baby kids">Baby & kids</option>
          <option value="tech electronics">Tech & electronics</option>
          <option value="fashion accessories">Fashion & accessories</option>
          <option value="outdoor travel">Outdoor & travel</option>
          <option value="cleaning organization">Cleaning & organization</option>
          <option value="car accessories">Car accessories</option>
        </select>
      </div>
      <div class="field">
        <label>Price range (selling price USD)</label>
        <select id="priceRange">
          <option value="$15-$30">Budget · $15–$30</option>
          <option value="$25-$50" selected>Sweet spot · $25–$50</option>
          <option value="$40-$80">Mid · $40–$80</option>
          <option value="$60-$120">Premium · $60–$120</option>
        </select>
      </div>
    </div>
    <div class="field" style="margin-bottom:1rem;">
      <label>Target zones</label>
      <div class="zone-checks">
        <label class="zone-check"><input type="checkbox" value="USA" checked><span class="zone-check-label usa">🇺🇸 USA</span></label>
        <label class="zone-check"><input type="checkbox" value="UK" checked><span class="zone-check-label uk">🇬🇧 UK</span></label>
        <label class="zone-check"><input type="checkbox" value="Australia" checked><span class="zone-check-label au">🇦🇺 Australia</span></label>
        <label class="zone-check"><input type="checkbox" value="Saudi Arabia" checked><span class="zone-check-label gulf">🇸🇦 Saudi Arabia</span></label>
        <label class="zone-check"><input type="checkbox" value="UAE" checked><span class="zone-check-label gulf">🇦🇪 UAE</span></label>
        <label class="zone-check"><input type="checkbox" value="Kuwait" checked><span class="zone-check-label gulf">🇰🇼 Kuwait</span></label>
        <label class="zone-check"><input type="checkbox" value="Qatar" checked><span class="zone-check-label gulf">🇶🇦 Qatar</span></label>
      </div>
    </div>
    <div class="field" style="margin-bottom:1rem;">
      <label>Number of products to find</label>
      <select id="count">
        <option value="5">5 products</option>
        <option value="8" selected>8 products</option>
        <option value="12">12 products</option>
      </select>
    </div>
    <div class="error-box" id="errorBox"></div>
    <button class="run-btn" id="runBtn" onclick="runResearch()">
      <div class="spinner"></div>
      <span class="btn-text">Find Trending Products</span>
    </button>
  </div>

  <div class="status-bar" id="statusBar">
    <div class="status-dot"></div>
    <span id="statusText">Analyzing trends...</span>
  </div>

  <div id="resultsWrap" style="display:none;">
    <div class="results-header">
      <div class="results-title" id="resultsTitle">Trending products</div>
      <div class="results-meta" id="resultsMeta"></div>
    </div>
    <div class="products-grid" id="productsGrid"></div>
  </div>

  <div class="empty" id="emptyState">
    <div class="empty-icon">
      <svg width="20" height="20" viewBox="0 0 20 20" fill="none"><path d="M10 2l2.4 5 5.6.8-4 3.9.9 5.5L10 14.5l-4.9 2.7.9-5.5L2 7.8l5.6-.8L10 2z" stroke="#44445a" stroke-width="1.4" stroke-linejoin="round"/></svg>
    </div>
    <p style="font-size:13px;">Configure your search above and click<br><strong style="color:var(--text);">Find Trending Products</strong></p>
  </div>

  <p class="footer-note">Results are AI-generated suggestions · Always verify demand on TikTok and AliExpress before importing</p>
</div>

<script>
const ZONES_INFO = {
  'USA': { code:'usa', flag:'🇺🇸', color:'#3b82f6' },
  'UK': { code:'uk', flag:'🇬🇧', color:'#8b5cf6' },
  'Australia': { code:'au', flag:'🇦🇺', color:'#10b981' },
  'Saudi Arabia': { code:'gulf', flag:'🇸🇦', color:'#f59e0b' },
  'UAE': { code:'gulf', flag:'🇦🇪', color:'#f59e0b' },
  'Kuwait': { code:'gulf', flag:'🇰🇼', color:'#f59e0b' },
  'Qatar': { code:'gulf', flag:'🇶🇦', color:'#f59e0b' },
};

function setStatus(msg) {
  const bar = document.getElementById('statusBar');
  bar.className = 'status-bar visible';
  document.getElementById('statusText').textContent = msg;
}
function hideStatus() {
  document.getElementById('statusBar').className = 'status-bar';
}
function showError(msg) {
  const box = document.getElementById('errorBox');
  box.textContent = msg;
  box.className = 'error-box visible';
}
function hideError() {
  document.getElementById('errorBox').className = 'error-box';
}

function getSelectedZones() {
  return Array.from(document.querySelectorAll('.zone-check input:checked')).map(i => i.value);
}

function scoreClass(score) {
  if (score >= 88) return 'score-hot';
  if (score >= 75) return 'score-high';
  return 'score-med';
}
function scoreLabel(score) {
  if (score >= 88) return '🔥 HOT';
  if (score >= 75) return '↑ HIGH';
  return '~ MED';
}

function renderProducts(products) {
  const grid = document.getElementById('productsGrid');
  grid.innerHTML = '';
  products.forEach((p, i) => {
    const zones = p.zones || [];
    const zoneTags = zones.map(z => {
      const info = ZONES_INFO[z] || { code:'usa', flag:'', color:'#888' };
      return `<span class="zone-tag zt-${info.code}">${ZONES_INFO[z]?.flag || ''} ${z}</span>`;
    }).join('');

    const card = document.createElement('div');
    card.className = 'product-card';
    card.style.setProperty('--accent-color', p.accentColor || 'var(--accent)');
    card.innerHTML = `
      <div class="card-top">
        <span class="card-rank">#${String(i+1).padStart(2,'0')}</span>
        <span class="score-badge ${scoreClass(p.score)}">${scoreLabel(p.score)} · ${p.score}/100</span>
      </div>
      <div class="product-name">${p.name}</div>
      <div class="product-desc">${p.description}</div>
      <div class="metrics">
        <div class="metric">
          <div class="metric-label">Buy price (Ali)</div>
          <div class="metric-value amber">${p.aliPrice}</div>
        </div>
        <div class="metric">
          <div class="metric-label">Sell price</div>
          <div class="metric-value">${p.sellPrice}</div>
        </div>
        <div class="metric">
          <div class="metric-label">Est. profit</div>
          <div class="metric-value green">${p.profit}</div>
        </div>
        <div class="metric">
          <div class="metric-label">Ship time</div>
          <div class="metric-value">${p.shipping}</div>
        </div>
      </div>
      <div class="zone-tags">${zoneTags}</div>
      <div class="tiktok-angle">
        <div class="tiktok-angle-label">TikTok angle</div>
        <div class="tiktok-angle-text">"${p.tiktokAngle}"</div>
      </div>
      <div class="card-actions">
        <button class="copy-btn" onclick="copyTerm(this, '${p.aliSearch.replace(/'/g,"\\'")}')">Copy AliExpress search</button>
        <button class="import-btn" onclick="openDsers('${p.aliSearch.replace(/'/g,"\\'")}')">→ Open in DSers</button>
      </div>
    `;
    grid.appendChild(card);
  });
}

function copyTerm(btn, term) {
  navigator.clipboard.writeText(term).then(() => {
    btn.textContent = '✓ Copied!';
    btn.className = 'copy-btn copied';
    setTimeout(() => {
      btn.textContent = 'Copy AliExpress search';
      btn.className = 'copy-btn';
    }, 2000);
  });
}

function openDsers(term) {
  const url = `https://www.dsers.com/application/find-supplier?productName=${encodeURIComponent(term)}`;
  window.open(url, '_blank');
}

async function runResearch() {
  const btn = document.getElementById('runBtn');
  const category = document.getElementById('category').value;
  const priceRange = document.getElementById('priceRange').value;
  const count = parseInt(document.getElementById('count').value);
  const zones = getSelectedZones();

  if (zones.length === 0) { showError('Please select at least one target zone.'); return; }

  hideError();
  btn.disabled = true;
  btn.className = 'run-btn loading';
  document.getElementById('resultsWrap').style.display = 'none';
  document.getElementById('emptyState').style.display = 'none';

  const englishZones = zones.filter(z => ['USA','UK','Australia'].includes(z));
  const gulfZones = zones.filter(z => ['Saudi Arabia','UAE','Kuwait','Qatar'].includes(z));

  const prompt = `You are a dropshipping product research expert specializing in TikTok viral products.

Find ${count} trending dropshipping products for a Shopmart store targeting these markets:
${englishZones.length ? `English markets: ${englishZones.join(', ')}` : ''}
${gulfZones.length ? `Gulf markets: ${gulfZones.join(', ')}` : ''}

Category focus: ${category === 'any' ? 'Any high-potential category' : category}
Selling price range: ${priceRange} USD

Requirements for each product:
- Must be sourceable from AliExpress
- Must have strong TikTok viral potential (visual, demonstrates value, solves problem)
- Must ship within 7-15 days via AliExpress Standard Shipping
- Gulf products: must be culturally appropriate for Saudi Arabia, UAE, Kuwait, Qatar
- Prefer products NOT saturated on TikTok yet

Return ONLY a valid JSON array. No explanation, no markdown, no backticks. Just the raw JSON array.

Each product object must have exactly these fields:
{
  "name": "Short product name (max 5 words)",
  "description": "One sentence: what it does and why people buy it (max 20 words)",
  "score": number 60-99 (overall opportunity score),
  "aliPrice": "e.g. $4–$8",
  "sellPrice": "e.g. $29.99",
  "profit": "e.g. ~$18",
  "shipping": "e.g. 8–12 days",
  "zones": ["USA","UK","Australia","Saudi Arabia","UAE","Kuwait","Qatar"] (only zones where this product has demand),
  "tiktokAngle": "One sentence describing the exact TikTok video hook/angle that would make this go viral",
  "aliSearch": "Exact search term to find this on AliExpress (3-6 words)",
  "accentColor": one of ["#3b82f6","#8b5cf6","#10b981","#f59e0b","#ef4444","#00d68f"]
}

Sort by score descending. Return only the JSON array, nothing else.`;

  const statuses = [
    'Scanning TikTok trends for your markets...',
    'Analyzing AliExpress pricing & shipping...',
    'Scoring virality potential per zone...',
    'Ranking by profit opportunity...',
    'Almost done — finalizing results...'
  ];
  let si = 0;
  setStatus(statuses[si]);
  const statusInterval = setInterval(() => {
    si = Math.min(si+1, statuses.length-1);
    document.getElementById('statusText').textContent = statuses[si];
  }, 2500);

  try {
    const res = await fetch('https://api.anthropic.com/v1/messages', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        model: 'claude-sonnet-4-20250514',
        max_tokens: 4000,
        messages: [{ role: 'user', content: prompt }]
      })
    });

    clearInterval(statusInterval);

    if (!res.ok) {
      const err = await res.json().catch(() => ({}));
      throw new Error(err.error?.message || `API error ${res.status}`);
    }

    const data = await res.json();
    const raw = data.content?.find(c => c.type === 'text')?.text || '';

    let products;
    try {
      const clean = raw.replace(/```json|```/g,'').trim();
      const match = clean.match(/\[[\s\S]*\]/);
      if (!match) throw new Error('No JSON array found in response');
      products = JSON.parse(match[0]);
    } catch(e) {
      throw new Error('Could not parse product data. Please try again.');
    }

    if (!Array.isArray(products) || products.length === 0) {
      throw new Error('No products returned. Please try again.');
    }

    hideStatus();
    document.getElementById('resultsWrap').style.display = 'block';
    document.getElementById('resultsTitle').textContent = `${products.length} trending products found`;
    document.getElementById('resultsMeta').textContent = `${zones.join(' · ')}`;
    renderProducts(products);

  } catch(e) {
    clearInterval(statusInterval);
    hideStatus();
    showError('Error: ' + e.message);
    document.getElementById('emptyState').style.display = 'block';
  } finally {
    btn.disabled = false;
    btn.className = 'run-btn';
  }
}
</script>
</body>
</html>
