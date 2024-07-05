<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--     <title>Islombek Ravshanov - Portfolio</title> -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <header class="bg-dark text-white text-center py-5">
        <h1>Islombek Ravshanov</h1>
        <p class="lead">Backend Developer</p>
    </header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Portfolio</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">📝Maqsad</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">📂Loyihalar</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">📞Bog'lanish</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <section id="about" class="py-5">
        <div class="container">
            <h2 class="text-center">📝Maqsad</h2>
            <p class="lead text-center">"Yuqori sifatli web dasturlarni ishlab chiqishda yetakchi bo'ladigan jamoaning bir qismi bo'lish. Tajriba to'plash, dasturlashga oid xar qanday sohada o'zimni sinab ko'rish. O'z ishimni haqiqiy ustasiga aylanish, doyimiy o'rganish"</p>
            <h4>🏫Ta'lim</h4>
            <p>Najot ta’lim Pyton Django kursi bitiruvchisi | Online resurslar</p>
            <h4>💼Ko'nikmalar</h4>
            <ul>
                <li>Dasturlash tillari: JavaScripts, Python, Go</li>
                <li>API texnologiyalar: Django Rest Framework, FastApi</li>
                <li>Web texnologiyalar: HTML, CSS</li>
                <li>Back-end: Django</li>
                <li>Ma'lumotlar bazasi: SQLite, Postgresql, MySQL</li>
                <li>Telegram-bot: Aiogram, Telebot</li>
                <li>O'rganishda davom etmoqda: Go, Flask, FastAPI, Nodejs, Pentesting, PHP</li>
            </ul>
        </div>
    </section>
    <section id="projects" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">📂Loyihalar</h2>
            <div class="card-deck">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Social-app loyhasi</h5>
                        <p class="card-text"><strong>Maqsad:</strong> Instagramga o'xshash, post, comment, user-verify qismlariga ega loyiha yaratish</p>
                        <p class="card-text"><strong>Texnologiyalar:</strong> django, django rest-framework, simplejwt</p>
                        <p class="card-text"><strong>Rol:</strong> Backend developer</p>
                        <p class="card-text"><strong>Loyiha linki:</strong> <a href="https://github.com/gtrirf/userverify" class="btn btn-primary">GitHub</a></p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Chat-app loyhasi</h5>
                        <p class="card-text"><strong>Maqsad:</strong> real-time messenger yaratish</p>
                        <p class="card-text"><strong>Texnologiyalar:</strong> django, channels, websockets, Docker, html, css, javascirpts</p>
                        <p class="card-text"><strong>Rol:</strong> Full stack developer</p>
                        <p class="card-text"><strong>Loyiha linki:</strong> <a href="https://chatapp-1-zfhh.onrender.com/" class="btn btn-primary">Loyihani ko'rish</a></p>
                        <p class="card-text"><strong>GitHub:</strong> <a href="https://github.com/gtrirf/chatapp" class="btn btn-primary">GitHub</a></p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">delivery-app loyhasi</h5>
                        <p class="card-text"><strong>Maqsad:</strong> yetkazib berish xizmati loyihasi backendini ishlan chiqish</p>
                        <p class="card-text"><strong>Texnologiyalar:</strong> django, django, rest-framework, authtoken, simplejwt</p>
                        <p class="card-text"><strong>Rol:</strong> backend developer</p>
                        <p class="card-text"><strong>Loyiha linki:</strong> <a href="https://github.com/gtrirf/delivery-app" class="btn btn-primary">GitHub</a></p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">E-commerce Platforma</h5>
                        <p class="card-text"><strong>Maqsadi:</strong> Online do’kon yaratish</p>
                        <p class="card-text"><strong>Texnologiyalar:</strong> Django, Postgresql, html, css, javascripts</p>
                        <p class="card-text"><strong>Rol:</strong> Full Stack developer</p>
                        <p class="card-text"><strong>Loyiha linki:</strong> <a href="https://bazaaar-uz.onrender.com/" class="btn btn-primary">Loyihani ko'rish</a></p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Kutubxona loyihasi</h5>
                        <p class="card-text"><strong>Maqsad:</strong> Kutubxonaga obuna bo’lishni hamda kitobni ijaraga olishni raqamlashtirish.</p>
                        <p class="card-text"><strong>Texnologiyalar:</strong> Django, Postgresql, html, css, javascripts</p>
                        <p class="card-text"><strong>Rol:</strong> Full stack developer</p>
                        <p class="card-text"><strong>Loyiha linki:</strong></p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Blog-site loyihasi</h5>
                        <p class="card-text"><strong>Maqsad:</strong> Foydalanuvchilar, ya’ni barcha, Blog va Turli xil yangiliklar, maqolalar, yarata oladi</p>
                        <p class="card-text"><strong>Texnologiyalar:</strong> django, Posgresql, html, css, javascripts</p>
                        <p class="card-text"><strong>Rol:</strong> Full stack developer</p>
                        <p class="card-text"><strong>Loyiha linki:</strong> <a href="https://blogsite-new-edition.onrender.com/" class="btn btn-primary">Loyihani ko'rish</a></p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center">📞Bog'lanish</h2>
            <p class="text-center">Email: <a href="mailto:iravshanovpy@gmail.com">iravshanovpy@gmail.com</a></p>
            <p class="text-center">LinkedIn: <a href="https://www.linkedin.com/in/islombek-ravshanov-3042252b7/">Islombek Ravshanov</a></p>
            <p class="text-center">GitHub: <a href="https://github.com/gtrirf/">gtrirf</a></p>
            <p class="text-center">Telegram: <a href="https://t.me/horizon_blogs">Personal Telegram channel</a></p>
        </div>
    </section>
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 Islombek Ravshanov</p>
    </footer>
<!--     <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script> -->
<!--     <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script> -->
<!--     <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script> -->
</body>
</html>
