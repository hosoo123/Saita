# Saita
<!DOCTYPE html>
<html lang="mn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tyeekree Gaming & Shop</title>
  <style>
    /* -------------------- Basic Anime Style -------------------- */
    body {
      font-family: 'Comic Sans MS', sans-serif;
      background: linear-gradient(135deg, #f0c0ff, #a0c0ff);
      margin: 0;
      padding: 0;
    }
    header {
      background-color: rgba(255,255,255,0.8);
      padding: 20px;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
      border-bottom: 3px solid #ff69b4;
    }
    nav {
      display: flex;
      justify-content: center;
      background: rgba(255,255,255,0.6);
      padding: 10px 0;
      gap: 20px;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #ff69b4;
    }
    section {
      padding: 50px;
      text-align: center;
    }
    .shop-item {
      display: inline-block;
      background: rgba(255,255,255,0.7);
      margin: 20px;
      padding: 20px;
      border-radius: 15px;
      width: 200px;
      transition: 0.3s;
    }
    .shop-item:hover {
      transform: scale(1.05);
      border: 2px solid #ff69b4;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(255,255,255,0.8);
      border-top: 3px solid #ff69b4;
    }
    input, textarea {
      padding: 10px;
      width: 80%;
      margin: 10px 0;
      border-radius: 10px;
      border: 1px solid #ccc;
    }
    button {
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      background-color: #ff69b4;
      color: white;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background-color: #ff1493;
    }
  </style>
</head>
<body>

  <header>
    Tyeekree Gaming & Shop
  </header>

  <nav>
    <a href="#home">Нүүр</a>
    <a href="#shop">Дэлгүүр</a>
    <a href="#contact">Холбоо барих</a>
  </nav>

  <section id="home">
    <h2>Тоглоомын сувгаас Онлайн Дэлгүүр хүртэл</h2>
    <p>Anime стильтэй, хурдан, сонирхолтой вэбсайт. Манай шинэ тоглоомууд болон бараануудтай танилцана уу!</p>
  </section>

  <section id="shop">
    <h2>Онлайн Дэлгүүр</h2>
    <div class="shop-item">
      <h3>Тоглоом 1</h3>
      <p>Үнэ: 5000₮</p>
      <button>Захиалах</button>
    </div>
    <div class="shop-item">
      <h3>Тоглоом 2</h3>
      <p>Үнэ: 7000₮</p>
      <button>Захиалах</button>
    </div>
    <div class="shop-item">
      <h3>Мерч 1</h3>
      <p>Үнэ: 3000₮</p>
      <button>Захиалах</button>
    </div>
  </section>

  <section id="contact">
    <h2>Холбоо барих</h2>
    <form action="mailto:here-your-email@example.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Таны нэр" required><br>
      <input type="email" name="email" placeholder="Таны и-мэйл" required><br>
      <textarea name="message" rows="5" placeholder="Зурвас" required></textarea><br>
      <button type="submit">Илгээх</button>
    </form>
  </section>

  <footer>
    © 2025 Tyeekree Gaming & Shop
  </footer>

</body>
</html>
