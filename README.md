<!DOCTYPE html><html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Дом для отдыха в Котайке</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header, footer { background: #4a90e2; color: white; text-align: center; padding: 1rem; }
    .lang-switch { margin-top: 10px; }
    .content { padding: 2rem; max-width: 800px; margin: auto; }
    .gallery img { width: 100%; max-width: 300px; margin: 10px; }
    .contact { font-weight: bold; }
    .hidden { display: none; }
    nav { text-align: center; margin: 1rem 0; }
    nav a { margin: 0 10px; text-decoration: none; color: #4a90e2; font-weight: bold; }
  </style>
</head>
<body>
  <header>
    <h1 id="title">Дом для отдыха в Котайке</h1>
    <div class="lang-switch">
      <button onclick="setLang('ru')">Рус</button>
      <button onclick="setLang('hy')">Հայ</button>
      <button onclick="setLang('en')">Eng</button>
    </div>
  </header>  <div class="content">
    <nav>
      <a href="#about">О доме</a>
      <a href="#gallery">Галерея</a>
      <a href="#pricing">Цены</a>
      <a href="#contact">Контакты</a>
    </nav><section id="about">
  <h2 class="t" data-ru="О доме" data-hy="Տան մասին" data-en="About the house"></h2>
  <p class="t" data-ru="3 комнаты, 2 спальни. Есть бассейн, Wi-Fi, кухня, всё необходимое для комфортного отдыха."
     data-hy="3 սենյակ, 2 ննջասենյակ։ Կա լողավազան, Wi-Fi, խոհանոց, ամեն ինչ հարմարավետ հանգստի համար։"
     data-en="3 rooms, 2 bedrooms. Includes pool, Wi-Fi, kitchen — everything for a comfortable stay."></p>
  <p><strong class="t" data-ru="Адрес:" data-hy="Հասցե:" data-en="Address:"></strong> Котайк, Гетамеч 4/2/6</p>
</section>

<section id="gallery">
  <h2 class="t" data-ru="Галерея" data-hy="Պատկերասրահ" data-en="Gallery"></h2>
  <p class="t" data-ru="Фотографии будут добавлены скоро." data-hy="Լուսանկարները շուտով կավելացվեն։" data-en="Photos will be added soon."></p>
  <div class="gallery"></div>
</section>

<section id="pricing">
  <h2 class="t" data-ru="Цены и условия" data-hy="Գներ եւ պայմաններ" data-en="Prices & Conditions"></h2>
  <p class="t" data-ru="80,000 драм за сутки." data-hy="80,000 դրամ մեկ օրվա համար։" data-en="80,000 AMD per night."></p>
</section>

<section id="contact">
  <h2 class="t" data-ru="Контакты" data-hy="Կապ" data-en="Contact"></h2>
  <p class="contact">+374 93 010903</p>
</section>

  </div>  <footer>
    <p>&copy; 2025 Дом для отдыха</p>
  </footer>  <script>
    function setLang(lang) {
      document.querySelectorAll('.t').forEach(el => {
        el.innerText = el.dataset[lang];
      });
    }
    // Установить язык по умолчанию
    setLang('ru');
  </script></body>
</html>
