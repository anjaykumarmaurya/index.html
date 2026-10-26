# index.html

<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Seva Bharat</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f3f6fc;
      color: #17243a;
    }
    header {
      background: #102b57;
      color: white;
      padding: 18px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }
    header h2 { margin: 0; }
    header p { margin: 5px 0 0; font-size: 13px; }
    .hero {
      padding: 55px 6%;
      background: linear-gradient(120deg, #e4edff, #fff7e5);
      text-align: center;
    }
    .hero h1 { font-size: clamp(30px, 5vw, 48px); margin: 0 0 15px; }
    .hero p { line-height: 1.7; }
    .btn {
      display: inline-block;
      border: 0;
      border-radius: 8px;
      background: #f2b544;
      color: #17243a;
      padding: 12px 20px;
      font-weight: bold;
      cursor: pointer;
      text-decoration: none;
      margin-top: 12px;
    }
    main { max-width: 1100px; margin: auto; padding: 30px 18px; }
    .notice {
      background: #fff1cf;
      padding: 13px;
      border-radius: 8px;
      font-size: 13px;
      line-height: 1.6;
    }
    .tools { margin: 25px 0; }
    input {
      width: 100%;
      padding: 13px;
      border: 1px solid #ccd5e3;
      border-radius: 8px;
      font-size: 16px;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 16px;
    }
    .card {
      background: white;
      padding: 22px;
      border-radius: 13px;
      border: 1px solid #e0e7f1;
      box-shadow: 0 5px 18px #102b570d;
    }
    .card .icon { font-size: 30px; }
    .card h3 { margin-bottom: 8px; }
    .card p { color: #65738a; font-size: 14px; line-height: 1.6; }
    footer {
      background: #102b57;
      color: white;
      text-align: center;
      padding: 25px 15px;
      margin-top: 30px;
      line-height: 1.8;
    }
  </style>
</head>
<body>
  <header>
    <div>
      <h2>🇮🇳 Digital Seva Bharat</h2>
      <p>आपकी डिजिटल सेवाएँ, एक जगह</p>
    </div>
    <a class="btn" href="#services">सर्विस देखें</a>
  </header>

  <section class="hero">
    <h1>हर डिजिटल सेवा,<br>एक ही प्लेटफॉर्म पर।</h1>
    <p>बिल भुगतान, सरकारी आवेदन की जानकारी और बिज़नेस सेवाएँ।</p>
    <a class="btn" href="#services">सभी सेवाएँ देखें ↓</a>
  </section>

  <main>
    <div class="notice">
      <strong>डेमो वेबसाइट:</strong>
      यह वेबसाइट अभी जानकारी दिखाती है। वास्तविक भुगतान,
      लॉगिन और सरकारी सेवाएँ अभी कनेक्ट नहीं हैं।
      किसी भी फॉर्म में OTP, PIN या पासवर्ड दर्ज न करें।
    </div>

    <section id="services">
      <h2>हमारी डिजिटल सेवाएँ</h2>
      <p>अपनी जरूरत की सेवा खोजें।</p>

      <div class="tools">
        <input id="search" type="search"
          placeholder="सेवा खोजें: PAN, बैंक, बिल..."
          aria-label="सेवा खोजें">
      </div>

      <div class="services" id="serviceList">
        <article class="card">
          <div class="icon">⚡</div>
          <h3>बिल भुगतान</h3>
          <p>बिजली, पानी, गैस और मोबाइल बिल की जानकारी।</p>
        </article>
        <article class="card">
          <div class="icon">🪪</div>
          <h3>PAN कार्ड</h3>
          <p>नए PAN आवेदन और सुधार की जानकारी।</p>
        </article>
        <article class="card">
          <div class="icon">🏦</div>
          <h3>बैंकिंग सेवाएँ</h3>
          <p>बैंक खाता, CSP और अधिकृत बैंकिंग सेवाओं की जानकारी।</p>
        </article>
        <article class="card">
          <div class="icon">📄</div>
          <h3>सरकारी प्रमाणपत्र</h3>
          <p>आय, जाति और निवास प्रमाणपत्र की जानकारी।</p>
        </article>
        <article class="card">
          <div class="icon">📱</div>
          <h3>मोबाइल रिचार्ज</h3>
          <p>मोबाइल और DTH रिचार्ज सेवाओं की जानकारी।</p>
        </article>
        <article class="card">
          <div class="icon">🏢</div>
          <h3>बिज़नेस सेवाएँ</h3>
          <p>GST, Udyam और व्यवसाय पंजीकरण की जानकारी।</p>
        </article>
        <article class="card">
          <div class="icon">👷</div>
          <h3>EPFO और पेंशन</h3>
          <p>PF, UAN और पेंशन संबंधी जानकारी।</p>
        </article>
        <article class="card">
          <div class="icon">🚌</div>
          <h3>यात्रा सेवाएँ</h3>
          <p>बस, ट्रेन और फ्लाइट बुकिंग की जानकारी।</p>
        </article>
        <article class="card">
          <div class="icon">🛡️</div>
          <h3>बीमा सेवाएँ</h3>
          <p>वाहन, स्वास्थ्य और जीवन बीमा की जानकारी।</p>
        </article>
      </div>
      <p id="empty" hidden>कोई सेवा नहीं मिली। दूसरा नाम खोजें।</p>
    </section>
  </main>

  <footer>
    <strong>Digital Seva Bharat</strong><br>
    सभी डिजिटल सेवाओं की जानकारी एक जगह।<br>
    © 2026 Digital Seva Bharat
  </footer>

  <script>
    const search = document.getElementById("search");
    const cards = [...document.querySelectorAll(".card")];
    const empty = document.getElementById("empty");

    search.addEventListener("input", () => {
      const query = search.value.toLowerCase().trim();
      let count = 0;

      cards.forEach(card => {
        const match = card.innerText.toLowerCase().includes(query);
        card.hidden = !match;
        if (match) count++;
      });

      empty.hidden = count !== 0;
    });
  </script>
</body>
</html>
