<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>متجري البسيط</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f2f2f2;
      color: #333;
    }
    header {
      background: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #00b894;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h2 {
      font-size: 18px;
      margin: 10px 0;
    }
    .product p {
      color: #666;
      margin: 5px 0 15px;
    }
    .buy-button {
      background: #00b894;
      color: white;
      padding: 10px 15px;
      text-decoration: none;
      border-radius: 5px;
      transition: 0.3s;
      display: inline-block;
    }
    .buy-button:hover {
      background: #019875;
    }
    footer {
      background: #222;
      color: #bbb;
      text-align: center;
      padding: 15px;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>متجر أشرف</h1>
  <p>أفضل المنتجات الرقمية بأسعار مناسبة</p>
</header>

<section class="products">

  <div class="product">
    <img src="https://via.placeholder.com/300x200.png?text=منتج+1" alt="منتج 1">
    <h2>منتج رقم 1</h2>
    <p>سعر: 10 دولار</p>
    <a href="https://wa.me/201234567890" class="buy-button" target="_blank">اطلب الآن</a>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/300x200.png?text=منتج+2" alt="منتج 2">
    <h2>منتج رقم 2</h2>
    <p>سعر: 15 دولار</p>
    <a href="https://wa.me/201234567890" class="buy-button" target="_blank">اطلب الآن</a>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/300x200.png?text=منتج+3" alt="منتج 3">
    <h2>منتج رقم 3</h2>
    <p>سعر: 5 دولار</p>
    <a href="https://t.me/yourusername" class="buy-button" target="_blank">تواصل تيليجرام</a>
  </div>

</section>

<footer>
  &copy; 2025 - متجر أشرف | جميع الحقوق محفوظة
</footer>

</body>
</html>
