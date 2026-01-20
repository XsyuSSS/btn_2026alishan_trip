<div class="display-box scroll-reveal" id="status-display">⏳ 正在載入阿里山資訊...</div>

<div class="info-card scroll-reveal">
  <span class="info-title">⛩️ 阿里山御神籤</span>
  <p style="font-size: 0.85rem; color: #666; text-align: center; margin-bottom: 20px;">
    誠心祈求今日行程平安，點擊下方抽取籤詩。
  </p>
  
  <div style="text-align: center;">
    <button class="omikuji-btn" onclick="drawOmikuji()">抽一張御神籤</button>
  </div>

  <div id="omikuji-result" class="omikuji-card">
    <div class="omikuji-header">
      <div id="o-number" class="omikuji-number"></div>
      <div id="o-rank" class="omikuji-rank"></div>
    </div>
    <div id="o-poem" class="omikuji-poem"></div>
    <div class="omikuji-details">
      <div class="detail-item"><strong>運勢</strong> <span id="o-fortune"></span></div>
      <div class="detail-item"><strong>旅行</strong> <span id="o-travel"></span></div>
      <div class="detail-item"><strong>戀愛</strong> <span id="o-love"></span></div>
      <div class="detail-item"><strong>願望</strong> <span id="o-wish"></span></div>
      <div class="detail-item"><strong>失物</strong> <span id="o-lost"></span></div>
      <div class="detail-item"><strong>待人</strong> <span id="o-people"></span></div>
      <div class="detail-item"><strong>工作</strong> <span id="o-job"></span></div>
    </div>
    <div id="o-bless" class="omikuji-blessing"></div>
  </div>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">📅 活動日期</span>
  1/26(一) 集合過夜，1/27(二) ~ 1/29(四)
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">👥 參加人員 (21人)</span>
  <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 10px;">
    <span class="name-tag">沈亞妮</span><span class="name-tag">賴貫綸</span><span class="name-tag">侯秉良</span><span class="name-tag">劉昀蒨</span><span class="name-tag">趙翊晴</span><span class="name-tag">莊荏次</span><span class="name-tag">趙釩淇</span><span class="name-tag">郭炫志</span><span class="name-tag">邱秩豪</span><span class="name-tag">劉恩菁</span><span class="name-tag">林承憙</span><span class="name-tag">邱郁涵</span><span class="name-tag">胡評迪</span><span class="name-tag">胡屹伶</span><span class="name-tag">蘇佑恩</span><span class="name-tag">蘇詒嗯</span><span class="name-tag">楊貴婷</span><span class="name-tag">陳采葳</span><span class="name-tag">王勳儀</span><span class="name-tag">王琦鈞</span><span class="name-tag">陳怡萱</span>
  </div>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">🛠️ 工作人員 (7人)</span>
  <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 10px;">
    <span class="name-tag">講師</span><span class="name-tag">李典佑</span><span class="name-tag">黃家瑄</span><span class="name-tag">楊宗憲</span><span class="name-tag">沈宗辰</span><span class="name-tag">梁芳青</span><span class="name-tag">張采維</span>
  </div>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">📋 參考資源</span>
  <a style="margin-right:15px; color:#0066cc;" href="https://1drv.ms/w/c/68f596cc1c2c044a/IQBBccRisxCQTodab9f3zykgAXJ-yrFY2iUa-Xd5DNcacAA?e=7fNc0f" target="_blank">📄 阿里山之旅 (Word)</a>
  <a style="color:#0066cc;" href="https://apps.apple.com/tw/app/%E6%A3%AE%E9%81%8A%E9%98%BF%E9%87%8C%E5%B1%B1alipedia/id1491273055" target="_blank">📱 森遊阿里山 (App)</a>
</div>

