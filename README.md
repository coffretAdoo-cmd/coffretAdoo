<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Coffret Adoo — أفضل باكات Raflilia</title>
  <style>
    :root{
      --accent:#E11D48;
      --muted:#6B7280;
      --bg:#f7f7fb;
    }
    body{
      font-family:Inter,Arial,Helvetica,sans-serif;
      background:var(--bg);
      margin:0;
      color:#111;
    }
    header{
      background:linear-gradient(90deg,#111827, #1f2937);
      color:#fff;
      padding:22px 16px;
      text-align:center;
    }
    header h1{margin:0;font-size:22px}
    .container{max-width:980px;margin:26px auto;padding:0 16px}
    .top{display:flex;gap:16px;align-items:center;justify-content:space-between;flex-wrap:wrap}
    .hero{background:#fff;padding:18px;border-radius:14px;box-shadow:0 6px 20px rgba(16,24,40,0.06);flex:1}
    .hero p{margin:8px 0;color:var(--muted)}
    .phone{background:var(--accent);color:#fff;padding:10px 14px;border-radius:10px;font-weight:700;text-decoration:none}
    .packs{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px;margin-top:18px}
    .card{background:#fff;padding:14px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.06)}
    .card img{width:100%;height:170px;object-fit:cover;border-radius:8px}
    .card h3{margin:10px 0 6px}
    .price{color:var(--accent);font-weight:800}
    .order-btn{display:inline-block;margin-top:10px;padding:10px 12px;border-radius:10px;background:#10b981;color:#fff;text-decoration:none}

    .order-area{background:#fff;padding:18px;border-radius:12px;margin-top:20px;box-shadow:0 6px 18px rgba(2,6,23,0.06)}
    label{display:block;font-size:14px;margin-top:10px;color:#111}
    input[type=text],select,textarea{width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9ef;margin-top:6px;font-size:14px}
    .submit{margin-top:12px;padding:12px 14px;border-radius:10px;background:#25D366;color:#fff;border:0;font-weight:700}
    footer{text-align:center;color:var(--muted);font-size:13px;padding:26px 10px}

    @media (max-width:640px){header h1{font-size:18px}}
  </style>
</head>
<body>
  <header>
    <h1>Coffret Adoo — عروض Raflilia Packs (طلب عبر WhatsApp)</h1>
  </header>

  <div class="container">
    <div class="top">
      <div class="hero">
        <h2>Coffret RAFLILIA Collection 5 Pièces Pour Femme et Homme</h2>
        <p>اختار الباك، عطي الاسم و البلاصة و رقم الهاتف — و غادي نرسلوك فوراً عبر WhatsApp باش تأكد الطلب.</p>
      </div>

      <!-- رقم الهاتف بارز -->
      <a class="phone" href="https://wa.me/212642553660" target="_blank">📱 طلب عبر واتساب: 0642553660</a>
    </div>

    <section class="packs" aria-label="Packs list">

      <!-- Sample packs -->
      <article class="card">
        <img src="https://makeupstore15.com/wp-content/uploads/2025/04/WhatsApp-Image-2025-04-01-a-14.38.04_e3442015.jpg" alt="Pack 1" />
        <h3>Pack LUXURIANCE</h3>
        <div class="price">199 DH</div>
        <p>مجموعة كاملة من منتجات العناية والتجميل للنساء، مناسبة لجميع أنواع البشرة وجميع الأعمار.كل باك كيجمع بين العطر، اللوشن، الكريمات، والزيوت بجودة عالية وثبات ممتاز.</p>
        <a class="order-btn" href="#order-form">طلب الآن</a>
      </article>

      <article class="card">
        <img src="https://makeupstore15.com/wp-content/uploads/2025/04/WhatsApp-Image-2025-04-01-a-14.38.03_46e2ddca.jpg" alt="Pack 2" />
        <h3>Pack BROWN</h3>
        <div class="price">199 DH</div>
        <p>مجموعة كاملة من منتجات العناية والتجميل للنساء، مناسبة لجميع أنواع البشرة وجميع الأعمار.</p>
        <a class="order-btn" href="#order-form">طلب الآن</a>
      </article>

      <article class="card">
        <img src="https://makeupstore15.com/wp-content/uploads/2025/03/IMG-20250328-WA0068-1.jpg" alt="Pack 3" />
        <h3>Pack YOU</h3>
        <div class="price">199 DH</div>
        <p>مجموعة كاملة من منتجات العناية والتجميل للنساء، مناسبة لجميع أنواع البشرة وجميع الأعمار.</p>
        <a class="order-btn" href="#order-form">طلب الآن</a>
      </article>

      <article class="card">
        <img src="https://makeupstore15.com/wp-content/uploads/2025/03/IMG-20250328-WA0074-2.jpg" alt="Pack 4" />
        <h3>Pack AMIRAT AL ARAB</h3>
        <div class="price">199 DH</div>
        <p>مجموعة كاملة من منتجات العناية والتجميل للنساء، مناسبة لجميع أنواع البشرة وجميع الأعمار.</p>
        <a class="order-btn" href="#order-form">طلب الآن</a>
      </article>

    </section>

    <!-- Order form -->
    <section id="order-form" class="order-area">
      <h2>نموذج الطلب — عبي المعلومات و غادي نرسل الطلب عبر WhatsApp</h2>
      <form id="waForm" onsubmit="sendWhatsApp(event)">
        <label for="name">الاسم الكامل</label>
        <input id="name" name="name" type="text" placeholder="سمية ديالك" required />

        <label for="phone">رقم التلفون</label>
        <input id="phone" name="phone" type="text" placeholder="مثال: 06XXXXXXXX" required />

        <label for="location">المدينة / العنوان</label>
        <input id="location" name="location" type="text" placeholder="مثال: الدار البيضاء، السويسي" required />

        <label for="pack">اسم الباك لي بغيتي</label>
        <select id="pack" name="pack" required>
          <option value="Pack Raflilia Premium">Pack Raflilia Premium — 49 DH</option>
          <option value="Pack Raflilia Mega">Pack Raflilia Mega — 69 DH</option>
          <option value="Pack Raflilia Master">Pack Raflilia Master — 99 DH</option>
        </select>

        <label for="note">ملاحظة (اختياري)</label>
        <textarea id="note" name="note" rows="3" placeholder="شي ملاحظة إضافية..."></textarea>

        <button class="submit" type="submit">إرسال الطلب عبر WhatsApp</button>
      </form>

      <p style="margin-top:12px;color:var(--muted)">
        <strong>ملاحظة:</strong> عند الضغط على إرسال، غادي يفتح واتساب مع رسالة مكتوبة تلقائياً لرقم <strong>0642553660</strong>.
      </p>
    </section>
  </div>

  <footer>
    Coffret Adoo — أسرع وأوثق من TwinFragrance. جاهز للـ GitHub Pages / Netlify / Vercel.
  </footer>

  <script>
    function esc(text){return encodeURIComponent(text)}
    function sendWhatsApp(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const phone = document.getElementById('phone').value.trim();
      const location = document.getElementById('location').value.trim();
      const pack = document.getElementById('pack').value;
      const note = document.getElementById('note').value.trim();
      const target = '212642553660';
      let msg = `طلب من الموقع:\n`;
      msg += `الاسم: ${name}\n`;
      msg += `الهاتف: ${phone}\n`;
      msg += `المكان: ${location}\n`;
      msg += `الباك: ${pack}\n`;
      if(note) msg += `ملاحظة: ${note}\n`;
      const url = `https://wa.me/${target}?text=${encodeURIComponent(msg)}`;
      window.open(url,'_blank');
    }
  </script>
</body>
</html>
