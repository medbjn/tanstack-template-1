/casino-project
│
├── index.html         ← Landing Page
├── login.html         ← صفحة تسجيل الدخول
├── register.html      ← صفحة إنشاء حساب
├── style.css          ← التنسيق العام
├── /games
│   └── slot.html       ← لعبة Slot بسيطة
├── /php
│   ├── register.php
│   ├── login.php
│   └── db.php
└── /assets
    └── images, logos, إلخ

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Casino Royale</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>🎰 Casino Royale</h1>
    <p>أهلاً بك في عالم الربح والتشويق! جرب ألعاب الكازينو الأونلاين الآن.</p>
    <a href="register.html" class="btn">إنشاء حساب</a>
    <a href="login.html" class="btn">تسجيل الدخول</a>
  </header>

  <section class="features">
    <h2>ألعابنا</h2>
    <ul>
      <li>🎰 Slot Machine</li>
      <li>🎲 Dice</li>
      <li>🃏 Blackjack</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Casino Royale - جميع الحقوق محفوظة</p>
  </footer>

</body>
</html>
body {
  font-family: 'Tahoma', sans-serif;
  margin: 0;
  padding: 0;
  background: #111;
  color: white;
  text-align: center;
}

header {
  padding: 60px 20px;
  background-color: #000;
}

h1 {
  color: gold;
  font-size: 48px;
}

.btn {
  display: inline-block;
  margin: 10px;
  padding: 15px 25px;
  background: gold;
  color: black;
  text-decoration: none;
  border-radius: 8px;
  transition: background 0.3s;
}

.btn:hover {
  background: #d4af37;
}

.features {
  margin: 40px 20px;
}

footer {
  padding: 20px;
  font-size: 14px;
  color: #888;
  background-color: #000;
}
