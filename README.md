<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Вкусная кухня - Кулинарные рецепты</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <i class="fas fa-utensils"></i>
                <h1>Вкусная кухня</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Главная</a></li>
                    <li><a href="#recipes">Рецепты</a></li>
                    <li><a href="#gallery">Галерея</a></li>
                    <li><a href="#about">О нас</a></li>
                    <li><a href="#contact">Контакты</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="home" class="hero">
        <div class="container">
            <h2>Добро пожаловать на наш кулинарный сайт!</h2>
            <p>Откройте для себя лучшие рецепты со всего мира</p>
            <a href="#recipes" class="btn">Посмотреть рецепты</a>
        </div>
    </section>
    <section id="recipes" class="recipes">
        <div class="container">
            <h2>Популярные рецепты</h2>
            <div class="recipe-grid">
                <div class="recipe-card">
                    <img src="images/pasta.jpg" alt="Паста Карбонара">
                    <h3>Паста Карбонара</h3>
                    <p>Классический итальянский рецепт с беконом и сыром</p>
                    <a href="#" class="btn">Читать рецепт</a>
                </div>
                <div class="recipe-card">
                    <img src="images/salad.jpg" alt="Греческий салат">
                    <h3>Греческий салат</h3>
                    <p>Свежий и полезный салат с фетой и оливками</p>
                    <a href="#" class="btn">Читать рецепт</a>
                </div>
                <div class="recipe-card">
                    <img src="images/dessert.jpg" alt="Тирамису">
                    <h3>Тирамису</h3>
                    <p>Нежный итальянский десерт с кофейным вкусом</p>
                    <a href="#" class="btn">Читать рецепт</a>
                </div>
            </div>
        </div>
    </section>
    <section id="gallery" class="gallery">
        <div class="container">
            <h2>Наша галерея</h2>
            <div class="gallery-grid">
                <div class="gallery-item"><img src="images/gallery1.jpg" alt="Блюдо 1"></div>
                <div class="gallery-item"><img src="images/gallery2.jpg" alt="Блюдо 2"></div>
                <div class="gallery-item"><img src="images/gallery3.jpg" alt="Блюдо 3"></div>
                <div class="gallery-item"><img src="images/gallery4.jpg" alt="Блюдо 4"></div>
                <div class="gallery-item"><img src="images/gallery5.jpg" alt="Блюдо 5"></div>
                <div class="gallery-item"><img src="images/gallery6.jpg" alt="Блюдо 6"></div>
            </div>
        </div>
    </section>
    <section id="about" class="about">
        <div class="container">
            <h2>О нашей кухне</h2>
            <p>Мы собираем лучшие рецепты со всего мира и адаптируем их для домашнего приготовления. Наша миссия - сделать кулинарию доступной и увлекательной для всех.</p>
            <div class="features">
                <div class="feature">
                    <i class="fas fa-clock"></i>
                    <h3>Быстрые рецепты</h3>
                    <p>Рецепты на 15-30 минут для занятых людей</p>
                </div>
                <div class="feature">
                    <i class="fas fa-heart"></i>
                    <h3>Полезное питание</h3>
                    <p>Здоровые и сбалансированные блюда</p>
                </div>
                <div class="feature">
                    <i class="fas fa-globe"></i>
                    <h3>Международная кухня</h3>
                    <p>Рецепты из разных стран мира</p>
                </div>
            </div>
        </div>
    </section>
    <section id="contact" class="contact">
        <div class="container">
            <h2>Свяжитесь с нами</h2>
            <form id="contact-form">
                <div class="form-group">
                    <input type="text" placeholder="Ваше имя" required>
                </div>
                <div class="form-group">
                    <input type="email" placeholder="Ваш email" required>
                </div>
                <div class="form-group">
                    <textarea placeholder="Ваше сообщение" required></textarea>
                </div>
                <button type="submit" class="btn">Отправить</button>
            </form>
        </div>
    </section>
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Вкусная кухня</h3>
                    <p>Лучшие рецепты для вашего стола</p>
                </div>
                <div class="footer-section">
                    <h3>Контакты</h3>
                    <p><i class="fas fa-envelope"></i> info@vkusnayakuhnya.ru</p>
                    <p><i class="fas fa-phone"></i> +7 (123) 456-78-90</p>
                </div>
                <div class="footer-section">
                    <h3>Соцсети</h3>
                    <div class="social-icons">
                        <a href="#"><i class="fab fa-vk"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>&copy; 2025 Вкусная кухня. Все права защищены.</p>
        </div>
    </footer>
    <script src="js/script.js"></script>
