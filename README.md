# LFU — Лицей Финансового университета

Портал статических HTML-страниц Лицея Финансового университета: расписание, кабинеты, программа «МехИИ», поступление и методические материалы.

## Быстрый доступ

- [Открыть портал](index.html)
- [Каталог ИИ](guides/AI_guide.html)
- [Практический гайд для преподавателя](guides/ai_teacher_guide.html)
- [Расписание с кабинетами](schedule/lfu_2026-2027_shedule.html)
- [Карта кабинетов и свободных слотов](schedule/cabinets.html)
- [Расписание без кабинетов](schedule/shedule.html)

## Материалы

| Страница | Назначение |
|---|---|
| [`index.html`](index.html) | Главная страница и каталог материалов |
| [`guides/AI_guide.html`](guides/AI_guide.html) | Каталог 114 ИИ-сервисов с фильтрами и локальными сценариями |
| [`guides/ai_teacher_guide.html`](guides/ai_teacher_guide.html) | Практический гайд: промпт, урок, конспект, тест и LMS |
| [`guides/guide.html`](guides/guide.html) | Инструкция Лицея и FAQ для педагогов |
| [`schedule/lfu_2026-2027_shedule.html`](schedule/lfu_2026-2027_shedule.html) | Полное расписание 2026–2027 |
| [`schedule/cabinets.html`](schedule/cabinets.html) | Кабинеты и свободные слоты |
| [`schedule/shedule.html`](schedule/shedule.html) | Упрощённое расписание |
| [`projects/MechAI.html`](projects/MechAI.html) | Аналитика курсов программы «МехИИ» |
| [`projects/MechAI_KTP.html`](projects/MechAI_KTP.html) | Интегрированное КТП и ИИ-трек |
| [`projects/online_lfu.html`](projects/online_lfu.html) | Moodle, МТС Линк и ИИ |
| [`projects/distant.html`](projects/distant.html) | Исследование гибридного образования |
| [`admission/fa_priemka_2026.html`](admission/fa_priemka_2026.html) | Гид поступающего в 2026 году |
| [`reports/summary_26_27.html`](reports/summary_26_27.html) | Дайджест развития Лицея 2026/27 |
| [`reports/VarFin_instructions_jury.html`](reports/VarFin_instructions_jury.html) | Инструкция жюри ВарФин 2026 |

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
- `https://altersam.github.io/LFU/schedule/cabinets.html`

## Структура

```text
LFU/
├── index.html
├── guides/
├── schedule/
├── projects/
├── admission/
├── reports/
└── README.md
```

## Технологии

- HTML5 и CSS3
- Нативный JavaScript
- Адаптивная вёрстка
- Chart.js через CDN в `fa_priemka_2026.html`

Материалы подготовлены для внутреннего использования Лицеем Финансового университета при Правительстве РФ.
