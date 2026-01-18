 
<style>
  .hero-container {
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1583391262137-9759329977f6?q=80&w=2000'); /* 暫代阿里山意象圖 */
    background-size: cover;
    background-position: center;
    padding: 60px 20px;
    text-align: center;
    color: white;
    border-radius: 12px;
    margin-bottom: 30px;
  }
  .countdown-box {
    background: rgba(255, 255, 255, 0.2);
    display: inline-block;
    padding: 10px 20px;
    border-radius: 50px;
    font-weight: bold;
    margin-top: 15px;
    border: 1px solid rgba(255,255,255,0.4);
  }
  .notice-banner {
    background-color: #fff5f5;
    border-left: 5px solid #ff4d4f;
    padding: 15px;
    margin: 20px 0;
    border-radius: 4px;
  }
  .participant-card {
    background: #f9f9f9;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #eee;
    font-style: italic;
    color: #555;
  }
</style>

<div class="hero-container">
  <h1 style="color: white; border: none; margin: 0;">少年展力 2026 阿里山之旅</h1>
  <p style="font-size: 1.2rem; opacity: 0.9;">千里之行，始於足下</p>
  <div class="countdown-box" id="timer">計算倒數中...</div>
</div>

- **活動日期：** 1/26(一) 集合過夜，1/27(二) ~ 1/29(四)
- **參加人員 (21人)：**
<div class="participant-card">
沈亞妮、賴貫綸、侯秉良、劉昀蒨、趙翊晴、莊荏次、趙釩淇、郭炫志、邱秩豪、劉恩菁、林承憙、邱郁涵、胡評迪、胡屹伶、蘇佑恩、蘇詒嗯、楊貴婷、陳采葳、王勳儀、王琦鈞、陳怡萱
</div>
- **工作人員 (7人)：**
*講師、李典佑、黃家瑄、楊宗憲、沈宗辰、梁芳青、張采維*

---

<div class="notice-banner">
  <strong style="color: #cf1322;">🚨 封閉步道公告！115/1/19 至 116/5/31 封閉巨木群棧道(1)</strong><br>
  為提升遊憩品質與步行安全，將進行木棧道更新工程。前往神木車站、香林神木，請改由<strong>慈雲寺下方步道</strong>及<strong>巨木群棧道(2)</strong>通行。
</div>

<script>
  function updateTimer() {
    const target = new Date("2026-01-26T09:00:00").getTime();
    const now = new Date().getTime();
    const diff = target - now;
    
    if (diff <= 0) {
      document.getElementById("timer").innerHTML = "🚀 活動進行中！";
      return;
    }
    
    const days = Math.floor(diff / (1000 * 60 * 60 * 24));
    const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    document.getElementById("timer").innerHTML = `⏳ 距離出發還有 ${days} 天 ${hours} 小時`;
  }
  setInterval(updateTimer, 1000);
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

