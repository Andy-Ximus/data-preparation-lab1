# Data Preparation Lab 1
Лабораторная работа №1. Подготовка и разметка неструктурированных данных.

## Структура репозитория
- `data/` — Данные:
  - `raw/` — Исходные данные:
  - `text/` — Текстовые данные:
    - `train/` — Обучающие данные:
      - `pos/` — Положительные отзывы.
      - `neg/` — Отрицательные отзывы.
      - `unsup/` — Неразмеченные отзывы.
      - `labeledBow.feat` — Файл с предварительно обработанными обучающими данными.
      - `unsupBow.feat` — Файл с необработанными данными.
      - `urls_pos*` — Файлы с ссылками на оригинальные положительные отзывы.
      - `urls_neg*` — Файлы с ссылками на оригинальные отрицательные отзывы.
      - `urls_unsup*` — Файлы с ссылками на оригинальные необработанные отзывы.
    - `test/` — Тестовые данные:
      - `pos/` — Положительные отзывы для теста.
      - `neg/` — Отрицательные отзывы для теста.-
      - `unsupBow.feat` — Файл с необработанными данными.
      - `urls_pos*` — Файлы с ссылками на оригинальные положительные отзывы.
      - `urls_neg*` — Файлы с ссылками на оригинальные отрицательные отзывы.
  - `processed/` — обработанные данные.
  - `examples/` — примеры данных.
- `code/` — Код:
  - `preprocessing/` — скрипты для обработки данных.
  - `analysis/` — скрипты для анализа.
  - `models/` — скрипты для работы с моделями.
- `results/` — Результаты:
  - `figures/` — графики.
  - `models/` — обученные модели.
  - `output/` — текстовые результаты.
- `docs/` — Документация.
