<!DOCTYPE html>
<html lang="mk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Авто Перална</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eaf5ff;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #0073e6;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #005bb5;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #4fa3e4;
            color: white;
        }
        .container {
            padding: 20px;
        }
        h2 {
            color: #005bb5;
        }
        .services, .contact {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .service, .contact-info {
            background-color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            flex: 1;
            min-width: 250px;
        }
        .service img {
            width: 100%;
            border-radius: 8px;
        }
        .contact-info img {
            width: 50px;
            margin-right: 10px;
        }
        .contact-info {
            display: flex;
            align-items: center;
        }
    </style>
</head>
<body>

    <header>
        <h1>Добредојдовте на нашата Авто Перална!</h1>
    </header>

    <nav>
        <a href="#services">Услуги</a>
        <a href="#contact">Контакт</a>
    </nav>

    <div class="container">
        <section id="services">
            <h2>Наши Услуги</h2>
            <div class="services">
                <div class="service">
                    <img src="https://via.placeholder.com/500x300/0073e6/ffffff?text=%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%BE+%D0%A7%D0%B8%D1%81%D1%82%D0%B5%D1%9A%D0%B5" alt="Основно Чистење">
                    <h3>Основно Чистење</h3>
                    <p>Основно перење на вашето возило, вклучувајќи екстериерно и интериерно чистење.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/500x300/0073e6/ffffff?text=%D0%9F%D1%80%D0%B5%D0%BA%D1%83%D0%BC%D0%B5%D1%80%D0%BD%D0%BE+%D0%A7%D0%B8%D1%81%D1%82%D0%B5%D1%9A%D0%B5" alt="Прекумерно Чистење">
                    <h3>Прекумерно Чистење</h3>
                    <p>Професионално чистење на вашето возило со детали на сите површини.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/500x300/0073e6/ffffff?text=%D0%9F%D0%BE%D0%BB%D0%B8%D1%80%D0%B0%D1%9A%D0%B5" alt="Полирање">
                    <h3>Полирање</h3>
                    <p>Полирање на каросеријата за да го вратите сјајот и да го заштитите вашиот автомобил.</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Контактирајте Не</h2>
            <div class="contact">
                <div class="contact-info">
                    <img src="https://via.placeholder.com/50/0073e6/ffffff?text=%D0%90" alt="Адреса">
                    <div>
                        <h3>Адреса:</h3>
                        <p>Улица на Перална 1, Виница</p>
                    </div>
                </div>
                <div class="contact-info">
                    <img src="https://via.placeholder.com/50/0073e6/ffffff?text=%D0%A2" alt="Телефон">
                    <div>
                        <h3>Телефон:</h3>
                        <p>+389 70 000 000</p>
                    </div>
                </div>
            </div>

            <div class="contact-info">
                <img src="https://via.placeholder.com/50/0073e6/ffffff?text=%D0%A7" alt="Работно Време">
                <div>
                    <h3>Работно Време:</h3>
                    <p>Понеделник - Петок: 08:00 - 18:00</p>
                    <p>Сабота: 09:00 - 14:00</p>
                    <p>Недела: Затворено</p>
                </div>
            </div>
        </section>
    </div>

</body>
</html>
