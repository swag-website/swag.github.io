<!DOCTYPE html>
<html lang="mn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SWAG — Таны стиль, Таны дүр төрх</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; background: #f7f7f7; }
        header { background: black; color: white; padding: 20px; text-align: center; font-size: 24px; font-weight: bold; }
        nav { background: #222; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-size: 18px; }
        .hero { padding: 40px; text-align: center; }
        .btn { background: black; color: white; padding: 12px 24px; border-radius: 8px; text-decoration: none; font-size: 18px; }
        .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 20px; }
        .card { background: white; padding: 15px; border-radius: 10px; }
        .card img { width: 100%; border-radius: 10px; }
        footer { background: #111; color: white; padding: 20px; text-align: center; margin-top: 40px; }
    </style>
</head>
<body>

<header>SWAG</header>

<nav>
    <a href="index.html">Home</a>
    <a href="products.html">Бүтээгдэхүүн</a>
    <a href="contact.html">Холбоо барих</a>
</nav>

<section class="hero">
    <h1>Таны стиль, Таны дүр төрх</h1>
    <p>Шинэ загварууд • Өдөр тутмын хямдрал • Түргэн хүргэлт</p>
    <a class="btn" href="products.html">Бүх бүтээгдэхүүн</a>
</section>

<section class="products">
    <div class="card">
        <img src="https://placehold.co/300x300?text=Hoodie" alt="">
        <h3>SWAG Black Crown Hoodie</h3>
        <p>Үнэ: 89,000₮</p>
        <a class="btn" href="contact.html">Захиалах</a>
    </div>

    <div class="card">
        <img src="https://placehold.co/300x300?text=Tee" alt="">
        <h3>SWAG Logo Tee</h3>
        <p>Үнэ: 29,000₮</p>
        <a class="btn" href="contact.html">Захиалах</a>
    </div>
</section>

<footer>© 2025 SWAG — All rights reserved.</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="mn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SWAG — Бүтээгдэхүүн</title>
    <style>
        body { font-family: Arial; background: #f7f7f7; margin: 0; }
        header { background: black; color: white; padding: 20px; text-align: center; font-size: 24px; }
        nav { background: #222; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-size: 18px; }
        .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 20px; }
        .card { background: white; padding: 15px; border-radius: 10px; }
        .card img { width: 100%; border-radius: 10px; }
        .btn { background: black; color: white; padding: 10px; text-decoration: none; display: block; text-align: center; border-radius: 6px; }
    </style>
</head>
<body>

<header>SWAG — Бүтээгдэхүүн</header>

<nav>
    <a href="index.html">Home</a>
    <a href="products.html">Product</a>
    <a href="contact.html">Contact</a>
</nav>

<section class="products">
    <div class="card">
        <img src="https://placehold.co/300x300?text=Hoodie">
        <h3>Black Crown Hoodie</h3>
        <p>Үнэ: 89,000₮</p>
        <a class="btn" href="contact.html">Захиалах</a>
    </div>

    <div class="card">
        <img src="https://placehold.co/300x300?text=Tee">
        <h3>SWAG Logo Tee</h3>
        <p>Үнэ: 29,000₮</p>
        <a class="btn" href="contact.html">Захиалах</a>
    </div>
</section>

</body>
</html>
<!DOCTYPE html>
<html lang="mn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SWAG — Захиалга</title>
    <style>
        body { font-family: Arial; background: #f7f7f7; margin: 0; padding: 20px; }
        header { background: black; color: white; padding: 20px; text-align: center; font-size: 24px; }
        .box { background: white; padding: 20px; border-radius: 8px; max-width: 500px; margin: auto; }
        .qr { width: 100%; margin-top: 20px; border-radius: 12px; }
        .field { margin-bottom: 15px; }
        input, textarea { width: 100%; padding: 10px; border-radius: 8px; border: 1px solid #ccc; }
        button { padding: 12px; width: 100%; background: black; color: white; border-radius: 8px; font-size: 18px; }
    </style>
</head>
<body>

<header>SWAG — Захиалга</header>

<div class="box">
    <h3>Захиалга өгөх</h3>

    <div class="field">
        <input type="text" placeholder="Нэр">
    </div>
    <div class="field">
        <input type="text" placeholder="Утасны дугаар">
    </div>
    <div class="field">
        <textarea rows="5" placeholder="Ямар бүтээгдэхүүн захиалах вэ?"></textarea>
    </div>

    <button>Захиалга илгээх (FREE)</button>

    <h3>Төлбөр хийх (QR)</h3>
    <img class="qr" src="https://placehold.co/350x350?text=Your+QR" alt="">
</div>

</body>
</html>
