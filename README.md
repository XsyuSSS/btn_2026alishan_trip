<style>
  /* 頂部倒數背景區 */
  .hero-container {
    background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1583391262137-9759329977f6?q=80&w=2000');
    background-size: cover;
    background-position: center;
    padding: 50px 20px;
    text-align: center;
    border-radius: 12px;
    margin-bottom: 25px;
  }
  
  /* 倒數計時框 */
  .countdown-box {
    background: rgba(255, 255, 255, 0.95);
    color: #333;
    display: inline-block;
    padding: 12px 30px;
    border-radius: 50px;
    font-weight: bold;
    font-size: 1.3rem;
    box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    border: 1px solid #ddd;
  }

  /* 統一的資訊框樣式 */
  .info-card {
    background: #fdfdfd;
    padding: 18px 22px;
    border-radius: 10px;
    border: 1px solid #eee;
    margin-bottom: 15px;
    line-height: 1.6;
    box-shadow: 0 2px 8px rgba(0,0,0,0.03);
  }

  /* 資訊框的小標題 */
  .info-title {
    font-weight: bold;
    color: #2c3e50;
    display: block;
    border-bottom: 2px solid #eef2f7;
    padding-bottom: 8px;
    margin-bottom: 12px;
    font-size: 1.05rem;
  }

  /* 內容文字樣式 */
  .info-content {
    color: #555;
    font-size: 1rem;
  }

  .text-italic {
    font-style: italic;
    color: #666;
  }

  /* 封閉公告紅框 */
  .notice-banner {
    background-color: #fff5f5;
    border-left: 5px solid #ff4d4f;
    padding: 18px;
    margin: 25px 0;
    border-radius: 6px;
    color: #444;
  }
</style>

<div class="hero-container">
  <div class="countdown-box" id="timer">⏳ 正在載入倒數計時...</div>
</div>

<div class="info-card">
  <span class="info-title">📅 活動日期</span>
  <div class="info-content">1/26(一) 集合過夜，1/27(二) ~ 1/29(四)</div>
</div>

<div class="info-card">
  <span class="info-title">👥 參加人員 (21人)</span>
  <div class="info-content text-italic">
    沈亞妮、賴貫綸、侯秉良、劉昀蒨、趙翊晴、莊荏次、趙釩淇、郭炫志、邱秩豪、劉恩菁、林承憙、邱郁涵、胡評迪、胡屹伶、蘇佑恩、蘇詒嗯、楊貴婷、陳采葳、王勳儀、王琦鈞、陳怡萱
  </div>
</div>

<div class="info-card">
  <span class="info-title">🛠️ 工作人員 (7人)</span>
  <div class="info-content text-italic">
    講師、李典佑、黃家瑄、楊宗憲、沈宗辰、梁芳青、張采維
  </div>
</div>

<div class="notice-banner">
  <strong style="color: #cf1322; font-size: 1.1rem;">🚨 封閉步道公告！115/1/19 至 116/5/31 封閉巨木群棧道(1)</strong><br>
  <div style="margin-top: 8px;">
    為提升遊憩品質與步行安全，將進行木棧道更新工程。前往神木車站、香林神木，請改由<strong>慈雲寺下方步道</strong>及<strong>巨木群棧道(2)</strong>通行，並請提前規劃行程。
  </div>
</div>

<script>
  function updateTimer() {
    // 設定出發時間
    const target = new Date("2026-01-26T09:00:00").getTime();
    const now = new Date().getTime();
    const diff = target - now;
    
    const timerElement = document.getElementById("timer");
    
    if (diff <= 0) {
      timerElement.innerHTML = "🚀 活動正式開始！";
      return;
    }
    
    const days = Math.floor(diff / (1000 * 60 * 60 * 24));
    const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const mins = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
    
    timerElement.innerHTML = `⏳ 距離出發還有 ${days} 天 ${hours} 小時 ${mins} 分`;
  }

  // 每分鐘更新一次時間即可，節省效能
  setInterval(updateTimer, 60000);
  updateTimer();
</script>

{% include nav.html %}

- <a href="https://maps.app.goo.gl/E5tVA1S5XXwA2FJf9" target="_blank" rel="noopener noreferrer">文山賓館</a>
- <a href="https://maps.app.goo.gl/7e9d66BGSsHWXwar6" target="_blank" rel="noopener noreferrer">山芝鄉風味館</a>
<details>
  <summary>▲山芝鄉菜單</summary>
  <p style="text-align:center; margin-top:10px;">
    <img src="{{ '山芝鄉01.png' | relative_url }}" style="max-width:100%;">
    <img src="{{ '山芝鄉02.png' | relative_url }}" style="max-width:100%;">
  </p>
</details>
- <a href="https://maps.app.goo.gl/YkTcaQMVUffh5ye76" target="_blank" rel="noopener noreferrer">欣欣餐廳</a>
<details>
  <summary>▲欣欣菜單</summary>
  <p style="text-align:center; margin-top:10px;">
    <img src="{{ '欣欣.png' | relative_url }}" style="max-width:100%;">
  </p>
</details>
- <a href="https://maps.app.goo.gl/xWCNVNBRQLPEozMJ8" target="_blank" rel="noopener noreferrer">7-11神木</a>
- <a href="https://maps.app.goo.gl/qDD2GdU1qWYCnTV58" target="_blank" rel="noopener noreferrer">娜若瑪菲 小商圈(推薦：香姨小吃（21麵食）)</a>
<details>
  <summary>▲香姨小吃菜單</summary>
  <p style="text-align:center; margin-top:10px;">
    <img src="{{ '香姨小吃.png' | relative_url }}" style="max-width:100%;">
  </p>
</details>

