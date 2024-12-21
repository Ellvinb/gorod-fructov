<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Город Фруктов</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #ffffff, #add8e6, #dda0dd);
        }
        header {
            background: linear-gradient(to right, #ffffff, #add8e6);
            color: #4a148c;
            text-align: center;
            padding: 2em 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 3em;
            font-weight: 600;
            background: linear-gradient(to right, #dda0dd, #add8e6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 0.5em 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1em;
            font-weight: 500;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 2em;
            text-align: center;
        }
        .section-title {
            font-size: 2em;
            color: #4a148c;
            margin-bottom: 1em;
        }
        .fruit-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5em;
            padding: 2em;
        }
        .fruit-item {
            background: rgba(173, 216, 230, 0.3);
            padding: 1em;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .fruit-item img {
            width: 100px;
            height: 100px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 1em;
        }
        .fruit-item h3 {
            margin: 0.5em 0;
            font-size: 1.2em;
            color: #333;
        }
        .fruit-item p {
            margin: 0;
            color: #666;
            font-size: 1em;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            margin-top: 2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Город Фруктов</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="home">
            <h2 class="section-title">Добро пожаловать в Город Фруктов</h2>
            <p>Добро пожаловать в "Город Фруктов" - ваш идеальный выбор для свежих и сочных фруктов каждый день!</p>
        </section>
        <section id="about">
            <h2 class="section-title">О нас</h2>
            <p>"Город Фруктов" - это компания, которая предлагает широкий ассортимент свежих фруктов высочайшего качества. Мы заботимся о том, чтобы каждый клиент получил только самые вкусные и натуральные продукты. Наша миссия - сделать ваш день ярче и вкуснее!</p>
        </section>
        <section id="fruits">
            <h2 class="section-title">Популярные фрукты</h2>
            <div class="fruit-grid">
                <div class="fruit-item">
                    <img src="ae104298-a4ac-5e79-aa4b-d8a1b194f529.jpg" alt="Яблоки">
                    <h3>Яблоки</h3>
                    <p>150 ₽/кг</p>
                </div>
                <div class="fruit-item">
                    <img src="i.jpg" alt="Бананы">
                    <h3>Бананы</h3>
                    <p>120 ₽/кг</p>
                </div>
                <div class="fruit-item">
                    <img src="0v6wrf8a3worxnvgm5f7waoze5l2c5rh.jpg" alt="Апельсины">
                    <h3>Апельсины</h3>
                    <p>200 ₽/кг</p>
                </div>
                <div class="fruit-item">
                    <img src="maxresdefault.jpg" alt="Виноград">
                    <h3>Виноград</h3>
                    <p>300 ₽/кг</p>
                </div>
                <div class="fruit-item">
                    <img src="2d8852313d8480c.jpg" alt="Клубника">
                    <h3>Клубника</h3>
                    <p>450 ₽/кг</p>
                </div>
            </div>
        </section>
        <section id="contact">
            <h2 class="section-title">Контакты</h2>
            <p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 <a href="https://gorodfructov.ru" target="_blank">gorodfructov.ru</a>. Все права защищены.</p>
    </footer>
</body>
</html>
