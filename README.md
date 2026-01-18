<div class="display-box scroll-reveal" id="status-display">⏳ 正在載入阿里山資訊...</div>

<div class="info-card scroll-reveal">
  <span class="info-title">📅 活動日期</span>
  1/26(一) 集合過夜，1/27(二) ~ 1/29(四)
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">👥 參加人員 (21人)</span>
  <span style="font-style: italic; color: #666; font-size: 0.9rem;">沈亞妮、賴貫綸、侯秉良、劉昀蒨、趙翊晴、莊荏次、趙釩淇、郭炫志、邱秩豪、劉恩菁、林承憙、邱郁涵、胡評迪、胡屹伶、蘇佑恩、蘇詒嗯、楊貴婷、陳采葳、王勳儀、王琦鈞、陳怡萱</span>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">🛠️ 工作人員 (7人)</span>
  <span style="font-style: italic; color: #666; font-size: 0.9rem;">講師、李典佑、黃家瑄、楊宗憲、沈宗辰、梁芳青、張采維</span>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">📋 參考資源</span>
  <a style="margin-right:15px; color:#0066cc;" href="https://1drv.ms/w/c/68f596cc1c2c044a/IQBBccRisxCQTodab9f3zykgAXJ-yrFY2iUa-Xd5DNcacAA?e=7fNc0f" target="_blank">📄 阿里山之旅 (Word)</a>
  <a style="color:#0066cc;" href="https://apps.apple.com/tw/app/%E6%A3%AE%E9%81%8A%E9%98%BF%E9%87%8C%E5%B1%B1alipedia/id1491273055" target="_blank">📱 森遊阿里山 (App)</a>
</div>

<div class="notice-banner scroll-reveal">
  <strong class="text-red">🚨 封閉步道公告！115/1/19 至 116/5/31 封閉巨木群棧道(1)</strong><br>
  <div style="margin-top: 10px; color: #444; line-height: 1.6;">
    為提升遊憩品質與步行安全，將進行木棧道更新工程。前往神木車站、香林神木，請改由<strong>慈雲寺下方步道</strong>及<strong>巨木群棧道(2)</strong>通行，並請提前規劃行程。
  </div>
</div>

<div class="info-card scroll-reveal">
  <span class="info-title">⛰️ 阿里山即時氣象監測</span>
  
  <div style="width: 100%; height: 350px; border-radius: 12px; overflow: hidden; border: 1px solid #eee; margin-bottom: 15px;">
    <iframe 
      src="https://www.windy.com/23.528/120.801?22.948,120.801,8" 
      width="100%" 
      height="100%" 
      frameborder="0">
    </iframe>
  </div>

  <div style="text-align: center;">
    <a href="https://www.cwa.gov.tw/V8/C/W/Town/Town.html?TID=1001012" target="_blank" 
       style="display: inline-block; background: #3498db; color: white; padding: 10px 25px; border-radius: 50px; text-decoration: none; font-weight: bold; box-shadow: 0 4px 10px rgba(52, 152, 219, 0.3);">
       📊 查看氣象署逐時預報 (詳細氣溫/降雨)
    </a>
    <p style="font-size: 0.85rem; color: #888; margin-top: 10px;">
      💡 地圖可縮放查看雲雨動態；點擊按鈕查看官方精確預報。
    </p>
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
  // 初始化 ScrollReveal (確保 Class 名稱對應到上面的標籤)
  ScrollReveal().reveal('.scroll-reveal', {
    delay: 200,
    distance: '20px',
    origin: 'bottom',
    easing: 'ease-in-out',
    interval: 100
  });

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

    if (quotes[todayStr]) {
      display.innerHTML = `<span class="quote-en">${quotes[todayStr].en}</span><span class="quote-zh">${quotes[todayStr].zh}</span>`;
    } else if (diff > 0) {
      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const mins = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
      display.innerHTML = `⏳ 距離出發還有 ${days} 天 ${hours} 小時 ${mins} 分`;
    } else {
      display.innerHTML = `🌲 2026 阿里山之旅 · 圓滿達成`;
    }
  }
  setInterval(updateDisplay, 60000);
  updateDisplay();
</script>
