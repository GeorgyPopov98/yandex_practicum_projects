# Анализ проведения А/В тестирования.

## Данные

Оценка результатов А/В-тестирования производилась по следующим данным:

Данные о маркетинговых кампаниях:

- Название маркетингового события;
- Регионы, в которых будет проводиться рекламная кампания;
- Дата начала кампании;
- Дата завершения кампании.

Данные о событиях клиента:

- Идентификатор пользователя;
- Дата и время покупки;
- Тип события;
- Дополнительные данные о событии.

Данные о пользователях в опредленной группе A/B-теста:

- Идентификатор пользователя;
- Название теста;
- Группа пользователя.

Данные о пользователях, участвовавших в А/В-тесте:

- Идентификатор пользователя;
- Дата регистрации;
- Регион пользователя;
- Устройство, с которого происходила регистрация.

## Задачи

Оценка корректности проведения теста.
Анализ результатов теста.

## Вывод

Сущестует проблема большого количества неактивных пользователей, пересечении пользователей между двумя разными тестами, а также неполном наборе данных о покупках.
 
Конверсия на всех этапах воронки продаж лучше у группы А.

Значимые различия в конверсии пользователей есть только между событиями product_page.

## Статус проекта

Завершен.

## Используемые библиотеки
*pandas*, *Matplotlib*, *Math*, *SciPy*
