<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>kita rehat sejenak</title>

  <!-- Google Font: Poppins -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --pink:#F8C8DC;
      --white:#ffffff;
      --text:#333;
      --muted:#7a6b78;
      --accent:#ff7ab6;
      --max-width:1000px;
    }

    *{box-sizing:border-box}
    html,body{
      height:100%;
      margin:0;
      font-family:'Poppins',system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      background: linear-gradient(180deg, var(--pink) 0%, #FFEAF2 60%);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    .wrap{
      max-width:var(--max-width);
      margin:2rem auto;
      background:var(--white);
      border-radius:18px;
      padding:28px;
      box-shadow:0 8px 30px rgba(0,0,0,0.08);
      border: 1px solid rgba(255,120,160,0.08);
    }

    header{
      text-align:center;
      padding:18px 12px 6px;
    }
    .title{
      font-size:clamp(28px,6vw,44px);
      font-weight:700;
      color:#6b2740;
      margin:0;
      text-transform:lowercase;
      letter-spacing:0.6px;
    }
    .subtitle{
      margin-top:8px;
      font-size:clamp(12px,2.2vw,16px);
      color:var(--muted);
      font-weight:400;
    }

    main{
      display:grid;
      grid-template-columns: 1fr;
      gap:20px;
      margin-top:18px;
    }

    .card{
      background:linear-gradient(180deg, rgba(248,200,220,0.35), rgba(255,255,255,0.6));
      border-radius:12px;
      padding:18px;
      border:1px solid rgba(255,120,160,0.12);
    }

    h2.section-title{
      margin:0 0 10px 0;
      font-size:18px;
      color:#5c2337;
      text-transform:lowercase;
    }

    p{margin:0 0 12px 0; line-height:1.6; color:var(--text); font-size:15px}

    /* Foto area */
    .photo-area{
      display:flex;
      gap:16px;
      align-items:flex-start;
      flex-wrap:wrap;
    }
    .photo-area img{
      width:100%;
      max-width:420px; /* responsive */
      height:auto;
      border-radius:10px;
      border:6px solid var(--pink);
      display:block;
      object-fit:cover;
      box-shadow:0 8px 20px rgba(107,39,64,0.08);
    }
    .photo-caption{
      font-size:13px;
      color:var(--muted);
      max-width:520px;
      align-self:center;
    }

    /* Buttons */
    .actions{
      display:flex;
      gap:12px;
      flex-wrap:wrap;
      margin-top:6px;
    }
    .btn{
      background:var(--accent);
      color:var(--white);
      border:none;
      padding:10px 16px;
      border-radius:999px;
      font-weight:600;
      cursor:pointer;
      box-shadow:0 6px 18px rgba(255,122,160,0.18);
      transition:transform .18s ease, box-shadow .18s ease, opacity .12s;
    }
    .btn.secondary{
      background:transparent;
      color:#6b2740;
      border:1.5px solid rgba(107,39,64,0.08);
      box-shadow:none;
      font-weight:600;
    }
    .btn:active{transform:translateY(1px)}
    .btn:disabled{opacity:.6;pointer-events:none}

    /* alasanHebat hidden */
    #alasanHebat{
      display:none;
      margin-top:12px;
      background:rgba(255,255,255,0.5);
      padding:12px;
      border-radius:10px;
      border:1px dashed rgba(107,39,64,0.06);
    }
    #alasanHebat ol{
      margin:0;
      padding-left:18px;
      color:#5b2b3f;
      line-height:1.7;
      font-weight:500;
    }

    /* Spotify embed area */
    .embed-box{
      min-height:300px;
      border-radius:12px;
      display:flex;
      align-items:center;
      justify-content:center;
      background:linear-gradient(180deg, rgba(255,255,255,0.6), rgba(248,200,220,0.12));
      border:1px solid rgba(107,39,64,0.03);
      color:var(--muted);
      padding:18px;
      text-align:center;
    }

    footer{
      margin-top:18px;
      text-align:center;
      color:var(--muted);
      font-size:13px;
    }

    /* responsive grid for photo + text on large screens */
    @media(min-width:880px){
      main{
        grid-template-columns: 1fr 1fr;
        gap:20px 28px;
      }
      .wrap{padding:34px}
      header{padding-bottom:8px}
    }

    @media(max-width:420px){
      .photo-area img{max-width:100%}
      .subtitle{padding:0 6px}
    }
  </style>
</head>
<body>
  <div class="wrap" role="main">
    <header>
      <h1 class="title">kita rehat sejenak</h1>
      <p class="subtitle">jeda dulu dari kerjaan UT dan drillbit yg menyebalkan itu</p>
    </header>

    <main>
      <!-- Bagian 2: Validasi Perasaan -->
      <section class="card" aria-labelledby="val-title">
        <h2 id="val-title" class="section-title">di baca ajaa yaa sayaang semoga lebih tenang walaupun ga akan bantu banyak</h2>
        <p>
