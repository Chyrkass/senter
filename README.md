<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Умняша - Детский центр подготовки к школе</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f7fe;
            color: #333;
        }
        
        header {
            background-color: #6a4c93;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        
        .logo {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
            color: #ffd166;
        }
        
        nav {
            background-color: #8a6cb4;
            padding: 10px 0;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        
        nav li {
            margin: 0 15px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        
        nav a:hover {
            background-color: #6a4c93;
        }
        
        .hero {
            background-image: url('https://via.placeholder.com/1200x400/6a4c93/ffffff?text=Добро+пожаловать+в+Умняшу');
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            position: relative;
        }
        
        .hero-overlay {
            background-color: rgba(106, 76, 147, 0.7);
            padding: 30px;
            border-radius: 10px;
        }
        
        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        
        .btn {
            display: inline-block;
            background-color: #ffd166;
            color: #333;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            transition: transform 0.3s;
        }
        
        .btn:hover {
            transform: scale(1.05);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .section-title {
            text-align: center;
            color: #6a4c93;
            margin-bottom: 40px;
            font-size: 2em;
        }
        
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-bottom: 40px;
        }
        
        .service-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            width: 30%;
            margin-bottom: 30px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-img {
            height: 200px;
            background-size: cover;
            background-position: center;
        }
        
        .service-content {
            padding: 20px;
        }
        
        .service-content h3 {
            color: #6a4c93;
            margin-top: 0;
        }
        
        .teachers {
            background-color: #e8f4f8;
            padding: 40px 0;
        }
        
        .teacher-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .teacher-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            width: 22%;
            margin: 1%;
            overflow: hidden;
            text-align: center;
            padding-bottom: 20px;
        }
        
        .teacher-photo {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .contact-form {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            max-width: 600px;
            margin: 0 auto;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        
        .form-group input, 
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
        }
        
        .form-group textarea {
            height: 100px;
        }
        
        footer {
            background-color: #6a4c93;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
        
        .social-icons {
            margin: 20px 0;
        }
        
        .social-icons a {
            color: white;
            margin: 0 10px;
            font-size: 1.5em;
        }
        
        @media (max-width: 768px) {
            .service-card, .teacher-card {
                width: 100%;
                margin-bottom: 20px;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Умняша</div>
        <p>Детский центр подготовки к школе</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">О нас</a></li>
            <li><a href="#services">Программы</a></li>
            <li><a href="#teachers">Педагоги</a></li>
            <li><a href="#schedule">Расписание</a></li>
            <li><a href="#contacts">Контакты</a></li>
        </ul>
    </nav>
    
    <section class="hero">
        <div class="hero-overlay">
            <h1>Подготовка к школе с радостью!</h1>
            <p>Комплексные развивающие занятия для детей 4-7 лет</p>
            <a href="#contacts" class="btn">Записаться на пробное занятие</a>
        </div>
    </section>
    
    <section id="about" class="container">
        <h2 class="section-title">О нашем центре</h2>
        <p>Центр "Умняша" - это место, где дети в игровой форме приобретают навыки, необходимые для успешного обучения в школе. Наши занятия развивают мышление, память, внимание, речь, мелкую моторику и социальные навыки.</p>
        <p>Мы работаем с 2010 года и помогли более 500 детям легко адаптироваться к школьной жизни. Наша методика сочетает лучшие традиции отечественной педагогики и современные развивающие технологии.</p>
    </section>
    
    <section id="services" class="container">
        <h2 class="section-title">Наши программы</h2>
        <div class="services">
            <div class="service-card">
                <div class="service-img" style="background-image: url('https://via.placeholder.com/400x200/ffd166/ffffff?text=АБВГДейка')"></div>
                <div class="service-content">
                    <h3>АБВГДейка (4-5 лет)</h3>
                    <p>Основы чтения, письма, счета в игровой форме. Развитие речи и расширение словарного запаса.</p>
                </div>
            </div>
            
            <div class="service-card">
                <div class="service-img" style="background-image: url('https://via.placeholder.com/400x200/06d6a0/ffffff?text=Почемучки')"></div>
                <div class="service-content">
                    <h3>Почемучки (5-6 лет)</h3>
                    <p>Углубленная подготовка: чтение, математика, логика, окружающий мир. Развитие познавательной активности.</p>
                </div>
            </div>
            
            <div class="service-card">
                <div class="service-img" style="background-image: url('https://via.placeholder.com/400x200/118ab2/ffffff?text=Будущий+первоклассник')"></div>
                <div class="service-content">
                    <h3>Будущий первоклассник (6-7 лет)</h3>
                    <p>Интенсивная подготовка к школе: чтение, письмо, математика, психологическая готовность.</p>
                </div>
            </div>
            
            <div class="service-card">
                <div class="service-img" style="background-image: url('https://via.placeholder.com/400x200/ef476f/ffffff?text=Творческая+мастерская')"></div>
                <div class="service-content">
                    <h3>Творческая мастерская</h3>
                    <p>Рисование, лепка, аппликация - развитие мелкой моторики, воображения и креативного мышления.</p>
                </div>
            </div>
            
            <div class="service-card">
                <div class="service-img" style="background-image: url('https://via.placeholder.com/400x200/073b4c/ffffff?text=Логика+и+мышление')"></div>
                <div class="service-content">
                    <h3>Логика и мышление</h3>
                    <p>Развитие логического мышления, внимания, памяти через занимательные игры и упражнения.</p>
                </div>
            </div>
            
            <div class="service-card">
                <div class="service-img" style="background-image: url('https://via.placeholder.com/400x200/6a4c93/ffffff?text=Английский+для+малышей')"></div>
                <div class="service-content">
                    <h3>Английский для малышей</h3>
                    <p>Игровое изучение английского языка с носителями и русскоязычными педагогами.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="teachers" class="teachers">
        <div class="container">
            <h2 class="section-title">Наши педагоги</h2>
            <div class="teacher-grid">
                <div class="teacher-card">
                    <img src="https://via.placeholder.com/300x300/6a4c93/ffffff?text=Ольга+Иванова" alt="Ольга Иванова" class="teacher-photo">
                    <h3>Ольга Иванова</h3>
                    <p>Педагог дошкольного образования, стаж 15 лет</p>
                </div>
                
                <div class="teacher-card">
                    <img src="https://via.placeholder.com/300x300/ffd166/ffffff?text=Анна+Петрова" alt="Анна Петрова" class="teacher-photo">
                    <h3>Анна Петрова</h3>
                    <p>Логопед-дефектолог, специалист по раннему развитию</p>
                </div>
                
                <div class="teacher-card">
                    <img src="https://via.placeholder.com/300x300/06d6a0/ffffff?text=Мария+Сидорова" alt="Мария Сидорова" class="teacher-photo">
                    <h3>Мария Сидорова</h3>
                    <p>Психолог, специалист по подготовке к школе</p>
                </div>
                
                <div class="teacher-card">
                    <img src="https://via.placeholder.com/300x300/118ab2/ffffff?text=Джон+Смит" alt="Джон Смит" class="teacher-photo">
                    <h3>Джон Смит</h3>
                    <p>Преподаватель английского языка, носитель</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="schedule" class="container">
        <h2 class="section-title">Расписание занятий</h2>
        <div style="overflow-x: auto;">
            <table style="width: 100%; border-collapse: collapse; margin: 0 auto;">
                <thead>
                    <tr style="background-color: #6a4c93; color: white;">
                        <th style="padding: 10px; text-align: left;">Группа</th>
                        <th style="padding: 10px; text-align: left;">Дни</th>
                        <th style="padding: 10px; text-align: left;">Время</th>
                    </tr>
                </thead>
                <tbody>
                    <tr style="border-bottom: 1px solid #ddd;">
                        <td style="padding: 10px;">АБВГДейка (4-5 лет)</td>
                        <td style="padding: 10px;">Пн, Ср</td>
                        <td style="padding: 10px;">10:00 - 11:30</td>
                    </tr>
                    <tr style="border-bottom: 1px solid #ddd;">
                        <td style="padding: 10px;">Почемучки (5-6 лет)</td>
                        <td style="padding: 10px;">Вт, Чт</td>
                        <td style="padding: 10px;">10:00 - 12:00</td>
                    </tr>
                    <tr style="border-bottom: 1px solid #ddd;">
                        <td style="padding: 10px;">Будущий первоклассник (6-7 лет)</td>
                        <td style="padding: 10px;">Пн, Ср, Пт</td>
                        <td style="padding: 10px;">17:00 - 18:30</td>
                    </tr>
                    <tr style="border-bottom: 1px solid #ddd;">
                        <td style="padding: 10px;">Творческая мастерская</td>
                        <td style="padding: 10px;">Сб</td>
                        <td style="padding: 10px;">11:00 - 12:30</td>
                    </tr>
                    <tr style="border-bottom: 1px solid #ddd;">
                        <td style="padding: 10px;">Английский для малышей</td>
                        <td style="padding: 10px;">Вт, Чт</td>
                        <td style="padding: 10px;">16:00 - 17:00</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>
    
    <section id="contacts" class="container">
        <h2 class="section-title">Записаться на занятие</h2>
        <div class="contact-form">
            <form>
                <div class="form-group">
                    <label for="name">Имя ребенка</label>
                    <input type="text" id="name" required>
                </div>
                
                <div class="form-group">
                    <label for="age">Возраст</label>
                    <input type="number" id="age" min="3" max="7" required>
                </div>
                
                <div class="form-group">
                    <label for="parent">Имя родителя</label>
                    <input type="text" id="parent" required>
                </div>
                
                <div class="form-group">
                    <label for="phone">Телефон</label>
                    <input type="tel" id="phone" required>
                </div>
                
                <div class="form-group">
                    <label for="program">Интересующая программа</label>
                    <select id="program" style="width: 100%; padding: 10px; border: 1px solid #ddd; border-radius: 5px;">
                        <option value="">Выберите программу</option>
                        <option value="abvgd">АБВГДейка (4-5 лет)</option>
                        <option value="pochemuchki">Почемучки (5-6 лет)</option>
                        <option value="first-grade">Будущий первоклассник (6-7 лет)</option>
                        <option value="art">Творческая мастерская</option>
                        <option value="english">Английский для малышей</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="message">Дополнительная информация</label>
                    <textarea id="message"></textarea>
                </div>
                
                <button type="submit" class="btn" style="border: none; cursor: pointer;">Отправить заявку</button>
            </form>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <div class="logo" style="font-size: 2em;">Умняша</div>
            <p>Детский центр подготовки к школе</p>
            
            <div class="social-icons">
                <a href="#"><i class="fab fa-vk"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-whatsapp"></i></a>
            </div>
            
            <p>Адрес: г. Москва, ул. Детская, д. 5</p>
            <p>Телефон: +7 (123) 456-78-90</p>
            <p>Email: info@umnysha-center.ru</p>
            
            <p>&copy; 2023 Центр "Умняша". Все права защищены.</p>
        </div>
    </footer>
    
    <!-- Font Awesome для иконок -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
