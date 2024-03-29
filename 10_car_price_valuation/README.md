# Оценка стоимости автомобиля

#### Тема проекта:
- Оценка рыночной стоимости автомобиля

#### Цель:
- Построить модель, предсказывающую рыночную стоимость автомобиля

#### Поставленные задачи:
- Изучить предоставленные данные;
- Обучить несколько моделей для определения стоимости;
- Для обучения использовать в том числе модели градиентного бустинга;
- Сравнить результаты значений RMSE и скорость обучения.

#### Краткий план работы:
- [Шаг 1. Подготовка данных](#Шаг-1.-Подготовка-данных)
  - [1.1. Открытие файла](#1.1.-Открытие-файла)
  - [1.2. Проверка и изучение данных](#1.2.-Проверка-и-изучение-данных)
  - [1.3. Подготовка данных для обучения](#1.3.-Подготовка-данных-для-обучения)
- [Шаг 2. Обучение и анализ моделей](#Шаг-2.-Обучение-и-анализ-моделей)
  - [2.1. Константная модель](#2.1.-Константная-модель)
  - [2.2. Случайный лес (RandomForestRegressor)](#2.2.-Случайный-лес-(RandomForestRegressor))
  - [2.3. Градиентный бустинг (CatBoostRegressor)](#2.3.-Градиентный-бустинг-(CatBoostRegressor))
  - [2.4. Градиентный бустинг (LGBMRegressor)](#2.4.-Градиентный-бустинг-(LGBMRegressor))
  
#### Вывод:
- Изучены и предобработаны предоставленные данные;
- Обучено и протестировано несколько моделей;
- Проведено сравнение результатов RMSE и скорости работы.

**Статус проекта**: проект завершён.  

**Используемые библиотеки**: *numpy*, *pandas*, *matplotlib*, *sklearn*, *catboost*, *lightgbm*

**Источник данных**: [курс Data Science от Яндекс.Практикум](https://praktikum.yandex.ru/profile/data-scientist/)