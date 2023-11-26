# Дипломный проект. «Модель прогнозирования прогнозирования количества аварийных событий по вине персонала»


## Оглавление
[0. Цель исследования](README.md#Цель-исследования) <br>
[1. Поставленные задачи](README.md#Обязательные-условия-для-проекта)<br>
[2. Этапы проекта](README.md#Этапы-проекта)<br>
[3. Информация о данных](README.md#Информация-о-данных)<br>
[4. Результаты исследования](README.md#Результаты-исследования)<br>

### 0. Цель исследования

Разработать модель, которая позволила бы прогнозировать количество аварийных событий по вине персонала на один год вперед.

:arrow_up:[к оглавлению](README.md#Оглавление)

### 1. Поставленные задачи

* Провести разведывательный анализ.  
* Анализ существующих решений для выбранной темы.
* Построить различные модели для прогнозирования количества аварийных событий.
* Выделить три модели для небольшого веб-сервис, на вход которому поступают данные о варианте модели, а сервис прогнозирует количество аварийных событий по вине персонала на один год вперед.

:arrow_up:[к оглавлению](README.md#Оглавление)

### 2. Этапы проекта

➔ 1. Знакомство с данными, первичная обработка
* Загрузка данных, которые предварительно обезличены

➔ 2. Моделирование и оценка моделей
* Разделение данных
* Обучаем различные модели и оцениваем качество
    * SARIMA
      ![image](https://github.com/dprohor/timeseries2/assets/152056985/2f2c6637-cf03-46d0-beac-ee8e86e3959a)

      ![image](https://github.com/dprohor/timeseries2/assets/152056985/3d400915-1f0a-43ec-a32e-2ac7fc9ef602)

    * Prophet
    * LSTM
    * GRU
    * TSfresh + CatBoost

* Выводы
![image](https://github.com/dprohor/timeseries2/assets/152056985/ccf9f31e-c43b-4720-9bcb-57e744fb5646)

:arrow_up:[к оглавлению](README.md#Оглавление)

### 3. Информация о данных

➔ 'datetime' — дата, первый день месяца;<br>

➔ **'count'** — количество аварийных событий по вине персонала.

:arrow_up:[к оглавлению](README.md#Оглавление)

### 4. Результаты исследования



:arrow_up:[к оглавлению](README.md#Оглавление)
