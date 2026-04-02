<!DOCTYPE html>
<html lang="ky">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Байхан Кафе </title>
    <link rel="stylesheet" href="cafe.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Кафе "Байхан"</h1>
            <nav>
                <a href="#menu">Меню</a>
                <a href="#booking">Брондоо</a>
                <a href="#cart" id="cart-link">Себет (0)</a>
            </nav>
        </div>
    </header>

    <main class="container">
        <section id="menu">
            <h2>Биздин Меню</h2>
            <div class="menu-grid">
                <div class="menu-item">
                    <h3>Плов "Байхан"</h3>
                    <p>250 сом</p>
                    <button onclick="addToCart('Плов', 250)">Кошуу</button>
                </div>
                <div class="menu-item">
                    <h3>Манты (5 даана)</h3>
                    <p>200 сом</p>
                    <button onclick="addToCart('Манты', 200)">Кошуу</button>
                </div>
                <div class="menu-item">
                    <h3>Шашлык</h3>
                    <p>180 сом</p>
                    <button onclick="addToCart('Шашлык', 180)">Кошуу</button>
                </div>
            </div>
        </section>

        <section id="booking">
            <h2>Столду алдын ала ээлөө</h2>
            <form id="booking-form">
                <input type="text" placeholder="Атыңыз" required>
                <input type="datetime-local" required>
                <input type="number" placeholder="Адам саны" required>
                <button type="submit">Брондоо</button>
            </form>
        </section>
    </main>

    <script src="cafe.js"></script>
</body>
</html>
