# Лабораторные работы по статистическому анализу

Этот репозиторий содержит серию лабораторных работ, выполненных в рамках курса по статистическому анализу. Работы охватывают как базовую обработку данных с использованием `pandas`, так и продвинутые методы: дисперсионный анализ, множественную регрессию, A/B-тесты и проверку статистических гипотез (включая непараметрические критерии).  
Цель — развитие практических навыков в применении статистики для анализа данных и принятия решений на её основе.

## Содержание

- [Лабораторная работа №1](#лабораторная-работа-1)
- [Лабораторная работа №2](#лабораторная-работа-2)
- [Лабораторная работа №3](#лабораторная-работа-3)
- [Лабораторная работа №4](#лабораторная-работа-4)
- [Лабораторная работа №5](#лабораторная-работа-5)
- [Лабораторная работа №6](#лабораторная-работа-6)
- [Лабораторная работа №7](#лабораторная-работа-7)

---

## Лабораторная работа 1

**Тема**: Основы работы с табличными данными в `pandas`.

**Описание**:  
Изучение базовых операций обработки и анализа данных: чтение CSV-файлов, фильтрация, группировка, сводные таблицы, визуализация распределений. Построение первых статистических наблюдений на основе датафрейма.

---

## Лабораторная работа 2

**Тема**: Исследовательский анализ данных (EDA).

**Описание**:  
Углублённое знакомство с исследовательским анализом: выявление пропусков, выбросов, корреляционный анализ, построение диаграмм рассеяния и boxplot’ов. Подготовка данных к дальнейшему статистическому анализу.

---

## Лабораторная работа 3

**Тема**: T-критерий Стьюдента.

**Описание**:  
Сравнение средних значений числовой переменной между двумя группами. Анализ данных `Iris`:  
- Применение t-test для оценки статистических различий между двумя подвыборками.  
- Проверка гипотез о равенстве средних.

**Ключевые навыки**:  
`ttest_ind`, проверка нормальности, визуализация распределений.

---

## Лабораторная работа 4

**Тема**: Дисперсионный анализ (ANOVA).

**Описание**:  
Изучение влияния категориальных факторов на формирование цены.  
- Однофакторный дисперсионный анализ (ANOVA).  
- Исследование взаимодействий между факторами (two-way ANOVA).  
- Интерпретация значений F-статистики и p-value.

**Ключевые навыки**:  
`statsmodels`, `ols`, `anova_lm`, визуализация влияния факторов.

---

## Лабораторная работа 5

**Тема**: A/B-тестирование.

**Описание**:  
Проведение эксперимента для оценки эффективности новой системы рекомендаций в онлайн-сервисе.  
- Проверка гипотез о различии в вовлечённости и среднем чеке.  
- Применение t-теста и анализ результатов.  
- Обоснование вывода о внедрении новой системы на всех пользователей.

**Ключевые навыки**:  
A/B тесты, экспериментальный дизайн, интерпретация p-value и доверительных интервалов.

---

## Лабораторная работа 6

**Тема**: Множественная линейная регрессия.

**Описание**:  
Построение и анализ модели множественной регрессии:
- Проверка общей статистической значимости модели (F-критерий).  
- Проверка значимости отдельных коэффициентов (t-критерий).  
- Вычисление и интерпретация коэффициента детерминации (R²).  
- Анализ изменения R² при добавлении взаимодействий между признаками.

**Ключевые навыки**:  
`LinearRegression`, `ols`, F-test, t-test, визуализация остатков.

---

## Лабораторная работа 7

**Тема**: Непараметрические критерии проверки гипотез.

**Описание**:  
Применение непараметрических методов для анализа данных без предположений о нормальности. Использованы критерии:
- Розенбаума  
- Манна — Уитни  
- Краскела — Уоллеса  
- Знаков  
- Уилкоксона  
- Фридмана  
- Пейджа  
- Пирсона (χ²)

**Ключевые навыки**:  
Непараметрические методы анализа, ранговые критерии, работа с зависимыми и независимыми выборками.

---

## Технологии и библиотеки

- `pandas`, `numpy`
- `scipy.stats`
- `statsmodels`
- `matplotlib`, `seaborn`
- Jupyter Notebook / Python

---

## Применимость к ML

Данные лабораторные работы формируют фундаментальную базу для:
- Проведения статистических проверок гипотез в машинном обучении.
- Оценки результатов A/B-тестов.
- Построения интерпретируемых моделей (линейная регрессия).
- Принятия решений на основе данных.

