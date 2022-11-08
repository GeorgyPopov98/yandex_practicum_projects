# Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста.

## Данные

Для приоритезации гипотез были предоставлены следующие данные:

- Краткое описание гипотезы;
- Охват пользователей по 10-балльной шкале;
- Влияние на пользователей по 10-балльной шкале;
- Уверенность в гипотезе по 10-балльной шкале;
- Затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.

Оценка результатов А/В-тестирования производилась по следующим данным:

Данные о заказах клиента:

- Идентификатор заказа;
- Идентификатор пользователя, совершившего заказ;
- Дата, когда был совершён заказ;
- Выручка заказа;
- Группа A/B-теста, в которую попал заказ.

Данные о количестве пользователей в определенную дату в опредленной группе A/B-теста:

- Дата;
- Группа A/B-теста;
- Количество пользователей в указанную дату в указанной группе A/B-теста

## Задача

Приоритезировать гипотезы. Произвести оценку результатов A/B-тестирования различными методами.

## Используемые библиотеки
*pandas*, *Matplotlib*, *Math*, *SciPy*, *Seaborn*