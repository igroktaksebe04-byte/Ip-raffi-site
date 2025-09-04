<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IP RAFFI — Сварные изделия</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #333;
    }
    header {
      background-color: #2e7d32;
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 24px;
    }
    header a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      margin-left: 15px;
    }
    .banner {
      background: url('https://images.unsplash.com/photo-1581091870632-2d63f3c91d3f?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    .banner h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    .banner p {
      font-size: 20px;
      margin-bottom: 30px;
    }
    .banner a {
      background-color: #43a047;
      color: white;
      padding: 15px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
    .catalog {
      padding: 50px 20px;
      text-align: center;
    }
    .catalog h3 {
      font-size: 28px;
      margin-bottom: 40px;
      color: #2e7d32;
    }
    .items {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .item {
      border: 1px solid #ddd;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .item img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
    }
    .advantages {
      background-color: #f4f4f4;
      padding: 50px 20px;
      text-align: center;
    }
    .advantages h3 {
      font-size: 28px;
      margin-bottom: 30px;
      color: #2e7d32;
    }
    .adv-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .adv {
      padding: 20px;
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #2e7d32;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>IP RAFFI</h1>
    <nav>
      <a href="#catalog">Каталог</a>
      <a href="#contacts">Контакты</a>
      <a href="https://wa.me/7707366311" target="_blank">WhatsApp</a>
    </nav>
  </header>

  <section class="banner">
    <h2>Металлическая мебель и сварные изделия</h2>
    <p>Столы, стулья, кровати и многое другое под заказ в Шымкенте</p>
    <a href="https://wa.me/7707366311" target="_blank">Заказать в WhatsApp</a>
  </section>

  <section class="catalog" id="catalog">
    <h3>Наша продукция</h3>
    <div class="items">
      <div class="item">
        <img src="https://images.unsplash.com/photo-1616627573543-4b77faf7a1f1?auto=format&fit=crop&w=600&q=80" alt="Стол">
        <h4>Столы</h4>
        <p>Прочные и стильные металлические столы для дома и бизнеса.</p>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1604328698692-6d6a44d3d1d2?auto=format&fit=crop&w=600&q=80" alt="Стул">
        <h4>Стулья</h4>
        <p>Удобные и долговечные стулья из металла с современным дизайном.</p>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1623716024762-5e0d7e48b1d5?auto=format&fit=crop&w=600&q=80" alt="Кровать">
        <h4>Кровати</h4>
        <p>Металлические кровати на заказ — надёжность и комфорт.</p>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1600566753376-12d87f63c7a4?auto=format&fit=crop&w=600&q=80" alt="Индивидуальный заказ">
        <h4>Индивидуальные заказы</h4>
        <p>Изготавливаем любые сварные изделия по вашим чертежам и идеям.</p>
      </div>
    </div>
  </section>

  <section class="advantages">
    <h3>Почему выбирают нас</h3>
    <div class="adv-grid">
      <div class="adv">Качество и прочность</div>
      <div class="adv">Индивидуальные размеры</div>
      <div class="adv">Доступные цены</div>
      <div class="adv">Быстрая доставка</div>
    </div>
  </section>

  <footer id="contacts">
    <p>Свяжитесь с нами: <br>
      WhatsApp: <a href="https://wa.me/7707366311" target="_blank" style="color:white;">+7 707 366 311</a><br>
      Телефон: +7 778 103 9073
    </p>
    <p>© IP RAFFI, 2025</p>
  </footer>

</body>
</html>