</body>
</html>
/* Основные стили */
:root {
    --primary-color: #ff6b6b;
    --secondary-color: #ff8e8e;
    --dark-color: #333;
    --light-color: #f4f4f4;
    --white: #fff;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: var(--dark-color);
    background-color: var(--light-color);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.btn {
    display: inline-block;
    background: var(--primary-color);
    color: var(--white);
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    text-decoration: none;
    font-size: 16px;
    transition: all 0.3s ease;
}

.btn:hover {
    background: var(--secondary-color);
    transform: translateY(-3px);
}

/* Шапка */
header {
    background: var(--white);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 20px;
}

.logo {
    display: flex;
    align-items: center;
}

.logo i {
    font-size: 2rem;
    color: var(--primary-color);
    margin-right: 10px;
}

.logo h1 {
    font-size: 1.5rem;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 30px;
}

nav ul li a {
    text-decoration: none;
    color: var(--dark-color);
    font-weight: 500;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: var(--primary-color);
}

/* Герой секция */
.hero {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('../images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    align-items: center;
    text-align: center;
    color: var(--white);
    margin-top: 60px;
}

.hero h2 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

/* Секция с рецептами */
.recipes {
    padding: 80px 0;
}

.recipes h2 {
    text-align: center;
    margin-bottom: 50px;
    font-size: 2.5rem;
    color: var(--primary-color);
}

.recipe-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.recipe-card {
    background: var(--white);
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.recipe-card:hover {
    transform: translateY(-10px);
}

.recipe-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.recipe-card h3 {
    padding: 15px 20px 5px;
    font-size: 1.3rem;
}

.recipe-card p {
    padding: 0 20px 15px;
    color: #666;
}

.recipe-card .btn {
    margin: 0 20px 20px;
    display: block;
    text-align: center;
}

/* Галерея */
.gallery {
    padding: 80px 0;
    background: var(--white);
}

.gallery h2 {
    text-align: center;
    margin-bottom: 50px;
    font-size: 2.5rem;
    color: var(--primary-color);
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.gallery-item {
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    height: 250px;
}

.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s;
}

.gallery-item:hover img {
    transform: scale(1.1);
}

/* О нас */
.about {
    padding: 80px 0;
}

.about h2 {
    text-align: center;
    margin-bottom: 30px;
    font-size: 2.5rem;
    color: var(--primary-color);
}

.about p {
    max-width: 800px;
    margin: 0 auto 50px;
    text-align: center;
    font-size: 1.1rem;
    line-height: 1.8;
}

.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.feature {
    text-align: center;
    padding: 30px;
    background: var(--white);
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
}

.feature i {
    font-size: 3rem;
    color: var(--primary-color);
    margin-bottom: 20px;
}

.feature h3 {
    margin-bottom: 15px;
    font-size: 1.3rem;
}

/* Контакты */
.contact {
    padding: 80px 0;
    background: var(--white);
}

.contact h2 {
    text-align: center;
    margin-bottom: 50px;
    font-size: 2.5rem;
    color: var(--primary-color);
}

#contact-form {
    max-width: 600px;
    margin: 0 auto;
    padding: 30px;
    background: var(--light-color);
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
}

.form-group {
    margin-bottom: 20px;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 16px;
}

.form-group textarea {
    height: 150px;
    resize: vertical;
}

/* Подвал */
footer {
    background: var(--dark-color);
    color: var(--white);
    padding: 50px 0 0;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin-bottom: 30px;
}

.footer-section h3 {
    font-size: 1.3rem;
    margin-bottom: 20px;
    color: var(--primary-color);
}

.footer-section p {
    margin-bottom: 10px;
}

.footer-section i {
    margin-right: 10px;
    color: var(--primary-color);
}

.social-icons {
    display: flex;
    gap: 15px;
}

.social-icons a {
    color: var(--white);
    font-size: 1.5rem;
    transition: color 0.3s;
}

.social-icons a:hover {
    color: var(--primary-color);
}

.copyright {
    text-align: center;
    padding: 20px 0;
    background: rgba(0, 0, 0, 0.2);
    font-size: 0.9rem;
}

/* Адаптивность */
@media (max-width: 768px) {
    header .container {
        flex-direction: column;
        padding: 15px;
    }

    .logo {
        margin-bottom: 15px;
    }

    nav ul {
        flex-direction: column;
        align-items: center;
    }

    nav ul li {
        margin: 5px 0;
    }

    .hero h2 {
        font-size: 2rem;
    }

    .hero p {
        font-size: 1rem;
    }
}
