<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>عالم السيارات</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      direction: rtl;
      text-align: center;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px 0;
    }

    h1 {
      margin: 0;
    }

    .car-section {
      padding: 30px;
    }

    .car {
      background-color: white;
      margin: 20px auto;
      padding: 20px;
      width: 90%;
      max-width: 600px;
      border-radius: 15px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .car img {
      width: 100%;
      border-radius: 10px;
    }

    button {
      background-color: #e74c3c;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      margin-top: 10px;
    }

    button:hover {
      background-color: #c0392b;
    }

    .about {
      margin: 40px auto;
      padding: 20px;
      background-color: white;
      width: 90%;
      max-width: 600px;
      border-radius: 15px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .about img {
      width: 250px;
      border-radius: 15px;
      margin-bottom: 15px;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      padding: 15px 0;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>موقع يوسف للسيارات</h1>
    <p>تعرف على أشهر السيارات في العالم</p>
  </header>

  <section class="car-section">
    <div class="car">
      <h2>تويوتا</h2>
      <img src="https://cdn.pixabay.com/photo/2020/04/14/20/55/toyota-5046840_1280.jpg" alt="تويوتا">
      <p>تويوتا من أكثر السيارات اعتمادية واقتصادية في العالم.</p>
      <button onclick="alert('تويوتا شركة يابانية تأسست سنة 1937')">اعرف المزيد</button>
    </div>

    <div class="car">
      <h2>مرسيدس</h2>
      <img src="https://cdn.pixabay.com/photo/2017/01/06/19/15/auto-1957037_1280.jpg" alt="مرسيدس">
      <p>مرسيدس تمثل قمة الفخامة والقوة في عالم السيارات الألمانية.</p>
      <button onclick="alert('مرسيدس تأسست في ألمانيا سنة 1926')">اعرف المزيد</button>
    </div>

    <div class="car">
      <h2>فورد</h2>
      <img src="https://cdn.pixabay.com/photo/2017/09/13/00/45/ford-2746814_1280.jpg" alt="فورد">
      <p>فورد رائدة في الصناعة الأمريكية، وتشتهر بسياراتها القوية.</p>
      <button onclick="alert('فورد تأسست في أمريكا سنة 1903')">اعرف المزيد</button>
    </div>
  </section>

  <div class="about">
    <h2>عنّي</h2>
    <img src="youssef.jpg" alt="صورة يوسف">
    <p>أنا يوسف، شاب مصري مهتم بتكنولوجيا السيارات وتصميم المواقع. ده أول موقع ليا باستخدام GitHub Pages!</p>
  </div>

  <footer>
    <p>© 2025 موقع يوسف للسيارات. جميع الحقوق محفوظة.</p>
  </footer>
</body>
</html>
