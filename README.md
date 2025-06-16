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
/* Современный минималистичный стиль */
:root {
  --primary: #2a2a2a;       /* Основной цвет текста */
  --secondary: #5c5c5c;     /* Вторичный текст */
  --accent: #e63946;        /* Акцентный цвет */
  --light: #f8f9fa;         /* Светлый фон */
  --white: #ffffff;         /* Чистый белый */
  --border: #e0e0e0;        /* Цвет границ */
  --shadow: 0 4px 12px rgba(0, 0, 0, 0.05); /* Тень */
}

/* Базовая сброс стилей */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
  line-height: 1.6;
  color: var(--primary);
  background-color: var(--white);
  -webkit-font-smoothing: antialiased;
}

.container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 24px;
}

/* Типографика */
h1, h2, h3, h4 {
  font-weight: 700;
  line-height: 1.2;
  margin-bottom: 1rem;
}

h1 { font-size: 2.5rem; }
h2 { font-size: 2rem; }
h3 { font-size: 1.5rem; }

p {
  margin-bottom: 1.25rem;
  color: var(--secondary);
}

/* Кнопки */
.btn {
  display: inline-block;
  padding: 12px 24px;
  background-color: var(--accent);
  color: var(--white);
  border: none;
  border-radius: 4px;
  font-weight: 500;
  text-decoration: none;
  cursor: pointer;
  transition: all 0.3s ease;
}

.btn:hover {
  background-color: #c1121f;
  transform: translateY(-2px);
}

.btn-outline {
  background: transparent;
  border: 1px solid var(--accent);
  color: var(--accent);
}

.btn-outline:hover {
  background: var(--accent);
  color: var(--white);
}

/* Шапка */
header {
  position: fixed;
  top: 0;
  width: 100%;
  background-color: var(--white);
  box-shadow: var(--shadow);
  z-index: 1000;
  padding: 16px 0;
}

.header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  display: flex;
  align-items: center;
  gap: 12px;
  text-decoration: none;
}

.logo i {
  font-size: 1.5rem;
  color: var(--accent);
}

.logo h1 {
  font-size: 1.25rem;
  margin: 0;
  color: var(--primary);
}

nav ul {
  display: flex;
  list-style: none;
  gap: 24px;
}

nav a {
  text-decoration: none;
  color: var(--secondary);
  font-weight: 500;
  transition: color 0.3s;
  position: relative;
}

nav a:hover {
  color: var(--accent);
}

nav a::after {
  content: '';
  position: absolute;
  bottom: -4px;
  left: 0;
  width: 0;
  height: 2px;
  background-color: var(--accent);
  transition: width 0.3s;
}

nav a:hover::after {
  width: 100%;
}

/* Герой секция */
.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  padding: 120px 0 80px;
  background-color: var(--light);
}

.hero-content {
  max-width: 600px;
}

.hero h2 {
  font-size: 3rem;
  margin-bottom: 24px;
  color: var(--primary);
}

.hero p {
  font-size: 1.25rem;
  margin-bottom: 32px;
  color: var(--secondary);
}

/* Секции */
.section {
  padding: 80px 0;
}

.section-title {
  text-align: center;
  margin-bottom: 48px;
}

.section-title h2 {
  position: relative;
  display: inline-block;
}

.section-title h2::after {
  content: '';
  position: absolute;
  bottom: -12px;
  left: 50%;
  transform: translateX(-50%);
  width: 80px;
  height: 3px;
  background-color: var(--accent);
}

/* Карточки рецептов */
.recipe-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 32px;
}

.recipe-card {
  background: var(--white);
  border-radius: 8px;
  overflow: hidden;
  box-shadow: var(--shadow);
  transition: transform 0.3s, box-shadow 0.3s;
}

.recipe-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.1);
}

.recipe-img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.recipe-content {
  padding: 24px;
}

.recipe-content h3 {
  margin-bottom: 12px;
}

.recipe-meta {
  display: flex;
  justify-content: space-between;
  margin-top: 16px;
  font-size: 0.875rem;
  color: var(--secondary);
}

/* Галерея */
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 24px;
}

.gallery-item {
  height: 250px;
  overflow: hidden;
  border-radius: 8px;
}

.gallery-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s;
}

.gallery-item:hover img {
  transform: scale(1.05);
}

/* О нас */
.about-content {
  max-width: 800px;
  margin: 0 auto;
  text-align: center;
}

.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 32px;
  margin-top: 48px;
}

.feature {
  text-align: center;
  padding: 32px;
}

.feature i {
  font-size: 2.5rem;
  color: var(--accent);
  margin-bottom: 16px;
}

/* Контакты */
.contact-form {
  max-width: 600px;
  margin: 0 auto;
  padding: 40px;
  background: var(--white);
  border-radius: 8px;
  box-shadow: var(--shadow);
}

.form-group {
  margin-bottom: 24px;
}

.form-group label {
  display: block;
  margin-bottom: 8px;
  font-weight: 500;
}

.form-control {
  width: 100%;
  padding: 12px 16px;
  border: 1px solid var(--border);
  border-radius: 4px;
  font-size: 1rem;
  transition: border 0.3s;
}

.form-control:focus {
  outline: none;
  border-color: var(--accent);
}

textarea.form-control {
  min-height: 150px;
  resize: vertical;
}

/* Подвал */
footer {
  background-color: var(--primary);
  color: var(--white);
  padding: 60px 0 0;
}

.footer-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 40px;
  margin-bottom: 40px;
}

.footer-logo {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 16px;
}

.footer-logo i {
  font-size: 1.5rem;
  color: var(--accent);
}

.footer-logo h3 {
  font-size: 1.25rem;
  margin: 0;
  color: var(--white);
}

.footer-about p {
  color: rgba(255, 255, 255, 0.7);
}

.footer-links h4,
.footer-contact h4 {
  color: var(--white);
  margin-bottom: 24px;
  font-size: 1.125rem;
}

.footer-links ul {
  list-style: none;
}

.footer-links li {
  margin-bottom: 12px;
}

.footer-links a {
  color: rgba(255, 255, 255, 0.7);
  text-decoration: none;
  transition: color 0.3s;
}

.footer-links a:hover {
  color: var(--accent);
}

.contact-info {
  display: flex;
  align-items: center;
  margin-bottom: 16px;
  color: rgba(255, 255, 255, 0.7);
}

.contact-info i {
  margin-right: 12px;
  color: var(--accent);
}

.social-links {
  display: flex;
  gap: 16px;
  margin-top: 24px;
}

.social-links a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background-color: rgba(255, 255, 255, 0.1);
  color: var(--white);
  transition: all 0.3s;
}

.social-links a:hover {
  background-color: var(--accent);
  transform: translateY(-3px);
}

.copyright {
  padding: 24px 0;
  text-align: center;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  color: rgba(255, 255, 255, 0.5);
  font-size: 0.875rem;
}

/* Анимации */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.animate {
  animation: fadeIn 0.6s ease forwards;
}

/* Адаптивность */
@media (max-width: 768px) {
  .header-container {
    flex-direction: column;
    gap: 16px;
  }
  
  nav ul {
    gap: 16px;
  }
  
  .hero h2 {
    font-size: 2.25rem;
  }
  
  .section {
    padding: 60px 0;
  }
  
  .recipe-grid,
  .gallery-grid {
    grid-template-columns: 1fr;
  }
}
