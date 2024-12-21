# gorod-fructov
HTML сайт для Города Фруктов
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
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1em 0;
            text-align: center;
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
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        table {
            margin: 0 auto;
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
            <p>Это главная страница вашего сайта. Настройте её по своему желанию!</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>Здесь вы можете разместить информацию о себе или о проекте.</p>
        </section>
        <section id="fruits">
            <h2>Популярные фрукты и цены</h2>
            <table>
                <thead>
                    <tr>
                        <th>Фрукт</th>
                        <th>Примерная цена за кг (₽)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Яблоки</td>
                        <td>150</td>
                    </tr>
                    <tr>
                        <td>Бананы</td>
                        <td>120</td>
                    </tr>
                    <tr>
                        <td>Апельсины</td>
                        <td>200</td>
                    </tr>
                    <tr>
                        <td>Виноград</td>
                        <td>300</td>
                    </tr>
                    <tr>
                        <td>Клубника</td>
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
