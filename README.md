<html lang="bg">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Handmade Store & Portfolio</title>
    <style>
        body { margin: 0; font-family: Arial, sans-serif; background: #f6f6f6; }
        header { background: #333; color: white; padding: 20px; text-align: center; }
        nav { display: flex; justify-content: center; gap: 20px; padding: 10px; background: #444; }
        nav a { color: white; text-decoration: none; font-weight: bold; }
        .section { padding: 40px 20px; max-width: 1200px; margin: auto; }
        .hero { background: url('https://picsum.photos/1600/500](https://gurushots.com/photo/d0cdae52cedf90b73c6c1f6d10690723') center/cover; color: white; padding: 120px 20px; text-align: center; }
        .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .card { background: white; border-radius: 10px; padding: 15px; box-shadow: 0 2px 6px rgba(0,0,0,0.15); }
        .card img { width: 100%; border-radius: 10px; }
        footer { background: #333; color: white; text-align: center; padding: 20px; margin-top: 40px; }
    </style>
</head>
<body>
    <header>
        <h1>Hand Made In Bulgaria</h1>
    </header>

    <nav>
        <a href="#home">Начало</a>
        <a href="#products">Магазин</a>
        <a href="#portfolio">Портфолио</a>
        <a href="#contact">Контакти</a>
    </nav>

    <section id="home" class="hero">
        <h2>Уникални ръчно изработени изделия</h2>
        <p>Създадени с внимание, вдъхновение и любов.</p>
    </section>

    <section id="products" class="section">
        <h2>Магазин</h2>
        <div class="products">
            <div class="card">
                <img src="https://picsum.photos/300" alt="product1" />
                <h3>Продукт 1</h3>
                <p>Кратко описание на продукта.</p>
                <strong>25.00 лв</strong>
            </div>
            <div class="card">
                <img src="https://picsum.photos/301" alt="product2" />
                <h3>Продукт 2</h3>
                <p>Кратко описание на продукта.</p>
                <strong>30.00 лв</strong>
            </div>
            <div class="card">
                <img src="https://picsum.photos/302" alt="product3" />
                <h3>Продукт 3</h3>
                <p>Кратко описание на продукта.</p>
                <strong>40.00 лв</strong>
            </div>
        </div>
    </section>

    <section id="portfolio" class="section">
        <h2>Портфолио</h2>
        <p>Добави тук галерия със свои проекти или снимки.</p>
        <div class="products">
            <img src="https://picsum.photos/400" class="card" />
            <img src="https://picsum.photos/401" class="card" />
            <img src="https://picsum.photos/402" class="card" />
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Контакти</h2>
        <p>Email: yourmail@example.com</p>
        <p>Instagram: @yourprofile</p>
    </section>

    <footer>
        <p>© 2025 Handmade Store & Portfolio</p>
    </footer>
</body>
</html>

