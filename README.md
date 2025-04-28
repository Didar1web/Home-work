# Home-work
Home work
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Моя страница</title>

    <style>
        /* Стили для ссылки "Перейти к основному содержанию" */
        .skip-link {
            position: absolute;
            left: -999px;
            top: auto;
            width: 1px;
            height: 1px;
            overflow: hidden;
        }
        .skip-link:focus {
            position: static;
            width: auto;
            height: auto;
            background: #000;
            color: #fff;
            padding: 10px;
            z-index: 1000;
        }

        /* nav с inline-block и шириной 80% */
        nav {
            display: inline-block;
            width: 80%;
        }

        /* Стилизовать изображения внутри nav */
        nav img {
            width: 10%;
        }

        /* Закомментированный стиль li */
        /*
        li {
            list-style: none;
        }
        */

        /* Сетка для класса grid */
        .grid {
            display: grid;
            grid-template-columns: 40% 40%;
            justify-content: space-around;
            align-items: center;
            row-gap: 20px;
        }

        /* Только изображения внутри grid */
        .grid img {
            width: 100%;
        }

        /* Сетка для класса flex */
        .flex {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        /* Цвета для контраста */
        body {
            background-color: #ffffff;
            color: #222222;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav li {
            display: inline-block;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            background-color: #f0f0f0;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<a href="#main" class="skip-link">Перейти к основному содержанию</a>

<nav>
    <img src="logo.png" alt="Логотип">
    <ul>
        <li><a href="index.html">Главная</a></li>
        <li><a href="about.html">О нас</a></li>
        <li><a href="parks.html">Парки</a></li>
    </ul>
</nav>

<main id="main">
    <h1>Добро пожаловать на наш сайт!</h1>

    <section class="grid">
        <img src="image1.jpg" alt="Изображение 1">
        <img src="image2.jpg" alt="Изображение 2">
    </section>

    <section class="flex">
        <img src="image3.jpg" alt="Изображение 3">
        <img src="image4.jpg" alt="Изображение 4">
        <img src="image5.jpg" alt="Изображение 5">
    </section>
</main>

<footer>
    <p>Все права защищены © 2025</p>
</footer>

</body>
</html>

