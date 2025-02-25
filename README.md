<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин Телефонів</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Магазин Телефонів</h1>
        <nav>
            <ul>
                <li><a href="#">Головна</a></li>
                <li><a href="#">Телефони</a></li>
                <li><a href="#">Контакти</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="products">
            <h2>Наші Телефони</h2>
            <div class="product">
                <img src="phone1.jpg" alt="Телефон 1">
                <h3>Телефон 1</h3>
                <p>Опис телефону. Ціна: 10000 грн</p>
                <button class="add-to-cart">Додати в кошик</button>
            </div>
            <div class="product">
                <img src="phone2.jpg" alt="Телефон 2">
                <h3>Телефон 2</h3>
                <p>Опис телефону. Ціна: 12000 грн</p>
                <button class="add-to-cart">Додати в кошик</button>
            </div>
            <div class="product">
                <img src="phone3.jpg" alt="Телефон 3">
                <h3>Телефон 3</h3>
                <p>Опис телефону. Ціна: 15000 грн</p>
                <button class="add-to-cart">Додати в кошик</button>
            </div>
        </section>

        <section class="cart">
            <h2>Ваш Кошик</h2>
            <ul id="cart-items">
                <!-- Товари в кошику будуть додаватися сюди -->
            </ul>
            <button id="checkout-btn">Оформити замовлення</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Магазин Телефонів</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
