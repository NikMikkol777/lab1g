# Лабораторная работа №1 — Первичное исследование и оценка качества данных

## О проекте
Первичный аудит датасета **Bank Marketing** (UCI): паспортизация, проверка пропусков,
дубликатов, выбросов, «грязных» категорий и разведочный анализ.

**Студент:** Михеев Никита Валерьевич  
**Группа:** 302

## Структура
- `data/` — датасет `bank-additional-full.csv`
- `notebooks/01_data_understanding.ipynb` — основной ноутбук
- `report/quality_report.md` — текстовый отчёт

## Как запустить

```bash
# 1. Клонировать репозиторий
git clone <repo_url>
cd lab1

# 2. Установить зависимости
pip install pandas numpy matplotlib seaborn scipy jupyter

# 3. Запустить ноутбук
jupyter notebook notebooks/01_data_understanding.ipynb