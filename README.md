<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Город Фруктов</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #ffffff, #add8e6, #dda0dd);
        }
        header {
            background-color: #ffffff;
            color: #333;
            padding: 2em 0;
            text-align: center;
            border-bottom: 5px solid #add8e6;
        }
        header h1 {
            background-color: rgba(200, 200, 255, 0.8);
            display: inline-block;
            padding: 0.5em 1em;
            border-radius: 10px;
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
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        table {
            margin: 2em auto;
            border-collapse: collapse;
            width: 80%;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #f4f4f4;
        }
        .fruit-image {
            width: 100px;
            height: 100px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать в Город Фруктов</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>Добро пожаловать в "Город Фруктов" - ваш идеальный выбор для свежих и сочных фруктов каждый день!</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>"Город Фруктов" - это компания, которая предлагает широкий ассортимент свежих фруктов высочайшего качества. Мы заботимся о том, чтобы каждый клиент получил только самые вкусные и натуральные продукты. Наша миссия - сделать ваш день ярче и вкуснее!</p>
        </section>
        <section id="fruits">
            <h2>Популярные фрукты и цены</h2>
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
                        <td><img src="maxresdefault.jpg.jpg" alt="Виноград" class="fruit-image"></td>
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
            <h2>Contact</h2>
            <p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 <a href="https://gorodfructov.ru" target="_blank">gorodfructov.ru</a>. Все права защищены.</p>
    </footer>
</body>
</html>
