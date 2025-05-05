# zhang-latin-school
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Школа Латинских танцев Чжан</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- 导航栏 -->
    <nav>
        <div class="container">
            <h1>Школа Латинских танцев Чжан</h1>
            <ul>
                <li><a href="index.html">Главная</a></li>
                <li><a href="about.html">Об Schule</a></li>
                <li><a href="teachers.html">Преподаватели</a></li>
                <li><a href="registration.html">Записаться</a></li>
                <li><a href="quiz.html">Тест знаний</a></li>
                <li><a href="additional.html">Дополнительно</a></li>
                <li><a href="contact.html">Контакты</a></li>
                <li><a href="portfolio.html">Давайте познакомимся</a></li>
            </ul>
        </div>
    </nav>

    <!-- 主内容 -->
    <main class="container">
        <section class="hero">
            <h2>Вступайте в мир латинских танцев!</h2>
            <p>Для детей и взрослых, начинающих и продвинутых</p>
            <a href="registration.html" class="button">Записаться на пробный урок</a>
        </section>
    </main>

    <!-- 页脚 -->
    <footer>
        <p>© 2025 школа Латинских танцев Чжан. Все права защищены.</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

nav {
    background: #ff4757; /* 红色主题色 */
    color: white;
    padding: 20px;
}

nav .container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: 500;
}

main .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 40px 20px;
}

.hero {
    text-align: center;
    padding: 80px 20px;
    background: linear-gradient(135deg, #ff4757 25%, #ff6b81 100%);
    color: white;
    border-radius: 15px;
    margin-top: 40px;
}

.button {
    display: inline-block;
    padding: 15px 30px;
    background: white;
    color: #ff4757;
    text-decoration: none;
    border-radius: 25px;
    font-weight: bold;
    margin-top: 20px;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 30px;
    margin-top: 40px;
}<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Контакты - школа Латинских танцев Чжан</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- 导航栏（同主页） -->
    <nav>
        <!-- 复制主页导航代码 -->
    </nav>

    <main class="container">
        <h2>Свяжитесь с нами</h2>
        <div class="contact-info">
            <p><strong>Адрес:</strong> г. Шанхай, ул. ДANCEWAY, 55</p>
            <p><strong>телефон:</strong> +86 10-1234-5678</p>
            <p><strong>email:</strong> zhang.latin.school@gmail.com</p>
            
            <!-- 虚构地图（用Yandex地图模拟） -->
            <iframe 
                src="https://yandex.ru/map-widget/v1/?um=constructor:1234567890" 
                width="100%" 
                height="400" 
                frameborder="0"
            ></iframe>
        </div>

        <h3>Информация о разработчике:</h3>
        <p>
            ФИО: Чжан Эрбо<br>
            Группа: 研2024-舞蹈学01班<br>
            Институт: Национальный университет искусств и культуры
        </p>
    </main>

    <!-- 页脚（同主页） -->
</body>
</html>