aku tau kamu udah giat bgt sampe seharian dalam beberapa hari ini. dan skor plagiasi itu malah makin gajelas dan ngeselin ya. gapapa sayang, pasti ada jalan keluarnya walaupun susah. capek itu wajar bgt, nangis juga gapapa banget. kamu udah lakuin yg terbaik dan aku bangga bgt sama kamu dan mama papa kamu juga pasti bangga bgt sama kamu. ILYSM SAYAANGGG MWAAHHH - a BIG hug for oyeenn sayangkuu
        </p>
        <p style="font-size:13px;color:var(--muted);margin-top:6px;">(saya di sini nemenin kamu, beneran. ngopi? ngemil? curhat dikit?)</p>
      </section>

      <!-- Bagian 3: Area Penyemangat (Foto Idol) -->
      <section class="card" aria-labelledby="photo-title">
        <h2 id="photo-title" class="section-title">nihh dari pacar kamu yg ganteng</h2>
        <div class="photo-area">
          <img src="https://i.pinimg.com/1200x/95/c6/98/95c69874c65cd3bdbf7a0bab22eec526.jpg" width="735" height="977" alt="foto pacar ganteng (placeholder)" />
          <div class="photo-caption">
            tuuu liat yangg taehyung juga bangga sama kamu pasti dia seneng tuh kalo liat kamu, kata dia bilang 'hwaiting floren' btw aku dm dia bilang kamu ARMY sejati dan lagi bikin artikel tentang BTS ini
          </div>
        </div>
      </section>

      <!-- Bagian 4: Tombol Aksi dan 3 Alasan (DYNAMIC) -->
      <section class="card" aria-labelledby="action-title">
        <h2 id="action-title" class="section-title">sedikit hiburan biar napas lega</h2>
        <p style="margin-bottom:8px;">pilih dulu yang pengen kamu coba, semuanya aman dan cuma dari aku yang sayang.</p>

        <div class="actions">
          <button class="btn" id="scrollToMusic">jeda dulu nih dengerin yah</button>
          <button class="btn secondary" id="showAlasanBtn" onclick="toggleAlasan()">3 fun fun fun fact</button>
        </div>

        <div id="alasanHebat" aria-hidden="true">
          <ol>
            <li>kamu keren sehari aja bisa revisi terus kumpul, aku bangga banget sama kamu!</li>
            <li>aku kangen terus deh sama kamu kenapa ya kamu ngangenin baget, keren kamu bikin aku kangen teruss.</li>
            <li>btw kamu ga pernah ga cantik alias cantik teruss!</li>
          </ol>
        </div>

      </section>

      <!-- Bagian 5: Playlist/Music Section -->
      <section id="music" class="card" aria-labelledby="music-title">
        <h2 id="music-title" class="section-title">dengerin nih kedistract bentar biar goyang</h2>
        <div class="embed-box" role="region" aria-label="Spotify embed area">
          <div>
            <p style="margin:0 0 6px 0; font-weight:600; color:#5b2b3f;">embed Spotify di sini (placeholder)</p>
            <p style="margin:0; font-size:13px; color:var(--muted); max-width:560px">
              Tempelkan kode &lt;https://open.spotify.com/album/4VFwqb1N4CvkB00X2noeup?si=oZIE0WDuQUqBzHuhX8ou6w&gt; Spotify: **
            </p>
            <p style="margin-top:10px;font-size:12px;color:var(--muted)">atau gunakan <em>share → embed</em> dari Spotify lalu paste iframe di sini.</p>
          </div>
        </div>
      </section>
    </main>

    <footer>
      <small>dibuat khusus buat kamu — istirahat dulu, aku nemenin. ❤️</small>
    </footer>
  </div>

  <script>
    // Toggle the hidden alasanHebat div
    function toggleAlasan(){
      var box = document.getElementById('alasanHebat');
      if(!box) return;
      if(box.style.display === 'block'){
        box.style.display = 'none';
        box.setAttribute('aria-hidden','true');
        document.getElementById('showAlasanBtn').textContent = '3 fun fun fun fact';
      } else {
        box.style.display = 'block';
        box.setAttribute('aria-hidden','false');
        document.getElementById('showAlasanBtn').textContent = 'tutup';
        // smooth scroll to the revealed box
        setTimeout(function(){
          box.scrollIntoView({behavior:'smooth', block:'center'});
        }, 150);
      }
    }

    // Smooth scroll to music section
    document.getElementById('scrollToMusic').addEventListener('click', function(){
      var el = document.getElementById('music');
      if(!el) return;
      el.scrollIntoView({behavior:'smooth', block:'start'});
      // small focus for a11y
      setTimeout(function(){ el.querySelector('.section-title')?.focus?.(); }, 700);
    });
  </script>
</body>
</html>
