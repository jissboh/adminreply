<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>SteelDeal x THH Admin Workflow</title>
<style>
  @font-face{font-family:NotoThai;src:url('file:///usr/share/fonts/truetype/noto/NotoSansThai-Regular.ttf') format('truetype');font-weight:400}
  @font-face{font-family:NotoThai;src:url('file:///usr/share/fonts/truetype/noto/NotoSansThaiUI-Bold.ttf') format('truetype');font-weight:700}
  *{box-sizing:border-box}
  body{margin:0;background:#eef2f7;font-family:NotoThai,Arial,sans-serif;color:#172033}
  .page{width:1600px;min-height:2100px;margin:0 auto;background:linear-gradient(180deg,#ffffff 0%,#f8fafc 100%);padding:70px 78px 82px;position:relative;overflow:hidden}
  .page:before{content:"";position:absolute;right:-220px;top:-190px;width:620px;height:620px;border-radius:50%;background:rgba(214,37,37,.10)}
  .page:after{content:"";position:absolute;left:-240px;bottom:-240px;width:620px;height:620px;border-radius:50%;background:rgba(15,23,42,.07)}
  .header{position:relative;z-index:1;display:flex;align-items:center;justify-content:space-between;gap:40px;margin-bottom:34px}
  .brand{display:flex;align-items:center;gap:22px}
  .logo{width:92px;height:92px;border-radius:22px;background:#c91f1f;color:#fff;display:flex;align-items:center;justify-content:center;font-weight:700;font-size:34px;box-shadow:0 18px 35px rgba(201,31,31,.22)}
  .title h1{font-size:48px;line-height:1.08;margin:0;color:#111827;font-weight:700}
  .title p{font-size:24px;margin:12px 0 0;color:#64748b}
  .badge{background:#111827;color:#fff;border-radius:999px;padding:16px 24px;font-size:22px;box-shadow:0 18px 35px rgba(15,23,42,.18)}
  .intro{position:relative;z-index:1;display:grid;grid-template-columns:1.25fr .75fr;gap:26px;margin-bottom:42px}
  .panel{background:#fff;border:1px solid #e5e7eb;border-radius:28px;padding:28px;box-shadow:0 18px 45px rgba(15,23,42,.08)}
  .panel h2{font-size:27px;margin:0 0 14px;color:#c91f1f}
  .panel p,.panel li{font-size:22px;line-height:1.45;margin:0;color:#334155}
  .panel ul{margin:0;padding-left:28px}
  .workflow{position:relative;z-index:1;display:flex;flex-direction:column;align-items:center;gap:18px;margin:10px auto 42px;width:970px}
  .box{width:970px;background:#fff;border:2px solid #dbe3ef;border-radius:30px;padding:22px 28px;box-shadow:0 14px 34px rgba(15,23,42,.08);position:relative}
  .box .step{position:absolute;left:-22px;top:22px;width:54px;height:54px;border-radius:16px;background:#c91f1f;color:#fff;display:flex;align-items:center;justify-content:center;font-size:24px;font-weight:700;box-shadow:0 10px 22px rgba(201,31,31,.22)}
  .box h3{font-size:29px;line-height:1.15;margin:0 0 8px 40px;color:#111827}
  .box p{font-size:22px;line-height:1.42;margin:0 0 0 40px;color:#475569}
  .box .quote{display:inline-block;background:#fef2f2;color:#991b1b;border:1px solid #fecaca;border-radius:16px;padding:8px 14px;margin-top:10px;font-size:21px}
  .arrow{font-size:42px;line-height:1;color:#94a3b8;margin:-2px 0}
  .decision-wrap{width:970px;display:grid;grid-template-columns:1fr 1fr;gap:22px;align-items:stretch}
  .decision{background:#fff;border:2px dashed #cbd5e1;border-radius:30px;padding:24px;box-shadow:0 14px 34px rgba(15,23,42,.06)}
  .decision h4{font-size:25px;margin:0 0 10px;color:#111827}
  .decision p{font-size:21px;line-height:1.38;margin:0;color:#475569}
  .yes{border-color:#86efac;background:#f0fdf4}.yes h4{color:#166534}
  .no{border-color:#fecaca;background:#fff7f7}.no h4{color:#991b1b}
  .columns{position:relative;z-index:1;display:grid;grid-template-columns:1fr 1fr;gap:28px;margin-top:32px}
  .checklist{background:#111827;color:#fff;border-radius:30px;padding:30px;box-shadow:0 20px 45px rgba(15,23,42,.20)}
  .checklist h2{font-size:30px;margin:0 0 16px;color:#fff}
  .checklist ul{margin:0;padding:0;list-style:none;display:grid;gap:12px}
  .checklist li{font-size:21px;line-height:1.35;padding-left:36px;position:relative;color:#e5e7eb}
  .checklist li:before{content:"✓";position:absolute;left:0;top:0;color:#22c55e;font-weight:700}
  .template{background:#fff;border:1px solid #e5e7eb;border-radius:30px;padding:30px;box-shadow:0 18px 45px rgba(15,23,42,.08)}
  .template h2{font-size:30px;margin:0 0 16px;color:#c91f1f}
  .template pre{margin:0;background:#f8fafc;border:1px solid #e2e8f0;border-radius:20px;padding:20px;font-family:NotoThai,Arial,sans-serif;font-size:20px;line-height:1.48;white-space:pre-wrap;color:#334155}
  .footer{position:relative;z-index:1;margin-top:38px;display:flex;justify-content:space-between;align-items:center;color:#64748b;font-size:18px;border-top:1px solid #e2e8f0;padding-top:22px}
  .red{color:#c91f1f;font-weight:700}.small{font-size:18px;color:#64748b}
</style>
</head>
<body>
  <main class="page">
    <section class="header">
      <div class="brand">
        <div class="logo">SD</div>
        <div class="title">
          <h1>Workflow ตอบลูกค้า<br>และส่งต่อเซลล์ทำราคา</h1>
          <p>SteelDeal x THH — สำหรับ Admin ใช้งานหน้าร้าน / LINE / Facebook</p>
        </div>
      </div>
      <div class="badge">เวอร์ชันเข้าใจง่าย</div>
    </section>

    <section class="intro">
      <div class="panel">
        <h2>เป้าหมาย</h2>
        <p>ให้ Admin ตอบลูกค้าได้ไว เก็บข้อมูลครบ และส่งต่อให้เซลล์ทำราคาได้ทันที โดยไม่ต้องเดาข้อมูลเอง</p>
      </div>
      <div class="panel">
        <h2>จำ 3 เรื่องนี้</h2>
        <ul>
          <li>ข้อมูลสินค้าต้องครบ</li>
          <li>Location ต้องชัด</li>
          <li>ทุก Lead ต้องลง Tracker</li>
        </ul>
      </div>
    </section>

    <section class="workflow">
      <div class="box"><div class="step">1</div><h3>ลูกค้าทักเข้ามา</h3><p>เริ่มต้นจาก LINE, Facebook, โทร หรือช่องทางอื่น</p></div>
      <div class="arrow">↓</div>
      <div class="box"><div class="step">2</div><h3>ทักทายลูกค้า</h3><p>ใช้ข้อความมาตรฐานเพื่อตอบให้เร็วและสุภาพ<br><span class="quote">“สวัสดีค่ะ SteelDeal ยินดีให้บริการค่ะ”</span></p></div>
      <div class="arrow">↓</div>
      <div class="box"><div class="step">3</div><h3>ถามข้อมูลหลักให้ครบ</h3><p>ประเภทสินค้า + ขนาด, จำนวน, สถานที่จัดส่ง, เบอร์โทร, เอกสารภาษีถ้ามี</p></div>
      <div class="arrow">↓</div>
      <div class="box"><div class="step">4</div><h3>ตรวจสอบข้อมูลสินค้า</h3><p>เหล็กรูปพรรณต้องมี ดำ/GI + ขนาด + ความหนา | เหล็กเส้นต้องถาม ตรง/พับ + ยี่ห้อ + มอก.</p></div>
      <div class="decision-wrap">
        <div class="decision yes"><h4>ถ้าข้อมูลครบ</h4><p>ไปขั้นตอนถามราคาเงินสดหรือผ่อน</p></div>
        <div class="decision no"><h4>ถ้าข้อมูลไม่ครบ</h4><p>ถามเพิ่มก่อน ห้ามส่งเซลล์ทันที เพราะเซลล์ทำราคาไม่ได้</p></div>
      </div>
      <div class="arrow">↓</div>
      <div class="box"><div class="step">5</div><h3>ถามเงื่อนไขราคา</h3><p>ถามว่า “ต้องการราคาเงินสด หรือราคาผ่อนคะ” และแจ้งว่าเงินสดมีส่วนลดเพิ่มเติม</p></div>
      <div class="arrow">↓</div>
      <div class="box"><div class="step">6</div><h3>ตรวจสอบพื้นที่จัดส่ง</h3><p>ถ้าเกิน 300 กม. จัดส่งได้เฉพาะยอดสั่ง 15 ตันขึ้นไป</p></div>
      <div class="decision-wrap">
        <div class="decision yes"><h4>ไม่เกิน 300 กม.</h4><p>ส่งต่อเซลล์ทำราคาได้ตามปกติ</p></div>
        <div class="decision no"><h4>เกิน 300 กม.</h4><p>เช็คว่ายอดถึง 15 ตันหรือไม่ ถ้าไม่ถึงให้แจ้งลูกค้าก่อน</p></div>
      </div>
      <div class="arrow">↓</div>
      <div class="box"><div class="step">7</div><h3>ส่งข้อมูลให้เซลล์ทำราคา</h3><p>ส่งข้อมูลที่ครบแล้วเท่านั้น พร้อมสรุปให้เป็นระเบียบ</p></div>
      <div class="arrow">↓</div>
      <div class="box"><div class="step">8</div><h3>ลงข้อมูลใน SteelDeal Lead Tracker</h3><p>ต้องลงทุก Lead ทันทีหลังคุยเสร็จ เพื่อไม่ให้ข้อมูลหาย</p></div>
    </section>

    <section class="columns">
      <div class="checklist">
        <h2>Checklist ก่อนส่งเซลล์</h2>
        <ul>
          <li>ชื่อลูกค้าและเบอร์โทร</li>
          <li>ประเภทสินค้า / ขนาด / ความหนา</li>
          <li>ดำ หรือ GI / ตรง หรือ พับ</li>
          <li>จำนวนที่ต้องการ</li>
          <li>สถานที่จัดส่ง อย่างน้อยตำบล/อำเภอ</li>
          <li>Google Map ถ้ามี</li>
          <li>ข้อมูลใบกำกับภาษี ถ้าลูกค้าต้องการ</li>
        </ul>
      </div>
      <div class="template">
        <h2>Template ส่งต่อเซลล์</h2>
        <pre>ชื่อลูกค้า:
เบอร์:

สินค้า:
ขนาด:
ความหนา:
ดำ/GI:
ตรง/พับ:
จำนวน:

จัดส่ง:
Google Map:

เงินสด/ผ่อน:
ใบกำกับภาษี: มี / ไม่มี</pre>
      </div>
    </section>

    <section class="footer">
      <div><span class="red">SteelDeal</span> — เหล็กราคาโรงงาน ส่งถึงที่ ไม่มีขั้นต่ำ</div>
      <div class="small">อ้างอิงจาก SOP เดิม: SteelDeal x THH</div>
    </section>
  </main>
</body>
</html>
