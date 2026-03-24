<!DOCTYPE html>

<html class="dark" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>F1 CAPITAL — Стратегическое управление трофейными активами</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&amp;family=Inter:wght@300;400;500&amp;family=Newsreader:ital,wght@0,400;0,700;1,400&amp;family=Material+Symbols+Outlined:wght@100..700&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-secondary-container": "#b6b5b4",
              "primary-fixed": "#dae5e0",
              "surface-container-highest": "#2d3734",
              "error": "#ffb4ab",
              "primary-fixed-dim": "#bec9c4",
              "surface-container-lowest": "#07100d",
              "error-container": "#93000a",
              "surface-container-high": "#222c29",
              "on-primary-fixed-variant": "#3e4945",
              "surface-container": "#18221f",
              "on-primary-fixed": "#141e1b",
              "tertiary-container": "#2e1f00",
              "on-surface-variant": "#c3c8c5",
              "surface-container-low": "#141e1b",
              "on-error-container": "#ffdad6",
              "secondary-container": "#474746",
              "inverse-primary": "#56615d",
              "surface-bright": "#313b38",
              "surface": "#0b1513",
              "on-primary-container": "#818c87",
              "on-tertiary-fixed": "#261900",
              "secondary-fixed": "#e4e2e1",
              "outline-variant": "#434846",
              "secondary": "#c8c6c5",
              "on-secondary": "#303030",
              "on-tertiary-container": "#c5a059",
              "on-surface": "#dae5e0",
              "primary-container": "#1a2421",
              "background": "#0b1513",
              "tertiary-fixed": "#ffdea5",
              "on-background": "#dae5e0",
              "primary": "#bec9c4",
              "outline": "#8d928f",
              "surface-tint": "#bec9c4",
              "inverse-surface": "#dae5e0",
              "tertiary": "#c5a059",
              "secondary-fixed-dim": "#c8c6c5",
              "inverse-on-surface": "#28332f",
              "on-tertiary-fixed-variant": "#5d4201",
              "on-secondary-fixed": "#1b1c1c",
              "tertiary-fixed-dim": "#c5a059",
              "on-error": "#690005",
              "on-tertiary": "#412d00",
              "on-secondary-fixed-variant": "#474746",
              "surface-variant": "#2d3734",
              "surface-dim": "#0b1513",
              "on-primary": "#28332f"
            },
            fontFamily: {
              "headline": ["Cinzel", "serif"],
              "editorial": ["Newsreader", "serif"],
              "body": ["Inter", "sans-serif"],
              "label": ["Inter", "sans-serif"]
            },
            borderRadius: {"DEFAULT": "0px", "lg": "0px", "xl": "0px", "full": "9999px"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        body {
            background-color: #0b1513;
            color: #dae5e0;
            overflow-x: hidden;
        }
        .luxury-gradient {
            background: linear-gradient(180deg, #1a2421 0%, #07100d 100%);
        }
        .glass-panel {
            background: rgba(45, 55, 52, 0.4);
            backdrop-filter: blur(40px);
        }
    </style>
</head>
<body class="font-body selection:bg-tertiary selection:text-on-tertiary">
<!-- TopNavBar (Shared Component Identity) -->
<nav class="bg-[#0b1513] transition-colors duration-500 docked full-width top-0 z-50 fixed w-full">
<div class="flex justify-between items-center w-full px-12 py-8 max-w-[1920px] mx-auto">
<div class="font-['Cinzel'] text-2xl tracking-[0.2em] text-[#c5a059]">F1 CAPITAL</div>
<div class="hidden md:flex items-center space-x-12">
<a class="text-[#c5a059] border-b border-[#c5a059]/30 pb-1 font-body text-sm uppercase tracking-widest" href="#">Экспертиза</a>
<a class="text-[#dae5e0] opacity-80 hover:text-[#c5a059] transition-all duration-300 font-body text-sm uppercase tracking-widest" href="#">Активы</a>
<a class="text-[#dae5e0] opacity-80 hover:text-[#c5a059] transition-all duration-300 font-body text-sm uppercase tracking-widest" href="#">Философия</a>
<a class="text-[#dae5e0] opacity-80 hover:text-[#c5a059] transition-all duration-300 font-body text-sm uppercase tracking-widest" href="#">Контакты</a>
</div>
<div class="flex items-center gap-8">
<button class="text-[#bec9c4] text-sm font-light tracking-tight hover:text-[#c5a059] transition-colors duration-300">Закрытый вход</button>
<div class="w-10 h-10 bg-surface-container-highest flex items-center justify-center">
<span class="material-symbols-outlined text-primary text-xl">account_circle</span>
</div>
</div>
</div>
</nav>
<!-- HERO SECTION -->
<header class="relative min-h-screen flex flex-col justify-center luxury-gradient overflow-hidden">
<div class="absolute inset-0 opacity-60">
<img alt="Modern basalt trophy estate at dusk" class="w-full h-full object-cover" data-alt="Cinematic wide shot of a modern ultra-premium basalt architectural masterpiece trophy estate in a moody misty atmosphere at dusk with warm interior lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD98H7eM-T_Kx_Jp_Jv3v7z_6P7Q5m_7y8i_R1u2_S3p4q5r6t7u8v9w0x1y2z3a4b5c6d7e8f9g0h1i2j3k4l5m6n7o8p9q0r1s2t3u4v5w6x7y8z9a0b1c2d3e4f5g6h7i8j9k0l1m2n3o4p5q6r7s8t9u0v1w2x3y4z5a6b7c8d9e0f1g2h3i4j5k6l7m8n9o0p1q2r3s4t5u6v7w8x9y0z1a2b3c4d5e6f7g8h9i0"/>
</div>
<div class="absolute inset-0 bg-black/30"></div>
<div class="relative z-10 px-12 md:px-24 max-w-[1440px]">
<div class="mb-12">
<span class="font-editorial italic text-tertiary text-xl tracking-wide">F1 Capital Management</span>
<h1 class="font-headline text-5xl md:text-8xl leading-tight mt-6 tracking-[0.05em] uppercase text-on-surface max-w-6xl">
                F1 CAPITAL: <span class="text-tertiary">Стратегическое управление</span> <br/> трофейными активами
            </h1>
</div>
<div class="flex flex-col md:flex-row items-start md:items-end gap-16">
<div class="max-w-xl">
<p class="font-body text-xl font-light leading-relaxed text-on-surface-variant mb-10">
                    Консолидация эксклюзивных земельных массивов и сопровождение закрытых инвестиционных сделок высшего порядка. 
                </p>
<button class="bg-tertiary text-on-tertiary px-12 py-6 font-headline text-lg tracking-widest hover:bg-opacity-90 transition-all duration-500">
                    [ ИЗУЧИТЬ РЕЕСТР ОБЪЕКТОВ ]
                </button>
</div>
<div class="border-l border-outline-variant pl-8 mb-4">
<p class="font-editorial italic text-3xl text-on-surface mb-2">70%</p>
<p class="font-body text-xs uppercase tracking-[0.2em] text-on-surface-variant">сделок проходят без публичного экспонирования</p>
</div>
</div>
</div>
<div class="absolute bottom-12 left-12 flex items-center gap-4 animate-bounce">
<span class="material-symbols-outlined text-tertiary">expand_more</span>
<span class="font-body text-xs uppercase tracking-widest text-outline">листайте вниз</span>
</div>
</header>
<!-- FOUNDER & EXPERTISE -->
<section class="py-32 bg-surface">
<div class="px-12 md:px-24 max-w-[1920px] mx-auto">
<div class="grid grid-cols-1 lg:grid-cols-12 gap-24 items-start">
<div class="lg:col-span-5">
<div class="sticky top-40">
<h2 class="font-headline text-4xl md:text-6xl mb-12 tracking-wide uppercase">Экспертиза <br/>и приватность</h2>
<div class="w-full aspect-[4/5] bg-surface-container-low overflow-hidden">
<img alt="Basalt architectural texture" class="w-full h-full object-cover grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-1000" data-alt="Macro close-up of dark grey basalt stone with precise architectural lines showcasing brutalist luxury textures" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBi1RLr3Q0X13rH9y3iWt5RQtWOgEnkp43q9yiQRUbCQIRpO25OhXWznP9TxWzZbwi9Jv0Ix5eUH4iEp8Wk_Nmq9BYoAoVc6KDA9qB8btwgBKWiJJjuHG8FucE2O2_z18xeH8TI58D5dpcFWq1xqMSGADo0iACDAAjKiqgC8vGzOrUfB_kpyfKzPPd--jKu2LXlJKl4BCBHRwU1nzvWSzJbZLWsEjdMPDtiMladZpwyKdy4b-NPnrRGa6bI-Cf1MpxV4tMrty1BfCs"/>
</div>
</div>
</div>
<div class="lg:col-span-7 space-y-32 pt-24">
<!-- Expertise Item 1 -->
<div class="max-w-xl">
<span class="text-tertiary font-editorial text-2xl">01</span>
<h3 class="font-headline text-2xl uppercase tracking-widest mt-4 mb-6">Land Development</h3>
<p class="font-body text-on-surface-variant leading-relaxed text-lg">
                        Профессиональное развитие земельных территорий: от изменения ВРИ до создания архитектурных концепций мирового уровня. Мы превращаем ландшафты в наследие.
                    </p>
</div>
<!-- Expertise Item 2 -->
<div class="max-w-xl ml-auto">
<span class="text-tertiary font-editorial text-2xl">02</span>
<h3 class="font-headline text-2xl uppercase tracking-widest mt-4 mb-6">Investment Arbitrage</h3>
<p class="font-body text-on-surface-variant leading-relaxed text-lg">
                        Поиск и капитализация скрытых возможностей на рынке недвижимости. Арбитраж стоимости через глубокий аудит и стратегическую реструктуризацию активов.
                    </p>
</div>
<!-- Expertise Item 3 -->
<div class="max-w-xl">
<span class="text-tertiary font-editorial text-2xl">03</span>
<h3 class="font-headline text-2xl uppercase tracking-widest mt-4 mb-6">Legal Security</h3>
<p class="font-body text-on-surface-variant leading-relaxed text-lg">
                        Безупречная юридическая чистота. Мы обеспечиваем полную анонимность и защиту интересов UHNW-клиентов в самых сложных транзакционных сценариях.
                    </p>
</div>
</div>
</div>
</div>
</section>
<!-- ASSET SHOWCASE -->
<section class="py-32 bg-surface-container-low">
<div class="px-12 md:px-24 max-w-[1920px] mx-auto">
<div class="flex flex-col md:flex-row justify-between items-end mb-24 gap-8">
<div>
<span class="font-body text-xs uppercase tracking-[0.3em] text-tertiary mb-4 block">Selected Portfolio</span>
<h2 class="font-headline text-4xl md:text-6xl uppercase tracking-wide">Реестр активов</h2>
</div>
<div class="text-right">
<p class="font-editorial italic text-2xl text-on-surface-variant">Текущие предложения</p>
</div>
</div>
<!-- Bento-style Showcase -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<!-- Main Featured Asset -->
<div class="group relative overflow-hidden bg-surface-container-highest flex flex-col h-full">
<div class="aspect-[16/9] overflow-hidden">
<img alt="Luxury Estate" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-1000" data-alt="Ultra-modern brutalist concrete villa set in a dark evergreen forest during twilight with soft warm interior lighting reflecting on architectural lines" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBBc1TJtK5Qx4aRML6jTHv_ARJp33KpO0OiNU0ZoqItI-kbfcF2FGnEUkpyqXskG7-qEm6M9Gb1FenTQu1YeR4Xg0qM35nTJqfDYtxOl2Vn8qG6Y32r-vZ2-b3oM_U6ksuOiVTRnyM1UsG_ZJgQz3Gk4Ds1BbqvQ21TXB79WbzQPSxB0GrHlZTDEyVeYilnQTYDrZJyq26UonoxZMAqhr6CezHhwD9LEGk1UvvFGpiZgID1UsoSOCp6yN4PGczer0H0M7w3KFKTp3c"/>
</div>
<div class="p-12 flex-grow">
<div class="flex justify-between items-start mb-8">
<div>
<h4 class="font-headline text-3xl uppercase mb-2">Объект Akulinino</h4>
<p class="font-editorial italic text-on-surface-variant text-xl">Подмосковье, Элитный кластер</p>
</div>
<span class="border border-tertiary/40 text-tertiary px-4 py-1 text-[10px] uppercase tracking-widest">[ OFF-MARKET ]</span>
</div>
<div class="grid grid-cols-2 gap-12 mb-12">
<div>
<p class="text-[10px] uppercase tracking-[0.2em] text-outline mb-2">Площадь массива</p>
<p class="font-headline text-2xl">5.54 Га</p>
</div>
<div>
<p class="text-[10px] uppercase tracking-[0.2em] text-outline mb-2">Электроснабжение</p>
<p class="font-headline text-2xl">400 кВт</p>
</div>
</div>
<button class="w-full border border-outline-variant py-6 font-body text-sm uppercase tracking-[0.3em] hover:bg-tertiary hover:text-on-tertiary hover:border-tertiary transition-all duration-500">
                        Детализация объекта
                    </button>
</div>
</div>
<!-- Secondary Info Panel / Grid -->
<div class="grid grid-rows-2 gap-12 h-full">
<div class="bg-surface-container-high p-12 flex flex-col justify-center border-l-4 border-tertiary">
<h4 class="font-editorial italic text-3xl mb-6">Инвестиционный фокус</h4>
<p class="font-body text-on-surface-variant leading-relaxed">
                        Мы специализируемся на участках с уникальными природными характеристиками и сложным ГПЗУ, где наша экспертиза создает максимальную добавленную стоимость.
                    </p>
</div>
<div class="relative overflow-hidden bg-surface-container-highest group">
<img alt="Architectural details" class="absolute inset-0 w-full h-full object-cover opacity-50 group-hover:scale-110 transition-transform duration-1000" data-alt="Abstract architectural lines of a slate building against a misty gray sky with sharp edges and minimal geometry" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAWNgdZFsUYHzA4cH7TTEAVYJTdb_4M-CwdcJd3lE3Xwas1miPvuK1EPM2C4epyAjeQ-v-RszsLQONbtrE6V_rfuVDdTQ7Z14dWaBuSB0Db122Jn78jup2K8loL_DaJkn-U0Nf2ieNbmff4PCl1ESxHtP7dOsBJ_cklgyJawulvQh4971z97b1QM-wNEbYjvP_7AdiYlS1wzKvtHfOQ_9SedDM8SAZTVQg8jTKrChciNUPtAFd4oGEw94ScvbIPK1FzYfkpicKMJFI"/>
<div class="relative z-10 p-12 h-full flex flex-col justify-end">
<span class="text-[10px] uppercase tracking-[0.3em] text-on-surface mb-4">Предстоящие лоты</span>
<h4 class="font-headline text-2xl uppercase">Moscow City &amp; Region</h4>
<p class="text-tertiary font-body text-sm mt-2">Доступно по запросу</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- CONFIDENTIAL CTA -->
<section class="py-40 bg-surface relative overflow-hidden">
<div class="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/carbon-fibre.png')] opacity-10"></div>
<div class="px-12 md:px-24 max-w-[1440px] mx-auto relative z-10 text-center">
<div class="max-w-4xl mx-auto">
<span class="material-symbols-outlined text-6xl text-tertiary/40 mb-12">lock</span>
<h2 class="font-headline text-4xl md:text-6xl mb-12 tracking-wide uppercase leading-tight">
                Конфиденциальный <br/> реестр активов
            </h2>
<p class="font-body text-xl text-on-surface-variant mb-16 max-w-2xl mx-auto font-light">
                Получите доступ к закрытой базе предложений Moscow City и эксклюзивным земельным активам Подмосковья.
            </p>
<div class="flex flex-col md:flex-row justify-center gap-8">
<button class="bg-on-surface text-surface px-16 py-6 font-headline text-lg tracking-widest hover:bg-tertiary hover:text-on-tertiary transition-all duration-500">
                    [ ЗАПРОСИТЬ ИНВЕСТИЦИОННОЕ ДОСЬЕ ]
                </button>
</div>
</div>
</div>
</section>
<!-- OFFICE & CONTACTS -->
<section class="py-32 bg-surface-container-lowest">
<div class="px-12 md:px-24 max-w-[1920px] mx-auto">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-24">
<div>
<h2 class="font-headline text-4xl mb-12 uppercase tracking-widest">Связь с офисом</h2>
<div class="space-y-12">
<div>
<p class="text-[10px] uppercase tracking-[0.3em] text-outline mb-4">Штаб-квартира</p>
<p class="font-headline text-2xl">Москва-Сити, Neva Towers</p>
<p class="font-body text-on-surface-variant mt-2">Пресненская наб., 17, Башня 2</p>
</div>
<div>
<p class="text-[10px] uppercase tracking-[0.3em] text-outline mb-4">Direct Contact</p>
<p class="font-headline text-2xl">+7 (495) 000-00-00</p>
<p class="font-editorial italic text-tertiary text-xl mt-2">office@f1capital.ru</p>
</div>
</div>
<div class="mt-20 w-full h-[300px] bg-surface-container">
<div class="w-full h-full grayscale opacity-40 hover:opacity-70 transition-opacity" data-location="Moscow Neva Towers">
<img alt="Moscow City Skyline" class="w-full h-full object-cover" data-alt="Night cityscape of Moscow City skyscrapers with shimmering lights and a misty atmosphere overlooking the river" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBhGsgvCptsm_TXK8vNCaahGJ3WcG95S6D5ve2a9Q-Von4WN6wecyi6fTH0JQwsx8-zHwzwmG97ZHzy_KJvd-m7w0LIdQMTos_S4okkjHULzhhC64LxPDSkX6jCXz_PCvK4GuleIu57PoCGuChM_tmj_H4MOnCi2qRw7YlBvrwnUt3Kc4VzVTXFebTQ5r4u9lU_PzXAgcPXQ_5UExCdQCRM-8FFdavX5dUp7CASpiSOfDJE8JzExsp8z1nuhTI1591xsJVLA0fTaZw"/>
</div>
</div>
</div>
<div class="bg-surface p-12 md:p-20">
<h3 class="font-editorial italic text-3xl mb-12">Оставить запрос</h3>
<form class="space-y-12">
<div class="relative">
<input class="w-full bg-transparent border-b border-outline-variant focus:border-tertiary focus:ring-0 py-4 font-body text-xs tracking-widest placeholder:text-outline/50 uppercase transition-all duration-500" placeholder="ВАШЕ ИМЯ" type="text"/>
</div>
<div class="relative">
<input class="w-full bg-transparent border-b border-outline-variant focus:border-tertiary focus:ring-0 py-4 font-body text-xs tracking-widest placeholder:text-outline/50 uppercase transition-all duration-500" placeholder="E-MAIL / ТЕЛЕФОН" type="email"/>
</div>
<div class="relative">
<textarea class="w-full bg-transparent border-b border-outline-variant focus:border-tertiary focus:ring-0 py-4 font-body text-xs tracking-widest placeholder:text-outline/50 uppercase transition-all duration-500 resize-none" placeholder="ИНТЕРЕСУЮЩИЙ ТИП АКТИВА" rows="4"></textarea>
</div>
<button class="w-full bg-tertiary text-on-tertiary py-6 font-headline tracking-widest uppercase hover:bg-opacity-80 transition-all" type="submit">
                        Отправить запрос
                    </button>
<p class="text-[10px] text-outline text-center uppercase tracking-widest leading-loose">
                        Нажимая кнопку, вы соглашаетесь с Политикой <br/> строгой конфиденциальности F1 CAPITAL.
                    </p>
</form>
</div>
</div>
</div>
</section>
<!-- Footer (Shared Component Identity) -->
<footer class="bg-[#07100d] border-t border-[#dae5e0]/10">
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-16 px-12 py-20 w-full max-w-[1920px] mx-auto">
<div class="space-y-8">
<div class="font-['Cinzel'] text-lg text-[#c5a059] opacity-50 uppercase tracking-[0.2em]">F1 CAPITAL</div>
<p class="font-['Inter'] text-sm uppercase tracking-widest leading-loose text-[#dae5e0]/60">
                © 2024 F1 CAPITAL. <br/> Исключительное управление трофейными активами.
            </p>
</div>
<div class="space-y-6">
<h4 class="font-['Inter'] text-xs font-bold uppercase tracking-[0.3em] text-[#bec9c4]">Юридическая информация</h4>
<ul class="space-y-4">
<li><a class="font-['Inter'] text-sm uppercase tracking-widest text-[#dae5e0]/60 hover:text-[#c5a059] transition-colors" href="#">Политика конфиденциальности</a></li>
<li><a class="font-['Inter'] text-sm uppercase tracking-widest text-[#dae5e0]/60 hover:text-[#c5a059] transition-colors" href="#">Комплаенс</a></li>
</ul>
</div>
<div class="space-y-6">
<h4 class="font-['Inter'] text-xs font-bold uppercase tracking-[0.3em] text-[#bec9c4]">Навигация</h4>
<ul class="space-y-4">
<li><a class="font-['Inter'] text-sm uppercase tracking-widest text-[#dae5e0]/60 hover:text-[#c5a059] transition-colors" href="#">Раскрытие информации</a></li>
<li><a class="font-['Inter'] text-sm uppercase tracking-widest text-[#dae5e0]/60 hover:text-[#c5a059] transition-colors" href="#">Карта сайта</a></li>
</ul>
</div>
<div class="flex flex-col items-start md:items-end justify-between">
<div class="flex gap-6">
<span class="material-symbols-outlined text-[#bec9c4] opacity-50 hover:opacity-100 cursor-pointer transition-opacity">public</span>
<span class="material-symbols-outlined text-[#bec9c4] opacity-50 hover:opacity-100 cursor-pointer transition-opacity">shield</span>
</div>
<div class="mt-8 text-[10px] text-outline/30 uppercase tracking-[0.4em]">Designed for UHNW Only</div>
</div>
</div>
</footer>
</body></html>


<!DOCTYPE html>

<html class="dark" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>F1 CAPITAL | Частное Управление Недвижимостью</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700;900&amp;family=Inter:wght@100;300;400;600&amp;family=Newsreader:ital,opsz,wght@0,6..72,200..800;1,6..72,200..800&amp;family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "secondary-fixed": "#e4e2e1",
                        "on-error": "#690005",
                        "inverse-surface": "#dae5e0",
                        "on-tertiary-fixed": "#261900",
                        "tertiary-fixed-dim": "#e9c176",
                        "on-secondary": "#303030",
                        "primary-fixed-dim": "#bec9c4",
                        "secondary-container": "#474746",
                        "primary-container": "#1a2421",
                        "primary": "#bec9c4",
                        "error": "#ffb4ab",
                        "surface-container": "#18221f",
                        "on-error-container": "#ffdad6",
                        "on-secondary-container": "#b6b5b4",
                        "on-primary": "#28332f",
                        "on-tertiary-fixed-variant": "#5d4201",
                        "surface-container-highest": "#2d3734",
                        "error-container": "#93000a",
                        "surface-container-lowest": "#07100d",
                        "surface-container-low": "#141e1b",
                        "secondary-fixed-dim": "#c8c6c5",
                        "on-primary-container": "#818c87",
                        "tertiary-fixed": "#ffdea5",
                        "on-primary-fixed-variant": "#3e4945",
                        "surface": "#0b1513",
                        "on-surface-variant": "#c3c8c5",
                        "surface-dim": "#0b1513",
                        "on-secondary-fixed-variant": "#474746",
                        "on-secondary-fixed": "#1b1c1c",
                        "secondary": "#c8c6c5",
                        "background": "#0b1513",
                        "primary-fixed": "#dae5e0",
                        "surface-tint": "#bec9c4",
                        "tertiary": "#e9c176",
                        "surface-container-high": "#222c29",
                        "inverse-on-surface": "#28332f",
                        "on-tertiary": "#412d00",
                        "surface-variant": "#2d3734",
                        "on-primary-fixed": "#141e1b",
                        "surface-bright": "#313b38",
                        "on-background": "#dae5e0",
                        "on-surface": "#dae5e0",
                        "tertiary-container": "#2e1f00",
                        "outline": "#8d928f",
                        "on-tertiary-container": "#a68440",
                        "inverse-primary": "#56615d",
                        "outline-variant": "#434846"
                    },
                    fontFamily: {
                        "headline": ["Cinzel", "serif"],
                        "body": ["Inter", "sans-serif"],
                        "label": ["Inter", "sans-serif"],
                        "editorial": ["Newsreader", "serif"]
                    },
                    borderRadius: {
                        "DEFAULT": "0px",
                        "lg": "0px",
                        "xl": "0px",
                        "full": "9999px"
                    },
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
            vertical-align: middle;
        }
        ::-webkit-scrollbar { width: 4px; }
        ::-webkit-scrollbar-track { background: #07100d; }
        ::-webkit-scrollbar-thumb { background: #1a2421; }
        body { background-color: #0b1513; color: #dae5e0; overflow-x: hidden; }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="font-body selection:bg-tertiary selection:text-on-tertiary">
<!-- Header / TopAppBar -->
<nav class="bg-[#0b1513] fixed top-0 left-0 w-full z-50 flex justify-between items-center px-12 py-6 max-w-[1920px] mx-auto">
<div class="text-2xl font-headline tracking-widest text-[#e9c176]">F1 CAPITAL</div>
<div class="hidden md:flex items-center gap-10">
<a class="text-[#e9c176] border-b-2 border-[#e9c176] pb-1 font-label text-xs tracking-widest uppercase" href="#">Land</a>
<a class="text-[#bec9c4] hover:text-[#e9c176] transition-colors font-label text-xs tracking-widest uppercase" href="#">Houses</a>
<a class="text-[#bec9c4] hover:text-[#e9c176] transition-colors font-label text-xs tracking-widest uppercase" href="#">Mansions</a>
<a class="text-[#bec9c4] hover:text-[#e9c176] transition-colors font-label text-xs tracking-widest uppercase" href="#">Penthouses</a>
<a class="text-[#bec9c4] hover:text-[#e9c176] transition-colors font-label text-xs tracking-widest uppercase" href="#">Apartments</a>
</div>
<div class="flex items-center gap-6">
<button class="text-[#bec9c4] hover:scale-95 transition-all duration-200">
<span class="material-symbols-outlined" data-icon="account_gold_fingerprint">fingerprint</span>
</button>
<button class="text-[#bec9c4] hover:scale-95 transition-all duration-200">
<span class="material-symbols-outlined" data-icon="menu">menu</span>
</button>
</div>
</nav>
<main class="pt-24">
<!-- Hero Section -->
<section class="relative h-[921px] flex items-center px-12 overflow-hidden bg-primary-container">
<div class="absolute inset-0 z-0">
<div class="absolute inset-0 bg-gradient-to-r from-surface-container-lowest via-surface-container-lowest/40 to-transparent z-10"></div>
<img class="w-full h-full object-cover opacity-60" data-alt="Ultra-modern brutalist concrete villa architecture in a misty forest at dawn with soft atmospheric lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDi_QA-kzOXXikr8Uauz9YgnFtDb9q7JBKYq_plZyiHG3MiwL0fRwdqw6eiWeYchjh74AvMjQCSbYkPzeyX4Em7H4JDeH-QgRSI3pvvCJwGqCOIXSiJasGd4G5ZBIR5OyKbG-ZdvEHOGyq5amdmr3dXGBAlMdd4quFaZvjPRieuUBXEwgW4h50KuayuKbO4lSOueevZhKHGlZ9Es9Z4MDixMs7aXPBtwF8eNEFqiekhItyLkwS08QMzHBvvHYhBxpBBO-D8_qsT6k8"/>
</div>
<div class="relative z-20 max-w-4xl">
<span class="font-editorial italic text-tertiary text-2xl mb-4 block">Искусство владения</span>
<h1 class="font-headline text-6xl md:text-8xl leading-none tracking-tight mb-8">МОНОЛИТ <br/> ЧАСТНОГО <br/> КАПИТАЛА</h1>
<p class="font-body text-on-surface-variant max-w-md text-lg leading-relaxed mb-12">
                    F1 CAPITAL — архитектурный манифест в мире управления активами. Мы создаем пространство, где роскошь встречается с безупречной стратегией.
                </p>
<div class="flex gap-4">
<button class="bg-tertiary text-on-tertiary px-10 py-5 font-label tracking-widest uppercase text-xs hover:bg-tertiary-fixed-dim transition-colors">
                        Смотреть портфолио
                    </button>
<button class="border border-outline-variant/20 px-10 py-5 font-label tracking-widest uppercase text-xs hover:bg-surface-container-highest transition-colors">
                        Консультация
                    </button>
</div>
</div>
</section>
<!-- ASSET REGISTRY SECTION -->
<section class="py-32 px-12 bg-surface">
<div class="max-w-[1920px] mx-auto">
<div class="flex justify-between items-end mb-16">
<div>
<h2 class="font-headline text-4xl mb-4 uppercase tracking-[0.1em]">РЕЕСТР АКТИВОВ</h2>
<div class="h-1 w-24 bg-tertiary"></div>
</div>
<div class="flex gap-4">
<button class="w-12 h-12 flex items-center justify-center border border-outline-variant/20 hover:bg-surface-container-low transition-all">
<span class="material-symbols-outlined text-primary">chevron_left</span>
</button>
<button class="w-12 h-12 flex items-center justify-center border border-outline-variant/20 hover:bg-surface-container-low transition-all">
<span class="material-symbols-outlined text-primary">chevron_right</span>
</button>
</div>
</div>
<!-- Asset Carousel -->
<div class="flex gap-8 overflow-x-auto hide-scrollbar pb-12 snap-x">
<!-- Card 1 -->
<div class="min-w-[450px] snap-start group cursor-pointer">
<div class="aspect-[4/5] overflow-hidden bg-surface-container-low relative">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" data-alt="Hyper-modern glass mansion in the mountains of Switzerland, dramatic clouds, moody desaturated tones" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCl1Idi6QR2kqzegqB662llDB2hZeasvlC9Zu67ivGnu0Zdr2zXxqZBMWkBro8yHPGv9PQAVQxydZDkBZxnZiFRTVwqKSI1vwgsMZ37-gZH55Eq_MVVIsQOOATzfaVwsqK-H4pvf5OOGJc2WIWKt2yNkeZI8r9V7-rr2NpGLf9R6OaCgXFo82KC0s-DX63JX1oyFfxNRvAI45b5FRBvRlmW0843hDzTEo-WBSaTgj_b4jW1qTQEtW30V1hJOIeE5VV_RKKuBw61XuU"/>
<div class="absolute top-6 left-6 bg-surface-container-lowest/80 backdrop-blur px-4 py-2 text-[10px] tracking-[0.2em] font-label uppercase">
                                Available • $42M
                            </div>
</div>
<div class="mt-6">
<h3 class="font-headline text-xl mb-2 group-hover:text-tertiary transition-colors">Особняк "Эфир"</h3>
<p class="font-body text-on-surface-variant text-sm tracking-wide">Кантон Граубюнден, Швейцария</p>
</div>
</div>
<!-- Card 2 -->
<div class="min-w-[450px] snap-start group cursor-pointer">
<div class="aspect-[4/5] overflow-hidden bg-surface-container-low relative">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" data-alt="Minimalist penthouse interior with high ceilings and floor to ceiling windows overlooking Tokyo at twilight" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAtqN7VKIgBGKr2bVHPdgZjvYuKzYMQIYToIW1wR1E3Cu0eorm85bt_Wv2J2JukhtjUhdiSRN2s67GH28VO7qtKEyxj9b1bqHjLH7QCiAoXIVI87m_0DJ8cokhpbonB5w0XTPOUC67cu6xrt9GeKanMWMKePfMmvR_MQ1ChKZrMrfeYv0ykhwC4fF33TYHx-JDteGAhW2q3z5j5Gw2gev_PtI5ol3Fg9sH8McHM8lcbuNppjsXFxuKcvBANJzmAfObAPTumDh82sCU"/>
<div class="absolute top-6 left-6 bg-surface-container-lowest/80 backdrop-blur px-4 py-2 text-[10px] tracking-[0.2em] font-label uppercase">
                                Private Placement • $18M
                            </div>
</div>
<div class="mt-6">
<h3 class="font-headline text-xl mb-2 group-hover:text-tertiary transition-colors">Пентхаус "Зенит"</h3>
<p class="font-body text-on-surface-variant text-sm tracking-wide">Акасака, Токио</p>
</div>
</div>
<!-- Card 3 -->
<div class="min-w-[450px] snap-start group cursor-pointer">
<div class="aspect-[4/5] overflow-hidden bg-surface-container-low relative">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" data-alt="Coastal modern villa with white stone walls and infinity pool merging with the Mediterranean sea at dusk" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD_0aRFUsv7Lmb-r1qKkahtzR8dESMefJLcg2m12ReLa_C3g_NshOU8v2oXBDm6J0yWaQwpBCVX8aglDHGX2D50nRE_elu8piF96S1GnMpVcpXKCKk_2r8foJ9Gsktj1nBZMC_NiBzDef5tF0hXad6OkSxzw2VD-Hjn7l1GFGV20Z3MF2D-I7656cjhdNrhdYPCW5lpRHaH8UtNor-t6aNq_CgxHj6GOcL4DqhVZvtpB6_wrq2GLdE5HmF1OdpUXatDpUh61evyxEU"/>
<div class="absolute top-6 left-6 bg-surface-container-lowest/80 backdrop-blur px-4 py-2 text-[10px] tracking-[0.2em] font-label uppercase">
                                Landmark • $29M
                            </div>
</div>
<div class="mt-6">
<h3 class="font-headline text-xl mb-2 group-hover:text-tertiary transition-colors">Вилла "Горизонт"</h3>
<p class="font-body text-on-surface-variant text-sm tracking-wide">Лазурный берег, Франция</p>
</div>
</div>
<!-- Card 4 -->
<div class="min-w-[450px] snap-start group cursor-pointer">
<div class="aspect-[4/5] overflow-hidden bg-surface-container-low relative">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" data-alt="Large private forested estate land with mist rising from a river in the early morning light" src="https://lh3.googleusercontent.com/aida-public/AB6AXuATKv1zvH65LAbQlQwQzFmFeL-vf7RKXMCF1H05_MfVGE-Lc7B5EB01XdimIi8RgYisyUpUIbYGYmqdk7V7qzWN-TLMePwIVgsbXzZmey_gqEVQh_UxnDDnKESTHTFPkM1DuF6yrCf8v4__oByynNjQi07hhXopmz4X-O7lsAMPK28g0rK_7_4rMG4RoCOp0Haz5sOu6Psa9sSVWaorX6VJ_dFcMV_4YJysC2ShRoSAO5DRurlZubYUTLSzqXar_0ynGJE139OAB4c"/>
<div class="absolute top-6 left-6 bg-surface-container-lowest/80 backdrop-blur px-4 py-2 text-[10px] tracking-[0.2em] font-label uppercase">
                                Prime Land • $12M
                            </div>
</div>
<div class="mt-6">
<h3 class="font-headline text-xl mb-2 group-hover:text-tertiary transition-colors">Участок "Север"</h3>
<p class="font-body text-on-surface-variant text-sm tracking-wide">Озерный край, Великобритания</p>
</div>
</div>
</div>
<!-- Category Selector -->
<div class="mt-24 border-t border-outline-variant/10 pt-12">
<div class="flex flex-wrap justify-center gap-12 md:gap-24">
<button class="group flex flex-col items-center gap-4 focus:outline-none">
<span class="font-label text-xs uppercase tracking-[0.3em] text-tertiary font-bold">Земельные участки</span>
<div class="h-[2px] w-full bg-tertiary transition-all duration-300"></div>
</button>
<button class="group flex flex-col items-center gap-4 focus:outline-none">
<span class="font-label text-xs uppercase tracking-[0.3em] text-on-surface-variant hover:text-tertiary transition-colors">Дома/Коттеджи</span>
<div class="h-[2px] w-0 bg-tertiary group-hover:w-full transition-all duration-300"></div>
</button>
<button class="group flex flex-col items-center gap-4 focus:outline-none">
<span class="font-label text-xs uppercase tracking-[0.3em] text-on-surface-variant hover:text-tertiary transition-colors">Особняки</span>
<div class="h-[2px] w-0 bg-tertiary group-hover:w-full transition-all duration-300"></div>
</button>
<button class="group flex flex-col items-center gap-4 focus:outline-none">
<span class="font-label text-xs uppercase tracking-[0.3em] text-on-surface-variant hover:text-tertiary transition-colors">Пентхаусы</span>
<div class="h-[2px] w-0 bg-tertiary group-hover:w-full transition-all duration-300"></div>
</button>
<button class="group flex flex-col items-center gap-4 focus:outline-none">
<span class="font-label text-xs uppercase tracking-[0.3em] text-on-surface-variant hover:text-tertiary transition-colors">Квартиры</span>
<div class="h-[2px] w-0 bg-tertiary group-hover:w-full transition-all duration-300"></div>
</button>
</div>
</div>
</div>
</section>
<!-- Stats Section (Asymmetric) -->
<section class="grid grid-cols-1 md:grid-cols-12 gap-0 bg-surface-container-lowest">
<div class="md:col-span-7 bg-surface-container-low p-24">
<h3 class="font-editorial text-4xl italic mb-12 max-w-lg">"Пространство — это высшее проявление богатства."</h3>
<div class="grid grid-cols-2 gap-16">
<div>
<div class="font-headline text-5xl text-tertiary mb-2">€4.2B+</div>
<div class="font-label text-[10px] uppercase tracking-widest text-on-surface-variant">Активов под управлением</div>
</div>
<div>
<div class="font-headline text-5xl text-tertiary mb-2">12</div>
<div class="font-label text-[10px] uppercase tracking-widest text-on-surface-variant">Юрисдикций присутствия</div>
</div>
</div>
</div>
<div class="md:col-span-5 h-[500px] md:h-auto overflow-hidden relative">
<img class="w-full h-full object-cover grayscale opacity-40" data-alt="Monolithic black stone wall with subtle water feature, atmospheric soft directional lighting, luxury spa vibe" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCLUTESFe9VKxp8ABaNuSMUER38Mwe0mLoBlFledToIlByNtFjZp2uBr-fu3Ea-oAl7dmrxmI8pXOyBXC4Mn30dHkEoLxJp_qwzXNmh3dfjacOcwaSgh927MFVQRIX4Jnw1x_hzg3E0Kkgo9feFhzv9pKVn9H-9SXd9LZBG6caEcD4ucmGuhELu0d2zlAbYX0gEQAfQZyxXou2tc5vyn4fUlUTizJBNRPVvEnPWX5-M6L2WHsSXKEoPWVnYjqBRIAtIu832jiFJS8o"/>
<div class="absolute inset-0 bg-primary-container/30 backdrop-overlay"></div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-[#07100d] border-t border-[#bec9c4]/10 py-24 flex flex-col items-center gap-12 w-full max-w-7xl mx-auto px-8">
<div class="font-headline text-3xl tracking-widest text-[#e9c176]">F1 CAPITAL</div>
<div class="flex flex-wrap justify-center gap-8 md:gap-16">
<a class="font-label text-[10px] uppercase tracking-[0.2em] text-[#c8c6c5] hover:text-[#e9c176] transition-colors" href="#">Privacy Policy</a>
<a class="font-label text-[10px] uppercase tracking-[0.2em] text-[#c8c6c5] hover:text-[#e9c176] transition-colors" href="#">Terms of Excellence</a>
<a class="font-label text-[10px] uppercase tracking-[0.2em] text-[#c8c6c5] hover:text-[#e9c176] transition-colors" href="#">Regulatory Disclosures</a>
<a class="font-label text-[10px] uppercase tracking-[0.2em] text-[#c8c6c5] hover:text-[#e9c176] transition-colors" href="#">Contact</a>
</div>
<div class="w-24 h-px bg-tertiary/30"></div>
<div class="text-center font-label text-[10px] uppercase tracking-[0.2em] text-[#c8c6c5]/50 leading-loose">
            © 2024 F1 CAPITAL. AN ARCHITECTURAL MONOLITH IN PRIVATE WEALTH. <br/>
            LONDON | TOKYO | ZURICH | DUBAI
        </div>
</footer>
</body></html>

