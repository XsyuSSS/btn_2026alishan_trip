<div class="display-box scroll-reveal" id="status-display">⏳ 正在載入阿里山資訊...</div>

<div class="info-card scroll-reveal">
  <span class="info-title">⛩️ 阿里山御神籤</span>
  <p style="text-align: center; font-size: 0.85rem; color: #666; margin-bottom: 20px;">
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
      <a class="map-btn" href="https://maps.app.goo.gl/E5tVA1S5XXwA2FJf9" target="_blank">📍 開啟導航</a>
    </div>
  </div>

  <div class="info-card scroll-reveal">
    <div class="res-info-container">
      <span style="font-size: 2rem;">🍱</span>
      <h4 style="margin: 10px 0 5px;">山芝鄉風味館</h4>
      <div style="margin-bottom: 10px;">
        <span class="name-tag" style="background:#fff3e0; color:#e65100; border:none;">風味熱炒</span>
      </div>
      <a class="map-btn" href="https://maps.app.goo.gl/7e9d66BGSsHWXwar6" target="_blank">📍 開啟導航</a>
    </div>
    <details class="menu-card-enhanced" style="margin-top: 15px;">
      <summary class="menu-header-enhanced">查看菜單</summary>
      <div style="text-align:center; padding: 10px;">
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
      <a class="map-btn" href="https://maps.app.goo.gl/YkTcaQMVUffh5ye76" target="_blank">📍 開啟導航</a>
    </div>
    <details class="menu-card-enhanced" style="margin-top: 15px;">
      <summary class="menu-header-enhanced">查看菜單</summary>
      <div style="text-align:center; padding: 10px;">
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
      <a class="map-btn" href="https://maps.app.goo.gl/BfetNBdEaW512GR16" target="_blank">📍 開啟導航</a>
    </div>
    <details class="menu-card-enhanced" style="margin-top: 15px;">
      <summary class="menu-header-enhanced">查看菜單</summary>
      <div style="text-align:center; padding: 10px;">
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

  // B. 御神籤數據 (完整 50 支)
  const omikujiData = [
    { id: 1, rank: "大吉", poem: "雲開見青嶺\n松影落清泉\n心定風自息\n一步到晴天", f: "大吉，萬事順遂，先穩後旺。", t: "宜登高望遠，路途平安。", l: "緣分清朗，真心即成。", w: "可成，耐心等佳音。", m: "在明處，不久可得。", p: "以誠相待，得貴人助。", j: "好機會臨門，適合主動爭取。", b: "願你所行皆坦途，所遇皆良人。" },
    { id: 2, rank: "吉", poem: "溪聲隨月遠\n竹影入窗長\n慢步逢佳處\n回頭是故鄉", f: "吉，穩中有進，勿急躁。", t: "適合短程，越簡越順。", l: "先熟後甜，別催結果。", w: "可成，先做準備。", m: "可能在袋中或車內。", p: "少說多聽，易得信任。", j: "循序漸進，能被看見。", b: "願你步步踏實，日日安穩。" },
    { id: 3, rank: "中吉", poem: "山雨初停後\n石階帶苔香\n不求風太急\n自有日光長", f: "中吉，先小阻後轉順。", t: "避免趕行程，留白更好。", l: "有進展，但需耐心。", w: "可成，時間是關鍵。", m: "在角落處，需細找。", p: "放柔語氣，化解誤會。", j: "適合修正計畫、補強細節。", b: "願你雨後見虹，心中常晴。" },
    { id: 4, rank: "吉", poem: "風過林不語\n鳥鳴自有期\n心中藏好意\n終會被人知", f: "吉，低調反而更順。", t: "順行，宜早出發。", l: "別試探太多，真誠最強。", w: "可成，靠自己多一些。", m: "會回來，或有人代尋。", p: "善意不必張揚，仍能被感受。", j: "穩住節奏，成果會累積。", b: "願你的善良被溫溫柔接住。" },
    { id: 5, rank: "小吉", poem: "雲薄遮山色\n路彎見野花\n莫怨行程慢\n慢處更堪誇", f: "小吉，小福常在，勿貪快。", t: "有小延誤，但無大礙。", l: "慢慢靠近，比急著告白更好。", w: "可成，需多努力一點。", m: "找回機率高，先回想最後使用處。", p: "少計較，反得好回應。", j: "先把基本功做好，後面會順。", b: "願你在緩慢裡，也能遇見驚喜。" },
    { id: 6, rank: "末吉", poem: "山路多回轉\n溪橋有微搖\n不怕行得慢\n只怕心先飄", f: "末吉，起伏正常，守住心就穩。", t: "宜保守，注意交通與時間。", l: "別因不安亂猜，先穩自己。", w: "可成，但需等待時機成熟。", m: "暫時不易尋，先放下再找。", p: "不要逞強，求助反而順。", j: "先求穩定，別硬拚高風險。", b: "願你心不亂，路自平安。" },
    { id: 7, rank: "中吉", poem: "月照千峰靜\n泉鳴萬里清\n不爭先與後\n自得一身輕", f: "中吉，放下比較，運勢更開。", t: "適合獨行或少人同行。", l: "平淡中藏甜，細水長流。", w: "可成，別急著證明。", m: "在床邊、桌下、或車座附近。", p: "你越溫和，越有人靠近。", j: "不必搶功，默默做反而升。", b: "願你不爭而得，不求而來。" },
    { id: 8, rank: "吉", poem: "松高知歲久\n石暖記人來\n今日添一願\n明朝花自開", f: "吉，累積的努力開始發芽。", t: "適合拜訪老地方，有收穫。", l: "舊緣可續，新緣可遇。", w: "可成，持續投入。", m: "可能被收起來了，問人可得。", p: "多問候一句，人情就回來。", j: "適合談合作、爭取資源。", b: "願你所願皆有回音，所等皆不落空。" },
    { id: 9, rank: "小吉", poem: "風輕花不落\n水緩石更圓\n只要心不急\n好事在眼前", f: "小吉，小確幸增加，耐心最旺。", t: "宜輕裝，越簡單越順。", l: "不要太用力，舒服最重要。", w: "可成，先完成一小步。", m: "在衣物堆或包包夾層。", p: "別把話說滿，留餘地更好。", j: "按部就班，適合整理與收尾。", b: "願你輕輕走，也走到好地方。" },
    { id: 10, rank: "大吉", poem: "朝日出雲海\n山門響清鐘\n一念成光路\n萬事向春風", f: "大吉，運勢大開，適合啟動新計畫。", t: "大吉之行，見景也見福。", l: "告白、確立關係皆宜。", w: "大成，趁勢而行。", m: "立刻找會找到，別拖。", p: "遇貴人，對方願意提攜。", j: "升遷、轉職、提案皆有利。", b: "願你從此春風作伴，喜事成雙。" },
    { id: 11, rank: "吉", poem: "霧散山腰白\n風來竹葉鳴\n不須求速到\n自會到分明", f: "吉，方向正確，越走越清楚。", t: "路況先迷後順，跟著規劃走。", l: "別急著定義關係，先培養默契。", w: "可成，先整理步驟再行動。", m: "可能在門口、玄關附近。", p: "以穩定回應，對方更信任你。", j: "適合做流程優化，成果立見。", b: "願你撥雲見路，步步踏實。" },
    { id: 12, rank: "中吉", poem: "石上新苔綠\n林間舊夢輕\n若能收雜念\n心自有回聲", f: "中吉，心越清，運越順。", t: "適合慢遊，少跑點更有收穫。", l: "舊情緒要放下，新互動才進來。", w: "可成，先去掉多餘擔心。", m: "在書桌、抽屜或紙堆中。", p: "你越平靜，越能安定他人。", j: "適合整理資料、重新排優先序。", b: "願你心中清明，萬事自有回音。" },
    { id: 13, rank: "小吉", poem: "鳥落松枝上\n花開石縫邊\n不嫌今日小\n終成明日圓", f: "小吉，小成果累積成大收穫。", t: "小插曲無妨，保持彈性即可。", l: "多一點關心，比甜言更有效。", w: "可成，先從最小的一步開始。", m: "在座位附近或衣服口袋。", p: "別硬撐，真誠說明反而更好。", j: "適合把未完成的事補齊。", b: "願你今日小喜，明日大成。" },
    { id: 14, rank: "吉", poem: "山泉穿石過\n不語也成河\n只要日日進\n終會見長波", f: "吉，持續努力會有明顯回報。", t: "宜水邊或自然景點，放鬆好運。", l: "慢慢建立信任，關係更穩。", w: "可成，靠持續累積。", m: "可能在車上或移動路線中。", p: "你保持一致，他人就安心。", j: "適合長期計畫，穩穩推進。", b: "願你日日向前，終見大河。" },
    { id: 15, rank: "末吉", poem: "風急樹先動\n雲低山更深\n若能守一步\n便可轉成春", f: "末吉，別被外界帶節奏，守住就好。", t: "不宜太趕，注意天氣與安全。", l: "情緒起伏時，先照顧自己再談。", w: "可成，但要避開衝動決定。", m: "暫難尋回，晚些再找更有機會。", p: "不必迎合所有人，守界線更順。", j: "先求穩，避免臨時大改。", b: "願你守得住一步，也守得住春天。" },
    { id: 16, rank: "大吉", poem: "日照千山亮\n風清萬里開\n心中無所懼\n好事自前來", f: "大吉，勇敢做決定，越做越旺。", t: "遠行亦吉，遇景遇福。", l: "主動更有利，真心會被接住。", w: "大成，趁勢出手。", m: "很快出現，或有人送回。", p: "貴人相助，適合請教與合作。", j: "適合提案、爭取升遷或新任務。", b: "願你無懼向前，萬事迎光。" },
    { id: 17, rank: "中吉", poem: "松風吹舊影\n月落照新階\n不怕前路遠\n只怕不肯來", f: "中吉，關鍵在「開始」。", t: "適合安排新路線，會有新收穫。", l: "別只等對方，溫柔主動更好。", w: "可成，行動比想像更重要。", m: "在常用路徑或固定位置附近。", p: "你先伸手，對方就靠近。", j: "適合啟動新企劃，先做再修。", b: "願你願意出發，就已走在好路上。" },
    { id: 18, rank: "吉", poem: "溪長知水意\n雲淡識天心\n若問前程事\n笑看花自深", f: "吉，順其自然反而更順。", t: "宜輕鬆走，別排太滿。", l: "放鬆互動，對方更願靠近。", w: "可成，別用力過頭。", m: "在沙發縫、床邊或角落。", p: "柔和說話，比說服更有效。", j: "適合協調與溝通，成果好。", b: "願你心寬路寬，花開自深。" },
    { id: 19, rank: "小吉", poem: "雨落添清氣\n路濕更須行\n莫怕鞋沾泥\n終會到天晴", f: "小吉，有小麻煩但能平安過關。", t: "注意雨具與交通，仍可成行。", l: "有誤會時，先說清楚就好。", w: "可成，別因小阻就退。", m: "在包包底層或外套裡。", p: "多一句關心，能化解冷場。", j: "遇卡關先拆小步驟，能突破。", b: "願你踏過泥濘，也踏到晴天。" },
    { id: 20, rank: "吉", poem: "山遠不遮目\n雲高不礙行\n心若常明亮\n處處是通明", f: "吉，思路清晰就能解題。", t: "適合看風景，心情更旺。", l: "坦率說感受，關係更靠近。", w: "可成，先把目標講清楚。", m: "在視線可及處，只是你沒注意。", p: "你越清楚界線，越被尊重。", j: "適合做簡報、提案、公開表達。", b: "願你心明如燈，所到皆亮。" },
    { id: 21, rank: "中吉", poem: "花香隨步近\n路轉見人多\n若能藏鋒芒\n自有好因果", f: "中吉，別太鋒利，柔一點更順。", t: "人多處注意保管物品。", l: "別太強勢，溫柔更得心。", w: "可成，但要避開衝突。", m: "可能被人代收，問一問。", p: "少評價多理解，人緣變好。", j: "適合團隊合作，別單打獨鬥。", b: "願你柔中帶光，處處得緣。" },
    { id: 22, rank: "末吉", poem: "山風翻舊葉\n溪水洗新痕\n若問何時好\n先把心放穩", f: "末吉，先安頓內心再談運勢。", t: "不宜臨時更動，照原計畫較好。", l: "先別急著要答案，先把自己照顧好。", w: "可成，慢慢來更穩。", m: "短期難回，先整理環境再找。", p: "你若焦躁，對方也會退。", j: "先把基本事做穩，別追求完美。", b: "願你先穩住心，福氣自然近。" },
    { id: 23, rank: "吉", poem: "雲過留青影\n風來帶木香\n今日添一笑\n明日少悲傷", f: "吉，好運藏在好心情裡。", t: "宜散步、踏青、親近自然。", l: "笑容是你的王牌，放鬆更迷人。", w: "可成，保持正向行動。", m: "在你常放的位置，只是被遮住。", p: "一句玩笑化解僵局。", j: "適合創意發想、做活動企劃。", b: "願你今日多笑，明日更輕。" },
    { id: 24, rank: "大吉", poem: "山開迎曙色\n泉湧照人心\n一步逢新景\n千門皆可尋", f: "大吉，開新局的最好時機。", t: "大吉，適合探索新地方。", l: "新緣旺，舊緣也能升溫。", w: "大成，越行動越快實現。", m: "會找回，且比想像更快。", p: "遇到願意幫你的人，別客氣。", j: "適合轉職、接新案、談合作。", b: "願你走進新景，也走進新福。" },
    { id: 25, rank: "小吉", poem: "石階雖不直\n仍可到雲邊\n只要不回頭\n終會見晴天", f: "小吉，繞路也是路。", t: "有小變動，但仍順利完成。", l: "別用同一招，換方式更有效。", w: "可成，調整方法就行。", m: "在轉角處或某個袋子裡。", p: "別硬碰硬，轉彎更好說話。", j: "遇阻先換策略，別硬扛。", b: "願你不怕繞路，仍到晴天。" },
    { id: 26, rank: "吉", poem: "月明照遠徑\n松靜護歸人\n心若常有光\n夜亦不覺深", f: "吉，越晚越好，後勢更強。", t: "夜行需小心，但能平安。", l: "細水長流型，越久越甜。", w: "可成，靠持續與信念。", m: "可能在車內 or 座位縫。", p: "你是別人的安心感。", j: "適合做長期經營，口碑會起來。", b: "願你心中有光，夜路也暖。" },
    { id: 27, rank: "中吉", poem: "雲起遮山影\n風停見水清\n若能忍一刻\n便得好前程", f: "中吉，忍耐一下就轉順。", t: "先不順後順，別急著放棄。", l: "別用情緒推進，穩住更甜。", w: "可成，關鍵在「再等一下」。", m: "有人可能拿錯，詢問可回。", p: "先讓一步，反而得尊重。", j: "適合等消息、等時機，不宜躁進。", b: "願你忍得住一刻，換得一片晴。" },
    { id: 28, rank: "末吉", poem: "山深路更靜\n心急影先斜\n若能慢一息\n自有月來遮", f: "末吉，越急越亂，慢下來才順。", t: "避免臨時衝動出發，先查資訊。", l: "別急著證明自己，先陪伴。", w: "可成，但要按順序來。", m: "在不常翻的地方，需耐心找。", p: "不要硬求回應，留空間更好。", j: "先完成眼前一件事，再談下一件。", b: "願你慢一息，福就靠近一寸。" },
    { id: 29, rank: "吉", poem: "花落還會開\n水去亦能回\n今日若肯信\n明日自成輝", f: "吉，相信自己，運勢就亮。", t: "適合回訪舊地，有驚喜。", l: "有復合或再靠近的機會。", w: "可成，別半途自疑。", m: "會回來，或以另一種形式出現。", p: "你先相信對方，對方也更真。", j: "適合修復關係、重啟合作。", b: "願你所失皆復得，所盼皆成輝。" },
    { id: 30, rank: "大吉", poem: "朝風開萬樹\n日出照千門\n一念生新路\n好運自相奔", f: "大吉，運勢爆開，適合衝刺。", t: "大吉，遠行也能順利。", l: "主動表達會有好結果。", w: "大成，速度比你想的快。", m: "很快找回，或出現線索。", p: "遇到重要貴人，記得把握。", j: "適合公開亮相、爭取舞台。", b: "願你一念成路，好運奔來。" },
    { id: 31, rank: "小吉", poem: "雲薄遮一角\n山高見遠天\n只要再一步\n便是好春年", f: "小吉，差一點點就到。", t: "注意時間安排，別拖延。", l: "再多一點勇敢就成功。", w: "可成，補最後一步即可。", m: "在你走過的路上，回頭找。", p: "別怕麻煩人，問一下就通。", j: "臨門一腳，適合收尾與定案。", b: "願你再一步，就踏進春天。" },
    { id: 32, rank: "中吉", poem: "泉清知石白\n風定見林深\n不必爭先後\n自有好相逢", f: "中吉，順勢而行，會遇到對的人。", t: "適合與可信任的人同行。", l: "相處舒服就是答案。", w: "可成，靠緣分也靠行動。", m: "可能被放到別處，問家人同事。", p: "別逞強，互相幫助更好。", j: "合作運佳，適合找夥伴。", b: "願你不爭也得，終有相逢。" },
    { id: 33, rank: "吉", poem: "山鳥啼新語\n松風送遠香\n心中若有願\n天地也幫忙", f: "吉，有助力，事情會被推動。", t: "適合參拜、走山路，心更順。", l: "有人暗中關心你，留意訊號。", w: "可成，說出口更容易實現。", m: "在朋友或同事那裡，問問看。", p: "你越真誠，越有人願意挺你。", j: "適合提需求、談資源、爭取支援。", b: "願你所願，天地同助。" },
    { id: 34, rank: "末吉", poem: "路窄須側身\n橋搖莫急奔\n只要心不亂\n終會過此門", f: "末吉，遇到窄路，慢慢過就好。", t: "避免趕車趕路，安全第一。", l: "別用壓迫方式推進，會反效果。", w: "可成，但要避開急躁。", m: "不易找回，先停一下再回想。", p: "少爭輸贏，多留體面。", j: "適合保守處理，別冒險。", b: "願你不慌不忙，平安過門。" },
    { id: 35, rank: "小吉", poem: "花開不問早\n雲散自成晴\n今日添一善\n明日得一情", f: "小吉，善意會帶來好回應。", t: "適合輕旅行，心情變好。", l: "多做一件貼心小事就加分。", w: "可成，靠善緣推進。", m: "有人可能幫你收好。", p: "你先釋出善意，對方也回暖。", j: "適合服務、教育、陪伴型工作更旺。", b: "願你一善起風，萬事回溫。" },
    { id: 36, rank: "吉", poem: "松影長如畫\n泉聲細似歌\n若能守初心\n福自不嫌多", f: "吉，回到初心，運勢就回來。", t: "適合靜心之旅，越走越清爽。", l: "不必華麗，真誠最動人。", w: "可成，別忘最初想要什麼。", m: "在你常用的角落，仔細找。", p: "你越真，越吸引真朋友。", j: "適合深耕專業，成果慢慢爆發。", b: "願你守住初心，福氣自來。" },
    { id: 37, rank: "中吉", poem: "雲重遮峰頂\n雨細潤山根\n只要不退步\n終會見乾坤", f: "中吉，眼前不明，但後面會開。", t: "注意天候，備案準備好。", l: "先觀察，別急著下結論。", w: "可成，但要多一點耐心。", m: "在濕雨天容易遺忘，回想最近去處。", p: "不要誤解別人，先問清楚。", j: "適合穩住品質，別急著交差。", b: "願你不退一步，終見乾坤。" },
    { id: 38, rank: "吉", poem: "山花迎客笑\n溪月照人行\n若問何時好\n此刻便分明", f: "吉，好運就在當下。", t: "臨時出發也順，說走就走。", l: "把握現在的互動，不必等完美時機。", w: "可成，現在開始就對了。", m: "在今天活動範圍內，回去找。", p: "你先開口，氣氛就好轉。", j: "適合立刻處理拖延事項，效率高。", b: "願你把握此刻，福氣立現。" },
    { id: 39, rank: "小吉", poem: "路旁生細草\n石上落微光\n只要常抬眼\n處處有芬芳", f: "小吉，小確幸連發，心情會變好。", t: "適合散步與慢逛，越慢越美。", l: "別想太多，享受互動就好。", w: "可成，先讓自己快樂起來。", m: "在小包、側袋、或某個夾層。", p: "你溫柔一點，世界就溫柔一點。", j: "適合做細節、整理、行政收整。", b: "願你抬眼皆光，轉身皆香。" },
    { id: 40, rank: "大吉", poem: "日高山色近\n風暖水聲柔\n一心行正道\n萬事不須愁", f: "大吉，正道之運，做對的事就贏。", t: "大吉，出門遇好人好景。", l: "適合承諾與穩定，感情升級。", w: "大成，且比預期更好。", m: "會找回，且不只一件好消息。", p: "你是別人的貴人，也會遇到貴人。", j: "適合做決策、帶領、推動大事。", b: "願你行正道，萬事皆須愁。" },
    { id: 41, rank: "吉", poem: "雲淡山更秀\n風輕路更寬\n不必問前路\n前路自平安", f: "吉，平穩安定，適合養成好節奏。", t: "順行，適合家庭或朋友同行。", l: "穩穩相處，越來越安心。", w: "可成，按計畫即可。", m: "在固定位置附近，回去找。", p: "你給人安心感，對方願靠近。", j: "適合長期安排、制度建立。", b: "願你前路平安，心也平安。" },
    { id: 42, rank: "中吉", poem: "泉冷知山早\n雲高識路長\n若能添一忍\n自有好收場", f: "中吉，忍一下，結局會漂亮。", t: "注意保暖與體力分配。", l: "少說重話，多說真話。", w: "可成，先處理阻礙。", m: "可能在外出地點，打電話詢問。", p: "別急著評斷，留餘地更好。", j: "適合處理難題，最後會被肯定。", b: "願你多一分忍，換十分圓滿。" },
    { id: 43, rank: "小吉", poem: "花影落衣袖\n風聲過耳邊\n不求多與快\n只求穩與安", f: "小吉，平安就是福，穩住就贏。", t: "宜輕鬆，避免太操勞。", l: "不必轟轟烈烈，舒服最重要。", w: "可成，慢慢推進。", m: "在衣物或包包深處。", p: "你越溫和，越被珍惜。", j: "適合做例行工作與穩定輸出。", b: "願你穩穩走，安安到。" },
    { id: 44, rank: "吉", poem: "松間藏小路\n月下見微光\n只要不放棄\n終會到遠方", f: "吉，有希望、有路，繼續就對。", t: "適合探索冷門路線，收穫大。", l: "只要真心，關係會慢慢靠近。", w: "可成，別半途停。", m: "可能被放在不常用的地方。", p: "你堅持善意，對方會看見。", j: "適合做長期專案，會有成果。", b: "願你不放棄，終到遠方。" },
    { id: 45, rank: "末吉", poem: "雲暗非無路\n風急亦能行\n只要守一念\n終會見天青", f: "末吉，別怕低潮，它會過去。", t: "避免冒險行程，保守較佳。", l: "別在情緒中做決定。", w: "可成，但要先撐過一段。", m: "暫時找不到，晚點會有線索。", p: "你越焦慮越誤解，先冷靜。", j: "不宜硬拚，先顧好身心。", b: "願你守住一念，終見天青。" },
    { id: 46, rank: "中吉", poem: "泉響如人語\n山開似夢長\n若能聽心意\n便不怕迷航", f: "中吉，聽內心的聲音會帶你走對路。", t: "適合靜心之旅，別排太滿。", l: "先確認自己要什麼，再靠近對方。", w: "可成，方向要選對。", m: "在你「以為不可能」的地方。", p: "你越真誠，越吸引對的人。", j: "適合做價值選擇，別只看短利。", b: "願你聽見心意，不再迷航。" },
    { id: 47, rank: "吉", poem: "風暖花先笑\n雲開路更寬\n今日多一勇\n明日少遺憾", f: "吉，勇敢一點，運勢更旺。", t: "說走就走也順，適合踏出新一步。", l: "適合表達心意，或更靠近一步。", w: "可成，主動是鑰匙。", m: "在你最後停留的地方。", p: "你先伸手，關係就升溫。", j: "適合主動爭取資源或機會。", b: "願你多一分勇，少一分遺憾。" },
    { id: 48, rank: "小吉", poem: "山路有微坡\n溪橋有微晃\n不怕小不穩\n只怕心太慌", f: "小吉，小波動正常，別嚇自己。", t: "注意腳步與安全，仍能順利。", l: "別過度解讀訊息，保持自然。", w: "可成，先穩住節奏。", m: "在你最近使用的地方附近。", p: "別急著討好，做自己就好。", j: "適合調整節奏、重新分配時間。", b: "願你不慌不忙，穩穩前行。" },
    { id: 49, rank: "吉", poem: "松老根更穩\n泉長水更清\n今日添一力\n明日見新晴", f: "吉，越努力越穩，後面更亮。", t: "適合走遠一點，會有收穫。", l: "你越成熟，越吸引對的人。", w: "可成，努力會有回報。", m: "在較大的包或行李中。", p: "你可靠，別人自然願靠近。", j: "適合建立制度、培養新人、帶團隊。", b: "願你添一分力，迎十分晴。" },
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