<div class="notice-banner scroll-reveal">
  <strong class="text-red">🚨 封閉步道公告！115/1/19 至 116/5/31 封閉巨木群棧道(1)</strong>
  <div style="margin-top: 10px; color: #444; line-height: 1.6;">
    為提升遊憩品質與步行安全，前往神木車站請改由<strong>慈雲寺下方步道</strong>及<strong>巨木群棧道(2)</strong>通行。
  </div>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">⛰️ 阿里山即時氣象監測</span>
  <div class="weather-btn-container">
    <a href="https://www.cwa.gov.tw/V8/C/W/Town/Town.html?TID=1001018" target="_blank" class="weather-link btn-cwa">📊 氣象署逐時預報</a>
    <a href="https://www.windy.com/23.510/120.805?radar,23.350,120.805,10" target="_blank" class="weather-link btn-windy">🌀 Windy 雲圖監測</a>
  </div>
</div>

{% include nav.html %}

---

### 🍴 餐廳資訊與菜單

<div class="restaurant-grid">

  <div class="info-card scroll-reveal">
    <div class="res-info-container">
      <span style="font-size: 2rem;">🏠</span>
      <h4 style="margin: 10px 0 5px;">文山賓館</h4>
      <div style="margin-bottom: 10px;">
        <span class="name-tag" style="background:#e3f2fd; color:#1976d2; border:none;">住宿提供</span>
        <span class="name-tag" style="background:#f3e5f5; color:#7b1fa2; border:none;">合菜晚餐</span>
      </div>
      <p style="font-size: 0.85rem; color: #666;">團體預約制，提供在地山產合菜。</p>
      <a class="map-btn" href="https://maps.app.goo.gl/E5tVA1S5XXwA2FJf9" target="_blank">📍 開啟地圖導航</a>
    </div>
  </div>

  <div class="info-card scroll-reveal">
    <div class="res-info-container">
      <span style="font-size: 2rem;">🍱</span>
      <h4 style="margin: 10px 0 5px;">山芝鄉風味館</h4>
      <div style="margin-bottom: 10px;">
        <span class="name-tag" style="background:#fff3e0; color:#e65100; border:none;">風味熱炒</span>
      </div>
      <a class="map-btn" href="https://maps.app.goo.gl/7e9d66BGSsHWXwar6" target="_blank">📍 開啟地圖導航</a>
    </div>
    <details class="menu-card-enhanced" style="margin-top: 15px;">
      <summary class="menu-header-enhanced">查看菜單內容</summary>
      <div class="menu-content" style="text-align:center;">
        <img src="{{ '山芝鄉01.png' | relative_url }}" style="max-width:100%; border-radius: 8px;">
        <img src="{{ '山芝鄉02.png' | relative_url }}" style="max-width:100%; border-radius: 8px; margin-top: 10px;">
      </div>
    </details>
  </div>

  <div class="info-card scroll-reveal">
    <div class="res-info-container">
      <span style="font-size: 2rem;">🥘</span>
      <h4 style="margin: 10px 0 5px;">欣欣餐廳</h4>
      <div style="margin-bottom: 10px;">
        <span class="name-tag" style="background:#e8f5e9; color:#2e7d32; border:none;">團體餐飲</span>
      </div>
      <a class="map-btn" href="https://maps.app.goo.gl/YkTcaQMVUffh5ye76" target="_blank">📍 開啟地圖導航</a>
    </div>
    <details class="menu-card-enhanced" style="margin-top: 15px;">
      <summary class="menu-header-enhanced">查看菜單內容</summary>
      <div class="menu-content" style="text-align:center;">
        <img src="{{ '欣欣.png' | relative_url }}" style="max-width:100%; border-radius: 8px;">
      </div>
    </details>
  </div>

  <div class="info-card scroll-reveal">
    <div class="res-info-container">
      <span style="font-size: 2rem;">🍜</span>
      <h4 style="margin: 10px 0 5px;">香姨小吃</h4>
      <div style="margin-bottom: 10px;">
        <span class="name-tag" style="background:#ffebee; color:#c62828; border:none;">特色小吃</span>
      </div>
      <a class="map-btn" href="https://maps.app.goo.gl/BfetNBdEaW512GR16" target="_blank">📍 開啟地圖導航</a>
    </div>
    <details class="menu-card-enhanced" style="margin-top: 15px;">
      <summary class="menu-header-enhanced">查看菜單內容</summary>
      <div class="menu-content" style="text-align:center;">
        <img src="{{ '香姨小吃.png' | relative_url }}" style="max-width:100%; border-radius: 8px;">
      </div>
    </details>
  </div>

