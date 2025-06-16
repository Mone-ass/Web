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
