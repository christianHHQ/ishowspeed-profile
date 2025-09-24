<!doctype html>

<html lang="th">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>IShowSpeed — โปรไฟล์</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#ff5c8a;--muted:#94a3b8;--glass:rgba(255,255,255,0.04)}
    *{box-sizing:border-box}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,'Noto Sans Thai',"Helvetica Neue",Arial;margin:0;background:linear-gradient(180deg,#061025 0%, #0b1730 100%);color:#e6eef8;line-height:1.45}
    .container{max-width:1000px;margin:32px auto;padding:20px}header{display:flex;gap:20px;align-items:center}
.avatar{width:140px;height:140px;border-radius:12px;overflow:hidden;flex:0 0 140px;border:4px solid rgba(255,255,255,0.06);background:linear-gradient(135deg,#14213d,#0b2b45);display:grid;place-items:center}
.avatar img{width:100%;height:100%;object-fit:cover}
.title h1{margin:0;font-size:1.6rem}
.title p{margin:6px 0 0;color:var(--muted)}

.card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 24px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}

.grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:20px}
@media (max-width:880px){.grid{grid-template-columns:1fr} .avatar{width:110px;height:110px;flex:0 0 110px}}

.bio h2,.music h2,.gallery h2{margin-top:0}
.meta{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
.chip{background:var(--glass);padding:6px 10px;border-radius:999px;color:var(--muted);font-size:0.9rem}

.stats{display:flex;gap:12px;margin-top:12px}
.stat{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(0,0,0,0.02));padding:10px;border-radius:8px;min-width:80px;text-align:center}
.stat strong{display:block;font-size:1.1rem}

.songs{list-style:none;padding:0;margin:0}
.songs li{padding:10px;border-bottom:1px dashed rgba(255,255,255,0.03);display:flex;justify-content:space-between;align-items:center}
.songs li:last-child{border-bottom:0}
.btn{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:8px;color:inherit;cursor:pointer}

.gallery-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
@media (max-width:600px){.gallery-grid{grid-template-columns:repeat(2,1fr)}}
.gallery-grid img{width:100%;height:110px;object-fit:cover;border-radius:8px;cursor:pointer}

footer{margin-top:20px;color:var(--muted);font-size:0.9rem;text-align:center}

.modal{position:fixed;inset:0;background:rgba(2,6,23,0.7);display:none;align-items:center;justify-content:center;padding:20px}
.modal.open{display:flex}
.modal .modal-card{max-width:900px;width:100%;background:#071427;padding:12px;border-radius:10px}
.modal img{width:100%;height:auto;border-radius:8px}

.timeline{margin-top:12px;border-left:2px dashed rgba(255,255,255,0.04);padding-left:12px}
.event{margin-bottom:12px}
.event time{display:block;color:var(--muted);font-size:0.85rem}

.row{display:flex;gap:8px;align-items:center}
.hidden{display:none}

  </style>
</head>
<body>
  <div class="container">
    <header class="card" aria-label="โปรไฟล์ IShowSpeed">
      <div class="avatar">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/IShowSpeed_2023.jpg" alt="IShowSpeed">
      </div>
      <div class="title">
        <h1 id="idol-name">IShowSpeed</h1>
        <p id="idol-sub">Streamer • YouTuber • Rapper</p>
        <div class="meta" id="tags">
          <span class="chip">แนวเพลง: Rap / Hip-Hop</span>
          <span class="chip">เริ่มดัง: 2020</span>
          <span class="chip">ผู้ติดตาม: 25M+</span>
        </div>
        <div class="stats">
          <div class="stat"><small>อายุ</small><strong id="age">20</strong></div>
          <div class="stat"><small>สูง</small><strong id="height">172 cm</strong></div>
          <div class="stat"><small>น้ำหนัก</small><strong id="weight">65 kg</strong></div>
        </div>
      </div>
    </header><div class="grid">
  <main>
    <section class="card bio">
      <h2>ประวัติย่อ</h2>
      <p id="bio-text">IShowSpeed หรือชื่อจริง Darren Watkins Jr. เป็นสตรีมเมอร์และยูทูบเบอร์ชาวอเมริกันที่มีชื่อเสียงจากการไลฟ์สตรีมเกมและคอนเทนต์ตลก ๆ ความโดดเด่นคือความเป็นเอกลักษณ์ ความตลก และพลังงานที่มากมาย รวมถึงผลงานเพลงที่ได้รับความนิยม</p>

      <div class="timeline">
        <div class="event"><time>2020</time><strong>เริ่มสตรีมบน YouTube และ Twitch</strong></div>
        <div class="event"><time>2021</time><strong>เพลง breakout: "Shake"</strong></div>
        <div class="event"><time>2022</time><strong>ได้รับความนิยมระดับโลกจากคอนเทนต์ฟุตบอลและเพลง "World Cup"</strong></div>
      </div>
    </section>

    <section class="card music" style="margin-top:16px">
      <h2>เพลง / ผลงานเด่น</h2>
      <ul class="songs">
        <li><span>Shake</span><div class="row"><button class="btn" onclick="playSample('Shake')">▶ ฟัง</button><button class="btn" onclick="copyText('Shake')">คัดลอกชื่อ</button></div></li>
        <li><span>Ronaldo (Siu)</span><div class="row"><button class="btn" onclick="playSample('Ronaldo (Siu)')">▶ ฟัง</button><button class="btn" onclick="copyText('Ronaldo (Siu)')">คัดลอกชื่อ</button></div></li>
        <li><span>World Cup</span><div class="row"><button class="btn" onclick="playSample('World Cup')">▶ ฟัง</button><button class="btn" onclick="copyText('World Cup')">คัดลอกชื่อ</button></div></li>
      </ul>
    </section>
  </main>

  <aside>
    <section class="card" style="margin-bottom:12px">
      <h2>ข้อมูลสั้น</h2>
      <p><strong>วันเกิด:</strong> <span id="birthday">21 มกราคม 2005</span></p>
      <p><strong>กรุ๊ปเลือด:</strong> <span id="blood">—</span></p>
      <p><strong>ประเทศ:</strong> <span id="agency">สหรัฐอเมริกา</span></p>
      <div style="margin-top:8px">
        <button class="btn" onclick="toggleFollow(this)">ติดตาม</button>
        <button class="btn" onclick="downloadCard()">ดาวน์โหลดโปรไฟล์</button>
      </div>
    </section>

    <section class="card gallery">
      <h2>แกลเลอรี่</h2>
      <div class="gallery-grid">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/IShowSpeed_2023.jpg" alt="IShowSpeed" onclick="openModal(this.src)">
        <img src="https://via.placeholder.com/400?text=Speed+2" alt="IShowSpeed 2" onclick="openModal(this.src)">
        <img src="https://via.placeholder.com/400?text=Speed+3" alt="IShowSpeed 3" onclick="openModal(this.src)">
      </div>
    </section>

    <section class="card" style="margin-top:12px">
      <h2>โซเชียล</h2>
      <p class="meta">
        <a class="chip" href="https://www.youtube.com/@IShowSpeed" target="_blank">YouTube</a>
        <a class="chip" href="https://www.instagram.com/ishowspeed/" target="_blank">Instagram</a>
        <a class="chip" href="https://twitter.com/ishowspeedsui" target="_blank">Twitter/X</a>
      </p>
    </section>
  </aside>
</div>

<div class="modal" id="modal">
  <div class="modal-card">
    <button class="btn" style="float:right;margin-bottom:8px" onclick="closeModal()">ปิด</button>
    <img id="modal-img" src="" alt="ดูรูป">
  </div>
</div>

<footer>
  โปรไฟล์ตัวอย่างของ IShowSpeed — สามารถแก้ไข/เพิ่มเติมได้ตามต้องการ
</footer>

  </div>  <script>
    function openModal(src){document.getElementById('modal-img').src=src;document.getElementById('modal').classList.add('open')}
    function closeModal(){document.getElementById('modal').classList.remove('open')}
    function playSample(name){alert('เล่นตัวอย่าง: '+name+' (ตัวอย่างเท่านั้น)')}
    function copyText(text){navigator.clipboard?.writeText(text).then(()=>alert('คัดลอก: '+text))}
    function toggleFollow(btn){btn.textContent = btn.textContent === 'ติดตาม' ? 'เลิกติดตาม' : 'ติดตาม'}
    function downloadCard(){
      const data = { name: document.getElementById('idol-name').textContent, bio: document.getElementById('bio-text').textContent };
      const blob = new Blob([JSON.stringify(data, null, 2)],{type:'application/json'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a'); a.href = url; a.download = 'ishowspeed-profile.json'; a.click(); URL.revokeObjectURL(url);
    }
  </script></body>
</html>