</div>

<script src="https://unpkg.com/scrollreveal"></script>
<script>
  // A. 初始化 ScrollReveal
  ScrollReveal().reveal('.scroll-reveal', {
    delay: 200,
    distance: '20px',
    origin: 'bottom',
    easing: 'ease-in-out',
    interval: 100
  });

  // B. 御神籤數據庫 (50支籤)
  const omikujiData = [
    { id: 1, rank: "大吉", poem: "雲開見青嶺\n松影落清泉\n心定風自息\n一步到晴天", f: "大吉，萬事順遂，先穩後旺。", t: "宜登高望遠，路途平安。", l: "緣分清朗，真心即成。", w: "可成，耐心等佳音。", m: "在明處，不久可得。", p: "以誠相待，得貴人助。", j: "好機會臨門，適合主動爭取。", b: "願你所行皆坦途，所遇皆良人。" },
    // ... (此處省略中間第 2-49 支籤內容，請保留您原本的 50 支完整數據)
    { id: 50, rank: "大吉", poem: "雲開千嶺秀\n日照萬川明\n一心行善處\n福至自成榮", f: "大吉，福氣成形，做什麼都能順。", t: "大吉，遇見好景也遇見好人。", l: "真心相守，關係穩固開花。", w: "大成，且能超出預期。", m: "必得回，或得到更好的替代。", p: "人緣大旺，貴人相助。", j: "升遷、成果、名聲皆有收穫。", b: "願你福至成榮，歲歲安穩。" }
  ];

  function drawOmikuji() {
    const random = omikujiData[Math.floor(Math.random() * omikujiData.length)];
    const card = document.getElementById('omikuji-result');
    
    document.getElementById('o-number').innerText = `第 ${random.id} 番`;
    document.getElementById('o-rank').innerText = random.rank;
    document.getElementById('o-poem').innerText = random.poem;
    document.getElementById('o-fortune').innerText = random.f;
    document.getElementById('o-travel').innerText = random.t;
    document.getElementById('o-love').innerText = random.l;
    document.getElementById('o-wish').innerText = random.w;
    document.getElementById('o-lost').innerText = random.m;
    document.getElementById('o-people').innerText = random.p;
    document.getElementById('o-job').innerText = random.j;
    document.getElementById('o-bless').innerText = random.b;

    card.style.display = 'block';
    card.style.animation = 'none';
    card.offsetHeight; 
    card.style.animation = 'floating 3s ease-in-out infinite';
  }

  // C. 倒數與名言邏輯
  function updateDisplay() {
    const now = new Date();
    const targetDate = new Date("2026-01-26T09:00:00").getTime();
    const diff = targetDate - now.getTime();
    const display = document.getElementById("status-display");
    
    if (!display) return;

    const todayStr = now.getFullYear() + "-" + String(now.getMonth() + 1).padStart(2, '0') + "-" + String(now.getDate()).padStart(2, '0');
    const quotes = {
      "2026-01-27": { en: "“Coming together is a beginning. Keeping together is progress. Working together is success.”", zh: "「聚在一起是開始，守在一起是進步，一同工作是成功。」" },
      "2026-01-28": { en: "“It is not the mountain we conquer, but ourselves.”", zh: "「我們征服的不是高山，而是我們自己。」" },
      "2026-01-29": { en: "“The future belongs to those who believe in the beauty of their dreams.”", zh: "「未來屬於那些相信夢想之美的人。」" }
    };

    display.classList.remove('is-near', 'is-ongoing');

    if (quotes[todayStr]) {
      display.classList.add('is-ongoing');
      display.innerHTML = `<span class="quote-en">${quotes[todayStr].en}</span><br><span class="quote-zh">${quotes[todayStr].zh}</span>`;
    } else if (diff > 0) {
      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const mins = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
      if (days < 7) { display.classList.add('is-near'); }
      display.innerHTML = `⏳ 距離出發還有 ${days} 天 ${hours} 小時 ${mins} 分`;
    } else {
      display.innerHTML = `🌲 2026 阿里山之旅 · 圓滿達成`;
    }
  }

  window.onload = function() {
    updateDisplay();
    setInterval(updateDisplay, 60000);
  };
</script>
