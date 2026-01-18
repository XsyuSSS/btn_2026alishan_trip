<div class="display-box scroll-reveal" id="status-display">⏳ 正在載入阿里山資訊...</div>

<script src="https://unpkg.com/scrollreveal"></script>
<script>
  // 1. 初始化動畫
  ScrollReveal().reveal('.scroll-reveal', {
    delay: 200,
    distance: '20px',
    origin: 'bottom',
    easing: 'ease-in-out',
    interval: 100
  });

  // 2. 修正後的更新邏輯
  function updateDisplay() {
    const now = new Date();
    const targetDate = new Date("2026-01-26T09:00:00").getTime();
    const diff = targetDate - now.getTime();
    const display = document.getElementById("status-display");
    
    if (!display) return; // 安全機制：避免找不到元素報錯

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

  // 確保頁面載入後立刻執行一次，並設定定時更新
  window.onload = function() {
    updateDisplay();
    setInterval(updateDisplay, 60000);
  };
</script>

<div class="info-card scroll-reveal">
  <span class="info-title">📅 活動日期</span>
  1/26(一) 集合過夜，1/27(二) ~ 1/29(四)
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">👥 參加人員 (21人)</span>
  <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 10px;">
    <span class="name-tag">沈亞妮</span><span class="name-tag">賴貫綸</span>
    <span class="name-tag">侯秉良</span><span class="name-tag">劉昀蒨</span>
    <span class="name-tag">趙翊晴</span><span class="name-tag">莊荏次</span>
    <span class="name-tag">趙釩淇</span><span class="name-tag">郭炫志</span>
    <span class="name-tag">邱秩豪</span><span class="name-tag">劉恩菁</span>
    <span class="name-tag">林承憙</span><span class="name-tag">邱郁涵</span>
    <span class="name-tag">胡評迪</span><span class="name-tag">胡屹伶</span>
    <span class="name-tag">蘇佑恩</span><span class="name-tag">蘇詒嗯</span>
    <span class="name-tag">楊貴婷</span><span class="name-tag">陳采葳</span>
    <span class="name-tag">王勳儀</span><span class="name-tag">王琦鈞</span>
    <span class="name-tag">陳怡萱</span>
  </div>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">🛠️ 工作人員 (7人)</span>
    <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 10px;">
    <span class="name-tag">講師</span><span class="name-tag">李典佑</span>
    <span class="name-tag">黃家瑄</span><span class="name-tag">楊宗憲</span>
    <span class="name-tag">沈宗辰</span><span class="name-tag">梁芳青</span>
    <span class="name-tag">張采維
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
    為提升遊憩品質與步行安全，將進行木棧道更新工程。前往神木車站、香林神木，請改由<strong>慈雲寺下方步道</strong>及<strong>巨木群棧道(2)</strong>通行。
  </div>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">⛰️ 阿里山即時氣象監測</span>
  <div class="weather-btn-container">
    <a href="https://www.cwa.gov.tw/V8/C/W/Town/Town.html?TID=1001012" target="_blank" class="weather-link btn-cwa">📊 氣象署逐時預報</a>
    <a href="https://www.windy.com/23.510/120.805?radar,23.350,120.805,10" target="_blank" class="weather-link btn-windy">🌀 Windy 雲圖監測</a>
  </div>
</div>

{% include nav.html %}

---

### 🍴 餐廳資訊與菜單

- [⛰️ 文山賓館](https://maps.app.goo.gl/E5tVA1S5XXwA2FJf9)
- [🍱 山芝鄉風味館](https://maps.app.goo.gl/7e9d66BGSsHWXwar6)
<details class="menu-card scroll-reveal">
  <summary class="menu-header">山芝鄉菜單</summary>
  <div class="menu-content">
    <img src="{{ '山芝鄉01.png' | relative_url }}" style="max-width:100%;">
    <img src="{{ '山芝鄉02.png' | relative_url }}" style="max-width:100%;">
  </div>
</details>

- [🍱 欣欣餐廳](https://maps.app.goo.gl/YkTcaQMVUffh5ye76)
<details class="menu-card scroll-reveal">
  <summary class="menu-header">欣欣菜單</summary>
  <div class="menu-content">
    <img src="{{ '欣欣.png' | relative_url }}" style="max-width:100%;">
  </div>
</details>

- [🍜 娜若瑪菲 小商圈 (香姨小吃)](https://maps.app.goo.gl/BfetNBdEaW512GR16)
<details class="menu-card scroll-reveal">
  <summary class="menu-header">香姨小吃菜單</summary>
  <div class="menu-content">
    <img src="{{ '香姨小吃.png' | relative_url }}" style="max-width:100%;">
  </div>
</details>

<script src="https://unpkg.com/scrollreveal"></script>
<script>
  // A. 初始化動畫
  ScrollReveal().reveal('.scroll-reveal', {
    delay: 200,
    distance: '20px',
    origin: 'bottom',
    easing: 'ease-in-out',
    interval: 100
  });

  // B. 倒數與狀態更新
  function updateDisplay() {
    const now = new Date();
    const targetDate = new Date("2026-01-26T09:00:00").getTime();
    const diff = targetDate - now.getTime();
    const display = document.getElementById("status-display");
    const todayStr = now.getFullYear() + "-" + String(now.getMonth() + 1).padStart(2, '0') + "-" + String(now.getDate()).padStart(2, '0');

    const quotes = {
      "2026-01-27": { en: "“Coming together is a beginning. Keeping together is progress. Working together is success.”", zh: "「聚在一起是開始，守在一起是進步，一同工作是成功。」" },
      "2026-01-28": { en: "“It is not the mountain we conquer, but ourselves.”", zh: "「我們征服的不是高山，而是我們自己。」" },
      "2026-01-29": { en: "“The future belongs to those who believe in the beauty of their dreams.”", zh: "「未來屬於那些相信夢想之美的人。」" }
    };

    display.classList.remove('is-near', 'is-ongoing');

    if (quotes[todayStr]) {
      display.classList.add('is-ongoing');
      display.innerHTML = `<span class="quote-en">${quotes[todayStr].en}</span><span class="quote-zh">${quotes[todayStr].zh}</span>`;
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
  setInterval(updateDisplay, 60000);
  updateDisplay();
