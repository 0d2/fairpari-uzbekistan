FairPari Guide UZ — папка для деплоя
=====================================

Содержимое:
- ru-uz/index.html     — русская версия главной
- ru-uz/privacy.html   — политика конфиденциальности (RU)
- uz-uz/index.html     — узбекская версия главной
- uz-uz/privacy.html   — политика конфиденциальности (UZ)
- logo.svg             — логотип бренда
- screens/             — скриншоты (home.png, home-mob.png, bonuses.png и др.)
- footer/              — ecogra.svg, dmca.webp, responsible.webp (ссылки на ecogra.org, dmca.com, responsiblegambling.org)
- styles-privacy.css   — стили для страниц политики
- sitemap.xml          — карта сайта (замените YOUR_DOMAIN на ваш домен)
- robots.txt           — правила для краулеров (замените YOUR_DOMAIN в Sitemap)

Перед публикацией:
1. Партнёрская ссылка: в ru-uz/index.html и uz-uz/index.html в <head> найдите
   window.REF_LINK = 'https://ref.link'
   и замените на вашу ссылку. Все CTA и ссылки на зеркало/бонус подставятся автоматически.

2. Домен: в sitemap.xml замените YOUR_DOMAIN на полный URL сайта (напр. https://yoursite.com).
   В robots.txt в строке Sitemap: замените YOUR_DOMAIN на тот же URL.

Структура URL после деплоя:
- Русская версия: .../ru-uz/  (или .../ru-uz/index.html)
- Узбекская версия: .../uz-uz/
Переключение языка — в шапке (ссылки между ru-uz и uz-uz).

Футер: логотипы eCOGRA, DMCA, Responsible Gambling ведут на официальные сайты (не на REF_LINK).

Дата обновления контента в футере и сводной таблице: март 2026.
