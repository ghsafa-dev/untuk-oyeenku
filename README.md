<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>kita rehat sejenak</title>

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
      scroll-behavior: smooth; /* Tambahkan smooth scroll */
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
    #alasanHebat li {
      list-style-type: decimal;
    }

    /* Spotify embed area (Sudah Dibersihkan, tinggal tempel iframe) */
    #music iframe {
      border: 0;
      border-radius: 12px;
      height: 350px; /* Minimal tinggi */
      width: 100%;
      max-width: 500px;
      display: block;
      margin: 10px auto;
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
            <section class="card" aria-labelledby="val-title">
        <h2 id="val-title" class="section-title">di baca ajaa yaa sayaang semoga lebih tenang walaupun ga akan bantu banyak</h2>
        <p>
aku tau kamu udah giat bgt sampe seharian dalam beberapa hari ini. dan skor plagiasi itu malah makin gajelas dan ngeselin ya. gapapa sayang, pasti ada jalan keluarnya walaupun susah. capek itu wajar bgt, nangis juga gapapa banget. kamu udah lakuin yg terbaik dan aku bangga bgt sama kamu dan mama papa kamu juga pasti bangga bgt sama kamu. ILYSM SAYAANGGG MWAAHHH - a BIG hug for oyeenn sayangkuu
        </p>
        <p style="font-size:13px;color:var(--muted);margin-top:6px;">(yg terbaik buat kamu yaa, aamiinnnn)</p>
      </section>

            <section class="card" aria-labelledby="photo-title">
        <h2 id="photo-title" class="section-title">nihh dari pacar kamu yg ganteng</h2>
        <div class="photo-area">
                    <img src="https://images.unsplash.com/photo-1542438692-72c687e87b64?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzNzcyMTJ8MHwxfHNlYXJjaHw3MHx8S29yZWFuJTIwaWRvbHxlbnwwfHx8fDE3MDYyMjk0MjZ8MA&ixlib=rb-4.0.3&q=80&w=420" width="420" height="560" alt="foto pacar kamu yg ganteng " />
          <div class="photo-caption">
            tuuu liat yangg taehyung juga bangga sama kamu pasti dia seneng tuh kalo liat kamu, kata dia bilang 'hwaiting floren' btw aku dm dia bilang kamu ARMY sejati dan lagi bikin artikel tentang BTS ini
          </div>
        </div>
      </section>

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

            <section id="music" class="card" aria-labelledby="music-title">
        <h2 id="music-title" class="section-title">dengerin nih kedistract bentar biar goyang</h2>
        
        <div style="height:300px; background:#f5f5f5; border-radius:12px; display:flex; align-items:center; justify-content:center; color:#999; font-size:14px;">
            TEMPЕL KODE IFRAME SPOTIFY KAMU DI SINI
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
      var btn = document.getElementById('showAlasanBtn');
      if(!box || !btn) return;
      
      if(box.style.display === 'block'){
        box.style.display = 'none';
        box.setAttribute('aria-hidden','true');
        btn.textContent = '3 fun fun fun fact';
      } else {
        box.style.display = 'block';
        box.setAttribute('aria-hidden','false');
        btn.textContent = 'tutup';
        // smooth scroll ke revealed box
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
    });
  </script>
</body>
</html>
