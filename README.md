# Тема итоговой работы: «Модель прогнозирования количества аварийных событий по вине персонала»


## Оглавление
[0. Цель проекта](README.md#Цель-исследования) <br>
[1. Поставленные задачи](README.md#Обязательные-условия-для-проекта)<br>
[2. Этапы проекта](README.md#Этапы-проекта)<br>
[3. Информация о данных](README.md#Информация-о-данных)<br>
[4. Результаты исследования](README.md#Результаты-исследования)<br>

### 0. Цель проекта

Разработка модели, которая позволила бы прогнозировать количество аварийных событий по вине персонала на 12 месяцев вперед.

:arrow_up:[к оглавлению](README.md#Оглавление)

### 1. Поставленные задачи

* Провести разведывательный анализ;  
* Анализ существующих решений для выбранной темы;
* Построить различные модели прогнозирования количества аварийных событий;
* На основе модели разработать небольшого веб-сервис, который прогнозирует количество аварийных событий по вине персонала на 12 месяцев вперед. Фреймворк для разработки веб-приложений должен использоваться Streamlit;
* Развернуть веб-сервис на площадке huggingface;
* Исходный код выложит на репозиторий github.

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
      ![image](https://github.com/dprohor/timeseries2/assets/152056985/0fb5718b-e8b1-4ffc-9325-a9487f8bff87)
      
      ![image](https://github.com/dprohor/timeseries2/assets/152056985/58ec9f57-835b-4e99-b492-af9dc01afe09)

    * LSTM
      ![image](https://github.com/dprohor/timeseries2/assets/152056985/33325dd2-804e-490b-a3ed-5623434e730c)

    * GRU
      ![image](https://github.com/dprohor/timeseries2/assets/152056985/a8d99e19-2b1c-40a8-ac3c-1b647b71107c)

    * TSfresh + CatBoost

* Выводы
![image](https://github.com/dprohor/timeseries2/assets/152056985/ccf9f31e-c43b-4720-9bcb-57e744fb5646)

:arrow_up:[к оглавлению](README.md#Оглавление)

### 3. Информация о данных

➔ 'datetime' — дата, первый день месяца;<br>

➔ **'count'** — количество аварийных событий по вине персонала.

:arrow_up:[к оглавлению](README.md#Оглавление)

### 4. Результаты исследования

Для прогнозирования будущих событий были использованы модели SARIMA, Prophet и tsfresh. Прогнозы количества аварийных событий по вине персонала на один год вперед следующие: 

![image](https://github.com/dprohor/timeseries2/assets/152056985/6b72ae39-aef5-4176-ad8e-8be21e286806)

Для критерия оценки использовались такие параметры MAPE, RMSE, MSE. 

По результатам, все модели хорошие.  Это означает, что при необходимости они могут быть донастроены и использованы в соответствии с конкретными целями и задачами

:arrow_up:[к оглавлению](README.md#Оглавление)
