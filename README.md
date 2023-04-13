# **Выполнения задач по семинарам "Основы языка Python для аналитиков"**
## __I. Задачи реализованы на Jupyter Notebook__
---
## __*1. Задачи по 1 семинару "Оформление ноутбука и закрепление функций и генераторов"*__
~~~
Задачи и их способы решения по Семинару 1 указаны в табл.№1
~~~
## __*Табл.№1 - Задачи по 1-му семинару*__
|__*№*__|__*Наименование*__|__*Условия задачи*__|__*Комментарии*__|__*Приложение*__|
|:-----:|:----------------:|:------------------:|:---------------:|:--------------:|
|*1*|*Условие 1*|*Оформляйте ноутбук, используя __Markdown__.*|__*Игнорироание атрибутов в теге"*"*__|[КОД](https://github.com/SergeyPochikaev/Python_Analyst/blob/main/HomeWork/Lesson1_LaptopDesign_unctions_and_Generators/Task1_LaptopDesign.ipynb)| 
|*2*|*Условие 2*|*На складе лежат разные фрукты в разном количестве. Нужно написать функцию, которая на вход принимает любое количество названий фруктов и их количество, а возвращает общее количество фруктов на складе*|apple = 23, orange = 15, lemon = 5|[КОД](https://github.com/SergeyPochikaev/Python_Analyst/blob/main/HomeWork/Lesson1_LaptopDesign_unctions_and_Generators/Task2_Function_kwargs.ipynb)|
|*3*|*Условие 3*|*Дан список с затратами на рекламу. Но в данных есть ошибки, некоторые затраты имеют отрицательную величину. Удалите такие значения из списка и посчитайте суммарные затраты.*|__*Пример:*__ [100, 125, 345, 655, 200] -> 1425|[КОД](https://github.com/SergeyPochikaev/Python_Analyst/blob/main/HomeWork/Lesson1_LaptopDesign_unctions_and_Generators/Task3_Function_kwargs.ipynb)|
|*4*|*Условие 4*|*Даны два списка. Дата покупки и Суммы покупок по датам. Найдите, какая выручка у компании в ноябр (Используйте list comprehensions) и выручку компании в зависимости от месяца с использованием аннотирование типов(Для этого напишите функцию, которая на вход принимает список с датами и список с выручкой, а на выходе словарь, где ключи - это месяцы, а значения - это выручка)*|{'09': 25647, '12': 45452, '10': 28645, '11': 25098}|[КОД](https://github.com/SergeyPochikaev/Python_Analyst/blob/main/HomeWork/Lesson1_LaptopDesign_unctions_and_Generators/Task4_Dictionary_of_Two_Lists.ipynb)|
---
__* Примечание:__
```html
<table bgcolor='green' border="5" bordercolor="red">
```
---
## __II. Задачи реализованы в Pandas__
---
## __*1. Задачи по 2 семинару "Анализ датасета с помощью Pandas"*__
~~~
Задачи и их способы решения по Семинару 1 указаны в табл.№2
~~~
## __*Табл.№2 - Задачи по 2-му семинару*__
|__*№*__|__*Наименование*__|__*Условия задачи*__|__*Приложение*__|
|:-----:|:----------------:|:------------------|:--------------:|
|__*1*__|__*Условие 1*__|*Скачать файл в уроке. Считать данные с помощью pandas. Вывести на экран первые 5 строк. Посмотреть на описание признаков и на их содержание*|[КОД](https://github.com/SergeyPochikaev/Python_Analyst/blob/main/HomeWork/Lesson2_LaptopDesign_unctions_and_Generators/DataAnalysis_in_Pandas.ipynb)| 
|__*2*__|__*Условие 2*__|*Проведите первичный анализ данных. Изучите типы данных. Найдите количество пропущенных ячеек в данных. Посчитайте основные статистики по всем признакам и поизучайте их. Пишите выводы*||
|__*3*__|__*Условие 3*__|Ответьте на несколько вопросов||
|*3.1*|*Условие 3.1*|*В каком диапазоне изменяются стоимости недвижимости?*||
|*3.2*|*Условие 3.2*|*Какую долю в среднем занимают жилая площадь от всей площади по всем домам?*||
|*3.3*|*Условие 3.3*|*Как много домов с разными этажами в данных?*||
|*3.4*|*Условие 3.4*|*Насколько хорошие состояния у домов в данных?*||
|*3.5*|*Условие 3.5*|*Найдите года, когда построили первый дом, когда построили последний дом в данных?*||
|__*4*__|__*Условие 4*__|Ответьте на несколько вопросов||
|*4.1*|*Условие 4.1*|*Сколько в среднем стоят дома, у которых 2 спальни?*||
|*4.2*|*Условие 4.2*|*Какая в среднем общая площадь домов, у которых стоимость больше 600 000?*||
|*4.3*|*Условие 4.3*|*Как много домов коснулся ремонт?*||
|*4.4*|*Условие 4.4*|*Насколько в среднем стоимость домов с оценкой grade домов выше 10 отличается от стоимости домов с оценкой grade меньше 4?*||
|__*5*__|__*Условие 5.1*__|Выберите дом клиенту||
|*5.1*|*Условие 5.1*|*Клиент хочет дом с видом на набережную, как минимум с тремя ванными и с подвалом. Сколько вариантов есть у клиента?*||
|*5.2*|*Условие 5.2*|*Клиент хочет дом либо с очень красивым видом из окна, либо с видом на набережную, в очень хорошем состоянии и год постройки не меньше 1980 года. В какой ценовом диапазоне будут дома?*||
|*5.3*|*Условие 5.3*|*Клиент хочет дом без подвала, с двумя этажами, стоимостью до 150000. Какая оценка по состоянию у таких домов в среднем?*||
---
## __*2. Задачи по 3 семинару "Изменение таблиц в Pandas"*__
~~~
Задачи и их способы решения по Семинару 1 указаны в табл.№2
~~~
## __*Табл.№2 - Задачи по 2-му семинару*__
|__*№*__|__*Наименование*__|__*Условия задачи*__|__*Приложение*__|
|:-----:|:----------------:|:------------------|:--------------:|
|__*1*__|__*Задача 1*__|*Скачать данные - недвижимость (в закрепе к уроку). Считать данные с помощью pandas Вывести на экран первые 5 строк*|[КОД](https://github.com/SergeyPochikaev/Python_Analyst/blob/main/HomeWork/Lesson3_ChangingTables_in_Pandas/Task1_ChangingTables_in_Pandas.ipynb)|
|*1.1*|*Условие 1.1*|*Создать новый признак price_per_sq_lot, который будет содержать среднюю стоимость за один кв. метр общей площади*||
|*1.2*|*Условие 1.2*|*Создать новый признак delta_renovated, который будет содержать разницу в годах между годом реновацией дома и годом постройки дома (Если реновации дома не было, то в новом признаке поставьте 0)*||
|*1.3*|*Условие 1.3*|*Создайте признаки года продажи, месяца продажи*||
|*1.4*|*Условие 1.4*|*Удалите признаки date, zipcode, lat, long*||
|__*2*__|__*Задача 2*__|*Создайте датафрейм с лиентами: clients = pd.DataFrame({'client_id':[...],'house_id': [...]*})||
|*2.1*|*Условие 2.1*|*Присоедините к таблице clients данные по домам через метод join*||
|*2.2*|*Условие 2.2*|*2.2 Присоедините к таблице clients данные по домам через метод merge (Это нужно, чтобы понимать, какие дома покупались клиентами house_id - это индексы датафрейма с домами)*||
|__*3*__|__*Задача 3*__|*Составьте несколько сводных таблиц*||
|*3.1*|*Условие 3.1*|*Найдите среднюю стоимость домов в зависимости от количества спален (Отсортируйте от меньшей стоимости к большей)*||
|*3.2*|*Условие 3.2*|*Найдите минимальную, среднюю и максимальную стоимости домов в зависимости от состояния дома*||
|*3.3*|*Условие 3.3*|*Постройте таблицу с подсчетом количества домов в данных в зависимости от вида на набережную и оценкой вида*||
|*3.4*|*Условие 3.4*|*Каких домов в зависимости от этажности и количества спален больше?*||
|*3.5*|*Условие 3.5*|*Постройте таблицу с подсчетом медианной стоимости домов в данных в зависимости от состояния дома и оценки дома*||
---