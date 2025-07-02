<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Олег и Екатерина | Свадьба 12.09.2025</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <style>
        @font-face {
            font-family: 'Ouvality Cyrillic';
            src: url('https://fonts.cdnfonts.com/css/ouvality') format('woff2');
            font-weight: normal;
            font-style: normal;
        }
        
        :root {
            --beige: #F5F5DC;
            --light-brown: #D2B48C;
            --transparent: rgba(255, 255, 255, 0.8);
            --pink: #FFC0CB;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Ouvality Cyrillic', 'Playfair Display', serif;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            background-color: var(--beige);
            color: #333;
            overflow-x: hidden;
        }
        
        section {
            min-height: 100vh;
            width: 100%;
            padding: 50px 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .names-section {
            background: linear-gradient(rgba(245, 245, 220, 0.8), rgba(245, 245, 220, 0.8)), 
                        url('https://disk.yandex.ru/a/RbXUmUlLc9tzTg') center/cover no-repeat;
        }
        
        .names-container {
            background-color: var(--transparent);
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            font-size: 4rem;
            margin-bottom: 20px;
            color: var(--light-brown);
        }
        
        .date {
            font-size: 2rem;
            color: #555;
        }
        
        .text-section {
            background-color: var(--beige);
            line-height: 1.8;
        }
        
        .text-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
            color: var(--light-brown);
        }
        
        p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        
        .photo-grid {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 40px 0;
            flex-wrap: wrap;
        }
        
        .photo-grid img {
            max-width: 300px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .calendar-section {
            background-color: var(--beige);
        }
        
        .calendar {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            max-width: 400px;
        }
        
        .calendar-header {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--light-brown);
        }
        
        .calendar-grid {
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            gap: 10px;
        }
        
        .calendar-day {
            padding: 10px;
            border-radius: 50%;
        }
        
        .wedding-day {
            background-color: var(--pink);
            color: white;
            font-weight: bold;
        }
        
        .location-section {
            background: linear-gradient(rgba(245, 245, 220, 0.8), rgba(245, 245, 220, 0.8)), 
                        url('https://disk.yandex.ru/a/RbXUmUlLc9tzTg') center/cover no-repeat;
        }
        
        .location-container {
            background-color: var(--transparent);
            padding: 40px;
            border-radius: 10px;
            max-width: 600px;
        }
        
        .signature {
            margin-top: 50px;
            font-size: 1.5rem;
            color: var(--light-brown);
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .date {
                font-size: 1.5rem;
            }
            
            h2 {
                font-size: 2rem;
            }
            
            .photo-grid img {
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Первый раздел с именами и датой -->
    <section class="names-section" id="names">
        <div class="names-container">
            <h1>Олег и Екатерина</h1>
            <div class="date">12 сентября 2025 г.</div>
        </div>
    </section>

    <!-- Второй раздел с текстом приглашения -->
    <section class="text-section" id="invitation">
        <div class="text-content">
            <h2>Дорогие гости!</h2>
            <p>Вы получили это сообщение, а значит, мы спешим поделиться с вами радостной новостью – у нас скоро свадьба!</p>
            <p>Мы приглашаем вас разделить с нами радость этого особенного события и стать частью нашей семейной истории.</p>
            <p>Ваше присутствие сделает наш день еще более значимым и незабываемым.</p>
            
            <h2>История любви</h2>
            <p>Наша история началась пять лет назад, когда мы встретились. С тех пор мы прошли вместе через множество приключений и счастливых моментов. Наши отношения развивались и крепли с каждым днём. Мы поддерживали друг друга в трудные времена и радовались общим победам.</p>
            
            <div class="photo-grid">
                <img src="https://disk.yandex.ru/a/RbXUmUlLc9tzTg" alt="Фото пары 1">
                <img src="https://disk.yandex.ru/a/RbXUmUlLc9tzTg" alt="Фото пары 2">
            </div>
            
            <p>С каждым годом наша любовь становилась всё сильнее, и теперь мы готовы сделать следующий шаг. Мы счастливы разделить этот особенный момент с вами и надеемся, что вы станете частью нашей дальнейшей истории.</p>
        </div>
    </section>

    <!-- Третий раздел с календарем -->
    <section class="calendar-section" id="calendar">
        <div class="calendar">
            <div class="calendar-header">Сентябрь 2025</div>
            <div class="calendar-grid">
                <div class="calendar-day">Пн</div>
                <div class="calendar-day">Вт</div>
                <div class="calendar-day">Ср</div>
                <div class="calendar-day">Чт</div>
                <div class="calendar-day">Пт</div>
                <div class="calendar-day">Сб</div>
                <div class="calendar-day">Вс</div>
                
                <!-- Дни недели (пример для сентября 2025) -->
                <div class="calendar-day">1</div>
                <div class="calendar-day">2</div>
                <div class="calendar-day">3</div>
                <div class="calendar-day">4</div>
                <div class="calendar-day">5</div>
                <div class="calendar-day">6</div>
                <div class="calendar-day">7</div>
                <div class="calendar-day">8</div>
                <div class="calendar-day">9</div>
                <div class="calendar-day">10</div>
                <div class="calendar-day">11</div>
                <div class="calendar-day wedding-day">12</div>
                <div class="calendar-day">13</div>
                <div class="calendar-day">14</div>
                <div class="calendar-day">15</div>
                <div class="calendar-day">16</div>
                <div class="calendar-day">17</div>
                <div class="calendar-day">18</div>
                <div class="calendar-day">19</div>
                <div class="calendar-day">20</div>
                <div class="calendar-day">21</div>
                <div class="calendar-day">22</div>
                <div class="calendar-day">23</div>
                <div class="calendar-day">24</div>
                <div class="calendar-day">25</div>
                <div class="calendar-day">26</div>
                <div class="calendar-day">27</div>
                <div class="calendar-day">28</div>
                <div class="calendar-day">29</div>
                <div class="calendar-day">30</div>
            </div>
        </div>
    </section>

    <!-- Четвертый раздел с местом проведения -->
    <section class="location-section" id="location">
        <div class="location-container">
            <h2>Место проведения</h2>
            <p>г. Смоленск, ул. Глинки, д. 4</p>
            
            <div class="signature">
                <p>Будем рады видеть вас на нашем празднике!</p>
                <p>Олег и Екатерина</p>
            </div>
        </div>
    </section>

    <script>
        // Плавная прокрутка между разделами
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Анимация появления элементов при скролле
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = 1;
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, { threshold: 0.1 });
        
        document.querySelectorAll('section').forEach(section => {
            section.style.opacity = 0;
            section.style.transform = 'translateY(20px)';
            section.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
            observer.observe(section);
        });
    </script>
</body>
</html>
