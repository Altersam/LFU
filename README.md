# LFU — Лицей Финансового университета

Портал статических HTML-страниц Лицея Финансового университета: расписание, кабинеты, программа «МехИИ», поступление и методические материалы.

## Быстрый доступ

- [Открыть портал](index.html)
- [Расписание с кабинетами](lfu_2026-2027_shedule.html)
- [Карта кабинетов и свободных слотов](cabinets.html)
- [Расписание без кабинетов](shedule.html)

## Материалы

| Страница | Назначение |
|---|---|
| [`index.html`](index.html) | Главная страница и каталог материалов |
| [`lfu_2026-2027_shedule.html`](lfu_2026-2027_shedule.html) | Полное расписание 2026–2027 с классами, учителями, кабинетами и сводкой |
| [`cabinets.html`](cabinets.html) | Общее расписание кабинетов, свободные слоты и МТС Линк |
| [`shedule.html`](shedule.html) | Упрощённое расписание для учеников и родителей |
| [`MechAI.html`](MechAI.html) | Аналитика курсов программы «МехИИ» |
| [`MechAI_KTP.html`](MechAI_KTP.html) | Интегрированное КТП 10–11 класса и ИИ-трек |
| [`fa_priemka_2026.html`](fa_priemka_2026.html) | Гид поступающего в Финуниверситет в 2026 году |
| [`online_lfu.html`](online_lfu.html) | Руководство для преподавателей: Moodle, МТС Линк и ИИ |
| [`VarFin_instructions_jury.html`](VarFin_instructions_jury.html) | Инструкция жюри конкурса ВарФин 2026 |
| [`distant.html`](distant.html) | Исследование гибридного и дистанционного образования |

## Запуск

Все страницы являются самостоятельными HTML-файлами и не требуют сборки или установки зависимостей.

```bash
git clone https://github.com/Altersam/LFU.git
cd LFU
python -m http.server 8000
```

Откройте [http://localhost:8000](http://localhost:8000) или [index.html](index.html).

## GitHub Pages

После включения GitHub Pages главная страница будет доступна по адресу:

`https://altersam.github.io/LFU/`

Прямые ссылки:

- `https://altersam.github.io/LFU/index.html`
- `https://altersam.github.io/LFU/cabinets.html`

## Структура

```text
LFU/
├── index.html
├── lfu_2026-2027_shedule.html
├── cabinets.html
├── shedule.html
├── MechAI.html
├── MechAI_KTP.html
├── fa_priemka_2026.html
├── online_lfu.html
├── VarFin_instructions_jury.html
├── distant.html
└── README.md
```

## Технологии

- HTML5 и CSS3
- Нативный JavaScript
- Адаптивная вёрстка
- Chart.js через CDN в `fa_priemka_2026.html`

Материалы подготовлены для внутреннего использования Лицеем Финансового университета при Правительстве РФ.
