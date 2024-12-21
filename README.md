<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Город Фруктов</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;500&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #ffffff, #add8e6, #dda0dd);
        }
        header {
            background: linear-gradient(to bottom, #ffffff, #add8e6);
            color: #333;
            padding: 3em 0;
            text-align: center;
            border-bottom: 5px solid #add8e6;
        }
        header h1 {
            font-size: 2.5em;
            color: #4a148c;
            margin-top: 20px;
            display: inline-block;
            padding: 0.5em 1em;
            border-radius: 10px;
            background: rgba(173, 216, 230, 0.5);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
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
        .hidden-table {
            visibility: hidden;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
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
            <h2 class="section-title">About</h2>
            <p>"Город Фруктов" - это компания, которая предлагает широкий ассортимент свежих фруктов высочайшего качества. Мы заботимся о том, чтобы каждый клиент получил только самые вкусные и натуральные продукты. Наша миссия - сделать ваш день ярче и вкуснее!</p>
        </section>
        <section id="fruits" class="hidden-table">
            <h2 class="section-title">Популярные фрукты</h2>
            <table>
                <thead>
                    <tr>
                        <th>Фрукт</th>
                        <th>Фотография</th>
                        <th>Примерная цена за кг (₽)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Яблоки</td>
                        <td><img src="ae104298-a4ac-5e79-aa4b-d8a1b194f529.jpg" alt="Яблоки" class="fruit-image"></td>
                        <td>150</td>
                    </tr>
                    <tr>
                        <td>Бананы</td>
                        <td><img src="i.jpg" alt="Бананы" class="fruit-image"></td>
                        <td>120</td>
                    </tr>
                    <tr>
                        <td>Апельсины</td>
                        <td><img src="0v6wrf8a3worxnvgm5f7waoze5l2c5rh.jpg" alt="Апельсины" class="fruit-image"></td>
                        <td>200</td>
                    </tr>
                    <tr>
                        <td>Виноград</td>
                        <td><img src="maxresdefault.jpg" alt="Виноград" class="fruit-image"></td>
                        <td>300</td>
                    </tr>
                    <tr>
                        <td>Клубника</td>
                        <td><img src="2d8852313d8480c.jpg" alt="Клубника" class="fruit-image"></td>
                        <td>450</td>
                    </tr>
                </tbody>
            </table>
        </section>
        <section id="contact">
            <h2 class="section-title">Contact</h2>
            <p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 <a href="https://gorodfructov.ru" target="_blank">gorodfructov.ru</a>. Все права защищены.</p>
    </footer>
</body>
</html>
