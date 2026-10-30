<!DOCTYPE html>
<html lang="ru" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ЧтоВнутри? — Умный сканер состава продуктов и пищевых добавок</title>
  <meta name="description" content="Мгновенный анализ состава продуктов по штрихкоду и фото. Поиск скрытого сахара, опасных Е-добавок и аллергенов индивидуально для всей семьи в Telegram и MAX.">
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: {
              50: '#ecfdf5',
              100: '#d1fae5',
              500: '#10b981',
              600: '#059669',
              700: '#047857',
              900: '#064e3b',
            }
          }
        }
      }
    }
  </script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', sans-serif; }
    .glass { background: rgba(255, 255, 255, 0.85); backdrop-filter: blur(12px); }
  </style>
</head>
<body class="bg-slate-50 text-slate-900 antialiased selection:bg-brand-500 selection:text-white">

  <!-- ШАПКА / НАВИГАЦИЯ -->
  <header class="sticky top-0 z-50 glass border-b border-slate-200/80 transition-all">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 h-16 flex items-center justify-between">
      <a href="#" class="flex items-center space-x-2.5">
        <span class="w-9 h-9 rounded-xl bg-gradient-to-tr from-brand-600 to-emerald-400 text-white flex items-center justify-center text-lg font-black shadow-md shadow-brand-500/20">🔍</span>
        <span class="font-black text-lg tracking-tight bg-gradient-to-r from-slate-900 to-slate-700 bg-clip-text text-transparent">ЧтоВнутри?</span>
      </a>

      <nav class="hidden md:flex items-center space-x-8 text-xs font-semibold text-slate-600">
        <a href="#features" class="hover:text-brand-600 transition">Возможности</a>
        <a href="#family" class="hover:text-brand-600 transition">Семья</a>
        <a href="#pricing" class="hover:text-brand-600 transition">Тарифы</a>
        <a href="#truth" class="hover:text-brand-600 transition">Фото vs Штрихкод</a>
        <a href="#faq" class="hover:text-brand-600 transition">FAQ</a>
      </nav>

      <div class="flex items-center space-x-2.5">
        <a href="https://t.me/Food_Inspection_bot" target="_blank" class="px-3.5 py-2 bg-sky-500 hover:bg-sky-600 active:scale-95 text-white font-bold text-xs rounded-xl shadow-sm transition flex items-center gap-1.5">
          <span>✈️</span> <span class="hidden sm:inline">Telegram</span>
        </a>
        <a href="https://max.ru" target="_blank" class="px-3.5 py-2 bg-gradient-to-r from-brand-600 to-teal-600 hover:opacity-95 active:scale-95 text-white font-bold text-xs rounded-xl shadow-sm transition flex items-center gap-1.5">
          <span>💬</span> <span class="hidden sm:inline">MAX</span>
        </a>
      </div>
    </div>
  </header>

  <!-- ГЛАВНЫЙ ЭКРАН (HERO) -->
  <section class="relative pt-12 pb-20 overflow-hidden">
    <div class="absolute inset-0 bg-gradient-to-b from-brand-50/60 via-transparent to-transparent pointer-events-none"></div>
    <div class="max-w-6xl mx-auto px-4 sm:px-6 relative">
      <div class="text-center max-w-3xl mx-auto space-y-6">
        
        <div class="inline-flex items-center space-x-2 bg-brand-50 border border-brand-200/80 px-3.5 py-1.5 rounded-full text-brand-700 text-xs font-bold shadow-sm">
          <span>⚡️</span>
          <span>Самообучающийся сканер состава нового поколения</span>
        </div>

        <h1 class="text-3xl sm:text-5xl md:text-6xl font-black text-slate-900 tracking-tight leading-[1.15]">
          Узнайте чистую правду о еде <span class="bg-gradient-to-r from-brand-600 to-teal-500 bg-clip-text text-transparent">за 1 секунду</span>
        </h1>

        <p class="text-sm sm:text-base text-slate-600 leading-relaxed max-w-2xl mx-auto font-normal">
          Хватит ломать глаза у магазинных полок. Наведите камеру на штрихкод или сфотографируйте состав — нейросеть мгновенно найдёт скрытый сахар, опасные Е-добавки и аллергены индивидуально для вас, ваших детей и родителей.
        </p>

        <!-- КНОПКИ ДЕЙСТВИЯ -->
        <div class="pt-4 flex flex-col sm:flex-row items-center justify-center gap-3.5">
          <a href="https://t.me/Food_Inspection_bot" target="_blank" class="w-full sm:w-auto px-6 py-4 bg-gradient-to-r from-sky-500 to-blue-600 hover:from-sky-600 hover:to-blue-700 text-white font-extrabold text-sm rounded-2xl shadow-lg shadow-sky-500/25 active:scale-95 transition flex items-center justify-center gap-2">
            <span>✈️ Открыть сканер в Telegram</span>
          </a>
          <a href="https://max.ru" target="_blank" class="w-full sm:w-auto px-6 py-4 bg-slate-900 hover:bg-slate-800 text-white font-extrabold text-sm rounded-2xl shadow-lg shadow-slate-900/20 active:scale-95 transition flex items-center justify-center gap-2">
            <span>💬 Запустить в мессенджере MAX</span>
          </a>
        </div>

        <p class="text-[11px] text-slate-400 font-medium">Работает без установки приложений • 5 бесплатных проверок каждый день</p>

      </div>
    </div>
  </section>

  <!-- КИЛЛЕР-ФИЧИ -->
  <section id="features" class="py-20 bg-white border-y border-slate-200">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="text-center max-w-2xl mx-auto mb-16 space-y-3">
        <h2 class="text-xs font-bold text-brand-600 uppercase tracking-widest">Технологическое превосходство</h2>
        <p class="text-2xl sm:text-4xl font-black text-slate-900">Больше, чем просто сканер</p>
      </div>

      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-slate-50 p-7 rounded-3xl border border-slate-200 space-y-4">
          <div class="w-12 h-12 rounded-2xl bg-amber-100 text-amber-700 flex items-center justify-center text-2xl font-black">🚨</div>
          <h3 class="text-base font-bold text-slate-900">Детектор смены рецептуры</h3>
          <p class="text-xs text-slate-600 leading-relaxed">Контролируем свежесть партий каждые 30 дней и предупреждаем, если производитель втихую удешевил товар.</p>
        </div>

        <div class="bg-slate-50 p-7 rounded-3xl border border-slate-200 space-y-4">
          <div class="w-12 h-12 rounded-2xl bg-emerald-100 text-emerald-700 flex items-center justify-center text-2xl font-black">🧠</div>
          <h3 class="text-base font-bold text-slate-900">Самообучающаяся база</h3>
          <p class="text-xs text-slate-600 leading-relaxed">Каждый новый продукт кэшируется, а редкие Е-добавки автоматически пополняют наш независимый каталог.</p>
        </div>

        <div class="bg-slate-50 p-7 rounded-3xl border border-slate-200 space-y-4">
          <div class="w-12 h-12 rounded-2xl bg-sky-100 text-sky-700 flex items-center justify-center text-2xl font-black">🚦</div>
          <h3 class="text-base font-bold text-slate-900">Четкий светофор</h3>
          <p class="text-xs text-slate-600 leading-relaxed">Понятные статусы: 🟢 <b>ПРИГОДНО</b>, 🟡 <b>НЕЙТРАЛЬНО</b> или 🔴 <b>ОПАСНО</b> с указанием точной причины.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- СЕМЕЙНЫЙ РЕЖИМ -->
  <section id="family" class="py-20">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="grid md:grid-cols-2 gap-12 items-center">
        <div class="space-y-6">
          <div class="inline-flex items-center space-x-2 bg-emerald-50 text-emerald-700 px-3 py-1 rounded-full text-xs font-bold">
            <span>👨‍👩‍👧</span><span>Безопасность для близких</span>
          </div>
          <h2 class="text-2xl sm:text-4xl font-black text-slate-900 leading-tight">Один скан в магазине — защита для всей семьи</h2>
          <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
            Настройте возраст и особенности здоровья для каждого члена семьи. Режим <b>«Вся семья»</b> проверит один товар сразу против всех ваших домашних за один снимок.
          </p>
        </div>
        <div class="bg-slate-100 rounded-3xl p-6 border border-slate-200 space-y-3">
          <div class="bg-white p-3.5 rounded-2xl border flex justify-between items-center"><span class="text-xs font-bold">👤 Я (Без лактозы)</span><span class="text-[10px] font-black bg-emerald-50 text-emerald-700 px-2 py-0.5 rounded">🟢 ПРИГОДНО</span></div>
          <div class="bg-white p-3.5 rounded-2xl border flex justify-between items-center"><span class="text-xs font-bold">👦 Сын (5 лет, аллергия)</span><span class="text-[10px] font-black bg-red-50 text-red-700 px-2 py-0.5 rounded">🔴 ОПАСНО (E102)</span></div>
          <div class="bg-white p-3.5 rounded-2xl border flex justify-between items-center"><span class="text-xs font-bold">👵 Мама (62 года, диабет)</span><span class="text-[10px] font-black bg-amber-50 text-amber-700 px-2 py-0.5 rounded">🟡 НЕЙТРАЛЬНО</span></div>
        </div>
      </div>
    </div>
  </section>

  <!-- РАЗДЕЛ ТАРИФОВ (ЦЕНЫ) -->
  <section id="pricing" class="py-20 bg-white border-t border-slate-200">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="text-center max-w-2xl mx-auto mb-16 space-y-3">
        <h2 class="text-xs font-bold text-brand-600 uppercase tracking-widest">Инвестиция в здоровье</h2>
        <p class="text-2xl sm:text-4xl font-black text-slate-900">Простые и честные тарифы PRO</p>
        <p class="text-xs sm:text-sm text-slate-500">Безлимитные проверки без ограничений и семейные профили.</p>
      </div>

      <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
        
        <!-- Тариф 1 мес -->
        <div class="bg-slate-50 p-6 rounded-3xl border border-slate-200 flex flex-col justify-between space-y-6">
          <div class="space-y-2">
            <h3 class="text-sm font-bold text-slate-900">1 месяц</h3>
            <p class="text-2xl font-black text-brand-600">150 ⭐ <span class="text-xs font-normal text-slate-400">/ ~290 ₽</span></p>
            <p class="text-[11px] text-slate-500">Идеально для разового теста безлимита</p>
          </div>
          <a href="https://t.me/Food_Inspection_bot?start=pro_30" target="_blank" class="w-full py-3 bg-slate-900 text-white font-bold text-xs rounded-xl text-center shadow hover:bg-slate-800 transition">Выбрать тариф</a>
        </div>

        <!-- Тариф 2 мес -->
        <div class="bg-slate-50 p-6 rounded-3xl border border-slate-200 flex flex-col justify-between space-y-6">
          <div class="space-y-2">
            <div class="flex justify-between items-center"><h3 class="text-sm font-bold text-slate-900">2 месяца</h3><span class="text-[10px] bg-emerald-100 text-emerald-800 px-2 py-0.5 rounded-full font-bold">-10%</span></div>
            <p class="text-2xl font-black text-brand-600">270 ⭐ <span class="text-xs font-normal text-slate-400">/ ~520 ₽</span></p>
            <p class="text-[11px] text-slate-500">Выгодное продление на сезон покупок</p>
          </div>
          <a href="https://t.me/Food_Inspection_bot?start=pro_60" target="_blank" class="w-full py-3 bg-slate-900 text-white font-bold text-xs rounded-xl text-center shadow hover:bg-slate-800 transition">Выбрать тариф</a>
        </div>

        <!-- Тариф 3 мес -->
        <div class="bg-slate-50 p-6 rounded-3xl border border-slate-200 flex flex-col justify-between space-y-6">
          <div class="space-y-2">
            <div class="flex justify-between items-center"><h3 class="text-sm font-bold text-slate-900">3 месяца</h3><span class="text-[10px] bg-emerald-100 text-emerald-800 px-2 py-0.5 rounded-full font-bold">-15%</span></div>
            <p class="text-2xl font-black text-brand-600">380 ⭐ <span class="text-xs font-normal text-slate-400">/ ~740 ₽</span></p>
            <p class="text-[11px] text-slate-500">Оптимальный выбор для регулярных проверок</p>
          </div>
          <a href="https://t.me/Food_Inspection_bot?start=pro_90" target="_blank" class="w-full py-3 bg-slate-900 text-white font-bold text-xs rounded-xl text-center shadow hover:bg-slate-800 transition">Выбрать тариф</a>
        </div>

        <!-- Тариф 6 мес (Хит) -->
        <div class="bg-gradient-to-br from-amber-500 to-orange-600 p-6 rounded-3xl text-white flex flex-col justify-between space-y-6 shadow-lg shadow-orange-500/20">
          <div class="space-y-2">
            <div class="flex justify-between items-center"><h3 class="text-sm font-black">6 месяцев (Семья)</h3><span class="text-[10px] bg-yellow-300 text-slate-900 px-2 py-0.5 rounded-full font-black">-25% ХИТ</span></div>
            <p class="text-2xl font-black">675 ⭐ <span class="text-xs font-normal opacity-80">/ ~1290 ₽</span></p>
            <p class="text-[11px] opacity-90">Максимальная экономия и безлимит для всей семьи на полгода</p>
          </div>
          <a href="https://t.me/Food_Inspection_bot?start=pro_180" target="_blank" class="w-full py-3 bg-white text-orange-600 font-extrabold text-xs rounded-xl text-center shadow hover:bg-slate-50 transition">Выбрать хит</a>
        </div>

      </div>
    </div>
  </section>

  <!-- ЭКСПЕРТНЫЙ БЛОК: ФОТО VS ШТРИХКОД -->
  <section id="truth" class="py-20 bg-slate-50 border-t border-slate-200">
    <div class="max-w-4xl mx-auto px-4 sm:px-6">
      <div class="bg-slate-900 text-white p-8 sm:p-12 rounded-[2.5rem] shadow-xl space-y-6">
        <h2 class="text-2xl sm:text-3xl font-black">Почему фото состава точнее штрихкода?</h2>
        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
          Штрихкод — это просто цифры на упаковке. Когда завод меняет рецептуру или выпускает партию в другом регионе со старыми цифрами, штрихкод об этом не знает. <b>Фотография реального состава на пачке гарантирует 100% точность</b>, так как искусственный интеллект читает свежие буквы прямо с упаковки.
        </p>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" class="py-20 bg-white border-t border-slate-200">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 space-y-12">
      <div class="text-center space-y-2">
        <p class="text-2xl sm:text-3xl font-black text-slate-900">Часто задаваемые вопросы</p>
      </div>
      <div class="space-y-4">
        <details class="group bg-slate-50 p-5 rounded-2xl border border-slate-200 cursor-pointer">
          <summary class="flex justify-between items-center font-bold text-xs sm:text-sm text-slate-900 list-none">
            <span>Это действительно работает без установки приложений?</span>
            <span class="text-brand-600 group-open:rotate-180 transition">▼</span>
          </summary>
          <p class="text-xs text-slate-600 mt-3 leading-relaxed">Да, сервис открывается прямо внутри Telegram или мессенджера MAX в один клик.</p>
        </details>
        <details class="group bg-slate-50 p-5 rounded-2xl border border-slate-200 cursor-pointer">
          <summary class="flex justify-between items-center font-bold text-xs sm:text-sm text-slate-900 list-none">
            <span>Как работает оплата в Telegram Stars и рублях?</span>
            <span class="text-brand-600 group-open:rotate-180 transition">▼</span>
          </summary>
          <p class="text-xs text-slate-600 mt-3 leading-relaxed">Оплата происходит через официальные защищенные шлюзы платформ (Telegram Stars или СБП/карты в РФ) моментально и безопасно.</p>
        </details>
      </div>
    </div>
  </section>

  <!-- ОБРАТНАЯ СВЯЗЬ -->
  <section id="feedback" class="py-20 bg-slate-100/70 border-t border-slate-200">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 space-y-12">
      <div class="text-center max-w-xl mx-auto space-y-3">
        <h2 class="text-xs font-bold text-brand-600 uppercase tracking-widest">Служба заботы</h2>
        <p class="text-2xl sm:text-3xl font-black text-slate-900">Обратная связь</p>
        <p class="text-xs text-slate-500">Заметили ошибку в товаре или есть предложения? Напишите нам.</p>
      </div>

      <div class="grid md:grid-cols-2 gap-8 items-start">
        <div class="bg-white p-6 rounded-3xl border border-slate-200 space-y-4">
          <h3 class="text-sm font-bold text-slate-900">Контакты:</h3>
          <a href="https://t.me/Food_Inspection_bot" target="_blank" class="flex items-center space-x-3 p-3 rounded-2xl bg-slate-50 hover:bg-slate-100 transition">
            <span class="text-2xl">🤖</span>
            <div><p class="text-xs font-bold text-slate-900">Бот в Telegram</p><p class="text-[11px] text-slate-500">@Food_Inspection_bot</p></div>
          </a>
          <a href="https://max.ru" target="_blank" class="flex items-center space-x-3 p-3 rounded-2xl bg-slate-50 hover:bg-slate-100 transition">
            <span class="text-2xl">💬</span>
            <div><p class="text-xs font-bold text-slate-900">Мессенджер MAX</p><p class="text-[11px] text-slate-500">Официальная поддержка</p></div>
          </a>
        </div>

        <form id="contactForm" onsubmit="handleContactSubmit(event)" class="bg-white p-6 rounded-3xl border border-slate-200 space-y-3.5 shadow-sm">
          <h3 class="text-sm font-bold text-slate-900">Написать разработчикам:</h3>
          <div><label class="text-[11px] font-bold text-slate-600 block mb-1">Ваше имя:</label><input type="text" id="contactName" required placeholder="Анна" class="w-full text-xs p-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:border-brand-500"></div>
          <div><label class="text-[11px] font-bold text-slate-600 block mb-1">Контакты (Telegram / Email):</label><input type="text" id="contactInfo" required placeholder="@username" class="w-full text-xs p-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:border-brand-500"></div>
          <div><label class="text-[11px] font-bold text-slate-600 block mb-1">Сообщение:</label><textarea id="contactMessage" required rows="3" placeholder="Вопрос или неточность в товаре..." class="w-full text-xs p-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:border-brand-500"></textarea></div>
          <button type="submit" id="btnSubmitContact" class="w-full py-3.5 bg-brand-600 hover:bg-brand-700 text-white font-extrabold text-xs rounded-xl shadow-md transition">Отправить сообщение</button>
          <p id="formStatus" class="hidden text-center text-xs font-bold text-brand-600 pt-1">✅ Сообщение отправлено!</p>
        </form>
      </div>
    </div>
  </section>

  <!-- ПОДВАЛ И ЮРИДИЧЕСКАЯ ИНФОРМАЦИЯ -->
  <footer class="bg-slate-900 text-slate-400 py-12 text-xs border-t border-slate-800">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 space-y-8">
      
      <!-- Юридический блок с ИНН -->
      <div class="p-4 rounded-2xl bg-slate-800/60 border border-slate-700/80 text-[11px] leading-relaxed text-slate-300 space-y-1">
        <p class="font-bold text-white">Мотовилов Роман Викторович • ИНН 540233076795</p>
        <p class="text-amber-400 font-bold flex items-center gap-1"><span>⚠️</span> ВАЖНОЕ ПРАВОВОЕ УВЕДОМЛЕНИЕ (ДИСКЛЕЙМЕР):</p>
        <p class="opacity-90">Сервис «ЧтоВнутри? / Food Scanner PRO» предоставляет исключительно справочно-информационные услуги по автоматизированной расшифровке состава упакованных товаров. Сервис не является медицинской организацией, не ставит диагнозов и не заменяет консультации врача. При тяжелых формах аллергий всегда проверяйте маркировку на упаковке лично.</p>
      </div>

      <div class="flex flex-col sm:flex-row justify-between items-center gap-4 text-slate-500 text-[11px]">
        <p>© 2026 ЧтоВнутри? (Food Scanner PRO). Все права защищены.</p>
        <div class="flex space-x-6">
          <a href="#" class="hover:text-white transition">Соглашение</a>
          <a href="#" class="hover:text-white transition">Политика конфиденциальности</a>
        </div>
      </div>
    </div>
  </footer>

  <script>
    async function handleContactSubmit(event) {
      event.preventDefault();
      const btn = document.getElementById('btnSubmitContact');
      const status = document.getElementById('formStatus');
      btn.innerText = "⏳ Отправка...";
      btn.disabled = true;

      try {
        await fetch("https://zloy4elovek0.app.n8n.cloud/webhook/scan", {
          method: "POST",
          headers: { "Content-Type": "application/json" },
          body: JSON.stringify({
            action: "feedback",
            name: document.getElementById('contactName').value.trim(),
            contact: document.getElementById('contactInfo').value.trim(),
            message: document.getElementById('contactMessage').value.trim(),
            source: "landing_page"
          })
        });
      } catch (e) {}

      btn.innerText = "Отправлено";
      status.classList.remove('hidden');
      document.getElementById('contactForm').reset();
    }
  </script>
</body>
</html>
